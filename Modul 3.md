# I. Gathering data
## 1.1 🧠 Identifying data for analysis
### 🎯 Goal:
- Understand:
  - **Where you are**
  - **Where you want to be**
  - **What and how to measure**

### 📝 Steps:

#### 1️⃣ Identify Required Data
- Define:
  - What info is needed?
  - What are the potential sources?
- Example: For targeted marketing, you might need:
  - Customer profile (age, income, location, etc.)
  - Purchase history, complaints, social media engagement

#### 2️⃣ Plan for Data Collection
- Define:
  - Timeframes (real-time vs. fixed period)
  - Volume (sample size, population range)
  - Risks, dependencies, and mitigation

#### 3️⃣ Choose Data Collection Methods
- Determine:
  - How and from where to collect (internal, social media, APIs, etc.)
  - Adjust plans during execution based on real-world conditions

### 🔒 Key Considerations:
- **Data Quality**: Accuracy, completeness, relevance, accessibility
- **Data Governance**: Usability, security, compliance (e.g., GDPR)
- **Data Privacy**: Confidentiality, licensing, traceability
---
## 1.2 Data source
### 📂 Types of Sources:

| Type            | Description                                                                                  |
|------------------|----------------------------------------------------------------------------------------------|
| **Primary**       | Data collected directly by you (e.g., surveys, internal CRM, interviews)                    |
| **Secondary**     | Data collected from existing sources (e.g., research, publications, external surveys)       |
| **Third-party**   | Data purchased from aggregators (e.g., marketing, demographics datasets)                    |

### 🏷️ Common Data Sources:

- **Databases** (internal or external, cloud-based)
- **Web data** (websites, social media platforms like Facebook, Twitter)
- **Sensor data** (from IoT, wearables, smart cities)
- **Data exchange platforms** (e.g., AWS Data Exchange, Snowflake)
- **Surveys, Census data, Interviews, Observations**

### 📌 Key Insight:
> Combining **primary, secondary**, and **third-party data** gives broader, deeper insights into complex problems.
---
## 1.3 📥 How to gather and import data

### 🧰 Methods of Data Collection:

| Method             | Description                                                                                      |
|--------------------|--------------------------------------------------------------------------------------------------|
| **SQL Queries**     | Structured queries from relational databases                                                     |
| **APIs**            | Request data from endpoints, validate data (e.g., zip code, social media stats)                 |
| **Web Scraping**    | Extract text, images, contacts, product info from web pages using set parameters                 |
| **RSS Feeds**       | Capture updated data from news/forums                                                            |
| **Data Streams**    | Collect real-time continuous data (e.g., sensors, GPS, social media)                             |
| **Data Exchange**   | Use secure, governed platforms for regulated data sharing                                        |

### 🗃️ Importing Data into Repositories

#### 🏛️ Structured Data:
- From: OLTP, forms, spreadsheets
- Stored in: **Relational DBs**, **NoSQL**

#### 📦 Semi-structured Data:
- From: XML, JSON, email, logs
- Stored in: **NoSQL clusters**, **Document DBs**

#### 🌀 Unstructured Data:
- From: Social media, images, videos, PDFs
- Stored in: **Data Lakes**, **NoSQL**

### ⚙️ Tools for Importing:
- **ETL Tools**: Talend, Informatica
- **Languages**: Python, R (with libraries like Pandas, BeautifulSoup)
- **Data Pipelines**: Automate extraction, transformation, and loading

## ✅ Summary Table

| Phase                       | Key Activities                                                                 |
|-----------------------------|---------------------------------------------------------------------------------|
| Identifying Data            | Define goal, choose data types and sources                                     |
| Planning Data Collection    | Timeframes, volume, risk, privacy, governance                                  |
| Gathering Methods           | SQL, APIs, scraping, streaming, surveys, sensors                               |
| Data Repositories           | RDBMS (structured), NoSQL (semi-structured), Data Lakes (all types)            |
| Importing Tools             | Talend, Informatica, Python, ETL pipelines                                     |
| Compliance & Quality        | Ensure accuracy, legal compliance, security, and auditable traceability        |

---
## Pratice quiz


# II. Wrangling data
