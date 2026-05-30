# E-Commerce Data Analysis Project

## Project Overview
This project analyzes a large-scale retail dataset containing over 500,000 transactions. The goal was to clean raw transaction data and identify key revenue drivers and seasonal trends.

## Key Steps Performed
* **Data Scrubbing:** Handled a dataset with 25% missing or invalid records. Removed negative quantities and missing Customer IDs to ensure financial accuracy.
* **Feature Engineering:** Created a `Total_Sales` metric and converted date strings into usable time-series objects.
* **Regional Analysis:** Identified the UK, Netherlands, and EIRE as the top three revenue-generating markets.
* **Trend Visualization:** Plotted monthly revenue which revealed a 100% growth spike during the Q4 holiday season.

## Tools Used
* Python (Pandas, Matplotlib)
* Google Colab
* Jupyter Notebooks
