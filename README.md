# yatube_project
### Описание
REST API для проекта Yatube.
Для получения полной документации по API перейдите в эндпоинт /redoc при запущеном сервере.
Реализует набор CRUD методов для записей, комментариям к ним, групп. Также доступна аутентификация по токену.
### Технологии
 - Python 3.9
 - Django 2.2.16
 - Django Rest Framework 3.12.4
 - Simple-JWT 4.7.2

### Запуск в Dev-режиме
1. Установить зависимости из файла requirements.txt:

```
pip install -r requirements.txt
```

2. Выполнить миграции:

```
python manage.py migrate
```

3. Запустить проект:

```
python manage.py runserver
```
### Автор
Сонин Михаил
