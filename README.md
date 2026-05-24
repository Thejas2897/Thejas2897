# Thejas Manjunath — DevOps / SRE / Platform Engineer

I build reliable, observable, and compliant infrastructure. Two years of production SRE work across a GxP-regulated pharma platform (Deloitte) and a live fintech trading system (QiCAP Markets) — with a focus on performance engineering, compliance-aware CI/CD, and incident reduction.

**What I work on:**

- Redis performance engineering — empirical benchmarking, latency tuning, production-readiness validation
- End-to-end platform engineering — Terraform → EKS → CI/CD → Observability → Chaos
- Compliance-aware CI/CD — audit trails, change-control gating, S3 Object Lock, Vault secrets
- Observability — Prometheus, Grafana, ELK, 4 Golden Signals instrumentation, AlertManager
- Kafka event pipelines — producer/consumer patterns, consumer lag alerting, broker failure recovery
- Chaos engineering — LitmusChaos experiments, steady-state hypothesis, SLO impact documentation

**Current focus:** Targeting DevOps / SRE / Platform Engineering roles at Tier 1 and Tier 2 product and fintech companies in Bengaluru.

---

## Projects

| Project | What it demonstrates | Status |
|---|---|---|
| [sre-platform-demo](https://github.com/Thejas2897/sre-platform-demo) | End-to-end: Terraform → EKS → Jenkins CI/CD → Prometheus/Grafana/ELK → LitmusChaos | 🔨 Building |
| [redis-performance-toolkit](https://github.com/Thejas2897/redis-performance-toolkit) | Empirical Redis benchmarking — 9x latency reduction, 371% throughput, documented null results | ✅ Complete |
| [compliance-cicd-pipeline](https://github.com/Thejas2897/compliance-cicd-pipeline) | FDA 21 CFR Part 11 → SOX/PCI-DSS bridge — audit trail, Trivy gates, Vault secrets | 🔨 Building |
| [observability-stack](https://github.com/Thejas2897/observability-stack) | Prometheus + Grafana 4 Golden Signals + ELK + AlertManager — 2 of 3 observability pillars | ✅ Complete |
| [kafka-monitoring-pipeline](https://github.com/Thejas2897/kafka-monitoring-pipeline) | 3-broker Kafka — consumer lag alerting, broker failure recovery, Prometheus JMX | 🔨 Building |
| [chaos-engineering-lab](https://github.com/Thejas2897/chaos-engineering-lab) | LitmusChaos on K8s — pod-delete, network-loss, cpu-hog with SLO impact documented | 🔨 Building |
| [aiops-incident-responder](https://github.com/Thejas2897/aiops-incident-responder) | Isolation Forest anomaly detection + LLM-generated incident summaries → Slack | 🔨 Building |

---

## Measured Results Worth Knowing

- **95% reduction** in pre-release validation time — 47 manual checks → 12 minutes
- **9x p50 write latency reduction** — Redis appendfsync tuning, benchmarked on production-equivalent bare-metal hardware
- **371% SET throughput increase** — same tuning exercise, 100k mixed-workload benchmark on bare-metal hardware
- **Zero slow-query log entries** — empirically proved SCAN vs KEYS blocking behaviour on bare-metal benchmark
- **14+ unauthorized infrastructure changes caught** — daily Terraform drift detection before deployment failures
- **~95% → 99.6% trading-day prep success rate** — CI/CD modernisation on live trading platform
- **30 min → 90 sec rollback time** — atomic symlink-swap rollback, shadow-tested on staging hosts

---

## Stack

**Infrastructure:** AWS (EC2, S3, EKS, IAM, SCPs, CloudWatch, Secrets Manager), Terraform, Docker, Linux  
**Orchestration:** Kubernetes (EKS), Helm  
**CI/CD:** Jenkins, GitHub Actions  
**Observability:** Prometheus, Grafana, ELK Stack, Splunk, AlertManager  
**Security & Compliance:** FDA 21 CFR Part 11, GxP, SOX/PCI-DSS awareness, Vault, Trivy  
**Data / Messaging:** Redis, Kafka, SQL  
**Languages:** Python, Bash, Go  

---

*Based in Bengaluru. Open to DevOps, SRE, and Platform Engineer roles.*  
*[LinkedIn](https://linkedin.com/in/thejas-manjunath)*
