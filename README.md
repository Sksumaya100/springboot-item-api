# Item Management REST API (Spring Boot)

This is a simple Java Spring Boot backend application that implements a RESTful API
for managing items (similar to e-commerce or movie catalog use cases).

## Features
- Add a new item
- Get all items
- Get item by ID
- In-memory data storage using ArrayList
- Input validation using Jakarta Validation

## Tech Stack
- Java 21
- Spring Boot
- Maven

## API Endpoints

### Add Item
POST /items

Request Body:
```json
{
  "name": "Laptop",
  "description": "Gaming laptop"
}
