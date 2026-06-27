# Hi, I'm Matheus 

I'm a software developer based in Moncton, New Brunswick, originally from Brazil. I finished my Software Development diploma at NBCC in June 2026, and my focus is backend work with **C# and ASP.NET Core**.

Most of what I build lives on the server side: REST APIs, data models, authentication, and the architecture that holds it all together. For my final term I did a practicum at **Gravitit**, where I worked on a real product that's now running in production.

I'm currently looking for my first backend / full-stack developer role in Canada.

[LinkedIn](https://www.linkedin.com/in/mcamiloferraro/) · [Portfolio](https://matheusferraro.github.io/) · [Email](mailto:matheus.ferraro@gmail.com)

---

## What I've been building

### Flight Plan (TA-FLIGHTPLAN) — live in production
My practicum project at Gravitit. It's a web app that lets pilots fill out an official ICAO flight plan online and download it as a print-ready PDF, replacing the hand-filled paper form. There's airport autocomplete, cross-field validation that catches mistakes before the PDF is generated, and an admin area for managing users, airports, and templates.

| | |
| :--- | :--- |
| **Stack** | .NET 8 · ASP.NET Core MVC · EF Core · SQL Server · ASP.NET Core Identity · FreeSpire.XLS (Excel → PDF) · Serilog + Application Insights |
| **Architecture** | N-Tier / Layered — one solution, five projects, dependencies pointing inward |
| **Live** | [miplandevuelo.com](https://miplandevuelo.com/) |

This is the project I learned the most from — real users, a real deploy, real logging and monitoring.

### TCG Project — current work
What I'm building right now: a backend for a trading card game, structured with **Vertical Slice Architecture**. Each feature owns its full path (request → handler → data) instead of being spread across horizontal layers. It's a deliberate contrast to the layered and clean-architecture projects below — same kind of problem, different way of organizing the code.

| | |
| :--- | :--- |
| **Stack** | C# · ASP.NET Core Web API · EF Core · SQL Server |
| **Architecture** | Vertical Slice |
| **Status** | In progress |

### RecipeWorld
A full-stack recipe app built with ASP.NET Core MVC. A service layer keeps the controllers thin, there's full authentication with role-based access (admins approve new ingredients and categories before they go live), code-first migrations, and unit tests.

| | |
| :--- | :--- |
| **Stack** | .NET 8 · ASP.NET Core MVC · EF Core · SQL Server · ASP.NET Core Identity (RBAC) · xUnit · Moq · Bootstrap |
| **Architecture** | Layered / service pattern |
| **Repo** | [RecipeWorld](https://github.com/MatheusFerraro/RecipeWorld) |

### SmartRetail-System — capstone
An end-to-end inventory tracker: an ESP32 with an ultrasonic sensor measures shelf stock, posts it to an ASP.NET Core Web API, and a live dashboard reads from it. The backend and the API contract are the parts I cared about most; the hardware was where I started before moving fully into backend.

| | |
| :--- | :--- |
| **Stack** | ASP.NET Core Web API · C# · EF Core · SQL Server · Chart.js · ESP32 (C++) |
| **Repo** | [SmartRetail-System](https://github.com/MatheusFerraro/SmartRetail-System) · [Demo video](https://www.youtube.com/watch?v=raHG7weVkfM) |

---

## Built with others

Two projects I worked on with [Brian Cabello](https://github.com/briancabello):

| Project | What it is | Stack |
| :--- | :--- | :--- |
| [Flavor-da-Casa](https://github.com/briancabello/Flavor-da-Casa) | Restaurant management system | Java · Spring Boot · **Clean Architecture** |
| [Trivia-Quest](https://github.com/briancabello/Trivia-Quest) | Real-time multiplayer trivia game | Node.js · Express · Socket.io |

---

## A note on architecture

Something I've done on purpose is build across different architectural styles, so I understand the trade-offs firsthand instead of always reaching for the same template:

- **Clean Architecture** — Flavor-da-Casa
- **Layered / N-Tier** — Flight Plan
- **Vertical Slice** — my current TCG project

Each one answers the same question — *where does the business logic go?* — in a different way, and each fits a different size of problem.

---

## Tools I work with

| Area | Tech |
| :--- | :--- |
| **Backend** | C#, .NET, ASP.NET Core (MVC + Web API), Entity Framework Core, Java / Spring Boot |
| **Data** | SQL Server, some MongoDB |
| **Testing** | xUnit, Moq |
| **Frontend** | JavaScript, React, HTML, CSS, Chart.js |
| **Other** | Git, Docker (basics), Azure (learning), Serilog |
| **Earlier work** | C / C++ on ESP32 & Arduino — where I started, before focusing on backend |

---

## Languages

🇧🇷 Portuguese (native) · 🇨🇦 English (fluent) · 🇫🇷 French (learning)

---

📫 Open to backend and full-stack roles. The easiest way to reach me is [LinkedIn](https://www.linkedin.com/in/mcamiloferraro/) or [email](mailto:matheus.ferraro@gmail.com).