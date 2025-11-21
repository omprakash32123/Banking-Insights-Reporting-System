# Banking Reporting & Insights Dashboard
  The banking sector produces large volumes of financial and customer-related data every day. To make better decisions, banks require clear insights on customer behaviours, transaction patterns, loan performance, and risk factors.
# **Project Overview**
  A dashboard helps in monitoring this information in real time. This project, Banking Reporting & Insights Dashboard, focuses on creating an interactive dashboard using a sample banking dataset. The dashboard shows key metrics such as total customers, average transactions, loan summary, account distribution, and credit-risk patterns. It allows a bank manager or analyst to instantly understand business performance without manually calculating anything.The project mainly concentrates on data cleaning, data analysis and dashboard creation, without using any machine learning models.

# Objectives of the Project

•	To collect and prepare a banking dataset for reporting.

•	To perform data cleaning such as handling missing values and duplicates.

•	To analyse customer and transaction data for important insights.

•	To design a simple and professional dashboard that is easy to understand.

•	To help banking staff take decisions using visual insights.

*This project contains **two datasets**:

1. **Uncleaned Dataset** – raw data with missing values, wrong formats, duplicates, spelling errors, and out-of-range values.
2. **Cleaned Dataset** – fully processed and ready for dashboard creation.

The dashboard helps in understanding customer behaviour, balance patterns, and transaction activities.

---

## **📂 Included Files**

| File Name                           | Description                                      |
| ----------------------------------- | ------------------------------------------------ |
| `uncleaned_banking_data.csv`      | Raw dataset containing uncleaned banking records |
| `banking_dataset_clean.xlsx`        | Cleaned and organised dataset for dashboard      |
| Dashboard file (`.pbix`)            | Power BI / Excel dashboard showing insights      |
| README.md                           | Documentation of the entire project              |

---

## **📑 Dataset Description**

Both datasets include the following fields:

### **Customer Details**

* UserID
* Name
* Gender
* Age (25–45 in cleaned dataset)
* Region (Indian cities)

### **Account Details**

* Bank Account Number (10 digits)
* Account Type (Savings / Current)
* Account Balance
* Account Opening Date

### **Transaction Details**

* Transaction ID
* Transaction Date
* Transaction Type (Deposit / Withdrawal / Transfer / Online Payment)
* Transaction Amount
* Transaction Channel (ATM / Online / Branch)

## **Data Cleaning Performed (for Cleaned Dataset)**

✔ Age corrected to 25–45

✔ Region missing values replaced with “Unknown”

✔ Account Type standardised

✔ Negative balances fixed

✔ Missing balances filled

✔ Transaction Type formatted

✔ Wrong or blank transaction channels cleaned

✔ Duplicate rows removed

✔ Transaction amount corrected (negative → zero)

✔ Date formats fixed

## **📈 Dashboard Features**

The dashboard includes:

### **Key Performance Indicators (KPIs)**

* Total Customers
* Total Balance
* Average Balance
* Total Transactions
* Deposit vs Withdrawal summary

### **Visual Charts**

* **Pie Chart** – Account Type Distribution
* **Bar Chart** – Transaction Type Count
* **Line Chart** – Monthly Transaction Trends
* **Table View** – Top 10 customers by balance
* **Region Map (optional)** – Users by region

### **Filters**

* Account Type
* Region
* Transaction Type
* Date

## **🛠 Tools Used**

* **Microsoft Excel** – Data cleaning
* **Power BI** – Dashboard creation (or Excel dashboard)
* **Python (optional)** – For generating the dataset

## **📚 Future Enhancements**

*Real-time transaction monitoring.

*High-value transaction alerts inside dashboard.

*Monthly/Yearly transaction trend forecasting.

*Customer transaction behaviour analysis.
 
*Segmentation of transactions.

*Channel performance insights.

## **👤 Author**

3 **OMPRAKASH V**
# **Software Engineer** & **Data Analyist** 
