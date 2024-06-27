<h1>About data</h1>
This Logistics Service Provider is the largest and fastest-growing fully integrated player in India by revenue in Fiscal 2021. They aim to build the operating system for commerce, through a combination of world-class infrastructure, logistics operations of the highest quality, and cutting-edge engineering and technology capabilities.

The Data team builds intelligence and capabilities using this data that helps them to widen the gap between the quality, efficiency, and profitability of their business versus their competitors.

<h1>Business Problem</h1>

The company wants to understand and process the data coming out of data engineering pipelines:

• Clean, sanitize and manipulate data to get useful features out of raw fields

• Make sense out of the raw data and help the data science team to build forecasting models on it

<h1>Concept Used</h1>

- Feature Creation
- Relationship between Features
- Column Normalization /Column Standardization
- Handling categorical values
- Missing values - Outlier treatment / Types of outliers

## Project Goal

### Objective

Conduct a comprehensive exploratory data analysis (EDA) to identify patterns and relationships in delivery data, focusing on feature creation, handling categorical values, missing values treatment, outlier detection, and hypothesis testing.

### Recommendations

- **Data-Driven:** Ensure recommendations are based on robust data analysis.
- **Audience:** Tailor insights for business executives with a basic understanding of data science. Avoid technical jargon.

### Key Questions Explored

1. **How I Began:**

   - Imported the dataset and performed usual exploratory data analysis steps, such as checking the structure and characteristics of the dataset.
   - Established relationships between dependent and independent variables (e.g., Working day, Weather, Season).

2. **Feature Creation:**

   - Merged rows based on `Trip_uuid`, `Source ID`, and `Destination ID` using groupby and aggregation functions like sum() and cumsum().
   - Extracted features from fields such as Destination Name, Source Name, and Trip_creation_time.

3. **Data Cleaning and Exploration:**

   - Handled missing values in the data.
   - Analyzed the structure of the data.
   - Merged rows based on hints provided.

4. **In-depth Analysis and Feature Engineering:**

   - Calculated the time taken between `od_start_time` and `od_end_time` and kept it as a feature.
   - Conducted hypothesis testing and visual analysis to compare various time and distance metrics.

5. **Hypothesis Testing:**

   - Performed hypothesis testing on relationships between actual_time aggregated values, OSRM time aggregated values, and segment actual time aggregated values.

6. **Outlier Detection and Handling:**

   - Identified outliers in numerical variables using visual analysis.
   - Handled outliers using the IQR method.

7. **Handling Categorical Values:**

   - Performed one-hot encoding of categorical variables (e.g., route_type).

8. **Normalization/Standardization:**
   - Normalized/standardized numerical features using MinMaxScaler or StandardScaler.

### Inferences and Recommendations

- Provided actionable insights based on the analysis, such as identifying busiest corridors, average distance, and time taken.
- Recommendations were clear and easy to understand, avoiding technical jargon and complications.

---
