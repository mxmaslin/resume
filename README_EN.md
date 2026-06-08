# Maslin Maxim Mikhailovich

**Python Backend Developer · 7+ years of commercial experience (Django, FastAPI, PostgreSQL)**

Male, 49 years old, born May 30, 1977

**Email:** [zapzarap@yandex.ru](mailto:zapzarap@yandex.ru) — preferred contact  
**MAX:** [max.ru/u/f9LHodD0cOJo6LfPoZriBTPNxYKVPwiMxcGpGqTTewSp5mwOzS946NvX8Ok](https://max.ru/u/f9LHodD0cOJo6LfPoZriBTPNxYKVPwiMxcGpGqTTewSp5mwOzS946NvX8Ok)  
**Telegram:** [@dr_blumenau](https://t.me/dr_blumenau)  
**GitHub:** [github.com/mxmaslin](https://github.com/mxmaslin)

**Location:** Moscow, Shchukinskaya metro  
**Citizenship:** Russia; authorized to work in Belarus and Russia  
**Relocation:** Russia; open to business trips

---

## Desired position

**Python Backend Developer (Django, FastAPI, PostgreSQL)**

**Specializations:** programmer, developer  
**Employment type:** full-time  
**Work format:** remote, hybrid

---

## Work experience — 7 years 2 months

*Commercial Python development. Developer documentation (Waves) — listed separately below.*

### April 2026 — present · 2 months

**[Fooddvor](https://fooddvor.ru)** · Moscow · e-commerce

**Python Backend Developer (FastAPI)**

**Product:** WooCommerce online store, Telegram order notifications.

**Stack:** Python 3, FastAPI, Redis, Docker, GitLab CI, Pytest, REST API, HMAC, WordPress/WooCommerce.

- Designed **fooddvor-tg-relay** microservice (FastAPI): HMAC, idempotency, Redis/SQS queue, worker → Telegram Bot API.
- Moved notification delivery off the checkout critical path; eliminated checkout blocking when Telegram API is unavailable.
- Integrated WordPress: non-blocking call (2s timeout), direct API fallback.
- Set up **GitLab CI** for the service and deployment.

---

### February 2026 — March 2026 · 2 months

**[Open Solutions](https://osinit.com)** · Penza · compliance / GRC

**Python Backend Developer (Django, DRF)**

**Product:** GRC platform — action plans, workflow builder.

**Stack:** Python 3, Django, Django REST Framework, PostgreSQL, Redis, Celery, RabbitMQ, Docker, GitLab CI, Pytest, Swagger/OpenAPI.

- Built **REST API** for plan action assignees (CRUD, company/group/user permissions), Pytest integration tests.
- Implemented CRUD for plan/action status transitions in workflow (pre-/post-functions, validations, service layer).
- Restored **Swagger/OpenAPI** (drf-spectacular), stabilized GitLab CI.

---

### August 2024 — December 2025 · 1 year 5 months

**[Big Three](https://big3.ru)** · Moscow · B3 low-code platform

**Python Backend Developer (Django, DRF)**

**Stack:** Python 3, Django, DRF, PostgreSQL, Redis, Celery, RabbitMQ, Docker Swarm, GitLab, Pytest, raw SQL.

- Implemented `get_depth_level` for hierarchical directories: depth in **one SQL query**, descendant updates in two (recursive **CTEs**).
- Optimized critical queries (**EXPLAIN ANALYZE**), reduced hierarchy operation time.
- Fixed “zombie login” on Gostech: **Keycloak** end-session + redirect chain.
- Restored mail delivery (Celery LOW→MEDIUM queue) and profile defect in the low-code layer.
- Refactored legacy B3 code; Pytest coverage for critical changes.

---

### April 2023 — August 2024 · 1 year 5 months

**[Samolet Development](https://samoletgroup.ru)** · Moscow

**Python Backend Developer (Django, FastAPI)**

**Stack:** Python 3, Django, FastAPI, PostgreSQL, Redis, **Apache Kafka**, Celery, Docker, **Kubernetes**, GitLab, Pytest, **OAuth2**, django-guardian, Grafana.

- Deployed **2FA** for OAuth2 provider S.ID (15+ apps, 8000+ employees).
- Forced logout: token revoke + Redis sessions on LDAP events.
- Built **JWT proxy** for ECM (−67% access approval time).
- Kafka GLPI adapter (50,000+ evt/min); **RBAC** in kafka-manager (guardian).
- API documentation (ITHub/DockHub), OAuth2 2nd-line support.

---

### November 2021 — November 2022 · 1 year 1 month

**[Globant](https://globant.com)** · Ubisoft (Flare) · Minsk

**Python Backend Developer** — Python 2→3 migration (232 modules), Twisted, Azure AD, Pytest.

---

### March 2020 — October 2021 · 1 year 8 months

**Lendsbay** · [lendsbay.com](https://lendsbay.com) · Moscow · fintech / P2P lending

**Python Backend Developer** — **AIOHTTP**, ~**10,000 RPS** to PostgreSQL, 100,000+ users; credit bureau XML parser; −**12.3%** churn (penalty forgiveness).

---

### 2017 — 2020 · 3 years

**[Waves](https://waves.tech)** · remote · fintech / blockchain platform

**Technical Writer (developer documentation)**

Focus: integration developer docs and cryptocurrency exchange **REST API**.

- Wrote and maintained **developer documentation** in **English**: guides, reference, integration scenarios.
- Documented exchange **REST API**: endpoints, data models, errors, request examples.
- Aligned API doc structure with backend teams; unified terminology for external developers.

*After this period — commercial Python backend development (from 2020).*

---

### March 2017 — December 2017 · 10 months

**[FinTech](https://www.fintech.ru)** · Moscow — Junior Python Backend Developer (Django, DRF).

---

### September 2016 — March 2017 · 7 months

Internship (Corona Travel), Django freelance — forum engine, rental accounting, landing pages.

---

## Education

**MSU**, Faculty of Philosophy, 1998

---

## Professional development

**2025** — Advanced Django 5 · **2024** — SQL Academy; Async Python · **2020** — Python Web Developer

---

## Skills

**Languages:** Russian — native; English — B1 (technical documentation; Waves — EN)

**Key skills:**  
Python, Django Framework, Django REST Framework, FastAPI, PostgreSQL, SQL, REST API, Redis, Celery, Docker, Git, GitLab, Pytest, Linux, Apache Kafka, OAuth, RabbitMQ, Swagger, SQLAlchemy, JavaScript, Kubernetes, Keycloak

---

## Additional information

### References

**Samolet Development** — Alexander Trubnikov (Head of Centralized IT Services)

### About me

**Python Backend Developer** with **7+ years** of commercial experience: **Django/DRF**, **FastAPI**, **PostgreSQL**, **REST API**, **Celery**, **Redis**, **Docker**, **GitLab CI**, **Pytest**. Strengths — integrations (**OAuth2**, **Kafka**), hierarchies and **SQL/CTEs**, GRC/workflow, e-commerce.

Previously **3 years** writing **developer documentation** and **REST API** docs in English ([Waves](https://waves.tech)) — I design clear APIs and **OpenAPI/Swagger**. Frontend (JavaScript, Vue) for fullstack tasks when needed.

| Area | Technologies |
| --- | --- |
| Backend | Django/DRF, FastAPI, AIOHTTP, Pyramid |
| Data | PostgreSQL, Redis, SQLAlchemy, recursive CTEs |
| Queues | Celery, RabbitMQ, Apache Kafka |
| DevOps | Docker, GitLab CI, Kubernetes (basics) |
| Security | OAuth2, JWT, Keycloak, HMAC, RBAC (guardian) |

*Updated: June 8, 2026*
