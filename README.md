# Ecommerce Spring Boot API

This project is a small backend application built with Spring Boot.  
It represents a very simple e-commerce system and was created mainly for learning and practice.

The goal of this project is to understand how a REST API works, how data flows between controller, service, and repository layers, and how to use Spring Data JPA with a database.

## What can this API do?
- Add new products  
- List all products  
- Get a product by its ID  
- Store data in an in-memory H2 database  

## Technologies
- Java 17  
- Spring Boot  
- Spring Web  
- Spring Data JPA  
- H2 Database  
- Maven  

## API Endpoints
- GET `/products` – returns all products  
- GET `/products/{id}` – returns a product by ID  
- POST `/products` – creates a new product  

Example request body:
```json
{
  "name": "Keyboard",
  "price": 25.5
}
