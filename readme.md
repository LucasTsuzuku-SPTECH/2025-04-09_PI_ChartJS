# SPTECH Chart.JS 🚩

Desafio da Alura baseada no curso "Praticando Spring Framework: Challenge Fórum Hub"

## Objetivo 📜

Crie uma página HTML e utilize a biblioteca "Chart.JS" como foi explicado, criando uma dashboard como a imagem abaixo:

![Alt text](/src/img/2024-12-26-Esquema_Aplicacao.jpg)

Para facilitar, estes são os dados:

Gráfico de Linhas:

<p align="center">Figura 1: Esquema API REST Stateless</p>

![Alt text](/src/img/2024-12-26-Esquema_Requisicao.jpg)

Horário Temperatura Umidade
12:00 30 80
13:00 29 82
14:00 28 80
15:00 25 85
16:00 22 80
17:00 23 83

Gráfico de Barras:

Mês Temperatura Média Umidade Média
Janeiro 22 90
Fevereiro 24 89
Março 27 93
Abril 23 87
Maio 20 88
Junho 18 82

Caso queira, pode adicionar CSS à página!
Formato de entrega:
Crie um repositório PÚBLICO para subir o código desenvolvido, e envie o endereço do GitHub contendo seu repositório PÚBLICO com os arquivos criados para esta tarefa.

## Ferramentas e tecnologias 👨‍💻

- Spring Initializr
  - JAVA 17
  - Spring Boot 3.4
  - Maven
  - Packaging Jar
- Dependências:
  - Spring Web
  - Spring Boot DevTools
  - Spring Data JPA
  - Flyway Migration
  - Mysql Driver
  - Validation
  - Spring Security
- Insomnia REST
- JSON Web Tokens

## Passo a Passo 👣

- Criar repositório Github
- Construção banco de dados
- CRUD Tópico
- Criação do endpoint de detalhamento de tópicos
- Teste dos endpoints
- Autenticação com Spring Security
- Geração de token usando JWT
- Autenticação com JWT

## Resultados 🎁

![Alt text](/src/img/results1.png)

## Referências 📚

- https://cursos.alura.com.br/course/spring-framework-challenge-forum-hub
- https://trello.com/b/OKIUKgxe/alura-f%C3%B3rum-challenge-one-sprint-01
- https://git-scm.com/docs/git-help
- https://graphite.dev/guides/git-set-upstream
- https://pt.stackoverflow.com/questions/580380/posso-chamar-um-metodo-especifico-no-spring-security-sem-est%C3%A1-logado
- https://stackoverflow.com/questions/9424364/cant-compile-project-when-im-using-lombok-under-intellij-idea
- https://intellij-support.jetbrains.com/hc/en-us/community/posts/23064675521682-Lombok-not-workin-with-Intellij
- https://blog.algaworks.com/entendendo-o-equals-e-hashcode/
- https://pt.stackoverflow.com/questions/235719/como-renomear-o-nome-da-coluna-tabela-sql
- https://stackoverflow.com/questions/25681386/how-to-map-hibernate-entity-fields-using-camelcase-to-snake-case-underscore-da
- https://dev.mysql.com/doc/refman/8.4/en/datetime.html
- https://pt.stackoverflow.com/questions/545059/como-mudar-a-constrains-de-null-para-not-null
- https://www.baeldung.com/spring-data-jpa-getreferencebyid-findbyid-methods
- https://bcrypt-generator.com/

## Atualizações 🕐

- 2024/12/26 - Primeira versão do aplicativo

## Pendências 🚨

- Adicionar outras entidades:

  - Resposta
  - Usuário
  - Curso
  - Perfil

- Documentação com Swagger
- Implemente outras rotas em sua aplicação
  - Para que nosso fórum seja completo devemos ter outras rotas ou endpoints que nos permitam criar, listar, atualizar e excluir outras informações além dos tópicos como:
    - /usuario
    - /respostas
- Testes Unitários
- Criar uma aplicação frontend
