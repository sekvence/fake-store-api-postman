# Fake Store API v2.1.11 — Postman API Tests

## Project Overview

This project contains API tests for the Fake Store API created in Postman.

The collection covers CRUD operations for the **Products** endpoint.

## Covered Endpoints

- GET /products
- GET /products/{id}
- POST /products
- PUT /products/{id}
- DELETE /products/{id}

## Test Coverage

### Positive scenarios

- Get all products
- Get product by existing ID
- Create product
- Update product
- Delete product

### Negative scenarios

- Non-existing ID
- Invalid ID
- Missing required field
- Invalid data type
- Empty body
- Boundary values
- Extra fields
- ID mismatch

## Validations

- Status codes
- Response body
- JSON Schema
- Response time
- Business logic validation
- Required fields
- Data types

## Tools

- Postman 12.19.2
- JavaScript
- Chai Assertions

## API

https://fakestoreapi.com

## How to use

1. Clone or download this repository.
2. Import the Postman collection.
3. (Optional) Import the Postman environment.
4. Run individual requests or the entire collection using Postman Collection Runner.

## Notes

- Fake Store API is a mock API intended for testing purposes.
- Product creation, update and deletion are simulated and are not permanently stored.
- Some endpoints may return inconsistent responses during repeated collection runs because of the public demo environment.
