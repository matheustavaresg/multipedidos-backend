# Desafio Técnico - Multipedidos

Objetivo: Avaliar suas habilidades de desenvolvimento através da criação de um CRUD (Create, Read, Update, Delete) com um frontend interagindo com um Lambda que armazena dados em um banco DynamoDB.

## Instruções Técnicas

## Backend
- Toda configuração e desenvolvimento foi realizado na AWS sob a conta 248278816999 - Matheus Tavares

- DynamoDB
- Foi criada uma tabela chamada multipedidos-items para armazenar os dados desejados.

- Lambda
- Foi criada uma função Lambda em NodeJS multipedidos-crud-item com interação com o DynamoDB para realizar as operações de Cadastro, Atualização, Listagem e Exclusão.

- API Gateway
- Foi criada a API multipedidos-crud-items com as devidas configuração e integração com a função Lambda citada acima.

- A API pode ser acessada pelo endereço: https://n0pi1338ec.execute-api.us-east-1.amazonaws.com

## Instruções de utilização:
- Disponível na raíz do projeto o arquivo de Collection do Postman Multipedidos.postman_collection.json
