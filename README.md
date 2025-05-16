# COVID-19 Global Data Tracker 🌍🦠

![COVID-19 Data Analysis](https://img.shields.io/badge/Data-Science-blueviolet) 
![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Pandas](https://img.shields.io/badge/Pandas-1.3+-brightgreen)

A data analysis project tracking the global spread of COVID-19, examining cases, deaths, recoveries, and vaccination progress across different countries.

## 📌 Project Overview
This project analyzes the COVID-19 pandemic using real-world data to:
- Track infection and mortality trends
- Compare country responses
- Visualize vaccination progress
- Identify key patterns in the global spread

## 🎯 Objectives
- Import and clean COVID-19 global datasets
- Analyze temporal trends in cases, deaths, and vaccinations
- Compare metrics across countries/regions
- Visualize data through interactive charts and maps
- Generate actionable insights from the pandemic data

## 🛠️ Tools & Libraries
```python
import pandas as pd       # Data manipulation
import numpy as np        # Numerical operations
import matplotlib.pyplot as plt  # Basic visualization
import seaborn as sns     # Advanced visualization
import plotly.express as px # Interactive visualizations
from datetime import datetime # Date handling

🚀 How to Run/View the Project

    Prerequisites:

        Python 3.8+

        Jupyter Notebook (recommended)

    Setup:
    bash

    git clone https://github.com/creppymain/covid19.git
    cd covid19
    pip install -r requirements.txt

    Running the Analysis:

        Download the dataset from Our World in Data

        Place the CSV in the project root

        Open and run covid19.ipynb in Jupyter

🔍 Key Insights

    Vaccination Disparities: Developed nations showed 3-5× faster vaccination rollout than developing countries

    Wave Patterns: Most countries experienced 3-4 major infection waves with 4-6 month intervals

    Mortality Trends: Death rates declined by 40-60% post-vaccination availability

    Regional Spread: Neighboring countries showed correlated case patterns with 2-3 week lags

📂 Project Structure

/covid-19
│── /data                 # Raw and processed datasets
│── /notebooks            # Jupyter notebooks
│── /visualizations       # Generated charts and graphs
│── requirements.txt      # Python dependencies
│── README.md             # This file

🤔 Reflections

This project revealed:

    The critical importance of open data during global crises

    How visualization can make complex pandemic data accessible

    The value of time-series analysis in public health

    Challenges in data consistency across different reporting systems
