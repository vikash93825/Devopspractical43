# 🚀 AWS Cloud Practice Project

## 📌 Overview
This project demonstrates hands-on experience with core AWS services by building a secure and scalable cloud architecture.

It includes networking, compute, storage, and database setup using AWS best practices.

---

## 🛠️ Services Used

- AWS IAM (Identity and Access Management)
- Amazon VPC (Virtual Private Cloud)
- Amazon EC2 (Elastic Compute Cloud)
- Amazon S3 (Simple Storage Service)
- Amazon RDS (Relational Database Service)

---

## 🏗️ Architecture

- Custom VPC with:
  - Public Subnet (for EC2)
  - Private Subnet (for RDS)
- Internet Gateway for public access
- Security Groups and NACLs for security
- EC2 connected to RDS database
- S3 used for storage

---

## ⚙️ Features

- Secure IAM user and role management
- Public & Private subnet architecture
- EC2 instance hosting Node.js application
- RDS MySQL database integration
- S3 bucket for storage
- Network security using Security Groups & NACL

---

## 🔄 Workflow

1. Created IAM users and roles
2. Set up VPC with subnets
3. Launched EC2 instance in public subnet
4. Created RDS in private subnet
5. Connected EC2 to RDS using endpoint
6. Deployed Node.js application
7. Stored assets in S3
