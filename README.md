🌫️ Air Quality Index (AQI) Prediction using Air & Weather Data

This project aims to predict the Air Quality Index (AQI) based on environmental and meteorological data using a Linear Regression model. It demonstrates a complete data science workflow including data preprocessing, feature engineering, exploratory data analysis (EDA), and model building.

🔍 Project Highlights

Objective: To build a regression model that accurately predicts AQI levels from pollutant and weather-related features.

Dataset:

Contains readings from various monitoring stations with features like:

Pollutants: PM2.5, PM10, NO2, NH3, SO2, CO, O3

Weather: Temperature, Wind Speed

Target: AQI (Air Quality Index)

Cleaned and preprocessed for null values and inconsistent formatting

Key Steps:

Missing Value Treatment: Handled missing values via imputation

Exploratory Data Analysis (EDA):

Used histograms, correlation heatmaps, and scatter plots to understand variable distributions and relationships

Feature Selection: Removed less relevant columns to enhance model accuracy and reduce overfitting

Data Splitting: Train-test split using an 80-20 ratio

Model Building:

Applied Linear Regression from sklearn

Evaluated with R² Score and Mean Absolute Error (MAE)

Visualization: Displayed actual vs predicted AQI values using bar plots and scatter plots

📊 Technologies & Libraries Used

pandas, numpy – for data handling and preprocessing

matplotlib, seaborn – for visualization and EDA

scikit-learn – for model training, evaluation, and preprocessing tools

📈 Results

The Linear Regression model achieved a decent R² Score, indicating a moderate correlation between selected features and AQI.

Visualization of predicted vs actual AQI values showed the model's effectiveness in capturing underlying patterns.

