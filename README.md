# **Comparing Several Machine Learning Models for House Price Prediction**

In this project, we will compare different machine learning models to predict the prices of houses using a dataset of various features such as the number of rooms, the age of the house, and its location. We will train and evaluate the following models:

- Random Forest Regressor

- Linear Regression

- Neural Network

- XGBoost

The dataset contains information on houses sold in a particular area and the corresponding sale price. We will split the dataset into a training set and a test set to evaluate the models' performance.

## **Getting Started**

To get started, clone the repository:

````
git clone https://github.com/amyrmahdy/california-price-houses.git
````

Then, navigate to the project directory and install the required packages using pip:

```
cd california-price-houses
pip install -r requirements.txt
```

## **Dataset**

The California Housing dataset is a famous dataset in machine learning and contains information collected by the U.S Census Service about the housing in California in the 1990s.


## **Preprocessing**

The preprocessing steps performed on the dataset include:

- Removing duplicate rows

- Removing rows with missing values

- Converting categorical variables to binary variables using one-hot encoding

- Scaling the dataset using MinMaxScaler



## **Model Comparison**

The models were trained on the preprocessed dataset, and their performance was evaluated using the R2 score metric. The R2 score represents the proportion of variance in the target variable that can be explained by the independent variables. The R2 score for each model is shown below:


![r2score](r2score.png)



## **Conclusion**

In conclusion, we compared four different machine learning models for house price prediction and found that **XGBoost** had the best performance, followed closely by Random Forest Regressor. The results indicate that the choice of the machine learning model can have a significant impact on the accuracy of house price prediction. You can find the step-by-step code for this project in the `main.ipynb` file in the repository. For a more detailed explanation of the project and the code, you can check out my [Medium article](https://amyrmahdy.medium.com/model-comparison-a-step-by-step-guide-to-comparing-several-machine-learning-models-for-predictive-a8fc57af45b).






### **Author: amyrmahdy**

### **Date: 4 Oct 2022**

