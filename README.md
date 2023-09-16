# Seoul Bike Sharing Demand Predictor

#### [Project for the Python-For-Data-Analysis Course (ESILV 2022)]

This project aims to predict the number of rented bikes in Seoul, South Korea using the Seoul Bike Sharing Demand dataset. With 13 variables, including temperature, humidity, and season, this dataset can help rental companies ensure a stable supply of bikes for the public.

## 📊 Data Analysis

We started by exploring the dataset and adding some variables, including pollution and public holidays, to see if they have any correlation with the target variable (Rented Bike Count). We carried out some visualizations, including scatter plots and heatmaps, to see the relationships between each variable and the target variable. We also plotted each distribution to see the range and distribution of each variable.

## 🛠️ Data Preprocessing

We preprocessed the data by removing outliers, handling missing values, and normalizing the data. We removed the rows with missing values and used the mean value to fill in the missing values in the temperature and humidity columns. We also normalized the data using the MinMaxScaler to scale the values between 0 and 1. We split the data into training and testing sets using a 70:30 ratio.

## 🤖 Model Selection

We compared the performance of different regression models, including Linear Regression, Decision Tree Regression, Random Forest Regression, and Gradient Boosting Regression. We used cross-validation to evaluate the models and select the best one. We used the GridSearchCV function to tune the hyperparameters of each model and find the best combination of hyperparameters.

## 📈 Model Evaluation

We evaluated the performance of the selected model using various metrics, including Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and R-squared (R2) score. We also visualized the predicted values and the actual values to see how well the model fits the data. We used the SHAP (SHapley Additive exPlanations) library to explain the predictions and see the contribution of each feature to the prediction.

## 📝 Conclusion

Based on our analysis and evaluation, we concluded that the Gradient Boosting Regression model performs the best in predicting the number of rented bikes in Seoul. The model achieved an R2 score of 0.87 on the test set, which indicates a good fit to the data. Rental companies can use this information to improve their services and meet customer demand more effectively.

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
