# Tech Stack

# 1. Backend

## Options Considered

### Java + Spring Boot

**What is it?**

Java is a general-purpose, object-oriented programming language. Spring Boot is a framework built on the Spring ecosystem that makes it easier to build backend applications and REST APIs.

Typical architecture:

```text
React
  ↓
REST API
  ↓
Spring Boot
  ↓
JPA / Hibernate
  ↓
MySQL
```

**Why do we need it?**

Spring Boot is suitable for building large, maintainable backend systems. It provides features and tools for building REST APIs, database applications, authentication, testing, caching, and scalable services.

**Advantages:**

* Strong job market in Egypt, particularly for enterprise and backend development.
* Excellent for enterprise applications.
* Strong ecosystem for databases and APIs.
* Excellent testing ecosystem.
* Good support for Docker and cloud deployment.
* Suitable for scalable systems.
* Java is already familiar to me.

**Disadvantages:**

* Spring has many concepts and can initially feel complicated.
* More verbose than Go or Node.js.
* Requires learning the Spring ecosystem in addition to Java.

---

### C# + ASP.NET Core

**What is it?**

C# is Microsoft's general-purpose programming language. ASP.NET Core is Microsoft's modern framework for building web applications and backend APIs.

Typical architecture:

```text
React
  ↓
REST API
  ↓
ASP.NET Core
  ↓
Entity Framework Core
  ↓
MySQL
```

**Why do we need it?**

ASP.NET Core can be used to build REST APIs, web applications, enterprise systems, and high-performance services.

**Advantages:**

* Excellent performance.
* Strong development tooling.
* Excellent database support through Entity Framework Core.
* Strong dependency injection and testing support.
* Excellent Docker and cloud support.
* Very suitable for enterprise software.
* C# is a powerful and widely used programming language.
* There are .NET backend opportunities in Egypt.

**Disadvantages:**

* Many .NET positions are connected to the Microsoft ecosystem.

---

### Go + Gin

**What is it?**

Go (Golang) is a programming language designed by Google with a focus on simplicity, concurrency, and efficient execution. Gin is a lightweight web framework for Go.

Typical architecture:

```text
React
  ↓
REST API
  ↓
Go + Gin
  ↓
SQL Driver / ORM
  ↓
MySQL
```

**Why do we need it?**

Go is particularly suitable for high-performance backend services. It provides a good environment for learning concurrency, networking, APIs, performance, and distributed systems.

**Advantages:**

* High performance.
* Excellent concurrency support.
* Lightweight.
* Relatively simple language.
* Good for backend services and microservices.
* Excellent Docker support.
* Very suitable for a scalable URL shortener.

**Disadvantages:**

* Smaller Egyptian job market compared with Java.
* Fewer enterprise opportunities locally compared with Java.
* Gin has a smaller ecosystem than frameworks such as Spring.
* I would need to learn Go and the framework for this project.

---

### Node.js + NestJS/Fastify

**What is it?**

Node.js allows JavaScript and TypeScript to run on the backend. NestJS is a structured backend framework built around Node.js and TypeScript.

Typical architecture:

```text
React
  ↓
REST API
  ↓
NestJS
  ↓
ORM
  ↓
MySQL
```

**Why do we need it?**

NestJS can be used to build structured backend applications and APIs. Using TypeScript on both the frontend and backend can also make full-stack development more consistent.

**Advantages:**

* Large JavaScript/TypeScript ecosystem.
* Good for building APIs.
* NestJS provides a structured architecture.
* Good for full-stack development.
* Good Docker support.
* Can use TypeScript across both frontend and backend.
* There are Node.js/NestJS opportunities in Egypt.

**Disadvantages:**

* Not my first choice for demonstrating deep backend concepts in this particular project.
* I would need to learn JavaScript/TypeScript more deeply.
* The large ecosystem provides many choices, which can make architectural decisions more complicated.
* Java currently appears more strategically useful for my career direction.

---

## Comparison

| Criteria             | Java + Spring Boot | C# + ASP.NET Core | Go + Gin | Node.js + NestJS |
| -------------------- | ------------------ | ----------------- | -------- | ---------------- |
| Egypt job market     | ⭐⭐⭐⭐⭐              | ⭐⭐⭐⭐              | ⭐⭐⭐      | ⭐⭐⭐⭐             |
| Backend development  | ⭐⭐⭐⭐⭐              | ⭐⭐⭐⭐⭐             | ⭐⭐⭐⭐⭐    | ⭐⭐⭐⭐             |
| Enterprise software  | ⭐⭐⭐⭐⭐              | ⭐⭐⭐⭐⭐             | ⭐⭐⭐⭐     | ⭐⭐⭐⭐             |
| Performance          | ⭐⭐⭐⭐               | ⭐⭐⭐⭐⭐             | ⭐⭐⭐⭐⭐    | ⭐⭐⭐⭐             |
| Scalability          | ⭐⭐⭐⭐⭐              | ⭐⭐⭐⭐⭐             | ⭐⭐⭐⭐⭐    | ⭐⭐⭐⭐             |
| Database ecosystem   | ⭐⭐⭐⭐⭐              | ⭐⭐⭐⭐⭐             | ⭐⭐⭐⭐     | ⭐⭐⭐⭐             |
| Testing              | ⭐⭐⭐⭐⭐              | ⭐⭐⭐⭐⭐             | ⭐⭐⭐⭐     | ⭐⭐⭐⭐             |
| Docker / Cloud       | ⭐⭐⭐⭐⭐              | ⭐⭐⭐⭐⭐             | ⭐⭐⭐⭐⭐    | ⭐⭐⭐⭐⭐            |
| Learning difficulty  | Medium / High      | Medium            | Medium   | Medium           |
| Existing knowledge   | **Java**           | **C#**              | Some Go  | None             |
| Fit for this project | ⭐⭐⭐⭐⭐              | ⭐⭐⭐⭐⭐             | ⭐⭐⭐⭐⭐    | ⭐⭐⭐⭐             |
| Career value for me  | **Very High**      | Very High         | High     | High             |

