# Predict diamonds price:diamonds:
Predict diamonds price using scikit-learn packages
dataset source : https://www.kaggle.com/shivam2503/diamonds

# Goal : 
Use the given 9 independent variables (6 numerical, 3 categorical) to predict the diamond price (target variable). The dataset contains 53,940 entries. 

# Steps : 
1. Import packages
2. EDA
3. Split the data
4. Model building
  - Multilinear Regression Model
  - Random Forest Regressor
5. Model evaluation
  - R square
  - Adjusted R square
  - Mean Squared Error (MSE)
  - Mean Absolute Error (MAE)

# Summary :

| Model  | R2     | Adjusted R2 | MSE | MAE |
| ------ | ------ | ------ | ------ | ------ |
| Linear Regression | 0.9195 | 0.9193 | 1,290,368 | 726.29 |
| Random Forest | 0.9828 | 0.9827 | 274,684 | 263.92 |

The Random Forest has the best result among these models.
