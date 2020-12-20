Описание
-----------
Здесь представлен сайт с новостными блогами на различные темы айти новостей. Где любой зарегистрированный пользователь может разместить свою статью.

Требования
-----------
Для развертывания и дальнейшего редактирования сайта локально, на своем компьютере, должны быть установлены
```
python 3.5 +
```
Как установить
--------------
Установка Python3
```
sudo apt-get install python3
sudo apt-get install python3-pip
```
Клонируйте репозиторий, перейдите в папку itNews и установите необходимые библиотеки
```
git clone https://github.com/MZen2610/itNews.git
cd itNews
pip install -r requirements.txt
```
В папке itNews/itNews требуется создать файл .env, где вы будете хранить данные для подключения
```
itNews/.env
```
Скопируйте данные из файла itNews/env-environ в новый файл itNews/.env
Заполните данные в новом файле itNews/.env
```
DJANGO_SECRET_KEY=your_secret_key

DJANGO_DEBUG=False
```

Запустите проект
```
python3 manage.py runserver
```
Перейдите по адресу http://127.0.0.1:8000/
Опубликованный на сервере проект можно так же увидеть по адресу https://django-itnews.herokuapp.com/

Сайт был создан по урокам https://itproger.com/