### Decision

**Chosen technology:**

C# + ASP.NET Core

**Why:**

I chose C# with ASP.NET Core because I already have experience with C#, while I have not yet worked with ASP.NET Core. This allows me to build on an existing programming language skill while developing professional backend development skills.

ASP.NET Core is suitable for building REST APIs, enterprise applications, and scalable backend services. It also provides strong support for databases, authentication, testing, dependency injection, Docker, and cloud deployment.

Another important factor is the Egyptian job market. During my job search, I found a significant number of relevant C#/.NET and ASP.NET Core opportunities, including junior and backend positions. This makes the technology relevant to my career goals.

This project will also give me substantial practical experience with C# and .NET, since I currently have more limited project experience using C# compared with my general programming experience.


## 2. Database

### Options Considered

#### MySQL

**What is it?**

MySQL is a relational database management system (RDBMS) that stores structured data in tables and uses SQL for querying and managing data.

**Why do we need it?**

The URL shortener needs to store structured information such as users, shortened URLs, original URLs, expiration dates, and analytics data. MySQL can manage these relationships and provide reliable transactions and indexed queries.

**Advantages:**

* I already have experience working with MySQL.
* Strong support for relational data and SQL.
* Good performance for read-heavy applications.
* Supports indexes for fast short URL lookups.
* Supports transactions and constraints.
* Widely used in web and backend applications.
* Works well with ASP.NET Core and Entity Framework Core.
* Easy to run locally and with Docker.

**Disadvantages:**

* Some advanced database features are less extensive than PostgreSQL.
* Scaling a relational database horizontally can require additional architecture.
* Some advanced queries and database features may require more work compared with PostgreSQL.

---

#### PostgreSQL

**What is it?**

PostgreSQL is an open-source relational database management system (RDBMS) that uses SQL and provides advanced features for storing, querying, and managing structured data.

**Why do we need it?**

PostgreSQL can store the core data of the URL shortener, including users, shortened URLs, expiration information, and analytics-related data. It provides strong support for transactions, constraints, indexing, and complex queries.

**Advantages:**

* I already have experience working with PostgreSQL.
* Strong support for relational data and complex queries.
* Powerful indexing and query optimization capabilities.
* Strong support for transactions and data integrity.
* Provides many advanced database features.
* Works well with ASP.NET Core and Entity Framework Core.
* Open-source and widely used in backend development.
* Suitable for applications that may require more advanced database functionality.

**Disadvantages:**

* Some advanced features may be unnecessary for a simple MVP.
* Can require more database knowledge to take full advantage of its capabilities.
* Scaling a relational database horizontally still requires additional architecture.

---

#### MongoDB

**What is it?**

MongoDB is a NoSQL document database that stores data as flexible JSON-like documents instead of rows and tables.

**Why do we need it?**

MongoDB could be used to store URL and analytics information as documents. Its flexible schema can be useful when the structure of stored data changes frequently.

**Advantages:**

* Flexible document-based data model.
* Easy to store data with different structures.
* Supports horizontal scaling.
* Good for applications with large amounts of semi-structured or unstructured data.
* Useful for learning NoSQL database concepts.

**Disadvantages:**

* Relationships between users, URLs, and other entities are less natural than in a relational database.
* The core data of this project is highly structured.
* Would introduce a different database paradigm when a relational database already fits the requirements well.
* Some relational operations can be more complicated compared with SQL databases.
* Using MongoDB would not automatically make the application more scalable.

---

#### DynamoDB

**What is it?**

DynamoDB is a fully managed NoSQL database service provided by AWS. It supports key-value and document data models and is designed for highly scalable applications.

**Why do we need it?**

DynamoDB could be used to store shortened URLs and retrieve them using their short codes. For example, a short code could be used as a key to quickly retrieve the corresponding original URL.

A lookup could be represented as:

```text
shortCode → originalUrl
```

**Advantages:**

* Highly scalable and designed for large workloads.
* Very fast key-based lookups.
* Fully managed by AWS.
* Supports key-value and document data models.
* Can work well with serverless architectures.
* Suitable for applications that require high availability and scalability.

**Disadvantages:**

