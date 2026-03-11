<div align="center">

# Olga Tatarinova

**Senior Data Engineer · Real-Time Data Platform Specialist**

*Building the infrastructure that turns raw events into business intelligence*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/olgatatarinova/)
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
- Apache Kafka · MSK
- Apache Flink (exactly-once)
- Debezium CDC
- Avro + Schema Registry

    </td>
    <td valign="top" width="33%">

**Storage & Processing**
- ClickHouse (OLAP)
- Delta Lake / Apache Iceberg
- Apache Spark
- PostgreSQL

    </td>
    <td valign="top" width="33%">

**Transformation & Orchestration**
- dbt Core (Silver/Gold layers)
- Apache Airflow · MWAA
- Great Expectations
- DataHub (data lineage)

    </td>
  </tr>
  <tr>
    <td valign="top">

**Cloud & Infrastructure**
- AWS (S3, Kinesis, Glue, SageMaker)
- Yandex Cloud
- Docker · Kubernetes
- Terraform

    </td>
    <td valign="top">

**Observability**
- Prometheus · Grafana
- Loki · Promtail
- Alertmanager
- OpenTelemetry

    </td>
    <td valign="top">

**MLOps**
- MLflow · SageMaker
- Feature Store
- Model Monitor
- XGBoost · LightGBM

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

**Wildberries** · Senior Data Engineer *(current)*
- Built ClickHouse analytics for sorting center performance metrics — 226 objects across 20 database schemas
- Designed Kafka/Flink streaming pipeline processing **700M+ events/hour**
- Led migration from legacy ClickHouse cluster to new 3-node architecture with zero downtime
- Debugged production MV (materialized view) bugs in distributed ClickHouse cluster

**CandyCat** · Data Engineer / Product Analyst
- A/B testing infrastructure → AOV **+8.94%**
- RFM segmentation → CAC **-2.73%**
- ARIMA demand forecasting, reducing overstock by ~15%

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

[![LinkedIn](https://img.shields.io/badge/Connect_on_LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/olga-tatarinova)
[![Email](https://img.shields.io/badge/Email_Me-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:your@email.com)

---

<div align="center">
<sub>Built with ☕ and ClickHouse queries in Nha Trang, Vietnam 🌊</sub>
</div>
