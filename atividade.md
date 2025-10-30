## Atividade

### Única Vez
Clonar o repositório  
`$ git clone https://github.com/uniarp/teste-git-2025.git`

### P/ Cada iteração
```sh
$ git checkout main
$ git pull origin main
$ git checkout -b <nome-branch>
..
$ git add <nome-arquivo>
$ git commit -m '<descricao>'
..
$ git push origin <nome-branch>
```

## Interface
- Criar **Pull Request**
- Review e Aprovar
- **Merge**


Ex:
```
$ git clone https://github.com/uniarp/teste-git-2025.git
$ git checkout -b danconte72/001
$ git status
$ git diff
$ git status
$ git add README.md
$ git status
$ git commit -m '[#001] add nome daniel'
$ git push origin danconte72/001
$ git diff
$ git add README.md
$ git commit -m 'correção maiúsculo'
$ git push origin danconte72/001
```