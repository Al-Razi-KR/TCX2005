# L10_Part-3_SDLC-and-Development-Methods — Raw Transcript

A typical system project follows core activities which are analysis, design, programming, testing, conversion and maintenance.
0:06
Think of it as a lifecycle. It starts with defining the problem.
0:19
Which includes identification of causes.
0:25
Potential solution with an eye on feasibility of each solution and the IT requirements for implementation purposes, then designing a solution.
0:28
Building it. Testing it, rolling it out and supporting it in the long run.
0:40
Even though this may seem like a linear process, in reality, these steps are often revisited, especially in the modern agile development.
0:47
Designing the system goes far beyond just coding.
1:01
You need to specify everything from output, input, the user interface, database structures, control,
1:05
security protocols, training, and even how jobs might change by the introduction of a new system.
1:14
The slide on the screen reminds us that systems are used by people in real workspaces.
1:22
The successful design must be holistic, with detailed specifications to understand all potential impacts.
1:28
Once the design is complete, developers, they start coding.
1:39
But testing is just as crucial. We test components using unit testing.
1:44
We test the whole system using system testing, and we find out whether users approve of the developed it or not through user acceptance testing.
1:52
It is not just about fixing bugs. It's about ensuring that the system actually solves the business problem and meets the user requirements.
2:03
Conversion is the moment of truth, which is shifting from old system to new.
2:17
There are four main strategies parallel where both new and old systems are made to run together.
2:23
Direct cutover, where a full switch is made to the new system. Pilot, where testing is done in a small group.
2:31
In phased rollout, we are rolling out is done in stages with careful observation of how things are going.
2:40
Each approach has a trade off in cost, risk and speed.
2:49
Each strategy requires different levels of end user training and system documentation.
2:55
The choice depends on factors like systems complexity, organizations readiness and available resources, and also the tolerance for risk.
3:01
Let me share a compelling example that demonstrates modern system development and convergent strategies in action.
3:16
NUHS partnered with Integrated Health Information Systems to implement a mobile
3:25
first strategy through their OneNUHS mobile app.
3:30
This case is particularly interesting because healthcare organizations face unique challenges in general.
3:37
They need to maintain continuous operations while implementing a new technology.
3:44
They handle sensitive patient data requiring strict security measures.
3:49
And the third diverse user population, from tech savvy professionals to patients who may struggle with digital interfaces.
3:53
NUHS positioned their new app as the digital front door to the health system,
4:02
which means a single point of access for patients to interact with various healthcare services.
4:08
The development timeline was around 12 months to conceptualise and develop the first two versions,
4:15
which shows the complexity involved in the healthcare system development.
4:21
What makes this case study exemplary for its practitioners, like us, is the systematic approach to conversion and development employed by NUHS.
4:28
Rather than attempting to launch everything at once. They followed a carefully planned strategy that demonstrates best practices in system conversion.
4:39
NUHS used a pilot approach, starting with a small user group to catch issues early.
4:49
Then they faced the rollout with MVP, which is minimum viable product one, two and three.
4:57
Gradually adding features. Their success was not just in the tech.
5:05
It was in how they rolled it out during a critical time in health care.
5:11
The annuities case here demonstrates several key system conversion principles that are applicable across industries.
5:18
Testing in small groups. Rolling out in phases.
5:27
Building iteratively and always keep user experience.
5:30
At the center are some of the core principles that we should take note of.
5:34
Their mobile first strategy was not just digital, it was a transformation in how patients interact with healthcare systems.
5:40
Now that the system is up and running, we enter the longest phase of the system's life, which is production and maintenance.
5:51
This is where the system is used in daily operations and continuously monitored for performance and improvement.
6:00
At this stage, the system is periodically reviewed for necessary revisions.
6:08
Maintenance activities can vary, but industry research shows that typical distribution about 20%, goes into debugging and emergency fixes.
6:14
These are usually your urgent issues that surface in live usage.
6:24
Another 20% involves changes to the system environment, such as updates to the hardware, software, platform or reporting requirements.
6:29
But the majority, which sits around 60%, is dedicated to user requested enhancements, better documentation, and process optimization.
6:39
This reflects how real world system use surfaces, new needs, and improvement opportunities that may not have been anticipated during its development.
6:50
So while the development project may feel like it end at a launch,
7:01
in reality systems evolve continuously and successful organizations they plan for the evolution through proactive support and maintenance strategies.
7:06
Now let's take a moment to talk about how systems are built.
7:20
Broadly, there are two approaches structured and object oriented.
7:24
Structured is a step by step approach which is great for complex and stable environment.
7:29
Object oriented is flexible, reuse friendly, and better for modern evolving needs.
7:36
Many organizations nowadays also use a hybrid of these two models.
7:43
Structured methods are process driven and focus on separating data and processes.
7:50
They use tools like data flow diagrams to map out how data move through a system.
7:57
These methods shine when you need thorough documentation and predictability, like for example, in banking or government projects.
8:03
Here's an example on your screen, which is a DFD or data flow diagram in action.
8:19
The diagram depicts a university course registration system.
8:25
It shows processes, data flows and files clearly.
8:29
DFDs and process specifications help uncover flaws early and build a shared understanding,
8:35
which is essential when designing systems that many stakeholders are going to rely upon.
8:42
Another methodology is structure charts, structure charts, breakdown system functions into smaller modules.
8:53
Think of it as a family tree of system components.
9:03
It helps plan who builds what, supports modular testing and ensures the system has complete functional coverage.
9:07
On screen, you can see a high level structure chart for a payroll system.
9:17
So on the extreme left you see get valued input and then do the computation and
9:22
then writing the output as three major modules which are further split underneath.
9:28
Let's take a quick break here. And next we shall discuss object oriented development.
9:34
