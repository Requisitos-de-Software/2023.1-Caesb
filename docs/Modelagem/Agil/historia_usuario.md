# Histórias de Usuário

## Introdução:
Neste artefato, será realizado as histórias de usuário do projeto do aplicativo da CAESB. As histórias de usuário são uma técnica ágil para capturar requisitos e definir as funcionalidades do aplicativo de forma centrada no usuário. Elas permitem que a equipe de desenvolvimento compreenda as necessidades dos usuários e oriente o processo de desenvolvimento para atender a essas necessidades de maneira eficiente.

## Metodologia:
A metodologia adotada para a definição das histórias de usuário segue uma abordagem ágil, permitindo um processo iterativo e colaborativo. Durante a fase de planejamento do projeto, a equipe de desenvolvimento identificou  as funcionalidades-chave através da [instrospecção](../../Elicitacao/introspeccao.md), do [questionário](../../Elicitacao/questionario.md), e do [storytelling](../../Elicitacao/storytelling.md) que serão abordadas. Em seguida, essas funcionalidades foram priorizadas através da [priorização in or out](../../Elicitacao/priorizacaoInOrOut.md), e por fim foram  expressas como histórias de usuário, a partir do [backlog](../Agil/backlog.md) seguindo um formato específico que inclui uma descrição sucinta, critérios de aceitação e uma estimativa de esforço.


## Modelo de História de Usuário:


A tabela 1 abaixo tem como objetivo fornecer uma compreensão detalhada de cada coluna utilizada na documentação das histórias de usuário. Essa tabela serve como um guia de referência para a equipe de desenvolvimento, permitindo uma melhor compreensão das informações contidas nas histórias de usuário.
| Coluna              | Descrição                                                                                                                                                                                                                                                                                            |
|---------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| ID                  | Identificador único da história de usuário. Pode ser um número sequencial ou um código alfanumérico para referência e rastreabilidade.                                                                                                                                                               |
| História de Usuário | Descrição resumida e objetiva da funcionalidade ou requisito que o usuário deseja que seja implementado no sistema. A história de usuário deve ser escrita na perspectiva do usuário, seguindo a estrutura "Eu, como usuário, desejo...".                                                                 |
| Descrição           | Descrição detalhada da história de usuário, fornecendo informações adicionais sobre o contexto, motivação e possíveis detalhes de implementação. Isso ajuda a equipe de desenvolvimento a compreender completamente a história e suas nuances.                                                                 |
| Critérios de Aceitação | Conjunto de condições ou requisitos específicos que devem ser atendidos para que a história de usuário seja considerada completa e aceita pelo cliente ou usuário final. Esses critérios devem ser claros, objetivos, verificáveis e mensuráveis. Eles definem as expectativas de funcionamento da história. |
| Prioridade           | Nível de importância ou prioridade atribuído à história de usuário. Isso ajuda a equipe de desenvolvimento a priorizar as funcionalidades e a planejar as iterações ou sprints do projeto. Pode ser classificado como Alta, Média ou Baixa, ou usar uma escala numérica para uma melhor ordenação.               |

<div style="text-align: center">
<p> Tabela 1: Modelo texto estruturado para descrição de  História de usuário (Fonte: autor, 2023).</p>
</div>

## Motivo de se ter as histórias de usuário no projeto:
As histórias de usuário desempenham um papel fundamental no desenvolvimento do aplicativo CAESB, por diversos motivos:

- Foco no usuário: As histórias de usuário permitem que a equipe de desenvolvimento se concentre nas necessidades reais dos usuários. Ao capturar as funcionalidades em termos de tarefas que os usuários desejam realizar, é possível criar um aplicativo final mais alinhado com suas expectativas e requisitos.
- Comunicação eficaz: As histórias de usuário são uma ferramenta de comunicação poderosa entre a equipe de desenvolvimento e os stakeholders. Elas proporcionam uma maneira clara e concisa de transmitir informações sobre as funcionalidades desejadas, evitando ambiguidades e mal-entendidos.
- Priorização de requisitos: Com as histórias de usuário, é possível priorizar as funcionalidades de acordo com sua importância e valor percebido pelos usuários. Isso permite que a equipe de desenvolvimento foque nas características mais cruciais e entregue valor em incrementos iterativos.
- Estimativas e planejamento: Ao definir as histórias de usuário com critérios de aceitação e uma estimativa de esforço, a equipe de desenvolvimento pode realizar um planejamento mais preciso das atividades e do tempo necessário para implementar cada funcionalidade. Isso contribui para uma alocação de recursos mais eficiente e um cronograma mais realista.

