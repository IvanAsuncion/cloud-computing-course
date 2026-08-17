# Client Cloud Recommendations & Multi-Cloud Decision Matrix

## Checkpoint 4 – Cloud Platform Recommendation Scenarios

### Client A – Startup Company
* **Scenario:** A startup company launching a new mobile application with a limited budget and rapid growth expectations over the next few years.
* **Recommended Platform:** **Amazon Web Services (AWS)**
* **Justification:** AWS is ideal for startups because of its pay-as-you-go pricing model, generous AWS Activate startup credits, and extensive serverless ecosystem that minimizes initial operational overhead. As the application grows, AWS's auto-scaling infrastructure will allow the app to seamlessly scale from hundreds to millions of users without re-architecting the system.
* **Recommended Services:**
  1. **AWS Amplify / Amazon API Gateway:** For rapid front-end and back-end mobile API development.
  2. **Amazon DynamoDB:** A fully managed NoSQL database for flexible, low-latency mobile application data storage.
  3. **AWS Lambda:** Serverless computing to run backend code in response to API requests without paying for idle server time.

---

### Client B – University
* **Scenario:** A university already utilizing Windows Server, Microsoft 365, and Active Directory looking to migrate services to the cloud.
* **Recommended Platform:** **Microsoft Azure**
* **Justification:** Microsoft Azure is the most natural and cost-effective choice for an organization already deeply integrated into the Microsoft software ecosystem. The university can utilize Azure Hybrid Benefit to reuse existing Windows Server licenses, dramatically reducing cloud migration expenses. Furthermore, native integration between Azure Active Directory (Microsoft Entra ID) and local Active Directory ensures seamless single sign-on (SSO) and identity governance across all systems.
* **Recommended Services:**
  1. **Microsoft Entra ID (Azure AD):** For identity management and seamless integration with existing on-premises Active Directory.
  2. **Azure Virtual Machines:** To migrate and run legacy Windows Server workloads smoothly in the cloud.
  3. **Azure SQL Database:** For hosting university administrative databases with automated maintenance and high security.

---

### Client C – AI Research Company
* **Scenario:** A research company developing Artificial Intelligence and Machine Learning applications requiring high-performance computing.
* **Recommended Platform:** **Google Cloud Platform (GCP)**
* **Justification:** Google Cloud Platform is the industry leader in data engineering, advanced analytics, and artificial intelligence infrastructure. GCP offers specialized hardware like Tensor Processing Units (TPUs) alongside high-performance GPUs designed specifically to accelerate AI/ML model training and execution. Their unified AI ecosystem, Vertex AI, allows researchers to build, tune, and deploy machine learning pipelines at speed and scale.
* **Recommended Services:**
  1. **Vertex AI:** A fully managed end-to-end platform for building, deploying, and scaling machine learning models.
  2. **Compute Engine with GPUs/TPUs:** High-performance compute instances optimized for deep learning workloads.
  3. **BigQuery:** Serverless, highly scalable data warehousing for processing and analyzing massive datasets required for AI model training.

---

### Client D – Global E-Commerce Company
* **Scenario:** A multinational online shopping company serving global customers requiring highly available infrastructure with automatic scaling.
* **Recommended Platform:** **Amazon Web Services (AWS)**
* **Justification:** AWS possesses the largest, most mature global cloud infrastructure, making it uniquely qualified to handle traffic spikes during major shopping events. With its expansive network of global Availability Zones and Edge Locations, an e-commerce giant can deliver ultra-low latency experiences anywhere in the world. Furthermore, AWS was born out of Amazon's own e-commerce engine, providing proven reliability and high availability for global transactional platforms.
* **Recommended Services:**
  1. **Amazon EC2 Auto Scaling & Elastic Load Balancing (ELB):** To automatically handle unpredictable web traffic surges and distribute incoming traffic.
  2. **Amazon CloudFront:** A global Content Delivery Network (CDN) to serve static product media and web assets at lightning speeds.
  3. **Amazon Aurora / Amazon DynamoDB:** High-performance relational and NoSQL databases capable of handling thousands of concurrent user transactions per second.

---

## Checkpoint 6 – Multi-Cloud Decision Matrix

| Business Requirement | Recommended Platform | Justification |
| :--- | :--- | :--- |
| **Startup Company** | **AWS** | Low initial cost via serverless services, generous startup credit programs, and seamless long-term scalability. |
| **Enterprise Organization** | **AWS / Azure** | Enterprise-grade governance, massive global reach, deep compliance coverage, and robust multi-account management. |
| **Microsoft Environment** | **Microsoft Azure** | Direct identity synchronization with Active Directory and cost savings via Azure Hybrid Benefit for Windows Server/SQL licenses. |
| **AI / Machine Learning** | **GCP** | Specialized TPU hardware, advanced machine learning tooling via Vertex AI, and high-performance data analytics. |
| **Kubernetes Deployment** | **GCP** | Native Kubernetes support via Google Kubernetes Engine (GKE), providing the most advanced managed Kubernetes environment. |
| **Global Web Application** | **AWS** | Largest footprint of global Regions, Availability Zones, and CloudFront edge locations for low-latency worldwide delivery. |
