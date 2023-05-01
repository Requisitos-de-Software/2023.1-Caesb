

# Metodologia

## Introdução

Para aprimorar a agilidade da equipe, e realizar um trabalho com base em uma abordagem sistemática, disciplinada, e quantificável, é necessária a definição de metodologias que auxiliem o desenvolvimento do grupo como todo. Dessa forma, o grupo se apropriou de algumas metodologias e as adaptou conforme as necessidades da equipe.

## Metodologias

### DevOps

O DevOps, apesar de no escopo geral ser uma abordagem de colaboração e integração entre equipes de desenvolvimento de software, também é considerado uma metodologia. Dessa forma, no contexto do grupo, utilizaremos  as seguintes práticas do DevOps:

- **Versionamento**: Criar novas versões do "código" toda vez que houver uma mudança significativa. Dessa forma, utilizamos isso para permitir que o grupo acompanhe as mudanças no documento, e para permitir não apenas uma rastreabilidade maior como também para facilitar a reversão caso seja necessário pelo git.

- **Revisão**: Os chamados "code reviews" são práticas que o grupo utilizou para garantir a qualidade do projeto e para evitar erros. Para isso utilizaremos os pull requests com revisores dos arquivos.

### Scrum

O Scrum é uma metodologia ágil que foi utilizada pelo grupo por fornecer uma estrutura para gerenciamento de projetos que permite a entrega de produtos com mais qualidade através de eficiência e eficácia. Portanto essa metodologia foi utilizada através dos seguintes aspectos:

- **Sprints**: Período de uma semana na qual estabelecemos tarefas que desenvolverão uma versão incremental, no caso uma entrega. Dividimos a sprint em duas etapas, planning e review. Nas segundas as 20 horas, via Teams, planejaremos o que será feito e as quartas as 20 horas, via Teams, terpa a reunião de revisão em que será discutido o produto realizado durante a semana.

- **Refinamento do produto**: Neste processo o objetivo principal é revisar a lista de tarefas, prazos, e necessidades, para que seja definido as prioridades do que deve ser feito e realizado durante a semana. Neste projeto, essa etapa será realizada levando em conta as entregas propostas pelo professor, tomando como prioridade tarefas que são sequênciais (não dependem de outra para funcionar).

## Políticas
Estabelecemos políticas de commit e pull request que irão auxiliar no uso das metodologias citadas acima.

### Política de commit
A política de commit criada estabelece regras sobre as alterações no documento, que trazem informações para o restante da equipe. Garantindo a integridade do documento e facilita a colaboração e a revisão. Criamos algumas tipos de commits que funcionam como etiquetas. Na tabela 1, pode ser visto quais são eles.

**Tipos de Commit**

|   Tipo de commit   |             Título             |       Descrição                                                                                            |
|--------------------|--------------------------------|------------------------------------------------------------------------------------------------------------|
|  "create"            |  Criação inicial               |  Criando novo artefato                                                                              |
|  "fix"             |  Concerto de bugs              |  Concerto de um erro                                                                                       |
|  "style"           |  Estilos                       |  Alterações estéticas no documento (imagens, cores, disposição de espaços...)|     
|  "refactor"        |  Refatoração de código         |  Correção não muito significativa relacionado ao texto                                    |
|  "perf"            |  Melhorias de performace       |  Melhorias relacionadas aos feeedback do professor                                                    |
|  "test"            |  Testes                        |  Adição de testes que estavam faltando ou correção de testes já existentes                                 |
|  "build"           |  Construção de código          |  Mudanças que alteram a estrutura do sistema ou as dependências externas                                   |
|  "ci"              |  Integrações contínuas         |  Alterações em nossos arquivos e scripts de configuração de CI                                             |
|  "revert"          |  Reversões                     |  Reverte um commit anterior                                                                                |


<p><center>Tabela 1: Tipos de commit. (Fonte: autor, 2023).</center></p>

**Regras**

* Os commits devem ser escritos em português, no gerúndio
* Devem ser objetivos e possuírem títulos de no máximo 72 caracteres
* Composição = (tipo de commit): + mensagem

**Exemplo**
    
        git commit -m "create: Adicionando o artefato x"



### Política de Pull Request
**Quando abrir um pull request:**

* Correções triviais (um link quebrado , um erro simples e óbvio, entre outros)
* Começar a trabalhar em uma contribuição que já foi pedida ou discutida através de uma tarefa destinada.

**Como abrir um pull request:**

1. Clone o repositório localmente, realize um pull para manter no estado atual do repositório;
2. Crie uma branch para suas modificações;
3. Se seu pull request for relacionado a  HTML/CSS, inclua imagens de antes e depois para comparação;
4. Teste suas modificações para não realizar mudanças prejudiciais ao projeto;
5. Contribua com o estilo do projeto da melhor forma possível, com os padrões e parâmetros já existentes

**Exemplo**
```
# Descrição
    Descreva as motivações e as mudanças para o pull request.

# Revisão
    - [ ] O Pull Request está vinculado a apenas um assunto.
    - [ ] O título está objetivo.
    - [ ] A descrição está gramaticalmente correta.
    - [ ] A branch está direcionada para a main.
    - [ ] O revisor foi selecionado corretamente.
```

## Referências

> Metodologias ágeis. Disponível no [link](https://www.ivoryit.com.br/2022/05/06/metodologias-de-desenvolvimento-de-software-conheca-as-principais/).

>Devops. Disponível no [link](https://www.redhat.com/pt-br/topics/devops).

## Histórico de Versão
|    Data    | Data Prevista de Revisão | Versão |      Descrição       |                                                                Autor                                                                 |               Revisor               |
| :--------: | :----------------------: | :----: | :------------------: | :----------------------------------------------------------------------------------------------------------------------------------: | :---------------------------------: |
| 14/04/2023 |        15/04/2023        |  1.0   | Criação do documento | [Paulo](https://github.com/PauloVictorFS) e [Raquel](https://github.com/raqueleucaria) | [Pedro](https://github.com/pedrobarbosaocb) |
| 26/04/2023 |        27/04/2023        |  2.0   | Revisão pós entrega 1|[Raquel](https://github.com/raqueleucaria) | [Pedro](https://github.com/pedrobarbosaocb) |