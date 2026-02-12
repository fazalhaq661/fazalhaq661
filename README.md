<h1 align="center">Hi 👋, I'm Fazalhaq Fazel</h1>
<h3 align="center">Fintech Backend Engineer | Kotlin | Spring Boot | ISO8583</h3>

---

## 🚀 About Me

- 💳 Building ISO8583 financial messaging systems
- ⚡ Reactive backend engineer (Project Reactor - Mono/Flux)
- 🏦 Working on OTP, USSD, Card & Payment integrations
- 🐳 Dockerized microservices architecture
- 🗄 PostgreSQL & transaction-safe systems
- 🌍 Based in Afghanistan

---

## 🛠 Tech Stack

### Backend
![Kotlin](https://img.shields.io/badge/Kotlin-1.9-blue)
![Java](https://img.shields.io/badge/Java-21-orange)
![Spring Boot](https://img.shields.io/badge/SpringBoot-4-green)
![Reactor](https://img.shields.io/badge/Reactor-Reactive-purple)

### Database & Infra
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-15-blue)
![Docker](https://img.shields.io/badge/Docker-Containerized-blue)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-Async-orange)

---

## 💳 Fintech Focus

- ISO8583 Client & Server implementation
- Custom dialect handling (SVFE_H2H)
- LLVAR / LLLVAR field processing
- ASCII TLV (Field 48)
- Bitmap parsing & financial message validation
- High reliability transaction systems

---

## 📈 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=fazalhaq661&show_icons=true&theme=radical" />
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=fazalhaq661&layout=compact&theme=radical" />
</p>

---

## 🔄 Contribution Activity

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=fazalhaq661&theme=react-dark" />
</p>

---

## 🏦 Banking System Architecture

```mermaid
flowchart LR
    A[USSD / POS / ATM] --> B[Switch Layer]
    B --> C[ISO8583 Client]
    C --> D[APS / External Switch]
    C --> E[Core Banking]
    E --> F[PostgreSQL DB]
    C --> G[OTP Service]
    G --> H[SMS / Email Gateway]
```

### Architecture Focus

- 🔁 Async handling with RabbitMQ
- 🧠 Dialect-based ISO8583 parsing
- 🧩 Modular Spring Boot multi-module design
- 🐳 Fully containerized deployment
- 📊 Logging & transaction tracing

---

## 🔐 Secure by Design

Security is not optional in financial systems.

✔️ Input validation at ISO field level  
✔️ Strict LLVAR / LLLVAR length verification  
✔️ Transaction integrity checks  
✔️ Idempotent request handling  
✔️ Sensitive data masking in logs  
✔️ Database transaction management  
✔️ Docker isolation  

---

## 🧪 Testing & Quality Engineering

I design systems that are testable and production-ready.

### Integration Testing
- 🐳 Testcontainers with PostgreSQL
- 🔄 Real database testing (no fake mocks for critical flows)
- 📦 Multi-module integration tests

### Unit Testing
- MockBean isolation
- ISO message validation tests
- STAN uniqueness verification

### Example Stack
- JUnit 5
- SpringBootTest
- Testcontainers
- Kotlin test

---

## 💳 ISO8583 Expertise

- Bitmap parsing & validation
- LLVAR / LLLVAR encoding
- ASCII TLV (Field 48)
- Custom dialect (SVFE_H2H)
- MessageFactory usage
- Financial transaction flow design

---

## 🔥 Current Goals

- Master advanced Spring Boot internals
- Improve ISO8583 performance & resilience
- Contribute to fintech open-source
- Build production-grade financial infrastructure

---

## 📫 Connect With Me

- LinkedIn: (add link)
- Email: (optional)

---

⭐️ Always building secure and scalable financial systems.
