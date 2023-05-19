# Especificação Suplementar

## Introdução
Especificação Suplementar é um documento adicional que fornece informações extras e requisitos específicos para complementar as especificações de um aplicativo, ajudando a garantir que todos os aspectos relevantes sejam considerados durante o desenvolvimento e evitando problemas de requisitos omitidos ou mal compreendidos.

O objetivo é garantir que todos os requisitos importantes sejam identificados e documentados de forma clara, permitindo que a equipe de desenvolvimento e outras partes interessadas tenham uma compreensão abrangente do aplicativo. Sendo um documento que foca na parte de requisitos não funcionais, trabalhando ao lado dos casos de usos que contempla os funcionais, que ao mesclar os dois é possível ter uma cobertura completa de todos os requisitos.

## Metodologia
Para a elaboração desse, foi elicitado os requisitos do sistema utilizando o metodo de [introspecção](../Elicitacao/introspeccao.md), e se teve com base o modelo FURPS+, modelo esse que é composto diferentes categorias de requisitos, onde cada um apresenta um conjunto de características que devem ser considerados durante o processo de desenvolvimento, sendo eles apresentados na tabela 1:

Observação: Todas as abreviações são explicadas na tabela 2.

<center>

|Sigla|Significado|
|:---:|:---------:|
|F|Functionality (Funcionalidades)|
|U|Usability (Usabilidade)|
|R|Reliability (Confiabilidade)|
|P|Performance (Desempenho)|
|S|Supportability (Suportabilidade)|
|+|Outra Categoria|

</center>
<p align="center">Tabela 1 - Significado FURPS+. (Fonte: Autor, 2023)</p>

<br>

<center>

|Abreviação|Significado|
|:--------:|:---------:|
|ST|Requisitos de Storytelling|
|INT|Requisitos de Introspecção|
|ES|Requisitos de Especificação Suplementar|
|ID|Identificador dentro da Categoria|

</center>
<p align="center">Tabela 2 - Legenda. (Fonte: Autor, 2023)</p>

## Escopo

Para essa especificação suplementar compreende, como foco da análise, o uso referente ao aplicativo para Android da empresa CAESB e suas interações, comunicações e registro de dados.

## Funcionalidades
Faz referência aos requisitos funcionais, ou seja, relacionados com as funcionalidades do aplicativo, que são capacidade do mesmo realizar as tarefas necessárias. Eles foram levantados na elicitação de requisitos e podem ser vistos todos os elicitados como sua prioridade na parte de [priorização de requisitos](../Elicitacao/priorizacao-FTF.md) e na especificação de [casos de uso](casos_de_uso.md).

## Usabilidade
Faz referência requisitos relacionados à facilidade de uso do sistema pelos usuários, o que inclui aspectos de interface como também metas de usabilidade, como as propostas por Nielsen, o que incluí questões como eficiência de uso, acessibilidade, entre outros. Para atender esse ponto foi identificado que o aplicativo deve atender os seguintes requisitos apresentados na tabela 3:

<center>

|Requisito|Identificador|ID|
|:-------:|:-----------:|::|
|A interface do usuário deve ser intuitiva e de fácil navegação, considerando o perfil diversificado dos usuários.|ES01|U1| 
|O aplicativo deve fornecer feedback claro e mensagens de erro compreensíveis em caso de problemas.|ES02|U2|
|O tempo médio de treinamento para que usuários normais se tornem produtivos em operações básicas do aplicativo não deve exceder 1 hora.|ES03|U3|
|O tempo médio para que um usuário solicite a segunda via de uma fatura através do aplicativo deve ser menor que 30 segundos|ES04|U4|
|Eu, como usuário, desejo que o tempo necessário para realizar tarefas seja menor que 1 minuto.|ST07|U5|
|Eu, como usuário, desejo que a quantidade de passos para realizar uma tarefa seja menor que 3.|ST08|U6|

</center>
<p align="center">Tabela 3 - Requisitos de Usabilidade. (Fonte: Autor, 2023)</p>

## Confiabilidade
Faz referência requisitos relacionados a confiabilidade do aplicativo, ou seja, sua capacidade de funcionar corretamente em diferentes condições, como também como que ele responde a falhas, tanto no quesito de evitar falhas como no de correção de falhas. Para atender esse ponto foi identificado que o aplicativo deve atender os seguintes requisitos apresentados na tabela 4:

<center>

|Requisito|Identificador|ID|
|:-------:|:-----------:|::|
|O aplicativo deve ter uma disponibilidade mínima de 99% durante o horário comercial (das 8h às 18h) para garantir que os usuários possam acessá-lo na maioria das horas de utilização.|ES05|C1|
|O MTBF(Mean Time Between Failures) do aplicativo deve ser de pelo menos 170 horas, o que significa que o sistema deve operar continuamente, em média, por pelo menos 170 horas antes de ocorrer uma falha.|ES06|C2|
|O MTTR(Mean Time To Repair) do aplicativo que é o tempo máximo permitido para reparo de uma falha do sistema deve ser de 4 horas, ou seja, o sistema deve ser restaurado dentro desse período após uma falha.|ES07|C3|
|A precisão das informações exibidas nas faturas dos usuários deve ter uma resolução mínima de 2 casas decimais e estar de acordo com as normas contábeis.|ES08|C4|
|O aplicativo deve ser capaz de lidar com pelo menos 150.000 usuários simultâneos sem comprometer o desempenho ou a segurança.|INT11|C5|
|O aplicativo deve ter uma taxa de disponibilidade de pelo menos 99% durante o horário comercial.|INT12|C6|
|O aplicativo deve ter um procedimento de manutenção que permita que o tempo de inatividade seja limitado a no máximo 10 horas por mês.|INT13|C7|

