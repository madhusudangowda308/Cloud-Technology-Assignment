**Cloud Technology for Business (B9MG119)**

This repo contains the Cloud Strategy and Sample Deployment of an organization called BOOKSHOW

Repo Link: https://github.com/Praveenbose/Cloud-Technology-Assignment




1. Primary Objective

The primary objective of this project is to develop a comprehensive cloud strategy for BookShow, which is one of the leading online ticketing platforms. BookShow currently manages its IT infrastructure, including hardware, software, and on-site. Our strategy aims to transition from the current on-premises model to a cloud-based solution to enhance operational efficiency and overall business performance. To help drive this transformation, we will outline a detailed cloud strategy and a sample deployment plan.

2. Background of the Enterprise
BookShow is a prominent entertainment company known for its leading Online Ticketing Platform, catering to various events including movies, plays, concerts, and sporting events. In addition to ticketing, BookShow offers an online media streaming service and comprehensive management solutions for both virtual and on-ground entertainment experiences, covering all genres. The core operation of BookShow revolves around its online platform, which facilitates the booking of tickets for various entertainment events, with a primary focus on movies. 

2.1 Size of the Business

BookShow is a medium-sized enterprise with a total of approximately 33 employees. The workforce is structured as follows:

IT Management:
  - 2 IT Managers

Network and Systems Administration:
  - 2 Network Administrators
  - 4 Systems Administrators

Development Team:
  - 4 Backend Developers
  - 4 Frontend Developers

IT Support and Maintenance:
  - 3 IT Support Specialists
  - 4 Help Desk Technicians

Cloud and Database Management:
  - 1 Cloud Engineer
  - 2 Cloud Solutions Architects
  - 2 Database Administrators

Project and Security Management:
  - 1 Scrum Master
  - 3 Security Specialists
  - 1 IT Project Manager

3. Current IT setup 

Let's delve into the detailed IT infrastructure of BookShow, covering aspects of hardware, software, and on-site management.

3.1 Hardware
 
On-premises Servers:

BookShow’s IT infrastructure includes several key components. The web servers host the website and application, handling user inquiries, ticket bookings, and providing web content, typically using software like Apache and Nginx (Nginx, n.d.; Apache HTTP Server Project, n.d.). The database servers are dedicated to storing and managing transactional data, customer information, and event details, utilizing relational database management systems like SQL Server or PostgreSQL (Microsoft SQL Server, n.d.; PostgreSQL, n.d.). Media servers are employed for streaming media content and storing large media files. Backup servers ensure critical data backup and data availability during power outages. In addition to other features, hardware load balancers are utilized to ensure that web traffic is evenly distributed to web servers, resulting in high availability and reliability.

3.2 Software

Operating Systems:

The operating systems primarily used are Linux servers, such as Ubuntu and CentOS, chosen for their reliability and security, and deployed across web, database, and media servers. BookShow utilizes several key applications and services to ensure smooth operations. A custom ticketing platform is specialized software that manages ticket bookings, user profiles, financial transactions, and event organization. CRM (Customer Relationship Management) will manage interactions with customers, sales, and support (ProInfluent, n.d.). Content management system 'CMS', manages website content management, promotions, and advertising (Kinsta, n.d.). Integration of APIs and services with multiple payment gateways to support online transactions. Additionally, Server health and performance are monitored using monitoring tools like Nagios and Zabbix. (Nagios, n.d.; Zabbix, n.d.).

3.3 Internet Connectivity and Network Hardware

BookShow ensures robust internet connectivity with high-bandwidth connections to handle large volumes of user traffic. Additionally, switches and routers are employed to maintain seamless internal and external network connectivity.

3.4 Security Components

BookShow implements a range of security measures to secure its infrastructure. A hardware firewall is implemented to safeguard the system from external cyber threats, while a software firewall is employed to defend the network from unauthorized access. Network traffic is monitored by an intrusion detection system “IDS” and an “intrusion prevention system” IPS to detect suspicious activity and prevent potential attacks (Okta, n.d.). Additionally, measures are taken to mitigate the impact of Distributed Denial of Service (DDoS) attacks to ensure continuous service availability.

