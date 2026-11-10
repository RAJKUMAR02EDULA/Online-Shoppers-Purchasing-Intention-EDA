# 🛒 Online Shoppers Purchasing Intention – EDA Project

## 📌 Project Overview

This project focuses on Exploratory Data Analysis (EDA) of online shopping customer behavior to understand the factors influencing purchasing decisions.

The analysis uses Python to explore customer browsing patterns, website engagement, visitor types, and purchasing behavior.

The main objective is to identify patterns and relationships between customer activities and purchase outcomes, helping businesses improve customer engagement and conversion rates.

## 🎯 Project Objectives

- Understand online shopping customer behavior.
- Analyze purchasing and non-purchasing sessions.
- Identify factors associated with purchasing decisions.
- Analyze visitor types and browsing patterns.
- Examine website engagement metrics.
- Identify relationships between numerical variables.
- Generate meaningful business insights through data visualization.

## 🛠️ Technologies & Libraries Used

| Technology | Purpose |
|---|---|
| Python | Data analysis |
| Jupyter Notebook | Development environment |
| Pandas | Data manipulation |
| NumPy | Numerical operations |
| Matplotlib | Data visualization |
| Seaborn | Statistical visualization |

## 📂 Project Structure

```text
EDA-PROJECT/
│
├── EDA CSV/
│   └── online_shoppers_intention.csv
│
├── PPT/
│   └── Online_Shoppers_EDA_Project.pptx
│
├── project code/
│   └── eda_project.ipynb
│
└── README.md
```

## 📊 Dataset Information

The project uses the Online Shoppers Purchasing Intention dataset.

| Dataset Details | Value |
|---|---|
| Total Records | 12,330 |
| Total Columns | 18 |
| Duplicate Records | 125 |
| Records After Cleaning | 12,205 |
| Missing Values | 0 |
| Target Variable | Revenue |

### Dataset Features

- Administrative
- Administrative_Duration
- Informational
- Informational_Duration
- ProductRelated
- ProductRelated_Duration
- BounceRates
- ExitRates
- PageValues
- SpecialDay
- Month
- OperatingSystems
- Browser
- Region
- TrafficType
- VisitorType
- Weekend
- Revenue

## 🔍 Data Analysis Process

### 1. Data Loading and Exploration
- Imported the dataset using Pandas.
- Examined the first and last records.
- Checked dataset shape and column names.
- Analyzed data types and statistical summaries.

### 2. Data Cleaning
- Checked missing values.
- Identified duplicate records.
- Removed 125 duplicate records.
- Standardized column names.
- Retained all valid observations.

### 3. Outlier Detection
- Used boxplots to identify outliers.
- Examined numerical variables.
- Applied the IQR approach for outlier detection.
- Retained potentially meaningful extreme observations.

### 4. Univariate Analysis
- Analyzed individual numerical variables.
- Examined categorical variable distributions.
- Studied purchasing and non-purchasing sessions.
- Visualized visitor types and monthly distributions.

### 5. Bivariate Analysis
- Compared Page Value with Revenue.
- Analyzed Product Related Pages against Revenue.
- Examined browsing duration and purchasing outcomes.
- Compared Bounce Rate and Exit Rate across purchase groups.

### 6. Multivariate Analysis
- Created correlation heatmaps.
- Examined relationships between numerical variables.
- Analyzed visitor type and purchasing behavior.
- Compared Page Value across multiple customer segments.

### 7. Pivot Table Analysis
- Analyzed Page Value by visitor type.
- Compared monthly Page Value.
- Examined revenue-based differences.
- Calculated monthly purchase rates by visitor type.

## 📈 Visualizations Created

- Bar Charts
- Histograms
- Boxplots
- Count Plots
- Scatter Plots
- Correlation Heatmaps
- Pivot Table Analysis

## 💡 Key Business Insights

1. Approximately 84.37% of shopping sessions did not result in a purchase.
2. Approximately 15.63% of sessions resulted in a purchase.
3. Revenue-generating sessions generally have higher Page Value.
4. Customers visiting more product-related pages tend to show stronger purchasing intent.
5. Revenue-generating sessions generally show lower Bounce Rates and Exit Rates.
6. Returning Visitors represent the largest visitor group.
7. Purchasing behavior varies across different months and visitor types.
8. Higher Page Values are generally associated with lower Bounce Rates and Exit Rates.

## 📌 Business Recommendations

- Improve website navigation and user experience.
- Optimize product pages to encourage conversions.
- Develop personalized offers for returning visitors.
- Reduce bounce rates through better website engagement.
- Identify high-intent visitors and improve conversion strategies.
- Analyze monthly purchasing trends to optimize marketing campaigns.

## 🚀 How to Run the Project

### Step 1: Clone the Repository

```bash
git clone https://github.com/your-username/EDA-PROJECT.git
```

### Step 2: Install Required Libraries

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### Step 3: Open Jupyter Notebook

```bash
jupyter notebook
```

### Step 4: Run the Project

1. Open `eda_project.ipynb`.
2. Keep the CSV dataset in the correct folder.
3. Update the dataset path if required.
4. Execute the notebook cells sequentially.
5. Explore the visualizations and findings.

## 🎓 Skills Demonstrated

- Python Programming
- Data Cleaning
- Exploratory Data Analysis (EDA)
- Data Manipulation
- Statistical Analysis
- Data Visualization
- Correlation Analysis
- Customer Behavior Analysis
- Business Insight Generation

## 👨‍💻 Author

**Raj Kumar**

Aspiring Data Analyst

**Technical Skills:** Python | SQL | Excel | Power BI | MySQL | Pandas | NumPy

## 🏁 Conclusion

This project demonstrates how Python-based Exploratory Data Analysis can help understand online shopping behavior and identify patterns associated with purchasing decisions.

Through data cleaning, statistical exploration, visualization, and business interpretation, the project provides valuable insights into customer engagement and online purchasing intention.

---

⭐ If you find this project useful, please consider giving this repository a star!
