# Argenis Lopez | Backend Engineer & SRE Advocate

I design systems to survive production.

---

## Engineering Philosophy: Resilience by Design
I specialize in building Cloud-Native Backend Systems where reliability, observability, and infrastructure are first-class citizens. My work is focused on:

- **Chaos Engineering**: Automated weekly E2E failure simulations to verify system degradation and recovery.
- **Evidence-Based SRE**: A public record of **9 real production incidents** with detailed post-mortems and resolutions.
- **Clean Architecture**: Strict domain isolation to ensure logic remains independent of frameworks and infrastructure.

---

## Engineering Projects

### [Portfolio System: A Study in Resilience](https://github.com/Argenis1412/portfolio)
*Production-grade environment built to demonstrate SRE principles under pressure.*

- **Infrastructure as Code (IaC)**: Fully managed via Terraform with automated CI/CD provisioning.
- **Observability Stack**: Prometheus + Sentry + OpenTelemetry for full system transparency and honest telemetry.
- **JSON-First Read Path**: Reduced P95 latency from ~320ms to **<50ms** while eliminating DB as a single point of failure.
- **Multi-Layer Anti-Abuse**: Honeypots + Redis-backed Rate Limiting + Idempotency keys as architectural standards.

### [Loja App: Payment Logic Laboratory](https://github.com/Argenis1412/Loja_app)
*Payment engine focused on deterministic financial calculations and pure Domain-Driven Design (DDD).*

- **Deterministic Financials**: Logic guarantees mathematically exact totals by absorbing rounding drift in final installments.
- **Pure Domain**: 100% decoupling of business rules from infrastructure (SQLAlchemy/FastAPI).

---

## Tech Stack & Arsenal
- **Core**: Python (3.12), FastAPI, Pydantic V2, structlog.
- **Data & Resilience**: PostgreSQL, Redis (Upstash), Circuit Breakers, Idempotency Stores.
- **SRE & DevOps**: Terraform, GitHub Actions, Docker, Prometheus, Grafana, Sentry.
- **Validation**: Pytest (Resilience + Chaos), k6 (SLO Benchmarking).

---

## Contact & Links
<div align="left">
  <a href="https://argenisbackend.com">
    <img src="https://img.shields.io/badge/Portfolio-argenisbackend.com-000000?style=flat-square&logo=vercel&logoColor=white" alt="Portfolio" />
  </a>
  <a href="https://www.linkedin.com/in/argenis1412/">
    <img src="https://img.shields.io/badge/LinkedIn-argenis1412-0077B5?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="https://wa.me/5541995103364">
    <img src="https://img.shields.io/badge/WhatsApp-Contact-25D366?style=flat-square&logo=whatsapp&logoColor=white" alt="WhatsApp" />
  </a>
  <a href="mailto:argenislopez28708256@gmail.com">
    <img src="https://img.shields.io/badge/Email-argenislopez-D14836?style=flat-square&logo=gmail&logoColor=white" alt="Email" />
  </a>
</div>