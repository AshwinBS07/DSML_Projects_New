<h1>About data</h1>

This coaching institute has helped thousands of students like you make it to top colleges abroad. Be it GMAT, GRE or SAT, their unique problem-solving methods ensure maximum scores with minimum effort.
They recently launched a feature where students/learners can come to their website and check their probability of getting into the IVY league college. This feature estimates the chances of graduate admission from an Indian perspective.

<h1>Business Problem</h1>
Analyzing will help this coaching institute in understanding what factors are important in graduate admissions and how these factors are interrelated among themselves. It will also help predict one's chances of admission given the rest of the variables.

<h1>Concept Used</h1>

- Exploratory Data Analysis
- Linear Regression

---

## Project Goal

### Objective

Perform comprehensive data analysis on graduate admissions to understand the factors influencing acceptance, build predictive models, and provide actionable insights for improving the admission process.

### Recommendations

- **Data-Driven:** Ensure each recommendation is supported by thorough data analysis, statistical tests, and model evaluation.
- **Audience:** Present findings and recommendations in a manner accessible to university administrators and decision-makers with a basic understanding of data science. Avoid technical jargon and complications.

### Key Questions Explored

1. **Exploratory Data Analysis (EDA):**

   - Imported the dataset and performed usual exploratory data analysis steps to check the structure and characteristics of the dataset.
   - Dropped unique row identifiers to prevent the model from building a bias based on row numbers.
   - Conducted both non-graphical and graphical analyses to understand the distribution of variables among graduate applicants.

2. **Understanding Relationships:**

   - Analyzed the relationship between different factors responsible for graduate admissions.
   - Checked correlations among independent variables and their interactions.

3. **Building Linear Regression Models:**

   - Used Linear Regression from the Statsmodel library and explained the results.
   - Tested the assumptions of linear regression including multicollinearity, mean of residuals, linearity of variables, homoscedasticity, and normality of residuals.
   - Evaluated the model using MAE, RMSE, R2 score, and Adjusted R2.

4. **Model Evaluation and Assumptions Testing:**

   - Checked multicollinearity by VIF score and dropped variables until none had VIF > 5.
   - Ensured the mean of residuals was nearly zero.
   - Confirmed the linearity of variables with no pattern in the residual plot.
   - Tested for homoscedasticity.
   - Verified the normality of residuals with a nearly bell-shaped curve and points in the QQ plot almost on the line.

5. **Model Performance Evaluation:**

   - Evaluated the model using metrics such as MAE, RMSE, R2, and Adjusted R2.
   - Compared train and test performance to check for any overfitting or underfitting.
   - Commented on the performance measures and suggested if there is a need to improve the model.

6. **Feature Engineering:**

   - Created new features to prepare the data for actual analysis.
   - Extracted features from fields like Destination Name, Source Name, and Trip_creation_time.
   - Calculated time differences and other relevant features for in-depth analysis.

7. **Actionable Insights & Recommendations:**

   - Provided actionable insights based on the analysis and model results.
   - Commented on the significance of predictor variables.
   - Suggested additional data sources for model improvement.
   - Recommended ways to implement the model in real-world scenarios and potential business benefits from improving the model.

8. **Testing Different Models:**
   - Tried out different linear regression models, including Ridge and Lasso regression.

---
