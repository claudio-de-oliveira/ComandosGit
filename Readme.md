# Comandos Git

### … or create a new repository on the command line

- echo "# ComandosGit" >> README.md
- git init
- git add README.md
- git commit -m "first commit"
- git branch -M main
- git remote add origin https://github.com/claudio-de-oliveira/ComandosGit.git
- git push -u origin main (-u na primeira vez)

### … or push an existing repository from the command line

- git remote add origin https://github.com/claudio-de-oliveira/ComandosGit.git
- git branch -M main
- git push origin main

### Branches

- git checkout -b "branch-novo"
- git push origin branch-novo
- git checkout main (retorna para o main)
- git merge branch-novo (o merge vai acontecer no main)
- git push origin main

## Projeto de terceiros

- git clone https://github.com/claudio-de-oliveira/ComandosGit.git
