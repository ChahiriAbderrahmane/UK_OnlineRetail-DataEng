<div align="center">
  <a href="https://lookerstudio.google.com/reporting/d51192fe-033f-4717-ba91-dd90c2f11dee/page/p_mgrr5jq6sd">
    <img src="https://github.com/ChahiriAbderrahmane/UK_OnlineRetail-DataEng/blob/master/%F0%9F%93%8A_Online_Retail_Dashboard_Chahiri_page-0001.jpg" alt="Banner" width="720">
  </a>

  <div id="user-content-toc">
    <ul>
      <summary><h1 style="display: inline-block;">👨‍🔧 Online Retail Data Pipeline 👷</h1></summary>
    </ul>
  </div>
  
  <p>Retail Data Pipeline with aws S3 bucket, Databricks, GCP BigQuery and Looker</p>
    <a href="https://lookerstudio.google.com/reporting/d51192fe-033f-4717-ba91-dd90c2f11dee/page/p_mgrr5jq6sd" target="_blank">Dashboard</a>
    📊 
    <a href="https://github.com/ChahiriAbderrahmane/UK_OnlineRetail-DataEng" target="_blank">Request Feature</a>
</div>
<br>

## 📝 Table of Contents

1. [ Project Overview ](#introduction)
2. [ Key Insights ](#features)
3. [ Project Architecture ](#arch)
4. [ Credits ](#refs)
5. [ Contact ](#contact)

<a name="introduction"></a>
## 🔬 Project Overview 

This an end-to-end data engineering project, where I created an ELT data pipeline to extract, analyze, and visualize insights from the data of an online retail company based in the UK.

### 💾 Dataset

This is a transnational data set that contains all the transactions occurring between 01/12/2010 and 09/12/2011 for a UK-based and registered non-store online retail. The company mainly sells unique all-occasion gifts. Many customers of the company are wholesalers.

The dataset includes the following columns:

| **Column** | **Description** |
| :--------------- |:---------------| 
| **InvoiceNo** |  Invoice number. Nominal, a 6-digit integral number uniquely assigned to each transaction. If this code starts with the letter 'c', it indicates a cancellation.  |  
| **StockCode** | Product (item) code. Nominal, a 5-digit integral number uniquely assigned to each distinct product. |
| **Description**   |  Product (item) name. Nominal.  |
| **Quantity**   |  The quantities of each product (item) per transaction. Numeric.  |
| **InvoiceDate**   |  Invoice Date and time. Numeric, the day and time when each transaction was generated.  |
| **UnitPrice**   |  Unit price. Numeric, Product price per unit in sterling.  |
| **CustomerID**   |  Customer number. Nominal, a 5-digit integral number uniquely assigned to each customer.  |
| **Country**   |  Country name. Nominal, the name of the country where each customer resides.   |

### 🎯 Project Goals

- CSV ingestion from S3 into Databricks
- Clean and transform data with Spark into parquet tables
- Data Modeling: Implement a star schema for analytical queries
- Load processed tables into BigQuery
- Provide interactive dashboards in Looker Studio

<a name="features"></a>
## 🕵️ Key Insights

- 💸 **Total Revenue by Country**
  - The UK 🇬🇧 is the country that generated the most of the company's revenue with over 1.8M followed by France with 182.4k.

    
- 📈 **Revenue by months**
  - The month with the most revenue is July with more than 220K.
  - The month with the lowest revenue is December with 100K.
 
> We can observe significant revenue increases in January (New Year), July (Wimbledon Finals), and November (Bonfire Night).


<a name="arch"></a>
## 📝 Project Architecture
![Architecture](https://github.com/ChahiriAbderrahmane/UK_OnlineRetail-DataEng/blob/master/Project%20Architecture.jpg)

### ⚙️ Data Modeling
![image](https://github.com/ChahiriAbderrahmane/UK_OnlineRetail-DataEng/blob/master/Database%20ER%20diagram%20.png)

# Here are some screenshots of the work I've done.

<div align="center">
  <img src="https://github.com/ChahiriAbderrahmane/UK_OnlineRetail-DataEng/blob/master/screen1.png" width="45%" />
  <img src="https://github.com/ChahiriAbderrahmane/UK_OnlineRetail-DataEng/blob/master/screen3.png" width="45%" />
</div>

<div align="center">
  <img src="https://github.com/ChahiriAbderrahmane/UK_OnlineRetail-DataEng/blob/master/screen4.png" width="45%" />
  <img src="https://github.com/ChahiriAbderrahmane/UK_OnlineRetail-DataEng/blob/master/screen5.png" width="45%" />
</div>

<div align="center">
  <img src="https://github.com/ChahiriAbderrahmane/UK_OnlineRetail-DataEng/blob/master/screen6.png" width="45%" />
</div>



### 🛠️ Technologies Used
![Amazon S3](https://img.shields.io/badge/Amazon%20S3-FF9900?style=for-the-badge&logo=amazons3&logoColor=white)
![Databricks](https://img.shields.io/badge/Databricks-FF3621?style=for-the-badge&logo=databricks&logoColor=white)
![BigQuery](https://img.shields.io/badge/BigQuery-4285F4?style=for-the-badge&logo=googlebigquery&logoColor=white)
![Looker Studio](https://img.shields.io/badge/Looker%20Studio-4285F4?style=for-the-badge&logo=looker&logoColor=white)

<a name="refs"></a>
## 📋 Credits

- This Project is inspired by this video of the [YouTube Channel Darshil Parmar](https://www.youtube.com/watch?v=0iNJPKheQqM&t=1304s)

<a name="contact"></a>
## 📨 Contact Me

[LinkedIn](https://www.linkedin.com/in/abderrahmane-chahiri-151b26237/) •
[Website](https://github.com/ChahiriAbderrahmane) •
Gmail: [chahiri.abderrahmane.eng@gmail.com](chahiri.abderrahmane.eng@gmail.com)
