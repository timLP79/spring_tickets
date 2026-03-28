# Ticket System

A self-hostable trouble ticket system for small businesses. Built with Java 21, Spring Boot, Thymeleaf, and PostgreSQL. Designed to be deployable as a single instance per client with no vendor lock-in.

---

## Tech Stack

| Layer | Technology |
|-------|------------|
| Language | Java 21 |
| Framework | Spring Boot 3.5.0 |
| Templating | Thymeleaf |
| Data Access | Spring Data JPA |
| Database | PostgreSQL |
| Migrations | Flyway |
| Security | Spring Security |
| Build Tool | Gradle |

---

## Features (Planned)

- Create, assign, and track support tickets
- Role-based access: Admin, Agent, User
- Department-based ticket routing
- Ticket prioritization (Low, Medium, High, Urgent)
- Status tracking (Open, In Progress, On Hold, Resolved, Closed)
- Comment threads on tickets

---

## Getting Started

### Prerequisites

- Java 21
- PostgreSQL

### Configuration

The application reads database credentials from environment variables:

```
DB_URL=jdbc:postgresql://localhost:5432/ticketsystem
DB_USERNAME=your_username
DB_PASSWORD=your_password
```

### Run

```bash
./gradlew bootRun
```

---

## Project Structure

```
com.absolutecode.ticketsystem
├── config/         # Spring Security, app config
├── controller/     # HTTP request handling
├── service/        # Business logic
├── repository/     # Spring Data JPA interfaces
├── model/          # JPA entities
└── exception/      # Custom exceptions
```

---

## Contact

- GitHub: [@timLP79](https://github.com/timLP79)
- LinkedIn: [tim-palacios](https://www.linkedin.com/in/tim-palacios/)
