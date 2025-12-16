# Flask Books API

A simple **RESTful API** built with **Flask** and **Flask-RESTful** to manage a collection of books. Supports **CRUD operations**: create, read, update, and delete books. Designed to run in a Jupyter notebook or as a standalone Flask app.

## Features

- List all books (`GET /books`)
- Get a single book by ISBN (`GET /books/<isbn>`)
- Add a new book (`POST /books`)
- Update a book (`PUT /books/<isbn>`)
- Delete a book (`DELETE /books/<isbn>`)

## Requirements

- Python 3.8+
- Flask
- Flask-RESTful
- nest_asyncio (if running in Jupyter notebooks)
- requests (optional, for testing)

<img width="487" height="679" alt="Screenshot (155)" src="https://github.com/user-attachments/assets/d6f51f4a-14f6-4a61-b5df-a6c1e6cd8ea2" />
<img width="455" height="674" alt="Screenshot (156)" src="https://github.com/user-attachments/assets/dd603404-4bce-4a04-b3fa-055868c8bceb" />
<img width="436" height="612" alt="Screenshot (157)" src="https://github.com/user-attachments/assets/b9764280-170e-412f-afb0-18f4b41b7f2a" />

For Delete MAthod Just add the ISBN of the book You want to delete at the end of URL/Books/ISBN

Install dependencies:

```bash
pip install flask flask-restful nest_asyncio requests
