# Eventide Infrastructure

Инфраструктура для киберспортивной платформы Eventide.

## Сервисы

| Сервис | Порт |
|--------|------|
| Auth DB | 5432 |
| User DB | 5433 |
| Tournament DB | 5434 |
| Bracket DB | 5435 |
| Match DB | 5436 |
| Notification DB | 5437 |
| Redis | 6379 |
| RabbitMQ | 5672 |
| RabbitMQ UI | 15672 |

## Запуск

```bash
docker-compose up -d