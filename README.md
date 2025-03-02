# 📊 MSME Growth, Contribution & Financial Challenges in India

## 📌 Project Overview
This Power BI and Power Query project provides an in-depth analysis of **MSME (Micro, Small, and Medium Enterprises) Growth, Contribution, and Financial Challenges in India**. The study explores MSME formalization, female entrepreneurship, manufacturing sector insights, employment trends, GDP contribution, and financial gaps.

## 📁 Data Sources  
- **[Udyam Registration Portal](https://udyamregistration.gov.in/Government-India/Ministry-MSME-registration.htm)**
- **[MSME Dashboard (Ministry of MSME)](https://dashboard.msme.gov.in/dashboard.aspx)**
- **[MSME Finance Gap ](https://www.smefinanceforum.org/data-sites/msme-finance-gap)**
- Government Reports & Economic Surveys
- World Bank
- Industry Research on MSME Financial Gaps  


### 🔍 Key Areas of Analysis  
- **📈 MSME Formalization:** Growth in **Udyam Registrations** and digital inclusion.  
- **👩‍💼 Women Entrepreneurs:** Role of female-led businesses in MSME development.  
- **🏭 Manufacturing Sector:** Contribution of **MSMEs to GDP, employment, and industry**.  
- **🌍 Global MSME Comparison:** How India compares to other countries in **financial inclusion and policy support**.  
- **📊 MSME Financial Gaps:** Identifying funding challenges and access to credit.  


## 🛠️ Technologies Used
- **Power BI** (Data Visualization & Interactive Dashboards)
- **Power Query** (Data Transformation & ETL Processing)
- **Excel / CSV** (Data Storage & Preprocessing)
- **GitHub** (Project Repository & Documentation)

  ## 🔍 Special Use of Power Query  

Power Query played a **crucial role** in this project, enabling efficient **data extraction, transformation, and loading (ETL)** before visualization in Power BI. Given the **large and diverse data sources**, Power Query was instrumental in **cleaning, reshaping, and preparing** the dataset.  

### 📌 Key Functions of Power Query in This Project  

1️⃣ **Extracting Data from Multiple Sources**  
   - Web Data Extraction: Direct connection to government websites such as **Udyam Registration Portal** and **MSME Dashboard**.  
   - PDF Files: Processed reports, research papers, and government documents.  
   - CSV Files: Integrated structured datasets from official sources.  
   - Excel Files: Merged and cleaned Excel-based data for further analysis.  

2️⃣ **Data Transformation Techniques**  
   - **Unpivot Columns**: Converted wide-format data into a **long format** for better analysis.  
   - **Custom Columns**: Created calculated fields for **financial gap analysis, gender-based MSME insights**, and growth trends.  
   - **Merge Queries**: Combined multiple datasets, such as **financial constraints vs. MSME type**, to derive deeper insights.  
   - **Append Queries**: Stacked data from **different years & sources** into a unified dataset.  
   - **Handling Missing Data**: Applied **fill down, replace values, and remove errors** techniques to clean datasets.  

3️⃣ **Loading into Power BI Desktop**  
   - The transformed data was seamlessly **loaded into Power BI Desktop** for creating **interactive dashboards**.  
   - Data model optimization was performed using **relationships between tables**, ensuring a **high-performance report**.  

Power Query's powerful ETL capabilities allowed for **dynamic data integration**, making this project **scalable, automated, and insightful** for MSME analysis. 🚀  


## 📂 Repository Structure
```plaintext
📁 India-MSME-Dynamics
│── 📊 Power BI Dashboards
│── 📜 README.md (Project Documentation)
│── 📈 Data Insights & Reports
│── 📁 Dashboard Images
│── 📄 MSME_Data.csv
```


---

## 🔍 Key Insights & Visualizations

### **1️⃣ Formalisation of MSMEs**
- **Total MSMEs Registered (2020-2025):** 56.62 million
- **Micro:** 31.16 million | **Small:** 0.73 million | **Medium:** 0.068 million
- **Top 5 States with Highest MSME Registration:** Maharashtra, Tamil Nadu, Uttar Pradesh, Rajasthan, Gujarat
- **Women-Owned MSMEs:** 39% (22.07 million)

![Formalisation of MSMEs](https://github.com/pradip-data/India-MSME-Dynamics/blob/4dcc948ee1af91f0a09998473eb1359aacd7cb24/dashboard%20%20images/1.Formalisation%20of%20MSMEs.png)

---

### **2️⃣ Female Entrepreneurial Landscape**
- **Total Female Labor Force:** 141.25 million
- **Top 5 States with Highest Female LFPR:** Chhattisgarh, Sikkim, Himachal Pradesh, Arunachal Pradesh, Meghalaya
- **Financial Condition of Women-Owned MSMEs (2017):**
  - Fully Constrained: 17.22%
  - Partly Constrained: 12.43%
  - Unconstrained: 70.35%
- **Total Financial Gap in Women-Owned MSMEs (2017):** $20.17 billion (0.76% of India's GDP)

![Female Entrepreneurial Landscape](https://github.com/pradip-data/India-MSME-Dynamics/blob/4dcc948ee1af91f0a09998473eb1359aacd7cb24/dashboard%20%20images/2.Female%20Entrepreneurial%20Landscape.png)

---

### **3️⃣ Manufacturing MSMEs Landscape**
- **Total MSME Manufacturing Registrations:** 11 million
- **Employment in Manufacturing MSMEs:** 11 million (30.36% of total manufacturing employment)
- **Top 5 States with Highest MSME Manufacturing Registration:** Maharashtra, Tamil Nadu, Uttar Pradesh, Gujarat, Rajasthan
- **Focus Areas for Growth:** Sectors with the lowest registrations (e.g., Remediation, Petroleum Extraction, Sewerage, etc.)

![Manufacturing MSMEs Landscape](https://github.com/pradip-data/India-MSME-Dynamics/blob/4dcc948ee1af91f0a09998473eb1359aacd7cb24/dashboard%20%20images/3.Manufacturing%20MSMEs%20Landscape.png)

---

### **4️⃣ MSMEs in Focus: Employment, GDP & Beyond**
- **MSME Sector Employment Growth:**
  - 2021-22: 35 million
  - 2022-23: 46 million
  - 2023-24: 97 million
- **MSME Share in India's GDP:**
  - 2017-18: 29.70%
  - 2022-23: 30.10%
- **MSME Exports Contribution:**
  - 2019-20: 49.75% | 2023-24: 45.73%

![MSMEs in Focus - Employment, GDP & Beyond](https://github.com/pradip-data/India-MSME-Dynamics/blob/4dcc948ee1af91f0a09998473eb1359aacd7cb24/dashboard%20%20images/4.MSMEs%20in%20Focus-Employment%20%2CGDP%20%26%20beyond.png)

---

### **5️⃣ Global MSME Financial Footprint**
- **India’s MSME Potential Demand (2015):** $369.52 billion (17.82% of India's GDP)
- **Current Supply:** $139.46 billion (6.73% of GDP)
- **Financial Gap:** $230.54 billion (11.10% of GDP)
- **Micro Industry Financial Gap:** $8.96 billion
- **Small & Medium Industry Financial Gap:** $221.11 billion

![Global MSME Financial Footprint](https://github.com/pradip-data/India-MSME-Dynamics/blob/4dcc948ee1af91f0a09998473eb1359aacd7cb24/dashboard%20%20images/5.Global%20MSMEs%20Financial%20Footprint.png)

---

## 📌 Conclusion & Recommendations
### **1️⃣ Strengthen MSME Formalization & Women Entrepreneurship**
✅ Promote digital registration & support mechanisms for micro and small businesses.
✅ Increase financial literacy programs for women entrepreneurs.
✅ Encourage policies for gender-inclusive growth in MSMEs.

### **2️⃣ Enhance Manufacturing Sector Growth**
✅ Focus on underdeveloped subcategories (e.g., petroleum extraction, sewerage, mining support services).
✅ Provide incentives for high-growth industries like food manufacturing and textiles.

### **3️⃣ Improve MSME Financial Access & Reduce Credit Gap**
✅ Increase financial inclusion programs to bridge the $230.54 billion financial gap.
✅ Strengthen MSME lending initiatives with reduced interest rates and easier access to capital.
✅ Encourage FinTech adoption for alternative lending solutions.

### **4️⃣ Boost MSME Employment & Export Performance**
✅ Develop export-focused MSME clusters.
✅ Support skill development programs for employment generation.
✅ Improve infrastructure & supply chain efficiency to enhance competitiveness.

---

## 🚀 Conclusion & Future Roadmap 🌍  

The **India-MSME-Dynamics** project provides deep insights into the evolving landscape of Micro, Small, and Medium Enterprises (MSMEs), highlighting key trends in formalization, women entrepreneurship, manufacturing growth, and financial accessibility. By leveraging **Power BI** and **Power Query**, this project efficiently integrates data from diverse sources, transforming raw information into actionable insights. Moving forward, strengthening MSME digitalization, improving financial inclusion, and fostering innovation-driven policies will be crucial. With advanced analytics and data-driven strategies, MSMEs can enhance their global competitiveness, bridge financial gaps, and contribute significantly to India's economic growth. The future roadmap focuses on continuous data refinement, deeper industry collaborations, and dynamic policymaking to support sustainable MSME development.  


---



