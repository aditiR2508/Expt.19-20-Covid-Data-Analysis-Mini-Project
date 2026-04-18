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
### In this data analysis project, we are analyzing global COVID-19 trends to effectively monitor daily case counts, calculate clinical outcomes, and present data through statistical summaries.
### Various data science principles have been incorporated into this project to enhance information management. Essential libraries such as Pandas and NumPy are utilized to ensure efficient data manipulation and numerical operations.
### Visual representations and data cleaning techniques are implemented to enhance accuracy and visualization, facilitating informed insights into the pandemic's progression while grouping operations are used to summarize and analyze regional impacts comprehensively.
### By integrating these tools, the project offers detailed insights into the pandemic's progression, facilitating informed interpretation of global health data.

# 

# OBJECTIVE OF THE PROJECT
### 1. Data Cleaning and Preprocessing: To import the COVID-19 dataset and clean it by removing unnecessary columns like 'SNo' and 'Last Update' to focus on core metrics.
### 2. Datatype Optimization: To convert observation dates and clinical counts into appropriate numerical and datetime formats for performing time-series operations.
### 3. Regional Impact Assessment: To analyze the spread across different countries and provinces, identifying regions with the highest confirmed cases.
### 4. Trend Analysis: To determine periods of high infection and recovery by grouping data by observation dates and regions
### 5. Clinical Outcome Assessment: To determine periods of high mortality or recovery rates and prospective areas for intervention by analyzing regional data every month.
### 6. Thorough Data Insights: To gather information from the study to produce practical insights for understanding pandemic behavior and regional health trends.

# 

# RAW DATA
### The database consists of 3,06,429 entries. It includes global records of COVID-19 cases, categorized by date, province/state, and country.
### Data Structure Overview:
#### 1. ObservationDate: The date the cases were recorded (Converted to datetime64[ns]).
#### 2. Province/State: Specific regional data.
#### 3. Country/Region: National data.
#### 4. Confirmed: Total number of confirmed COVID-19 cases.
#### 5. Deaths: Total number of deceased patients.
#### 6. Recovered: Total number of patients who recovered from the virus.

# 

# FUNCTIONS AND TOOLS USED
### The Python data analysis toolkit gives users the ability to quickly gain insightful information from large datasets. This project utilizes several built-in functions for complex data modeling and statistical analysis:
#### 1. .info() and .isnull().sum(): Used for data validation to check the health of the dataset and identify missing values
#### 2. .drop(): Utilized to clean the data by removing irrelevant columns like 'SNo' and 'Last Update'.
#### 3. .groupby(): A powerful tool for summarizing data by date or region into a more meaningful format without altering original entries.
#### 4. .max() and .min(): Used to retrieve the largest and smallest values, such as finding the peak confirmed cases in a specific region.
#### 5. pd.to_datetime(): Essential for converting dates to proper formats to facilitate time-series analysis.
#### 6. .astype('int64'): Used to clean numerical columns by converting them to integers for better memory management and clarity.

# 

# DATA ANALYSIS & OPERATIONS
### The experiment involved the following data processing steps:
#### 1. Data Cleaning: Initial inspection showed that Province/State had approximately 80,000 missing entries, while all other core columns were fully populated. Irrelevant tracking columns were dropped for clarity.
#### 2. Type Casting: Confirmed, Death, and Recovery values were initially stored as floats. These were converted to integers to ensure logical consistency in clinical reporting.
#### 3. Specific Regional Focus: Filtered records to analyze the impact in India. Data was further drilled down into specific states like Maharashtra, which showed a maximum of 5,713,215 confirmed cases during the study period.

# 

# CONCLUSION
### Through this project, we explored the fundamentals of data analysis using Python and demonstrated how powerful it is at concluding large datasets. 
### Maharashtra recorded the maximum confirmed cases in India, reflecting its status as a high-transmission hub. Tripura and West Bengal were also analyzed to understand varying regional patterns.
### Data Precision: By utilizing professional data tools, we were able to get overall clinical counts and assess mortality rates for the entire study period.
### Python remains a valuable tool due to its ability to handle hundreds of thousands of entries with high efficiency. By utilizing these data analysis functions, we can effectively visualize trends and gain insights to aid in strategic planning and public health decision-making
