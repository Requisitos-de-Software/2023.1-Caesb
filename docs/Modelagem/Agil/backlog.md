# Backlog

## Introdução
O backlog é uma lista que contempla todas as funcionalidades desejadas para um determinado produto, no caso do projeto, do aplicativo. É uma ferramenta fundamental para organizar e priorizar o trabalho em equipe, fornecendo uma visão geral das atividades pendentes e o progresso do projeto.

O backlog é criado durante o processo de planejamento do projeto e ele não precisa estar completo no início do projeto, uma vez que pode começar com tudo aquilo que é mais óbvio e fundamental a um primeiro momento, e mudá-lo com o tempo, a medida que se aprende mais sobre o produto e seus usuários.

## Motivo da Escolha
Foi escolhido utilizar o backlog pelos benefícios significativos que ele traz para todas as partes envolvidas durante o desenvolvimento do projeto. Proporcionando transparência e permitindo uma visão clara e compartilhada das atividades pendentes e uma comunicação eficiente das equipes de stackholders. Uma vez que ele traz uma divisão clara de Temas, Épicos e Histórias de Usuários.

## Metodologia
Para que fosse realizado o backlog, se utilizou todos os requisitos elicitados pelas seguintes formas:

* [Introspecção](../../Elicitacao/introspeccao.md)
* [Questionário](../../Elicitacao/questionario.md)
* [StoryTelling](../../Elicitacao/storytelling.md)

Diante de todos os requisitos apresentados nessas páginas, foi divido todos em temas relativos o qual estavam inserindo dentro do aplicativo e dentro de cada tema ocorre mais uma divisão, sendo os Épicos e cada épico apresentou sua história de usuário. 
Para a validação, foi utilizado uma entrevista que pode ser encontrada no tópico de validação.
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

<table>
  <tr>
    <th>Tema</th>
    <th>Épicos</th>
    <th>ID</th>
  </tr>
  <tr>
    <td style="vertical-align:middle" rowspan="2">Consumo</td>
    <td>Pagamento: Todas as funcionalidades de pagamentos e suas formas de ser realizado.</td>
    <td>EP01</td>
  </tr>
  <tr>
    <td>Acompanhamento: Todas as funcionalidades que podem dar feddback ao usuário sobre o consumo.</td>
    <td>EP02</td>
  </tr>
  <tr>
    <td style="vertical-align:middle" rowspan="3">Serviços</td>
    <td>Detalhamento: Funcionalidades que permitem o usuário acessar informações valiosas de seu interesse.</td>
    <td>EP03</td>
  </tr>
  <tr>
    <td>Solicitação:  Todo tipo de solicitação de serviço que o usuário pode fazer.</td>
    <td>EP04</td>
  </tr>
  <tr>
    <td>Conta: Toda funcionalidade que envolve a conta de usuário</td>
    <td>EP05</td>
  </tr>
</table>

</center>

<p style="text-align: center"> Tabela 2: Épicos Definidos (Fonte: autores, 2023).</p>

Cada épico vai possuir suas histórias de usuário correspondente, o que serão especificadas e detalhadas dentro do documento de [histórias de usuário](../Agil/historia_usuario.md).			

