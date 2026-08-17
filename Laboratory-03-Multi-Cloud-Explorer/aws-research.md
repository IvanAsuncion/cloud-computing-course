# AWS Research Report: Amazon Web Services

## Brief Overview
Amazon Web Services (AWS) is a comprehensive and broadly adopted cloud platform provided by Amazon. Launched officially in March 2006, AWS provides on-demand cloud computing platforms and APIs to individuals, companies, and governments on a metered pay-as-you-go basis. AWS delivers over 200 fully featured services from data centers globally, offering compute power, database storage, content delivery, networking, and advanced capabilities like artificial intelligence and machine learning.

---

## Global Infrastructure
AWS provides a highly reliable, scalable, and resilient global cloud infrastructure consisting of physical locations around the world grouped into geographic areas.

* **AWS Regions:** An AWS Region is a physical geographic location where AWS clusters data centers. As of 2026, AWS operates 38+ geographic Regions globally across North America, South America, Europe, Asia Pacific, the Middle East, and Africa.
* **Availability Zones (AZs):** Every AWS Region consists of multiple (a minimum of 3) isolated, physically separate Availability Zones. Each AZ consists of one or more discrete data centers equipped with independent power, cooling, and physical security, linked via redundant, ultra-low-latency networking.
* **Edge Network (Points of Presence):** AWS operates a global network of hundreds of edge locations and regional edge caches across 90+ cities in 45+ countries. These edge locations power Amazon CloudFront (Content Delivery Network) and AWS Global Accelerator to deliver low-latency content delivery and data transfer.

---

## Cloud Management Console
The **AWS Management Console** is a web-based graphical interface used to access, manage, and monitor all AWS cloud resources. Key features include:

* **Service Navigation & Search:** Quick access to all 200+ AWS services through an integrated search bar and categorized drop-down menus.
* **Customizable Dashboard:** Widgets that show recent resources, cost overviews, application health, and quick launch shortcuts.
* **Resource Groups & Tagging:** Ability to organize and manage resources logically based on project, environment, or team tags.
* **Integrated CloudShell:** Browser-based command-line interface (CLI) directly accessible from the console for running AWS CLI scripts without local software installation.

![AWS Management Console Overview](screenshots/aws-homepage.png)
> *Note: Place your screenshot of the AWS Management Console or AWS official homepage in the `screenshots/aws-homepage.png` directory.*

---

## Four (4) Core Services

### 1. Amazon Elastic Compute Cloud (Amazon EC2)
* **Category:** Compute
* **Description:** Provides resizable, virtual compute capacity in the cloud. EC2 allows users to launch virtual machine instances (VMs) running Linux or Windows OS within minutes, offering complete control over server configurations, security settings, and scaling policies.

### 2. Amazon Simple Storage Service (Amazon S3)
* **Category:** Storage
* **Description:** An object storage service offering high scalability, data availability, security, and performance. Amazon S3 stores unstructured data (such as backup files, media files, logs, and static website files) as objects inside logical containers called buckets, providing 99.999999999% (11 9s) of data durability.

### 3. Amazon Relational Database Service (Amazon RDS)
* **Category:** Database
* **Description:** A managed relational database service that simplifies setting up, operating, and scaling relational databases in the cloud. It automates time-consuming administrative tasks such as hardware provisioning, database setup, patching, and backups for engines like PostgreSQL, MySQL, MariaDB, Oracle, and SQL Server.

### 4. Amazon Virtual Private Cloud (Amazon VPC)
* **Category:** Networking
* **Description:** Logically isolated virtual network sections within the AWS Cloud where users launch AWS resources. VPC provides control over virtual networking environments, including selection of IP address ranges, creation of subnets, route tables, network gateways, and security groups.

---

## Three (3) Advantages

1. **Market Leadership & Broadest Ecosystem:** As the pioneer of modern public cloud infrastructure, AWS offers the largest ecosystem of tools, integrations, third-party software marketplace applications, and trained professionals worldwide.
2. **High Security & Compliance:** Architected to be one of the most flexible and secure cloud computing environments available, offering extensive compliance certifications (including HIPAA, PCI-DSS, SOC 1/2/3, ISO 27001) and granular identity controls via AWS Identity and Access Management (IAM).
3. **PaaS & Serverless Innovation:** AWS offers extensive serverless and managed infrastructure capabilities (such as AWS Lambda, Amazon ECS/EKS, and Amazon DynamoDB) allowing organizations to build and scale applications without managing server instances.

---

## Typical Enterprise Use Cases

* **Migrating Legacy Infrastructure & Enterprise Workloads:** Moving traditional enterprise applications, databases, and enterprise resource planning (ERP) suites from on-premises data centers to AWS to reduce capital expenditure (CapEx) and operational costs.
* **Global Web & Mobile Application Backends:** Running scalable, highly available web applications, API backends, and microservice architectures leveraging EC2, Auto Scaling, Elastic Load Balancing, and CloudFront.
* **Big Data Analytics & Data Warehousing:** Collecting, storing, and analyzing petabyte-scale data lakes using Amazon S3, Amazon Redshift, Amazon EMR, and AWS Glue for business intelligence and advanced machine learning workloads.
