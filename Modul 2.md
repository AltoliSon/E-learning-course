# I. The data ecosystem and Languages for data professionals
## 1.1 Overview of the Data analyst ecosystem 
![image](https://github.com/user-attachments/assets/ab0b0df5-7772-423e-859e-f3dc488c003e)

## 1.2 Type of data
![image](https://github.com/user-attachments/assets/77936285-4141-4e06-a5f6-19970bdcf975)
## 1.3 Understanding different types of file formats
| File Format       | Full Name                             | Key Characteristics                                                                                   | Common Use Cases                                      |
|------------------|----------------------------------------|--------------------------------------------------------------------------------------------------------|-------------------------------------------------------|
| CSV / TSV        | Comma / Tab-Separated Values           | - Text files with values separated by a delimiter<br>- CSV uses commas, TSV uses tabs<br>- Human-readable and widely supported | Data exchange between systems, spreadsheets           |
| XLSX             | Microsoft Excel Open XML Spreadsheet   | - XML-based spreadsheet format<br>- Supports multiple worksheets, rows, columns, and cells<br>- Secure and feature-rich | Business reports, data analysis in Excel              |
| XML              | Extensible Markup Language             | - Self-descriptive and tag-based<br>- Human- and machine-readable<br>- Platform and language independent | Data exchange between different systems and platforms |
| PDF              | Portable Document Format               | - Preserves document layout across platforms<br>- Can include forms<br>- Not easily editable           | Legal documents, financial statements, data forms     |
| JSON             | JavaScript Object Notation             | - Lightweight, text-based<br>- Language-independent<br>- Easy to use with APIs and web apps            | Web services, APIs, configuration files               |

## 1.4 Sources of data
| Data Source Type     | Description                                                                                               | Examples / Tools Used                                                                                          | Common Use Cases                                                                 |
|----------------------|-----------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------|
| **Relational Databases** | Structured data stored in multiple tables using RDBMS.                                                 | SQL Server, Oracle, MySQL, IBM DB2                                                                             | Customer transactions, HR systems, CRM data, sales analytics                    |
| **Flat Files**           | Plain text files with one record per line, values separated by delimiters (CSV, TSV).                  | CSV, TSV                                                                                                        | Data exchange, simple tabular data, logs                                        |
| **Spreadsheet Files**    | Flat files with additional features like formulas, formatting, multiple sheets.                         | Microsoft Excel (.XLS/.XLSX), Google Sheets, Apple Numbers, LibreOffice                                        | Financial reports, business data analysis                                       |
| **XML Datasets**         | Hierarchical structured data using tags, supports complex structures.                                   | XML                                                                                                            | Online surveys, bank statements, nested or complex data                         |
| **APIs & Web Services**  | Interfaces for accessing data via requests, returns structured/unstructured data formats.               | REST APIs, Twitter API, Facebook API, Stock Market APIs, Validation APIs                                       | Social media analysis, financial data, address validation, app integrations     |
| **Web Scraping**         | Technique to extract data from web pages by parsing the HTML or DOM structure.                         | BeautifulSoup, Scrapy, Selenium, Pandas                                                                         | Price comparison, sales leads, forum data, training datasets for ML             |
| **Data Streams**         | Continuous, real-time flow of data often geo-tagged and timestamped.                                    | Apache Kafka, Apache Spark Streaming, Apache Storm                                                             | IoT sensors, market tickers, surveillance feeds, clickstreams, flight data      |
| **RSS Feeds**            | Syndicated, regularly updated data streams, especially from news and forums.                            | RSS Readers                                                                                                     | News updates, blog tracking, event notifications                                |

## 1.5 Summary and highlights
A data analyst ecosystem includes the infrastructure, software, tools, frameworkd, and processes used to gather, clean, analyze, mine and visualize data. 

## 1.6 Pratice quiz
![image](https://github.com/user-attachments/assets/02d09616-23f2-4ac1-96c7-d269f8f60961)
![image](https://github.com/user-attachments/assets/e2b52eb9-6b5a-48e7-9017-e1d56ac305bc)
![image](https://github.com/user-attachments/assets/dc657eeb-4265-476a-a0ed-784811a51bde)

## 1.7 Graded quiz
![image](https://github.com/user-attachments/assets/bf41a77d-72be-427f-88f4-56bb85161649)
![image](https://github.com/user-attachments/assets/54ac5db0-7f0d-49e2-9be9-62fb5c6b58cc)
![image](https://github.com/user-attachments/assets/4e4fc15a-efc8-4214-a310-78b60ede56e0)
![image](https://github.com/user-attachments/assets/bce70a49-6a46-4169-be42-8de88be60c23)
![image](https://github.com/user-attachments/assets/6fb2b52b-50aa-4ac0-98e3-a9e75ac1cb72)
---
# II. Understanding data repositories and big data platforms
## 2.1 Overview of Data repositories
 
📦 A data repository is a system where data is collected, organized, and isolated for use in business operations, reporting, and analysis. It may range from a small to a large-scale infrastructure and can include: **Databases - Data Warehouses - Big Data Stores**

### 2.1.1 🗃️ Databases
A database is a structured collection of data that supports: Input-Storage-Search & Retrieval-Modification
A Database Management System (DBMS) is a set of programs used to manage and interact with the database. ➕ Querying is used to extract specific information, e.g., retrieving customers inactive for 6+ months.

🧱 Types of Databases
1. Relational Databases (RDBMS)
- Data organized in tables (rows & columns)
- Structured with a fixed schema
- Uses SQL (Structured Query Language)
- Optimized for complex queries and large data volumes
2. Non-Relational Databases (NoSQL)
- Schema-less, flexible, scalable
- Built for handling big data, IoT, social media
- Allows storage of varied and fast-paced data
### 2.1.2 🏢 Data Warehouse
A Data Warehouse is a centralized repository designed for analytics and business intelligence.

🔁 ETL Process
- Extract data from multiple sources
- Transform it into a clean, usable format
- Load it into a repository
  
🔹 Related Concepts
- Data Marts: Subsets of data warehouses
- Data Lakes: Store raw and unstructured data
- Traditional data warehouses used relational databases, but modern warehouses may use NoSQL systems as well.
  
### 2.1.3 🌐 Big Data Stores
Designed for very large datasets. Uses distributed computing and storage. Supports scalability and high-speed processing

✅ Benefits of Data Repositories
- Centralized and isolated data
- Improved reporting and analysis
- Credible data access
- Efficient long-term storage (archiving)
---
## 2.2 RDBMS
### 2.2.1 📌 What is a Relational Database?
- A **relational database** organizes data into **tables** made of **rows (records)** and **columns (attributes)**.
- Tables can be **linked** using common fields (e.g., Customer ID).
- Enables powerful **queries** to combine data across multiple tables.

### 2.2.2 🧩 Key Components
- **DBMS (Database Management System):** Software to manage, query, and maintain databases.
- **SQL (Structured Query Language):** Standard language used for querying relational databases.

### 2.2.3 📊 Relational vs. Flat Files
| Relational DB                     | Flat File                          |
|----------------------------------|------------------------------------|
| Multiple linked tables           | One single table per file          |
| Uses SQL for powerful queries    | Limited querying capability        |
| Scalable to millions of records  | Row/column limits (e.g., Excel)    |
| Schema enforced (structured)     | Less structured                    |

### 2.2.4 🔗 Relational Structure Example
- **Customer Table**: Contains Company ID, Name, Address, Phone
- **Transaction Table**: Contains Transaction Date, Customer ID, Amount
- Tables are **related by Customer ID**

### 2.2.5 ✅ Advantages of RDBMS
- **Flexibility**: Add tables/columns while running queries
- **Data Integrity**: Minimized redundancy via normalization
- **Backup & Recovery**: Easy exports/imports, cloud mirroring
- **ACID Compliance**:
  - **A**tomicity
  - **C**onsistency
  - **I**solation
  - **D**urability

### 2.2.6 ☁️ Popular Relational Databases
- **On-premise**: MySQL, PostgreSQL, Oracle, Microsoft SQL Server, IBM DB2
- **Cloud-based (DBaaS)**:
  - Amazon RDS
  - Google Cloud SQL
  - Azure SQL Database
  - Oracle Cloud, IBM DB2 on Cloud

### 2.2.7 🔍 Use Cases
- **OLTP (Online Transaction Processing)**: Fast insert/update/delete for many users
- **OLAP (Online Analytical Processing)**: Business intelligence with historical data
- **IoT Solutions**: Lightweight, fast querying from edge devices

### 2.2.8 ⚠️ Limitations of RDBMS
- Not suitable for **semi-structured/unstructured data**
- **Schema-dependent** during migration between systems
- **Field length limits** may restrict large data entries
Less effective with **big data**, **social media**, or **multimedia formats**. Relational databases remain the **most widely used** solution for handling **structured data**, despite limitations in handling modern, unstructured or real-time streaming data.
---
## 2.3 NoSQL
### 2.3.1 📌 What is NoSQL?

- **NoSQL** stands for **“Not Only SQL”**, not “No SQL”.
- It refers to **non-relational databases** with **flexible schemas**, suitable for handling:Structured data- Semi-structured data- Unstructured data- Designed for scalability, performance, and handling **high-volume web/mobile/cloud applications**.

### 2.3.2 🔢 Types of NoSQL Databases

### 1. 🔑 Key-Value Stores
- Data stored as **key-value pairs**
- **Use cases**: Session storage, real-time recommendations, caching
- **Examples**: Redis, Memcached, DynamoDB
- **Limitation**: Poor for querying relationships or multiple unique keys

### 2. 📄 Document-Based Databases
- Stores entire record as a **document (e.g., JSON)**
- **Use cases**: eCommerce, medical records, CRM, analytics
- **Examples**: MongoDB, DocumentDB, CouchDB, Cloudant
- **Limitation**: Limited support for complex transactions or advanced queries

### 2.3.3 ⚖️ NoSQL vs. RDBMS – Key Differences

| Feature                     | RDBMS                               | NoSQL                                     |
|----------------------------|--------------------------------------|--------------------------------------------|
| Schema                     | Fixed, predefined                    | Flexible, schema-less                      |
| Data Types                 | Mostly structured                    | Structured, semi-structured, unstructured  |
| Query Language             | SQL                                  | NoSQL APIs, JSON, or SQL-like languages    |
| Scaling                    | Vertical                             | Horizontal (scale-out)                     |
| ACID Compliance            | Fully supported                      | Partial or eventual consistency            |
| Cost                       | Higher (often commercial)            | Lower, supports commodity hardware         |
| Maturity                   | Long-established, well-documented    | Newer, evolving rapidly                    |

### 2.3.4 🧠 Summary
- NoSQL databases were built to overcome **limitations of relational databases**, especially in the age of **cloud computing, IoT, and big data**.
- With diverse data models and horizontal scalability, NoSQL is ideal for **modern, large-scale, and agile systems**.
- While RDBMS remains dominant for structured and transactional data, **NoSQL continues to grow** in importance and adoption.
---
## 2.4 Data marts, data lakes, ETL, and data pipelines
### 1. Overview of Data marts, lake, warehouse.
- A data warehouse is a multi-purpose anabler of operational and performance analytics.
![image](https://github.com/user-attachments/assets/2614ee1b-99f3-402b-916c-bd1a5acf96a0)
- A data lake is a storage repository that can store large amounts of structured, semi-structured, unstructured data in their native format, classified and tagged with metadata. 
#### 🗃️ Data Warehouse

- Centralized repository for **cleaned and structured data**, ready for reporting and analytics.
- Acts as a **single source of truth**.
- Suitable for **large volumes** of operational data.
- Data is already **modeled and structured** before being loaded.
- Supports both **operational** and **performance analytics**.

#### 🧩 Data Mart

- A **subset** of a data warehouse tailored for **specific business units** (e.g., sales, finance).
- Offers **isolated performance and security**.
- Designed for **business-specific reporting and analytics**.

#### 🌊 Data Lake

- Repository for storing **large volumes** of **structured, semi-structured, and unstructured data**.
- Data is stored in its **raw native format**, tagged with metadata.
- Ideal when:
  - Use cases are **not pre-defined**
  - You want to **retain all source data**
- Often used for:
  - **Advanced and predictive analytics**
  - As a **staging area** for data warehouses

### 🔄 2. ETL Process (Extract, Transform, Load)

#### 📥 Extract
- **Collect raw data** from source systems
- Two methods:
  - **Batch Processing** (e.g., Stitch, Blendo)
  - **Stream Processing** (e.g., Apache Kafka, Samza, Storm)

#### 🔧 Transform
- Clean and standardize data:
  - Unify date formats, units
  - Remove duplicates
  - Enrich data (e.g., split full name)
  - Apply business rules
  - Validate and relate data

#### 📤 Load
- Move transformed data into destination:
  - **Initial Load**: Populate full dataset
  - **Incremental Load**: Apply periodic updates
  - **Full Refresh**: Replace data completely
- Includes **load verification** and **error recovery mechanisms**


### 🔗 3. Data Pipelines

- A **broader concept** than ETL: end-to-end data movement from source to destination.
- Can handle:
  - **Batch data**
  - **Streaming data**
  - Or both (hybrid pipelines)
- Allows **real-time processing** (e.g., sensor or traffic data)
- Final destination can be:
  - **Data lake**
  - **Analytics platforms**
  - **Visualization tools**
- Popular tools: **Apache Beam**, **Google DataFlow**
---
## 2.5 Big Data processing Tools
#### Summary: Big Data Tools — Hadoop, Hive, and Spark
- **Hadoop** provides the backbone of big data storage and distributed processing.
- **Hive** makes querying big data easier for analysts using familiar SQL-like syntax.
- **Spark** brings speed, flexibility, and real-time analytics capabilities to the big data ecosystem.

#### 🔄 Comparison Table

| Feature               | Hadoop                                | Hive                                  | Spark                                |
|-----------------------|----------------------------------------|----------------------------------------|--------------------------------------|
| Role                  | Storage & distributed processing       | Data warehouse on Hadoop               | General-purpose data processing       |
| Data Processing       | Batch (slow)                           | Batch (with SQL-like queries)          | Real-time + batch (very fast)        |
| Data Storage          | HDFS                                   | HDFS / HBase                           | Uses HDFS, Hive, and more            |
| Latency               | High                                   | High                                   | Low (real-time possible)             |
| Query Language        | Java-based APIs                        | SQL-like (HiveQL)                      | SQL, Python, Scala, R                |
| Use Cases             | Big data storage, cold data offload    | ETL, Reporting, Large-scale querying   | ML, stream processing, fast analytics|
