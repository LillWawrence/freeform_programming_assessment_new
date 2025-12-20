readme markdown

Freeform Programming Assessment – Powerlifting Analysis

This project uses data from the OpenPowerlifting project, https://www.openpowerlifting.org.

The original dataset can be accessed at:
- https://data.openpowerlifting.org
- https://openpowerlifting.gitlab.io/opl-csv/bulk-csv.html

Repository Contents:

The Git repository contains two Python programs:

1) 'data_trimming.ipynb'

- Shows the data cleaning and reduction applied to the original downloaded dataset
- The raw data is over 700MB, so cannot be uploaded to Turnitin
- This notebook is not intended to be run, as it uses this 700MB dataset
- It shows the code used to filter the data (sex and year range), and saves a compressed csv file of the subset of data used in the main notebook

2) 'freeform_programming_assessment.ipynb'

- Further cleans and manipulates the trimmed dataset
- Produces summary statistics
- Codes all data visualisations used in the analysis and presentation slides

To reduce repository size and size added per Git commit, cell outputs were cleared before each Git commit.

Python packages used:
1) Pandas
2) Missingno
3) Matplotlib (pyplot and ticker)
4) Plotly (express)
5) Seaborn
6) Scipy