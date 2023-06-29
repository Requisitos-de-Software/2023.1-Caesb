# Forward-From
## Introdução

De acordo com o artigo "Rastreablidade de Requisitos", de Miriam Sayão e Julio Cesar Sampaio do Prado Leite,Edwards M apresenta que "rastreabilidade pode ser definida como sendo a técnica usada para prover relacionamento entre requisitos, arquitetura e implementação final do sistema". Como a rastreabilidade é uma parte importante do processo da qualidade de um Software,esse artefato consiste na apresentação da rastreabilidade "foward-from"

## Metodologia

A rastreabilidade de Requisitos forward-from liga requisitos a artefatos de desenho  (SAYÃO; LEITE, 2005). Dessa forma, para realizar essa rastreabilidade, foi utilizado o Meta-modelo utilizado por Toranzo[1] que apresenta a classificação das informações a serem realizadas em quatro níveis, que visam abranger diferentes tipos de informações relevantes para o acompanhamento e controle do desenvolvimento do sistema:

- Ambiental:  Abrange informações do contexto externo que podem afetar o sistema em desenvolvimento, como mudanças regulatórias e avanços tecnológicos.
- Organizacional:  Inclui informações sobre a organização, como sua missão, objetivos e políticas, que podem impactar os requisitos do sistema.
- Gerencial: Associa tarefas aos requisitos, auxiliando a gestão do projeto.
- Desenvolvimento: Engloba informações sobre os artefatos produzidos no processo de desenvolvimento, como documentos, diagramas e programas.

Além disso, neste meta modelo, o suporte a rastreabilidade identifica os seguintes tipos de elos:


- Satisfação: indica que a classe de origem depende da satisfação dos requisitos da classe de destino.
- Recurso: indica que a classe de origem depende de recursos fornecidos pela classe de destino.
- Responsabilidade: registra a participação, responsabilidade e ação de pessoas sobre os artefatos.
- Representação: captura a representação ou modelagem dos requisitos em outras linguagens ou formatos.
- Alocado: indica que a classe de origem está relacionada à classe de destino, que representa um subsistema.
- Agregação: indica a composição de elementos, ou seja, como diferentes elementos se juntam para formar uma entidade maior.

Sendo assim, os requisitos presentes no artefato serão apresentados através do seguinte template enconstrado na tabela 1 abaixo

| Artefato Analisado    | Classificação do Artefato Analisado |
| :----------------------: | :--------------------: |
| Tipos de Elo | Artefatos Relacionados |
| Satisfação | - |
| Recurso | - |
| Representação | - |
| Alocado | - |
| Agregação | - |
| Responsabilidade|-|
Tabela 1 - Template Forward-from (Fonte: Meta-modelo de Toranzo (TORANZO, 2002)<a id="REF2" href="#anchor_2">^2^</a>.)

## Rastreabilidade
Na Tabela 2 abaixo será apresentado as legendas que serão utilizadas, com os seus respectivos significados

|Legenda | Artefato                  |
| ------- | ------------------------- |
| US      | História usuário          |
| ST      | Storytelling              |
| UC      | Casos de Uso              |
| C       | Cenários                  |
| L       | Léxico                    |
| ES      | Especificação Suplementar |
| INT     | Introspecção              |
| Q       | Questionário              |
| RF      | Requisitos Funcionais     |
| RNF     | Requisitos não Funcionais |

<div style="text-align: center">
<p> Tabela 1: Legenda (Fonte: autor, 2023).</p>
</div>

Dessa forma, nas tabelas 3 a 24 abaixo serão apresentadas a rastreabilidade dos requisitos funcionais 

 

### RF01 
 Visualização da segunda via da fatura

| Tipos de Elo | Artefatos Relacionados |
| :---: | :---: |
| Satisfação | Especificação Suplementar: Usabilidade <br> História de usuário: US06 |
| Recurso | Cenário: Visualização da segunda via da fatura <br>Especificação Suplementar:Confiabilidade,Desempenho,Suportabilidade|
| Representação | <font><figure markdown>![](../../assets/img/fatura.jpg){: style="height:500px;width:250px"} |
| Alocado | Léxico 11: Fatura <br> Épico: EP01 - Pagamento |
| Agregação | Cenário: Visualização da segunda    da via da fatura <br> História de usuário: US06 <br>  Requisitos : Q01,Q03 |
| Responsabilidade|-|

