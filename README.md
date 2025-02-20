# Covid19-Data-Analysis-using-R
This project analyzes a real-world COVID-19 dataset to identify the countries with the highest positivity rates (positive cases relative to testing numbers). The analysis provides insights into testing trends and the impact of the pandemic globally. 

## 📂 Dataset  
- The dataset (`tested_worldwide.csv`) contains COVID-19 testing and case details for multiple countries over time.  
- Source: [Kaggle - COVID-19 Testing Dataset](https://www.kaggle.com/datasets/lin0li/covid19testing)  

## 🔍 Key Steps in Analysis  
1. **Data Cleaning:** Handling missing values, correcting data types, and filtering relevant data.  
2. **Data Aggregation:** Grouping by country and calculating total tests, positive cases, and positivity rates.  
3. **Visualization:** A bar chart was created to highlight the most affected countries.  
4. **Statistical Insights:** Correlation analysis between total tests and positive cases.  

## 📈 Project Outcomes  
- Identified **top 10 countries** with the highest positivity rates.  
- Computed **summary statistics** (average, max, min positivity rate).  
- Visualized the most affected countries using `ggplot2` in R.  

## 🛠️ Tech Stack  
- **R**
- **R Packages:** dplyr, ggplot2, tidyverse
