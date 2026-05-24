# L2 Part 4 — IS Types and Management Levels

**Source:** Auto-generated captions from `L2_Part-4_IS-Types-and-Management` video

---

## Why Different Management Groups Need Different IS

Three reasons organisations require distinct IS for each management level:

1. **Different interests, specialties and responsibilities** — a frontline supervisor needs detailed operational data; a senior executive needs broader strategic information
2. **No single system can serve all needs** — the volume, variety, and velocity of data would overwhelm a single system architecture
3. **Different business functions need dedicated support** — sales/marketing, manufacturing, finance, and HR each have distinct requirements

---

## The Management Pyramid

```
         ┌─────────────────────┐
         │   Senior Management │  ← ESS
         ├─────────────────────┤
         │  Middle Management  │  ← MIS / DSS
         ├─────────────────────┤
         │ Operational Level   │  ← TPS
         └─────────────────────┘
```

| Level | Who | System | Purpose |
|-------|-----|--------|---------|
| Operational | Workers & supervisors | TPS | Day-to-day transactions and activities |
| Middle management | Managers | MIS / DSS | Aggregated reports, analysis, planning |
| Senior management | Executives | ESS | High-level summaries, trend analysis, strategy |

**Key principle:** These systems are not isolated — they build on one another. TPS collects raw data → MIS organises it for internal monitoring → DSS enables complex decision-making → ESS integrates internal and external data for strategic leadership.

---

## Transaction Processing Systems (TPS)

Serve **operational managers and staff**. Record and perform the daily routine transactions necessary to conduct business.

**Examples of transactions handled:**
- Sales order entry
- Payroll processing
- Shipping

**Characteristics:**
- Support **highly structured, predefined decision-making** (e.g., a POS system follows clear rules: process sale, calculate tax, update billing, update inventory)
- Allow managers to monitor internal operations and relations with the external environment
- Are the **major producers of information** for all other systems — if TPS data is flawed, all higher-level analysis suffers

### Payroll TPS Example

```
Employee Database (names, pay rates, tax details)
           ↓
    Payroll Processing
           ↓
┌──────────────────────────────┐
│ • Paychecks (employees)      │
│ • Government tax reports     │
│ • General Ledger entries     │
│ • Management payroll reports │
│ • Online pay stub queries    │
└──────────────────────────────┘
```

Shows how TPS automates routine tasks, ensures accuracy, and feeds data upward to MIS, DSS and ESS.

---

## Business Intelligence Systems

Provide data and tools to help managers make **improved, non-routine decisions**. Unlike TPS, they support analysis rather than predefined procedures.

May incorporate **external data** (e.g., stock prices, competitor pricing) as well as internal data. Many use sophisticated mathematical models or statistical techniques.

**Three main types:** MIS, DSS, ESS.

---

### Management Information Systems (MIS)

Serve **middle management** by providing periodic reports on the firm's current performance, based on data gathered from TPS.

- Answer questions with predefined procedures (e.g., "How many units did we sell in each region last month?")
- **Limited analytical capabilities** — excellent at organising and summarising data by preset parameters, but not designed for complex scenario analysis

**Value:** Transform raw TPS data into structured information that highlights performance patterns and exceptions, helping middle managers monitor operations and make tactical decisions.

#### MIS Report Example — Healthcare Inpatient Admissions (Q3 2024)

Report organised by service code, service description, and hospital region — showing actual vs. planned admissions.

**Key insights a manager could read:**
- Overall admission rate: **101% of plan** (slightly exceeding targets)
- Highest performing region: **South at 105% of plan** — practices worth replicating
- Most active service line: **General Medicine** (56,046 admissions) — implications for resource allocation
- General surgery in South is 8% above target — may require capacity adjustment

Managers can identify areas needing attention (e.g., Northeast general medicine at 96% of plan) and initiate corrective actions.

---

### Decision Support Systems (DSS)

Serve **middle management** for **non-routine decisions** requiring analysis rather than predefined procedures.

