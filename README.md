# 📊 Bank Loan Analysis Dashboard — Power BI + SQL

## 🧠 Overview
This project presents an **interactive Power BI dashboard** built to analyze and monitor **bank loan performance data**.  
It delivers comprehensive insights into loan applications, funding, repayments, borrower behavior, and portfolio quality using real-time metrics.

The dashboard provides clarity on **Good vs Bad Loans**, **state-wise loan distribution**, **purpose-based trends**, and **month-over-month performance** — helping financial teams make **data-driven lending decisions**.

---

## 🎯 Objective
The main goals of this project are to:

- Evaluate **loan portfolio health** across multiple dimensions  
- Track key KPIs such as **funded amount**, **received amount**, **DTI**, and **interest rate**  
- Identify **trends, risk areas, and growth opportunities**  
- Provide **interactive filters** for better segmentation (by state, purpose, loan grade, etc.)  
- Enable **data-driven lending and recovery strategies**

---

## ⚙️ Tools & Technologies Used

| Tool | Purpose |
|------|----------|
| 🧩 **Power BI** | Dashboard creation, visualization, and KPI reporting |
| 🧮 **PostgreSQL** | Data storage, management, and validation |
| 🧠 **SQL Queries** | Data transformation, cleaning, and validation logic |
| 📑 **Excel/CSV** | Raw dataset import and preprocessing |

---

## 🧾 Data Validation (PostgreSQL)

Before importing the data into Power BI, all data was **validated using SQL queries** to ensure reliability and accuracy.

### ✅ Key Validation Checks:
- Verified loan status counts (**Fully Paid**, **Charged Off**, **Current**)  
- Matched total **Funded Amount** and **Received Amount** aggregates  
- Validated **month-wise totals** for consistency  
- Cross-checked **interest rate** and **DTI** averages  
- Ensured **state-wise and purpose-wise totals** matched raw data  

---

## 🗂️ Dashboard Pages

### 🧭 1️⃣ Summary Page

**Purpose:**  
Provides a high-level snapshot of the loan portfolio and overall performance.

**Contains:**

#### 📊 KPIs:
- **Total Loan Applications:** 38.6K  
- **Total Funded Amount:** $435.8M  
- **Total Amount Received:** $473.1M  
- **Average Interest Rate:** 12%  
- **Average DTI:** 13.3%  
- **Good Loan Ratio:** 86.2%  
- **Bad Loan Ratio:** 13.8%

**Loan Status Table:** Displays funded, received, and MTD/MOM metrics per status.

![](https://github.com/umar9643/BANK-LOAN-ANALYSIS-SQL-POWER-BI/blob/main/Dashboard_ss/Screenshot%202025-10-31%20223631.png)

---

### 🌍 2️⃣ Overview Page

**Purpose:**  
Provides an analytical view of loan trends and distributions.

**Contains:**
- **Trend Line:** Total Funded Amount by month (steady growth from Jan to Dec)  
- **Map Visualization:** Loans distributed across various states  
- **Bar Charts:**  
  - Total Funded Amount by Employment Length  
  - Total Funded Amount by Purpose  
- **Donut Chart:** Funded Amount by Term (36/60 months)  
- **Treemap:** Funded Amount by Home Ownership  

![](https://github.com/umar9643/BANK-LOAN-ANALYSIS-SQL-POWER-BI/blob/main/Dashboard_ss/Screenshot%202025-10-31%20223654.png)

---

### 📋 3️⃣ Details Page

**Purpose:**  
Displays a complete record of each loan, offering a granular view of the dataset.

**Contains Columns:**
- Loan ID  
- Purpose  
- Home Ownership  
- Grade  
- Issue Date  
- Funded Amount  
- Interest Rate  
- Installment  
- Amount Received  

![](https://github.com/umar9643/BANK-LOAN-ANALYSIS-SQL-POWER-BI/blob/main/Dashboard_ss/Screenshot%202025-10-31%20223709.png)

---

## 🔍 Key Insights & Findings

### 💰 Performance Insights
- **86.2% of all loans** are *Good Loans*, indicating strong repayment behavior.  
- **13.8% Bad Loans** suggest potential default risk but within manageable limits.  
- **Total Funded Amount ($435.8M)** vs **Total Amount Received ($473.1M)** shows a positive cash inflow trend.  
- **Month-over-month growth (~7%)** reflects an expanding loan portfolio.  

### 🏡 Customer Behavior
- Majority of loans are taken for **Debt Consolidation**, followed by **Credit Card** and **Home Improvement**.  
- Borrowers with **10+ years of employment** have the highest funded amount ($116M) — implying strong creditworthiness.  
- **Mortgage holders** receive the largest funding share (~$219M), reflecting secured loan preference.  

### 📈 Financial Metrics
- **Average DTI (13.3%)** indicates healthy debt management among borrowers.  
- **Average Interest Rate (12%)** ensures profitability without excessive risk.  
- **MTD/MOM performance** indicates consistent portfolio growth and interest income.

---

## 🧠 Insights Summary

| Metric | Observation | Business Implication |
|---------|--------------|----------------------|
| Good Loan % | 86.2% | High repayment reliability |
| Bad Loan % | 13.8% | Minor risk, manageable defaults |
| Funded vs Received | Positive Gap ($37.3M) | Indicates timely repayments |
| Employment Length | 10+ years = $116M | Stable income borrowers are ideal |
| Top Loan Purpose | Debt Consolidation | Focused product demand |
| Ownership Type | Mortgage > Rent | Homeowners are low-risk borrowers |

---

## 🧩 Filters & Interactivity
The report provides **dynamic filtering options** for better exploration:

- Purpose  
- Grade  
- State  
- Good vs Bad Loans  
- Select Measure (Funded, Received, Interest, etc.)

---

## 💡 Conclusion & Decision-Making

### 🧾 Conclusion:
This dashboard provides a **data-driven view of a bank’s lending portfolio**, enabling stakeholders to:

- Monitor key lending metrics in real time  
- Detect high-risk loan categories before they escalate  
- Identify profitable loan segments (e.g., debt consolidation, mortgage)  
- Optimize funding strategy based on borrower employment and home ownership data  
- Maintain a balanced loan portfolio by tracking DTI and interest rate trends  

### 🧭 Business Decisions Supported:
- **Risk Management:** Focus on improving recovery for bad loans (13.8%) through targeted interventions.  
- **Customer Segmentation:** Prioritize lending to borrowers with longer employment history and mortgage ownership.  
- **Marketing Focus:** Promote consolidation and credit-related products, which show consistent funding demand.  
- **Performance Monitoring:** Continue expanding in states showing steady growth in loan approvals and repayments.

---

## 🧠 Learnings
- Strengthened **integration between SQL & Power BI** for validated reporting.  
- Gained deeper insights into **financial metrics and loan performance analytics**.  
- Enhanced **data storytelling and dashboard design** for professional presentations.

---

## 👨‍💻 Author

**🧑 Umar Alam**  
📍 *Data Science Enthusiast | Power BI & SQL Developer*  
🔗 [**LinkedIn — Umar Alam**](https://www.linkedin.com/in/umar-alam-a1b2c3)
