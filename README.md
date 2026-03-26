Student Performance Analysis System (Synthetic Data)

Overview

This project analyzes student academic performance using a structured, analytics-focused pipeline built on synthetically generated data. The system simulates real-world educational datasets and applies data preprocessing, exploratory data analysis (EDA), and performance evaluation techniques.
The workflow includes:
•	Synthetic data generation for 250 students 
•	Data preprocessing and cleaning 
•	Exploratory data analysis (EDA) 
•	Performance evaluation and insights generation 
•	Visualization of trends and patterns 
The objective is to demonstrate a scalable and reproducible analytics approach that helps identify performance trends, top-performing students, and those needing improvement.
________________________________________
Dataset

Source: Synthetic dataset (generated programmatically)
Description: The dataset contains student academic and demographic details.
Column Name	Description
Student_ID	Unique student ID
Name	Student name
Gender	Male / Female
Department	CSE, IT, ECE
Year	1st / 2nd / 3rd
Maths	Marks
Science	Marks
English	Marks
Attendance (%)	Range: 50–100
Internal Marks	Range: 0–25
________________________________________
Objectives

•	Generate a realistic synthetic dataset representing student records 
•	Perform data cleaning and preprocessing 
•	Analyze student performance using statistical methods 
•	Identify top-performing and low-performing students 
•	Perform group-based and relational analysis 
•	Visualize key insights for better decision-making 
________________________________________
Project Highlights

1. Data Generation
   
•	Created synthetic dataset of 250 students 
•	Included academic scores, attendance, and demographic attributes 
•	Simulated real-world variability in student performance 
________________________________________
2. Data Preprocessing
   
•	Checked for missing values and inconsistencies 
•	Ensured correct data types 
•	Prepared dataset for analysis 
________________________________________
3. Exploratory Data Analysis (EDA)

•	Used descriptive statistics: 
o	Mean 
o	Median 
o	Mode 
o	Standard deviation 
•	Analyzed distribution of marks across subjects 
•	Calculated: 
o	Total marks 
o	Average marks 
o	Grade classification 
________________________________________
4. Performance Analysis

•	Identified: 
o	Top-performing students 
o	Low-performing (fail) students 
•	Performed group-based analysis: 
o	Department-wise performance 
o	Gender-wise comparison 
o	Year-wise trends 
________________________________________
5. Relationship Analysis

•	Studied relationships between variables: 
o	Attendance vs Marks 
o	Internal Marks vs Final Performance 
________________________________________
6. Visualization

Used various charts to represent insights:
•	Bar charts (department & gender analysis) 
•	Pie charts (distribution overview) 
•	Histograms (marks distribution) 
•	Scatter plots (relationship analysis) 
________________________________________
Tools and Technologies

•	Python 
•	pandas 
•	numpy 
•	matplotlib 
•	seaborn 
•	Jupyter Notebook 
________________________________________
Results

Key Findings

•	Students with higher attendance tend to score better 
•	Internal marks positively influence final performance 
•	Certain departments show consistently higher averages 
•	Clear distinction between top performers and at-risk students 
________________________________________
Interpretation

•	Attendance plays a crucial role in academic success 
•	Continuous assessment (internal marks) improves final outcomes 
•	Group-based analysis helps institutions identify gaps 
•	Visualization improves understanding of performance patterns 
________________________________________
Pipeline Usage

Run Analysis

python main.py
Notebook Exploration
Open the Jupyter Notebook to explore:
•	Data generation 
•	EDA 
•	Visualizations 
________________________________________
Future Improvements

•	Add machine learning model for performance prediction 
•	Build a dashboard using Power BI / Streamlit 
•	Integrate real-world datasets 
•	Automate reporting system 
•	Add student recommendation system

