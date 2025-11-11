## Лабораторная работа №6

  

# GITHUB

  

### По курсу: "ОСНОВЫ ПРОГРАММИРОВАНИЯ"

  

**Цель лабораторной работы:** изучение базовых возможностей системы

управления версиями, опыт работы с Git Api, опыт работы с локальным и

удаленным репозиторием.

```
$ git branch -a
$ git log
$ git checkout -b new_branch
$ git add .
$ git commit -m "Commit in new branch"
$ git checkout master
$ git add .
$ git commit -m "Some changes in master branch"
$ git merge new_branch
$ git log --merge
$ git add .
$ git commit -m "Now conflict solved"
$ git branch -d new_branch
$ git add .
$ git commit -m "Ut sit amet ipsum non orci tincidunt pharetra"
$ git add .
$ git commit -m "Nulla gravida"
$ git add .
$ git commit -m "Donec vel lorem a urna tempor"
$ git reset --soft HEAD~1
$ git checkout -b report
$ git push origin master
```
