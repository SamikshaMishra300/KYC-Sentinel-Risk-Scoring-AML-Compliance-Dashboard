# KYC-Sentinel-Risk-Scoring-AML-Compliance-Dashboard

## 📌 Project Overview  
This project simulates a KYC risk scoring model integrated with an AML risk level analysis dashboard. It classifies customer profiles into High, Medium, and Low risk categories based on demographic, occupational, and adverse screening attributes. The goal is to support compliance teams in proactive risk mitigation.

![1751642168704](https://github.com/user-attachments/assets/eecf25bb-2405-4fbe-ad2f-f904eb0db3f0)

---

## 🎯 Objectives  
- Develop an automated risk scoring formula for customer classification  
- Visualize risk distribution using an interactive Power BI dashboard  
- Identify high-risk customers for Enhanced Due Diligence (EDD) and STR filing  

---

## 🗃 Dataset Details  
- **Rows:** 1000 (simulated data)  
- **Columns:** Customer ID, Province, Age, Occupation, Employment Status, Source of Funds, PEP, Sanctions Watchlist Hit, Adverse Media, Previous STR Filed, Account Type, Monthly Transactions, Risk Score, Risk Level  
- **Source:** Self-created for academic and portfolio demonstration purposes  

---

## ⚙ Methodology  

### Risk Scoring (Excel):  
- +8 → Source of Funds: Crypto, Unknown, Gambling Proceeds  
- +10 → PEP = Yes  
- +5 → Occupation: Crypto Investor, Freelancer, Real Estate Agent, Import/Export Agent  
- +6 → Monthly Transactions > 20,000  
- +3 → Age < 21 or Age > 70  
- +10 → Sanctions Watchlist Hit = Yes  
- +5 → Adverse Media = Yes  
- +7 → Previous STR Filed = Yes  

**Risk Classification:**  
- High, Medium, Low (based on total score thresholds)

---

## 📊 Power BI Dashboard Features  
- KPI Cards: Total Customers, High-Risk Count, STR Filed %  
- Pie Chart: Risk Level Distribution  
- Bar Charts:  
  - Risk Level by Source of Funds  
  - High-Risk Profiles by Province  
- Matrix: Province vs. PEP  
- Scrollable Table: Customer Details  
- Filters: Occupation, Province, Source of Funds, Account Type  

---

## 📌 Key Insights  
- 36 high-risk customers (3.6%)  
- Crypto and Gambling Proceeds were top risk sources  
- Manitoba and British Columbia had highest high-risk profiles  

---

## 💡 Recommendations  
- Conduct EDD for all high-risk customers  
- Monitor medium-risk profiles periodically  
- Automate model for real-time monitoring in compliance systems  

---

## 🛠 Tools Used  
- Microsoft Excel (Nested IF, logic, formatting)  
- Power BI (Data modeling, DAX, visuals)  
- AML & KYC compliance knowledge  
