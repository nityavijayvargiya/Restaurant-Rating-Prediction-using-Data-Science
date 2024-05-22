# Restaurant-Rating-Prediction-using-Data-Science
Task assigned by Cognifyz Technologies On Restaurant Data Analysis and Prediction in 3 Levels each divided into further tasks.

During my Data Science Internship at Cognifyz Technologies (April-May 2024), I was tasked with analyzing and making predictions on a large restaurant dataset. The project was divided into three levels, each with specific tasks. I successfully built a regression model to predict restaurant ratings, achieving an impressive accuracy of 98%. Here's a more structured breakdown of the project:

1. Data Analysis and Insights: I explored the restaurant data to uncover meaningful patterns and trends. This likely involved tasks like identifying popular cuisines, analyzing customer demographics, and understanding factors influencing ratings.

2. Level-Based Tasks: Cognifyz provided a structured approach to the project, dividing it into three levels with further subtasks. This ensured a focused and progressive learning experience.

3. High-Accuracy Regression Model: The core deliverable of the internship was the development of a regression model. This model effectively predicts restaurant ratings based on the analyzed data, achieving a remarkable accuracy of 98%.
   
Overall, this internship at Cognifyz Technologies allowed me to gain valuable experience in data Science, model building, and extracting valuable insights from the restaurant industry.

**Level 1: Data Exploration and Analysis**

- **Objective:** Gain foundational skills in data exploration, descriptive analysis, and geospatial insights for a restaurant dataset.
 **Tasks:**
- Explore data structure, address missing values, perform data conversions, and analyze class imbalances.
- Calculate statistical measures, investigate distributions of categorical variables, and identify top cuisines and cities.

**Level 2: Advanced Analysis**

- **Objective:** Enhance insights from the restaurant dataset through tasks focused on table booking, delivery services, pricing, and feature engineering.
 **Tasks:**
-  Calculate percentages of table booking and online delivery, compare ratings for restaurants with and without booking, and analyze online delivery availability.
-  Determine the most common price range, calculate average ratings for each price range, and associate colors with top-rated ranges.
-   Leverage feature engineering techniques for enhanced data intelligence.


**Level 3: Predictive Modeling and Insights**

- **Objective:** Perform predictive modeling, customer preference analysis, and data visualization to extract deeper insights.
 **Tasks:**
- Build regression models to predict restaurant ratings, evaluate model performance, and compare algorithms.
- Analyze the relationship between cuisine types and ratings, identify popular cuisines, and determine specific cuisines with higher ratings.
- Create visualizations to depict rating distributions, compare average ratings, and visualize feature relationships.

---

#Detailed Breakdown of what I learned from each level.

**1. Data Overview (Level 1)**

- Dataset Characteristics: I analyzed a dataset containing 9,551 restaurants described by 21 features. There were very few missing values, mainly concentrated in the "Cuisines" column.
- Data Preparation: The data required some preprocessing steps, including converting features to the appropriate data types.
- Rating Distribution: I observed an uneven distribution in the "Aggregate rating" column. This suggests there might be more data points clustered at certain rating values than others.
  
**2. Descriptive Statistics (Level 1)**

- Restaurant Distribution: I analyzed key statistical metrics for numerical columns to understand restaurant distribution. Countries with codes 1 and 216 had the highest number of restaurants, likely corresponding to locations with a high concentration of restaurants (e.g., a specific country). Looking at city-level data, New Delhi, Gurgaon, and Noida emerged as the areas with the most restaurants.
- Cuisine Popularity: North Indian and Chinese cuisines were the most popular choices based on our analysis.
  
**3. Geospatial Analysis (Level 1)**

- Geographic Distribution: My analysis revealed a clear concentration of restaurants in North America and Asia, particularly India. This highlights potential regional preferences in cuisine or dining habits.
- City Breakdown: Within India, New Delhi emerged as the city with the most restaurants, followed by Gurgaon, Noida, and Faridabad. This suggests a higher density of restaurants in these urban centers.
- Location and Ratings: Interestingly, I found no significant correlation between restaurant latitude and ratings. However, longitude did show a negative correlation with ratings. This could indicate potential regional trends in restaurant quality or pricing that require further investigation.
  
**4. Service Analysis (Level 2)**
- Online Services: In analysis revealed that only about 12.12% of restaurants offered online table booking, while delivery services were more common, reaching 25.66%.
- Impact of Table Booking: Interestingly, restaurants that provided table booking options boasted a significantly higher average rating (3.44) compared to those without (2.56). This suggests a potential correlation between offering table booking and customer satisfaction.
- Delivery and Price Point: I observed a trend where online delivery was more prevalent in restaurants with medium-priced food. This could be due to factors like affordability or menu options typically associated with delivery.
  
**5. Price Range Analysis (Level 2)**

- The most common Price range was 1.
- Restaurants in price range 4 achieved the highest average rating.
  
**6. Feature Engineering (Level 2)**

- Two new features were created: "Restaurant Name Length" and "Address Length" .
- Binary columns "Has Table Booking" and "Has Online Delivery" were introduced encoding categorical values.

**7. Predictive Modeling (Level 3)**

- Four regression models (Linear Regression, Decision Tree, Random Forest and AdaBooster) were employed for rating prediction.
- Random Forest and Adabooster outperformed others with the lowest Mean Squared Error (MSE) and highest R-squared value.
  
**8. Customer Preference Analysis (Level 3)**
- Impact on Ratings: Cuisines like cafes, Mughlai, North Indian, and fast food have a substantial influence on restaurant ratings. However, their performance can vary considerably.
- Rating Distribution: North Indian and Chinese restaurants exhibit a wider range of ratings, with some excelling and others falling short. In contrast, cafes and fast food tend to have more predictable ratings, suggesting a more standardized experience.
- Popularity by Volume: North Indian, Mughlai, and Chinese cuisines are clear leaders in terms of voting volume, indicating their widespread presence and customer interest.
- Popularity by Rating: Diners seem to have a strong preference for Italian, Hawaiian, Seafood, Tea, Sandwich, Continental, and Indian cuisines, reflected in their consistently high average ratings.

**9. Data Visualization (Level 3)**

- Rating Distribution: Our visualizations reveal a negative skew in restaurant ratings. This means there are more restaurants clustered around average scores, with fewer on the extremes of very high or very low ratings.
- Cuisine Preferences: When it comes to cuisine, Italian, Hawaiian, Seafood, Tea, Sandwich, Continental, and Indian stand out. These cuisines boast the highest average ratings, suggesting a strong preference among diners.
- Location Insights: While average rating is a valuable metric, location also plays a role. Visualizations can highlight geographic trends. Cities like Inner City, Quezon City, and Makati City might be popular for reasons beyond just having the highest average ratings. There could be a higher concentration of specific cuisines or unique dining experiences that attract customers.
- The Power of Reviews: Visualizations often confirm a positive correlation between the number of votes (reviews) and average rating. This suggests that more popular restaurants tend to have more reviews, which can influence the overall average score.

  
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
* AdaBooster performs the best and Random forest was as good as the other.

# Insights from Exploratory Data Analysis.
* Expensive restaurants tend to have higher ratings.
* Visualized the geospatial distribution of restaurants on the map using their co-ordinates.
* New Delhi has the highest number of restaurants.
* 'North Indian' is the most popular cuisine overall.

  ## Reference
 - [Cognifyz Technologies Data Science Internship]([https://www.cognifyz.com/careers/career.html](https://cognifyz.com/))
