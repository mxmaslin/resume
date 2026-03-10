# Maslin Maxim Mikhailovich

## `Python Backend Developer | Senior`

**Contact**: zapzarap@yandex.ru | Telegram: [@dr_blumenau](https://t.me/dr_blumenau)

[Download PDF](https://github.com/mxmaslin/resume/blob/main/Maslin_backend_RU.pdf) (Size: 56 KB)

[Русская версия](https://github.com/mxmaslin/resume/blob/main/README.md)

## Professional Profile

Python Backend Developer with 6+ years of commercial experience. Specializes in building reliable, scalable services, complex integrations, and high‑load systems — from architecture design to metric configuration and analytics. Prior to development, spent 8+ years as a technical writer, which cultivated skills in working with complex concepts, designing clear systems, and using LLMs effectively. Ready to act as a Fullstack Engineer (Senior Backend / Middle Frontend), compensating for a dedicated React/Vue developer through JavaScript proficiency, the use of agentic Cursor IDE, and strong prompt engineering skills.

## Core Competencies

- **Service Development**: Full‑cycle development with Django/DRF, asynchronous frameworks (FastAPI, AIOHTTP, Twisted).
- **Security & Authentication**: Expertise in OAuth2, 2FA, JWT, proxy authorization, Role Based Access Control.
- **Data & Infrastructure**: SQL optimization (recursive CTEs), Apache Kafka (high‑load producers/consumers), ETL, containerization (Docker, K8s), monitoring (Prometheus), dashboards (Grafana).
- **Legacy Code**: Refactoring, migration from Python 2 to 3, test coverage.
- **Tools & Approaches**: Pytest, GitLab CI/CD, using AI assistants (Cursor IDE) to accelerate development.

## Tech Stack

| Category               | Technologies                                                  |
| ----------------------- | ----------------------------------------------------------- |
| Languages               | Python 2/3, JavaScript (ES6+), SQL                          |
| Backend Frameworks      | Django/DRF, FastAPI, AIOHTTP, Twisted, Pyramid              |
| Databases & ORM         | PostgreSQL, Redis, SQLAlchemy, Alembic, peewee ORM          |
| Queues & Async          | Apache Kafka, RabbitMQ, Celery                              |
| Infrastructure & DevOps | Docker, Kubernetes, Docker Swarm, Git/GitLab, Prometheus, Grafana, Ansible, bash |
| Testing                 | Pytest, unittest                                            |
| Other                   | REST API, OAuth2, JWT, Linux, HTML/CSS, JavaScript, Vue     |

## Work Experience

### [Big3](https://big3.ru)

*The company develops a universal low‑code application platform for business and government, as well as solutions built on it*.

**Period**: August 2024 – December 2025 (1 year 5 months).

Tech Stack: Python 3, Django, DRF, Django Unittest + Pytest, PostgreSQL, Redis, Celery, RabbitMQ, Docker, Docker Swarm, GitLab.

Developed and delivered new functionality for applications built on B3 — the company's proprietary platform. Implemented integrations with third‑party services, actively used raw SQL for complex tasks, optimized queries, and debugged code for both applications and the underlying platform.

**Key Achievements**:

- Optimized complex SQL queries using recursive CTEs, reducing critical operation execution time by 34% (EXPLAIN ANALYZE measurements before/after), thereby lowering database load.
- Refactored legacy code in the B3 core platform, eliminating 12 critical performance bottlenecks.
- Started using Cursor AI assistant in the development process, improving efficiency when writing and debugging code.

During this period I gained hands‑on experience with recursive CTEs both in raw SQL and within Django ORM.

### [Samolet Development](https://samolet.ru)

*A major real estate developer that extensively uses IT technologies to manage construction and property operations*.

**Period**: April 2023 – August 2024 (1 year 5 months).

Tech Stack: Python 3, Django, FastAPI, PostgreSQL, Redis, RabbitMQ, Celery, Apache Kafka, Docker, Pytest, Prometheus, Grafana, Kubernetes, GitLab.

**Key Tasks and Achievements**:

- Authentication Systems Development & Security:
  - Designed and implemented two‑factor authentication (2FA) for a custom OAuth2 provider, improving security for 15+ corporate applications and protecting data of 8,000+ employees.
  - Implemented social login with mandatory 2FA when linking new accounts.
  - Created a forced logout mechanism: OAuth2 token revocation and session deletion in Redis upon password change or account deactivation.
  - Designed a JWT‑based proxy authorization microservice for integration with corporate document management, reducing access approval time by 67% (metrics from the ticket tracker).
- Backend Development & Integrations:
  - Developed high‑load Apache Kafka producers and consumers processing 50,000+ events per minute with latency below 12 ms (according to Grafana metrics).
  - Implemented an adapter service for synchronizing data between the equipment inventory system and internal processing, automating handling of 3,200+ equipment units.
  - Introduced RBAC for Apache Kafka, standardizing access management for 23 microservices.
- Infrastructure & Monitoring:
  - Maintained architecture documentation following "architecture as code" principles using [DockHub](https://dochub.info/main).
  - Developed Grafana dashboards for monitoring Prometheus metrics.
  - Participated in second‑line on‑call rotations, advising developers from other teams on OAuth2 integration.
- Code Quality:
  - Actively wrote unit and integration tests using Pytest, including refactoring legacy code.

During this period I gained experience with FastAPI, Apache Kafka, Kubernetes, Grafana, and OAuth2 protocol implementation.

### [Globant](https://globant.com)

*An international IT company specializing in digital transformation and software development for large corporate clients*.

*Client: Ubisoft, project — an internal tool for visualizing video game defects during manual testing*.

**Period**: November 2021 – November 2022 (1 year).

Tech Stack: Python 2, Python 3, Twisted, PostgreSQL, Redis, Pytest, GitLab.

**Key Projects and Achievements**:

- Performed a complete migration of a corporate application from Python 2 to Python 3. Refactored 88 modules for compatibility with the new interpreter version while preserving 100% functionality and API backward compatibility. The project gained long‑term support, and its security was upgraded to meet modern standards.
- Integrated Microsoft Azure AD as the OAuth2 server, replacing the client's legacy custom authentication token provider.
- Covered critical code sections with integration tests using Pytest, achieving 98% coverage (pytest‑cov).

During this period I gained deep practical experience with the Twisted asynchronous framework and mastered integration with cloud authorization providers using Microsoft Azure as an example.

### Lendsbay

*A fintech startup developing a platform for secure person‑to‑person lending (P2P lending)*.

**Period**: March 2020 – October 2021 (1 year 8 months).

Tech Stack: Python 3, AIOHTTP, Pyramid, PostgreSQL, SQLAlchemy, Alembic, Celery, Redis, RabbitMQ, Docker, GitLab.

**Key Tasks and Achievements**:

- Developed the backend for the high‑load Lendsbay mobile application, handling ~10,000 RPS to the database (source: pg_stat_database), ensuring service stability for tens of thousands of users.
- Business Logic & Integrations:
  - Developed an XML parser for credit bureau extracts, using the data to periodically recalculate the user's proprietary credit score.
  - Implemented functionality for regular notifications to collection agencies about overdue user payments.
  - Designed an automatic penalty waiver algorithm with flexible condition settings, reducing customer churn by 12.3% (according to business analytics).
- Interfaces & Data Visualization:
  - Built an interactive analytics system within the admin panel from scratch: developed dashboards with d3.js charts and complex filtering for analyzing key business metrics.
  - On personal initiative, developed a functional prototype of the client‑side web interface to evaluate UX hypotheses.

During this period I gained extensive experience with the AIOHTTP asynchronous framework to ensure high performance. I mastered and effectively applied the Pyramid framework for building the admin interface. Actively used SQLAlchemy ORM for complex queries and Alembic for migrations.

### [FinTech, CJSC](https://fintech.ru)

*A Russian vendor and specialized developer of secure government information systems, platforms, and biometric solutions*.

**Period**: March 2017 – December 2017 (10 months).

Tech Stack: Python 2, Django, Django REST Framework (DRF), PostgreSQL, Git.

Developed the backend for the PSZI "Sintez" platform — a system for automated management of administrative and economic units.

**Key Tasks and Achievements**:

- Participated in developing and maintaining the platform backend using Django and Django REST Framework (DRF).
- Developed REST APIs for frontend integration and communication with related systems.
- Designed and implemented data models, ensuring integrity and efficient PostgreSQL operations.
- Contributed to business logic development related to managing and tracking administrative and economic resources.

Gained experience with Django REST Framework for API development and PostgreSQL in an enterprise project.

### Freelance

**Period**: September 2016 – March 2017 (7 months).

Tech Stack: Python 3, Django, Bootstrap, jQuery, Git.

**Key Projects and Experience**:

- Internship at Corona Travel: successfully built a forum engine from scratch as a training project using Django, implementing basic posting and commenting functionality. Completed several entry‑level practical tasks, reinforcing commercial development and teamwork skills.
- Freelance Projects: developed a rental property management system from scratch using Django, which included managing property listings, calculating payments, and generating reports. Created a corporate landing page for a financial organization with responsive design in Bootstrap and interactive elements in jQuery.

During this period I gained practical experience building Django backends and implementing user interfaces with Bootstrap and jQuery.

## Additional Education

### 2025

[Advanced Django 5 for Professionals](https://stepik.org/cert/2715715)

### 2024

- [SQL Academy](https://sql-academy.org/ru/check-certificate/671152b1cce5890029df30be?language=ru)
- [Asynchronous Python](https://stepik.org/cert/2699882)

### 2021

[Interactive SQL Simulator](https://stepik.org/cert/1028495)

### 2020

- [Python Web Developer](https://otus.ru/certificate/653fdb3150e544669d310d73f7508303/)
- [SQL Course Simulator](https://github.com/mxmaslin/skillfactory/blob/master/sql/Maxim%20Maslin.pdf)

### 2019

- [SQL Basics](https://stepik.org/cert/211612)
- [Building Web Services in Python](https://coursera.org/share/ac3e87c3924eadbff7472895453166d2)

### 2018

[OOP and Design Patterns in Python](https://www.coursera.org/account/accomplishments/certificate/KSV7WVKJJMMB)

### 2017

- [6.00.1x: Introduction to Computer Science and Programming Using Python](https://courses.edx.org/certificates/0bf0fd829fe843df836e6f8f2e843079)
- [Introduction to Databases](https://stepik.org/certificate/f43b16a5f289e9a4d5e0d2b86dd6a8d89083585c.pdf)
- [Web Technologies](https://stepik.org/certificate/07e2f2e0ea62704c492890188db3b1f5a005b478.pdf)
- [Programming in Python](https://www.coursera.org/account/accomplishments/certificate/KQLCFRTFGNHJ)

### 2016

- [Capstone: Retrieving, Processing, and Visualizing Data with Python](https://www.coursera.org/account/accomplishments/certificate/WYJNN67SSRK5)
- [Principles of Computing (Part 1)](https://www.coursera.org/account/accomplishments/certificate/AV2ET5W8AX)
- [Python: Basics and Applications](https://stepik.org/certificate/1107c82f7136344eb36d77827bfeaeb590142df4.pdf)
- [Using Databases with Python](https://www.coursera.org/account/accomplishments/certificate/PF3DYSXMQ2U2)

### 2015

- [Python Data Structures](https://www.coursera.org/account/accomplishments/certificate/7ZEZAPA8X6EL)
- [Using Python to Access Web Data](https://www.coursera.org/account/accomplishments/certificate/2DKZCW2NTF6S)
- An Introduction to Interactive Programming in Python, Rice University (Coursera)

### 2014

- [Introduction to Linux](https://stepik.org/certificate/6bdb64d72bcb0d6cf84d3f18c2dc90c3092c73b6.pdf)
- [Programming in Python](https://stepik.org/certificate/ebda31fb800f9f2f5e2fca75abb2e943a4de4e3f.pdf)
- [Creating Web Interfaces with HTML and CSS](https://assets.htmlacademy.ru/certificates/intensive/2/14240.pdf)

### 2012

Learn to Program: The Fundamentals, University of Toronto (Coursera)

## Contact

zapzarap@yandex.ru or [@dr_blumenau](https://t.me/dr_blumenau).