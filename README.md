# Pycaret-
Pycaret: PyCaret is an open-source, low-code machine learning library in Python that aims to reduce the cycle time from hypothesis to insights. 
Increased Productivity
Easy to Use
Business Ready
Analyze Model Performance easily
Data Preparation to Deployment in PyCaret is fully automated

PyCaret is essentially a Python wrapper around several machine learning libraries and frameworks such as scikit-learn, XGBoost, LightGBM, CatBoost, spaCy, Optuna, Hyperopt, Ray, and many more.

It can be used for
Classification
Regression
Clustering
Anomaly Detection
Natural Language Processing
Association Rule Mining

Features and functions of pycaret library
The get_data() function from pycaret.dataset allows you to use the datasets from the GIT repository.
The setup() function also allows you to configure simple data preparation, such as scaling, power transforms, missing data handling, and PCA transforms.
We can compare standard machine learning models by calling the compare_models() function. By default, it will evaluate models using 10-fold cross-validation, sort results by classification accuracy, and return the single best model.
We can tune model hyperparameters using the tune_model() function in the PyCaret library.The function takes an instance of the model to tune as input and knows what hyperparameters to tune automatically.
We have evaluate_model() to evaluate our model and get different respective plots.
We have finalize_model() which considers overall data along with hold-out/test data to train the model before deployment.
Pycaret is compatible with many deployment like aws etc.


Here I've implemented for regression and classification problem.
