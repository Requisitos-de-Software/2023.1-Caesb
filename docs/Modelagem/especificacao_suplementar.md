# Especificação Suplementar

## Introdução
Especificação Suplementar é um documento adicional que fornece informações extras e requisitos específicos para complementar as especificações de um aplicativo, ajudando a garantir que todos os aspectos relevantes sejam considerados durante o desenvolvimento e evitando problemas de requisitos omitidos ou mal compreendidos.

O objetivo é garantir que todos os requisitos importantes sejam identificados e documentados de forma clara, permitindo que a equipe de desenvolvimento e outras partes interessadas tenham uma compreensão abrangente do aplicativo. Sendo um documento que foca na parte de requisitos não funcionais, trabalhando ao lado dos casos de usos que contempla os funcionais, que ao mesclar os dois é possível ter uma cobertura completa de todos os requisitos.

## Metodologia
Para a elaboração desse documento se teve com base o modelo FURPS+, modelo esse que é composto diferentes categorias de requisitos, onde cada um apresenta um conjunto de características que devem ser considerados durante o processo de desenvolvimento, sendo eles apresentados na tabela 1:

Observação: Todas as abreviações são explicadas na tabela 2.

<center>

|Silga|Significado|
|:---:|:-----------:|
|F|Functionality (Funcionalidades)|
|U|Usability (Usabilidade)|
|R|Reliability (Confiabilidade)|
|P|Performance (Desempenho)|
|S|Supportability (Suportabilidade)|
|+|Outra Categoria|

</center>
<p align="center">Tabela 1 - Significado FURPS+.(Fonte: Autores)</p>

<center>

|Abreviação|Significado|
|:--------:|:---------:|
|ST|Requisitos de Storytelling|
|INT|Requisitos de Introspecção|
|ID|Identificador dentro da Categoria|

</center>
<p align="center">Tabela 2 - Legenda.(Fonte: Autores)</p>

## Funcionalidades
Faz referência aos requisitos funcionais, ou seja, relacionados com as funcionalidades do aplicativo, que são capacidade do mesmo realizar as tarefas necessárias. Eles foram levantados na elicitação de requisitos e podem ser vistos todos os elicitados como sua prioridade na parte de [priorização de requisitos](../Elicitacao/priorizacao-FTF.md) e na especificação de [casos de uso](casos_de_uso.md).

## Usabilidade
Faz referência requisitos relacionados à facilidade de uso do sistema pelos usuários, o que inclui aspectos de interface como também metas de usabilidade, como as propostas por Nielsen, o que incluí questões como eficiência de uso, acessibilidade, entre outros. Tendo isso mente, dos requisitos elicitados, a tabela 3 mostram os de Usabilidade:

<center>

|Requisito|Identificador|ID|
|:-------:|:-----------:|::|
|Eu, como usuário, desejo que o tempo necessário para realizar tarefas seja menor que 1 minuto.|ST07|U1|
|Eu, como usuário, desejo que a quantidade de passos para realizar uma tarefa seja menor que 3.|ST08|U2|

</center>
<p align="center">Tabela 3 - Requisitos de Usabilidade. (Fonte: Autores)</p>

## Confiabilidade
Faz referência requisitos relacionados a confiabilidade do aplicativo, ou seja, sua capacidade de funcionar corretamente em diferentes condições, como também como que ele responde a falhas, tanto no quesito de evitar falhas como no de correção de falhas. Tendo isso mente, dos requisitos elicitados, a tabela 4 mostram os de Confiabilidade:

<center>

|Requisito|Identificador|ID|
|:-------:|:-----------:|::|
|O aplicativo deve ser capaz de lidar com pelo menos 150.000 usuários simultâneos sem comprometer o desempenho ou a segurança.|INT11|C1|
|O aplicativo deve ter uma taxa de disponibilidade de pelo menos 99% durante o horário comercial.|INT12|C2|
|O aplicativo deve ter um procedimento de manutenção que permita que o tempo de inatividade seja limitado a no máximo 10 horas por mês.|INT13|C3|

