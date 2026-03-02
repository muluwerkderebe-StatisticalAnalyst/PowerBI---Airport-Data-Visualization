# ✈️ Airport Authority Data Analysis
**Exploratory Data Analysis (EDA) & Interactive Power BI Dashboard**
By Muluwerk Derebe — *Statistical Analyst & Researcher*

[Muluwerk Derebe-PowerBI Public repository](https://app.powerbi.com/groups/me/reports/01d9caab-dbd1-4cf1-95ab-70d4ed9c3df6/c938a11c1fcf667dd5a8?experience=power-bi)

# 📌 Overview
This project presents a comprehensive Exploratory Data Analysis (EDA) of U.S. airport operations using 2018 flight data. The analysis focuses on flight volume, delays, cancellations, ground processing time, and passenger satisfaction. Insights are delivered through a fully interactive Power BI dashboard, supported by data transformations in Power Query and analytical measures written in DAX.
The goal of this project is to demonstrate strong capabilities in:
* Data modeling and transformation
* Business‑oriented analytical storytelling
* KPI design and performance monitoring
* Power BI dashboard development
* Aviation operations analytics

# 🛠️ Tools & Technologies
* Power BI (Data modeling, DAX, interactive visuals)
* Power Query (ETL, conditional columns, error handling)
* DAX (16+ custom measures for KPIs and performance metrics)
* Excel / CSV (Raw data source)
* Geospatial mapping (Power BI map visuals)
# 📊 Dashboard Pages & Key Insights
## 1. All‑in‑One Overview Dashboard
A consolidated view of:
* Total flights
* Departure & arrival delays
* Cancellations
* Ground processing time
* Passenger satisfaction
* Origin–destination filtering
* Monthly trends
This page acts as the control center for all major KPIs.

## 2. Total Flights (Incoming & Outgoing)
**Highlights include:**
* 7 million total flights in 2018
* Monthly flight distribution
* Top airports by traffic volume
* Comparison of origin vs. destination flows

## 3. Delayed Flights Analysis
Breakdown of delays by:
* Departure vs. arrival delays
* Monthly delay patterns
* Delay causes (Security, Carrier, Late Aircraft, NAS, Weather)
* Total delay minutes (e.g., Late Aircraft: 35M minutes)
This page helps identify operational bottlenecks and seasonal patterns.

## 4. Ground Processing Time (GPT)
* 248 million minutes of total ground processing time
* GPT by carrier
* Monthly GPT trends
* Relationship between GPT and departure delays
This metric is crucial for airport efficiency and turnaround performance.

## 5. Passenger Satisfaction
Passenger feedback distribution:
* Strongly satisfied: 63% (4.6M)
* Satisfied: 16.79% (1.2M)
* Dissatisfied: 18.15% (1.3M)
* Strongly dissatisfied: 1.62% (117K)
Satisfaction is analyzed alongside flight performance indicators.

# 🧩 Data Preparation & Modeling
Power Query Transformations
The dataset includes:
* 34 columns
* more than 7 million rows
* Multiple conditional columns
* Error replacements
* Month extraction
* Filtering and cleaning steps
Example from the document:
“Added Conditional Column… Replaced Errors… Inserted Month…”
“ReplaceErrorValues(#'Added Conditional Column3', {{'DELAY REASON', 'ON‑TIME'}})”

These steps ensured clean, analysis‑ready data.

## DAX Measures (16+)
Custom measures were created for:
* Percent delayed
* Percent canceled
* On‑time performance
* Delay reason classification
* Ground processing KPIs
* Satisfaction segmentation
Example from the dataset:
“Dep‑Delayed flights”, “Arri‑Percent on‑time”, “Delay Reason DAX2”

These measures power the dashboard’s dynamic insights.

📁 Project Structure
📂 Airport-Authority-EDA
│
├── 📊 Power BI Dashboard (.pbix)
├── 📄 Presentation Slides (.pptx)
├── 📁 Data (raw & cleaned)
├── 📜 DAX Measures Documentation
└── README.md



# 🎯 Key Business Questions Answered
* Which airports handle the highest flight volumes?
* What are the major causes of flight delays?
* How do delays vary by month and airport?
* How efficient are carriers in ground processing time?
* How does operational performance influence passenger satisfaction?

# 🚀 Skills Demonstrated
* Advanced Power BI modeling
* DAX for KPI creation
* ETL using Power Query
* Geospatial visualization
* Operational analytics for aviation
* Dashboard storytelling for business decision‑making

# 📬 Contact
**Muluwerk Derebe**
*Data Scientist*
GitHub: muluwerkderebe‑StatisticalAnalyst
