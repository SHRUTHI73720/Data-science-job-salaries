# Data-science-job-salaries
This Repositary details a **Data Science Job Salaries project**, using **ML, Python, SQL, and Excel**. It covers the entire process: **problem definition, data cleaning (607 entries), EDA, financial modeling (Linear Regression), and visualization** of salary trends by experience, company size, and job type (remote/onsite).
A comprehensive README for this project, based on the steps and insights provided in the PDF, will help users understand the analysis and replicate the work.

Data Science Job Salaries Analysis
Project Overview
This project involves a detailed analysis and predictive modeling of a global dataset of Data Science job salaries. The objective is to uncover key trends and identify factors that drive salary levels in the data science industry. The analysis follows a standard data science pipeline, including Exploratory Data Analysis (EDA), feature engineering, and predictive modeling using Linear Regression.





The project's domain is Finance/Data Analysis, and it is classified as an intermediate difficulty level.


🛠️ Tools and Technologies
Category	Tools
Primary Language	
Python 


Libraries	Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, Streamlit
Databases/Data Formats	
SQL, CSV 


Visualization	
Matplotlib and Seaborn for static plots; Streamlit for interactive dashboards 




Export to Sheets
💡 Key Findings
The exploratory data analysis yielded several significant insights into salary trends (all salary figures are mean annual salaries in USD, based on the dataset's conversion):

Factor	Highest Paid Segment	Mean Salary (USD)	Lowest Paid Segment	Mean Salary (USD)
Experience Level	
Executive 



∼$199,392 

Entry-level 


∼$61,643 

Employment Type	
Contract 



∼$184,575 

Part-time 


∼$33,071 

Job Type (Remote Ratio)	
Remote 



∼$120,763 

Hybrid 


∼$80,722 

Company Size	
Large 



∼$118,214 

Small 


∼$77,872 


Export to Sheets
Top Roles and Locations

Highest Paid Roles (Mean Salary): Principal Data Engineer, Financial Data Analyst, and Principal Data Scientist.




Most Job Openings: Data Scientist, Data Engineer, and Data Analyst.


Highest Paying Company Locations (Mean Salary): Russia, United States, and New Zealand.


Most Job Opportunities (Location): The US, the UK, and Canada.

📑 Dataset Details
The dataset contains various attributes related to data science roles:

Column Name	Description	Possible Values/Examples
work_year	The year the salary was paid.	
2020, 2021, 2022 


experience_level	The level of experience.	
Entry (EN), Mid (MI), Senior (SE), Executive (EX) 

employment_type	The type of employment.	
Full-time (FT), Part-time (PT), Contract (CT), Freelance (FL) 

job_title	The role worked in.	
Data Scientist, Analyst, etc. 


salary_in_usd	The converted salary amount in USD.	
Continuous (e.g., 79,833) 


remote_ratio	The percentage of work done remotely.	
0 (Onsite), 50 (Hybrid), 100 (Remote) 



company_size	Average number of employees.	
S (<50), M (50-250), L (>250) 

employee_residence	Employee's primary country of residence.	
ISO 3166 Country Codes 


Export to Sheets
💻 Project Steps
The analysis was performed following these steps:


Problem Definition: Analyze and model data science job salaries to uncover trends and predict salaries based on job factors.


Data Loading and Understanding: Loading the CSV dataset, inspecting the structure, and checking data types .



Data Cleaning: Handling duplicates, removing unnecessary columns (Unnamed: 0, salary, salary_currency), and standardizing abbreviations for categorical variables (experience_level, employment_type, company_size, remote_ratio/job_type) .


Feature Engineering: Encoding categorical variables and creating derived features like salary_ratio (salary/salary_in_usd) .


Exploratory Data Analysis (EDA): Calculating summary statistics, analyzing salary distribution (histograms), and visualizing relationships between salary and categorical features (boxplots, violin plots, and correlation heatmaps) .


Financial Modeling (Prediction): Training a Linear Regression model to predict salary_in_usd using features like experience level and job type .



Data Visualization for Insights: Creating an interactive dashboard using Streamlit to visualize salary trends and filtering options .
