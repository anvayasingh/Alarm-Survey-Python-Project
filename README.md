# Alarm Survey Data Cleaning & Analysis

# Project Overview
This notebook performs **data cleaning and exploratory analysis** on a dataset collected from an "Alarm Survey."

The dataset includes:
- Sleep habits
- Alarm usage
- Wake-up behaviors
- Morning routines

The focus is to clean messy survey data and prepare it for analysis.

# Data Used
- `Alarm Survey Data.xlsx`

# Steps Performed

# 1. Data Import
- Loaded Excel data into Pandas
- Checked column data types
- Identified object fields that needed conversion to numeric/datetime

# 2. Data Cleaning
- Stripped extra spaces  
- Standardized categorical responses  
- Converted strings to numeric formats  
- Fixed incorrect entries and malformed data  
- Replaced missing values logically  
- Simplified multi-choice fields  

# 3. Structure & Typing
- Ensured correct formats:
  - Datetime  
  - Integer responses  
  - Categoricals  
- Verified with `.dtypes`, `.info()`

# 4. Exploratory Data Analysis (EDA)
Analyses included:
- Count of people using alarms vs not  
- Wake-up time patterns  
- Distribution of snooze usage  
- Sleep duration estimates  
- Relationships between habits and alarm dependency  

# 5. Visualization
Using **Seaborn**, you created:
- Countplots  
- Bar charts  
- Frequency graphs of responses  

# Tech Stack
- Python  
- Pandas  
- NumPy  
- Seaborn  

# Key Insights
- Clear behavioral clusters based on alarm usage  
- Many responses show inconsistencies that required careful cleaning  
- Data is now fully ready for modeling or deeper analysis  
