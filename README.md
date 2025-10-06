# 🌩️ DevOps & Cloud Project – Static Website Hosting

This project demonstrates how to **host a static website on AWS** using multiple cloud and DevOps services such as **S3**, **CloudFront**, **ACM (SSL Certificate Manager)**, **CodePipeline**, and **GitHub** for continuous integration and delivery.

---

## 🚀 Project Overview

- 🌐 **Website Type:** Static (HTML, CSS, JS)
- ☁️ **Cloud Provider:** AWS
- 🛠️ **Services Used:**
  - Amazon S3 – for hosting static website files
  - AWS CloudFront – for content delivery and caching
  - AWS Certificate Manager (ACM) – for HTTPS setup
  - AWS CodePipeline – for CI/CD automation
  - GitHub – for source control
  - GoDaddy – for domain configuration (CNAME)

---

## 🧰 Tools & Technologies

| Category | Tools |
|-----------|--------|
| Cloud | AWS S3, CloudFront, ACM |
| DevOps | CodePipeline |
| Version Control | GitHub |
| Domain | GoDaddy |
| Languages | HTML, CSS, JavaScript |

---

## 🧱 Architecture Diagram

```text
GitHub Repo → CodePipeline → S3 Bucket → CloudFront → HTTPS (ACM) → Domain (GoDaddy)

