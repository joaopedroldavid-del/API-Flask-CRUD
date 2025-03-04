# API Flask CRUD

This is a simple CRUD (Create, Read, Update, Delete) API built using Flask.

## Features
- Create new records
- Retrieve existing records
- Update records
- Delete records

## Installation

### Prerequisites
- Python 3.8+
- Virtual environment (optional but recommended)

### API Endpoints

#### Create a new record
- **POST** `/tasks`
- **Request Body:**
  ```json
  {
    "title": "Task Title",
    "description": "Task Description"
  }
  ```

#### Retrieve all records
- **GET** `/tasks`

#### Retrieve a specific record
- **GET** `/tasks/<id>`

#### Update a record
- **PUT** `/tasks/<id>`
- **Request Body:**
  ```json
  {
    "title": "Updated Title",
    "description": "Updated Description"
  }
  ```

#### Delete a record
- **DELETE** `/tasks/<id>`