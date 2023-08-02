# Exemplos de operações básicas para git via CLI

## Comandos de uso geral da CLI

- Criar pasta: mkdir nomepasta
- Listar conteúdo: dir
- Limpar tela: cls
- Entrar na pasta: cd nome pasta
- sair: ctrl c

## Comandos Principais

`git user.name` e `git user.email `
Verificar email e usúario

`git config --global user.name "nome"`
`git config --global user.email "email"`

Mudar usuário de forma global

**obs:** Normalmente ester dados estão relacionados ao usuário/conta do site

Mudar usuário e e-mail de forma global

`git init`
Inicializar um repositório (executado dentro da pasta)

`git branch nome-branch-aatual novo-nome-para-branch`
Renomear brranches

Para alterar a branch de *master* para *main*, usariámos: `git branch master main`

`Git status`
Verificar status atual do repositório.

`Git add nomearquivo` ou `git add .`

Adicionara (tornar arquivo rastreável) ao monitoramento do git.

`git commit -m "Texto da mensagem sobre stá alteração"`

Fazer commit das alterações (salvar no histórico).

`git remote add origin endereço-do-repositório.git`

adicionar/conectar o repositório remoto ao local.

`git pull origin main`
Pegar e obter as mudanças do repositório online.

`git clone endereço-repositório.git`

copiando e baixando um repositório para a máquina remota.