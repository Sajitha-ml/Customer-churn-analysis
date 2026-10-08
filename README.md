# Customer-churn-analysis
# Customer Churn Data Visualization & Storytelling

## 📌 Project Overview

This project focuses on analyzing and visualizing customer churn data using Python to identify patterns, trends, and factors associated with customer attrition.

The goal is to transform raw customer data into meaningful visual insights that can be easily understood by both technical and non-technical stakeholders.

The project uses **Python, Pandas, Matplotlib, and Seaborn** to perform exploratory analysis and create business-focused visualizations.

---

## 🎯 Objectives

The main objectives of this project are:

* Analyze customer churn patterns.
* Identify customer groups with higher churn rates.
* Compare churn across different customer attributes.
* Create clear and meaningful visualizations.
* Use data storytelling to communicate important business insights.
* Identify potential factors that may contribute to customer churn.
* Present findings in a format suitable for business decision-making.

---

## 🛠️ Technologies Used

| Technology       | Purpose                         |
| ---------------- | ------------------------------- |
| Python           | Data analysis and visualization |
| Pandas           | Data manipulation and analysis  |
| NumPy            | Numerical operations            |
| Matplotlib       | Data visualization              |
| Seaborn          | Statistical visualization       |
| VS Code          | Development and analysis        |

---

## 📂 Dataset

The project uses a customer churn dataset containing customer demographic, service,tenure,contract, billing, support, satisfaction, and churn information.

### Key Features

* Customer ID
* Gender
* Age
* Tenure
* Contract Type
* Payment Method
* Monthly Charges
* Total Charges
* Internet Service
* Tech Support
* Streaming Service
* Number of Complaints
* Support Calls
* Last Login
* Satisfaction Score
* Churn

The target variable is:

**Churn**

* `0` → Customer retained
* `1` → Customer churned

---

## 🔍 Data Preparation

Before visualization, the dataset was checked and prepared for analysis.

The preprocessing steps included:

1. Loading the raw dataset.
2. Inspecting the dataset structure.
3. Checking data types.
4. Identifying missing values.
5. Handling missing values.
6. Checking for duplicate records.
7. Validating numerical ranges.
8. Preparing categorical and numerical variables for analysis.
9. Creating meaningful groups and categories for visualization.

---

## 📊 Exploratory Data Analysis

The analysis explores customer churn from multiple perspectives.

### Overall Churn

The overall churn rate was analyzed to understand the proportion of customers who left the service.

### Contract Type

Churn was compared across:

* Month-to-Month
* One Year
* Two Year

Customers with **Month-to-Month contracts** showed a substantially higher churn rate compared with customers on longer-term contracts.

### Tenure

Customers were grouped according to their tenure:

* 0–12 months
* 13–24 months
* 25–48 months
* 49+ months

The analysis showed that **newer customers have a higher likelihood of churn**, while customers with longer tenure tend to be more stable.

### Customer Complaints

Customers were grouped based on the number of complaints.

Higher complaint levels were associated with increased churn, indicating that unresolved customer issues can be an important warning signal.

### Support Calls

The relationship between support calls and churn was also examined.

Customers making frequent support calls showed higher churn rates than customers requiring little or no support.

### Satisfaction Score

Customer satisfaction was analyzed to understand its relationship with churn.

Customers with lower satisfaction levels demonstrated significantly higher churn rates.

### Last Login Activity

Customers were categorized based on the number of days since their last login.

Longer periods of inactivity were associated with increased churn, making inactivity a useful potential indicator of customer disengagement.

### Monthly Charges

Monthly charges were grouped into meaningful ranges to investigate whether pricing levels were associated with churn.

Higher monthly charges showed higher churn rates in the analysis.

---

## 📈 Visualizations

The project includes multiple visualization techniques to communicate the findings effectively.

Examples include:

* Bar charts
* Donut chart
* Heat map
* Count plots
* Churn-rate comparisons
* Distribution plots
* Category-based comparisons
* Relationship visualizations
* Percentage-based charts
* Business-focused visual storytelling

The visualizations were designed to highlight the most important patterns rather than simply display raw numbers.

---

## 💡 Key Insights

The analysis identified several important churn patterns:

### 1. Contract Type Matters

Customers on **Month-to-Month contracts** have a significantly higher churn rate than customers with one-year or two-year contracts.

### 2. Early-Tenure Customers Are More Vulnerable

Customers within their first year showed considerably higher churn than long-term customers.

### 3. Complaints Are a Strong Warning Signal

Customers with a higher number of complaints had substantially higher churn rates.

### 4. Customer Satisfaction Is Important

Lower satisfaction scores were associated with significantly higher churn.

### 5. Frequent Support Calls Indicate Risk

Customers who frequently contact support may be experiencing unresolved service problems and therefore represent a higher churn-risk group.

### 6. Customer Inactivity Can Indicate Disengagement

Customers who had not logged in for longer periods showed increased churn rates.

### 7. Multiple Factors Should Be Considered Together

Churn is not driven by a single factor. Contract type, tenure, satisfaction, complaints, support interactions, pricing, and customer engagement can collectively provide stronger signals of customer risk.

---

## 📖 Business Story

The visual analysis tells a clear customer-retention story:

> **Customers who are new, dissatisfied, frequently contact support, submit more complaints, and remain on flexible month-to-month contracts are more likely to churn.**

This suggests that businesses should focus retention efforts on customers showing multiple warning signals rather than treating every customer equally.

---

## 🚀 Business Recommendations

Based on the analysis, the following strategies could help reduce churn:

### Improve Early Customer Engagement

Provide additional onboarding and support during the first 12 months of the customer relationship.

### Encourage Long-Term Contracts

Offer incentives or benefits to customers who move from month-to-month contracts to longer-term plans.

### Monitor Customer Complaints

Create an early-warning system for customers with repeated complaints.

### Improve Customer Support

Identify customers with frequent support interactions and proactively investigate their issues.

### Focus on Customer Satisfaction

Conduct targeted surveys and provide personalized retention offers to dissatisfied customers.

### Monitor Customer Inactivity

Customers who have not logged in for an extended period can be contacted with personalized engagement campaigns.

### Build a Churn-Risk Monitoring System

Combine multiple behavioral indicators to identify customers who may be at risk of leaving.

---

## 📁 Project Structure

```text
Customer-Churn-Visualization/
│
├── data/
│   └── customer_churn_data.csv
│
├── notebooks/
│   └── customer_churn_visualization.ipynb
│
├── visualizations/
│   ├── churn_by_contract.png
│   ├── churn_by_tenure.png
│   ├── churn_by_satisfaction.png
│   ├── churn_by_complaints.png
│   ├── churn_by_support_calls.png
│   └── churn_by_last_login.png
│
├── reports/
│   └── Customer_Churn_Visualization_Report.docx
│
├── requirements.txt
│
└── README.md


## 📦 Requirements

The main Python libraries used in this project are:

```text
pandas
numpy
matplotlib
seaborn
vs code
```

---

## 📌 Project Outcome

This project demonstrates the ability to:

* Perform exploratory data analysis.
* Clean and prepare real-world-style data.
* Analyze categorical and numerical variables.
* Calculate and compare churn rates.
* Create effective business visualizations.
* Identify meaningful customer segments.
* Communicate analytical findings through data storytelling.
* Translate data insights into actionable business recommendations.

---

## 👩‍💻 Author

**Sajitha S**

---

## ⭐ If You Find This Project Useful

Feel free to explore the repository, review the analysis, and use the project as a reference for customer churn analytics and data visualization.
