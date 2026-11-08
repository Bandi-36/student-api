# Student API

A simple REST API for managing students, built with Spring Boot.

## Tech Stack
Java 17, Spring Boot, Spring Data JPA, H2 Database, Maven

## Features
- Add a student (POST)
- View all students or one student (GET)
- Update a student (PUT)
- Delete a student (DELETE)

## API Endpoints
| Method | URL | Description |
|--------|-----|-------------|
| POST | /students | Add a student |
| GET | /students | List all students |
| GET | /students/{id} | Get one student |
| PUT | /students/{id} | Update a student |
| DELETE | /students/{id} | Delete a student |

## How to Run
1. Clone the repository
2. Run `./mvnw spring-boot:run` (or run `StudentApiApplication` from your IDE)
3. Open http://localhost:8080/students

## Project Structure
- `model`: Student entity
- `repository`: database access (Spring Data JPA)
- `controller`: REST endpoints