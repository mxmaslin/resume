# Маслин Максим Михайлович

**Python Backend-разработчик · 7+ лет коммерческой разработки (Django, FastAPI, PostgreSQL)**

Мужчина, 49 лет, родился 30 мая 1977

**Email:** [zapzarap@yandex.ru](mailto:zapzarap@yandex.ru) — предпочитаемый способ связи  
**MAX:** [max.ru/u/f9LHodD0cOJo6LfPoZriBTPNxYKVPwiMxcGpGqTTewSp5mwOzS946NvX8Ok](https://max.ru/u/f9LHodD0cOJo6LfPoZriBTPNxYKVPwiMxcGpGqTTewSp5mwOzS946NvX8Ok)  
**Telegram:** [@dr_blumenau](https://t.me/dr_blumenau)  
**GitHub:** [github.com/mxmaslin](https://github.com/mxmaslin)

**Проживает:** Смоленск  
**Гражданство:** Россия, есть разрешение на работу: Беларусь, Россия  
**Готов к переезду:** Россия, готов к командировкам

---

## Желаемая должность

**Python Backend-разработчик (Django, FastAPI, PostgreSQL)**

**Специализации:** программист, разработчик  
**Тип занятости:** полная занятость  
**Формат работы:** удалённо, гибрид  
**Желательное время в пути до работы:** не имеет значения

---

## Опыт работы — 7 лет 2 месяца

*Коммерческая разработка на Python. Документация для разработчиков (Waves) — отдельно ниже.*

### Февраль 2026 — Март 2026 · 2 месяца

**[Открытые решения](https://osinit.com)** · Пенза  
Разработка ПО · compliance / GRC

**Python Backend-разработчик (Django, DRF)**

**Продукт:** GRC-платформа — планы мероприятий, конструктор workflow.

**Стек:** Python 3, Django, Django REST Framework, PostgreSQL, Redis, Celery, RabbitMQ, Docker, GitLab CI, Pytest, Swagger/OpenAPI.

- Реализовал **REST API** ответственных за мероприятия плана (CRUD, permissions по компании/группам/пользователям), интеграционные тесты Pytest.
- Реализовал CRUD переходов статусов планов и мероприятий в workflow (pre-/post-функции, валидации, сервисный слой).
- Восстановил работоспособность **Swagger/OpenAPI** (drf-spectacular), стабилизировал **GitLab CI/CD** (MR → pytest → deploy).

---

### Август 2024 — Декабрь 2025 · 1 год 5 месяцев

**[БОЛЬШАЯ ТРОЙКА](https://big3.ru)** · Москва  
Разработка ПО · low-code платформа B3

**Python Backend-разработчик (Django, DRF)**

**Продукт:** платформа-конструктор B3 для бизнеса и госсектора.

**Стек:** Python 3, Django, DRF, PostgreSQL, Redis, Celery, RabbitMQ, Docker Swarm, GitLab, Pytest, raw SQL.

- Реализовал `get_depth_level` для иерархического справочника: глубина вложенности за **один SQL-запрос**, обновление потомков за два (рекурсивные **CTE**).
- Оптимизировал критичные запросы (**EXPLAIN ANALYZE**), сократил время операций с иерархиями.
- Устранил «зомби-логин» на Гостехе: **Keycloak** end-session + цепочка редиректов.
- Восстановил отправку почты (очередь Celery LOW→MEDIUM) и дефект профиля в low-code слое.
- Рефакторил legacy-код B3, покрытие критичных изменений Pytest.

---

### Апрель 2023 — Август 2024 · 1 год 5 месяцев

**[Самолет Девелопмент](https://samoletgroup.ru)** · Москва  
Корпоративные IT-сервисы

**Python Backend-разработчик (Django, FastAPI)**

**Стек:** Python 3, **Golang**, Django, FastAPI, PostgreSQL, Redis, **Apache Kafka**, Celery, Docker, **Kubernetes**, GitLab CI/CD, Pytest, **OAuth2**, django-guardian, Grafana.

- Внедрил **2FA** для OAuth2-провайдера S.ID (15+ приложений, 8000+ сотрудников).
- Реализовал принудительный logout: отзыв токенов + Redis-сессии при событиях LDAP.
- Разработал **JWT proxy** для ECM (−67% время согласования доступов).
- Построил Kafka-адаптер GLPI (50 000+ evt/min, latency <12 ms); **RBAC** в kafka-manager (guardian).
- **TECHPLAT-1059** (Go, микросервис **smail**): маршрутизация входящих писем из Kafka — разбор заголовков project/origin, привязка transport при сохранении в PostgreSQL (GORM), проверка whitelist AllowedTransports; доработка consumer и сервисного слоя BuildMailModel/ScheduleMail.
- **TECHPLAT-3831** (Go, **smail**): миграция на новый Kafka-кластер — TLS-подключение consumer/producer, сертификаты из env (base64) вместо файлов, вынос dialer в отдельную функцию, рефакторинг конфигурации окружения, обновление k8s-манifestов; прошёл code review.
- Настраивал **GitLab CI/CD** для сервисов: MR → test → build → deploy dev/stage/prod; секреты и deploy tokens в CI Variables.
- Вёл документацию API (ITHub/DockHub), 2-я линия поддержки OAuth2-провайдера.

---

### Ноябрь 2021 — Ноябрь 2022 · 1 год 1 месяц

**[Globant](https://globant.com)** · Ubisoft (Flare) · Минск

**Python Backend-разработчик**

**Продукт:** Flare — внутренний проект Ubisoft для визуализации багов видеоигр.

**Стек:** Python 2/3, Twisted, PostgreSQL, Redis, Pytest, GitLab, Microsoft Azure AD.

- Выполнил миграцию **Python 2 → 3** (232 модуля) с сохранением API.
- Интегрировал авторизацию **Microsoft Azure AD**.
- Поднял покрытие критичных модулей **Pytest**.

---

### Март 2020 — Октябрь 2021 · 1 год 8 месяцев

**ООО Лендсбэй** · [lendsbay.com](https://lendsbay.com) · Москва  
P2P-кредитование · финтех

**Python Backend-разработчик**

**Стек:** Python 3, **AIOHTTP**, Pyramid, SQLAlchemy, Alembic, PostgreSQL, Celery, Redis, RabbitMQ, Docker, GitLab.

- Разрабатывал backend мобильного приложения при ~**10 000 RPS** к БД (pg_stat_database), 100 000+ пользователей.
- Разработал парсер XML-выгрузок БКИ для автоматизированного скоринга.
- Спроектировал алгоритм автоматического «прощения» штрафов — снижение оттока клиентов на **12,3%** (данные бизнес-аналитики).
- Создал дашборды аналитики в админке (d3.js, фильтрация по метрикам).

---

### Февраль 2017 — Февраль 2020 · 3 года 1 месяц

**[Waves](https://waves.tech)** · Москва  
Финтех-платформа

**Технический писатель (documentation developer)**

**Фокус:** developer documentation и **REST API** для внешних интеграторов (английский язык).

- Писал и поддерживал **developer documentation** на **английском**: гайды, reference, сценарии интеграции.
- Описывал **REST API** платформы и смежных сервисов: эндпоинты, модели данных, ошибки, примеры запросов.
- Согласовывал структуру API-документации с backend-командами; унифицировал терминологию для внешних разработчиков.
- Переводил сложные доменные темы в инструкции для интеграторов.

*После этого периода — коммерческая backend-разработка на Python (с 2020).*

---

### Март 2017 — Декабрь 2017 · 10 месяцев

**[ФинТех, ОАО](https://www.fintech.ru)** · Москва

**Junior Python Backend-разработчик (Django, DRF)**

**Стек:** Python 2, Django, **Django REST Framework**, PostgreSQL, Git.

- Разрабатывал **REST API** и модели данных на Django/DRF для учёта АХО-ресурсов.

*Ранее: стажировка (Corona Travel), фриланс на Django — учёт аренды, лендинги.*

---

## Образование

**Высшее**, 1998  
**МГУ им. М.В. Ломоносова**, философский факультет

---

## Повышение квалификации

**2025** — Продвинутый Django 5 для продолжающих  
**2024** — SQL Academy; Асинхронный Python  
**2020** — Web-разработчик на Python  
*Полный список сертификатов (2014–2025) — в профиле hh / по запросу.*

---

## Навыки

**Языки:** русский — родной; английский — B1 (рабочая документация, техписатель Waves — EN)

**Ключевые навыки:**  
Python, Golang, Django Framework, Django Rest Framework, FastAPI, PostgreSQL, MongoDB, Elasticsearch, SQL, REST API, Redis, Celery, RabbitMQ, Apache Kafka, OAuth, Docker, Git, GitLab CI/CD, Pytest, Linux, Kubernetes

---

## Дополнительная информация

### Рекомендации

**Самолет Девелопмент** — Александр Трубников (руководитель отдела централизованных ИТ-сервисов)

### Обо мне

**Python Backend-разработчик** с **7+ годами коммерческого опыта**: **Django/DRF**, **FastAPI**, **PostgreSQL**, **REST API**, **Celery**, **Redis**, **Docker**, **GitLab CI/CD**, **Pytest**. Сильные стороны — интеграции (**OAuth2**, **Kafka**), иерархии и **SQL/CTE**, GRC/workflow. В Самолёте — две боевые задачи на **Golang** в smail (TECHPLAT-1059, TECHPLAT-3831); **GitLab CI/CD** настраивал сам: test → build → deploy, секреты в CI Variables.

Ранее **3 года** писал **developer documentation** и **REST API**-доки на английском ([Waves](https://waves.tech)) — проектирую понятные API и **OpenAPI/Swagger**. При необходимости — frontend (JavaScript, Vue) в рамках fullstack-задач.

| Категория | Технологии |
| --- | --- |
| Backend | Django/DRF, FastAPI, Golang (smail: TECHPLAT-1059/3831), AIOHTTP, Pyramid |
| Данные | PostgreSQL, Redis, MongoDB*, Elasticsearch*, рекурсивные CTE |
| Очереди | Celery, RabbitMQ, Apache Kafka |
| DevOps | Docker, GitLab CI/CD, Kubernetes (базово) |
| Безопасность | OAuth2, JWT, Keycloak, HMAC, RBAC (guardian) |

\* **MongoDB, Elasticsearch** — коммерческого опыта не было; владение демонстрирую кодом: **[github.com/mxmaslin/elastic_mongo](https://github.com/mxmaslin/elastic_mongo)** — API каталога и поиска контента для стриминга (FastAPI, DDD-слои): MongoDB — документная модель, optimistic concurrency, атомарные upsert'ы; Elasticsearch — полнотекстовый поиск с fuzziness, фильтры, highlight, пагинация, reindex; 58 unit + 35 integration тестов (реальные Mongo/ES), mypy strict, GitHub Actions CI, Docker Compose.

*Обновлено: 04.07.2026*
