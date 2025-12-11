# Маслин Максим Михайлович

## Разработчик бэкенда на Python | Senior

Контакты: zapzarap@yandex.ru | Telegram: @dr_blumenau

[Скачать PDF](https://github.com/mxmaslin/resume/blob/main/Maslin%20backend.pdf?raw=true) (Size: 258 KB)

## Профессиональный профиль

Backend-разработчик на Python с 6+ лет коммерческого опыта. Специализируюсь на создании надежных, масштабируемых сервисов, сложных интеграциях и работе с высоконагруженными системами. До перехода в разработку 8+ лет работал техническим писателем и аналитиком, что сформировало навыки работы со сложными концепциями, проектирования понятных систем и эффективной коммуникации.

## Ключевые компетенции:

- **Разработка сервисов**: Полный цикл разработки на Django/DRF, FastAPI, асинхронных фреймворках (AIOHTTP, Twisted).
- **Безопасность и аутентификация**: Глубокая практика OAuth2, 2FA, JWT, прокси-авторизации, RBAC (ролевая модель доступа).
- **Работа с данными и инфраструктурой**: Оптимизация SQL (рекурсивные CTE), Apache Kafka (high-load продьюсеры/консьюмеры), ETL, контейнеризация (Docker, K8s), мониторинг (Grafana).
- **Работа с Legacy-кодом**: Рефакторинг, миграция с Python 2 на 3, покрытие тестами.
- **Инструменты и подход**: Pytest, GitLab CI/CD, использование AI-ассистентов (Cursor) для ускорения разработки, принцип "архитектура как код".

## Технологический стек

| Категория | Технологии |
|---|---|
| Языки	| Python 2/3, JavaScript (ES6+), SQL | 
| Фреймворки (Backend)	| Django/DRF, FastAPI, AIOHTTP, Twisted, Pyramid | 
| Базы данных & ORM	| PostgreSQL, Redis, SQLAlchemy, Alembic, peewee | 
| Очереди & Async	| Apache Kafka, RabbitMQ, Celery | 
| Инфраструктура & DevOps	|  Docker, Kubernetes, Docker Swarm, Git/GitLab, Grafana, bash| 
| Тестирование | 	Pytest, unittest| 
| Прочее	|  REST API, OAuth2, JWT, Linux, HTML/CSS | 

## Опыт работы

### Большая Тройка

#### Разработчик бэкенда (Python) | Август 2024 — Декабрь 2025

**Технологии**: Python 3, Django, DRF, PostgreSQL, Redis, Celery, RabbitMQ, Docker, Docker Swarm, GitLab, Pytest.

Разработка и внедрение нового функционала для приложений на базе проприетарной платформы компании (B3).

- Реализация интеграций со сторонними сервисами и внутренними системами.
- Активная работа с сырым SQL для решения сложных задач, оптимизация запросов (включая использование рекурсивных CTE).
- Отладка и анализ кода как прикладных приложений, так и самой платформы.
- Внедрение AI-инструментов (Cursor) в процесс разработки для повышения эффективности.

### Самолёт Девелопмент

#### Разработчик бэкенда (Python) | Апрель 2023 — Август 2024 (1 год 5 месяцев)

**Технологии**: Python 3, Django, FastAPI, PostgreSQL, Redis, RabbitMQ, Celery, Apache Kafka, Docker, Kubernetes, Grafana, GitLab, Pytest.

Работа над безопасностью и разработкой серверной части для высоконагруженных продуктов.

- **Безопасность**: Разработал и внедрил двухфакторную аутентификацию (2FA) для кастомного OAuth2-провайдера, включая аутентификацию через соцсети. Создал микросервис прокси-авторизации на JWT для доступа к корпоративному документообороту.
- **Бэкенд & Интеграции**: Разрабатывал high-load продьюсеры и консьюмеры Apache Kafka. Реализовал адаптер-сервис для синхронизации данных между внешними и внутренними системами. Внедрил RBAC для Apache Kafka.
- **Инфраструктура & Мониторинг**: Вёл архитектурную документацию ("архитектура как код"), разрабатывал дашборды в Grafana. Участвовал в дежурствах 2-й линии поддержки по OAuth2.
- **Качество кода**: Активное покрытие тестами (Pytest) и рефакторинг legacy-кода.

### Globant (Проект для Ubisoft)

#### Разработчик Python | Ноябрь 2021 — Ноябрь 2022 (1 год)

**Технологии**: Python 2/3, Twisted, PostgreSQL, Redis, Pytest, GitLab.

**Проект**: Flare — внутренний сервис Ubisoft для визуализации ручного тестирования.

- **Ключевой проект**: Выполнил полную миграцию корпоративного приложения с Python 2 на Python 3, обеспечив долгосрочную поддержку и безопасность.
- **Интеграции**: Провел успешную замену провайдера аутентификации, интегрировав Microsoft Azure AD вместо устаревшего собственного решения.

Приобрёл глубокий опыт работы с асинхронным фреймворком Twisted.

### Лендсбэй

#### Разработчик Python | Март 2020 — Октябрь 2021 (1 год 8 месяцев)

**Технологии**: Python 3, AIOHTTP, Pyramid, PostgreSQL, SQLAlchemy, Alembic, Celery, Redis, RabbitMQ, Docker, GitLab.

Разработка бэкенда для высоконагруженного (~10k запросов/час) мобильного приложения и его админ-панели.

- **Бизнес-логика**: Разработал парсер XML-выгрузок из Бюро Кредитных Историй для автоматизации скоринга. Создал систему оповещений коллекторских агентств.
- **Улучшение продукта**: Реализовал гибкий алгоритм автоматического "прощения" штрафов, улучшив клиентский опыт.
- **Аналитика & Интерфейсы**: С нуля создал систему интерактивной аналитики в админке с дашбордами на d3.js и сложной фильтрацией.

Глубокий опыт с AIОHTTP (производительность) и Pyramid.

### ФинТех, ОАО

#### Разработчик Python | Март 2017 — Декабрь 2017 (10 месяцев)

**Технологии**: Python 2, Django, Django REST Framework (DRF), PostgreSQL, Git.

Разработка серверной части платформы ПСЗИ «Синтез» (система управления административно-хозяйственными единицами).

- Участие в разработке и поддержке бэкенда на Django/DRF.
- Проектирование REST API, моделей данных и обеспечение работы с PostgreSQL.

Первый коммерческий опыт в enterprise-разработке.

### Фриланс / Стажировка

#### Начало карьеры в разработке | Сентябрь 2016 — Март 2017 (7 месяцев)

**Технологии**: Python 3, Django, Bootstrap, jQuery, Git.

Стажировка (Corona Travel): Разработка с нуля учебного движка для форума на Django.

Фриланс-проекты: Создание системы учёта аренды недвижимости на Django и корпоративного лендинга.

## Образование и сертификации

### Основное образование

#### МГУ им. М.В. Ломоносова, Философский факультет (1998).

Специальность нерелевантна IT-позиции. Ценность представляет сформированное системное мышление и навыки работы с информацией.

### Дополнительное образование

 #### 2025

[Продвинутый Django 5 для продолжающих](https://stepik.org/cert/2715715)

#### 2024

- [SQL Academy](https://sql-academy.org/ru/check-certificate/671152b1cce5890029df30be?language=ru)
- [Асинхронный Python](https://stepik.org/cert/2699882)

#### 2021

[Интерактивный тренажёр по SQL](https://stepik.org/cert/1028495)

#### 2020

- [Web-разработчик на Python](https://otus.ru/certificate/653fdb3150e544669d310d73f7508303/)
- [Курс-тренажёр по SQL](https://github.com/mxmaslin/skillfactory/blob/master/sql/Maxim%20Maslin.pdf)

#### 2019

- [Основы SQL](https://stepik.org/cert/211612)
- [Создание Web-сервисов на Python](https://coursera.org/share/ac3e87c3924eadbff7472895453166d2)

#### 2018

[ООП и паттерны проектирования в Python](https://www.coursera.org/account/accomplishments/certificate/KSV7WVKJJMMB)

#### 2017

- [6.00.1x: Introduction to Computer Science and Programming Using Python](https://courses.edx.org/certificates/0bf0fd829fe843df836e6f8f2e843079)
- [Введение в базы данных](https://stepik.org/certificate/f43b16a5f289e9a4d5e0d2b86dd6a8d89083585c.pdf)
- [Веб-технологии](https://stepik.org/certificate/07e2f2e0ea62704c492890188db3b1f5a005b478.pdf)
- [Программирование на Python](https://www.coursera.org/account/accomplishments/certificate/KQLCFRTFGNHJ)

#### 2016

- [Capstone: Retrieving, Processing, and Visualizing Data with Python](https://www.coursera.org/account/accomplishments/certificate/WYJNN67SSRK5)
- [Principles of Computing (Part 1)](https://www.coursera.org/account/accomplishments/certificate/AV2ET5W8AX)
- [Python: основы и применение](https://stepik.org/certificate/1107c82f7136344eb36d77827bfeaeb590142df4.pdf)
- [Using Databases with Python](https://www.coursera.org/account/accomplishments/certificate/PF3DYSXMQ2U2)

#### 2015

- [Python Data Structures](https://www.coursera.org/account/accomplishments/certificate/7ZEZAPA8X6EL)
- [Using Python to Access Web Data](https://www.coursera.org/account/accomplishments/certificate/2DKZCW2NTF6S)
- An Introduction to Interactive Programming in Python, Rice University (Coursera)

#### 2014

- [Введение в Linux](https://stepik.org/certificate/6bdb64d72bcb0d6cf84d3f18c2dc90c3092c73b6.pdf)
- [Программирование на Python](https://stepik.org/certificate/ebda31fb800f9f2f5e2fca75abb2e943a4de4e3f.pdf)
- [Создание веб-интерфейсов с помощью HTML и CSS](https://assets.htmlacademy.ru/certificates/intensive/2/14240.pdf)

#### 2012

Learn to Program: The Fundamentals, University of Toronto (Coursera)

## Контакты для связи

zapzarap@yandex.ru | https://t.me/dr_blumenau