* Closely integrated with the AWS ecosystem.
* Requires learning AWS-specific concepts.
* More difficult to reproduce locally compared with MySQL or PostgreSQL.
* Less suitable when the application requires many relationships and complex queries.
* Can introduce unnecessary complexity for the MVP.
* Some advanced features and usage patterns can result in additional cloud costs.

---

### Decision

**Chosen technology:**

PostgreSQL

**Why:**

I chose PostgreSQL because I already have experience with it and it provides strong support for the relational structure of this project. The URL shortener contains structured entities such as users, URLs, expiration information, and analytics data, which are well suited to a relational database.

PostgreSQL also provides powerful indexing, transactions, constraints, and query optimization capabilities. These features will allow me to explore database engineering topics such as query optimization, indexing, `EXPLAIN`, transactions, and performance testing as the project becomes more scalable.

MongoDB and DynamoDB were considered because they are popular NoSQL databases and would provide experience with different database models. However, a NoSQL database is not automatically better for scalability. The structured relationships in this project make a relational database a better fit for the primary database.

DynamoDB could be particularly useful for a highly scalable, key-based URL lookup system, but it would introduce AWS-specific infrastructure and additional complexity that is not necessary for the current project.

PostgreSQL will be used as the primary database together with ASP.NET Core and Entity Framework Core.

## 3. Database Access

### Options Considered

#### Entity Framework Core

**What is it?**

Entity Framework Core (EF Core) is an Object-Relational Mapper (ORM) for .NET. It allows C# applications to interact with relational databases using C# objects and LINQ instead of writing SQL for every database operation.

**Why do we need it?**

The URL shortener backend needs to communicate with PostgreSQL to create, retrieve, update, and delete users, URLs, and other application data. EF Core can handle this communication and map C# classes to database tables.

**Advantages:**

* Official Microsoft-supported ORM for .NET.
* Integrates naturally with ASP.NET Core.
* Supports PostgreSQL through database providers.
* Reduces the amount of repetitive SQL code.
* Supports LINQ for querying data.
* Supports migrations for managing database schema changes.
* Supports transactions and relationships.
* Makes it easier to work with database entities using C# objects.
* Good for maintainable and larger applications.

**Disadvantages:**

* Can generate inefficient queries if used incorrectly.
* Adds an abstraction layer between the application and database.
* Developers still need to understand SQL and database concepts.
* Some complex or highly optimized queries may be easier to write directly in SQL.

---

#### Dapper

**What is it?**

Dapper is a lightweight Object-Relational Mapper (micro-ORM) for .NET. It allows developers to write SQL queries directly while automatically mapping query results to C# objects.

**Why do we need it?**

Dapper could be used when we want more control over the SQL queries while still avoiding some of the repetitive code required by raw database APIs.

**Advantages:**

* Very lightweight.
* Fast and efficient.
* Gives developers direct control over SQL queries.
* Simple to learn.
* Works well for performance-sensitive queries.
* Provides less abstraction than a full ORM.

**Disadvantages:**

* Requires writing SQL manually.
* Does not provide the same level of database management features as EF Core.
* Database schema changes and migrations require additional tools or approaches.
* More repetitive code can be required for larger applications.
* Developers need stronger SQL knowledge.

---

#### ADO.NET

**What is it?**

ADO.NET is the low-level data access technology provided by .NET for communicating directly with databases. It provides APIs for executing SQL commands, reading results, and managing database connections and transactions.

**Why do we need it?**

ADO.NET can provide direct control over database communication and can be used when fine-grained control over SQL execution and connections is required.

**Advantages:**

* Provides direct control over database operations.
* Does not add the abstraction of an ORM.
* Can be highly efficient when used correctly.
* Helps developers understand how application-to-database communication works at a lower level.
* Built into the .NET ecosystem.

**Disadvantages:**

* Requires writing more code.
* Requires manually handling many database operations.
* More repetitive than EF Core or Dapper.
* Database mapping must largely be handled manually.
* Less convenient for developing a larger application.
* Requires more effort to maintain.

---

### Decision

**Chosen technology:**

Entity Framework Core

**Why:**

I chose Entity Framework Core because it integrates naturally with ASP.NET Core and provides a maintainable way to interact with PostgreSQL using C#. It supports LINQ, migrations, transactions, relationships, and database modeling, which are useful for this project.

EF Core will allow me to focus on building the application's backend while still learning important database concepts such as indexing, query optimization, transactions, and database performance.

Although EF Core will be the primary database access technology, I will still learn how SQL works and inspect the queries generated by EF Core. If a particular query becomes performance-sensitive, Dapper or raw SQL can be considered where direct control over the query provides a clear benefit.

The final database access stack will be:

```text
C#
  ↓
ASP.NET Core
  ↓
Entity Framework Core
  ↓
PostgreSQL
```

## 4. Frontend

### Options Considered

#### React

**What is it?**

React is a JavaScript library for building user interfaces. It allows applications to be built using reusable components and manages the UI based on application state.

**Why do we need it?**

The URL shortener needs a frontend where users can register and log in, create shortened URLs, view their URLs, and interact with analytics and other features provided by the backend API.

**Advantages:**

