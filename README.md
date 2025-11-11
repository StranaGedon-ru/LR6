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


### История комитов
```
cc817f6 - 2025-11-11 - Artem Bashta - report01
9e69bc0 - 2025-11-11 - Artem Bashta - Nulla gravida
53dfb71 - 2025-11-11 - Artem Bashta - Ut sit amet ipsum non orci tincidunt pharetra
1655dbb - 2025-11-11 - Artem Bashta - Now conflict solved
9ceb09a - 2025-11-11 - Artem Bashta - Some changes in master branch
154342c - 2025-11-11 - Artem Bashta - Commit in new branch
921f53b - 2020-11-21 - Kurtyanik - Обновление информации
c08a654 - 2020-11-21 - Kurtyanik - Файл создан пустым
3c6e913 - 2020-11-21 - Kurtyanik - Initial commit
```