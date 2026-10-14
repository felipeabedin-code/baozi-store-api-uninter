# Baozi Store — API REST

## 1. Descrição do projeto

A Baozi Store é uma loja fictícia especializada na venda de pãozinho chinês. Este projeto consiste no desenvolvimento de uma API REST para gerenciar clientes, produtos e pedidos, como parte da atividade prática da disciplina de Desenvolvimento Web Back End, do curso de Análise e Desenvolvimento de Sistemas da UNINTER.

A aplicação foi desenvolvida utilizando Java e Spring Boot, com persistência de dados por meio do Spring Data JPA e do banco de dados relacional H2.

## 2. Tecnologias utilizadas

- Java
- Spring Boot
- Spring Data JPA
- H2 Database
- Maven
- Postman

## 3. Funcionalidades implementadas

A API permite realizar operações de cadastro, consulta e exclusão de registros, organizadas em três entidades principais.

### Clientes

- Cadastrar clientes.
- Listar todos os clientes.
- Consultar um cliente específico pelo ID.
- Excluir um cliente pelo ID.

### Produtos

- Cadastrar produtos.
- Listar todos os produtos.
- Consultar um produto específico pelo ID.
- Excluir um produto pelo ID.

### Pedidos

- Registrar pedidos.
- Listar todos os pedidos.
- Consultar um pedido específico pelo ID.
- Excluir um pedido pelo ID.

Cada pedido relaciona um cliente a um produto e registra a quantidade solicitada.

## 4. Endpoints da API

| Método HTTP | Endpoint | Descrição |
|---|---|---|
| POST | /clientes | Cadastrar um cliente |
| GET | /clientes | Listar todos os clientes |
| GET | /clientes/{id} | Consultar um cliente pelo ID |
| DELETE | /clientes/{id} | Excluir um cliente |
| POST | /produtos | Cadastrar um produto |
| GET | /produtos | Listar todos os produtos |
| GET | /produtos/{id} | Consultar um produto pelo ID |
| DELETE | /produtos/{id} | Excluir um produto |
| POST | /pedidos | Registrar um pedido |
| GET | /pedidos | Listar todos os pedidos |
| GET | /pedidos/{id} | Consultar um pedido pelo ID |
| DELETE | /pedidos/{id} | Excluir um pedido |

## 5. Banco de dados

A aplicação utiliza o H2 Database, um banco de dados relacional configurado por meio do arquivo `application.properties`.

O Spring Data JPA é utilizado para facilitar a persistência e o gerenciamento dos dados da aplicação.

## 6. Execução do projeto

O projeto utiliza Java, Spring Boot e Maven. Os arquivos do Maven Wrapper estão incluídos no repositório para auxiliar na execução da aplicação.

A aplicação está configurada para utilizar a porta 8081.

## 7. Testes da API

Os endpoints da aplicação foram testados utilizando o Postman, permitindo verificar as operações de cadastro, consulta geral, consulta por ID e exclusão de clientes, produtos e pedidos.

## 8. Finalidade acadêmica

O projeto foi desenvolvido para fins acadêmicos, com o objetivo de aplicar os conceitos de desenvolvimento Back End, construção de APIs REST, utilização de métodos HTTP, persistência de dados e organização de aplicações Java com Spring Boot.
