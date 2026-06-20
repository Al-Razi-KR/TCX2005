# L9_Part-2_EastSpring-Case-and-Decision-Types — Raw Transcript

Let's begin by examining our case study about East Spring investment, which is a significant Asian asset management company in Asia.
0:05
This case illustrates how organizations rebuild their information systems to enhance decision making capabilities.
0:15
If you haven't read this case, I would highly advise you to do it before before going through this recording.
0:24
And as you go through this case, try to identify the specific problems East Spring faced with their legacy systems,
0:31
the key reasons or causes behind these issues.
0:39
What are the solution approaches taken? What were the impacts of those approaches and what learnings we can extract
0:44
as the students of information systems from the experience of this company?
0:51
EastSpring's journey offers valuable insight into the challenges that organization faced when their existing
0:57
systems are no longer supportive to the quality and speed of decision making required for their business growth.
1:05
Okay, so take a moment to reflect on these aspects before we move on to analyze the case in more detail in the next couple of slides.
1:13
Okay, let's analyze EastSpring's situation a little more closely.
1:27
The core problem EastSpring faced was that the technology infrastructure had reached end of life and was becoming increasingly unmanageable.
1:32
If you have read the case study, you would know that their environment had grown exceedingly complex,
1:43
with around 30 key applications at their Singapore headquarters, plus more than around 20 additional applications spread across their operations.
1:47
This complexity was causing upgrade projects to stall, creating systemic problems that seemed almost impossible to resolve.
1:58
And most critically, their existing infrastructure could not sustain their planned business expansion.
2:07
The systems that had supported them in the past simply could not handle the decision making requirements of their growing organization.
2:14
No. For a financial services company where timely, data driven decisions are essential.
2:23
This situation represented an existential kind of threat to their future growth.
2:29
So what caused this situation? And we can extract several contributing factors from this case study.
2:39
First. Over the years, in-house developers, excuse me, had integrated and modified systems to work with existing legacy applications.
2:49
Now, each modification made sense at the time,
2:59
but collectively they created a web of dependencies that became increasingly difficult to maintain or upgrade.
3:02
Then business units across different regions had developed locally specific requirements,
3:11
leading to further customisation and complexity of what worked for operations in one country might not necessarily work in another.
3:16
Resulting in a patchwork of solutions rather than coherent systems.
3:26
Third. Applications had been built around these systems over time to cater to EastSpring's evolving business like this, their business grew and changed.
3:32
New functionality was bolted onto existing systems rather than redesigning them from the ground up.
3:42
So this case illustrates a common challenge in many organizations.
3:50
Systems that were once adequate become obstacles to growth as decision making requirements evolve and business complexities increase over time.
3:55
For spring, the solution would require much more than incremental improvement.
4:05
So faced with these challenges. EastSpring took a strategic approach, rather than attempting piecemeal fixes.
4:13
The case further tells us that in 2015, they began by reviewing all their business processes.
4:23
This fundamental first step was crucial because it focused on the business needs driving their systems rather than the technology itself.
4:30
They created a target operating model for the entire region, providing a comprehensive framework for what the future state should look like.
4:39
With this vision in place, they developed a three year project plan based on strategic classification of their processes.
4:52
They classified processes as critical, important, and unimportant for critical processes, those essential to their core businesses.
5:00
They would maintain control through an in-house team.
5:11
For important but non-core processes.
5:15
They would leverage outsourcing to gain efficiency while maintaining adequate oversight for unimportant processes.
5:18
They would simply use off the shelf products without customisation, accepting standardised functionality to reduce complexity.
5:26
And perhaps the most significant strategic decision was to prioritize systems with breadth of services,
5:38
rather than pursuing best in breed point solutions for each function.
5:45
This approach reduced integration challenges and created a more cohesive environment.
5:50
Notably, they made the bold decision to use off the shelf products for all processes and avoid in-house development entirely.
5:56
This meant each spring would need to adapt their business processes to match the new enterprise software,
6:06
rather than customizing the software to fit their existing processes.
6:12
This represented a fundamental shift in thinking that many organizations today struggle with.
6:17
So the impacts were many fold. EastSpring successfully expanded to 14 markets worldwide, including the U.K., U.S., Luxembourg.
6:27
The case study tells us they experienced growth around 25%.
6:36
Their ability to understand risk parameters for various firms improved significantly and enabled sophisticated decision making.
6:41
They moved beyond basic Excel spreadsheets to more sophisticated analysis capabilities.
6:50
And overall, these changes dramatically improved both operational efficiencies and decision making capabilities across the organization.
6:55
Okay. And I ask students, what can we learn from this?
7:03
First, business processes evaluation should precede technology implementation by starting with a comprehensive review of their processes each spring.
7:08
Ensure the technology would align with actual business needs rather than simply automating existing inefficiencies.
7:19
Then categorizing processes by strategic importance enables better resource allocation as before, in the case, by distinguishing between critical,
7:28
important and unimportant processes, this spring could focus their resources where they would create the most value for decision making.
7:38
Third. Sometimes adapting business processes to standard software can be more effective than customizations.
7:47
While customizations might seem ideal.
7:55
It often creates long term maintenance and upgrade challenges that outweigh the short term benefits of perfect fit.
7:58
Then cloud based solutions can also reduce infrastructure needs and specialized team requirements.
8:06
By embracing cloud technologies EastSpring, essentially reduce their need for specialized technical expertise in certain areas,
8:13
allowing them to focus their talent on more strategic initiatives.
8:21
Fifth strategic vendor selection. Aligned with specific business needs often yields better results than simply choosing the most feature rich options.
8:26
In case of East spring prioritized systems with breadth of services, rather than best-in-breed point solution.
8:37
You do. This reduced their integration challenges in the longer term.
8:45
And finally, a phased implementation enables learning and adjustment throughout the project.
8:50
Rather than attempting a big bang approach in the case, we saw EastSpring's three year plan,
8:58
allowed them to learn from early phases and adjust their approach as they progressed.
9:04
These learnings illustrate the importance of taking a strategic, business focused approach to enhance decision making,
9:12
rather than viewing the whole change as purely a technical challenge.
9:20
Right now that we have seen a real world example of rebuilding systems to enhance decision making.
9:26
Let's explore the theoretical foundations that help us understand different types of decisions and how information systems can support that.
9:34
Decisions fall along a spectrum of structure from highly structured to completely unstructured.
9:46
Not structured decisions are repetitive, routine decisions with well-defined procedures.
9:54
For these decisions, there is typically a clear right answer and a standard process to follow to get to that answer.
10:00
The case study provides a good example. If you remember that spring decided to use off the shelf solutions for processes like a job function.
10:10
These decisions can often be automated or supported by transaction processing systems, or what we saw earlier in earlier lectures as TPS.
10:20
Semi-structured decisions have some structure element but still require human judgment.
10:31
These decisions may follow some standard procedures, but they also involve variables that require interpretation and assessment.
10:38
In our today's case study offerings. Categorization of business processes as critical, important, or unimportant.
10:48
Represents a semi-structured decision. Because guidelines exist.
10:56
Where judgment is needed to apply the the guidelines correctly and classify the processes under various buckets.
11:03
So semi-structured decisions are often supported by decision support systems.
11:12
Then comes unstructured decisions. Unstructured decisions have no predetermined procedures or.
11:20
And they rely heavily on intuition, experience, and judgment.
11:27
There is often no clear right answer, and the decision may involve complex factors that are difficult to quantify.
11:32
In our case study EastSpring's strategic decision to completely overhaul their technology and their business
11:41
processes to match new enterprise software represents this type of decision.
11:48
Executive support systems, or ESS, typically assist with these decisions by providing high level information and analytical capabilities.
11:54
Understanding this spectrum helps organizations determine what type of information
12:05
system will best support different decision scenarios that they face.
12:10
Now. The types of decisions I mean to be made also vary by management level within the organization.
12:18
So let's. Let's take a moment to look into this particular aspect.
12:26
Senior managers. Senior managers such as CEO, CFOs, and other executives typically make many unstructured decisions.
12:31
They are dealing with strategic questions that have long term implications and often involve external factors and uncertainty.
12:41
These might include decisions about entering new markets, major capital investments, or organizational restructuring.
12:51
Executive support systems, or ESS, are designed specifically to support this type of high level decision making.
12:59
Then comes your middle managers.
13:08
Middle managers, like department heads and regional managers make more structured decisions, but often with unstructured components involved.
13:10
They might be implementing strategic initiatives from senior management while adapting them to their specific area of responsibility.
13:19
Decision support systems, or DSS, are particularly valuable at this level,
13:29
providing analytical tools and scenario modeling capabilities such as what-if analysis.
13:34
Then comes the operational managers, the operational managers,
13:44
and in rank and file employees generally make more structured decisions as part of their day to day activities at work.
13:48
These might include inventory reordering, customer service responses, or daily production scheduling.
13:56
Transaction processing systems, or TPS. And Management Information System or Mis.
14:04
Support these more routine decisions by providing accurate, timely information about operations.
14:10
This hierarchy of decision types help explain why organizations need different types of information systems to support decision making,
14:18
a different level. One size does not fit all.
14:27
When it comes to decision support in a real organization. Now let us apply our understanding of decision types to a practical scenario.
14:31
Imagine here an airline company with various decision scenarios across its operations, which are given in the second column.
14:43
Title decision scenario. So you have been given various different scenarios, such as whether to expand a line route into South America,
14:52
determine daily crew assignments for scheduled flights all the way to approving overtime for ground staff during peak season.
15:01
Take a moment to think about each scenario and classify it according to the decision maker,
15:10
which is the column after decision scenario, and then the last column on decision type.
15:16
This exercise will help you apply what we just learned or discussed in the earlier slides.
15:23
All right. I hope you have spent sufficient time to work through this activity.
15:33
And here are some sample responses for you to cross-check your understanding.
15:38
For example, whether to expand airline routes to South America would be an unstructured decision made by senior management.
15:43
This would involve complex strategic consideration about market potential, competition, regulatory requirements, and long term resource allocation.
15:51
Right. All the way to the end.
16:01
Approving overtime for Groundstaff during peak season is a structured decision,
16:04
typically made by middle management based on passenger volume, staffing levels, and budgetary parameters.
16:08
Okay. Now that we understand the types of decisions organizations are facing, make.
16:15
Let's examine the decision making process itself. Regardless of whether a decision is structured or unstructured,
16:25
the process typically follows four key phases intelligent design, choice, and implementation.
16:33
Intelligence is the first and foremost. This involves discovering, identifying, and understanding the process occurring in the organization.
16:42
Right. So you have to first discover, identify and understand the problems which are there in the organization.
16:54
This phase of intelligence is about sensing that something needs attention and gathering information to define the issue clearly.
17:02
This discovery phase often involves monitoring systems, performance metrics, and environmental scanning that actually show indicators of problems.
17:12
For example, in East Spring's case, they recognized that their aging systems were becoming unmanageable and were limiting business growth.
17:22
Now once the problem is understood. Design phase focuses on identifying and exploring potential solutions.
17:35
It involves developing alternative creating models and establishing criteria for evaluating the options.
17:43
In the Springs case.
17:51
The company engaged in this phase when they reviewed all their business processes and created their target operating model, or for the whole region.
17:52
Then the third phase is choice. This is where decision makers select from among the solution alternatives they have identified in the earlier phase.
18:06
The selection process might involve optimization for structured problems or judgment for unstructured ones.
18:16
Each spring, for example, made their choice when they decided to classify processes as critical,
18:23
important or unimportant, and selected their implementation approach according to their classification.
18:29
Finally. Implementation.
18:37
Implementation involves making the chosen alternative work and continuing to monitor how well the solution addresses the original problem.
18:40
Success here often depend from change management as much as technical execution.
18:50
Each spring three year phased implementation plan illustrates this stage of the process.
18:55
Information systems play different roles at each stage.
19:03
They help detect problems during intelligence, provide analysis tools during designed,
19:07
often offer decision models during choice, and support execution during implementation.
19:13
Understanding this process. Health organization design more effective decision support system.
19:20
While the decision making process we just discussed provides a useful framework.
19:30
Real world decision making is often messier and more complex.
19:35
There are three main reasons why investments in information technology do not always produce positive results when it comes to decision making.
19:41
First is the the problem of information quality.
19:50
Information quality can be a significant challenge.
19:55
High quality decisions require high quality information that is accurate, timely, complete and relevant.
19:59
However, many organizations struggle with data quality issues such as inconsistent data, outdated information, or incomplete records.
20:07
All the sophisticated analytics in the world will not help if the underlying data is flawed.
20:17
This is why spring's approach of reviewing all the business processes before implementing
20:24
new systems was so important that it likely included addressing data quality issues.
20:30
Second comes management filters because management filters can distort how information is perceived and used.
20:38
Managers have selective attention and various cognitive biases that may cause them to
20:47
reject information that does not conform to their prior conceptions and expectations.
20:52
For example,
20:59
a manager might pay attention to sales data that confirms their marketing strategy is working while ignoring indicators suggesting otherwise.
21:00
These human factors mean that even the perfect information system that you have.
21:10
May not be able to guarantee perfect decision making.
21:17
Third, organizational inertia and politics often resist major change.
21:25
Strong forces within organizations, from embedded work processes to stakeholder interests, can oppose decisions that call for significant changes.
21:31
In many cases, the technical capacity to make better decisions exist, but organizational factors prevent implementation of those decisions.
21:43
Each springs decision to adapt their business processes to match standard software, rather than customizing software to existing processes.
21:53
Represents a conscious effort to overcome this kind of organizational inertia.
22:01
These realities actually highlight that enhancing decision making through information systems is not just about technology,
22:08
but about addressing the human and the organizational contexts in which decisions are constantly being made.
22:16
The most effective approaches you will see, read, recognize, and account for these factors,
22:24
rather than assuming that better technology alone will automatically lead to better decisions.
22:30
Now let us shift our focus to an increasingly important trend high velocity automated decision making.
22:40
This term represents a significant evolution in how organizations use information systems today to support decision processes.
22:48
High velocity automated decision making is made possible through computer algorithms
22:57
that precisely define the steps for handling highly structured decision.
23:02
In these systems, humans are taken out of the decision loop entirely for specific types of transactions and processes.
23:09
This automation allows for decisions to be made in fraction of seconds rather than minutes, hours or days.
23:17
Singapore offers several excellent examples of this approach in financial services.
23:25
DBS Quick Finance leverages automated decision making to approve loans for small businesses within minutes rather than weeks.
23:31
Traditional processes might require the system analyzes the applicant's transaction history,
23:40
credit profile, and other points to make instant lending decisions without human intervention.
23:46
But while we do not know the details of the exact system, what this is, how a system might work.
23:55
In e-commerce. Lazada and Shopee use dynamic pricing algorithms that automatically adjust product prices,
24:03
perhaps based on factors like inventory levels, time of the day, and the customer browsing behavior.
24:10
These systems make thousands of pricing decisions every hour.
24:16
That would be impossible for human managers to handle. Then in manufacturing smart factory systems at Jurong Innovation District,
24:20
continuously monitor production lines and automatically adjust parameters for optimal performance.
24:30
These systems can detect quality issues and reroute production, or adjust machine settings without waiting for human decision to be made.
24:37
Now, what's remarkable about these examples is that they are not just speeding up existing decision processes.
24:46
They are fundamentally transforming them by embedding decision logic into algorithms.
24:53
Organizations can achieve consistency, speed, and scaling capabilities that were not possible in human centric approaches.
25:00
Of course, automated decision making is most appropriate for highly structured, well understood decision scenarios.
25:09
Unstructured decisions still require human judgment and intuition.
25:16
The key here is identifying which decisions can be automated and which require human involvement, and then only designing systems accordingly.
25:21
Now let's end this part of the lecture video with business intelligence, which is the heart of modern decision support.
25:33
Business intelligence encompasses the infrastructure for collecting, storing, and analyzing data produced by various business components.
25:42
This includes databases, data warehouses, and data marts that we discussed in our earlier session on data management.
25:53
Built on this foundation is business analytics, which refers to the tools and techniques for analyzing data.
26:03
These include online analytical processes, processing OLAP, statistical analysis,
26:11
predictive modeling, data mining capabilities that transform raw data into actionable insights.
26:17
We will study a lot of these in TCX2002.
26:25
Numerous business intelligence vendors create and sell these capabilities as packaged solutions.
26:33
Companies like Tableau, Microsoft with power BI, and software like SAP,
26:38
provide tools that organizations can implement to enhance their decision making capabilities.
26:45
It's important to understand that business intelligence is not just one tool or one system.
26:52
It's a whole environment where data sources are connected to analytical tools and then to delivery platforms like dashboards or reports.
26:58
These parts work together to support better decision making across an organization.
27:07
For example, sales data from a CRM system can be analyzed using power BI software and then shared through
27:14
an interactive dashboard to help managers adjust their sales strategy in real time.
27:21
All right, so in the next section,
27:28
we will explore the specific analytical tools that business intelligence systems provide and how they help organizations identify relationships,
27:29
patterns and trends in their data. Okay, so I'll see you in the next video.
27:38
