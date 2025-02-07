#Databases
# 📌 What is a Database?  

A **database** is a structured collection of data that is stored and managed electronically. It allows users to **store, retrieve, update, and manage data efficiently**.  

💡 **Example:** A company's **employee records, customer details, and financial transactions** are stored in a database.  

---

## 🔹 Types of Databases  
There are two main types:  

1️⃣ **Relational Databases (SQL)** – Data is stored in tables with **rows & columns**.  

2️⃣ **Non-Relational Databases (NoSQL)** – Data is stored in various formats like **JSON, key-value, or graph structures**.  
# **What Are Relational Databases? (SQL Databases)**
A **Relational Database (RDBMS)** stores data in **structured tables** with relationships between them. It follows the **ACID** properties (**Atomicity, Consistency, Isolation, Durability**) to ensure **data reliability**.

💡 **Example:**  
A banking system stores **customers, accounts, and transactions** in separate tables but links them using **unique IDs** (Primary & Foreign Keys).

---

## **🛠️ Popular Relational Databases (RDBMS)**

| **Database**      | **Description** |
|------------------|----------------------------------------------|
| **MySQL**        | Open-source, widely used in web applications (e.g., WordPress, e-commerce). |
| **PostgreSQL**   | Advanced SQL database with strong security & performance (used in financial apps). |
| **Oracle Database** | Enterprise-grade database for large-scale applications (used by banks, telecom). |
| **SQL Server**   | Microsoft’s database, integrated with .NET applications (used in businesses). |
| **SQLite**       | Lightweight, used in mobile applications & embedded systems. |
# **📌 What is a Non-Relational Database (NoSQL)?**  

A **Non-Relational Database (NoSQL)** is a type of database that **does not use tables, rows, and columns** like traditional SQL databases. Instead, it stores data in **flexible formats** such as **JSON, key-value pairs, documents, or graphs**.  

💡 **Why NoSQL?**  
- Handles **large-scale, unstructured, or semi-structured data**.  
- Provides **high scalability and fast performance**.  
- Used in **Big Data, real-time applications, and distributed systems**.  

---

## **🔹 Types of NoSQL Databases**  

NoSQL databases are classified into **four main types**, each designed for different use cases:  

### **1️⃣ Document-Oriented Databases**  
- Stores data in **JSON-like documents**.  
- Each document contains **key-value pairs** and can have different structures.  
- Best for **content management, catalogs, and user profiles**.  

**🔹 Examples:**  
- **MongoDB**  
- **CouchDB**  
- **Firebase Firestore**  

💡 **Example (MongoDB Document)**:  
```json
{
  "employee_id": 101,
  "name": "Alice Johnson",
  "department": "IT",
  "skills": ["Python", "SQL", "Machine Learning"]
}
## **🔹 Key-Value Databases**  
- Stores data as a **key-value pair**.  
- Best for **caching, session management, and simple lookups**.  

### **🔹 Examples:**  
- **Redis**  
- **DynamoDB (AWS)**  
- **Riak KV**  

