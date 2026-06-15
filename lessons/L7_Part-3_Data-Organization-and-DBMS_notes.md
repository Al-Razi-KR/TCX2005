# L7 Part 3 — Data Organization and DBMS

**Source:** Auto-generated captions from `L7_Part-3_Data-Organization-and-DBMS` video

---

## Data Hierarchy

Think of data organization like a filing system, but on a much larger digital scale.

| Level | Definition | Example |
|---|---|---|
| **Database** | A group of related files working together | University database (students, courses, faculties, grades) |
| **File** | A group of records of the same type | Student records file |
| **Record** | A group of related fields describing one instance | One student's name, ID, major, GPA |
| **Field** | A group of characters representing a single attribute | Student ID number, Name |
| **Character/Byte/Bit** | Smallest unit | The letter "J" in "John" |

Data builds upward: bits/bytes → characters → fields → records → files → databases.

---

## Entities and Attributes

- **Entity** — any person, place, or thing about which we store information (e.g. a student, a course)
- **Attribute** — each characteristic describing an entity (e.g. student name, course credits)

---

## Four Common Problems in Traditional File-Based Systems

Modern organisations generate massive volumes of data from transactions, websites, mobile apps, social media, and sensors — with growing **volume, variety, and velocity**. Traditional file-based environments break down in four key ways:

1. **Data redundancy and inconsistency** — The same data stored in multiple places, often with slight differences, leads to confusion, errors, and unnecessary storage costs. One of the most frequent and impactful issues in legacy systems.

2. **Program data dependence** — Applications are tightly coupled to the structure of data. Even small changes in data formats require corresponding changes to every program that accesses that data, making upgrades slow and risky.

3. **Limited flexibility and poor security** — Isolated, rigid systems are difficult to adapt to new requirements or emerging threats. Security measures are inconsistent across siloed systems.

4. **Limited data sharing and availability** — When data is trapped in silos, teams cannot access the full picture, restricting collaboration, slowing decision-making, and reducing data's overall value.

---

## Program Data Dependence — Example

A company stores customer names limited to 30 characters. As the business expands internationally, it increases the field length to 50 characters. In a traditional system, this simple change requires:

- Updating every program that accesses the customer file (customer service, invoicing, reporting, analytics)
- Converting existing data
- Updating report layouts
- Re-testing every modified application

**Result:** Added cost, delays, and risk of new errors.

---

## Physical Data Independence

Modern **Database Management Systems (DBMS)** solve program data dependence by separating how data is *defined* from how applications *access* it.

- Applications interact with data through a DBMS layer rather than directly with data files
- Changes to the physical data structure do not require changes to the application layer
- This principle is called **physical data independence** — making systems more adaptable, maintainable, and future-ready

---

## Traditional File Processing — The Problem Visualised

In traditional environments, each department (Accounting, HR, Sales, Manufacturing) maintains its own systems and separate data files. This fragmented approach causes:

- **Data redundancy** — Same data stored in multiple locations; wastes storage and increases maintenance costs
- **Data inconsistency** — One department updates a customer's address; others do not → conflicting versions of the same record
- **Reporting difficulties** — Generating integrated reports requires manual reconciliation across departments, which is error-prone

**Example:** A customer moves. The new address must be updated separately in Sales, Billing, and Shipping files. If any department misses the update, the customer receives bills at the old address and shipments at the new one.

---

## DBMS — The Solution

A **Database Management System (DBMS)** centralises data and provides controlled access to all authorised users and applications.

**How it solves traditional problems:**

| Problem | DBMS Solution |
|---|---|
| Data redundancy | Stores each piece of data only once |
| Data inconsistency | Centralised updates eliminate conflicting records |
| Program data dependence | Separates program logic from data structure |
| Poor security | Centralised data management and security controls |

**Example:** When a customer address field expands from 30 to 50 characters, only the central data definition changes. All applications continue working without modification because they access data through the DBMS interface.

### Multiple Views from One Database

A single DBMS can present different views of the same data to different users based on their role:

| User | View |
|---|---|
| Recruiter | Candidate and hiring data |
| Benefits specialist | Enrollment and eligibility information |
| Payroll clerk | Salary and tax information |
| Manager | Performance and team data |

All views come from the same integrated database — ensuring consistency while providing role-appropriate access.

---

## Coming Up (Part 4)

Specific DBMS capabilities and newer database technologies enabling modern data architectures.
