# Pesa Pulse: API Data Analysis Using Python Structures

A data-analysis project in Python. It pulls a partner's customer directory from an API, explores its nested structure, answers "where are our customers?" with plain Python and then with pandas and ends with a chart that marketing can drop into a slide.

## What this project does

1. Fetches customer data from the API with `requests`, handling failures without crashing.
2. Explores the nested JSON structure.
3. Extracts the attributes that matter into flat records.
4. Finds the unique cities.
5. Counts customers per city and per email domain .
6. Loads the data into a **pandas** DataFrame and checks that pandas agrees with the hand-written counts.
7. Exports the results to CSV.
8. Draws and saves charts with **matplotlib**.

## Requirements

- Python 3.10+
- [requests](https://requests.readthedocs.io/) for the API call
- [pandas](https://pandas.pydata.org/) for tables and CSV export
- [matplotlib](https://matplotlib.org/) for charts
- Jupyter Notebook
