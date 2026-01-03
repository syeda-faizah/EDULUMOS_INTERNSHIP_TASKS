# Netflix Movies & TV Shows – Exploratory Data Analysis (EDA)

This repository contains the work completed for the Netflix EDA task as part of the **Data Science Internship**.  

The project analyzes Netflix’s content library to uncover trends in **content type distribution, release patterns, country-wise production, movie durations, and ratings** using Python, Pandas, and visualization libraries.  

---

## Files Included

|                  File Name                   |                                  Description                                |
|----------------------------------------------|-----------------------------------------------------------------------------|
| `netflix_titles.csv`                         | Dataset containing Netflix Movies and TV Shows                              |
| `SyedaFaizah_Week4_Task03_Netflix_EDA.ipynb` | Jupyter Notebook with data preprocessing, feature engineering, and analysis |
| `SyedaFaizah_Week4_Task03_Report.pdf`        | Final report with methodology, results, visualizations, and conclusions     |

---

## Getting Started

1. Clone the repository:

```bash
git clone https://github.com/syeda-faizah/EDULUMOS_INTERNSHIP_TASKS.git
```
Install dependencies:

pip install pandas numpy matplotlib seaborn

Open the notebook:

jupyter notebook SyedaFaizah_Week4_Task03_Netflix_EDA.ipynb

## Dataset Overview
Total Titles: 8,807

Columns: 12

show_id – Unique identifier for each title

type – Movie or TV Show

title – Name of the content

director – Director(s) of the title

cast – Main actors/actresses

country – Country of production

date_added – Date content was added to Netflix

release_year – Original release year

rating – Audience rating (e.g., PG-13, TV-MA)

duration – Duration in minutes (Movies) or number of seasons (TV Shows)

listed_in – Genre/category of the content

description – Short synopsis

## Notes:

Missing values in director, cast, country were filled with Unknown

Missing rating and date_added values were filled with mode values

date_added converted to datetime; extracted year_added and month_added

Duration processed into numeric values (duration_num) and type (minutes or seasons)

## Tools & Technologies
Python

Pandas & NumPy

Matplotlib & Seaborn

## Summary of Analysis
This project explores trends in Netflix’s content library using Exploratory Data Analysis (EDA).

## Key Steps:

Data Preprocessing – Handled missing values, converted dates, processed durations

Feature Engineering – Created year_added, month_added, duration_num, duration_type

Analysis & Visualizations – Plots and trends are included in the report PDF

## Key Insights
Movies dominate Netflix content library

Rapid growth in content after 2016

USA produces the majority of titles, followed by India and the UK

Most movies are 80–120 minutes long

TV Shows dominate mature ratings, while Movies are more evenly distributed across age groups

Content additions peak mid-year, showing seasonal trends

## Future Scope
Analyze genre-wise trends to identify popular categories

Study cast/director influence on content popularity

Build predictive models for content success based on historical trends

Incorporate user ratings and reviews for deeper insights

## Metadata
Submitted By: Syeda Faizah

Internship: Data Science Internship

Submission: January 2026

## Dataset Source
Publicly available on Kaggle: Netflix Movies and TV Shows
