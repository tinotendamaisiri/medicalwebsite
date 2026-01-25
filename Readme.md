<h1 align="center">Medical Website Template</h1>

<h3 align="center">http://www.tinotendamaisiri.com/medicalwebsite.github.io/</h3>
<br/>
<img src="img/medical.gif" alt="video">

# MediCare Hub – Highly Available AWS Architecture ☁️

MediCare Hub is a lightweight medical web application re-architected on AWS to demonstrate **high availability, fault tolerance, and self-healing infrastructure**, aligned with the **Reliability Pillar of the AWS Well-Architected Framework**.

This project transforms a traditional single-instance deployment into a **production-style, multi-AZ AWS architecture** capable of recovering from instance failures and Availability Zone outages.

---

## 📌 Problem Statement

The original MediCare Hub application was hosted on a single EC2 instance with a single database, making it vulnerable to:

- EC2 instance crashes  
- Database downtime  
- Availability Zone failures  
- Manual recovery and extended downtime  

Any failure resulted in loss of access to critical medical data.

---

## 🎯 Solution Overview

The application was lifted and shifted to AWS and redesigned with **reliability-first principles**, using managed AWS services to achieve:

- High availability
- Automated recovery
- Horizontal scalability
- Minimal operational overhead

The resulting system is **self-healing**, **multi-AZ**, and **cost-aware**.

---

## 🏗️ Architecture Highlights
<img width="876" height="493" alt="medicare 2" src="https://github.com/user-attachments/assets/24aadfa1-144a-46fb-9d27-15377aaa0bf7" />

- **Auto Scaling EC2** instances deployed across multiple Availability Zones  
- **Application Load Balancer (ALB)** for traffic distribution and health checks  
- **Amazon RDS (Multi-AZ)** for resilient relational data storage  
- **Amazon Route 53** health checks and DNS failover  
- **Amazon EFS** for shared storage across EC2 instances  
- **Amazon CloudWatch** for monitoring and alarms  

This design ensures the application remains available even during infrastructure failures.

---

## 🛠 AWS Services Used

- Amazon EC2  
- Auto Scaling Group  
- Application Load Balancer (ALB)  
- Amazon RDS (Multi-AZ)  
- Amazon Route 53  
- Amazon EFS  
- Amazon CloudWatch  
- Amazon S3 (optional backup/failover support)

---

## 📂 Repository Structure


