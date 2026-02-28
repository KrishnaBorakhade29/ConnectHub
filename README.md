# ConnectHub

ConnectHub is a backend REST API project built using **Java 21** and **Spring Boot 3**, designed for social networking applications. It provides core features like user registration/login, post creation, commenting, and likes — all secured with JWT-based authentication.

## Features

- User Authentication (Register / Login / Refresh Token)
- JWT Security with Spring Security
- Post, Comment, and Like management
- MySQL database with JPA/Hibernate
- Modular layered architecture (Controller → Service → Repository)

## Tech Stack

- Java 21
- Spring Boot 3
- Spring Security + JWT
- MySQL
- Lombok + MapStruct
- Maven

## Getting Started

1. Clone the repository
2. Set up a MySQL database named `connecthub`
3. Update `application.properties` with your DB credentials
4. Run with `./mvnw spring-boot:run`

## API Endpoints

| Method | Endpoint | Description |
|--------|----------|-------------|
| POST | `/auth/register` | Register a new user |
| POST | `/auth/login` | Login and get JWT |
| GET | `/users` | Get all users |
| POST | `/posts` | Create a post |
| GET | `/posts` | Get all posts |
| POST | `/comments` | Add a comment |
| POST | `/likes` | Like a post |

## License

MIT