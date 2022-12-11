# TelegramBot.PythonProject2
Данный проект был создан с оброзовательной целью по курсу програмирования “Практикум Python”. \
Задача - создание функционального проекта на языке програмирования Python, с читаемым и модифицируемым кодом, а также большими возможностями реализованных с помощью знаний полученных в течение данного курса.

-----------------------------------------------------------------------------------------------------------------------------

```diff
Название проекта :
    Casino For Students
Автор проекта :
    Project-MGS 
Год публикации :
    2022 
```


                                                  
-----------------------------------------------------------------------------------------------------------------------------

## Описание проекта :
Casino For Students - это бот созданный для телеграмма, который представляет из себя многопользовательское казино, где клиенты могут играть в множество мини-игр на деньги и выводить заработанные средства к себе на счет.
+ Casino For Students был реализован с помощь набора модулей aiogram, Telethon, requests, loguru, pyqiwip2p.
+ Для того, чтобы все скаченные файлы правильно работали и бот запускался, следует настроить файл config.cfg.
+ !ОБРАТИТЕ ВНИМАНИЕ! Чтобы бот мог польностью функционировать следует заполнить все необжодимые поля данного файла:
  1) bot_token = ...
  2) bot_login = ...
  3) admin_id = ...
  4) channel_id = ...
  5) admin_group = ...
Для этого следует зарегестрировать своего нового бота в BotFather, получить bot_token и bot_login, также вам обязательно надо получить id своего аккаунта,/ вписать в admin_id, admin_group, создать чат, получить id чата, добавить туда своего бота и вписать id в channel_id. Такая функция была специально /добавлена в данного бота, чтобы уведомления о новых играх приходили в чат, где могли бы распологатся пользователи. /
