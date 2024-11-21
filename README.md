# DSList

Este projeto foi desenvolvido durante o intensivo Java Spring ministrado por Nélio Alves (Dev Superior). O objetivo do projeto é criar uma aplicação para gerenciar uma lista de jogos.

## Tecnologias Utilizadas

- Java
- Spring Boot
- JPA / Hibernate
- PostgreSQL
- Docker

## Funcionalidades

- Cadastro de jogos
- Listagem de jogos
- Atualização de informações dos jogos
- Remoção de jogos

## Como Executar o Projeto

### Pré-requisitos

- Java 11 ou superior
- Docker e Docker Compose

### Passos para Executar

1. Clone o repositório:
   ```bash
   git clone https://github.com/vitorbnr/dslist.git
   cd dslist

Execute o Docker Compose para iniciar os serviços:

docker-compose up -d
Execute a aplicação:

./mvnw spring-boot:run
A aplicação estará disponível em http://localhost:8080.

Estrutura do Projeto
src/main/java: Código fonte da aplicação

src/main/resources: Arquivos de configuração

docker-compose.yml: Configuração dos serviços Docker
