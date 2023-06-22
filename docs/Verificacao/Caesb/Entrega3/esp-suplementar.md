# Especificação Suplementar 

## Introdução

Segundo a norma internacional ISO/IEC/IEEE 12207:2017(E) (ISO/IEC/IEEE, 2017, p. 82) [[1]()], o objetivo da verificação se define em "prover evidência objetiva que o sistema ou elemento do sistema atende completamente seus requisitos e características especificados". Com isso, afim de garantir qualidade e consistência dos requisitos, realizaremos a verificação dos documentos do nosso grupo, [Caesb](https://requisitos-de-software.github.io/2023.1-Caesb/)[[2]()], da disciplina Requisitos de Software.

## Objetivos
O objetivo deste documento é realizar a verificação da Especificação Suplementar, artefato da Entrega 3, do Grupo 4, [Caesb](https://requisitos-de-software.github.io/2023.1-Caesb/). De forma impessoal, este documento não deseja avaliar os membros do grupo, mas o artefato em si.

## Metodologia
Como método de investigação e produção da verificação, utilizaremos a inspeção, mais especificamente a _Fagan Inspection_. Na qual, segundo Bush [[3]()], consiste na "inspeção de documentos entendidos como prontos para uso e busca por defeitos". Seguindo as etapas de planejamento, visão geral, preparação, inspecção e correção. Maiores detalhes de planejamento, estão apresentados no [Planejamento da Entrega 3](./0planejamento.md).

## Verificações anteriores
Uma das atividades da disciplina de Requisitos de Software, ministrada pelo professor André Barros, é realizar a verificação do projeto de outro grupo. A nossa verificação foi feita sobre a Especificação Suplementar do grupo 5 ([SimpleNote](../../Grupo5/Entrega3/esp-suplementar.md)). E o grupo 3 ([VLC](https://github.com/Requisitos-de-Software/2023.1-VLC/blob/master/docs/verificacao/entrega_3/verificacao_especificacao-suplementar.md)), fez a inspeção do nosso projeto, da Caesb.

Dessa forma, reavaliamos nosso checklist, levando em conta os pontos levantados pelo grupo 3, mas principalmente baseando-se nas literaturas de referência. Assim, um novo checklist foi criado para a avaliação da nossa própria introspecção.

## Checklist
<!-- LIVRO BASE PARA CRIAÇÃO DAS PERGUNTAS -->
Os checklists foram estabelecido com base nos critérios propostos nos slide da professora Milene sobre Modelagem de Requisitos [[4]()]. Seguindo as perguntas padrões estabelecidas pelo grupo no [Planejamento Geral](../0planejamento-geral.md), está apresentado na Tabela 1, o checklist da Especificação Suplementar.


<!-- ADICIONAR O CHECKLIST -->

<center>

| ID| Descrição | Avaliação | Observação | 
|---|---|---|---|
| 1 | O artefato possui uma introdução condizente com o conteúdo do texto? |Sim|-| 
| 2 | Todas as bibliografias/referências bibliográficas são utilizadas de forma correta? |Sim|-| 
| 3 | Todas as tabelas e figuras são chamadas no texto, possuem legendas e fontes? |Sim |-| 
| 4 | A metodologia esta de acordo com o artefato analisado?<a href="#1">¹</a> |Sim |- |
| 5 | Existe ligação com os documentos anteriores do projeto? | Sim | - |
| 6 | Os requisitos não funcionais do sistema são o foco da modelagem? | Não | Existem requistos funcionais |
| 7 | O documento segue o padrão FURPS+? <a href="#2">²</a> | Sim | - |
| 8 | O documento apresenta aspectos sobre prevenção de erros em Usabilidade? | Não | Possui de prevenção |
| 9 | O documento apresenta aspectos sobre estética e o design em Usabilidade? | Não | Não possui |
| 10 | O documento apresenta aspectos sobre consistência e padrões em Usabilidade? | Não | Não possui |
| 11 | O documento apresenta aspectos sobre frequência e gravidade de falha em Confiabilidade? | Sim | - |
| 12 | O documento apresenta aspectos sobre tempo médio entre falhas em Confiabilidade? | Sim | - |
| 13 | O documento apresenta aspectos sobre disponibilidade da aplicação em Performance? | Sim | - |
| 14 | O documento apresenta aspectos sobre tempo de resposta em Performance? | Sim | - |
| 15 | O documento apresenta aspectos sobre a compatibilidade com outros sistemas em Suportabilidade? | Sim | - |

<p>Tabela 1 - Checklist da Especificação Suplementar (Fonte: Autores)</p>
</center>

<div id="1"></div>
[¹]() Explicação do uso da metodologia de análise dos requisitos não funcionais.
<div id="2"></div>
[²]() Destrinchando os aspectos de Funcionalidade, Usabilidade, Confiabilidade, Performance, Suportabilidade.

## Gráfico
Com base no checklist feito no processo de inspeção da Especificação Suplementar, foi produzido o gráfico de avaliação do artefato, que pode ser visualizado/analisado na Figura 1.
<center>
<img src="../../assets/img/espec.png"></img>
<p>Figura 1 - Gráfico da Especificação Suplementar (Fonte: Autores)</p>
</center>

## Correção
O planejamento e a situação da correção do artefato, Especificação Suplementar, será registrado na Tabela 2. A data se refere ao período previsto para correção e revisão.
<center>

|ID |Descrição |Detalhes |Corretor|Revisor|Data|Status|
|-------|------|------|---------|---|--|--|
| 6 | Não funcionais | Retirar os funcionais | [Raquel](https://github.com/raqueleucaria) | [Pedro](https://github.com/pedrobarbosaocb)  |25/06/2023 a 26/06/2023|-|
| 8 | Prevenção de erro em Usabilidade  | Inclui| [Raquel](https://github.com/raqueleucaria) | [Pedro](https://github.com/pedrobarbosaocb)  |25/06/2023 a 26/06/2023|-|
| 9 | Estética e o design em Usabilidade | Inclui | [Raquel](https://github.com/raqueleucaria) | [Pedro](https://github.com/pedrobarbosaocb)  |25/06/2023 a 26/06/2023|-|
| 10 | Consistência e padrões em Usabilidade | Inclui | [Raquel](https://github.com/raqueleucaria) | [Pedro](https://github.com/pedrobarbosaocb)  |25/06/2023 a 26/06/2023|-|


<p>Tabela 2 - Distribuição da Correção dos Artefatos (Fonte: Autores)</p>
</center>

### Atualização
As atualizações no processo de correção da Especificação Suplementar, são:

- Nenhuma
<!-- - xx/xx/xxxx - Correção da bibliográfia (ID 2) - Projeto 50% correto. -->

## Referência bibliográfica

> [1] ISO/IEC/IEEE 12207:2017(E) (ISO/IEC/IEEE, 2017, p. 82). Disponível em: <https://www.iso.org/obp/ui/#iso:std:iso-iec-ieee:24765:ed-2:v1:en> . Acesso em: 13 jun. 2023

> [2] CAESB, grupo 4. Disponível em <https://requisitos-de-software.github.io/2023.1-Caesb/> . Acesso em: 16 jun. 2023.

> [3] BUSH, Marilyn, Chris Gerrard, Clifford Shelley. Fagan Inspection: The Silver Bullet No-one Wants to Fire. London SPIN, 25 mar. 2010.

> [4] SERRANO, Milene, SERRANO, Maurício. Modelagem de Requisitos (Aula 13). UnB Gama, Brasília, 2023. Disponível no [link](../assets/referencias/RequisitosCasosdeUso.pdf.pdf).


## Bibliografia

> Sommerville, Ian. Engenharia de software. 08. ed. São Paulo: Pearson Addison Wesley, 2007.

> SERRANO, Milene; SERRANO, Maurício. Análise de Requisitos (Aula 23). UnB Gama, Brasília, 2023. Disponível no [link](../assets/referencias/Requisitos%20-%20Aula%20023.pdf).

> WIEGERS, Karl; BEATTY, Joy. Software Requirements (Developer Best Practices). 3rd Edition. Microsoft Press, 2013. 

> RIBEIRO, Bruno. Verificação do artefato de Especificação Suplementar do Grupo 4 (Caesb). Repositório do Grupo VLC da disciplina de Requisitos da Universidade de Brasília, 2023. Disponível em: <https://github.com/Requisitos-de-Software/2023.1-VLC/blob/master/docs/verificacao/entrega_3/verificacao_especificacao-suplementar.md>. Acesso em: 18 de Junho de 2023.


## Histórico de Versão
|    Data    | Data Prevista de Revisão | Versão |      Descrição       |                                 Autor                                  |               Revisor               |
| :--------: | :----------------------: | :----: | :------------------: | :--------------------------------------------------------------------: | :---------------------------------: |
| 19/06/2023 |        21/06/2023        |  1.0   | Criação do documento |  [Raquel Eucaria](https://github.com/raqueleucaria) |[Guilherme](https://github.com/guilhermekishimoto) |