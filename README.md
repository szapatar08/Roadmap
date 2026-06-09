# 🗺️ Software Roadmap  
> This roadmap covers everything from development fundamentals to advanced software architecture, following a logical learning order: from the simplest to the most complex.

---

## 📌 PHASE 0 — Computational Foundations

> Before writing a single line of code, you need to understand how the machine works.

### 0. Computational Logic
- What is computing and how does a computer work?
  * Hardware vs Software
  * CPU, RAM, storage
  * Binary and data representation (bits, bytes, ASCII, Unicode)
- What is an operating system?
  * Types: Windows, Linux, macOS
  * Kernel and user space
  * Process and memory management
- Basic Linux commands
  * Navigation: `ls`, `cd`, `pwd`, `tree`
  * Files: `touch`, `mkdir`, `rm`, `cp`, `mv`, `cat`, `less`, `nano`, `vim`
  * Permissions: `chmod`, `chown`, `sudo`
  * Processes: `ps`, `top`, `htop`, `kill`
  * Network: `ping`, `curl`, `wget`, `netstat`, `ifconfig`, `ip`
  * Redirection and pipes: `>`, `>>`, `|`, `grep`, `awk`, `sed`
  * Bash environment variables: `export`, `echo $VAR`, `.bashrc`, `.bash_profile`
  * Basic shell scripting
- What is a variable?
  * Assignment and primitive types
  * Memory and reference
- What is a function and what is it for?
  * Code reuse
  * Input, process and output
- What is a conditional and what is it for?
  * `if / else / else if`
  * Comparison and logical operators
  * Switch / match
- What is a loop and what is it for?
  * `for`, `while`, `do-while`
  * Break, continue
  * Nested loops
- Computational thinking
  * Problem decomposition
  * Pattern recognition
  * Abstraction
  * Algorithms as recipes

---

## 📌 PHASE 1 — Programming Logic (Python as the base language)

> Python is ideal as a first language due to its clean syntax. Here you learn to think like a programmer.

### 1. Python Fundamentals
- Variables and data types
  * `int`, `float`, `str`, `bool`, `None`
  * Dynamic vs static typing
- Constants (convention `UPPER_CASE`)
- Arithmetic operations: `+`, `-`, `*`, `/`, `//`, `%`, `**`
- Logical and comparison operations: `and`, `or`, `not`, `==`, `!=`, `>`, `<`, `>=`, `<=`
- Conditionals
  * `if / elif / else`
  * Ternary operator
- Loops
  * `for` with `range()` and over collections
  * `while`
  * `break`, `continue`, `pass`
  * List comprehensions (introduction)
- Collections
  * Lists (`list`): indexing, slicing, methods
  * Tuples (`tuple`): immutability
  * Dictionaries (`dict`): key-value, methods
  * Sets (`set`): uniqueness, set operations
- Functions
  * Definition with `def`
  * Parameters and arguments (positional, keyword, default)
  * `*args` and `**kwargs`
  * Return values (`return`)
  * Scope: local vs global
  * Lambda / anonymous functions
  * Higher-order functions: `map`, `filter`, `reduce`
  * Recursion
- Strings in depth
  * Methods: `split`, `join`, `strip`, `replace`, `format`, f-strings
  * Basic regular expressions (`re`)
- Error handling
  * `try / except / finally`
  * Exception types
  * Raising exceptions with `raise`
  * Creating custom exceptions
- Object-Oriented Programming in Python
  * Classes and objects
  * Constructor `__init__`
  * Instance vs class attributes
  * Instance, class, and static methods
  * Encapsulation (`_`, `__`)
  * Inheritance and `super()`
  * Magic methods (`__str__`, `__repr__`, `__eq__`, etc.)
- Modules and packages
  * `import`, `from ... import`
  * Creating your own modules
  * `pip` and virtual environments (`venv`)
- Files
  * Reading and writing (`open`, `with`)
  * Formats: `.txt`, `.csv`, `.json`

---

## 📌 PHASE 2 — Algorithms and Complexity

> Knowing how to program is not enough; you have to program well and efficiently.

### 2. Algorithms
- What is an algorithm?
  * Characteristics: finite, defined, effective
  * Pseudocode and flowcharts
- Complexity and measurement
  * Big O notation: O(1), O(n), O(n²), O(log n), O(n log n)
  * Time vs space
  * Best, worst, and average case
- Fundamental data structures
  * Arrays and Linked Lists
  * Stacks and Queues
  * Trees: binary, BST, AVL
  * Graphs: representation, traversal (BFS, DFS)
  * Hash tables (HashMap)
  * Heaps and priority queues
- Sorting algorithms
  * Bubble Sort, Selection Sort, Insertion Sort (O(n²))
  * Merge Sort, Quick Sort (O(n log n))
  * Comparison and when to use each
- Search algorithms
  * Linear search O(n)
  * Binary search O(log n)
- Algorithmic paradigms
  * Divide and conquer
  * Dynamic programming (memoization, tabulation)
  * Greedy algorithms
  * Backtracking
- Classic problems
  * Fibonacci, factorial
  * Tower of Hanoi
  * Knapsack problem
  * Graph paths (Dijkstra, BFS/DFS)

---

## 📌 PHASE 3 — Version Control

> Version control is as fundamental as knowing how to write code. Nobody works without Git.

