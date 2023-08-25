# Sectoral Analysis for Indian Economy
 Top-Down Investment Strategy Optimization with Time Series Forecasting 

**Project Title: Sectoral Analysis for Indian Economy**

**1. Data Collection and Preprocessing:**
- Identify potential features from sectoral annual reports, research papers, government websites, etc.
- Collect relevant data from sources like CMIE & World Bank.
- Import data into Jupyter Notebook.
- Trim spaces, remove commas, and set appropriate indices.
- Handle missing values and outliers.

**2. Exploratory Data Analysis (EDA):**
- Generate summary statistics for the dataset.
- Create distribution plots and line plots for a deeper understanding.
- Explore relationships between variables using line plots.

**3. Feature Selection and Engineering:**
- Perform correlation analysis to identify high correlations.
- Drop features with high correlation coefficients to reduce multicollinearity.
- Use Granger causality test to determine causal relationships.
- Adjust the dataset based on lag order from Granger causality.

**4. Model Building using Multiple Linear Regression (MLR):**
- Split data into training and testing sets.
- Apply scaling transformations to predictor variables.
- Check MLR assumptions (linearity, independence, homoscedasticity, normality).
- Fit MLR model using stepwise backward elimination.
- Validate model using appropriate evaluation metrics.
- Compare actual vs. predicted values.

**5. Time Series Modeling using SARIMAX:**
- Create line plots to visualize time series data.
- Perform time series decomposition.
- Check stationarity visually and using Dickey-Fuller test.
- Apply differencing for stationarity.
- Choose optimal orders for SARIMA model based on AIC, BIC, and HQIC.
- Fit and validate SARIMA model.

**6. Iterative Improvement (Dynamic Model):**
- Gather feedback from stakeholders and domain experts.
- Identify areas for improvement based on feedback.
- Update pipeline and models iteratively.
- Continuously incorporate new data for model refinement.

**7. Forecasting and Model Selection:**
- Make forecasts using the validated models.
- Compare the performance of different models.
- Choose the most appropriate model based on evaluation metrics.
- Generate forecasts for risk-adjusted returns in the investment strategy.

Remember, this pipeline is a general outline of the steps you can follow in your project. Adjustments might be needed based on specific data characteristics and project requirements.