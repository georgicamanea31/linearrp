# Linear Regression Machine Learning Project

# Tesla Stock Price Prediction Using Linear Regression
This project analyzes and predicts Tesla's stock prices using linear regression. It leverages Python’s data science libraries, including Pandas, Seaborn, Matplotlib, and Scikit-learn, to perform exploratory data analysis (EDA) and build a predictive model.

Project Steps
Data Loading & Exploration:

The dataset (TSLA.csv) is loaded using Pandas.
Basic statistics and structure of the data are inspected (df.info(), df.describe()).
Pairwise relationships between stock price features are visualized using Seaborn pair plots.
Data Visualization:

A scatterplot matrix is generated to observe correlations between different stock price attributes.
A linear model plot (lmplot) is created to visualize the relationship between the Open and High prices.
Building the Linear Regression Model:

Features (X): Open, Low, Close, and Volume prices.
Target (Y): High price.
The dataset is split into training (80%) and testing (20%) sets.
A Linear Regression model is trained using scikit-learn.
Model coefficients are extracted and displayed.
Model Evaluation:

The model makes predictions on the test dataset.
A scatter plot compares predicted vs. actual High prices.
Error Metrics:
Mean Absolute Error (MAE)
Mean Squared Error (MSE)
Root Mean Squared Error (RMSE)
Key Takeaways:
The model attempts to predict Tesla’s High stock price based on other stock attributes.
The visualization and evaluation steps help assess the accuracy of the regression model.
Future improvements could involve feature engineering, polynomial regression, or deep learning approaches for better accuracy.