### 3. Git and GitHub/GitLab
- Git
  * What is it and why does it exist?
  * Installation and configuration (`git config`, SSH keys)
  * Basic flow: `init`, `add`, `commit`, `status`, `log`
  * Commits: conventions (Conventional Commits: `feat:`, `fix:`, `chore:`, etc.)
  * Branches
    - Create, switch, delete
    - Strategies: Git Flow, GitHub Flow, Trunk-Based
  * Merge
    - Fast-forward vs 3-way merge
    - Merge commits
  * Rebase
    - Interactive rebase (`git rebase -i`)
    - Difference between merge and rebase
  * Conflict resolution
    - Identifying conflicts
    - Visual tools (VS Code, JetBrains)
    - `git stash`
  * `.gitignore`
    - Patterns and rules
    - Global `.gitignore`
  * Advanced commands
    - `git cherry-pick`
    - `git bisect`
    - `git reflog`
    - `git reset` (soft, mixed, hard)
    - `git revert`
    - `git tag`
- GitHub / GitLab
  * Pull Requests / Merge Requests
    - Best practices for descriptions
    - Code review
    - Approvals and branch protection
  * Issues and project management
    - Labels, milestones, assignees
    - Linking to commits and PRs
  * Fork and Clone
    - Differences and use cases
    - Contributing to open source projects
  * GitHub Actions / GitLab CI (introduction)
    - Basic workflows (`.github/workflows/`)
    - Jobs and steps
    - Triggers: push, PR, schedule
  * GitHub Pages (static deployment)
  * Wikis and Documentation in repositories

---

## 📌 PHASE 4 — Web Fundamentals (HTML, CSS, JavaScript)

> Understanding how the internet works is essential regardless of whether you'll be frontend or backend.

### 4. How the Internet Works
- What is the Internet? Brief history and architecture
- Client-server model
- IoT (Internet of Things): concept and use cases
- DNS: how domains are resolved
- Web browser
  * Rendering engine (Blink, WebKit, Gecko)
  * Page loading process (DNS → TCP → TLS → HTTP → Render)
  * Browser cache
- Web page vs website vs web application
- HTTP/HTTPS protocol
  * Structure of a request and response
  * Methods: `GET`, `POST`, `PUT`, `PATCH`, `DELETE`, `OPTIONS`, `HEAD`
  * Status codes: 1xx, 2xx, 3xx, 4xx, 5xx
  * Important headers: `Content-Type`, `Authorization`, `Cache-Control`, `CORS`
  * HTTP/1.1 vs HTTP/2 vs HTTP/3
  * Cookies and sessions
  * Postman / Insomnia / Thunder Client
    - Collections and environments
    - Endpoint testing
    - API documentation
- SSL / HTTPS certificates
  * TLS and the handshake
  * Certificates: CA, self-signed
  * HSTS (HTTP Strict Transport Security)
  * Let's Encrypt / CertBot
- JSON
  * Syntax and data types
  * `JSON.parse()` and `JSON.stringify()`
  * vs XML and YAML
- Environment variables
  * `.env` files
  * Secrets management (Vault, AWS Secrets Manager, GitHub Secrets)
  * Never commit secrets

### 5. HTML
- Structure of an HTML document (`DOCTYPE`, `<html>`, `<head>`, `<body>`)
- Semantic and non-semantic tags
- `<head>`: `<meta>`, `<title>`, `<link>`, `<script>`
- `<body>`: structure and content
- Headings (`<h1>` to `<h6>`) and hierarchy
- Paragraphs, spans and divs
- Lists: ordered, unordered and definition
- Links: `<a>`, attributes `href`, `target`, `rel`
- Images: `<img>`, attributes `src`, `alt`, lazy loading
- Embeddings: `<iframe>`, `<video>`, `<audio>`
- Forms
  * `<form>`, `<input>`, `<textarea>`, `<select>`, `<button>`
  * Attributes: `name`, `id`, `type`, `required`, `placeholder`
  * Native HTML5 validation
- Semantic HTML
  * `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<aside>`, `<footer>`
  * Importance for SEO and accessibility
- Tables: `<table>`, `<thead>`, `<tbody>`, `<tr>`, `<th>`, `<td>`
- Web accessibility (a11y)
  * ARIA attributes (`aria-label`, `role`, `aria-hidden`)
  * Correct use of headings and landmarks
  * Color contrast and keyboard reading

### 6. CSS
- Ways to include CSS: inline, internal, external
- Selectors
  * Element, class (`.`), ID (`#`), universal (`*`)
  * Combinators: descendant, direct child, sibling
  * Pseudo-classes: `:hover`, `:focus`, `:nth-child`, `:not`
  * Pseudo-elements: `::before`, `::after`, `::placeholder`
  * Specificity and cascade
- Box Model: `margin`, `border`, `padding`, `content`
- Display: `block`, `inline`, `inline-block`, `none`
- Positioning: `static`, `relative`, `absolute`, `fixed`, `sticky`
- Flexbox
  * `display: flex`, `flex-direction`, `justify-content`, `align-items`
  * `flex-wrap`, `gap`, `flex-grow/shrink/basis`
- CSS Grid
  * `grid-template-columns/rows`, `grid-area`, `gap`
  * Difference from Flexbox: when to use each
- Colors
  * Keywords
  * HEX, RGB, RGBA
  * HSL, HSLA
  * OKLCH (modern, wider color gamut)
- Typography
  * `font-family`, `font-size`, `font-weight`, `line-height`
  * Google Fonts and custom fonts
  * CSS variables (`--color-primary: #3b82f6`)
- Responsive Design
  * Media queries (`@media`)
  * Mobile-first vs Desktop-first
  * Relative units: `em`, `rem`, `%`, `vw`, `vh`, `dvh`
- Animations and transitions
  * `transition`, `animation`, `@keyframes`
  * `transform`: translate, rotate, scale, skew
