# 📚 StoryPromptAPI

**StoryPromptAPI** is the backend for a creative, story-driven social platform. Users receive daily prompts created by admins and can write stories in response. Other users can read, upvote, or downvote each other's stories. Each user has a profile that they can customize, along with a personal history of past submissions.

This API handles all server-side logic and data operations — from user authentication and profile management to story posting and voting.

---

## ✨ Features

- 🔐 User registration and login (with JWT authentication)
- 🧠 Daily writing prompts created by admins
- ✍️ Story creation, editing, and deletion
- 👍👎 Like and dislike system for both prompts and stories
- 👤 Profile customization and post history
- 🛠️ Full REST API using .NET Core Web API

---

## 🛠️ Tech Stack

- **.NET 8 / ASP.NET Core Web API**
- **Entity Framework Core** (with SQL Server)
- **ASP.NET Core Identity** for user authentication and management
- **JWT Bearer Authentication** for secure token-based access

---

## 📦 Notable NuGet Packages

- `Microsoft.AspNetCore.Authentication.JwtBearer` – For handling JWT tokens
- `Microsoft.AspNetCore.Identity.EntityFrameworkCore` – Identity framework integration with EF Core
- `Microsoft.EntityFrameworkCore` – ORM for database interactions
- `Microsoft.EntityFrameworkCore.SqlServer` – SQL Server provider
- `Microsoft.EntityFrameworkCore.Design` – Design-time support (e.g., migrations)
- `Microsoft.EntityFrameworkCore.Tools` – CLI and tooling support
