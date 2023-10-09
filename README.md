# Documentação do git para ajudar nos comandos.

## Iniciar o projeto no git bash here
````
git init:
````
Ele inicia o arquivo ".git/" para controlar a pasta.

````
git branch -m <branch>
````
Ele modifica o nome da branch atual
## Configuração de usuario
````
 git config --global user.name"<seu_name>"
````
 ````
 git config --global user.email"<seu_email>"
````
 ## Comando para atualizar modificações
````
git status
````
 ele é responsável por validar os arquivos modificados dentro do projeto.
````
git add
````
 Ele é responspavel por colocar o arquivo modificado em uma área segura.
````
git commit -m "<texto_da_modificação>"
````
Ele é responsável por criar uma nova versão do projeto com as referencias do criador.

````
git log
````
 Validar os meus comentários e modificações
````
git checkout -b develop <nome_da_branch>:
````
 Cria uma nova branch ou ramo
````
git checkout
````
 Muda de branch/ramo
````
git merge
````
 Ele adiciona a branch atual e o conteúdo de outra branch
````
gitk
````
 abre uma tela que mostra todo o historico do que foi feito no projeto
````
git clone
````
 Baixa o projeto do repositório
````
git push
````
 Ele envia alterações para o repositório
````
git push setupstream orgin <branch>
````
Ele evia as alterações para uma branch especifica do repositorio
 
````
git pull:
````
 Ele puxa as alterações do repositório


## Possíveis erros: 
### erro 403:
Não conseguimos logar com a nossa conta pois consta outra conta no pc.

Solução: 
> Apagando as credenciais(vai no gerenciador de credenciais e apaga o usuario anterior)
