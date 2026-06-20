# L10 Part 4 — OO Development and AI Tools

**Source:** Auto-generated captions from `L10_Part-4_OO-Development-and-AI-Tools` video

---

## Object-Oriented (OO) Development

Rather than focusing on processes and data flows separately (as structured methods do), OO approaches **integrate data and the processes that act on that data** into cohesive units called **objects**.

### Core Concepts

| Concept | Definition |
|---|---|
| **Object** | Basic unit of system analysis and design; combines data and the operations that act on it into a single self-contained entity. Data can only be accessed via operations associated with that object → better security and data integrity. |
| **Class** | A template that defines common attributes and operations for a group of objects. All objects of that class have the features of their class. |
| **Inheritance** | Objects can inherit structures and behaviours from a more general ancestor class, promoting code reuse and consistency. |

**University system example:**
- `Student` and `Faculty` objects might both inherit from a more general `Person` class (defines shared attributes like name, address)
- `Student` class adds: attributes (student ID, GPA), methods (enrol in course, drop course, calculate GPA)
- All `Student` objects belong to the `Student` class and share its attributes and methods

### OO Analysis Phase

Analysts identify **real world entities** the system needs to model and represent.

Example entities in a university system: `Student`, `Course`, `Instructor`, `Registration`

### OO Design Phase

- Define how objects **behave and interact** with each other
- Group objects into **classes and subclasses** arranged in hierarchies reflecting real-world relationships
- Each class specifies: **methods** (what an object can do) and **attributes** (what data it holds)

### Advantages Over Structured Methods

| Advantage | Why It Matters |
|---|---|
| **More intuitive** | Models the real world more naturally |
| **Reusability** | Objects (and classes) can be used across multiple systems — reduces development time and cost |
| **Better maintainability** | Changes to an object's internal implementation don't affect other parts of the system |
| **Iterative and incremental** | Better suited to projects where requirements evolve over time (which is most real-world projects) |

---

## Traditional Waterfall Model (Contrast)

The traditional **SDLC** is often referred to as the **waterfall model** — one of the earliest and most structured methodologies:

- Follows a strict sequence: **Define → Design → Build → Test → Deploy**
- Offers structure, clear documentation, and predictability
- Works well in **stable settings** (e.g. infrastructure, government projects)
- **Limitation:** slow and hard to adapt when requirements change

---

## Build vs. Buy vs. Outsource

Many organisations today ask: should we **build** internally, **buy** off-the-shelf software, or **outsource** development entirely?

### Outsourcing: Benefits and Risks

| Benefits | Risks |
|---|---|
| Flexibility | **Vendor lock-in** |
| Cost savings (on paper) | Hidden costs |
| Access to specialised expertise | Data security concerns |
| — | Lost agility if vendor timelines/capabilities don't align |
| — | Distracts leadership or IT teams from core priorities (innovation, strategy) |

### The True Cost of Outsourcing

Outsourcing often appears cheaper but the **Total Cost of Ownership (TCO)** is higher:
- Training the vendor and sharing internal knowledge
- Running old and new systems in parallel temporarily (doubled workload)
- Ongoing contract management, quality control, cross-timezone communication
- Risk of having to reverse course if the solution doesn't meet expectations

> **Always evaluate TCO, not just the vendor quote.** That is the only way to make an informed, long-term decision.

---

## AI in System Development

A powerful new force reshaping how systems are built: **AI and machine learning** — not just used *inside* systems, but used to *build* them.

| Application | How AI Helps |
|---|---|
| **Code Generation** | Tools like GitHub Copilot generate working code from natural language instructions — speeds up development; still needs human review for quality and fitness |
| **Requirements Engineering** | AI scans documents, emails, or transcripts to extract and structure requirements automatically — reduces risk of missing critical user needs |
| **Testing** | AI creates test cases and sample data from system specifications — faster, and often catches edge cases humans might miss |
| **Documentation** | Automatically generates user manuals and internal technical guides — addresses the overlooked documentation problem under tight deadlines |
| **UX/UI Design** | Translates requirements into draft interfaces — quick starting point for designers, helps teams visualise user journeys earlier in the process |

> **Key principle:** AI **enhances, not replaces** human judgment. Domain understanding and alignment with business strategy remain essential — IS professionals are the bridge between AI-powered tools and real-world business needs.

### What AI Is Also Transforming

- Chatbots answer queries
- AI writes reports, finds patterns in data, forecasts demand
- AI maps processes to suggest automation

These tools are changing how **businesses operate**, not just how systems are built.

---

## Case Study: JP Morgan Chase — COIN (Contract Intelligence)

JP Morgan Chase developed an AI system called **COIN (Contract Intelligence)**.

**Problem:** Reviewing complex legal documents (e.g. loan agreements) consumed **360,000 hours of lawyer time every year**.

**Solution:** COIN uses **machine learning and natural language processing (NLP)** to:
- Scan contracts
- Extract key terms
- Identify critical clauses
- All done **within seconds**, with higher accuracy and zero fatigue

**Impact:**
- What once took hours per document is now instant
- Lawyers were **elevated** — instead of spending time on routine checks, they now focus on exception handling, negotiation, and strategic legal thinking
- The routine was automated; the expertise remained human

> "COIN isn't just a productivity tool — it's a strategic asset. It creates value by freeing up people to do what they do best, while ensuring speed, consistency, and scale."

**Lesson for IS professionals:** Successful AI systems solve **clear business problems** with the right mix of data, design, and human oversight.
