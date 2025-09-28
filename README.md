# California Employment and Wages Analysis Dashboard

## Project Overview
This project analyzes employment and wage trends in California using the Quarterly Census of Employment and Wages (QCEW) dataset. The data is cleaned, processed, and aggregated to provide meaningful insights into employment and wage patterns across different regions and industries.

The final cleaned dataset **is** being prepared for integration with Tableau or Power BI for interactive dashboards.

The interactive dashboard can be accessed at the following link:

**[Insert Tableau or Power BI dashboard link here]**

## Data Processing Summary
- Loaded the QCEW dataset and removed rows with missing data to ensure accuracy.  
- Renamed columns for clarity and converted key numerical columns to appropriate types.  
- Aggregated data by `Area_Type` to calculate sums and averages of weekly wages and monthly employment.  
- Sorted and summarized the data to identify regional employment and wage trends.  
- Exported the processed data to a CSV file for further use.

## Next Steps

Please open the accompanying Jupyter Notebook to explore the detailed data cleaning, analysis, and visualizations.

---


# Visualizations

Below are key visualizations generated during the analysis. These help illustrate trends and insights from the employment and wage data.

---

## 1. Average Weekly Wages by Area Type

*Description:*  
This bar chart shows the average weekly wages grouped by `Area_Type` (e.g., County, MSA). It highlights how wages vary across different regional classifications.

![Weekly Wages by Area Type](weekly_wages_by_area.png)

---

## 2. Total Employment by Area Type

*Description:*  
A bar plot representing the total average monthly employment across each `Area_Type`. Useful for understanding workforce distribution.

![Total Employment by Area Type](total_employment_by_area.png)

---

## 3. Top 5 Areas by Average Weekly Wage

*Description:*  
A horizontal bar chart displaying the top 5 highest-paying areas in California based on average weekly wages.

![Top 5 Weekly Wage Areas](top5_weekly_wages.png)

---

## 4. Industry Employment Trends

*Description:*  
Line plot or heatmap showcasing how employment varies across industries (`Industry_Name`) over time.

![Industry Trends](industry_employment_trends.png)

---

Thank you for reviewing this project!
