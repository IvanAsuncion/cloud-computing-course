# Azure Research Report: Microsoft Azure

## Brief Overview
Microsoft Azure is a premier public cloud computing platform developed and operated by Microsoft. Initially launched in February 2010 as Windows Azure and later rebranded to Microsoft Azure in 2014, the platform provides hundreds of integrated cloud services—including compute, storage, networking, analytics, and artificial intelligence. Azure allows organizations to build, deploy, manage, and scale applications across a global network of datacenters using both open-source technologies and proprietary Microsoft tools.

---

## Global Infrastructure
Microsoft Azure features one of the largest global datacenter footprints among public cloud providers, engineered to deliver high availability, disaster recovery, and low latency worldwide.

* **Azure Regions:** An Azure region is a geographical area containing one or more datacenters connected through a dedicated regional low-latency network. Azure has over 60 announced regions globally spanning more than 140 countries.
* **Availability Zones:** Availability zones are physically separate locations within an Azure region. Each zone comprises one or more datacenters equipped with independent power, cooling, and networking. Most major Azure regions feature a minimum of three availability zones to ensure fault tolerance and high availability.
* **Azure Edge Zones & Network:** Microsoft maintains a global network spanning hundreds of thousands of miles of fiber-optic cables and hundreds of Edge Points of Presence (PoPs), enabling high-speed routing via ExpressRoute and Azure Content Delivery Network (CDN).

---

## Cloud Management Console
The **Azure Portal** is a web-based, unified management console that provides an alternative to command-line tools for creating, configuring, and managing all Azure resources. Key features include:

* **Unified Dashboard:** Customizable grid layouts displaying real-time metrics, resource maps, cloud health statuses, and billing updates.
* **Resource Groups:** A fundamental management container used to group related Azure resources (e.g., VMs, databases, virtual networks) for collective deployment, monitoring, and access control.
* **Azure Cloud Shell:** An interactive, browser-accessible shell that allows administrators to execute Azure CLI or Azure PowerShell commands directly from the browser.
* **Integrated Cost Management:** Native visibility into enterprise cloud spending, budget alerts, and cost optimization recommendations via Azure Advisor.

![Azure Portal Overview]([screenshots/azure-homepage.png](https://github.com/IvanAsuncion/cloud-computing-course/blob/main/Laboratory-03-Multi-Cloud-Explorer/screenshots/azure-homepage.PNG)

---

## Four (4) Core Services

### 1. Azure Virtual Machines (Azure VMs)
* **Category:** Compute
* **Description:** An Infrastructure-as-a-Service (IaaS) offering that provides on-demand, scalable compute resources. Azure VMs support both Linux and Windows Server operating systems, enabling users to customize memory, vCPUs, GPUs, and persistent storage attached to each virtual instance.

### 2. Azure Blob Storage
* **Category:** Storage
* **Description:** A massively scalable object storage solution designed for unstructured data such as text, binary data, media files, and system backups. Blob Storage serves data directly to browsers, streams video/audio, and provides tiered storage levels (Hot, Cool, Cold, and Archive) to optimize storage costs.

### 3. Azure SQL Database
* **Category:** Database
* **Description:** A fully managed Relational Database-as-a-Service (PaaS) built on the Microsoft SQL Server engine. It handles core database management functions—such as upgrading, patching, backups, and performance monitoring—without user involvement, boasting built-in high availability and AI-driven performance tuning.

### 4. Azure Virtual Network (VNet)
* **Category:** Networking
* **Description:** The fundamental building block for private networks in Azure. VNets enable many types of Azure resources (such as Azure VMs) to securely communicate with each other, the internet, and on-premises networks via private IP addresses, VPN gateways, or dedicated ExpressRoute connections.

---

## Three (3) Advantages

1. **Seamless Microsoft Ecosystem Integration:** Native, frictionless interoperability with enterprise tools such as Active Directory (Microsoft Entra ID), Windows Server, Microsoft 365, Visual Studio, and SQL Server.
2. **Hybrid Cloud Leadership (Azure Arc):** Industry-leading support for hybrid and multi-cloud environments through Azure Arc and Azure Stack, allowing companies to run Azure services and manage resources across on-premises data centers and edge locations.
3. **Enterprise Compliance & Security:** Offers extensive security tooling (Microsoft Defender for Cloud, Microsoft Sentinel) and holds the largest compliance portfolio in the cloud industry across global, regional, and industry-specific standards.

---

## Typical Enterprise Use Cases

* **Enterprise Hybrid Cloud Deployments:** Integrating existing on-premises Windows Active Directory environments and legacy Windows Server workloads directly with Azure cloud infrastructure.
* **Enterprise Application & Web Hosting:** Deploying web applications, microservices, and enterprise resource planning (ERP) suites utilizing Azure App Service, Azure Kubernetes Service (AKS), and Azure SQL Database.
* **Enterprise AI & Machine Learning:** Leveraging Azure OpenAI Service and Azure Machine Learning to build, fine-tune, and deploy generative AI applications and predictive analytics models safely within enterprise boundaries.
