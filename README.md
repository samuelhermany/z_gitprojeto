commit iniciar sempre com verbo

linha 1
item 2

# cria repositorio no git hub com o CLI

gh repo create z_gitprojeto --public --source=. --remote=origin --push

# cria repositorio no git hub com o CLI EM UMA ORGANIZAÇÃO

gh repo create akn-solutions/z_gitprojeto --public --source=. --remote=origin --push

# ver em qual branch estou

git branch

# Criar nova branch

git checkout -b nome-da-branch
git checkout -b teste

# subir nova branch para o github

git push -u origin nome_branch

# branch-criar pul request

gh pr create

# branch - atualizar a main

gh pr merge

# atualizar a main local

git checkout main
git pull
