## 📌 Project Overview

This project analyzes solar energy data from different countries to discover patterns, clean the dataset, and generate insights using Exploratory Data Analysis (EDA). The goal is to build a clean and reproducible data analysis pipeline while following best practices in data science and Git.

---

## 🧰 Environment & Setup

### Requirements

To run this project, install dependencies using:

```bash
pip install -r requirements.txt
```

**Main libraries used:**

* pandas
* numpy
* matplotlib
* seaborn
* plotly
* jupyter

### Project Structure

```
solar-data-discovery-duresa-eshetu/
│
├── data/                    # Raw and cleaned datasets
├── notebooks/               # Jupyter notebooks for EDA
├── scripts/                 # Python scripts for cleaning and analysis
├── outputs/                 # Exported graphs and visuals
├── requirements.txt         # List of required Python packages
├── README.md                # Project overview and instructions
└── .gitignore
```

---

## 🧪 Data Profiling, Cleaning, and EDA

* Loaded and examined the dataset for missing values and inconsistencies.
* Cleaned the data by:

  * Removing or imputing missing values
  * Converting date columns and standardizing units
* Performed EDA to explore trends in solar energy usage by country and over time.
* Visualizations include:

  * Line plots of solar generation over years
  * Bar charts comparing countries
  * Histograms of capacity distributions

## 🌐 Cross-Country Comparison

Analyzed solar energy trends for multiple countries based on:

* Total solar energy generation
* Year-on-year growth
* Per capita solar capacity

Key insights were visualized with side-by-side comparisons to highlight differences in energy investment and output.

## ✨ Time Management & Git Usage

* Used Git for version control with clear commit history.
* Regular commits made throughout analysis stages.
* The repository is organized with a clean structure and documented steps.
* Setup instructions included for easy reproducibility.