### RF02 
 Solicitar um serviço específico oferecido pela CAESB

| Tipos de Elo | Artefatos Relacionados |
| :---: | :---: |
| Satisfação | Especificação Suplementar: Usabilidade <br> História de usuário: US16 |
| Recurso | Cenário: Solicitação de serviço <br> Especificação Suplementar: Confiabilidade, Desempenho, Suportabilidade |
| Representação |<font><figure markdown>![](./assets/servicos.jpg){: style="height:500px;width:250px"}|
| Alocado | Léxico 19: Serviço <br> Épico: EP04 - Solicitação |
| Agregação | Cenário: Solicitação de serviço <br> História de usuário: US16 <br> Requisitos: Q11, Q12, Q14, Q20 |
| Responsabilidade | - |

### RF03 
 Entrar no aplicativo utilizando credenciais de acesso

| Tipos de Elo | Artefatos Relacionados |
| :---: | :---: |
| Satisfação | Especificação Suplementar: Segurança <br> História de usuário: US21 |
| Recurso | Cenário: Login no aplicativo <br> Especificação Suplementar: Confiabilidade, Desempenho, Suportabilidade |
| Representação | <font><figure markdown>![](./assets/login.jpg){: style="height:500px;width:250px"}} |
| Alocado | Léxico 18: Credenciais <br> Épico: EP05 - Conta |
| Agregação | Cenário: Parte do  Login no aplicativo em todos <br> História de usuário: US21 <br> Requisitos: Q15, Q16, Q19, Q23 |
| Responsabilidade | - |

### RF04 
 Denunciar um vazamento de água para a CAESB
 
| Tipos de Elo | Artefatos Relacionados |
| :---: | :---: |
| Satisfação | Especificação Suplementar: Usabilidade <br> História de usuário: US18 |
| Recurso | Cenário: Denúncia de vazamento <br> Especificação Suplementar: Confiabilidade, Desempenho, Suportabilidade |
| Representação | <font><figure markdown>![](../../assets/vazamento.jpg){: style="height:500px;width:250px"} |
| Alocado | Léxico 13 e 19: Informar e solicitar serviço <br> Épico: EP04 - Solicitaço |
| Agregação | Cenário: Denúncia de vazamento <br> História de usuário: US18 <br> Requisitos: Q12, Q13, Q18, Q22 |
| Responsabilidade | - |

### RF05 
 Visualizar o consumo de água com detalhes
 
| Tipos de Elo | Artefatos Relacionados |
| :---: | :---: |
| Satisfação | Especificação Suplementar: Usabilidade <br> História de usuário: US07 |
| Recurso | Cenário: Visualização do consumo de água <br> Especificação Suplementar: Confiabilidade, Desempenho, Suportabilidade |
| Representação |  <font><figure markdown>![](../../assets/detalhes-consumo.jpg){: style="height:500px;width:250px"} |
| Alocado | Léxico 05 e 07 : Consumo e Consultar <br> Épico: EP01 - Pagamento |
| Agregação | Cenário: Visualização do consumo de água <br> História de usuário: US07 <br> Requisitos: Q06 |
| Responsabilidade | - |



### RF06 
 Visualizar o histórico de consumo de água
 
| Tipos de Elo | Artefatos Relacionados |
| :---: | :---: |
| Satisfação | Especificação Suplementar: Usabilidade <br> História de usuário: US12 |
| Recurso | Cenário: Consulta ao histórico de consumo de água <br> Especificação Suplementar: Confiabilidade, Desempenho, Suportabilidade |
| Representação | <font><figure markdown>![](../../assets/historico-consumo.jpg){: style="height:500px;width:250px"} |
| Alocado |  Léxico 05 e 07 : Consumo e Consultar  <br> Épico: EP02 - Acompanhamento |
| Agregação | Cenário: Consulta ao histórico de consumo de água <br> História de usuário: US12 <br> Requisitos: Q08 |
| Responsabilidade | - |

### RF07 
Receber notificações sobre falta de água na região

