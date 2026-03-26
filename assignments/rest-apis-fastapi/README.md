# 📘 Assignment: Building REST APIs with FastAPI

## 🎯 Objective

Learn to build scalable web APIs using the FastAPI framework. You'll create endpoints to handle HTTP requests, work with request/response models, and implement basic REST principles while practicing data structures in Python (lists, dictionaries, and data validation).

## 📝 Tasks

### 🛠️ Build a Basic Todo API

#### Description
Create a simple Todo API with FastAPI that allows users to create, read, update, and delete todo items. Your API should persist data in memory and handle various HTTP operations.

#### Requirements
Completed program should:

- Define a Todo model with fields for id, title, description, and status (completed or not)
- Implement GET endpoint to retrieve all todos
- Implement GET endpoint to retrieve a specific todo by id
- Implement POST endpoint to create a new todo with validation
- Implement PUT endpoint to update an existing todo
- Implement DELETE endpoint to remove a todo
- Return appropriate HTTP status codes for each operation


### 🛠️ Add Advanced Features

#### Description
Enhance your Todo API with filtering, sorting, and error handling to make it more robust and feature-complete.

#### Requirements
Completed program should:

- Implement query parameters to filter todos by status (completed/incomplete)
- Implement sorting functionality (by creation date or title)
- Add proper error handling with meaningful error messages
- Return a 404 status code when a todo is not found
- Validate input data and return 422 status code for invalid requests
- Add basic documentation using FastAPI's automatic OpenAPI/Swagger UI
