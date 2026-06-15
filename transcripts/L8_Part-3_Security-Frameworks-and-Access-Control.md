# L8_Part-3_Security-Frameworks-and-Access-Control — Raw Transcript

Auto-generated captions may contain errors.

Welcome back. Now let's understand who is behind these attacks.
0:03
It is important to distinguish between hackers and what we know as crackers.
0:08
This distinction helps us understand the cybersecurity landscape a bit more accurately.
0:18
Hackers in the original sense of this term. It's meant for skilled computer enthusiasts who enjoy exploring computer systems,
0:25
finding creative solutions to technical problems, and understanding how technologies work.
0:34
They often participate in activities like bug bounty programs, open source development, and security research with permission.
0:41
For example, as you might know, ethical hackers, which are also known as white hat hackers,
0:51
are hired by companies to test their security systems and identify vulnerabilities before any malicious actor can exploit them.
0:57
Now. In contrast, crackers are what we know them as.
1:07
Blackhat hackers use their technical skills with malicious intent, breaking into systems without permission, stealing data or causing damage.
1:12
The term cracker emerged specifically to distinguish these malicious actors from the broader hacker community.
1:24
While both groups may use similar techniques, technical approaches, their intentions and legal standings are fundamentally different.
1:32
These malicious actors engage in various activities.
1:42
Such as system intrusion and damage, where they break into network to steal data or disrupt operations.
1:47
Cyber vandalism involves intentional disruption or defacement of website or corporate systems,
1:55
like your 2014 Sony Pictures attack that we discussed a while back.
2:02
Denial of service attacks are attacks where these malicious actors flood systems with traffic until these systems crash,
2:09
preventing legitimate users from accessing services. Spam continues to be a major vector for malware distribution and phishing.
2:20
Till date. Identity theft that happens through phishing or fake emails.
2:29
Evil twins, also known as fake networks and farming, also known as DNS manipulation, allows attackers to steal credentials and personal information.
2:36
Click fraud happens when the malicious actors cheats advertisers by generating fake clicks on online ads.
2:50
While cyberterrorism aims at intimidating or causing harm through digital means.
3:02
We are also seeing the rise of state sponsored cyber warfare.
3:09
These days, where nations target each other's critical infrastructure and information systems.
3:13
Now. Understanding these actors and their tactics helps organizations develop more targeted security strategies
3:20
that address both technical vulnerabilities and the human behaviors that attackers are exploiting.
3:27
And at the heart of all this, if you see, is a system.
3:34
Moving on. Let's look at the critical.
3:40
What are the critical vulnerabilities that organizations often underestimate, which are internal threats and software flaws?
3:47
Not all threats come from shadowy hackers in distant countries.
3:59
In fact, internal threats often pose greater risks because these attackers have legitimate access and insider knowledge.
4:04
Consider this scenario.
4:13
For example, a disgruntled employee with database access could extract customer lists before leaving to join a competitor.
4:15
An IT administrator with privileged access could disable security systems or steal sensitive data without triggering any alarm.
4:29
The case of Edward Snowden demonstrates how internal threats can operate at scale.
4:38
As an NSA contractor, he had legitimate access to systems and used that access to exfiltrate massive amounts of classified information.
4:45
While this was a government case, private organizations faced similar risks from insiders with privileged access.
4:55
Next. Security procedures often enable these internal threats when organizations don't properly segment access.
5:06
Monitor activities. Or enforce the principle of least privilege?
5:15
They create opportunities for abuse. Employees who lack security awareness makes for easy targets for social engineering.
5:20
Social engineering, in which attackers manipulate people into revealing information or performing actions that compromise security.
5:31
Both regular employees and I.T. specialists can be sources of risk.
5:40
In the DBS Hong Kong case mentioned earlier, bank employees allegedly sold customer data to call centres.
5:47
Highlighting how financial incentives can turn insiders into threats.
5:54
Also, we all know about the never ending pattern of software vulnerability.
6:01
Commercial softwares contain flaws, which is an unavoidable reality.
6:07
Even well-funded companies with extensive testing. Seldom achieve perfection.
6:13
Microsoft Windows, for example. They typically release dozens of security patches every month.
6:20
The bugs in commercial software create security vulnerabilities that attackers can exploit.
6:27
Then comes the zero day vulnerabilities. These vulnerabilities are particularly dangerous because they are unknown to software developers.
6:36
Attackers who discover these flaws can exploit them before patches are even available.
6:44
The WannaCry ransomware attack of 2017 exploited a windows zero day vulnerability affecting hundreds of thousands of computers worldwide.
6:51
Effective patch management becomes crucial in such cases for maintaining security.
7:03
Organizations must balance the need for update with business continuity because.
7:08
Because of which installing patches also require proper testing.
7:14
So to ensure that these patches don't break existing systems.
7:19
This creates a window of vulnerability that attackers can also exploit.
7:24
The challenge is that software complexity continues to increase while the development cycle becomes shorter and shorter,
7:31
potentially leading to more vulnerabilities entering into production systems.
7:40
Organizations today must implement robust testing code, review processes and update management strategies to address this ongoing challenge.
7:45
To organize our security thinking, let us examine the foundational framework known as the CIA triad.
8:00
These are the three characteristics that make information valuable and worthy of protection.
8:09
This framework provides the basis for almost all security programs and helps organizations prioritize their security efforts.
8:15
Confidentiality here refers to limiting access to information only to authorized users.
8:27
This can involve several approaches.
8:35
Like information classification, which entails categorizing data as public, internal, confidential, or restricted.
8:37
Then comes securing document storage, which is the use of appropriate protections based on the classifications developed by the company.
8:48
Then it is also crucial to implement consistent rules across the organizations as general security policies.
9:00
And let's not forget the education level of the staff.
9:08
So the company must run education programs to ensure staff understand their responsibilities.
9:12
And also company needs to use encryption to make information unreadable to unauthorized users or bad actors.
9:21
We'll give you an example a hospital. Might use encryption to protect protect patient records and restrict access to only
9:30
those healthcare providers who are directly involved in a patient's care program.
9:39
This maintains patient privacy while still allowing necessary access for treatment purposes.
9:45
Integrity now ensures data remains whole, complete and uncorrupted.
9:58
The integrity of information is threatened when it is exposed to unauthorized changes that could damage or destroy its authentic state.
10:05
Organizations maintain integrity through various means, such as hash functions that create digital fingerprints of data.
10:15
Digital signatures that verify who created or who modified certain information.
10:25
Access control measures that prevent unauthorized changes.
10:32
An audit logs that help auditors track all the modifications made on the data.
10:36
For example, financial institutions use integrity checks to ensure transaction data has not been tampered with when you transfer money.
10:43
Hash functions verify that amount and account details were not altered when the data was transferred from point A to point B.
10:53
And finally, availability means making sure data is accessible and correctly formatted for use without any external interference or obstruction.
11:04
This often overlooked dimension of security actually ensures that system remains operational when needed.
11:16
Authorized users can access information when required, and backups exist in case of systemic failures.
11:24
Consider an e-commerce site during a holiday sale. All the confidentiality and integrity protection matters little.
11:33
If the system crashes and customers can't place orders.
11:41
For such a business, availability becomes the most critical security dimension.
11:47
During peak periods. This brings us to a crucial insight, which is.
11:51
Perfectly perfect security is impossible.
12:04
And wouldn't be desirable if it were possible. The three principles of this framework that we just discussed.
12:08
Confidentiality, integrity, availability often create competing priorities that security professionals need to balance.
12:17
Let's understand it to an example. The most secure system might keep data in an airtight computer in a locked vault, which is perfectly confidential.
12:26
But now this is terribly available.
12:38
So the availability goes out of the window.
12:43
Conversely, making data widely available to ensure accessibility for everyone might compromise confidentiality.
12:45
So the security challenge lies in finding the right balance among these three principles,
12:55
based on the organization's specific needs and risk tolerance.
13:00
So it's crucial that we understand that security is a process, not a goal.
13:07
Organizations must balance protection with accessibility.
13:13
And consider various trade offs. Such as security controls versus user convenience.
13:18
What do we mean by that? Let us take an example. Requiring multiple authentication factors significantly improves security.
13:27
But it creates friction for legitimate users who might get frustrated with various prompts of security verification.
13:36
A hospital implementing two-factor authentication (2FA) for its electronic health record system improves patient data protection for sure,
13:47
but might slow down emergency room access during some critical situation.
13:54
Then let's talk about cost of security versus value of protected assets.
14:02
Security measures should be proportional to what you are protecting.
14:08
A small retail business might not need the same expensive security infrastructure as a financial institution.
14:13
For example.
14:22
A local bookstore might reasonably decide that simple encryption and access controls are sufficient for them to do their day to day business.
14:23
While a bank must invest millions in sophisticated fraud detection system.
14:32
Finally, organizations must determine how much risk they can tolerate while maintaining operational effectiveness.
14:39
For example, an insurance company might accept the risk of allowing employees to access email
14:47
remotely because the productivity benefits outweigh the increased security exposure.
14:53
So it's a trade off everywhere. Citibank.
15:00
Example of the slide shows this balance perfectly.
15:06
Their new anti-spam measure improves security but create friction for legitimate users who must adjust their device settings to access services.
15:12
Citibank determined that the fraud reduction benefits justified the additional customer effort required.
15:23
The key message here is that these competing priorities that we just talked about require continuous evolution.
15:31
And just as with other business needs, the balance point may shift.
15:40
But security is not about eliminating all risks.
15:49
It's about managing them intelligently while enabling the organization to function as effectively as possible, as smoothly as possible.
15:52
Let us explore the critical framework for understanding comprehensive security, which is the integration of people, process and technology.
16:07
This is not just a theoretical model.
16:17
It is the foundation of effective security architecture.
16:22
Security truly is only as strong as its weakest link, and frequently that weakest link turns out to be humans.
16:27
Think of it like a medieval castle. You might have massive stone walls, which represents your technology.
16:38
You have strict rules about who enters the castle. Which of your processes.
16:46
But if the gatekeeper is essentially bribed or fooled. Then all of the differences become meaningless.
16:51
So let's understand this people factor.
16:58
Employees often represent the most vulnerable point in security systems for several reasons.
17:02
First, they are susceptible to social engineering or sophisticated psychological manipulation.
17:09
The classic example is the tech support scam, where attackers call employees claiming to be from I.T. and request passwords to fix their problem.
17:17
Second, people often bypass security control for convenience.
17:28
According to a recent cyber ark study, 65% of the employees often bypass cyber security policies to make their life easier.
17:33
This includes behaviors like using personal devices and verify hotspots and forwarding corporate emails to personal accounts.
17:43
When security measures create significant friction with productivity,
17:52
employees will naturally find workarounds rather than letting security slow down their work.
17:56
Furthermore, employees may lack awareness of security best practices.
18:04
They might click on phishing emails that appear to come from their bank,
18:08
or post sensitive company information on social media, without realizing the implication.
18:13
For example, employees posting photos from the office might unknowingly reveal network diagrams on a whiteboard in the field behind.
18:19
Fraud is the insider threat. Insider threats can be either malicious or accidental.
18:31
A frustrated employee might deliberately exfiltrate data,
18:38
while someone who doesn't understand data classification might innocently send sensitive information to unauthorized recipients.
18:42
Here. We need to understand that technology alone cannot solve security problems.
18:57
The most sophisticated firewall or encryption system is useless if employees are sharing passwords or clicking on malicious links.
19:02
The most detailed security policies are ineffective if people don't follow them or understand their importance.
19:11
Okay. What about access control principle?
19:20
Let us look into the fundamental principles that form the foundation of modern access control.
19:24
These principles might sound straightforward, but their proper implementation can significantly transform your organization's security posture.
19:33
Need to know is our first principle, and it is based on a concept that originated
19:46
in military intelligence. This principle states that users should only have access to the information required for their specific role.
19:52
No more, no less. Consider an example.
20:02
A hospital implementing need to know would ensure that doctors can access only their patients records.
20:06
Administrators can see billing information, but not medical records,
20:14
and janitorial staff can access only building systems, but not patient data at all.
20:19
Each role has precisely the access needed to perform their function.
20:25
Creating security through compartmentalization.
20:29
Least privilege takes the concept a step further, while Need To Know focuses on what information users can access.
20:35
Least privilege focuses on what actions they can perform.
20:44
Users should have the minimum permissions necessary to complete their tasks.
20:48
Nothing more. When Sony Pictures was breached in 2014, attackers moved laterally through their network.
20:53
Partly because too many users in the organizations had unnecessarily elevated privileges given.
21:03
Finally, Zero Trust represents the evolution of these principles for our modern cloud based mobile first technology.
21:12
It operates on a simple premise.
21:21
Never trust. Always verify. In traditional security models.
21:25
Once you are inside the network perimeter, you were largely trusted.
21:31
Zero trust eliminates this assumption completely. Under a zero trust model.
21:36
Every access request is thoroughly authenticated, authorized, and encrypted before access is granted, regardless of where the request originates.
21:42
Let's examine how zero trust principles translate into practical architecture through Microsoft's implementation,
21:58
which is a model that many organizations are now adopting in response to modern security challenges.
22:05
Microsoft Zero trust approach represents a fundamental shift from traditional perimeter based security to continuous monitoring and verification.
22:13
I give you an example to understand the difference.
22:24
Compare a medieval castle to modern embassy security. Castle security focused on strong perimeter walls.
22:26
But once you are inside the walls of the castle, you could move freely.
22:35
Modern embassy security checks credentials at every door, monitors all movements, and restricts access to specific zones, even for authorized.
22:41
So there are these three core principles followed. Always authenticate using all available data points.
22:54
For example, accessing financial data from a coffee shop Wi-Fi.
23:03
Would trigger additional verification step compared to accessing the same data from the office workstation through office Wi-Fi.
23:08
Use least privileged access in form of just in time and just enough access principles.
23:19
This principle ensures users only have access to what they need and when they need it, rather than granting broad permissions that could be exploited.
23:27
For example, I.T administrators, when they are helping a user might only get elevated privileges for specific tasks and limited time periods,
23:38
after which the privilege expires. The idea is to minimize the blast radius.
23:47
If an account is compromised. Then third one is assumed.
23:54
Breach has already happened. This principle operates on the assumption that attackers have already gained some level of access,
24:03
and the architecture then focuses on continuously monitoring for any unusual activity in the network across connected devices.
24:12
And then there is the use of analytics to detect threats in real time, which is also part of your continuous monitoring.
24:21
For example, if an attacker compromises a marketing employees account,
24:32
they should not be able to access finance systems, production databases, or intellectual property repositories.
24:37
This comprehensive approach factors in the highly connected nature of modern I.T infrastructure that we studied in previous lectures.
24:46
Security must address every component and every connection point.
24:55
To be effective in today's threat landscape.
24:59
As a result of interconnected systems, organizations today do not operate in isolation.
25:07
They rely on complex networks of suppliers, vendors, and service providers who often have direct access to their most sensitive systems and data.
25:14
Now. This interconnection creates what security professionals call a supply chain risk in cybersecurity,
25:26
which is the idea that your security is only as strong as your weakest supplier.
25:35
So how do organizations manage these risks? Let's walk through each stage of an effective supplier risk management process.
25:41
Let's start with planning. This first stage is about defining your requirements and establishing your risk tolerance.
25:52
Organizations need to determine what security standards suppliers must meet based on the data and systems they will access.
26:01
For example. Our supplier handling protected health information would face stricter requirements than another one providing office supplies.
26:10
Then move to due diligence. Selection. This critical phase involves thoroughly evaluating potential suppliers before signing any contract with them.
26:23
This includes reviewing their security practices,
26:34
whether they have certifications like ISO 27001 and incident response history of those potential suppliers.
26:38
Once a supplier is selected, security requirements must be formalized in legally binding agreement.
26:48
This is about establishing specific measurable service level.
26:56
Agreements or SLAs for security controls, incident reporting procedures, and breach notification timelines.
27:01
For example, a contract with a supplier might require the supplier to notify you within 24 hours of any security incident that could affect your data.
27:09
Now the relationship does not end after signing a contract.
27:22
Regular monitoring ensures suppliers maintain compliance with security requirements throughout the relationship.
27:28
Which includes periodic security assessments, performance reviews, vulnerability scan, and compliance validation.
27:36
Finally, all good things must come to an end and vendor relationships are no exception.
27:45
The termination phase ensures that when a relationship ends with a supplier, it does so.
27:52
Security. This includes secure data transfer or deletion, revoking access privileges, returning any physical device or assets,
27:59
and implementing a smooth transition plan to a new provider without creating security gaps.
28:10
Without a proper termination procedure, former suppliers might retain access to your systems long after the business relationship has ended.
28:17
The AWS example on this slide shows how cloud providers can help with this process by providing a clear
28:28
service level agreement that specify the shared responsibilities for both the company and the customers.
28:36
Let's take a quick break here and discuss risk management strategies,
28:47
followed by tools and technologies that organizations deploy in their defense strategy.
28:51
