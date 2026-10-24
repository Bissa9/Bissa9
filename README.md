# Hi, I'm Ebtisam Khalid 👋

Full-stack developer. I build complete systems: ASP.NET Core back ends with real-time features and transactional business logic, React and Next.js front ends, and the occasional interactive 3D scene.

**Open to front-end, back-end and full-stack roles.**

## Featured projects

### [SupportTime](https://github.com/Bissa9/RealtimeSupportSystem): real-time help desk (.NET 10)
Customers open tickets, agents claim them, and both talk live over SignalR. A background service tracks SLA deadlines and flags every ticket as within SLA, at risk or breached.

- Three roles (customer, agent, admin), editable SLA policies by priority, in-app notifications
- ASP.NET Core MVC, EF Core, ASP.NET Identity, SignalR, SQLite (SQL Server by configuration)
- Docker, GitHub Actions CI, xUnit tests for the SLA clock logic

### [NileStock](https://github.com/Bissa9/NileStock): warehouse and order API (ASP.NET Core 8)
An order pipeline that reserves stock inside a database transaction (Repeatable Read with row locks) so two customers can't buy the same units, then handles payment, packing, shipping and delivery. Cancelling releases or returns the stock.

- Layered architecture (Domain, Application, Infrastructure, API), repository and unit-of-work patterns
- JWT auth with four roles, FluentValidation, Serilog, Swagger, EF Core with MySQL

### [Rently](https://github.com/Bissa9/Rently): peer-to-peer car rental marketplace
Renters book cars and owners earn from them.

- Stripe payments, webhooks and refunds; JWT auth with email verification and password reset
- Car listings with image uploads, availability checks, reviews, loyalty points, owner earnings and withdrawals
- A Rasa support chatbot
- React 19, Redux, Node.js, Express, MongoDB

### [AnimalShelter](https://github.com/Bissa9/AnimalShelter): shelter and adoption API (ASP.NET Core, .NET 10)
A REST API where users browse and adopt animals and admins manage the catalogue. Adoptions are transactional with optimistic concurrency, so two people can't adopt the same animal.

- JWT auth with hashed refresh tokens, role-based access, rate limiting, Redis caching
- Clean architecture, integration tests against real MySQL and Redis containers (Testcontainers), Docker and GitHub Actions CI

### [ClearDay](https://github.com/Bissa9/ClearDay): energy-aware task planner
Pick your energy level and get a realistic next task, instead of a wall of to-dos.

- Next.js 14, TypeScript (strict), Tailwind CSS
- Layered architecture with the recommendation rules kept separate from the UI; accessible and responsive

### [Haunted House](https://github.com/Bissa9/HauntedHouse): interactive Three.js scene
The camera flies in and orbits a haunted house while ghost lights circle it, then the house explodes into fragments with a fire particle effect.

### [Yaka Arrow](https://github.com/Bissa9/YakaArrow): 3D scene you control by whistling
Pitch detection with the Web Audio API drives an arrow flying through a lit hall. React Three Fiber, TypeScript, Vite.

## What I work with

| Area | Tools |
|---|---|
| Back end | C#, ASP.NET Core (MVC and Web API), Entity Framework Core, SignalR, ASP.NET Identity, JWT, Node.js, Express |
| Data | MySQL, SQLite, MongoDB, Prisma |
| Front end | React, Next.js, TypeScript, Redux, Tailwind CSS |
| 3D / creative | Three.js, React Three Fiber, GSAP, Web Audio API |
| Integrations | Stripe, Cloudinary, Firebase, Rasa |
| Tooling | Docker, GitHub Actions, xUnit, Swagger |


## Get in touch

- 💼 [LinkedIn](https://www.linkedin.com/in/ebtisam-khalid4/)
