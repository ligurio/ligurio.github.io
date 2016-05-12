---
date: 2015-05-26T00:00:00Z
title: Выступление Майкла Видеуса, разработчика MySQL и MariaDB
url: /2015/05/26/monty-talk/
---

Вчера мне [предоставилась](http://habrahabr.ru/company/acronis/blog/258601/)
возможность послушать выступление Майкла Видеуса. Этот человек участвовал с
самого начала в разработке MySQL, основал компанию для разработки этой базы
данных, потом продал компанию Sun Microsystems и после покупки Sun Microsystems
компанией Oracle он стал развивать форк MySQL - проект MariaDB.

Всего Майкл показал нам 90 слайдов в своём выступлении и большинство
из них включало технические детали MariaDB. Я в виде тезисов перечислю
те вещи, которые меня больше всего заинтересовали в его выступлении:

- Майкл [добавляет](https://bronevichok.ru/trash/Monty/thumb_15050189_1024.jpg)
в названия продуктов имена своих детей: MySQL, MariaDB и MaxDB;
- компания вокруг проекта MySQL получала основной доход за счёт консультаций
и custom development и Майкл отметил в слайдах, что открытый код MySQL никак не повлиял бы на доходы компании;
- с 1995 по 2000 штат компании MySQL AB вырос с 2 до 15 человек и в ней не было
ни отдела продаж, ни отдела маркетинга;
- рекламу проекту делали сами основатели компании: Майк оказывал техническую поддержку
пользователями базы данных (всего около 300 000 писем), а Дэвид посещал конференции;
- В 1999 году компания приняла инвестиции в размере 50M USD;
- для MariaDB [есть расширение](https://mariadb.org/feedback_plugin/), которое позволяет собирать статистику об использовании базы данных, статистика [свободно доступна](https://mariadb.org/feedback_plugin/) на сайте проекта;

Майкл перечислил причины, по которым пользователи MySQL должны переключиться на использование MariaDB:

- бинарная совместимость между MariaDB и MySQL - переключение с одной БД на другую занимает минуты;
- запросы к БД выполняются быстрее, чем в MySQL за счёт использования XtraDB;
- открытый процесс разработки;
- MariaDB включает в себя больше функциональности, чем в MySQL;
- Меньше риска потерять функциональность (приводятся фичи, удалённые в MySQL);

Часть слайдов из выступления можно найти [здесь](https://bronevichok.ru/trash/Monty/),
[блог Майкла](http://monty-says.blogspot.ru/).

*Добавлено:* выложили [запись выступления](https://www.youtube.com/watch?v=4xJVsCIK2zg).