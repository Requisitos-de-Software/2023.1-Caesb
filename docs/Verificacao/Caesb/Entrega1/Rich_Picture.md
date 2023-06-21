# Rich Picture
## Introdução

Segundo a norma internacional ISO/IEC/IEEE 12207:2017(E) (ISO/IEC/IEEE, 2017, p. 82) [1], o objetivo da verificação se define em "prover evidência objetiva que o sistema ou elemento do sistema atende completamente seus requisitos e características especificados". Com isso, afim de garantir qualidade e consistência dos requisitos, realizaremos a verificação dos documentos do nosso grupo, [Caesb](https://requisitos-de-software.github.io/2023.1-Caesb/)[2], da disciplina Requisitos de Software.

## Objetivos
O objetivo deste documento é realizar a verificação do Rich Picture, artefato da Entrega 1, do Grupo 4, [Caesb](https://requisitos-de-software.github.io/2023.1-Caesb/). De forma impessoal, este documento não deseja avaliar os membros do grupo, mas o artefato em si.



## Metodologia
Como método de investigação e produção da verificação, utilizaremos a inspeção, mais especificamente a _Fagan Inspection_. Na qual, segundo Bush [3], consiste na "inspeção de documentos entendidos como prontos para uso e busca por defeitos". Seguindo as etapas de planejamento, visão geral, preparação, inspecção e correção. Maiores detalhes de planejamento, estão apresentados no [Planejamento da Entrega 1](./0planejamento.md).

## Verificações anteriores
Uma das atividades da disciplina de Interação Humano Computador, ministrada pelo professor André Barros, é realizar a verificação do projeto de outro grupo. A nossa verificação foi feita sobre o Rich Picture do grupo 5 ([SimpleNote](https://requisitos-de-software.github.io/2023.1-Caesb/Verificacao/Grupo5/Entrega1/Rich_Picture/)). E o grupo 3 ([VLC](https://requisitos-de-software.github.io/2023.1-VLC/#/verificacao/entrega_1/verificacao_aplicativos_escolhidos)), fez a inspeção do nosso projeto (Caesb).

Dessa forma, reavaliamos nosso checklist, levando em conta os pontos levantados pelo grupo 3, mas principalmente baseando-se nas literaturas de referência. Assim, um novo checklist foi criado para a avaliação do nosso próprio Rich Picture.

## Checklist
<!-- LIVRO BASE PARA CRIAÇÃO DAS PERGUNTAS -->
Os checklists foram estabelecido com base nos critérios da literatura Rich Picture Guidelines[[4]](https://aprender3.unb.br/pluginfile.php/2523045/mod_resource/content/2/1_5145791542719414573.pdf). Seguindo as perguntas padrões estabelecidas pelo grupo no [Planejamento Geral](../0planejamento-geral.md), está apresentado na Tabela 1, o checklist da Rich Picture. O checklist foi preenchido com base na versão 2.1 do Rich Picture do grupo 4, [Caesb](https://requisitos-de-software.github.io/2023.1-Caesb/).


<!-- ADICIONAR O CHECKLIST -->

<center>

|  ID  | Descrição | Avaliação | Observação |
| :--: | :-------: | :-------: | :--------: |
|  01  | O artefato possui uma introdução condizente com o conteúdo do texto? |Sim||
|  02  | Todas as bibliografias/referências bibliográficas são utilizadas no texto? |Não| Não possui bibliografias/referências bibliográficas |
|  03  | Todas as tabelas e figuras são chamadas no texto, possuem legendas e fontes? |Sim||
|  04  | As metodologias do texto definem de forma condizente as formas e os métodos que o grupo realizou o artefato? |Não| Não possui metodologia|
|  05  | Existe uma Rich Picture para o aplicativo selecionado? | Sim ||
|  06  | Apenas a versão mais recente do Rich Picture selecionado está sendo apresentada? | Não | Possui duas versões do Rich Picture selecionado no artefato, melhor colocar apenas a última versão|
|  07  | É informado como o Rich Picture foi construido? |Não| |
|  08  | A Rich Picture apresenta atores[¹]? |Sim||
|  09  | Os atores são representado graficamente como palitos de fósforo? |Sim||
|  10  | A Rich Picture apresenta operações[²]? |Sim||
|  11  | As operações estão rotuladas apenas como verbos no infinitivo? |Incompleto|Possui uma operação com verbo no infinitivo seguida por um substantivo|
|  12  | Cada operação é executada por um ator ou outra operação? |Sim||
|  13  | Cada operação é representada como círculos ou ovais, com um rótulo descritivo dentro? |Sim||
|  14  | A Rich Picture apresenta armazenamentos de dados/tabelas[³]? |Sim||
|  15  | Os armazenamentos de dados/tabelas estão rotuladas como substantivos? |Sim||
|  16  | Os armazenamentos de dados/tabelas são representados como retângulos? |Sim||
|  17  | A Rich Picture apresenta setas que mostram a direção do fluxo de dados (ou informações) entre atores, armazenamentos de dados e operações? |Sim||
|  18  | As setas são de ponta única? |Sim||
|  19  | O fluxo das setas faz sentido dentro do sistema? |Sim||
|  20  | A Rich Picture possui rótulos para facilitar o entendimento do fluxo de dados? |Não||
|  21  | A Rich Picture possui limite/fronteira do sistema? |Sim||
|  22  | Os componetes da Rich Picture estão corretamentes posicionados[⁴] em relação ao limite/fronteira do sistema? |Sim||
|  23  | O artefato possui legendas explicando os componentes do Rich Picture? |Sim||


<p>Tabela 1 - Checklist Rich Picture (Fonte: Autores)</p>
</center>


[¹]() Atores são os usuários do seu sistema. <br>
[²]() Operações especificam o que o sistema faz. <br>
[³]() Armazenamentos de dados/tabelas são usadas para representar como as informações são coletadas, armazenadas e manipuladas dentro de um sistema. <br>
[⁴]() Atores fora e o que o sistema deve realizar dentro do limite/fronteira do sistema.


## Gráfico
Na figura 1, abaixo, está apresentado o gráfico de distribuição das avaliações do checklist.

<center>
<img src="../../assets/img/richPicture.png"></img>
<p>Figura 1 - Gráfico Checklist (Fonte: Autores)</p>
</center>

## Correção
Na tabela 2, abaixo, está apresentado comentários sobre as correções a serem feitas no artefato.
<center>

|ID |Descrição |Detalhes |Corretor|Revisor|Status|
|-------|------|------|---------|---|--|
| 02 | Bibliografias/referências bibliográficas não são utilizadas no texto | Citar nos textos as bibliografias/referências bibliográficas | Guilherme | Daniel |-|
| 04 | Não possui metodologia | Criar um tópico de metodologia | Guilherme | Daniel |-|
| 06 | Possui mais de uma versão do Rich Picture selecionado | Deixar apenas a versão mais recente do Rich Picture para evitar confusões | Guilherme | Daniel |-|
| 07 | Não é informado como o Rich Picture foi construido | Mencionar como foi construido no tópico de metodologia | Guilherme | Daniel |-|
| 11 | Nem todas as operações estão rotuladas como verbos no infinitivo | A operação 'Simular Tarifa' está rotulada com verbo no infinitivo seguida por um substantivo| Guilherme | Daniel |-|
| 20 | A Rich Picture não possui rótulos para facilitar o entendimento do fluxo de dados | Adicionar possíveis rótulos para facilitar o entendimento, evitando ambiguidade por exemplo| Guilherme | Daniel |-|


<p>Tabela 2 - Distribuição da Correção dos Artefatos (Fonte: Autores)</p>
</center>

<!-- ### Atualização
Apresentar a atualização das correções feitas. E a porcentagem de "sim" no momento. Conforme o exemplo:

- xx/xx/xxxx - Correção da bibliográfia (ID 2) - Projeto 50% correto. -->

## Referência bibliográfica

> [1] ISO/IEC/IEEE 12207:2017(E) (ISO/IEC/IEEE, 2017, p. 82). Disponível em: https://www.iso.org/obp/ui/#iso:std:iso-iec-ieee:24765:ed-2:v1:en . Acesso em: 13 jun. 2023

> [2] CAESB, grupo 4. Disponível em https://requisitos-de-software.github.io/2023.1-Caesb/ . Acesso em: 16 jun. 2023.

> [3] BUSH, Marilyn, Chris Gerrard, Clifford Shelley. Fagan Inspection: The Silver Bullet No-one Wants to Fire. London SPIN, 25 mar. 2010.

> [4] Artigo base em https://aprender3.unb.br/pluginfile.php/2523045/mod_resource/content/2/1_5145791542719414573.pdf . Acesso em: 20 jun. 2023.


## Bibliografia
> SANTOS, Mizael. Planejamento da Verificação da Etapa 1 do Grupo 4. Repositório do Grupo VLC da disciplina de Requisitos da Universidade de Brasília, 2023. Disponível em: <https://requisitos-de-software.github.io/2023.1-VLC/#/verificacao/entrega_1/verificacao_aplicativos_escolhidos>. Acesso em: 20 de Junho de 2023.

> REINEHR, Sheila. Engenharia de requisitos. E-book. ISBN 9786556900674. Disponível em: <https://integrada.minhabiblioteca.com.br/#/books/9786556900674/>. Acesso em: 13 jun. 2023.

> Sommerville, Ian. Engenharia de software. 08. ed. São Paulo: Pearson Addison Wesley, 2007.

> SERRANO, Milene, SERRANO, Maurício. Análise de Requisitos (Aula 23). UnB Gama, Brasília, 2023. Disponível no [link](../assets/referencias/Requisitos%20-%20Aula%20023.pdf).

## Histórico de Versão
|    Data    | Data Prevista de Revisão | Versão |      Descrição       |                                 Autor                                  |               Revisor               |
| :--------: | :----------------------: | :----: | :------------------: | :--------------------------------------------------------------------: | :---------------------------------: |
| 20/06/2023 |        21/06/2023        |  1.0   | Criação do documento |  [Guilherme](https://github.com/guilhermekishimoto)| [Daniel]() |