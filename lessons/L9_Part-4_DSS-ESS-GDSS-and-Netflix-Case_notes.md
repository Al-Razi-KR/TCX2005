# L9 Part 4 — DSS, ESS, GDSS and Netflix Case

**Source:** Auto-generated captions from `L9_Part-4_DSS-ESS-GDSS-and-Netflix-Case` video

---

## BI Users by Organisational Level

| Level | Users | BI Tools Used | Information Needs |
|---|---|---|---|
| **Operational** | Employees, supervisors | Structured reporting systems | Detailed, transaction-level info to execute standardised processes (e.g. shipping supervisor checking order details, inventory, availability for daily shipments) |
| **Middle** | Analysts, tactical managers | Interactive dashboards, flexible BI tools | Trend analysis, performance vs. targets, relationships between variables (e.g. regional sales manager tracking territories and product lines) |
| **Senior** | Executives, strategic planners | High-level, forward-looking BI | Synthesised info on key trends, risks, opportunities — not operational detail (e.g. CEO dashboard: market share trends, competitive positioning, growth projections) |

> As you move up the hierarchy, tools shift from **structured reporting → flexible analysis → strategic insights**. One size does not fit all.

---

## Decision Support Systems (DSS)

DSS are designed for **semi-structured decisions** — problems with some structure but still requiring judgment and interpretation.

**What distinguishes DSS:** use of **mathematical/analytical models** to simulate scenarios and explore potential outcomes.

### DSS Analytical Capabilities

| Capability | Description | Example |
|---|---|---|
| **What-If Analysis** | Change variables and see how outcomes differ | Financial analyst adjusts interest rate assumptions to evaluate investment return impact; manufacturing manager changes production schedule to assess throughput |
| **Sensitivity Analysis** | Systematically vary a variable's value to determine how sensitive outcomes are to that variable | Identifies which factors have the greatest impact on results |
| **Backward Sensitivity** | Start with a desired outcome and determine what input values are needed to achieve it | Sales manager identifies what growth rate is needed to hit a specific profit target |
| **Multidimensional Analysis** | Examine data from multiple perspectives simultaneously via OLAP tools (e.g. pivot tables) | Identify patterns not apparent in single-dimensional views |

> DSS bridges the gap between rigid transaction systems and the highly flexible executive support environment.

---

## Executive Support Systems (ESS)

Senior executives need **synthesised, forward-looking** information — ESS are built for this.

### Balanced Scorecard

A common framework implemented in many ESS to ensure **comprehensive performance monitoring** across four dimensions:

| Dimension | What It Tracks | Example Metrics |
|---|---|---|
| **Financial** | Financial performance and sustainability | Revenue, profit, ROI, cash flow |
| **Business Process** | How well internal processes are executed | Quality, cycle time, productivity, cost efficiency |
| **Customer** | How well customer needs are being met | Satisfaction, retention, acquisition, market share |
| **Learning & Growth** | Capacity for innovation and improvement | Employee capabilities, IS quality, organisational culture |

> A holistic view across all four dimensions supports strategic decisions that consider both short-term results and long-term capabilities.

### Business Performance Management (BPM)

BPM systems link **strategic objectives directly to operational execution**:
- Translates high-level strategies (differentiation, low-cost, scope) into specific, measurable operational targets

**Example — Airline with a differentiation strategy (superior customer service):**
- BPM establishes KPIs: on-time performance, baggage handling accuracy, customer satisfaction scores, response time to service issues
- These operational metrics become the concrete manifestation of the abstract strategic goal

### ESS Data Sources and Capabilities

- **Internal data:** enterprise applications → operational performance, resource utilisation, financials
- **External data:** financial market databases, industry benchmarks, economic indicators → context vs. competitors and market trends
- **Drill-down:** executives can move from high-level summaries to increasingly granular detail to identify root causes

**Example drill-down:** CEO sees declining market share → drills to affected regions/product lines → examines specific customer segments or competitive factors causing the trend.

