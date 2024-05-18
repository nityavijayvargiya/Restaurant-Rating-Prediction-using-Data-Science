# Restaurant-Rating-Prediction-using-Data-Science
Task assigned by Cognifyz Technologies On Restaurant Data Analysis and Prediction in 3 Levels each divided into further tasks.

During my Data Science Internship at Cognifyz Technologies (April-May 2024), I was tasked with analyzing and making predictions on a large restaurant dataset. The project was divided into three levels, each with specific tasks. I successfully built a regression model to predict restaurant ratings, achieving an impressive accuracy of 98%. Here's a more structured breakdown of the project:

1. Data Analysis and Insights: I explored the restaurant data to uncover meaningful patterns and trends. This likely involved tasks like identifying popular cuisines, analyzing customer demographics, and understanding factors influencing ratings.

2. Level-Based Tasks: Cognifyz provided a structured approach to the project, dividing it into three levels with further subtasks. This ensured a focused and progressive learning experience.

3. High-Accuracy Regression Model: The core deliverable of the internship was the development of a regression model. This model effectively predicts restaurant ratings based on the analyzed data, achieving a remarkable accuracy of 98%.
   
Overall, this internship at Cognifyz Technologies allowed me to gain valuable experience in data Science, model building, and extracting valuable insights from the restaurant industry.

**Level 1: Data Exploration and Analysis**

- **Objective:** Gain foundational skills in data exploration, descriptive analysis, and geospatial insights for a restaurant dataset.
- **Tasks:**
- Explore data structure, address missing values, perform data conversions, and analyze class imbalances.
- Calculate statistical measures, investigate distributions of categorical variables, and identify top cuisines and cities.

**Level 2: Advanced Analysis**

- **Objective:** Enhance insights from the restaurant dataset through tasks focused on table booking, delivery services, pricing, and feature engineering.
- **Tasks:**
-  Calculate percentages of table booking and online delivery, compare ratings for restaurants with and without booking, and analyze online delivery availability.
-  Determine the most common price range, calculate average ratings for each price range, and associate colors with top-rated ranges.
-   Leverage feature engineering techniques for enhanced data intelligence.


**Level 3: Predictive Modeling and Insights**

- **Objective:** Perform predictive modeling, customer preference analysis, and data visualization to extract deeper insights.
- **Tasks:**
- Build regression models to predict restaurant ratings, evaluate model performance, and compare algorithms.
- Analyze the relationship between cuisine types and ratings, identify popular cuisines, and determine specific cuisines with higher ratings.
- Create visualizations to depict rating distributions, compare average ratings, and visualize feature relationships.

---

# Project Summary
**Data Exploration and Analysis (Level 1)**

- We delved into the data, ensuring its integrity through comprehensive exploration and preprocessing.
- Descriptive analysis revealed key statistics, popular cuisines and cities.
- Geospatial insights visualized restaurant locations and correlations with ratings.
  
**Advanced Analysis (Level 2)**

- Table booking and online delivery data unveiled customer preferences and service availability.
- The most common price range linked to the highest average rating was identified.
- Feature engineering techniques enhanced the dataset's informational value.

**Predictive Modeling and Insights (Level 3)**

- Regression models were built to predict restaurant ratings, with Random Forest excelling.
- The relationship between cuisine types and ratings was explored.
- Data visualizations provided valuable insights into rating distributions.
- Overall Insights

The project encompassed in-depth data analysis, predictive modeling, and customer preference understanding. These findings offer valuable tools for data-driven decision-making, customer insights, and restaurant rating prediction.

#Detailed Breakdown

**1. Data Overview (Level 1)**

- Analyzed a dataset containing 9,551 restaurants with 21 features.
- Minimal null values were present, primarily in the "Cuisines" column.
- Data type conversion was required.
- The "Aggregate rating" distribution exhibited a imbalanced  pattern.
  
**2. Descriptive Statistics (Level 1)**

- Key statistical metrics were identified for numerical columns.
- Countries with the most restaurants were represented by codes 1 and 216. Cities like New Delhi, Gurgaon, and Noida had the highest restaurant counts.
- North Indian and Chinese cuisines were most popular.
  
**3. Geospatial Analysis (Level 1)**

- Restaurants were concentrated in North America and Asia (particularly India).
- New Delhi led in restaurant presence, followed by Gurgaon, Noida, and Faridabad.
- Latitude showed no correlation with ratings, while longitude exhibited a negative correlation.
  
**4. Service Analysis (Level 2)**

- Roughly 12.12% of restaurants offered table booking, and 25.66% provided online delivery.
- Restaurants with table booking had a significantly higher average rating (3.44) compared to those without (2.56).
- Online delivery was more prevalent in restaurants with medium-priced food.
  
**5. Price Range Analysis (Level 2)**

- Price range 1 was the most common.
- Restaurants in price range 4 achieved the highest average rating, followed by 3, 2, and 1.
  
**6. Feature Engineering (Level 2)**

- Two new features were created: "Restaurant Name Length" and "Address Length" based on corresponding lengths.
- Categorical variable encoding introduced binary columns "Has Table Booking" and "Has Online Delivery."

**7. Predictive Modeling (Level 3)**

- Three regression models (Linear Regression, Decision Tree, Random Forest) were employed for rating prediction.
- Random Forest outperformed others with the lowest Mean Squared Error (MSE) and highest R-squared value.
  
**8. Customer Preference Analysis (Level 3)**

- Cuisines like cafe, mughlai, north Indian, and fast food significantly impacted ratings.
- North Indian and Chinese cuisines showed greater rating variability, while cafe and fast food remained consistent.
- Based on votes, North Indian, Mughlai, and Chinese were the most popular.
- Italian, Hawaiian, Seafood, Tea, Sandwich, Continental, and Indian cuisines received the highest average ratings.

**9. Data Visualization (Level 3)**

- Restaurant ratings followed a negatively skewed distribution.
- Italian, Hawaiian, Seafood, Tea, Sandwich, Continental, and Indian cuisines had the highest average ratings.
- Cities like Inner City, Quezon City, and Makati City emerged as most popular based on average rating.
- A positive correlation between votes and restaurant ratings was observed.

  
This comprehensive project journey provided valuable insights into restaurant data, customer preferences, pricing, services, and predictive modeling, contributing to a holistic understanding of the restaurant industry.

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
