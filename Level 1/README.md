# 🍽️ Restaurant Insights Exploration

An end-to-end exploratory data analysis (EDA) project focused on understanding trends and insights in the restaurant industry using real-world data. This repository contains the entire workflow — from raw dataset to clean visual insights — aimed at aiding stakeholders in data-driven decision-making.

---

## 📚 Table of Contents

- [Project Description](#project-description)
- [Motivation](#motivation)
- [Data Source](#data-source)
- [Data Preprocessing](#data-preprocessing)
- [Key Questions](#key-questions)
- [Visualizations](#visualizations)
- [Key Insights](#key-insights)
- [Technologies Used](#technologies-used)
- [How to Run](#how-to-run)
- [Project Structure](#project-structure)
- [Acknowledgements](#acknowledgements)

---

## 📝 Project Description

This project performs a comprehensive analysis of a restaurant dataset to extract meaningful insights about customer preferences, city-wise distributions, cost factors, and cuisine trends. The outcome of this project can help food businesses, marketing teams, and entrepreneurs identify promising areas and strategize accordingly.

---

## 🎯 Motivation

With the restaurant industry growing rapidly, especially in metropolitan areas, it's essential to understand:

- Where the concentration of restaurants is highest
- What cuisines are most popular in different cities
- How pricing strategies vary geographically
- What patterns exist in user ratings and reviews

These insights can help businesses:
- Optimize location choices
- Tailor menu offerings
- Adjust pricing strategies
- Improve marketing focus

---

## 🗂️ Data Source

The dataset (from a public source or data competition) contains information about restaurants in various cities and includes:

- Restaurant names
- Location
- Cost for two
- Cuisine types
- User ratings
- Online delivery options

*Note: Dataset source can be added here once finalized.*

---

## 🔧 Data Preprocessing

The raw dataset underwent several preprocessing steps:

- Dropped irrelevant or missing columns
- Renamed columns for clarity
- Converted cost strings to numeric values
- Cleaned location names and cuisines
- Removed duplicate entries
- Normalized rating scales

A clean dataset was saved as `preprocessed_dataset.csv`.

---

## ❓ Key Questions

The project aimed to answer the following:

- Which cities have the highest number of restaurants?
- What are the most popular cuisines offered?
- What is the average cost for two in various cities?
- Is there a correlation between cost and rating?
- Do cities differ in cuisine diversity?

---

## 📊 Visualizations

Several visualizations were generated to support the analysis:

- 📍 **Top Cities by Restaurant Count**: Bar chart showing leading cities
- 🍱 **Popular Cuisines**: Frequency of top cuisines
- 🌐 **Cuisine vs City**: Annotated charts mapping cuisine types to cities
- 💰 **Cost Trends**: Heatmaps and scatter plots showing pricing patterns

> All charts are saved in `.png` format and are reusable in presentations or dashboards.

---

## 📌 Key Insights

- **Bangalore**, **Delhi NCR**, and **Mumbai** lead in restaurant count.
- **North Indian**, **Chinese**, and **Fast Food** are the most commonly available cuisines.
- Average meal cost is significantly higher in metro cities.
- Online delivery is more prevalent in high-density cities.
- Ratings tend to be higher for moderately priced restaurants.

---

## 🛠️ Technologies Used

- **Python** – Data processing and analysis
- **Pandas** – Data wrangling
- **Matplotlib & Seaborn** – Visualization
- **Jupyter Notebook** – Interactive analysis environment

---

## 🚀 How to Run

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Rajender1709Reddy/restaurant-insights-exploration.git
   cd restaurant-insights-exploration

---

## 📁 Project Structure

restaurant-insights-exploration/
- Dataset.csv                        # Original dataset
- preprocessed_dataset.csv           # Cleaned dataset
- top_cities.png                     # Bar plot of top cities
- top_cuisines.png                   # Plot of top cuisines
- top_cities_and_cuisines_annotated.png # Annotated insights
- restaurant_insights.ipynb          # Jupyter notebook for analysis
- README.md                         # Project documentation


---

## 🙌 Acknowledgements

Thanks to the open data community for sharing valuable restaurant datasets that make this analysis possible. Special credit to all contributors of Python's data science libraries.

