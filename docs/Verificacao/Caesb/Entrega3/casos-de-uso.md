# Casos de Uso

## Introdução

Segundo a norma internacional ISO/IEC/IEEE 12207:2017(E) (ISO/IEC/IEEE, 2017, p. 82) [[1]()], o objetivo da verificação se define em "prover evidência objetiva que o sistema ou elemento do sistema atende completamente seus requisitos e características especificados". Com isso, afim de garantir qualidade e consistência dos requisitos, realizaremos a verificação dos documentos do nosso grupo, [Caesb](https://requisitos-de-software.github.io/2023.1-Caesb/)[[2]()], da disciplina Requisitos de Software.

## Objetivos
O objetivo deste documento é realizar a verificação do Casos de Uso, artefato da Entrega 3, do Grupo 4, [Caesb](https://requisitos-de-software.github.io/2023.1-Caesb/). De forma impessoal, este documento não deseja avaliar os membros do grupo, mas o artefato em si.

## Metodologia
Como método de investigação e produção da verificação, utilizaremos a inspeção, mais especificamente a _Fagan Inspection_. Na qual, segundo Bush [[3]()], consiste na "inspeção de documentos entendidos como prontos para uso e busca por defeitos". Seguindo as etapas de planejamento, visão geral, preparação, inspecção e correção. Maiores detalhes de planejamento, estão apresentados no [Planejamento da Entrega 3](./0planejamento.md).

## Verificações anteriores
Uma das atividades da disciplina de Requisitos de Software, ministrada pelo professor André Barros, é realizar a verificação do projeto de outro grupo. A nossa verificação foi feita sobre o Casos de Uso do grupo 5 ([SimpleNote](../../Grupo5/Entrega3/casos-de-uso.md)). E o grupo 3 ([VLC](https://github.com/Requisitos-de-Software/2023.1-VLC/blob/master/docs/verificacao/entrega_3/verificacao_casos-de-uso.md)), fez a inspeção do nosso projeto, da Caesb.

Dessa forma, reavaliamos nosso checklist, levando em conta os pontos levantados pelo grupo 3, mas principalmente baseando-se nas literaturas de referência. Assim, um novo checklist foi criado para a avaliação da nossa própria introspecção.

## Checklist
<!-- LIVRO BASE PARA CRIAÇÃO DAS PERGUNTAS -->
O checklist foi estabelecido com base nos critérios propostos nos slide da professora Milene sobre Modelagem de Requisitos[[4]()] e no livro de Engenharia de Requisitos[[5]()]. Seguindo as perguntas padrões estabelecidas pelo grupo no [Planejamento Geral](../0planejamento-geral.md), está apresentado na Tabela 1, o checklist do Casos de Uso.



<!-- ADICIONAR O CHECKLIST -->

<center>

| ID| Descrição | Avaliação | Observação | 
|---|---|---|---|
| 1 | O artefato possui uma introdução condizente com o conteúdo do texto? |Incompleto| Muito simples| 
| 2 | Todas as bibliografias/referências bibliográficas são utilizadas de forma correta? |Não|Uso incorreto| 
| 3 | Todas as tabelas e figuras são chamadas no texto, possuem legendas e fontes? | Sim |-| 
| 4 | A metodologia esta de acordo com o artefato analisado? <a href="#1">¹</a> | Incompleto | Esta de acordo, porém poderia melhorar a organização do documento |
| 5| Os casos de uso estão associados a requisitos de usuário ou histórias de usuário específicas?  | Não | Não está explicitado | 
| 6| A caixa de limite do sistema delimitando o escopo dos casos de uso?  <a href="#2">²</a>  | Sim |  -  |
| 7 | Os atores que interagem com o sistema são identificados corretamente? <a href="#3">²</a> | Sim | - |
| 8 | Os atores são representados corretamente? <a href="#4">³</a> | Sim | - |
| 9 | Os casos de uso são identificados corretamente? <a href="#5">⁵</a> | Sim | - |
| 10 | Os casos de uso são representados corretamente? <a href="#6">⁶</a> | Sim | - |
| 11 |Os relacionamentos de associação entre atores e casos de uso estão corretos? <a href="#7">⁷</a> | Sim | - |
| 12 | Na especificação, os pré-requisitos estão definidos? <a href="#8">⁸</a>  | Sim | - |
| 13 | Na especificação, as condições de entrada e saída estão especificadas? |  Sim   |  -    |
| 14 | O artefato contém legendas claras para cada símbolo utilizado no diagrama de casos de uso?  | Incompleto |  Falta os de include e extend   |
| 15| Os casos de uso foram validados?  | Sim | Por persona | 


<p>Tabela 1 - Checklist do Casos de Uso (Fonte: Autores)</p>
</center>

<div id="1"></div>
[¹]() Explicação do uso da metodologia esta de acordo com o objetivo.
<div id="2"></div>
[²]() A caixa de limite do sistema é representada como retângulo que delimita a fronteira do sistema.
<div id="3"></div>
[³]()  Atores primários são as pessoas, organizações ou sistema externo que interage ao sistema, e atores secundários são as pessoa, organização ou sistema externo que reaje ao sistema.
<div id="4"></div>
[⁴]()  Os atores devem ficar fora da caixa de limite do sistema, os principais devem ficar a esquerda e os secundários a direita. Além disso, deve ser nomeado o ator (ex: usuário). E devem estar  na forma de bonecos de palito.
<div id="5"></div>
[⁵]()  Os casos de uso representam as funcionalidades do sistema, assim é preciso identificar se as funcionalidades representadas estão de acordo com o projeto. Além disso, devem ser rotulados com verbos (no infinitivo) e descrições simples.
<div id="6"></div>
[⁶]()  Os casos de uso devem ficar dentro do limite do sistema, e devem estar na forma de elipses (ovais).
<div id="7"></div>
[⁷]() Usando os relacionamentos de extend(caso de uso pode ser estendido por outro caso de uso em certas condições), include (caso de uso é incluído em outro caso de uso).
<div id="8"></div>
[⁸]() Pré-requisitos são as condições que devem ser satisfeitas antes do caso de uso ser executado.

## Gráfico
Com base no checklist feito no processo de inspeção do Casos de Uso, foi produzido o gráfico de avaliação do artefato, que pode ser visualizado/analisado na Figura 1.
<center>
<img src="../../assets/img/casos.png"></img>
<p>Figura 1 - Gráfico do Casos de Uso (Fonte: Autores)</p>
</center>

## Correção
O planejamento e a situação da correção do artefatos, Casos de Uso, será registrado na Tabela 2. A data se refere ao período previsto para correção e revisão.
<center>

|ID |Descrição |Detalhes |Corretor|Revisor|Data|Status|
|-------|------|------|---------|---|--|--|
| 1 | Introdução | Complementar a introdução | [Raquel](https://github.com/raqueleucaria) |[Caetano](https://github.com/caeslucio)|24/06/2023 a 26/06/2023|-|
| 2 | Bibliografias/referências bibliográficas | Corrigir e acrescentar | [Raquel](https://github.com/raqueleucaria) | [Caetano](https://github.com/caeslucio)  |24/06/2023 a 26/06/2023|-|
| 4 | Metodologia | Melhorar a organização do documento | [Raquel](https://github.com/raqueleucaria) |[Caetano](https://github.com/caeslucio) |24/06/2023 a 26/06/2023|-|
| 5 | histórias de usuário  | Apresentar no documento| [Raquel](https://github.com/raqueleucaria) | [Caetano](https://github.com/caeslucio) |24/06/2023 a 26/06/2023|-|
| 14 | Legendas | Especificar as setas de relacionamento | [Raquel](https://github.com/raqueleucaria) |[Caetano](https://github.com/caeslucio) |24/06/2023 a 26/06/2023|-|



<p>Tabela 2 - Distribuição da Correção dos Artefatos (Fonte: Autores)</p>
</center>

### Atualização
As atualizações no processo de correção do Casos de Uso, são:

- Nenhuma
<!-- - xx/xx/xxxx - Correção da bibliográfia (ID 2) - Projeto 50% correto. -->

## Referência bibliográfica

> [1] ISO/IEC/IEEE 12207:2017(E) (ISO/IEC/IEEE, 2017, p. 82). Disponível em: <https://www.iso.org/obp/ui/#iso:std:iso-iec-ieee:24765:ed-2:v1:en> . Acesso em: 13 jun. 2023

> [2] CAESB, grupo 4. Disponível em <https://requisitos-de-software.github.io/2023.1-Caesb/> . Acesso em: 16 jun. 2023.

> [3] BUSH, Marilyn, Chris Gerrard, Clifford Shelley. Fagan Inspection: The Silver Bullet No-one Wants to Fire. London SPIN, 25 mar. 2010.

> [4] SERRANO, Milene, SERRANO, Maurício. Modelagem de Requisitos (Aula 13). UnB Gama, Brasília, 2023. Disponível no [link](../assets/referencias/RequisitosCasosdeUso.pdf.pdf).

> [5] REINEHR, Sheila. Engenharia de requisitos. [Digite o Local da Editora]: Grupo A, 2020. E-book. ISBN 9786556900674. Disponível em: <https://integrada.minhabiblioteca.com.br/#/books/9786556900674/>. Acesso em: 19 jun. 2023.


## Bibliografia

> Sommerville, Ian. Engenharia de software. 08. ed. São Paulo: Pearson Addison Wesley, 2007.

> SERRANO, Milene; SERRANO, Maurício. Análise de Requisitos (Aula 23). UnB Gama, Brasília, 2023. Disponível no [link](../assets/referencias/Requisitos%20-%20Aula%20023.pdf).

> WIEGERS, Karl; BEATTY, Joy. Software Requirements (Developer Best Practices). 3rd Edition. Microsoft Press, 2013. 

> REINEHR, Sheila. Engenharia de requisitos. [Digite o Local da Editora]: Grupo A, 2020. E-book. ISBN 9786556900674. Disponível em: <https://integrada.minhabiblioteca.com.br/#/books/9786556900674/>. Acesso em: 19 jun. 2023. 

> RIBEIRO, Bruno. Verificação do artefato de Casos de Uso do Grupo 4 (Caesb). Repositório do Grupo VLC da disciplina de Requisitos da Universidade de Brasília, 2023. Disponível em: <https://github.com/Requisitos-de-Software/2023.1-VLC/blob/master/docs/verificacao/entrega_3/verificacao_casos-de-uso.md>. Acesso em: 19 de Junho de 2023.


## Histórico de Versão
|    Data    | Data Prevista de Revisão | Versão |      Descrição       |                                 Autor                                  |               Revisor               |
| :--------: | :----------------------: | :----: | :------------------: | :--------------------------------------------------------------------: | :---------------------------------: |
| 19/06/2023 |        21/06/2023        |  1.0   | Criação do documento |  [Raquel Eucaria](https://github.com/raqueleucaria) | [Pedro](https://github.com/pedrobarbosaocb) |
