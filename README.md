<h1 align="center">
  Movies App Backend
</h1>

<p align="center">
 <img src="https://img.shields.io/static/v1?label=Tipo&message=Desafio&color=8257E5&labelColor=000000" alt="Desafio" />
</p>

API para gerenciar filmes e reviews (CRUD) que faz parte [desse desafio](https://www.youtube.com/watch?v=5PdEmeopJVQ) para pessoas desenvolvedoras backend que estão se desenvolvendo em Java Spring.

## Tecnologias
 
- [Spring Boot](https://spring.io/projects/spring-boot)
- [Spring Web](https://docs.spring.io/spring-framework/reference/web/webflux.html)
- [Spring Data MongoDB](https://spring.io/projects/spring-data-mongodb)
- [Lombok](https://projectlombok.org/)

## Práticas adotadas

- SOLID
- Consultas com filtros dinâmicos usando o Query By Example
- Injeção de Dependências
- Repositórios
- Services

## Como Executar

### Localmente
- Clonar repositório git
- Construir o projeto:
```
./mvnw clean package
```
- Executar:
```
java -jar movies/target/movies-0.0.1-SNAPSHOT.jar
```

A API poderá ser acessada em [localhost:8080](http://localhost:8080).

```

A API poderá ser acessada em [localhost:8080](http://localhost:8080).

## API Endpoints

Para fazer as requisições HTTP abaixo, foi utilizada a ferramenta [postman](https://www.postman.com/):

- POST /api/v1/movies (cadastrar um novo filme)

- GET /api/v1/movies (lista de todos os filmes)

