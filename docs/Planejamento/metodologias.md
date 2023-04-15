

# Metodologia

## Introdução

Para aprimorar a agilidade da equipe, e realizar um trabalho com base em uma abordagem sistemática, disciplinada, e quantificável, é necessária a definição de metodologias que auxiliem o desenvolvimento do grupo como todo. Dessa forma, o grupo utilizou-se das seguintes metodologias:

## DevOps:

O DevOps, apesar de no escopo geral ser  uma abordagem de colaboração e integração entre equipes de desenvolvimento de software, também é considerado uma metodologia. Dessa forma, no contexto do grupo, utilizaremos  as seguintes práticas do DevOps

- Versionamento do código: Essa técnica é o processo de criar novas versões do código toda vez que houver uma mudança significativa neste. Dessa forma, o grupo utilizou isso para permitir que o grupo acompanhe as mudanças no código, e para permitir não apenas uma rastreabilidade maior como também para facilitar a reversão caso seja necessário. Para isso utilizaremos o git.

- Revisão de código: Os chamados "code reviews" são práticas que o grupo utilizou para garantir a qualidade do código e para evitar bugs. Para isso utilizaremos os pull requests conforme template apresentado na pagina do github.

- Gestão de problemas: Também conhecido como "issue tracking", esse processo é realizado para permitir que os integrantes do grupo registrem coisas e solicitem funcionalidades e questões relacionadas ao produto. Sendo assim, o grupo utilizou o github para acompanhar e priorizar as demandas do projeto.

## Scrum:

O Scrum é uma metodologia ágil que foi utilizada pelo grupo por fornecer uma estrutura para gerenciamento de projetos que permite a entrega de produtos com mais qualidade através de eficiência e eficácia. Portanto essa metodologia foi utilizada através dos seguintes aspectos:

- Sprints: A ideia principal de sprints é a definição de um período de tempo definido que os integrantes da equipe trabalharão em uma tarefa específica. Em vista disso, o grupo utilizou sprints de duração semanal que ocorrerá em duas etapas. No inicio da semana (segunda 20:00) ocorre uma reunião que englobará todo o planejamento do que deve ser feito na semana (planning), para que todos saibam qual tarefa deve ser realizada e finalizada durante a semana. Já no final da semana, ocorre a reunião de revisão (quarta feira 20:00) do que foi feito durante a sprint, em que será discutido o produto realizado durante a semana (review)

- Refinamento do produto: Neste processo o objetivo principal é revisar a lista de tarefas, prazos, e necessidades, para que seja definido as prioridades do que deve ser feito e realizado durante a semana. Neste projeto, essa etapa será realizada levando em conta as entregas propostas pelo professor, tomando como prioridade tarefas que são sequênciais (não dependem de outra para funcionar).

## Política de commit
A política de commit é essencial no desenvolvimento de software em equipe, pois estabelece regras claras sobre como as alterações no código-fonte devem ser registradas e compartilhadas com o resto da equipe. Com o objetivode de garantir a integridade do código, facilita a colaboração e a revisão de alterações criamos regras e definimos tipos de commits.

**Tipos de Commit**

|   Tipo de commit   |             Título             |       Descrição                                                                                            |
|--------------------|--------------------------------|------------------------------------------------------------------------------------------------------------|
|  "feat"            |  Features                      |  Nova Feature                                                                                              |
|  "fix"             |  Concerto de bugs              |  Concerto de um bug                                                                                        |
|  "docs"            |  Documentação                  |  Documente apenas as mudanças                                                                              |
|  "style"           |  Estilos                       |  Alterações que não afetam significamente o código (espaço em branco, formatação, falta de ponto e vírgula)|     
|  "refactor"        |  Refatoração de código         |  Uma alteração de código que não corrige um bug nem adiciona um recurso                                    |
|  "perf"            |  Melhorias de performace       |  Mudança de código que aumenta a performace do software                                                    |
|  "test"            |  Testes                        |  Adição de testes que estavam faltando ou correção de testes já existentes                                 |
|  "build"           |  Construção de código          |  Mudanças que alteram a estrutura do sistema ou as dependências externas                                   |
|  "ci"              |  Integrações contínuas         |  Alterações em nossos arquivos e scripts de configuração de CI                                             |
|  "chore"           |  Tarefas                       |  Outras mudanças que não midificam src ou os arquivos de testes                                            |
|  "revert"          |  Reversões                     |  Reverte um commit anterior                                                                                |
|  "initial"         |  Inicial                       |  Commit inicial                                                                                            |

**Regras**
* Os commits devem ser escritos em português, no gerúndio
* Devem ser objetivos e possuírem títulos de no máximo 72 caracteres
* Composição = (tipo de commit): + mensagem

**Exemplo**

```
git commit -m "docs: Adicionando arquivo x"
```


## Política de Pull Request
**Quando abrir um pull request:**

É necessário abrir um pull request nas seguintes situações:

* enviar correções triviais (um link quebrado , um erro simples e óbvio, entre outros)
* começar a trabalhar em uma contribuição que já foi pedida ou discutida através de uma issue

**Como abrir um pull request:**

* clone o repositório localmente, realize um pull para manter no estado atual do repositório
* crie uma branch para suas modificações
* referencia alguma issue relevante ou documentação auxiliar para seu pull request (como por exemplo "fechando #21")
* se seu pull request for relacionado a  HTML/CSS, inclua imagens de antes e depois para comparação 
* teste suas modificações para não realizar mudanças prejudiciais ao projeto
* contribua com o estilo do projeto da melhor forma possível , com os padrões e parâmetros já existentes

para criar um pull request, utilize o exemplo abaixo:

**Exemplo de pull request:**
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

> Metodologias ágeis - <a href="https://www.ivoryit.com.br/2022/05/06/metodologias-de-desenvolvimento-de-software-conheca-as-principais/">www.ivoryit.com.br/</a>
> Devops - <a href="https://www.redhat.com/pt-br/topics/devops">www.redhat.com/pt-br</a>

## Histórico de Versão
|    Data    | Data Prevista de Revisão | Versão |      Descrição       |                                                                Autor                                                                 |               Revisor               |
| :--------: | :----------------------: | :----: | :------------------: | :----------------------------------------------------------------------------------------------------------------------------------: | :---------------------------------: |
| 14/04/2023 |        15/04/2023        |  1.0   | Criação do documento | [Paulo](https://github.com/PauloVictorFS) e [Raquel](https://github.com/raqueleucaria) | [Pedro](https://github.com/pedrobarbosaocb) |