# 🗺️ Software Roadmap — Santiago Zapata Rendón
> Creado el 23 de mayo. Basado en el recorrido desde el día 0 en Riwi hasta hoy.  
> Este roadmap cubre desde los fundamentos del desarrollo hasta arquitectura de software avanzada, siguiendo un orden lógico de aprendizaje: de lo más simple a lo más complejo.

---

## 📌 FASE 0 — Fundamentos Computacionales

> Antes de escribir una sola línea de código, necesitas entender cómo funciona la máquina.

### 0. Lógica Computacional
- ¿Qué es la computación y cómo funciona un computador?
  * Hardware vs Software
  * CPU, RAM, almacenamiento
  * Binario y representación de datos (bits, bytes, ASCII, Unicode)
- ¿Qué es un sistema operativo?
  * Tipos: Windows, Linux, macOS
  * Kernel y espacio de usuario
  * Gestión de procesos y memoria
- Comandos básicos de Linux
  * Navegación: `ls`, `cd`, `pwd`, `tree`
  * Archivos: `touch`, `mkdir`, `rm`, `cp`, `mv`, `cat`, `less`, `nano`, `vim`
  * Permisos: `chmod`, `chown`, `sudo`
  * Procesos: `ps`, `top`, `htop`, `kill`
  * Red: `ping`, `curl`, `wget`, `netstat`, `ifconfig`, `ip`
  * Redirección y pipes: `>`, `>>`, `|`, `grep`, `awk`, `sed`
  * Variables de entorno en bash: `export`, `echo $VAR`, `.bashrc`, `.bash_profile`
  * Shell scripting básico
- ¿Qué es una variable?
  * Asignación y tipos primitivos
  * Memoria y referencia
- ¿Qué es una función y para qué sirve?
  * Reutilización de código
  * Entrada, proceso y salida
- ¿Qué es un condicional y para qué sirve?
  * `if / else / else if`
  * Operadores de comparación y lógicos
  * Switch / match
- ¿Qué es un loop y para qué sirve?
  * `for`, `while`, `do-while`
  * Break, continue
  * Loops anidados
- Pensamiento computacional
  * Descomposición de problemas
  * Reconocimiento de patrones
  * Abstracción
  * Algoritmos como recetas

---

## 📌 FASE 1 — Lógica de Programación (Python como lenguaje base)

> Python es ideal como primer lenguaje por su sintaxis limpia. Aquí aprendes a pensar como programador.

### 1. Fundamentos de Python
- Variables y tipos de datos
  * `int`, `float`, `str`, `bool`, `None`
  * Tipado dinámico vs estático
- Constantes (convención `UPPER_CASE`)
- Operaciones aritméticas: `+`, `-`, `*`, `/`, `//`, `%`, `**`
- Operaciones lógicas y de comparación: `and`, `or`, `not`, `==`, `!=`, `>`, `<`, `>=`, `<=`
- Condicionales
  * `if / elif / else`
  * Operador ternario
- Loops
  * `for` con `range()` y sobre colecciones
  * `while`
  * `break`, `continue`, `pass`
  * List comprehensions (introducción)
- Colecciones
  * Listas (`list`): indexing, slicing, métodos
  * Tuplas (`tuple`): inmutabilidad
  * Diccionarios (`dict`): clave-valor, métodos
  * Conjuntos (`set`): unicidad, operaciones de conjuntos
- Funciones
  * Definición con `def`
  * Parámetros y argumentos (posicionales, keyword, por defecto)
  * `*args` y `**kwargs`
  * Retorno de valores (`return`)
  * Scope: local vs global
  * Funciones lambda / anónimas
  * Funciones de orden superior: `map`, `filter`, `reduce`
  * Recursividad
- Strings a fondo
  * Métodos: `split`, `join`, `strip`, `replace`, `format`, f-strings
  * Expresiones regulares básicas (`re`)
- Manejo de errores
  * `try / except / finally`
  * Tipos de excepciones
  * Lanzar excepciones con `raise`
  * Crear excepciones personalizadas
- Programación Orientada a Objetos en Python
  * Clases y objetos
  * Constructor `__init__`
  * Atributos de instancia vs de clase
  * Métodos de instancia, clase y estáticos
  * Encapsulamiento (`_`, `__`)
  * Herencia y `super()`
  * Métodos mágicos (`__str__`, `__repr__`, `__eq__`, etc.)
- Módulos y paquetes
  * `import`, `from ... import`
  * Crear tus propios módulos
  * `pip` y entornos virtuales (`venv`)
- Archivos
  * Lectura y escritura (`open`, `with`)
  * Formatos: `.txt`, `.csv`, `.json`

---

## 📌 FASE 2 — Algoritmia y Complejidad

> Saber programar no es suficiente; hay que saber programar bien y eficientemente.

### 2. Algoritmia
- ¿Qué es un algoritmo?
  * Características: finito, definido, efectivo
  * Pseudocódigo y diagramas de flujo
- Complejidad y medición
  * Notación Big O: O(1), O(n), O(n²), O(log n), O(n log n)
  * Tiempo vs espacio
  * Mejor, peor y caso promedio
- Estructuras de datos fundamentales
  * Arrays y listas enlazadas (Linked Lists)
  * Pilas (Stack) y Colas (Queue)
  * Árboles: binarios, BST, AVL
  * Grafos: representación, recorrido (BFS, DFS)
  * Tablas hash (HashMap)
  * Heaps y colas de prioridad
- Algoritmos de ordenamiento
  * Bubble Sort, Selection Sort, Insertion Sort (O(n²))
  * Merge Sort, Quick Sort (O(n log n))
  * Comparación y cuándo usar cada uno
- Algoritmos de búsqueda
  * Búsqueda lineal O(n)
  * Búsqueda binaria O(log n)
- Paradigmas algorítmicos
  * Divide y vencerás
  * Programación dinámica (memoización, tabulación)
  * Algoritmos voraces (Greedy)
  * Backtracking
- Problemas clásicos
  * Fibonacci, factorial
  * Torres de Hanói
  * Problema de la mochila (Knapsack)
  * Caminos en grafos (Dijkstra, BFS/DFS)

---

## 📌 FASE 3 — Control de Versiones

> El control de versiones es tan fundamental como saber escribir código. Nadie trabaja sin Git.