* Widely used in frontend development.
* Large ecosystem and community.
* Component-based architecture encourages reusable code.
* Works well with REST APIs.
* Can be used independently from the ASP.NET Core backend.
* Good choice for learning modern frontend development.
* Strong relevance to frontend and full-stack job opportunities.
* Allows the backend and frontend to remain independently deployable.

**Disadvantages:**

* Requires additional libraries for some features.
* Requires learning modern JavaScript concepts and frontend tooling.
* SEO is not a major advantage for a private URL management application.
* The project will need a separate backend API for server-side functionality.

---

#### Next.js

**What is it?**

Next.js is a React-based framework for building web applications. It provides features such as routing, server-side rendering, static generation, and server-side functionality.

**Why do we need it?**

Next.js could be used to build the frontend of the URL shortener while providing additional features such as routing and different rendering strategies.

**Advantages:**

* Built on React.
* Provides built-in routing.
* Supports server-side rendering and static generation.
* Provides a structured framework for larger frontend applications.
* Widely used in modern web development.
* Can support both frontend and some server-side functionality.

**Disadvantages:**

* Adds more concepts and complexity compared with using React alone.
* Some of its server-side features overlap with responsibilities already handled by ASP.NET Core.
* Requires learning Next.js-specific concepts in addition to React.
* Server-side rendering and SEO are not particularly important for most parts of this application.
* Could make the architecture less clear because the project already has a dedicated backend.

---

#### Vue

**What is it?**

Vue is a progressive JavaScript framework for building user interfaces and single-page applications. It uses a component-based architecture.

**Why do we need it?**

Vue could be used to create the user interface for the URL shortener and communicate with the ASP.NET Core REST API.

**Advantages:**

* Relatively easy to learn.
* Component-based architecture.
* Good support for building single-page applications.
* Provides a structured frontend framework.
* Can communicate easily with REST APIs.
* Good developer experience.

**Disadvantages:**

* Smaller ecosystem and job market compared with React.
* Less relevant to the user's current frontend/full-stack job-search goals than React.
* Would introduce another frontend technology without providing a major advantage for this project.
* Some advanced functionality requires additional libraries.

---

#### Angular

**What is it?**

Angular is a TypeScript-based frontend framework developed by Google for building web applications. Unlike React, which is primarily a UI library, Angular provides a more complete and structured framework with built-in features for routing, forms, dependency injection, HTTP communication, and application structure.

**Why do we need it?**

Angular could be used to build the frontend of the URL shortener and communicate with the ASP.NET Core REST API. It can handle the user interface, routing, forms, authentication state, URL management, and analytics dashboard.

**Advantages:**

* Full-featured framework with many built-in features.
* Uses TypeScript, providing static typing and better tooling.
* Strong component-based architecture.
* Built-in routing and HTTP client.
* Built-in support for forms and dependency injection.
* Provides a consistent structure for larger applications.
* Well suited for enterprise and large-scale applications.
* Works well with ASP.NET Core REST APIs.
* Good support from Google and a large developer community.

**Disadvantages:**

* Steeper learning curve compared with React.
* More opinionated and structured, which provides less flexibility.
* Requires learning Angular-specific concepts such as modules, services, dependency injection, and Angular's component architecture.
* Can introduce more complexity than necessary for a relatively small frontend.
* The framework's larger built-in feature set may be unnecessary for the initial MVP.

---

### Decision

**Chosen technology:**

React

**Why:**

I chose React because it provides a strong foundation for building the frontend while keeping the architecture of the project clear. The frontend will communicate with the ASP.NET Core backend through REST APIs, allowing the frontend and backend to remain separate components.

React is also widely used in frontend and full-stack development and will provide useful practical experience for my career goals.

Next.js was considered because it is a popular React-based framework, but many of its server-side features are not necessary for this project because ASP.NET Core will already handle the backend and API responsibilities. Using React directly will also allow me to focus on learning core frontend concepts rather than introducing additional framework-specific complexity.

Vue was also considered, but React is a better fit for my current career goals and provides stronger exposure to a widely used frontend ecosystem.

### Frontend Tools

The frontend will use the following tools:

**React:** UI components and application state.

**JavaScript / TypeScript:** Application programming language.

**Vite:** Frontend development server and build tool.

**React Router:** Client-side routing between application pages.

**HTTP Client:** Communication with the ASP.NET Core REST API.

**CSS:** Styling and responsive layouts.

**ESLint:** Identifying JavaScript/TypeScript code quality and potential errors.

**Prettier:** Consistent code formatting.

### Frontend Responsibilities

The React frontend will be responsible for:

* Providing the user interface.
* User registration and login forms.
* Creating shortened URLs through the API.
* Displaying the user's shortened URLs.
* Displaying URL expiration information.
* Displaying basic analytics.
* Handling loading and error states.
* Client-side form validation.
* Managing authentication state on the client.
* Navigating between application pages.
* Sending HTTP requests to the ASP.NET Core API.
* Displaying API responses to the user.
* Providing a responsive interface.

The frontend will **not** be responsible for:

* Direct database access.
* Business logic that must be trusted by the server.
* Authentication decisions.
* Authorization enforcement.
* URL generation.
* Database operations.
* Rate limiting.
* Caching.
* Analytics persistence.

