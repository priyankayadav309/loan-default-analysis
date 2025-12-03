# Loan-Default-Risk-Analysis-Excel-Python-PowerBI

##  Project Title
**Loan Default Risk Analysis**

A data-driven project to identify patterns and customer segments with a higher probability of loan default.

---

##  Overview
This project investigates loan default behavior using Excel, Python, and Power BI.  
The analysis includes descriptive statistics, segmentation, and visual insights to highlight high-risk customer groups.

---

##  Problem Statement
Loan defaults create significant financial risk for lenders.  
This project aims to identify **who is more likely to default** and what factors contribute to higher default rates.

---

##  Dataset
- **loan_default_raw.csv**  
- **loan_default_clean.csv**

Dataset fields include Age, Income, Credit Score, Employment Type, Loan Purpose, and Default Flag.

---

##  Tools & Technologies Used
- **Excel:** Summary statistics, pivot tables  
- **Python:** Pandas, Matplotlib/Seaborn for EDA & visuals  
- **Power BI:** Interactive dashboard with KPIs & charts  

---

##  Methods

### **Excel Analysis**
- MIN, MAX, AVERAGE, COUNT  
- Pivot tables based on:  
  - Category  
  - Credit Score  
  - Age  
  - Income  
  - Employment Type  

### **Python Analysis**
- Imported necessary libraries  
- Loaded dataset  
- Missing value checks  
- Summary statistics  
- Default rate calculation  
- Loan purpose-wise default rate  
- Employment type-wise default rate  
- Credit score bucket creation  
- Income bucket creation  
- Identification of high-risk customers  
- Visuals:  
  - Default distribution  
  - Credit Score Bucket vs Default Rate  

### **Power BI Dashboard**
**KPIs:**
- Total Loans  
- Total Defaults  
- Default Rate (%)  

**Charts:**
- Loan Purpose wise Default Rate %
- Income wise Default Rate % 
- Employment Type wise Default Rate % 
- Age group wise Default Rate % 
- Credit Score wise Default Rate % 

---

##  Key Insights
- Customers with **low credit scores** show the highest chance of default.  
- **Low-income groups** default significantly more.  
- Some **employment types** and **loan purposes** show higher risk patterns.  
- Age groups show varying risk patterns depending on income and credit score.  

---

##  Dashboard / Output
Includes:  
- KPI Cards (Total Loans, Total Defaults, Default %)  
- Visual charts for segment-wise default analysis  

---

##  How to Run This Project
1. Excel Analysis → Review summary stats & pivots
Download Excel file: [Click here](https://drive.google.com/drive/folders/1lR2UASM69c4TbpEw0A4JSUaxtRBplWhi?usp=sharing)  
2. Open Python notebook → Run all cells to reproduce analysis  
3. Open Power BI file → Explore dashboard insights  

---

##  Results & Conclusion
The analysis shows that **loan default risk is concentrated in customers with low credit scores, low income, and certain employment types**.  
Understanding these patterns helps lenders strengthen risk filters and make better loan approval decisions.

---

##  Future Work
- Add a machine learning model for predicting default probability 

---

##  Contact
**Priyanka Yadav**  
Data Analyst  
Email: priyankayadav9822@gmail.com