| Tipos de Elo | Artefatos Relacionados |
| :---: | :---: |
| Satisfação | Especificação Suplementar: Usabilidade <br> História de usuário: US14 |
| Recurso | Cenário: Recebimento de notificação de falta de água <br> Especificação Suplementar: Confiabilidade, Desempenho, Suportabilidade |
| Representação | <font><figure markdown>![](../../assets/notificacao.jpg){: style="height:500px;width:250px"} |
| Alocado | Léxico 15:Notificação  <br> Épico: EP03 - Detalhamento |
| Agregação | Cenário: Recebimento de notificação de falta de água <br> História de usuário: US14 <br> Requisitos: Q09|
| Responsabilidade | - |

### RF08 
 Realização de pagamento da fatura pelo PIX
 
| Tipos de Elo | Artefatos Relacionados |
| :---: | :---: |
| Satisfação | Especificação Suplementar: Usabilidade <br> História de usuário: US01 |
| Recurso | Cenário: Pagamento via PIX <br> Especificação Suplementar: Confiabilidade, Desempenho, Suportabilidade |
| Representação | <font><figure markdown>![](../../assets/chave-pix.jpg){: style="height:500px;width:250px"} |
| Alocado | Léxico 11, 16, 17: Fatura, Pagamento e Pagar <br> Épico: EP01 - Pagamento |
| Agregação |  História de usuário: US01 <br> Requisitos: Q10 |
| Responsabilidade | - |

### RF09 
 Realização de pagamento da fatura por boleto
 
| Tipos de Elo | Artefatos Relacionados |
| :---: | :---: |
| Satisfação | Especificação Suplementar: Usabilidade <br> História de usuário: US02 |
| Recurso | Cenário: Pagamento via boleto <br> Especificação Suplementar: Confiabilidade, Desempenho, Suportabilidade |
| Representação | <font><figure markdown>![](../../assets/codigo-barra.jpg){: style="height:500px;width:250px"} |
| Alocado | Léxico 11, 16, 17: Fatura, Pagamento e Pagar <br> Épico: EP01 - Pagamento |
| Agregação |  História de usuário: US02 <br> Requisitos: Q12 |
| Responsabilidade | - |

### RF10 
 Receber notificações sobre faturas próximas do vencimento
 
| Tipos de Elo | Artefatos Relacionados |
| :---: | :---: |
| Satisfação | Especificação Suplementar: Usabilidade <br> História de usuário: US08 |
| Recurso | Cenário: Recebimento de notificação de vencimento <br> Especificação Suplementar: Confiabilidade, Desempenho, Suportabilidade |
| Representação | <font><figure markdown>![](../../assets/notificacao.jpg){: style="height:500px;width:250px"} |
| Alocado | Léxico 11 e 15 :Fatura e Notificação <br> Épico: EP01 - Pagamento |
| Agregação | Cenário: Recebimento de notificação de vencimento <br> História de usuário: US08 <br> Requisitos: Q13 |
| Responsabilidade | - |

### RF11 
 Ter acesso aos protocolos de serviço
 
| Tipos de Elo | Artefatos Relacionados |
| :---: | :---: |
| Satisfação | Especificação Suplementar: Usabilidade <br> História de usuário: US13 |
| Recurso | Cenário: Acesso aos protocolos de serviço <br> Especificação Suplementar: Confiabilidade, Desempenho, Suportabilidade |
| Representação | <font><figure markdown>![](../../assets/historico-atendimento.jpg){: style="height:500px;width:250px"} |
| Alocado | Léxico 06 e 19: Suporte e Solicitar serviço <br> Épico: EP03 - Detalhamento |
| Agregação | Cenário: Acesso aos protocolos de serviço <br> História de usuário: US13 <br> Requisitos: Q14 |
| Responsabilidade | - |

### RF12 
Realização de pagamento da fatura por cartão

| Tipos de Elo | Artefatos Relacionados |
| :---: | :---: |
| Satisfação | Especificação Suplementar: Usabilidade <br> História de usuário: US03 |
| Recurso | Cenário: Pagamento via cartão <br> Especificação Suplementar: Confiabilidade, Desempenho, Suportabilidade |
| Representação | - |
| Alocado |  Léxico 11, 16, 17: Fatura, Pagamento e Pagar<br> Épico: EP01 - Pagamento |
| Agregação |   História de usuário: US03 <br> Requisitos: Q15 |
| Responsabilidade | - |

