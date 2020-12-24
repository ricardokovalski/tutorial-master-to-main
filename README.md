# Tutorial master to main

Tutorial de como trocar a branch master para a branch main em seus repositórios.

```
# Passo 1
$ git branch -m master main

# Passo 2
$ git push -u origin main

# Passo 3
$ git symbolic-ref refs/remotes/origin/HEAD refs/remotes/origin/main

# Passo 4
https://docs.github.com/en/github/administering-a-repository/setting-the-default-branch

# Passo 5
$ git push origin --delete master
```
