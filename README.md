# Реализация тестового задания для АпТрейдер (UpTrader)
___
### Описание задачи:
Нужно сделать django app, который будет реализовывать древовидное меню
___
### Стек:
* Python
* Django
* PostgreSQL
___
Для запуска проекта у себя локально необходимо:

git clone репозитория
```
git@github.com:VadimPokhabov/test_tree_menu.git
```
Установить виртуальное окружение venv
```
python3 -m venv venv для MacOS и Linux систем
python -m venv venv для windows
```
Активировать виртуальное окружение
```
source venv/bin/activate для MasOs и Linux систем
venv\Scripts\activate.bat для windows
```
Установить файл с зависимостями
```
pip install -r requirements.txt
```
Создать базу данных в PgAdmin, либо через терминал.
Заполнить своими данными файл .env в корне вашего проекта. Образец файла лежит в корне .env.sample
Для запуска проекта использовать команду
```
python manage.py ruserver
```
