## 🚀 About Me

- 🔧 Specialized in **Python backend development**
- ⚙️ Focused on building APIs that handle **real-world constraints: abuse, edge cases, and system reliability**
- 🚀 Shipped production systems deployed on **Koyeb + Vercel**
- 🧠 Currently deepening knowledge in:
  - Authentication systems (JWT, OAuth2)
  - Caching strategies (Redis)
  - Cloud infrastructure fundamentals

---

## 🛠️ Tech Stack

**Backend**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Pydantic](https://img.shields.io/badge/Pydantic-E92063?style=flat-square&logo=pydantic&logoColor=white)

**Databases**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![Alembic](https://img.shields.io/badge/Alembic-6BA81E?style=flat-square&logoColor=white)

**Infrastructure & DevOps**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white)
![Koyeb](https://img.shields.io/badge/Koyeb-121212?style=flat-square&logo=koyeb&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)

**Testing & Quality**

![Pytest](https://img.shields.io/badge/Pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white)
![Vitest](https://img.shields.io/badge/Vitest-6E9F18?style=flat-square&logo=vitest&logoColor=white)

---

## 🧩 Key Concepts I Work With

- Scalable REST API design under **real usage constraints**
- Security hardening:
  - Rate limiting
  - Anti-spam systems (deduplication, honeypots, silent drop)
- Clean Architecture — Domain / Service / Infrastructure separation
- Structured logging & observability
- Defensive programming & testable domain logic

---

## 📌 Featured Projects

### 🔹 [Portfolio Backend System](https://github.com/Argenis1412/portfolio)
Backend system built to handle **real-world spam and abuse scenarios with layered defenses**.

| Feature | Detail |
|---|---|
| 🛡️ Anti-spam | 30-min persistent deduplication + honeypots + silent drop |
| ⚡ Rate limiting | Identity-based throttling via `slowapi` |
| 📋 Observability | Structured logging with `structlog` |
| 🏗️ Architecture | Clean Architecture — framework-independent core |
| ✅ Quality gate | CI/CD with 70% test coverage enforcement |
| 🐳 Infra | Docker + GitHub Actions + Koyeb / Vercel |

`FastAPI` `Python 3.12` `SQLite` `SQLModel` `Alembic` `Docker` `React 19` `TypeScript` `TanStack Query`

#### 🧠 Key Design Decisions

- **Silent drop over explicit rejection** — Eliminates attacker feedback loops and reduces adaptive spam behavior.
- **30-minute deduplication window** — Prevents burst spam while preserving legitimate retries.
- **Framework-independent domain** — Business logic isolated from FastAPI, enabling fast and reliable unit testing.
- **Honeypot strategy** — Zero UX cost, effective bot filtering.
- **Structured logging from day one** — Ready for production observability stacks without refactoring.

---

### 🔹 [Loja App — Payment System](https://github.com/Argenis1412/Loja_app)
Payment engine focused on **deterministic financial calculations and explicit business rules**.

| Feature | Detail |
|---|---|
| 💳 Payment modes | Cash, debit, credit 0% (2–6x), credit 10% (12–24x) |
| 🔢 Precision | Deterministic totals — zero rounding drift |
| 🏗️ Architecture | DDD — business logic fully isolated |
| 🗄️ Persistence | Repository pattern + PostgreSQL + Alembic |
| 🎨 Frontend | Strict API consumer (React + TypeScript) |
| 🚀 Deploy | Render (API) + Vercel (UI) |

`FastAPI` `Python 3.11` `PostgreSQL` `SQLAlchemy` `Alembic` `Pytest` `React` `TypeScript` `Vite` `Tailwind CSS`

#### 🧠 Key Design Decisions

- **Deterministic installment calculation** — Final payment absorbs rounding to guarantee exact totals.
- **Domain-first design** — Business rules implemented in pure Python, not tied to ORM behavior.
- **Repository abstraction** — Persistence layer fully decoupled from domain logic.
- **Backend as source of truth** — Frontend contains no business logic, ensuring consistency and integrity.

---

## 📫 Contact

<div align="center">

[![Email](https://img.shields.io/badge/Email-argenislopez28708256%40gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:argenislopez28708256@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Argenis_Lopez-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/argenis1412)
[![GitHub](https://img.shields.io/badge/GitHub-Argenis1412-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/Argenis1412)

</div>

---

<div align="center">
  <sub>💡 <em>I build backend systems that remain reliable under real-world conditions — not just ideal scenarios.</em></sub>
</div>