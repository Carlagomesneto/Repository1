# Repository1
Treinar Respositora

~~~bash
git config --global core.editor "code --wait"
~~~

O comando acima define o Visual Studio Code como o editor padrão das mensagens de commit

~~~bash
git commit --allow-empty
~~~

O parâmetro `--allow-empty`permite a criação de um commit vazio, para fins de testes e prática do Git.

~~~bash
git commit -a
~~~

O parâmetro `-a` adiciona todos os arquivos modificados ou não ingorados ao commit atual.


~~~bash
git checkout -b novoBranch
git switch -c novoBranch
~~~

O parâmetro `-b`alterna para ` novoBranch` criando o branch. o mesmo 
acontece com o comando `git switch` com o parâmetro `-c`. 

~~~bash
git branch -D nomeBranch
git push --delete origin nomeBranch
~~~

Para apagar um Branch é preciso primeiro apagá-lo localmente (1º comando) e depois
propagar a deleção para o repositório remoto (2º comando).

