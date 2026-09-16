# Hi, I'm Sebastián 👋

**Final-year Software Engineering student** at Universidad Rey Juan Carlos (Madrid, Spain).
I build backends in Java and Spring, front ends in React — and I like being the one who takes a project all the way to a real server with a real domain and real users.

🔎 **Looking for a backend / full-stack internship starting January 2027.**

---

## 🚀 Naruart — my main project, live in production

**[naruart.com](https://naruart.com)** · Online catalogue for a professional illustrator. Designed, built and deployed **entirely by me**, from the data model to the firewall.

| | |
|---|---|
| **Backend** | Spring Boot 4 · Java 25 · PostgreSQL 18 · Spring Data JPA · MapStruct · Flyway |
| **Frontend** | React 19 · React Router (framework mode, SSR) · TypeScript · Tailwind CSS · Zustand |
| **Security** | Spring Security 7 · JWT in memory + HttpOnly refresh cookie · TOTP MFA · brute-force lockout per account and per IP · checkout idempotency · per-request nonce CSP |
| **Infra** | Docker Compose (4 containers) · Caddy reverse proxy with automatic TLS · Cloudflare (DNS, WAF, rate limiting, R2 object storage) · UFW on the `DOCKER-USER` chain · Hetzner VPS |
| **Operations** | Daily automated backups replicated off-site — **and a restore drill I actually ran end to end** · Sentry error monitoring · GDPR legal texts and signed data-processing agreements |

The e-commerce layer is fully built and currently switched off behind a feature flag, as a product decision — it comes back with one environment variable.

> 🔒 The repository is private. **Happy to walk through the code or the architecture on request** — just reach out.

---

## 🛠️ What I work with

![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=flat-square&logo=cloudflare&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![Selenium](https://img.shields.io/badge/Selenium-43B02A?style=flat-square&logo=selenium&logoColor=white)

**Also:** JUnit · Mockito · RestAssured · JaCoCo · Artillery · Maven · Node.js/Express · Figma · Jira · UML · Scrum · AI-assisted development (Claude Code)

---

## 📚 University projects

| Project | What it was | What I did |
|---|---|---|
| **[TicketHub](https://github.com/CodeURJC-DAW-2025-26/practica-daw-2025-26-grupo-10)** | Event ticketing platform — Spring Boot, MySQL, React, TypeScript, Docker. Team of 5. | Co-owned the Spring Security layer; worked across the backend (entities, services, REST controllers, DTOs) and built the purchase flow, product page with stock handling and admin profile editing. Solved the lost-update problem on concurrent profile edits with JPA optimistic locking (`@Version`). |
| **Software Quality Assurance — Nitflex** | Testing and CI/CD on a Spring Boot app deployed to Azure. Team of 4. | Unit, integration, REST and end-to-end tests; designed the GitHub Actions CI workflow that runs the suites on every push to working branches; load testing with Artillery against p95 targets. |
| **Software Evolution — SpotBugs** | Refactoring a real open-source static analysis tool with no documentation. | Migrated Java 8 → Java 21, added JSON export of results to both the CLI and the GUI, documented the architecture before and after in UML. |
| **[Software Design & Architecture](https://github.com/Gabim23/Software-Arquitecture)** | Monolith → microservices design for a parcel transport company. Team of 6, four iterations. | API Gateway (Kong), Circuit Breaker, State pattern for order phases, Strategy for route optimisation, external payment gateway — all modelled in UML. |
| **Software Processes** | Scrum practice on a programming-learning web app. | Rotated weekly through developer, Scrum Master and Product Owner. User stories, estimation, burndown charts, retrospectives on Jira and Miro. |
| **[Human-Computer Interaction](https://github.com/ikramej/IPO_2024-25)** | Interface prototyping and user research. | Figma prototype, implementation in HTML/JS, evaluation with real users through questionnaires. |

---

## 📫 Get in touch

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/sebastian-silvera-546212234/)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:silverasebastian82@gmail.com)
[![Website](https://img.shields.io/badge/naruart.com-111111?style=flat-square&logo=googlechrome&logoColor=white)](https://naruart.com)

📍 Madrid, Spain · open to relocation and remote work
