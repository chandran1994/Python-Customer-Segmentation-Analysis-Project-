# Customer Segmentation & Customer Analytics for Business Decision-Making

## Project Overview

This project focuses on customer analytics and segmentation using transactional sales data to identify high-value customer groups, understand purchasing behavior, and generate business insights that support marketing, inventory planning, and demand management decisions.

The objective was to move beyond simple sales reporting and develop a structured customer analytics framework capable of answering critical business questions:

* Who are the most valuable customers?
* Which customer groups drive the majority of revenue?
* How does purchasing behavior differ across customer segments?
* Which regions and product categories contribute most to sales?
* How can customer insights support inventory and supply chain decisions?

The project combines Exploratory Data Analysis (EDA), RFM Analysis, Cohort Analysis, and Clustering Algorithms to create a complete customer segmentation workflow.

---

## Project Notebooks

| Notebook                                  | Objective                                                                |
| ----------------------------------------- | ------------------------------------------------------------------------ |
| Exploratory Data Analysis.ipynb           | Analyze customer demographics, purchasing behavior, and sales patterns   |
| Cohort Analysis.ipynb                     | Measure customer retention and repeat purchase behavior over time        |
| RFM Analysis & Clustering Algorithm.ipynb | Segment customers using Recency, Frequency, and Monetary metrics         |
| Clustering Algorithms.ipynb               | Apply unsupervised machine learning techniques for customer segmentation |

---

## View Notebooks

### Exploratory Data Analysis

📓 [View Notebook](https://nbviewer.org/github/chandran1994/Python-Customer-Segmentation-Analysis-Project/blob/main/Exploratory%20Data%20Analysis.ipynb)

### Cohort Analysis

📓 [View Notebook](https://nbviewer.org/github/chandran1994/Python-Customer-Segmentation-Analysis-Project/blob/main/Cohort%20Analysis.ipynb)

### RMF Analysis & Clustering

📓 [View Notebook](https://nbviewer.org/github/chandran1994/Python-Customer-Segmentation-Analysis-Project/blob/main/RMF%20Analysis%20%26%20Clustering%20Algorithm.ipynb)

### Clustering Algorithms

📓 [View Notebook](https://nbviewer.org/github/chandran1994/Python-Customer-Segmentation-Analysis-Project/blob/main/Clustering%20Algorithms.ipynb)


---

# Customer Analytics Workflow

```text
Customer Transaction Data
            ↓
Data Cleaning & Preparation
            ↓
Exploratory Data Analysis
            ↓
Customer Behavior Analysis
            ↓
RFM Analysis
            ↓
Cohort Analysis
            ↓
Customer Clustering
            ↓
Business Recommendations
```

---

## Data Preparation

The project began with data cleaning and preprocessing to ensure analytical accuracy and reliability.

Key preprocessing activities included:

* Missing value treatment
* Duplicate removal
* Data type validation
* Customer-level aggregation
* Revenue calculations
* Feature transformation
* Data quality checks

The cleaned dataset provided a reliable foundation for customer behavior analysis and segmentation.

---

## Exploratory Data Analysis

The first analytical stage focused on understanding customer purchasing patterns across demographic, geographic, and behavioral dimensions.

The analysis examined:

### Customer Demographics

```python
Gender Analysis

Age Group Analysis

Marital Status Analysis

Occupation Analysis
```

### Geographic Analysis

```python
State-Wise Revenue Analysis

Regional Demand Patterns

Customer Distribution Analysis
```

### Product Analysis

```python
Product Category Performance

Revenue Contribution

Purchase Volume Analysis
```

The analysis identified key customer groups responsible for the majority of revenue generation and revealed meaningful differences in purchasing behavior across customer segments.

---

## RFM Analysis

To better understand customer value, RFM (Recency, Frequency, Monetary) Analysis was performed.

Each customer was evaluated based on:

```python
Recency   → How recently the customer purchased

Frequency → How often the customer purchases

Monetary  → How much revenue the customer generates
```

These metrics were used to classify customers into meaningful business segments.

### Customer Segmentation Framework

```text
High Recency
High Frequency
High Monetary
        ↓
Loyal / High-Value Customers

Low Frequency
Low Monetary
        ↓
At-Risk Customers

High Frequency
Moderate Monetary
        ↓
Growth Opportunity Customers
```

RFM analysis provided a structured method for identifying the most profitable customer groups and prioritizing customer retention efforts.

---

## Cohort Analysis

Cohort Analysis was used to evaluate customer retention and repeat purchase behavior over time.

Customers were grouped according to their first purchase period and tracked across subsequent periods to understand retention trends.

### Cohort Framework

```text
Customer Acquisition Month
            ↓
Repeat Purchase Tracking
            ↓
Retention Measurement
            ↓
Cohort Performance Comparison
```

This analysis helped identify:

* Customer retention trends
* Repeat purchase behavior
* Customer lifetime patterns
* Potential churn indicators

The results provided insight into how effectively customers were retained after their initial purchase.

---

## Customer Clustering

The final stage of the project focused on unsupervised machine learning for customer segmentation.

Customer attributes and behavioral metrics were transformed into numerical features suitable for clustering algorithms.

### Machine Learning Pipeline

```text
Feature Selection
        ↓
Feature Scaling
        ↓
Cluster Evaluation
        ↓
Customer Segmentation
        ↓
Business Interpretation
```

### Clustering Techniques Applied

```python
K-Means Clustering

Customer Group Identification

Cluster Profiling

Behavioral Segmentation
```

The resulting clusters revealed distinct customer groups with different purchasing characteristics, spending behaviors, and engagement levels.

---

## Key Business Insights

The analysis identified several high-value customer characteristics:

* Customers generating disproportionate revenue contributions
* Demographic groups with stronger purchasing behavior
* High-performing geographic regions
* Product categories driving demand
* Customer segments with strong retention patterns
* Customer groups suitable for targeted marketing campaigns

These insights can support more effective business and operational decision-making.

---

## Business Value

This project demonstrates how customer analytics can support data-driven decision-making across multiple business functions.

Customer segmentation enables organizations to -

* Improve customer retention
* Optimize marketing spend
* Increase customer lifetime value
* Improve demand visibility
* Support inventory planning
* Enhance regional distribution strategies
* Improve forecasting accuracy
* Prioritize high-value customer groups
