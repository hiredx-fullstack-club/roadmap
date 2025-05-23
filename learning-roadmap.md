# Learning Roadmap: Full-stack Development Path

This document covers the technical skills and knowledge required to become a proficient full-stack developer.

### 1.1. Foundational Web Skills

**Goal:** Understand the core building blocks of the web.

* **HTML:**
    * Semantic HTML5 elements, accessibility basics (ARIA attributes)
    * Forms and input types, SEO best practices
    * *Resources:* MDN Web Docs, HTML.com
* **CSS:**
    * Selectsors, specificity, cascade, Box Model, Flexbox, Grid
    * Responsive Design (Media Queries, Mobile-first)
    * CSS Variables, Preprocessors (Sass/Less - optional)
    * *Resources:* CSS-Tricks, Flexbox Froggy, Grid Garden
* **JavaScript (ES6+):**
    * Variables (let, const), data types, operators, control flow (if/else, loops)
    * Functions (arrow functions), Objects, Arrays, Destructuring
    * Asynchronous JS (Promises, async/await), DOM Manipulation
    * Fetch API / AJAX, Error Handling
    * *Resources:* JavaScript.info, FreeCodeCamp JS course

### 1.2. Version Control: Git & GitHub

**Goal:** Collaborate effectively and manage code changes.

* **Git Basics:**
    * `git init`, `git add`, `git commit`, `git branch`, `git checkout`
    * `git merge`, `git rebase`, `git push`, `git pull`, `git clone`
    * Resolving merge conflicts
* **GitHub Usage:**
    * Repositories, Issues, Pull Requests, Forking workflows
    * Collaborating on projects
    * *Resources:* Git documentation, GitHub Guides

### 1.3. Frontend Core

**Goal:** Build interactive and performant user interfaces.

#### 1.3.1. CSS Frameworks & Methodologies

* **Frameworks:** (Choose one to start, explore others)
    * Tailwind CSS: Utility-first approach
    * Bootstrap: Component-based framework
    * Material UI, Ant Design: React component libraries
* **Methodologies:** (Optional, but good to know)
    * BEM (Block Element Modifier), CSS Modules, Styled Components

#### 1.3.2. JavaScript Frameworks/Libraries

* **Deep Dive into ONE:** (e.g., React, Vue, Angular)
    * Components, props, state, lifecycle methods/hooks
    * Routing, API integration
* **Next.js:** (Recommended for modern React full-stack development)
    * Server-Side Rendering (SSR), Static Site Generation (SSG), Incremental Static Regeneration (ISR)
    * File-based routing, API Routes, Server Components/Actions
    * Data fetching strategies (`getServerSideProps`, `getStaticProps`, `useSWR`)
* **State Management:**
    * Context API (React), Vuex (Vue), NgRx (Angular)
    * Redux (general purpose), Zustand, Recoil, Pinia (newer, often simpler alternatives)

#### 1.3.3. Build Tools

* **Package Managers:** npm, Yarn, pnpm
* **Bundlers:** Webpack, Vite, Parcel
* **Transpilers:** Babel
* **Linters/Formatters:** ESLint, Prettier

### 1.4. Backend Core

**Goal:** Build robust and scalable server-side applications.

#### 1.4.1. Server-side Language & Framework

