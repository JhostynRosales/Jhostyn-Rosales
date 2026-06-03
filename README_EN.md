# Hey, I'm Jhostyn Rosales 👋

### Junior Software Developer | Fullstack & Cross-Platform

*🇪🇸 [Leer en Español](./README.md)*

Welcome to my GitHub profile! I'm a proactive and fast-learning developer driven by professional growth in the tech industry. My main focus is on modern web development, management systems, AI integration and cross-platform applications.

---

### About Me

- 💻 Currently working as a **Fullstack Developer (Internship)** at *Palmar Logistic*.
- 🎓 Studying **Advanced Diploma in Web Application Development (DAW)** at Colegio Valle del Miro.
- 📜 **Advanced Diploma in Cross-Platform Application Development (DAM)** (First year completed with an average grade of 8/10 at Colegio Cooperativa Lagomar).
- 📍 Based in Valdemoro, Madrid, Spain.
- 🗣️ Languages: Spanish (Native), English (B2 — Cambridge FCE), Catalan (Basic).

---

### Tech Stack

| Area | Technologies |
| :--- | :--- |
| **Frontend** | Angular, HTML5, CSS3, JavaScript, TypeScript, Bootstrap |
| **Backend** | Java (Spring Boot, Spring Data, Spring Security, MVC), Python, PHP, REST APIs |
| **Databases** | MySQL, PostgreSQL, ObjectDB |
| **Messaging & DevOps** | RabbitMQ, Docker, Git, GitHub, Linux, Postman, Maven |

---

### Featured Projects

#### [`petlogilink-api`](https://github.com/JhostynRosales/petlogilink-api) — Fullstack Logistics Automation Platform

Monorepo integrating a **Java 17 / Spring Boot 3** backend with an **Angular 18** frontend, designed to orchestrate logistics and inventory synchronization for a multichannel e-commerce system.

| Backend | Frontend |
| :--- | :--- |
| REST API for order ingestion (Amazon/Miravia webhooks) | Dashboard with Chart.js graphs by marketplace |
| `@Scheduled` stock sync engine with dynamic margins | Interactive inventory table with filters and inline editing |
| Rule-based SEO automation service | Real-time event log terminal |
| In-Memory repositories (zero external dependencies) | Login system with route guards |

**Stack:** Java 17 · Spring Boot 3 · Angular 18 · TypeScript · Chart.js · Maven

---

#### [`notification-microservice`](https://github.com/JhostynRosales/notification-microservice) — Event-Driven Architecture

Standalone microservice that consumes events from **RabbitMQ** and sends transactional emails asynchronously, decoupling notifications from the main API.

```
Main API  ──▶  RabbitMQ (Exchange)  ──▶  Notification Service  ──▶  Email SMTP
 (publish)      order.notifications       @RabbitListener            Thymeleaf HTML
                    .queue
```

- Programmatic Exchange, Queue and Bindings configuration with Spring AMQP.
- Professional HTML email templates rendered with Thymeleaf (order confirmation).
- Containerized environment with Docker Compose (RabbitMQ + Management UI).

**Stack:** Java 17 · Spring Boot 3 · RabbitMQ · Spring Mail · Thymeleaf · Docker

---

### Professional Experience

**Fullstack Developer (Internship) — Palmar Logistic** *(March 2026 — June 2026)*

- **Systems Integration:** Consuming and developing JSON-REST APIs for communication with external carriers (Correos Express) and real-time tracking flow management.
- **AI Automation:** Implementing Python scripts integrating Large Language Models (LLMs) to automate commercial SEO content and metadata generation.
- **Business Logic (E-commerce):** Developing custom PHP modules (PrestaShop) for dynamic stock management, scheduled tasks (Crons) and parcel assignment engines based on weight/dimension rules.

---

### Certifications

- 🎓 **Angular Development Certification** — SoloLearn (2026)

---

### Contact

If you'd like to talk about software development, collaborate on a project or learn more about my background, feel free to reach out.

- 📧 **Email:** [jhxavier@gmail.com](mailto:jhxavier@gmail.com)
- 📍 **Location:** Valdemoro, Madrid, Spain
