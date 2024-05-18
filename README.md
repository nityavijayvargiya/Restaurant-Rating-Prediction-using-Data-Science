# Restaurant-Rating-Prediction-using-Data-Science
Task assigned by Cognifyz Technologies On Restaurant Data Analysis and Prediction in 3 Levels each divided into further tasks.

During my Data Science Internship at Cognifyz Technologies (April-May 2024), I was tasked with analyzing and making predictions on a large restaurant dataset. The project was divided into three levels, each with specific tasks. I successfully built a regression model to predict restaurant ratings, achieving an impressive accuracy of 98%. Here's a more structured breakdown of the project:

1. Data Analysis and Insights: I explored the restaurant data to uncover meaningful patterns and trends. This likely involved tasks like identifying popular cuisines, analyzing customer demographics, and understanding factors influencing ratings.

2. Level-Based Tasks: Cognifyz provided a structured approach to the project, dividing it into three levels with further subtasks. This ensured a focused and progressive learning experience.

3. High-Accuracy Regression Model: The core deliverable of the internship was the development of a regression model. This model effectively predicts restaurant ratings based on the analyzed data, achieving a remarkable accuracy of 98%.
   
Overall, this internship at Cognifyz Technologies allowed me to gain valuable experience in data analysis, model building, and extracting valuable insights from the restaurant industry.



## Task 1
**Objective:** Build a machine learning model to predict the aggregate rating of a restaurant based on other features.

**Steps:**
* Preprocess the dataset by handling missing values, encoding categorical variables, and splitting the data into training and testing sets.
* Select a regression algorithm (e.g., linear regression, decision tree regression) and train it on the training data.
* Evaluate the model's performance using appropriate regression metrics (e.g., mean squared error, R-squared) on the testing data.
* Interpret the model's results and analyze the most influential features affecting restaurant ratings.

  
## Task 2
**Objective:** Create a restaurant recommendation system based on user preferences.

**Steps:**
* Preprocess the dataset by handling missing values and encoding categorical variables.
* Determine the criteria for restaurant recommendations (e.g., cuisine preference, price range).
* Implement a content-based filtering approach where users are recommended restaurants similar to their preferred criteria.
* Test the recommendation system by providing sample user preferences and evaluating the quality of recommendations.


## Task 3
**Objective:** Develop a machine learning model toclassify restaurants based on their cuisines.

**Steps:**

* Preprocess the dataset by handling missing values and encoding categorical variables.
* Split the data into training and testing sets.
* Select a classification algorithm (e.g., logistic regression, random forest) and train it on the training data.
* Evaluate the model's performance using appropriate classification metrics (e.g., accuracy, precision, recall) on the testing data.
* Analyze the model's performance across different cuisines and identify any challenges or biases.

## Task 4
**Objective:** Perform a geographical analysis of the restaurants in the dataset.

**Steps:**

* Explore the latitude and longitude coordinates of the restaurants and visualize their distribution on a map.
* Group the restaurants by city or locality and analyze the concentration of restaurants in different areas.
* Calculate statistics such as the average ratings, cuisines, or price ranges by city or locality.
* Identify any interesting insights or patterns related to the locations of the restaurants.


# Dataset
CSV file is uploaded here in the repository.

# Platform
Google Colab

# Libraries
pandas, numpy, matplotlib, seaborn, scikitlearn

# Data Preprocessing and splitting
* Cuisines had 9 null values So dropped the values.
* Removed features that will inhibit model performance
* The target variables were imbalnce.
* Split training data and test data in the ratio 8:2

# Model Evaluation
* My restaurant rating prediction model obtained a R2 score of 0.98.
* Decisiom tree performs better on the model than linear regression.

# Insights from EDA
* Expensive restaurants tend to have higher ratings.
* Visualized the geospatial distribution of restaurants on the map using their co-ordinates.
* New Delhi has the highest number of restaurants.
* 'North Indian' is the most popular cuisine overall.
