# Neutral_Temperature_Plotly
# Daily Averaged Kinetic Temperature Plot

This repository contains a Python script for plotting daily averaged kinetic temperature values over a specified period. The script reads CSV files, processes the data, and generates an interactive line plot using Plotly.

## Project Overview

This project processes kinetic temperature data from multiple CSV files and visualizes it in an interactive plot. The data contains daily average kinetic temperature values, 
which are plotted relative to a specified end date (February 27, 2010). The plot is customizable with titles, axis labels, and tick formatting.

## Files

- `kinetic_temperature_plot.py`: The main Python script that processes the CSV files and generates the plot.
- `daily_average_nt_2009_12.csv`, `daily_average_nt_2010_01.csv`, `daily_average_nt_2010_02.csv`: Example CSV files containing daily averaged kinetic temperature data.

## Requirements

To run the script, you'll need to have Python installed, along with the following libraries:

- `pandas`: For reading and manipulating CSV files.
- `plotly`: For creating interactive plots.
- `datetime`: For handling date and time manipulations.

You can install the required libraries by running:

```bash
pip install pandas plotly
How to Use
Make sure you have the required libraries installed.

Place your CSV files (e.g., daily_average_nt_2009_12.csv, daily_average_nt_2010_01.csv, daily_average_nt_2010_02.csv) in the same directory as the Python script.

Run the Python script:

    python kinetic_temperature_plot.py

    The script will process the data and display an interactive plot in your web browser.

Customization

    Data Files: Modify the file_paths list in the script to include the paths to your own CSV files.
    End Date: The script uses February 27, 2010, as day 0. If you need to adjust the reference date, you can change the value of end_date in the script.
    Plot Style: You can adjust the plot's title, axis labels, font sizes, and other styling properties in the update_layout section of the script.

Example Plot

The generated plot will look similar to the following:

    X-axis: Days relative to February 27, 2010.
    Y-axis: Daily averaged kinetic temperature at 110 km.
    The plot is interactive, allowing you to zoom in, hover over data points, and explore the data.


