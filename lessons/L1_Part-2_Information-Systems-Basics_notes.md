# L1 Part 2 — Information Systems Basics

**Source:** Auto-generated captions from `L1_Part-2` video

---

## Case Study: Retail Stores

Retail is used as the running example throughout this lecture — we have all experienced it and can relate to it.

### How retail has evolved
- Physical-only stores → **omnichannel** (blending online + offline)
- Even brick-and-mortar stores now use IS to track inventory, analyse sales/customer behaviour, and optimise operations

### Three major challenges retailers face
1. **Intense competition from online retailers** — Amazon, Lazada, Shopee raised the bar on convenience and price transparency
2. **Organisational change** — deploying a new IS is not just installing software; it means changing business processes and restructuring teams. *"The technology might be the easiest part — getting people to change their work habits is usually much harder."*
3. **Complementary assets** — success requires investing beyond the technology itself: supportive culture, staff training, and efficient processes

### Complementary assets — hospital RFID example
Singapore hospital CSSD (Central Sterilisation Services Dept) implemented RFID for inventory management. The project required **process re-engineering + staff training** to succeed — not just the tech.

---

## How IS Enhance Retail Operations

### Frictionless shopping (Amazon Go / Amazon Web Mart)
- Cameras + sensors + AI eliminate checkout queues
- System identifies items taken from shelves, processes payment automatically as customer exits

### Curbside pickup
- IS tracks when order is placed, notifies customer when ready, monitors arrival via mobile location, coordinates handover

### Smart shelf technology
- **Weight sensors** — track inventory in real time
- **Proximity sensors** — detect customers approaching
- **RFID readers** — scan products for accuracy
- **3D cameras** — capture product interactions
- **Microphones** — pick up audio cues for customer needs

### Digital signage applications
- Dynamic pricing (updates by demand or time of day)
- Real-time advertising (changes based on who is in the store)
- Anonymous customer tracking (privacy-preserving)
- Navigation assistance to find products

> Singapore context: PayNow / GrabPay already represent this convergence of tech redefining in-store transactions.

### Six key benefits of retail IS
1. **Personalised offers** — e.g. FairPrice using purchase history to send customised discounts
2. **Operational efficiency** — e.g. self-checkout serves more customers with fewer staff
3. **Inventory management** — sensors auto-trigger reordering when stock falls below threshold
4. **Customer tracking** — insights into movement patterns and product interactions
5. **Enhanced marketing** — targeted promotions instead of generic campaigns
6. **Improved shopping experience** — seamless, personalised, enjoyable

> Example: **Decathlon RFID** lets customers scan products for information without needing staff assistance.

---

## What Is an Information System?

> **Definition:** A set of interrelated components that work together to **collect, process, store, and distribute** information.

- Notice: no mention of computers — IS existed before computers (e.g. 1950s paper filing systems: forms → human calculation → filing cabinets → printed reports)
- Modern IS is typically technology-based and supports: **decision making, coordination, control, analysis, and visualisation**
- Three core dimensions (covered later): **Technology · Management · Organisation**

---

## Data vs. Information

| Term | Definition |
|------|-----------|
| **Data** | Raw facts and observations (e.g. a list of numbers) |
| **Information** | Data that has been **processed and organised** in a meaningful way that creates value for its recipient |

### Example
- Raw data: `331 Bright Dish Soap 1.29` (and thousands of similar entries)
- After processing → organised information: Item 331 "Bright Dish Soap", Northwest region, Superstore 122 → 7,156 units sold, YTD revenue $9,234.24

### Key tension
Organisations are often **drowning in data yet starving for information**.

> Singapore example: NEA collects terabytes of raw sensor data → only valuable once transformed into actionable output like the Pollutant Standards Index (PSI) or weather alerts.

---

## Four Key Activities of an Information System

```
Input → Processing → Output → (Feedback back to Input)
```

| Activity | Description | Credit-card example |
|----------|-------------|---------------------|
| **Input** | Capture raw data from organisation or environment | Card number, merchant ID, amount, date, location |
| **Processing** | Convert raw data into meaningful form (sort, calculate, compare) | Verify identity, check credit limit, categorise expense |
| **Output** | Transfer processed information to people or activities that use it | Mobile notification, transaction history, monthly statement |
| **Feedback** | Return output to appropriate members to evaluate/correct input | Fraud report → triggers corrective actions and improves detection algorithm |

> Note: Feedback can be **human/external** to the process OR **embedded inside** the process itself.

---

## Retail Transaction Flow Example

1. Customer makes a purchase (data captured: product, price, payment method, time)
2. System **processes** → identifies patterns (e.g. products bought together, ice cream sales spike in hot weather)
3. **Output** → inventory warnings, sales metrics, staffing recommendations
4. **Feedback loop** → system learns (e.g. product placement strategies that increase sales, effective promotions per customer segment)

### Online retail (e-commerce) process
1. Customer data captured
2. Payment verified
3. Inventory checked
4. Shipping label generated
5. Inventory records updated
6. Confirmation email sent to customer
7. Shipping info transmitted to logistics partner

> At each step: collect → process → output → feedback. If a problem occurs (payment failure, out-of-stock), automatic feedback loops trigger alternative processes.

> Scale example: Shopee / Lazada manage millions of transactions daily through exactly this kind of IS flow.
