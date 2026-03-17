# What is JSON?

## Overview

JSON (JavaScript Object Notation) is a lightweight data format used to store and exchange data between systems.

It is easy for humans to read and write, and easy for machines to parse and generate. JSON is widely used in web applications, especially in APIs, to transmit data between a client and a server.


## Why JSON Is Important

JSON is commonly used because it is simple, flexible, and language-independent.

Key benefits include:

- **Readable** – Easy for humans to understand
- **Lightweight** – Uses minimal syntax compared to other formats
- **Language-independent** – Can be used with most programming languages
- **Widely supported** – Commonly used in web APIs and modern applications


## JSON Structure

JSON represents data as key-value pairs.

Each key is a string, and each value can be a supported data type such as a string, number, object, or array.

A basic JSON object looks like this:

```json
{
  "name": "Alice",
  "age": 25
}
```

## Common Data Types in JSON

JSON supports several data types:

- **String** – `"text"`
- **Number** – `10`, `3.14`
- **Boolean** – `true`, `false`
- **Object** – `{ "key": "value" }`
- **Array** – `[1, 2, 3]`
- **Null** – `null`

### Example
```json
{
  "name": "Alice",
  "age": 25,
  "isStudent": false,
  "courses": ["Math", "Science"]
}
```

## JSON in APIs

JSON is most commonly used in REST APIs for sending and receiving data.

### Example API Response
```json
{
  "id": 1,
  "name": "Alice",
  "email": "alice@example.com"
}
```

When a client sends a request to an API, the server often responds with JSON data.
This allows structured data to be easily parsed and used by the client application.

## JSON vs Other Formats

JSON is often compared to formats like XML.

| Feature     | JSON           | XML                         |
|-------------|----------------|-----------------------------|
| Readability | Easy to read   | More verbose                |
| Size        | Lightweight    | Larger                      |
| Parsing     | Faster         | Slower                      |
| Usage       | Common in APIs | Less common in modern APIs  |

## Summary

JSON is a simple and lightweight format for representing structured data.

It is widely used in APIs and modern applications because it is easy to read, easy to process, and supported across a wide range of programming languages.