### RF13 
 Receber notificações sobre a próxima leitura do medidor
 
| Tipos de Elo | Artefatos Relacionados |
| :---: | :---: |
| Satisfação | Especificação Suplementar: Usabilidade <br> História de usuário: US11 |
| Recurso | Cenário: Recebimento de notificação de leitura <br> Especificação Suplementar: Confiabilidade, Desempenho, Suportabilidade |
| Representação | - |
| Alocado |Léxico  15 : Notificação <br> Épico: EP02 - Acompanhamento |
| Agregação | Cenário: Recebimento de notificação de leitura <br> História de usuário: US11 <br> Requisitos: Q16 |
| Responsabilidade | - |

### RF14 
Entrar em contato com a equipe de suporte

| Tipos de Elo | Artefatos Relacionados |
| :---: | :---: |
| Satisfação | Especificação Suplementar: Usabilidade <br> História de usuário: US19 |
| Recurso | Cenário: Contato com a equipe de suporte <br> Especificação Suplementar: Confiabilidade, Desempenho, Suportabilidade |
| Representação | <font><figure markdown>![](./assets/suporte.jpg){: style="height:500px;width:250px"} |
| Alocado | Léxico 06: Suporte <br> Épico: EP04 - Solicitação |
| Agregação | Cenário: Contato com a equipe de suporte <br> História de usuário: US19 <br> Requisitos: Q17 |
| Responsabilidade | - |

### RF15 
Utilizar a autenticação biométrica para acessar o aplicativo

| Tipos de Elo | Artefatos Relacionados |
| :---: | :---: |
| Satisfação | Especificação Suplementar: Usabilidade <br> História de usuário: US22 |
| Recurso | Cenário: Acesso ao aplicativo via autenticação biométrica <br> Especificação Suplementar: Confiabilidade, Desempenho, Suportabilidade |
| Representação | - |
| Alocado | Léxico 18: Segurança <br> Épico: EP05 - Conta |
| Agregação | História de usuário: US22 <br> Requisitos: INT01 |
| Responsabilidade | - |

### RF16 
Cadastrar um cartão de crédito/débito

| Tipos de Elo | Artefatos Relacionados |
| :---: | :---: |
| Satisfação | Especificação Suplementar: Usabilidade <br> História de usuário: US04 |
| Recurso | Cenário: Cadastro de um cartão de crédito/débito <br> Especificação Suplementar: Confiabilidade, Desempenho, Suportabilidade |
| Representação | - |
| Alocado | Léxico 03, Léxico 18: Cadastro, Segurança <br> Épico: EP01 - Pagamento |
| Agregação |  História de usuário: US04 <br> Requisitos: INT02 <br> ST04 |
| Responsabilidade | - |



### RF17 
Ativar o pagamento automático da fatura por cartão cadastrado

| Tipos de Elo | Artefatos Relacionados |
| :---: | :---: |
| Satisfação | Especificação Suplementar: Pagamento automático <br> História de usuário: US09 |
| Recurso | Cenário: Ativação do pagamento automático da fatura <br> Especificação Suplementar: Confiabilidade, Desempenho, Suportabilidade |
| Representação | - |
| Alocado | Léxico 16, 17: Pagamento  e Pagar <br> Épico: EP01 - Pagamento |
| Agregação | Cenário: Ativação do pagamento automático da fatura <br> História de usuário: US09 <br> Requisitos: INT06<br> ST05 |
| Responsabilidade | - |

### RF18 
Cadastrar mais de um imóvel em minha conta

| Tipos de Elo | Artefatos Relacionados |
| :---: | :---: |
| Satisfação | Especificação Suplementar: Usabilidade <br> História de usuário: US20 |
| Recurso | Cenário: Cadastro de mais de um imóvel <br> Especificação Suplementar: Confiabilidade, Desempenho, Suportabilidade |
| Representação | - |
| Alocado | Léxico 3: Cadastro  <br> Épico: EP05 - Conta |
| Agregação | Cenário: Cadastro de mais de um imóvel <br> História de usuário: US20 <br> Requisitos: INT07 <br> ST06|
| Responsabilidade | - |