</center>
<p align="center">Tabela 4 - Requisitos de Confiabilidade. (Fonte: Autor, 2023)</p>

## Desempenho
Faz referência requisitos relacionados ao desempenho do aplicativo, como o tempo de resposta, tempo de processamento, capacidade de processamento, sua estabilidade e eficiência. Para atender esse ponto foi identificado que o aplicativo deve atender os seguintes requisitos apresentados na tabela 5:

<center>

|Requisito|Identificador|ID|
|:-------:|:-----------:|::|
|O tempo médio de resposta para o processamento de uma transação no aplicativo não deve exceder 3 segundos.|ES09|D1|
|O aplicativo deve suportar uma taxa mínima de processamento de 100 transações por segundo para atender à demanda dos usuários.|ES10|D2| 
|O sistema deve ser capaz de acomodar simultaneamente pelo menos 150.000 usuários conectados ao mesmo tempo, garantindo assim uma capacidade adequada.|ES11|D3|
|Quando houver uma queda na conexão de internet do usuário, o aplicativo deve ser capaz de fornecer um modo de degradação, permitindo a execução de funções básicas offline, como visualização de faturas anteriores.|ES12|D4|
|O aplicativo deve ser otimizado para minimizar o consumo de memória, garantindo um uso eficiente dos recursos do dispositivo do usuário.|ES13|D5|
|O aplicativo deve ser capaz de lidar com pelo menos 150.000 usuários simultâneos sem comprometer o desempenho ou a segurança.|INT11|D6|
|Eu, como usuário, desejo que o tempo necessário para realizar tarefas seja menor que 1 minuto.|ST07|D7|



</center>
<p align="center">Tabela 5 - Requisitos de Desempenho. (Fonte: Autor, 2023)</p>

## Suportabilidade
Faz referência requisitos relacionados a facilidade de manutenção e suporte do aplicativo ao longo do tempo, o que inclui aspectos como facilidade de instalação, configuração e manutenção, uma documentação adequada, treinamento de usuários e um suporte técnico. Para atender esse ponto foi identificado que o aplicativo deve atender os seguintes requisitos apresentados na tabela 6:

<center>

|Requisito|Identificador|ID|
|:-------:|:-----------:|::|
|O código do aplicativo deve ser desenvolvido de acordo com as diretrizes do padrão de codificação definido pela equipe de desenvolvimento da CAESB.|ES14|SU1|
|O aplicativo deve estar disponível para o Android na versão 5.0|ES15|SU2|
|O aplicativo deve estar disponível para o IOS na versão 12.0|ES16|SU3|
|O aplicativo deve ser atualizado frequentemente para garantir a correção de erros, melhorias de desempenho e novos recursos.|INT16|SU4|
|O aplicativo deve funcionar perfeitamente em todos os dispositivos, incluindo computadores.|INT17|SU5|


</center>
<p align="center">Tabela 6 - Requisitos de Suportabilidade. (Fonte: Autor, 2023)</p>

## Outra Categoria
O + do FURPS+ indica que outras categorias podem ser adicionadas para complementar as categorias dos requisitos, tendo isso em mente, na elicitação de requisitos se teve 2 que entraram em outra categoria, sendo elas:

### Segurança
Faz referência a requisitos que estão relacionados com a proteção do usuário, tendo como fatores a sua privacidade e a proteção dos dados que ele voluntariamente oferece para o aplicativo para que ele possa utilizar. Tendo isso mente, dos requisitos elicitados, a tabela 7 mostram os de Segurança:

<center>

|Requisito|Identificador|ID|
|:-------:|:-----------:|::|
|Eu, como usuário, desejo que o aplicativo garanta a segurança das minhas informações pessoais e financeiras.|ST03|SE1|


</center>
<p align="center">Tabela 7 - Requisitos de Segurança. (Fonte: Autor, 2023)</p>

### Acessibilidade 
Faz referência a requisitos que estão relacionados com o quão acessível é o aplicativo, ou seja, quantos tipos de usuários diferentes ele tem suporte, e se esses usuários com características específicas conseguem não apenas acessar o aplicativo, mas o utilizar normalmente. Tendo isso mente, dos requisitos elicitados, a tabela 8 mostram os de Acessibilidade:

<center>

|Requisito|Identificador|ID|
|:-------:|:-----------:|::|
|O aplicativo deve seguir as diretrizes de acessibilidade da [WACG 2.1](https://www.w3c.br/traducoes/wcag/wcag21-pt-BR/), garantindo que seja acessível para pessoas com deficiência visual, auditiva ou física.|INT14|A1|


</center>
<p align="center">Tabela 8 - Requisitos de Acessibilidade. (Fonte: Autor, 2023)</p>

## Bibliografia
> SERRANO, Milene - Slides da aula 11. Disponibilizados pelo Professor

> GOIAS, Rocha; SOBRINHO, Francisco - PHP Software Company - Projeto de Software Floricultura Beija-Flor Especificação Suplementar - Versão 101.6

## Histórico de Versão

| Data | Data Prevista de Revisão | Versão | Descrição | Autor | Revisor |
| :--: | :----------------------: | :----: | :-------: | :---: | :-----: |
| 17/05/2023 | 17/05/2023 |  1.0   | Criação do Documento | [Daniel](https://github.com/guilhermekishimoto) e [Caetano](https://github.com/caeslucio) |  [Pedro](https://github.com/pedrobarbosaocb) |
| 19/05/2023 | 19/05/2023 |  1.1   | Fazendo correção da Revisão | [Daniel](https://github.com/guilhermekishimoto) | [Caetano](https://github.com/caeslucio) |
