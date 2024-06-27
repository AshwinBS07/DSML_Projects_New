<h1>About data</h1>

This Loan providing company is an online platform committed to delivering customized loan products to millennials. They innovate in an otherwise dull loan segment, to deliver instant, flexible loans on consumer friendly terms to salaried professionals and businessmen.

The data science team at this company is building an underwriting layer to determine the creditworthiness of MSMEs as well as individuals.

This company deploys formal credit to salaried individuals and businesses 4 main financial instruments:

- Personal Loan
- EMI Free Loan
- Personal Overdraft
- Advance Salary Loan
- This case study will focus on the underwriting process behind Personal Loan only

<h1>Problem Statement</h1>

Given a set of attributes for an Individual, determine if a credit line should be extended to them. If so, what should the repayment terms be in business recommendations?

<h1>Concept Used</h1>

- Exploratory Data Analysis
- Feature Engineering
- Logistic Regression
- Precision Vs Recall Tradeoff

---

## Project Goal

To analyze and predict loan status using various predictor variables and provide actionable insights for minimizing non-performing assets (NPAs) while maximizing loan approvals.

### Objective

- Perform exploratory data analysis to understand the structure and characteristics of the dataset.
- Investigate the relationship between the target variable (Loan_Status) and predictor variables.
- Implement feature engineering and preprocessing steps to prepare data for modeling.
- Build and evaluate a logistic regression model to predict loan status.
- Provide actionable insights and recommendations based on the analysis.

### Recommendations

- **Data-Driven:** Ensure each recommendation is supported by thorough data analysis, statistical tests, and model evaluation.
- **Audience:** Present findings and recommendations in a manner accessible to bank executives and decision-makers with a basic understanding of data science. Avoid technical jargon and complications.

### Key Questions Explored

1. **Exploratory Data Analysis (EDA):**

   - Imported the dataset and performed exploratory data analysis steps to check the structure and characteristics of the dataset.
   - Analyzed how much the target variable (Loan_Status) depends on different predictor variables using count plots, box plots, and heat maps.
   - Checked correlation among independent variables and their interactions.

2. **Feature Engineering and Preprocessing:**

   - Created flags for `Pub_rec`, `Mort_acc`, and `Pub_rec_bankruptcies` (if value > 1.0 then 1 else 0).
   - Handled missing values and outlier treatment.
   - Scaled the data using MinMaxScaler or StandardScaler.

3. **Model Building and Evaluation:**

   - Built a Logistic Regression model using Sklearn/Statsmodel library and explained the results.
   - Evaluated the model using classification reports, ROC AUC curve, and precision-recall curve.

4. **Results Evaluation:**

   - Evaluated model performance using metrics like ROC AUC, precision-recall curve, and classification report.
   - Discussed tradeoff questions to balance detecting real defaulters and minimizing false positives.

5. **Actionable Insights & Recommendations:**
   - Provided insights on how to improve loan approval processes and minimize NPAs.
   - Suggested strategies to ensure the model can detect real defaulters while reducing false positives.

---

<h2>Important Questions Answered.</h2>

1.  What percentage of customers have fully paid their Loan Amount?

    Answer: Around 80% of customers have fully paid their Loan Amount.

2.  Comment about the correlation between Loan Amount and Installment features.

    Answer: There is a very high correlation between loan amount and installment. pearson co-efficient is ~ 0.97. This indicates high multi-collinearity between these two features. Hence installment column is dropped while creating the model.

3.  The majority of people have home ownership as?

    Answer: Mortgage and rent. With 50% and 40% in order.

4.  People with grades A are more likely to fully pay their loans. (T/F)

    Answer: True. Out of all people with grade 'A', ~ 94% got their loan approved.

5.  Name the top 2 afforded job titles.

    Answer: Teacher & Manager

6.  Thinking from a bank's perspective, which metric should our primary focus be on
    ROC-AUC: Not a good metric to consider as we have highly imbalanced data.
    Precision: Consider when only want to reduce Non-performing asset
    Recall: Consider when we do not want to miss a good opportunity to provide a loan to the customer
    F1-score: Good metric for us, because we want to consider both Precision and Recall.

    Answer: F1-Score

7.  How does the gap in precision and recall affect the bank?

    Answer: Recall score: 0.95 and Precision score: 0.9. which tells us that there are more false positives than the false negatives.

8.  If the Precision value is low, it means the Bank's NPA (defaulters) may increase. 8. Which were the features that heavily affected the outcome?

    Answer: A few important features are

        - Loan sub-grade
        - Annual Income
        - Interest rate
        - Mortgaged accounts
        - Purpose
        - Application Type
        - Employment Length
        - Home Ownership

9.  Will the results be affected by geographical location?

    Answer: Yes. Few regions have high chances of getting loans compared to other states.
