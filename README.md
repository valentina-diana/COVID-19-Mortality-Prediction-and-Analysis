# COVID-19 Mortality Prediction and Analysis

## **Introduction**

This project analyzes confirmed COVID-19 cases and implements 7 mortality prediction algorithms. The main goal is to identify the algorithm that offers the best performance in estimating mortality based on the available variables. The project includes an initial data analysis (EDA) and detailed visualizations, followed by the training and comparison of predictive models.

The data was extracted from **Google Cloud BigQuery**, using a public COVID-19 dataset. The connection to BigQuery was made through the **Google API** and a **JSON authentication file**.

## **Objectives**

- **Data Extraction:** Accessing the COVID-19 datasets from Google BigQuery.
- **Data Cleaning and Transformation:** Processing and aggregating data for predictive analysis.
- **Exploratory Data Analysis:** Creating graphs and analyzing relationships between variables.
- **Model Development:** Training and evaluating 7 machine learning models for mortality prediction.
- **Model Comparison:** Comparing the performance of the algorithms.
- **Visualization:** Creating visualizations for interpreting results.

## **Data Procurement**

The dataset used in this project was extracted from **Google Cloud BigQuery** using the following technologies:

- **BigQuery API:** Querying the database.
- **JSON Authentication File:** Secure access to BigQuery via the JSON file.
- **Google Colab Integration:** Integrating Google Colab for direct access to the data.

The dataset contains detailed information about COVID-19 cases, including variables such as confirmed cases, deaths, recovered cases, and other relevant factors.

## **Algorithms Used**

The project implements the following 7 prediction algorithms:

1. **Linear Regression**
2. **Gradient Boosted Trees**
3. **Random Forest**
4. **Elastic Net**
5. **Decision Tree Regressor**
6. **Lasso Regression**
7. **Support Vector Machines (SVM)**

## **Data Structure**

The data used comes from the **world_covid** table and includes the following columns:

- **refresh_date:** The date of the update.
- **country_name:** The name of the country.
- **state_name:** The name of the state.
- **confirmed:** The number of confirmed cases.
- **deaths:** The number of deaths.
- **recovered:** The number of recovered cases.

## **Key Features**

1. **Data Extraction and Cleaning:**
   - Collecting and cleaning data from BigQuery for further analysis.

2. **Exploratory Data Analysis (EDA):**
   - Creating descriptive graphs to explore the data, including distributions of cases and deaths across countries and years, and correlations between relevant variables.

3. **Predictive Modeling:**
   - Implementing and training 7 algorithms for mortality prediction.

4. **Model Comparison:**
   - Evaluating the models using metrics such as **R²** and **RMSE**, to identify the most performant algorithm.

5. **Visualization:**
   - Creating comparative and predictive visualizations for interpreting the results.

## **Frameworks and Technologies Used**

- **Google Colab:** Development and execution environment.
- **PySpark:** Processing and analyzing large datasets.
- **Google BigQuery:** Storing and querying the datasets.
- **Pandas:** Data manipulation.
- **Matplotlib & Seaborn:** Data visualization.
- **Scikit-learn:** Implementing machine learning models.

## **Implementation Steps**

1. **Setup Environment:** Configuring Google Colab and authenticating to BigQuery.
2. **Data Extraction and Cleaning:** Collecting and processing the data.
3. **Exploratory Data Analysis:** Descriptive analysis and creating graphs.
4. **Model Training and Evaluation:** Training the models and evaluating them.
5. **Visualization and Insights:** Generating comparative graphs and interpreting the results.

## **Model Performance Metrics**

Each model was evaluated using the following metrics:

- **R² (Coefficient of Determination):** Measures the proportion of variance explained by the model.
- **RMSE (Root Mean Squared Error):** Evaluates the magnitude of error and penalizes large deviations in predictions.

## **Conclusion**

The project combines descriptive analysis and prediction to provide a detailed insight into COVID-19 mortality. The initial data analysis provided a solid foundation for identifying relevant factors, and model comparison allowed for selecting the algorithm with the best performance in mortality prediction.
