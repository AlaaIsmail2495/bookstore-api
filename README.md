# Bookstore Management API 📚

A simple and robust RESTful API built with **FastAPI** to manage a bookstore inventory, featuring data persistence using JSON.

## 🚀 Features
- **GET /books**: Retrieve a list of books with optional limit filtering.
- **GET /books/{id}**: Fetch a single book by its ID.
- **POST /books**: Add a new book to the inventory.
- **PUT /books/{id}**: Update an existing book's details.
- **DELETE /books/{id}**: Remove a book from the system.

## 🛠️ Tech Stack
- **Python**
- **FastAPI**
- **Pydantic**
- **JSON** (for data storage)

## 💻 How to Run
1. Install dependencies:
   ```bash
   pip install fastapi uvicorn pydantic