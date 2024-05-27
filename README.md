# Описание.

## Проект api_final_yatube.

## Технологии:
* Python 3.9
* Django 3.2
* DRF

## Описание проекта

_Данный проект позволяет осуществлять работу с приложением Yatube
по средством API на базе Django + Django REST framework._

# Установка.

## Как запустить проект:

* Клонировать репозиторий и перейти в него в командной строке:

        https://github.com/gr1ban/api_final_yatube-master
        cd api_final_yatube-master

* Cоздать и активировать виртуальное окружение:

        python3 -m venv venv
        source venv/Scripts/activate

* Установить зависимости из файла requirements.txt:

        python -m pip install --upgrade pip
        pip install -r requirements.txt

* Выполнить миграции:

        python manage.py migrate
        
* Запустить проект:

        python manage.py runserver

* Перейти на локальный сервер:

        http://127.0.0.1:8000/        