# SpaceX Data Analysis and Prediction

## Overview

This project involves analyzing SpaceX launch data to predict the success of first-stage landings. Using a combination of data collection, data wrangling, exploratory data analysis (EDA), interactive visualizations, and predictive modeling, the project aims to understand factors influencing launch success and improve predictive accuracy.

## Project Components

1. **Data Collection**
   - Gathered data using SpaceX REST API and web scraping from Wikipedia.
   - Collected data includes flight numbers, payload masses, launch sites, outcomes, and more.

2. **Data Wrangling**
   - Cleaned data by handling missing values, encoding categorical variables, and creating binary labels for launch outcomes.

3. **Exploratory Data Analysis (EDA)**
   - Performed visual analysis with charts and scatter plots.
   - Conducted SQL queries for in-depth insights into the dataset.

4. **Interactive Mapping**
   - Built interactive maps using Folium to visualize launch sites, outcomes, and distances to key landmarks.

5. **Dashboard Creation**
   - Developed an interactive dashboard with Plotly Dash.
   - Features include pie charts, sliders, scatter plots, and dropdown lists for detailed analysis.

6. **Predictive Analysis**
   - Created and evaluated multiple classification models (Logistic Regression, SVM, Decision Tree, KNN).
   - Used `GridSearchCV` for hyperparameter tuning and selected the best-performing model based on accuracy and other metrics.

## Getting Started

### Prerequisites

- Python 3.x
- Required libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `folium`, `plotly`, `scikit-learn`, `beautifulsoup4`, `requests`, `sqlite3`

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/spacex-data-analysis.git
