# Backlog

## Introdução
O backlog é uma lista que contempla todas as funcionalidades desejadas para um determinado produto, no caso do projeto, do aplicativo. É uma ferramenta fundamental para organizar e priorizar o trabalho em equipe, fornecendo uma visão geral das atividades pendentes e o progresso do projeto.

O backlog é criando durante o processo de planejamento do projeto e ele não precisa estar completo no início do projeto, uma vez que pode começar com tudo aquilo que é mais óbvio e fundamental a um primeiro momento, e mudá-lo com o tempo, a medida que se aprende mais sobre o produto e seus usuários.

## Motivo da Escolha
Foi escolhido utilizar o backlog pelos benefícios significativos que ele traz para todas as partes envolvidas durante o desenvolvimento do projeto. Proporcionando transparência e permitindo uma visão clara e compartilhada das atividades pendentes e uma comunicação eficiente das equipes de stackholders. Uma vez que ele traz uma divisão clara de Temas, Épicos e Histórias de Usuários.

## Metodologia
Para que fosse realizado o backlog, se utilizou todos os requisitos elicitados pelas seguintes formas:

* [Introspecção](../../Elicitacao/introspeccao.md)
* [Questionário](../../Elicitacao/questionario.md)
* [StoryTelling](../../Elicitacao/storytelling.md)

Diante de todos os requisitos apresentados nessas páginas, foi divido todos em temas relativos o qual estavam inserindo dentro do aplicativo e dentro de cada tema ocorre mais uma divisão, sendo os Épicos e cada épico apresentou sua história de usuário.
Dessa forma, foram organizados todos os requisitos funcionais e apresentados todos na tabela 1. 

| ID   | Descrição                                                                                                           | Rastreabilidade          |
|:----:|---------------------------------------------------------------------------------------------------------------------|:------------------------:|
| RF01 | O usuário deve poder pegar a 2ª via da fatura                                                                       | Q03                      |
| RF02 | O usuário deve poder solicitar serviço (CRU)                                                                        | Q09 e INT10              |
| RF03 | O usuário deve poder fazer login com seus dados (CRUD)                                                              | INT01 e INT09            |
| RF04 | O usuário deve poder informar sobre vazamentos                                                                      | Q17                      |
| RF05 | O aplicativo deve permitir que os usuários gerem relatórios detalhados sobre seu consumo de água e os custos associados ao consumo | INT08 e ST02              |
| RF06 | O aplicativo deve permitir que os usuários visualizem o historico de consumo de água                                | INT02 e ST04             |
| RF07 | O usuário deve ser notificado sobre falta de água em sua região                                                     | Q11 e INT04              |
| RF08 | O aplicativo deve permitir que o usuário pague suas contas de água utilizando chave pix                             | INT06                    |
| RF09 | O aplicativo deve permitir que o usuário copie o código do boleto                                                   | Q05 e ST05               |
| RF10 | Notificar usuário que a fatura está próxima do vencimento                                                           | Q02, INT04 e ST01        |
| RF11 | Deve se ter mais detalhe e clareza com relação aos protocolos e serviços                                            | Q14                      |
| RF12 | O aplicativo deve permitir que o usuário pague suas contas de água utilizando cartão de crédito ou débito           | INT05                    |
| RF13 | Apresentar quando que ocorrerá uma próxima leitura                                                                  | Q15                      |
| RF14 | O aplicativo deve permitir que os usuários entrem em contato com a equipe de suporte da CAESB                       | INT07 e ST06             |
| RF15 | O usuário deve poder acessar sua conta por meio de sua impressão digital previamente cadastrada                     | Q10                      |
| RF16 | O aplicativo deve permitir que o usuário cadastre cartões de crédito/débito                                         | Q04 e ST05               |
| RF17 | O usuário deve possuir uma forma de pagamento por cartão que seja automática                                        | Q06 e ST05               |
| RF18 | A possibilidade de se utilizar cadastros de outras casas, podendo haver, por exemplo, um sistema de troca de contas | Q08                      |
| RF19 | O aplicativo deve informar o motivo para a qualidade de banho em uma área do lago não ser a ideal                   | Q16                      |
| RF20 | O usuário deve poder acessar o seu histórico de pagamentos                                                          |                          |
| RF21 | O aplicativo deve disponibilizar o status do agendamento da leitura                                                 |                          |
| RF22 | O usuário deve poder solicitar a realização da autoleitura                                                          |                          |

<p style="text-align: center"> Tabela 1: Requisitos funcionais elicitados (Fonte: autores, 2023).</p>

## Temas
Tendo os requisitos elicitados, foi possível verificar que eles fazem parte de dois grandes grupos, sendo eles:

