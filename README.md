# Домашнее задание к занятию "`Жизненный цикл ПО`" - `Бакулев Евгений`

### Что нужно сделать

Необходимо создать собственные workflow для двух типов задач: bug и остальные типы задач. Задачи типа bug должны проходить жизненный цикл:

Open -> On reproduce.
On reproduce -> Open, Done reproduce.
Done reproduce -> On fix.
On fix -> On reproduce, Done fix.
Done fix -> On test.
On test -> On fix, Done.
Done -> Closed, Open.
Остальные задачи должны проходить по упрощённому workflow:

Open -> On develop.
On develop -> Open, Done develop.
Done develop -> On test.
On test -> On develop, Done.
Done -> Closed, Open.
Что нужно сделать

Создайте задачу с типом bug, попытайтесь провести его по всему workflow до Done.
Создайте задачу с типом epic, к ней привяжите несколько задач с типом task, проведите их по всему workflow до Done.
При проведении обеих задач по статусам используйте kanban.
Верните задачи в статус Open.
Перейдите в Scrum, запланируйте новый спринт, состоящий из задач эпика и одного бага, стартуйте спринт, проведите задачи до состояния Closed. Закройте спринт.
Если всё отработалось в рамках ожидания — выгрузите схемы workflow для импорта в XML. Файлы с workflow и скриншоты workflow приложите к решению задания.




![Скриншот](https://github.com/garrkiss/terraform_2/blob/main/img/task1/task1-1.png)

### Задание 4

![Скриншот](https://github.com/garrkiss/terraform_2/blob/main/img/task4/task4.png)


По остальным заданиям [Ссылка на репозиторий](https://github.com/garrkiss/terra2)

