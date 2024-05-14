# Online Transaction Data Analysis and Visualization

## Project Overview
This project analyzes and visualizes transaction data from a UK-based and registered non-store online retailer. The dataset spans transactions from December 2010 to December 2011. The primary goal is to explore the sales trends over this period and highlight key patterns and insights that can inform sales and marketing strategies.

## Installation
To run this analysis, you need Python installed on your system, along with the following libraries:
- Pandas
- NumPy
- Matplotlib

- You can install these packages using pip:
  
```bash
pip install pandas numpy matplotlib

```


## Data
The dataset used in this project (online_retail.csv) contains several fields per transaction, including the invoice number, stock code, description, quantity, invoice date, unit price, customer ID, and country.


## Analysis and Visualization Details
This project conducts a comprehensive analysis of the data, including data profiling, cleaning null values, and detecting duplicates. The analysis then moves on to statistical exploration and visualization:

* Conversion of invoice dates to a datetime format.
* Calculation of total sales.
* Monthly sales aggregation and visualization over the period.

### Key Visualizations
* Line chart of monthly sales: This chart displays the trend of sales from December 2010 to December 2011, with annotations highlighting significant data points and trends.


## Design Principles
This visualization adheres to the following design principles:

* Substantive: Shows clear trends over time, effectively using a line chart for time series data.
* Perceptual: Uses contrasting colors to highlight annotations and ensure they stand out.
* Aesthetic: Employs a minimal color palette
