# Como gerenciamos projetos

Nós usamos o GitHub para gerenciar os nossos projetos e tarefas.
A [página do projeto](https://github.com/orgs/zoonk/projects/11) lista todas as atividades nas quais estamos trabalhando atualmente.
Nós valorizamos o [senso de dono](../sobre/valores.md#senso-de-dono).
Portanto, cabe a você escolher uma tarefa na qual gostaria de trabalhar.
Não espere que outras pessoas te digam o que fazer.
Leia o [guia de contribuição](../CONTRIBUTING.md) para saber como ajudar no projeto.

## Criando um repositório

Às vezes, quando trabalhando em algo novo, pode ser útil criar um repositório.
Caso seja necessário, siga os passos abaixo.

- [ ] Navegue até a [lista de repositórios](https://github.com/orgs/zoonk/repositories).
- [ ] Clique no botão `New repository` para criar um novo repositório.
- [ ] Selecione `zoonk` no menu `Owner`.
- [ ] Dê um nome para o repositório no campo `Repository name`.
Deve ser o mesmo nome do projeto ou uma versão mais curta dele.
Se tiver espaço entre as palavras, use `-` (ex. `meu-novo-projeto-super-bacana`).
- [ ] Escreva uma breve descrição para o seu projeto.
- [ ] Selecione a opção `Public` para tornar o repositório visível a todos.
Como falamos anteriormente, valorizamos [transparência](../sobre/valores.md#transparência) e trabalhamos em público.
- [ ] Marque a opção `Add a README file`.
- [ ] Na opção `Choose a license`, vamos escolher `MIT` para projetos de software
e `Creative Commons Zero v1.0 Universal` para projetos de conteúdo.
- [ ] Clique no botão `Create repository`.

Depois que o repositório for criado, vamos adicionar algumas configurações padrão.
Vamos começar criando um código de conduta:

- [ ] Vá até a página principal do repositório.
- [ ] Clique em `Add file` e, depois, em `Create new file`.
- [ ] Nomeie o documento como `CODE_OF_CONDUCT.md`.
- [ ] Em outra aba do navegador, acesse https://www.contributor-covenant.org/translations/
- [ ] Procure a tradução em `Português do Brasil` na lista de traduções.
- [ ] Clique em `Text/Markdown`.
- [ ] Copie todo o conteúdo da página.
- [ ] Cole o conteúdo no editor do GitHub.
- [ ] Procure a parte onde diz `[INSERIR MÉTODO DE CONTATO]` e substitua esse texto pelo link https://forms.gle/BqKXt4i5oNEpCMKh8.
- [ ] Clique em `Commit new file` para salvar o documento.

Usamos o GitHub Discussions para comunicar erros, sugerir novas funcionalidades e discutir ideias.
Portanto, tarefas (`issues`) devem ser criadas apenas por integrantes da nossa equipe.
Para diminuir as chances de um contribuidor externo criar uma tarefa sem iniciar uma conversa primeiro,
precisamos atualizar os nossos modelos de tarefa (`Issue templates`):

- [ ] Crie um novo documento na pasta `.github/ISSUE_TEMPLATE` com o nome `config.yml`.
- [ ] Copie o conteúdo [deste arquivo](../.github/ISSUE_TEMPLATE/config.yml) no novo documento.
- [ ] Atualize os links do documento para utilizar o endereço (URL) do novo repositório.

Agora vamos atualizar as configurações gerais do repositório:

- [ ] Clique na aba `Settings` do repositório.
- [ ] Atualize a imagem que vai aparecer na pré-visualização em redes sociais (`social preview image`).
      Atualize a imagem disponível no
      [repositório de redes sociais](https://github.com/zoonk/social-media/blob/main/templates/GitHub_Social_Preview.sketch)
      para incluir o nome do repositório.
      Caso você não saiba editar a imagem, crie uma nova tarefa (`issue`) naquele repositório solicitando que um designer crie a imagem.
- [ ] Na sessão `Features`, desmarque a opção `Wiki`.
- [ ] Marque a opção `Issues`.
- [ ] Marque a opção `Projects`.
- [ ] Marque a opção `Preserve this repository`.
- [ ] Marque a opção `Discussions`.
- [ ] Na sessão `Pull Requests`, desmarque a opção `Allow merge commits`.
- [ ] Marque a opção `Allow squash merging`.
- [ ] Marque a opção `Default to PR title for squash merge commits`.
- [ ] Desmarque a opção `Allow rebase merging`.
- [ ] Marque a opção `Always suggest updating pull request branches`.
- [ ] Marque a opção `Automatically delete head branches`.

O próximo passo é atualizar as configurações de colaboradores e equipes:

- [ ] Na página de configurações (`Settings`), clique no menu `Collaborators and teams` na barra lateral esquerda.
- [ ] Na sessão `Manage access`, clique no botão `Add teams`.
- [ ] Use a busca para procurar o nome da equipe que deve ter acesso ao repositório
(ou [crie uma nova equipe](https://github.com/orgs/zoonk/new-team) antes).
- [ ] Selecione a opção `Maintain` para a sua equipe.

Depois disso, atualize as opções de moderação de conteúdo:

- [ ] Na página de configurações (`Settings`), clique no menu `Moderation options` na barra lateral esquerda.
- [ ] Clique no item `Code review limits`.
- [ ] Marque a opção `Limit to users explicitly granted read or higher access`.

Após alterar as opções de moderação, precisamos mudar as configurações de `branch` também:

- [ ] Na página de configurações (`Settings`), procure pela sessão `Code and automation` e clique no menu `Branches`.
- [ ] Na sessão `Branch protection rules`, clique no botão `Add rule`.
- [ ] Em `Branch name pattern`, digite `main` para que as alterações sejam aplicadas à branch principal.
- [ ] Desça na página até `Protect matching branches`.
- [ ] Marque a opção `Require a pull request before merging`.
- [ ] Marque a opção `Require approvals`.
- [ ] Selecione `1` na opção `Required number of approvals before merging`.
- [ ] Marque a opção `Dismiss stale pull request approvals when new commits are pushed`.
- [ ] Marque a opção `Allow specific actors to bypass required pull requests`.
- [ ] Marque a opção `Require status checks to pass before merging`.
- [ ] Marque a opção `Require branches to be up do date before merging`.
- [ ] Marque a opção `Require conversation resolution before merging`.
- [ ] Marque a opção `Require linear history`.
- [ ] Marque a opção `Require deployments to succeed before merging`.
- [ ] Desmarque a opção `Allow force pushes`.
- [ ] Desmarque a opção `Allow deletions`.
- [ ] Clique no botão `Create`.

Se você está criando um repositório que não seja de software,
provavelmente não vai precisar usar o [GitHub Actions](https://github.com/features/actions).
Nesse caso, desabilite essa funcionalidade:

- [ ] Na página de configurações (`Settings`), procure pela sessão `Actions` e clique no menu `General`.
- [ ] Selecione a opção `Disable actions`.
- [ ] Clique no botão `Save`.

Se você estiver criando um repositório de software, revise as opções de segurança (na aba `Security`)
e os padrões de comunidade (na aba `Insights` e, depois, no menu `Community Standards`).

Lembre-se também de remover outras funcionalidades não utilizadas:

- [ ] Clique na aba `Code` do seu repositório.
- [ ] Na sessão `About`, clique no ícone de engrenangem (configurações).
- [ ] Adicione palavras-chave relevantas ao seu projeto (ex. `manual`, `design`, `redes-sociais`, etc.).
- [ ] Desmarque todas as opções que você não irá utilizar
(ex. projetos que não são de software provavelmente não irão usar `releases`, `packages` e `environments`).
