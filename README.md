# Spring Boot Item API

A simple **Java Spring Boot** backend application that implements a **RESTful API** for managing items, suitable for e-commerce or catalog-style use cases.

## Features

- Add a new item
- Retrieve all items
- Retrieve item by ID
- In-memory data storage using `ArrayList`
- Input validation using **Jakarta Validation**

## Tech Stack

- **Java 21**
- **Spring Boot**
- **Maven**
- **Jakarta Validation**

## API Endpoints

### Add Item

**POST** `/items`  

**Request Body:**
```json
{
  "name": "Laptop",
  "description": "Gaming laptop"
}
**Response:**
```json
{
  "id": 1,
  "name": "Laptop",
  "description": "Gaming laptop"
}
**Get All Items

GET /items**
**Response:**
```json
[
  {
    "id": 1,
    "name": "Laptop",
    "description": "Gaming laptop"
  },
  {
    "id": 2,
    "name": "Phone",
    "description": "Smartphone"
  }
]
**Get Item by ID

GET /items/{id}**
**Response:**
```json
{
  "id": 1,
  "name": "Laptop",
  "description": "Gaming laptop"
}
Getting Started
Prerequisites

Java 21 or higher

Maven

Git

Run Locally

1.**Clone the repository:**
git clone https://github.com/Sksumaya100/springboot-item-api.git
cd springboot-item-api
2.**Build the project:**
mvn clean install
3.**Run the application:**
mvn spring-boot:run
4.API will be available at: http://localhost:8080/items

**License**

This project is open source. Feel free to use, modify, and distribute.



