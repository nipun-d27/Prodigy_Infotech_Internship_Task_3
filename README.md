# Prodigy_Infotech_Internship_Task_3
Using the Online shoppers purchasing intention dataset building a decision tree classifier to predict whether a customer will purchase the product or service based on the behavioral data.

**Decision Tree Classifier on Online Shoppers Purchasing Intention Dataset
Objective:**
The objective of this project was to develop a Decision Tree Classifier to predict whether a user will make a purchase on an e-commerce website based on their session behavior and demographic characteristics.

**Dataset Overview:**
The dataset used for this project was the Online Shoppers Purchasing Intention Dataset from the UCI Machine Learning Repository. It includes data on over 12,000 user sessions, with features such as:
Number of pages visited
Duration on informational and product pages
Bounce rates and exit rates
Visitor type (New or Returning)
Weekend session flag
Traffic type
Month of visit
Target variable: Revenue (indicating whether a purchase was made)

**Data Exploration and Preprocessing:**
Exploratory Data Analysis (EDA) was performed to understand the structure of the data, check for missing values, and assess class distributions. Categorical features such as Month, VisitorType, and Weekend were encoded appropriately using label encoding and one-hot encoding. The target variable Revenue was converted to binary format (1 for purchase, 0 for no purchase).

**Train-Test Split:**
The dataset was split into training and testing subsets using an 80-20 split with train_test_split. This ensured that the model would be evaluated on unseen data.

**Model Training:**
A Decision Tree Classifier was trained using the training data. The model learned to split the data based on various features that help determine whether a user is likely to make a purchase.

**Model Evaluation:**
The model's performance was evaluated using the accuracy score, classification report, and confusion matrix. The model achieved an accuracy score of 0.85888, indicating that it correctly predicted the outcome approximately 86% of the time on unseen data.

**Feature Importance:**
We visualized the top contributing features to the model's predictions. The most influential features included ExitRates, PageValues, ProductRelated_Duration, and BounceRates, highlighting their importance in user purchase behavior.

**Decision Tree Visualization:**
To better understand how the model makes decisions, we plotted the trained decision tree using plot_tree() with a limited depth for clarity. This visualization helped illustrate how feature values lead to different prediction outcomes.

**Conclusion:**
Based on the trained Decision Tree Classifier and the observed accuracy score of 0.85888, we conclude that the model is effective at predicting whether a customer will make a purchase based on their session behavior. It can be used as a decision-support tool in e-commerce settings to identify users who are likely to buy, enabling more targeted marketing and personalized user engagement strategies.
