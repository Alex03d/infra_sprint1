Kittygram

Введение

Kittygram - это веб-приложение, которое позволяет пользователям делиться фотографиями своих котов. Пользователи могут создавать профили, публиковать фотографии, ставить "лайки" и комментировать посты других пользователей.

Технологии

Kittygram разработан с использованием следующих технологий:

Python 3
Django
PostgreSQL
Docker
Nginx
Gunicorn

Установка и запуск

Требования
Python 3
Docker и Docker Compose
Git

Установка

Клонируйте репозиторий на свой локальный компьютер:

git clone git@github.com:Alex03d/infra_sprint1.git

Перейдите в директорию проекта:

cd kittygram

Создайте виртуальное окружение и активируйте его:

python3 -m venv venv

source venv/bin/activate

Установите зависимости проекта:

pip install -r requirements.txt

Запустите миграции:

python manage.py migrate

Запуск

Запустите сервер разработки Django:

python manage.py runserver

Откройте веб-браузер и перейдите по адресу http://pussygram.hopto.org

Kittygram распространяется под лицензией MIT. Смотрите файл LICENSE для подробной информации.

Контакты

Если у вас есть вопросы или предложения, пожалуйста, свяжитесь с нами по электронной почте: adondokov@yandex.ru
