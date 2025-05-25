# Django Project блога "МАСТЕРПК"

## Описание

  Это проект блога на Django.

## Функции

  -  Регистрация и авторизация
  - Создание, редактирование и удаление постов
  - Просмотр списка постов, детали поста и поиск
  - Реадактирование профиля и возможноть оставлять комментарии

## Установка и настройка

### Колинирование репозитория
````bash
  git clone 
  cd django_site
````
### Создание виртуального репозитория
````bash
  python -m venv venv
  source venv/bin/activate
  source venv/Scripts/activate # Для windows
````
### Установка зависимостей 
````bash
  pip install -r requirements.txt
````
### Применение миграций 
````bash
  python manage.py migrate
````
### Применение миграций 
````bash
  python manage.py migrate
````
### Создание  суперпользователя 
````bash
  python manage.py createsuperuser
````
### Запуск сервера 
````bash
  python manage.py runserver
````
## Основные страницы
- Главная страница: http://127.0.0.1:8080/
- Детали поста: http://127.0.0.1:8080/detail/2/
- Создание поста: http://127.0.0.1:8080/create/
- Редактирование поста: http://127.0.0.1:8080/update/5/
- Профиль пользователя: http://127.0.0.1:8080/prfile/

## Тестирование 
````bash
  python manage.py test blog
````