- CSS Frameworks
  * Bootstrap: grid, components, utilities
  * Tailwind CSS: utility-first, configuration, JIT
  * Comparison and when to use each

### 7. JavaScript (Vanilla)
- History and role of JS in the browser
- Variables: `var`, `let`, `const` and their differences
- Data types: primitives and objects
- Operators: arithmetic, comparison, logical, ternary, nullish coalescing (`??`), optional chaining (`?.`)
- Functions
  * Declaration, expression, arrow functions
  * Closures
  * IIFE
  * Callbacks
- Arrays in depth
  * `map`, `filter`, `reduce`, `find`, `findIndex`, `some`, `every`, `flat`, `flatMap`
  * Spread operator, destructuring
- Objects
  * Creation, properties, methods
  * Destructuring
  * Spread operator
  * `Object.keys/values/entries`
  * Prototypes and prototype chain
- DOM (Document Object Model)
  * Selection: `getElementById`, `querySelector`, `querySelectorAll`
  * Manipulation: `innerHTML`, `textContent`, `classList`, `style`, `setAttribute`
  * Creating and removing nodes
- Events
  * `addEventListener`, `removeEventListener`
  * Event bubbling and capturing
  * `event.preventDefault()`, `event.stopPropagation()`
  * Event delegation
- Asynchrony
  * Event loop, call stack, task queue
  * Callbacks and callback hell
  * Promises: `new Promise`, `.then()`, `.catch()`, `.finally()`
  * `Promise.all`, `Promise.allSettled`, `Promise.race`
  * `async / await`
  * Error handling in asynchronous code
- Fetch API and HTTP requests
  * `fetch()`, options, headers
  * Consuming REST APIs
- ES6 modules
  * `import` / `export`, default vs named exports
- Browser console
  * `console.log/warn/error/table/time/group`
- DevTools
  * Elements, Console, Network, Sources, Performance, Lighthouse
- Browser storage
  * `localStorage`, `sessionStorage`, `cookies`, IndexedDB
- NodeJS
  * What is it and what is it for?
  * CommonJS modules (`require`) vs ESModules (`import`)
  * Event-driven and non-blocking I/O
  * `npm`: `install`, `scripts`, `package.json`, `package-lock.json`, `node_modules`
  * `npx`: run binaries without installing globally
  * Express.js
    - Routing
    - Middlewares
    - Request and Response
    - Environment variables
    - Database connections
    - Complete REST API

### 8. TypeScript
- Why TypeScript? JavaScript + type safety
- Static vs dynamic typing
- Basic types: `string`, `number`, `boolean`, `null`, `undefined`, `void`, `any`, `unknown`, `never`
- Typed arrays and tuples
- Interfaces and Types (`type` vs `interface`)
- Union Types (`|`) and Intersection Types (`&`)
- Generics (`<T>`)
- Enums
- Type assertions (`as`)
- Decorators (introduction)
- `tsconfig.json`: important options
- Integration with frameworks (React, Angular, Express)
- Utility Types: `Partial`, `Required`, `Readonly`, `Pick`, `Omit`, `Record`

---

## 📌 PHASE 5 — Databases

> Data is the heart of any application. You need to know how to store it correctly.

### 9. Databases
- What are databases?
  * Data, information and knowledge
  * DBMS (Database Management System)
- Database engine vs Database manager
- SQL (Relational)
  * What is the relational model?
  * DDL: `CREATE`, `ALTER`, `DROP`, `TRUNCATE`
  * DML: `SELECT`, `INSERT`, `UPDATE`, `DELETE`
  * DQL: `SELECT` with `WHERE`, `ORDER BY`, `GROUP BY`, `HAVING`, `LIMIT`
  * JOINs: `INNER`, `LEFT`, `RIGHT`, `FULL OUTER`, `CROSS`, `SELF`
  * Subqueries and CTEs (`WITH`)
  * Aggregate functions: `COUNT`, `SUM`, `AVG`, `MAX`, `MIN`
  * Indexes: types, when to use, performance impact
  * Transactions and ACID (Atomicity, Consistency, Isolation, Durability)
  * Isolation levels: Read Uncommitted, Read Committed, Repeatable Read, Serializable
  * Normalization: 1NF, 2NF, 3NF, BCNF
  * Denormalization: when and why
  * Views
  * Stored procedures and functions
  * Triggers
  * Migrations
  * Engines: MySQL, PostgreSQL, SQL Server, SQLite
- NoSQL (Non-Relational)
  * When to use NoSQL vs SQL?
  * Types:
    - Documents: MongoDB, CouchDB
    - Key-value: Redis, DynamoDB
    - Columnar: Cassandra, HBase
    - Graphs: Neo4j
  * Advantages and limitations (CAP Theorem)
  * MongoDB: collections, documents, CRUD, indexes, aggregation pipeline
  * Redis: cache, pub/sub, TTL, use cases
- Data modeling
  * ERD (Entity-Relationship Diagram)
    - Entities, attributes, relationships
    - Cardinalities: 1:1, 1:N, N:M
  * Relational Diagram
  * Tools: dbdiagram.io, draw.io, Mermaid

---

## 📌 PHASE 6 — Modern Frontend

> Once you have the JS and CSS fundamentals, you can scale to modern frameworks.

### 10. React
- What is it and how does it work internally? (Virtual DOM, reconciliation)
- Create project: `create-react-app` vs Vite
- JSX: syntax and rules
- Functional components
- Props: data passing, types, defaultProps
- State with `useState`
- Lifecycle with `useEffect`
- Conditional rendering and lists (`key`)
- Handling controlled and uncontrolled forms
- Hooks
  * `useState`, `useEffect`, `useContext`, `useRef`, `useMemo`, `useCallback`, `useReducer`
  * Custom Hooks
