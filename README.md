# Hi, I'm Sara 👋
### Full-Stack Developer · .NET · React / Angular · AI Agents & RAG

I build end-to-end systems: APIs, data layers and user interfaces, and I've worked on a real full-stack project in a 4-month practicum. My recent work focuses on applied AI: RAG pipelines, LLM agents and MCP tool integrations. The projects below span .NET, Java / Spring Boot, Node.js, Python, React and Angular.

📍 [Israel] · 📧 [sarasimihaloua@gmail.com] 

---

## 💼 Experience

### Full-Stack Developer, Practicum (4 months)
*Government security organization*

- Co-built a **project budget management system**: ASP.NET Core Web API (C#, MongoDB, Repository pattern, DI) with a React frontend and an analytics dashboard.
- Worked in a **fully air-gapped environment** under strict security constraints, with no internet access during development.
- Iterated **weekly with the stakeholder**, adapting the system to evolving requirements.
- Aligned the code with the organization's existing project structure and conventions so it would run reliably across all of their environments.

---

## 🧰 Tech Stack

| Area | Technologies |
|---|---|
| **Languages** | C#, Java 21, Python, JavaScript, TypeScript |
| **Backend** | .NET, ASP.NET Core, Entity Framework Core, Node.js (Express), FastAPI, Django, Spring Boot 3 (Spring Security, JPA/Hibernate, AOP), RESTful APIs |
| **Frontend** | React (Redux Toolkit / RTK Query), Angular, HTML5, CSS, Vite |
| **AI Development** | RAG, LangChain, LangGraph, LlamaIndex, AI Agent Development, MCP, Embeddings, Prompt Engineering, Google Gemini, Cohere |
| **Databases** | SQL Server, PostgreSQL, MongoDB, Redis, SQLite, Pinecone (vector DB) |
| **Principles & Architecture** | OOP, Design Patterns, Dependency Injection, Layered Architecture, Repository pattern, Microservices, API Gateway (YARP), BFF, Saga |
| **Security** | JWT authentication, Role-Based Access Control (RBAC), PBKDF2 / bcrypt hashing, rate limiting, CORS |
| **Messaging & Infra** | RabbitMQ, Docker / Docker Compose, Nginx (load balancing), Serilog, Seq |
| **Platforms** | AWS, Unix/Linux, Salesforce (Apex, unit testing) |
| **Tools** | GitHub, Visual Studio, VS Code, IntelliJ, Eclipse, PyCharm, Jupyter, SSMS, uv |
| **AI-assisted development** | GitHub Copilot, Claude, ChatGPT, Gemini |

---

## 🚀 Featured Projects

### 🧩 [Learn Budget Microservices](https://github.com/sara-simi-git/Learn_Budget_Microservices)
A distributed .NET system for course enrollment, built to demonstrate production-style architecture.
- 7 independently deployable services, each owning its own data store (PostgreSQL, SQL Server, MongoDB)
- **YARP API Gateway + BFF**, JWT authentication
- **Choreography-based Saga** over RabbitMQ with compensation (confirm or cancel) and Redis-backed idempotency
- Redis cache-aside, two catalog replicas behind **Nginx**, end-to-end **correlation IDs** traced in Seq
- Architecture decisions documented in ADRs
- One command to run it all: `docker compose up --build`

**Stack:** C#, .NET 9, Docker, RabbitMQ, MongoDB, PostgreSQL, SQL Server, Redis, YARP, Nginx, Serilog, Seq

### 🎟️ [Chinese Auction](https://github.com/sara-simi-git/CSharp_API-Angular-Project)
A full-stack charity-raffle platform: users buy tickets for gifts, and an admin draws a winner for each gift.
- Layered ASP.NET Core 9 API (Controller → Service → Repository), EF Core Code First with migrations, Swagger
- Security treated as a design requirement: PBKDF2 hashing with transparent re-hashing, role and ownership checks (IDOR protection), rate limiting, fail-fast secrets handling
- Angular 20 SPA with signals, route guards, and JWT and error interceptors
- Admin sales analytics and random winner selection

**Stack:** C#, ASP.NET Core 9, EF Core, SQL Server, Angular 20, TypeScript, JWT, Serilog

### 🗓️ [Meetings Management API (Spring Boot)](https://github.com/sara-simi-git/spring-boot-meetings-api)
A secured REST API for users, meetings and participants, packaged to run with one command.
- **Java 21 + Spring Boot 3**: layered architecture, DTOs with Bean Validation, JPA/Hibernate relationships
- **Stateless JWT security** with a custom filter, BCrypt hashing, and method-level **role-based access** (`@PreAuthorize`)
- AOP logging of the service layer and a global exception handler (400 / 401 / 403 / 404)
- PostgreSQL + multi-stage Docker build: `docker compose up --build`

**Stack:** Java 21, Spring Boot, Spring Security, JPA/Hibernate, PostgreSQL, Docker, Maven

### 🔎 [NotebookLM-Style Research Assistant](https://github.com/sara-simi-git/NotebookLM_Project)
A human-in-the-loop AI research tool: the user enters a topic, an agent searches the web, the user approves the sources, and a summary is generated only from the approved ones.
- Agent built with LangChain / LangGraph and Google Gemini, web search via Tavily
- FastAPI backend, React + Vite frontend

**Stack:** Python, FastAPI, LangGraph, Gemini, React, Vite

### 🌦️ [MCP Weather Agent](https://github.com/sara-simi-git/MCP_Weather_Agent)
A terminal assistant built on the **Model Context Protocol**: an LLM decides when to call weather tools exposed by separate MCP servers.
- Host that connects to multiple MCP servers over stdio, discovers their tools automatically, and namespaces them to avoid collisions
- LLM tool calling through OpenRouter, with results routed back into the conversation
- One server uses the US National Weather Service API; another drives a browser with **Playwright** to fetch Israeli forecasts

**Stack:** Python, MCP (FastMCP), OpenRouter, Playwright, uv

### 💬 [RAG Chatbot with LlamaIndex](https://github.com/sara-simi-git/Chatbot_Based_Rag_LamIndex)
A question-answering system over a custom knowledge base using Retrieval-Augmented Generation.
- Cohere models, Pinecone vector database, LlamaIndex pipeline, Gradio UI

**Stack:** Python, LlamaIndex, Cohere, Pinecone, Gradio

### 🧸 [Toy Store (MERN)](https://github.com/sara-simi-git/Node-React-Project)
An online toy store with a shopping basket and an admin catalog-management area.
- Express 5 REST API with Mongoose models, JWT middleware, bcrypt hashing
- Basket totals calculated on the server from database prices
- React 19 client with Redux Toolkit / RTK Query and a role-aware UI

**Stack:** Node.js, Express, MongoDB, React, Redux Toolkit

### ✅ [Team Tasks Manager (Django)](https://github.com/sara-simi-git/Tasks_System_Python)
A team task board: team heads create tasks, members claim them and mark them finished, with filtering by status and assignee.
- Team-scoped data, task status workflow, ModelForms, sessions, CSRF protection, migrations

**Stack:** Python, Django, SQLite

---

## 🎓 Education

**Software Engineering, Technological Certificate (MAHAT)** · 2024–2026
Beth Jacob Seminary, Jerusalem · **Average: 96**
Invested seriously in every project and received excellent feedback from lecturers.

**High School Diploma (with honors)** · 2020–2024
Beth Jacob High School, Jerusalem

---

## 💡 How I work

- **From requirements to working software:** during my practicum I iterated weekly with the stakeholder as requirements evolved.
- **Structure and security by default:** layered architecture, JWT and role-based access, hashed passwords, and documented design decisions (ADRs).
- **Easy to run:** my backend projects start with a single `docker compose up`.
- **AI, applied:** RAG, agents and MCP integrations built as working applications, with a human approval step where it matters.

---

📫 **Let's talk:** [sarasimihaloua@gmail.com]