### RF19 
Ver o histórico de pagamentos realizados

| Tipos de Elo | Artefatos Relacionados |
| :---: | :---: |
| Satisfação | Especificação Suplementar: Usabilidade <br> História de usuário: US24 |
| Recurso | Cenário: Visualização do histórico de pagamentos <br> Especificação Suplementar: Confiabilidade, Desempenho, Suportabilidade |
| Representação | <font><figure markdown>![](./assets/historico-pagamento.jpg){: style="height:500px;width:250px"} |
| Alocado | Léxico 07, 11: Consultar e Fatura <br> Épico: EP01 - Pagamento |
| Agregação | História de usuário: US24 <br> Requisitos: INT08 <br> ST02|
| Responsabilidade | - |

### RF20 
Ver detalhes da conta de água

| Tipos de Elo | Artefatos Relacionados |
| :---: | :---: |
| Satisfação | Especificação Suplementar: Usabilidade <br> História de usuário: US15 |
| Recurso | Cenário: Visualização de detalhes da conta de água <br> Especificação Suplementar: Confiabilidade, Desempenho, Suportabilidade |
| Representação | <font><figure markdown>![](./assets/detalhes-consumo.jpg){: style="height:500px;width:250px"} |
| Alocado | Léxico 07, 11: Consultar e Fatura <br> Épico: EP02 - Acompanhamento |
| Agregação | História de usuário: US15 <br> Requisitos: INT09 |
| Responsabilidade | - |

### RF21 
Verificar o andamento da leitura do medidor de água

| Tipos de Elo | Artefatos Relacionados |
| :---: | :---: |
| Satisfação | Especificação Suplementar: Usabilidade <br> História de usuário: US10 |
| Recurso | Cenário: Verificação do andamento da leitura <br> Especificação Suplementar: Confiabilidade, Desempenho, Suportabilidade |
| Representação | - |
| Alocado | Léxico 15: Notificar <br> Épico: EP02 - Acompanhamento |
| Agregação | Cenário: Verificação do andamento da leitura <br> História de usuário: US10 <br> Requisitos: INT10 |
| Responsabilidade | - |

### RF22 
Solicitação da autoleitura do medidor de água

| Tipos de Elo | Artefatos Relacionados |
| :---: | :---: |
| Satisfação | Especificação Suplementar: Usabilidade <br> História de usuário: US17 |
| Recurso | Cenário: Solicitação de autoleitura do medidor de água <br> Especificação Suplementar: Confiabilidade, Desempenho, Suportabilidade |
| Representação | <font><figure markdown>![](./assets/autoleitura.jpg){: style="height:500px;width:250px"} |
| Alocado |Léxico 19: Solicitar Serviço <br> Épico: EP04 - Solicitação |
| Agregação | Cenário: Solicitação de autoleitura do medidor de água <br> História de usuário: US17 <br> Requisitos: Q09 <br> INT10|
| Responsabilidade | - |

Novamente, a natureza e o número exato de requisitos associados dependem do projeto específico e de sua complexidade.


## Bibliografia

 >The Multiview++ Environment: Requirements Traceability from perspective of stakeholders". In: WER' 99 - Workshop em Engenharia de Requisitos, Buenos Aires, Argentina, 1999. Anais. pp. 198-216.

>SAYÃO, Miriam; LEITE, Julio. Rastreabilidade de Requisitos. PUC-Rio: Departamento de Informática, ISSN 0103-9741, Rio de Janeiro, 2005. Disponível em: https://www-di.inf.puc-rio.br/~julio/rastre.pdf. Acesso em: 25 de jun de 2023.


## Histórico de Versão

 Data | Data Prevista de Revisão | Versão | Descrição | Autor | Revisor |
| :--: | :----------------------: | :----: | :-------: | :---: | :-----: |
| 27/06/2023 |        28/06/2023        |  1.0   | Criação do documento   | [Guilherme](https://github.com/guilhermekishimoto) e [Paulo](https://github.com/PauloVictorFS) | [Daniel](https://github.com/daniel-de-sousa) |