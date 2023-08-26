# 🛍️ MLScrapMaster

O **MLScrapMaster** é uma ferramenta poderosa desenvolvida em Python, projetada para acessar o Mercado Livre, pesquisar produtos específicos e extrair informações essenciais como nome e preço. Uma vez coletados, os dados são estruturados em um arquivo Excel e enviados diretamente para o e-mail do usuário, proporcionando uma forma conveniente de monitorar os preços dos produtos no Mercado Livre.

## 🚀 Características Principais

- **Pesquisa Avançada**: Pesquise produtos específicos e obtenha informações detalhadas.
- **Exportação para Excel**: Todos os dados são meticulosamente estruturados em uma planilha Excel.
- **Notificação por E-mail**: Receba sua planilha diretamente no seu e-mail de preferência.

## 📚 Bibliotecas Utilizadas

- **requests**: Realiza solicitações HTTP para acessar sites.
- **BeautifulSoup (bs4)**: Analisa o HTML das páginas, facilitando a extração de informações.
- **openpyxl**: Manipulação avançada de arquivos Excel.
- **getpass**: Garante a segurança ao lidar com senhas.
- **EmailMessage (email.message)**: Criação e manipulação de mensagens de e-mail.
- **re**: Trabalha com expressões regulares, proporcionando flexibilidade na busca de informações.
- **yagmail**: Simplifica o processo de envio de e-mails.

## ⚙️ Como Funciona

1. **E-mail do Usuário**: No início, o script solicita que o usuário forneça um endereço de e-mail. Este será usado para enviar o arquivo Excel.
2. **Pesquisa de Produto**: O usuário informa o produto que deseja pesquisar.
3. **Extração de Dados**: O script navega pelo Mercado Livre, pesquisando o produto e coletando detalhes como nome e preço.
4. **Criação do Excel**: As informações são organizadas e salvas em um arquivo Excel.
5. **Envio de E-mail**: O arquivo Excel é enviado para o e-mail fornecido pelo usuário.

## 💻 Execução

Para executar o MLScrapMaster, siga os passos abaixo:

```python
scrappy = Scrappy()
scrappy.start()

```
## 📦 Instalação

Instale todas as bibliotecas necessárias com:

$ pip install -r requirements.txt
Nota: re, getpass e email.message já estão incluídas na biblioteca padrão do Python.

## ⚠️ Aviso

Este é um projeto de exemplo. Ao utilizar, assegure-se de não violar os Termos de Serviço do Mercado Livre.
