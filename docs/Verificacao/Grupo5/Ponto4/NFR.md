# Verificação do NFR Framework do Grupo 5

## Introdução

Este documento apresenta os resultados da inspeção realizada, abrangendo os objetivos, a metodologia utilizada e os principais problemas identificados. Com base nessas informações, serão sugeridas ações corretivas para aprimorar o sistema e garantir sua conformidade com os requisitos estabelecidos.

## Objetivo

Este documento tem como objetivo relatar os resultados das verificações realizadas no artefato [NFR Framework](https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/nfr/) na versão `1.0` da Etapa 4 do [Grupo 5](https://requisitos-de-software.github.io/2023.1-Simplenote/). As verificações foram conduzidas para avaliar a consistência, adequação e abrangência do framework, bem como identificar possíveis lacunas ou melhorias necessárias. Os resultados dessas verificações fornecerão insights valiosos para aprimorar o NFR Framework e contribuir para a qualidade e eficácia dos requisitos não-funcionais do projeto.

## Metodologia

Os resultados da verificação do artefato foram obtidos através das checklists elaboradas na página de [planejamento](). As checklists foram desenvolvidas com base nas perguntas apresentadas e nesta avaliação foram utilizadas as opções **"Sim"**, **"Não"**, **"Incompleto"** ou **"Não se aplica"** para respondê-las. Para indentificação mais rápida das correções necessárias, as opções **"Não"** e **"Incompleto"** estarão em negrito. Além disso, nesta avaliação tivemos a oportunidade de fornecer observações detalhadas em cada pergunta, abordando pontos relevantes. Essas checklists foram fundamentadas na dissertação de mestrado de Reinaldo Antônio da Silva, fornecendo uma base sólida para a avaliação do artefato. Os integrantes do Grupo 4 ([Caetano](https://github.com/caeslucio) e [Daniel](https://github.com/daniel-de-sousa)) serão responsáveis pela avaliação e revisão do artefato, respectivamente. O cronograma seguido para essa atividade já foi detalhado na página de [planejamento]().

## Checklist Estrutural

A Tabela 1 estabelece a checklist com os dados obtidos a partir da verificação da estrutura preliminar do documento. Na sessão de [Feedbacks Específicos](#feedbacks-específicos) será apresentado o detalhamento do conteúdo estudado e a qualidade do artefato em geral.

| ID | Pergunta | Avaliação |Observação|
| - | - | - | - |
| 1 | O artefato possui uma introdução condizente com o conteudo do texto? | Sim |  |
| 2 | Todas as bibliografias/referências bibliográficas são utilizadas no texto? | Sim |  | 
| 3 | O artefato possui o histórico de versões com as datas de criação e revisão, versão, descrição, autor e revisor? | **Incompleto** | Falta data de revisão |
| 4 | Todas as tabelas e imagens são chamadas no texto, possuem legendas e fontes? | **Incompleto** | Tabelas não tem. Não há autor nem fonte nas demais |
| 5 | Os textos estão na norma padrão? | Sim |  |
| 6 | Há referência para fontes externas para validação dos gráficos SIG? | **Não** | Não é citado |
| 7 | Cada SIG possui sua respectiva propagação de Impacto? | **Não** | Especificado abaixo |
| 8 | Os softgoals se refinam até um nível de especificação bem definido? | **Não** | Detalhamento na [ID 8](#-id-8) |
| 9 | Os cartões de especificação representam requisitos não-funcionais verificáveis? | **Não** | Não há cartões de especificação |
| 10 | Os cartões de especificação possuem: Identificador, Classificação, Descrição, Justificativa, Origem, Critério de Ajuste, Dependências, Prioridade, Conflitos e História? | **Não** | Não há cartões de especificação |
| 11 | Os Softgoals NFR estão representados apropriadamente dada a sua definição? | **Incompleto** | Detalhamento [abaixo]() |
| 12 | Os Softgoals de Operacionalização estão representados apropriadamente dada a sua definição? | Sim |  |
| 13 | Os Softgoals de Afirmação estão representados apropriadamente dada a sua definição? | **Não** | Não há Softgoals de afirmação |
| 14 | Os requisitos não-funcionais apresentados nos cartões foram priorizados com algum método? | **Não** | Não apresenta priorização |

<center>

Tabela 1 - Verificação do Planejamento da Avaliação do NFR Framework. Fonte: autor, 2023.

</center>

## Feedbacks Específicos

Inicialmente, declaramos que todas as correções são de cunho técnico e relacionados ao conteúdo estudado para este artefato e a relevância para o projeto, não tendo relação direta com os autores do documento ou com sua competência. Dito isso, o artefato demonstra o que é o NFR Framework e contém alguns grafos que são de fácil compreensão, que fazem sentido, e que podem ser úteis para a equipe e para clientes que possam estar interessados. Em adição, falta algumas informações importantes para um maior aproveitamento do artefato e conexões com outros documentos, que tornariam as especificações dos requisitos não funcionais mais relevantes para a execução de correções e soluções. Dentre as informações esperadas, não é demonstrada a propagação de impacto, os cartões de especificação, e de onde vieram os NFRs especificados. Para um feedback mais específico, segue as seções abaixo.

### - ID 7
**Cada SIG possui sua respectiva propagação de Impacto?**

Como visto no documento, infelizmente não há propagação de impacto em nenhum dos NFRs analizados, como também não é citada a explicação da definição de sendo essencial para analisar e compreender as consequências ou efeitos que uma mudança ou evento pode ter em diferentes partes de um sistema ou processo. É útil para identificar as áreas afetadas, antecipar possíveis problemas e tomar medidas adequadas para mitigar os impactos negativos e maximizar os efeitos positivos.

 | **Não** | Detalhamento na [ID 7](#id-7) |

Os softgoals se refinam até um nível de especificação bem definido? Os cartões de especificação representam requisitos não-funcionais verificáveis?

Por exemplo, no [SIG Usabilidade](https://requisitos-de-software.github.io/2023.1-Booking/modelagem/modelo-agil/nfrFramework/#nfr03-usabilidade), todos os softgoals são extremamente gerais e não apresentam soluções específicas para se levantar bem um Requisito Não-Funcional verificável. Sendo assim, estes deveriam ser refinados ainda mais para cada SIG. Dentro do SIG referido, podemos citar um: "O sistema deve ser claro e de fácil uso". Esse requisito não é verificável, dado que para um requisito ser verificável, vale da seguinte definição: "Um requisito é verificável se existir um processo finito, com custo compensador, que possa ser executado por uma pessoa ou máquina, e que mostre a conformidade do produto final com o requisito"<a id="anchor_2" href="#REF2">^2^</a>.

### ID 10 - Os cartões de especificação possuem: Identificador, Classificação, Descrição, Justificativa, Origem, Critério de Ajuste, Dependências, Prioridade, Conflitos e História?

Não apresenta as dependências, as histórias e os conflitos. A história é sua data de criação, as dependências são os requisitos relacionados e os conflitos são os requisitos que causam conflitos, sendo estes mais visíveis na propagação de impactos<a id="anchor_1" href="#REF1">^1^</a>. Além disso, a definição de alguns, por exemplo, o de Usabilidade, não está de acordo com a literatura utilizada para validar dentro do projeto. De acordo com a dissertação, Usabilidade é: "um requisito que especifica a interação do usuário final com o sistema e o esforço necessário para aprender, operar, preparar a entrada e interpretar a saída do sistema"<a id="anchor_3" href="#REF3">^3^</a>.

### ID 13 - Os Softgoals de Afirmação estão representados apropriadamente dada a sua definição?

Um dos motivos da falta de refinamento dos softgoals é a ausência de Softgoals de Afirmação. Os softgoals de afirmação são fatores delimitantes dentro de um domínio, ou seja, servem como um filtro para as características<a id="anchor_4" href="#REF4">^4^</a>.


### ID 14 - Os requisitos não-funcionais apresentados nos cartões foram priorizados com algum método?

Provavelmente todos os requisitos presentes nos cartões possuem relações com requisitos já elicitados e priorizados pelo seu grupo anteriormente. Por exemplo, a relação entre Desempenho e o requisito NFST02 priorizado pelo [Three Level-Scale](https://requisitos-de-software.github.io/2023.1-Booking/elicitacao/threeLevelScale/), cuja descrição é: "o aplicativo deve ser rápido e responsivo, com tempo de carregamento mínimo e tempos de resposta rápidos".


## Sugestões de Correções

- Refinar os softgoals.
- Criar ao menos 5 cartões de especificação para requisitos não-funcionais mais específicos.
- Utilizar softgoals de afirmação para ajudar o processo de refinação.
- Tomar cuidado com a verificabilidade dos requisitos ao refiná-los, evite ambiguidades.
- Reaproveitar priorizações já feitas para priorizar os RNF dos cartões.

## Bibliografia

>SILVA, Reinaldo Antônio da. NFR4ES: Um Catálogo de Requisitos Não-Funcionais para Sistemas Embarcados. 2019. Disponível em: https://repositorio.ufpe.br/handle/123456789/34150. Acesso em: 10 de junho de 2023.

>SERRANO, Milene; SERRANO, Mauricio. Slides da aula de Requisitos – Aula 17. 2019. Acesso em: 10 de junho de 2023.

>CHUNG, L.; NIXON, B. A.; YU, E.; MYLOPOULOS, J. Non-functional requirements in software engineering. Springer Science & Business Media: [s.n.], 2000. v. 5.

>MESQUITA, Renato Cardoso. Engenharia dos requisitos de software. Departamento de Eng. Elétrica da UFMG, Belo Horizonte, 2019. Disponível em: <https://www.cin.ufpe.br/~joa/menu_options/school/cursos/engsoft/aulas/requisitos-conceitos.pdf>. Acesso em: 09/06/2023.

>MARIZA, D.; ZOWGHI, D.; NURMULIANI, N. An investigation into the notion of non-functional requirements. In: Proceedings of the 2010 ACM Symposium on Applied Computing. ACM: [s.n.], 2010. p. 311–317.

## Histórico de Versão

| Data | Data Prevista de Revisão | Versão | Descrição | Autor | Revisor |
| :-: | :-: | :-: | :-: | :-: | :-: |
| 22/05/2023 | 23/05/2023 |  1.0   | Criação do Documento | [Caetano](https://github.com/caeslucio) | [Paulo](https://github.com/PauloVictorFS) |