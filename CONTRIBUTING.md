# Como ajudar no Zoonk

Obrigado pelo interesse em ajudar no Zoonk.
Por favor, leia o nosso [código de conduta](./CODE_OF_CONDUCT.md) e toda esta página antes de começar.

## Como organizar tarefas

Primeiro entenda [como trabalhamos](./como-trabalhamos) e organizamos as nossas tarefas.
Valorizamos [transparência](./sobre/valores.md#transparência) e [senso de dono](./sobre/valores.md#senso-de-dono).
Isso significa que todas as tarefas são públicas.
Qualquer pessoa pode ver no que estamos trabalhando e é estimulada à pegar uma tarefa na qual gostaria de trabalhar.

A [página do projeto](https://github.com/orgs/zoonk/projects/11) mostra todas as tarefas que precisam ser realizadas.
As tarefas são organizadas da seguinte maneira:

|Coluna|Descrição|
|------|---------|
|Todo|Tarefas aprovadas. Pode começar a trabalhar nelas imediatamente.|
|In Progress|Tarefas que estão em andamento. Ao iniciar uma tarefa, mova ela de `Todo` para esta coluna.|
|In Review|Tarefas que estão parcialmente concluídas ou esperando alguém revisá-las. Depois de [abrir uma pull request](./como-trabalhamos/como-usar-o-github.md) para uma tarefa, mova a tarefa de `In Progress` para cá.|
|Done|Tarefas que estão completas e publicadas na `branch` principal (`main`). Isso não significa, necessariamente, que elas já foram publicadas para o usuário final.|

As tarefas que ainda não foram priorizadas não aparecem na aba principal (`Planned`).
Mas você pode vê-las na aba `Backlog`.
Para sugerir uma nova funcionalidade ou comunicar algum erro, [inicie uma nova conversa](./como-trabalhamos/gerenciar-conversas.md).

## Erros, sugestões, discussões de ideias e opiniões

[Inicie uma conversa](https://github.com/zoonk/manual/discussions/new) para comunicar erros,
sugerir funcionalidades, discutir ideias e dar opiniões.

## Como contribuir em um projeto do Zoonk

- Navegue até a [página do projeto](https://github.com/orgs/zoonk/projects/11).
- Escolha uma tarefa que esteja na coluna `Próximas Tarefas` e não esteja designada a ninguém.
- Designamos (`assign`) essa tarefa para nós mesmos.
- Movemos a tarefa para a coluna `Em Progresso`.
- Criamos uma nova `branch` para trabalhar nessa tarefa.
- [Abrimos uma pull request](./como-trabalhamos/como-usar-o-github.md) quando a tarefa estiver completa.
- Designamos (`assign`) a `pull request` para a pessoa líder do projeto (podemos encontrá-la no arquivo `README` do repositório).
- Movemos a tarefa para a coluna `Em Revisão`.

## Revisando tarefas

Depois de revistar uma tarefa (`pull request`), existem dois cenários possíveis:

### Trabalho é aprovado

- **Pessoa Revisora:** Depois de aprovar a `pull request`, publique as alterações usando a opção `squash and merge`.
- **Automático:** A tarefa passa do status `In Review` para `Done`.

### Trabalho não é aprovado

- **Pessoa Revisora:** Comunique claramente quais mudanças precisam ser feitas (e por quê) para que o trabalho seja aprovado.
- **Pessoa Revisora:** Marque a opção `Request changes`. Isso fará com que a tarefa volte para a coluna `In Progress`.
- **Pessoa revisora:** Designe a `pull request` novamente à pessoa autora para que ela trabalhe nas correções desejadas.
- **Pessoa autora:** Faça as correções (ou comente as sugestões caso não concorde com elas) até que a `pull request` seja aprovada.

### Publicando alterações

- Use a opção `Squash and merge` para publicar uma `pull request`.
- Remova toda a descrição gerada automaticamente pelo GitHub para evitar poluir o histórico de alterações.
