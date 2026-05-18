# Thejas Manjunath — SRE / DevOps / Platform Engineer

I build reliable, observable, and compliant infrastructure. Two years of production SRE work across a pharmaceutical GxP platform (Deloitte / Eli Lilly) and a financial data platform (QiCAP Markets), with a focus on performance engineering, compliance automation, and incident reduction.

**What I work on:**
- Redis performance engineering — empirical benchmarking, latency tuning, production-readiness validation
- Observability — Prometheus, Grafana, ELK, OpenTelemetry, 4 Golden Signals instrumentation
- Compliance-aware CI/CD — audit trails, change-control gating, S3 Object Lock, Vault secrets
- Kafka event pipelines — producer/consumer patterns, consumer lag alerting, broker failure recovery
- Chaos engineering — LitmusChaos experiments, steady-state hypothesis, SLO impact documentation

**Current focus:** Targeting SRE / Platform Engineer roles at Tier 1 and Tier 2 product and fintech companies.

---

## Featured Projects

| Project | What it demonstrates |
|---------|---------------------|
| [redis-performance-toolkit](https://github.com/Thejas2897/redis-performance-toolkit) | Empirical Redis benchmarking — 9x latency reduction, 371% throughput increase, documented null results |
| [observability-stack](https://github.com/Thejas2897/observability-stack) | Full metrics + logs stack — Prometheus, Grafana 4 Golden Signals, ELK, AlertManager |
| [compliance-cicd-pipeline](https://github.com/Thejas2897/compliance-cicd-pipeline) | FDA 21 CFR Part 11 → SOX/PCI-DSS bridge — audit trail, Trivy gates, Vault secrets |
| [kafka-monitoring-pipeline](https://github.com/Thejas2897/kafka-monitoring-pipeline) | Event-driven pipeline — 3-broker Kafka, consumer lag alerting, broker failure recovery |
| [aiops-incident-responder](https://github.com/Thejas2897/aiops-incident-responder) | Isolation Forest anomaly detection + LLM-generated incident summaries → Slack |

---

## Production Numbers Worth Knowing

- **95% reduction** in pre-release validation time — 47 manual checks → 12 minutes (Deloitte / Eli Lilly)
- **9x p50 write latency reduction** — Redis appendfsync tuning, measured on bare-metal hardware
- **371% SET throughput increase** — same tuning exercise, 100k mixed-workload benchmark
- **14+ unauthorized infrastructure changes caught** — daily Terraform drift detection before deployment failures
- **Zero slow-query log entries** — after replacing KEYS * with SCAN in production health checks

---

## Stack

**Infrastructure:** Kubernetes, Terraform, AWS (EC2, S3, EKS, IAM, SCPs), Docker  
**Observability:** Prometheus, Grafana, ELK, Jaeger, OpenTelemetry, Splunk  
**CI/CD:** Jenkins, GitHub Actions, Trivy, Vault  
**Data / Messaging:** Redis, Kafka, PostgreSQL  
**Languages:** Python, Bash, HCL  
**Compliance:** FDA 21 CFR Part 11, GxP, SOX, PCI-DSS awareness

---

*Open to SRE, DevOps, and Platform Engineer roles. Based in Bengaluru.*  
*GitHub: [Thejas2897](https://github.com/Thejas2897) · [LinkedIn](https://linkedin.com/in/thejas-manjunath)*
