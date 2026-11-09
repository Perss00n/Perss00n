
# Hi, I'm Marcus! 👋

I've been interested in computers and programming since my teenage years, but ended up spending 18 years working as a floor layer. In 2023, I decided it was time to turn that long-standing interest into something more and went back to school to become a developer.

I graduated in May 2026 as a backend developer, with C# and .NET as my main focus. During my internship at IOSoft AB, I got to work in a real development team, writing code, tests, and getting feedback through code reviews.

These days, I spend a lot of my time building my own projects and exploring new technologies. I mainly enjoy backend development, but I also like frontend work and understanding how everything connects, from the database to what the user sees.

I'm also interested in AI, particularly running local models and experimenting with coding agents to see where they can actually help in software development.

- 🌍 Based in Uddevalla, Sweden
- 🌐 [Personal website](https://marcuslehm.se)
- 🎓 Backend Developer — Yrkeshögskolan i Uddevalla (2024–2026)
- 💼 Looking for my first full-time developer role

## 🛠️ Technologies & Tools

- **Languages:** C#, PHP, JavaScript, SQL, HTML, CSS
- **Frameworks:** .NET, ASP.NET Core, Blazor, Entity Framework Core, Laravel
- **Databases:** SQL Server, MySQL
- **Testing:** xUnit, NSubstitute, Testcontainers
- **Tools:** Visual Studio, VS Code, Git, GitHub, GitHub Actions, Docker
- **Other:** REST APIs, Clean Architecture, CQRS, ASP.NET Identity

## ✨ Featured Projects

Here are two of my larger .NET projects. I built both from scratch, handling everything from application architecture and database design to frontend development and testing.

### 🎮 [PlaySphere](https://github.com/Perss00n/PlaySphere-Showcase)

A web application for discovering games, built with **.NET 10**, **Blazor Server**, and **Clean Architecture**.

Users can browse new releases, search the IGDB game catalog, filter games by genre, platform, year, and rating, and save favorites to their profiles.

Some of the things I've worked on:

- Clean Architecture with separation between Domain, Application, Infrastructure, and presentation
- Caching with `IMemoryCache.GetOrCreateAsync` to avoid duplicate requests
- Result pattern for handling expected failures without relying on exceptions
- ASP.NET Identity with multiple user roles
- Around 380 unit tests using xUnit v3 and NSubstitute

`C#` · `.NET 10` · `Blazor Server` · `EF Core 10` · `SQL Server` · `IGDB API` · `xUnit`

### 🎉 [Office Event Hub](https://github.com/Perss00n/Office-Event-Hub-Showcase)

An event management application for workplaces, built with **.NET 10**, **.NET Aspire**, **Blazor Server**, and **Clean Architecture**.

Employees can create events, upload images, register or unregister, and receive live updates when something changes.

Some of the technical parts include:

- Domain model with an `Event` aggregate root that handles its own business rules
- CQRS-style commands and queries
- Real-time updates between connected clients
- OpenTelemetry for tracing and metrics
- Integration tests using Testcontainers with a real SQL Server instance

`C#` · `.NET 10` · `.NET Aspire` · `Blazor Server` · `EF Core 10` · `SQL Server` · `CQRS` · `Testcontainers`

> **About the repositories:** These are public showcases of my projects. The complete source code is currently kept private, but I'm happy to walk through the code and explain how things work.

## 📫 Get in Touch

- **Email:** [Perss00n@gmail.com](mailto:Perss00n@gmail.com)
- **Website:** [marcuslehm.se](https://marcuslehm.se)
- **LinkedIn:** [Marcus Lehm](https://www.linkedin.com/in/marcus-lehm-903222412)

Feel free to reach out if you want to talk about development, projects, or potential opportunities.