### 3. Git y GitHub/GitLab
- Git
  * ¿Qué es y por qué existe?
  * Instalación y configuración (`git config`, SSH keys)
  * Flujo básico: `init`, `add`, `commit`, `status`, `log`
  * Commits: convenciones (Conventional Commits: `feat:`, `fix:`, `chore:`, etc.)
  * Branches
    - Crear, cambiar, eliminar
    - Estrategias: Git Flow, GitHub Flow, Trunk-Based
  * Merge
    - Fast-forward vs 3-way merge
    - Merge commits
  * Rebase
    - Rebase interactivo (`git rebase -i`)
    - Diferencia entre merge y rebase
  * Resolución de conflictos
    - Identificar conflictos
    - Herramientas visuales (VS Code, JetBrains)
    - `git stash`
  * `.gitignore`
    - Patrones y reglas
    - `.gitignore` global
  * Comandos avanzados
    - `git cherry-pick`
    - `git bisect`
    - `git reflog`
    - `git reset` (soft, mixed, hard)
    - `git revert`
    - `git tag`
- GitHub / GitLab
  * Pull Requests / Merge Requests
    - Buenas prácticas de descripción
    - Code review
    - Aprobaciones y protección de ramas
  * Issues y gestión de proyecto
    - Labels, milestones, assignees
    - Vinculación con commits y PRs
  * Fork y Clone
    - Diferencias y casos de uso
    - Contribuir a proyectos open source
  * GitHub Actions / GitLab CI (introducción)
    - Workflows básicos (`.github/workflows/`)
    - Jobs y steps
    - Triggers: push, PR, schedule
  * GitHub Pages (despliegue estático)
  * Wikis y Documentación en repositorios

---

## 📌 FASE 4 — Fundamentos Web (HTML, CSS, JavaScript)

> Entender cómo funciona el internet es indispensable sin importar si serás frontend o backend.

### 4. Cómo Funciona el Internet
- ¿Qué es Internet? Breve historia y arquitectura
- Modelo cliente-servidor
- IoT (Internet de las Cosas): concepto y casos de uso
- DNS: cómo se resuelven los dominios
- Navegador web
  * Motor de renderizado (Blink, WebKit, Gecko)
  * Proceso de carga de una página (DNS → TCP → TLS → HTTP → Render)
  * Caché del navegador
- Página web vs sitio web vs aplicación web
- Protocolo HTTP/HTTPS
  * Estructura de una petición y respuesta
  * Métodos: `GET`, `POST`, `PUT`, `PATCH`, `DELETE`, `OPTIONS`, `HEAD`
  * Códigos de estado: 1xx, 2xx, 3xx, 4xx, 5xx
  * Headers importantes: `Content-Type`, `Authorization`, `Cache-Control`, `CORS`
  * HTTP/1.1 vs HTTP/2 vs HTTP/3
  * Cookies y sessions
  * Postman / Insomnia / Thunder Client
    - Colecciones y entornos
    - Testing de endpoints
    - Documentación de APIs
- Certificados SSL / HTTPS
  * TLS y el handshake
  * Certificados: CA, autofirmados
  * HSTS (HTTP Strict Transport Security)
  * Let's Encrypt / CertBot
- JSON
  * Sintaxis y tipos de datos
  * `JSON.parse()` y `JSON.stringify()`
  * vs XML y YAML
- Variables de entorno
  * Archivos `.env`
  * Secrets management (Vault, AWS Secrets Manager, GitHub Secrets)
  * Nunca committear secretos

### 5. HTML
- Estructura de un documento HTML (`DOCTYPE`, `<html>`, `<head>`, `<body>`)
- Etiquetas semánticas y no semánticas
- `<head>`: `<meta>`, `<title>`, `<link>`, `<script>`
- `<body>`: estructura y contenido
- Headings (`<h1>` al `<h6>`) y jerarquía
- Párrafos, spans y divs
- Listas: ordenadas, desordenadas y de definición
- Links: `<a>`, atributos `href`, `target`, `rel`
- Imágenes: `<img>`, atributos `src`, `alt`, lazy loading
- Embeddings: `<iframe>`, `<video>`, `<audio>`
- Formularios
  * `<form>`, `<input>`, `<textarea>`, `<select>`, `<button>`
  * Atributos: `name`, `id`, `type`, `required`, `placeholder`
  * Validación nativa HTML5
- HTML semántico
  * `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<aside>`, `<footer>`
  * Importancia para SEO y accesibilidad
- Tablas: `<table>`, `<thead>`, `<tbody>`, `<tr>`, `<th>`, `<td>`
- Accesibilidad web (a11y)
  * Atributos ARIA (`aria-label`, `role`, `aria-hidden`)
  * Uso correcto de headings y landmarks
  * Contraste de colores y lectura por teclado

### 6. CSS
- Formas de incluir CSS: inline, interno, externo
- Selectores
  * Elemento, clase (`.`), ID (`#`), universal (`*`)
  * Combinadores: descendiente, hijo directo, hermano
  * Pseudoclases: `:hover`, `:focus`, `:nth-child`, `:not`
  * Pseudoelementos: `::before`, `::after`, `::placeholder`
  * Especificidad y cascada
- Box Model: `margin`, `border`, `padding`, `content`
- Display: `block`, `inline`, `inline-block`, `none`
- Posicionamiento: `static`, `relative`, `absolute`, `fixed`, `sticky`
- Flexbox
  * `display: flex`, `flex-direction`, `justify-content`, `align-items`
  * `flex-wrap`, `gap`, `flex-grow/shrink/basis`
- CSS Grid
  * `grid-template-columns/rows`, `grid-area`, `gap`
  * Diferencia con Flexbox: cuándo usar cada uno
- Colores
  * Palabras clave
  * HEX, RGB, RGBA
  * HSL, HSLA
  * OKLCH (moderno, mayor gamut de color)
- Tipografía
  * `font-family`, `font-size`, `font-weight`, `line-height`
  * Google Fonts y fuentes personalizadas
  * Variables CSS (`--color-primary: #3b82f6`)
- Responsive Design
  * Media queries (`@media`)
  * Mobile-first vs Desktop-first
  * Unidades relativas: `em`, `rem`, `%`, `vw`, `vh`, `dvh`
