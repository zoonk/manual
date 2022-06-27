# Como usar o GitHub

Este guia é focado, principalmente, para quem não trabalha com desenvolvimento de software porque
existem mais recursos e tutoriais sobre como usar o Git e GitHub para desenvolvedores.
Se você é um desenvolvedor júnior ou se não trabalha com desenvolvimento de software,
vale a pena dar uma olhada no [guia do GitHub](https://docs.github.com/pt/get-started/quickstart/hello-world)
e pesquisar alguns tutoriais online,
como [este do Tableless](https://tableless.com.br/tudo-que-voce-queria-saber-sobre-git-e-github-mas-tinha-vergonha-de-perguntar/)
ou [este outro do próprio GitHub](https://github.com/git-guides/install-git) (está em inglês).

Neste guia vamos focar em como usar o GitHub para gerenciar o nosso trabalho no Zoonk.

## O que é Git?

O `Git` é uma ferramenta para gerenciar versões diferentes de arquivos.
Por exemplo, ao invés de ter `meu_arquivo_v1`, `meu_arquivo_v2`, etc.,
temos apenas um arquivo e podemos ver todo o histórico de alterações dele usando o Git.

## O que é o GitHub?

O `GitHub` é um site que nos permite utilizar o `Git` de forma mais fácil.

## Qual a diferença entre Git e GitHub?

O `Git` é a tecnologia que permite ter o controle de versão dos arquivos.
O `GitHub` é um serviço que utiliza essa tecnologia.
Essas duas tecnologias são bastante utilizadas em desenvolvimento de software.
Mas, aqui no Zoonk, também utilizamos elas para a nossa documentação e para gerenciar os nossos processos.

## Por que usamos o GitHub

Usamos o GitHub porque acreditamos ser a forma mais fácil de tornar aberto tudo o que fazemos por aqui.
Ele nos permite tornar os nossos processos mais transparentes, organizar as nossas conversas
e fazer tudo isso de forma assíncrona em um só lugar.

Não estamos dizendo que o GitHub é perfeito.
Existem outras ferramentas mais completas para o gerenciamento de tarefas e também para fórum de discussões.
Mas toda escolha tem prós e contras.
No momento, acreditamos que ter todas as nossas informações em um mesmo lugar (o GitHub)
nos ajuda a atingir os nossos objetivos e está mais alinhado com os nossos [valores](../sobre/valores.md), principalmente no quesito transparência.
Seria mais difícil ter o mesmo nível de transparência e agilidade utilizando várias ferramentas diferentes porque
aumentaria a complexidade do projeto e os [nossos recursos são bem limitados](https://github.com/zoonk/finances).

## Principais conceitos

- **Projects**: Onde gerenciamos as nossas tarefas.
- **Repositories**: Onde armazenamos os documentos dos nossos projetos.
- **Issues**: Tarefas que precisamos executar.
- **Branch**: É como se fosse uma pasta onde armazenamos, de forma temporária, as alterações que estamos fazendo para uma tarefa.
- **Pull request**: Onde fazemos uma solicitação para publicar as nossas alterações na `branch` principal (`main`).
- **Discussions**: Um fórum onde estão todas as nossas conversas e decisões sobre um projeto.

## Como fazer alterações

Este guia vai focar em como você pode alterar arquivos utilizando o site github.com.
Porém, você também pode utilizar as seguintes ferramentas para usos mais avançados (não obrigatório):

- [GitHub Desktop](https://desktop.github.com/)
- [GitHub CLI](https://cli.github.com/)
- [Git CLI](https://github.com/git-guides/install-git)
- [VS Code](https://code.visualstudio.com/)
- [GitHub Codespaces](https://github.com/features/codespaces)

### Criando uma branch

A primeira coisa que você precisa fazer quando começa a trabalhar em uma tarefa (`issue`) é [criar uma nova branch](https://docs.github.com/pt/desktop/contributing-and-collaborating-using-github-desktop/making-changes-in-a-branch/managing-branches).
Costuma ser útil dar um nome descritivo para as `branches`, incluindo o seu nome de usuário e o número de identificação da tarefa.
Por exemplo: `meunomedeusuario/42-atualizar-o-guia-do-github`.

No lado direito da página da tarefa (`issue`) tem um link que permite criar uma `branch` diretamente daquela página:

![Captura de tela do GitHub mostrando o link para criar uma nova branch](https://user-images.githubusercontent.com/4393133/176026827-016a975f-f49d-462c-9a27-a00b2f64e4f6.png)

### Atualizando um documento

Depois de criar uma `branch`, navegue até o documento que você gostaria de atualizar.
Por exemplo: Este documento, que você está lendo, está localizado na pasta `como-trabalhamos` com o nome de `como-usar-o-github.md`.

O GitHub tem um botão com o ícone de um lápis que você pode utilizar para editar a página.
Clique nele e selecione a opção `Edit this file`:

<img alt="Captura de tela do GitHub mostrando a opção 'Edit this file'" src="https://user-images.githubusercontent.com/4393133/175760174-2da05369-b088-43e5-abc7-5070efa32f4a.png">

O GitHub vai abrir o editor de texto com o conteúdo do documento.
Faça todas as alterações necessárias.
O editor está usando o [formato Markdown](https://docs.github.com/pt/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax) (por isso, a extensão `.md` no final do documento).

Ao terminar de editar o documento, clique no botão `Commit changes` para salvar as suas modificações:

<img alt="Captura de tela do GitHub mostrando a opção 'commit changes'" src="https://user-images.githubusercontent.com/4393133/175760264-4386974a-eb66-4827-a981-a2fe0f3b47df.png">

Essas alterações serão salvas na `branch` que você criou.
Elas ainda não foram publicadas na `branch` principal (`main`).
Se você precisa editar mais documentos, siga os mesmos passos acima.
Caso contrário, pule para a sessão "[Publicando alterações](#publicando-alterações)" abaixo.

### Adicionando documentos

Antes de adicionar um novo documento, tenha certeza que você criou uma nova `branch`
e que você esteja trabalhando nessa `branch` ao invés da principal (`main`).

Depois de criar a sua `branch`, você pode adicionar um novo documentos clicando nos botões `Add file` e `Create new file`.
Se você já tiver criado os documentos no seu computador e não quiser utilizar o editor do GitHub,
pode usar a opção `Upload files` para enviar os arquivos do seu computador para o repositório no GitHub.

<img alt="Captura de tela do GitHub mostrando a opção para criar um arquivo" src="https://user-images.githubusercontent.com/4393133/175760441-23dbdf2b-71af-4020-b9ce-7fc79571436d.png">

Antes de começar a digitar o conteúdo do documento, lembre-se de dar um nome para ele:

<img alt="Captura de tela do GitHub mostrando o campo para nomear um arquivo" src="https://user-images.githubusercontent.com/4393133/175760469-2a4c19c0-4371-4ac5-abc7-c8566170863d.png">

Você pode adicionar esse documento a uma pasta específica digitando `/` depois do nome da pasta.
Por exemplo: `sobre/valores/README.md` criaria um documento com o nome `README.md` na pasta `sobre/valores`.
Se a pasta `sobre` e/ou `valores` não existir, o GitHub vai criá-la.

Após nomear o documento, digite o conteúdo desejado e clique no botão `Commit changes` para salvar o documento.
Lembrando que o arquivo será salvo apenas na sua `branch` por enquanto.
Você ainda precisará abrir uma `pull request` para solicitar que as suas alterações sejam publicadas.

### Apagando um documento

Para apagar um documento você pode seguir os mesmos passos utilizados para atualizar algo.
Porém, você precisará clicar no ícone de lixeira ao invés de clicar no de lápis.

### Publicando alterações

Como falamos na parte dos [principais conceitos](#principais-conceitos), uma `branch` é onde salvamos as novas alterações de forma temporária.
Por enquanto, as suas alterações estão visíveis apenas na sua `branch` porque elas não estão publicadas ainda.
É como se fosse o nosso rascunho. Podemos colocar qualquer alteração lá, que não vai afetar o que está publicado na `branch` principal (`main`).
Para publicar as suas alterações, você precisa abrir uma [pull request](https://docs.github.com/pt/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-pull-requests).

Abir uma `pull request` é a forma de pedir que o seu trabalho seja revisado por outro integrante da equipe.
Depois que a sua alteração for aprovada, ela será publicada na `branch` principal (`main`) e a sua `branch` temporária será apagada.
Você pode seguir estes passos para abrir uma `pull request`:

- Clique na aba `Pull requests`.
- Clique no botão `New pull request`.
- No menu `base`, selecione `main`. É lá que você precisa publicar as suas alterações.
- No menu `compare`, selecione a `branch` que você criou.
- Clique no botão `Create pull request`.

O GitHub vai mostrar todas as alterações feitas por você.
Por favor, revise as suas modificações antes de abrir a `pull request`.
Se tudo estiver correto, faça o seguinte:

- Dê um título descritivo para as suas alterações, começando com a sessão que você está modificando
(ex. `Como trabalhamos: Atualiza instruções sobre como apagar um documento`).
- Descreva as alterações que você fez e acrescente quaisquer comentários que possam ser relevantes para explicar a mudança.
- Se a sua `pull request` for relacionada à uma tarefa, use a palavra-chave `Closes #42`, onde `42` é o número de identificação da tarefa.
Isso vai garantir que a tarefa seja encerrada automaticamente quando a `pull request` for publicada na `branch` principal.
- Na coluna do lado direito tem dois items chamados `Reviewers` (Revisores) e `Asignees` (Designados):

<img alt="Captura de tela do GitHub mostrando a coluna lateral direita" src="https://user-images.githubusercontent.com/4393133/175761006-966d6a5c-b91e-49fe-bf07-0520e223974e.png">

Quando abrir a `pull request` peça a revisão de quem lidera o projeto e designe a revisão para essa pessoa também.
Ou seja, adicione ela como `Reviewer` e `Assignee`.
Você pode conferir quem lidera o projeto no arquivo `README.md` da pasta principal.

Após seguir os passos acima, clique no botão `Create pull request`.
O GitHub vai criar uma `pull request` para que seja revisada.
Depois de aprovada, ela será publicada na `branch` principal (`main`) pela pessoa que revisou por último o seu trabalho.

**Importante:** Depois de criar a `pull request`, mova a sua tarefa da coluna `Em Progresso` para `Em Revisão`.
Se você precisar fazer uma correção pequena (ex. corrigir um erro de digitação), não é necessário criar uma tarefa (`issue`) para isso.

## Encontrou algum problema?

- [Sugerir alteração](https://github.com/zoonk/manual/edit/main/como-trabalhamos/como-usar-o-github.md)
- [Iniciar conversa](https://github.com/zoonk/manual/discussions/new)
