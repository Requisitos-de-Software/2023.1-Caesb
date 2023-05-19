# Léxicos

## Introdução

A técnica de léxico consiste em descrever os símbolos e termos específicos de uma aplicação. Busca-se identificar frases e símbolos relevantes, descrevendo-os com uma **noção** (significado/conceito) e um **impacto** (efeito na aplicação).
## Metodologia
Os léxicos foram identificados a partir dos requisitos [elicitados](), [priorizados](), e pelo uso do aplicativo.E a sua descrição segue o **vocabulário mínimo** estabelecendo relações entre os termos e utilizando um conjunto reduzido de palavras objetivas. 

Além disso, damos um **sinônimo** para os léxicos, auxiliando no entendimento e evitando ambiguidade. É importante, também, classificar o léxico em **estado, objeto ou modelo**, respectivamente um seria uma condição/forma da aplicação, o outro uma informação e o último uma ação que o software realizará, provavelmente sobre determinado objeto.

Dessa forma, a construção de todos os léxicos seguirá a estrutura apresentada como exemplo na tabela 1.

**L0X** _-> número do léxico, seguindo a ordem de maior relevância/priorização_

| Léxico | Sinônimos | Noção | Impacto | Classificação |
| --- | --- | --- | --- | --- |
| Nome do léxico | Sinônimos do léxico no contexto | Noções do léxico | Impacto do léxico na aplicação | Classificação do léxico (estado, objeto ou verbo) |

<p align="center">Tabela 1: Exemplo de léxico (Fonte: Autor, 2023)</p>

## Léxicos
<style>
  .etiqueta-container {
    /* display: flex;
    flex-wrap: wrap; */
    justify-content: space-between;
    column-count: 5;

  }
  
  .etiqueta {
    background-color: white;
    border: 2px solid rgba(0, 0, 255, 0.8);
    border-radius: 20px;
    box-shadow: 1px 1px 3px rgba(0, 0, 139, 0.1);
    padding: 5px;
    width: 125px;
    margin-bottom: 10px;
    text-align: center;
    font-size: 13px;
    font-weight: bold;
    display: block;
  }
  
  .etiqueta a {
    color: blue;
    text-decoration: none;
  }
</style>

<div class="etiqueta-container">
  <a class="etiqueta" href="#L03">Acessibilidade</a>
  <a class="etiqueta" href="#L19">Alterar Idioma</a>
  <a class="etiqueta" href="#L05">Cadastro</a>
  <a class="etiqueta" href="#L12">Compreensão</a>
  <a class="etiqueta" href="#L10">Consumo</a>
  <a class="etiqueta" href="#L15">Contatar Suporte</a>
  <a class="etiqueta" href="#L02">Consultar</a>
  <a class="etiqueta" href="#L13">Desempenho</a>
  <a class="etiqueta" href="#L14">Disponibilidade</a>
  <a class="etiqueta" href="#L17">Editar dados</a>
  <a class="etiqueta" href="#L01">Fatura</a>
  <a class="etiqueta" href="#L18">Idioma</a>
  <a class="etiqueta" href="#L06">Informar</a>
  <a class="etiqueta" href="#L16">Multiplataforma</a>
  <a class="etiqueta" href="#L07">Notificar</a>
  <a class="etiqueta" href="#L11">Pagamento</a>
  <a class="etiqueta" href="#L09">Pagar</a>
  <a class="etiqueta" href="#L08">Segurança</a>
  <a class="etiqueta" href="#L04">Solicitar Serviço</a>
</div>

### <div id="L01">L01 - Fatura</div>

| Léxico | Sinônimos | Noção | Impacto | Classificação |
| --- | --- | --- | --- | --- |
| Fatura  | Conta | Documento com as informações do serviço da Caesb e solicitação de pagamento | O usuário tem acesso ao documento digital | Objeto |
<p align="center">Tabela 2: Léxico 01 (Fonte: Autor, 2023)</p>


### <div id="L02">L02 - Consultar </div>

