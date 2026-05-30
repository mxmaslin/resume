# Maslin Maxim Mikhailovich

Male, 49 years old, born May 30, 1977

**Email:** [zapzarap@yandex.ru](mailto:zapzarap@yandex.ru) — preferred contact method  
**MAX:** [max.ru/u/f9LHodD0cOJo6LfPoZriBTPNxYKVPwiMxcGpGqTTewSp5mwOzS946NvX8Ok](https://max.ru/u/f9LHodD0cOJo6LfPoZriBTPNxYKVPwiMxcGpGqTTewSp5mwOzS946NvX8Ok)  
**Telegram:** [@dr_blumenau](https://t.me/dr_blumenau)  
**GitHub:** [github.com/mxmaslin](https://github.com/mxmaslin)

**Location:** Moscow, Shchukinskaya metro  
**Citizenship:** Russia; authorized to work in Belarus and Russia  
**Relocation:** Russia; open to business trips

---

## Desired position

**Senior Developer (AI, Django, FastAPI)**

**Specializations:** programmer, developer  
**Employment type:** full-time  
**Work format:** remote, hybrid  
**Commute preference:** not important

---

## Work experience — 7 years 2 months

### April 2026 — present · 2 months

**[Fooddvor](https://fooddvor.ru)** · Moscow  
Food products · fresh vegetables and fruits (promotion, wholesale)

**Senior Developer (Python/PHP)**

**Product:** WooCommerce online store, Telegram chatbot.

**Stack:** Python 3, FastAPI, Redis, Docker, GitLab CI, Pytest, WordPress/WooCommerce, HMAC.

**Responsibilities:**

- Writing program code
- Fixing identified bugs
- Developing and maintaining the server-side application
- Analyzing root causes of bugs to prevent recurrence
- Integrating software modules and assembling application components
- Developing and maintaining the client-side web application
- Developing and integrating APIs for data exchange between systems and applications
- Version control, tracking and managing code changes
- Managing the development team
- Reporting on development progress

**Achievements:**

- Built scalable asynchronous Telegram notification delivery when hosting in Russia has unstable access to api.telegram.org.
- Moved notifications off the critical order path.
- Eliminated checkout blocking risk from synchronous API calls.
- Designed the fooddvor-tg-relay microservice (FastAPI, clean architecture): HMAC, idempotency, Redis/SQS queue, worker → Telegram Bot API.
- Integrated WordPress: non-blocking send (2s timeout), fallback to direct API.
- Implemented GitLab CI.

---

### February 2026 — March 2026 · 2 months

**[Open Solutions](https://osinit.com)** · Penza  
Information technology, system integration, internet · software development

**Senior Python Backend Developer**

**Product:** compliance platform, action plans module and workflow constructor.

**Stack:** Python 3, Django, DRF, drf-spectacular, PostgreSQL, Redis, Celery, RabbitMQ, Docker, GitLab CI, Pytest.

**Responsibilities:**

- Writing program code
- Fixing identified bugs
- Developing and maintaining the server-side application
- Reporting on development progress
- Analyzing root causes of bugs to prevent recurrence
- Integrating software modules and assembling application components
- Developing and maintaining the client-side web application
- Formatting code per customer requirements and industry/company standards
- Reviewing code written by other developers
- Version control, tracking and managing code changes
- Formalizing and algorithmizing tasks before implementation
- Developing and integrating APIs for data exchange between systems and applications

**Achievements:**

- Built REST API for action plan execution responsibles (CRUD, permissions by company/groups/users); integration tests.
- Implemented CRUD for plan and action status transitions in workflow (pre-/post-functions, validations, service layer).
- Extended status API, restored Swagger/OpenAPI, stabilized GitLab CI.

---

### August 2024 — December 2025 · 1 year 5 months

**[Big3](https://big3.ru)** · Moscow  
Information technology, system integration, internet · software development · enterprise integration, IT consulting

**Senior Python Backend Developer**

**Product:** B3 low-code platform for business and government.

**Stack:** Python 3, Django, DRF, Pytest, PostgreSQL, Redis, Celery, RabbitMQ, Docker Swarm, GitLab.

- Developed new features and integrations on B3 (customized Django); optimized raw SQL, recursive CTEs; debugged platform and applications.
- Implemented get_depth_level for hierarchical directory: depth in one SQL query, descendant updates in two.
- Optimized SQL with recursive CTEs, reducing critical operation time (EXPLAIN ANALYZE measurements).
- Fixed “zombie login” on GoTech: Keycloak end-session + redirect chain for frontend.
- Restored email delivery (Celery queue LOW→MEDIUM) and profile defect (root cause in low-code layer).
- Refactored legacy B3; started using Cursor in development.

**Period takeaway:** hands-on recursive CTEs in raw SQL and Django ORM. AI tools in development: Copilot, Windscribe; settled on Cursor with MCP, skills, rules and token consumption optimization as the main assistant.

---

### April 2023 — August 2024 · 1 year 5 months

**[Samolet Development](https://samoletgroup.ru)** · Moscow  
Financial sector · construction, real estate, development

**Senior Python Backend Developer**

**Product:** corporate IT services for a major real estate developer.

**Stack:** Python 3, Django, FastAPI, PostgreSQL, Redis, Kafka, Celery, Docker, Pytest, Grafana, K8s, GitLab, django-guardian.

- 2FA for OAuth2 provider S.ID (15+ applications, 8000+ employees); social login with mandatory 2FA.
- Forced logout: token revocation + Redis sessions on LDAP events.
- JWT proxy for ECM (−67% access approval time, ticket system).
- Kafka: GLPI adapter, 50,000+ evt/min, latency <12 ms; RBAC in kafka-manager (guardian).
- ITHub/DockHub documentation, Grafana, 2nd-line OAuth2 support, Pytest on refactoring.

**Period takeaway:** FastAPI, Apache Kafka, Kubernetes, Prometheus, Grafana; OAuth2 protocol implementation.

---

### November 2021 — November 2022 · 1 year 1 month

**[Globant](https://globant.com)** · Minsk · Ubisoft (Flare)  
Information technology, system integration, internet · software development

**Python Backend Developer**

**Product:** Flare, Ubisoft internal tool for visualizing manual QA defects in video games.

**Stack:** Python 2/3, Twisted, PostgreSQL, Redis, Pytest, GitLab.

- Completed Python 2 → 3 migration (232 modules), preserving API.
- Implemented Microsoft Azure AD integration.
- High test coverage on critical modules (Pytest).

**Period takeaway:** deep practical experience with Twisted; cloud identity provider integration (Microsoft Azure).

---

### March 2020 — October 2021 · 1 year 8 months

**Lendsbay LLC** · [lendsbay.com](https://lendsbay.com) · Moscow  
Financial sector · financial and credit intermediation

**Python Backend Developer**

**Product:** P2P lending platform.

**Stack:** Python 3, AIOHTTP, Pyramid, SQLAlchemy, Alembic, PostgreSQL, Celery, Redis, RabbitMQ, Docker, GitLab.

Developed the server side of the high-load Lendsbay mobile app at ~10,000 RPS to the database (source: pg_stat_database), serving 100,000+ users.

**Business logic and integrations:**

- Built an XML parser for credit bureau exports, improving Lendsbay automated scoring accuracy.
- Implemented periodic notifications to collection agencies about overdue user payments.
- Designed an automatic penalty waiver algorithm with flexible conditions, reducing churn by 12.3% (per business analytics).

**UI and data visualization:**

- Built interactive analytics in the admin panel from scratch: d3.js dashboards with complex filtering for key business metrics.
- On own initiative, built a functional prototype of the client web UI to validate UX hypotheses.

**Period takeaway:** AIOHTTP, Pyramid, SQLAlchemy ORM, Alembic migrations.

---

### March 2017 — December 2017 · 10 months

**[FinTech, JSC](https://www.fintech.ru)** · Moscow  
Information technology, system integration, internet · enterprise integration, IT consulting

**Junior Python Backend Developer**

**Product:** web service for administrative resource accounting.

**Stack:** Python 2, Django, Django REST Framework (DRF), PostgreSQL, Git.

- Developed and maintained backend on Django and DRF.
- Built REST API for frontend and integration with adjacent systems.
- Designed data models; ensured PostgreSQL integrity and efficiency.
- Developed business logic for administrative resource management and accounting.

**Period takeaway:** Django REST Framework and PostgreSQL in an enterprise project.

---

### September 2016 — March 2017 · 7 months

**Intern / Python Backend Developer** · Moscow

**Internship at Corona Travel:**

- Built a forum engine on Django from scratch: posting and commenting.
- Completed entry-level tasks, strengthening commercial development and teamwork skills.

**Freelance projects:**

- Rental property accounting system on Django: property database, payment calculation, reporting.
- Corporate landing page for a financial organization with responsive Bootstrap design and jQuery interactions.

**Period takeaway:** Django backend, user interfaces with Bootstrap and jQuery.

**Tech stack:** Python 3, Django, Bootstrap, jQuery, Git.

---

## Education

**Higher education**, 1998  
**Lomonosov Moscow State University**, Moscow  
Faculty of Philosophy, teacher training

---

## Professional development, courses

- **2015** — An Introduction to Interactive Programming in Python, Rice University, Programming
- **2012** — Learn to Program: The Fundamentals, University of Toronto, Programming

---

## Digital certificates

| Year | Certificate |
|------|-------------|
| 2025 | Advanced Django 5 for Professionals |
| 2024 | SQL Academy |
| 2024 | Asynchronous Python |
| 2021 | Interactive SQL Trainer |
| 2020 | Python Web Developer |
| 2020 | SQL Course Trainer |
| 2019 | SQL Basics |
| 2019 | Building Web Services in Python |
| 2018 | OOP and Design Patterns in Python |
| 2017 | 6.00.1x: Introduction to Computer Science and Programming Using Python |
| 2017 | Introduction to Databases |
| 2017 | Web Technologies |
| 2017 | Programming in Python |
| 2016 | Capstone: Retrieving, Processing, and Visualizing Data with Python |
| 2016 | Principles of Computing (Part 1) |
| 2016 | Python: Basics and Applications |
| 2016 | Using Databases with Python |
| 2015 | Python Data Structures |
| 2015 | Using Python to Access Web Data |
| 2014 | Introduction to Linux |
| 2014 | Programming in Python |
| 2014 | Creating Web Interfaces with HTML and CSS |

---

## Skills

**Languages:** Russian — native; English — B1 — intermediate

**Skills:** Python, Git, SQL, PostgreSQL, Django Rest Framework, Redis, Celery, Docker, Linux, Kubernetes, SQLAlchemy, FastAPI, Pytest, AIOHTTP, Grafana, RabbitMQ, Django Framework, REST API, Prometheus, JavaScript, Apache Kafka, OAuth, Ollama, MCP, Prompt engineering, GitLab, Cursor, Bash, LLM, Swagger

---

## Additional information

### References

**Samolet Development** — Alexander Trubnikov (Head of Centralized IT Services Department)

### About me

**Professional profile**

Python backend developer with 7 years of commercial experience. I specialize in reliable scalable services, complex integrations, and high-load systems — from API design to metrics and CI/CD. Experience in OAuth2/security, Kafka, Django platforms, GRC/workflow, and e-commerce.

Before development, I spent 8+ years as a technical writer — which helps me design clear systems, document APIs, and use LLM/AI (Cursor) effectively. I can work with frontend (JavaScript, Vue) for fullstack tasks when needed.

**Core competencies**

- **Service development:** Django/DRF, FastAPI, AIOHTTP, Twisted; event-driven integrations, OpenAPI.
- **Security:** OAuth2, OIDC, 2FA, JWT, Keycloak, HMAC, RBAC (including django-guardian).
- **Data and infrastructure:** PostgreSQL, recursive CTEs, Kafka (high-load), Celery, Redis, Docker/K8s, Grafana/Prometheus.
- **Legacy and quality:** Python 2→3 migration, refactoring, Pytest, GitLab CI/CD.
- **Tools:** Cursor, MCP, documentation as code (DockHub/ITHub).

**Technology stack**

| Category | Technologies |
| --- | --- |
| Languages | Python 2/3, JavaScript (ES6+), SQL, PHP (WP integrations) |
| Backend | Django/DRF, FastAPI, AIOHTTP, Twisted, Pyramid |
| Databases & ORM | PostgreSQL, Redis, SQLAlchemy, Alembic |
| Queues | Apache Kafka, RabbitMQ, Celery |
| DevOps | Docker, Docker Compose, Kubernetes, Docker Swarm, Git/GitLab, bash |
| Observability | Prometheus, Grafana |
| Other | REST API, OpenAPI/Swagger, OAuth2, JWT, Keycloak, Linux, WooCommerce |

*Updated: May 30, 2026*
