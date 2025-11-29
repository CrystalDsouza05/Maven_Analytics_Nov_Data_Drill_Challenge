# SPY Golden Cross Detection Dashboard (Power BI)

This project was created as part of a **Maven Analytics Data Drill Challenge** focused on detecting Golden Cross signals using historical stock market data for the SPDR S&P 500 ETF Trust (SPY).

The objective was to calculate moving averages and identify trend reversal points using analytical logic and visual storytelling.

---

## 🔍 Challenge Description

This challenge was provided by Maven Analytics and required participants to:

- Work with five years of daily closing price data for SPY
- Calculate:
  - 50-day moving average
  - 200-day moving average
- Identify every **Golden Cross** event where:
  - The 50-day moving average crosses from below to above the 200-day moving average
- Visualize and interpret potential bullish signals

Dataset source:
https://bit.ly/48YeURB

Participants were encouraged to build the solution using any analytics tool such as Excel, Power BI, Python, SQL, or related platforms.

---

## 📘 What is a Golden Cross?

A **Golden Cross** occurs when a short-term moving average rises above a long-term moving average. In financial markets, this pattern is interpreted as a bullish signal and may indicate the beginning of an upward trend.

---

## 📊 Golden Cross Events Detected

Based on the analysis, two Golden Cross events were identified in the dataset:

| Date        | Close Price |
|--------------|-------------|
| 02 Feb 2023  | 417         |
| 01 Jul 2025  | 618         |

These points signal moments where short-term momentum overtook the long-term trend, often associated with market recovery and investor confidence.

---

## ⚙️ Approach & Logic

### Moving Averages
- 50-Day MA represents short-term momentum
- 200-Day MA reflects long-term trend direction

### Golden Cross Detection
A Golden Cross is flagged only when:
- Today's 50-day MA is greater than today’s 200-day MA AND
- The previous trading day's 50-day MA was lower than the previous 200-day MA

This ensures accurate detection of crossover events without false signals.

---

## 📈 Dashboard Features

- Line chart visualizing:
  - Closing price
  - 50-Day MA
  - 200-Day MA
- Highlighted Golden Cross points on the price trend
- Tooltip explanations
- Clean layout and time-based filtering

---

## Dashboard Image

<img width="1613" height="904" alt="image" src="https://github.com/user-attachments/assets/00997cb3-18d2-4190-af8d-d9acc80068c6" />

---

## 🛠 Tools Used

- Power BI Desktop
- Power Query
- DAX
- Excel (for preprocessing)

---

## 🎯 Key Skills Demonstrated

- Technical indicator logic
- Time-series analysis
- Financial data modeling
- DAX measures and calculated columns
- Dashboard design and storytelling

---

## 🏁 Project Status

Completed ✅  
Open for enhancements and optimization.

---

## 📢 Credits

This challenge was organized by:
Maven Analytics  
LinkedIn Data Drill Initiative

Special thanks to Maven Analytics for providing the dataset and learning opportunity.

---

## 📬 Feedback

Suggestions, feedback, and collaborations are always welcome.

---

Thank you for exploring this project.
