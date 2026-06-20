# L9 Part 2 — EastSpring Case and Decision Types

**Source:** Auto-generated captions from `L9_Part-2_EastSpring-Case-and-Decision-Types` video

---

## Case Study: EastSpring Investment

EastSpring is a significant Asian asset management company. This case illustrates how organisations rebuild their IS to enhance decision-making capabilities.

**Guiding questions to consider:**
- What specific problems did EastSpring face with their legacy systems?
- What were the root causes?
- What solution approaches were taken?
- What were the impacts?
- What learnings can IS students extract?

---

### The Problem

EastSpring's technology infrastructure had reached **end of life** and was becoming increasingly unmanageable:
- ~30 key applications at Singapore HQ + ~20 additional applications across regional operations
- Upgrade projects were stalling due to systemic complexity
- Existing infrastructure could **not sustain planned business expansion**
- For a financial services company, timely data-driven decisions are existential — this was a strategic threat

### Root Causes

1. **Legacy integration debt** — In-house developers had modified systems over years to work with existing legacy apps; each change made sense individually but collectively created a web of unmaintainable dependencies
2. **Regional customisation** — Business units across regions developed locally specific requirements, creating a patchwork of solutions instead of coherent systems
3. **Bolt-on growth** — New functionality was added onto existing systems as the business grew, rather than redesigning from the ground up

> "Systems that were once adequate become obstacles to growth as decision-making requirements evolve."

### Solution Approach (from 2015)

EastSpring took a **strategic, process-first** approach rather than piecemeal fixes:

1. Reviewed **all business processes** before touching technology
2. Created a **Target Operating Model (TOM)** for the entire region
3. Developed a **3-year phased project plan** based on process classification:

| Process Category | Approach |
|---|---|
| **Critical** (core business) | Maintain in-house control |
| **Important** (non-core) | Outsource for efficiency with oversight |
| **Unimportant** | Use off-the-shelf products without customisation |

4. Prioritised **systems with breadth of services** over best-of-breed point solutions → reduced integration complexity
5. Made the bold decision to **use off-the-shelf products for all processes** and avoid in-house development entirely
   - This meant adapting **business processes to match the software**, not customising the software to fit existing processes

### Impacts

- Successfully expanded to **14 markets worldwide** (UK, US, Luxembourg, and more)
- Experienced ~**25% growth**
- Improved ability to understand **risk parameters** for various firms
- Moved beyond Excel to **sophisticated analysis capabilities**
- Dramatically improved operational efficiency and decision-making across the organisation

### Key Learnings

| # | Learning |
|---|---|
| 1 | **Business process review before technology** — ensures tech aligns with actual needs, not just automating inefficiencies |
| 2 | **Classify processes by strategic importance** — focus resources where they create most decision-making value |
| 3 | **Adapt processes to standard software** — customisation creates long-term maintenance burden that outweighs short-term fit |
| 4 | **Cloud reduces infrastructure needs** — frees talent for more strategic initiatives |
| 5 | **Strategic vendor selection** — breadth of services > most feature-rich option |
| 6 | **Phased implementation** — enables learning and adjustment throughout; avoids "big bang" risk |

---

## Types of Decisions

Decisions fall along a spectrum from highly structured to completely unstructured.

### Structured Decisions
- Repetitive, routine decisions with well-defined procedures
- Clear right answer and standard process
- Example from case: using off-the-shelf solutions for non-core processes
- **Supported by:** Transaction Processing Systems (TPS)

### Semi-Structured Decisions
- Have some structured elements but **require human judgment**
- Follow standard procedures but involve variables needing interpretation
- Example from case: EastSpring's classification of processes as critical/important/unimportant (guidelines exist, but judgment needed to apply them)
- **Supported by:** Decision Support Systems (DSS)

### Unstructured Decisions
- No predetermined procedures; rely on **intuition, experience, and judgment**
- No clear right answer; involve complex, hard-to-quantify factors
- Example from case: EastSpring's strategic decision to completely overhaul systems and adapt business processes to new enterprise software
- **Supported by:** Executive Support Systems (ESS)

---

## Decision Making by Management Level

