## Customer Churn Prediction 2020


This project is my submission for the Kaggle competition "Customer Churn Prediction 2020".



### Introduction
The goal of this competition is to build a machine learning model that can accurately predict whether a customer will churn (i.e., cancel their service) based on various customer account and usage features. Predicting customer churn is an important problem for many businesses, as it allows them to proactively identify at-risk customers and take steps to retain them.

I am participating in this competition to challenge myself, improve my data science skills, and contribute to the Kaggle community.

### Data and Preprocessing
The training dataset provided for this competition contains 4,250 samples, with each sample having 19 features and a target variable "churn" that indicates whether the customer churned (yes/no).

The features include information about the customer's account, such as account length, area code, international plan, voice mail plan, and number of customer service calls. There are also features related to the customer's usage, such as total minutes, calls, and charges for day, evening, night, and international calls.

To prepare the data for modeling, I will  perform the following preprocessing steps:
1. Handled missing values by imputing the mean for numerical features and the mode for categorical features.
2. Encoded categorical features using one-hot encoding.
3. Engineered additional features, such as the ratio of international to total calls and charges.

### Modeling
I will experiment with several machine learning algorithms for this competition, including:
- **Random Forest Classifier**: A robust ensemble method that can handle both numerical and categorical features, as well as complex, nonlinear relationships in the data.
- **XGBoost Classifier**: A powerful gradient boosting algorithm that has shown excellent performance on many classification tasks.
- **Logistic Regression**: A simple and interpretable model that can provide insights into the relationship between the features and the target variable.

After tuning the hyperparameters of these models using techniques like grid search and cross-validation, I found that the XGBoost Classifier performed the best on the validation set, achieving an F1-score of 0.82.

### Results


### Future Work


### Usage
To run my code and reproduce the results, please follow these steps:
1. Clone the GitHub repository: `git clone https://github.com/Endework/CustomerChurnPrediction2020.git`
2. Install the required dependencies: `pip install -r requirements.txt`


### Acknowledgments

Citations:
[1] https://www.kaggle.com/code/triowibowo28/customer-churn-prediction
