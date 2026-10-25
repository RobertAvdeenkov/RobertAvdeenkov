##  Tech Stack & Skills

###  Core & Async
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Asyncio](https://img.shields.io/badge/Asyncio-3B7BBF?style=for-the-badge&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)

- **Асинхронность**: очереди потребителя/производителя, семафоры, `httpx`, `asyncio.to_thread`, `create_task`, `background_tasks`, `wait_for`, `wait` vs `gather`, `as_completed`, `shield`, `current_tasks`/`all_tasks`, `Event`, `Lock`
- **Логирование**: модуль `logging`

###  Databases & ORM
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?style=for-the-badge&logo=sqlalchemy&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)

- **SQL**: простые и сложные запросы, агрегатные и оконные функции, даты, CTE, транзакции, `EXPLAIN`, составные и частичные индексы, миграции, уровни изоляции, пагинация
- **SQLAlchemy**: `selectinload`, работа с асинхронной БД, написание сырого SQL
- **Redis**: `redis.asyncio`, `pub/sub`, `set`/`setex`/`get`

###  API & Security
![REST](https://img.shields.io/badge/REST_API-02569B?style=for-the-badge&logo=swagger&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white)
![CORS](https://img.shields.io/badge/CORS-FF6C37?style=for-the-badge&logo=postman&logoColor=white)

- **Сети и API**: куки, headers, CORS, REST API
- **Безопасность**: JWT (refresh и access токены), `bcrypt`
- **WebSockets**: базовый уровень, реализован чат с комнатами по собственному концепту

###  DevOps & Tools
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=for-the-badge&logo=rabbitmq&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)

- **Docker**: контейнеризация, `docker-compose` (базовый уровень)
- **RabbitMQ**: `aio_pika`, DLX, retry (базовый уровень)
- **CI/CD**: базовое понимание и настройка
- **Деплой**: Render
- **Git**, **Postman**

###  Testing & Architecture
![Pytest](https://img.shields.io/badge/Pytest-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white)

- **Тестирование**: `pytest` (`@pytest.fixture`, `TestClient`, тестовая БД, `pytest-asyncio`)
- **Архитектура**: разделение монолитных файлов на модули, паттерн «репозиторий + сервис»
- **Английский**: B1
