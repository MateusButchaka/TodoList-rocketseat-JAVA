# TodoList-rocketseat-JAVA

# Desenvolvimento de um Aplicativo Todolist em Java com Spring Boot

Recentemente, completei um curso intensivo de uma semana na 
Rocketseat, onde aprendi a desenvolver um aplicativo de 
gerenciamento de tarefas (todolist) usando Java e o poderoso 
framework Spring Boot. O projeto resultante inclui funcionalidades 
como autenticação de usuário, CRUD de tarefas e até mesmo a criação 
de uma imagem Docker para fácil implantação.


# • Pacotes Error e Filter: 
Criei pacotes para lidar com exceções (erros) 
e para aplicar filtros nas solicitações. O ExceptionHandlerController 
trata exceções específicas, enquanto o FilterTashAuth autentica usuários 
com base em credenciais no cabeçalho de autorização.

# • Pacote Task: 
Neste pacote, defini o modelo de tarefa (TaskModel) com campos como descrição, 
título e datas. A interface ITaskRepository permite a manipulação dos dados no 
banco de dados, e o TaskController expõe endpoints para criar, listar e atualizar 
tarefas.

# • Pacote User
Aqui, represento o modelo de usuário (UserModel) com informações como nome de 
usuário e senha. O IUserRepository gerencia as operações relacionadas a usuários, 
e o UserController lida com a criação de novos usuários.
Classe Principal TodolistApplication: É a classe de ponto de entrada do aplicativo 
Spring Boot. O método main inicia o aplicativo.

# • Arquivo pom.xml:
O arquivo de configuração do Maven com as dependências do projeto, versão do 
Java e outras configurações.

# • Dockerfile: 
Essa parte é emocionante. O Dockerfile permite empacotar nosso aplicativo 
em um contêiner Docker. Começa com uma imagem base do Ubuntu, instala o Java 17, 
copia o código-fonte do projeto para o contêiner, compila com o Maven e define o 
ponto de entrada para executar o aplicativo Spring Boot.


# Este projeto me proporcionou a oportunidade de explorar o desenvolvimento Java com Spring Boot e criar um aplicativo de gerenciamento de tarefas funcional. A experiência incluiu o uso de pacotes e classes para estruturar o projeto, gerenciamento de exceções, CRUD de tarefas, e até mesmo a preparação para implantação em contêineres Docker.