</center>
<p align="center">Tabela 4 - Requisitos de Confiabilidade. (Fonte: Autores)</p>

## Desempenho
Faz referência requisitos relacionados ao desempenho do aplicativo, como o tempo de resposta, tempo de processamento, capacidade de processamento, sua estabilidade e eficiência. Tendo isso mente, dos requisitos elicitados, a tabela 5 mostram os de Desempenho:

<center>

|Requisito|Identificador|ID|
|:-------:|:-----------:|::|
|Eu, como usuário, desejo que o tempo necessário para realizar tarefas seja menor que 1 minuto.|ST07|D1|
|O aplicativo deve ser capaz de lidar com pelo menos 150.000 usuários simultâneos sem comprometer o desempenho ou a segurança.|INT11|D2|


</center>
<p align="center">Tabela 5 - Requisitos de Desempenho. (Fonte: Autores)</p>

## Suportabilidade
Faz referência requisitos relacionados a facilidade de manutenção e suporte do aplicativo ao longo do tempo, o que inclui aspectos como facilidade de instalação, configuração e manutenção, uma documentação adequada, treinamento de usuários e um suporte técnico. Tendo isso mente, dos requisitos elicitados, a tabela 6 mostram os de Suportabilidade:

<center>

|Requisito|Identificador|ID|
|:-------:|:-----------:|::|
|O aplicativo deve ser atualizado frequentemente para garantir a correção de erros, melhorias de desempenho e novos recursos.|INT16|SU1|
|O aplicativo deve funcionar perfeitamente em todos os dispositivos, incluindo computadores.|INT16|SU2|


</center>
<p align="center">Tabela 6 - Requisitos de Suportabilidade. (Fonte: Autores)</p>

## Outra Categoria
O + do FURPS+ indica que outras categorias podem ser adicionadas para complementar as categorias dos requisitos, tendo isso em mente, na elicitação de requisitos se teve 2 que entraram em outra categoria, sendo elas:

### Segurança
Faz referência a requisitos que estão relacionados com a proteção do usuário, tendo como fatores a sua privacidade e a proteção dos dados que ele voluntariamente oferece para o aplicativo para que ele possa utilizar. Tendo isso mente, dos requisitos elicitados, a tabela 7 mostram os de Segurança:

<center>

|Requisito|Identificador|ID|
|:-------:|:-----------:|::|
|Eu, como usuário, desejo que o aplicativo garanta a segurança das minhas informações pessoais e financeiras.|ST03|SE1|


</center>
<p align="center">Tabela 7 - Requisitos de Segurança. (Fonte: Autores)</p>

### Acessibilidade 
Faz referência a requisitos que estão relacionados com o quão acessível é o aplicativo, ou seja, quantos tipos de usuários diferentes ele tem suporte, e se esses usuários com características específicas conseguem não apenas acessar o aplicativo, mas o utilizar normalmente. Tendo isso mente, dos requisitos elicitados, a tabela 8 mostram os de Acessibilidade:

<center>

|Requisito|Identificador|ID|
|:-------:|:-----------:|::|
|O aplicativo deve seguir as diretrizes de acessibilidade da WACG 2.1, garantindo que seja acessível para pessoas com deficiência visual, auditiva ou física.|INT14|A1|


</center>
<p align="center">Tabela 8 - Requisitos de Acessibilidade. (Fonte: Autores)</p>

## Referências

## Histórico de Versão

| Data | Data Prevista de Revisão | Versão | Descrição | Autor | Revisor |
| :--: | :----------------------: | :----: | :-------: | :---: | :-----: |
| 17/05/2023 | 17/05/2023 |  1.0   | Criação do Documento | [Daniel](https://github.com/guilhermekishimoto) e [Caetano](https://github.com/caeslucio) |  [Pedro](https://github.com/pedrobarbosaocb) |
