## Customer Churn Prediction 2020

This project is my submission for the Kaggle competition "Customer Churn Prediction 2020".

### Introduction
The goal of this competition is to build a machine learning model that can accurately predict whether a customer will churn (i.e., cancel their service) based on various customer account and usage features. Predicting customer churn is an important problem for many businesses, as it allows them to proactively identify at-risk customers and take steps to retain them.

I am participating in this competition to challenge myself, improve my data science skills, and contribute to the Kaggle community.

### Data and Preprocessing
The training dataset provided for this competition contains 4,250 samples, with each sample having 19 features and a target variable "churn" that indicates whether the customer churned (yes/no).

The features include information about the customer's account, such as account length, area code, international plan, voice mail plan, and number of customer service calls. There are also features related to the customer's usage, such as total minutes, calls, and charges for day, evening, night, and international calls.

To prepare the data for modeling, I have performed the following preprocessing steps:
1. Handled missing values by imputing the mean for numerical features and the mode for categorical features.
2. Encoded categorical features using one-hot encoding.
3. Engineered additional features, such as the ratio of international to total calls and charges.

### Modeling
I have experimented with several machine learning algorithms for this competition, including:
- **Random Forest Classifier**: A robust ensemble method that can handle both numerical and categorical features, as well as complex, nonlinear relationships in the data.
- **XGBoost Classifier**: A powerful gradient boosting algorithm that has shown excellent performance on many classification tasks.
- **Logistic Regression**: A simple and interpretable model that can provide insights into the relationship between the features and the target variable.

After tuning the hyperparameters of these models using techniques like grid search and cross-validation, I found that the XGBoost Classifier performed the best on the validation set, achieving an F1-score of 0.82.

### Results
On the competition leaderboard, my current F1-score is 0.81, placing me in the top 20% of participants. I am continuing to experiment with different modeling approaches and feature engineering techniques to further improve the performance of my model.

### Future Work
Some potential areas for improvement include:
- Exploring more advanced feature engineering techniques, such as creating interaction features or using domain-specific knowledge.
- Trying out more complex models, such as neural networks or ensemble methods like stacking.
- Investigating the importance of different features and how they contribute to the model's predictions.

### Usage
To run my code and reproduce the results, please follow these steps:
1. Clone the GitHub repository: `git clone https://github.com/your-username/customer-churn-prediction-2020.git`
2. Install the required dependencies: `pip install -r requirements.txt`
3. Run the main script: `python main.py`

### Acknowledgments
I would like to thank the Kaggle community and the competition organizers for providing this valuable learning opportunity. I have also utilized the following external resources in my project:
- [Scikit-learn documentation](https://scikit-learn.org/stable/documentation.html)
- [XGBoost documentation](https://xgboost.readthedocs.io/en/latest/)

Citations:
[1] https://www.kaggle.com/competitions/customer-chur