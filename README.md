# Моё руководство с Git

## 1 Семинар

git add- сохранение

git commit- фиксация изменений и называем последовательно в ковычках

git log- выводит список всех файлов в хронологическом порядке

git diff- разница между текущей и зафиксированной

git init - инициализация

git version- показывает версию

git config --global user.name - указываем своё имя в ковычках

git config --global user.email - указываем свою электронную почту

git checkout- команда позволяет перемещаться между сохранениями

git checkout master- переход к последнему изменению

git merge - объединение веток

## 2 семинар

ветки - черновик
git merge - слияние веток
git status - команда, вызывающая информацию

## Домашнее задание к 9.10

-   Создать 4 ветки

git checkout Second1

git add

git commit -m "название измения"

git checkout Second2

git checkout Second3

git checkout Second4

-   Слить 4 ветки
    Пробую создать конфликт еще раз
    Error 1
    git merge Second1
    git merge Second2
    git merge Second3
    git merge Second4
    git merge Second5
