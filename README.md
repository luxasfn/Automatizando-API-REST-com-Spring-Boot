
# Automatizando API REST com Spring Boot

## Apresentação do Projeto

“Automatizando API REST com Spring Boot” é um projeto desenvolvido com o objetivo de demonstrar, na prática, como construir uma API RESTful moderna, enxuta e eficiente utilizando o ecossistema do Spring Boot.

A proposta é criar uma estrutura base reutilizável que automatize operações comuns de CRUD (Create, Read, Update, Delete) com o mínimo de configuração, aproveitando ao máximo os recursos e anotações do Spring. Essa abordagem não apenas acelera o desenvolvimento, como também promove uma arquitetura limpa, escalável e fácil de manter.

Durante a construção do projeto, foram aplicadas boas práticas como separação em camadas (Controller, Service, Repository), uso de banco de dados em memória para testes (H2), e integração com o Spring Data JPA, permitindo persistência de dados de forma simples e declarativa.

O projeto serve tanto como base para quem está aprendendo o ecossistema Spring, quanto como ponto de partida para aplicações mais complexas em ambientes corporativos, microserviços e soluções backend robustas.

## Tecnologias Utilizadas

- Java 17
- Spring Boot 3
- Spring Data JPA
- Hibernate
- Banco de dados H2
- Maven

## Estrutura Padrão

```
src
└── main
    ├── java
    │   └── com.exemplo.api
    │       ├── controller
    │       ├── model
    │       ├── repository
    │       └── service
    └── resources
        └── application.properties
```

## Como Executar

1. Clone o repositório:
```bash
git clone https://github.com/luxasfn/Automatizando-API-REST-com-Spring-Boot.git
```

2. Importe o projeto em sua IDE de preferência (IntelliJ, Eclipse, VSCode etc.)

3. Rode a aplicação a partir da classe principal (`ApiApplication.java`)

4. Acesse e teste os endpoints via Postman ou browser.

## Licença

Este projeto está licenciado sob a MIT License.
