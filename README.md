# Skinet Project Repository

This is my learning repository for building the SkiNet e-commerce app following [Neil Cummings' Udemy course](https://www.udemy.com/course/learn-to-build-an-e-commerce-app-with-net-core-and-angular).

This app is built using .Net 9 and Angular 20

## 🔧 Tech Stack Overview

> 1. Backend: ASP.NET Core 9 Web API
> 1. Frontend: Angular 20 SPA
> 1. Database: EF Core + SQL Server
> 1. Authentication: JWT-based Auth
> 1. Real-Time Communication: SignalR
> 1. UI Components: Angular Material

🚀 The project emphasizes clean architecture, secure authentication, rich user profiles, and scalable design patterns—ideal for full-stack developers aiming to sharpen practical skills.

### 🔗 Inspired by [Neil Cummings' SkiNet course and source code](https://github.com/TryCatchLearn/skinet)

## Getting Started

1. Clone the repository
2. Navigate to the project directory
3. Restore dependencies: `dotnet restore`
4. Run the API: `dotnet run --project src/API`
5. Open browser to: `https://localhost:7007/scalar/v1`

## Project Setup Instructions

```powershell
# Check .NET version
dotnet --info
dontnet -h

# List available templates
dotnet new list

# Create solution
dotnet sln -h
dotnet new sln

# Create API project with controllers
dotnet new webapi -controllers -n API -f net9.0 -o src/API
dotnet sln add src/API/

# List solution projects
dotnet sln list

# Restore packages
dotnet restore

# Run the application
dotnet run --project src/API
```
