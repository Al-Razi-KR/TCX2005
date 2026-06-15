# L7_Part-4_Big-Data-and-Business-Intelligence — Raw Transcript

Auto-generated captions may contain errors.

Modern DBMs platforms provide several key capabilities that make them indispensable.
0:05
The data definition capability to start with allows administrators to specify the structure of data.
0:12
And then what fields exist? What are their types and what are their relationships?
0:19
This information is stored in the data dictionary. It is a comprehensive catalog of all data elements in the database.
0:25
In the table. On the slide, you see a small part of a data dictionary, which can have many more fields or columns in real life.
0:36
For updating, removing, or querying the data for reporting.
0:45
DBMs platforms provides sophisticated tools. The Data manipulation language allows users to add, change, delete, or retrieve data.
0:50
I'm sure you must have heard of Structured Query Language or SQL, which has become the standard for database operations.
1:02
Many DBMs platforms also include report generation capabilities.
1:10
For example, Microsoft Access can create quite nice, polished reports without additional programming.
1:15
These capabilities transform raw data into actionable information exactly what is needed for their customer insights.
1:24
As data becomes more complex and abundant. Organizations are turning to newer technologies to meet their needs.
1:37
For example, non-relational databases, which are often known as NoSQL databases, offer a flexible alternative to traditional relational.
1:47
Dimensional systems. They store data across distributed machines and are built to scale horizontally,
1:56
making them ideal for managing massive volumes of structured and unstructured data.
2:04
This includes things like social media posts, images, sensor logs, and much more.
2:10
At the same time. Cloud databases are also gaining popularity, especially among startups and smaller organizations.
2:19
Services like AWS or Microsoft Azure eliminate the need to manage infrastructure manually,
2:29
while private cloud deployments provide similar benefits with added control.
2:38
These tools. Were instrumental in Astros move to modern Data Lake, giving them flexibility and scalability to manage diverse data types at scale.
2:44
Now that we have seen how these technologies support storage and flexibility,
2:56
let us also look at the bigger challenge driving this shift in the market.
3:02
Big data. Let's take a closer look at the growing challenge of big data.
3:09
Big data refers to massive sets of unstructured and semi-structured data that are generated continuously from a variety of resources.
3:15
These include web traffic, social media activity, sensor output, and data from connected Internet of Things devices or IoT devices for short.
3:26
The volume of this data is enormous. We are no longer talking about gigabytes or terabytes, but petabytes and exabytes,
3:38
which are far beyond the processing capability of typical database systems.
3:47
What makes big data valuable is not just its size, but the patterns, relationships, and anomalies it can reveal.
3:52
And these insights often go undetected in traditional tools.
4:00
However, working with big data requires specialized technologies that can store, process, and analyze it efficiently.
4:06
To understand this better, let's walk through an example. Imagine a retail chain that collects point of sale data from cash registers.
4:15
This is structured data neatly organized into rows and columns.
4:24
Now add customer reviews to this data with reviews which are written in free text.
4:30
These are semi-structured data points. Then include security camera footage, which is unstructured video data,
4:37
and combine that with in-store movement patterns from floor sensors, which represents IoT data.
4:45
Think about it. Managing all of this together using traditional database would be incredibly difficult if you're if at all.
4:53
If not impossible. But big data technologies are designed to handle this kind of variety.
5:01
They can integrate and analyze these diverse sources to uncover rich, meaningful insights, for example,
5:10
patterns in customer behavior that help improve store layout, marketing strategies, and inventory planning.
5:18
Now comes the question of business intelligence infrastructure.
5:27
The infrastructure that allows organizations to turn all this kind of device data into meaningful business insights.
5:31
Business intelligence infrastructure refers to the systems that collect, process, and transform data into valuable insights.
5:42
At the core of all these are data warehouses which consolidate data from operational systems.
5:51
These warehouses are optimized for analysis rather than real time transactions,
5:59
and serve as the foundation for reporting and decision support systems.
6:04
In addition,
6:11
data marts provide focused subsets of the warehouse tailored to specific business functions such as sales data mart or financial data mart.
6:12
6:12
When working with massive data sets, especially in big data environments.
6:23
Tools like Hadoop play an important role. Its distributed file system or HDFS enables scalable storage across multiple machines.
6:27
While the technique of MapReduce allows parallel processing of large volumes of data.
6:38
These technologies help us organize and process data at scale.
6:45
But how can we go from large scale processing to real time insights?
6:50
Building on the foundation of traditional data warehouses. Many organizations now deploy high speed analytical platforms.
7:02
These platforms combine relational and non relational tools and are optimized for performance with large datasets.
7:11
A key innovation here is in-memory computing and processing, which stores data in Ram or random access memory rather than on disk.
7:21
This drastically improve speed and reduces analysis time from hours to just seconds.
7:31
The result is a system that supports real time decision making.
7:38
Organizations can now detect fraud as it happens. Personalized services instantly or respond to market shifts in real time.
7:43
This level of agility is increasingly becoming essential for data driven businesses,
7:52
and it reflects how far business intelligence infrastructure has evolved.
7:58
From static reports to live, dynamic insights that support real time strategy formulation or execution.
8:04
This diagram gives us a high level view of how data flows to a modern business intelligence infrastructure.
8:16
It all begins with multiple data sources, including operational data, historical records, IoT, streaming, web and social media data, and phone data.
8:25
External third party sources. These diverse data types are collected and processed using an ETL process which stands for extract, transform and Load.
8:36
Some of this data flows directly into data warehouse, optimized for creating and reporting.
8:49
While unstructured or high volume data is sent to a Hadoop data lake for scalable storage and processing.
8:57
The final process. Data is then available in data warehouse and specialized data marts to be used by analytical platforms.
9:04
From here, insights are extracted using tools on an analytics platform, which supports advanced techniques like data mining and real time query.
9:13
These insights are then delivered to different users across the organisation.
9:24
For example, casual users who use dashboards and pre-built reports for their day to day decision support.
9:30
And power users, such as data scientists, who run deeper queries and uncover trends using sophisticated tools.
9:38
What is important here for us is the architectural separation between transactional systems and analytical environments.
9:46
This design ensures that heavy analysis workloads don't slow down day to day operations like order processing or payments.
9:54
Together. The setup creates a scalable, efficient and insight driven infrastructure that supports both strategic planning and operational decision.
10:05
Let's talk about tools for business intelligence.
10:21
Modern business intelligence depends on a range of powerful analytical tools that help organizations unlock value for their from their data.
10:25
These tools are designed to consolidate, analyze, and give users easy access to large volumes of data, enabling better and faster business decisions.
10:34
One key tool is OLAP, or Online Analytical Processing.
10:45
It enables users to examine data across multiple dimensions, such as analysis by products,
10:50
analyzed by region, analyzed by trend or time periods, or customer segments.
10:58
For example,
11:05
a manager can instantly compare sales of hardware department in Eastern Region last June to performance in other regions or across other months.
11:06
Another important tool is data mining, which helps uncover hidden patterns and relationships within larger datasets.
11:17
It is often used to build predictive models, such as identifying customers who are more likely to cancel a subscription,
11:28
or for banks, who are the customers more likely to default on the loans they have taken.
11:36
Then comes text mining. Text mining is used to extract meaning from semi or unstructured data sources like email support tickets or customer reviews.
11:45
It can help organizations analyse sentiments, detect emerging issues or categorise feedback at scale.
11:56
Lastly, Web Mining, which focuses on data from websites and online platforms.
12:05
It looks at how users navigate a site, which pages they visit, how long they stay, and what content drives engagement or conversion.
12:12
Together, these tools turn raw data into actionable insights that support wide range of decisions,
12:22
from day to day operations to long term strategic planning. Now let's talk a bit about governance and data quality.
12:28
Here's a sobering statistic. More than 25% of critical data in fortune 1000 company databases is inaccurate or incomplete.
12:40
Poor data quality undermines all the sophisticated analytics we have discussed.
12:51
So before implementing any new database system,
12:57
organizations must identify and correct faulty data and establish better routines for maintaining data quality.
13:00
This is not just a technical challenge, as it requires organizational commitment and clear processes in place.
13:09
Consider the impact of poor data quality. Such as wrong decisions based on faulty analysis.
13:17
Customer dissatisfaction from incorrect information. Regulatory compliance failures and wasted resources.
13:25
Chasing data errors. That is why data quality must be addressed systematically, not as an afterthought.
13:32
Effective data management requires a comprehensive governance framework with clear roles and responsibilities.
13:47
Data Administration creates and enforces specific policies and procedures for data handling.
13:55
Information Policy contains the rules for data sharing and management across the organization.
14:04
Data governance, on the other hand, takes a broader view managing data availability, usability, integrity and security across the enterprise.
14:13
This includes establishing data standards, defining ownership, and ensuring regulatory compliance.
14:24
Quality assurance involves regular data quality audits,
14:32
data cleansing initiatives to fix existing problems, and ongoing monitoring to prevent new issues.
14:37
Organizations like Astro succeed because they do not just implement new AI systems and technologies,
14:45
but they also establish governance frameworks to ensure their data remain accurate, consistent, and valuable.
14:53