| Léxico | Sinônimos | Noção | Impacto | Classificação |
| --- | --- | --- | --- | --- |
| Consultar  | Acessar | O que o usuário precisa fazer para ter a fatura, análise de consumo, etc. | Ter acesso as funcionalidades do aplicativo | Verbo |
<p align="center">Tabela 3: Léxico 02 (Fonte: Autor, 2023)</p>

### <div id="L03">L03 - Acessibilidade </div>

| Léxico | Sinônimos | Noção | Impacto | Classificação |
| --- | --- | --- | --- | --- |
| Acessibilidade | Inclusão | Forma que as informções do aplicativo são disponibilizadas | Permite o uso de todos os usuários | Estado |
<p align="center">Tabela 4: Léxico 03 (Fonte: Autor, 2023)</p>

### <div id="L04">L04 - Solicitar Serviço</div>

| Léxico | Sinônimos | Noção | Impacto | Classificação |
| --- | --- | --- | --- | --- |
| Solicitar serviço  | Demandar | Fazer um chamado a Caesb de determinado serviço | Permite a agilidade para demandar um serviço | Verbo |
<p align="center">Tabela 5: Léxico 04 (Fonte: Autor, 2023)</p>

### <div id="L05">L05 - Cadastro </div>

| Léxico | Sinônimos | Noção | Impacto | Classificação |
| --- | --- | --- | --- | --- |
| Cadastro | Dados pessoais | Dados dos usuários e residência | Permite associar um usuário a uma ou mais residências com contas | Estado |
<p align="center">Tabela 6: Léxico 05 (Fonte: Autor, 2023)</p>

### <div id="L06">L06 - Informar </div>

| Léxico | Sinônimos | Noção | Impacto | Classificação |
| --- | --- | --- | --- | --- |
| Informar | Relatar | Informar pelo aplicativo vazamentos | Permite a agilidade no processo | Verbo |
<p align="center">Tabela 7: Léxico 06 (Fonte: Autor, 2023)</p>

### <div id="L07">L07 - Notificar </div>

| Léxico | Sinônimos | Noção | Impacto | Classificação |
| --- | --- | --- | --- | --- |
| Notificar | Avisar | Alertas que o usuário recebe com base em determinados gatilhos no sistema | Sistema mais interativo | Verbo |
<p align="center">Tabela 8: Léxico 07 (Fonte: Autor, 2023)</p>


### <div id="L08">L08 - Segurança </div>

| Léxico | Sinônimos | Noção | Impacto | Classificação |
| --- | --- | --- | --- | --- |
| Segurança | Confiança | Proteção dos dados do usuário | Garante que os dados não serão vazados, ou interceptados. Gera confiança ao usuário. | Estado |
<p align="center">Tabela 9: Léxico 08 (Fonte: Autor, 2023)</p>


### <div id="L09">L09 - Pagar </div>

| Léxico | Sinônimos | Noção | Impacto | Classificação |
| --- | --- | --- | --- | --- |
| Pagar | Debitar | Pagar diretamente pelo aplicativo a conta, ai inves de apenas acessar a conta | Permite a agilidade no processo | Verbo |
<p align="center">Tabela 10: Léxico 09 (Fonte: Autor, 2023)</p>


### <div id="L10">L10 - Consumo </div>

| Léxico | Sinônimos | Noção | Impacto | Classificação |
| --- | --- | --- | --- | --- |
| Consumo | Gastos | Maior detalhe do consumo dos meses | Permite que o usuário visualize melhor e análise seu consumo | Objeto |
<p align="center">Tabela 11: Léxico 10 (Fonte: Autor, 2023)</p>


### <div id="L11">L11 - Pagamento </div>

| Léxico | Sinônimos | Noção | Impacto | Classificação |
| --- | --- | --- | --- | --- |
| Pagamento | Opções de pagamento | Formas de pagamento diversificadas | Permite a escolha da melhor forma de pagamento pelo usuário | Objetos |
<p align="center">Tabela 12: Léxico 11 (Fonte: Autor, 2023)</p>


### <div id="L12">L12 - Compreensão </div>

