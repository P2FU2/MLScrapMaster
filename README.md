MLScrapMaster
O MLScrapMaster é um script de Python que acessa o site do Mercado Livre, pesquisa um produto específico, extrai informações de preço e nome dos produtos e salva essas informações em um arquivo Excel. Após a criação do arquivo, o script envia esse arquivo por e-mail para o usuário.

Bibliotecas Utilizadas
requests: para realizar solicitações HTTP.
BeautifulSoup (bs4): para analisar o HTML das páginas.
openpyxl: para criar e manipular arquivos Excel.
getpass: para lidar com senhas.
email.message (EmailMessage): para manipular mensagens de e-mail.
re: para trabalhar com expressões regulares.
yagmail: para enviar e-mails.
Como Funciona
O script começa solicitando ao usuário que informe um endereço de e-mail. Este e-mail será utilizado para enviar o arquivo Excel no final do processo.

Em seguida, o script solicita ao usuário que informe o produto que deseja pesquisar.

O script acessa o Mercado Livre e realiza uma busca pelo produto. Ele percorre várias páginas de resultados e extrai o nome e o preço dos produtos.

As informações extraídas são salvas em um arquivo Excel.

Finalmente, o script envia o arquivo Excel criado para o endereço de e-mail informado pelo usuário.

Execução
Para executar o script, basta inicializar um objeto da classe Scrappy e chamar o método start.

python
Copy code
scrappy = Scrappy()
scrappy.start()
Este script é uma ferramenta útil para pessoas que querem acompanhar os preços dos produtos no Mercado Livre e preferem receber essas informações diretamente em seu e-mail, em um arquivo Excel de fácil leitura.

Para facilitar sua vida:
O comando abaixo instalará as seguintes bibliotecas: re, getpass, e email.message são parte da biblioteca padrão do Python, então você não precisa instalá-las separadamente.
$ pip install -r requirements.txt


Por favor, observe que este é apenas um projeto de exemplo e não deve ser utilizado para propósitos que violem os Termos de Serviço do Mercado Livre.


