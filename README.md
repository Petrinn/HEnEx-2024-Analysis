# HEnEx-2024-Analysis
Python analysis of 2024 HEnEx market data, focusing on MCP trends and traded quantities.
 HEnEx 2024 Analysis

## Overview

This project was developed as part of a Big Blue Academy assignment.

In collaboration with Despoina Alonistioti, we created a Python-based data analysis project focused on the 2024 HEnEx Day-Ahead Market results.

The purpose of this project is to process, analyze, and visualize 2024 HEnEx market data in order to better understand hourly and monthly trends in electricity prices and traded quantities.

## Project Description

The analysis is based on 2024 EL-DAM results data from HEnEx.

The project focuses mainly on merging multiple 2024 HEnEx Excel files, aggregating the data, and visualizing key market indicators, such as:

* Market Clearing Price, also known as MCP
* Hourly MCP trends
* Monthly and hourly average MCP
* Buy and sell trades by classification
* Average traded quantities by technology type
* Relationship between selected technologies and average MCP per hour

## Technologies Used

* Python
* Pandas
* Matplotlib
* Seaborn
* Jupyter Notebook
* Excel files as input data

## Dataset

The project uses Excel files containing 2024 EL-DAM results.

The data is loaded from Excel files matching the following pattern:

```python
2024*_EL-DAM_Results_EN_v01.xlsx
```

The notebook reads the `EL-DAM_Results` sheet from each file, filters the data for the year 2024, and combines all files into one dataset for analysis.

## Main Analysis Steps

1. Import and combine 2024 EL-DAM Excel files
2. Convert delivery time data into datetime format
3. Filter records for the year 2024
4. Create month and hour-based aggregations
5. Analyze MCP by hour and month
6. Analyze buy and sell trades by classification
7. Visualize average trades by side and classification
8. Compare selected technologies with mean MCP per hour

## Visualizations

The project includes several visualizations, such as:

* Heatmap of average MCP by month and hour
* Line plot of average MCP per hour
* Bar charts of average buy trades by classification
* Bar charts of average sell trades by classification
* Combined bar chart of average trades by side and classification
* Stacked bar chart of selected technologies with mean MCP per hour


## Usage

Before running the notebook, make sure that the Excel files are available in the correct folder and that the file path in the notebook matches your local directory.

Then, run the notebook cells in order.

## Requirements

The project requires the following Python libraries:

```txt
pandas
matplotlib
seaborn
openpyxl
```

## Contributors

* Despoina Alonistioti
* Petrina Korfiati


## Acknowledgements

This project was completed as gitpart of a Big Blue Academy exercise.

## License

This project is for educational purposes.
