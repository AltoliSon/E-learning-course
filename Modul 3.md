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
![image](https://github.com/user-attachments/assets/eca95980-9894-4d34-b776-66bce56f327c)
![image](https://github.com/user-attachments/assets/e6dddc25-188c-4e8b-820e-a6fa2139cd24)
![image](https://github.com/user-attachments/assets/3a4980ca-e223-4511-a2b4-590765389b28)
![image](https://github.com/user-attachments/assets/afcb7f00-1cbb-491d-8440-8a494372f87e)
![image](https://github.com/user-attachments/assets/c8712aba-0a0a-4e80-9f4d-62abd731a506)
![image](https://github.com/user-attachments/assets/418e9413-ad71-4faf-9dd5-2eb99039b96a)
![image](https://github.com/user-attachments/assets/75f95abb-83f6-4c3a-a1cb-917b075dfd38)

---
# II. Wrangling data
## 1️⃣ What is Data Wrangling?

**Data wrangling** (or **data munging**) is the process of transforming and preparing raw data into a usable format for analysis.

### 🌀 4 Phases of Data Wrangling:

| Phase          | Description                                                                                   |
|----------------|-----------------------------------------------------------------------------------------------|
| **Discovery**  | Explore data, understand structure, define how to organize, clean, and map data for use case  |
| **Transformation** | Bulk of wrangling: structuring, cleaning, enriching, normalizing, denormalizing           |
| **Validation** | Ensure consistency, quality, and completeness of transformed data                             |
| **Publishing** | Deliver the final, clean dataset with metadata for analysis or downstream processes          |

### 🔧 Transformation Tasks:

#### 🏗️ Structuring:
- Modify format/schema (e.g., merge APIs and DB data)
- Use **Joins** (combine columns) and **Unions** (combine rows)

#### 🧼 Cleaning:
- Handle missing values, nulls, duplicates, outliers, typos
- Convert data types (e.g., text to date), standardize formats

#### 🧠 Enriching:
- Add valuable data points from other systems or public sources
- Examples: add sentiment scores, business performance, geo data

#### 🔄 Normalization / Denormalization:
- Normalize: reduce redundancy (used in transactional systems)
- Denormalize: combine for fast querying (used in analytics)

## 🧰 2️⃣ Tools for Data Wrangling

### 📊 Spreadsheet-Based Tools
| Tool                 | Description                                                                 |
|----------------------|-----------------------------------------------------------------------------|
| **Excel + Power Query** | Manual wrangling with formulas and data connectors                         |
| **Google Sheets**       | Query function for light wrangling; suitable for small datasets            |

### 🧪 Open Source & Cloud Tools
| Tool               | Key Features                                                                  |
|--------------------|-------------------------------------------------------------------------------|
| **OpenRefine**     | Menu-driven UI; format conversion; web extensions; supports TSV, CSV, JSON    |
| **Google DataPrep**| Visual, intelligent cleaning; detects schema and anomalies; no infrastructure |
| **Watson Refinery**| Built-in cleansing, governance compliance; handles multiple data sources      |
| **Trifacta Wrangler** | Interactive, collaborative wrangling; export-ready for tools like Tableau  |

### 🐍 Programming-Based Tools (Python & R)
| Language | Libraries/Tools      | Description                                                  |
|----------|----------------------|--------------------------------------------------------------|
| **Python** | `Pandas`, `Numpy`, `Jupyter` | Fast, flexible data manipulation, cleaning, merging           |
| **R**      | `Dplyr`, `Data.table`, `Jsonlite` | Syntax-rich libraries for wrangling and API integration      |

> 🛠️ **Tool selection depends on** data size, format, team skillsets, infrastructure, and ease of use.

## 🧽 3️⃣ Data Cleaning

**Data cleaning** is a critical step in the data wrangling process and ensures that your analysis is based on high-quality, trustworthy data.

### 🧹 Workflow Steps

| Step         | Description                                                                 |
|--------------|-----------------------------------------------------------------------------|
| **Inspection** | Detect errors, inconsistencies, and missing values using rules or profiling |
| **Cleaning**   | Fix/remove bad data based on business logic and use case                   |
| **Verification**| Check accuracy and effectiveness after cleaning; re-validate constraints  |

### ⚠️ Common Data Issues & Fixes

| Issue             | Solution                                                                 |
|-------------------|--------------------------------------------------------------------------|
| Missing Values     | Filter, source externally, or use **imputation**                         |
| Duplicates         | Identify and remove repeated entries                                     |
| Irrelevant Data    | Drop fields that don’t support the use case                              |
| Incorrect Data Types | Convert to correct type (e.g., text ➝ number)                          |
| Standardization    | Normalize formats (e.g., date, casing, units)                            |
| Syntax Errors      | Trim whitespaces, fix typos (e.g., "NY" vs. "New York")                  |
| Outliers           | Investigate extreme values; keep or remove based on context              |

### 📄 Documentation & Quality Reporting

- **Document**: What changes were made, why, and their impact
- **Report**: Data health, compliance, audit trail, and risk mitigation

## ✅ Summary Table

| Topic               | Key Insights                                                                 |
|---------------------|------------------------------------------------------------------------------|
| Data Wrangling      | Process of preparing raw data for analysis (explore ➝ transform ➝ validate) |
| Tools               | Excel, OpenRefine, Google DataPrep, Trifacta, Python (Pandas), R (Dplyr)     |
| Data Cleaning       | Subset of wrangling focused on fixing errors, inconsistencies, and outliers  |
| Importance          | Ensures accurate, credible, and compliant analytics                          |
| Documentation       | Tracks changes for transparency and reproducibility                          |

