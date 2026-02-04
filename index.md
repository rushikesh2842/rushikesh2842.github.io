---
layout: home
title: "Rushikesh Palnitkar"
---

# Rushikesh Palnitkar

**Data Engineer | AWS, Snowflake, Event-Driven ETL**

I build cloud-native data platforms and ETL pipelines on AWS that turn raw, high-volume data into reliable, analytics-ready datasets — cutting processing time from hours to minutes.[file:1]

[View Resume](link-to-your-resume-pdf) · [GitHub](https://github.com/rushikesh2842) · [LinkedIn](your-linkedin-url)  
Dallas–Fort Worth, TX · Open to internships and data engineer roles[file:1]

---

## What I Do

- Design and build batch and event-driven ETL pipelines on AWS (Lambda, Step Functions, EMR, Glue, Redshift, S3).[file:1]  
- Architect data lakes and warehouses using Delta Lake / medallion patterns and Snowflake for low-latency analytics.[file:1]  
- Automate infrastructure and deployments with Terraform and CI/CD (GitHub Actions) to keep systems reliable and easy to evolve.[file:1]  
- Enable stakeholders with clean, queryable datasets and dashboards in Power BI and Grafana.[file:1]

---

## Skills & Tech

- Data Engineering: ETL/ELT, Data Lakes on S3, Medallion architecture, Data Warehousing, Time-series pipelines.[file:1]  
- Cloud & Infra: AWS (Lambda, Step Functions, Glue, EMR, Redshift, S3, EventBridge, SNS, EC2, ECR), Terraform, GitHub Actions.[file:1]  
- Programming: Python, SQL, Bash, PowerShell.[file:1]  
- Data & Analytics: Snowflake, MySQL, PostgreSQL, MS SQL, MongoDB, DynamoDB, Grafana, Power BI, QuickSight.[file:1]  
- Big Data & ML: PySpark, TensorFlow, PyTorch, MFCC/Mel spectrogram-based preprocessing.[file:1]

---

## Featured Projects

### Serverless Time-Series Extraction

**Goal:** Turn 100 GB of multidimensional satellite weather data (netCDF) into queryable time-series datasets per location.[file:1]  

**Solution:**  
- Orchestrated 365 concurrent AWS Lambda functions via Step Functions, each processing a day of data.[file:1]  
- Containerized Lambdas with netCDF4 and Pandas to parse netCDF and write Parquet to S3.[file:1]  
- Used AWS Glue to consolidate daily files and re-partition by geographical point ID, generating 100+ time-series datasets per location.[file:1]  

**Impact:** Reduced processing time from 7 hours to about 2 minutes while staying fully serverless and scalable.[file:1]  

**Stack:** AWS S3, Lambda, Step Functions, Glue, ECR, Docker, Python, netCDF4, Pandas.[file:1]  

[View Code](link-to-repo)

---

### Event-Driven ETL Pipeline

**Goal:** Build an event-driven pipeline with a 20-minute end-to-end SLA for analytics-ready data.[file:1]  

**Solution:**  
- Configured EventBridge to trigger a Step Functions state machine on each S3 object creation.[file:1]  
- Orchestrated Lambda and PySpark jobs on EMR to perform aggregations and generate Redshift manifest files with metadata.[file:1]  
- Used Redshift stored procedures for automated upserts from staging to core tables and partitioned S3 data lake for data scientists.[file:1]  

**Impact:** Achieved 20-minute refresh SLA and reduced data scientists’ preprocessing time by 50%.[file:1]  

**Stack:** AWS S3, EventBridge, Step Functions, Lambda, EMR, Athena, Glue, Redshift, SNS, PySpark, Python.[file:1]  

[View Code](link-to-repo)

---

### Microservices E-commerce Platform

**Goal:** Deploy a microservices-based ecommerce application with scalable, automated infrastructure.[file:1]  

**Solution:**  
- Containerized 22 microservices with Docker and orchestrated them using Kubernetes on AWS EC2.[file:1]  
- Automated infrastructure with Terraform and CI/CD with GitHub Actions for builds, tests, and deployments.[file:1]  
- Implemented rolling updates and zero-downtime deployments.[file:1]  

**Impact:** Reduced time to deploy infrastructure by 85% and shortened release cycle time by 35%.[file:1]  

**Stack:** AWS EC2, Docker, Kubernetes, Terraform, GitHub Actions.[file:1]  

[View Code](link-to-repo)

---

## Experience

### Data Engineer Intern · Axisray · Sept 2023 – June 2024

- Led development of an ETL pipeline that processed 5M+ records daily from disparate sources.[file:1]  
- Integrated Snowflake and Delta Lake medallion layers, cutting time-series query latency by 40%.[file:1]  
- Reduced daily load times from 1–2 hours to under 15 minutes via automated Bash scripts.[file:1]  
- Maintained 99%+ uptime and improved data quality using Grafana dashboards and validation checks.[file:1]  
- Automated infra provisioning with Terraform and GitHub Actions, reducing recovery time by 50%.[file:1]

### ML Intern · BISAG-N · Jan 2023 – May 2023

- Built a deep learning-based sound recognition model with TensorFlow and PyTorch CNNs, improving accuracy from 70% to 91%.[file:1]

---

## Education

**MS in Computer Science**, University of Texas at Arlington (GPA: 3.78)[file:1]  
Aug 2024 – May 2026  

---

## Contact

- Email: rushi142019@gmail.com[file:1]  
- Location: Dallas–Fort Worth, TX[file:1]  
- GitHub: [github.com/rushikesh2842](https://github.com/rushikesh2842)[web:2]  
- LinkedIn: https://www.linkedin.com/in/rushikesh-palnitkar/
