Project: django-shop 
Developer: Yuriy IV.

Документация по запуску проекта:

Создаем и активируем виртуальное окружение:

```
python -m venv venv
source venv\bin\activate 
```


Клонируем репозиторий:
```
git clone https://github.com/iTheSand/django-shop.git
```


Устанавливаем необходимые зависимости:

```
pip install -r /django-shop/requirements.txt
```


Создаем и применяем миграции:

```
python manage.py makemigrations
python manage.py migrate
```


Заполняем базу данных тестовыми клиентами (DEBUG=True):

```
python manage.py filling_database 
```


Запускаем сервер:

```
python manage.py runserver
```
