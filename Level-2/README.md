# Level 2 project
🍽️ Restaurant Insights Exploration — Level 2
Building on the foundational exploratory analysis, Level 2 dives deeper into advanced data modeling and predictive analytics to forecast restaurant success factors and customer behavior trends.
📚 Table of Contents
Project Description

Objectives

Data Source

Data Preparation

Modeling Techniques

Results and Evaluation

Technologies Used

How to Run

Project Structure

Acknowledgements
📝 Project Description
This phase extends the restaurant insights exploration by applying machine learning models and statistical techniques to predict factors like restaurant ratings, customer footfall, and cuisine popularity trends. It aims to provide actionable forecasts to aid restaurant owners and marketers.

🎯 Objectives
Develop predictive models to estimate restaurant ratings based on features such as location, cost, and cuisine.

Analyze customer behavior patterns using clustering and segmentation.

Identify key variables impacting restaurant success.

Validate model performance using appropriate metrics.

🗂️ Data Source
Utilizes the cleaned and preprocessed dataset generated in Level 1 (preprocessed_dataset.csv), enriched with engineered features to improve model quality.

🔧 Data Preparation
Feature engineering on cost and cuisine variables.

Handling missing values and outliers.

Encoding categorical variables.

Splitting data into training and testing sets.

🧠 Modeling Techniques
Regression models (Linear Regression, Random Forest Regressor) for rating prediction.

Clustering algorithms (K-Means) for customer segmentation.

Model evaluation using RMSE, R², and silhouette scores.

📈 Results and Evaluation
Summary of model performances and key metrics.

Visualizations of clusters and prediction errors.

Interpretation of feature importance and insights.

🛠️ Technologies Used
Python libraries: scikit-learn, pandas, numpy, matplotlib, seaborn.

Jupyter Notebook for interactive modeling and visualization.


🚀 How to Run
Clone the repository and navigate to the Level 2 folder:

bash
Copy
Edit
git clone https://github.com/Rajender1709Reddy/restaurant-insights-exploration.git
cd restaurant-insights-exploration/Level-2

📁 Project Structure
bash
Copy
Edit
Level-2/
├── restaurant_modeling.ipynb       # Main notebook with modeling workflow
├── preprocessed_dataset.csv        # Cleaned dataset from Level 1
├── feature_engineering.py          # Scripts for feature engineering
├── models/                        # Saved machine learning models
│   ├── random_forest_model.pkl
│   └── kmeans_model.pkl
├── visualizations/                 # Plots and charts from analysis
│   ├── cluster_visualization.png
│   └── prediction_errors.png
└── README.md        


🙌 Acknowledgements
Thanks to the open-source community and data science libraries that empower this advanced analysis. Special thanks to the creators of scikit-learn and Jupyter for making modeling accessible.