- Animaciones y transiciones
  * `transition`, `animation`, `@keyframes`
  * `transform`: translate, rotate, scale, skew
- Frameworks CSS
  * Bootstrap: grid, componentes, utilidades
  * Tailwind CSS: utility-first, configuración, JIT
  * Comparación y cuándo usar cada uno

### 7. JavaScript (Vanilla)
- Historia y rol de JS en el navegador
- Variables: `var`, `let`, `const` y sus diferencias
- Tipos de datos: primitivos y objetos
- Operadores: aritméticos, comparación, lógicos, ternario, nullish coalescing (`??`), optional chaining (`?.`)
- Funciones
  * Declaración, expresión, arrow functions
  * Closures
  * IIFE
  * Callbacks
- Arrays a fondo
  * `map`, `filter`, `reduce`, `find`, `findIndex`, `some`, `every`, `flat`, `flatMap`
  * Spread operator, destructuring
- Objetos
  * Creación, propiedades, métodos
  * Desestructuración
  * Spread operator
  * `Object.keys/values/entries`
  * Prototipos y cadena de prototipos
- DOM (Document Object Model)
  * Selección: `getElementById`, `querySelector`, `querySelectorAll`
  * Manipulación: `innerHTML`, `textContent`, `classList`, `style`, `setAttribute`
  * Creación y eliminación de nodos
- Eventos
  * `addEventListener`, `removeEventListener`
  * Event bubbling y capturing
  * `event.preventDefault()`, `event.stopPropagation()`
  * Delegación de eventos
- Asincronía
  * Event loop, call stack, task queue
  * Callbacks y callback hell
  * Promesas: `new Promise`, `.then()`, `.catch()`, `.finally()`
  * `Promise.all`, `Promise.allSettled`, `Promise.race`
  * `async / await`
  * Manejo de errores en código asíncrono
- Fetch API y peticiones HTTP
  * `fetch()`, opciones, headers
  * Consumo de APIs REST
- Módulos ES6
  * `import` / `export`, default vs named exports
- Consola del navegador
  * `console.log/warn/error/table/time/group`
- DevTools
  * Elements, Console, Network, Sources, Performance, Lighthouse
- Almacenamiento en el navegador
  * `localStorage`, `sessionStorage`, `cookies`, IndexedDB
- NodeJS
  * ¿Qué es y para qué sirve?
  * Módulos CommonJS (`require`) vs ESModules (`import`)
  * Event-driven y non-blocking I/O
  * `npm`: `install`, `scripts`, `package.json`, `package-lock.json`, `node_modules`
  * `npx`: ejecutar binarios sin instalar globalmente
  * Express.js
    - Routing
    - Middlewares
    - Request y Response
    - Variables de entorno
    - Conexión a bases de datos
    - REST API completa

### 8. TypeScript
- ¿Por qué TypeScript? JavaScript + seguridad de tipos
- Tipado estático vs dinámico
- Tipos básicos: `string`, `number`, `boolean`, `null`, `undefined`, `void`, `any`, `unknown`, `never`
- Arrays y Tuples tipados
- Interfaces y Types (`type` vs `interface`)
- Union Types (`|`) y Intersection Types (`&`)
- Generics (`<T>`)
- Enums
- Type assertions (`as`)
- Decoradores (introducción)
- `tsconfig.json`: opciones importantes
- Integración con frameworks (React, Angular, Express)
- Utility Types: `Partial`, `Required`, `Readonly`, `Pick`, `Omit`, `Record`

---

## 📌 FASE 5 — Bases de Datos

> Los datos son el corazón de cualquier aplicación. Hay que saber almacenarlos correctamente.

### 9. Bases de Datos
- ¿Qué son las bases de datos?
  * Datos, información y conocimiento
  * DBMS (Database Management System)
- Motor de bases de datos vs Gestor de bases de datos
- SQL (Relacionales)
  * ¿Qué es el modelo relacional?
  * DDL: `CREATE`, `ALTER`, `DROP`, `TRUNCATE`
  * DML: `SELECT`, `INSERT`, `UPDATE`, `DELETE`
  * DQL: `SELECT` con `WHERE`, `ORDER BY`, `GROUP BY`, `HAVING`, `LIMIT`
  * JOINs: `INNER`, `LEFT`, `RIGHT`, `FULL OUTER`, `CROSS`, `SELF`
  * Subconsultas y CTEs (`WITH`)
  * Funciones de agregación: `COUNT`, `SUM`, `AVG`, `MAX`, `MIN`
  * Índices: tipos, cuándo usar, impacto en performance
  * Transacciones y ACID (Atomicidad, Consistencia, Aislamiento, Durabilidad)
  * Niveles de aislamiento: Read Uncommitted, Read Committed, Repeatable Read, Serializable
  * Normalización: 1FN, 2FN, 3FN, BCNF
  * Desnormalización: cuándo y por qué
  * Vistas (Views)
  * Procedimientos almacenados y funciones
  * Triggers
  * Migraciones
  * Gestores: MySQL, PostgreSQL, SQL Server, SQLite
- NoSQL (No Relacionales)
  * ¿Cuándo usar NoSQL vs SQL?
  * Tipos:
    - Documentos: MongoDB, CouchDB
    - Clave-valor: Redis, DynamoDB
    - Columnar: Cassandra, HBase
    - Grafos: Neo4j
  * Ventajas y limitaciones (CAP Theorem)
  * MongoDB: colecciones, documentos, CRUD, índices, aggregation pipeline
  * Redis: caché, pub/sub, TTL, casos de uso
- Modelado de datos
  * DER (Diagrama Entidad-Relación)
    - Entidades, atributos, relaciones
    - Cardinalidades: 1:1, 1:N, N:M
  * Diagrama Relacional
  * Herramientas: dbdiagram.io, draw.io, Mermaid

---

## 📌 FASE 6 — Frontend Moderno

> Una vez tienes los fundamentos de JS y CSS, puedes escalar a frameworks modernos.

