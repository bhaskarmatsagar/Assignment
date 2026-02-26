# 📊 Trader Performance vs Market Sentiment Analysis

## Data Science Intern -- Round 0 Assignment

Submitted to: Primetrade.ai

------------------------------------------------------------------------

## 📌 Project Objective

This project analyzes how **Bitcoin market sentiment (Fear vs Greed)**
influences:

-   Trader performance (PnL, win rate)
-   Trading behavior (trade size, frequency, long/short bias)
-   Profit consistency across trader segments

The goal is to extract actionable insights that can inform smarter
trading strategies.

------------------------------------------------------------------------

## 📂 Datasets Used

### 1️⃣ Bitcoin Market Sentiment Dataset

Contains daily market classification: - Fear - Greed

Columns: - Date - Classification

------------------------------------------------------------------------

### 2️⃣ Historical Trader Data (Hyperliquid)

Contains: - Account - Coin - Execution Price - Size USD - Side
(Buy/Sell) - Closed PnL - Timestamp - Trade ID - Fee - etc.

------------------------------------------------------------------------

## ⚙️ Methodology

### Step 1 --- Data Preparation

-   Loaded both datasets
-   Checked shape, missing values, duplicates
-   Converted timestamps to date format
-   Merged sentiment data with trader data on daily level
-   Created new features:
    -   Daily PnL per trader
    -   Win indicator
    -   Win rate
    -   Average trade size
    -   Trade frequency
    -   Cumulative PnL

------------------------------------------------------------------------

### Step 2 --- Sentiment-Based Analysis

Compared trader behavior during:

-   Fear days
-   Greed days

Metrics analyzed: - Average Closed PnL - Win rate - Trade size - Number
of trades - Long/Short ratio

------------------------------------------------------------------------

### Step 3 --- Trader Segmentation

Created trader segments:

-   High vs Low profit traders
-   Frequent vs Infrequent traders
-   Large vs Small position traders

Analyzed how each segment behaves across sentiment regimes.

------------------------------------------------------------------------

## 📈 Key Insights

### Insight 1

Trader profitability is generally higher during **Greed** periods
compared to Fear periods.

### Insight 2

Average trade size increases during Greed periods, indicating higher
confidence and risk appetite.

### Insight 3

Frequent traders tend to show more consistent profitability compared to
infrequent traders.

------------------------------------------------------------------------

## 💡 Strategy Recommendations

### Strategy 1

Increase trading activity during Greed periods as overall profitability
and win rate improve.

### Strategy 2

Reduce position size and risk exposure during Fear periods to minimize
downside risk.

### Strategy 3

Maintain consistent trading discipline rather than sporadic
participation.

------------------------------------------------------------------------

## 📊 Visualizations Included

-   PnL distribution (Fear vs Greed)
-   Win rate comparison
-   Trade size comparison
-   Long vs Short ratio
-   Trader segmentation analysis

------------------------------------------------------------------------

## 🛠️ Tech Stack

-   Python
-   pandas
-   numpy
-   matplotlib
-   seaborn
-   Jupyter Notebook

------------------------------------------------------------------------

## ▶️ How to Run

1.  Clone the repository
2.  Install dependencies:

``` bash
pip install pandas numpy matplotlib seaborn
```

3.  Open:

```{=html}
<!-- -->
```
    Assignment_completed.ipynb

4.  Run all cells

------------------------------------------------------------------------

## 👤 Author

Your Name\
Data Science Internship Applicant
