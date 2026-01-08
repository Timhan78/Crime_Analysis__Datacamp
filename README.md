# Crime Data Analysis (DataCamp Project)

## Overview

This is my **first fully completed data analysis project**, developed independently as part of my studies on **DataCamp** and adapted for my personal portfolio.

The project focuses on exploratory data analysis of crime data, with particular attention to **time patterns**, **night-time crime hotspots**, and **victim age group segmentation**.  
The emphasis is on clear logic, correct use of pandas, and reproducible analysis rather than advanced modelling.

---

## Project Goals

The main objectives of this project are:

1. Identify the **hour with the highest frequency of crimes**
2. Determine the **area with the highest number of night crimes**  
   (defined as crimes committed between **22:00 and 03:59**)
3. Analyse crime frequency across **defined victim age groups**

---

## Data Source

This project is based on a practical exercise from **DataCamp**.

- Original project page:  
  https://projects.datacamp.com/projects/1876

The dataset was downloaded locally from DataCamp and analysed in Python.  
All data cleaning, feature engineering, aggregation, and interpretation steps in this repository were implemented by me as part of my learning process.

---

## Tools and Technologies

- Python
- pandas
- NumPy
- Matplotlib / Seaborn
- Jupyter Notebook
- Git & GitHub

---

## Key Analysis Steps

- Validation and exploration of time variables (`TIME OCC`, `hour_of_OCC`)
- Identification of peak crime hours using frequency analysis
- Correct handling of night-time intervals that cross midnight
- Aggregation of night crimes by area
- Creation of meaningful **age groups** using explicit bins
- Frequency analysis of crimes by age group

---

## Key Findings

- Crimes show a clear **temporal concentration** during specific hours
- Certain **areas** experience significantly higher crime activity at night
- Crime frequency varies noticeably across **victim age groups**

(Exact values and outputs are shown in the notebook.)

---

## Why this project matters

This project demonstrates:

- My ability to complete an analysis **end-to-end**
- A solid understanding of pandas aggregation and grouping logic
- Attention to common pitfalls in time-based and categorical analysis
- Clean, readable, and reproducible analytical workflows

As my **first finished project**, it represents an important milestone in my transition toward a data analytics role.

---

## How to run the project

1. Clone the repository
2. Open `crime_analysis_datacamp.ipynb` in Jupyter Notebook or VS Code
3. Run all cells from top to bottom

No additional configuration is required.

---

## Notes

- This repository is intended as a **learning and portfolio project**
- The dataset is public and provided by DataCamp
- The analytical approach and notebook structure are my own
