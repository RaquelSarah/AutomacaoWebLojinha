## Lojinha Web Automação - JUnit e Web Driver

Esse é um repositório que contém a automação de alguns testes Web de um software denominado Lojinha. Os sub-tópicos abaixo descrevem algumas decisões tomadas da estruturação do Projeto.

## Tecnologias Utilizadas

-   Java  [https://www.oracle.com/br/java/technologies/javase/javase8u211-later-archive-downloads.html]
-   JUnit  [https://mvnrepository.com/artifact/org.junit.jupiter/junit-jupiter-api/5.10.0]
-   Selenium Java  [https://mvnrepository.com/artifact/org.seleniumhq.selenium/selenium-java/4.0.0-beta-4]
-   Maven  [https://maven.apache.org/]

## Testes Automatizados

Testes para validar  a inserção de produtos na Web da Lojinha com base nas regras de negócios, utilizando a técnica de testes de Valor Limite.

## Notas Gerais

-   Inicialmente eu preparei o projeto em Java com as dependências, configurando as bibliotecas;
-   Refatorei o código usando 2 design Patterns: Page Objects e Fluent Pages;
-   Utilizei a anotação Before Each para abrir o navegador e navegar para a pagina da lojinha Web;
-   Criei dados iniciais através de classe Data Factory, para facilitar a criação e controle dos mesmos;
-   Nesse Projeto fiz uso do JUnit 5, o que me permitiu a possibilidade de usar a anotação DisplayName para dar descrições em português para os meus testes.
