# Bank Customer Churn Analysis

## Project Overview
This project explores a bank customer dataset (`bank_churn_data.csv`) to identify key demographic factors that drive customer attrition (churn). By analyzing the distribution of customer age, education levels, and income categories, this repository provides data-driven interpretations and actionable retention strategies to minimize churn across various customer segments.

## Key Findings and Interpretations

### 1. Age Distribution and Churn Correlation
* **Customer Base Profile:** The majority of the bank's customers fall within the 35 to 55 age range, with both the average and median age situated at approximately 46 years old. This indicates that the core demographic consists of working-age individuals approaching their pre-retirement phase.
* **High-Risk Age Groups:** The highest churn rate is observed in the 50–59 age bracket, reaching approximately 17.8%. This is closely followed by the 60–69 age group (16.2%) and the 40–49 age group (14.5%). Conversely, the youngest demographic (20–29 years old) exhibits the lowest churn rate at just 8.5%.
* **Critical Churn Peaks:** Specific ages demonstrate alarmingly high attrition, particularly customers at age 62 (experiencing a churn rate of over 25%), as well as ages 65 and 53. This strongly suggests that customers nearing or entering retirement are highly vulnerable to churning.

### 2. Education, Income, and Churn Dynamics
* **Socioeconomic Correlation:** There is a clear positive correlation between a customer's education level and their income[cite: 2]. Customers with higher educational backgrounds (Post-Graduate, Doctorate) predominantly fall into higher income brackets ($80K - $120K or $120K+)[cite: 2]. Meanwhile, "Uneducated" customers or those with only a "High School" diploma are heavily concentrated in the lowest income category (Less than $40K).
* **Churn by Education Level:** "Uneducated" customers record the highest churn rate at 18.5%, followed by "High School" graduates at 16.2%. Customers with Doctorate and Post-Graduate degrees are the most loyal, with the lowest churn rates hovering between 9% and 10%.
* **Churn by Income Level:** The "Less than $40K" income bracket experiences the highest attrition at 19.1%, whereas the highest income bracket ($120K+) has the lowest at 8.7%. The data indicates that higher income directly correlates with a significantly lower likelihood of churning.
* **The Compounding Effect:** The intersection of low education and low income creates the highest risk segment, with churn rates exceeding 25%. In contrast, the combination of high education and high income yields a highly stable customer segment with churn rates below 10%.

## Strategic Recommendations
Based on the exploratory data analysis, the following targeted retention strategies are recommended to improve customer loyalty:
* **Pre-Retirement & Senior Programs:** Develop tailored retention strategies specifically for customers aged 50 and above. This can include exclusive loyalty programs, specialized pre-retirement financial products, and highly personalized banking services designed to secure their long-term trust.
* **Support for Vulnerable Socioeconomic Segments:** The low-income and low-education segment requires immediate prioritization for retention efforts. The bank should consider offering financial literacy education, administrative fee subsidies, or light installment loan products to alleviate financial friction and reduce attrition in this demographic.
