# Unidad4

### Describe the different data analysis architectures.
The data architecture is a fundamental element for the information management and business organization systems to be successful.
It integrates the models, policies and rules that govern what data is to be collected; how they will be stored, classified and exploited through the available technological infrastructure.
In the same way that data architecture is critical to the good management of a company, so is its corporate strategy, so it is necessary to take care of its design and implementation. The two are related, since if something fails in the design of the corporate strategy, there may be many failures in data management and, consequently, in the organization of the company. A migration process, for example, can become a real headache if the database design presents problems.
An example of a well-defined data architecture are those companies that, after learning about the changes to be applied to the RGPD, adapted their databases before the regulation came into force.
Costs reduction
The most powerful and potential data technologies, such as the Hadoop system and cloud-based analytics, must be brought into use. These generate a cost advantage, since when it comes to storing large amounts of data, there is a large amount of supply that shows exponential growth in the following years, also allowing us to identify more efficient ways of marketing.
Faster decision making
Referring to the Hadoop system, its speed and information analytics, combined with the ability to analyze new data sources, serve companies to have information immediately (either as a summary or as specific data that is required ) and in this way make decisions based on what they have learned (artificial intelligence).
Generate new products / services
Big Data offers the ability to analyze and measure customer needs, therefore, their satisfaction is given through the analysis of their information, with which it is possible to know with certainty what they want or need. Through analytics, companies create new products and services to meet the demands of their customers. They can even generate new needs that they did not know they had.
### Identify the characteristics of a data center.
1. Security: Data is the fundamental support of any business model in the modern era, so ensuring information security is one of the main priorities of companies. On the one hand, it is necessary to take into account the protection measures that will be implemented in the physical environment. In this sense, the access control measures (identification cards, biometrics, etc.) stand out so that only authorized personnel can contact the data center. On the other hand, it is essential to have protection tools such as data encryption. , either by hardware or by software, as well as security solutions against the loss of information and / or corruption in power failures.

2. Cooling: Achieving an ideal temperature environment is also a very important point in order to obtain the best possible performance from the data center. Since it must be in continuous operation, it is essential to establish an optimal cooling system to avoid that high temperatures adversely affect the performance, efficiency and useful life of the components. In this scenario, it is necessary to emphasize that the refrigeration system should not only focus on reducing heat and maintaining optimal operating temperatures, but it should also control humidity levels.

3. Storage capacity: As larger amounts of data are generated, companies demand storage solutions with greater capacities. Thanks to technological advancement, companies have at their disposal storage units (either conventional hard drives or solid state drives) that have increasingly higher capacities that allow this high volume of information to be stored without problems.

4. Data transfer: Storage capacity is useless if it cannot be accessed quickly. In this sense, it is essential that the data transfer (in reading or writing) occurs quickly, since this way we promote accessibility to information. Likewise, it is essential that there is an optimal level of information transmission speed between the data center and the rest of the devices is optimal.

“A Data Center is a physical or digital space where all the information, systems and resources necessary for the proper functioning of a company are stored. Therefore, the proper functioning of this storage system is critical for any business model, ”says Pedro González, Kingston's business developer in Spain. "In this sense, from Kingston we work to offer SSDs with the best characteristics of both performance, security and durability, with the aim of helping companies protect their information and have a data center of the highest quality" adds González.
### Cloud Computing Features
According to NIST, the cloud computing model is made up of five fundamental characteristics:
• Self-service on demand
• Ubiquitous access to the Internet, unlimited and multiplatform
• Offshoring of data and processes
• Scalability and flexibility
• Supervised service
Although not directly specified, an inherent feature of cloud computing is high dependency on third parties. Whether you work with the type of cloud you work with, there will always be a contracted company to serve as the service provider. As we have already commented, this fact allows us as a company to “forget” about the maintenance and management of resources. It is the service provider that is responsible for all processes and information security. In conclusion, the corporate migration to the cloud will bring a great number of advantages to the organization, such as:
• Reduction of costs and payment for use
• Automation of maintenance tasks
• Increased storage capacity depending on needs
• Flexibility
• Increased data access capacity and productivity
### Fog Computing
Fog Computing (FC) is the concept of a network structure that extends from the outer edges of where data is created to where it will be stored, whether in the cloud or in a customer's data center.
Fog is another layer of a distributed network environment and is closely related to cloud computing and the Internet of Things (IoT). Public infrastructure as a service (IaaS) cloud providers can be viewed as a high-level global endpoint for data; The edge of the network is where the data from the IoT devices is created.
FC is the idea of ​​a distributed network connecting these two environments. "Mist provides the missing link in data that needs to be sent to the cloud, and what can be analyzed locally, at the edge," explains Mung Chiang, dean of Purdue University's School of Engineering and one of the leading Fog Computing and Edge Computing researchers.
Real-time analysis: A large number of use cases require real-time analysis. From manufacturing systems that need to be able to react to events as they happen, to financial institutions that use real-time data to inform business decisions or control fraud. Fog computing implementations can help facilitate the transfer of data between your created place and a variety of places where you need to go.
### Data Engineering
the concepts of science and data engineering are wrongly considered synonymous. The truth is that the first one acts at the tip, near the end user; while the latter operates closer to the base of the infrastructure and is therefore sometimes considered less glamorous and often ends up being neglected.

However, when it comes to data science, it requires intelligence and the ability to carry out consolidated analyzes, providing forecasts for business development. Data engineering is a fundamental part of the process of extracting value from databases, most of the time, rustic and from various sources. In a practical way, if there is no good process in the area, data science fails to exercise its role.

### Define the concepts of data acquisition, management, process and administration.

Data acquisition systems, as the name implies, are products or processes that are used to collect information to document or analyze a phenomenon. In its simplest form, a technician who records the temperature of an oven on paper is executing data acquisition.

Data management is the practice of organizing and maintaining data processes to meet the needs of the continuous life cycle of information. The emphasis on data management began with the electronic age of data processing, but data management methods have roots in accounting, statistics, logistics planning, and other disciplines that predated the rise of corporate computing.
Data processing occurs when data is collected and translated into usable information. Data scientists are often involved, alone or in teams, and it is important that the processing is done correctly so as not to adversely affect the final product or the results obtained from the data.

Data administration or data resource management is an organizational function that works in the areas of information systems and computer science that plans, organizes, describes and controls data resources.


Arquitechture Lambda & Kappa: The main difference is the flow of data processing involved. Lambda has an architecture consisting of the batch layer, the speed layer, the serving layer, unlike kappa is composed of the speed layer and the serving layer.
#### Lambda
Their goal was to have a robust fault-tolerant system, both human and hardware, that was linearly scalable and that allowed low-latency writes and reads.

lambda architecture image: https://new.paradigmadigital.com/wp-content/uploads/2018/04/arquitecturas-big-data4.png

#### Kappa
In it he points out the possible “weak” points of Lambda Architecture and how to solve them through evolution. His proposal is to remove the batch layer leaving only the streaming layer.
This layer, unlike the batch type, has neither a beginning nor an end from a temporal point of view and is continually processing new data as they arrive.
As a batch process can be understood as a bounded stream, we could say that batch processing is a subset of streaming processing.

Kappa architecture image: https://new.paradigmadigital.com/wp-content/uploads/2018/04/arquitecturas-big-data5.png
