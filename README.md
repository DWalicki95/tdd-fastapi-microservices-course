# Test-Driven Development with FastAPI and Docker

> Hands-on learning repository — work in progress.

This repo documents my hands-on practice while working through the [Test-Driven Development with FastAPI and Docker](https://testdriven.io/courses/tdd-fastapi/) course by TestDriven.io.

I'm building a text summarization microservice from scratch using a strict TDD workflow, then containerizing and deploying it. Code is committed incrementally as I progress through the course, so the repository reflects a learning journey rather than a finished product.

---

## Why this repository exists

I treat courses as **hands-on practice**, not passive reading. Every concept introduced in the course is implemented, tested, and committed here. The goal is to build genuine fluency with production-grade backend tooling — not just to follow along.

---

## Skills being practiced

- **Test-Driven Development** — writing failing tests first, then implementing
- **FastAPI** — async RESTful API design with Python type hints
- **Docker & Docker Compose** — multi-container local development
- **PostgreSQL** with async access via Tortoise ORM
- **Database migrations** with Aerich
- **Configuration management** with pydantic-settings
- **Testing with pytest** — unit, integration, fixtures, coverage
- **CI/CD with GitHub Actions** *(upcoming)*
- **Deployment to Heroku** with Docker *(upcoming)*
- **Code quality tooling** — linting, formatting *(upcoming)*

---

## Tech stack

Python 3.13 · FastAPI · Uvicorn · PostgreSQL · Tortoise ORM · Aerich · pydantic-settings · pytest · Docker · Docker Compose

---

## Running locally

```bash
docker compose up -d --build
```

API will be available at `http://localhost:8004`.

---

## Course reference

- Course: [TDD with FastAPI and Docker](https://testdriven.io/courses/tdd-fastapi/)
- Provider: [TestDriven.io](https://testdriven.io/)

---

*This repository is for educational purposes, following the TestDriven.io course curriculum.*
