# Stroke-Prediction-Hackathon-Kaggle
# Project Title

A brief description of what this project does and who it's for

# Machine Learning Hackathon - Stroke Prediction

## Overview

I recently participated in an exhilarating Machine Learning Hackathon hosted on Kaggle, focusing on a Stroke Prediction classification problem. This experience not only enriched my understanding of machine learning concepts but also provided a platform to apply theoretical knowledge to real-world problem-solving.

## Challenges 🚀

### Data Pre-processing Journey

#### Dealing with Missing Data
One of the initial challenges was handling missing records, particularly in the BMI feature. The solution involved a careful inspection of the dataset and replacing missing BMI values with the mean BMI, ensuring a comprehensive and representative dataset.

#### Unbalanced Dataset
The dataset presented an imbalance in the instances of stroke data, requiring a strategic approach. To address this, Synthetic Minority Over-sampling Technique (SMOTE) was employed to balance the dataset, enhancing the model's ability to recognize patterns related to stroke prediction.

![image](https://github.com/soumya1107/Stroke-Prediction-Hackathon-Kaggle/assets/64662510/4f262bef-3c3e-49e8-b217-44f4e81e17d5)

Dataset after SMOTE operation

![image](https://github.com/soumya1107/Stroke-Prediction-Hackathon-Kaggle/assets/64662510/571c37b5-728e-479b-8b4d-169a6b91de23)



#### Categorical to Numerical Conversion
Converting categorical values into numerical form was a vital step. Each categorical feature underwent encoding, transforming them into numerical representations that could be effectively utilized by machine learning models.


#### Feature Scaling
Feature scaling emerged as a crucial step to ensure fair model training. The process involved scaling numerical features to a standard range, facilitating faster convergence and preventing certain features from dominating others.

#### Feature Scaling
Feature scaling emerged as a crucial step to ensure fair model training. The process involved scaling numerical features to a standard range, facilitating faster convergence and preventing certain features from dominating others.

#### Feature Correlation and Selection
Understanding feature correlations played a pivotal role in model performance. Visualizing correlations and setting a threshold (e.g., 0.5) for feature selection helped ensure that highly correlated features were not introduced into the model. If predictor variables were found to be correlated, the variable with a lower correlation coefficient value than the target variable was dropped. Although based on the correlation data between age and Marital status attempts to eleiminate the marital status didnt really bring about better metric scores in terms actually, so the model was fed back with the marital status data. 

![image](https://github.com/soumya1107/Stroke-Prediction-Hackathon-Kaggle/assets/64662510/3b433ff8-93c6-4d15-ae7e-010c5666fd31)

## Hyperparameter Tuning 🔧

Optimizing the model's hyperparameters played a crucial role in enhancing accuracy. Through techniques like GridSearchCV and RandomizedSearchCV, I systematically fine-tuned parameters such as learning rates, tree depths, and ensemble sizes. This meticulous tuning not only boosted model performance but also emphasized the importance of finding the right configuration for optimal results. Hyperparameter tuning turned the models from good to great, showcasing the significance of parameter optimization in the pursuit of higher accuracy.



## Model Selection 🤖

### Logistic Regression
Utilizing logistic regression allowed for a baseline model, providing insights into the linear relationships between features and stroke prediction.

### Decision Tree Classifier
The decision tree classifier explored non-linear relationships within the data, creating a tree-like model to make predictions based on feature splits.

### Random Forest Classifier
Leveraging a bagging technique, the random forest classifier aggregated predictions from multiple decision trees, enhancing overall model accuracy and robustness.

### Sequential Model (Neural Network)
The journey concluded with the implementation of a simple neural network using Keras. This sequential model provided a deeper exploration of the intricate relationships within the data, employing layers of interconnected neurons to make predictions.

## Key Takeaways 🌟

Participating in this hackathon proved instrumental in bridging the gap between theory and practical implementation. It not only strengthened my ability to tackle real-world challenges but also highlighted the significance of data preprocessing, model selection, and the impact of various techniques on model performance.

This experience underscored the importance of a well-rounded understanding of machine learning concepts and the adaptability required to navigate challenges unique to each dataset. The combination of thoughtful preprocessing, model selection, and experimentation with different algorithms laid the foundation for a comprehensive approach to the Stroke Prediction problem.

## Personal Learning 💡

This practical experience taught me that it's not necessarily the most sophisticated or cutting-edge ML model that guarantees better results. Instead, focusing on steps like data pre-processing, cleaning, wrangling, converting categorical data to numerical data, and handling imbalanced datasets bore the real fruits. It's the attention to detail in these foundational aspects that can significantly impact the success of a machine learning project.




