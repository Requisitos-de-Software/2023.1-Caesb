# In Or Out

## Introdução

Segundo a norma internacional ISO/IEC/IEEE 12207:2017(E) (ISO/IEC/IEEE, 2017, p. 82) [[1]()], o objetivo da verificação se define em "prover evidência objetiva que o sistema ou elemento do sistema atende completamente seus requisitos e características especificados". Com isso, afim de garantir qualidade e consistência dos requisitos, realizaremos a verificação dos documentos do nosso grupo, [Caesb](https://requisitos-de-software.github.io/2023.1-Caesb/)[[2]()], da disciplina Requisitos de Software.

## Objetivos
O objetivo deste documento é realizar a verificação do In Or Out, artefato da Entrega 2, do Grupo 4, [Caesb](https://requisitos-de-software.github.io/2023.1-Caesb/). De forma impessoal, este documento não deseja avaliar os membros do grupo, mas o artefato em si.

## Metodologia
Como método de investigação e produção da verificação, utilizaremos a inspeção, mais especificamente a _Fagan Inspection_. Na qual, segundo Bush [[3]()], consiste na "inspeção de documentos entendidos como prontos para uso e busca por defeitos". Seguindo as etapas de planejamento, visão geral, preparação, inspecção e correção. Maiores detalhes de planejamento, estão apresentados no [Planejamento da Entrega 2](../0planejamento.md).

## Verificações anteriores
Uma das atividades da disciplina de Requisitos de Software, ministrada pelo professor André Barros, é realizar a verificação do projeto de outro grupo. O grupo 3 ([Banco Central](https://github.com/Requisitos-de-Software/2023.1-VLC/blob/master/docs/verificacao/entrega_2/in_or_out.md)), fez a inspeção do nosso In Or Out. Dessa forma, criaremos nosso checklist, levando em conta os pontos levantados pelo grupo 3, mas principalmente baseando-se nas literaturas de referência.

## Checklist
<!-- LIVRO BASE PARA CRIAÇÃO DAS PERGUNTAS -->
Os checklists foram estabelecido com base nos critérios estabelecidos na literatura Software Requirements (Developer Best Practices)[[4]()]. E Seguindo as perguntas padrões estabelecidas pelo grupo no [Planejamento Geral](../0planejamento-geral.md), está apresentado na Tabela 1, o checklist da In Or Out.


<!-- ADICIONAR O CHECKLIST -->

<center>

| ID| Descrição | Avaliação | Observação | 
|---|---|---|---|
| 1 | O artefato possui uma introdução condizente com o conteúdo do texto? |Incompleto|Muito simples| 
| 2 | Todas as bibliografias/referências bibliográficas são utilizadas de forma correta? |Não|Uso incorreto e literatura base poderia ser mais acadêmica| 
| 3 | Todas as tabelas e figuras são chamadas no texto, possuem legendas e fontes? |Incompleto |O vídeo não é chamado no texto| 
| 4 | A metodologia esta de acordo com o artefato analisado?<a href="#1">¹</a> |Incompleto |Complementar com nova literatura base | 
|5|É apresentado o cronograma da atividade? |Não|Não foi apresentado|
|6|Foi preparada uma lista para a atividade?<a href="#2">²</a> |Incompleto|No vídeo é mostrado a lista de requisitos, porém no documento não fala sobre.|
|7|A participação do cliente e/ou persona no processo de priorização?|Sim|-|
|8|É feita uma toma de decisão? <a href="#3">³</a>|Sim|-|
|9|A lista é reduzida ao mínimo necessário? <a href="#4">⁴</a>|Incompleta|Poderia reduzir mais|
|10|Há a gravação/registro da atividade?|Sim|-|
|11 | É feito um agrupamento de requisitos elicitados?  |Não |Não foi agrupado |
|12| Os requisitos retirados são postos como requisitos de um próximo lançamento?<a href="#5">⁵</a> |Não|Não teve essa definição|

<p>Tabela 1 - Checklist do In Or Out (Fonte: Autores)</p>
</center>

<div id="1"></div>
[¹]() Explicação do uso da metodologia no processo de priorização.
<div id="2"></div>
[²]() Se requisitos foram reunidos em uma listas e estão ligados com os artefatos anteriores, de elicitação.
<div id="3"></div>
[³]() Com a lista de requisitos, cada um é analisado e é decidido se está dentro(In) ou fora(Out) para implementação..
<div id="4"></div>
[⁴]() Considerando que será feito várias entregas, cada uma precisa estar bem reduzida.
<div id="5"></div>
[⁵]() Conforme o texto base, ao invés de criar uma ordem de priorização, os requisitos devem ser agrupados por ordem de lançamento.

## Gráfico
Com base no checklist feito no processo de inspeção do In Or Out, foi produzido o gráfico de avaliação do artefato, que pode ser visualizado/analisado na Figura 1.
<center>
<img src="../../../assets/img/InOrOut.png"></img>
<p>Figura 1 - Gráfico do In Or Out (Fonte: Autores)</p>
</center>

## Correção
O planejamento e a situação da correção do artefatos, In Or Out, será registrado na Tabela 2. A data se refere ao período previsto para correção e revisão.
<center>

|ID |Descrição |Detalhes |Corretor|Revisor|Data|Status|
|-------|------|------|---------|---|--|--|
| 1 | Introdução | Complementar a introdução | [Raquel](https://github.com/raqueleucaria) |[Paulo](https://github.com/PauloVictorFS) |23/06/2023 a 25/06/2023|-|
| 2 | Bibliografias/referências bibliográficas | Corrigir e acrescentar | [Raquel](https://github.com/raqueleucaria) | [Paulo](https://github.com/PauloVictorFS)  |23/06/2023 a 25/06/2023|-|
| 3 | Vídeo  | Referenciar no texto| [Raquel](https://github.com/raqueleucaria) | [Paulo](https://github.com/PauloVictorFS)  |24/06/2023 a 26/06/2023|-|
| 4 | Metodologia | Complementar com nova literatura | [Raquel](https://github.com/raqueleucaria) | [Paulo](https://github.com/PauloVictorFS)  |23/06/2023 a 25/06/2023|-|
| 5 | Cronograma | Apresentar o cronograma que não foi registrado | [Raquel](https://github.com/raqueleucaria) | [Paulo](https://github.com/PauloVictorFS)  |24/06/2023 a 26/06/2023|-|
| 6 | Lista de requisitos | Citar no texto que foi criado e linkar com os artefatos anteriores | [Raquel](https://github.com/raqueleucaria) |[Paulo](https://github.com/PauloVictorFS) |23/06/2023 a 25/06/2023|-|
| 9 | Redução dos requisitos | Rever os requisitos "out" | [Raquel](https://github.com/raqueleucaria) | [Paulo](https://github.com/PauloVictorFS)  |24/06/2023 a 26/06/2023|-|
| 11 | Agrupamento  | Apresentar o cronograma que não foi registrado| [Raquel](https://github.com/raqueleucaria) | [Paulo](https://github.com/PauloVictorFS)  |24/06/2023 a 26/06/2023|-|
| 12 | Lançamentos futuros | Explicar que os agrupamentos fora serão implementados posteriormente | [Raquel](https://github.com/raqueleucaria) | [Paulo](https://github.com/PauloVictorFS)  |24/06/2023 a 26/06/2023|-|


<p>Tabela 2 - Distribuição da Correção dos Artefatos (Fonte: Autores)</p>
</center>

### Atualização
As atualizações no processo de correção do In Or Out, são:

- Nenhuma
<!-- - xx/xx/xxxx - Correção da bibliográfia (ID 2) - Projeto 50% correto. -->

## Referência bibliográfica

> [1] ISO/IEC/IEEE 12207:2017(E) (ISO/IEC/IEEE, 2017, p. 82). Disponível em: <https://www.iso.org/obp/ui/#iso:std:iso-iec-ieee:24765:ed-2:v1:en> . Acesso em: 13 jun. 2023

> [2] CAESB, grupo 4. Disponível em <https://requisitos-de-software.github.io/2023.1-Caesb/> . Acesso em: 16 jun. 2023.

> [3] BUSH, Marilyn, Chris Gerrard, Clifford Shelley. Fagan Inspection: The Silver Bullet No-one Wants to Fire. London SPIN, 25 mar. 2010.

> [4] WIEGERS, Karl; BEATTY, Joy. Software Requirements (Developer Best Practices). 3rd Edition. Microsoft Press, 2013.


## Bibliografia

> Sommerville, Ian. Engenharia de software. 08. ed. São Paulo: Pearson Addison Wesley, 2007.

> SERRANO, Milene, SERRANO, Maurício. Análise de Requisitos (Aula 23). UnB Gama, Brasília, 2023. Disponível no [link](../assets/referencias/Requisitos%20-%20Aula%20023.pdf).

> WIEGERS, Karl; BEATTY, Joy. Software Requirements (Developer Best Practices). 3rd Edition. Microsoft Press, 2013. 

> PENHA, Igor; GOBBI, Lucas Gobbi. Verificação In or Out (Caesb). Repositório do Grupo VLC da disciplina de Requisitos da Universidade de Brasília, 2023. Disponível em: <https://github.com/Requisitos-de-Software/2023.1-VLC/blob/master/docs/verificacao/entrega_2/in_or_out.md>. Acesso em: 18 de Junho de 2023.

> CAMPELLO, Gabriel. In or Out, Verificação grupo +1,. Repositório do Grupo Bilheteria Digital da disciplina de Requisitos da Universidade de Brasília, 2023. Disponível em: <https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/verificacao/grupo2/entrega2/inorout2/>. Acesso em: 18 de Junho de 2023. 

## Histórico de Versão
|    Data    | Data Prevista de Revisão | Versão |      Descrição       |                                 Autor                                  |               Revisor               |
| :--------: | :----------------------: | :----: | :------------------: | :--------------------------------------------------------------------: | :---------------------------------: |
| 19/06/2023 |        21/06/2023        |  1.0   | Criação do documento |  [Raquel Eucaria](https://github.com/raqueleucaria) | [Caetano](https://github.com/caeslucio) |