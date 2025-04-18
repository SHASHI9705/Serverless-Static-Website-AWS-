# 🏗️ Static Serverless Website Deployment on AWS - Architecture & Flow

This repository showcases the **architecture diagram** and **deployment steps** for hosting a **static website** using **serverless AWS services** like **S3, CloudFront, Route 53, and ACM**.

---

## 🌐 Overview

Deploying a static serverless website on AWS enables:
- 🚀 Fast and scalable delivery
- 💰 Low-cost, pay-as-you-go hosting
- 🔐 High availability and security with HTTPS
- 🛡️ Built-in protection using AWS tools

This repo is ideal for use cases like:
- Static websites (portfolios, landing pages)
- AI-powered apps (like skincare analysis tools)
- Serverless web apps with light frontend logic

---

## 🧩 Architecture Diagram In repo.


**Main AWS Services Used:**
1. **Amazon S3** – Hosts the static site (HTML, CSS, JS, images)
2. **CloudFront** – CDN that serves the site globally with low latency
3. **Amazon Route 53** – Domain registration & DNS routing
4. **AWS Certificate Manager (ACM)** – Provides HTTPS via SSL/TLS

---

## 🚀 Deployment Flow (Step-by-Step)

### ✅ Step 1: Prepare Your Static Website

### ✅ Step 2: Upload to S3

### ✅ Step 3: Secure with HTTPS (ACM)

### ✅ Step 4: Set Up CloudFront

### ✅ Step 5: Configure Route 53


---

## 🔐 Optional Enhancements

| Feature        | Tool/Service           | Purpose                            |
|----------------|------------------------|------------------------------------|
| User Auth      | AWS Cognito            | Sign-in / sign-up functionality    |
| Backend Logic  | AWS Lambda + API Gateway | Lightweight serverless APIs       |
| Serverless DB  | DynamoDB or MongoDB Atlas | Store user inputs or AI results |
| Security       | AWS WAF + OAI + IAM    | Extra protection for content       |

---



> 💡 Built with ❤️ to simplify cloud hosting for developers and students.

