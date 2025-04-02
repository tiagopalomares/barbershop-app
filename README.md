
# Barbershop API

Este é um projeto de API para gestão de agendamentos em uma barbearia. O sistema permite cadastrar clientes, agendar serviços e gerenciar os atendimentos de forma simples e eficiente.
## Stack utilizada

Java

Spring Boot

Gradle

Spring Data JPA

H2 Database (Banco de dados em memória para testes)

Lombok
## Como Executar o Projeto

Clone o repositório:

git clone https://github.com/tiagopalomares/barbershop-app.git

Acesse a pasta do projeto:

cd barbershop-app

Execute o projeto com Gradle:

./gradlew bootRun  # Linux/Mac
gradlew bootRun  # Windows

A API estará rodando em http://localhost:8080.
## Endpoints Principais

GET /clientes - Lista todos os clientes

POST /clientes - Cadastra um novo cliente

GET /agendamentos - Lista todos os agendamentos

POST /agendamentos - Cria um novo agendamento
## Sobre o Projeto

Este projeto foi desenvolvido durante um bootcamp da DIO (Digital Innovation One) como parte do aprendizado em desenvolvimento backend com Spring Boot.
