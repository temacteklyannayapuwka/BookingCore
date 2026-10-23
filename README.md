# BookingCore

[English](README.md) | [Русский](README.ru.md)

BookingCore is an HTTP API project for booking meeting rooms and equipment.

## Current capabilities

- HTTP server listening on port 8080.
- `GET /health` returns `200 OK` with `{"status":"ok"}`.
- HTTP server timeouts.

## Run

Requires Go 1.22 or later.

```sh
go run ./cmd/bookingcore
```

Check the server:

```sh
curl -i http://localhost:8080/health
```
