# Gopika-FODS-Assignment1

# Amazon Sales Data Analysis

## Introduction..

This project involves analyzing Amazon sales data to extract meaningful insights. The dataset contains various details about sales, including regions, countries, item types, sales channels, order priorities, order and ship dates, units sold, unit prices, unit costs, total revenues, total costs, and total profits.

## Files

- `FODS_Assignment1.ipynb`: Jupyter notebook containing the code for data analysis.
- `AmazonSalesData.csv`: The dataset used for analysis.

## Requirements

- Python 3
- pandas

## Installation

To install the required packages, run:
```bash
pip install pandas
```
## Data analysis
Importing Libraries: The notebook imports the pandas library, which is essential for data manipulation and analysis.

```bash
import pandas as pd
```
Loading the Dataset: It reads a CSV file named AmazonSalesData.csv into a DataFrame.

```bash
df = pd.read_csv('/content/AmazonSalesData.csv')
```

Displaying the Data: It prints the contents of the DataFrame to give an initial overview of the dataset.
```bash
print(df)
```
Display the first five rows of the dataset to get a quick overview of the data
```bash
df.head()
```

Display the last five rows of the dataset to understand the data structure towards the end
```bash
df.tail()
```

Display the dimensions of the dataset (number of rows and columns)
```bash
df.shape
```

Display the column names of the dataset
```bash
df.columns
```
Display the dimensions of the dataset (number of rows and columns)
```bash
df.shape
```
Display the count of each data type in the dataset
```bash
df.dtypes.value_counts()
```
```bash

import matplotlib.pyplot as plt

//Generate histograms for each numeric column in the dataset
//figsize=(8,8) sets the overall size of the plot to 8 inches by 8 inches
//color='#cc5500' sets the color of the histograms to a specific shade of orange

df.hist(figsize=(8,8), color='#cc5500')

# Display the figure containing the histograms

plt.show()
```
Histograms: These are graphical representations that show the distribution of data points for each numeric column. Each bar in a histogram represents the frequency (count) of data points within a specific range (bin).
Figure Size (figsize): Adjusting the figure size helps in making the plots more readable, especially when dealing with multiple histograms.
Color: Changing the color of the histograms can make the plots more visually appealing and distinguishable, especially when presenting the data.










