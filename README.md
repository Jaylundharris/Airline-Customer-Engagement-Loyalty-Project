# ✈️ Airline Customer Loyalty & Churn Analysis  
**A complete end-to-end data analytics project analyzing customer satisfaction, loyalty behavior, and churn risk for an airline dataset.**

This project demonstrates real-world data analyst skills including data cleaning, EDA, segmentation, churn risk modeling, correlation analysis, and dashboard creation using **Power BI**, **Python**, and **SQL**.

---

# 📁 Project Structure

📦 airline-loyalty-analysis
├── dashboards/
│ ├── Executive_Overview_dashboard.png
│ ├── Customer_Satisfaction_Breakdown_dashboard.png
│ ├── Churn_Risk_Drivers_dashboard.png
│ ├── Travel_Delay_Insights_dashboard.png
│ └── Churn_Risk_Segmentation_dashboard.png
│
├── data/
│ ├── processed/
│ │ ├── flight_customer.db
│ │ ├── flight_customer.csv
│ │ ├── customer_info_cleaned.csv
│ │ ├── more_customers_cleaned.csv
│ │ └── correlation_matrix.csv
│ └── raw/
│ ├── train.csv
│ └── test.csv
│
├── notebooks/
│ ├── 01_data_exploration.ipynb
│ ├── 02_data_cleaning.ipynb
│ ├── 03_loyalty_segmentation.ipynb
│ ├── 04_satisfaction_drivers.ipynb
│ ├── 05_churn_risk_model.ipynb
│ └── 06_visualizations_dashboard_exports.ipynb
│
├── README.md
└── LICENSE

---

# 🎯 Project Objectives

### **1. Understand Customer Behavior**
Identify satisfaction trends, loyalty patterns, and drivers of dissatisfaction.

### **2. Build a Loyalty & Churn Segmentation Model**
Segment customers using satisfaction and service KPIs into:
- Loyal  
- Neutral  
- Disloyal  

### **3. Identify Key Churn Drivers**
Analyze which service factors (WIFI, food, boarding, seat comfort, delays, etc.) influence churn.

### **4. Create Executive Dashboards in Power BI**
Deliver actionable insights across multiple dashboards:
- Executive Overview  
- Customer Satisfaction Breakdown  
- Churn Risk Drivers  
- Travel & Delay Insights  
- Churn Segmentation  

---

# 🧹 Data Cleaning & Processing

Performed in **Python (Pandas)**.

### Steps Completed
- Removed duplicates  
- Handled missing values  
- Cleaned satisfaction and service rating columns  
- Merged multiple customer datasets  
- Engineered loyalty features  
- Exported data to SQLite and CSV  

Processed data lives in:

/data/processed/

---

# 🔍 Exploratory Data Analysis

Completed in:  
`01_data_exploration.ipynb`  
`02_data_cleaning.ipynb`

### Key Insights
- Female passengers show higher dissatisfaction  
- Personal travel customers are less satisfied than business travelers  
- Eco class passengers consistently score lowest  
- Online boarding, WIFI, and leg room have strong influence on dissatisfaction  
- Larger flight distances correlate with lower dissatisfaction  

---

# 🧠 Loyalty Segmentation

Notebook:  
`03_loyalty_segmentation.ipynb`

### Segments
| Segment | Description |
|--------|-------------|
| **Loyal** | Consistently high satisfaction indicators |
| **Neutral** | Mid-range ratings |
| **Disloyal** | Low ratings and higher service complaints |

These segments are used throughout the dashboards.

---

# 📊 Churn Risk Drivers

Notebook:  
`05_churn_risk_model.ipynb`

### Top Drivers That Increase Churn Risk
- Low online boarding score  
- Low leg room score  
- Low seat comfort  
- Low inflight WIFI  
- High delays (arrival/departure)  
- Being classified as “disloyal”  

Validation through:
- Correlation heatmap  
- Aggregated service metrics  
- Power BI Key Influencers  

---

# 📈 Power BI Dashboards

Dashboards exported as PNGs in `/dashboards`.

### **Executive Overview**
- Total customers  
- Churn rate  
- Loyal vs disloyal %  
- Average flight distance  
- Delay metrics  
- Satisfaction donut chart  

### **Customer Satisfaction Breakdown**
- Satisfaction % by gender  
- Satisfaction % by travel type  
- Satisfaction % by class  

### **Churn Risk Drivers**
- Bar charts of avg service ratings  
- Correlation matrix heatmap  
- Driver comparisons between satisfied vs dissatisfied groups  

### **Travel & Delay Insights**
- Scatter plots of delay vs satisfaction  
- Distance vs dissatisfaction  

### **Churn Risk Segmentation**
- Segmented visualizations across demographic factors  

---

# 🛠 Technologies Used

### Python
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- SQLite3  

### Power BI
- KPI Cards  
- Donut & Bar Charts  
- Matrix with conditional formatting  
- Key Influencers visual  

### SQL
- Data extraction  
- Aggregation  
- Segmentation queries  

---

# 🚀 How to Run

### Clone the repo:
```bash
git clone https://github.com/<your-username>/airline-loyalty-analysis.git
Install dependencies:
bash
Copy code
pip install pandas numpy matplotlib seaborn
Run notebooks:
Follow the order in /notebooks.

Run dashboards:
Open Power BI → Load flight_customer.db or flight_customer.csv.
```
---
# 📬 Contact
Jaylund Harris

Data Analyst — Python | SQL | Power BI

📩 Email: jaylundharris@gmail.com

🔗 LinkedIn: https://www.linkedin.com/in/jaylund-harris-571936384/

💼 GitHub: https://github.com/Jaylundharris

