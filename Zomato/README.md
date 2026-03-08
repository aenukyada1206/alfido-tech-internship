**Zomato Restaurant Data Analysis \& Rating Prediction**



**Project Overview:**

This project focuses on Exploratory Data Analysis (EDA) and Machine Learning modeling using the Zomato restaurant dataset.

The objective of the project is to analyze restaurant data and identify key factors that influence restaurant ratings. Using data preprocessing techniques and machine learning algorithms, a predictive model is built to estimate restaurant ratings based on various features such as cuisine type, location, online ordering availability, and cost.

This project demonstrates the complete data science workflow, including data cleaning, visualization, feature engineering, and model building using Scikit-learn.



**Objectives:**

The main goals of this project are:

* Perform data cleaning and preprocessing
* Conduct Exploratory Data Analysis (EDA)
* Identify patterns affecting restaurant ratings
* Visualize important relationships in the dataset
* Build a machine learning model to predict restaurant ratings
* Evaluate the model using performance metrics



**Dataset Description:**

The dataset contains information about restaurants listed on Zomato.

Key Features:

|Feature|Description|
|-|-|
|Restaurant Name|Name of the restaurant|
|Location|Area where the restaurant is located|
|Cuisines |Type of cuisines served|
|Average Cost for two |Estimated cost for two people|
|Online Order|Whether online ordering is available|
|Table Booking|Whether table booking is available|
|Restaurant Type|Type of restaurant|
|Votes|Number of user votes|
|Rating|Restaurant rating|





**Technologies Used:**



**Programming Language**

* Python



**Libraries**

* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn



**Development Environment**

* Jupyter Notebook / Google Colab



**Project Workflow:**



1\. Data Loading

The dataset is loaded using Pandas and the structure of the dataset is explored.

Tasks performed:

* Viewing dataset shape
* Inspecting column names
* Displaying sample records





2\. Data Cleaning \& Preprocessing

Real-world datasets often contain missing or inconsistent values. Data cleaning is performed to ensure data quality.

Key steps include:

* Handling missing values
* Removing unnecessary columns
* Cleaning text fields
* Converting categorical variables
* Preparing data for machine learning



3\. Exploratory Data Analysis (EDA)

EDA helps in understanding the patterns and relationships within the dataset.

**Analysis Performed**

* Distribution of restaurant ratings
* Restaurant types available
* Online order availability
* Table booking availability
* Cost vs rating relationship
* Cuisine popularity analysis
* Votes vs rating relationship

**Visualization tools used:**

* Seaborn
* Matplotlib



**Key Insights:**

Some important insights discovered from the dataset include:

* Most restaurants have ratings between 3.5 and 4.5
* Online ordering is available in a large number of restaurants
* Restaurants with more votes generally tend to have higher ratings
* Some cuisines are significantly more popular than others
* Higher cost does not always guarantee higher ratings



**Machine Learning Model:**

A Random Forest Regressor model is implemented using Scikit-learn to predict restaurant ratings.

Steps in Model Building:

1. Feature selection
2. Train-test data splitting
3. Data preprocessing
4. Model training
5. Model evaluation



**Libraries Used:**

from sklearn.model\_selection import train\_test\_split

from sklearn.preprocessing import OneHotEncoder

from sklearn.compose import ColumnTransformer

from sklearn.impute import SimpleImputer

from sklearn.ensemble import RandomForestRegressor

from sklearn.metrics import mean\_squared\_error, r2\_score



**Model Evaluation:**

The model performance is evaluated using the following metrics:

•	Mean Squared Error (MSE)

•	R² Score

These metrics help determine how accurately the model predicts restaurant ratings.



**Future Improvements:**

This project can be further improved by:

* Using advanced models like XGBoost or Gradient Boosting
* Applying hyperparameter tuning
* Creating interactive dashboards using Power BI or Tableau
* Deploying the model using Flask or Streamlit



**Conclusion:**

This project demonstrates how data analysis and machine learning techniques can be used to extract insights from real-world datasets and build predictive models.

Through data preprocessing, visualization, and machine learning, the project identifies important factors affecting restaurant ratings and provides a framework for rating prediction.



**Author:**

Student Project – Data Science / Machine Learning

Developed as part of academic coursework to demonstrate practical implementation of EDA and machine learning using Python and Scikit-learn.





