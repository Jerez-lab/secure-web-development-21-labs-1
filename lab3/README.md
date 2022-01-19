# Отчет по Лабораторной работе №3
> Цель работы: Поиск и устранение XSS уязвимостей.

## Задание 1
1. Войти на сайт и увидеть список книг и авторов

Чтобы авторизоваться на сайте предварительно создадим пользователя в таблице users, в качестве пароля запишем **md5** хеш:

![alt text](img/Screenshot_1.png "Таблица Users")

В результате успешной авторизации и редиректа на route **/books** видим список книг и авторов:

![alt text](img/Screenshot_2.png "Список книг")