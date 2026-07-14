# Thejas Manjunath — DevOps / Site Reliability Engineer

DevOps / SRE with 2 years of production experience across GxP-regulated (Deloitte) and fintech (QiCAP Markets) environments — including hands-on FDA 21 CFR Part 11 compliance depth. Delivered empirical Redis performance engineering (9x latency reduction, 371% throughput improvement) and CI/CD platform modernisation on a live trading system. Grounded in AWS, Python automation, Terraform IaC, and Splunk-based observability from a Deloitte platform-reliability role operating under 99.95% availability SLOs. Currently deepening Kubernetes, Prometheus, Grafana, ELK, and Kafka for cloud-native SRE roles.

**What I work on:**
- Redis performance engineering — empirical benchmarking, latency tuning, production-readiness validation
- CI/CD modernisation — crontab/script-based pipelines migrated to Temporal workflows, idempotent job design, atomic symlink-swap rollback
- Observability — Splunk, Prometheus, Grafana, ELK, OpenTelemetry
- Compliance-aware infrastructure — FDA 21 CFR Part 11 change-control, IAM/SCP least-privilege, Terraform drift detection as a continuous control
- Policy-as-code — OPA test cases for deploy-time guardrails (e.g. market-hours deploy blocks)

**Current focus:** Targeting SRE / DevOps roles at product and fintech companies.

---

## Featured Projects

| Project | What it demonstrates |
|---|---|
| [redis-performance-toolkit](https://github.com/Thejas2897/redis-performance-toolkit) | 6-node Redis Cluster simulation, 100k mixed-workload stress test, 9x p50 latency reduction, 371% throughput increase, 5-script backup/restore/migration toolkit with idempotent restore logic |
| [observability-stack](https://github.com/Thejas2897/observability-stack) | Metrics + logs stack — Prometheus, Grafana, ELK, AlertManager |
| [compliance-cicd-pipeline](https://github.com/Thejas2897/compliance-cicd-pipeline) | FDA 21 CFR Part 11 → SOX/PCI-DSS-style change-control gating, audit trail design |
| [kafka-monitoring-pipeline](https://github.com/Thejas2897/kafka-monitoring-pipeline) | Event-driven pipeline — Kafka, consumer lag alerting, broker failure recovery |
| [aiops-incident-responder](https://github.com/Thejas2897/aiops-incident-responder) | Anomaly detection + LLM-generated incident summaries |

---

## Production Numbers Worth Knowing

- **9x p50 write latency reduction** (1.103 ms → 0.127 ms) — Redis `appendfsync` tuning, measured on bare-metal hardware
- **371% SET throughput increase** — same tuning exercise, 100k mixed-workload benchmark
- **99,601 req/s throughput ceiling** measured on a 6-node Redis Cluster simulation, with a connection-flood bug diagnosed and fixed via a shared bounded connection pool (zero request loss)
- **~50 → 0 slow-query log entries**, and BGSAVE fork-spike (49 ms) eliminated through 14-parameter tuning across 6 config groups
- **Rollback time cut from ~30 min to under 90 sec** — atomic symlink-swap rollback shadow-tested on staging
- **Trading-day prep success rate: ~95% → 99.6%** over a phased CI/CD modernisation rollout
- **95% reduction in pre-release validation time** — 47 manual health checks automated, ~4 hrs → 12 min (Deloitte)
- **14+ unauthorized infrastructure changes caught** — daily Terraform drift detection before deployment failures (Deloitte)
- **Post-mortem reconstruction time cut from ~4–6 hrs to ~90 min** — Splunk + CloudWatch incident dashboards (Deloitte)

---

## Stack

**Cloud & Infrastructure:** AWS (EC2, VPC, ALB, RDS, S3, IAM, CloudWatch, Secrets Manager, ECR), Terraform, Linux/Bash
**CI/CD:** Jenkins, GitHub Actions, Docker & Docker Compose, Temporal, OPA
**Containers & Orchestration:** Kubernetes (Deployments, Services, ConfigMaps, Helm)
**Observability:** Splunk, Prometheus, Grafana, ELK Stack, OpenTelemetry
**Data / Caching:** Redis (cluster, tuning, slowlog, backup/restore), SQL
**Languages:** Python, Bash, Go
**Compliance:** FDA 21 CFR Part 11, GxP audit trails, IAM/SCP least-privilege, 99.95% SLA operations

---

## Background

- **QiCAP Markets** (Jan–Apr 2026) — DevOps/Infrastructure intern on a live trading platform: Redis performance engineering, and CI/CD migration from crontab scripts to Temporal workflows
- **Deloitte USI** (2019–2021) — Analyst on a GxP-regulated platform-reliability role: toil automation, Terraform drift detection, Splunk observability, FDA 21 CFR Part 11 change-control
- **2022–2025** — Full-time UPSC (Civil Services) preparation, returning to technical depth in the latter part before re-entering industry via QiCAP Markets in 2026
- **B.E. Electronics & Communication Engineering**, CMRIT, Bengaluru (2019)

---

*Open to DevOps / SRE roles. Based in Bengaluru.*
*[LinkedIn](https://linkedin.com/in/thejas-manjunath)*
