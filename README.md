# COVID-19 Data Visualization

## Introduction
This project is mainly for visualizing COVID-19 data. It includes various Python scripts that utilize Pandas, Matplotlib and Seaborn to create informative visualizations such as histograms, line plots, and heatmap.

## Project Structure
- General function:
  - `get_covid_data`: A function to download the latest COVID-19 data or load it from a local CSV file if already downloaded.
  - `create_plots`: A utility function to facilitate the generation of plots in a subplot layout.
- Specific functions:
  - `create_histograms`: Generates histograms for new cases smoothed over time for specific countries.  
  - `create_lineplot_cases`: Creates line plots to visualize the total and new COVID-19 cases over time.
  - `create_stackplot`: Create stack plots to see how weekly ICU admissions and Hospital Admissions changed over time in countries that have higher human devlopment index.

## Dependencies
- Python
- Pandas
- Matplotlib
- Seaborn
- NumPy
- requests
- pathlib

## Data
The data is from: https://github.com/owid/covid-19-data
