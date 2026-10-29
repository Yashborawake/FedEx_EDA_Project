# 📦 FedEx Logistics Data Analysis (EDA)

## 📌 Project Overview

This project focuses on Exploratory Data Analysis (EDA) of FedEx logistics data to understand shipment performance, delivery efficiency, transportation costs, and operational challenges. Using SQL, Python, and Power BI, the project analyzes logistics data to identify trends, compare shipping methods, and generate actionable business insights.

The objective is to understand how transportation modes affect delivery time and operational efficiency, helping businesses make data-driven logistics decisions.

## 🎯 Project Objectives

- Analyze shipment and delivery performance.
- Compare delivery efficiency across transportation modes.
- Identify patterns in logistics costs and delivery times.
- Perform data cleaning and handle missing values.
- Detect potential outliers using the IQR method.
- Apply statistical analysis to compare transportation methods.
- Generate actionable insights to support logistics decision-making.

## 🛠️ Tools & Technologies

- **SQL** – Data querying and analysis
- **Python** – Data cleaning, EDA, and statistical analysis
- **Pandas & NumPy** – Data manipulation
- **Matplotlib & Seaborn** – Data visualization
- **Power BI** – Interactive data visualization and reporting
- **Jupyter Notebook** – Analysis and documentation

## 🔍 Project Workflow

1. **Data Loading:** Imported the logistics dataset for analysis.
2. **Data Cleaning:** Examined missing values, corrected data types, and prepared the dataset.
3. **Exploratory Data Analysis:** Analyzed shipment trends, delivery times, and transportation costs.
4. **Outlier Detection:** Used the Interquartile Range (IQR) method to identify potential outliers.
5. **Statistical Analysis:** Applied ANOVA to evaluate differences in delivery times across transportation modes.
6. **Visualization:** Created visualizations to communicate key patterns and findings.
7. **Business Insights:** Interpreted the results to identify opportunities for operational improvement.

## 📊 Key Findings

- **Transportation Efficiency:** Air transportation showed faster delivery performance, while Truck transportation appeared more cost-efficient.
- **Missing Data:** Approximately 27% of values in the `PO Sent to Vendor Date` column were missing, highlighting a data-quality issue.
- **Statistical Analysis:** ANOVA produced a p-value of approximately `4.47 × 10⁻¹⁰`, indicating statistically significant differences among the analyzed transportation groups under the test assumptions.
- **Historical Data:** The dataset covered the period from 2006 to 2009.
- **Operational Insights:** Comparing transportation speed and cost can help businesses evaluate shipping methods according to delivery requirements and budget constraints.

## 📈 Statistical Analysis

ANOVA (Analysis of Variance) was used to compare the delivery-time distributions across four transportation modes:

- Air
- Truck
- Ocean
- Air Charter

**ANOVA p-value:** `4.470610766235379e-10`

Since the p-value is below 0.05, the analysis indicates a statistically significant difference in the group means, assuming the test requirements are satisfied. Further analysis is needed to determine which specific transportation modes differ from one another.

## 💡 Business Recommendations

- Evaluate transportation options by balancing delivery speed and cost.
- Investigate missing vendor-date records to improve data quality.
- Monitor delivery performance across transportation modes.
- Use statistical testing to support operational decisions.
- Improve shipment tracking and reporting to identify potential delays.

## 📂 Project Repository

**GitHub Repository:** [FedEx_EDA_Project]((https://github.com/Yashborawake/FedEx_EDA_Project.git))

## 🚀 Conclusion

This project demonstrates how exploratory data analysis and statistical techniques can be applied to logistics operations. By combining SQL, Python, and Power BI, the analysis highlights transportation performance differences, data-quality issues, and opportunities to improve delivery planning and cost efficiency.

The project strengthened my practical understanding of data cleaning, exploratory analysis, statistical testing, data visualization, and business-oriented problem-solving.

## 👨‍💻 Author

**Yash Borawake**

- [GitHub](https://github.com/Yashborawake)
- [LinkedIn](https://www.linkedin.com/in/yash-borawake/)

---

*This project was developed for learning and analytical demonstration purposes.*
