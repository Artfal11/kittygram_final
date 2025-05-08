Kittygram Final - это веб-приложение для публикации и просмотра фотографий котиков. Пользователи могут создавать и просматривать котиков, загружать фотографии и ставить им достижения.


## Описание проекта

Сайт с возможностью публикации фотографий котов и их достижений.

## Технологии

- Фронтенд: React
- Бэкенд: Django Rest Framework
- База данных: PostgreSQL
- Nginx
- Docker
- Gunicorn «Green Unicorn»
- Github actions


## Запуск проекта

Выполняем запуск:

```bash
docker compose -f docker-compose.yml up
```

## Миграции



```bash
docker compose -f [имя-файла-docker-compose.yml] exec backend python manage.py migrate
```

И далее проект доступен на:

```
http://localhost:9000/
```