# Bitcoin Data Analysis

This project performs an analysis of Bitcoin historical price data. The notebook processes the data to generate insights about price movements and trends.

## Project Overview

This repository contains a Jupyter Notebook that analyzes historical Bitcoin price data. The dataset includes daily price information such as:

- Opening price
- Closing price
- High and low prices for the day
- Volume traded
- Market capitalization

The analysis calculates the price trend (whether the closing price was higher or lower than the opening price) and visualizes important trends.

## Features

- **Data Cleaning and Preprocessing**: Cleans and processes the Bitcoin dataset for analysis.
- **Price Trend Analysis**: Determines whether the price trend is upward or downward based on the difference between the closing and opening prices.
- **Data Visualization**: Includes various plots to visualize the trends in Bitcoin prices over time.

## Usage

### Requirements

To run this project, you need the following Python packages installed:

- `pandas`
- `matplotlib`
- `seaborn`
- `numpy`
- `plotly` (optional, for interactive visualizations)

You can install them using:

```bash
pip install pandas matplotlib seaborn numpy plotly
```

### Running the Notebook

1. Clone this repository:
    ```bash
    git clone https://github.com/your-username/bitcoin-data-analysis.git
    ```
2. Navigate to the project directory:
    ```bash
    cd bitcoin-data-analysis
    ```
3. Open the Jupyter Notebook:
    ```bash
    jupyter notebook Bitcoin_data_analysis.ipynb
    ```
4. Run the notebook to see the analysis and visualizations.

## Data

The dataset contains the following fields:
- `Date`: The date of the observation.
- `Open`: Opening price of Bitcoin on that date.
- `Close`: Closing price of Bitcoin on that date.
- `High`: The highest price reached that day.
- `Low`: The lowest price reached that day.
- `Volume`: The amount of Bitcoin traded.
- `Market Cap`: The total market capitalization of Bitcoin.

## Price Trend Calculation

The price trend is calculated using a simple comparison:

```python
if close_price > open_price:
    trend = "Up"
else:
    trend = "Down"
```

This is stored as a new column in the dataset called `Price Trend`.

## Results

The notebook includes:
- Daily price movements over time.
- Visualizations of trends in the Bitcoin market.
- A detailed comparison of upward vs. downward price trends.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.
