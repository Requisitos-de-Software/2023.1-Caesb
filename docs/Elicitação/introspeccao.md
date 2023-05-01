

## Introdução

A elicitação de requisitos por meio da introspecção envolve a compreensão das propriedades que um sistema deve possuir para alcançar o sucesso desejado. Nesse método, o Engenheiro de Requisitos é desafiado a imaginar as suas próprias preferências e necessidades ao desempenhar uma determinada tarefa, considerando os recursos e equipamentos disponíveis.

## Motivo da Escolha

A escolha do método de introspecção se deve ao fato de estarmos na fase inicial do projeto, o que nos permite explorar nossas próprias ideias e preferências. Além disso, a introspecção é uma técnica rápida e flexível que nos permite avançar de forma ágil.

A seguir, na tabela 1, é possível observar os requisitos elicitados por introspecção.

| Identificador | Requisito | Tipo |  Implementado |
| :----------: |:----------:| :------: | :-----------: |
| INT01 | O aplicativo deve permitir que os usuários se registrem para criar uma conta        | RF  |   Sim  |
| INT02 | O aplicativo deve permitir que os usuários visualizem o historico de consumo de água       | RF  |   Sim  |
| INT03 |  O aplicativo deve permitir que os usuários visualizem as faturas dos pagamentos       | RF  |   Sim  |
| INT04 | O aplicativo deve permitir a emissão de notificações sobre informações relevantes ao usuário   | RF  |   Sim  |
| INT05 | O aplicativo deve permitir que o usuário pague suas contas de água utilizando cartão de crédito ou débito         | RF  |   Sim  |
| INT06 | O aplicativo deve permitir que o usuário pague suas contas de água utilizando chave pix      | RF  |   Sim  |
| INT07 | O aplicativo deve permitir que os usuários entrem em contato com a equipe de suporte da CAESB para resolver problemas e fazer perguntas                | RF  |   Sim  |
| INT08 | O aplicativo deve permitir que os usuários gerem relatórios detalhados sobre seu consumo de água e os custos associados ao consumo                 | RF  |   Sim  |
| INT09 | O aplicativo deve permitir que os usuários alterem as informações cadastradas no sistema    | RF |  Sim |
| INT10 | O aplicativo deve permitir que os usuários visualizem um histórico detalhado dos serviços solicitados | RF |   Sim  |
| INT11 | O aplicativo deve ser capaz de lidar com pelo menos 150.000 usuários simultâneos sem comprometer o desempenho ou a segurança  | RNF |   Sim  |
| INT12 | O aplicativo deve ter uma taxa de disponibilidade de pelo menos 99% durante o horário comercial                  | RNF  |   Sim  |
| INT13 | O aplicativo deve ter um procedimento de manutenção que permita que o tempo de inatividade seja limitado a no máximo 10 horas por mês. |RNF |   Sim  |
| INT14 | O aplicativo deve seguir as diretrizes de acessibilidade da WACG 2.1 [[1]](https://www.w3c.br/traducoes/wcag/wcag21-pt-BR/), garantindo que seja acessível para pessoas com deficiência visual, auditiva ou física.         | RNF |   Sim  |
| INT15 |  O aplicativo deve permitir que os usuários escolham entre pelo menos 3 idiomas diferentes           | RNF  |   Não  |
| INT16 |  O aplicativo deve ser atualizado frequentemente para garantir a correção de erros, melhorias de desempenho e novos recursos.         | RNF  |   Não  |
 INT16 |  O aplicativo deve funcionar perfeitamente em todos os dispositivos, incluindo computadores.         | RNF  |   Não  |
<div style="text-align: center">
<p> Tabela 1: Requisitos elicitados (Fonte: autor, 2022).</p>
</div>


## Referências
[1] Diretrizes de acessibilidade, disponível no [link](https://www.w3c.br/traducoes/wcag/wcag21-pt-BR/). <br/>

## Histórico de Versão

|    Data    | Data Prevista de Revisão | Versão |      Descrição       |                                                                Autor                                                                 |               Revisor               |
| :--------: | :----------------------: | :----: | :------------------: | :----------------------------------------------------------------------------------------------------------------------------------: | :---------------------------------: |
| 30/04/2023 |        30/04/2023        |  1.0   | Criação do documento   | [Guilherme](https://github.com/guilhermekishimoto) e [Paulo](https://github.com/PauloVictorFS) | [Caetano](https://github.com/caeslucio) |