# Laboratory 03: Multi-Cloud Explorer

## Overview
This laboratory activity explores the core services, infrastructure, and strategic enterprise use cases of the world's leading public cloud providers: **Amazon Web Services (AWS)**, **Microsoft Azure**, and **Google Cloud Platform (GCP)**[cite: 1]. By acting as a Cloud Solutions Consultant, this research evaluates cloud features, compares platform capabilities, maps equivalent services, and delivers scenario-based cloud recommendations[cite: 1].

---

## Repository Structure

```text
Laboratory-03-Multi-Cloud-Explorer/
├── README.md
├── aws-research.md
├── azure-research.md
├── gcp-research.md
├── cloud-platform-comparison.md
├── client-recommendations.md
├── reflection.md
└── screenshots/
    ├── aws-homepage.png
    ├── azure-homepage.png
    ├── gcp-homepage.png
    ├── killercoda-terminal.png
    └── github-repository.png
```[cite: 1]

---

## Linux Environment & Cloud Host Mapping

As part of investigating infrastructure migration, a Linux environment was launched on the KillerCoda Playground to analyze system specifications and determine how on-premises Linux servers map to equivalent cloud resources[cite: 1].

### System Investigation Commands & Output

| System Metric | Linux Command Used | Sample Output / Findings |
| :--- | :--- | :--- |
| **Operating System** | `cat /etc/os-release` or `lsb_release -a` | Ubuntu 22.04.3 LTS (Jammy Jellyfish) |
| **CPU Information** | `lscpu` or `cat /proc/cpuinfo` | x86_64 Architecture, 2 vCPUs (Intel Xeon / AMD EPYC) |
| **Memory (RAM)** | `free -h` | Total: ~4.0 GiB, Used: ~450 MiB, Free: ~3.5 GiB |
| **Disk Space** | `df -h /` | Total: ~30 GB, Used: ~4.2 GB, Available: ~25.8 GB |

![KillerCoda Terminal Output](screenshots/killercoda-terminal.png)
> *Note: Place your terminal output screenshot in `screenshots/killercoda-terminal.png`.*[cite: 1]

---

### Cloud Hosting Recommendations for Migration

If this Linux server environment were to be migrated to the public cloud, it could be hosted using the following compute and storage infrastructure:

* **Amazon Web Services (AWS):**
  * **Compute:** Amazon EC2 (`t3.medium` or `t4g.medium` instance type with 2 vCPUs and 4 GiB RAM)[cite: 1].
  * **Storage:** Amazon EBS (Elastic Block Store) General Purpose SSD (`gp3`, 30 GB volume)[cite: 1].
  * **OS Image:** Ubuntu 22.04 LTS AMI (Amazon Machine Image)[cite: 1].

* **Microsoft Azure:**
  * **Compute:** Azure Virtual Machines (`Standard_B2s` or `Standard_D2s_v5` with 2 vCPUs and 4 GiB RAM)[cite: 1].
  * **Storage:** Azure Managed Disks (Standard SSD or Premium SSD, 32 GB volume)[cite: 1].
  * **OS Image:** Ubuntu Server 22.04 LTS Marketplace Image[cite: 1].

* **Google Cloud Platform (GCP):**
  * **Compute:** Compute Engine (`e2-medium` or `n2-standard-2` with 2 vCPUs and 4 GiB RAM)[cite: 1].
  * **Storage:** Compute Engine Persistent Disk (Balanced Persistent Disk, 30 GB)[cite: 1].
  * **OS Image:** Ubuntu 22.04 LTS Public Disk Image[cite: 1].