## Backlog
Na tabela 3 possui o Backlog completo com os temas, épicos e histórias de usuário correspondentes.



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
    <td>Eu, como usuário, desejo realizar o pagamento da fatura pelo PIX.</td>
    <td>US01</td>
    <td>RF08</td>
  </tr>
  <tr>
    <td>Eu, como usuário, desejo realizar o pagamento da fatura por boleto.</td>
    <td>US02</td>
    <td>RF09</td>
  </tr>
  <tr>
    <td>Eu, como usuário, desejo efetuar o pagamento da fatura utilizando cartão de débito ou crédito.</td>
    <td>US03</td>
    <td>RF12</td>
  </tr>
  <tr>
    <td>Eu, como usuário, desejo cadastrar um cartão de crédito/débito para facilitar pagamentos futuros.</td>
    <td>US04</td>
    <td>RF16</td>
  </tr>
  <tr>
    <td>Eu, como usuário, desejo ver o histórico de pagamentos realizados.</td>
    <td>US05</td>
    <td>RF19</td>
  </tr>
  <tr>
    <td>Eu, como usuário, desejo visualizar a segunda via da fatura.</td>
    <td>US06</td>
    <td>RF01</td>
  </tr>
  <tr>
    <td>Eu, como usuário, desejo ver o consumo de água com os custos detalhados.</td>
    <td>US07</td>
    <td>RF05</td>
  </tr>
  <tr>
    <td>Eu, como usuário, desejo receber notificações sobre faturas próximas do vencimento.</td>
    <td>US08</td>
    <td>RF10</td>
  </tr>
  <tr>
    <td>Eu, como usuário, desejo ativar o pagamento automático da fatura por cartão cadastrado.</td>
    <td>US09</td>
    <td>RF17</td>
  </tr>
  <tr>
    <td style="vertical-align:middle" rowspan="3">EP02 - Acompanhamento</td>
    <td>Eu, como usuário, desejo verificar o andamento da leitura do medidor de água.</td>
    <td>US10</td>
    <td>RF21</td>
  </tr>
  <tr>
    <td>Eu, como usuário, desejo receber notificações sobre a próxima leitura do medidor de água.</td>
    <td>US11</td>
    <td>RF13</td>
  </tr>
  <tr>
    <td>Eu, como usuário, desejo visualizar o histórico de consumo de água.</td>
    <td>US12</td>
    <td>RF06</td>
  </tr>
  <tr>
    <td style="vertical-align:middle" rowspan="10">Serviços</td>
    <td style="vertical-align:middle" rowspan="3">EP03 - Detalhamento</td>
    <td>Eu, como usuário, desejo ter acesso aos protocolos de serviço relacionados às solicitações realizadas.</td>
    <td>US13</td>
    <td>RF11</td>
  </tr>
  <tr>
    <td>Eu, como usuário, desejo receber notificações sobre falta de água na região.</td>
    <td>US14</td>
    <td>RF07</td>
  </tr>
  <tr>
    <td>Eu, como usuário, desejo acessar informações sobre a qualidade do lago.</td>
    <td>US15</td>
    <td>RF19</td>
  </tr>
  <tr>
    <td style="vertical-align:middle"rowspan="4">EP04 - Solicitação</td>
    <td>Eu, como usuário, desejo solicitar um serviço específico oferecido pela CAESB.</td>
    <td>US16</td>
    <td>RF02</td>
  </tr>
  <tr>
    <td>Eu, como usuário, desejo solicitar a autoleitura do medidor de água.</td>
    <td>US17</td>
    <td>RF22</td>
  </tr>
  <tr>
    <td>Eu, como usuário, desejo denunciar um vazamento de água para a CAESB.</td>
    <td>US18</td>
    <td>RF04</td>
  </tr>
  <tr>
    <td>Eu, como usuário, desejo entrar em contato com a equipe de suporte da CAESB.</td>
    <td>US19</td>
    <td>RF14</td>
  </tr>
  <tr>
    <td style="vertical-align:middle" rowspan="3">EP05 - Conta</td>
    <td>Eu, como usuário, desejo cadastrar mais de um imóvel em minha conta.</td>
    <td>US20</td>
    <td>RF18</td>
  </tr>
  <tr>
    <td>Eu, como usuário, desejo entrar no aplicativo utilizando minhas credenciais de acesso.</td>
    <td>US21</td>
    <td>RF03</td>
  </tr>
  <tr>
    <td>Eu, como usuário, desejo utilizar a autenticação biométrica, como a impressão digital, para acessar o aplicativo.</td>
    <td>US22</td>
    <td>RF15</td>
  </tr>
</table>

<p style="text-align: center"> Tabela 3: Apresentação do Backlog (Fonte: autores, 2023).</p>

## Validação
Durante o processo de validação do backlog tiverem os respectivos participantes, como também seus cargos apresentados na tabela 4. Como também a entrevista de validação no iframe 1.

### Participantes

<center>

|        Nome       |            Cargo           |
|:-----------------:|:--------------------------:|
| Paulo Victor      | Equipe de desenvolviento   | 
| Wildemberg Sales  | Product Owner              |
<div style="text-align: center">
<p> Tabela 4: Participantes (Fonte: autor, 2023).</p>
</div>

</center>

### Entrevista

<center>

<iframe width="700" height="400" src="https://www.youtube.com/embed/mGdaJMpBTOQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

</center>

<p style="text-align: center"> Iframe 1: Entrevista com o Usuário no papel de P.O (Fonte: autores, 2023).</p>



## Bibliografia
> SERRANO, Milene; Slides: Requisitos - Aula 15. - Disponibiliados pelo professor.

> JAMES, Michael e Luke Walter; Scrum Reference Card, 2017.

## Histórico de Versão

| Data | Data Prevista de Revisão | Versão | Descrição | Autor | Revisor |
| :--: | :----------------------: | :----: | :-------: | :---: | :-----: |
| 20/05/2023 | 20/05/2023 |  1.0   | Criação do Documento | [Daniel](https://github.com/daniel-de-sousa) e [Pedro](https://github.com/pedrobarbosaocb) |  [Caetano](https://github.com/caeslucio) |
| 24/05/2023 | 24/05/2023 |  1.1   | Refinamento do Documento | [Daniel](https://github.com/daniel-de-sousa) e [Pedro](https://github.com/pedrobarbosaocb) |  [Caetano](https://github.com/caeslucio) |






