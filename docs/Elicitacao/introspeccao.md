

## Introdução

A elicitação de requisitos por meio da introspecção envolve a compreensão das propriedades que um sistema deve possuir para alcançar o sucesso desejado. Nesse método, o Engenheiro de Requisitos é desafiado a imaginar as suas próprias preferências e necessidades ao desempenhar uma determinada tarefa, considerando os recursos e equipamentos disponíveis.

## Motivo da Escolha

A escolha do método de introspecção se deve ao fato de estarmos na fase inicial do projeto, o que nos permite explorar nossas próprias ideias e preferências. Além disso, a introspecção é uma técnica rápida e flexível que nos permite avançar de forma ágil.

A seguir, na tabela 1, é possível observar os requisitos elicitados por introspecção.


- INT: Requisitos de <span>Introspecção</span>
- ES: Requisitos da <span>Especificação Suplementar</span>
- RF: Requisitos <span>Funcionais</span>
- RNF: Requisitos não <span>Funcionais</span>

| Identificador | Requisito | Tipo |  Implementado |
| :-----------: |:---------:| :--: | :-----------: |
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
| INT14 | O aplicativo deve seguir as diretrizes de acessibilidade da [WACG 2.1](https://www.w3c.br/traducoes/wcag/wcag21-pt-BR/), garantindo que seja acessível para pessoas com deficiência visual, auditiva ou física.         | RNF |   Não  |
| INT15 |  O aplicativo deve permitir que os usuários escolham entre pelo menos 3 idiomas diferentes           | RNF  |   Não  |
| INT16 |  O aplicativo deve ser atualizado frequentemente para garantir a correção de erros, melhorias de desempenho e novos recursos.         | RNF  |   Não  |
| INT17 |  O aplicativo deve funcionar perfeitamente em todos os dispositivos, incluindo computadores.         | RNF  |   Não  |
<div style="text-align: center">
<p> Tabela 1: Requisitos elicitados (Fonte: autores, 2023).</p>
</div>

A seguir, se tem na tabela 2 os requisitos não funcionais do aplicativo que o aplicativo deve possuir, presente também no artefato de [Especificação Suplementar](../Modelagem/especificacao_suplementar.md).

<center>

| Identificador | Requisito | Tipo |
| :-----------: |:---------:| :--: |
| ES01 | A interface do usuário deve ser intuitiva e de fácil navegação, considerando o perfil diversificado dos usuários. | RNF|
| ES02 | O aplicativo deve fornecer feedback claro e mensagens de erro compreensíveis em caso de problemas. | RNF |
| ES03 | O tempo médio de treinamento para que usuários normais se tornem produtivos em operações básicas do aplicativo não deve exceder 1 hora. | RNF |
| ES04 | O tempo médio para que um usuário solicite a segunda via de uma fatura através do aplicativo deve ser menor que 30 segundos. | RNF |
| ES05 | O aplicativo deve ter uma disponibilidade mínima de 99% durante o horário comercial (das 8h às 18h) para garantir que os usuários possam acessá-lo na maioria das horas de utilização. | RNF |
| ES06 | O MTBF(Mean Time Between Failures) do aplicativo deve ser de pelo menos 170 horas, o que significa que o sistema deve operar continuamente, em média, por pelo menos 170 horas antes de ocorrer uma falha. | RNF |
| ES07 | O MTTR(Mean Time To Repair) do aplicativo que é o tempo máximo permitido para reparo de uma falha do sistema deve ser de 4 horas, ou seja, o sistema deve ser restaurado dentro desse período após uma falha. | RNF |
| ES08 | A precisão das informações exibidas nas faturas dos usuários deve ter uma resolução mínima de 2 casas decimais e estar de acordo com as normas contábeis. |  RNF |
| ES09 | O tempo médio de resposta para o processamento de uma transação no aplicativo não deve exceder 3 segundos. |  RNF |
| ES10 | O aplicativo deve suportar uma taxa mínima de processamento de 100 transações por segundo para atender à demanda dos usuários. |  RNF |
| ES11 | O sistema deve ser capaz de acomodar simultaneamente pelo menos 150.000 usuários conectados ao mesmo tempo, garantindo assim uma capacidade adequada. |  RNF |
| ES12 | Quando houver uma queda na conexão de internet do usuário, o aplicativo deve ser capaz de fornecer um modo de degradação, permitindo a execução de funções básicas offline, como visualização de faturas anteriores. |  RNF |
| ES13 | O aplicativo deve ser otimizado para minimizar o consumo de memória, garantindo um uso eficiente dos recursos do dispositivo do usuário. |  RNF |
| ES14 | O código do aplicativo deve ser desenvolvido de acordo com as diretrizes do padrão de codificação definido pela equipe de desenvolvimento da CAESB. |  RNF |
| ES15 | O aplicativo deve estar disponível para o Android na versão 5.0 |  RNF |
| ES16 | O aplicativo deve estar disponível para o IOS na versão 12.0 |  RNF |

</center>
<p align="center">Tabela 2 - Requisitos não funcionais do aplciativo. (Fonte: autor: Daniel, 2023)</p>



## Referências
> Diretrizes de acessibilidade, disponível no [link](https://www.w3c.br/traducoes/wcag/wcag21-pt-BR/). <br/>

## Histórico de Versão

| Data | Data Prevista de Revisão | Versão | Descrição | Autor | Revisor |
| :--: | :----------------------: | :----: | :-------: | :---: | :-----: |
| 30/04/2023 |        30/04/2023        |  1.0   | Criação do documento   | [Guilherme](https://github.com/guilhermekishimoto) e [Paulo](https://github.com/PauloVictorFS) | [Caetano](https://github.com/caeslucio) |
| 19/05/2023 | 19/05/2023 |  1.1   | Fazendo correção da Revisão | [Daniel](https://github.com/daniel-de-sousa) | [Caetano](https://github.com/caeslucio) |
