🏏 Cricket Data Analysis – Power BI Project
📌 Project Purpose

This project explores cricket performance data through interactive dashboards in Power BI.
The aim is to demonstrate data collection (web scraping), cleaning, modeling, and visualization skills while analyzing Batting, Bowling, and Fielding performance.

🛠 Tech Stack & Methods

Power BI → Dashboard design, data modeling, visualization

DAX formulas:

Deviation & Absolute Deviation → measure player consistency vs. average performance

LOOKUPVALUE → fetch related stats across tables (e.g., player/team details)

POWER function → normalize or calculate ratios across categories

👉 These formulas ensure analysis is comparative and performance-driven, not just descriptive.

Data Cleaning & Transformation:

Removed invalid strike rates (0 or unrealistic values)

Converted data types for correct aggregation

Categorized strike rates into intuitive labels (“Average”, “Good”, “Excellent”)

Web Scraping:

Extracted cricket performance data from online resources

Transformed raw HTML tables into structured CSV format for Power BI
📂 Dataset

Source: 🔗 (https://stats.espncricinfo.com/ci/engine/stats/index.html?class=2;opposition=3;team=6;template=results;type=batting)Link Here

Type: CSV files (Batting, Bowling, Fielding data)

Description: Cleaned and structured from scraped cricket data

🌟 Features & Highlights

Batting Analysis → Runs, Strike Rates, Boundaries, Centuries

Bowling Analysis → Wickets, Economy, Best Figures, Averages

Fielding Analysis → Catches, Stumpings, Keeper vs Fielder splits
📈 Example Insights

Consistency Check: Deviation highlights which batters are reliable vs streaky

Bowler Effectiveness: Economy + Wickets → identify top strike bowlers

Fielding Reliability: Dismissal ratios → most dependable fielders

❓ FAQ

Q: Why use deviation/absolute deviation in sports analysis?
A: Averages hide volatility. Deviation reveals consistency — whether a player’s performance is stable or unpredictable.

Q: Why categorize strike rates?
A: Labels like “Good” or “Excellent” are more intuitive for coaches, analysts, and fans than raw numbers.

Screenshot/Demo
BATTING :-(https://github.com/Karuna9502/CRICKET-DATA-ANALYSIS/blob/main/BATTING.png)
BOWLLING :-(https://github.com/Karuna9502/CRICKET-DATA-ANALYSIS/blob/main/BALLING.png)
FIEDLING :- ()
