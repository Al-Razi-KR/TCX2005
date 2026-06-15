# L7 Part 4 — Big Data and Business Intelligence

**Source:** Auto-generated captions from `L7_Part-4_Big-Data-and-Business-Intelligence` video

---

## DBMS Capabilities

| Capability | Description |
|---|---|
| **Data definition** | Administrators specify data structure — what fields exist, their types, and relationships. Stored in the **data dictionary** (a catalog of all data elements) |
| **Data manipulation language (DML)** | Tools to add, change, delete, or retrieve data — **SQL (Structured Query Language)** is the industry standard |
| **Report generation** | Platforms like Microsoft Access generate polished reports without additional programming, turning raw data into actionable information |

---

## Newer Database Technologies

**Non-relational databases (NoSQL)**
- Flexible alternative to traditional relational databases
- Store data across distributed machines; built to scale horizontally
- Ideal for massive volumes of structured and unstructured data: social media posts, images, sensor logs

**Cloud databases**
- Services like Amazon AWS or Microsoft Azure eliminate the need to manage infrastructure manually
- Private cloud deployments offer similar benefits with added control
- Instrumental in Astro's move to a modern Data Lake

---

## Big Data

> Big data refers to massive sets of unstructured and semi-structured data generated continuously from a variety of sources.

**Sources:** Web traffic, social media, sensor output, IoT devices

**Scale:** No longer gigabytes or terabytes — now **petabytes and exabytes**, far beyond the capacity of typical database systems.

**Value:** Reveals patterns, relationships, and anomalies that go undetected with traditional tools.

### Example — Retail Chain

| Data Type | Source |
|---|---|
| Structured | Point-of-sale data from cash registers |
| Semi-structured | Customer reviews (free text) |
| Unstructured | Security camera footage (video) |
| IoT | In-store movement patterns from floor sensors |

Traditional databases cannot manage this variety together — big data technologies are designed to integrate and analyse these diverse sources.

---

## Business Intelligence (BI) Infrastructure

The systems that collect, process, and transform data into valuable insights.

| Component | Role |
|---|---|
| **Data warehouse** | Consolidates data from operational systems; optimised for analysis and reporting, not real-time transactions |
| **Data marts** | Focused subsets of the warehouse tailored to specific business functions (e.g. sales data mart, financial data mart) |
| **Hadoop** | Distributed file system (HDFS) enabling scalable storage across multiple machines; uses **MapReduce** for parallel processing of large data volumes |
| **In-memory computing** | Stores data in RAM rather than on disk — reduces analysis time from hours to seconds; enables real-time decision-making |

### Data Flow (ETL Process)

**Extract → Transform → Load**

1. Multiple data sources (operational, historical, IoT, streaming, web/social, external third-party)
2. ETL process collects and processes data
3. Structured data → **data warehouse**; unstructured/high-volume → **Hadoop data lake**
4. Data available in data warehouse and data marts
5. Analytics platform extracts insights via data mining and real-time query
6. Delivered to:
   - **Casual users** — dashboards and pre-built reports for day-to-day decisions
   - **Power users (data scientists)** — deeper queries, trend analysis

> Key design principle: analytical workloads are separated from transactional systems so heavy analysis doesn't slow down day-to-day operations (e.g. order processing, payments).

---

## BI Tools

| Tool | Purpose |
|---|---|
| **OLAP (Online Analytical Processing)** | Examine data across multiple dimensions — by product, region, time period, customer segment. e.g. compare hardware sales in Eastern Region last June vs. other regions/months |
| **Data mining** | Uncover hidden patterns and build predictive models — e.g. identify customers likely to cancel a subscription or default on a loan |
| **Text mining** | Extract meaning from unstructured sources (emails, support tickets, reviews) — analyse sentiment, detect issues, categorise feedback at scale |
| **Web mining** | Analyse website data — user navigation, page visits, dwell time, content engagement and conversion |

---

## Data Quality and Governance

> More than **25% of critical data** in Fortune 1000 company databases is inaccurate or incomplete.

Poor data quality undermines all sophisticated analytics. Before implementing any new database system, organisations must identify and correct faulty data and establish routines for maintaining quality.

**Impact of poor data quality:**
- Wrong decisions based on faulty analysis
- Customer dissatisfaction from incorrect information
- Regulatory compliance failures
- Wasted resources chasing data errors

### Governance Framework

| Role | Responsibility |
|---|---|
| **Data Administration** | Creates and enforces specific policies and procedures for data handling |
| **Information Policy** | Rules for data sharing and management across the organisation |
| **Data Governance** | Broader oversight — manages data availability, usability, integrity and security; establishes standards, defines ownership, ensures regulatory compliance |
| **Quality Assurance** | Regular data quality audits, cleansing initiatives, and ongoing monitoring |

> Organisations like Astro succeed not just by implementing new technologies, but by establishing governance frameworks to ensure data remains accurate, consistent, and valuable.
