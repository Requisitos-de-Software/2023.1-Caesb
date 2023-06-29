# Backward - From

## Introdução
Rastreabilidade é a habilidade de se rastrear algo, sabendo de todo seu histórico, desse modo, a rastreabilidade de requisitos estabelece relação entre os requisitos elicitados e suas origens e outros artefatos derivados. 
Mas especificamente, o backward - from está preocupado em fazer a rastreabilidade para trás, ou seja, do requisito até a sua fonte.

## Metodologia
Para se realizar essa rastreabilidade, serão usados os requisitos elicitados nos seguintes artefatos:

* [Questionário](../Elicitacao/questionario.md)
* [Introspecção](../Elicitacao/introspeccao.md)
* [Storytelling](../Elicitacao/storytelling.md)
* [Especificação Suplementar - (Presentes também na Introspecção após Priorização)](../Modelagem/especificacao_suplementar.md)

Para melhor identificação será usada a legenda presente na tabela 1:

<center>

| Legenda |         Artefato          |
|:-------:|:-------------------------:|
| Q       | Questionário              |
| INT     | Introspecção              |
| ST      | Storytelling              |
| ES      | Especificação Suplementar |
| RF      | Requisito Funcional       |
| RNF     | Requisito não Funcional   |
| EF      |      Elo Funcional        |
| ENF     |     Elo não Funcional     |

<p>Tabela 1 - Legenda. (Fonte: Autor, 2023)</p>

</center>

Para que se possa ter mais informações e analisar melhor esses requisitos, será usado o Meta - Modelo de Toranzo que visa classificar os requisitos em quatro categorias, presentes nos slides da Professora Milene, Requisitos - Aula 26[1]:

* **Ambiental**: Informações do contexto no qual a organização está inserida.
* **Organizacional**: Informações sobre à organização (Missão, Objetivos e Estratégia).
* **Gerencial**: Informações que auxiliar a gerência do projeto.
* **Desenvolvimento**: Informações associadas aos diversos artefatos gerados ao longo do processo de desenvolvimento (Artefatos de requisitos, diagramas, códigos, casos de teste e outros).

Tendo diferentes elos associados a eles, presentes nos slides da Professora Milene, Requisitos - Aula 26[1]:

* **Satisfação**: Classe origem tem dependência de satisfação com a classe destino.
* **Recurso**: Classe origem tem dependência de recurso com a classe destino.
* **Responsabilidade**: Registra a participação, responsabilidade e ação de pessoas sobre artefatos.
* **Representação**: Captura a representação ou modelagem dos requisitos em outras linguagens.
* **Alocado**: Classe origem está relacionada à classe destino, representando um subsistema.
* **Agregação**: Composição de elementos.

## Requisitos Funcionais
Dessa foram, a tabela 2 apresenta todos os requisitos funcionais com sua rastreabilidade.

<center>

