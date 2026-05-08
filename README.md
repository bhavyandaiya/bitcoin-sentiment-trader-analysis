# Bitcoin Market Sentiment and Trader Performance Analysis

## Overview

This project analyzes the relationship between Bitcoin market sentiment and trader performance using historical trading data and the Fear and Greed Index.

The objective was to uncover behavioral and profitability patterns under different market sentiment conditions and derive insights that could support smarter trading strategies.

---

## Datasets Used

### 1. Historical Trader Data
Contains detailed trade level activity including:
- Execution price
- Trade size
- Closed PnL
- Fees
- Direction
- Timestamp

### 2. Fear and Greed Index
Contains daily Bitcoin market sentiment classifications:
- Extreme Fear
- Fear
- Neutral
- Greed
- Extreme Greed

---

## Project Workflow

1. Data loading and inspection
2. Data cleaning and preprocessing
3. Datetime conversion
4. Dataset merging using date
5. EDA
6. Visualization and behavioral analysis
7. Correlation analysis
8. Insight generation

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---


## Key Findings

1. Trader profitability was highest during Extreme Greed market conditions.

2. Extreme Greed also showed the highest trader win rate, indicating stronger overall trade consistency.

3. Fear markets exhibited the highest trading activity, suggesting traders become more active during uncertain conditions.

4. Extreme Fear showed relatively lower win rates despite moderate profitability, implying that a few large winning trades may offset many smaller losses.

5. Larger trade sizes strongly correlated with higher transaction fees.

6. Closed PnL showed weak direct correlation with most numerical variables, suggesting that profitability depends more on market conditions and strategy execution than simple trade size.

---

#### Author
Bhavyan Daiya (https://www.linkedin.com/in/bhavyan-daiya-648939241/)