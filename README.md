# Argenis Lopez — Backend Engineer & SRE

I design systems to survive production.

---

## Focus

Backend systems where **reliability, observability, and safety** are first-class concerns — not afterthoughts.

- **AI-Assisted Engineering**: Building tooling that makes LLM-generated code auditable and safe to apply in production.
- **Cloud-Native SRE**: Automated failure simulations, structured post-mortems, and evidence-based incident response.
- **Clean Architecture**: Domain logic isolated from frameworks, databases, and transport layers.

---

## Projects

### [PatchForge](https://github.com/Argenis1412/PatchForge)
*Git-native refactoring engine. Generate, validate, and apply code patches safely.*

The core problem: AI-generated code reaches production without deterministic validation. PatchForge enforces a structured pipeline — `scan → plan → preview → validate → apply` — where every change is reviewed as a diff, tested against a real suite, and applied atomically with rollback support.

- 546 tests across the full lifecycle
- Ruff + Pytest gates before any file is touched
- Persistent artifacts (`plan.json`, `patch.diff`, `validation.json`) for auditability

### [Portfolio System](https://github.com/Argenis1412/portfolio)
*Production environment built around SRE principles.*

- Infrastructure as Code via Terraform
- Observability stack: Prometheus + Sentry + OpenTelemetry
- P95 read latency under 50ms via JSON-first path

### [Loja App](https://github.com/Argenis1412/Loja_app)
*Payment engine with deterministic financial logic and Domain-Driven Design.*

---

## Stack

<div align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/FastAPI-05998B?style=for-the-badge&logo=fastapi&logoColor=white" />
  <img src="https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white" />
  <img src="https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
</div>

---

## GitHub

<a href="https://github.com/Argenis1412">
  <img height=170 align="center" src="https://github-readme-stats.vercel.app/api?username=Argenis1412&show_icons=true&include_all_commits=true&theme=dark" />
</a>
<a href="https://github.com/Argenis1412">
  <img height=170 align="center" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Argenis1412&layout=compact&langs_count=8&card_width=430&theme=dark" />
</a>

---

## Contact

<div align="left">
  <a href="https://argenisbackend.com">
    <img src="https://img.shields.io/badge/Portfolio-argenisbackend.com-000000?style=flat-square&logo=vercel&logoColor=white" />
  </a>
  <a href="https://www.linkedin.com/in/argenis1412/">
    <img src="https://img.shields.io/badge/LinkedIn-argenis1412-0077B5?style=flat-square&logo=linkedin&logoColor=white" />
  </a>
  <a href="mailto:argenisbackend@gmail.com">
    <img src="https://img.shields.io/badge/Email-argenisbackend@gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white" />
  </a>
</div>
