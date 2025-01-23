
# World Life Expectancy Analysis

## Project Overview

This project explores global trends in life expectancy using a dataset containing over 200,000 health metrics records from countries worldwide. The dataset includes variables such as GDP, healthcare expenditures, schooling, mortality, and vaccination rates and spans several years. The project aims to uncover patterns and correlations influencing life expectancy and visualize key trends using tools such as MySQL, Excel, and Tableau Public.

## Objectives

1. **Understand Life Expectancy Trends**: Analyze how life expectancy varies across different countries and over time.
2. **Identify Key Factors**: Determine which factors (e.g., GDP, healthcare expenditure, schooling) correlate strongly with life expectancy.
3. **Create Visualizations**: Develop impactful visualizations to highlight trends and insights.

---

## Tools Used

1. **MySQL**: Data cleaning and exploratory data analysis (EDA).
2. **Excel**: Initial analysis and simple visualizations.
3. **Tableau Public**: Interactive dashboards and advanced visualizations.

---

## Data Cleaning

The dataset was cleaned to ensure accuracy and consistency. Steps included:

- **Handling Missing Values**:
  - `Life Expectancy`: Missing values were replaced with the global mean.
  - `Status`: Missing entries were filled with "Unknown."
- **Renaming Columns**: Spaces in column names were replaced with underscores for better compatibility.
- **Removing Unnecessary Columns**: Columns such as `Row_ID` were dropped as they were irrelevant to the analysis.
- **Standardizing Data Types**: Ensured `Year` was an integer and `GDP` was numeric.

---

## Exploratory Data Analysis (EDA)

Using MySQL, the following insights were uncovered:

1. **Global Trends**:
   - Developed countries generally have higher life expectancy compared to developing countries.
   - Countries with higher GDP and healthcare expenditure tend to show better life expectancy.
2. **Correlations**:
   - Positive correlation between life expectancy and schooling years.
   - Negative correlation between life expectancy and mortality rates.

---

## Visualizations

### 1. **Life Expectancy Over Time (Line Chart)**

- **Objective**: Show trends in life expectancy for selected countries.
- **Countries Selected**: Afghanistan, India, and Japan.
- **Insights**:
  - Afghanistan showed gradual improvements over time despite challenges.
  - India exhibited steady growth, reflecting improved healthcare.
  - Japan maintained consistently high life expectancy, demonstrating the benefits of advanced healthcare systems and infrastructure.

### 2. **Geographic Heatmap**

- **Objective**: Visualize life expectancy across countries on a global map.
- **Insights**:
  - Regions such as Sub-Saharan Africa had the lowest life expectancy.
  - Europe and East Asia had the highest life expectancy, highlighting disparities.

### 3. **Scatter Plot of Healthcare Expenditure vs. Life Expectancy**

- **Objective**: Show the relationship between healthcare spending and life expectancy.
- **Insights**:
  - A strong positive correlation was observed.
  - Outliers included countries with high expenditure but lower-than-expected life expectancy, indicating potential inefficiencies.

---

## Key Findings

1. **Economic and Educational Factors Matter**: Higher GDP and schooling levels significantly influence life expectancy.
2. **Healthcare Expenditure is Crucial**: Countries that invest more in healthcare generally have better life expectancy outcomes.
3. **Developed vs. Developing Countries**: The gap between developed and developing nations remains significant, although some developing countries are making notable progress.

---

## Challenges

- **Missing Data**: Certain years and countries lacked complete data, requiring imputation or exclusion.
- **Outliers**: Extreme values in variables like GDP occasionally distorted results, necessitating additional preprocessing.

---

## Conclusion

This project successfully demonstrated the power of data analytics and visualization in understanding global health trends. The findings provide valuable insights into how economic, educational, and healthcare factors influence life expectancy. The visualizations developed in Tableau Public compellingly represent these insights, making the data accessible and actionable.


---

**Author**: Shahariar Shadab\
