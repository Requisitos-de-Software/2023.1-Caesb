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

---
<table>
  <tr>
    <th>Temas</th>
    <th>Épicos</th>
    <th>Histórias de Usuário</th>
    <th>ID</th>
    <th>Rastreabilidade</th>
  </tr>
  <tr>
    <td style="vertical-align:middle" rowspan="12">Consumo</td>
    <td style="vertical-align:middle" rowspan="9">EP01 - Pagamento</td>
    <td>Realizar pagamento pelo pix</td>
    <td><a href="#">US01</a></td>
    <td>RF08</td>
  </tr>
  <tr>
    <td>Realizar pagamento por boleto</td>
    <td><a href="#">US02</a></td>
    <td>RF09</td>
  </tr>
  <tr>
    <td>Realizar pagamento por cartão de débito/crédito</td>
    <td><a href="#">US03</a></td>
    <td>RF12</td>
  </tr>
  <tr>
    <td>Poder cadastrar cartão de crédito/débito</td>
    <td><a href="#">US04</a></td>
    <td>RF16</td>
  </tr>
  <tr>
    <td>Visualizar histórico de pagamentos</td>
    <td><a href="#">US05</a></td>
    <td>RF19</td>
  </tr>
  <tr>
    <td>Visualizar 2a via da fatura</td>
    <td><a href="#">US06</a></td>
    <td>RF01</td>
  </tr>
  <tr>
    <td>Visualizar consumo junto com os custos detalhados</td>
    <td><a href="#">US07</a></td>
    <td>RF05</td>
  </tr>
  <tr>
    <td>Ser notificado sobre fatura proxima do vencimento</td>
    <td><a href="#">US08</a></td>
    <td>RF10</td>
  </tr>
  <tr>
    <td>Poder ativar pagamento automático da fatura por cartão cadastrado</td>
    <td><a href="#">US09</a></td>
    <td>RF17</td>
  </tr>
  <tr>
    <td style="vertical-align:middle" rowspan="3">EP02 - Acompanhamento</td>
    <td>Verificar andamento da leitura</td>
    <td><a href="#">US10</a></td>
    <td>RF21</td>
  </tr>
  <tr>
    <td>Ser notificado sobre a próxima leitura</td>
    <td><a href="#">US11</a></td>
    <td>RF13</td>
  </tr>
  <tr>
    <td>Visualizar histórico de consumo</td>
    <td><a href="#">US12</a></td>
    <td>RF06</td>
  </tr>
  <tr>
    <td style="vertical-align:middle" rowspan="10">Serviços</td>
    <td style="vertical-align:middle" rowspan="3">EP03 - Detalhamento</td>
    <td>Ter acesso aos protocolos de serviço</td>
    <td><a href="#">US13</a></td>
    <td>RF11</td>
  </tr>
  <tr>
    <td>Ser notificado sobre falta de água na região</td>
    <td><a href="#">US14</a></td>
    <td>RF07</td>
  </tr>
  <tr>
    <td>Saber motivo pelo qual a qualidade do lago indicada</td>
    <td><a href="#">US15</a></td>
    <td>RF19</td>
  </tr>
  <tr>
    <td style="vertical-align:middle"rowspan="4">EP04 - Solicitação</td>
    <td>Solicitar serviço</td>
    <td><a href="#">US16</a></td>
    <td>RF02</td>
  </tr>
  <tr>
    <td>Solicitar autoleitura</td>
    <td><a href="#">US17</a></td>
    <td>RF22</td>
  </tr>
  <tr>
    <td>Denunciar vazamento de água</td>
    <td><a href="#">US18</a></td>
    <td>RF04</td>
  </tr>
  <tr>
    <td>Devo poder contactar a equipe de suporte</td>
    <td><a href="#">US19</a></td>
    <td>RF14</td>
  </tr>
  <tr>
    <td style="vertical-align:middle" rowspan="3">EP05 - Conta</td>
    <td>Poder cadastrar mais do que um imóvel</td>
    <td><a href="#">US20</a></td>
    <td>RF18</td>
  </tr>
  <tr>
    <td>Poder entrar no aplicativo utilizando meus dados</td>
    <td><a href="#">US21</a></td>
    <td>RF03</td>
  </tr>
  <tr>
    <td>Entrar usando digital</td>
    <td><a href="#">US22</a></td>
    <td>RF15</td>
  </tr>
</table>

<p style="text-align: center"> Tabela 3: Apresentação do Backlog (Fonte: autores, 2023).</p>

## Bibliografia
> SERRANO, Milene; Slides: Requisitos - Aula 15. - Disponibiliados pelo professor.

> JAMES, Michael e Luke Walter; Scrum Reference Card, 2017.

## Histórico de Versão

| Data | Data Prevista de Revisão | Versão | Descrição | Autor | Revisor |
| :--: | :----------------------: | :----: | :-------: | :---: | :-----: |
| 20/05/2023 | 20/05/2023 |  1.0   | Criação do Documento | [Daniel](https://github.com/daniel-de-sousa) e [Pedro](https://github.com/pedrobarbosaocb) |  [Caetano](https://github.com/caeslucio) |