
**House Price Prediction**
This repository contains a Jupyter notebook ([House_price_predicition.ipynb](https://github.com/Anujjadaun97/Boston-House-Price-Prediction/blob/main/House_price_predicition.ipynb) that demonstrates a machine learning workflow for predicting house prices using the Boston House Price dataset. The prediction model is built using XGBoost Regressor.

**Workflow**
The notebook follows a clear and structured workflow:

**Load Data**: The dataset is loaded from a publicly available URL.

**Data Preprocessing**: Initial steps to prepare the data for model training.

**Data Analysis**: Exploratory data analysis (EDA) to understand the dataset's characteristics and relationships between features.

**Train Test Split**: The dataset is split into training and testing sets to evaluate the model's performance on unseen data.

**XGBoost Regressor**: Implementation of the XGBoost Regressor model for house price prediction.

**Evaluation**: Evaluation of the trained model using appropriate metrics.

**Dataset**
The project uses the [Boston House Price dataset](https://github.com/Anujjadaun97/Boston-House-Price-Prediction/blob/main/housing.csv), which includes various features related to housing in Boston and their corresponding median house prices. The features include:

CRIM: Per capita crime rate by town

ZN: Proportion of residential land zoned for lots over 25,000 sq.ft.

INDUS: Proportion of non-retail business acres per town

CHAS: Charles River dummy variable (= 1 if tract bounds river; 0 otherwise)

NOX: Nitric oxides concentration (parts per 10 million)

RM: Average number of rooms per dwelling

AGE: Proportion of owner-occupied units built prior to 1940

DIS: Weighted distances to five Boston employment centers

RAD: Index of accessibility to radial highways

TAX: Full-value property-tax rate per $10,000

PTRATIO: Pupil-teacher ratio by town

B: 1000(Bk - 0.63)^2 where Bk is the proportion of blacks by town

LSTAT: % lower status of the population

PRICE: Median value of owner-occupied homes in $1000s (Target variable)

**Technologies Used**
Python

Jupyter Notebook

Pandas

NumPy

Seaborn

Matplotlib

Scikit-learn

XGBoost

**How to Run the Notebook**
Clone this repository to your local machine.

Ensure you have Python and Jupyter Notebook installed.

**Install the required libraries:**


pip install pandas numpy seaborn matplotlib scikit-learn xgboost
**Open the Jupyter Notebook:**


jupyter notebook House_price_predicition.ipynb

Run all cells in the notebook to execute the workflow and see the results.

Contributing
Feel free to fork this repository, make improvements, and submit pull requests. For major changes, please open an issue first to discuss what you would like to change.
