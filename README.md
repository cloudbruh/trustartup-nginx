<h1 align="center"> Trustartup Nginx + Docker Compose </h1>

<h3 align="center">
  Конфигурация NGINX для локального запуска Trustartup.
</h3>

## Содержание

-   [Описание](#описание)
-   [Технологии](#технологии)
-   [Использование](#использование)
-   [API](#api)

## Описание

С помощью реверс-прокси nginx и docker compose поднимает фронтенд и бэкенд.

## Технологии

-   Nginx
-   Docker

## Использование

### Docker

-   [Docker](https://www.docker.com/get-docker)
-   [Docker Compose](https://docs.docker.com/compose/)

Запустите приложение:

```bash
docker-compose up -d
```

По умолчанию приложение запустится на `8080` порте