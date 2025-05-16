
# Automatizando API REST com Spring Boot

## Apresentação do Projeto

“Automatizando API REST com Spring Boot” é um projeto desenvolvido com o objetivo de demonstrar, na prática, como construir uma API RESTful moderna, enxuta e eficiente utilizando o ecossistema do Spring Boot.

A proposta é criar uma estrutura base reutilizável que automatize operações comuns de CRUD (Create, Read, Update, Delete) com o mínimo de configuração, aproveitando ao máximo os recursos e anotações do Spring. Essa abordagem não apenas acelera o desenvolvimento, como também promove uma arquitetura limpa, escalável e fácil de manter.

Durante a construção do projeto, foram aplicadas boas práticas como separação em camadas (Controller, Service, Repository), uso de banco de dados em memória para testes (H2), e integração com o Spring Data JPA, permitindo persistência de dados de forma simples e declarativa.

O projeto serve tanto como base para quem está aprendendo o ecossistema Spring, quanto como ponto de partida para aplicações mais complexas em ambientes corporativos, microserviços e soluções backend robustas.

## Aprendizados
Este projeto permitiu a consolidação de conceitos fundamentais no desenvolvimento de APIs REST com Spring Boot, destacando:

## Arquitetura em camadas
Estruturação da aplicação com separação entre Controller, Service e Repository, respeitando os princípios da Clean Architecture.

Aplicação do padrão MVC para melhor manutenção, legibilidade e escalabilidade.

## Uso de anotações do Spring
Implementação de funcionalidades com o mínimo de código repetitivo, aproveitando anotações como @RestController, @GetMapping, @PostMapping, @Autowired, @Entity, @Repository, entre outras.

Compreensão do ciclo de vida das requisições RESTful no Spring.

## Integração com banco de dados
Uso do Spring Data JPA para persistência de dados e simplificação da lógica de acesso a banco com interfaces de repositório.

Configuração de banco H2 em memória para testes rápidos, e entendimento da estrutura de entidades com JPA.

## Testes e validações
Criação de endpoints seguros com validações básicas de entrada.

Testes de requisições utilizando ferramentas como Postman.

## Serialização e respostas HTTP
Retorno de respostas consistentes em formato JSON.

Gerenciamento de status HTTP como 200 OK, 201 Created, 400 Bad Request e 404 Not Found.

## Automatização do CRUD
Automatização de operações básicas (Create, Read, Update, Delete) com mínimo esforço de codificação graças ao Spring Boot.

Compreensão de como a convenção do Spring permite gerar endpoints funcionais rapidamente.



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
