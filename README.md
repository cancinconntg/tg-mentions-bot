@@ -1,64 +1,6 @@
#  tg-mentions-bot

###  Açıklama

Telegram-бот для упоминания пользователей по настраиваемым группам.

Бот доступен по ссылке https://t.me/TgMentionsBot

###  Поддерживаемые команды

''
/ list_groups - просмотр списка групп
/ add_group - добавление группы
/ remove_group - удаление группы
/ add_group_alias - добавление алиаса группы
/ remove_group_alias - удаление алиаса группы
/ list_members - группе'daki список пользователей
/ add_members - добавление пользователей в группу
/ remove_members - удаление пользователей из группы
/ enable_anarchy - настраивать бота могут все
/ disable_anarchy - настраивать бота могут администраторы и владелец
/ call - позвать пользователей группы
/ yardım - справка по всем операциям
''

###  Примеры использования

Добавление / удаление группы
''
/ add_group group1
/ remove_group group1
''

Добавление / удаление синонима (алиаса) для группы
''
/ add_group_alias grup1 qqq
/ remove_group_alias group1 qqq
''

Добавление / удаление пользователей
''
/ add_members grup1 @FirstUser @SecondUser
/ remove_members grup1 @FirstUser @SecondUser
''

Получение списка групп / пользователей
''
/ list_groups
/ list_members group1
''

Упоминание списка пользователей ve группы
''
/ çağrı grubu1
/ qqq'i ara
/ call group1 какое-то сообщение
''

###  Деплой в Heroku

Бот готов для разворачивания в Heroku.

Для этого подготовлены файлы [ runtime.txt ] (runtime.txt) ve [ Procfile ] (Procfile).