### 10. React
- ¿Qué es y cómo funciona internamente? (Virtual DOM, reconciliación)
- Crear proyecto: `create-react-app` vs Vite
- JSX: sintaxis y reglas
- Componentes funcionales
- Props: paso de datos, tipos, defaultProps
- Estado con `useState`
- Ciclo de vida con `useEffect`
- Renderizado condicional y de listas (`key`)
- Manejo de formularios controlados y no controlados
- Hooks
  * `useState`, `useEffect`, `useContext`, `useRef`, `useMemo`, `useCallback`, `useReducer`
  * Hooks personalizados (Custom Hooks)
- Gestión de estado
  * Context API
  * Redux Toolkit (RTK)
  * Zustand
  * Jotai / Recoil
- React Router v6
  * `<Routes>`, `<Route>`, `<Link>`, `<NavLink>`
  * Parámetros de URL y query strings
  * Rutas protegidas
- Consumo de APIs
  * `fetch` y `axios`
  * React Query / TanStack Query
- Performance en React
  * `React.memo`, `useMemo`, `useCallback`
  * Code splitting y lazy loading
  * Profiler
- Testing en React
  * React Testing Library
  * Jest
- Next.js (introducción)
  * SSR, SSG, ISR
  * File-based routing
  * API Routes

### 11. Angular
- ¿Qué es y cuándo usarlo? (empresarial, estructurado)
- Angular CLI: `ng new`, `ng generate`, `ng serve`
- Módulos (`NgModule`) y Standalone Components (Angular 17+)
- Componentes: template, clase, metadata (`@Component`)
- Directivas
  * Estructurales: `*ngIf`, `*ngFor`, `*ngSwitch`
  * De atributo: `[ngClass]`, `[ngStyle]`
  * Pipes: `date`, `currency`, `async`
- Data binding: interpolación, property, event, two-way (`[(ngModel)]`)
- Servicios e inyección de dependencias
- HttpClient para consumo de APIs
- RxJS y Observables
  * `Observable`, `Subject`, `BehaviorSubject`
  * Operadores: `map`, `filter`, `switchMap`, `mergeMap`, `catchError`, `debounceTime`
- Routing: `RouterModule`, guards, lazy loading de módulos
- Formularios: Reactivos vs Template-driven
- Angular Material (UI library)
- Signals (Angular 17+): estado reactivo moderno

---

## 📌 FASE 7 — Ruta Backend con C# y .NET

> El backend es donde vive la lógica de negocio. C# es uno de los lenguajes más robustos para esto.

### 12. Fundamentos de C#
- Historia y ecosistema .NET (Core, Framework, .NET 5+)
- Tipos de proyectos: Console, Web API, MVC, Class Library
- Tipos de datos
  * Primitivos: `int`, `long`, `double`, `float`, `decimal`, `bool`, `char`, `string`
  * Tipos por valor vs por referencia
  * `var`, `dynamic`, `object`
  * Nullable types: `int?`, `string?`
- Arrays, Listas y colecciones
  * `Array`, `List<T>`, `Dictionary<K,V>`, `HashSet<T>`, `Queue<T>`, `Stack<T>`
  * `IEnumerable<T>`, `ICollection<T>`, `IList<T>`
- Loops: `for`, `foreach`, `while`, `do-while`
- Condicionales: `if/else`, `switch`, pattern matching
- Operadores: aritméticos, lógicos, bit a bit, ternario, null-coalescing (`??`), null-conditional (`?.`)
- Funciones y métodos
  * Parámetros: `ref`, `out`, `params`, opcionales, nombrados
  * Sobrecarga de métodos
  * Extension methods