---

## Group Decision Support Systems (GDSS)

GDSS address the unique challenge of **collaborative decision making** — for groups rather than individuals.

- Facilitate solution development for **unstructured problems** across teams (co-located or distributed)
- Tools for: **collecting, ranking, editing, and synthesising** ideas and responses from multiple participants
- Overcome common group pitfalls: dominant personalities, uneven participation, premature convergence, social pressure
- **Anonymity** feature allows honest input without fear of judgment or repercussions → more diverse contributions

**Modern GDSS platforms:** Cisco Collaboration Meeting Room (CMR Hybrid), Microsoft Teams (with collaboration tools)

---

## Case Study: Netflix — Data-Driven Decision Making

Netflix represents one of the most advanced implementations of data-driven decision making in business.

### Recommendation Engine

Netflix collects terabytes of user data:
- Viewing patterns, ratings, time of day, device used, when viewers pause/rewind

Combined with content metadata:
- Genre, actors, directors, length, release date, tone, pacing, themes

**Result:** The algorithm identifies non-obvious patterns (e.g. viewers who enjoy slow-paced 1970s crime dramas also tend to enjoy certain contemporary foreign films with similar pacing and themes — despite different genre classification).

**Strategic value:** Not just convenience — it increases subscriber engagement and **reduces churn** by helping viewers discover content they enjoy.

### Content Production Decisions

Before greenlighting a new show, Netflix analyses hundreds of variables:
- Viewer demographics, genre performance, production cost, popularity, specific scene preferences → predict viewership and ROI

### A/B Testing and Marketing

- Extensive **A/B testing** to optimise UI elements
- **Personalised marketing campaigns** based on viewing history → targeted announcements relevant to demonstrated interests → higher response rates and viewer engagement

### Integration of Systems

The power lies in **integration across analytical systems**:
- Recommendation engine insights → inform content acquisition
- UI testing → inform content presentation
- Viewing patterns → inform marketing priorities

> Data flows across functional boundaries to support interconnected decisions at all levels.

---

## Future Trends in BI and Decision Support

| Trend | Description |
|---|---|
| **Automated Insights** | AI identifies significant patterns or anomalies without human analysts asking specific questions |
| **Natural Language Processing (NLP)** | Users query data conversationally — no need to learn specialised query languages or report design tools |
| **Augmented Analytics** | AI enhances human analytical capabilities: automates data cleaning, transformation, and integration; detects patterns automatically; generates plain-language explanations of complex analysis for non-technical users |

> Outcome: faster, better-informed decision making throughout the organisation — BI becomes accessible to non-technical users while becoming more powerful for advanced analysts.

---

## BI Implementation Challenges

| Challenge | Detail |
|---|---|
| **Data Quality and Integration** | Data stored across multiple systems with different formats, definitions, and quality standards; requires standardisation, cleaning, and governance. Example: "customer" defined differently across regional divisions makes cross-regional analysis impossible without harmonisation |
| **Skills Gap** | Effective BI requires both technical skills (implement/manage systems) and analytical skills (derive meaningful insights); hard to recruit, retain, and develop |
| **Balancing Automation and Human Judgment** | Organisations must determine which decisions can be safely automated, which benefit from human-machine collaboration, and which require primarily human judgment; requires change management to align automated decisions with organisational values |
| **Ethics and Data Usage** | Privacy, consent, bias, transparency. GDPR in Europe; PDPA in Singapore — specific requirements for data collection and use. Beyond compliance: do data practices meet ethical standards and maintain customer trust? |

> The most successful BI implementations treat these as **strategic challenges**, not purely technical ones — addressing technology, process, governance, and people together.

---

## Next Lecture Preview

**L10: Building Information Systems** — how organisations develop new systems that produce meaningful organisational change; a logical progression from *using* IS for decision support to *creating* new capabilities that transform how organisations operate.
