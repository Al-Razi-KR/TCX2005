# L8 Part 3 — Security Frameworks and Access Control

**Source:** Auto-generated captions from `L8_Part-3_Security-Frameworks-and-Access-Control` video

---

## Hackers vs. Crackers

| Term | Definition |
|---|---|
| **Hackers** (original) | Skilled computer enthusiasts who explore systems, find creative solutions, and understand how technologies work — e.g. ethical/white hat hackers hired by companies to test security via bug bounty programs |
| **Crackers (Black hat hackers)** | Use technical skills with malicious intent — break into systems without permission, steal data, or cause damage |

Both groups may use similar techniques, but their **intentions and legal standings** are fundamentally different.

---

## Types of Cyber Attacks

| Attack | Description |
|---|---|
| **System intrusion** | Breaking into networks to steal data or disrupt operations |
| **Cyber vandalism** | Intentional disruption or defacement of websites/corporate systems — e.g. 2014 Sony Pictures attack |
| **Denial of Service (DoS)** | Flooding systems with traffic until they crash, preventing legitimate users from accessing services |
| **Spam** | Major vector for malware distribution and phishing |
| **Identity theft** | Via phishing or fake emails |
| **Evil twins** | Fake networks that steal credentials |
| **Pharming (DNS manipulation)** | Redirects users to fraudulent sites to steal personal information |
| **Click fraud** | Generating fake clicks on online ads to cheat advertisers |
| **Cyberterrorism** | Intimidating or causing harm through digital means |
| **State-sponsored cyber warfare** | Nations targeting each other's critical infrastructure and IS |

---

## Internal Threats

Not all threats come from external hackers — internal threats often pose greater risks because attackers have **legitimate access and insider knowledge**.

**Examples:**
- A disgruntled employee with database access could extract customer lists before leaving to join a competitor
- An IT administrator with privileged access could disable security systems or steal data without triggering alarms
- **Edward Snowden (NSA)** — as a contractor with legitimate access, he exfiltrated massive amounts of classified information

**Enabling factors:**
- Poor access segmentation — not enforcing the principle of least privilege
- Low security awareness — employees susceptible to social engineering
- Financial incentives — e.g. DBS Hong Kong case: employees allegedly sold customer data to call centres

---

## Software Vulnerabilities

- Commercial software always contains flaws — even well-funded companies with extensive testing seldom achieve perfection
- Microsoft Windows typically releases **dozens of security patches every month**
- **Zero day vulnerabilities** — unknown to software developers; attackers exploit them before patches are even available
  - **Example:** WannaCry ransomware (2017) exploited a Windows zero day vulnerability — affected hundreds of thousands of computers worldwide
- Challenge: software complexity increases while development cycles shorten → more vulnerabilities reach production

---

## The CIA Triad

The foundational framework for IS security — three characteristics that make information valuable and worthy of protection.

### 1. Confidentiality
Limiting access to information to only authorised users.

- **Information classification** — categorise data as Public, Internal, Confidential, or Restricted
- **Secure storage** — apply protections based on classification
- **General security policies** — consistent rules across the organisation
- **Staff education** — ensure employees understand their responsibilities
- **Encryption** — makes information unreadable to unauthorised users

**Example:** A hospital encrypts patient records and restricts access to only the healthcare providers directly involved in a patient's care.

### 2. Integrity
Ensures data remains whole, complete, and uncorrupted.

- **Hash functions** — create digital fingerprints of data
- **Digital signatures** — verify who created or modified information
- **Access controls** — prevent unauthorised changes
- **Audit logs** — track all modifications

**Example:** Financial institutions use hash functions to verify that transaction amounts and account details were not altered during transfer.

### 3. Availability
Ensuring data is accessible and correctly formatted for use without interference.

- System remains operational when needed
- Authorised users can access information when required
- Backups exist in case of systemic failures

**Example:** An e-commerce site during a holiday sale — confidentiality and integrity matter little if the system crashes and customers cannot place orders.

---

## Security Trade-offs

> Perfect security is impossible — and wouldn't be desirable if it were possible.

The CIA triad's three principles often create **competing priorities**:

