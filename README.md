<h1 align="center"> Trustartup Business Logic </h1>

<h3 align="center">
  Микросервис для проекта Trustartup.
</h3>

## Содержание

-   [Описание](#описание)
-   [Технологии](#технологии)
-   [Использование](#использование)
-   [API](#api)

## Описание

С помощью реверс-прокси nginx и docker compose поднимает бэкенд.

## Технологии

-   Nginx
-   Docker

## Использование

### Docker

-   [Docker](https://www.docker.com/get-docker)

Сначала постройте образ:

```bash
docker-compose build
```

Запустите микросервис:

```bash
docker-compose up -d
```

По умолчанию сервис запустится на `8080` порте