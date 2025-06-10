# laptop_price_analysis

## Tools
* Python 3.x
* Pandas, NumPy
* Scikit-learn
* Matplotlib, Seaborn
  
## Purpose
In this project, I developed a machine learning model that predicts the prices of laptops based on their specifications. All steps such as data cleaning, feature engineering, model training, hyperparameter tuning, and performance analysis were performed using Python (Pandas, Scikit-learn, Matplotlib). This is very basic project so that just a few attributes are used to analyze the set. There are also more important attributes.
The purpose is to predict the Price by regarding some attribute such as Brand, Screen-Size and RAM.

The data set: Raw_Ebay.csv (a collection of sold laptops from e-bay)
Missing values and categorical variables are handled.
##Data Preprocessing
* Missing data was checked and imputed as appropriate (mean/median if necessary).
* Categorical data such as Brand was transformed with dummy.
* Necessary columns were selected and X (independent variables) and y (dependent variable/price) were separated.
* Pre-modeling transformations were prepared to suit the pipeline structure.

## Model
Lineer Regression and Random Forest Models are set to compare.

## Model Performance
RainForest:
MSE (Mean Squared Error): 53119.40
R² (Coefficient of Determination): 0.12

The model was observed to have very low accuracy.

**Test and Training Set Comparison:**
Training set error is low, test set error is high → Overfitting probability.

The generalizability of the model was low.

**Learning Curve:**
train_score and test_score stabilize over time.
Even if the amount of data is increased, the capacity of the model seems to be limited.

## Visualizations
Model Performance Graph:
* MSE and R² comparisons are presented visually.
* The response of training and test scores to data growth is examined.
* Which attributes are more predictive by Random Forest is analyzed.