| Trade-off | Example |
|---|---|
| **Security vs. accessibility** | The most secure system locks data in a vault — perfectly confidential, but completely unavailable |
| **Security controls vs. user convenience** | Multi-factor authentication improves security but creates friction — 65% of employees bypass security policies to make their work easier (CyberArk study) |
| **Cost of security vs. value of assets** | A local bookstore needs simple encryption; a bank must invest millions in fraud detection |
| **Risk tolerance vs. operational effectiveness** | An insurance company may accept employees accessing email remotely because productivity benefits outweigh security exposure |

**Example:** Citibank's anti-spam measures improved security but required customers to adjust device settings — the bank determined fraud reduction benefits justified the additional customer friction.

> Security is a **process**, not a goal. Organisations must continuously rebalance protection and accessibility based on evolving needs and risks.

---

## People-Process-Technology (PPT) Model

Security is only as strong as its weakest link — and that weakest link is frequently **people**.

> "Think of it like a medieval castle. You might have massive stone walls (technology) and strict rules about who enters (processes). But if the gatekeeper is bribed or fooled, all of those defences become meaningless."

### Why People Are the Weakest Link

1. **Social engineering** — e.g. tech support scams where attackers call employees claiming to be from IT and request passwords
2. **Bypassing controls for convenience** — 65% of employees bypass security policies (CyberArk); using personal devices, unverified hotspots, forwarding corporate emails to personal accounts
3. **Lack of awareness** — clicking phishing emails, posting sensitive info on social media (e.g. unknowingly revealing network diagrams on a whiteboard in office photos)
4. **Insider threats** — can be malicious (deliberate data exfiltration) or accidental (sending sensitive info to unauthorised recipients)

> The most sophisticated firewall is useless if employees share passwords or click malicious links.

---

## Access Control Principles

### 1. Need to Know
Users should only have access to information **required for their specific role** — no more, no less.

**Hospital example:**
- Doctors → access only their patients' records
- Administrators → billing information, not medical records
- Janitorial staff → building systems only, not patient data

Creates security through **compartmentalisation**.

### 2. Least Privilege
Focuses on **what actions users can perform** (not just what they can access) — minimum permissions necessary to complete tasks.

**Example:** Sony Pictures (2014) — attackers moved laterally through the network partly because too many users had unnecessarily elevated privileges.

### 3. Zero Trust
> "Never trust. Always verify."

- Traditional model: once inside the network perimeter, users were largely trusted
- Zero Trust: **every access request is authenticated, authorised, and encrypted**, regardless of origin

---

## Microsoft's Zero Trust Implementation

Three core principles:

1. **Always authenticate using all available data points**
   - Accessing financial data from a coffee shop Wi-Fi → triggers additional verification compared to access from office workstation on office Wi-Fi

2. **Use least privileged access — Just-in-Time and Just-Enough-Access (JIT/JEA)**
   - IT administrators helping a user get elevated privileges only for specific tasks and limited time — after which the privilege expires
   - Minimises the **blast radius** if an account is compromised

3. **Assume breach has already happened**
   - Architecture continuously monitors for unusual activity across connected devices
   - Analytics detect threats in real time
   - Example: if a marketing employee's account is compromised, they should not be able to access finance systems, production databases, or IP repositories

---

## Supply Chain Risk Management

Organisations rely on networks of suppliers, vendors, and service providers who often have direct access to sensitive systems.

> Your security is only as strong as your weakest supplier.

### Five Stages

| Stage | Description |
|---|---|
| **1. Planning** | Define security requirements and risk tolerance — a supplier handling health information faces stricter standards than one providing office supplies |
| **2. Due diligence / Selection** | Review supplier security practices, certifications (e.g. ISO 27001), and incident response history |
| **3. Contracting** | Formalise security requirements in legally binding agreements — specific, measurable SLAs for security controls, incident reporting procedures, breach notification timelines (e.g. notify within 24 hours of any incident) |
| **4. Monitoring** | Periodic security assessments, performance reviews, vulnerability scans, and compliance validation throughout the relationship |
| **5. Termination** | Secure data transfer or deletion, revoking access privileges, returning physical assets, and implementing a smooth transition plan — without a proper termination procedure, former suppliers may retain access long after the relationship ends |

**AWS example:** Cloud providers provide clear SLAs specifying the **shared responsibility model** — what the provider secures vs. what the customer must secure.

---

## Coming Up (Part 4)

Risk management strategies and the tools and technologies organisations deploy in their defence.
