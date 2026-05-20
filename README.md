# MVCModelFirstWebApp

ASP.NET Core MVC web application built as part of the AUEB Coding Factory bootcamp.

## Current State

This project is **partially implemented**. Currently working:
- User registration (Teacher & Student sign up)
- User login with cookie-based authentication
- Teacher Dashboard (with placeholder data)
- Logout

Not yet implemented:
- Full CRUD for Teachers, Students, Courses
- Admin panel functionality
- Student Dashboard

## Tech Stack

- ASP.NET Core MVC (.NET 10)
- Entity Framework Core (Code First)
- SQL Server (via Docker)
- Serilog
- AutoMapper
- BCrypt password encryption
- Cookie Authentication & Role-based Authorization

## Run with Docker

```bash
docker compose up -d --build
```

Access at `http://localhost:8081`
