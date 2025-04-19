# Weather Power Forecasting Project

## Project Overview
This project aims to forecast power generation based on weather conditions using machine learning techniques. The dataset includes various weather parameters such as temperature, humidity, wind speed, and wind direction across different locations. By analyzing the relationship between these weather features and power generation, we can build a model to predict power output.

## Learning Objectives
- **Understand the Impact of Weather on Power Generation**: Learn how various weather parameters influence power generation.
- **Data Merging and Preprocessing**: Combine multiple datasets and clean them for machine learning.
- **Perform Exploratory Data Analysis (EDA)**: Visualize data distributions, relationships, and patterns.
- **Feature Engineering**: Create meaningful features for better model performance.
- **Build and Train Machine Learning Models**: Use regression models like Linear Regression for power forecasting.
- **Evaluate Model Performance**: Assess the accuracy of the model using metrics like MSE and R² score.
- **Interpret Model Results**: Analyze feature importance to understand the factors affecting power generation.

## Tools and Technologies Used
- **Python**: The primary programming language.
- **Libraries**:
  - `pandas` for data manipulation.
  - `numpy` for numerical operations.
  - `matplotlib`, `seaborn` for data visualization.
  - `scikit-learn` for machine learning and model evaluation.

## Steps

### 1. Data Merging and Preprocessing
- **Merge Multiple Datasets**: Combine data from different locations and clean the dataset.
- **Feature Engineering**: Encode categorical features like location and categorize wind direction into buckets.
- **Missing Data Handling**: Ensure there are no missing values in the dataset.

### 2. Exploratory Data Analysis (EDA)
- **Histograms**: Visualize the distribution of weather features.
- **Scatter Plots**: Explore relationships between temperature and power generation.
- **Box Plots**: Identify outliers and understand feature distributions.

### 3. Model Training and Evaluation
- **Linear Regression**: Build a regression model to predict power generation using weather features.
- **Train-Test Split**: Split the data into training and testing sets.
- **Model Performance**: Evaluate using Mean Squared Error (MSE) and R² Score.
- **Feature Importance**: Analyze the coefficients to determine which features impact power generation the most.

### 4. Visualization
- **Visualizations**: Use scatter plots, histograms, and box plots to explore data patterns and model results.
- **Predicted vs Actual Power**: Displays how well the model’s predictions match the actual power generation.
- **Feature Importance**: Shows the impact of weather parameters on power generation.

## Results
- **Predicted vs Actual Power**: Demonstrates the model’s prediction accuracy.
- **Feature Importance**: Highlights which weather conditions influence power generation the most.

## Installation Instructions

### 1. Clone the Repository:
```bash
git clone https://github.com/your-username/weather-power-forecasting.git
```
### 2. Install Dependencies:
Use pip to install the necessary libraries:
```bash
pip install pandas numpy scikit-learn matplotlib seaborn
```
### 3. Run the Project:
-**Jupyter Notebook**: Run the weather_power_forecasting.ipynb for an interactive experience.
-**Python Scripts**: Alternatively, you can execute individual Python scripts from the src directory.

##Conclusion
###This project demonstrates the power of machine learning in predicting power generation based on weather conditions. It provides insights into the key features influencing power output and allows for optimization and forecasting in energy management.

