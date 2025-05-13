# Week-8-

# COVID-19 Data Analysis

This project analyzes global COVID-19 data using Python and several data science libraries. The main analysis is performed in the Jupyter notebook [covid_data.ipynb](covid_data.ipynb).

## Files

- **[covid_data.ipynb](covid_data.ipynb)**: The main Jupyter notebook containing all data analysis, cleaning, visualization, and exploratory tasks.
- **owid-covid-data.csv**: The dataset used for analysis, sourced from Our World in Data.
- **README.md**: This file.

## Overview of [covid_data.ipynb](covid_data.ipynb)

The notebook performs the following tasks:

1. **Data Loading**  
   Loads the COVID-19 dataset (`owid-covid-data.csv`) using pandas.

2. **Data Exploration**  
   - Displays column names and previews the first few rows.
   - Identifies missing values in the dataset.

3. **Data Cleaning**  
   - Filters data for specific countries (e.g., Russia, Canada, Kenya, China, Australia).
   - Removes rows with missing dates and converts date columns to datetime.
   - Handles missing values in selected columns.

4. **Exploratory Data Analysis (EDA)**  
   - Plots total COVID-19 cases and deaths over time for the top affected countries.
   - Visualizes the top 10 countries by total cases on the latest available date.
   - Shows vaccination progress for randomly selected countries.
   - Analyzes smoking rates by gender for a random country.

5. **Geospatial Visualization**  
   - Builds a choropleth map to visualize COVID-19 case density per 100,000 people by country using Plotly.

## Requirements

- Python 3.x
- pandas
- matplotlib
- seaborn
- plotly
- geopandas

Install dependencies with:
```sh
pip install pandas matplotlib seaborn plotly geopandas
```

## How to Use

1. Place `owid-covid-data.csv` in the same directory as the notebook.
2. Open [covid_data.ipynb](covid_data.ipynb) in Jupyter Notebook or VS Code.
3. Run the notebook cells to perform the analysis and view the visualizations.

## Notes

- The notebook is organized into cells, each performing a specific step in the analysis pipeline.
- Visualizations include line charts, bar charts, pie charts, and choropleth maps.
- The code is commented for clarity and learning purposes.

---

Data source: [Our World in Data](https://ourworldindata.org/covid-cases)