|  ID  | Requisito | Rastreabilidade | Elo |
|:----:|-----------|:---------------:|:---:|
| RF01 | O aplicativo deve permitir que os usuários visualizem as faturas dos pagamentos | INT03 </br> Q01 </br> Q03 </br> ST04 | <a href="#1">EF 01</a> |
| RF02 | O aplicativo deve permitir a emissão de notificações sobre informações relevantes ao usuário | INT04 </br> Q02 </br> Q11 </br> ST01 | <a href="#2">EF 02</a> |
| RF03 | O aplicativo deve permitir que o usuário pague suas contas de água utilizando cartão de crédito ou débito | INT05 </br> Q04 </br> ST05 | <a href="#3">EF 03</a> |
| RF04 | O aplicativo deve permitir que o usuário copie o código do boleto | Q05 | <a href="#4">EF 04</a> |
| RF05 | O usuário deve possuir uma forma de pagamento por cartão que seja automática | Q06 | <a href="#5">EF 05</a> |
| RF06 | A possibilidade de se utilizar cadastros de outras casas, podendo haver, por exemplo, um sistema de troca de contas | Q08 | <a href="#6">EF 06</a> |
| RF07 | O usuário deve poder solicitar serviço (CRU) | Q09 | <a href="#7">EF 07</a> |
| RF08 | O usuário deve poder acessar sua conta por meio de sua impressão digital previamente cadastrada | Q10 | <a href="#8">EF 08</a> |
| RF09 | O aplicativo deve apresentar uma divisão clara de seções | Q12 | <a href="#9">EF 09</a> |
| RF10 | O aplicativo deve padronizar todos os itens que aparecem nas suas seções | Q13 | <a href="#10">EF 10</a> |
| RF11 | Deve se ter mais detalhe e clareza com relação aos protocolos e serviços | Q14 | <a href="#11">EF 11</a> |
| RF12 | Apresentar quando que ocorrerá uma próxima leitura | Q15 | <a href="#12">EF 12</a> |
| RF13 | O aplicativo deve informar o motivo para a qualidade de banho em uma área do lago não ser a ideal | Q16 | <a href="#13">EF 13</a> |
| RF14 | O usuário deve poder informar sobre vazamentos| Q17 | <a href="#14">EF 14</a> |
| RF15 | O aplicativo deve permitir que os usuários se registrem para criar uma conta | INT01 | <a href="#15">EF 15</a> |
| RF16 | O aplicativo deve permitir que os usuários visualizem o historico de consumo de água | INT02 </br> ST04 | <a href="#16">EF 16</a> |
| RF17 | O aplicativo deve permitir que o usuário pague suas contas de água utilizando chave pix | INT06 </br> ST05 | <a href="#17">EF 17</a> |
| RF18 | O aplicativo deve permitir que os usuários entrem em contato com a equipe de suporte da CAESB para resolver problemas e fazer perguntas | INT07 </br> ST06 | <a href="#18">EF 18</a> |
| RF19 | O aplicativo deve permitir que os usuários gerem relatórios detalhados sobre seu consumo de água e os custos associados ao consumo | INT08 </br> ST02 | <a href="#19">EF 19</a> |
| RF20 | O aplicativo deve permitir que os usuários alterem as informações cadastradas no sistema | INT09 | <a href="#20">EF 20</a> |
| RF21 | O aplicativo deve permitir que os usuários visualizem um histórico detalhado dos serviços solicitados | INT10 | <a href="#21">EF 21</a> |

<p>Tabela 2 - Requisitos Funcionais. (Fonte: Autor, 2023)</p>

</center>

### Elos -  Requisitos Funcionais
A seguir se tem a categorização dos Elos dos requisitos fucnionais:

#### EF - 01
<div id="1"></div>

**Categoria**: Desenvolvimento

**Elementos Rastreáveis**:

* RF01:

    * Introspecção: INT03
    * Questionário: Q01 e Q03
    * Storytelling: ST04 

**Elos**: 

* Agregação: Q01, Q03 e ST04 agrega INT03

</br>

#### EF - 02
<div id="2"></div>

**Categoria**: Gerencial

**Elementos Rastreáveis**:

* RF02:

    * Introspecção: INT04
    * Questionário: Q02 e Q11
    * Storytelling: ST01

**Elos**: 

* Agregação: Q02, Q11 e ST01 agrega INT04
* Representação: Q02 representa ST01

</br>

#### EF - 03
<div id="3"></div>

**Categoria**: Desenvolvimento

**Elementos Rastreáveis**:

* RF03:

    * Introspecção: INT05
    * Questionário: Q04
    * Storytelling: ST05

**Elos**: 

* Agregação: INT05 e Q04 agrega ST05

</br>

#### EF - 04
<div id="4"></div>

**Categoria**: 

**Elementos Rastreáveis**:

* RF04:

    * Questionário: Q05

**Elos**: 

* Sem outros requisitos para moldar elo.

</br>

#### EF - 05
<div id="5"></div>

**Categoria**: 

**Elementos Rastreáveis**:

* RF05:

    * Questionário: Q06

**Elos**: 

* Sem outros requisitos para moldar elo.

</br>

#### EF - 06
<div id="6"></div>

**Categoria**: Organizacional

**Elementos Rastreáveis**:

* RF06:

    * Questionário: Q08

**Elos**: 

