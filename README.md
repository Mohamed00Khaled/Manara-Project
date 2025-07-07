# Scalable Web Application with ALB and Auto Scaling
Deploy a simple web application on AWS using EC2 instances, ensuring high availability and scalability with Elastic Load Balancing (ALB) and Auto Scaling Groups (ASG). The project demonstrates best practices for compute scalability, security, and cost optimization.

## 🏗️ Architecture: EC2-based Web App on AWS

![Architecture ](https://github.com/user-attachments/assets/8eac6a10-f872-4a85-9664-9e8e468b6281)


---

## 🔧 Key AWS Services Used

| Service | Description |
|--------|-------------|
| **Amazon EC2** | Hosts the web application in scalable instances |
| **Application Load Balancer (ALB)** | Distributes incoming HTTP/S traffic across multiple EC2 instances |
| **Auto Scaling Group (ASG)** | Automatically adjusts the number of EC2 instances based on load |
| **Amazon RDS** *(Optional)* | Provides a managed, scalable, and highly available relational database (MySQL/PostgreSQL) |
| **IAM** | Controls secure, role-based access for EC2 and other services |
| **CloudWatch** | Collects and monitors performance metrics and logs |
| **SNS (Simple Notification Service)** | Sends automated alerts based on CloudWatch alarms |

---

## 📝 Project Description

This project aims to:

- Deploy a **simple web application** hosted on EC2 instances.
- Use an **Application Load Balancer (ALB)** for distributing traffic across instances.
- Enable **Auto Scaling** to dynamically adjust compute resources based on traffic.
- Optionally, integrate an **Amazon RDS** instance for backend storage with Multi-AZ support.
- Set up **CloudWatch and SNS** for performance monitoring and alert notifications.
- Apply **IAM roles** for secure access management.

---

## 🎯 Learning Outcomes

By completing this project, you will learn how to:

- ✅ Set up a secure and scalable web application architecture using EC2.
- ✅ Configure and deploy an ALB to enable load distribution and fault tolerance.
- ✅ Create and manage an Auto Scaling Group for dynamic scalability.
- ✅ Monitor system performance and receive alerts using CloudWatch and SNS.
- ✅ Apply AWS best practices for **security**, **availability**, and **cost optimization**.

---

## 📌 Optional Enhancements

- Use **Amazon RDS** in Multi-AZ mode for high availability database integration.
- Add **S3** for static file storage.
- Use **CloudFront** to cache and deliver content globally.
- Implement **CI/CD** with CodePipeline and CodeDeploy for automated deployments.

---

## 📂 Repository Structure (suggested)
