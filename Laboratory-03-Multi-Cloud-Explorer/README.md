## Linux Server Investigation

### Operating System

The Linux server is running **Ubuntu 24.04.4 LTS (Noble Numbat)** with an x86_64 architecture.

### CPU Information

The server has **1 virtual CPU (vCPU)** using an **Intel Xeon E312xx (Sandy Bridge, IBRS update)** processor. The environment is running under **KVM virtualization**.

### Memory

The server has **2.2 GiB of total memory**. At the time of the investigation, approximately 1.2 GiB was being used and about 968 MiB was available.

### Disk Space

The root filesystem has **19 GiB of total storage**, with approximately **11 GiB used** and **7.5 GiB available**, resulting in about **60% disk usage**.

### Cloud Hosting Options

This Linux server configuration could be hosted using virtual machine services from all three major cloud providers:

| Cloud Provider | Suitable Service | Reason |
|---|---|---|
| **AWS** | Amazon EC2 | EC2 provides configurable Linux virtual machines with adjustable CPU, memory, and storage resources. |
| **Microsoft Azure** | Azure Virtual Machines | Azure Virtual Machines can run Linux distributions such as Ubuntu and provide configurable virtual machine resources. |
| **Google Cloud Platform** | Compute Engine | Compute Engine provides scalable virtual machines that can run Ubuntu Linux with configurable CPU, memory, and storage. |

The investigation demonstrates that the same type of Linux server can be deployed across AWS, Azure, or Google Cloud by using their respective virtual machine services.
