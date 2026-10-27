<div align="center">

# Привет! Я Ильмира 👋

**Go-разработчик · автоматизация процессов · ИИ-агенты и RAG**

Геолог, которая обнаружила: разбирать сложные системы и наводить в них
порядок можно не только в недрах — и ушла делать это в IT.


</div>

## 🛠 Стек

**Языки и фреймворки:**

![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=white)

**Базы данных:**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)

**DevOps и инструменты:**

![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)
![Swagger](https://img.shields.io/badge/Swagger-85EA2D?style=for-the-badge&logo=swagger&logoColor=black)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

**Специализация:**

![REST API](https://img.shields.io/badge/REST_API-2563EB?style=for-the-badge)
![gRPC](https://img.shields.io/badge/gRPC-24A0E9?style=for-the-badge&logo=grpc&logoColor=white)
![WebSocket](https://img.shields.io/badge/WebSocket-1E293B?style=for-the-badge)
![LLM Agents](https://img.shields.io/badge/LLM_Agents-8B5CF6?style=for-the-badge)
![Function Calling](https://img.shields.io/badge/Function_Calling-412991?style=for-the-badge)
![RAG](https://img.shields.io/badge/RAG-F59E0B?style=for-the-badge)
![Whisper STT](https://img.shields.io/badge/Whisper_STT-000000?style=for-the-badge&logo=openai&logoColor=white)

## 🚀 Проекты

### [🥉 AI-ассистент по техдокументации](https://github.com/il-mira7/ai-impulse-doc-assistant) — хакатон [«AI-импульс 2.0»](https://student.sber.ru/ai-impulse)
Трек ПАО «Газпром нефть» — **3 место**. Ассистент отвечает на вопросы по 139
руководствам (16 825 страниц, 17 отечественных продуктов) и показывает, откуда взят ответ — вплоть
до страницы PDF. По сути: гибридный поиск, интерпретация омонимов и работа на российских моделях с офлайн-фолбэком.
`Python` · `FastAPI` · `SQLite FTS5` · `RAG` · `LLM`

### 🏭 Цифровой двойник сортировочного центра — хакатон [Robozon](https://ozon-robozon.ru/) (Ozon)
Симуляция сортировочного центра, переваривающего 100 000 товаров в час: дискретно-событийный движок на чистом Go, собственный WebSocket для стриминга тиков в 3D-двойник (React + Three.js),
всё собирается в один бинарник. Моя роль — разложить задачу, руководить ИИ-агентом, который писал код,
и принимать результат. Код команды не публиковался.
`Go` · `DES` · `WebSocket RFC 6455` · `Docker` · `React/Three.js`

### [🤖 Proactive AI Planner Bot](https://github.com/il-mira7/planner-bot)
Telegram-планировщик, в котором ИИ-агент — полноценный собеседник: «напомни купить корм, я обычно
после работы» — и он сам создаст задачу (function calling), запомнит, что ты сова и магазины
до 23:00, и не станет дёргать уведомлениями в тихие часы. Голосовые тоже понимает (Whisper).
Код написан в паре с ИИ-агентом.
`Go` · `SQLite` · `LLM` · `Whisper`

### [🛒 ShopAPI](https://github.com/il-mira7/shop-api)
Бэкенд магазина бытовой техники в три этапа: классический CRUD на Gin и PostgreSQL, публикация за Nginx —
балансировка 2:1:1 на три инстанса, кэш, gzip, HTTPS — и отдельный gRPC-сервис авторизации со своей БД:
JWT, bcrypt, middleware на каждый запрос. 23 эндпоинта под Swagger.
Этот проект пишу руками.
`Go` · `Gin` · `PostgreSQL` · `gRPC` · `JWT` · `Nginx`

### [❌⭕ go-tic-tac-toe](https://github.com/il-mira7/go-tic-tac-toe)
Крестики-нолики, выросшие в настоящий сервис: сначала бот на минимаксе, потом партии на двоих
через PostgreSQL, потом JWT с refresh-токенами, история партий и таблица лидеров. Слои разделены,
зависимости собирает uber-fx, весь стек поднимается одной командой.
`Go` · `Gin` · `PostgreSQL` · `JWT` · `Docker` · `минимакс`

### [🍕 SQL Bootcamp — School 21](https://github.com/il-mira7/sql-bootcamp)
12 учебных проектов и 100 задач на PostgreSQL — от простых JOIN'ов до изоляции транзакций,
индексов с `EXPLAIN ANALYZE`, триггеров, функций PL/pgSQL и рекурсивных CTE. У каждого проекта —
свой README и схема БД.
`PostgreSQL` · `SQL` · `PL/pgSQL` · `psql`

### 🚗 Car Telemetry — *скоро*
Телеметрия и диагностика автомобиля: собственный движок протокола ISO-TP поверх OBD-II/UDS,
gRPC-стриминг показаний, Flutter-клиент. Самое интересное здесь — разговор с машиной на её языке.
Репозиторий готовится к публикации. `Go` · `gRPC` · `OBD-II/UDS` · `Flutter`

---

💬 Открыта к предложениям: Go-разработка, автоматизация процессов, ИИ-агенты.
