# GIC Cafe Assignment APIs : .NET 8.0 , MongoDB , XUnit CQRS and DDD  



This project is a .NET 8.0 web application that uses MongoDB for data storage, MediatR for CQRS (Command Query Responsibility Segregation) pattern, and Docker for containerization. It includes CRUD operations for employees and cafes in DDD pattern , along with query endpoints and MongoDB seeding.

## Project Structure

- **API**: ASP.NET Core Web API project.
- **Application**: Application layer with CQRS commands, queries, and handlers.
- **Core**: Core entities and domain logic.
- **Infrastructure**: MongoDB repository implementations and MongoSeeder for database seeding.

## Prerequisites

- Docker
- Docker Compose
- .NET SDK 8.0 (for local development, optional)

## Setup and Running

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/your-repo-name.git
cd your-repo-name