| Management Level | Examples | Decision Type | Supporting System |
|---|---|---|---|
| **Senior Managers** (CEO, CFO) | Enter new markets, major capital investment, restructuring | Mostly unstructured | ESS |
| **Middle Managers** (dept heads, regional managers) | Implement strategic initiatives, adapt to local context | Mixed (structured + unstructured) | DSS (what-if analysis, scenario modelling) |
| **Operational Managers / Staff** | Inventory reordering, crew scheduling, daily production | Mostly structured | TPS / MIS |

> "One size does not fit all when it comes to decision support in a real organisation."

### Activity: Airline Decision Classification

Example classifications:
- **Expand airline routes to South America** → Senior management → Unstructured (market potential, competition, regulation, long-term resources)
- **Approve overtime for ground staff during peak season** → Middle management → Structured (passenger volume, staffing levels, budget parameters)

---

## Simon's Decision-Making Process

Four key phases applicable to both structured and unstructured decisions:

| Phase | Description | EastSpring Example |
|---|---|---|
| **Intelligence** | Discover, identify, and understand problems occurring in the organisation; sense that something needs attention | Recognised aging systems were becoming unmanageable |
| **Design** | Identify and explore potential solutions; develop alternatives, create models, establish evaluation criteria | Reviewed all business processes; created Target Operating Model |
| **Choice** | Select from among solution alternatives | Classified processes as critical/important/unimportant; selected implementation approach |
| **Implementation** | Make the chosen alternative work; monitor how well it addresses the original problem | 3-year phased implementation plan |

**IS plays a different role at each phase:**
- Intelligence → problem detection systems
- Design → analysis and modelling tools
- Choice → decision models
- Implementation → execution and monitoring support

---

## Why IT Investments Don't Always Improve Decision Making

Three main challenges:

1. **Information Quality** — High-quality decisions need accurate, timely, complete, and relevant data. Inconsistent, outdated, or incomplete records undermine even sophisticated analytics. (EastSpring's process review likely addressed this.)

2. **Management Filters** — Managers have selective attention and cognitive biases; they may reject information that doesn't confirm their prior expectations. A manager might focus on sales data confirming a strategy is working while ignoring contrary indicators. Perfect information systems cannot guarantee perfect decisions.

3. **Organisational Inertia and Politics** — Embedded work processes and stakeholder interests resist significant change. Technical capacity to make better decisions may exist but organisational factors prevent acting on them. EastSpring's decision to adapt processes to standard software was a conscious effort to overcome this.

> Enhancing decision making is not just about technology — it requires addressing the **human and organisational context** in which decisions are made.

---

## High-Velocity Automated Decision Making

- Decisions made via **computer algorithms** that precisely define steps for highly structured decisions
- **Humans are removed from the decision loop** for specific transaction types
- Decisions made in **fractions of seconds** rather than minutes, hours, or days

### Singapore Examples

| Example | How It Works |
|---|---|
| **DBS Quick Finance** | Approves SME loans within minutes by analysing transaction history, credit profile, and other data points — no human intervention |
| **Lazada / Shopee** | Dynamic pricing algorithms adjust product prices based on inventory levels, time of day, and customer browsing behaviour — thousands of decisions per hour |
| **Jurong Innovation District smart factories** | Continuously monitor production lines; automatically adjust parameters, detect quality issues, and reroute production without waiting for human decision |

**Key insight:** These systems don't just speed up existing processes — they **fundamentally transform** them by embedding decision logic into algorithms, enabling consistency, speed, and scale impossible with human-centric approaches.

- Most appropriate for **highly structured, well-understood** decision scenarios
- Unstructured decisions still require human judgment

---

## Business Intelligence (BI)

**Business Intelligence** = the infrastructure for collecting, storing, and analysing data produced by various business components:
- Databases, data warehouses, data marts (covered in earlier sessions)

**Business Analytics** = tools and techniques for analysing data, built on the BI foundation:
- OLAP (Online Analytical Processing)
- Statistical analysis
- Predictive modelling
- Data mining

*(More on these in TCX2002)*

BI vendors create and sell these capabilities as **packaged solutions**. Key vendors: Tableau, Microsoft Power BI, SAP

**BI is not a single tool** — it is a whole environment:
```
Data Sources → Analytical Tools → Delivery Platforms (dashboards, reports)
```

**Example:** Sales data from a CRM → analysed in Power BI → shared via interactive dashboard → managers adjust sales strategy in real time.

> Next section will explore the specific analytical tools that BI systems provide and how they help identify relationships, patterns, and trends in data.