- State management
  * Context API
  * Redux Toolkit (RTK)
  * Zustand
  * Jotai / Recoil
- React Router v6
  * `<Routes>`, `<Route>`, `<Link>`, `<NavLink>`
  * URL parameters and query strings
  * Protected routes
- API consumption
  * `fetch` and `axios`
  * React Query / TanStack Query
- React Performance
  * `React.memo`, `useMemo`, `useCallback`
  * Code splitting and lazy loading
  * Profiler
- Testing in React
  * React Testing Library
  * Jest
- Next.js (introduction)
  * SSR, SSG, ISR
  * File-based routing
  * API Routes

### 11. Angular
- What is it and when to use it? (enterprise, structured)
- Angular CLI: `ng new`, `ng generate`, `ng serve`
- Modules (`NgModule`) and Standalone Components (Angular 17+)
- Components: template, class, metadata (`@Component`)
- Directives
  * Structural: `*ngIf`, `*ngFor`, `*ngSwitch`
  * Attribute: `[ngClass]`, `[ngStyle]`
  * Pipes: `date`, `currency`, `async`
- Data binding: interpolation, property, event, two-way (`[(ngModel)]`)
- Services and dependency injection
- HttpClient for API consumption
- RxJS and Observables
  * `Observable`, `Subject`, `BehaviorSubject`
  * Operators: `map`, `filter`, `switchMap`, `mergeMap`, `catchError`, `debounceTime`
- Routing: `RouterModule`, guards, lazy loading of modules
- Forms: Reactive vs Template-driven
- Angular Material (UI library)
- Signals (Angular 17+): modern reactive state

---

## 📌 PHASE 7 — Backend Path with C# and .NET

> The backend is where business logic lives. C# is one of the most robust languages for this.

### 12. C# Fundamentals
- History and .NET ecosystem (Core, Framework, .NET 5+)
- Project types: Console, Web API, MVC, Class Library
- Data types
  * Primitives: `int`, `long`, `double`, `float`, `decimal`, `bool`, `char`, `string`
  * Value types vs reference types
  * `var`, `dynamic`, `object`
  * Nullable types: `int?`, `string?`
- Arrays, Lists and collections
  * `Array`, `List<T>`, `Dictionary<K,V>`, `HashSet<T>`, `Queue<T>`, `Stack<T>`
  * `IEnumerable<T>`, `ICollection<T>`, `IList<T>`
- Loops: `for`, `foreach`, `while`, `do-while`
- Conditionals: `if/else`, `switch`, pattern matching
- Operators: arithmetic, logical, bitwise, ternary, null-coalescing (`??`), null-conditional (`?.`)
- Functions and methods
  * Parameters: `ref`, `out`, `params`, optional, named
  * Method overloading
  * Extension methods
