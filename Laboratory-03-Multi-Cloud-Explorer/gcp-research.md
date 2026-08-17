# GCP Research Report: Google Cloud Platform

## Brief Overview
Google Cloud Platform (GCP) is a suit of public cloud computing services offered by Google. First launched in April 2008 with the announcement of Google App Engine, GCP provides modular cloud services including compute, data storage, data analytics, networking, and machine learning. GCP runs on the same ultra-scalable global infrastructure that Google uses internally for its end-user products like Google Search, YouTube, and Gmail.

---

## Global Infrastructure
Google Cloud’s global infrastructure is engineered to deliver high performance, minimal latency, and high availability worldwide.

* **GCP Regions:** A GCP region is a specific geographic location where users can deploy cloud resources. As of 2026, Google Cloud operates 43 global regions across North America, South America, Europe, Asia-Pacific, the Middle East, and Africa.
* **Zones:** Each GCP region contains multiple isolated deployment locations known as zones (typically 3 per region). Google Cloud features 130 zones worldwide, each equipped with independent power, cooling, and networking infrastructure to guard against local outages.
* **Global Network & Edge Locations:** GCP connects its data centers via a massive private, software-defined fiber-optic network spanning over 200 edge locations (Points of Presence) across the globe. This private network reduces public internet exposure and optimizes performance for latency-sensitive applications.

---

## Cloud Management Console
The **Google Cloud Console** is an intuitive, web-based graphical interface used to manage, configure, and monitor all Google Cloud resources and project lifecycle workflows. Key features include:

* **Project-Based Hierarchy:** Resources are organized logically into Projects, Organizations, and Folders, enabling clean billing isolation, access control, and quota management.
* **Google Cloud Shell:** A free, browser-accessible command-line environment pre-configured with the Google Cloud CLI (`gcloud`) and developer utilities.
* **Resource Monitoring & Logs:** Built-in observability with Google Cloud Observability (formerly Stackdriver) for monitoring system metrics, traces, and centralized logs.
* **Smart Search & Navigation:** Universal search bar for rapidly locating services, virtual machine instances, APIs, and billing dashboards.

![GCP Console Overview](https://github.com/IvanAsuncion/cloud-computing-course/blob/main/Laboratory-03-Multi-Cloud-Explorer/screenshots/gcp-homepage.PNG)

---

## Four (4) Core Services

### 1. Compute Engine
* **Category:** Compute
* **Description:** An Infrastructure-as-a-Service (IaaS) offering that provides customizable virtual machines (VMs) running on Google’s infrastructure. It supports predefined or custom machine configurations (CPUs, GPUs, and Memory) and features fast boot times and sustained-use discounts.

### 2. Cloud Storage
* **Category:** Storage
* **Description:** A unified, highly durable RESTful object storage service designed for storing unstructured data. It offers multiple storage classes (Standard, Nearline, Coldline, Archive) based on access frequency, with global availability and automatic data encryption at rest.

### 3. BigQuery
* **Category:** Data Analytics / Database
* **Description:** A serverless, highly scalable, and cost-effective multi-cloud data warehouse designed for enterprise business agility. BigQuery allows organizations to run super-fast SQL queries across petabytes of data using Google's processing infrastructure without managing database servers.

### 4. Cloud Pub/Sub
* **Category:** Networking / Integration
* **Description:** An asynchronous, horizontally scalable messaging service that decouples stream-producing services from stream-processing services. It provides reliable, low-latency, many-to-many messaging for real-time event distribution and streaming analytics pipelines.

---

## Three (3) Advantages

1. **Industry Leadership in Data, AI, and BigQuery:** Unmatched capabilities in real-time analytics, machine learning, and artificial intelligence models (such as Gemini models and Vertex AI platform).
2. **Superior Container Infrastructure & Kubernetes Native Support:** As the original creator of Kubernetes, Google offers Google Kubernetes Engine (GKE), widely recognized as the most advanced, managed Kubernetes platform in the cloud industry.
3. **High-Performance Global Network & Cost Efficiency:** Uses Google's private global fiber network for fast data transit, coupled with customer-friendly pricing mechanisms like per-second billing, sustained-use discounts, and custom VM machine sizes.

---

## Typical Enterprise Use Cases

* **Big Data Analytics & Data Warehousing:** Aggregating data streams from various operational applications into BigQuery and Dataflow to perform real-time business intelligence and data visualization.
* **Artificial Intelligence & Machine Learning Workloads:** Training, tuning, and deploying advanced AI/ML algorithms and generative AI agents using Vertex AI, GPUs, and custom Tensor Processing Units (TPUs).
* **Modern Cloud-Native Container Orchestration:** Deploying, running, and managing microservice-based web applications at scale using Google Kubernetes Engine (GKE) and serverless Cloud Run.