* Sem outros requisitos para moldar elo.

</br>

#### EF - 07
<div id="7"></div>

**Categoria**: Desenvolvimento

**Elementos Rastreáveis**:

* RF07:

    * Questionário: Q09

**Elos**: 

* Sem outros requisitos para moldar elo.

</br>

#### EF - 08
<div id="8"></div>

**Categoria**: Desenvolvimento

**Elementos Rastreáveis**:

* RF08:

    * Questionário: Q10

**Elos**: 

* Sem outros requisitos para moldar elo.

</br>

#### EF - 09
<div id="9"></div>

**Categoria**: Desenvolvimento

**Elementos Rastreáveis**:

* RF09:

    * Questionário: Q12

**Elos**: 

* Sem outros requisitos para moldar elo.

</br>

#### EF - 10
<div id="10"></div>

**Categoria**: Organizacional

**Elementos Rastreáveis**:

* RF10:

    * Questionário: Q13

**Elos**: 

* Sem outros requisitos para moldar elo.

</br>

#### EF - 11
<div id="11"></div>

**Categoria**: Organizacional

**Elementos Rastreáveis**:

* RF11:

    * Questionário: Q14

**Elos**: 

* Sem outros requisitos para moldar elo. 

</br>

#### EF - 12
<div id="12"></div>

**Categoria**: Desenvolvimento

**Elementos Rastreáveis**:

* RF12:

    * Questionário: Q15

**Elos**: 

* Sem outros requisitos para moldar elo. 

</br>

#### EF - 13
<div id="13"></div>

**Categoria**: Ambiental

**Elementos Rastreáveis**:

* RF13:

    * Questionário: Q16


**Elos**: 

* Sem outros requisitos para moldar elo. 

</br>

#### EF - 14
<div id="14"></div>

**Categoria**: Desenvolvimento

**Elementos Rastreáveis**:

* RF14:

    * Questionário: Q17

**Elos**: 

* Sem outros requisitos para moldar elo. 

</br>

#### EF - 15
<div id="15"></div>

**Categoria**: Desenvolvimento

**Elementos Rastreáveis**:

* RF15:

    * Introspecção: INT01

**Elos**: 

* Sem outros requisitos para moldar elo. 

</br>

#### EF - 16
<div id="16"></div>

**Categoria**: Desenvolvimento

**Elementos Rastreáveis**:

* RF16:

    * Introspecção: INT02
    * Storytelling: ST04

**Elos**: 

* Agregação: INT02 agrega ST04

</br>

#### EF - 17
<div id="17"></div>

**Categoria**: Desenvolvimento

**Elementos Rastreáveis**:

* RF17:

    * Introspecção: INT06
    * Storytelling: ST05

**Elos**: 

* Agregação: INT06 agrega ST05

</br>

#### EF - 18
<div id="18"></div>

**Categoria**: Desenvolvimento

**Elementos Rastreáveis**:

* RF18:

    * Introspecção: INT07
    * Storytelling: ST06

**Elos**: 

* Representação: INT07 representa ST06

</br>

#### EF - 19
<div id="19"></div>

**Categoria**: Gerencial

**Elementos Rastreáveis**:

* RF19:

    * Introspecção: INT08
    * Storytelling: ST02

**Elos**: 

* Agregação: ST02 agrega INT08

</br>

#### EF - 20
<div id="10"></div>

**Categoria**: Desenvolvimento

**Elementos Rastreáveis**:

* RF20:

    * Introspecção: INT09

**Elos**: 

* Sem outros requisitos para moldar elo. 

</br>

#### EF - 21
<div id="21"></div>

**Categoria**: Desenvolvimento

**Elementos Rastreáveis**:

* RF21:

    * Introspecção: INT10

**Elos**: 

* Sem outros requisitos para moldar elo. 


## Requisitos Não Funcionais
Dessa foram, a tabela 3 apresenta todos os requisitos não funcionais com sua rastreabilidade.

<center>

