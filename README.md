# Task Master API

REST API for Task Management with User Roles and JWT Authentication.

## Tech Stack

- **FastAPI** - Web framework
- **SQLAlchemy** - ORM
- **Pydantic** - Data validation
- **Alembic** - Database migrations
- **Poetry** - Dependency management

## Requirements

- Python 3.14+

## Installation

```bash
poetry install
```

## Configuration

Copy `.env.example` to `.env` and configure the environment variables.

## Running

```bash
poetry run uvicorn src.app.main:app --reload
```

## License

None
