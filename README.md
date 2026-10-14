# Social Media API (FastAPI)

A REST API for a simple social media platform, built step by step while learning backend development with Python.

## Features (planned)
- [ ] CRUD for posts
- [ ] User registration and login (JWT authentication)
- [ ] Votes / likes on posts
- [ ] PostgreSQL database with SQLAlchemy ORM
- [ ] Database migrations with Alembic
- [ ] Automated tests with Pytest
- [ ] Docker and Docker Compose
- [ ] CI with GitHub Actions

## Tech stack
Python, FastAPI, Pydantic, PostgreSQL, SQLAlchemy, Alembic, Pytest, Docker

## Run locally
1. Create and activate a virtual environment:
   - Windows: `py -3 -m venv venv` then `venv\Scripts\activate`
2. Install dependencies: `pip install -r requirements.txt`
3. Start the server: `uvicorn main:app --reload`
4. Open http://127.0.0.1:8000/docs for the interactive API docs.

## Progress log
See [notes/learning-log.md](notes/learning-log.md).

## Author
Ayoub Ben-Yamina, M.Sc. Artificial Intelligence & Big Data