|   ID  | Requisito | Rastreabilidade | Elo |
|:-----:|-----------|:---------------:|:---:|
| RNF01 | O aplicativo deve seguir as diretrizes de acessibilidade da WACG 2.1 [2], garantindo que seja acessível para pessoas com deficiência visual, auditiva ou física. | INT14 </br> Q07 |  <a href="#22">ENF 01</a>  |
| RNF02 | O aplicativo deve ser capaz de lidar com pelo menos 150.000 usuários simultâneos sem comprometer o desempenho ou a segurança | INT11 </br> ES11 |  <a href="#23">ENF 02</a>  |
| RNF03 | O aplicativo deve ter uma taxa de disponibilidade de pelo menos 99% durante o horário comercial | INT12 </br> ES05 |  <a href="#24">ENF 03</a>  |
| RNF04 | O aplicativo deve ter um procedimento de manutenção que permita que o tempo de inatividade seja limitado a no máximo 10 horas por mês. | INT13 |  <a href="#25">ENF 04</a>  |
| RNF05 | O aplicativo deve permitir que os usuários escolham entre pelo menos 3 idiomas diferentes | INT15 |  <a href="#26">ENF 05</a>  |
| RNF06 | O aplicativo deve ser atualizado frequentemente para garantir a correção de erros, melhorias de desempenho e novos recursos. | INT16 |  <a href="#27">ENF 06</a>  |
| RNF07 | O aplicativo deve funcionar perfeitamente em todos os dispositivos, incluindo computadores. | INT17 |  <a href="#28">ENF 07</a>  |
| RNF08 | Eu, como usuario, desejo que o aplicativo garanta a segurança das minhas informações pessoais e financeiras | ST03 |  <a href="#29">ENF 08</a>  |
| RNF09 | Eu, como usuário, desejo que o tempo necessário para realizar tarefas seja menor que 1 minuto | ST07 |  <a href="#30">ENF 09</a>  |
| RNF10 | Eu, como usuário, desejo que a quantidade de passos para realizar uma tarefa seja menor que 3 | ST08 |  <a href="#31">ENF 10</a>  |
| RNF11 | A interface do usuário deve ser intuitiva e de fácil navegação, considerando o perfil diversificado dos usuários. | ES01 |  <a href="#32">ENF 11</a>  |
| RNF12 | O aplicativo deve fornecer feedback claro e mensagens de erro compreensíveis em caso de problemas. | ES02 |  <a href="#33">ENF 12</a>  |
| RNF13 | O tempo médio de treinamento para que usuários normais se tornem produtivos em operações básicas do aplicativo não deve exceder 1 hora. | ES03 |  <a href="#34">ENF 13</a>  |
| RNF14 | O tempo médio para que um usuário solicite a segunda via de uma fatura através do aplicativo deve ser menor que 30 segundos. | ES04 |  <a href="#35">ENF 14</a>  |
| RNF15 | O MTBF(Mean Time Between Failures) do aplicativo deve ser de pelo menos 170 horas, o que significa que o sistema deve operar continuamente, em média, por pelo menos 170 horas antes de ocorrer uma falha. | ES06 |  <a href="#36">ENF 15</a>  |
| RNF16 | O MTTR(Mean Time To Repair) do aplicativo que é o tempo máximo permitido para reparo de uma falha do sistema deve ser de 4 horas, ou seja, o sistema deve ser restaurado dentro desse período após uma falha. | ES07 |  <a href="#37">ENF 16</a>  |
| RNF17 | A precisão das informações exibidas nas faturas dos usuários deve ter uma resolução mínima de 2 casas decimais e estar de acordo com as normas contábeis. | ES08 |  <a href="#38">ENF 17</a>  |
| RNF18 | O tempo médio de resposta para o processamento de uma transação no aplicativo não deve exceder 3 segundos. | ES09 |  <a href="#39">ENF 18</a>  |
| RNF19 | O aplicativo deve suportar uma taxa mínima de processamento de 100 transações por segundo para atender à demanda dos usuários. | ES10 |  <a href="#40">ENF 19</a>  |
| RNF20 | Quando houver uma queda na conexão de internet do usuário, o aplicativo deve ser capaz de fornecer um modo de degradação, permitindo a execução de funções básicas offline, como visualização de faturas anteriores. | ES12 |  <a href="#41">ENF 20</a>  |
| RNF21 | O aplicativo deve ser otimizado para minimizar o consumo de memória, garantindo um uso eficiente dos recursos do dispositivo do usuário. | ES13 |  <a href="#42">ENF 21</a>  |
| RNF22 | O código do aplicativo deve ser desenvolvido de acordo com as diretrizes do padrão de codificação definido pela equipe de desenvolvimento da CAESB. | ES14 |  <a href="#43">ENF 22</a>  |
| RNF23 | O aplicativo deve estar disponível para o Android na versão 5.0 | ES15 |  <a href="#44">ENF 23</a>  |
| RNF24 | O aplicativo deve estar disponível para o IOS na versão 12.0 | ES16 |  <a href="#45">ENF 24</a>  |

