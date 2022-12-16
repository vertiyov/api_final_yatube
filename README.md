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