3.5 Power and Cooling

BookShow uses an UPS as a backup power, to ensure the server remains functional during a power outage. Additionally, a cooling system is applied to maintain optimal operating temperatures for servers and network devices. 

4. On-Site Management and Maintenance

4.1 IT Staff and Support Team

BookShow's IT department comprises specialized roles responsible for maintaining and supporting critical infrastructure and services. System Administrators oversee servers, storage systems, and network equipment, ensuring their smooth operation and reliability. Database administrators manage database servers, focusing on data integrity and performance optimization. Network administrators are responsible for managing network connections as well as implementing security measures to protect the network infrastructure. Also, dedicated support staff provide technical support to end-users, ensuring efficient use of IT resources throughout the organization.

4.2 Monitoring

BookShow employs both manual monitoring by IT staff and automated monitoring tools such as Nagios and Zabbix to ensure optimal server and network performance(Nagios, n.d.; Zabbix, n.d.). IT staff conduct regular checks to monitor system health and address any issues promptly. 

4.3 Maintenance

BookShow prioritizes regular updates and patching of software and firmware to maintain security and optimize performance. Additionally, they conduct routine hardware maintenance, including checks and replacements for aging components, ensuring that their infrastructure remains reliable and efficient. These practices contribute to the overall stability and security of BookShow's IT environment.

5. Current IT Challenges
Using the IT infrastructure as a guide, let's sum up the company's challenges:

5.1 High Capital Expenditures (CapEx)

BookShow faces significant capital expenditures primarily due to several factors. These include the continuous costs of purchasing and maintaining the physical servers and network equipment. Also, there are significant initial expenses related to acquiring hardware and software licenses. Moreover, the regular replacement and upgrading of these assets add to the company's overall capital expenditure. Investing in these is crucial to maintain and improve BookShow's IT infrastructure.

5.2 Operational Expenses (OpEx) 

BookShow incurs operational expenses related to various aspects of its IT infrastructure. This includes costs associated with power, cooling systems, and physical space required to house servers and networking equipment. Additionally, operational expenses cover the ongoing maintenance and management of hardware components. Furthermore, BookShow allocates resources for IT staff responsible for the day-to-day management and maintenance of servers, ensuring smooth operation and reliability of its IT environment. These operational expenditures are crucial for supporting the continuous functionality and efficiency of BookShow's technology infrastructure.

5.3 Scalability Problems 

BookShow encounters scalability challenges manifested in two primary issues. Firstly, the company struggles to swiftly add resources to manage surges in demand for significant events or releases. This limitation hinders their ability to efficiently accommodate peak traffic periods. Secondly, in anticipation of peak loads, BookShow tends to over-provision resources, resulting in unnecessary resource allocation and wastage during off-peak periods. These scalability issues highlight the need for a more flexible and efficient resource management approach to better meet fluctuating demand while optimizing resource utilization.

5.4 Frequent Downtime
The current on-premises servers often fail, particularly during peak hours or when there's a surge in demand for popular events. The company is frequently experiencing downtime because its servers cannot handle high traffic volumes. This persistent issue negatively impacts customer satisfaction, causing users to encounter payment interruptions and poor loading times when accessing the website. Consequently, the platform's reliability and overall user experience suffer, potentially leading to customer loss and a decline in trust and reputation.

5.5 Security Threats

Businesses encounter a major difficulty in keeping security patches and updates up to date because of the expensive allocation of resources. Consequently, the system becomes open to unauthorized access and various cyber threats, leading to potential data breaches and security risks.

5.6 Disaster recovery and redundancy

Setting up and maintaining backup and recovery solutions pose challenges for BookShow in terms of complexity and cost. Ensuring data redundancy and availability is crucial but requires significant effort and investment to achieve effectively. These tasks are essential for safeguarding data integrity and ensuring uninterrupted service delivery for BookShow's operations.

5.7 Performance and Monitoring

Server outages or poor performance may go unnoticed for extended periods of time if the monitoring system fails to provide proactive notifications or real-time insights. This could lead to customer annoyance and lost revenue due to the inability to purchase tickets. A non-scalable monitoring system may be overwhelmed by a sudden increase in traffic during well-attended events, resulting in platform slowness or crashes, unpleasant user experiences, and lost revenue as potential buyers abandon their purchases.

