# Fake Store API (v2.1.11) Testing (Postman)

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

- Postman (12.19.2)
    
- JavaScript
    
- Chai Assertions
    

## API

[https://fakestoreapi.com](https://fakestoreapi.com)