# Aplicativo Escolhido
## Introdução

Segundo a norma internacional ISO/IEC/IEEE 12207:2017(E) (ISO/IEC/IEEE, 2017, p. 82) [1], o objetivo da verificação se define em "prover evidência objetiva que o sistema ou elemento do sistema atende completamente seus requisitos e características especificados". Com isso, afim de garantir qualidade e consistência dos requisitos, realizaremos a verificação dos documentos do nosso grupo, [Caesb](https://requisitos-de-software.github.io/2023.1-Caesb/)[2], da disciplina Requisitos de Software.

## Objetivos
O objetivo deste documento é realizar a verificação das Aplicativo Escolhido, artefato da Entrega 1, do Grupo 4, [Caesb](https://requisitos-de-software.github.io/2023.1-Caesb/). De forma impessoal, este documento não deseja avaliar os membros do grupo, mas o artefato em si.

## Metodologia
Como método de investigação e produção da verificação, utilizaremos a inspeção, mais especificamente a _Fagan Inspection_. Na qual, segundo Bush [3], consiste na "inspeção de documentos entendidos como prontos para uso e busca por defeitos". Seguindo as etapas de planejamento, visão geral, preparação, inspecção e correção. Maiores detalhes de planejamento, estão apresentados no [Planejamento da Entrega 1](./0planejamento.md).

## Verificações anteriores
Uma das atividades da disciplina de Requisitos, ministrada pelo professor André Barros, é realizar a verificação do projeto de outro grupo. A nossa verificação foi feita sobre as Aplicativo Escolhido do grupo 5 ([SimpleNote](https://requisitos-de-software.github.io/2023.1-Simplenote/planejamento/Aplicativo%20Selecionado/)). E o grupo 3 ([VLC](https://requisitos-de-software.github.io/2023.1-VLC/#/verificacao/entrega_1/verificacao_aplicativos_escolhidos)), fez a inspeção do nosso projeto (Caesb).

Dessa forma, reavaliamos nosso checklist, levando em conta os pontos levantados pelo grupo 3, mas principalmente baseando-se nas literaturas de referência. Assim, um novo checklist foi criado para a avaliação do nossas próprias Aplicativo Escolhido.

## Checklist
<!-- LIVRO BASE PARA CRIAÇÃO DAS PERGUNTAS -->
Os checklists foram estabelecido com base nos critérios da literatura BUSH[³](#referencia-bibliografica). Seguindo as perguntas padrões estabelecidas pelo grupo no [Planejamento Geral](../0planejamento-geral.md), está apresentado na Tabela 1, o checklist do artefato Aplicativo Selecionado. As perguntas de 1 a 4 são baseadas nos padrões acordados pelo grupo, enquanto as demais questões, de 5 a 12, foram geradas a partir da inspeção e da literatura de referência.


<!-- ADICIONAR O CHECKLIST -->

<center>

| ID | Descrição | Avaliação | Observação |
| --- | --- | --- | --- |
| 1 | O artefato possui uma introdução condizente com o conteúdo do texto? | Não | Não há uma seção de introdução |
| 2 | Todas as bibliografias/referências bibliográficas são utilizadas de forma correta? | Incompleto | Não há uma seção de bibliografia/referencias bibliográficas |
| 3 | Todas as tabelas e figuras são chamadas no texto, possuem legendas e fontes? | Sim | - |
| 4 | A metodologia esta de acordo com o artefato analisado? | Sim | Está implícito, é importante que haja uma seção que explicite a metodologia |
| 5 | Há uma explicação do motivo de escolha do aplicativo? | Sim | - |
| 6 | Há um Rich Picture[¹](#legenda) de cada aplicativo analisado? | Sim | - |
| 7 | Há um Rich Picture do aplicativo escolhido? | Sim | - |
| 8 | Há no Rich Picture principal, Atores[²](#legenda) com nomes relevantes? | Sim | - |
| 9 | Há no Rich Picture principal, tarefas relacionadas aos Atores? | Sim | - |
| 10 | Há no Rich Picture principal, locais de armazenamento de dados? | Sim | Poderia ter um desenho do banco de dados para facilitar o entendimento |
| 11 | Há no Rich Picture principal, indicação do fluxo dos dados? | Sim | - |
| 12 | Há no Rich Picture principal, divisão entre as áreas dos sistema e os Atores? | Sim | - |

<p>Tabela 1 - Checklist Aplicativo Escolhido (Fonte: Autores)</p>
</center>

<div id="legenda"></div>

[¹]() Rich Picture: ferramenta de análise de problemas e expressão de ideias (CTEC2402). <br>
[²]() Atores: Usuário/Grupo de usuários presentes no escopo do sistema (CTEC2402).


## Gráfico
Com base no checklist feito no processo de inspeção do Aplicativo Selecionado, foi produzido o gráfico de avaliação do artefato, que pode ser visualizado/analisado na Figura 1.

<center>
<img src="../../assets/img/Aplicativo_Selecionado.png"></img>
<p>Figura 1 - Resultado Visual Checklist Aplicativo Selecionado (Fonte: Autores)</p>
</center>

## Correção
O planejamento e a situação da correção do artefatos, Aplicativo Selecionado, será registrado na Tabela 2. A data se refere ao período previsto para correção e revisão.
<center>

| ID | Descrição | Detalhes | Corretor | Revisor | Data | Status |
| --- | --- | --- | --- | --- | --- | --- |
| 1 | Bibliografia | Organizar bibliografia e referências bibliográficas | [Pedro](https://github.com/pedrobarbosaocb) | [Daniel](https://github.com/daniel-de-sousa) | 23/06/2023 a 25/06/2023 | ok |
| 2 | Metodologia | Adicionar metodologia utilizada em uma seção avulsa | [Pedro](https://github.com/pedrobarbosaocb) | [Daniel](https://github.com/daniel-de-sousa) | 23/06/2023 a 25/06/2023 | ok |
| 4 e 10 | Rich Picture | Adicionar mais desenhos a fim de melhorar o entendimento da mensagem que o Rich Picture representa | [Pedro](https://github.com/pedrobarbosaocb) | [Daniel](https://github.com/daniel-de-sousa) | 24/06/2023 a 26/06/2023 | Após reanálise do documento, foi percebido que houve a correção do Rich Picture, por isso não será corrigido novamente |


<p>Tabela 2 - Distribuição da Correção dos Artefatos (Fonte: Autores)</p>
</center>

### Atualização
A seguir estão listadas todas as atualizações do artefato analisado por este documento, a partir da data de sua data de entrega.

- 03/07/2023 - Correção pós verificação (ID's 1, 2 e 4)

<div id="referencia-bibliografica"></div>

## Referência bibliográfica

> [1] ISO/IEC/IEEE 12207:2017(E) (ISO/IEC/IEEE, 2017, p. 82). Disponível em: https://www.iso.org/obp/ui/#iso:std:iso-iec-ieee:24765:ed-2:v1:en . Acesso em: 13 jun. 2023

> [2] CAESB, grupo 4. Disponível em https://requisitos-de-software.github.io/2023.1-Caesb/ . Acesso em: 16 jun. 2023.

> [3] BUSH, Marilyn, Chris Gerrard, Clifford Shelley. Fagan Inspection: The Silver Bullet No-one Wants to Fire. London SPIN, 25 mar. 2010.

> [4] CTEC2402. Introducting to Rich Picture - Rich Picture Drawing Guidelines. 


## Bibliografia
> MACIEL, Geovanna. Planejamento da Verificação da Etapa 1 do Grupo 2. Repositório do Grupo Bilheteria Digital da disciplina de Requisitos da Universidade de Brasília, 2023. Disponível em: <https://requisitos-de-software.github.io/2023.1-VLC/#/verificacao/entrega_2/planejamento_verificacao_etapa2>. Acesso em: 16 de Junho de 2023.

> PENHA, Igor, Lucas Gobbi. Planejamento da Verificação da Etapa 2 do Grupo 4. Repositório do Grupo VLC da disciplina de Requisitos da Universidade de Brasília, 2023. Disponível em: <https://interacao-humano-computador.github.io/2022.2-Lichess/verificacao_validacao/pc5-planejamento/>. Acesso em: 16 de Junho de 2023.

> REINEHR, Sheila. Engenharia de requisitos. E-book. ISBN 9786556900674. Disponível em: <https://integrada.minhabiblioteca.com.br/#/books/9786556900674/>. Acesso em: 13 jun. 2023.

> Sommerville, Ian. Engenharia de software. 08. ed. São Paulo: Pearson Addison Wesley, 2007.

> SERRANO, Milene, SERRANO, Maurício. Análise de Requisitos (Aula 23). UnB Gama, Brasília, 2023. Disponível no [link](../assets/referencias/Requisitos%20-%20Aula%20023.pdf).

## Histórico de Versão
|    Data    | Data Prevista de Revisão | Versão |      Descrição       |                                 Autor                                  |               Revisor               |
| :--------: | :----------------------: | :----: | :------------------: | :--------------------------------------------------------------------: | :---------------------------------: |
| 14/06/2023 |        15/06/2023        |  1.0   | Criação do documento |  [Raquel Eucaria](https://github.com/raqueleucaria) e [Pedro](https://github.com/pedrobarbosaocb)| [Caetano](https://github.com/caeslucio) |
| 21/06/2023 |        21/06/2023        |  2.0   | Adicionando Checklist |  [Pedro](https://github.com/pedrobarbosaocb)| [Caetano](https://github.com/caeslucio) |
| 03/07/2023 |        04/007/2023        |  2.1   | Atualizando documento após correções |  [Pedro](https://github.com/pedrobarbosaocb)| [Daniel](https://github.com/daniel-de-sousa |"