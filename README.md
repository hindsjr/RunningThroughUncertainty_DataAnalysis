# Running Data Analysis

By Julia Hinds

## Overview
This project analyzes global running activity data from 2019–2020 to study how training patterns evolved before and during the COVID-19 pandemic.
It investigates trends in average distance and duration over time, the impact of government lockdowns, changes in country-specific running behavior, and marathon training adaptations, with a special focus on the Boston Marathon.

## Motivation
As a runner personally affected by the disruptions of 2020, I was motivated to explore how athletes worldwide adjusted their training habits during this period. This analysis combines real-world running data with COVID-19 government stringency indexes to better understand the resilience and challenges faced by the running community.

### Key Questions
How did average running distance and duration change over time?

How did training patterns vary between genders and countries?

What was the impact of COVID-19 lockdown measures on running activity?

How did marathon training, particularly for events like the Boston Marathon, differ between 2019 and 2020?

## Tools and Libraries
Python (Pandas, Matplotlib, Seaborn)

Dataset: Athlete running data (2019–2020) from Kaggle and COVID-19 Stringency Index from Our World in Data

## Results Summary
A slight decline in overall training volume was observed over two years, with clear seasonal peaks in spring and fall.

COVID-19 lockdowns showed only a weak global correlation with running activity, though country-specific variations were notable.

Training volumes dropped modestly after March 2020, with major race preparations significantly affected in 2020 compared to 2019.

## Structure

- ```Running_Through_Uncertainty-Data_Analysis.ipynb```
    - Python Jupyter Notebook containing analysis
- Inputs
    - Folder to store data from abopve dataset
- ```Running_Through_Uncertainty-Data_Analysis.pdf```
    - LaTEX PDF of notebook

## How to Run

1. Ensure you have the required datasets (run_ww_2019_d.csv, run_ww_2020_d.csv, and covid_stringency_index.csv).

2. Install necessary Python libraries: ```pip install pandas matplotlib seaborn```

3. Run the Jupyter Notebook to visualize results and summary plots.

## Acknowledgments
Running activity data and COVID-19 Stringency Index data sourced ```https://www.kaggle.com/datasets/mexwell/long-distance-running-dataset```
Additional resources: 
- https://ourworldindata.org/metrics-explained-covid19-stringency-index