* Consumo: Possuindo todas as atividades que tem relacionamento com o consumo de água do usuário, como pagar conta ou emitir uma segunda via.
* Serviços: Todos os serviços disponibilizados pela CAESB, como denuncia de vazamentos e notificações do interesse do usuário.

E a partir desses temas, foi definido épicos dentro de cada um deles, que representam grandes áreas de funcionalidades em um sistema.
## Épicos
Com base nos temas, foi possível criar os seguintes épicos apresentados na tabela 2:

<center>

|Tema|Épicos|ID|
|:--:|:-----|::|
|Consumo |Pagamento: Todas as funcionalidades de pagamentos e suas formas de ser realizado.|EP01|
|        |Acompanhamento: Todas as funcionalidades que podem dar feddback ao usuário sobre o consumo.|EP02|
|Serviços|Detalhamento: Funcionalidades que permitem o usuário acessar informações valiosas de seu interesse.|EP03|
|        |Solicitação:  Todo tipo de solicitação de serviço que o usuário pode fazer.|EP04|
|        |Conta: Toda funcionalidade que envolve a conta de usuário|EP05|

</center>

<p style="text-align: center"> Tabela 2: Épicos Definidos (Fonte: autores, 2023).</p>

Cada épico vai possuir suas histórias de usuário correspondente, o que serão especificadas e detalhadas dentro do documento de [histórias de usuário](../Agil/historia_usuario.md).			

## Backlog
Na tabela 3 possui o Backlog completo com os temas, épicos e histórias de usuário correspondentes.

| Temas       | Épicos                                      | Histórias de Usuário                                              | ID | Rastreabilidade |
|:-----------:|:-------------------------------------------:|-------------------------------------------------------------------|:------:|:---------------:|
|             | Pagamento                                   | Realizar pagamento pelo pix                                       |[US01]()| RF08            |
|             |                                             | Realizar pagamento por boleto                                     |[US02]()| RF09            |
|             |                                             | Realizar pagamento por cartão de débito/crédito                   |[US03]()| RF12            |
|             |                                             | Poder cadastrar cartão de crédito/débito                          |[US04]()| RF16            |
|Consumo      |                                             | Visualizar histórico de pagamentos                                |[US05]()| RF19            |
|             |                                             | Visualizar 2a via da fatura                                       |[US06]()| RF01            |
|             |                                             | Visualizar consumo junto com os custos detalhados                 |[US07]()| RF05            |
|             |                                             | Ser notificado sobre fatura proxima do vencimento                 |[US08]()| RF10            |
|             |                                             | Poder ativar pagamento automático da fatura por cartão cadastrado |[US09]()| RF17            |
|             |--                                           | --                                                                |--      | --              |
|             | Acompanhamento                              | Verificar andamento da leitura                                    |[US10]()| RF21            |
|             |                                             | Ser notificado sobre a próxima leitura                            |[US11]()| RF13            |
|             |                                             | Visualizar histórico de consumo                                   |[US12]()| RF06            |
|--           |--                                           | --                                                                |--      | --              |
|             | Detalhamento                                | Ter acesso aos protocolos de serviço                              |[US13]()| RF11            |
|             |                                             | Ser notificado sobre falta de água na região                      |[US14]()| RF07            |
|             |                                             | Saber motivo pelo qual a qualidade do lago indicada               |[US15]()| RF19            |
|             |--                                           | --                                                                |--      | --              |
|Serviços     | Solicitação                                 | Solicitar serviço                                                 |[US16]()| RF02            |
|             |                                             | Solicitar autoleitura                                             |[US17]()| RF22            |
|             |                                             | Denunciar vazamento de agua                                       |[US18]()| RF04            |
|             |                                             | Devo poder contactar a equipe de suporte                          |[US19]()| RF14            |
|             |--                                           | --                                                                |--      | --              |
|             | Conta                                       | Poder cadastrar mais do que um imovel                             |[US20]()| RF18            |
|             |                                             | Poder entrar no aplicativo utilizando meus dados                  |[US21]()| RF03            |
|             |                                             | Entrar usando digital                                             |[US22]()| RF15            |

<p style="text-align: center"> Tabela 3: Apresentação do Backlog (Fonte: autores, 2023).</p>

## Bibliografia
> SERRANO, Milene; Slides: Requisitos - Aula 15. - Disponibiliados pelo professor.

> JAMES, Michael e Luke Walter; Scrum Reference Card, 2017.

## Histórico de Versão

| Data | Data Prevista de Revisão | Versão | Descrição | Autor | Revisor |
| :--: | :----------------------: | :----: | :-------: | :---: | :-----: |
| 20/05/2023 | 20/05/2023 |  1.0   | Criação do Documento | [Daniel](https://github.com/daniel-de-sousa) e [Pedro](https://github.com/pedrobarbosaocb) |  [Caetano](https://github.com/caeslucio) |