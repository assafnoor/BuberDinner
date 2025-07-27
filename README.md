# BuberDinner

BuberDinner is a modular, layered .NET 8 solution designed to demonstrate clean architecture principles for building scalable and maintainable web applications. The project leverages modern frameworks and libraries such as ASP.NET Core, Entity Framework Core, MediatR, and Mapster.

## Solution Structure

- **src/BuberDinner.Api**  
  ASP.NET Core Web API entry point. Handles HTTP requests and orchestrates application logic.

- **src/BuberDinner.Application**  
  Contains business logic, application services, and use cases. Implements CQRS and MediatR patterns.

- **src/BuberDinner.Domain**  
  Core domain models and business rules. Encapsulates entities, value objects, and domain events.

- **src/BuberDinner.Infrastructure**  
  Implements persistence, authentication, and external integrations. Uses Entity Framework Core and JWT authentication.

- **src/BuberDinner.Contracts**  
  Shared contracts and DTOs for communication between layers.

- **tests/UnitTests/BuberDinner.Application.UnitTests**  
  Unit tests for application layer using xUnit, Moq, and FluentAssertions.

## Getting Started

### Prerequisites

- [.NET 8 SDK](https://dotnet.microsoft.com/download/dotnet/8.0)
- SQL Server (for local development)
- Visual Studio 2022 or VS Code

### Setup

1. **Clone the repository:**
   
2. **Restore dependencies:**
   
3. **Apply database migrations:**
   
## Technologies Used

- ASP.NET Core (.NET 8)
- Entity Framework Core (SQL Server)
- MediatR (CQRS)
- Mapster (Object Mapping)
- JWT Authentication
- ErroOr
- xUnit, Moq, FluentAssertions (Testing)



**Note:** Update connection strings and secrets as needed in `appsettings.json` and user secrets.

