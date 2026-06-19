# Cricket Matches Exploratory Data Analysis (EDA)

This project performs a comprehensive Exploratory Data Analysis (EDA) on a historical cricket dataset containing information about Indian Premier League (IPL) matches. The goal is to uncover key trends, team performances, toss decisions, venue statistics, and win distributions through clear data visualizations and statistical summaries.

## 📊 Project Overview

The analysis explores a dataset spanning various seasons and extracts meaningful insights about match outcomes. It handles data cleaning, handles missing information, and utilizes descriptive data visualization techniques to highlight patterns that influence a match's results.

## 🚀 Key Insights Discovered
* **Most Successful Team:** Mumbai Indians holds the record for the highest number of match wins.
* **Toss Strategy:** Teams predominantly prefer to **field** first upon winning the toss.
* **Top Venue:** **Eden Gardens** has hosted the maximum number of matches in this dataset.

---

## 🛠️ Tech Stack & Libraries
* **Language:** Python 3.13+
* **Data Manipulation:** `pandas`, `numpy`
* **Data Visualization:** `matplotlib`, `seaborn`
* **Environment:** Jupyter Notebook

---

## 📈 Visualizations Included

The notebook generates the following visual insights:
1. **Top 5 Winning Teams:** A horizontal bar plot illustrating the most dominant teams.
2. **Toss Decision Count:** A breakdown of choices made by captains (Batting vs. Fielding).
3. **Top 10 Venues:** A visual ranking of stadiums based on total matches hosted.
4. **Distribution of Wins (Runs & Wickets):** Histogram plots displaying victory margins.

---

## 📁 Directory Structure
```text
cricket-eda/
│
├── data/
│   └── matches.csv          # Source dataset containing match history
│
├── cricket2eda.ipynb        # Main Jupyter Notebook containing the analysis
└── README.md                # Project documentation
