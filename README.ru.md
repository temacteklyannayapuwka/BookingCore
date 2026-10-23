# BookingCore

[English](README.md) | [Русский](README.ru.md)

BookingCore — проект HTTP API для бронирования переговорных и оборудования.

## Текущие возможности

- HTTP-сервер на порту 8080.
- `GET /health` возвращает `200 OK` и `{"status":"ok"}`.
- Таймауты HTTP-сервера.

## Запуск

Требуется Go 1.22 или новее.

```sh
go run ./cmd/bookingcore
```

Проверка сервера:

```sh
curl -i http://localhost:8080/health
```