| Léxico | Sinônimos | Noção | Impacto | Classificação |
| --- | --- | --- | --- | --- |
| Compreensão | Objetividade | App direto sobre a informação | Faciliade no uso | Estado |
<p align="center">Tabela 13: Léxico 12 (Fonte: Autor, 2023)</p>


### <div id="L13">L13 - Desempenho </div>

| Léxico | Sinônimos | Noção | Impacto | Classificação |
| --- | --- | --- | --- | --- |
| Desempenho | Velocidade | Rapidez na navegação do App | Agilidade na hora de acessar uma tarefa e satisfação | Estado |
<p align="center">Tabela 14: Léxico 13 (Fonte: Autor, 2023)</p>

### <div id="L14">L14 - Disponibilidade </div>

| Léxico | Sinônimos | Noção | Impacto | Classificação |
| --- | --- | --- | --- | --- |
| Disponibilidade | Prontidão | Sistema se mantém mesmo em horários críticos (dias da semana e final de mês) | Agilidade nos processos e satisfação | Estado |

<p align="center">Tabela 15: Léxico 14 (Fonte: Autor, 2023)</p>


### <div id="L15">L15 - Contatar suporte</div>

| Léxico | Sinônimos | Noção | Impacto | Classificação |
| --- | --- | --- | --- | --- |
| Contatar Suporte | Contatar  Assistência técnica | Pedir ajuda via suporte no aplicativo | Receber auxílio no uso do app | Verbo |
<p align="center">Tabela 16: Léxico 15 (Fonte: Autor, 2023)</p>


### <div id="L16">L16 - Multiplataforma</div>

| Léxico | Sinônimos | Noção | Impacto | Classificação |
| --- | --- | --- | --- | --- |
| Mutiplataforma | Adaptável | Compatibilidade com diversos dispositivos e plataformas | Melhor usabilidade em diferentes dispositivos | Estado |
<p align="center">Tabela 17: Léxico 16 (Fonte: Autor, 2023)</p>


### <div id="L17"> L17 - Editar dados</div>

| Léxico | Sinônimos | Noção | Impacto | Classificação |
| --- | --- | --- | --- | --- |
| Editar dados | Alterar | Alterar a titulatidade das casas associadas e dados do perfil | Permite a alteração de residência e perfil de forma menos burocrática | Verbo |
<p align="center">Tabela 18: Léxico 17 (Fonte: Autor, 2023)</p>


### <div id="L18">L18 - Idioma</div>

| Léxico | Sinônimos | Noção | Impacto | Classificação |
| --- | --- | --- | --- | --- |
| Idioma | Língua | Opções de diferentes idiomas | Acessével a estrangeiros  | Estado |
<p align="center">Tabela 19: Léxico 18 (Fonte: Autor, 2023)</p>


### <div id="L19">L19 - Alterar Idioma</div>

| Léxico | Sinônimos | Noção | Impacto | Classificação |
| --- | --- | --- | --- | --- |
| Alterar Idioma | Alterar Língua | Permite a troca de idioma no site | Torna acessível a estrangeiros  | Estado |

<p align="center">Tabela 20: Léxico 19 (Fonte: Autor, 2023)</p>


## Bibliografia

[1] Barbosa, S. D. J.; Silva, B. S. da; Silveira, M. S.; Gasparini, I.; Darin, T.; Barbosa, G. D. J. (2021) *Interação Humano-Computador e Experiência do usuário*. Autopublicação. ISBN: 978-65-00-19677-1.

## Histórico de versões

|Data|Data Prevista de Revisão|Versão|Descrição|Autor|Revisor|
|-----|------|-----|-----|-----|-----|
| 12/05/2023 |        13/05/2023        |  1.0   | Criação do documento | [Raquel](https://github.com/raqueleucaria) | [Caetano](https://github.com/caeslucio)   |
| 17/05/2023 |        18/05/2023        |  2.0   | Ajuste do style | [Raquel](https://github.com/raqueleucaria) | [Pedro](https://github.com/pedrobarbosaocb)   |