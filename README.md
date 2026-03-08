# COVID-19 Data Cleaning & Exploratory Analysis

A real-world data analysis project using Python on a COVID-19 dataset
covering 211 countries from December 2019 to September 2020.

---

## What this project covers

- Loading and inspecting a raw dataset (44,521 rows, 28 columns)
- Handling missing values across multiple columns
- Removing aggregated rows (World, Europe etc.) for accurate country-level analysis
- Converting date columns to proper datetime format
- Fixing negative values caused by country reporting corrections
- Exploratory Data Analysis with 4 visualizations

---

## Visualizations

- Total COVID-19 cases over time (Top 5 countries)
- Daily new cases smoothed trend (Top 5 countries)
- Total deaths by continent (bar chart)
- Top 10 countries by death rate

---

## Tools used

- Python — pandas, matplotlib, seaborn
- Jupyter Notebook
- Microsoft Excel

---

## Files

- `covid19_analysis.ipynb` — full analysis notebook
- `covid19_cleaned.xlsx` — cleaned dataset ready for use

---

## Key findings

- USA, India, Brazil, Russia and France had the highest total cases
- Europe had the highest total deaths by continent
- Identified and removed aggregated location rows that were skewing results
- Handled negative case values from reporting corrections
