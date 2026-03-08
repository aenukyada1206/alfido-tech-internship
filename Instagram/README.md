#### **Instagram Data Analysis**



**Project Overview:**



This project performs Exploratory Data Analysis (EDA) and Machine Learning using Scikit-Learn on an Instagram dataset.

The goal is to analyze user behavior, engagement patterns, and predict engagement based on user interactions such as likes and comments.



The project explores relationships between users, photos, likes, comments, hashtags, and followers to extract meaningful insights from the dataset.



**Objectives:**



* Understand Instagram user activity and engagement.
* Perform data cleaning and exploratory data analysis (EDA).
* Identify most active users and popular hashtags.
* Analyze likes and comments distribution.
* Build a Machine Learning model using Scikit-Learn to predict engagement.





**Dataset:**



The dataset contains multiple relational tables representing Instagram activity.



**Files included:**



* users.csv → Information about users
* photos.csv → Photos posted by users
* likes.csv → Likes on photos
* comments.csv → Comments on photos
* tags.csv → Hashtags used in posts
* photo\_tags.csv → Mapping between photos and hashtags
* follows.csv → User follow relationships



**Technologies Used:**



* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* Google Colab/Jupyter Notebook



**Exploratory Data Analysis:**



* The following analyses were performed:
* Total number of users
* Total number of photos
* Average photos per user
* Most active users
* Most liked photos
* Most used hashtags
* Distribution of likes and comments
* Relationship between likes and comments



**Key Visualizations:**



* Top Active Users
* Popular Hashtags
* Likes Distribution
* Comments Distribution
* Likes vs Comments Scatter Plot
* Correlation Heatmap



**Machine Learning Model:**



A Linear Regression model was implemented using Scikit-Learn to predict engagement.



**Target Variable:**



**Engagement Score:**



Engagement = Likes + Comments



**Features:**



* Number of likes
* Number of comments



**Models Used:**



* Linear Regression
* Random Forest Regressor (for comparison)



**Evaluation Metrics:**



* Mean Squared Error (MSE)
* R² Score



**Key Insights:**



* A small percentage of users contribute most of the content.
* Some photos receive significantly higher engagement.
* Popular hashtags are reused frequently across posts.
* Likes and comments show a positive correlation.
* Engagement levels vary widely among posts.



**Project Workflow**:

1\. Import Libraries

2\. Load Dataset

3\. Data Cleaning

4\. Exploratory Data Analysis

5\. Data Visualization

6\. Feature Engineering

7\. Machine Learning Model

8\. Model Evaluation

9\. Insights \& Conclusion



**How to Run the Project:**



1\. Open the notebook in Google Colab / Jupyter Notebook.

2\. Upload the dataset files.

3\. Run all cells sequentially.

4\. The notebook will perform EDA and train the machine learning model.



**Conclusion:**



This project demonstrates how data analysis and machine learning can be used to understand user engagement patterns on social media platforms.



The insights obtained can help platforms identify popular content, analyze user behavior, and improve recommendation systems.



