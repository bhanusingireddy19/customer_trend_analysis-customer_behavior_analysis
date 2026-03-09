Customer Behavior Analysis – Developed using Python, PostgreSQL (pgAdmin4), and Power BI to analyze customer purchasing patterns and generate insights.

OVERVIEW:

  This project focuses on analyzing customer shopping behavior to identify purchasing patterns and generate business insights. The dataset was processed using Python for data analysis, SQL for querying structured data, and Power BI for building an interactive dashboard. The goal of this project is to understand customer segments, purchase frequency, and trends that can support data-driven decision making.

DATASET:

The dataset contains information related to customer shopping behavior, including:
1.Customer ID
2.Age and Gender
3.Purchase Frequency
4.Previous Purchases
5.Product Categories
6.Payment Method
7.Purchase Amount

TOOLS AND TECHNOLOGIES:
  The following tools were used in this project:
    Python – Data loading, data cleaning, and Exploratory Data Analysis (EDA)
    Pandas & Matplotlib / Seaborn – Data analysis and visualization
    SQL (PostgreSQL / MySQL / SQL Server) – Data querying and transformation
    Power BI – Interactive dashboard creation
    Jupyter Notebook – Python development environment

PROJECT STEPS:
1. Data Loading:
    Imported the dataset using Python.
    Loaded the dataset into a Pandas DataFrame for analysis.

2. Exploratory Data Analysis (EDA):
    Examined the structure of the dataset.
    Analyzed distributions of customer demographics and purchase behavior.
    Identified trends and patterns in purchasing activity.

3. Data Cleaning:
    Handled missing values.
    Standardized column names.
    Converted categorical values into meaningful formats.
    Removed inconsistencies in the dataset.

4. SQL Analysis:
    Loaded cleaned data into a relational database.
    Executed SQL queries to analyze:
    Customer segmentation
    Purchase frequency
    Total purchases by category
    Customer behavior patterns

5. Dashboard Development:
    Built an interactive Power BI dashboard to visualize insights.
    Created charts and visualizations such as:
    Customer segments
    Purchase frequency analysis
    Category-wise sales
    Demographic insights

DASHBOARD:

The Power BI dashboard provides an interactive view of customer behavior, including:
  Customer segmentation (New, Returning, Loyal customers)
  Purchase frequency trends
  Sales distribution by product category
  Customer demographic insights

RESULTS & INSIGHTS:

Key insights from the analysis include:
  Identification of different customer segments based on purchase history.
  Understanding of purchase frequency patterns.
  Insights into popular product categories.
  Visualization of demographic trends in customer behavior.

 HOW TO RUN PROJECT:
  1.Clone this repository.
  2.Install required Python libraries:
  --pip install pandas numpy matplotlib seaborn
  3.Run the Jupyter Notebook for data analysis.
  4.Import the cleaned dataset into your SQL database (PostgreSQL / MySQL / SQL Server).
  5.Execute SQL queries for further analysis.
  6.Open the Power BI dashboard file (.pbix) to explore visual insights. 

PROJECT STRUCTURE:

Customer-Behavior-Analysis
│
├── dataset
│   └── customer_shopping_behavior.csv
│
├── python_analysis
│   └── data_analysis.ipynb
│
├── sql_queries
│   └── customer_analysis.sql
│
├── powerbi_dashboard
│   └── customer_behavior_dashboard.pbix
│
└── report
    └── project_report.pdf
