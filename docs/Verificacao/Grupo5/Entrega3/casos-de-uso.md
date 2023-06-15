# Casos de Uso
## Introdução
Esse artefato é  uma verificação do artefato de casos de uso produzido pelo grupo 5, Simplenote.  

## Metodologia
A metodologia utilizada para a verificação dos casos de uso é baseada na criação de um checklist, que consiste em uma lista de perguntas e critérios a serem avaliados. Esse checklist foi elaborado com base no Lucidchart Diagrama de caso de uso e nos slides da Aula 11 da professora Milene e Maurício Serrano

## Checklist 
A seguir, na tabela 1, temos o checklist preenchido, da versão 1.1 do artefato, com as respostas para as perguntas do checklist planejado.

| ID  | Descrição                                                                                                                      | Avaliação | Observação |
|-----|--------------------------------------------------------------------------------------------------------------------------------|-----------|----------|
|  01  | O artefato possui uma introdução condizente com o conteudo do texto? | Sim  |    |
|  02  | Todas as bibliografias/referências bibliográficas são utilizadas no texto? | Sim   |  Poderia linkar as bibliografias utlizadas no texto |
|  03  | Todas as tabelas e imagens são chamadas no texto, possuem legendas e fontes? |  Incompleto | As tabelas e imagens não são chamadas no texto  |
|  04  | As metodologias do texto definem de forma condizente as formas e os métodos que o grupo realizou o artefato? | Sim  |     |
| UC01 | O sistema possui um título condizente descrito no topo da caixa limite?                                                                                                       |        Não   |  É opcional, porém ajuda a situar a pessoa que for ver o diagrama |
| UC02   | A caixa de limite do sistema (retângulo utilizado como fronteira do sistema) está definida corretamente, delimitando o escopo dos casos de uso?         |    Sim   |    |
| UC03 | Os atores primários (pessoa, organização ou sistema externo que interage ao sistema) e secundários (pessoa, organização ou sistema externo que reaje ao sistema) presentes estão nomeados?                                                                          |     Sim      |    |
| UC04 | Os atores estão posicionados fora da caixa de limite do sistema? |       Sim    |    |
| UC05 | O ator principal está à direita do da caixa de limite do sistema?                                                    |     Sim      |     |
| UC06 | O ator secundário está à esquerda do da caixa de limite do sistema?                                                    |     SIm      |     |
| UC07 | Os casos de uso estão dentro da caixa limite do sistema no diagrama de casos de uso?                                                            |     Sim      |     |
| UC08   | Os casos de uso estão corretamente rotulados com verbos (no infinitivo) e descrições simples?                           |    Incompleto   |    |
| UC09   | Os casos de uso estão representados por formas ovais?                                      |    Sim   |   |
| UC10  | Os relacionamentos de inclusão (include) entre casos de uso estão corretos, quando aplicável?           |   Não    |     |
| UC11  | Os relacionamentos de extensão (extend) entre casos de uso estão corretos, quando aplicável?            |   Sim    |     |
| UC12  | Os relacionamentos de associação entre atores e casos de uso estão corretos?                            |   Não    |    |
| UC13 | O artefato contém legendas claras para cada símbolo utilizado no diagrama de casos de uso?                                                 |        Sim   |     |
| UC14 | Na especificação, os pré-requisitos (condições que devem ser satisfeitas antes do caso de uso ser executado) estão definidos?                                                                         |     Sim      |     |
| UC15 | Na especificação, as condições de entrada (campos obrigatórios a serem preenchidos, formatos válidos de entrada ou restrições relacionadas aos dados fornecidos pelo usuário) estão especificadas?                                                                   |    Sim       |      |
| UC16 | Na especificação, as condições de saída (resultados esperados, mensagens de retorno ou formatos de saída esperados) estão especificadas?                                                                   |     Sim      |      |
| UC17 | As especificação possuem fluxos principais (sequência de passos ou ações que descrevem a trajetória principal de execução de um caso de uso)?                                                             |     Incompleto      |      |
| UC18 | As especificação possuem fluxos alternativos (caminhos diferentes dos fluxos principais em um caso de uso), quando existentes?                                                             |      Incompleto     |      |
| UC19 | As especificação possuem fluxos de exceção (cenários em que ocorrem erros ou exceções durante a execução de um caso de uso)?                                                             |     Incompleto      |      |
| UC20 | Os casos de uso estão associados a requisitos de usuário ou histórias de usuário específicas?                                 |      Sim     |      |
<p> Tabela 1: Checklist preenchido dos casos de uso (Fonte: autores, 2023).</p>

## Comentários
***UC08 -*** Os casos de uso estão corretamente rotulados com verbos (no infinitivo) e descrições simples?
<br>
- O caso de uso "lista de notas" não possui um verbo. O caso de uso deve ser rotulado com verbos (no infinitivo) e descrições simples, como por exemplo: "Listar notas".

 ***UC10 -*** Os relacionamentos de inclusão (include) entre casos de uso estão corretos, quando aplicável?
<br>
- O caso de uso "criar nota", por exemplo, possui um "include" que está com a cabeça da seta virada para o lado errado. O "include" deve ser feito do caso de uso que inclui para o caso de uso que é incluído.
- As setas de "include" devem ser tracejadas, e não cheias.

 ***UC11 -*** Os relacionamentos de extensão (extend) entre casos de uso estão corretos, quando aplicável?
- As setas de "extends" devem ser tracejadas, e não cheias.

 ***UC12 -*** Os relacionamentos de associação entre atores e casos de uso estão corretos?
 - A conexão entre os atores e os casos de uso não deve possuir seta, pois o ator não é um caso de uso que inclui ou estende outro caso de uso.

***UC17 -*** As especificação possuem fluxos principais (sequência de passos ou ações que descrevem a trajetória principal de execução de um caso de uso)?
<br>
- Possuem o objetivo final dos fluxos e não os fluxos em si. Os fluxos podem ser descritos numerados ou em tópicos, por exemplo.

***UC18 -*** As especificação possuem fluxos alternativos (caminhos diferentes dos fluxos principais em um caso de uso), quando existentes?
<br>
- Possuem o objetivo final dos fluxos e não os fluxos em si. Os fluxos podem ser descritos numerados ou em tópicos, por exemplo.

***UC19 -*** As especificação possuem fluxos de exceção (cenários em que ocorrem erros ou exceções durante a execução de um caso de uso)?
<br>
- Possuem o objetivo final dos fluxos e não os fluxos em si. Os fluxos podem ser descritos numerados ou em tópicos, por exemplo.

## Referências
> [Slides da aula “Requisitos – Aula 11” dos professores Milene Serrano e Maurício Serrano.](https://aprender3.unb.br/pluginfile.php/2523100/mod_resource/content/1/Requisitos%20-%20Aula%20013a.pdf)

> [Lucidchart - Diagrama de caso de uso UML.](https://www.lucidchart.com/pages/pt/diagrama-de-caso-de-uso-uml) 

## Histórico de Versão

| Data | Data Prevista de Revisão | Versão | Descrição | Autor | Revisor |
| :--: | :--: | :--: | :--: | :--: | :--: |
| 14/06/2023 | 14/06/2023 |  1.0   | Criação do documento | [Guilherme](https://github.com/guilhermekishimoto) |  [Pedro](https://github.com/pedrobarbosaocb) |
