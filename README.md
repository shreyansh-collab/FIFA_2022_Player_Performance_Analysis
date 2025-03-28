# FIFA 2022 Player Performance Analysis

## Overview
This project analyzes the performance of six top soccer players (L. Messi, K. Mbappé, Neymar Jr, Cristiano Ronaldo, O. Giroud, and G. Bale) using the FIFA 2022 dataset. The analysis focuses on key metrics such as overall rating, contribution score (shooting + passing ability), market value, and weekly wages, providing insights into player strengths and commercial potential. The project includes data analysis in Jupyter Notebook, visualizations in Power BI, a detailed report, and a presentation.

## Project Objectives
- Analyze athlete data to track key performance metrics.
- Develop actionable insights for player management and sponsorship strategies.
- Create a Power BI dashboard for interactive visualizations.
- Compile a detailed report for stakeholders.

## Repository Contents
- `FIFA_2022_Analysis.ipynb`: Jupyter Notebook with the full data analysis (data cleaning, metric calculation, initial visualizations).
- `FIFA_2022_Dashboard.pbix`: Power BI file containing the interactive dashboard.
- `FIFA_2022_Dashboard.pdf`: PDF export of the Power BI dashboard.
- `FIFA_2022_Player_Analysis_Report.pdf`: Detailed report summarizing the analysis, findings, and impact assessment.
- `fifa_2022_metrics_final.csv`: Exported data used for Power BI visualizations.

## Metrics Analyzed
- **Overall Rating**: Measures a player’s current ability (e.g., Messi: 93, Giroud: 79).
- **Contribution Score**: Combines shooting and passing ability to reflect on-field impact (e.g., Neymar Jr: 176, Giroud: 150).
- **Market Value (value_eur)**: Indicates commercial potential in euros (e.g., Mbappé: €194M, Giroud: €5M).
- **Weekly Wages (wage_eur)**: Reflects the financial cost of each player (e.g., Ronaldo: €320K, Giroud: €68K).

## Key Findings
- **L. Messi** leads with the highest overall rating (93) and a strong contribution score (175), making him a top all-around player.
- **K. Mbappé** has the highest market value (€194M), indicating significant commercial appeal as a rising star.
- **Neymar Jr** excels in playmaking with a passing ability of 94, contributing to a high contribution score (176).
- **Cristiano Ronaldo** maintains a high overall rating (91) and shooting ability (94), but his high wage (€320K) reflects his cost.
- **O. Giroud** offers value as a cost-effective player with a low market value (€5M) and wage (€68K).
- **G. Bale** has a moderate overall rating (82) and contribution score (172), with a market value of €25M.

## Visualizations
The Power BI dashboard includes:
- **Overall Rating Comparison**: Bar chart showing Messi leading with 93.
- **Shooting vs. Passing Ability**: Clustered bar chart breaking down contribution scores.
- **Market Value Comparison**: Area chart highlighting Mbappé’s €194M value.
- **Weekly Wages**: Donut chart showing Ronaldo’s €320K as the highest wage.

## How to Use This Project
1. **View the Analysis**: Open `FIFA_2022_Analysis.ipynb` in Jupyter Notebook to explore the data cleaning, metric calculation, and initial visualizations.
2. **Interact with the Dashboard**: Open `FIFA_2022_Dashboard.pbix` in Power BI Desktop to interact with the visualizations (requires Power BI Desktop).
3. **Read the Report**: Refer to `FIFA_2022_Player_Analysis_Report.pdf` for a detailed summary of the analysis and findings.

## Dataset
The analysis uses the FIFA 2022 dataset (`players_22.csv`), which can be sourced from Kaggle (not included in this repository due to file size).

## Tools Used
- **Python**: Pandas for data manipulation, Matplotlib for initial visualizations.
- **Power BI**: For creating the interactive dashboard.