6. Impact on Business and Revenue Loss

Revenue from ticket sales decreases when there are problems with downtime and performance, particularly during busy times. The company deals with higher expenses because of large capital and operational costs, which affects its financial situation and profit. Customers lose trust and loyalty when there is regular downtime and an unsatisfactory user experience on the platform. The company's ineffective IT infrastructure puts it at a disadvantage compared to its competitors.
To address these challenges and enhance operational efficiency, we will adopt a strategic approach using cloud services, specifically AWS (Amazon Web Services) technology. This initiative aims to effectively resolve our existing issues and drive significant improvements.
Let's take a brief look at what is cloud computing and its benefits, including AWS, and discuss the specific AWS services we intend to implement in this project.

7. Cloud Computing

Cloud computing involves providing computing services such as servers, storage, databases, networking, software, analytics, and intelligence via the Internet ("the cloud") in order to allow for quicker innovation, adaptable resources, and cost-effectiveness. You usually only pay for the cloud services that you utilize, which can reduce your operational expenses, enhance the efficiency of your infrastructure, and adapt as your business requirements evolve (Microsoft Azure, n.d.).

7.1 Benefits of Cloud Computing

1. Cost Efficiency: Cuts expenses on hardware, software, and data centers; reduces power and cooling costs; minimizes IT management requirements.

2. Speed: Facilitates fast, on-demand resource allocation; enhances business agility and capacity planning.

3. Worldwide Reach: Allows for flexible scaling of resources from ideal geographic locations as required .

4. Efficiency: Reduces time spent on hardware setup and maintenance, enabling IT teams to focus on primary business objectives.

5. Performance: Functions on a secure global network of updated data centers, minimizing latency and benefiting from economies of scale.

6. Dependability: Simplifies data backup, disaster recovery, and business continuity through multiple redundant sites.

7. Safety: Reinforces overall security posture with comprehensive policies, technologies, and controls.

7.2 Amazon Web Services:

Amazon Web Services (AWS) offers IT infrastructure services to businesses as web services now commonly known as cloud computing. Amazon Web Services provides a wide range of cloud-based products worldwide. These include various services such as computing, storage, databases, analytics, networking, mobile, developer tools, management tools, IoT, security, and enterprise applications. Users can access these services on demand, in seconds, and with pay-as-you-go pricing. AWS offers over 200 services, covering areas such as data warehousing, deployment tools, directories, and content delivery. Presently, AWS supports a dependable, scalable, and cost-effective cloud infrastructure platform that serves numerous businesses across 190 countries (Amazon Web Services, 2023).

7.2.1 What is AWS EC2?

Amazon Elastic Compute Cloud (Amazon EC2) is a service provided by Amazon Web Services (AWS) that offers flexible and scalable computing capacity. It helps in minimizing hardware expenses and enables quick development and deployment of applications. Amazon EC2 allows users to launch and manage virtual servers according to their requirements, and adjust capacity to handle varying workloads. Moreover, an EC2 instance refers to a virtual server in the AWS Cloud, with specific hardware configurations based on the chosen instance type (Amazon Web Services, 2023).

![image](https://github.com/Praveenbose/Cloud-Technology-Assignment/assets/169264693/9b36f17c-48a1-42d7-b440-e84608694ae8)
Fig 1: AWS EC2        

7.2.2 What is AWS CloudWatch?

Amazon CloudWatch provides real-time monitoring for your Amazon Web Services (AWS) resources and applications. You can track and collect metrics, which are measurable variables, and create custom dashboards to display them. Additionally, you can set up alarms and receive notifications or automate actions when certain thresholds are reached. This helps you gain insight into resource utilization, application performance, and operational health (Amazon Web Services, 2024).   

![image](https://github.com/Praveenbose/Cloud-Technology-Assignment/assets/169264693/a469ce8a-68e7-494e-9095-7d5908a16750)
                                                                 Fig 2: AWS CloudWatch

                                                                 


                                                                 