These responsibilities will remain in the backend.

### Frontend and Backend Separation

The frontend and backend will communicate through REST APIs:

```text
┌──────────────────────┐
│      React           │
│      Frontend        │
└──────────┬───────────┘
           │
           │ HTTP / REST API
           ▼
┌──────────────────────┐
│   ASP.NET Core       │
│      Backend         │
└──────────┬───────────┘
           │
           ▼
┌──────────────────────┐
│   Entity Framework   │
│       Core           │
└──────────┬───────────┘
           │
           ▼
┌──────────────────────┐
│     PostgreSQL       │
└──────────────────────┘
```

This separation allows the frontend and backend to be developed, tested, deployed, and scaled independently.


## 5. Cache

### Options Considered

#### Redis

**What is it?**

Redis is an in-memory data store that can be used as a cache. It stores data in memory, allowing frequently accessed data to be retrieved much faster than querying the primary database every time.

**Why do we need it?**

The URL shortener will frequently receive requests to redirect users from a short URL to its original URL. Instead of querying PostgreSQL for every redirect, frequently accessed short URLs can be stored in Redis.

For example:

```text
shortCode → originalUrl
```

When a user requests a popular short URL:

```text
Request
   ↓
Redis lookup
   ↓
Found? ── Yes ──→ Original URL → Redirect
   │
   No
   ↓
PostgreSQL
   ↓
Store result in Redis
   ↓
Redirect
```

**Advantages:**

* Very fast because data is stored in memory.
* Well suited for frequently accessed data.
* Supports expiration times (TTL).
* Can reduce the number of queries sent to PostgreSQL.
* Supports distributed caching across multiple backend instances.
* Works well with ASP.NET Core.
* Can be used for more than caching, such as rate limiting and temporary data.
* Open-source and widely used in scalable backend architectures.

**Disadvantages:**

* Data is primarily stored in memory, which is more expensive than database storage.
* Cached data can be lost depending on the Redis configuration.
* Adds another component to the system.
* Requires cache invalidation and expiration strategies.
* The application must handle cache misses correctly.

---

#### In-Memory Cache

**What is it?**

In-memory caching stores cached data directly in the memory of the application server.

In ASP.NET Core, this can be implemented using the built-in memory caching functionality.

**Why do we need it?**

It can be used to store frequently accessed URLs locally inside a backend instance, avoiding repeated database queries.

**Advantages:**

* Very fast.
* Simple to implement.
* No separate caching server is required.
* Useful for small applications and development.
* Built into the ASP.NET Core ecosystem.

**Disadvantages:**

* Each backend instance has its own cache.
* Cached data is not shared between multiple backend instances.
* Cache is lost when the application restarts.
* Becomes less suitable when the application is scaled horizontally.
* Cache invalidation becomes more difficult across multiple instances.

---

### Decision

**Chosen technology:**

Redis

**Why:**

I chose Redis because the URL shortener is expected to have a large number of read operations, particularly URL redirections. The same popular short URLs may be requested many times, making them good candidates for caching.

Redis will allow frequently accessed short URLs to be retrieved from memory instead of querying PostgreSQL for every request. This can reduce database load and improve redirect response time.

Redis also supports distributed caching, which is important for the scalability goals of this project. If multiple ASP.NET Core backend instances are running, they can share the same Redis cache.

The application will use a **cache-aside strategy**:

```text
1. Request short URL
        ↓
2. Check Redis
        ↓
   ┌────┴────┐
   │         │
 Cache Hit  Cache Miss
   │         │
   ↓         ↓
Return    Query PostgreSQL
URL           ↓
          Store in Redis
              ↓
          Return URL
```

If a cached entry expires or is not found, PostgreSQL remains the source of truth.

### Cache Responsibilities

Redis will primarily be responsible for:

* Caching short URL → original URL mappings.
* Reducing repeated PostgreSQL queries.
* Improving redirect performance.
* Reducing database load.
* Supporting shared caching across multiple backend instances.
* Managing cache expiration using TTL.
* Potentially supporting other features later, such as rate limiting.

Redis will **not** be the primary database.

PostgreSQL will remain the **source of truth**, while Redis will contain temporary cached copies of frequently accessed data.

### Cache Architecture

```text
                  ┌─────────────┐
                  │   React     │
                  │  Frontend   │
                  └──────┬──────┘
                         │
                         ▼
                  ┌─────────────┐
                  │ ASP.NET     │
                  │ Core API    │
                  └──────┬──────┘
                         │
                    Check Redis
                         │
              ┌──────────┴──────────┐
              │                     │
          Cache Hit             Cache Miss
              │                     │
              ▼                     ▼
       Original URL           PostgreSQL
                                    │
                                    ▼
                                  Redis
```

This design allows Redis to improve performance without making the system dependent on cached data. If Redis is unavailable or an entry is missing, the backend can retrieve the required data from PostgreSQL.


## 6. Testing

### Options Considered

#### xUnit

**What is it?**

xUnit is a testing framework for .NET applications. It allows developers to create automated tests for individual pieces of application logic and larger application components.

**Why do we need it?**

