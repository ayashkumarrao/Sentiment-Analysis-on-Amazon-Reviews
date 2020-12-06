![Python](https://img.shields.io/badge/Python-3.x-red) ![ML](https://img.shields.io/badge/Machine-Learning-blue) ![Status](https://img.shields.io/badge/Status-Completed-success) ![DS](https://img.shields.io/badge/Data-Science-ff69b4)

# Sentiment-Analysis-on-Amazon-Reviews

_Dataset link_:
[[ Link ]](https://media.githubusercontent.com/media/juliandariomirandacalle/NLP_Notebooks/master/01-Introduction_NLP/Customer_Reviews.csv)

_Dataset size_:
10,000 x 9 [ rows x columns ] 

| Column headers             | Description                                                       |
| -------------------------  | ----------------------------------------------------------------  |
|  ProductId                 |  ID of the referenced product by the customer.                    |
|  UserId                    |  Registered user ID.                                              |
|  ProfileName               |  Registered user profile name.                                    |
|  HelpfulnessNumerator      |  Number of users who found the review helpful.                    |
|  HelpfulnessDenominator    |  Number of users who voted whether the review was helpful or not. |
|  Score                     |  Rating between 1 and 5.                                          |
|  Time                      |  Timestamp of the review.                                         |
|  Summary                   |  Brief summary of the review.                                     |
|  Text                      |  Text of the review.                                              |


# Project Outline:

<u>Business motivation</u> :  
For ecommerce sites and outfitters to stay competitive and innovate, they must be able to draw and hold dedicated customers. One particularly effective approach in recent years has been to build personalized recommendation engines into their platform or interface. Determining the specific topics and sentiments associated with given sports and outdoors products is essential in building a recommendation engine. This project is mainly to understand the concepts covered in class and apply them to a specific domain.

<u>Problem formulation</u> :

1. Explore and Process the data in order to glean basic insights about the data and prep to utilize models

2. Finding a classification model that works best with the data.

3. Understanding the topics and words that describe the broad categories of Sports and Outdoors product sold over Amazon.

4. Given the data and model performance, determine what is the best course of actions going forward.

## Approach:

* EDA with WordCloud

* Preprocessing

* Model data
  Classification / Sentiment Analysis
        * Logistic Regression got F1 score of 0.9526

* Summarize Findings and Proposed Further Work

# Conclusions
In this case, we cleaned up and featurized an Amazon reviews dataset and built some classification models on these featurizations to predict sentiment. We saw that bag-of-words. Through increase the set of n-grams we used from 1-grams to up to 4-grams, we were able to get our logistic regression model accuracy up to 95%.
