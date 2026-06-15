# L8 Part 4 — Risk Management and Security Tools

**Source:** Auto-generated captions from `L8_Part-4_Risk-Management-and-Security-Tools` video

---

## Five Risk Control Strategies

| Strategy | Description | Example |
|---|---|---|
| **Defense** | Proactive — apply safeguards to eliminate or reduce risk before an incident occurs; multiple overlapping protective layers | Banks implement encryption, access control, and intrusion detection systems together |
| **Transference** | Shift the risk to another entity, typically through insurance or third-party services — does not eliminate risk, transfers financial impact | Airlines maintain cyber insurance covering data breach investigation, business interruption, security failure claims, mishandling/copyright violations, software extortion, and legal/regulatory costs |
| **Mitigation** | Reduce the potential impact when risks cannot be completely eliminated — incident response plans, redundant systems, regular drills | Modern banks maintain multiple data centres to ensure service continuity even if one location fails |
| **Acceptance** | Some risks cost more to address than the potential loss — organisations make a calculated decision to accept | A small business accepts the risk of brief service interruption rather than investing in expensive redundant systems |
| **Termination** | Remove the vulnerable asset from the operating environment entirely | When a legacy system becomes too vulnerable to secure effectively, shutting it down may be the only viable option |

> The key is using the **right strategy for each specific risk** based on likelihood, potential impact, and cost of controls — not applying one strategy universally.

---

## Security Tools: Defence in Depth

Security tools work like layers of an onion — multiple barriers attackers must overcome.

### 1. Firewalls
- **Next-generation firewalls** go beyond checking IP addresses — they analyse application-level traffic, detect malicious patterns, and can inspect encrypted traffic
- Act as sophisticated gatekeepers at the network border

### 2. Intrusion Detection / Prevention Systems
- **IDS (Intrusion Detection System)** — like security cameras; continuously monitors network activity and alerts administrators to suspicious behaviour
  - Example: if a finance employee downloads gigabytes of data at 3 a.m., the IDS flags this as anomalous
- **IPS (Intrusion Prevention System)** — goes further and automatically blocks suspicious activity instantly

### 3. Encryption
- **Data at rest** (stored on servers/databases) — encrypted so attackers who gain storage access cannot read it without the decryption key
- **Data in transit** — protected via HTTPS and VPNs, so information travelling across networks cannot be intercepted and understood
- **Example:** Banking apps encrypt transactions — even if someone intercepts the data between your phone and the bank server, they only see meaningless gibberish without the encryption keys

### 4. Identity and Access Management (IAM)
- Verifies who users are, what they are allowed to access, and enforces policies automatically
- Integrates with directory services like Active Directory to manage accounts, permissions, and authentication
- **MFA (Multi-Factor Authentication)** adds verification layers beyond passwords:
  - Something you **know** (password)
  - Something you **have** (phone or token device)
  - Something you **are** (biometrics)
- Microsoft: MFA blocks **99.9% of automated attacks** on user accounts

### 5. SIEM (Security Information and Event Management)
- Collects logs from all sources — servers, networks, applications — and correlates events to identify attack patterns
- Modern SIEM platforms use **AI and machine learning** to detect anomalies

**Example — how a SIEM connects the dots:**
- Multiple failed login attempts
- Unusual file access patterns
- Network traffic to known malicious IP addresses
- Changes to critical system configurations

By correlating these seemingly unrelated events, SIEM can identify a **coordinated attack in progress** that would be invisible when looking at each event in isolation. This helps detect **Advanced Persistent Threats (APTs)** — prolonged cyber attacks that operate stealthily across multiple systems over extended periods.

### 6. Endpoint Protection
- Goes beyond traditional antivirus
- Protects individual devices with **behavioural analysis** and real-time threat detection

### 7. Email Security Gateways
- Filter malicious attachments, block phishing attempts
- Can rewrite URLs to protect against zero-day threats

### 8. Data Loss Prevention (DLP)
- Monitor data movement and enforce policies to prevent sensitive information from leaving the organisation inappropriately
- Example: detect and block attempts to email customer data or print sensitive documents

---

## Key Takeaway

> No single security tool can protect against all threats — just as no single infrastructure component can meet all business demands. The key is using these tools **in tandem, in a coordinated way**, to create a comprehensive security strategy.

---

## Lecture Wrap-Up

- Security is not just about protection — it is about **enabling trust** that allows organisations to innovate and create value
- **Next session (L9):** How secure IS enhance decision making — read **Chapter 12** before class
