# SentinelStream

SentinelStream is a FinTech transaction monitoring backend built with **FastAPI**, **PostgreSQL**, **SQLAlchemy Async**, and **JWT authentication**.

The project demonstrates secure backend API development for user authentication, protected routes, and financial transaction management.

## Project Overview

SentinelStream focuses on building a clean backend foundation for financial transaction workflows. It includes user registration, login, JWT-based authentication, password hashing, transaction creation, and protected transaction retrieval.

## Key Features

- User registration and login
- JWT-based authentication
- Secure password hashing
- Protected API routes
- Create financial transactions
- Fetch authenticated user transactions
- PostgreSQL database integration
- Async SQLAlchemy ORM usage
- Interactive Swagger API documentation

## Tech Stack

| Area | Tools |
|---|---|
| Backend | FastAPI, Python |
| Database | PostgreSQL |
| ORM | SQLAlchemy Async |
| Authentication | JWT |
| Server | Uvicorn |
| API Docs | Swagger UI / OpenAPI |

## Authentication Flow

1. Register a new user
2. Login with credentials
3. Receive a JWT access token
4. Send the token in the request header
5. Access protected transaction APIs

```http
Authorization: Bearer <token>
```

## API Documentation

After starting the server, open:

```text
http://127.0.0.1:8000/docs
```

## Local Setup

```bash
git clone https://github.com/Kaif0333/SentinelStream.git
cd SentinelStream
```

Install dependencies based on the project requirements file if available:

```bash
pip install -r requirements.txt
```

Run the FastAPI app:

```bash
uvicorn app.main:app --reload
```

The app runs at:

```text
http://127.0.0.1:8000
```

## Example API Areas

| Area | Description |
|---|---|
| Auth | Register and login users |
| Transactions | Create and fetch financial transactions |
| Protected Routes | Access APIs only with a valid JWT token |
| API Docs | Explore endpoints through Swagger UI |

## Purpose

This project demonstrates real-world backend development skills for FinTech-style applications, including authentication, database operations, protected APIs, and clean API design.
