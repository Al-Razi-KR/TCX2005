# L9 Part 3 — BI Analytics and Operational Intelligence

**Source:** Auto-generated captions from `L9_Part-3_BI-Analytics-and-Operational-Intelligence` video

---

## BI Analytical Tools

Modern BI systems go far beyond simple reporting to enable **predictive and prescriptive analytics**.

| Tool | What It Does | Example |
|---|---|---|
| **OLAP** (Online Analytical Processing) | Examine data from multiple dimensions; drill down into details | Retail manager analyses sales by product category × region × time period simultaneously |
| **Statistical Analysis** | Apply mathematical techniques to identify correlations and validate models | Manufacturing company uses regression to understand relationship between production variables and product quality |
| **Data Mining** | Discover hidden patterns in large datasets; reveals non-obvious relationships | Telecoms company identifies customer behaviour patterns that predict churn |

---

## The BI Environment: 6 Key Elements

A complete BI environment requires all six elements working together to transform raw data into decision support.

| # | Element | Description |
|---|---|---|
| 1 | **Data from the Business Environment** | Transactional data, customer interactions, supplier info, and external data (social media, IoT, third-party). Quality and comprehensiveness directly impact decision quality. |
| 2 | **BI Infrastructure** | Data warehouses (consolidate from multiple sources), data marts (function-specific), and ETL (Extract, Transform, Load) processes that prepare data for analysis. |
| 3 | **Business Analytics Toolset** | OLAP, statistical analysis, data mining, and increasingly AI/ML — identify patterns, trends, and relationships not apparent through observation alone. |
| 4 | **Managerial Users and Methods** | Decision-making frameworks, management processes, and evaluation methods that translate insights into actions understood by business users. |
| 5 | **Delivery Platform** | Channels information to the right users: MIS for structured operational decisions, DSS for semi-structured tactical decisions, ESS for unstructured strategic decisions. |
| 6 | **User Interface** | How information is presented and interacted with — increasingly through dashboards, data visualisation, charts, and interactive graphics. |

---

## BI Analytical Capabilities

| Capability | Description |
|---|---|
| **Production Reports** | Standardised, regularly scheduled summaries (daily sales, monthly financials, quarterly inventory). Essential for monitoring operations. |
| **Parameterised Reports** | Customise standard reports by specifying date ranges, product categories, geographic regions — without technical skills. |
| **Dashboards and Scorecards** | Present KPIs visually for quick performance assessment; valuable for managers monitoring multiple areas simultaneously. |
| **Ad Hoc Query / Search** | Request specific information on demand, without waiting for scheduled reports or IT staff to create custom queries. |
| **Drill Down** | Move from summary → detail (e.g. overall sales → specific region → product → customer segment) to investigate unexpected trends. |
| **Forecasts, Scenarios and Models** | What-if analysis, predictive modelling, and simulations to explore potential future states and their business implications. |

---

## BI by Business Function

| Function | BI Applications |
|---|---|
| **Sales** | Forecast sales, monitor team performance, identify cross-selling opportunities, analyse sales cycle times → optimise resource allocation and conversion rates |
| **Service / Call Centre** | Track customer satisfaction, service costs, resolution rates, churn indicators → optimise staffing, identify training needs, improve retention |
| **Human Resources** | Measure employee productivity, analyse compensation patterns, understand workforce demographics, monitor retention rates → guide recruitment and development strategy |

> BI permeates virtually every aspect of the modern organisation, providing decision support tailored to each function's specific needs.

---

## Predictive Analytics

**Traditional analytics** = descriptive (what happened) or diagnostic (why it happened)  
**Predictive analytics** = focused on **what might happen in the future**

- Uses statistical techniques and machine learning algorithms on historical data to identify likelihood of future outcomes
- Identifies patterns and relationships in historical data → uses them to predict future events or behaviours
- Integrated across: sales, marketing, finance, fraud detection, healthcare

**Common examples:**

| Use Case | Description |
|---|---|
| **Credit Scoring** | Predicts likelihood a borrower will default based on financial history and characteristics |
| **Response Modelling** | Predicts which customers are most likely to respond positively to specific marketing offers |

> By moving from descriptive/diagnostic to **predictive** capabilities, organisations can make **proactive rather than reactive decisions** — a significant competitive advantage.

---

## Operational Intelligence

Traditional BI processes data in batches → insights arrive **hours or days** after events.

**Operational Intelligence** (also called *Business Activity Monitoring*) = **real-time analytics** on business operations:
- Monitors transaction streams, system status, and environmental conditions as they happen
- Enables **immediate response** to emerging situations

**Key driver:** Proliferation of **sensors and IoT devices** across manufacturing equipment, vehicle fleets, building systems, and consumer products → continuous data streams.

### Singapore Example: PSA Smart Port

| Capability | Application |
|---|---|
| Real-time container tracking | Optimise yard operations and minimise congestion |
| Predictive maintenance | Monitor equipment conditions to identify potential failures before they occur → reduce downtime and maintenance costs |
| Automated berth allocation | Optimise ship arrivals and departures based on real-time conditions → maximise throughput |

> Operational intelligence **closes the gap between insights and action** — systems can trigger immediate responses, automated workflows, or direct control of connected systems (e.g. auto-adjust production parameters based on quality measurements).

As business speeds up and more processes become digitised, operational intelligence is an increasingly important topic for new IS managers — both alongside and beyond traditional BI.
