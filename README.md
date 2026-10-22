# Hi, I'm Aira Jena 👋

**Backend engineer building fast, correct financial systems.**
Go · Java · PostgreSQL · Distributed Systems · Open Source

SDE-I at BLG Technologies (remote) · Google Summer of Code 2026 contributor at Apache Fineract · 40+ merged open-source PRs · LeetCode Knight (top 2%, peak rating 2058)

Based in India, working remotely and async-first. Open to full-time and contract roles with startups and international teams.

📫 [airajena.work@gmail.com](mailto:airajena.work@gmail.com) · 🌐 [airajena.in](https://airajena.in) · [LinkedIn](https://www.linkedin.com/in/aira-jena/) · [X](https://twitter.com/Oxaira)

---

## What I've shipped (with numbers)

| Impact | What I did |
|---|---|
| **97% faster API** (21s → 500ms) | Rebuilt a financial reporting pipeline with dependency-aware goroutine fan-out, materialized snapshots (removed 13.7s of recomputation) and multi-tier TTL caching |
| **200× throughput** (50 → 10K+ tenders/day) | Designed a multi-tenant, multi-vendor processing pipeline with parallel workers, fault-tolerant retries, LLM scoring and PDF/OCR extraction |
| **87.5% faster pages** (8s → 1s), **99.3% smaller payload** (2MB → 15KB) | Replaced full-table rendering and N+1 lookups with server-side pagination, indexed queries and caching in a Java backend serving 1000+ daily users |
| **1 round-trip per batch** instead of per-row inserts | Rewrote a Tally import as `unnest()` set-inserts using `WITH ORDINALITY` to resolve foreign keys in order, inside atomic versioned transactions |
| **30% lower cloud cost, 75% faster deploys** | Provisioned multi-region AWS with Terraform (50+ resources) and built a zero-downtime CI/CD pipeline |

Other work I'm proud of: an offline licensing system (HMAC-SHA256 tokens, machine binding, anti-clock-rollback), and an LLM ledger classifier whose output space is enforced in code so hallucinated categories never reach a financial statement.

---

## Open source

- **Google Summer of Code 2026, Apache Fineract**: building an end-to-end Business Intelligence platform for the core banking system: a 4-service Docker stack with a watermark-based CDC extractor, a layered dbt pipeline (raw → staging → facts → marts), and Apache Superset dashboards with row-level security (PAR-30/60/90, NPA).
- **[Apache Fineract](https://github.com/apache/fineract)**: shipped the Slack Chat Archive MVP (FINERACT-2171) and led the site migration from static HTML to Hugo, including CI/CD.
- **[Apache ShenYu](https://github.com/apache/shenyu)** and **Eclipse**: concurrency and infrastructure improvements.

---

## Featured projects

- **HexRide**: distributed ride-sharing platform with 8 microservices, conflict-free driver matching via H3 geospatial indexing, Resilience4j circuit breakers, and a full ELK + Prometheus + Grafana stack. *(Java, Spring Boot, PostgreSQL, Redis, Kafka)*
- **Multi-Threaded Web Server**: NIO2 server handling 50,000+ req/s at sub-100ms P95, with a custom HTTP/2 parser and Kafka streaming for 1M+ events/day. *(Java, Kafka, Redis, Docker)*

---

## Tech I work with

| | |
|---|---|
| **Languages** | Go, Java, Python, SQL, JavaScript, Bash |
| **Backend** | Spring Boot, Spring Cloud, Hibernate, REST APIs, Flask |
| **Data** | PostgreSQL, MySQL, MongoDB, Redis, dbt, Apache Superset |
| **Messaging & Distributed** | Kafka, RabbitMQ, Resilience4j, Eureka |
| **Cloud & DevOps** | AWS, Terraform, Docker, Kubernetes, GitHub Actions |
| **Observability** | Prometheus, Grafana, ELK, Zipkin |
| **AI** | pydantic-ai, OpenAI API, structured-output pipelines |

---

## Recognition

- National Finalist, Smart Odisha · National Semi-Finalist, Flipkart Grid and Tata Imagination Challenge (400K+ participants)
- 3× Oracle certified: OCI Developer Professional, OCI DevOps Professional, Oracle Agentic AI Foundations Associate

---

**Let's talk** if you're building something where performance, correctness, or data-heavy backends matter. Email works best.
