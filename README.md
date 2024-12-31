# Employee_Income_and_Retention_Analysis
ntroduction

This project focuses on analyzing the IBM HR Analytics dataset to understand the factors influencing employee income variation and retention. The aim is to explore how variables such as experience, tenure, and job roles impact compensation and organizational stability. By applying statistical methods and regression models, this study seeks to provide insights that can inform human resource strategies to enhance employee satisfaction and reduce turnover.

Dataset

The dataset consists of 1,470 employee records and includes 35 numerical and categorical variables, with no missing values, ensuring comprehensive analysis. Key variables in the dataset cover demographics such as age, gender, and marital status, as well as job roles and income data, including job titles, departmental classifications, and monthly income. Additionally, experience metrics, such as years in the current role, total working years, and years since the last promotion, are included. Retention factors like tenure at the company and work environment variables, including overtime and training opportunities, are also considered in the analysis.

Models

We implemented linear regression models to predict monthly income and tenure based on various predictors. The selected predictors include total working years, years at the company, training frequency, and tenure metrics. The target variables for the regression models were monthly income and years at the company. To improve model performance, a Box-Cox transformation was applied to normalize the monthly income data. This transformation aimed to reduce skewness and variance, ultimately enhancing the predictive accuracy of the models.

Results

The analysis revealed a strong correlation between monthly income and total working years, with employees having more experience earning higher salaries. The Box-Cox transformation successfully reduced income variance, improving the prediction accuracy for monthly income. For tenure prediction, the model showed better performance than the income prediction model, with fewer outliers and tighter error bounds. The results suggest that income disparities are largely influenced by job roles and tenure, and that retention strategies should focus on career development and equitable compensation across different employee groups.
