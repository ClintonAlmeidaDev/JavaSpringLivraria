# java-back-end-livro

Este repositório contém o código do livro Java Back End.

## Serviços

Esse é um projeto feito com base no livro Java Back End da Casa do codigo.

Aplicando um pouco dos conceito do mundo de Java Spring

A aplicação é composta de três microserviços, a user-api, a product-api e a shopping-api.

A user-api possui os serviços para gerenciar os usuários da aplicação.

A product-api possui os serviços para gerenciar os produtos disponíveis para compras.

A shopping-api os serviços para que usuários realizem compras.


## Postman

o arquivo `livro-back-end-java.postman_collection.json` é uma collection do Postman que possui as chamadas para os serviços da aplicação. A collection está configurada para chamar os serviços já no Kubernetes. Para chamar na execução local, basta trocar o shopping.com para localhost:808x.

## Execução

A maneira mais simples de executar a aplicação é utilizando o docker-compose, para isto, basta executar o comando `docker-compose up` depois que a imagem docker dos microserviços forem criadas.