* **Choose ONE Stack to Master, then explore others:**
    * **JavaScript (Node.js):**
        * Express.js: Lightweight framework
        * NestJS: Opinionated, TypeScript-first framework
    * **Python:**
        * Django: Full-featured framework
        * Flask: Micro-framework
    * **.NET Core (C#):**
        * ASP.NET Core: Powerful framework for building web apps and APIs
        * Entity Framework Core (ORM)
    * **Rust:**
        * Actix-web, Axum, Warp (web frameworks) - Focus on performance and safety
        * Understanding ownership, borrowing, and lifetimes
    * **PHP:**
        * **Laravel:** Widely used PHP framework for web artisans.
        * Concepts: Eloquent ORM, Blade templating, Artisan CLI.
    * **Elixir:**
        * **Phoenix Framework:** Built on Erlang VM for highly scalable and fault-tolerant applications.
        * Concepts: OTP, LiveView for real-time interactivity.
    * **Ruby:**
        * Ruby on Rails: Convention-over-configuration framework
    * **Go:**
        * Gin, Echo (web frameworks)
* **Core Concepts (Language Agnostic):**
    * HTTP/HTTPS, Request/Response cycle
    * Routing, Middleware, Error handling
    * Environment variables

#### 1.4.2. APIs & Communication Protocols

* **RESTful APIs:**
    * Principles (resources, verbs, statelessness)
    * Designing endpoints, Status codes
* **GraphQL:** (Optional, but increasingly popular)
    * Queries, Mutations, Subscriptions
    * Schema definition, Apollo Server/Client
* **Protobufs (Protocol Buffers) & gRPC:** (For high-performance, polyglot microservices)
    * **Concepts:** Language-agnostic, efficient serialization format (Protobufs)
    * **gRPC:** High-performance RPC framework built on HTTP/2 and Protobufs
    * **Usage:** Defining `.proto` files, code generation for client/server stubs
    * **Benefits:** Faster, smaller payloads, strong typing, bidirectional streaming

#### 1.4.3. Authentication & Authorization

* **Authentication:**
    * Session-based, Token-based (JWT)
    * OAuth 2.0, OpenID Connect
* **Authorization:**
    * Role-Based Access Control (RBAC), Permissions

### 1.5. Databases

**Goal:** Persist and manage application data.

#### 1.5.1. Relational Databases (SQL)

* **Concepts:** Tables, rows, columns, relationships (one-to-one, one-to-many, many-to-many)
* **SQL Fundamentals:** SELECT, INSERT, UPDATE, DELETE, JOINs
* **Databases:** PostgreSQL, MySQL, SQLite
* **ORM (Object-Relational Mapping):** Prisma, TypeORM, Sequelize, SQLAlchemy, Entity Framework Core (for .NET), Eloquent (for Laravel)

#### 1.5.2. Non-Relational Databases (NoSQL)

* **Concepts:** Document, Key-Value, Column-Family, Graph
* **Databases:** MongoDB (Document), Redis (Key-Value/Cache), Cassandra (Column-Family)
* **ODM (Object-Document Mapping):** Mongoose (for MongoDB)

### 1.6. Deployment & DevOps Basics

**Goal:** Get your applications live and manage infrastructure.

* **Cloud Platforms:** (Understand basics of one)
    * AWS (EC2, S3, RDS, Lambda)
    * Google Cloud Platform (GCP)
    * Microsoft Azure
    * Vercel, Netlify (Frontend deployment, especially for Next.js)
    * Heroku, Render (PaaS for full-stack)
* **Containerization (Docker):**
    * Dockerfiles, Images, Containers, Docker Compose
* **CI/CD (Continuous Integration/Continuous Deployment):**
    * GitHub Actions, GitLab CI/CD, Jenkins
    * Automating tests and deployments

### 1.7. Testing & Security

**Goal:** Build robust and secure applications.

* **Testing:**
    * Unit Testing (Jest, React Testing Library, Pytest, xUnit/.NET, Cargo test/Rust)
    * Integration Testing, End-to-End Testing (Cypress, Playwright, Selenium)
* **Security:**
    * Common Vulnerabilities (OWASP Top 10: XSS, CSRF, SQL Injection, etc.)
    * Secure coding practices, HTTPS, CORS
    * Environment variable management

### 1.8. Beyond the Basics & Advanced Topics

* **WebSockets:** Real-time communication
* **Serverless Functions:** AWS Lambda, Google Cloud Functions, Azure Functions
* **Microservices Architecture:**
* **Web Performance Optimization:**
* **Monorepos:**
* **Distributed Systems Concepts:**
* **1.8.1. High-Performance Web & Beyond (WebAssembly - Wasm):**
    * **Concepts:** Binary instruction format for a stack-based virtual machine, runs in browsers and other environments.
    * **Usage:** Compiling C/C++/Rust/Go to Wasm for performance-critical client-side logic or server-side functions.
    * **Benefits:** Near-native performance, portability, security.
* **1.8.2. Cross-Platform Desktop Development with Web Technologies:**
    * **Tauri:** Building smaller, faster, and more secure desktop applications with Rust backend and any frontend framework.
    * **Wails:** Building desktop applications with Go backend and web frontend.
    * *Alternatives:* Electron (for comparison, but heavier).
* **Emerging Technologies:** Keep an eye on new frameworks, tools, and paradigms.

---

## 2. Developer Tools & Workflow

**Goal:** Master your development environment for maximum efficiency and productivity.

### 2.1. Integrated Development Environments (IDEs) / Code Editors

* **VS Code:**
    * **Mastering Features:** Extensions (ESLint, Prettier, GitLens, Docker, Live Share), Debugging, Integrated Terminal, Snippets, Keyboard Shortcuts, Settings Sync.
    * **Customization:** Themes, font ligatures, custom keybindings.
* **Neovim / Vim:**
    * **Fundamentals:** Modal editing, basic commands (`hjkl`, `i`, `esc`, `dd`, `yy`, `p`, `w`, `b`).
    * **Configuration:** `init.vim` / `init.lua`, plugins (Packer, LazyVim, NvChad), LSP (Language Server Protocol) integration, auto-completion, fuzzy finders (Telescope, FZF).
    * **Advanced:** Macros, complex motions, custom commands.
* **Other Tools (familiarity is a plus):**
    * WebStorm, IntelliJ IDEA (for specific languages/frameworks)

### 2.2. Command Line Interface (CLI) Mastery

* **Basic Commands:** `ls`, `cd`, `mkdir`, `rm`, `mv`, `cp`, `grep`, `cat`.
* **Shell Scripting:** Basic Bash/Zsh scripting for automation.
* **Package Managers:** npm, Yarn, pnpm, Cargo (Rust), Pip (Python), Dotnet CLI (.NET).
* **Terminal Multiplexers:** Tmux, Screen (for persistent sessions).

### 2.3. Browser Developer Tools

* **Elements Tab:** Inspecting and modifying HTML/CSS.
* **Console Tab:** JavaScript execution, logging, debugging.
* **Sources Tab:** Debugging JavaScript, setting breakpoints.
* **Network Tab:** Analyzing requests, responses, performance.
* **Performance Tab:** Identifying bottlenecks.
* **Memory Tab:** Heap snapshots, memory leaks.
* **Application Tab:** Local storage, session storage, cookies, service workers.

### 2.4. Design & Prototyping Tools (Awareness)

* Figma, Adobe XD, Sketch (for understanding design handoffs).
