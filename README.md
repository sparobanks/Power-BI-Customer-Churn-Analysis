# **Customer Churn Analysis — Power BI Dashboard**

This project analyzes customer churn using the IBM Telco Customer Churn dataset.
The goal is to understand **how many customers churn**, **why they churn**, and **the monthly revenue impact** on the business.

This dashboard is built entirely in **Power BI**, supported by Python preprocessing.


## **Dashboard Visuals Included**

### **1. Total Customers**

* Displays the total number of customers in the dataset: **7032**
* Helps understand overall dataset size.



### **2. Gender Breakdown**

A simple distribution of:

* **Female (3549)**
* **Male (3483)**

Although not a key churn driver, it provides demographic context.



### **3. Total Churned Customers**

Shows the number of customers who stopped using the service:

* **1869 churned customers**

This is the basis for calculating churn metrics.


### **4. Churn by Contract Type**

Visual comparing churn across:

* **Month-to-month**
* **One-year**
* **Two-year**

**Insight:**

* Customers on **month-to-month contracts churn the most (1655 customers)**.
* Long-term contracts show significantly lower churn.



### **5. Churn by Payment Method**

Breakdown of churned customers by payment mode:

* Electronic check
* Mailed check
* Bank transfer
* Credit card (automatic)

**Insight:**

* **Electronic check users have the highest churn (1071)**, suggesting frustration or billing issues.



### **6. Total Amount Lost Monthly From Churn Customers**

A financial KPI showing:

* **$139.13K lost monthly**
  due to customers who churn.

This metric shows the **business impact** of churn beyond just customer counts.


## **Key Insights From the Dashboard**

* **Month-to-month customers have the highest churn rate**, showing they are the least committed.
* **Electronic check payment customers churn significantly more**, possibly due to payment reliability or convenience issues.
* Churn is **not driven by gender**.
* Monthly revenue loss from churn is substantial (**$139K per month**), representing a major risk to business performance.



## **Dataset Used**

IBM Telco Customer Churn
(Available on Kaggle)


## **Tools Used**

* **Power BI** – Dashboard & visualisation
* **Python (Pandas, NumPy)** – Data cleaning & preprocessing
* **Jupyter Notebook** – Exploratory analysis
* **CSV** – Cleaned dataset used in Power BI


## **Repository Structure**

```
/customer-churn-analysis
│
├── cleaned_churn_data.csv
│
├── Customer-Churn-Analysis.pdf   (dashboard export)
│
├── churn_analysis.ipynb
│
└── README.md
```


## **Purpose of the Project**

This project demonstrates:

* Data cleaning & preparation
* Exploratory data analysis (EDA)
* Business-focused dashboard creation
* Insight extraction and real-world interpretation
* Revenue impact analysis

Perfect for:

* Portfolio
* Academic coursework
* Data Analyst job applications


## **Author**

**Jasper Chinedu Nwangere**

**Email: sparobanks@gmail.com**

**[LinkedIn](https://www.linkedin.com/in/sparobanks/)**

