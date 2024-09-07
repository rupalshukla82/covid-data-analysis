# Covid Data Analysis

## Table of Contents

   - Description
   - Features
   - How to Use
   - Live Links
   - Technology Used
   - Lessons Learned

## Description

This repository contains an analysis of COVID-19 data focusing on confirmed cases, deaths, recovered, and critical cases across the top 15 countries. The aim is to provide insight into the pandemic's impact through graphical representations, offering a clear overview of these key metrics.
## Features

   - Unique values only for accuracy.
   - Graphical analysis using bar, scatter, and line plots.
   - Visualization of confirmed, critical, death, and recovery cases across the top 15 countries.
   - Line plots comparing death and recovery rates.

## How to Use

To use this repository locally, install the following Python packages:

   - numpy: pip install numpy
   - pandas: pip install pandas
   - matplotlib: pip install matplotlib

## Live Links

   - GitHub URL: Covid Data Analysis Repository
   - Live Demo : <a href="https://mybinder.org/v2/gh/rupalshukla82/covid-data-analysis/HEAD">Binder</a>

## Technology Used

   - NumPy: For numerical operations.
   - Pandas: For data manipulation and analysis.
   - Matplotlib: For static and interactive visualizations.

## Lessons Learned

   - Using aggregation functions (e.g., agg(['min', 'max'])) to find specific data values.
   - Displaying detailed data when only maximum and minimum values are available.
   - Summing country data using the groupby() method.
   - Sorting and extracting specific countries' data using sort_values() and head() methods.

