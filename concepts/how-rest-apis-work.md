# How REST APIs Work

## Overview

REST (Representational State Transfer) is a widely used architectural style for building web APIs. REST APIs enable communication between a client and a server using standard HTTP methods.

REST APIs are designed to be simple, scalable, and stateless, making them the most common type of API used in modern web applications.


## Key Characteristics of REST APIs

REST APIs follow several core principles:

- **Stateless** – Each request contains all the information needed. The server does not store client state.
- **Client-Server Architecture** – The client and server are separate, allowing independent development.
- **Uniform Interface** – Resources are accessed in a consistent way using standard HTTP methods.
- **Resource-Based** – Everything is treated as a resource identified by a URL.


## How REST APIs Work

REST APIs use a request-and-response model over HTTP.

1. The client sends an HTTP request to a specific endpoint.
2. The server processes the request.
3. The server returns an HTTP response with data or status information.

### Example Workflow

```
Client → HTTP Request → Server → HTTP Response → Client
```

## HTTP Methods in REST APIs

REST APIs use standard HTTP methods to perform operations on resources.

- **GET** – Retrieve data
- **POST** – Create new data
- **PUT** – Update existing data
- **DELETE** – Remove data

### Example Requests

```http
GET /users
POST /users
PUT /users/1
DELETE /users/1
```

Each method corresponds to a specific action on a resource.

## REST API Endpoints

An endpoint is a URL that represents a specific resource.

### Example
```http
GET https://api.example.com/users
GET https://api.example.com/users/1
```

- `/users` refers to a collection of users
- `/users/1` refers to a specific user

## Request and Response Format

REST APIs typically use JSON to exchange data.

### Example Request

```http
POST /users
```

### Example Response
```json
{
  "id": 1,
  "name": "Alice"
}
```

JSON (JavaScript Object Notation) is lightweight and easy to read, making it the most commonly used data format in REST APIs.

## Status Codes

REST APIs use HTTP status codes to indicate the result of a request.

- **200 OK** – Request succeeded
- **201 Created** – Resource created successfully
- **400 Bad Request** – Invalid request
- **401 Unauthorized** – Authentication required
- **404 Not Found** – Resource not found
- **500 Internal Server Error** – Server error

## Summary

REST APIs use standard HTTP methods to enable communication between clients and servers.

By following a stateless and resource-based design, REST APIs provide a scalable and flexible approach to building modern web services.
