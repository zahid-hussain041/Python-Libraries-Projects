# 📊 Data Analysis & Visualization Projects

This repository contains two Python-based data analysis projects developed using **Pandas, NumPy, Matplotlib, and Seaborn**.

The projects focus on data cleaning, statistical analysis, data exploration, and visualization using real-world datasets.

---

## 📁 Projects

### 1. 🦠 COVID-19 Data Analysis

This project analyzes country-wise COVID-19 data to understand the spread, deaths, recoveries, and active cases across different countries and WHO regions.

#### Dataset

**Country-wise COVID-19 Dataset**

#### Main Tasks

* Load and explore the dataset
* Check dataset shape and columns
* Analyze missing values
* Detect and remove duplicate records
* Perform statistical analysis
* Analyze WHO regions
* Find top 10 countries by:

  * Confirmed cases
  * Deaths
  * Active cases
* Calculate COVID-19 statistics by WHO region
* Perform correlation analysis
* Create a correlation heatmap
* Analyze relationships between:

  * Confirmed Cases vs Deaths
  * Confirmed Cases vs Recovered Cases
* Analyze the distribution of:

  * Confirmed cases
  * Deaths
* Calculate:

  * Total confirmed cases
  * Total deaths
  * Total recovered cases
  * Total active cases
  * Overall recovery rate
  * Overall death rate
* Save the cleaned dataset

#### Visualizations

The project includes:

* Bar charts
* Seaborn bar plots
* Scatter plots
* Histograms
* Correlation heatmap
* WHO region analysis

---

### 2. 🛒 E-Commerce / Orders Data Analysis

This project analyzes an orders dataset to understand customer orders, geographical distribution, and order trends over time.

#### Dataset

**List of Orders.csv**

#### Main Tasks

* Load and explore the dataset
* Check shape, columns, and data types
* Check missing values
* Clean invalid records
* Convert Order Date into datetime format
* Create new columns:

  * Year
  * Month
  * Month Name
  * Quarter
* Generate a complete dataset summary
* Calculate statistical measures using NumPy
* Analyze orders by:

  * State
  * City
  * Customer
  * Year
  * Month
  * Quarter
* Find top 10 states by orders
* Find top 10 cities by orders
* Find top 10 customers by orders
* Analyze monthly order trends
* Analyze quarterly orders
* Analyze yearly orders
* Save the cleaned dataset

#### Visualizations

The project includes:

* Horizontal bar charts
* Monthly line chart
* Quarterly bar chart
* Yearly bar chart

---

# 🛠️ Technologies Used

| Technology | Purpose                                |
| ---------- | -------------------------------------- |
| Python     | Programming language                   |
| Pandas     | Data cleaning and analysis             |
| NumPy      | Numerical and statistical calculations |
| Matplotlib | Data visualization                     |
| Seaborn    | Statistical visualization              |

---

# 📂 Repository Structure

```text
Data-Analysis-Projects/
│
├── README.md
│
├── COVID-19-Analysis/
│   ├── country_wise_latest.csv
│   ├── covid_analysis.py
│   └── cleaned_country_wise_latest.csv
│
├── Orders-Analysis/
│   ├── List of Orders.csv
│   ├── orders_analysis.py
│   └── cleaned_list_Of_orders.csv
│
└── screenshots/
    ├── covid/
    └── orders/
```

---

# 🔄 Data Analysis Workflow

Both projects follow a similar data analysis workflow:

```text
Dataset
   ↓
Load Data
   ↓
Explore Data
   ↓
Check Missing Values
   ↓
Check Duplicates
   ↓
Data Cleaning
   ↓
Statistical Analysis
   ↓
Grouping & Aggregation
   ↓
Data Visualization
   ↓
Generate Results
   ↓
Save Cleaned Dataset
```

---

# 📈 Key Concepts Demonstrated

### Data Cleaning

* Missing-value detection
* Duplicate detection
* Removing unnecessary records
* Date conversion
* Creating new columns

### Data Analysis

* `groupby()`
* `value_counts()`
* `sort_values()`
* `describe()`
* `nunique()`
* `resample()`
* Statistical calculations

### NumPy

* Mean
* Median
* Minimum
* Maximum
* Standard deviation

### Matplotlib

* Bar charts
* Horizontal bar charts
* Line charts
* Figure customization
* Labels and titles

### Seaborn

* Bar plots
* Scatter plots
* Histograms
* Heatmaps
* Correlation visualization

---

# 🎯 Project Objectives

The main objective of these projects is to practice and demonstrate practical **Data Analysis and Data Visualization** skills using Python.

These projects help in understanding how raw datasets can be:

1. Loaded
2. Cleaned
3. Processed
4. Analyzed
5. Visualized
6. Converted into meaningful information

---

# 🚀 How to Run

## 1. Clone the Repository

```bash
git clone https://github.com/your-username/Data-Analysis-Projects.git
```

## 2. Open the Project

```bash
cd Data-Analysis-Projects
```

## 3. Install Required Libraries

```bash
pip install pandas numpy matplotlib seaborn
```

## 4. Run the Python Files

For COVID-19 analysis:

```bash
python covid_analysis.py
```

For Orders analysis:

```bash
python orders_analysis.py
```

You can also run the projects using **Jupyter Notebook** or **VS Code**.

---

# 📊 Project Results

### COVID-19 Analysis

The project provides insights into:

* Countries with the highest confirmed cases
* Countries with the highest deaths
* Countries with the highest active cases
* WHO region-wise case distribution
* Relationships between confirmed, recovered, and death cases
* Overall recovery and death rates

### Orders Analysis

The project provides insights into:

* Total number of orders
* Number of customers
* Number of states and cities
* Top-performing states
* Top-performing cities
* Top customers by number of orders
* Monthly order trends
* Quarterly order distribution
* Yearly order trends

---

# 👨‍💻 Author

**Zahid Hussain Hulio**

BS Artificial Intelligence Student

---

# ⭐ Future Improvements

Future versions of these projects can include:

* Interactive dashboards
* Power BI integration
* Streamlit web applications
* More advanced statistical analysis
* Machine Learning models
* Interactive charts
* Automated data reports

---

## 📌 Skills Demonstrated

**Python | Pandas | NumPy | Matplotlib | Seaborn | Data Cleaning | Data Analysis | Data Visualization | Exploratory Data Analysis (EDA)**
