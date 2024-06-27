<h1>About data</h1>

This company is a leading ride-hailing platform in India, revolutionizing urban transportation by offering a variety of vehicle options, from bikes to luxury cars. Established in 2010, This company provides convenient and affordable mobility solutions through its user-friendly mobile app. It connects millions of riders to drivers across multiple cities, enhancing commuting experiences with safety features and real-time tracking. Beyond ride-hailing, This company is expanding into electric mobility and other services, aiming to create a comprehensive ecosystem for urban living. The company is committed to sustainability and improving the quality of life in cities worldwide.

<h1>Business Problem</h1>

Recruiting and retaining drivers is seen by industry watchers as a tough battle for this company. Churn among drivers is high and it’s very easy for drivers to stop working for the service on the fly or jump to Uber depending on the rates.

As the companies get bigger, the high churn could become a bigger problem. To find new drivers, this company is casting a wide net, including people who don’t have cars for jobs. But this acquisition is really costly. Losing drivers frequently impacts the morale of the organization and acquiring new drivers is more expensive than retaining existing ones.

You are working as a data scientist with the Analytics Department of this company, focused on driver team attrition. You are provided with the monthly information for a segment of drivers for 2019 and 2020 and tasked to predict whether a driver will be leaving the company or not based on their attributes like

- Demographics (city, age, gender etc.)
- Tenure information (joining date, Last Date)
- Historical data regarding the performance of the driver (Quarterly rating, Monthly business acquired, grade, Income)

<h1>Concepts Used</h1>

- Ensemble Learning- Bagging
- Ensemble Learning- Boosting
- KNN Imputation of Missing Values
- Working with an imbalanced dataset

### Project Goal

Analyze driver data to identify key factors influencing driver retention and performance, and develop predictive models to forecast drivers at risk of leaving the company.

### Objective

- Conduct exploratory data analysis to understand dataset structure and characteristics.
- Prepare and clean data, including date conversion, handling missing values with KNN Imputation, and aggregating driver data.
- Engineer features to capture trends in driver performance and income.
- Build and evaluate predictive models using ensemble learning techniques to identify drivers likely to leave the company.

### Recommendations

- Implement retention strategies for drivers with declining quarterly ratings or monthly incomes.
- Use predictive models to proactively identify at-risk drivers and develop targeted interventions.
- Regularly update and monitor models to ensure ongoing accuracy and effectiveness in predicting driver attrition.

### Data-Driven

- Performed comprehensive exploratory data analysis to reveal data structure and relationships.
- Created new features based on historical performance and income data to enhance predictive power.
- Employed machine learning models to generate actionable insights and improve driver retention strategies.

### Audience

Business executives, data scientists, and analysts in ride-hailing or logistics companies aiming to optimize driver retention and performance through data-driven strategies.

### Key Questions Explored

1. **Dataset Structure and Characteristics**:

   - Imported the dataset and performed initial exploratory analysis.
   - Converted date-like features to their respective data types.

2. **Missing Values and KNN Imputation**:

   - Checked for missing values in the dataset.
   - Prepared data for KNN Imputation, focusing on numerical features.

3. **Data Aggregation**:

   - Aggregated data to remove multiple occurrences of the same driver data.
   - Grouped data by unique Driver IDs.

4. **Feature Engineering**:

   - Created a column to indicate if the quarterly rating has increased for each driver.
   - Created a target variable to indicate if a driver has left the company.
   - Created a column to indicate if the monthly income has increased for each driver.

5. **Statistical Summary**:

   - Generated statistical summaries of the derived dataset.

6. **Correlation Analysis**:

   - Checked the correlation among independent variables and their interactions.

7. **One-Hot Encoding**:

   - Applied one-hot encoding to categorical variables.

8. **Class Imbalance Treatment**:

   - Addressed class imbalance in the dataset.

9. **Standardization**:

   - Standardized training data using appropriate scaling methods.

10. **Model Building**:

    - Used ensemble learning methods, including Bagging and Boosting, with hyper-parameter tuning.

11. **Results Evaluation**:

    - Generated classification reports.
    - Plotted and analyzed ROC AUC curves.

12. **Insights and Recommendations**:
    - Provided actionable insights based on the analysis.
    - Recommended strategies to improve driver retention and performance.

### Questions to be answered

- What are the main factors affecting driver retention and performance?
- Which predictors are most indicative of driver attrition?
- How can data be leveraged to improve retention strategies for drivers?
- What is the impact of quarterly ratings and monthly incomes on driver retention?
- How effective are ensemble learning methods in predicting driver attrition?
