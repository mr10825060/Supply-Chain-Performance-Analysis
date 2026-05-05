#  Supply Chain Delivery Performance Analysis

##  Summary
A data science project that analyzes global e-commerce delivery operations to identify causes of late deliveries and build a predictive model for shipment delay prediction.

---

##  Overview
This project focuses on analysing end-to-end supply chain and order fulfillment performance for a global e-commerce company. The goal is to understand why more than half of the orders are delivered late and to develop data-driven solutions for improving delivery efficiency, customer satisfaction, and profitability.

The analysis covers **172,765 orders** across multiple regions from **2015 to 2018**.

---

##  Problem Statement
The company is facing a major issue where a large percentage of orders are not delivered within the promised time. This is leading to:
- Poor customer experience  
- Loss of trust  
- Financial risk in terms of profit loss  
- Inefficient supply chain operations  

The objective is to:
- Identify root causes of late deliveries  
- Measure business impact  
- Build a predictive model for late delivery risk  

---

## Dataset
- Total Records: 172,765 orders  
- Time Period: January 2015 – January 2018  
- Key Features:
  - Shipping Mode  
  - Order Region  
  - Customer Segment  
  - Department Name  
  - Order Category  
  - Scheduled shipment days  
  - Order time features  
  - Delivery status (on-time / late)

---

## Tools and Technologies
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  
- Imbalanced-learn (SMOTE)  
- Jupyter Notebook  

---

## Methods
- Data Cleaning and Preprocessing  
- Exploratory Data Analysis (EDA)  
- Feature Engineering (time-based features, encoding)  
- Data Visualization for pattern detection  
- Handling class imbalance using SMOTE  
- Machine Learning using Random Forest Classifier  
- Model Evaluation (Accuracy, Precision, Recall, F1-score)

---

##  Key Insights
- **54.71% of orders are delivered late**
- First Class shipping shows extremely high delay rates
- Delay issue is **system-wide**, not region-specific
- Seasonal spikes occur in **August, September, and December**
- Payment processing delays contribute significantly to late deliveries
- Certain departments (Outdoors, Golf) have higher delay rates
- Estimated **$2.1M profit is at risk due to delays**

---

##  Dashboard / Model / Output
- Interactive analysis of delay distribution across:
  - Shipping Mode  
  - Region  
  - Customer Segment  
  - Department  
  - Time (month, hour, day)

### Machine Learning Model:
- **Random Forest Classifier**
- Accuracy: **74%**
- Precision (Late Orders): **78%**
- Built to predict high-risk orders before shipment

---

## ▶️ How to Run This Project

### Step 1: Clone the repository
```bash

2. Install the required libraries

```bash
pip install pandas numpy matplotlib seaborn scikit-learn imbalanced-learn jupyter
```

3. Open Jupyter Notebook

```bash
jupyter notebook
```

4. Open the notebook file:

```bash
Supply_Chain_analysis.ipynb
```

5. Run all cells sequentially to reproduce the analysis, visualizations, and machine learning model results.

