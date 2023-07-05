# Léxicos

## Introdução

Segundo a norma internacional ISO/IEC/IEEE 12207:2017(E) (ISO/IEC/IEEE, 2017, p. 82) [[1]()], o objetivo da verificação se define em "prover evidência objetiva que o sistema ou elemento do sistema atende completamente seus requisitos e características especificados". Com isso, afim de garantir qualidade e consistência dos requisitos, realizaremos a verificação dos documentos do nosso grupo, [Caesb](https://requisitos-de-software.github.io/2023.1-Caesb/) [[2]()], da disciplina Requisitos de Software.

## Objetivos
O objetivo deste documento é realizar a verificação dos Léxicos, artefato da Entrega 3, do Grupo 4, [Caesb](https://requisitos-de-software.github.io/2023.1-Caesb/). De forma impessoal, este documento não deseja avaliar os membros do grupo, mas o artefato em si.



## Metodologia
Como método de investigação e produção da verificação, utilizaremos a inspeção, mais especificamente a _Fagan Inspection_. Na qual, segundo Bush [[3]()], consiste na "inspeção de documentos entendidos como prontos para uso e busca por defeitos". Seguindo as etapas de planejamento, visão geral, preparação, inspecção e correção. Maiores detalhes de planejamento, estão apresentados no [Planejamento da Entrega 1](./0planejamento.md).

## Verificações anteriores
Uma das atividades da disciplina de Requisitos de Software, ministrada pelo professor André Barros, é realizar a verificação do projeto de outro grupo. A nossa verificação foi feita sobre os léxicos do grupo 5 ([SimpleNote](https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/lexico/)). E o grupo 3 [VLC](https://github.com/Requisitos-de-Software/2023.1-VLC/blob/master/docs/verificacao/entrega_3/verificacao_lexicos.md) fez a inspeção do nosso projeto (Caesb).

Dessa forma, reavaliamos nosso checklist, levando em conta os pontos levantados pelo grupo 3, mas principalmente baseando-se nas literaturas de referência, como o artigo A Strategy for Conceptual Model Acquisition [[4]()] e o livro "Engenharia de software" do autor Sommerville. Assim, um novo checklist foi criado para a avaliação dos nossos próprios Léxicos.

## Checklist
<!-- LIVRO BASE PARA CRIAÇÃO DAS PERGUNTAS -->
Os checklists foram estabelecido com base nos critérios da disciplina. Seguindo as perguntas padrões estabelecidas pelo grupo no [Planejamento Geral](../0planejamento-geral.md),  e está apresentado na Tabela 1 o checklist do artefato Léxicos.

<!-- ADICIONAR O CHECKLIST -->

<center>

| ID | Descrição | Avaliação | Observação |
| --- | --- | --- | --- |
| 1 | O artefato possui uma introdução condizente com o seu conteúdo? | Sim |  |
| 2 | Todas as bibliografias/referências bibliográficas são utilizadas no texto? | Não | Não há nenhuma menção direta das referências fora da seção de referências |
| 3 | Todas as tabelas e imagens são chamadas no texto, possuem legendas e fontes? | Sim | |
| 4 | As metodologias do texto definem de forma condizente as formas e os métodos que o grupo realizou o artefato? | Incompleto | Faltou especificar a utilização dos requisitos priorizados na realização do léxico |
| 5 | Há uma listagem ordenada de forma que facilite a busca por um léxico em específico? | Sim |  |
| 6 | Cada léxico segue um modelo de estrutura em comum?[¹]() | Sim |  |
| 7 | Cada léxico apresenta noções e impactos descritas por meio do emprego de símbolos da própria linguagem?[²]() | Sim |  |
| 8 | Cada léxico está escrito de forma coerente com sua classificação? | Sim |  |
| 9 | Cada léxico possui um nome condizente com o conteudo dele? | Sim |  |
| 10 | Cada léxico possui um sinônimo definido corretamente? | Sim |  |
| 11 | Cada léxico possui uma Descrição clara e condizente com o significado dele? | Não | Não há descrição |
<p>Tabela 1: Checklist de Verificação de Léxicos (Fonte: autor, 2023).</p>
</center>

[¹]() Modelo de estrutura contém Léxico,Sinônimos,Noção,Impacto,Classificação. <br>
[²]() Utiliza símbolos ou termos intrínsecos à própria linguagem.


## Gráfico

<center>
<img src="../../assets/img/lexicos.PNG"></img>
<p>Figura 1 - Checklist (Fonte: Autores)</p>
</center>

## Correção
Na tabela 2 abaixo serão  apresentado os erros encontrados durante a avaliação e o planejamento da correção desses erros
<center>

|ID |Descrição |Detalhes |Corretor|Revisor|Data|Status|
|-------|------|------|---------|---|--|----|
| 2 |  Não há nenhuma menção direta das referências no texto | Chamar as referências no texto | Paulo | Raquel |21/06/2023|Ok|
| 4 |Faltou especificar a utilização dos requisitos priorizados na realização do léxico |Especificar a utilização dos requisitos priorizados | Paulo | Raquel |21/06/2023|Ok|
| 11| Não há descrição nos léxicos | Adicionar descrição nos Léxicos | Paulo| Raquel |22/06/2023|-|



<p>Tabela 2 - Distribuição da Correção dos Artefatos (Fonte: Autores)</p>
</center>

### Atualização
Após a realização da verificação , foi consertado 2 errs, o do ID3 e o do ID4, gerando uma nova porcentagem correta de acima de 90%. Com relação ao erro do ID11(Não há descrição nos léxicos), Ele será consertado no dia 22/06/2023, e o artefato será atualizado após isso ser realizado.

- 21/06/2023 - Correção das Referências (ID 2) 
- 21/06/2023 - Correção das tabelas (ID 3) 


## Referência bibliográfica

> [1] ISO/IEC/IEEE 12207:2017(E) (ISO/IEC/IEEE, 2017, p. 82). Disponível em: https://www.iso.org/obp/ui/#iso:std:iso-iec-ieee:24765:ed-2:v1:en . Acesso em: 13 jun. 2023

> [2] CAESB, grupo 4. Disponível em https://requisitos-de-software.github.io/2023.1-Caesb/ . Acesso em: 16 jun. 2023.

> [3] BUSH, Marilyn, Chris Gerrard, Clifford Shelley. Fagan Inspection: The Silver Bullet No-one Wants to Fire. London SPIN, 25 mar. 2010.

> [4] LEITE, Julio. A Strategy for Conceptual Model Acquisition. 



## Bibliografia
> PENHA, Igor, Lucas Gobbi. Planejamento da Verificação da Etapa 3 do Grupo 4. Repositório do Grupo VLC da disciplina de Requisitos da Universidade de Brasília, 2023. Disponível em: <https://github.com/Requisitos-de-Software/2023.1-VLC/tree/master/docs/verificacao/entrega_3/>. Acesso em: 16 de Junho de 2023.

> REINEHR, Sheila. Engenharia de requisitos. E-book. ISBN 9786556900674. Disponível em: <https://integrada.minhabiblioteca.com.br/#/books/9786556900674/>. Acesso em: 13 jun. 2023.

> Sommerville, Ian. Engenharia de software. 08. ed. São Paulo: Pearson Addison Wesley, 2007.

> SERRANO, Milene, SERRANO, Maurício. Análise de Requisitos (Aula 23). UnB Gama, Brasília, 2023. Disponível no [link](../assets/referencias/Requisitos%20-%20Aula%20023.pdf).

## Histórico de Versão
|    Data    | Data Prevista de Revisão | Versão |      Descrição       |                                                                Autor                                                                 |               Revisor               |
| :--------: | :----------------------: | :----: | :------------------: | :----------------------------------------------------------------------------------------------------------------------------------: | :---------------------------------: |
| 20/06/2023 |        21/06/2023        |  1.0   | Criação do documento | [Paulo](https://github.com/PauloVictorFS)  | [Daniel](https://github.com/daniel-de-sousa)|


