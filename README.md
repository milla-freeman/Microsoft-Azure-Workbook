# ☁️ Microsoft Azure Cloud Computing Project  
### Azure Fundamentals • Cloud Models • ADF • Relational & Non-Relational Data • Security & Compliance

---

## 📌 Project Overview

This project showcases my introduction to **Microsoft Azure**, completed as part of a cloud and data engineering module.  
The work includes:

- Understanding cloud concepts  
- Analysing pricing and cost estimation  
- Exploring cloud service models (IaaS, PaaS, SaaS)  
- Public, private, hybrid and community cloud  
- Legal and regulatory frameworks (GDPR, DPA 2018, Computer Misuse Act)  
- Azure SQL databases using **AdventureWorks**  
- Azure Storage & non-relational data  
- Hands-on labs with **Azure Data Factory** and **Microsoft Fabric**  
- DP-900 practice exam activities  

---

## 🗂️ Files Included

- **Cloud Computing & ADF Workbook.docx** — full written tasks, research, SQL queries and screenshots  
- Additional lab screenshots 

---

## ☁️ Cloud Computing Topics Covered

### **🔹 What Cloud Computing Is**
- On-demand access to data, storage, applications and infrastructure  
- Reduces need for physical hardware  
- Improves accessibility, flexibility and cost efficiency  

### **🔹 Cloud Benefits for Businesses**
- Lower infrastructure costs  
- Remote collaboration  
- Scalability  
- Automated backups & security  
- Access to AI and analytics tools  

### **🔹 Cloud Service Models**
| Model | Description | Real-World Use |
|-------|-------------|----------------|
| **IaaS** | Virtual machines, storage, networking | Hosting websites, running apps |
| **PaaS** | Platform for development & deployment | Building & testing apps |
| **SaaS** | Software delivered online | Gmail, Teams, Salesforce |

---

## 🌐 Cloud Deployment Models

- **Public Cloud** – Shared resources (e.g., AWS, Azure)  
- **Private Cloud** – Dedicated resources for one organisation  
- **Hybrid Cloud** – Mix of on-premises and cloud  
- **Community Cloud** – Shared by organisations with similar needs  

Each model was researched with definitions and real-world industry examples.

---

## 📘 Legal, Ethical & Security Topics

### **📜 Computer Misuse Act (1990)**  
- Unauthorised access  
- Unauthorised modification  
- Access with intent to commit crime  

### **📜 Police & Justice Act (2006) Enhancements**
- Criminalising DoS attacks  
- Making/supplying hacking tools illegal  
- Clarifying unauthorised access rules  

### **📜 Data Protection**
- **GDPR**  
- **Data Protection Act 2018**  
- Rules around storing employee data  
- Sensitive data requiring employee consent  
- Examples of plagiarism and copyright infringement  

These were researched and written in workbook tasks.

---

## 🧮 Azure Pricing Calculator

The project includes an exercise estimating the cost of running a basic Azure web application using the **Azure Pricing Calculator**, demonstrating cost-management understanding.

---

## 🗄️ Azure Relational Data (SQL)

Hands-on SQL queries using **Azure SQL Database** and the **AdventureWorks** dataset.

### Examples:
```sql
-- Customers with last names starting with 'A'
SELECT c.CustomerID, c.FirstName, c.LastName
FROM SalesLT.Customer AS c
WHERE c.LastName LIKE 'A%';
````

```sql
-- Top 3 black products in size S ordered by price
SELECT TOP (3) ProductID, Name, Color, Size, ListPrice
FROM SalesLT.Product
WHERE Color = 'Black' AND Size = 'S'
ORDER BY ListPrice ASC;
```

```sql
-- Total quantity sold per product
SELECT p.ProductID, p.Name, SUM(sod.OrderQty) AS TotalQuantitySold
FROM SalesLT.SalesOrderDetail AS sod
JOIN SalesLT.Product AS p ON sod.ProductID = p.ProductID
GROUP BY p.ProductID, p.Name
ORDER BY TotalQuantitySold DESC;
```

Queries included filtering, aggregates, joins, subqueries and business scenarios.

---

## 📦 Azure Non-Relational Data

Completed Lab: **Explore Non-Relational Data in Azure**, including:

* Azure Blob Storage
* Containers & file structures
* JSON & unstructured data
* Access tiers & data retrieval

---

## 🔄 Azure Data Factory (ADF)

Practical ADF tasks included:

* Pipelines
* Linked services
* Data ingestion
* Copy Data tool
* Transformations
* Automation for data movement

Also completed Microsoft Fabric ADF tutorials using a JustIT account.

---

## 🧪 DP-900 Practice Exam

A team-based practice exam was completed covering:

* Azure data concepts
* Relational & non-relational databases
* Analytics workloads
* Azure Synapse, Databricks, Data Lake

---

## 📝 Reflection

Through this project, I gained confidence in:

* Understanding Azure fundamentals
* Working with relational & non-relational data
* Navigating Azure Portal
* Using SQL within Azure
* Applying cloud concepts to real-world business problems
* Using data factory tools for automation
* Understanding compliance, security & cloud governance

---

## 🚀 Future Improvements

* Build full ADF pipelines end-to-end
* Explore Azure Synapse & Databricks
* Deploy a small web app or database in Azure
* Automate reporting with Power BI + Azure



---
```
