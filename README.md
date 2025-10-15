# Challenge Generator

Challenge Generator is a web application designed to create, manage, and serve programming challenges.
It provides a backend API and a modern frontend interface for users to interact with challenges efficiently.
Supports future extensions like user authentication and challenge scoring.

## Features

- Create, update, and delete challenges
- Fast API responses with validation
- Persistent storage in MySQL
- Modern interactive frontend with React

## Tech Stack

### Backend
- **FastAPI** – Python web framework for building APIs
- **SQLAlchemy** – ORM for database interactions
- **Pydantic** – Data validation and settings management
- **MySQL** – Relational database for persistent storage
- **Uvicorn** – ASGI server to run the FastAPI app

### Frontend
- **React** – JavaScript library for building user interfaces

## Setup Instructions

1. **Clone the repository**
```bash
git clone https://github.com/MHZ0/Challenge-Generator.git
cd Challenge-Generator
```
2. **Backend Setup**
```bash
cd backend
```
# create virtual environment and install dependencies
```bash
python -m venv venv
venv\Scripts\activate   # Windows
pip install -r requirements.txt
```
# Run the backend server
```bash
uvicorn server.py --reload
```
3. **Frontend Setup**
```bash
cd frontend
npm install
npm start
```
Notes
Make sure to add your .env file for secrets (API keys, DB credentials, Clerk Secrets), which is ignored by Git.