<p>Tabela 3 - Requisitos não Funcionais. (Fonte: Autor, 2023)</p>

</center>

### Elos -  Requisitos Não Funcionais
A seguir se tem a categorização dos Elos dos requisitos Não fucnionais:

#### ENF - 01
<div id="22"></div>

**Categoria**: Organizacional

**Elementos Rastreáveis**:

* RNF01:

    * Introspecção: INT14
    * Questionário: Q07

**Elos**: 

* Representação: Q07 representa INT14

</br>

#### ENF - 02
<div id="23"></div>

**Categoria**: Gerencial

**Elementos Rastreáveis**:

* RNF02:

    * Introspecção: INT11
    * Especificação Suplementar: ES11

**Elos**: 

* Representação: ES11 representa INT11

</br>

#### ENF - 03
<div id="24"></div>

**Categoria**: Gerencial

**Elementos Rastreáveis**:

* RNF03:

    * Introspecção: INT12
    * Especificação Suplementar: ES05

**Elos**: 

* Representação: ES05 representa INT12

</br>

#### ENF - 04
<div id="25"></div>

**Categoria**: Organizacional

**Elementos Rastreáveis**:

* RNF04:

    * Introspecção: INT13

**Elos**: 

* Sem outros requisitos para moldar elo. 

</br>

#### ENF - 05
<div id="26"></div>

**Categoria**: Desenvolvimento

**Elementos Rastreáveis**:

* RNF05:

    * Introspecção: INT15

**Elos**: 

* Sem outros requisitos para moldar elo. 

</br>

#### ENF - 06
<div id="27"></div>

**Categoria**: Desenvolvimento

**Elementos Rastreáveis**:

* RNF06:

    * Introspecção: INT16

**Elos**: 

* Sem outros requisitos para moldar elo. 

</br>

#### ENF - 07
<div id="28"></div>

**Categoria**: Desenvolvimento

**Elementos Rastreáveis**:

* RNF07:

    * Introspecção: INT17

**Elos**: 

* Sem outros requisitos para moldar elo. 

</br>

#### ENF - 08
<div id="29"></div>

**Categoria**: Organizacional

**Elementos Rastreáveis**:

* RNF08:

    * Storytelling:  ST03

**Elos**: 

* Sem outros requisitos para moldar elo. 

</br>

#### ENF - 09
<div id="30"></div>

**Categoria**: Desenvolvimento

**Elementos Rastreáveis**:

* RNF09:

    * Storytelling:  ST07

**Elos**: 

* Sem outros requisitos para moldar elo. 

</br>

#### ENF - 10
<div id="31"></div>

**Categoria**: Desenvolvimento

**Elementos Rastreáveis**:

* RNF10:

    * Storytelling:  ST08

**Elos**: 

* Sem outros requisitos para moldar elo. 

</br>

#### ENF - 11
<div id="32"></div>

**Categoria**: Organizacional

**Elementos Rastreáveis**:

* RNF11:

    * Especificação Suplementar: ES01

**Elos**: 

* Sem outros requisitos para moldar elo. 

</br>

#### ENF - 12
<div id="33"></div>

**Categoria**: Gerencial

**Elementos Rastreáveis**:

* RNF12:

    * Especificação Suplementar: ES02

**Elos**: 

* Sem outros requisitos para moldar elo. 

</br>

