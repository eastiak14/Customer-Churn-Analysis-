# Customer Churn Analysis

**A Data Analysis Project Using Python**

## 1. Project Overview

Customer churn is an important challenge for businesses, especially in the telecommunications industry. Losing existing customers can affect business revenue and long-term growth.

This project analyzes customer churn patterns using two datasets, `Client.csv` and `Record.csv`. The datasets are merged using a common customer ID to perform exploratory data analysis, data visualization, and statistical analysis.

The main goal is to identify customer groups associated with higher churn rates and provide useful business recommendations.

## 2. Project Objectives

- Analyze customer churn distribution.
- Identify missing values and understand data quality.
- Explore customer behavior and usage patterns.
- Analyze churn across equipment age, revenue, and customer tenure.
- Perform statistical tests to examine associations with churn.
- Develop data-driven business recommendations.

## 3. Dataset Description

The project uses two datasets:

| Dataset | Description |
|---|---|
| Client.csv | Customer demographic and service information |
| Record.csv | Customer usage, revenue, and churn information |

**Dataset Summary:**
- Client Dataset: 100,000 records
- Record Dataset: 100,000 records
- Common Key: `Customer_ID`
- Merged Dataset: 100,000 rows and 100 columns

## 4. Tools and Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy
- Jupyter Notebook
- Visual Studio Code

## 5. Project Workflow

1. Data Loading
2. Data Inspection
3. Data Cleaning and Missing Value Analysis
4. Dataset Merging
5. Exploratory Data Analysis (EDA)
6. Data Visualization
7. Customer Churn Analysis
8. Statistical Analysis
9. Business Recommendations

## 6. Exploratory Data Analysis

The analysis includes:

- Customer churn distribution
- Missing value analysis
- Customer usage patterns
- Customer care interactions
- Customer tenure analysis
- Revenue group analysis
- Equipment age analysis
- Demographic analysis

## 7. Statistical Analysis

The following statistical techniques were applied:

- Chi-Square Test of Independence
- Cramér's V Association Strength
- Correlation Analysis

### Comparative Statistical Results

| Factor | Chi-Square | Cramér's V |
|---|---:|---:|
| Equipment Age | 1099.3107 | 0.1048 |
| Revenue Group | 141.8787 | 0.0377 |
| Customer Tenure | 223.4121 | 0.0473 |

All three factors showed statistically significant associations with customer churn (p < 0.05).

However, their association strengths were relatively weak.

## 8. Key Findings

1. **Equipment Age:** Customers using equipment older than two years have the highest churn rate (57.89%).

2. **Revenue Group:** Low-revenue customers have the highest churn rate (52.65%).

3. **Customer Tenure:** Customers with 13–24 months of tenure have the highest churn rate (51.78%).

4. **Usage Pattern:** Customers with slight usage decreases show a churn rate of 55.53%.

5. **Customer Care:** Customers with low customer-care interactions have a higher churn rate (51.23%) than those with high interactions (44.66%).

6. **Statistical Association:** Equipment Age has the strongest association with churn among the three statistically tested factors.

## 9. Business Recommendations

- **Equipment Upgrade:** Encourage customers using older equipment to upgrade their devices.
- **Affordable Packages:** Introduce suitable packages for low-revenue customers.
- **Customer Retention:** Develop targeted retention campaigns for customers with 13–24 months of tenure.
- **Customer Monitoring:** Regularly monitor customer usage patterns and service interactions.
- **Data-Driven Decisions:** Use customer data and predictive analytics to identify potential churn risks.

## 10. Project Structure

```text
GCI Final Assignment/
│
├── data/
│   ├── Client.csv
│   └── Record.csv
│
├── notebooks/
│   ├── final_analysis.ipynb
│   └── final_analysis.html
│
├── outputs/
│   ├── figures/
│   └── results/
│
├── reports/
│   └── final_analysis.pdf
│
├── requirements.txt
└── README.md
```

## 11. Installation and Usage

### Step 1: Clone the Repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

### Step 2: Navigate to the Project Folder

```bash
cd GCI-Final-Assignment
```

### Step 3: Install Dependencies

```bash
pip install -r requirements.txt
```

### Step 4: Open Jupyter Notebook

```bash
jupyter notebook
```

Open `notebooks/final_analysis.ipynb` and run the notebook cells.

## 12. Project Outputs

The project generates:

- Five analytical visualizations.
- Five CSV analysis result files.
- An interactive Jupyter Notebook.
- An HTML version of the analysis.
- A PDF report.

## 13. Conclusion

This project demonstrates how exploratory data analysis and statistical techniques can be used to understand customer churn patterns.

The findings indicate that equipment age, revenue group, customer tenure, and usage patterns are associated with customer churn.

These insights can help businesses identify potentially high-risk customer segments and develop more effective customer retention strategies.

Statistical association does not necessarily imply causation. Further predictive modeling would be required to investigate churn risk and its underlying factors.

---

**Project:** Customer Churn Analysis  
**Language:** Python  
**Project Type:** Exploratory Data Analysis and Statistical Analysis