Cricket Matches Exploratory Data Analysis (EDA)

This repository contains a comprehensive Exploratory Data Analysis (EDA) on a historical cricket dataset of Indian Premier League (IPL) matches. The goal is to uncover key trends, team performances, toss decisions, venue statistics, and win distributions using clean python-based data visualizations and statistical summaries.

📊 Project Overview

The analysis explores a rich dataset of cricket matches to discover patterns influencing game outcomes. It processes data cleaning, handles missing values, and implements descriptive data visualizations to highlight trends across multiple dimensions such as team dominance, favorite venues, and match-winning factors.

Dataset Features Analysed:

Match Information: Match date, season, city, venue, and participating teams.

Toss Decisions: Toss winner and the subsequent decision (bat first or field first).

Match Outcomes: Winning team, margin of victory (by runs or by wickets), and player of the match.

Officials: On-field umpires.

🚀 Key Insights Discovered

Most Successful Team: Mumbai Indians holds the record for the highest number of match wins in this dataset.

Toss Strategy: Teams predominantly prefer to field first upon winning the toss.

Top Venue: Eden Gardens is the stadium that has hosted the maximum number of matches.

📈 Visualizations & Analysis Steps

The notebook cricket2eda.ipynb contains step-by-step executions of the following:

Data Overview & Cleaning:

Handled missing values (e.g., filled missing cities using mode values).

Dropped columns with excessive missing values (such as umpire3).

Top 5 Winning Teams: A horizontal bar plot illustrating the most dominant teams.

Toss Decision Count: A breakdown of choices made by captains (Batting vs. Fielding).

Top 10 Venues: A visual ranking of stadiums based on the total number of matches hosted.

Distribution of Wins by Runs: A histogram plot with Kernel Density Estimation (KDE) demonstrating victory margins in runs.

Distribution of Wins by Wickets: A frequency distribution of victory margins in wickets.

🛠️ Tech Stack & Dependencies

Language: Python 3

Data Manipulation: pandas, numpy

Data Visualization: matplotlib, seaborn

Environment: Jupyter Notebook / JupyterLab

⚙️ Setup and Installation

Prerequisites

Make sure you have Python installed on your system. You can download it from python.org.

1. Clone the Repository

Clone this repository to your local machine using the command line:

git clone [https://github.com/yourusername/cricket-eda.git](https://github.com/yourusername/cricket-eda.git)
cd cricket-eda


2. Install Dependencies

Install all the required python packages using pip:

pip install pandas numpy matplotlib seaborn notebook


3. Update Dataset Path

Inside the cricket2eda.ipynb notebook, locate the file loading cell and ensure the data path correctly points to your local copy of matches.csv. For example:

data = pd.read_csv("data/matches.csv")


4. Run the Notebook

Launch Jupyter Notebook to interact with and run the analysis:

jupyter notebook


Once the browser window opens, click on cricket2eda.ipynb and run the cells sequentially to reproduce the visualizations and insights.

📁 Directory Structure

cricket-eda/
│
├── data/
│   └── matches.csv          # Source dataset containing match history
│
├── cricket2eda.ipynb        # Jupyter Notebook containing the full python code
└── README.md                # Project documentation


📝 License

This project is open-source and available under the MIT License.
