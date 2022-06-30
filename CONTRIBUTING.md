# Como ajudar no Zoonk

Obrigado pelo interesse em ajudar no Zoonk.
Por favor, leia o nosso [código de conduta](./CODE_OF_CONDUCT.md) e toda esta página antes de começar.

## Como organizamos as tarefas

Primeiro precisamos entender [como trabalhamos](./como-trabalhamos) e organizamos as nossas tarefas.
Valorizamos [transparência](./sobre/valores.md#transparência) e [senso de dono](./sobre/valores.md#senso-de-dono).
Isso significa que todas as nossas tarefas são públicas.
Qualquer pessoa pode ver no que estamos trabalhando e estimulada à pegar uma tarefa na qual gostaria de trabalhar.

A [página de projetos](https://github.com/orgs/zoonk/projects?type=beta) mostra todas as tarefas que precisam ser feitas para cada projeto.
As tarefas são organizadas da seguinte maneira:

|Coluna|Descrição|
|------|---------|
|Não Priorizadas|Tarefas que ainda não foram priorizadas. Colocamos aqui ideias e funcionalidades futuras. Uma tarefa estar aqui não significa que vamos trabalhar nela. Nós colocamos aqui todas as ideias que temos para poder mapeá-las. Para propôr uma nova ideia, [comece uma conversa](./como-trabalhamos/gerenciar-conversas.md).|
|Próximas Tarefas|Tarefas aprovadas. Podemos começar a trabalhar nelas imediatamente.|
|Em Progresso|Tarefas que estão em andamento. Quando começamos a trabalhar em uma tarefa, movemos ela de `Próximas tarefas` para esta coluna.|
|Em Revisão|Tarefas que estão parcialmente concluídas ou esperando alguém revisá-las. Depois de [abrir uma pull request](./como-trabalhamos/como-usar-o-github.md) para uma tarefa, movemos a tarefa de `Em Progresso` para cá.|
|Completo|Tarefas que estão completas e publicadas na `branch` principal (`main`). Isso não significa, necessariamente, que elas já foram publicadas para o usuário final.|

## Erros, sugestões, discussões de ideias e opiniões

Nós [iniciamos uma conversa](./como-trabalhamos/gerenciar-conversas.md)
para comunicar erros, sugerir funcionalidades, discutir ideias e dar opiniões.
Quando não sabemos qual o projeto mais adequado para iniciar a conversa,
[abrimos uma discussão aqui no manual da empresa](https://github.com/zoonk/manual/discussions)
para que alguém indique qual seria o lugar mais apropriado.

## Como contribuimos em um projeto do Zoonk

- [Escolhemos um projeto](https://github.com/orgs/zoonk/projects?type=beta) no qual gostaríamos de trabalhar.
- Escolhemos uma tarefa que esteja na coluna `Próximas Tarefas` e não esteja designada a ninguém.
- Designamos (`assign`) essa tarefa para nós mesmos.
- Movemos a tarefa para a coluna `Em Progresso`.
- Criamos uma nova `branch` para trabalhar nessa tarefa.
- [Abrimos uma pull request](./como-trabalhamos/como-usar-o-github.md) quando a tarefa estiver completa.
- Designamos (`assign`) a `pull request` para a pessoa líder do projeto (podemos encontrá-la no arquivo `README` do repositório).
- Movemos a tarefa para a coluna `Em Revisão`.

## Revisando tarefas

Depois de revistarmos uma tarefa (`pull request`), existem dois cenários possíveis:

### Trabalho é aprovado

- Quem revisou a `pull request` publica as alterações usando a opção `stash and merge`.
- Quem revisou move a tarefa da coluna `Em Revisão` para `Completo` caso isso não tenha sido feito automaticamente.

### Trabalho não é aprovado

- Quem revisou deve comunicar claramente quais mudanças precisam ser feitas (e por quê) para que o trabalho seja aprovado.
- Quem revisou deve designar a `pull request` novamente ao autor dela para que as correções sejam feitas.
- Quem revisou deve mover a `pull request` da coluna `Em revisão` para `Em progresso`.
- Quem trabalhou na tarefa deve fazer as alterações solicitadas até que o trabalho seja aprovada pela pessoa revisora.

### Publicando alterações

- Usamos a opção `Squash and merge` para publicar uma `pull request`.
- Removemos toda a descrição gerada automaticamente pelo GitHub para evitar poluir o histórico de alterações.
