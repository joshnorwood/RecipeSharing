# Recipe Sharing App

A full-stack web application for sharing and discovering recipes, built with ASP.NET Core and Razor Pages. Users can create accounts, post their own recipes, and browse recipes shared by others.

## Features

- **User authentication** — secure registration and login powered by ASP.NET Core Identity
- **Create & share recipes** — authenticated users can post their own recipes
- **Browse recipes** — view recipes shared by the community
- **SQLite database** — lightweight local data storage via Entity Framework Core
- **Responsive UI** — clean, accessible interface using Razor Pages and Bootstrap

## Tech Stack

- **C#** — primary language
- **ASP.NET Core** — web framework
- **Razor Pages** — server-side UI rendering
- **Entity Framework Core** — database ORM
- **ASP.NET Core Identity** — user authentication & authorization
- **SQLite** — local database
- **HTML / CSS / Bootstrap** — frontend styling

## Getting Started

### Prerequisites

- [.NET SDK 6.0+](https://dotnet.microsoft.com/download)
- Visual Studio 2022 or VS Code with the C# extension

### Run Locally

```bash
git clone https://github.com/joshnorwood/Recipe-Sharing.git
cd Recipe-Sharing
dotnet restore
dotnet run
```

Then open your browser and navigate to `https://localhost:5001`.

## Project Structure

```
Recipe-Sharing/
├── Models/          # Data models (Recipe, User, etc.)
├── Pages/           # Razor Pages (UI + page logic)
├── Data/            # Database context and migrations
├── Areas/Identity/  # Authentication pages (login, register)
├── wwwroot/         # Static files (CSS, JS, images)
├── Program.cs       # App entry point and service configuration
└── appsettings.json # App configuration
```

## What I Learned

- How to build a **full-stack web app** with ASP.NET Core and Razor Pages
- How to implement **user authentication** with ASP.NET Core Identity
- How to design and query a **relational database** using Entity Framework Core
- How **MVC architecture** separates data, logic, and presentation
- How to scaffold and customize **CRUD operations** for a data model

## Future Improvements

- [ ] Add recipe categories and search/filter functionality
- [ ] Allow users to upload photos with their recipes
- [ ] Add ratings and comments on recipes
- [ ] Deploy to Azure App Service for public access
- [ ] Add ingredient scaling based on serving size

## Author

Built by Josh Norwood as a full-stack development project.  
🔗 [GitHub](https://github.com/joshnorwood)

---

*Built with C#, ASP.NET Core, Entity Framework Core, and SQLite.*
