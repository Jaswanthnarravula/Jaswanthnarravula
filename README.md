<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0F172A,60:1E3A8A,100:2563EB&height=170&section=header&text=Jaswanth%20Narravula&fontSize=40&fontColor=FFFFFF&fontAlignY=34&desc=Backend%20Engineer%20%C2%B7%20Identity%2C%20Distributed%20Systems%2C%20Data-Intensive%20Services&descAlignY=56&descSize=16" width="100%"/>

**Software Engineer @ Xclusive Trading Inc.** &nbsp;·&nbsp; **M.S. Computer Science, University of Alabama at Birmingham**

Go &nbsp;·&nbsp; Java 17 &nbsp;·&nbsp; Python &nbsp;—&nbsp; OAuth 2.1 / OpenID Connect &nbsp;·&nbsp; Microservices &nbsp;·&nbsp; PostgreSQL Performance

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/jaswanth-narravula)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:jaswanthnarravula@gmail.com)

</div>

---

## What I Work On

I build the backend systems other applications depend on — identity providers, service boundaries, and the data layer underneath them.

- **Identity and access.** Engineered a standards-based **OAuth 2.1 / OpenID Connect** provider in Go — authorization code flow with PKCE, refresh-token rotation, RS256-signed JWTs, automated JWKS key rotation, Argon2id credential hashing, and RBAC. It is the central SSO provider for internal applications, delivering single sign-on to **3,000+ users**.
- **Service decomposition.** Decomposed a production platform into **6 microservices** with isolated failure domains, so one degraded service no longer takes the platform down with it. Rebuilt its ETL workflows to be idempotent and replay-safe with exponential backoff — a retried or partially failed batch reprocesses cleanly instead of writing duplicates.
- **Database performance.** Cut report-generation time by **~60%** through PostgreSQL execution-plan analysis, targeted indexing, query optimization, and denormalized reporting tables over **50M+ rows**, supporting 8+ production services.
- **API design and hardening.** Stateless REST APIs secured with Microsoft Entra ID SSO over OIDC, RS256 JWT validation, and route-level RBAC — sustaining **sub-200 ms p95** latency under production monitoring, with per-IP rate limiting, CSRF protection, HSTS/CSP, and audit logging.

---

## Engineering Focus

<div align="center">
<table width="100%">
<tr>
<td width="33%" valign="top">

### Backend & Distributed Systems
- Go, Java 17, Python
- Spring Boot · Spring Data JPA
- FastAPI · Flask
- Microservices & REST APIs
- Concurrency & transactional integrity
- Idempotent, replay-safe ETL

</td>
<td width="33%" valign="top">

### Identity & Security
- OAuth 2.1 · OpenID Connect
- PKCE, refresh-token rotation
- RS256 JWT · JWKS key rotation
- Argon2id · RBAC · audit logging
- Microsoft Entra ID / Azure AD SSO
- Rate limiting, CSRF, HSTS/CSP

</td>
<td width="33%" valign="top">

### Data & Platform
- PostgreSQL · MySQL · Redis
- Query plans, indexing, tuning
- Elasticsearch · Celery queues
- Docker · Nginx · Linux
- GitHub Actions CI/CD
- AWS · Azure

</td>
</tr>
</table>
</div>

---

## Tech Stack

<div align="center">

**Languages**

[![Languages](https://skillicons.dev/icons?i=go,java,python,ts,js,bash&theme=dark&perline=6)](https://skillicons.dev)

**Backend & Frameworks**

[![Backend](https://skillicons.dev/icons?i=spring,fastapi,flask,react,vite&theme=dark&perline=5)](https://skillicons.dev)

**Data & Infrastructure**

[![Data](https://skillicons.dev/icons?i=postgres,mysql,redis,elasticsearch,docker,nginx,linux&theme=dark&perline=7)](https://skillicons.dev)

**Cloud, CI/CD & Tooling**

[![Cloud](https://skillicons.dev/icons?i=aws,azure,githubactions,git,postman,pytorch&theme=dark&perline=6)](https://skillicons.dev)

</div>

---

## Selected Work

> Built and maintained in production at Xclusive Trading Inc. and IBM. Source is proprietary and not publicly available.

| Project | What It Does | Stack |
|---------|--------------|-------|
| **Enterprise SSO Identity Provider** | OAuth 2.1 + OpenID Connect provider written from scratch — the same standards Entra ID, Okta and Google Cloud IAM implement, not a wrapper around them. PKCE, automatic JWKS rotation, 4-tier RBAC, admin session management, 15+ client integration examples. | Go 1.22 · Chi v5 · PostgreSQL · RS256 JWT · Argon2id · Nginx · systemd |
| **Full-Stack Sales Platform** | Internal sales platform in daily production use: React + Vite frontend over 6 independent Python microservices with isolated failure boundaries, JWT role propagation from the internal SSO provider, and replayable ETL pipelines. | React · Vite · Python · Flask · FastAPI · PostgreSQL · REST |
| **Workforce Management Backend** | Async-first FastAPI backend serving all internal management tiers — Azure AD SSO over OIDC, real-time WebSocket notifications with heartbeat and reconnection, 4-tier route-level RBAC, calendar scheduling with recurrence rules. | Python · FastAPI · PostgreSQL · SQLAlchemy · WebSockets · Azure AD · Docker |
| **Price Intelligence Platform** | Asynchronous ingestion pipeline over unreliable external sources: Celery/Redis task orchestration with retry and failure handling, Elasticsearch fuzzy search, cross-retailer ranking, and price-history analytics. | FastAPI · Celery · Redis · Elasticsearch · PostgreSQL · Docker Compose |
| **Corporate Loan Processing Platform** &nbsp;<sub>IBM · DBS Bank</sub> | 10+ production REST APIs automating loan intake, eligibility validation and multi-stage approvals, built around a state-driven workflow engine with optimistic locking to keep concurrent approvals from landing in invalid states. **API response times reduced 30%.** | Java 17 · Spring Boot · JPA/Hibernate · MySQL · Redis · JUnit 5 · Mockito |
| **ASL Gesture Recognition** &nbsp;<sub>Graduate research</sub> | PyTorch pipeline for 24 static ASL gestures. Transfer learning with ResNet-18 lifted test accuracy from 13.21% to 43.36% and macro-F1 from 0.081 to 0.351, with macro-F1 tracked alongside accuracy so class imbalance couldn't hide the gains. | Python · PyTorch · ResNet-18 |

---

## Education & Credentials

- **M.S. Computer Science** — University of Alabama at Birmingham *(Jan 2024 – Dec 2025)*
  <sub>Database Systems · Software Design & Integration · Machine Learning · Deep Learning · Computer Vision · Network, Computer & Cloud Security</sub>
- **B.Tech Computer Science** — Jawaharlal Nehru Technological University Hyderabad *(2019 – 2023)*
  <sub>Data Structures & Algorithms · Operating Systems · Distributed Systems · Compiler Design · Cryptography & Network Security</sub>
- **AWS Cloud Architecting** and **AWS Machine Learning Foundations** — Amazon Web Services

---

<div align="center">

**Sugar Land, Texas** &nbsp;·&nbsp; open to backend and distributed-systems roles

[![LinkedIn](https://img.shields.io/badge/Connect_on_LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/jaswanth-narravula)
[![Email](https://img.shields.io/badge/Get_in_touch-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:jaswanthnarravula@gmail.com)

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:2563EB,40:1E3A8A,100:0F172A&height=100&section=footer" width="100%"/>

</div>
