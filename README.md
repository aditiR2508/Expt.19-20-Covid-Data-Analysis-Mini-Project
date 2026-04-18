# Expt.19-20-Covid-Data-Analysis-Mini-Project
# PROJECT REPORT
# 
## Symbiosis Institute of Technology, Pune
## Department of Applied Science
## F.Y. B.Tech ; Academic Year: 2025-26
# 
## EDP Lab Project Report
## Covid Data Analysis
# 
## By: 
## Aditi Rathore
## 25070123006
## EnTC A-1
# 
## Faculty Incharge: Mrs. Snehal Bhosale

# INTRODUCTION
### In this data analysis project, we are analyzing global COVID-19 trends to effectively monitor daily case counts, calculate clinical outcomes, and present data through statistical summaries. Various data science principles have been incorporated into this project to enhance information management. Essential libraries such as Pandas and NumPy are utilized to ensure efficient data manipulation and numerical operations.
### Visual representations and data cleaning techniques are implemented to enhance accuracy and visualization, facilitating informed insights into the pandemic's progression while grouping operations are used to summarize and analyze regional impacts comprehensively. By integrating these tools, the project offers detailed insights into the pandemic's progression, facilitating informed interpretation of global health data.

# OBJECTIVE OF THE PROJECT
### 1. Data Cleaning and Preprocessing: To import the COVID-19 dataset and clean it by removing unnecessary columns like 'SNo' and 'Last Update' to focus on core metrics.
### 2. Datatype Optimization: To convert observation dates and clinical counts into appropriate numerical and datetime formats for performing time-series operations.
### 3. Regional Impact Assessment: To analyze the spread across different countries and provinces, identifying regions with the highest confirmed cases.
### 4. Trend Analysis: To determine periods of high infection and recovery by grouping data by observation dates and regions
### 5. Clinical Outcome Assessment: To determine periods of high mortality or recovery rates and prospective areas for intervention by analyzing regional data every month.
### 6. Thorough Data Insights: To gather information from the study to produce practical insights for understanding pandemic behavior and regional health trends.

# RAW DATA
### The database consists of 3,06,429 entries. It includes global records of COVID-19 cases, categorized by date, province/state, and country.
### Data Structure Overview:
#### 1. ObservationDate: The date the cases were recorded (Converted to datetime64[ns]).
#### 2. Province/State: Specific regional data.
#### 3. Country/Region: National data.
#### 4. Confirmed: Total number of confirmed COVID-19 cases.
#### 5. 
