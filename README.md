# Project-Data-base-Phyton

## Esse projeto tem como intuito aprender a ligar um codigo phyton a um banco de dados relacional de forma simples.

## Para este projeto utilizei as seguintes bibiotecas:

•SQLite-Utilizei essa biblioteca por ser a mais simples e rápida de se trabalhar para um projeto pequeno,ela permite criar, manipular e gerenciar bancos de dados SQLite diretamente em aplicações Python,sem precisar criar um servidor separado

•Pandas-Utilizei essa biblioteca para melhor vizualização das tabelas,ela oferece diversas ferramentas de manipulação de dados e ferramentas para trabalhar com tabelas

## Sobre os campos utilizados:

![image](https://github.com/user-attachments/assets/9061b2d6-9534-48c3-9663-78678f125433)

### A imagem acima mostra o codigo de criação da tabela principal do codigo,uma tabela simples de usuarios com os seguintes atributos:

•id-A chave primária da tabela,do tipo inteiro e que é preenchida automaticamente

•nome-Atributo do tipo string,que não pode estar vazio

•email-Atributo do tipo string,que não pode estar vazio e não aceita duplicados

•idade-Atributo do tipo inteiro que não pode estar vazio

![image](https://github.com/user-attachments/assets/fe616f30-a253-4db9-b774-32b35505472c)

### Esse campo realiza a criação de dois usuários genéricos para testar o banco de dados e dos comandos utilizados posteriormente no código.

![image](https://github.com/user-attachments/assets/5e6ebb15-6633-4502-a854-df48db26da44)

### Esse campo realiza a criação de uma das funções do código,que,quando chamada,adiciona um usuário ao banco de dados passando como parâmetro os dados informados pelo usuario.Ao final,a operação é confirmada para evitar erros.

![image](https://github.com/user-attachments/assets/17ce878c-c2cb-445e-a90b-c76e60322dd6)

### Esse campo realiza a atualização dos dados de um usuário que possui o id correspondente ao valor digitado pelo usuário. Caso o id não exista no banco de dados, o código exibe uma mensagem de erro e cancela a operaçãoo.

![image](https://github.com/user-attachments/assets/671a6395-7e0a-476c-8641-a69253ec1b85)

### Campo que realiza a exclusão dos dados de um usuário do banco de dados com base no id informado. Caso o id não exista, o código exibe uma mensagem de erro e cancela a operação.

![image](https://github.com/user-attachments/assets/a1a3cba8-8f30-4e2c-98e2-50a595cbc176)

### Os três campos acima tem as seguintes funções respectivamente:

1-Ler e listar o banco de dados utilizando uma função da biblioteca Pandas,exibindo os dados de forma dinâmica e interativa para o usuário

2-Pesquisar um usuário com base no id digitado pelo usuário. Essa função é utilizada para encontrar um registro específico no banco de dados e exibi-lo de forma formatada e interativa, usando a biblioteca Panda

3-Pesquisar um usuário com base no nome digitado pelo usuário. Essa função busca um registro específico no banco de dados e o exibe de maneira organizada, também utilizando a biblioteca Pandas

## Agora,vou demonstrar o código em execução,com todas as suas funcionalidades:

### Mostrando ao usuário todos os dados cadastrados no banco de dados:

![image](https://github.com/user-attachments/assets/7d7bc6f3-abce-4bf0-99ff-dccafedcd36b)

### Mostrando ao usuário os dados vinculados ao id que foi pesquisado:

![image](https://github.com/user-attachments/assets/9b44cc36-21ca-4c96-8362-08e55a9123dd)

### Mostrando ao usuário os dados vinculados ao nome que foi pesquisado:

![image](https://github.com/user-attachments/assets/d7e7a44e-e7c8-416a-8178-06dc1c6b0a12)

### Adicionando um usuário ao banco de dados e confirmando a operação:

![image](https://github.com/user-attachments/assets/c78f93f9-6db7-4b29-a2a9-5545f46a82dc)

![image](https://github.com/user-attachments/assets/648d4a38-eb6f-456c-a609-a8f07b4daac6)

### Atualizando o email do usuário com o id 3 e confirmando a operação:

![image](https://github.com/user-attachments/assets/fc38759a-0910-40b2-8105-ceb246aebaf7)

![image](https://github.com/user-attachments/assets/7f5b2d9d-2fc7-4584-a63b-75126bdb1ae5)

### Deletando o usuário com id 3 do banco de dados e confirmando a exclusão:

![image](https://github.com/user-attachments/assets/15d7c15a-da19-4fc3-a0bb-f92ff3628d41)

![image](https://github.com/user-attachments/assets/85013689-e670-44ac-8c38-e429bb6af931)
