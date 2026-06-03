# Hola, soy Jhostyn Rosales 👋

### Desarrollador de Software Junior | Fullstack & Multiplataforma

Soy una persona proactiva, con gran capacidad de aprendizaje y motivada por seguir creciendo profesionalmente dentro del sector tecnológico. Mi enfoque principal está en el desarrollo web moderno, los sistemas de gestión, la integración de Inteligencia Artificial y el desarrollo multiplataforma.

---

### Sobre Mí

- 💻 Actualmente trabajando como **Desarrollador Fullstack (Prácticas)** en *Palmar Logistic*.
- 🎓 Estudiando el **Grado Superior en Desarrollo de Aplicaciones Web (DAW)** en el Colegio Valle del Miro.
- 📜 Técnico Superior en **Desarrollo de Aplicaciones Multiplataforma (DAM)** (Primer curso completado con media de 8 en Colegio Cooperativa Lagomar).
- 📍 Ubicación: Valdemoro, Madrid, España.
- 🗣️ Idiomas: Español (Nativo), Inglés (B2 — Cambridge FCE), Catalán (Básico).

---

### Tecnologías y Competencias

| Área | Tecnologías |
| :--- | :--- |
| **Frontend** | Angular, HTML5, CSS3, JavaScript, TypeScript, Bootstrap |
| **Backend** | Java (Spring Boot, Spring Data, Spring Security, MVC), Python, PHP, API REST |
| **Bases de Datos** | MySQL, PostgreSQL, ObjectDB |
| **Mensajería & DevOps** | RabbitMQ, Docker, Git, GitHub, Linux, Postman, Maven |

---

### Proyectos Destacados

#### [`petlogilink-api`](https://github.com/JhostynRosales/petlogilink-api) — Plataforma Fullstack de Automatización Logística

Monorepo que integra un Backend en **Java 17 / Spring Boot 3** con un Frontend en **Angular 18**, diseñado para orquestar la logística y sincronización de inventarios de un e-commerce multicanal.

| Backend | Frontend |
| :--- | :--- |
| API REST para ingesta de pedidos (webhooks Amazon/Miravia) | Dashboard con gráficos Chart.js por marketplace |
| Motor `@Scheduled` de sincronización de stock con márgenes dinámicos | Tabla interactiva de inventario con filtros y edición inline |
| Servicio de automatización SEO basado en reglas | Terminal de logs en tiempo real |
| Repositorios In-Memory (sin dependencias externas) | Sistema de login con guards de ruta |

**Stack:** Java 17 · Spring Boot 3 · Angular 18 · TypeScript · Chart.js · Maven

---

#### [`notification-microservice`](https://github.com/JhostynRosales/notification-microservice) — Arquitectura Orientada a Eventos

Microservicio independiente que consume eventos desde **RabbitMQ** y envía correos electrónicos transaccionales de forma asíncrona, desacoplando las notificaciones de la API principal.

```
API Principal  ──▶  RabbitMQ (Exchange)  ──▶  Notification Service  ──▶  Email SMTP
  (publish)          order.notifications       @RabbitListener            Thymeleaf HTML
                         .queue
```

- Configuración programática de Exchange, Queue y Bindings con Spring AMQP.
- Plantillas HTML profesionales renderizadas con Thymeleaf (confirmación de pedido).
- Entorno contenerizado con Docker Compose (RabbitMQ + Management UI).

**Stack:** Java 17 · Spring Boot 3 · RabbitMQ · Spring Mail · Thymeleaf · Docker

---

### Experiencia Profesional

**Desarrollador Fullstack (Prácticas) — Palmar Logistic** *(Marzo 2026 — Junio 2026)*

- **Integración de Sistemas:** Consumo y desarrollo de APIs JSON-REST para comunicación con transportistas externos (Correos Express) y control de flujos de tracking en tiempo real.
- **Automatización con IA:** Implementación de scripts en Python integrando modelos de lenguaje (LLMs) para automatizar la generación de contenido y metadatos SEO comerciales.
- **Lógica de Negocio (E-commerce):** Desarrollo de módulos a medida en PHP (PrestaShop) para gestión dinámica de stocks, tareas programadas (Crons) y motores de asignación de paquetería por reglas de peso/dimensiones.

---

### Certificaciones

- 🎓 **Certificación de Desarrollo en Angular** — SoloLearn (2026)

---

### Contacto

Si quieres hablar sobre desarrollo de software, colaborar en algún proyecto o conocer más sobre mi perfil, no dudes en contactarme.

- 📧 **Email:** [jhxavier@gmail.com](mailto:jhxavier@gmail.com)
- 📍 **Localización:** Valdemoro, Madrid

