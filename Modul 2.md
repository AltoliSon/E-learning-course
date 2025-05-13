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

## 2.2 RDBMS
