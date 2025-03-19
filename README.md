# Linear Regression Machine Learning Project  
## Tesla Stock Price Prediction Using Linear Regression  

### Project Overview  
This project analyzes and predicts **Tesla's stock prices** using **linear regression**. It leverages Python’s data science libraries, including **Pandas, Seaborn, Matplotlib, and Scikit-learn**, to perform **exploratory data analysis (EDA)** and build a predictive model.  

---

## Project Steps  

### 1. Data Loading & Exploration  
- The dataset (`TSLA.csv`) is loaded using **Pandas**.  
- Basic statistics and structure of the data are inspected using:  
  ```python
  df.info()
  df.describe()
  ```  
- **Pairwise relationships** between stock price features are visualized using **Seaborn pair plots**.  

### 2. Data Visualization  
- A **scatterplot matrix** is generated to observe correlations between different stock price attributes.  
- A **linear model plot (`lmplot`)** is created to visualize the relationship between the **Open** and **High** prices.  

### 3. Building the Linear Regression Model  
- **Feature Selection:**  
  - **Features (`X`)**: Open, Low, Close, and Volume prices.  
  - **Target (`Y`)**: High price.  
- **Data Splitting:**  
  - The dataset is split into **training (80%)** and **testing (20%)** sets.  
- **Model Training:**  
  - A **Linear Regression** model is trained using **Scikit-learn**.  
- **Model Coefficients:**  
  - The regression coefficients are extracted and displayed after training.  

### 4. Model Evaluation  
- The model makes **predictions** on the test dataset.  
- A **scatter plot** compares **predicted vs. actual High prices**.  
- **Error Metrics** are calculated to measure performance:  
  - **Mean Absolute Error (MAE)**  
  - **Mean Squared Error (MSE)**  
  - **Root Mean Squared Error (RMSE)**  

---

## Key Takeaways  
- The model attempts to **predict Tesla’s High stock price** based on other stock attributes.  
- **Visualization and evaluation** steps help assess the accuracy of the regression model.  
- **Future Improvements**:  
  - Feature engineering to enhance predictive power.  
  - Experimenting with **polynomial regression** for non-linear patterns.  
  - Exploring **deep learning models** (e.g., LSTMs) for better accuracy in stock price prediction.  

---

## Dependencies  
To run this project, install the required libraries using:  

```bash
pip install pandas seaborn matplotlib scikit-learn
```

## Usage  
Run the script using:  

```bash
python linear_regression.py
```

---


