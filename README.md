# Spring Boot REST API - CRUD de Usuários
Este projeto é uma implementação básica de uma API RESTful com operações CRUD (Create, Read, Update, Delete) de usuários usando o Spring Boot. A API permite adicionar, atualizar, listar, buscar e remover usuários do banco de dados.

O projeto é dividido em três classes Java: Usuario, UsuarioRepository e UsuarioController. A classe Usuario representa o modelo de dados de um usuário, enquanto UsuarioRepository é a interface que define as operações básicas no banco de dados, como salvar, atualizar, listar e excluir. A classe UsuarioController é responsável por manipular as requisições HTTP e invocar as operações apropriadas no repositório.

## Tecnologias Utilizadas
### Java 8
### Spring Boot 2.5.0
### Spring Data JPA
### H2 Database
### Swagger

## Endpoints Disponíveis
A API possui os seguintes endpoints:

### POST /usuarios - adiciona um novo usuário ao banco de dados
### PUT /usuarios - atualiza os dados de um usuário já existente no banco de dados
### GET /usuarios - lista todos os usuários cadastrados no banco de dados
### GET /usuario/{id} - busca um usuário pelo ID
### DELETE /usuarios/{id} - remove um usuário do banco de dados pelo ID

## Documentação da API
A documentação da API foi gerada automaticamente pelo Swagger e está disponível em http://localhost:8080/swagger-ui.html. A partir dessa interface, é possível visualizar e testar todos os endpoints da API.

## Considerações Finais
Este projeto foi criado como uma demonstração básica de como construir uma API RESTful usando o Spring Boot. Ele pode ser utilizado como ponto de partida para implementações mais avançadas ou como exemplo de boas práticas de programação.
