# NHC Healthcare Data Analysis Project

This repository presents a series of Jupyter notebooks demonstrating core skills in healthcare data analysis using Python. These projects were developed as practical exercises in data wrangling, exploratory analysis, visualization, and forecasting to derive insights from healthcare datasets. This Project primarily serves as practice for learning and demonstrating fundemental knowledge of pandas. 

### Project Overview

#### 1. Data Wrangling & Manipulation
- **Objective**: Clean and reformat a raw dataset of 1000 generic medication names into a structured format with medication name and class.
- **Key Techniques**:
  - Data cleaning and restructuring using pandas
  - Identifed and corrected issues like incorrect header and irregular delimiters
  - Employed string operations and regular expression to split medication names from classes 
  - Performed text parsing and transformation
  - Validation and organization of unstructured data
  - Exported the clean data for downstream analysis 

#### 2. Pharmacy Sales Analysis
- **Objective**: Analyze medication sales data to identify top-selling categories and predict future demand.
- **Key Techniques**:
  - Loaded and explored the dataset using pandas to understand data types, null values, and structure.
  - Exploratory data analysis and summary statistics
  - Aggregated and grouped data to identify top-selling medication classes
  - Data visualization using matplotlib and seaborn to showcase sales trend and cateogory performance
  - Time-series forecasting with Prophet to predict future demand for key medication categories
  - Demand prediction and inventory planning insights

#### 3. Patient Visit Analysis
- **Objective**: Analyze hospital outpatient visit data to understand patient demographics, visit trends, and cost efficiency.
- **Key Techniques**:
   - Data preparation and cleaning
   - Standardized hospital visit data (data formatting, missing values handling)
   - Analyzed patient demographics by age, gender, and visit reason using visual plots.
   - Investigated time-based trends in patient volumes and service delivery.
   - Performed cost analysis involving patient expenses, insurance claims, and visit durations.
   - Evaluated hospital performance through KPIs like treatment time and cost per visit

### Skills Demonstrated

- Data Cleaning and Preparation: Practical use of pandas to clean, transform, and structure data.
- Exploratory Data Analysis (EDA): Gained insights through filtering, grouping, and statistical summaries.
- Visualization: Created meaningful plots using matplotlib and seaborn to communicate findings.
- Forecasting and Time-Series Analysis: Used Prophet to project future sales trends.
- Healthcare Insight Generation: Translated raw data into actionable insights for healthcare operations and planning.

### Tools and Libraries

- Python
- Pandas
- Matplotlib
- Seaborn
- Prophet

## Notebooks Included

- `Data_Wrangling_&_Manipulation.ipynb`
- `Pharmacy_Sales.ipynb`
- `Patient_Visit_Analysis.ipynb`

Each notebook is self-contained and includes detailed comments and outputs to illustrate the analysis process.