- Namespaces y using directives
- Manejo de excepciones: `try/catch/finally`, tipos de excepciones, excepciones personalizadas
- Tuples y ValueTuple
- Records (C# 9+): inmutabilidad y value equality
- Pattern matching avanzado
- Expresiones lambda y LINQ funcional

### 13. POO en C# (Programación Orientada a Objetos)
- ¿Qué es y para qué sirve?
- Clases y Objetos
  * Constructor: sobrecarga, `this`
  * Destructor y `IDisposable` / `using`
- Propiedades
  * Auto-properties
  * Getters y setters personalizados
  * `init` (C# 9+)
- Encapsulamiento
  * Modificadores de acceso: `public`, `private`, `protected`, `internal`, `protected internal`
- Herencia
  * `virtual`, `override`, `sealed`
  * Constructor base con `base`
  * Clase `Object` y métodos como `ToString()`, `Equals()`, `GetHashCode()`
- Polimorfismo
  * En tiempo de compilación (sobrecarga) vs en tiempo de ejecución (sobreescritura)
- Abstracción
  * Clases abstractas (`abstract`)
  * Interfaces: múltiple implementación, default interface methods (C# 8+)
- Genéricos (`<T>`)
  * Constraints (`where T : class`, `where T : new()`)
- Enums y structs
- Delegates, Events y lambdas
- Nullable Reference Types (C# 8+)
- Inmutabilidad y Records

### 14. Seguridad Web
- OWASP Top 10 (actualizado 2021)
  * A01 - Broken Access Control
  * A02 - Cryptographic Failures (antes: Sensitive Data Exposure)
  * A03 - Injection (SQL, NoSQL, Command Injection)
  * A04 - Insecure Design
  * A05 - Security Misconfiguration
  * A06 - Vulnerable and Outdated Components
  * A07 - Identification and Authentication Failures (antes: Broken Authentication)
  * A08 - Software and Data Integrity Failures
  * A09 - Security Logging and Monitoring Failures
  * A10 - Server-Side Request Forgery (SSRF)
  * Detalle: XSS (Stored, Reflected, DOM-based)
  * Detalle: CSRF
- JWT (JSON Web Tokens)
  * Estructura: Header, Payload, Signature
  * Firma y verificación (HS256, RS256)
  * Access tokens y Refresh tokens
  * Almacenamiento seguro (httpOnly cookies vs localStorage)
  * Expiración y revocación
- Autenticación vs Autorización
  * Claims-based identity
  * Role-based (RBAC) vs Policy-based (ABAC)
- Hashing de contraseñas
  * BCrypt, Argon2, PBKDF2
  * Salt y pepper
  * Por qué NO usar MD5/SHA1 para contraseñas
- CORS (Cross-Origin Resource Sharing)
  * Política same-origin
  * Headers y configuración
- Protección de headers HTTP
  * `Content-Security-Policy`
  * `X-Frame-Options`
  * `X-Content-Type-Options`
- Rate Limiting y protección contra ataques de fuerza bruta
- Validación y sanitización de entradas

### 15. ASP.NET Core
- Arquitectura de ASP.NET Core
  * Pipeline de middleware
  * `Program.cs` y configuración del host
  * Inyección de dependencias (DI) integrada
- MVC Pattern en ASP.NET Core
  * Controllers y Actions
  * Razor Views
  * `ViewData`, `ViewBag`, `TempData`
  * `IActionResult` y tipos de respuesta
  * Routing: convencional y por atributos
- Web API (REST API)
  * Controllers de API
  * `[ApiController]`, `[Route]`, `[HttpGet/Post/Put/Patch/Delete]`
  * Model Binding y validación con Data Annotations
  * Respuestas tipadas con `ActionResult<T>`
  * Versionado de APIs
  * Swagger / OpenAPI con Swashbuckle
- Entity Framework Core (EF Core)
  * ORM: qué es y cómo funciona
  * DbContext y DbSet
  * Code First vs Database First
  * Migraciones: `Add-Migration`, `Update-Database`, `Remove-Migration`
  * Relaciones: 1:1, 1:N, N:M en EF Core
  * LINQ con EF Core: queries, proyecciones, includes
  * Lazy Loading vs Eager Loading vs Explicit Loading
  * Configuración con Fluent API vs Data Annotations
  * Transacciones con EF Core
- LINQ
  * Sintaxis de query vs sintaxis de método
  * Operadores: `Where`, `Select`, `OrderBy`, `GroupBy`, `Join`, `FirstOrDefault`, `Any`, `All`, `Count`, `Sum`, `Take`, `Skip`
  * LINQ to Objects, LINQ to EF
- DTO (Data Transfer Object)
  * ¿Por qué no exponer entidades directamente?
  * Mapeo manual vs AutoMapper
  * Validaciones en DTOs con FluentValidation
- ViewModel
- Nuget Packages
  * Gestión de paquetes
  * NuGet.org
- Async/Await en ASP.NET Core
  * `Task`, `Task<T>`, `ValueTask`
  * Mejores prácticas: evitar deadlocks, `ConfigureAwait`
- Middleware
  * Creación de middleware personalizado
  * Orden de ejecución
  * Exception handling middleware
- Configuración
  * `appsettings.json`, `appsettings.Development.json`
  * `IConfiguration`, `IOptions<T>`
  * Variables de entorno en .NET
- Consumo de APIs externas
  * `HttpClient` y `IHttpClientFactory`
  * Polly: reintentos, circuit breaker
- Rate Limiting (ASP.NET Core 7+)
- Validate AntiForgery Token (`[ValidateAntiForgeryToken]`)
- Razor Pages

### 16. Testing en .NET
- ¿Por qué hacer testing? TDD (Test-Driven Development)
- Pirámide de testing: unitarias, integración, E2E
- xUnit vs NUnit vs MSTest
- Pruebas unitarias
  * Patrón AAA: Arrange, Act, Assert
  * Assertions en xUnit
  * Pruebas parametrizadas (`[Theory]`, `[InlineData]`)
- Mocking con Moq
  * `Mock<T>`, `Setup`, `Returns`, `Verify`
  * AutoMocker
- Pruebas de integración en ASP.NET Core
  * `WebApplicationFactory<T>`
  * `HttpClient` de prueba
  * Base de datos en memoria (InMemory, SQLite)
- Pruebas de cobertura
  * Coverlet y reportes HTML
  * Métricas de cobertura
- Property-Based Testing
  * FsCheck (para C#)
  * Qué son las propiedades y cómo definirlas
- FluentAssertions: assertions más legibles

### 17. Recursos Adicionales .NET
- ASP.NET Core Identity
  * UserManager, RoleManager, SignInManager
  * Claims y roles personalizados
  * Integración con JWT
- Webhooks
  * ¿Qué son? Push vs Pull
  * Implementación de endpoints para recibir webhooks
  * Seguridad: firma HMAC
- Minimal APIs (ASP.NET Core 6+)
- SignalR (WebSockets en .NET)
  * Hubs, clientes, tiempo real
- Blazor (introducción)
  * Server-side vs WebAssembly
- gRPC en .NET (alternativa a REST)
- Hosted Services y Background Workers

---

## 📌 FASE 8 — Ruta Backend Alternativa: Laravel (PHP)

> Laravel es uno de los frameworks más completos del ecosistema PHP. Ideal para proyectos web modernos.

### 18. Fundamentos de PHP
- Historia y ecosistema PHP
- Sintaxis básica, tipos y operadores
- Funciones y arrays en PHP
- OOP en PHP: clases, herencia, traits, interfaces

### 19. Laravel
- Instalación: Composer, Laravel Installer
- Estructura del proyecto
- Routing: web.php, api.php, Route facades
- Controllers: CRUD, Resource Controllers
- Blade Templating Engine
  * Layouts, includes, componentes, directivas
- Eloquent ORM
  * Modelos, migraciones, seeders, factories
  * Relaciones: hasOne, hasMany, belongsTo, belongsToMany, morphic
  * Query Builder
  * Scopes locales y globales
- Middleware
- Validación de formularios (Form Request Validation)
- Autenticación
  * Laravel Breeze / Jetstream
  * Sanctum (SPA auth) y Passport (OAuth2)
- Autorización: Gates y Policies
- Queues y Jobs (colas de trabajo)
- Events y Listeners
- Notificaciones: email, SMS, Slack **[1]**
- Almacenamiento de archivos (Storage Facade, S3)
- Caché: Redis, Memcached
- Artisan CLI
- Testing en Laravel
  * PHPUnit integrado
  * Feature tests y Unit tests
  * HTTP testing, database testing
- API Resources: transformación de respuestas
- Livewire (componentes reactivos server-side)

---

## 📌 FASE 9 — Temas Transversales

> Estos temas aplican sin importar el lenguaje o framework que uses.

### 20. QA (Quality Assurance)
- ¿Qué es QA y cuál es su rol en el equipo?
- Pruebas Funcionales
  * Unitarias: probar una sola unidad de código
  * De Integración: probar la interacción entre módulos
  * De Sistema: probar el sistema completo
  * De Aceptación (UAT): validar con el cliente
  * De Regresión: verificar que nada se rompió
  * Smoke testing y Sanity testing
- Pruebas No Funcionales
  * Rendimiento: tiempo de respuesta, throughput
  * Carga: comportamiento bajo N usuarios simultáneos
  * Estrés: límites del sistema
  * Usabilidad y UX
  * Seguridad
  * Volumen: grandes cantidades de datos
- Automatización de pruebas
  * Selenium / Playwright / Cypress (E2E)
  * k6 / JMeter (carga y performance)
- Bug lifecycle: report, triage, fix, verify, close
- BDD (Behavior-Driven Development): Gherkin, SpecFlow, Cucumber

### 21. Calidad de Software
- ¿Qué es calidad del software?
- Pilares: funcionalidad, confiabilidad, usabilidad, eficiencia, mantenibilidad, portabilidad
- ISO/IEC 25010 (actualización de ISO 9126)
  * Características y subcaracterísticas
- CMMI (Capability Maturity Model Integration)
- Deuda técnica: qué es y cómo gestionarla
- Code smells y refactoring
  * Principios SOLID
    - S: Single Responsibility
    - O: Open/Closed
    - L: Liskov Substitution
    - I: Interface Segregation
    - D: Dependency Inversion
  * DRY, KISS, YAGNI
- Clean Code (Robert C. Martin)
- Revisión de código (Code Review)
- Linters y formateadores: ESLint, Prettier, dotnet-format, StyleCop

### 22. DevOps
- ¿Qué es DevOps? Cultura y prácticas
- Docker
  * ¿Qué es la containerización y por qué importa?
  * Imágenes: Dockerfile, layers, multi-stage builds
  * Contenedores: ciclo de vida, comandos esenciales
  * Docker Compose: servicios, redes, volúmenes
  * Docker Hub y registries privados
  * Mejores prácticas: imágenes pequeñas, non-root users, health checks
- Redes
  * Modelo OSI (7 capas) simplificado
  * TCP/IP, UDP
  * IPv4 e IPv6: direccionamiento, CIDR, subredes
  * Puertos y protocolos comunes
  * SSH: conexión, llaves, tunneling, `scp`
  * Proxy y Reverse Proxy (NGINX, Traefik)
  * Firewall: `iptables`, `ufw`, security groups
  * DNS: resolución, registros A, CNAME, MX, TXT
  * Load balancing: round-robin, least connections
- NGINX
  * Servidor web y reverse proxy
  * Virtual hosts (server blocks)
  * SSL/TLS con Let's Encrypt
  * Caché, compresión gzip
  * Rate limiting
- CI/CD
  * ¿Qué es Integración Continua y Entrega/Despliegue Continuo?
  * Diferencia entre CI, CD (Delivery) y CD (Deployment)
  * Pipeline típico: build → test → lint → scan → deploy
  * Ambientes: desarrollo, staging, producción
  * **Jenkins**
    - ¿Qué es Jenkins y por qué sigue siendo relevante?
      · Historia: el servidor de CI/CD más antiguo y extendido de la industria
      · Open source, auto-hospedado, altamente configurable
      · Comparación con GitHub Actions, GitLab CI y CircleCI
    - Instalación y configuración
      · Instalación en servidor Linux (`.war`, `apt`, Docker)
      · Configuración inicial: usuario admin, plugins recomendados
      · Jenkins en Docker: imagen oficial `jenkins/jenkins:lts`
      · Acceso web y seguridad básica (`http://localhost:8080`)
    - Arquitectura de Jenkins
      · Master / Controller: orquesta los pipelines
      · Agents / Nodes: ejecutan las tareas (SSH, JNLP, Docker)
      · Executors: hilos de trabajo por nodo
      · Workspace: directorio de trabajo por job
    - Tipos de proyectos (Jobs)
      · Freestyle Project: configuración por interfaz gráfica
      · Pipeline Job: definido en código (Jenkinsfile)
      · Multibranch Pipeline: detecta ramas automáticamente
      · Organization Folder: escanea repos de GitHub/GitLab/Bitbucket
    - Jenkinsfile y Pipeline as Code
      · ¿Qué es un Jenkinsfile? Declarativo vs Scripted
      · Sintaxis declarativa (recomendada):
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
      · Bloques: `pipeline`, `agent`, `stages`, `stage`, `steps`, `post`
      · Directivas: `environment`, `options`, `parameters`, `triggers`, `when`
      · `post`: `always`, `success`, `failure`, `unstable`, `changed`
    - Agents y ejecución distribuida
      · `agent any`, `agent none`, `agent { label 'linux' }`
      · Agent Docker: `agent { docker { image 'node:18' } }`
      · Nodos remotos: conectar servidores via SSH o JNLP
      · Escalar con múltiples agents para builds paralelos
    - Plugins esenciales
      · Git Plugin: integración con repositorios Git
      · Pipeline Plugin: soporte para Jenkinsfile
      · Blue Ocean: UI moderna para pipelines
      · Credentials Plugin: manejo seguro de secretos
      · Docker Pipeline: integrar Docker en pipelines
      · Slack Notification: alertas al equipo
      · JUnit Plugin: publicar resultados de tests
      · Cobertura (JaCoCo, Covertura): reportes de cobertura
      · SonarQube Scanner: análisis de calidad de código
      · Kubernetes Plugin: agents dinámicos en K8s
    - Manejo de credenciales y secretos
      · Jenkins Credentials Store: usuario/contraseña, SSH keys, tokens
      · Usar credenciales en Jenkinsfile: `withCredentials`, `environment`
      · Nunca hardcodear secretos en el Jenkinsfile
    - Triggers y automatización
      · Poll SCM: revisar cambios cada N minutos
      · Webhooks: GitHub/GitLab notifica a Jenkins en cada push/PR
      · Cron: `triggers { cron('H 2 * * 1-5') }`
      · Build después de otro job: `upstream`
    - Pipelines avanzados
      · Stages en paralelo: `parallel { stage('A'){...} stage('B'){...} }`
      · Shared Libraries: reutilizar código Groovy entre pipelines
        · Estructura: `vars/`, `src/`, `resources/`
        · `@Library('my-shared-lib') _`
      · Input step: aprobación manual antes de deployar a producción
      · Stash / Unstash: pasar artefactos entre stages
      · Timeout y retry: `timeout(time: 10, unit: 'MINUTES')`
    - Integración con herramientas externas
      · SonarQube: análisis estático de código
      · Nexus / Artifactory: gestión de artefactos
      · Kubernetes: deploy con `kubectl` o Helm desde Jenkins
      · AWS: deploy con AWS CLI o SDK desde Jenkins
      · Docker Registry: build y push de imágenes
    - Seguridad en Jenkins
      · Matrix Authorization Strategy: permisos por usuario/rol
      · Role Strategy Plugin: roles granulares
      · Proteger el Jenkinsfile: evitar script injection
      · Configurar HTTPS con reverse proxy (NGINX)
      · Auditoría: logs de acceso y cambios
    - Buenas prácticas
      · Versionar el Jenkinsfile junto al código fuente
      · Usar Declarative Pipeline sobre Scripted
      · Mantener stages pequeños y con responsabilidad única
      · Fallar rápido: tests primero, deploy al final
      · Limpiar workspaces: `deleteDir()` o `cleanWs()`
      · Usar Docker agents para entornos reproducibles
      · Configurar notificaciones (Slack, email) en `post`
    - Jenkins vs alternativas modernas
      · GitHub Actions: integrado en GitHub, sin servidor propio
      · GitLab CI/CD: integrado en GitLab, muy completo
      · CircleCI / Travis CI: SaaS, menos configuración
      · Jenkins: máximo control, on-premise, legacy enterprises
  * GitHub Actions: workflows, jobs, secrets, environments, artifacts
  * GitLab CI/CD: `.gitlab-ci.yml`, stages, runners
- Kubernetes (K8s)
  * Conceptos: Pod, Deployment, Service, Ingress, ConfigMap, Secret
  * kubectl: comandos básicos
  * Helm charts
  * Diferencia con Docker Compose
- Infraestructura como Código (IaC)
  * Terraform: providers, resources, state
  * Pulumi (alternativa)
- Observabilidad y Monitoreo
  * Logs estructurados (JSON)
  * Serilog (.NET): sinks, enrichers, plantillas
  * OpenTelemetry: traces, metrics, logs
  * Prometheus y Grafana
  * Alertas y dashboards
  * ELK Stack (Elasticsearch, Logstash, Kibana)
- CertBot y renovación automática de certificados

### 23. Arquitectura de Software y Patrones de Diseño
- ¿Qué es la arquitectura de software?
- ¿Qué son los patrones de diseño?
- Diferencia entre arquitectura y patrones
- Principios fundamentales: SOLID, DRY, KISS, YAGNI, SoC (Separation of Concerns)
- Arquitecturas
  * Monolítica vs Microservicios vs Modular Monolith
  * MVC (Modelo-Vista-Controlador): variantes MVP, MVVM
  * Arquitectura en Capas (N-Layer)
    - Presentación, Aplicación, Dominio, Infraestructura
  * Clean Architecture (Robert C. Martin)
    - Capas concéntricas, regla de dependencia
  * Hexagonal Architecture (Ports and Adapters)
  * DDD (Domain-Driven Design)
    - Bounded Contexts
    - Entities, Value Objects, Aggregates
    - Domain Events
    - Repositories, Services, Factories
  * Event-Driven Architecture
  * CQRS (Command Query Responsibility Segregation)
    - Commands vs Queries
    - MediatR en .NET
  * Event Sourcing
  * Serverless
- Patrones de diseño (GoF)
  * Creacionales: Singleton, Factory Method, Abstract Factory, Builder, Prototype
  * Estructurales: Adapter, Decorator, Facade, Proxy, Composite, Bridge, Flyweight
  * De comportamiento: Strategy, Observer, Command, Iterator, Template Method, Chain of Responsibility, State, Mediator, Visitor
- Patrones adicionales
  * Repository Pattern
  * Unit of Work
  * Service Layer
  * Specification Pattern
  * Outbox Pattern
- Antipatrones
  * God Object, Spaghetti Code, Golden Hammer, Lava Flow
  * Big Ball of Mud
- Microservicios
  * Comunicación: REST, gRPC, mensajería (RabbitMQ, Kafka)
  * Service Discovery
  * API Gateway
  * Sagas y consistencia eventual

### 24. Metodologías Ágiles
- ¿Qué es Agile? Manifiesto Ágil y sus 12 principios
- SCRUM
  * Roles: Product Owner, Scrum Master, Dev Team
  * Artefactos: Product Backlog, Sprint Backlog, Increment
  * Ceremonias: Sprint Planning, Daily, Sprint Review, Retrospectiva
  * Definition of Done (DoD) y Definition of Ready (DoR)
  * Story Points y estimación
- Kanban
  * Tablero Kanban: columnas y WIP limits
  * Flujo continuo vs iteraciones
  * Métricas: Lead Time, Cycle Time, Throughput
- Lean
  * Principios Lean de manufactura aplicados a software
  * Eliminar desperdicios (muda)
- SAFe (Scaled Agile Framework): introducción
- Herramientas: Jira, Trello, Linear, GitHub Projects
- User Stories, Epics y Tasks
- Planning Poker

### 25. Documentación
- Importancia de documentar
- Docusaurus
  * Instalación y configuración
  * Markdown y MDX
  * Versionado de documentación
  * Despliegue en GitHub Pages
- OpenAPI / Swagger: documentar APIs REST
  * Swagger UI y Redoc
- README.md: cómo escribir un buen README
  * Badges, instalación, uso, contribución
- JSDoc / XML Doc Comments (C#)
- Architecture Decision Records (ADR)
- Diagramas con código: Mermaid, PlantUML, C4 Model
- Wiki en GitHub/GitLab

### 26. Ingeniería de Requisitos
- ¿Qué es y por qué importa?
- Etapas
  * Elicitación: entrevistas, workshops, observación, prototipos
  * Análisis: modelado, priorización (MoSCoW)
  * Especificación: casos de uso, historias de usuario, criterios de aceptación
  * Validación: revisiones, prototipos validados, UAT
  * Gestión: trazabilidad, control de cambios
- Tipos de Requisitos
  * Funcionales: qué debe hacer el sistema
  * No Funcionales: rendimiento, seguridad, escalabilidad, disponibilidad
  * De restricción: tecnología, presupuesto, tiempo
- Herramientas: Jira, Confluence, Notion, Azure DevOps
- Historias de Usuario: formato, criterios de aceptación (BDD con Gherkin)
- Modelado: casos de uso UML, diagramas de secuencia, diagramas de actividad

---

## 📌 FASE 10 — Cloud y Despliegue

### 27. AWS (Amazon Web Services)
- ¿Qué es el Cloud Computing? Modelos: IaaS, PaaS, SaaS
- IAM (Identity and Access Management)
  * Usuarios, grupos, roles, políticas
  * Least Privilege Principle
  * MFA y buenas prácticas
- VPC (Virtual Private Cloud)
  * Subnets públicas y privadas
  * Security Groups y NACLs
  * Internet Gateway y NAT Gateway
- EC2 (Elastic Compute Cloud)
  * Tipos de instancias y pricing
  * AMIs
  * User Data y configuración inicial
  * Despliegue de aplicaciones
- S3 (Simple Storage Service)
  * Buckets, objetos, permisos
  * Hosting estático
  * Ciclos de vida y versionado
- RDS (Relational Database Service)
  * Instancias gestionadas (MySQL, PostgreSQL, SQL Server)
  * Multi-AZ y Read Replicas
  * Backups automáticos
- Otros servicios relevantes
  * Lambda (serverless)
  * CloudFront (CDN)
  * ElastiCache (Redis gestionado)
  * SQS/SNS (mensajería)
  * ECS/EKS (contenedores)
  * CloudWatch (monitoreo y logs)
- Relación con Docker y CI/CD
  * ECR (Elastic Container Registry)
  * CodePipeline / GitHub Actions → deploy a AWS

---

## 📌 FASE 11 — Temas Avanzados y Especializaciones

### 28. Paradigmas de Programación
- Imperativo: instrucciones paso a paso
- Declarativo: qué, no cómo (SQL, HTML, configuración)
- Orientado a Objetos (OOP): encapsulamiento, herencia, polimorfismo
- Funcional
  * Funciones puras, inmutabilidad
  * Composición de funciones
  * Functors, Monads (introducción)
  * F# (funcional en el ecosistema .NET)
- Reactivo
  * Programación basada en flujos de datos y propagación de cambios
  * RxJS, Reactor (Java), System.Reactive (.NET)
- Orientado a Eventos (Event-Driven)
- Comparación: cuándo usar cada paradigma

### 29. Mensajería Asíncrona
- ¿Por qué mensajería? Desacoplamiento y escalabilidad
- RabbitMQ
  * Conceptos: Producer, Consumer, Queue, Exchange, Binding
  * Tipos de exchange: Direct, Topic, Fanout, Headers
  * Acknowledgements y durabilidad
  * Dead Letter Queues
  * Integración con .NET (MassTransit)
- Apache Kafka
  * Diferencia con RabbitMQ: log distribuido vs cola
  * Topics, partitions, consumer groups
  * Retención de mensajes
  * Casos de uso: event streaming, ETL
- Azure Service Bus / AWS SQS / SNS
- Patrones: Pub/Sub, Request-Reply, Saga

### 30. Multi-tenancy (Tenancy)
- ¿Qué es Multi-tenancy?
- Modelos de aislamiento
  * Base de datos por tenant
  * Esquema por tenant
  * Filas por tenant (discriminator column)
- Implementación en ASP.NET Core
- Seguridad y aislamiento de datos

### 31. Inteligencia Artificial para Desarrolladores
- Conceptos fundamentales
  * IA, ML, Deep Learning: diferencias y relación
  * Datos: datasets, features, labels
  * Tipos de aprendizaje: supervisado, no supervisado, refuerzo
- Machine Learning
  * Algoritmos: regresión, clasificación, clustering
  * Overfitting y underfitting
  * Validación cruzada
  * Scikit-learn (Python)
- Deep Learning
  * Redes neuronales: perceptrón, capas ocultas, activaciones
  * Backpropagation
  * CNNs (visión), RNNs/LSTMs (secuencias), Transformers
  * TensorFlow / PyTorch (introducción)
- LLMs (Large Language Models)
  * ¿Qué son? GPT, Claude, Llama, Gemini
  * Tokenización y contexto
  * Temperature, top-p, top-k
- RAG (Retrieval-Augmented Generation)
  * Embeddings y bases de datos vectoriales (Pinecone, Qdrant, pgvector)
  * Pipeline: ingest → embed → retrieve → generate
- Fine-tuning
  * Cuándo y por qué hacer fine-tuning
  * LoRA / QLoRA
- IA Generativa
  * Texto, imágenes (Stable Diffusion, DALL-E), código, audio, video
- n8n
  * Automatización de flujos con IA
  * Nodos de OpenAI, webhooks, HTTP Request
- Integración de IA en aplicaciones
  * OpenAI API / Anthropic API / HuggingFace
  * Azure OpenAI Service
  * Semantic Kernel (.NET)
  * LangChain (Python)

### 32. Prompt Engineering
- ¿Qué es y por qué importa?
- Componentes de un buen prompt
  * Role: definir el papel del modelo
  * Task: la tarea específica
  * Context: información de fondo
  * Format: formato de salida esperado
  * Constraints: limitaciones y restricciones
  * Examples: ejemplos para guiar la respuesta
- Técnicas avanzadas
  * Zero-Shot Prompting
  * Few-Shot Prompting
  * Chain-of-Thought (CoT)
  * Tree of Thought (ToT)
  * ReAct (Reasoning + Acting)
  * Prompt Chaining
  * Self-Consistency
- Evaluación de prompts
- System prompts vs user prompts
- Herramientas: PromptLayer, LangSmith

### 33. Herramientas de IA para Desarrolladores
- Claude Code / Kiro / Cursor
  * Flujos de trabajo con agentes de IA
  * Specs y contexto estructurado
- GitHub Copilot
  * Autocompletado inteligente
  * Copilot Chat, Copilot CLI
- Codeium, Tabnine
- OpenClaw / otras herramientas de análisis de código
- IA en el ciclo de desarrollo: generación, revisión, testing, documentación

---

*Roadmap mantenido por Santiago Zapata Rendón — última revisión: junio 2026*
