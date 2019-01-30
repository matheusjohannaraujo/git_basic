## <a href="https://matheusjohannaraujo.herokuapp.com">Matheus Johann Araújo</a>

> Country: Brasil

> State: Pernambuco

> Date: 2020-11-05

## <a href="https://github.com/matheusjohannaraujo/git_basic/">git_basic</a>

##### Links de apoio
###### https://git-scm.com/book/pt-br/v1
###### https://caiojcarvalho.wordpress.com/2017/07/22/definindo-usuario-e-senha-padrao-no-git

### Comandos básicos de Git

#### Inicia um repositório Git
> ```git init```

#### Exibe informação sobre o ramo atual e status do repositório Git
> ```git status```
	
#### Detalha as alterações que foram realizadas nos arquivos do repositório Git
> ```git diff```
	
#### Mostra o nome dos arquivos que foram alterados
> ```git diff --name-only```

#### Exibe as alterações do arquivo informado
> ```git diff arquivo.txt```	

#### Adiciona todos os arquivos do diretório
> ```git add arquivo.txt```

#### Adiciona todos os arquivos do diretório
> ```git add .```

#### Remove somento este item do git add
> ```git reset arquivo.txt```

#### Remove todos os arquivos e diretórios do git add
> ```git reset```

#### Lista as informações de configuração do git
> ```git config --list```
	
#### Configura um email padrão para o repositório
> ```git config user.email "matheusjohannaraujo@gmail.com"```

#### Configura um nome de usuário padrão para o repositório
> ```git config user.name "matheusjohannaraujo"```

#### Configura um email padrão e global para todos os repositórios
> ```git config --global user.email "matheusjohannaraujo@gmail.com"```

#### Configura um nome de usuário padrão e global para todos os repositórios
> ```git config --global user.name "matheusjohannaraujo"```

#### Registra alterações do projeto local
> ```git commit -m "Informação do commit"```

#### Adiciona `git add .` e registra as alterações do projeto local
> ```git commit -am "Informação do commit"```

#### Permite alterar a mensagem mais recente de commit do Git
> ```git commit --amend```

#### Altera a mensagem mais recente de commit do Git para "Nova mensagem"
> ```git commit --amend -m "Nova mensagem"```

#### Exibe os logs dos commits e outras informações
> ```git log```

#### Direciona do estado de commit atual para o commit informado, sem apagar as alterações no último commit e aplica o `git add .`

> ```git reset --soft 19d597880d0a84decf714498177a7c4efdff3bba```

#### Direciona do estado de commit atual para o commit informado, sem apagar as alterações no último commit e não aplica o `git add .`

> ```git reset --mixed 19d597880d0a84decf714498177a7c4efdff3bba```

#### Direciona do estado de commit atual para o commit informado, apagando as alterações no último commit

> ```git reset --hard 19d597880d0a84decf714498177a7c4efdff3bba```

#### Adiciona repositório remoto
> ```git remote add origin https://github.com/matheusjohannaraujo/git_basic.git```

#### Exibe o repositório remoto do projeto
> ```git remote -v```
	
#### Envia os arquivos para o repositório remoto da branch master
> ```git push -u origin master```
	
#### Cria um novo ramo, o ramo principal é o master
> ```git branch nome-do-ramo```

#### Lista os ramos existentes e qual deles esta selecionado
> ```git branch -a```

#### Muda para outro ramo
> ```git checkout nome-do-ramo```

#### Cria um novo ramo `git branch nome-do-ramo`, e muda para ele
> ```git checkout -b nome-do-ramo```

#### Muda o nome do ramo atual "nome-do-ramo" para "nome-do-ramo-2"
> ```git branch -m nome-do-ramo-2```

#### Envia os arquivos para o repositório remoto da branch "nome-do-ramo"
> ```git push -u origin nome-do-ramo```

#### Exclui o ramo "nome-do-ramo" do repositório remoto
> ```git push origin -d nome-do-ramo```

#### Volta para o ramo principal
> ```git checkout master```
	
#### Mescla o ramo master com o ramo "nome-do-ramo"
> ```git merge nome-do-ramo```
	
#### Exclui o ramo "nome-do-ramo"
> ```git branch -d nome-do-ramo```
	
#### Desfaz alterações no arquivo, CTRL+Z
> ```git checkout -- arquivo.txt```
	
#### Esconde alterações
> ```git stash```
	
#### Lista as alterações escondidas
> ```git stash list```
	
#### Exibe novamente as alterações
> ```git stach apply stash@{0}```
	
#### Exclui alteração escondida
> ```git stash drop stach@{0}```
	
#### Puxa as alterações de repositório online para o repositório local
> ```git pull origin```
	
#### Baixa um repositório remoto para o computador local
> ```git clone https://github.com/matheusjohannaraujo/git_basic.git```
