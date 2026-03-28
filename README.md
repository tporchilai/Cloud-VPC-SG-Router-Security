# 🌐 AWS VPC Setup & Network Connectivity Project
A hands-on implementation of Amazon Virtual Private Cloud (VPC) demonstrating how to design and configure secure, scalable cloud networking using AWS.
## 🚀 Project Overview
This project focuses on building a custom VPC environment from scratch, including:

- Creating a VPC with CIDR block
- Configuring public subnets
- Enabling internet connectivity using an Internet Gateway
- Understanding networking fundamentals in AWS

##  🏗️ Architecture Diagram

<img width="989" height="811" alt="architecture" src="https://github.com/user-attachments/assets/7b0eee3e-78c6-4aac-8519-0148a20422c7" />

## ⚙️ Tech Stack
- **Cloud Platform:** AWS
- **Networking Service:** Amazon VPC
- **Tools Used:**
       - AWS Management Console
       - AWS CloudShell (CLI)

## 🔑 Key Concepts
 **🌐 What is Amazon VPC?**

Amazon VPC allows you to create a logically isolated network in the cloud where you can launch AWS resources securely.

**🧩 CIDR Block**
- Defines the IP address range for the VPC

- Example:

            10.0.0.0/16
  
**🏢 Subnets**
- Logical subdivisions within a VPC
- Types:
        -Public Subnet → Has internet access
        -Private Subnet → No direct internet access
  
**🌍 Internet Gateway (IGW)**
- Enables communication between:
- VPC ↔ Internet
- Required for public subnet connectivity
 
## 🔄 Public IP Assignment
- Automatically assigns public IPs to instances
- Required for internet-facing resources
  
## 🛠️ Implementation Steps

**1️⃣ Create VPC**
- Defined a custom VPC with CIDR block
- Established isolated network environment
  
**2️⃣ Configure Subnet**
- Created subnet inside the VPC
- Enabled auto-assign public IPv4 address
  
**3️⃣ Create Internet Gateway**
- Created IGW resource
- Attached it to the VPC
  
**4️⃣ Enable Internet Connectivity**
- Connected subnet to Internet Gateway
- Ensured public access capability
  
**5️⃣ (Optional) Use AWS CLI**
- Created resources using CloudShell
- Practiced infrastructure automation
  
**📊 Results**
- Successfully created a fully functional VPC
- Enabled internet connectivity for resources
- Understood real-world AWS networking concepts
