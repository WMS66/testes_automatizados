# TESTES AUTOMATIZADOS

## JavaScript

-   MOCK:

    -   mock é o objeto necessário para o teste funcionar

    -   cenário:

        -   Ponto A

        -   Ponto B
        -   Ponto C

        A => B

        o mock para rodar o teste de B => C é o resultado do Ponto A para o ponto B
        B => C

        errado pois o teste está duplicado
        A => B => C

-   STUB:

    -   stub serve para interceptar chamadas externas (DB, API Externa, etc)
    -   garantir que o nosso teste será OFFLINE (Sem system, sem internet, sem memoria)

-   SPY:
    -   spy é um tipo de stub, mas é usado para validar como a função foi chamada, com quais parametros e quantas vezes

#

🖥️ fontes:

-   [Erick Wendel](https://www.youtube.com/watch?v=8hxhZkBzWhk)

-   [routes](https://github.com/ErickWendel/semana-javascript-expert06/blob/main/aulas/aula03-desafio-resolvido/tests/unit/server/routes.test.js)
-   [Nodejs](https://github.com/nodejs/node/pull/42325/files)
-   [Assert](https://nodejs.org/api/assert.html#class-assertcalltracker)
-   [ndejs-pull](https://github.com/nodejs/node/pull/41862/files)
-   [coverage](https://coverage.nodejs.org)
