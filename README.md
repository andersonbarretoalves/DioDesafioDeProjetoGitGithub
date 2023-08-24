# Repositório do desafio de Projeto sobre Git/Github da DIO

Repositório criado para o Desafio de Projetos.

## Links Úteis:

 - [Sintaxe Basica Markdown](https://www.markdownguide.org/basic-syntax/)
 - [Markdown Emoji](https://gist.github.com/rxaviers/7360908)
 - [Documentação Git](https://git-scm.com/docs/git/pt_BR)


## Comandos Úteis do Git:

 - **git init:** É um comando único que você usa durante a configuração inicial de um noivo Repositório. Ele inicia o repositorio git no Digetório local. EX: (.git).
 - **git add:**  Adiciona uma alteração no diretório ativo à área de staging. Ele diz ao **Git** que você quer incluir atualizações a um arquivo específico no próximo commit. **Ex: git add .** Nesse exemplo é adicionado todas os arquivos novos e modificações.
 - **git commit:** É usado para criar um instantâneo das alterações preparadas em um cronograma de um histórico de projetos do **Git**.
 - **git commit --amend -m "commit'** ira modifica ultimo commit.
 - **git reset --soft colar o rest do commit** usado para apagar o Commit.
 - **git reset --mixed colar o rest do commit** volta os arquivos para o status Untracked files(não rastreados). Obs: pode ser usado o --mixed EX: **git reset colar o rest do commit**
 - **git reset --hard colar o rest do commit** desfaz tudo até as modificações nos arquivos.
 - **git reset Readme.md** vai apagar o arquivo solicitado "Readme.me".
 - **git reflog** mostra todas as alterações e comandos usados.
 - **git status:** Exibe as condições do diretório de trabalho e da área de staging. 
 - **git remote add:** Para adicionar um origin para o repositório se não existe nenhum. Conecta o repositório local com o repositório online.
 - **git log** Exibe o log de informação do Commit.
 - **git remote -v:** Mostra a lista de repositório cadastrado.
 - **git push:** É usado para enviar o conteúdo do repositório local para um repositório remoto.
 - **git pull:** É usado para buscar e baixar conteúdo de repositórios remotos e fazer a atualização imediata ao repositório local para que os conteúdos sejam iguais.
 - **git clone:** É usado para realizar uma cópia de um repositório remoto.
 * * Ex: git clone URL nomeDaPasta
 * * Ex: git clone URL --branch nomeDaBrach --single-brach
 - **git config --list:** Para listar todas as configurações que o **Git** conseguir encontrar naquele momento.
 - **git update:** Usado para atualiar o **Git.**
 - **git --version:** Verifica a versão do **Git.**
 - **git config --global user.email "seu email":** Usado para configurar o seu email.
 - **git config --global user.name seu usuário:** Usado para configurar o seu nome de usuário.
 - **git restore** Usado para restaurar o conteúdo do diretório local. Obs: vai descartar todas as alterações feitas no diretorio local.

## Infomações Úteis:

### 📚 Comados de navegação no Windows :

 - **cd** - Usado para navegação entre as pastas.
 - **dir** - Usado para listar os arquivos da pasta.
 - **mkdir** -  É usado para criar novos diretórios.
 - **del/mrdir** - Usado para deletar diritórios.
 - **cls** - Usado para lipar a linha de comandos.

### 🐧 Comandos de navegação no Linux:

- **cd** - Usado para navegação entre as pastas.
 - **ls** - Usado para listar os arquivos da pasta.
 - **mkdir** -  É usado para criar novos diretórios.
 - **rm -rf** - Usado para deletar diritórios.
 - **clear** - Usado para lipar a linha de comandos.

### Obejetos do **Git:**

 - Blobs
 - Trees
 - Commits

### Sha1:

 - **Secure Hash Algorithm** ou **Algoritmo de Hash Seguro**, é um conjunto de funções hash croptográficas projetadas pela **NSA - Agência de Segurança Nacinal dos EUA.**

### Chave **SSH**:

 - **Secure Shell** - também conhecido como **Secure socket shell** é um protocolo que permite a conexão com servidores remotos, de forma criptografada e mais segura, usando um par de chave **RSA.**