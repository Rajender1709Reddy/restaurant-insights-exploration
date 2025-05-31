# Level 3 Project  
🍽️ **Restaurant Insights Exploration — Level 3**  
In this final phase of the project, we apply advanced predictive analytics and deep-dive analysis on cuisine and rating data to draw strategic, data-driven insights that can support business decisions in the food industry.

---

## 📚 Table of Contents

- Project Description  
- Objectives  
- Data Source  
- Data Preparation  
- Modeling Techniques  
- Results and Evaluation  
- Technologies Used  
- How to Run  
- Project Structure  
- Acknowledgements

---

## 📝 Project Description  
Level 3 focuses on developing refined predictive models, analyzing the influence of cuisine types on ratings, and generating clear, impactful visualizations. This stage enhances previous levels by leveraging the cleaned dataset to extract meaningful patterns and deliver actionable insights.

---

## 🎯 Objectives  

- Build regression models to predict restaurant ratings more accurately.  
- Analyze the impact of cuisine types on restaurant performance.  
- Interpret feature importance and model behavior.  
- Communicate findings with visualizations to support decision-making.

---

## 🗂️ Data Source  

This level uses `preprocessed_dataset.csv` from Level 1, with further enhancements and additional feature engineering relevant to model performance.

---

## 🔧 Data Preparation  

- Handling remaining missing values and outliers.  
- Feature engineering on cuisine, cost, and location variables.  
- Encoding of categorical features.  
- Train-test data splitting and scaling.

---

## 🧠 Modeling Techniques  

- **Regression Models**:  
  - Linear Regression  
  - Random Forest Regressor  
  - XGBoost Regressor  

- **Evaluation Metrics**:  
  - RMSE (Root Mean Squared Error)  
  - MAE (Mean Absolute Error)  
  - R² Score  

- **Cuisine Analysis**:  
  - Group-wise aggregation  
  - Visualization of cuisine vs. average ratings

---

## 📈 Results and Evaluation  

- Evaluated model performances and selected the best-performing regressor.  
- Identified key features influencing customer ratings.  
- Uncovered cuisine categories that significantly affect overall customer satisfaction.  
- Visualized results for better business interpretation.

---

## 🛠️ Technologies Used  

- **Languages**: Python  
- **Libraries**: pandas, numpy, matplotlib, seaborn, scikit-learn, xgboost  
- **Tools**: Jupyter Notebook, joblib (for model saving)

---

## 🚀 How to Run  

Clone the repository and navigate to the Level 3 directory:

```bash
git clone https://github.com/Rajender1709Reddy/restaurant-insights-exploration.git
cd restaurant-insights-exploration/Level-3

📁 Project Structure
Level-3/
├── rating_prediction_models.ipynb       # Model development and evaluation
├── cuisine_analysis.ipynb               # Cuisine-wise insights and visualizations
├── visualizations/                      # Graphs and plots from analysis
│   ├── cuisine_rating_distribution.png
│   └── model_performance_comparison.png
├── saved_models/                        # Trained machine learning models
│   ├── random_forest.pkl
│   └── xgboost_model.pkl
├── preprocessed_dataset.csv             # Enhanced dataset from Level 1
└── README.md

## 🙌 Acknowledgements

This project was made possible thanks to the incredible resources and contributions of the open-source data science community. Special thanks to:

- **Scikit-learn** – for providing robust machine learning tools and easy-to-use APIs.
- **XGBoost** – for its powerful and efficient implementation of gradient boosting.
- **Pandas & NumPy** – for data manipulation and numerical computation.
- **Matplotlib & Seaborn** – for enabling clear and insightful data visualizations.
- **Jupyter Notebook** – for creating an interactive development environment.
- **Open Datasets & Kaggle Community** – for inspiration and real-world use cases.

Gratitude also goes to instructors, mentors, and peers who provided guidance and support throughout the development of this project.




