# Tech challenge FIAP 🎓

1. [Introdução](#Introdução)
2. [Microsserviços](#Microsserviços)
3. [Execução](#Execução)
4. [Testes](#Testes)

## Introdução

Este projeto foi desenvolvido como parte do desafio técnico do curso de Arquitetura em Java da FIAP. O repositório
contém seis microsserviços responsáveis por gerenciar funcionalidades contidas em um fluxo de criação e processamento de
pedidos de forma escalável e resiliente.

### Desenvolvedores

* [Evandro 🧑🏾‍💻](https://github.com/evignacio) <br>
* [Ariel 🧑‍💻](https://github.com/Neuyer)

### Tecnologias utilizadas

![Java](https://img.shields.io/badge/Java-21-blue?style=for-the-badge&logo=java)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-3.3.5-brightgreen?style=for-the-badge)
![Maven](https://img.shields.io/badge/Maven-3.8.6-C71A36?style=for-the-badge&logo=apachemaven)
![Docker](https://img.shields.io/badge/Docker-24.0.6-2496ED?style=for-the-badge&logo=docker)
![Mongo](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white)
![kafka](https://img.shields.io/badge/Apache_Kafka-231F20?style=for-the-badge&logo=apache-kafka&logoColor=white)

## Microsserviços

* [ms-order-receiver](https://github.com/evignacio/ms-order-receiver)
* [ms-order](https://github.com/evignacio/ms-order)
* [ms-client](https://github.com/Neuyer/ms-client)
* [ms-product](https://github.com/evignacio/ms-product)
* [ms-stock](https://github.com/Neuyer/ms-stock)
* [ms-payment](https://github.com/evignacio/ms-payment)

## Execução

Para executar os serviços, siga as instruções abaixo:

* No diretorio raiz do projeto, execute o comando: `docker-compose up -d`
* Após a inicialização dos containers, acesse o endereço do Swagger de cada aplicação para executar as
  operações.  [Swagger](http://localhost:${porta}/swagger-ui/index.html#/)

## Testes

Os relatórios de teste podem ser encontrados na pasta `/JacocoReports`