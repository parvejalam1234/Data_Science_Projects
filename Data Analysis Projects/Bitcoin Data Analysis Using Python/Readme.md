# Bitcoin Data Analysis Using Python

## Objective
This project demonstrates the ability to manipulate data using Python, including filtering, looping, and applying conditional statements. It involves creating a Pandas DataFrame, adding data, performing Exploratory Data Analysis (EDA), and additional operations on Bitcoin price data.

---

## Assignment Breakdown

### 1. Create a DataFrame
A Pandas DataFrame is created with the following columns:
- `Date`: Date of Bitcoin prices
- `Open`: Opening price of Bitcoin on that day
- `High`: Highest price of Bitcoin on that day
- `Low`: Lowest price of Bitcoin on that day
- `Close`: Closing price of Bitcoin on that day
- `Volume`: Trading volume of Bitcoin on that day
- `Market Cap`: Market capitalization of Bitcoin on that day

---

### 2. Add Data
At least 30 days of historical Bitcoin dummy data is added to the DataFrame.

---

### 3. Perform Exploratory Data Analysis (EDA)
- **Descriptive Statistics**: Display the mean, median, standard deviation, and other statistics for the dataset.
- **Time Series Plot**: Plot a time series of the `Close` price of Bitcoin.
- **Volume Distribution**: Plot the distribution of Bitcoin `Volume`.
- **Pair Plot**: Show the relationship between `Open`, `Close`, `High`, and `Low` using a pair plot.
- **Correlation Matrix**: Calculate and display the correlation between `Open`, `High`, `Low`, `Close`, and `Volume`.

---

### 4. Apply Filtering Conditions
- Filter the DataFrame to display only the rows where:
  - The `Close` price is greater than the `Open` price (indicating a positive gain).
  - The trading `Volume` was higher than the average trading volume for that period.

---

### 5. For Loop and Conditional Statements
- **For Loop**: Iterate over the rows of the DataFrame and calculate the daily price change (difference between `Close` and `Open`), adding this as a new column `Price Change`.
- **If-Else Condition**: Create a new column `Price Trend` where:
  - If the `Close` price is higher than the `Open` price, the value is "Up."
  - Otherwise, the value is "Down."

---

## Deliverables
- A Python script or Jupyter Notebook that includes:
  1. Creation of the DataFrame with the specified columns.
  2. Insertion of at least 30 days of historical Bitcoin dummy data.
  3. EDA with descriptive statistics, visualizations (time series plot, distribution plot, pair plot), and correlation calculation.
  4. Filtering of the DataFrame based on the specified conditions.
  5. Implementation of a for loop and conditional statements to compute the `Price Change` and `Price Trend`.

---

### Prerequisites
- Python 3.x
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook (Optional)

---

### Running the Script
To run the Python script:
1. Ensure you have all the dependencies installed:
   ```bash
   pip install pandas matplotlib seaborn jupyter
