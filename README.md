# Seoul Bike Sharing Demand Prediction [Project for the Python-For-Data-Analysis Course (ESILV Project 2022)]

This project aims to predict the number of rented bikes in Seoul, South Korea using the Seoul Bike Sharing Demand dataset. With 13 variables, including temperature, humidity, and season, this dataset can help rental companies ensure a stable supply of bikes for the public.

## 📊 Data Analysis

After adding some variables, including pollution and public holidays, we carried out some visualizations to see the correlations between each variable and the target variable (Rented Bike Count). We also plot each distribution for a better overview.

## 🛠️ Data Preprocessing

We preprocess the data by removing outliers, handling missing values, and normalizing the data. We also split the data into training and testing sets.

## 🤖 Model Selection

We compare the performance of different regression models, including Linear Regression, Decision Tree Regression, Random Forest Regression, and Gradient Boosting Regression. We use cross-validation to evaluate the models and select the best one.

## 📈 Model Evaluation

We evaluate the performance of the selected model using various metrics, including Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and R-squared (R2) score. We also visualize the predicted values and the actual values to see how well the model fits the data.

## 📝 Conclusion

Based on our analysis and evaluation, we conclude that the Gradient Boosting Regression model performs the best in predicting the number of rented bikes in Seoul. Rental companies can use this information to improve their services and meet customer demand more effectively.

## 📋 Requirements

- Python 3.6 or higher
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## 🚀 Usage

1. Clone the repository:

```
git clone https://github.com/your-username/seoul-bike-sharing-demand.git
```

2. Install the required packages:

```
pip install -r requirements.txt
```

3. Open the Jupyter Notebook:

```
jupyter notebook
```

4. Run the cells in the notebook to reproduce the analysis and evaluation.

## 🙏 Credits

This project is based on the Seoul Bike Sharing Demand dataset from the UCI Machine Learning Repository. The dataset was collected by Capital Bikeshare and donated to the UCI Machine Learning Repository in 2015. The dataset can be found at: https://archive.ics.uci.edu/ml/datasets/Seoul+Bike+Sharing+Demand
