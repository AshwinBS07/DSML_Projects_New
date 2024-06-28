<h1>About data</h1>
This company is an ads and marketing based company helping businesses elicit maximum clicks @ minimum cost. This company is an ad infrastructure to help businesses promote themselves easily, effectively, and economically. The interplay of 3 AI modules - Design, Dispense, and Decipher, come together to make it this an end-to-end 3 step process digital advertising solution for all.

<h1>Business Problem</h1>

You are working in the Data Science team of This company trying to understand the per page view report for different wikipedia pages for 550 days, and forecasting the number of views so that you can predict and optimize the ad placement for your clients. You are provided with the data of 145k wikipedia pages and daily view count for each of them. Your clients belong to different regions and need data on how their ads will perform on pages in different languages.

<h1>Concepts Tested</h1>

- Exploratory data analysis
- Time Series forecasting- ARIMA, SARIMAX, and Prophet

### Project Goal

To analyze and forecast web traffic data using time series analysis techniques to provide insights and recommendations for strategic decision-making.

### Objective

- To clean and preprocess the dataset.
- To analyze the structure and characteristics of the dataset.
- To apply time series analysis techniques including ARIMA, SARIMAX, and Facebook Prophet for forecasting.
- To compare the performance of different models and provide actionable recommendations based on the findings.

### Recommendations

- Use ARIMA and SARIMAX models for short-term forecasting due to their lower Mean Absolute Percentage Error (MAPE).
- Utilize Facebook Prophet for long-term forecasting as it handles seasonality and holidays effectively.
- Implement the best-performing model for each language/region to improve the accuracy of forecasts.
- Regularly update the models with new data to maintain forecast accuracy.

### Data-Driven

- Conducted extensive exploratory data analysis to understand the dataset.
- Performed time series decomposition and stationarity tests.
- Built and evaluated ARIMA, SARIMAX, and Facebook Prophet models.
- Compared the performance of models using MAPE and other relevant metrics.

### Audience

- Data analysts and data scientists interested in time series forecasting.
- Business stakeholders looking to leverage web traffic data for strategic decisions.
- Technical teams responsible for implementing and maintaining forecasting models.

### Key Questions Explored

- What are the characteristics and structure of the dataset?
- How can the dataset be cleaned and preprocessed for time series analysis?
- Is the data stationary, and what methods can be used to achieve stationarity?
- How do different time series models (ARIMA, SARIMAX, Facebook Prophet) perform in forecasting?
- What insights and recommendations can be derived from the forecast results?

## Key Concepts Explored

1. **Exploratory Data Analysis (EDA)**:

   - **Structure and Characteristics**: Examining the dataset's structure, data types, and summary statistics.
   - **Null Values**: Identifying and understanding the reasons for missing values.
   - **Page Name Format**: Splitting and extracting information such as title, language, access type, and access origin.
   - **Visualization**: Using plots to understand distributions and relationships within the data.

2. **Data Preprocessing**:

   - **Handling Missing Values**: Implementing strategies for dealing with null values.
   - **Feature Extraction**: Separating and creating new features from existing columns (e.g., title, language).
   - **Data Transformation**: Converting data into a suitable format for time series modeling (e.g., pivoting).

3. **Stationarity and Time Series Analysis**:

   - **Stationarity Check**: Using the Dickey-Fuller test to assess stationarity.
   - **Methods for Stationarity**: Applying techniques like differencing and decomposition to achieve stationarity.
   - **ACF and PACF Plots**: Plotting autocorrelation and partial autocorrelation functions to identify patterns in the data.

4. **Modeling and Forecasting**:

   - **ARIMA Model**: Creating and training an ARIMA model for time series forecasting.
   - **SARIMAX Model**: Incorporating exogenous variables in a SARIMAX model for enhanced forecasting accuracy.
   - **Facebook Prophet**: Utilizing Facebook Prophet for robust time series forecasting, especially for long-term trends.

5. **Model Evaluation**:

   - **Parameter Tuning**: Using techniques like grid search to find the best parameters for models.
   - **Forecasting Performance**: Comparing model performance across different languages and regions using metrics like MAPE.
   - **Insights and Recommendations**: Drawing actionable insights from model comparisons and forecast results.

6. **Automating the Process**:
   - **Pipeline Creation**: Defining functions for data preprocessing, model training, and forecasting to streamline the workflow.
   - **Comparative Analysis**: Evaluating forecast results for multiple series and making informed recommendations based on the analysis.

This detailed approach ensures a comprehensive understanding of web traffic patterns and facilitates accurate and actionable forecasting for strategic decision-making.

### Questionnaire

#### Defining the problem statements and where can this and modifications of this be used?

- As a member of the Data Science team at this company, the task is to analyze the per-page view report for a dataset containing 145,000 Wikipedia pages over a span of 550 days. The goal is to forecast the number of views for each page to predict and optimize ad placement for clients belonging to different regions.

#### Write 3 inferences you made from the data visualizations

- Most used access type is all access, mobile-web and desktop are almost same.
- Most common search language is english followed by japnese
- Seasonality was found to be 7 days
- Most common access origin is through all agents.

#### What does the decomposition of series do?

- Decomposition of a time series refers to the process of breaking down the series into its 3 components: trend, seasonality, and noise (or residual).

#### What level of differencing gave you a stationary series?

- Single level

#### Difference between arima, sarima & sarimax.

- ARIMA
  -- ARIMA models are used to model and forecast time series data that exhibit non-stationarity
  -- ARIMA does not explicitly handle seasonality in the data
- SARIMA
  -- SARIMA extends ARIMA to handle seasonal patterns in time series data.
- SARIMAX
  -- SARIMAX further extends SARIMA by allowing for the inclusion of exogenous variables, which are external factors that may influence the time series being modeled.

#### Compare the number of views in different languages

<table border="1">
  <tr>
    <th>LANGUAGE</th>
    <th>count</th>
  </tr>
  <tr>
    <td>English</td>
    <td>22486</td>
  </tr>
  <tr>
    <td>Japanese</td>
    <td>19295</td>
  </tr>
  <tr>
    <td>Germal</td>
    <td>17362</td>
  </tr>
  <tr>
    <td>French</td>
    <td>16948</td>
  </tr>
  <tr>
    <td>Chinese</td>
    <td>15211</td>
  </tr>
  <tr>
    <td>Russian</td>
    <td>14270</td>
  </tr>
  <tr>
    <td>Spanish</td>
    <td>13551</td>
  </tr>
  <tr>
    <td>NO_Language</td>
    <td>14,494</td>
  </tr>

</table>

#### What other methods other than grid search would be suitable to get the model for all languages?

- Ensemble Methods
- Cross-Validation
- Random Search
