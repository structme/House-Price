House Price Prediction
Introduction
This project is aimed at predicting house prices using the data available on Kaggle's "House Prices: Advanced Regression Techniques" competition. The project uses various features such as the number of bedrooms, the size of the house, and the location, to predict the selling price of a house.

Data
The data used for this project was obtained from Kaggle's "House Prices: Advanced Regression Techniques" competition. The dataset includes information on various features of houses in the Ames, Iowa area, as well as their corresponding selling prices.

Methodology
The project was completed using Python and various Python libraries such as Pandas, Numpy, and Scikit-learn. The data was preprocessed to handle missing values and outliers, and then feature engineering techniques such as one-hot encoding and feature scaling were applied. After that, various regression models were built and compared to select the best performing model.

Results
The best performing model was the XGBoost Regressor, with an R-squared value of 0.90. This model was used to predict the selling price of houses in the test dataset.

Conclusion
The project successfully predicted the selling prices of houses using various features. The best performing model was XGBoost Regressor with an R-squared value of 0.90. This project could be improved by incorporating additional features or tuning the hyperparameters of the models used.

Usage
The project can be run by opening the "House Price.ipynb" file in Jupyter Notebook and running the code cells in order. The required packages can be installed by running "pip install -r requirements.txt" in the terminal.

References
"House Prices: Advanced Regression Techniques" competition on Kaggle
Python
Pandas
Numpy
Scikit-learn
XGBoost
