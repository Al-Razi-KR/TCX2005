# L6 Part 2 — Grab Case Study and IT Infrastructure Components

**Source:** Auto-generated captions from `L6_Part-2_Grab-Case-and-Infrastructure-Components` video

---

## Case Study: Grab's IT Infrastructure Journey

Grab started as a taxi booking app and evolved into Southeast Asia's leading **super app** — ride-hailing, food delivery, payments, and financial services (GrabPay / GrabCapital).

**Key question:** What role did IT infrastructure play in enabling this expansion?

---

### The Problem Grab Was Solving

1. **Unreliable, unpredictable taxi services** — passengers couldn't be certain when or if a ride would arrive
2. **Pricing opacity** — non-transparent pricing especially during peak periods caused customer frustration
3. **Limited payment options** — Southeast Asia has relatively low bank account penetration compared to developed markets

---

### Infrastructure Solutions Implemented

| Component | Detail |
|-----------|--------|
| **Cloud infrastructure** | Leveraged AWS services (Redshift, ElastiCache) for real-time data processing at scale |
| **Analytics platform** | Geohashing technology for spatial analysis — enabled precise location matching and mobilised drivers to high-demand areas, balancing supply and demand |
| **Mobile applications** | Integrated apps for Android and iOS providing real-time updates to both drivers and passengers |
| **Payment infrastructure** | Partnerships (e.g. Lippo) to create an e-payment platform accessible to the unbanked |
| **Unified infrastructure** | Consistent operation across 339 cities in 8 countries despite varying connectivity and technological development |

> Infrastructure is not just about having computers and servers — it is about creating a technological foundation that enables core business capabilities and future growth.

---

### Outcomes

- Managing nearly **6 million daily rides** and coordinating **2.8 million drivers** across the region
- Significantly enhanced **service reliability** through real-time matching algorithms
- Improved **resource allocation** — drivers available where and when most needed
- Expanded **financial inclusion** — payment solutions for unbanked and underbanked populations
- Achieved **regional market leadership** — transformed from taxi app to comprehensive super-app ecosystem

---

### Key Learnings

1. IT infrastructure directly enhances organisational performance by supporting essential business processes and generating value for multiple stakeholders (customers, drivers, merchants, partners)
2. Effective infrastructure allows dynamic optimisation of finite resources based on real-time conditions
3. **Modern infrastructure enables real-time data processing and decision-making** — increasingly essential in fast-moving markets
4. Infrastructure decisions have **long-term strategic implications** — the platform Grab built enabled not just ride-hailing, but expansion into food delivery, payments, and beyond

> Grab beautifully illustrates how infrastructure is not merely a technical foundation, but a **strategic asset** that enables — or in some cases constrains — what an organisation can and cannot do.

---

## Evolution of IT Infrastructure (5 Stages)

Each era builds on the previous and adds new capabilities. Many organisations today operate in **hybrid modes** combining elements from multiple eras.

| Stage | Era | Period | Key Characteristic | Local Example |
|-------|-----|--------|--------------------|---------------|
| 1 | **Mainframe** | 1959 → present | Centralised computing with terminal-based access; still used for high-volume transaction processing (banking, airlines, government) | DBS Bank adopted IBM Z15 mainframe for digital transformation |
| 2 | **Personal Computer** | 1981 → | Decentralised computing; individual productivity tools | NUS established first PC labs in the 1980s |
| 3 | **Client-Server** | 1980s → present | Networked computing with shared resources; balances centralised control with distributed access | Singapore's first LAN deployments |
| 4 | **Enterprise Computing** | 1990s → | Internet-enabled businesses; ERP and CRM systems integrating business functions | — |
| 5 | **Cloud & Mobile** | Mid-2000s → | Cloud-based services; mobile-first approach | GovTech Singapore's government tech stack |

> This evolution is not a simple replacement — each era adds new layers while often preserving good elements of previous approaches.

---

## Seven Core Components of Modern IT Infrastructure

Think of these as an **ecosystem**, not standalone parts — IS succeed when all components are integrated, aligned, and optimised together.

| # | Component | Description |
|---|-----------|-------------|
| 1 | **Data management & storage** | Organise, protect, and provide access to data assets — databases, data warehouses, cloud storage |
| 2 | **Internet platforms** | Tools and technologies supporting web-based services — web servers, APIs, cloud tools (AWS, Microsoft Azure) |
| 3 | **Computer hardware platforms** | Physical foundation — servers, desktops, laptops, mobile devices, specialised equipment |
| 4 | **Operating system platforms** | Software layer managing hardware and supporting applications — Windows, macOS, Linux, Android |
| 5 | **Enterprise software applications** | Business functionality — off-the-shelf (SAP, Oracle) and custom-developed applications |
| 6 | **Networking & telecommunications** | Connects users and systems; enables secure, efficient information flow within and outside the organisation |
| 7 | **Consulting & system integration services** | Design, build, and manage environments so all components work as one cohesive system |

**Why integration matters:** Even the most powerful servers underperform if running outdated software, connected to a slow network, or supporting poorly designed applications. All components must work in harmony.

---

## System Integration

**Definition:** Connecting different systems, applications, and data sources so they work together in a coordinated way as a single system.

### Integration Approaches

| Approach | How it works | Strength | Weakness |
|----------|-------------|----------|----------|
| **Point-to-point** | Connects one system directly to another | Simple when few systems | Number of connections grows rapidly with scale — harder to manage, more fragile |
| **Hub and spoke** | Central hub manages all communication between systems | Reduces direct connections needed | Single point of failure if hub is not properly secured and maintained |
| **Enterprise Service Bus (ESB)** | Flexible, scalable communication backbone | Supports loose decoupling; systems interact without knowing each other's internals | More complex to set up |
| **API-based** | Standardised application programming interfaces | Highly flexible; widely used in cloud-native and mobile-first environments | Requires well-designed APIs and governance |

### Common Integration Challenges

| Challenge | Description |
|-----------|-------------|
| **Legacy system integration** | Older systems not designed to communicate with modern platforms — may lack standard interfaces, run outdated tech, or be costly to modify |
| **Cross-platform compatibility** | Systems on different OS/architectures (Windows, Linux, cloud, on-prem) must still interact reliably |
| **Data migration** | Transferring data between systems while preserving accuracy, consistency, and meaning — critical during upgrades, mergers, or platform transitions |
| **Security & compliance** | Maintaining consistent data protection and regulatory standards across connected systems; integration increases interconnectivity, raising the importance of unified security controls |

> These challenges must be anticipated and managed carefully — they are often the very reason integration projects fail, even when the technology itself is well thought out.

---

## Coming Up (Part 3)

Trends in computer hardware platforms.
