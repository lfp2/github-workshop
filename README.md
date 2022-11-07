# github-workshop

Primeiros passos com Git e GitHub

[Slides do Workshop](https://www.canva.com/design/DAE6UgU_rBo/7reeTT8sGjzXR4w1FAafHA/view?utm_content=DAE6UgU_rBo&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton)

Olá! Este repositório serve para que você tenha sua primeira experiência com Git e GitHub.

## Pré-requisitos:

1. Instale o controle de versão [Git](https://git-scm.com/downloads)
2. (Opcional) Instale o [Visual Code Studio](https://code.visualstudio.com/download)

## Tutorial:

- Faça um [Fork](https://docs.github.com/pt/get-started/quickstart/fork-a-repo) desse repositório para sua conta clicando no botão Fork.
- Clique no botão Code, em seguida em Local e HTTPS. Copie a URL.

### Utilizando o Terminal

- Escolha um Diretório para seu repositório. Caso não saiba navegar na linha de comando, um bom tutorial está disponível [aqui](https://terminalcheatsheet.com/pt-BR/).
- Dentro do seu terminal, digite o comando `git clone <URL que você copiou>`
- Navegue para dentro da nova pasta com `cd github-workshop`
- Navegue para dentro do completed com `cd completed`
- Crie um novo arquivo Markdown com `touch <Seu usuário do GitHub>.md`. Um exemplo é `touch lfp2.md`
- Adicione a URL do seu perfil do GitHub com `echo "<URL do seu perfil no GitHub>" > <Seu usuário do GitHub.md>`. Um exemplo é `echo "https://github.com/lfp2" > lfp2.md`
- Adicione este arquivo para mudanças no Git com `git add <Seu usuário do GitHub.md>`
- Faça um commit da mudança com `git commit -m ":tada: Meu primeiro commit :tada:"`
- Essa mudança ainda está local. Mande para seu repositório no GitHub com `git push`

### Utilizando o Visual Code Studio

- Abra o menu de comandos (Ctrl + Shift + P), pesquise git clone e cole a URL que você copiou.
- Crie um novo arquivo Markdown dentro da pasta completed. Você pode criar um arquivo novo com o menu de comandos, pesquisando por Create File. O nome do arquivo é `<Seu usuário no GitHub>.md.` (Exemplo: `lfp2.md`)
- Coloque a URL do seu perfil do GitHub no arquivo. (Exemplo: `https://github.com/lfp2`)
- Vá no painel Source Control (Ctrl + Shift + G)
- Adicione o arquivo `<Seu usuário no GitHub>.md.`. O estado deve sair de `Changes` para `Staged Changes`.
- Adicione na mensagem `:tada: Meu primeiro commit :tada:`
- Aperte o botão `Commit`. Isso deixará salvo no seu histórico local.
- Para enviar a mudança pro GitHub, aperte o botão `Sync changes` e depois `Ok`.
