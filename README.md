# 🚀 Argenis Lopez | Backend Engineer

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=1e293b&height=150&section=header&text=Building%20Resilient%20Backend%20Systems&fontSize=30&fontColor=ffffff&animation=fadeIn" width="100%" />
</div>

*I build backend systems that remain reliable under real-world conditions — not just ideal scenarios.*

---

## 👨‍💻 About Me

I specialize in **Python backend development** with a strong focus on building APIs capable of handling **real-world constraints like abuse, edge cases, and high reliability**. I believe in engineering for production from day one—incorporating observability, defensive programming, and clean architecture.

- 🏗️ Currently deepening knowledge in: **Cloud infrastructure, Caching strategies (Redis), and Authentication (JWT/OAuth2)**
- 🚀 Deploying production-ready systems on **Koyeb, Vercel, and Render**
- 🛡️ Passionate about **security hardening** and **Anti-spam architectures**

---

## 🛠️ Tech Stack & Arsenal

<div align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=py,fastapi,postgres,sqlite,redis,docker,githubactions,sentry,react,ts&perline=10" />
  </a>
</div>

**Core Focus:**
- **Languages / Frameworks:** Python (3.11/3.12), FastAPI, Pydantic, SQLAlchemy, SQLModel
- **Data & Caching:** PostgreSQL, SQLite, Redis (Upstash)
- **DevOps & Observability:** Docker, GitHub Actions, Sentry, Prometheus
- **Architecture:** Clean Architecture, DDD Basics, Test-Driven Development (Pytest)

---

## 📌 Featured Engineering Projects

### 🛡️ [Graphite & Bronze: Production-Grade Portfolio Backend](https://github.com/Argenis1412/portfolio)
*Not just a CRUD demo. A system built to simulate and survive real-world backend challenges.*

| 🚀 Highlights | 🧠 Engineering Decisions |
|:---|:---|
| **JSON-First Read Path** for <50ms P95 latency | Read-heavy portfolio data bypasses the DB via in-memory cached JSON |
| **Multi-Layer Anti-Abuse** | 30-min Redis deduplication window + Honeypots + Silent Drop to frustrate attackers |
| **HTTP Caching (ETags)** | Zero-bandwidth revalidations with `304 Not Modified` |
| **Observability Stack** | Integrated Sentry, Prometheus, and OpenTelemetry from day one |
| **Quality Gates** | Hard CI/CD enforcing >80% test coverage and strict linting |

_Tech: FastAPI, Redis, PostgreSQL, Structlog, Slowapi, Docker, Actions_


### 💳 [Loja App: Payment Logic Laboratory](https://github.com/Argenis1412/Loja_app)
*Payment engine strictly focused on deterministic financial calculations and clean boundaries.*

| 🚀 Highlights | 🧠 Engineering Decisions |
|:---|:---|
| **Deterministic Installments** | Final payment absorbs any rounding drift to guarantee mathematically exact totals |
| **Backend as Source of Truth** | UI simply consumes the API; 100% of calculation rules isolated in pure Python domain logic |
| **Framework Independence** | Core rules are totally decoupled from SQLAlchemy/FastAPI |
| **Explicit Rules** | Handles Cash, Debit, Credit (2-6x 0% interest), Credit (12-24x 10% interest) |

_Tech: FastAPI, PostgreSQL, SQLAlchemy, Pytest, React, TypeScript_

---

## 📊 GitHub Analytics

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Argenis1412&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0D1117&cache_seconds=1800" height="195" alt="GitHub Stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Argenis1412&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D1117&cache_seconds=1800" height="195" alt="Top Languages" />
</div>

---

## 📫 Let's Connect

<div align="center">
  <a href="mailto:argenislopez28708256@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
  <a href="https://www.linkedin.com/in/argenis1412">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="https://github.com/Argenis1412">
    <img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
  </a>
</div>