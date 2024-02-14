﻿# my_9_repository
## Команды для работы с Git:
## 1.	Первоначальная настройка Git:
# •	указать имя пользователя — git config --global user.name "Ivan Ivanov";
# •	указать электронную почту — git config --global user.email "mail@gmail.com";
# •	посмотреть настройки — git config --list.
## 2.	Работа с репозиторием:
# •	создать репозиторий — git init;
# •	клонировать удалённый репозиторий — git clone [ссылка на удалённый репозиторий];
# •	связать удалённый и локальный репозитории — git remote add origin [ссылка на удалённый репозиторий].
## 3.	Работа с изменениями:
# •	подтянуть изменения — git pull;
# •	посмотреть статус файлов — git status;
# •	добавить файлы в индекс — git add [название файла].
# 4.	Работа с ветками:
# •	создать ветку — git switch --create branch-name;
# •	переключить ветку — git switch branch-name;
# •	посмотреть все локальные ветки — git branch;
# •	переименовать ветку — git branch -m [старое-название-ветки] [новое-название-ветки].
## 5.	Откладывание и удаление:
# •	отложить изменения — git stash push;
# •	вернуть отложенные изменения — git stash pop;
# •	отменить изменения, не добавленные в индекс — git restore [название файла];
# •	отменить изменения, добавленные в индекс — git reset --hard.
# 6.	**Удалить лишнее — git clean.
# Завершение работы
