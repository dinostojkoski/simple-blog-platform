# Simple Blog Platform

A full-stack blog platform with authentication using Spring Boot (backend) and ReactJS (frontend).

## Features
- User login
- Create, edit, delete blog posts
- REST API with Spring Boot
- Frontend built with React and TailwindCSS

## Tech Stack
- **Frontend:** ReactJS, TailwindCSS
- **Backend:** Spring Boot, Java
- **Database:** PostgreSQL
- **Containerization:** Docker & Docker Compose

## How to Run Locally

### Getting Started with Docker

### 1. Run Backend with Docker

> **Pre-requisites:** Install [Docker Desktop](https://www.docker.com/products/docker-desktop)

- Open Docker Desktop
- Open terminal in your IDE at the project root
- Run:

```bash
docker-compose up
````

Make sure to update `docker-compose.yml` if necessary (e.g., DB credentials or ports).

### 2. Run Frontend

Open a new terminal tab/window:

```bash
cd blog-frontend
npm install
npm run dev
```

## Login Credentials

Use the following credentials to log in:

* **Email:** `user@test.com`
* **Password:** `password`

If you don’t see the user icon after logging in, **refresh the page**.

## Notes

* Backend runs on port `8080` by default.
* Frontend runs on `http://localhost:5173` (or similar).
* CORS must be configured in Spring Boot to allow frontend access during dev.

## Author

Dino Stojkoski
GitHub: [@dinostojkoski](https://github.com/dinostojkoski)