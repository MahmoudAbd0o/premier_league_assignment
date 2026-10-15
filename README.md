# Premier League Data Visualization Practice ⚽

A complete solution for 50 data-visualization exercises using the Premier League dataset (200 records: 20 teams × 10 seasons, 2015-16 to 2024-25).

## Contents

- `premier_league_assignment.ipynb` — full notebook: code + 50 charts + observations
- `premier_league_practice_dataset.csv` — dataset used
- `requirements.txt` — dependencies

## Topics Covered

- Line charts (Q1–Q7): team trends, season averages
- Bar charts (Q8–Q16): top/bottom teams, goals, possession, clean sheets
- Scatter plots (Q17–Q24): shots vs goals, possession vs points, correlations
- Histograms (Q25–Q31): distributions of points, goals, cards
- Countplots (Q32–Q38): performance levels, appearances
- Boxplots (Q39–Q46): distributions across seasons and levels
- Pie charts (Q47–Q49): W/D/L shares, level shares
- Bonus (Q50): Goal Difference (`Goals_For - Goals_Against`), top 10 teams 2024-25

## How to Run

Make sure Python 3 is installed, then:

```bash
pip install -r requirements.txt
jupyter notebook premier_league_assignment.ipynb
```

Or open the `.ipynb` directly on GitHub — charts render inline.

## Dataset Columns

`Season, Team, Matches, Wins, Draws, Losses, Goals_For, Goals_Against, Points, Possession_Percent, Shots_Per_Match, Avg_Attendance_Thousands, Clean_Sheets, Yellow_Cards, Red_Cards, Corners_Per_Match, Pass_Accuracy_Percent, Performance_Level`

## Author

Mahmoud Abdo
