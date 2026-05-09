# Felix Mutinda Isaiah

**Staff ML Platform Architect** | **Feature Infrastructure** | **DevSecMLOps** | **Distributed Systems**

I architect production ML infrastructure for regulated industries at enterprise scale—specializing in feature platforms, governance-by-design, and DevSecMLOps patterns that enable velocity without compromising security or observability.

Currently building distributed feature engineering platforms, compliance automation, and unified observability at **Safaricom** (50M+ users, 50+ data science teams).

---

## What I Build

- **Multi-tenant Feature Platforms**: Configuration-driven infrastructure with contract-first SDKs, zero-migration adoption, and automatic lineage
- **Governance-by-Design Systems**: PII detection/masking (HMAC-SHA256, AST inspection) embedded in feature pipelines; compliance as code
- **Unified ML Observability**: Correlating model performance, data drift, and infrastructure health; reducing MTTR by ~90%
- **DevSecMLOps Pipelines**: CI/CD aligned to OWASP ML Top 10, NIST AI RMF, CIS Controls v8; security gates as default
- **Architecture Decision Records**: Documented trade-offs, constraints, and long-term vision as organizational knowledge artifacts

---

## Current Focus

- Real-time feature engineering on Apache Doris + dbt Core + MetricFlow
- ML platform architecture for regulated industries (telco, fintech, health)
- Building technical standards, mentoring senior engineers, and leveling frameworks
- Contributing to open-source MLOps tooling (dbt-Doris integration, local dev stacks)

---

## Featured Work

### 📚 Case Studies & Architecture Documentation
Production ML platform challenges, design decisions, and outcomes—sanitized for public sharing.

- [Distributed Feature Engineering for 50+ Teams](./mlops-case-studies/01-distributed-features) — 3-4 weeks → 5-7 days delivery cycle
- [Custom Feature Store vs. Off-the-Shelf: Decision Analysis](./mlops-case-studies/02-feature-store) — Constraints, trade-offs, outcomes
- [PII Governance in Production ML](./mlops-case-studies/03-pii-governance) — Compliance as code, not process
- [DevSecMLOps: Mapping Frameworks to CI/CD](./mlops-case-studies/04-devsecmlops) — OWASP, NIST, CIS, MITRE ATLAS

### 🧭 Architecture Decision Records (ADRs)
Lightweight ADRs documenting decisions shaping platform evolution.

- [ADR-001: Custom Feature Store Architecture](./adr-registry/0001-custom-feature-store.md)
- [ADR-002: Apache Doris for Real-Time Features](./adr-registry/0002-doris-rt-features.md)
- [ADR-003: PII Governance Layer Design](./adr-registry/0003-pii-governance.md)
- [ADR-004: Medallion Architecture for Payments Domain](./adr-registry/0004-medallion-payments.md)

### 🛠️ Reference Implementations (Sanitized)
Architecture patterns and design decisions—no proprietary code.

- [`feature-store-reference`](./feature-store-reference) — Multi-backend SDK patterns, governance hooks, TDD harness
- [`ml-observability-dashboard`](./ml-observability-dashboard) — Grafana configs, metrics schema, alerting patterns
- [`open-source-mlops-stack`](./open-source-mlops-stack) — MicroK8s + Kubeflow + Juju + MLflow + dbt + Doris (local dev)

### 🌐 Open-Source Contributions
- **dbt-Doris**: Active contributor to dbt-doris adapter (Spark-to-Doris translation, SCD Type 2, partition optimization)
- **MLOps Community**: Regular contributor of architecture patterns and compliance frameworks

---

## Architecture & Decision Philosophy

Platform architecture isn't about tools—it's about **constraint navigation**. Every system I design answers three questions:
1. What bottleneck does this remove for engineering teams?
2. How does this encode compliance, observability, or reliability by default?
3. What trade-offs are we accepting, and why?

I document decisions publicly (ADRs), measure adoption quantitatively, and treat infrastructure as a product. The best platforms are invisible: teams think about models, not pipelines.

---

## Technical Stack

**Cloud & Infrastructure**: AWS (SageMaker, Glue, Lambda, EMR), Kubernetes, Terraform, Docker, MicroK8s, Juju  
**Data Platforms**: Apache Doris, PostgreSQL, DuckDB, Redis, Kafka, dbt Core, MetricFlow  
**ML Tooling**: MLflow, Charmed Kubeflow, MLRun, Feature Store patterns, Model registry & lineage  
**Languages**: Python, SQL, Scala, sqlglot, Arrow  
**Governance**: OWASP ML Top 10, NIST AI RMF, CIS Controls v8, MITRE ATLAS, OPA/Rego, HMAC-SHA256

---

## Connect

- **LinkedIn**: [linkedin.com/in/felix-isaiah](https://linkedin.com/in/felix-isaiah-9a026b158)
- **Email**: [1mutindafelix@gmail.com](mailto:1mutindafelix@gmail.com)
- **Location**: Nairobi, Kenya
- **Portfolio**: [felix-mutinda.github.io](https://felix-mutinda.github.io)

---

> *"The best platform architecture solves constraints, not just technical problems."*
