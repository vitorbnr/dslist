# Projeto DSList 🎮

Este projeto é uma API para pesquisa de jogos com capacidade de classificação individual. A aplicação permite que os usuários encontrem informações sobre diferentes títulos e classifiquem os jogos com base em sua opinião.

## Tecnologias Utilizadas 💻

- **Java**
- **Spring Boot**
- **JPA / Hibernate**
- **PostgreSQL**
- **Postman**
- **H2 Database**

## Como Executar 🚀

Para executar o projeto em sua máquina, siga os passos abaixo:

1. **Clone o repositório**: Abra o terminal ou o prompt de comando e execute o comando abaixo para clonar o repositório localmente:
   ```bash
   git clone https://github.com/vitorbnr/dslist.git

Navegue até o diretório do projeto: Após o clone ser concluído, entre no diretório do projeto com o comando:

   ```bash
cd dslist
```
   
   ```bash
./mvnw clean install
```
- **Execute o projeto no terminal**: Após a compilação, execute o comando:

```bash
./mvnw spring-boot:run
```
- **Execute o projeto na IDE**: Abra sua IDE (por exemplo, IntelliJ IDEA), importe o projeto e execute a classe principal DslistApplication.java.

## Instruções de Uso 📋
Rotas GET:

/games: Busca a lista de jogos.

/games/{id}: Busca um jogo por meio do ID.

/lists: Busca a categoria das listas de jogos.

/lists/{id}/games: Busca a lista categorizada pelo gênero (ID) dos jogos.

Rotas POST:

lists/{id}/replacement: Permite ao usuário organizar a lista com base em sua opinião.

## Importar Coleção de JSON no Postman

Abra o Postman.

Clique em Import no canto superior esquerdo.

Selecione a opção Import.

Cole o arquivo chamado DSList.postman_collection.json fornecido no projeto.

## Visualize o H2 Console

Para visualizar o H2 Console e inspecionar o banco de dados em memória, siga os passos abaixo:

Certifique-se de que a aplicação está rodando.

Acesse o H2 Console no navegador através do endereço:

http://localhost:8080/h2-console
Use as seguintes credenciais para login:

JDBC URL: jdbc:h2:mem:testdb

User Name: sa

Password: (deixe em branco)

## Aprendizados 📚
Este projeto foi fundamental para fortalecer os seguintes conceitos:

Desenvolvimento de APIs RESTful com Spring Boot.

Integração com banco de dados PostgreSQL utilizando JPA/Hibernate.

Configuração e uso de variáveis de ambiente.

Manipulação de dados e criação de endpoints para operações CRUD.


