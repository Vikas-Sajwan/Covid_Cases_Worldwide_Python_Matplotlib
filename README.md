## 📊 COVID-19 Worldwide Data Analysis

This repository contains a comprehensive Python script for analyzing and visualizing a worldwide dataset of COVID-19 statistics. The project provides a professional-grade example of a data science workflow, including data cleaning, feature engineering, statistical analysis, and the creation of publication-quality visualizations using popular Python libraries.

-----

### 🎯 Project Overview

The primary goal of this project is to explore and derive insights from a snapshot of global COVID-19 data. The script systematically addresses a series of analysis questions, from calculating fundamental metrics to identifying trends and correlations, all while ensuring data integrity and producing clear, informative plots.

### 📁 Dataset

The analysis is performed on the `Covid_Dataset.csv` file, which contains key pandemic metrics for over 200 countries. The dataset includes:

  - **country**: The country name.
  - **total\_cases**: The cumulative number of confirmed cases.
  - **total\_deaths**: The total number of reported deaths.
  - **total\_recovered**: The total number of recovered individuals.
  - **active\_cases**: The number of currently active cases.
  - **total\_test**: The total number of tests conducted.
  - **population**: The country's total population.

The script includes robust data cleaning steps to handle inconsistencies like "N/A" values and non-numeric data types, ensuring all calculations are based on a reliable foundation.

-----

### 📈 Analysis & Features

The script covers a wide range of analytical tasks, including:

  - **Data Preprocessing**: Standardizing column names and handling missing values.
  - **Descriptive Statistics**: Calculating worldwide totals for cases, deaths, and recoveries.
  - **Feature Engineering**: Creating new derived metrics such as **mortality rate** and **tests per 1000 people**.
  - **Trend Identification**: Displaying the top 10 countries by total cases, deaths, and recovered cases.
  - **Comparative Analysis**: Identifying the country with the highest mortality rate among those with over 100,000 cases.
  - **Correlation Analysis**: Calculating the correlation coefficient between **total cases** and **total deaths**.

-----

### 🖼 Visualizations

The visualizations are designed with a minimalist white and dark grey theme for optimal clarity and focus on the data. The script generates a variety of plots to highlight key findings:

  - **Bar Charts**: Comparing total cases, deaths, and recoveries across the top countries.
  - **Scatter Plots**: Visualizing the relationship between different metrics, such as total cases and total deaths, including a linear regression line.
  - **Histograms & Box Plots**: Illustrating the statistical distribution of variables like `population` and `total_cases`.
  - **Log-Log Plots**: A scatter plot of `Population` vs. `Total Cases` on a log scale to effectively represent the data's wide range and distribution.

-----

### 🛠 Tech Stack

  - **pandas**: Used for all data manipulation, cleaning, and analysis tasks.
  - **numpy**: Utilized for numerical operations and the calculation of the linear regression line.
  - **matplotlib**: The primary library for creating and customizing all the data visualizations.

-----

### ▶️ Usage

To run this script, ensure you have Python installed and follow these steps:

1.  Clone this repository or download the script and the `Covid_Dataset.csv` file.
2.  Install the necessary Python libraries using pip:
    ```bash
    pip install pandas numpy matplotlib
    ```
3.  Execute the script from your terminal:
    ```bash
    python your_script_name.py
    ```

The script will print the analysis findings to the console and display the generated plots in a new window.
