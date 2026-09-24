Sample Superstore Sales Data Analysis
Project Overview
This project is developed as part of the Big Data Analytics (BDA) course. The objective is to perform Exploratory Data Analysis (EDA) on the Sample Superstore dataset to understand sales performance, data quality, and business trends.

The project demonstrates the complete workflow of data analysis, including data loading, preprocessing, statistical analysis, visualization, and business insights using Python.

Project Objectives
Load and inspect the dataset.
Understand the structure of the data.
Perform data preprocessing.
Convert date columns into proper datetime format.
Calculate delivery time for each order.
Check for missing values.
Generate descriptive statistics.
Analyze sales by product category.
Visualize sales patterns using charts.
Gain useful business insights from the data.
Project Structure
Task_1_BDA/
│
├── Task_1_BDA.ipynb
├── task_1_bda.py
├── samplesuperstore - samplesuperstore.csv
└── README.md
Files Description
1. Task_1_BDA.ipynb
This Jupyter Notebook contains the complete Exploratory Data Analysis process.

The notebook includes:

Importing required libraries
Loading the dataset
Displaying first records
Dataset information
Statistical summary
Date conversion
Delivery days calculation
Missing value analysis
Category-wise sales analysis
Data visualization
Final observations
2. task_1_bda.py
This file contains the same analysis implemented as a Python script.

It can be executed directly from the command prompt or terminal without opening Jupyter Notebook.

3. samplesuperstore - samplesuperstore.csv
This is the dataset used for analysis.

The dataset contains information such as:

Order ID
Order Date
Ship Date
Customer Details
Product Details
Category
Sales
Profit
Quantity
Region
State
City
Technologies Used
Python 3.x
Pandas
NumPy
Matplotlib
Seaborn
Jupyter Notebook
Python Libraries
Install the required libraries before running the project.

pip install pandas numpy matplotlib seaborn
How to Run the Project
Method 1 - Jupyter Notebook
Open the notebook.

jupyter notebook
Open

Task_1_BDA.ipynb
Run all cells one by one.

Method 2 - Python Script
Open terminal inside the project folder.

Run

python task_1_bda.py
Data Preprocessing
The following preprocessing steps are performed:

Reading CSV file
Checking dataset information
Converting Order Date
Converting Ship Date
Calculating Delivery Days
Checking missing values
Exploratory Data Analysis
The project performs:

Dataset overview
Statistical summary
Category analysis
Sales analysis
Delivery analysis
Missing value analysis
Data Visualization
The following charts are generated:

Sales by Category
A bar chart showing total sales for each product category.

Sales Distribution
A histogram displaying the distribution of sales values.

Expected Output
After execution, the project displays:

Dataset preview
Dataset information
Descriptive statistics
Missing values report
Delivery Days column
Category-wise sales summary
Sales by Category chart
Sales Distribution histogram
Business Insights
The analysis helps to:

Understand category-wise sales performance.
Identify delivery duration.
Detect missing values.
Study sales distribution.
Support better business decision-making.
Learning Outcomes
After completing this project, students will understand:

Data Loading
Data Cleaning
Data Preprocessing
Exploratory Data Analysis (EDA)
Data Visualization
Business Analytics
Basic Python Data Analysis
Author
Maharani Magarasi V

Bachelor of Computer Applications (BCA)

License
This project is created for educational and academic purposes only.
