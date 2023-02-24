# dicasgit

## Comandos básicos para o dia a dia utilizando o git.

Salva suas alterações

`git stash`

Sanvaldo suas alterações em um branch temporário

`git stash branch temp`

Fazendo checkout no branch correto

`git checkout funcionalidade-x`

Fazendo merge com o branch temporário

`git merge --no-ff temp`

Apagando o branch temporário

`git branch -d temp`


Li [aqui](https://www.theserverside.com/blog/Coffee-Talk-Java-News-Stories-and-Opinions/remove-revert-discard-local-uncommitted-changes-Git-how-to) sobre esses dois comandos. Eles descartam todas as alterações locais:


`git reset –hard`

`git clean -fxd`

Estudar mais sobre a aplicação dos dois comando acima.

Deletar todas as outras branches, exceto a main

`git branch | grep -v "main" | xargs git branch -D`
