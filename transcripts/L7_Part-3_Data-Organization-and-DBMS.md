# L7_Part-3_Data-Organization-and-DBMS — Raw Transcript

Auto-generated captions may contain errors.

Now that we have seen how Astro organized their data infrastructure, let us understand the fundamental terms and concepts of data organization.
0:07
Think of data organization like a filing system in your office, but on a much larger digital scale.
0:17
At the highest level. We have database, which is a group of related files working together.
0:23
For example, a university database might contain files for students, courses, faculties and grades.
0:29
A file is a group of records of the same type.
0:38
Your student records file would contain information about all students at the university.
0:43
Now coming to a record. A record is a group of related fields describing one instance.
0:49
Your individual student record contains your name, your ID, your major, your GPA, and other personal information.
0:55
A field is a group of characters representing a single attribute.
1:04
For example, your student ID number is one field, your name is another field.
1:10
These concepts relate to entities and attributes.
1:16
The working entity an attribute. An entity is any person, place, or thing about which we store information.
1:20
Like we store information about a student, or we store information about a course.
1:29
The student is an entity course in an entity. An attribute is each characteristic describing some entity like student name of course.
1:34
Credits. Right. So they describe that entity.
1:45
But understanding these building blocks is crucial because they form the foundation of all data management systems,
1:49
from simple spreadsheets to complex data lakes that we saw in Astros case.
1:56
Let's look at something called data hierarchy. This diagram on the slide illustrates the data hierarchy visually.
2:02
Notice how data builds from smallest unit bits and bytes representing individual characters up through fields, records, files, and finally databases.
2:10
For example, the characters will again form a field for firstName John.
2:24
Combining with other fields like LastName id, they format student record.
2:31
When you put multiple records together, it creates a student file and various files together form the complete student database.
2:39
This hierarchical structure allows for efficient data organization, retrieval and management,
2:48
which are some of the essential capabilities for any information system.
2:55
Now, modern organizations face a critical challenge regarding the data resource.
3:04
So data has become one of their most valuable assets. But managing that data effectively and efficiently is becoming more complex every day.
3:10
Modern businesses generate and consume massive volumes of data from a wide range of sources.
3:22
From transactions and websites to mobile apps, social media, sensors and much more.
3:29
With this growing volume, variety, and velocity of data.
3:38
Traditional file-based data environments start to break down in several ways.
3:42
It highlights four common problems. First is redundancy, or rather data redundancy and inconsistency.
3:48
This happens when the same data is stored in multiple places.
3:57
Often with slight differences, it leads to confusion, errors, and unnecessary storage costs, as you can imagine.
4:01
This is one of the most frequent and impactful issues in legacy systems, or older systems.
4:10
Second program, data independence. Now what is this?
4:17
In traditional environments, applications are tightly coupled to the structure of the data.
4:22
Even small changes in data formats require corresponding changes to the programs that access the data.
4:29
This makes upgrades slow and risky. Third, limited flexibility and poor security.
4:37
When systems are isolated and rigid, it becomes difficult to adapt to new requirements or respond to emerging threats.
4:45
Security measures are often inconsistent across disconnected systems or siloed systems.
4:54
Unfortunately, the problem of limited data sharing and availability when data is trapped in siloed teams cannot access the full picture.
5:01
This restricts collaboration between the teams, slows down decision making, and reduces the value that what all data would have provided.
5:10
If you look at this image on the slide. You will see that data redundancy is identified as both frequent and highly impactful,
5:21
often leading to inconsistent records, duplication of efforts, and unnecessary storage cost.
5:34
Program. Data dependence is also flagged as a common challenge in legacy systems, when applications are tightly coupled to specific data formats.
5:41
Even a small structural change can require widespread updates, making systems difficult to maintain and slow to adapt.
5:51
Together, these issues highlight why many organizations, including companies like Astro, are investing heavily in modern data architecture.
6:00
By reducing redundancy. Decoupling programs from rigid data structures and improving data sharing.
6:10
They are building systems that are more agile, reliable and scalable.
6:19
Okay, next, let's zoom in on one of these issues, program data dependence, and try to understand it better.
6:26
This is one of the most frustrating and costly challenge in traditional file based systems.
6:39
Imagine a company stores customer names in a file with each name limited to 30 characters at the time of design.
6:45
As the business expands internationally. Customers with longer names start to appear.
6:54
And the company decides to increase the field length from 30 to 50.
7:00
Characters. In a traditional system, this simple adjustment requires a significant effort.
7:05
Every program that accesses the customer file now must be updated.
7:12
This includes customer service interface, invoices, generators, reporting tools, and analytics scripts.
7:18
In addition, existing data must be converted.
7:26
Report layouts need to be updated and every modified application must go through testing again.
7:30
This result in added cost delays and the risk of introducing unforeseen new errors.
7:36
This situation illustrates what we mean by program data dependent.
7:46
When programs are tightly connected to the structure of the data.
7:51
Even small changes to that structure become a major technical challenge.
7:55
Modern database management systems. Address this problem by separating the way data is defined from the way applications access the data.
8:02
Instead of working directly with data format. Applications interact with the database through a layer called a DBMS, or a database management system.
8:12
This separation allows changes to the physical data structure without requiring changes to the application layer.
8:23
This principle is known as physical data independence.
8:32
It allows systems to be more adaptable, maintainable, and future ready.
8:36
While it may sound a bit technical,
8:42
physical data independence is essentially for building systems that can keep up with evolving business needs without slowing everything down.
8:45
Let's take a moment to visualize how data problems arise in traditional file processing environments, so that this concept is fully clear.
9:02
As you can see in this diagram, each department such as accounting, human resources,
9:11
sales, manufacturing, they all maintain their own systems and separate data files.
9:18
Each department also uses its own applications to interact with the data.
9:25
What this means in practice is that the same information, like customer details or product data,
9:31
might be stored in multiple places across different departments.
9:37
Each system may use its own data format, its own update schedule, and its own set of rules.
9:42
Now. This fragmented approach creates several major problems.
9:49
First. Data redundancy becomes a serious issue in this practice when the same data is stored in multiple locations.
9:53
It waste storage increases maintenance effort and raises costs.
10:02
Then data inconsistencies are also likely to occur.
10:09
For example, if one department updates a customer's address but the others do not.
10:12
The organization ends up with conflicting versions of the same customers.
10:17
Information. Finally, while generating integrated reports,
10:23
it becomes extremely difficult to synchronize or reconcile the whole data without a unified source of truth.
10:28
Reporting across departments require manual reconciliation and which is prone to error.
10:35
These issues not only impact data quality, but also hinder coordination across the organization.
10:42
That's why modern businesses are moving towards more centralized databases and shared data environments.
10:49
Well, in our next section, we will explore how modern systems solve some of these problems using database technology.
10:57
Here's a real world example for you. Imagine a customer move to a new address in a traditional system.
11:14
This change must be updated separately in the sales department's file, the billing department's file, and the shipping department's file.
11:21
If any department misses the update or enters it incorrectly.
11:29
Inconsistencies arise. The customer might receive bills at the old address while shipments go to the new one.
11:34
It is a frustrating experience, as you can imagine, that can potentially damage customer relationship.
11:42
So this simple example illustrates why modern organizations need more integrated data management systems.
11:49
So now let's finally go and see how database management systems solve some of these problems.
11:55
Database management systems represent a fundamental shift in how organizations.
12:09
Manage their data. Instead of each application maintaining its own files,
12:14
DBMs or database management systems centralizes data and provides controlled access to all authorized users and applications.
12:20
A database serves many applications by centralizing data and controlling redundancy.
12:32
The DBMs acts as an interface between applications and physical data files,
12:40
providing a consistent view of organizational data for whoever needs the data.
12:45
This approach solve the problems we have discussed because it controls redundancy by storing each piece of data only once.
12:52
Eliminates inconsistency through centralized updates, separates program from data structures, and enables centralized data management and security.
13:00
For example. When the customer address field needs to expand from 30 to 50 characters.
13:11
Only the central data definition of the address changes.
13:19
All applications continue working without modification because they access data through DBMs interface.
13:24
This is the foundation that enables modern data solutions like Astro's Data Lake by providing flexibility, consistency and scalability.
13:32
On the slide, you see a concrete example of how a DBMs provides multiple views of the same data.
13:48
On the extreme left, this human resource database demonstrates how users can access the same underlying data in ways that suit their specific needs,
13:56
so the data base might contain comprehensive employee information.
14:07
Like your employee ID name, social security number.
14:13
Positions holding the organization, date hired, and so on and so forth.
14:17
But the recruiter sees candidate and hiring data.
14:23
And while the benefit specialist sees enrollment and eligibility information,
14:27
the payroll clerk accesses salary and tax information, and the manager views performance and team data.
14:33
All these views come from the same integrated database, ensuring consistency while providing role appropriate access.
14:40
This is how modern DBMs systems support multiple information needs with single source of data.
14:49
Okay, let's take a short pause here.
14:56
And when we come back, we'll explore specific DBMs capabilities and newer database technologies that are enabling modern data architectures.
14:58
