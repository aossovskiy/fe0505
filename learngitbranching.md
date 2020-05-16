# Изучаем git

## 1. Знакомство с Git Commit

- [x] Коммиты в GIT:


git commit
git commit


- [X] Ветвление в Git:



или возможен вариант с двумя командами

git branch bugFix
git checkout bugFix  

- [X] Ветки и слияния:

git branch bugFix
git checkout bugFix  
git commit
git checkout master
git commit
git merge bugFix


- [X] Git Rebase

git branch bugFix
git checkout bugFix  
git commit
git checkout master
git commit
git checkout bugFix 
git rebase master