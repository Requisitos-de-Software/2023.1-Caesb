# Histórias de Usuário

## Introdução
Segundo a norma internacional ISO/IEC/IEEE 12207:2017(E) (ISO/IEC/IEEE, 2017, p. 82) [1], o objetivo da verificação se define em "prover evidência objetiva que o sistema ou elemento do sistema atende completamente seus requisitos e características especificados". Com isso, afim de garantir qualidade e consistência dos requisitos, realizaremos a verificação dos documentos do nosso grupo, [Caesb](https://requisitos-de-software.github.io/2023.1-Caesb/)[2], da disciplina Requisitos de Software.

## Objetivo
O objetivo deste documento é realizar a verificação da história de usuário, artefato da Entrega 2, do Grupo 4 (CAESB). De forma impessoal, este documento não deseja avaliar os membros do grupo, mas o artefato em si.

## Metodologia
Como método de investigação e produção da verificação, utilizaremos a inspeção, mais especificamente a _Fagan Inspection_. Na qual, segundo Bush [3], consiste na "inspeção de documentos entendidos como prontos para uso e busca por defeitos". Seguindo as etapas de planejamento, visão geral, preparação, inspeção e correção. Maiores detalhes de planejamento, estão apresentados no [Planejamento da Entrega 2](../0planejamento.md).

## Verificações Anteriores
Uma das atividades da disciplina de Requisitos de Software, ministrada pelo professor André Barros, foi a realização da verificação de um projeto de outro grupo. Desse modo a nossa verificação foi feita sobre as histórias de usuário do Grupo 05 (Simplenote) e o grupo 03 (VLC Media Player), fez a inspeção do nosso projeto (OpenStreeMap). 

Dessa forma, reavaliamos nosso checklist, levando em conta os pontos levantados pelo grupo 3, mas principalmente baseando-se nas literaturas de referência. Assim, um novo checklist foi criado para a avaliação das nossas histórias de usuário.

## Checklist
Os checklists foram estabelecidos com base nos critérios estabelecidos nos slides da professora Milene [4]. Seguindo as perguntas padrões estabelecidas pelo grupo no [Planejamento Geral](../0planejamento-geral.md), está apresentado na Tabela 1, o checklist da história de usuário.

<center>

|  ID | Descrição | Avaliação | Observação | 
|:---:|-----------|:---------:|------------|
| 1 | O artefato possui uma introdução condizente com o conteúdo do texto? | Sim || 
| 2 | Todas as bibliografias/referências bibliográficas são utilizadas de forma correta? | Sim || 
| 3 | Todas as tabelas e figuras são chamadas no texto, possuem legendas e fontes, levando em conta suas características? | Sim |  | 
| 4 | A metodologia esta de acordo com o artefato analisado? | Sim ||
| 5 | As histórias de usuário possuem títulos autoexplicativos?<a href="#1">¹</a> | Não | Não existe título |
| 6 | A forma que foram feitas deixa claro as informações "quem", "o que" e "por que"?<a href="#2">²</a> | Incompleto | O porquê não está muito bem especificado. |
| 7 | As histórias possuem critérios de aceitação?<a href="#3">³</a> | Sim ||
| 8 | Há a participação do cliente ou persona na sua construção? | Sim ||
| 9 | O cliente ou persona validou as histórias e os critérios de aceitação? | Sim ||
| 10 | Todas as histórias podem ser testadas? | Não | Algumas podem dificultar os testes. |
| 11 | As histórias estão priorizadas?<a href="#4">⁴</a> | Sim ||
| 12 | Quem priorizou foi o cliente ou a persona? | Sim ||
| 13 | É informado de onde e como foram construídas as histórias? | Sim ||
| 14 | Existe a rastreabilidade? | Sim | Falta colocar o vídeo na página. |

<p>Tabela 1 - Checklist da história de usuário (Fonte: Autor)</p>
</center>

</center>
<div id="1"></div>
¹ - É possível já ter um breve entendimento das histórias ao se ver o título.
<div id="2"></div>
² - São os seguintes elementos:
    
    * Quem: Quem executa a história.
    * O que: A ação descrita na história.
    * Porque: O motivo da execução da ação.

<div id="3"></div>
³ - Que definem aquela historia como satisfeita.
<div id="4"></div>
⁴ - A classificação de quais são mais importantes.

## Gráfico
Com base no checklist feito no processo de inspeção da história de usuário, foi produzido o gráfico de avaliação do artefato, que pode ser visualizado/analisado na Figura 1.
<center>

![](../assets/img/grafico_historias.png)

Figura 1 - Gráfico das histórias de usuários. (Fonte: Autor)

</center>

## Correção
O planejamento e a situação da correção do artefato da história de usuário será registrado na Tabela 2.

<center>

| ID | Descrição | Detalhes | Corretor | Revisor | Data | Status |
|:--:|:---------:|:--------:|:--------:|:-------:|:----:|:------:|
| 5 | Título | Colocar campo de título das histórias. | [Daniel](https://github.com/daniel-de-sousa) | [Raquel](https://github.com/raqueleucaria) | 26/06/2023 a 30/06/2023 | - |
| 6 | Elementos | Especificar mais dentro de cada história os elementos. | [Daniel](https://github.com/daniel-de-sousa) | [Raquel](https://github.com/raqueleucaria) | 26/06/2023 a 30/06/2023 | - |
| 10 | Teste | Rever historias que são difíceis de serem testadas. | [Daniel](https://github.com/daniel-de-sousa) | [Raquel](https://github.com/raqueleucaria) | 26/06/2023 a 30/06/2023  | - |

<p>Tabela 2 - Distribuição da Correção dos Artefatos (Fonte: Autores)</p>
</center>

## Atualização
Depois da atualização, se realizou uma nova verificação, apresentando as seguintes porcentagens:

* Sem atualização.

## Referência bibliográfica

> [1] ISO/IEC/IEEE 12207:2017(E) (ISO/IEC/IEEE, 2017, p. 82). Disponível em: <https://www.iso.org/obp/ui/#iso:std:iso-iec-ieee:24765:ed-2:v1:en> . Acesso em: 13 jun. 2023

> [2] CAESB, grupo 4. Disponível em <https://requisitos-de-software.github.io/2023.1-Caesb/> . Acesso em: 16 jun. 2023.

> [3] BUSH, Marilyn, Chris Gerrard, Clifford Shelley. Fagan Inspection: The Silver Bullet No-one Wants to Fire. London SPIN, 25 mar. 2010.

> [4] SERRANO, Milene, SERRANO, Maurício. Requisitos (Aula 15): Elicitação, Modelagem e Análise. UnB Gama, Brasília, 2023.


## Bibliografia

> SERRANO, Milene, SERRANO, Maurício.  Análise de Requisitos (Aula 07). UnB Gama, Brasília, 2023. Acesso em: 21 jun. 2023.

> PENHA, Igor, Lucas Gobbi. Verificação da Introspecção (Caesb). Repositório do Grupo VLC da disciplina de Requisitos da Universidade de Brasília, 2023. Disponível em: <https://github.com/Requisitos-de-Software/2023.1-VLC/blob/master/docs/verificacao/entrega_2/introspeccao.md/>. Acesso em: 21 de Junho de 2023.

> SANTOS, Daniel. Introspecção.  Repositório do Grupo CAESB da disciplina de Requisitos da Universidade de Brasília, 2023. Disponível em: <https://requisitos-de-software.github.io/2023.1-Caesb/Verificacao/Grupo5/Entrega2/elicitacao/introspeccao/>. Acesso em: 21 de Junho de 2023.

> VAZQUEZ, Carlos E; SIMÔES, Guilherme S. Engenharia de Requisitos Software Orientado ao Negócio. Acesso em: 21 de Junho de 2023.

> REINEHR, Sheila. Engenharia de requisitos. E-book. ISBN 9786556900674. Disponível em: <https://integrada.minhabiblioteca.com.br/#/books/9786556900674/>. Acesso em: 13 jun. 2023.

> Sommerville, Ian. Engenharia de software. 08. ed. São Paulo: Pearson Addison Wesley, 2007.

> Barbosa, S. D. J.; Silva, B. S. da; Silveira, M. S.; Gasparini, I.; Darin, T.; Barbosa, G. D. J. (2021) Interação Humano-Computador e Experiência do usuário. Autopublicação. ISBN: 978-65-00-19677-1 . Acesso em 21 de jun.2023

## Histórico de Versão
|    Data    | Data Prevista de Revisão | Versão |      Descrição       |                    Autor                     |                   Revisor                  |
| :--------: | :----------------------: | :----: | :------------------: | :------------------------------------------: | :----------------------------------------: |
| 21/06/2023 |        21/06/2023        |  1.0   | Criação do documento | [Daniel](https://github.com/daniel-de-sousa) | [Raquel](https://github.com/raqueleucaria) |