- Namespaces and using directives
- Exception handling: `try/catch/finally`, exception types, custom exceptions
- Tuples and ValueTuple
- Records (C# 9+): immutability and value equality
- Advanced pattern matching
- Lambda expressions and functional LINQ

### 13. OOP in C# (Object-Oriented Programming)
- What is it and what is it for?
- Classes and Objects
  * Constructor: overloading, `this`
  * Destructor and `IDisposable` / `using`
- Properties
  * Auto-properties
  * Custom getters and setters
  * `init` (C# 9+)
- Encapsulation
  * Access modifiers: `public`, `private`, `protected`, `internal`, `protected internal`
- Inheritance
  * `virtual`, `override`, `sealed`
  * Base constructor with `base`
  * `Object` class and methods like `ToString()`, `Equals()`, `GetHashCode()`
- Polymorphism
  * Compile-time (overloading) vs runtime (overriding)
- Abstraction
  * Abstract classes (`abstract`)
  * Interfaces: multiple implementation, default interface methods (C# 8+)
- Generics (`<T>`)
  * Constraints (`where T : class`, `where T : new()`)
- Enums and structs
- Delegates, Events and lambdas
- Nullable Reference Types (C# 8+)
- Immutability and Records

### 14. Web Security
- OWASP Top 10 (2021 update)
  * A01 - Broken Access Control
  * A02 - Cryptographic Failures (formerly: Sensitive Data Exposure)
  * A03 - Injection (SQL, NoSQL, Command Injection)
  * A04 - Insecure Design
  * A05 - Security Misconfiguration
  * A06 - Vulnerable and Outdated Components
  * A07 - Identification and Authentication Failures (formerly: Broken Authentication)
  * A08 - Software and Data Integrity Failures
  * A09 - Security Logging and Monitoring Failures
  * A10 - Server-Side Request Forgery (SSRF)
  * Detail: XSS (Stored, Reflected, DOM-based)
  * Detail: CSRF
- JWT (JSON Web Tokens)
  * Structure: Header, Payload, Signature
  * Signing and verification (HS256, RS256)
  * Access tokens and Refresh tokens
  * Secure storage (httpOnly cookies vs localStorage)
  * Expiration and revocation
- Authentication vs Authorization
  * Claims-based identity
  * Role-based (RBAC) vs Policy-based (ABAC)
- Password hashing
  * BCrypt, Argon2, PBKDF2
  * Salt and pepper
  * Why NOT to use MD5/SHA1 for passwords
- CORS (Cross-Origin Resource Sharing)
  * Same-origin policy
  * Headers and configuration
- HTTP header protection
  * `Content-Security-Policy`
  * `X-Frame-Options`
  * `X-Content-Type-Options`
- Rate Limiting and brute force attack protection
- Input validation and sanitization

### 15. ASP.NET Core
- ASP.NET Core architecture
  * Middleware pipeline
  * `Program.cs` and host configuration
  * Built-in dependency injection (DI)
- MVC Pattern in ASP.NET Core
  * Controllers and Actions
  * Razor Views
  * `ViewData`, `ViewBag`, `TempData`
  * `IActionResult` and response types
  * Routing: conventional and attribute-based
- Web API (REST API)
  * API Controllers
  * `[ApiController]`, `[Route]`, `[HttpGet/Post/Put/Patch/Delete]`
  * Model Binding and validation with Data Annotations
  * Typed responses with `ActionResult<T>`
  * API versioning
  * Swagger / OpenAPI with Swashbuckle
- Entity Framework Core (EF Core)
  * ORM: what it is and how it works
  * DbContext and DbSet
  * Code First vs Database First
  * Migrations: `Add-Migration`, `Update-Database`, `Remove-Migration`
  * Relationships: 1:1, 1:N, N:M in EF Core
  * LINQ with EF Core: queries, projections, includes
  * Lazy Loading vs Eager Loading vs Explicit Loading
  * Configuration with Fluent API vs Data Annotations
  * Transactions with EF Core
- LINQ
  * Query syntax vs method syntax
  * Operators: `Where`, `Select`, `OrderBy`, `GroupBy`, `Join`, `FirstOrDefault`, `Any`, `All`, `Count`, `Sum`, `Take`, `Skip`
  * LINQ to Objects, LINQ to EF
- DTO (Data Transfer Object)
  * Why not expose entities directly?
  * Manual mapping vs AutoMapper
  * DTO validations with FluentValidation
- ViewModel
- NuGet Packages
  * Package management
  * NuGet.org
- Async/Await in ASP.NET Core
  * `Task`, `Task<T>`, `ValueTask`
  * Best practices: avoid deadlocks, `ConfigureAwait`
- Middleware
  * Creating custom middleware
  * Execution order
  * Exception handling middleware
- Configuration
  * `appsettings.json`, `appsettings.Development.json`
  * `IConfiguration`, `IOptions<T>`
  * Environment variables in .NET
- Consuming external APIs
  * `HttpClient` and `IHttpClientFactory`
  * Polly: retries, circuit breaker
- Rate Limiting (ASP.NET Core 7+)
- Validate AntiForgery Token (`[ValidateAntiForgeryToken]`)
- Razor Pages

### 16. Testing in .NET
- Why do testing? TDD (Test-Driven Development)
- Testing pyramid: unit, integration, E2E
- xUnit vs NUnit vs MSTest
- Unit tests
  * AAA pattern: Arrange, Act, Assert
  * Assertions in xUnit
  * Parameterized tests (`[Theory]`, `[InlineData]`)
- Mocking with Moq
  * `Mock<T>`, `Setup`, `Returns`, `Verify`
  * AutoMocker
- Integration tests in ASP.NET Core
  * `WebApplicationFactory<T>`
  * Test `HttpClient`
  * In-memory database (InMemory, SQLite)
- Code coverage
  * Coverlet and HTML reports
  * Coverage metrics
- Property-Based Testing
  * FsCheck (for C#)
  * What are properties and how to define them
- FluentAssertions: more readable assertions

### 17. Additional .NET Resources
- ASP.NET Core Identity
  * UserManager, RoleManager, SignInManager
  * Custom claims and roles
  * Integration with JWT
- Webhooks
  * What are they? Push vs Pull
  * Implementing endpoints to receive webhooks
  * Security: HMAC signature
- Minimal APIs (ASP.NET Core 6+)
- SignalR (WebSockets in .NET)
  * Hubs, clients, real-time
- Blazor (introduction)
  * Server-side vs WebAssembly
- gRPC in .NET (REST alternative)
- Hosted Services and Background Workers

---

## 📌 PHASE 8 — Alternative Backend Path: Laravel (PHP)

> Laravel is one of the most complete frameworks in the PHP ecosystem. Ideal for modern web projects.

### 18. PHP Fundamentals
- History and PHP ecosystem
- Basic syntax, types and operators
- Functions and arrays in PHP
- OOP in PHP: classes, inheritance, traits, interfaces

### 19. Laravel
- Installation: Composer, Laravel Installer
- Project structure
- Routing: web.php, api.php, Route facades
- Controllers: CRUD, Resource Controllers
- Blade Templating Engine
  * Layouts, includes, components, directives
- Eloquent ORM
  * Models, migrations, seeders, factories
  * Relationships: hasOne, hasMany, belongsTo, belongsToMany, morphic
  * Query Builder
  * Local and global scopes
- Middleware
- Form validation (Form Request Validation)
- Authentication
  * Laravel Breeze / Jetstream
  * Sanctum (SPA auth) and Passport (OAuth2)
- Authorization: Gates and Policies
- Queues and Jobs
- Events and Listeners
- Notifications: email, SMS, Slack
- File storage (Storage Facade, S3)
- Cache: Redis, Memcached
- Artisan CLI
- Testing in Laravel
  * Integrated PHPUnit
  * Feature tests and Unit tests
  * HTTP testing, database testing
- API Resources: response transformation
- Livewire (server-side reactive components)

---

## 📌 PHASE 9 — Cross-Cutting Topics

> These topics apply regardless of the language or framework you use.

### 20. QA (Quality Assurance)
- What is QA and what is its role in the team?
- Functional Testing
  * Unit: testing a single unit of code
  * Integration: testing the interaction between modules
  * System: testing the complete system
  * Acceptance (UAT): validating with the client
  * Regression: verifying nothing broke
  * Smoke testing and Sanity testing
- Non-Functional Testing
  * Performance: response time, throughput
  * Load: behavior under N simultaneous users
  * Stress: system limits
  * Usability and UX
  * Security
  * Volume: large amounts of data
- Test automation
  * Selenium / Playwright / Cypress (E2E)
  * k6 / JMeter (load and performance)
- Bug lifecycle: report, triage, fix, verify, close
- BDD (Behavior-Driven Development): Gherkin, SpecFlow, Cucumber

### 21. Software Quality
- What is software quality?
- Pillars: functionality, reliability, usability, efficiency, maintainability, portability
- ISO/IEC 25010 (update to ISO 9126)
  * Characteristics and sub-characteristics
- CMMI (Capability Maturity Model Integration)
- Technical debt: what it is and how to manage it
- Code smells and refactoring
  * SOLID principles
    - S: Single Responsibility
    - O: Open/Closed
    - L: Liskov Substitution
    - I: Interface Segregation
    - D: Dependency Inversion
  * DRY, KISS, YAGNI
- Clean Code (Robert C. Martin)
- Code Review
- Linters and formatters: ESLint, Prettier, dotnet-format, StyleCop

### 22. DevOps
- What is DevOps? Culture and practices
- Docker
  * What is containerization and why does it matter?
  * Images: Dockerfile, layers, multi-stage builds
  * Containers: lifecycle, essential commands
  * Docker Compose: services, networks, volumes
  * Docker Hub and private registries
  * Best practices: small images, non-root users, health checks
- Networking
  * OSI model (7 layers) simplified
  * TCP/IP, UDP
  * IPv4 and IPv6: addressing, CIDR, subnets
  * Common ports and protocols
  * SSH: connection, keys, tunneling, `scp`
  * Proxy and Reverse Proxy (NGINX, Traefik)
  * Firewall: `iptables`, `ufw`, security groups
  * DNS: resolution, A, CNAME, MX, TXT records
  * Load balancing: round-robin, least connections
- NGINX
  * Web server and reverse proxy
  * Virtual hosts (server blocks)
  * SSL/TLS with Let's Encrypt
  * Cache, gzip compression
  * Rate limiting
- CI/CD
  * What is Continuous Integration and Continuous Delivery/Deployment?
  * Difference between CI, CD (Delivery) and CD (Deployment)
  * Typical pipeline: build → test → lint → scan → deploy
  * Environments: development, staging, production
  * **Jenkins**
    - What is Jenkins and why is it still relevant?
      · History: the oldest and most widely used CI/CD server in the industry
      · Open source, self-hosted, highly configurable
      · Comparison with GitHub Actions, GitLab CI and CircleCI
    - Installation and configuration
      · Installation on Linux server (`.war`, `apt`, Docker)
      · Initial setup: admin user, recommended plugins
      · Jenkins in Docker: official image `jenkins/jenkins:lts`
      · Web access and basic security (`http://localhost:8080`)
    - Jenkins architecture
      · Master / Controller: orchestrates the pipelines
      · Agents / Nodes: execute the tasks (SSH, JNLP, Docker)
      · Executors: worker threads per node
      · Workspace: working directory per job
    - Project types (Jobs)
      · Freestyle Project: configuration via GUI
      · Pipeline Job: defined in code (Jenkinsfile)
      · Multibranch Pipeline: automatically detects branches
      · Organization Folder: scans GitHub/GitLab/Bitbucket repos
    - Jenkinsfile and Pipeline as Code
      · What is a Jenkinsfile? Declarative vs Scripted
      · Declarative syntax (recommended):
        ```groovy
        pipeline {
          agent any
          stages {
            stage('Build') { steps { sh 'mvn package' } }
            stage('Test')  { steps { sh 'mvn test' } }
            stage('Deploy'){ steps { sh './deploy.sh' } }
          }
        }
        ```
      · Blocks: `pipeline`, `agent`, `stages`, `stage`, `steps`, `post`
      · Directives: `environment`, `options`, `parameters`, `triggers`, `when`
      · `post`: `always`, `success`, `failure`, `unstable`, `changed`
    - Agents and distributed execution
      · `agent any`, `agent none`, `agent { label 'linux' }`
      · Docker agent: `agent { docker { image 'node:18' } }`
      · Remote nodes: connect servers via SSH or JNLP
      · Scale with multiple agents for parallel builds
    - Essential plugins
      · Git Plugin: integration with Git repositories
      · Pipeline Plugin: Jenkinsfile support
      · Blue Ocean: modern UI for pipelines
      · Credentials Plugin: secure secrets management
      · Docker Pipeline: integrate Docker in pipelines
      · Slack Notification: team alerts
      · JUnit Plugin: publish test results
      · Coverage (JaCoCo, Cobertura): coverage reports
      · SonarQube Scanner: code quality analysis
      · Kubernetes Plugin: dynamic agents in K8s
    - Credentials and secrets management
      · Jenkins Credentials Store: user/password, SSH keys, tokens
      · Using credentials in Jenkinsfile: `withCredentials`, `environment`
      · Never hardcode secrets in the Jenkinsfile
    - Triggers and automation
      · Poll SCM: check for changes every N minutes
      · Webhooks: GitHub/GitLab notifies Jenkins on each push/PR
      · Cron: `triggers { cron('H 2 * * 1-5') }`
      · Build after another job: `upstream`
    - Advanced pipelines
      · Parallel stages: `parallel { stage('A'){...} stage('B'){...} }`
      · Shared Libraries: reuse Groovy code between pipelines
        · Structure: `vars/`, `src/`, `resources/`
        · `@Library('my-shared-lib') _`
      · Input step: manual approval before deploying to production
      · Stash / Unstash: pass artifacts between stages
      · Timeout and retry: `timeout(time: 10, unit: 'MINUTES')`
    - Integration with external tools
      · SonarQube: static code analysis
      · Nexus / Artifactory: artifact management
      · Kubernetes: deploy with `kubectl` or Helm from Jenkins
      · AWS: deploy with AWS CLI or SDK from Jenkins
      · Docker Registry: build and push images
    - Security in Jenkins
      · Matrix Authorization Strategy: permissions by user/role
      · Role Strategy Plugin: granular roles
      · Protect the Jenkinsfile: avoid script injection
      · Configure HTTPS with reverse proxy (NGINX)
      · Auditing: access and change logs
    - Best practices
      · Version the Jenkinsfile alongside the source code
      · Use Declarative Pipeline over Scripted
      · Keep stages small with single responsibility
      · Fail fast: tests first, deploy last
      · Clean workspaces: `deleteDir()` or `cleanWs()`
      · Use Docker agents for reproducible environments
      · Configure notifications (Slack, email) in `post`
    - Jenkins vs modern alternatives
      · GitHub Actions: integrated in GitHub, no own server
      · GitLab CI/CD: integrated in GitLab, very complete
      · CircleCI / Travis CI: SaaS, less configuration
      · Jenkins: maximum control, on-premise, legacy enterprises
  * GitHub Actions: workflows, jobs, secrets, environments, artifacts
  * GitLab CI/CD: `.gitlab-ci.yml`, stages, runners
- Kubernetes (K8s)
  * Concepts: Pod, Deployment, Service, Ingress, ConfigMap, Secret
  * kubectl: basic commands
  * Helm charts
  * Difference from Docker Compose
- Infrastructure as Code (IaC)
  * Terraform: providers, resources, state
  * Pulumi (alternative)
- Observability and Monitoring
  * Structured logs (JSON)
  * Serilog (.NET): sinks, enrichers, templates
  * OpenTelemetry: traces, metrics, logs
  * Prometheus and Grafana
  * Alerts and dashboards
  * ELK Stack (Elasticsearch, Logstash, Kibana)
- CertBot and automatic certificate renewal

### 23. Software Architecture and Design Patterns
- What is software architecture?
- What are design patterns?
- Difference between architecture and patterns
- Fundamental principles: SOLID, DRY, KISS, YAGNI, SoC (Separation of Concerns)
- Architectures
  * Monolithic vs Microservices vs Modular Monolith
  * MVC (Model-View-Controller): variants MVP, MVVM
  * Layered Architecture (N-Layer)
    - Presentation, Application, Domain, Infrastructure
  * Clean Architecture (Robert C. Martin)
    - Concentric layers, dependency rule
  * Hexagonal Architecture (Ports and Adapters)
  * DDD (Domain-Driven Design)
    - Bounded Contexts
    - Entities, Value Objects, Aggregates
    - Domain Events
    - Repositories, Services, Factories
  * Event-Driven Architecture
  * CQRS (Command Query Responsibility Segregation)
    - Commands vs Queries
    - MediatR in .NET
  * Event Sourcing
  * Serverless
- Design patterns (GoF)
  * Creational: Singleton, Factory Method, Abstract Factory, Builder, Prototype
  * Structural: Adapter, Decorator, Facade, Proxy, Composite, Bridge, Flyweight
  * Behavioral: Strategy, Observer, Command, Iterator, Template Method, Chain of Responsibility, State, Mediator, Visitor
- Additional patterns
  * Repository Pattern
  * Unit of Work
  * Service Layer
  * Specification Pattern
  * Outbox Pattern
- Anti-patterns
  * God Object, Spaghetti Code, Golden Hammer, Lava Flow
  * Big Ball of Mud
- Microservices
  * Communication: REST, gRPC, messaging (RabbitMQ, Kafka)
  * Service Discovery
  * API Gateway
  * Sagas and eventual consistency

### 24. Agile Methodologies
- What is Agile? Agile Manifesto and its 12 principles
- SCRUM
  * Roles: Product Owner, Scrum Master, Dev Team
  * Artifacts: Product Backlog, Sprint Backlog, Increment
  * Ceremonies: Sprint Planning, Daily, Sprint Review, Retrospective
  * Definition of Done (DoD) and Definition of Ready (DoR)
  * Story Points and estimation
- Kanban
  * Kanban board: columns and WIP limits
  * Continuous flow vs iterations
  * Metrics: Lead Time, Cycle Time, Throughput
- Lean
  * Lean manufacturing principles applied to software
  * Eliminating waste (muda)
- SAFe (Scaled Agile Framework): introduction
- Tools: Jira, Trello, Linear, GitHub Projects
- User Stories, Epics and Tasks
- Planning Poker

### 25. Documentation
- Importance of documenting
- Docusaurus
  * Installation and configuration
  * Markdown and MDX
  * Documentation versioning
  * Deployment on GitHub Pages
- OpenAPI / Swagger: documenting REST APIs
  * Swagger UI and Redoc
- README.md: how to write a good README
  * Badges, installation, usage, contribution
- JSDoc / XML Doc Comments (C#)
- Architecture Decision Records (ADR)
- Diagrams with code: Mermaid, PlantUML, C4 Model
- Wiki on GitHub/GitLab

### 26. Requirements Engineering
- What is it and why does it matter?
- Stages
  * Elicitation: interviews, workshops, observation, prototypes
  * Analysis: modeling, prioritization (MoSCoW)
  * Specification: use cases, user stories, acceptance criteria
  * Validation: reviews, validated prototypes, UAT
  * Management: traceability, change control
- Types of Requirements
  * Functional: what the system must do
  * Non-functional: performance, security, scalability, availability
  * Constraint: technology, budget, time
- Tools: Jira, Confluence, Notion, Azure DevOps
- User Stories: format, acceptance criteria (BDD with Gherkin)
- Modeling: UML use cases, sequence diagrams, activity diagrams

---

## 📌 PHASE 10 — Cloud and Deployment

### 27. AWS (Amazon Web Services)
- What is Cloud Computing? Models: IaaS, PaaS, SaaS
- IAM (Identity and Access Management)
  * Users, groups, roles, policies
  * Least Privilege Principle
  * MFA and best practices
- VPC (Virtual Private Cloud)
  * Public and private subnets
  * Security Groups and NACLs
  * Internet Gateway and NAT Gateway
- EC2 (Elastic Compute Cloud)
  * Instance types and pricing
  * AMIs
  * User Data and initial configuration
  * Application deployment
- S3 (Simple Storage Service)
  * Buckets, objects, permissions
  * Static hosting
  * Lifecycle policies and versioning
- RDS (Relational Database Service)
  * Managed instances (MySQL, PostgreSQL, SQL Server)
  * Multi-AZ and Read Replicas
  * Automatic backups
- Other relevant services
  * Lambda (serverless)
  * CloudFront (CDN)
  * ElastiCache (managed Redis)
  * SQS/SNS (messaging)
  * ECS/EKS (containers)
  * CloudWatch (monitoring and logs)
- Relationship with Docker and CI/CD
  * ECR (Elastic Container Registry)
  * CodePipeline / GitHub Actions → deploy to AWS

---

## 📌 PHASE 11 — Advanced Topics and Specializations

### 28. Programming Paradigms
- Imperative: step-by-step instructions
- Declarative: what, not how (SQL, HTML, configuration)
- Object-Oriented (OOP): encapsulation, inheritance, polymorphism
- Functional
  * Pure functions, immutability
  * Function composition
  * Functors, Monads (introduction)
  * F# (functional in the .NET ecosystem)
- Reactive
  * Programming based on data streams and change propagation
  * RxJS, Reactor (Java), System.Reactive (.NET)
- Event-Driven
- Comparison: when to use each paradigm

### 29. Asynchronous Messaging
- Why messaging? Decoupling and scalability
- RabbitMQ
  * Concepts: Producer, Consumer, Queue, Exchange, Binding
  * Exchange types: Direct, Topic, Fanout, Headers
  * Acknowledgements and durability
  * Dead Letter Queues
  * Integration with .NET (MassTransit)
- Apache Kafka
  * Difference from RabbitMQ: distributed log vs queue
  * Topics, partitions, consumer groups
  * Message retention
  * Use cases: event streaming, ETL
- Azure Service Bus / AWS SQS / SNS
- Patterns: Pub/Sub, Request-Reply, Saga

### 30. Multi-tenancy
- What is Multi-tenancy?
- Isolation models
  * Database per tenant
  * Schema per tenant
  * Rows per tenant (discriminator column)
- Implementation in ASP.NET Core
- Security and data isolation

### 31. Artificial Intelligence for Developers
- Fundamental concepts
  * AI, ML, Deep Learning: differences and relationship
  * Data: datasets, features, labels
  * Learning types: supervised, unsupervised, reinforcement
- Machine Learning
  * Algorithms: regression, classification, clustering
  * Overfitting and underfitting
  * Cross-validation
  * Scikit-learn (Python)
- Deep Learning
  * Neural networks: perceptron, hidden layers, activations
  * Backpropagation
  * CNNs (vision), RNNs/LSTMs (sequences), Transformers
  * TensorFlow / PyTorch (introduction)
- LLMs (Large Language Models)
  * What are they? GPT, Claude, Llama, Gemini
  * Tokenization and context
  * Temperature, top-p, top-k
- RAG (Retrieval-Augmented Generation)
  * Embeddings and vector databases (Pinecone, Qdrant, pgvector)
  * Pipeline: ingest → embed → retrieve → generate
- Fine-tuning
  * When and why to fine-tune
  * LoRA / QLoRA
- Generative AI
  * Text, images (Stable Diffusion, DALL-E), code, audio, video
- n8n
  * Workflow automation with AI
  * OpenAI nodes, webhooks, HTTP Request
- AI integration in applications
  * OpenAI API / Anthropic API / HuggingFace
  * Azure OpenAI Service
  * Semantic Kernel (.NET)
  * LangChain (Python)

### 32. Prompt Engineering
- What is it and why does it matter?
- Components of a good prompt
  * Role: define the model's role
  * Task: the specific task
  * Context: background information
  * Format: expected output format
  * Constraints: limitations and restrictions
  * Examples: examples to guide the response
- Advanced techniques
  * Zero-Shot Prompting
  * Few-Shot Prompting
  * Chain-of-Thought (CoT)
  * Tree of Thought (ToT)
  * ReAct (Reasoning + Acting)
  * Prompt Chaining
  * Self-Consistency
- Prompt evaluation
- System prompts vs user prompts
- Tools: PromptLayer, LangSmith

### 33. AI Tools for Developers
- Claude Code / Kiro / Cursor
  * Workflows with AI agents
  * Specs and structured context
- GitHub Copilot
  * Intelligent autocomplete
  * Copilot Chat, Copilot CLI
- Codeium, Tabnine
- OpenClaw / other code analysis tools
- AI in the development cycle: generation, review, testing, documentation

---

*Roadmap maintained by Santiago Zapata Rendón — last revision: June 2026*