- Answer "what if" questions: *"What is the impact on production if December sales doubled?"* or *"How would different pricing strategies affect market share?"*
- Incorporate internal data (from TPS and MIS) **plus external data** (market trends, competitor actions)

**Two types of DSS:**

| Type | Description | Example |
|------|-------------|---------|
| **Model-driven DSS** | Uses statistical or simulation models to analyse scenarios and optimise decisions | Voyage estimating system for shipping companies |
| **Data-driven DSS** | Analyses large volumes of structured data from various sources to identify patterns | Marketing analysis integrating customer demographics, purchase history, and behavioural data |

#### Voyage Estimating DSS Example

Shipping companies use this to optimise voyage planning. Variables modelled:
- Fuel consumption at different speeds
- Port availability at different locations
- Weather conditions along alternative routes
- Various timing considerations

Managers can explore: *"What if we increase speed to meet an early delivery date?"* or *"What if we reroute to avoid bad weather?"*

This DSS does not just report history — it **models future scenarios** and combines internal cost data, external weather/port information, and mathematical models.

---

### Executive Support Systems (ESS)

Serve **senior management** for non-routine decisions requiring judgment, evaluation, and deeper insight.

- Incorporate data about **external events** (new tax laws, competitor actions)
- Pull **summarised information** from internal MIS and DSS
- Provide a comprehensive view of both organisational performance and the broader operating context

**Common implementation: Digital Dashboard**
- Displays graphs and charts of Key Performance Indicators (KPIs)
- Real-time view of financial and operational performance
- Drill-down capabilities to explore areas of concern
- Highly customisable and user-friendly — senior executives don't have time for complex data manipulation

---

## Quick Quiz

> *"A manufacturing company uses a system that allows managers to ask: 'What would happen to production capacity if we added another shift?' and 'How would raw material costs affect pricing?'"*

**Answer: DSS (Decision Support System)**

The key identifier: focus on **what-if scenario analysis** to understand the potential impact of different decisions — exactly what DSS is designed to support.

---

## Enterprise Application Systems

Unlike the pyramid systems (which serve specific levels or functions), enterprise applications **link the entire organisation together**, spanning functional boundaries and all management levels. They break down information silos.

**Four major types:**

| System | Acronym | Purpose |
|--------|---------|---------|
| Enterprise Resource Planning | ERP | Integrates all business processes into one unified system |
| Supply Chain Management | SCM | Manages supplier relationships and optimises supply chain |
| Customer Relationship Management | CRM | *(self-read)* |
| Knowledge Management Systems | KMS | *(self-read)* |

---

### Enterprise Resource Planning (ERP)

Integrates all business processes — manufacturing/production, finance/accounting, sales/marketing, HR — into a **single unified software system with a shared database**.

**Benefits:**
- Eliminates data inconsistencies between departments
- Single source of truth for organisational data
- End-to-end process visibility across functional boundaries
- Facilitates coordination across the organisation

**Example:** When a customer places an order, ERP automatically checks inventory, reserves stock, updates the production schedule, generates invoicing for finance, and provides delivery details to logistics — all as one integrated process.

---

### Supply Chain Management (SCM)

Coordinates processes **beyond the organisation's boundary**, connecting suppliers, logistics providers and distribution partners into an integrated supply network.

**Key benefits:**
- Reduced operational costs through better coordination and reduced inventory
- Optimised delivery times through improved scheduling and logistics
- Improved sourcing decisions through better supplier information
- Enhanced production scheduling through better demand forecasting

**Example: Zara's Fast Fashion**
Zara's SCM connects design studios, factories, and retail stores. When items sell well, that information flows immediately to production facilities, which quickly manufacture more of the popular designs — allowing Zara to respond to trends far faster than competitors with less integrated supply chains.

---

### CRM and KMS — Self-Read

The instructor assigned these two as **self-reading** from Laudon & Laudon. Focus on:
- How each system contributes to organisational performance
- How they integrate with ERP and SCM

---

## Looking Ahead

Next lecture: How IS supports **organisational strategy** — Porter's competitive forces model and the value chain framework for understanding how IS creates strategic advantage.
