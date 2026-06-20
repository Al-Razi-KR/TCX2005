# L10_Part-4_OO-Development-and-AI-Tools — Raw Transcript

Um. Let's explore. Object oriented development, which represents a fundamental shift in how we think about building information systems,
0:04
rather than focusing on process and data flow separately.
0:14
Object oriented approaches integrate data in the process that act on the data into cohesive units we call objects.
0:19
An object serves as the basic unit of system analysis and design.
0:27
It combines data and the processes that operate on those data into a single, self-contained entity.
0:33
Importantly, data in an object can be accessed only by operations associated with that object.
0:41
This provides better security and data integrity.
0:48
Object oriented modeling is based on concepts of class and inheritance.
0:53
Objects belong to a certain class and have the features of their class.
0:59
To give you an example. In a university system, all student objects might belong to a student class that defines common attributes like name,
1:05
I.D. number, and enrollment status, along with common operations like enroll in a course or calculate GPA, etc.
1:15
Objects may inherit structures and behaviors from a more general ancestor class.
1:25
For instance, student and faculty objects might both inherit from a more general.
1:31
Person class that defines common attributes like name and address.
1:37
This inheritance mechanism promotes code reuse and maintains consistency across related object.
1:42
The object oriented approach offers several advantages over traditional structured methods.
1:51
It is more intuitive because it models the real world more naturally.
1:58
It promotes reusability because objects can be used in multiple systems.
2:03
And it supports better maintainability because changes to an object's internal implementation do not affect other parts of the system that use it.
2:08
Object oriented development takes a more iterative and incremental approach compared to your traditional structured development.
2:22
This makes it especially useful for projects where requirements may evolve over time,
2:31
which, as you might know, happens quite often in real world system development.
2:37
During the systems analysis phase,
2:42
the focus shifts from mapping processes to identifying key objects based on how the system interacts with its users.
2:45
Analysts look for real world entities the system needs to model and represent.
2:54
In a university setting, for example. Objects might include student object, course object, instructor object, and registration object.
3:00
Each representing a core concept in the whole system.
3:09
In the design phase, we defined how these objects behave and interact and interact with each other.
3:14
Objects are grouped into classes and subclasses, which are often arranged in hierarchies that reflect real world relationships.
3:23
Each class outlines what an object can do via its methods and what kind of data it holds via its attributes.
3:31
To give you an example, the student class may include attributes like student ID,
3:40
the student GPA, and methods like enrollment in a course or dropping out of a course.
3:46
One of the key strengths of object oriented design lies in its reusability.
3:55
During implementation, developers can pull classes from existing libraries.
4:02
They can modify them on inherit from them to create new classes.
4:07
If you already built a solid student class for one system,
4:13
you can often reuse or adapt it for another system that you are developing, which saves essential time and effort.
4:18
This reuse potential helps reduce both development time and cost,
4:27
particularly for organizations which are which are building multiple related systems.
4:32
So object oriented development is not just a technical alternative.
4:38
It's a mindset shift that aligns closely with the complexities and modularity needs in modern system development.
4:41
Now that we have seen how object oriented and iterative methods better suit evolving requirements,
4:52
it is important to contrast this with one of the oldest yet still widely used approaches in systems development.
4:59
The traditional SDLC is often referred to as the waterfall model,
5:07
which is one of the earliest and most structured methodologies for system development.
5:12
The traditional waterfall model follows a strict sequence starting at defining, designing, build, test and deploy.
5:18
It offers structure, clear documentation, and works well in stable settings like infrastructure or government projects.
5:28
But do note that it's slow and hard to adapt to changes.
5:36
Now, while many organizations still build their systems internally using structured or object oriented approaches,
5:51
not all choose to go with this route.
6:00
In fact, many firms today are asking a different question.
6:03
Should we build or. We buy or outsource the complete process entirely.
6:07
This brings us to our next topic, which is outsourcing.
6:15
These days, cloud based services, vendor built apps and even offshore teams are very common.
6:21
Outsourcing offers flexibility. And cost savings.
6:29
But it does come with risks like vendor lock-in.
6:34
Hidden costs and data security concerns. Outsourcing might look cheaper on paper, but the real cost is often much higher than the initial price tag.
6:37
Why? Because transitioning work to an external vendor takes time and effort.
6:52
You need to train the vendor, share internal knowledge, and often run both systems in parallel for a while, which doubles the workload temporarily.
6:57
Then there's contract management, regular check ins, quality control, and communication across different time zones or working cultures.
7:07
All of this requires internal staff time and coordination.
7:17
You may also face reverse course if the outsourced solution doesn't fully meet expectations and lost agility.
7:22
If vendor timelines or capabilities do not really align with your needs.
7:29
And finally, it can distract your leadership or IT team from focusing on core priorities like innovation or strategy.
7:35
But because they are now managing the outsourcing relationship.
7:44
So when make outsourcing decisions, organizations must always look at the total cost of ownership and not just the vendor scope.
7:49
That's the only way to make an informed and long term good choice.
7:58
Those who look beyond traditional and object oriented approaches, we see a powerful new force reshaping how systems are built.
8:08
This force is AI and machine learning.
8:16
Machine learning. This isn't just about using AI inside systems.
8:20
It is about using AI to build the systems themselves.
8:25
Let's start with code generation. Tools like GitHub Copilot act as intelligent assistant.
8:31
Nowadays generating working code directly from natural language instruction.
8:37
This significantly speeds up the development phase, but it still needs human review for quality and fitness.
8:42
Then we have requirements engineering. AI tools can now scan documents, emails or transcripts to extract and structure requirements automatically.
8:51
This reduces the risk of missing critical user needs. In testing, I can create test cases and sample data based on the system specification.
9:02
It is faster and often catches edge cases that human developers might miss.
9:14
Even documentation, which is often overlooked during tight deadlines.
9:20
Can now be generated automatically now, whether it's user manual or internal technical guide.
9:25
You can create a good quality manual.
9:32
And finally the UX and UI design.
9:37
I can translate requirements into draft interfaces, which offers a quick starting point for designers to refine this,
9:42
bring ideas to life faster, and helps team visualize user journeys earlier in the process.
9:51
Together, these tools are changing what it means to develop systems today.
9:58
But the key point is AI enhances, not replaces human judgment.
10:04
Domain understanding and alignment with business strategies are still essential and should be focused on.
10:11
This is where future professionals like us come in, because we are the bridge between AI powered development tools and real world business needs.
10:18
It's also transforming what systems can do.
10:31
Bots answer queries, AI writes report finds pattern in our data and forecast demand.
10:35
It even maps processes to suggest automation.
10:42
So I hope you see that these tools are changing how businesses operate, not just how we build systems.
10:48
Let's look at how all this plays out in real world and at scale.
11:00
J.P. Morgan Chase is one of the world's largest financial institutions, developed an AI system called Coin Contract Intelligence.
11:06
What was its job?
11:15
To review complex legal documents like loan agreement, which is a process that used to consume 360,000 hours of lawyer time every year.
11:17
Coin uses machine learning and natural language processing to scan contracts,
11:28
extract key terms, and identify critical clauses, all done within seconds.
11:33
What once took hours per document is now done instantly with higher accuracy and zero fatigue.
11:40
But here's what's important. It did not replace the lawyers.
11:49
It elevated them. Instead of spending time on routine checks.
11:53
Lawyers now can focus on exception handling, negotiation, and strategic legal thinking.
11:58
The routine was automated, but the expertise remained human.
12:05
This case shows how even just a productivity tool, it's a strategic asset.
12:10
It creates value by freeing up people to do what they do best while ensuring speed, consistency, and scale.
12:16
And for IS professionals,
12:25
it's a reminder that successful AI systems solve clear business problems with the right mix of data design and human oversight.
12:27
