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

<div align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/FastAPI-05998B?style=for-the-badge&logo=fastapi&logoColor=white" />
  <img src="https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white" />
  <img src="https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
</div>

---

## The Production Mantra

> "If it ain't broken, it's just a latent bug waiting for a Friday deploy. If it IS broken, it's probably DNS."

---

## Production Debugging Flowchart

```mermaid
flowchart TD
    A[Alert fires at 3 AM] --> B{Check logs?}
    B -->|Yes| C[Find nothing useful]
    B -->|No| D[Reboot everything]
    C --> E{Check metrics?}
    E -->|Yes| F[Notice it's been broken for 3 days]
    E -->|No| G[Blame network]
    F --> H["Ah, it was the deploy last Friday"]
    D --> H
    G --> H
    H --> I[Rollback]
    I --> J[Write post-mortem]
    J --> K["Root cause: I forgot to run the migration"]
    K --> L[Add migration to CI/CD]
    L --> M[Sleep for 4 hours]
    M --> N[Wait for next alert]
```

## GitHub Analytics

<a href="https://github.com/Argenis1412">
  <img height=180 align="center" src="https://github-readme-stats.vercel.app/api?username=Argenis1412&show_icons=true&include_all_commits=true&theme=dark" />
</a>
<a href="https://github.com/Argenis1412">
  <img height=180 align="center" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Argenis1412&layout=compact&langs_count=8&theme=dark" />
</a>
<br>
<br>

[![trophy](https://github-profile-trophy.vercel.app/?username=Argenis1412&theme=onedark&column=5&no-frame=false&margin-w=5)](https://github.com/ryo-ma/github-profile-trophy)

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