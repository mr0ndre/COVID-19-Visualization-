
# 📊 COVID-19 Global Visualization

This project presents an interactive visualization of COVID-19 cases and deaths across countries worldwide. The goal is to make large-scale pandemic data easier to explore, compare, and understand through clear and intuitive visual analytics.

# 🌐 Live Interactive Dashboard
👉 https://mr0ndre.github.io/COVID-19-Visualization-/

## 🔍 Key Features

🌍 Global coverage of COVID-19 cases and deaths by country

📈 Interactive Plotly visualizations (hover, zoom, filter)

🎨 Clean, minimal web layout for easy navigation

📊 Multiple visualization types (maps, distributions, comparisons)

## 🧠 What This Project Demonstrates

Data cleaning and preprocessing of real-world datasets

SQL & Python-based data analysis workflows

Effective data storytelling through visualization

Web integration of Plotly .html outputs using HTML & CSS

## 🛠️ Tech Stack

Python (Pandas, NumPy)

Plotly for interactive visualizations

HTML & CSS for presentation

SQLite for data querying

# 📂 About the Data

Date Formatting
All dates were standardized to the format YYYY.MM.DD to ensure consistency and improve readability across visualizations and analyses.

Country Identifiers
An additional column containing ISO-3 country codes was created to support accurate geographic mapping and cross-dataset compatibility.

Numerical Scaling
Several numerical variables exhibit large variance and skewed distributions across countries. To improve interpretability and visual contrast, logarithmic scaling was applied where appropriate.

# 📈 Data Source
COVID-19 Global Dataset from Kaggle
(josephassaker/covid19-global-dataset)

# Set Up 
1. Set Up Kaggle API, See documentation at: https://www.kaggle.com/docs/api
2. Download notebooks/download_data.ipynb and run it 
