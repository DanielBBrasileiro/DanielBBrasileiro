# README.md

<div align="center">

# Daniel Barbosa Brasileiro

### Data Engineering · Analytics · BI

**Accounting context. Engineering mindset. Data quality first.**

<img
src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=21&duration=2800&pause=900&color=2496ED&center=true&vCenter=true&width=760&lines=From+raw+data+to+reliable+decisions;SQL+%2B+Python+%2B+Data+Quality+%2B+BI;Accounting+context.+Engineering+mindset.;Building+pipelines+that+can+be+explained+and+audited"
alt="Typing SVG"
/>

<br />

<a href="https://www.linkedin.com/in/daniel-barbosa-brasileiro">
  <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" />
</a>
<a href="mailto:danielbarbosabrasileiro@gmail.com">
  <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
</a>
<a href="https://github.com/DanielBBrasileiro">
  <img src="https://img.shields.io/badge/GitHub-Portfolio-181717?style=for-the-badge&logo=github&logoColor=white" />
</a>

</div>

---

## What I do

I build **data products that turn messy operational data into reliable, traceable, and decision-ready information**.

My background in **Accounting** gives me a strong bias toward controls, reconciliation, business meaning, and auditability. My technical work brings that mindset into **SQL, Python, data pipelines, analytical modeling, automation, and BI**.

I am especially interested in problems where data needs to move from:

**raw → validated → modeled → useful**

My work and projects cover:

* data ingestion, transformation, and ETL/ELT workflows;
* SQL modeling, validation, reconciliation, and data quality;
* Python automation and API/file processing;
* analytical models and business metrics;
* Power BI and Tableau reporting;
* reproducible environments, testing, CI, and documentation.

---

# Featured work

## 🏦 FinBank Risk Lakehouse

### From synthetic banking data to validated analytical products

**Python · Rust · dbt · DuckDB · PostgreSQL · Streamlit · GitHub Actions**

[Explore FinBank Risk Lakehouse →](https://github.com/DanielBBrasileiro/finbank-risk-lakehouse)

FinBank is an end-to-end banking-risk data platform built to follow data from **source ingestion to an analyst-facing product**.

The project includes:

* deterministic financial datasets for reproducible testing;
* Python ingestion pipelines;
* Rust-based source contract validation;
* Bronze, Silver, and Gold data layers;
* dbt staging, intermediate, and mart models;
* data quality and reconciliation checks;
* idempotent event replay;
* DuckDB and PostgreSQL execution paths;
* automated CI and security checks;
* a Streamlit credit-risk dashboard;
* documented cloud extension paths.

<a href="https://github.com/DanielBBrasileiro/finbank-risk-lakehouse">
  <img
    src="https://raw.githubusercontent.com/DanielBBrasileiro/finbank-risk-lakehouse/main/docs/portfolio/screenshots/architecture-overview.svg"
    alt="FinBank Risk Lakehouse architecture"
    width="100%"
  />
</a>

> **What it demonstrates:** analytical engineering, data contracts, dimensional thinking, quality controls, reproducibility, CI, and financial-data context.

---

## 🇧🇷 CNPJ Analytics & Compliance Pipeline

### Turning Brazilian public-company files into an analytical data platform

**Python · Pandas · MinIO · Parquet · PostgreSQL · Docker · Streamlit**

[Explore CNPJ Analytics Pipeline →](https://github.com/DanielBBrasileiro/cnpj-analytics-pipeline)

An end-to-end data engineering project built around public Brazilian company data.

```text
Receita Federal data
        ↓
Bronze — raw files / MinIO
        ↓
Silver — cleaned Parquet datasets
        ↓
Gold — PostgreSQL analytical layer
        ↓
Streamlit
```

The project focuses on:

* reproducible ingestion;
* chunked processing for large files;
* schema and type normalization;
* S3-compatible object storage;
* analytical persistence in PostgreSQL;
* Docker-based local infrastructure;
* data exploration through Streamlit.

> **What it demonstrates:** ingestion, batch processing, data-layer architecture, relational storage, Docker, and working with public data at scale.

---

# How I think about data

```mermaid
flowchart LR
    A["Raw Sources"] --> B["Ingest"]
    B --> C["Validate"]
    C --> D["Transform"]
    D --> E["Model"]
    E --> F["Serve"]
    F --> G["Decision"]

    C -. "quality checks" .-> Q["Reconcile"]
    Q -. "trust" .-> E
```

For me, a pipeline is not finished when the data arrives.

It is finished when the result is **understandable, reproducible, reconciled, and useful to someone making a decision**.

---

# Toolbox

### Core

![Python](https://img.shields.io/badge/Python-3670A0?style=flat-square\&logo=python\&logoColor=ffdd54)
![SQL](https://img.shields.io/badge/SQL-336791?style=flat-square\&logo=postgresql\&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square\&logo=postgresql\&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square\&logo=pandas\&logoColor=white)
![Excel](https://img.shields.io/badge/Excel-217346?style=flat-square\&logo=microsoftexcel\&logoColor=white)

### Data Engineering & Analytics Engineering

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square\&logo=docker\&logoColor=white)
![dbt](https://img.shields.io/badge/dbt-FF694B?style=flat-square\&logo=dbt\&logoColor=white)
![DuckDB](https://img.shields.io/badge/DuckDB-FFF000?style=flat-square\&logo=duckdb\&logoColor=black)
![MinIO](https://img.shields.io/badge/MinIO-C72E49?style=flat-square\&logo=minio\&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square\&logo=githubactions\&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square\&logo=git\&logoColor=white)

### BI & Analytics

![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=flat-square\&logo=powerbi\&logoColor=black)
![Tableau](https://img.shields.io/badge/Tableau-E97627?style=flat-square\&logo=tableau\&logoColor=white)
![DAX](https://img.shields.io/badge/DAX-Power_BI-F2C811?style=flat-square)

### Building with

`Rust` · `Airflow` · `Dagster` · `AWS` · `Data Lakehouse patterns` · `AI-assisted analytics`

---

# The principles behind my projects

**Reliable > flashy.**
A beautiful dashboard cannot rescue unreliable data.

**Define the grain first.**
Good analytics starts by understanding what one row actually represents.

**Reconcile before celebrating.**
If the destination cannot be explained against the source, the pipeline is not done.

**Automate what repeats.**
Repeated manual work is usually an opportunity for code, validation, or better process design.

**Business meaning matters.**
Technically valid data can still be analytically wrong.

**Documentation is part of the product.**
Someone else should be able to understand what was built, how it works, and where its limits are.

---

# Current direction

I am continuing to deepen my work around:

**Data Engineering · Analytics Engineering · Data Quality · Financial Data · BI · Automation**

with a particular interest in systems that are **reliable, auditable, reproducible, and useful in real business decisions**.

---

<div align="center">

### raw → validated → modeled → decision

<br />

**Let's connect**

<a href="https://www.linkedin.com/in/daniel-barbosa-brasileiro">LinkedIn</a>
 •  <a href="mailto:danielbarbosabrasileiro@gmail.com">Email</a>

</div>
