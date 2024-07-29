# GIC Assignment APIs : .NET 8.0 , MongoDB , XUnit, MediatR for CQRS and DDD  

## .NET 8.0 , MongoDB , XUnit, MediatR for CQRS and DDD  



This project is a .NET 8.0 web application that uses MongoDB for data storage, MediatR for CQRS (Command Query Responsibility Segregation) pattern, and Docker for containerization. It includes CRUD operations for employees and cafes in DDD pattern , along with query endpoints and MongoDB seeding.

## Project Structure

- **API**: ASP.NET Core Web API project.
- **Application**: Application layer with CQRS commands, queries, and handlers.
- **Domain**: Core entities and domain logic.
- **Infrastructure**: MongoDB repository implementations and MongoSeeder for database seeding.

## Prerequisites

- Docker
- Docker Compose
- .NET SDK 8.0 (for local development, optional)

### Domain-Driven Design(DDD)
Domain-Driven Design(DDD) is a collection of principles and patterns that help developers craft elegant object systems. Properly applied it can lead to software abstractions called domain models. These models encapsulate complex business logic, closing the gap between business reality and code.

## Setup and Running

### 1. Clone the Repository

```bash
git clone https://github.com/manojkke/GICCafe.API.git
cd your-repo-name
