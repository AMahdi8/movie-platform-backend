# Movie Platform Backend

Backend service for a movie and TV series platform, developed as a freelance project using Django and Django REST Framework.

## Overview

A RESTful backend for managing movies and TV series, including seasons, episodes, genres, countries, languages, subtitles, trailers, reviews, tickets, and downloadable media.

The project was developed with a focus on REST API design, relational data modeling, authentication, media management, and production deployment.

## Features

* Movie and TV series management
* Season and episode management
* Genre, country, and language management
* Subtitle and trailer management
* Review and comment system
* Download file management
* User authentication and authorization
* RESTful APIs
* Pagination and API filtering
* Ticket management
* PostgreSQL database
* Asynchronous task processing with Celery
* Dockerized deployment
* Gunicorn and Nginx
* HTTPS configuration with Certbot

## Tech Stack

* Python
* Django
* Django REST Framework
* PostgreSQL
* Redis
* Celery
* Docker
* Docker Compose
* Gunicorn
* Nginx
* Certbot
* Pytest
* Git

## Architecture

The project consists of three main components:

* **Backend:** Django REST Framework application
* **Frontend:** Web application served through Nginx
* **Infrastructure:** PostgreSQL, Redis, Celery, Gunicorn, Nginx, and Certbot

## Project Structure

```text
movie-platform-backend/
├── backend/
├── frontend/
├── nginx/
├── docker-compose.yml
├── run_celery.sh
└── run_project.sh
```

## Installation

Clone the repository:

```bash
git clone https://github.com/AMahdi8/movie-platform-backend.git
cd movie-platform-backend
```

Create a `.env` file based on `.env.example` and configure the required environment variables.

Run the application using Docker Compose:

```bash
docker compose up --build
```

## API Documentation

API documentation is provided through Swagger/OpenAPI.

## Testing

Tests can be executed using pytest:

```bash
pytest
```

## Project Type

Freelance Backend Development Project
