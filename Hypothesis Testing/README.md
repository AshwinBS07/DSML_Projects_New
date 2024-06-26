<h1>About data</h1>

This micro-mobility service provider is India’s leading micro-mobility service provider, which offers unique vehicles for the daily commute. Starting off as a mission to eliminate traffic congestion in India, This micro-mobility service provider provides the safest commute solution through a user-friendly mobile app to enable shared, solo and sustainable commuting.

This micro-mobility service provider zones are located at all the appropriate locations (including metro stations, bus stands, office spaces, residential areas, corporate offices, etc) to make those first and last miles smooth, affordable, and convenient!

This micro-mobility service provider has recently suffered considerable dips in its revenues. They have contracted a consulting company to understand the factors on which the demand for these shared electric cycles depends. Specifically, they want to understand the factors affecting the demand for these shared electric cycles in the Indian market.

<h1>Problem Statement</h1>
The company wants to know:

Which variables are significant in predicting the demand for shared electric cycles in the Indian market?
How well those variables describe the electric cycle demands

<h1>Concept Used</h1>

<ul>Bi-Variate Analysis
<ul>2-sample t-test: testing for difference across populations
<ul>ANNOVA
<ul>Chi-square

---

## Project Goal

### Objective

Conduct an exploratory data analysis to establish relationships between various factors and the number of electric cycles rented, and perform hypothesis testing to derive insights.

### Recommendations

- **Data-Driven:** Ensure each recommendation is supported by robust data analysis.
- **Audience:** Tailor findings for business executives with a basic understanding of data science. Avoid technical jargon.

### Key Questions Explored

1. **How I Began:**

   - Imported the dataset and performed usual exploratory data analysis steps, such as checking the structure and characteristics of the dataset.
   - Established a relationship between the dependent variable (Count) and independent variables (Working day, Weather, Season, etc.).

2. **Hypothesis Testing:**

   - Selected appropriate tests to check:
     - Whether working day has an effect on the number of electric cycles rented.
     - Whether the number of cycles rented is similar or different in different seasons.
     - Whether the number of cycles rented is similar or different in different weather conditions.
     - Whether weather is dependent on season (check between two predictor variables).

3. **Hypothesis Formulation:**

   - Set up Null Hypothesis (H0).
   - Stated the Alternate Hypothesis (H1).

4. **Test Assumptions:**

   - Checked assumptions of the test (Normality, Equal Variance) using Histogram, Q-Q plot, or statistical methods like Levene’s test, Shapiro-Wilk test (optional).
   - Continued the analysis even if some assumptions failed, but double-checked using visual analysis and reported wherever necessary.

5. **Significance Level:**

   - Set a significance level (alpha).

6. **Test Statistics and Decision:**
   - Calculated test statistics.
   - Made a decision to accept or reject the null hypothesis.
   - Drew inferences from the analysis.

### Inferences and Recommendations

- Provided actionable insights based on the analysis.
- Recommendations were clear and easy to understand, avoiding technical jargon and complications.

---