## Critério Para Definição de Prioridade:

A prioridade de cada história de usuário foi determinada considerando três critérios principais:

- Valor para o usuário: Funcionalidades que trazem benefícios significativos, resolvem problemas críticos ou melhoram a usabilidade geral do aplicativo receberam alta prioridade.
- Dependências técnicas: Priorizamos histórias de usuário que não possuíam dependências complexas ou que poderiam desbloquear outras funcionalidades importantes.
- Restrições de prazo: Histórias de usuário que precisavam ser implementadas dentro de um prazo específico foram priorizadas adequadamente, garantindo que os requisitos mais urgentes fossem atendidos primeiro.

Esses critérios foram avaliados pela equipe de desenvolvimento em conjunto com o [perfil do usuário](../../Elicitacao/perfil_usuario.md) do projeto, garantindo que os esforços de desenvolvimento estivessem alinhados com as necessidades e objetivos do projeto.


## Especificações das histórias de usuário
A seguir, apresentamos a tabela 2 com as especificações das histórias de usuário. 


| ID  | História de Usuário                                                      | Critérios de Aceitação                                                                                                                                                                                          | Prioridade |
|-----|-------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|------------|
| US01   | Eu, como usuário, desejo realizar o pagamento da fatura pelo PIX.        | - O sistema deve gerar um código QR ou chave PIX para a fatura selecionada.<br>- Após o pagamento, o sistema deve atualizar o status do pagamento.                                                                  | Alta       |
| US02   | Eu, como usuário, desejo realizar o pagamento da fatura por boleto.      | - O sistema deve gerar um boleto com as informações da fatura selecionada.<br>- Após o pagamento, o sistema deve atualizar o status do pagamento.                                                                | Alta       |
| US03   | Eu, como usuário, desejo efetuar o pagamento da fatura utilizando cartão de débito ou crédito. | - O sistema deve permitir ao usuário cadastrar e selecionar um cartão para efetuar o pagamento.<br>- Após o pagamento, o sistema deve atualizar o status.                                         | Alta       |
| US04   | Eu, como usuário, desejo cadastrar um cartão de crédito/débito para facilitar pagamentos futuros. | - O sistema deve solicitar as informações do cartão e armazená-las de forma segura.<br>- Eu devo poder editar ou excluir os cartões cadastrados.                                                             | Média      |
| US05   | Eu, como usuário, desejo ver o histórico de pagamentos realizados.       | - O sistema deve exibir uma lista ordenada das faturas pagas, mostrando data, valor e método de pagamento utilizado.                                                                                          | Média      |
| US06   | Eu, como usuário, desejo visualizar a segunda via da fatura.              | - O sistema deve permitir ao usuário selecionar uma fatura e gerar a segunda via em formato PDF.<br>- Eu devo poder fazer o download ou visualização online da segunda via.                                     | Baixa      |
| US07   | Eu, como usuário, desejo ver o consumo de água com os custos detalhados. | - O sistema deve exibir informações como volume consumido, tarifa aplicada, valor total e detalhes dos itens da fatura.                                                                                     | Média      |
| US08   | Eu, como usuário, desejo receber notificações sobre faturas próximas do vencimento. | - O sistema deve enviar notificações push, e-mail ou SMS ao usuário com data e valor da fatura pendente.                                                                                                 | Alta       |
| US09   | Eu, como usuário, desejo ativar o pagamento automático da fatura por cartão cadastrado. | - O sistema deve permitir ao usuário selecionar um cartão cadastrado e definir a opção de pagamento automático.<br>- O pagamento deve ser processado automaticamente na data de vencimento.                    | Média      |
| US10  | Eu, como usuário, desejo verificar o andamento da leitura do medidor de água. | - O sistema deve exibir o status da leitura do medidor (realizada, em andamento ou agendada).                                                                                                               | Baixa      |
| US11  | Eu, como usuário, desejo receber notificações sobre a próxima leitura do medidor de água. | - O sistema deve enviar notificações push, e-mail ou SMS ao usuário informando a data estimada da próxima leitura.                                                                                         | Baixa      |
| US12  | Eu, como usuário, desejo visualizar o histórico de consumo de água.      | - O sistema deve exibir uma representação gráfica ou tabela com as informações do consumo de água em diferentes períodos.                                                                                  | Média      |
| US13  | Eu, como usuário, desejo ter acesso aos protocolos de serviço relacionados às solicitações realizadas. | - O sistema deve fornecer ao usuário uma lista dos protocolos de serviço com descrição e status atual.                                                                                                   | Baixa      |
| US14  | Eu, como usuário, desejo receber notificações sobre falta de água na região. | - O sistema deve enviar notificações push, e-mail ou SMS ao usuário informando sobre a interrupção do fornecimento de água e sua duração estimada.                                                          | Alta       |
| US15  | Eu, como usuário, desejo acessar informações sobre a qualidade do lago.  | - O sistema deve fornecer informações claras sobre os fatores que afetam a qualidade da água do lago.                                                                                                     | Média      |
| US16  | Eu, como usuário, desejo solicitar um serviço específico oferecido pela CAESB. | - O sistema deve permitir ao usuário selecionar o tipo de serviço, fornecer informações adicionais e registrar a solicitação.                                                                             | Alta       |
| US17  | Eu, como usuário, desejo solicitar a autoleitura do medidor de água.     | - O sistema deve fornecer orientações claras sobre como realizar a autoleitura.<br>- Eu devo poder informar os valores medidos.                                                                              | Média      |
| US18  | Eu, como usuário, desejo denunciar um vazamento de água para a CAESB.     | - O sistema deve permitir ao usuário fornecer informações sobre a localização e descrição do vazamento.<br>- A denúncia deve ser registrada pela CAESB.                                                    | Alta       |
| US19  | Eu, como usuário, desejo entrar em contato com a equipe de suporte da CAESB. | - O sistema deve fornecer opções de contato, como telefone, e-mail ou chat.<br>- O sistema deve informar prazos de resposta e canais de comunicação eficientes.                                             | Alta       |
| US20  | Eu, como usuário, desejo cadastrar mais de um imóvel em minha conta.       | - O sistema deve permitir adicionar informações de múltiplos imóveis.<br>- Eu devo poder gerenciar cada imóvel de forma individual.                                                                          | Média      |
| US21  | Eu, como usuário, desejo entrar no aplicativo utilizando minhas credenciais de acesso. | - O sistema deve fornecer um campo de login para que eu possa inserir minhas credenciais de acesso.<br>- As credenciais devem ser autenticadas e eu devo ser direcionado para minha área pessoal.    | Alta       |
| US22  | Eu, como usuário, desejo utilizar a autenticação biométrica, como a impressão digital, para acessar o aplicativo. | - O sistema deve fornecer a opção de configurar e habilitar a autenticação biométrica.<br>- Eu devo poder acessar o aplicativo utilizando minha impressão digital.                                      | Baixa      |


<div style="text-align: center">
<p> Tabela 2: Histórias de usuário (Fonte: autor, 2023).</p>
</div>


## Bibliografia

 > Slides Requisitos - aula 15. Milene Serrano e Maurício Serrano. Elicitação, modelagem e análise.

## Histórico de Versão
|    Data    | Data Prevista de Revisão | Versão |      Descrição       |                                                                Autor                                                                 |               Revisor               |
| :--------: | :----------------------: | :----: | :------------------: | :----------------------------------------------------------------------------------------------------------------------------------: | :---------------------------------: |
| 21/05/2023 |        22/05/2023        |  1.0   | Criação do documento | [Paulo](https://github.com/PauloVictorFS) e [Guilherme](https://github.com/guilhermekishimoto) | [Daniel](https://github.com/daniel-de-sousa)|