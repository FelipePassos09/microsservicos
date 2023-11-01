# Curso Microsservicos com .Net
Conteúdo de anotações realizadas durante o curso de microsserviços do Prof. Leandro Costa (Udemy).

## Diferenças entre arquityetura monolítica e microsserviços
Basicamente temos um conjunto de características inerentes a cada arquitetura mencionada sendo que um modelo não, necessáriamente, é melhor que o outro visto que para cada contexto teremos um conjunto de problemas e soluções que devem ser projetadas e que, a depender do caso, se adequam mais à um ou ao outro modelo.

Podemos dizer que enquanto uma arquitetura monolítica se concentra no relacionamento direto de todas as camadas da aplicação, sendo, neste caso, codependente do funcionamento de toda a solução, uma arquitetura em microsserviços permite o desacoplamento destes recursos de modo que podemos adotar soluções separadas e que se relacionam em um modelo de colaboração, ou seja, cada solução adotada, mesmo com linguagens de programação ou frameworks diferentes, colaboram em conjunto com a aplicação de modo que, a falha ou correção em uma delas não deve afetar diretamente as demais.

## Como desmembrar um monolito em microsserviços
Primeiramente devemos pensar que a solução de microsserviços objetiva desacoplar os recursos de uma aplicação para agregar tanto estabilidade quanto facilidade em manutenção, desenvolvimento e sustentação. Desse modo devemos nos preocupar em termos serviços "pequenos" de modo que possam ser mantidos por uma equipe pequena, com uma documentação abrangente e clara, mas que, dado o tamanho, não seja extensa. Outros pontos são  que cada serviço deve pessuir uma quantidade pequena de "segredos", ou seja, poucas regras de negócio e características dentro de si de modo que o conhecimento seja facilmente absorvido e propagado e, por último, deve ser previsível e fácil de experimentar, de modo que para a sua construção e manutenção, os processos de testes e melhorias sejam facilmente implementados e não tenham comportamentos anômalos inerentes ao serviço.

## Diferença entre microsserviços e SOA
Embora semelhantes em alngus aspectos, esses dois modelos possuem orientações opostas. Enquanto que o SOA é orientado à integração entre serviços e aplicações ele trata cada componente como uma aplicação à parte, já os microsserviços entendem que cada serviço é parte de uma mesma aplicação, de modo que cada serviço é orquestrado e tratado individualmente e como integrante da aplicação principal. 

