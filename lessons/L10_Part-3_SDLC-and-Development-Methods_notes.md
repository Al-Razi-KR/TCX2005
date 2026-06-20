# L10 Part 3 — SDLC and Development Methods

**Source:** Auto-generated captions from `L10_Part-3_SDLC-and-Development-Methods` video

---

## Systems Development Life Cycle (SDLC)

The SDLC defines the core activities of any system project: **analysis, design, programming, testing, conversion, and maintenance**.

Think of it as a **lifecycle** — starting with defining the problem and ending with long-term support:

| Phase | Description |
|---|---|
| **Analysis** | Identify the problem, root causes, potential solutions; assess **feasibility** of each solution and IT requirements for implementation |
| **Design** | Specify output, input, user interface, database structures, security protocols, training, and how jobs may change |
| **Programming** | Developers write code based on the approved design |
| **Testing** | Verify components and the full system work correctly and meet user needs |
| **Conversion** | Transition from old system to new |
| **Maintenance** | Ongoing support, fixes, and enhancements in production |

> Even though this appears linear, these steps are often revisited — especially in modern agile development.

---

## Design Phase

Successful design must be **holistic** — covering all potential impacts on people, processes, and data:
- Output and input specifications
- User interface design
- Database structures
- Security and control protocols
- Training requirements
- Job redesign implications from the introduction of a new system

---

## Testing Phase

| Type | Scope |
|---|---|
| **Unit Testing** | Test individual components in isolation |
| **System Testing** | Test the whole integrated system |
| **User Acceptance Testing (UAT)** | Determine whether users approve of the developed system — confirms it solves the business problem and meets user requirements |

> Testing is not just about fixing bugs — it's about ensuring the system solves the right problem.

---

## Conversion Strategies

Conversion is the **moment of truth** — shifting from the old system to the new.

| Strategy | Description | Trade-off |
|---|---|---|
| **Parallel** | Both old and new systems run simultaneously | Lowest risk; highest cost |
| **Direct Cutover** | Full switch to the new system at once | Lowest cost; highest risk |
| **Pilot** | New system tested with a small group first | Catches issues early; limited scope |
| **Phased Rollout** | Roll out in stages with careful observation | Balanced risk; takes longer |

**Choice depends on:** system complexity, organisational readiness, available resources, and tolerance for risk.
Each strategy also requires different levels of **end-user training** and **system documentation**.

---

## Case Study: NUHS — OneNUHS Mobile App

NUHS (National University Health System) partnered with Integrated Health Information Systems (IHiS) to implement a **mobile-first strategy** through the **OneNUHS mobile app**.

**Why healthcare is uniquely challenging:**
- Must maintain **continuous operations** while implementing new technology
- Handles **sensitive patient data** requiring strict security
- Serves a **diverse user population** (tech-savvy professionals to patients who may struggle with digital interfaces)

The app was positioned as the **"digital front door"** to the health system — a single access point for patients to interact with various healthcare services.

**Development timeline:** ~12 months to conceptualise and develop the first two versions.

### Conversion Approach (Best Practice Example)

| Step | What NUHS Did |
|---|---|
| **Pilot** | Started with a small user group to catch issues early |
| **Phased rollout with MVP** | Launched Minimum Viable Product (MVP) v1, v2, v3 — gradually adding features |
| **Iterative building** | Built iteratively while keeping user experience at the centre |

**Key system conversion principles demonstrated:**
- Test in small groups
- Roll out in phases
- Build iteratively
- Always keep user experience at the centre

> Their mobile-first strategy transformed how patients interact with the healthcare system — not just digital, but a fundamental shift in the patient experience.

---

## Production and Maintenance

Once live, maintenance is the **longest phase** of the system lifecycle. The system is used in daily operations and continuously monitored.

**Typical maintenance distribution:**

| Category | % of Maintenance Effort |
|---|---|
| Debugging and emergency fixes (urgent issues surfacing in live usage) | ~20% |
| Environment changes (updates to hardware, software, platform, reporting requirements) | ~20% |
| User-requested enhancements, better documentation, process optimisation | ~60% |

> The majority of maintenance is driven by **user-requested improvements** — real-world use surfaces new needs that weren't anticipated during development. Systems evolve continuously; successful organisations plan for this.

---

## Development Approaches: Structured vs. Object-Oriented

| Approach | Characteristics | Best For |
|---|---|---|
| **Structured** | Step-by-step; process-driven; separates data and processes; thorough documentation | Complex, stable environments (e.g. banking, government) |
| **Object-Oriented** | Flexible; reuse-friendly; models real-world entities as objects | Modern, evolving systems |
| **Hybrid** | Combines both | Common in many organisations today |

---

### Data Flow Diagrams (DFDs)

- A **structured method tool** that maps how data moves through a system
- Shows processes, data flows, and data stores clearly
- DFDs and process specifications help **uncover flaws early** and build shared understanding among stakeholders

**Example on slides:** University course registration system DFD.

---

### Structure Charts

- Break system functions into **smaller, modular components** — like a family tree of system components
- Help plan who builds what, support modular testing, and ensure complete functional coverage

**Example on slides:** High-level structure chart for a payroll system with three major modules: *Get Valid Input → Do Computation → Write Output*, each further subdivided.

---

## Next Section

Object-oriented development — covered in the next part.
