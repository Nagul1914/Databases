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

💡 **Example (Key-Value Store in Redis)**:  

```bash
SET employee:101 "Alice Johnson"
GET employee:101
## **🔹 Column-Family Stores (Wide-Column Stores)**  
- Stores data in **columns instead of rows**, allowing **fast queries on large datasets**.  
- Best for **real-time analytics, recommendation systems, and time-series data**.  

### **🔹 Examples:**  
- **Apache Cassandra**  
- **HBase** (Used in Hadoop Ecosystem)  
- **Google Bigtable**  

💡 **Example (Cassandra Table Definition):**  

```sql
CREATE TABLE employees (
    id UUID PRIMARY KEY,
    name TEXT,
    department TEXT,
    salary INT
);
## **🔹 Graph Databases**  
- Stores data as **nodes and relationships** (ideal for **connected data**).  
- Best for **social networks, fraud detection, and recommendation engines**.  

### **🔹 Examples:**  
- **Neo4j**  
- **ArangoDB**  
- **Amazon Neptune**  

💡 **Example (Neo4j Graph Representation - Social Network):**  

```plaintext
(Alice)-[:FRIEND]->(Bob)
(Bob)-[:WORKS_WITH]->(Charlie)
#Databases That Handle Different Types of Data
# 📌 **Types of Data and Databases**

## **1. Structured Data**  
Structured data is organized in a **predefined schema**, usually in **rows and columns** (like in relational databases). It is easy to search and query using **structured query languages (SQL)**.

### **🔹 Databases:**
- MySQL  
- PostgreSQL  
- Oracle Database  
- Microsoft SQL Server  

### **🔹 Use Cases:**
- Traditional business applications (e.g., ERP, CRM)  
- Financial systems  
- Transactional systems  

---

## **2. Semi-Structured Data**  
Semi-structured data does not have a **fixed schema**, but it contains **tags or markers** to separate data elements. It allows for **flexibility** in the structure of the data.

### **🔹 Databases:**
- MongoDB (Document-oriented)  
- Couchbase (Document-oriented)  
- Apache Cassandra (Column-family store)  
- Amazon DynamoDB (Key-Value store)  

### **🔹 Use Cases:**
- Content management systems (CMS)  
- Log and sensor data  
- E-commerce catalogs  

---

## **3. Unstructured Data**  
Unstructured data is **raw data** that does not follow a **specific format** or schema, making it difficult to store and retrieve using traditional databases.

### **🔹 Databases:**
- Hadoop HDFS (Distributed file system)  
- Elasticsearch (Search engine for unstructured data)  
- Amazon S3 (Object storage)  
- MongoDB (Can also handle unstructured data)  

### **🔹 Use Cases:**
- Multimedia files (audio, video, images)  
- Social media posts  
- Raw text data  
- Emails  

---

## **📊 Summary Table:**

| **Data Type**    | **Example Databases**                | **Use Cases**                              |
|------------------|--------------------------------------|--------------------------------------------|
| **Structured**   | MySQL, PostgreSQL, Oracle DB         | Financial systems, business apps          |
| **Semi-Structured** | MongoDB, Cassandra, DynamoDB        | CMS, e-commerce, logs, sensor data        |
| **Unstructured** | Hadoop HDFS, Elasticsearch, S3      | Multimedia, social media, raw text        |

---