The URL shortener needs automated tests to verify that its backend behaves correctly as new features are added. Tests can verify URL creation, validation, redirection, authentication, expiration, and other application behavior.

**Advantages:**

* Widely used in the .NET ecosystem.
* Works well with ASP.NET Core.
* Supports unit and integration testing.
* Simple and flexible.
* Works well with dependency injection and mocking libraries.
* Integrates with CI/CD pipelines.
* Helps prevent regressions when the project changes.

**Disadvantages:**

* Requires time to design and maintain tests.
* Developers need to understand what should and should not be tested.
* Unit tests alone cannot verify the complete system.

---

#### NUnit

**What is it?**

NUnit is a testing framework for .NET applications that provides tools for creating and running automated tests.

**Why do we need it?**

NUnit can be used to test the backend logic and application components of the URL shortener.

**Advantages:**

* Mature .NET testing framework.
* Large community.
* Supports unit and integration testing.
* Provides many testing features.

**Disadvantages:**

* Adds another testing framework when xUnit already provides the required functionality.
* The project would not gain a significant advantage from choosing it over xUnit.

---

#### MSTest

**What is it?**

MSTest is Microsoft's testing framework for .NET applications.

**Why do we need it?**

MSTest can be used to create automated tests for the ASP.NET Core backend.

**Advantages:**

* Official Microsoft testing framework.
* Integrates well with .NET and Visual Studio.
* Supports unit and integration testing.
* Simple setup.

**Disadvantages:**

* Less flexibility for some testing scenarios compared with other popular .NET testing frameworks.
* xUnit provides a strong alternative with a large .NET community.

---

### Decision

**Chosen technology:**

xUnit

**Why:**

I chose xUnit because it is a widely used testing framework in the .NET ecosystem and integrates well with ASP.NET Core.

The project will use automated tests to verify individual application components as well as interactions between the API, database, and other services.

Testing will include:

* Unit tests.
* Integration tests.
* API endpoint tests.
* Database-related tests.
* Authentication and authorization tests.
* URL expiration tests.
* Error handling tests.
* Later, performance and load testing.

The goal is not only to test whether individual methods work, but also to verify that the complete system behaves correctly.

---

## 7. API Documentation

### Options Considered

#### OpenAPI + Swagger

**What is it?**

OpenAPI is a standard for describing REST APIs. Swagger tools can use an OpenAPI specification to provide interactive API documentation and allow developers to test API endpoints.

**Why do we need it?**

The React frontend needs to understand how to communicate with the ASP.NET Core backend. API documentation will describe available endpoints, request parameters, request bodies, responses, authentication requirements, and possible errors.

**Advantages:**

* Provides interactive API documentation.
* Makes backend APIs easier to understand and test.
* Integrates well with ASP.NET Core.
* OpenAPI is a widely used API specification.
* Swagger UI allows endpoints to be tested directly from the browser.
* Useful when developing the frontend separately from the backend.

**Disadvantages:**

* Documentation can become outdated if it is not maintained.
* Interactive documentation is mainly intended for developers rather than end users.

---

#### Postman Collections

**What is it?**

Postman is a tool for sending HTTP requests and testing APIs. Collections can be used to organize and document API requests.

**Why do we need it?**

Postman can help test the URL shortener's REST endpoints during development.

**Advantages:**

* Easy to send and inspect HTTP requests.
* Useful for debugging APIs.
* Supports environments and variables.
* Can organize requests into collections.
* Useful for manual API testing.

**Disadvantages:**

* It is primarily a testing and development tool rather than a formal API specification.
* Does not replace OpenAPI documentation.
* Manual testing through Postman does not provide the same level of automated API verification as automated tests.

---

### Decision

**Chosen technology:**

OpenAPI + Swagger UI

**Why:**

I chose OpenAPI with Swagger UI because the URL shortener is built around a REST API and needs clear documentation for communication between the React frontend and ASP.NET Core backend.

The API documentation will describe:

* Available endpoints.
* HTTP methods.
* Request parameters.
* Request and response bodies.
* Authentication requirements.
* Status codes.
* Error responses.
* Example requests and responses.

Postman may still be used during development for manually testing and debugging API endpoints, but OpenAPI will be the primary API documentation approach.

---

## 8. Containerization

### Options Considered

#### Docker

**What is it?**

Docker is a containerization platform that packages applications and their dependencies into isolated containers so they can run consistently across different environments.

**Why do we need it?**

The URL shortener consists of multiple components, including the ASP.NET Core backend, PostgreSQL, Redis, and React frontend. Docker can provide a consistent environment for running these components.

**Advantages:**

* Provides consistent development and deployment environments.
* Makes it easier to run PostgreSQL and Redis locally.
* Isolates application components.
* Makes deployment easier.
* Widely used in modern software engineering.
* Works well with ASP.NET Core.
* Helps prepare the project for cloud deployment.

**Disadvantages:**

* Introduces additional concepts such as images, containers, networks, volumes, and Dockerfiles.
* Requires learning Docker-specific commands and configuration.
* Containerization can add complexity during development.

---

#### Docker Compose

**What is it?**

Docker Compose is a tool for defining and running multiple Docker containers as one application.