#### ENF - 13
<div id="34"></div>

**Categoria**: Gerencial

**Elementos Rastreáveis**:

* RNF13:

    * Especificação Suplementar: ES03

**Elos**: 

* Sem outros requisitos para moldar elo. 

</br>

#### ENF - 14
<div id="35"></div>

**Categoria**: Gerencial

**Elementos Rastreáveis**

* RNF14:

    * Especificação Suplementar: ES04

**Elos**: 

* Sem outros requisitos para moldar elo. 

</br>

#### ENF - 15
<div id="36"></div>

**Categoria**: Gerencial

**Elementos Rastreáveis**:

* RNF15:

    * Especificação Suplementar: ES06

**Elos**: 

* Sem outros requisitos para moldar elo. 

</br>

#### ENF - 16
<div id="37"></div>

**Categoria**: Gerencial

**Elementos Rastreáveis**:

* RNF16:

    * Especificação Suplementar: ES07

**Elos**: 

* Sem outros requisitos para moldar elo. 

</br>

#### ENF - 17
<div id="38"></div>

**Categoria**: Gerencial

**Elementos Rastreáveis**:

* RNF17:

    * Especificação Suplementar: ES07

**Elos**: 

* Sem outros requisitos para moldar elo. 

</br>

#### ENF - 18
<div id="39"></div>

**Categoria**: Gerencial

**Elementos Rastreáveis**:

* RNF18:

    * Especificação Suplementar: ES08

**Elos**: 

* Sem outros requisitos para moldar elo. 

</br>

#### ENF - 19
<div id="40"></div>

**Categoria**: Desenvolvimento

**Elementos Rastreáveis**:

* RNF19:

    * Especificação Suplementar: ES10

**Elos**: 

* Sem outros requisitos para moldar elo. 

</br>

#### ENF - 20
<div id="41"></div>

**Categoria**: Desenvolvimento

**Elementos Rastreáveis**:

* RNF20:

    * Especificação Suplementar: ES12

**Elos**: 

* Sem outros requisitos para moldar elo. 

</br>

#### ENF - 21
<div id="42"></div>

**Categoria**: Desenvolvimento

**Elementos Rastreáveis**:

* RNF21:

    * Especificação Suplementar: ES13

**Elos**: 

* Sem outros requisitos para moldar elo. 

</br>

#### ENF - 22
<div id="43"></div>

**Categoria**: Desenvolvimento

**Elementos Rastreáveis**:

* RNF22:

    * Especificação Suplementar: ES14

**Elos**: 

* Sem outros requisitos para moldar elo. 

</br>

#### ENF - 23
<div id="44"></div>

**Categoria**: Desenvolvimento

**Elementos Rastreáveis**:

* RNF23:

    * Especificação Suplementar: ES15

**Elos**: 

* Sem outros requisitos para moldar elo. 

</br>

#### ENF - 24
<div id="45"></div>

**Categoria**: Desenvolvimento

**Elementos Rastreáveis**:

* RNF24:

    * Especificação Suplementar: ES16

**Elos**: 

* Sem outros requisitos para moldar elo. 



## Referência Bibliográfica

> [1] Slides - Requisitos - Aula 26 - Milene Serrano e Maurício Serrano

> [2] Diretrizes de Acessibilidade - https://www.w3c.br/traducoes/wcag/wcag21-pt-BR/

## Bibliografia

> Slides - Requisitos - Aula 26 - Milene Serrano e Maurício Serrano

> Diretrizes de Acessibilidade - https://www.w3c.br/traducoes/wcag/wcag21-pt-BR/

> SAYÃO, Mirian; LEITE, Julio C. S. P. Rastreabilidade de Requisitos - Monografias em Ciência da Computação n° 20/05

## Histórico de Versão

| Data | Data Prevista de Revisão | Versão | Descrição | Autor | Revisor |
| :--: | :--: | :--: | :--: | :--: | :--: |
| 28/06/2023 | 28/06/2023 |  1.0   | Criação do documento | [Daniel](https://github.com/daniel-de-sousa) | [Pedro](https://github.com/pedrobarbosaocb) |