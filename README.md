# Работа с Git
## Проверка состояния репозитория
## git status
## Добавить все файлы в индекс (отслеживать изменения в файлах)
## git add .
## Зафиксировать изменения (создать коммит)
## git commit -m "comment for commit"
## Отправить изменения на удаленный репозиторий (github.com)
## git push
## Скачать изменения из удаленного репозитория
## git pull
## !!! Вносить изменения нужно только в актуальное состояние !!! (сначала скачиваем изменения git pull)
## sudo apt install python3.10-venv

# Виртуальное окружение venv 
## СНАЧАЛА СОЗДАЕМ ОКРУЖЕНИЕ:
## создание виртуального окружения Линукс:
## python3 -m venv venv
## создание виртуального окружения Windows
## python -m venv venv
## ПОТОМ АКТИВИРУЕМ
## активация виртуального окружения Линукс:
## source venv/bin/activate
## активация виртуального окружения Windows
## venv\Scripts\activate.bat
## ПОТОМ УСТАНАВЛИВАЕМ БИБЛИОТЕКИ
## pip install requests bs4
## УСТАНОВКА ИЗ ФАЙЛА:
## pip install -r requirements.txt
## СОХРАНЕНИЕ БИБЛИОТЕК В ФАЙЛ:
## pip freeze > requirements.txt
## Деактивация
## deactivate
## Смотрим список установленных пакетов
## pip list

# Джанго
## Устанавливаем Джанго
## pip install django
## Создаем проект
## django-admin startproject password_generator_project
## Заходим в папку
## cd password_generator_project
## Поднимаемся в папку на уровень выше (если необходимо)
## cd ..
## Включаем сервер Джанго
## python manage.py runserver
## Останавливаем сервер Джанго
## "CTRL"C (^C)
## Создаем приложение внутри проекта
## python manage.py startapp generator
## Создаем миграции
## python manage.py makemigrations
## Применяем миграцию
## python manage.py migrate
## Создаем суперпользователя
## python manage.py createsuperuser
## Меняем пароль у заданного пользователя
## python manage.py changepassword admin 1234555