**Why do we need it?**

The URL shortener requires multiple services to work together. Docker Compose can define the backend, PostgreSQL, Redis, and other required services in a single configuration.

**Advantages:**

* Makes multi-container development easier.
* Allows the complete local environment to be started with a single command.
* Defines services and their relationships in one configuration.
* Useful for development and testing.
* Works well with PostgreSQL and Redis.

**Disadvantages:**

* Adds another configuration file and concepts to learn.
* Primarily intended for local development and simpler environments rather than large-scale production orchestration.

---

### Decision

**Chosen technology:**

Docker + Docker Compose

**Why:**

I chose Docker and Docker Compose because the project contains multiple services that need to work together.

Docker will be used to containerize the application components, while Docker Compose will be used to run the local multi-service environment.

The development environment will eventually look similar to:

```text
┌─────────────────────┐
│      React          │
│     Container       │
└──────────┬──────────┘
           │
           ▼
┌─────────────────────┐
│   ASP.NET Core      │
│     Container       │
└───────┬───────┬─────┘
        │       │
        ▼       ▼
   PostgreSQL  Redis
   Container   Container
```

Docker will also make it easier to reproduce the project environment when deploying the application.

---

## 9. Deployment

### Options Considered

#### Microsoft Azure

**What is it?**

Microsoft Azure is a cloud computing platform that provides services for hosting applications, databases, containers, monitoring, and other infrastructure.

**Why do we need it?**

The URL shortener needs to eventually be deployed so that the application can be accessed outside the local development environment.

**Advantages:**

* Strong integration with the Microsoft/.NET ecosystem.
* Supports ASP.NET Core applications.
* Provides container hosting options.
* Provides managed database and caching services.
* Provides monitoring and logging services.
* Useful experience for .NET backend development.
* Supports scalable cloud architectures.

**Disadvantages:**

* Requires learning Azure-specific services.
* Cloud infrastructure can become complex.
* Some services can generate costs if not managed carefully.

---

#### AWS

**What is it?**

Amazon Web Services (AWS) is a cloud computing platform that provides services for application hosting, databases, caching, storage, networking, monitoring, and other infrastructure.

**Why do we need it?**

AWS can host the URL shortener and provide infrastructure needed for a scalable production architecture.

**Advantages:**

* Large range of cloud services.
* Strong support for scalable architectures.
* Widely used in industry.
* Provides services for containers, databases, caching, networking, and monitoring.
* Useful experience for cloud-based backend development.

**Disadvantages:**

* Large number of services can make it difficult for beginners.
* Requires learning AWS-specific concepts.
* Infrastructure can become unnecessarily complex for this project.
* Cloud costs need to be monitored carefully.

---

#### Render

**What is it?**

Render is a cloud platform designed to simplify deployment of web applications, APIs, databases, and other services.

**Why do we need it?**

Render could provide a simpler way to deploy the URL shortener without managing as much cloud infrastructure manually.

**Advantages:**

* Relatively simple deployment process.
* Easier to learn than a large cloud platform.
* Suitable for smaller applications and portfolio projects.
* Supports containerized applications.

**Disadvantages:**

* Provides less infrastructure control than major cloud platforms.
* Less useful for demonstrating detailed cloud architecture.
* May not provide the same depth of cloud experience as Azure or AWS.

---

### Decision

**Chosen technology:**

Microsoft Azure

**Why:**

I chose Azure because the backend is built using C# and ASP.NET Core, making Azure a natural cloud platform to learn alongside the Microsoft ecosystem.

The deployment phase will focus on understanding how to deploy a containerized ASP.NET Core application and connect it to the required infrastructure.

The project will also use cloud services where appropriate for components such as the database, cache, monitoring, and application hosting.

The exact Azure services will be selected later based on the final architecture and deployment requirements rather than adding cloud services unnecessarily.

---

## 10. Monitoring & Logging

### Options Considered

#### Serilog

**What is it?**

Serilog is a structured logging library for .NET applications. It allows applications to record information about requests, errors, application events, and other important activities.

**Why do we need it?**

The URL shortener needs logging to help identify errors, investigate problems, monitor application behavior, and understand what happens when requests are processed.

**Advantages:**

* Strong integration with .NET.
* Supports structured logging.
* Allows logs to be written to different destinations.
* Can include useful contextual information.
* Useful for debugging production applications.
* Can integrate with cloud logging systems.

**Disadvantages:**

* Logging must be designed carefully to avoid unnecessary or sensitive information.
* Large amounts of logs can increase storage and monitoring costs.

---

#### OpenTelemetry

**What is it?**

OpenTelemetry is an observability framework for collecting telemetry such as traces, metrics, and logs from applications.

**Why do we need it?**

As the project becomes more distributed, it becomes useful to understand not only whether an error occurred but also how requests move through the different components of the system.

**Advantages:**

* Supports metrics, traces, and logs.
* Useful for distributed systems.
* Helps identify performance bottlenecks.
* Vendor-neutral.
* Useful for understanding requests across multiple services.
* Can integrate with different observability platforms.

**Disadvantages:**

