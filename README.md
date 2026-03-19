📊 Loan Risk Analytics Dashboard



📌 Project Overview



This project focuses on analyzing loan application data to identify approval patterns, customer demographics, and financial risk factors.



The data pipeline is designed end-to-end, starting from raw data ingestion to dashboard visualization:



\- Data sourced from Kaggle

\- Stored in AWS S3

\- Loaded into Snowflake for processing

\- Data cleaning and EDA performed in Snowflake

\- Connected to Power BI for interactive dashboard creation



This project simulates a real-world business use case where stakeholders require insights to improve loan approval decisions and risk assessment.





🎯 Project Objectives



\- Analyze loan approval and rejection trends

\- Identify high-risk customers based on financial attributes

\- Understand customer demographics and behavior

\- Provide insights for better decision-making in loan approvals





🛠️ Tools \& Technologies Used



\- AWS S3 – Data storage

\- Snowflake – Data warehousing \& transformation

\- SQL – Data cleaning \& analysis

\- Power BI – Data visualization \& dashboard creation





🔄 Data Pipeline Architecture



Kaggle Dataset → AWS S3 → Snowflake → Data Cleaning \& EDA → Power BI Dashboard





📊 Dashboard Pages \& Insights



1️⃣ Executive Overview



\- Total Applications: 5000

\- Approved Loans: 1151

\- Rejected Loans: 3849

\- Approval Rate: 23%

\- Avg Loan Amount \& Credit Score analysis

\- Loan distribution by Education, Gender, Employment Type, and City





2️⃣ Customer Demographic Analysis



\- Experience level distribution

\- Income trends by Age Group and Education

\- Applications segmented by Gender and Education

\- Employment type distribution across education levels





3️⃣ Loan Approval Analysis



\- Approval rate by City, Age Group, and Education

\- Approval trends based on Experience

\- Credit score comparison between Approved vs Rejected loans

\- Approval distribution across employment types

\- Loan approval trends across credit score bands





4️⃣ Financial Risk Analysis



\- Loan amount distribution (bins)

\- Loan amount comparison by Education

\- Credit score distribution analysis

\- Risk classification (Low, Moderate, High, Very High)

\- Identification of high-risk customers

\- Relationship between Loan Amount and Approval Status





\## 📸 Dashboard Preview



\### Executive Overview

!\[Overview](images/overview.png)



\### Customer Demographics

!\[Demographics](images/demographics.png)



\### Loan Approval Analysis

!\[Loan Approval](images/loan\_approval.png)



\### Financial Risk Analysis

!\[Risk Analysis](images/risk\_analysis.png)





📁 Project Structure



dataset/           → Raw dataset files  

dax/               → DAX measures used in Power BI  

power bi/          → Power BI (.pbix) file  

images/            → Dashboard screenshots  

documentation/     → Detailed project explanation  

README.md          → Project overview  





🚀 Key Insights



\- Higher credit scores significantly increase loan approval chances

\- Salaried and self-employed individuals have higher approval rates than unemployed

\- Certain cities show higher application volumes and risk levels

\- Lower credit score groups are associated with higher rejection rates

\- Income and experience influence approval probability





▶️ How to Use



1\. Download the Power BI file from the repository

2\. Open using Power BI Desktop

3\. Refresh the dataset (if needed)

4\. Explore different dashboard pages using navigation panel





👤 Author



Hemanth

Aspiring Data Analyst | SQL | Power BI | Snowflake





⭐ If you like this project



Give it a ⭐ on GitHub and feel free to connect!

