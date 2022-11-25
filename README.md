# Yatube_api

### Описание
API для платформы Yatube

### Стек
- Python
- Django
- Django REST framework
- SQLite

### Как запустить проект
- Клонировать репозиторий и перейти в него в командной строке:
```
git clone https://github.com/FedyaevaAS/api_final_yatube
``` 
```
cd api_final_yatube
``` 
- Cоздать и активировать виртуальное окружение:
```
py -m venv env
``` 
- Установить зависимости из файла requirements.txt:
```
pip install -r requirements.txt
```
- Выполнить миграции:
```
py manage.py migrate
```
- Запустить проект:
```
py manage.py runserver
```
### Примеры запросов
- Получение списка публикаций (GET)
**api/v1/posts/**
- Создание публикации (POST)
**api/v1/posts/**
```
{
    "text": "string",
    "image": "string",
    "group": 0
}
```
- Обновление публикации (PUT)
**api/v1/posts/{id}/**
```
{
    "text": "string",
    "image": "string",
    "group": 0
}
```
### Автор
Федяева Анастасия
