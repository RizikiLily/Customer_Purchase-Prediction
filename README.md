# Customer Purchase Prediction using Random Forest Classifier

This project aims to predict whether a customer will make a purchase or not based on their gender, age, and estimated salary using a Random Forest Classifier. The dataset contains information about customers including their gender, age, estimated salary, and whether they made a purchase or not.

## Dataset

The dataset consists of the following columns:

- **User ID:** Unique identifier for each customer
- **Gender:** Gender of the customer (Male/Female)
- **Age:** Age of the customer
- **Estimated Salary:** Estimated salary of the customer
- **Purchased:** Binary variable indicating whether the customer made a purchase (1) or not (0)

## Exploratory Data Analysis (EDA)

Before building the predictive model, exploratory data analysis (EDA) was performed. This included:

- Checking for missing values
- Exploring the distribution of the target variable (Purchased)
- Visualizing the relationship between different features and the target variable
- Calculating correlation between numerical features

## Data Preprocessing

- Encoding the categorical variable "Gender" into numerical format using LabelEncoder
- Splitting the dataset into training and testing sets

## Model Building

A Random Forest Classifier was chosen as the predictive model due to its ability to handle both categorical and numerical data effectively. The model was trained on the training dataset and evaluated on the testing dataset.

## Evaluation Metrics

The performance of the model was evaluated using metrics such as accuracy, precision, recall, and F1-score.

## Conclusion

The Random Forest Classifier achieved an accuracy of 0.883 in predicting whether a customer will make a purchase or not based on their gender, age, and estimated salary. Further optimization and tuning of the model could potentially improve its performance.

## Files Included

- `customer_group.ipynb`: Jupyter notebook containing the code for data preprocessing, model building, and evaluation.
- `Customer_data.csv`: Dataset used for training and testing the model.
- `README.md`: This file, providing an overview of the project.

## Requirements

- Python 3.x
- Jupyter Notebook
- scikit-learn
- pandas
- matplotlib
- seaborn