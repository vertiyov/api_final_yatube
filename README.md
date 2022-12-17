# API для yatube. 

Стек: Python 3.7, Django Rest Framework

# Как запустить проект:

- Клонировать репозиторий и перейти в него в командной строке:
```
git@github.com:vertiyov/api_final_yatube.git
```

- Cоздать и активировать виртуальное окружение:
```
python3 -m venv env
source venv/bin/activate
```
- Установить зависимости из файла requirements.txt:
```
python3 -m pip install --upgrade pip
pip install -r requirements.txt
```
- Выполнить миграции:
```
python3 manage.py migrate
```
- Запустить проект:
```
python3 manage.py runserver
```

Примеры запросов:

##### POST /api/v1/posts/{id}/comments/

Request sample:
```
{
"text": "string"
}
``` 
Response sample:
```
{
    "id": 0,
    "author": "string",
    "text": "string",
    "created": "2022-12-17T21:08:10.621235Z",
    "post": 0
}
```

##### GET http://127.0.0.1:8000/api/v1/posts/{id}/

Response sample:
```
{
    "id": 0,
    "author": "string",
    "text": "string",
    "pub_date": "2022-12-17T21:08:10.621235Z",
    "image": "string",
    "group": 0
}
```

