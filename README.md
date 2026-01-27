
# 📊 COVID-19 Global Visualization

This project presents an interactive visualization of COVID-19 cases and deaths across countries worldwide. The goal is to make large-scale pandemic data easier to explore, compare, and understand through clear and intuitive visual analytics.

🔍 Key Features

🌍 Global coverage of COVID-19 cases and deaths by country

📈 Interactive Plotly visualizations (hover, zoom, filter)

🎨 Clean, minimal web layout for easy navigation

📊 Multiple visualization types (maps, distributions, comparisons)

🧠 What This Project Demonstrates

Data cleaning and preprocessing of real-world datasets

SQL & Python-based data analysis workflows

Effective data storytelling through visualization

Web integration of Plotly .html outputs using HTML & CSS

🛠️ Tech Stack

Python (Pandas, NumPy)

Plotly for interactive visualizations

HTML & CSS for presentation

SQLite for data querying

# Set Up 
1. Set Up Kaggle API, See documentation at: https://www.kaggle.com/docs/api
2. Download notebooks/download_data.ipynb and run it 

# Description 
- SQL - Mainly used for Data Manipulation. Selecting, filtering, grouping. Reshaping data. 
- Python - For data analysis, visualization 

# About Data: 
  - The COVID-19 dataset used are from https://www.kaggle.com/search?q=josephassaker%2Fcovid19-global-dataset+in%3Adatasets
  - Date Format: Dates are converted to the format YYYY.MM.DD, for better interpretation
  - Countries: Added a new column with ISO-3 code for each countries
  - Numerical values: There has been a quiet large standard deviation between each variables, therefore log-scale are applied to these values. 

# 🌐 Live Interactive Dashboard
👉 https://mr0ndre.github.io/COVID-19-Visualization-/

