# Fake Store API v2.1.11 — Postman API Tests

## Project Overview

API-тестирование Fake Store API в Postman.

Проект содержит коллекцию из 21 тест-кейса для проверки CRUD-операций с ресурсом Products. Тесты включают позитивные и негативные сценарии, автоматические проверки response и параметризацию запросов с помощью переменных Postman.

## Test Coverage

### CRUD Operations

- GET /products
- GET /products/{id}
- POST /products
- PUT /products/{id}
- DELETE /products/{id}

### Positive Scenarios

- Получение списка продуктов
- Получение продукта по существующему ID
- Создание продукта
- Обновление продукта
- Удаление продукта

### Negative Scenarios

- Несуществующий ID
- Некорректный ID
- Отсутствие обязательного поля
- Некорректный тип данных
- Пустой request body
- Граничные значения
- Передача дополнительных полей
- Несоответствие ID

## Automated Validations

Для каждого запроса реализованы автоматические проверки на JavaScript.

Проверяется:

- HTTP status code
- Response body
- JSON Schema
- Response time
- Обязательные поля
- Типы данных
- Бизнес-логика
- Корректность значений в response

## Postman Features

В проекте используются:

- Collection
- Environment variables
- Request variables
- JavaScript tests
- Chai Assertions
- Collection Runner

Переменные используются для параметризации запросов и повторного использования тестовых данных.

## Test Cases

Всего реализован 21 тест-кейс:

- Positive — проверка корректных сценариев
- Negative — проверка обработки невалидных данных и граничных условий

## Tools

- Postman 12.19.2
- JavaScript
- Chai Assertions
- REST API
- JSON
- HTTP

## API

Fake Store API — mock API для тестирования:

https://fakestoreapi.com

## How to Run

1. Clone or download the repository.
2. Import the Postman collection.
3. Import the environment, если он используется в коллекции.
4. Select the required environment.
5. Run individual requests or the complete collection using Collection Runner.

## Notes

Fake Store API является публичным mock API для тестирования.

Операции создания, обновления и удаления данных симулируются и не гарантируют постоянное изменение данных на сервере.

Поведение некоторых операций может отличаться при повторных запусках из-за особенностей публичного demo API.