* More complex than basic application logging.
* Requires additional configuration and concepts.
* May be unnecessary for the earliest MVP.

---

### Decision

**Chosen technology:**

Serilog + OpenTelemetry

**Why:**

I chose Serilog for structured application logging and OpenTelemetry for broader observability.

Serilog will be introduced earlier so that the backend has useful structured logs during development.

OpenTelemetry will become more important as the project introduces multiple backend instances, Redis, caching, load balancing, and deployment. It will help measure and understand system behavior across these components.

Monitoring will eventually include:

* Application errors.
* HTTP request information.
* Response times.
* Database performance.
* Cache performance.
* Cache hit and miss rates.
* Application health.
* Resource usage.
* Distributed request traces.

---

## 11. Development Tools

### Options Considered

#### Visual Studio

**What is it?**

Visual Studio is an integrated development environment (IDE) from Microsoft that provides tools for developing .NET applications.

**Why do we need it?**

Visual Studio can be used to develop, debug, test, and manage the ASP.NET Core backend.

**Advantages:**

* Excellent support for C# and ASP.NET Core.
* Powerful debugger.
* Integrated testing tools.
* Strong IntelliSense and code navigation.
* Good support for Entity Framework Core.
* Docker and container development support.

**Disadvantages:**

* Relatively large IDE.
* Uses more system resources than lightweight editors.
* Some advanced features are more than necessary for simple development.

---

#### Visual Studio Code

**What is it?**

Visual Studio Code is a lightweight source-code editor with extensions for many programming languages and frameworks.

**Why do we need it?**

VS Code can be used for frontend development, C# and ASP.NET Core development, Markdown documentation, configuration files, Git, and other development tasks.

**Advantages:**

* Lightweight.
* Excellent support for JavaScript, React, and TypeScript.
* Supports C# and ASP.NET Core development through extensions.
* Large extension ecosystem.
* Good Git integration.
* Works across different operating systems.
* Can be used for both frontend and backend development.

**Disadvantages:**

* Requires extensions for many features.
* Provides less built-in .NET functionality than Visual Studio.
* Debugging and project management may require more configuration.

---

#### Git

**What is it?**

Git is a distributed version control system used to track changes in source code and collaborate on software projects.

**Why do we need it?**

The project needs version control to track development, organize changes, create meaningful commits, and safely experiment with new features.

**Advantages:**

* Industry-standard version control system.
* Tracks the history of the project.
* Allows branches for separate features.
* Makes it possible to revert changes.
* Essential for collaborative software development.

**Disadvantages:**

* Requires learning Git commands and workflows.
* Poor Git practices can create a confusing project history.

---

#### GitHub

**What is it?**

GitHub is a platform for hosting Git repositories and collaborating on software projects.

**Why do we need it?**

GitHub will host the project's source code and documentation and make the completed project available as a portfolio project.

**Advantages:**

* Widely used by software developers.
* Provides remote repository hosting.
* Supports issues and project management.
* Makes the project accessible to recruiters and interviewers.
* Integrates with CI/CD workflows.

**Disadvantages:**

* Requires understanding how Git and GitHub work together.
* Public repositories require care when handling secrets and configuration.

---

#### Postman

**What is it?**

Postman is a tool for sending HTTP requests and testing APIs.

**Why do we need it?**

Postman can be used to manually test the ASP.NET Core REST API during development.

**Advantages:**

* Easy to test HTTP requests.
* Useful for debugging API behavior.
* Supports authentication and environment variables.
* Allows requests to be organized into collections.

**Disadvantages:**

* Manual testing does not replace automated tests.
* API requests can become difficult to manage if the collection becomes very large.

---

### Decision

**Chosen tools:**

* Visual Studio Code
* Git
* GitHub
* Postman

**Why:**

I will use Visual Studio Code as the primary development environment for both C# and ASP.NET Core backend development and React frontend development. It also provides a convenient environment for Markdown documentation, configuration files, Git, and other project-related tasks.

Although Visual Studio provides stronger built-in .NET functionality, VS Code provides the flexibility to work on both the frontend and backend using a single lightweight editor.

Git will be used for version control, while GitHub will host the project repository and documentation.

Postman will be used for manual API testing and debugging during development. Automated tests will remain the primary approach for verifying application behavior.

The development workflow will be:

```text
Write Code

    ↓

Git

    ↓

Test

    ↓

Commit

    ↓

GitHub

    ↓

CI/CD

    ↓

Deployment
```

### Final Development Stack

The overall technology stack selected for the project is:

```text
Frontend

    React + Vite

        ↓

REST API

        ↓

Backend

    C# + ASP.NET Core

        ↓

Database Access

    Entity Framework Core

        ↓

Primary Database

    PostgreSQL

Additional Infrastructure

    Redis

    Docker + Docker Compose

Testing

    xUnit + Integration Testing

API Documentation

    OpenAPI + Swagger UI

Deployment

    Microsoft Azure

Monitoring & Logging

    Serilog + OpenTelemetry

Development Tools

    VS Code

    Git

    GitHub

    Postman
```

This stack provides the foundation for the later project phases, where the system will be implemented, tested, containerized, deployed, and gradually improved for scalability.
