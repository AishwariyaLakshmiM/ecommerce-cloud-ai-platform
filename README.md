# E-Commerce Cloud AI Platform

Developed by: **Aishwariya Lakshmi M**  
Sri Manakula Vinayagar Engineering College, Puducherry  

---

## 📘 Project Overview

This project demonstrates a cloud-based **E-Commerce AI Platform** designed to showcase scalable infrastructure, data processing, and AI-driven decision support.  
The goal is to host an e-commerce system on a virtualized cloud environment integrated with data analytics and intelligent load balancing mechanisms.

Although the current version focuses on local simulation and architectural design, the project structure and codebase are fully cloud-ready for deployment on AWS.

---

## ☁️ Key Features

- Virtual machine setup (simulated EC2 environment)
- Sample dataset imported into a SQL database (SQLite)
- Basic data cleaning and preprocessing using **Pandas**
- Data visualization using **Matplotlib** and **Seaborn**
- AI module integration using **Scikit-learn** (for customer behavior prediction)
- Encryption logic for secure data handling (simulated at rest and in transit)
- Well-structured folder layout ready for AWS deployment

---

## ⚙️ Technology Stack

| Category | Tools & Technologies |
|-----------|----------------------|
| Programming Language | Python 3 |
| Data Processing | Pandas, NumPy |
| Visualization | Matplotlib, Seaborn |
| Machine Learning | Scikit-learn |
| Database | SQLite (can be extended to AWS RDS/MySQL) |
| Cloud Design (Planned) | AWS EC2, S3, RDS |
| Security | Simulated encryption using hashlib / Fernet |

---

## 🧠 AI Component

The AI module, **smv_predictor_v1**, analyzes sample e-commerce data to predict:
- Customer purchase likelihood  
- Price sensitivity  
- Product category recommendations  

Machine learning algorithms such as Logistic Regression and Decision Tree are used for model training and evaluation.

---

## 🗂️ Folder Structure

ecommerce-cloud-ai-platform/
│
├── data/ 
├── notebooks/ 
├── models/ 
├── scripts/ 
├── requirements.txt 
└── README.md 

---

## 📊 Visual Insights

The dataset was cleaned and analyzed using Pandas and visualized with Matplotlib & Seaborn.  
Key trends like **customer purchase frequency**, **average basket value**, and **price sensitivity** were observed.

---

## 🔒 Security and Encryption

Encryption has been simulated for both **data-at-rest** and **data-in-transit** using Python’s built-in cryptography functions.  
Future deployment on AWS will apply **KMS (Key Management Service)** and **SSL/TLS** for full-scale encryption.

---

## 🚀 Future Cloud Integration (Planned)

In the extended version of this project:
- A cloud EC2 instance (`smv_data-ai-node`) will be used to deploy the application.  
- Data will be stored securely in **AWS RDS (PostgreSQL)**.  
- S3 will be used to host static files and datasets.  
- A CI/CD pipeline will automate deployment.  
- The AI model will be containerized using **Docker** and integrated for real-time prediction.  

---

## 🧩 What I Learned

- Setting up a simulated cloud-ready Python environment  
- Structuring projects for data pipeline and AI integration  
- Implementing data visualization and ML algorithms  
- Designing a secure, scalable architecture for cloud migration  

---

## 🏁 Conclusion

This project serves as a foundational prototype for an **AI-driven e-commerce platform** that combines data analytics, security, and scalability.  
It demonstrates how local simulation can seamlessly evolve into a complete AWS deployment.

---

## 🗒️ Repository 
GitHub Repository: (https://github.com/AishwariyaLakshmiM/ecommerce-cloud-ai-platform)

---
This repository was developed for academic learning and cloud-AI integration demonstration purposes.
