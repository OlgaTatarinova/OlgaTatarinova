<div align="center">

# Olga Tatarinova

**Senior Data Engineer · Real-Time Data Platform Specialist**

*Building the infrastructure that turns raw events into business intelligence*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/olgatatarinova/)
[![Email](https://img.shields.io/badge/Email_Me-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:olga.tatarinova.work@gmail.com)
[![Location](https://img.shields.io/badge/📍_Nha_Trang,_Vietnam-gray?style=for-the-badge)](https://github.com/OlgaTatarinova)

</div>

---

## About Me

I'm a Senior Data Engineer with 5+ years building production data platforms for high-load e-commerce systems. Currently at **Wildberries** (one of Europe's largest e-commerce platforms), where I design and operate analytics infrastructure processing millions of events per day.

I specialize in the intersection of **real-time streaming** and **analytical workloads** — the hard problems that happen when you need both sub-second latency and historical query performance at scale.

```
PostgreSQL → Debezium CDC → Kafka → Flink → Delta Lake → dbt → ClickHouse → Grafana
```

---

## Core Stack

<table>
  <tr>
    <td valign="top" width="33%">

**Streaming & Messaging**
- Apache Kafka
- Apache Flink (exactly-once)
- Apache Spark (PySpark)
- Debezium CDC
- Avro + Schema Registry

    </td>
    <td valign="top" width="33%">

**Storage & Processing**
- ClickHouse (OLAP)
- Delta Lake / Apache Iceberg
- PostgreSQL · Greenplum
- AWS Redshift

    </td>
    <td valign="top" width="33%">

**Transformation & Orchestration**
- dbt Core (Silver/Gold layers)
- Apache Airflow (40+ DAGs)
- Great Expectations
- DataHub (data lineage)

    </td>
  </tr>
  <tr>
    <td valign="top">

**Cloud & Infrastructure**
- AWS (S3, Lambda, EC2, Redshift, Kinesis, Glue, SageMaker)
- Yandex Cloud
- Docker · Kubernetes · Terraform
- GitLab CI/CD

    </td>
    <td valign="top">

**Observability**
- Prometheus · Grafana
- Alertmanager (P0/P1/P2)
- Loki · Promtail
- Superset · Redash · DataLens

    </td>
    <td valign="top">

**Languages**
- SQL (advanced)
- Python
- English — fluent
- Chinese — conversational
- Russian — native

    </td>
  </tr>
  <tr>
    <td valign="top" colspan="3">

**AI-Augmented Development**
- Claude API · OpenAI API · LLM API integration
- Prompt Engineering (chain-of-thought, structured outputs, tool use)
- Claude Code (agentic coding workflows)
- AI-assisted code review, SQL generation, documentation
- LLM-powered data pipeline automation

    </td>
  </tr>
</table>

---

## Featured Projects

### 🏭 [E-Commerce Data Platform](https://github.com/OlgaTatarinova/ecommerce-data-platform)
> Production-grade local data platform — from CDC to ML predictions

A complete end-to-end data platform built with open-source tooling. Demonstrates real-world patterns: **exactly-once Flink**, **Avro schema evolution**, **Data Contracts**, full observability stack, and troubleshooting runbooks.

```
CDC (Debezium) → Kafka → Flink (exactly-once) → Delta Lake → dbt → Superset + Grafana
                                                                  ↳ MLflow → SageMaker
```

**Key features:** Schema Registry · Data Contracts · 5 Troubleshooting Runbooks · GDPR/PII masking · `make demo` one-command setup

[![Python](https://img.shields.io/badge/Python-3.11-blue?logo=python)](.)
[![Apache Flink](https://img.shields.io/badge/Flink-1.18-orange?logo=apacheflink)](.)
[![dbt](https://img.shields.io/badge/dbt-1.7-red?logo=dbt)](.)
[![Delta Lake](https://img.shields.io/badge/Delta_Lake-3.0-blue)](.)

---

### ☁️ [AWS E-Commerce Analytics Platform](https://github.com/OlgaTatarinova/aws-ecommerce-analytics)
> Cloud-native data platform on AWS — Kinesis · Glue · Iceberg · SageMaker

A 12-week portfolio project targeting **AWS Data Engineer Associate** certification. Implements a full Medallion architecture on AWS: real-time ingestion via Kinesis, S3 Lakehouse with Apache Iceberg, batch processing through AWS Glue + dbt, Flink anomaly detection, and MLOps pipeline with SageMaker + MLflow.

**Phases:** Foundation → Lakehouse → Batch (dbt) → Real-Time (Flink) → ML (Churn Prediction) → Serving (QuickSight)

[![AWS](https://img.shields.io/badge/AWS-Certified_Track-FF9900?logo=amazon-aws)](.)
[![Apache Iceberg](https://img.shields.io/badge/Iceberg-ACID_Tables-blue)](.)
[![SageMaker](https://img.shields.io/badge/SageMaker-MLOps-green)](.)

---

## Professional Experience Highlights

**Wildberries** · Senior Data Engineer / Tech Lead *(Dec 2025 — present)*
- Designed a **6-layer hybrid Kappa architecture** (Ingestion → Staging → Entities → Speed → Batch → Serving) processing **700M+ events/hour** from Kafka
- Built sharded ClickHouse cluster: sipHash64 partitioning, Buffer Engine for compaction, ReplicatedReplacingMergeTree for entity tracking
- Introduced Entities layer consolidating status lifecycles across **1.2B+ rows**, eliminating full-scans and enabling lineage tracking
- Optimized dashboards: pre-aggregated Serving layer reduced scan volume from **1.2M rows → 1,000 (~1000x speedup)**
- Implemented Rolling Backfill with 8-day recalculation window — 100% accuracy under delays up to 186 hours
- Led team of 3 engineers: code review, branching strategy, CI/CD (trunk-based Git)
- Analyzed 130,000+ lines of SQL across 4 business domains, 60+ dashboards, 20+ materialized views

**Wildberries** · Senior Data Engineer *(Apr 2024 — Dec 2025)*
- Built Medallion architecture (Bronze/Silver/Gold) from scratch on ClickHouse — first structured data platform for the team
- Designed Data Mesh across 5 products: each department as an independent data domain owner
- Deployed alerting for Kafka, ClickHouse, Airflow with 3-tier escalation (P0/P1/P2)
- **Doubled warehouse processing speed**, reduced inventory losses by **80%**

**CandyCat** · Senior Data Engineer *(Aug 2023 — Jun 2024)*
- Built real-time CDC pipeline: Debezium (PostgreSQL) → Kafka → Flink (streaming) + Spark (batch) — reduced data delivery latency **from 4 hours to 30 seconds**
- Built Apache Iceberg lakehouse with ACID guarantees and schema evolution — **reduced storage costs by 35%** via compaction and partitioning
- Orchestrated 40+ Airflow DAGs, dbt transformations, Terraform + Docker infrastructure
- Implemented AWS analytics: S3 data lake, Lambda for event processing, EC2 for batch, Redshift for OLAP

**Kata Academy** · Middle / Senior Data Engineer *(Feb 2022 — Aug 2023)*
- Built analytics system from scratch: PostgreSQL schema (3NF) + ETL pipelines to ClickHouse
- Created 50+ dashboards in DataLens and Superset for marketing and product teams
- Automated reporting — **reduced manual work by 50%**, weekly report prep from **8 hours → 15 minutes**
- Deployed and administered analytics infrastructure in Yandex Cloud

---

## What I'm Working On

- 🔨 **Production Hardening** of the E-Commerce Data Platform: Schema Registry, Data Contracts, troubleshooting runbooks
- 📚 **AWS Data Engineer Associate** certification (DEA-C01)
- 🤖 Exploring **MLOps** as a growth path — Feature Stores, model monitoring, retraining pipelines
- 📝 Writing ADRs (Architecture Decision Records) on Flink vs Spark, Delta Lake vs Iceberg

---

## GitHub Stats

<div align="center">

![Olga's GitHub Stats](https://github-readme-stats.vercel.app/api?username=OlgaTatarinova&show_icons=true&theme=dark&hide_border=true&bg_color=0d1117&title_color=FF6B35&icon_color=FF6B35)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=OlgaTatarinova&layout=compact&theme=dark&hide_border=true&bg_color=0d1117&title_color=FF6B35)

</div>

---

## Let's Connect

I'm actively looking for **remote Senior/Staff Data Engineer** roles at international companies — particularly those working on real-time data platforms, streaming analytics, or MLOps infrastructure.

> **Interested in:** Tinybird · DoubleCloud · Altinity · adtech/fintech scale-ups

[![LinkedIn](https://img.shields.io/badge/Connect_on_LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/olgatatarinova/)
[![Email](https://img.shields.io/badge/Email_Me-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:olga.tatarinova.work@gmail.com)

---

<div align="center">
<sub>Built with ☕ and ClickHouse queries in Nha Trang, Vietnam 🌊</sub>
</div>
