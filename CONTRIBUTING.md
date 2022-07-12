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
|Pending Specs|Rascunhos. Falta especificar os requirementos da tarefa.|
|Blocked|Tarefas que dependem de outras tarefas para serem realizadas. Quando as outras forem concluídas, mova a tarefa para `Todo`.|
|Todo|Tarefas aprovadas. Pode começar a trabalhar nelas imediatamente.|
|In Progress|Tarefas que estão em andamento. Ao iniciar uma tarefa, mova ela de `Todo` para esta coluna.|
|In Review|Tarefas que estão parcialmente concluídas ou esperando alguém revisá-las. Depois de [abrir uma pull request](./como-trabalhamos/como-usar-o-github.md) para uma tarefa, mova a tarefa de `In Progress` para cá.|
|Done|Tarefas que estão completas e publicadas na `branch` principal (`main`). Isso não significa, necessariamente, que elas já foram publicadas para o usuário final.|

As tarefas que ainda não foram priorizadas não aparecem na [aba principal (`Planned`)](https://github.com/orgs/zoonk/projects/11/views/1).
Mas você pode vê-las na [aba Backlog](https://github.com/orgs/zoonk/projects/11/views/3).
Para sugerir uma nova funcionalidade ou comunicar algum erro, [inicie uma nova conversa](./como-trabalhamos/gerenciar-conversas.md).

## Erros, sugestões, discussões de ideias e opiniões

[Inicie uma conversa](https://github.com/zoonk/manual/discussions/new) para comunicar erros,
sugerir funcionalidades, discutir ideias e dar opiniões.

## Como contribuir em um projeto do Zoonk

- [ ] Navegue até a [página do projeto](https://github.com/orgs/zoonk/projects/11).
- [ ] Escolha uma tarefa que esteja na coluna `Todo` e não esteja designada a ninguém.
- [ ] Designe (`assign`) essa tarefa para você.
- [ ] Mova a tarefa para a coluna `In Progress`.
- [ ] Crie uma nova `branch` para trabalhar nessa tarefa.
- [ ] [Abra uma pull request](./como-trabalhamos/como-usar-o-github.md) quando a tarefa estiver completa.
- [ ] Designe (`assign`) a `pull request` para a pessoa líder do projeto (podemos encontrá-la no arquivo `README` do repositório).
- [ ] Mova a tarefa para a coluna `In Review`.

## Revisando tarefas

Depois de revisar uma tarefa (`pull request`), existem dois cenários possíveis:

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

## Criando tarefas

Siga os passos abaixo para criar uma nova tarefa:

- [ ] Vá na [aba `All` do gerenciador de tarefas do projeto](https://github.com/orgs/zoonk/projects/11/views/2).
- [ ] Use `Ctrl + Barra de espaço` para adicionar um novo item.
- [ ] Selecione o item criado, clique na seta para baixo e, depois, em `Convert to issue`:

![Captura de tela do GitHub mostrando como converter um item em tarefa](https://user-images.githubusercontent.com/4393133/178562514-e66903ec-ed0e-4998-a679-2d6dbeee9cc1.png)

- [ ] Selecione o repositório onde você gostaria de criar a tarefa.
      Caso a tarefa seja um `Epic` (tenha sub-tarefas) e pertença a vários repositórios, selecione `.github`.
- [ ] Na coluna `Status`, selecione um dos itens de acordo com a [tabela acima em `Como organizar tarefas`](#como-organizar-tarefas).
- [ ] Na coluna `Category`, selecione `Epic` caso ela tenha sub-tarefas.
      Caso contrário, selecione `Bug` para erros, `Feature` para uma nova funcionalidade ou
      `Enhancement` para melhorias de uma funcionalidade existente.
- [ ] Na coluna `Assignees`, designe quem vai trabalhar na tarefa (deixe em branco caso não saiba).
      Caso tenha criado um `Epic`, designe você mesmo porque é sua responsabilidade garantir que todas as tarefas sejam completadas.
