# 🏏 IPL 2022 Data Visualization

A data analysis and visualization project on the **Indian Premier League (IPL) 2022** season using Python.

---

## 📁 Project Structure

```
numpy practice/
│
├── data_visualization.ipynb   # Main Jupyter Notebook
├── IPL.csv                    # Dataset (IPL 2022 match data)
└── README.md                  # Project description
```

---

## 📊 Dataset Overview

**File:** `IPL.csv`  
**Total Matches:** 74 (Group stage + Playoffs)  
**Season:** IPL 2022

| Column | Description |
|--------|-------------|
| `match_id` | Unique match number |
| `date` | Match date |
| `venue` | Stadium name and city |
| `team1` / `team2` | Competing teams |
| `stage` | Group or Playoff |
| `toss_winner` | Team that won the toss |
| `toss_decision` | Bat or Field |
| `first_ings_score` | 1st innings total runs |
| `first_ings_wkts` | 1st innings wickets lost |
| `second_ings_score` | 2nd innings total runs |
| `second_ings_wkts` | 2nd innings wickets lost |
| `match_winner` | Winning team |
| `won_by` | Runs or Wickets |
| `margin` | Winning margin |
| `player_of_the_match` | Best performer |
| `top_scorer` | Highest run-scorer in match |
| `highscore` | Top scorer's runs |
| `best_bowling` | Best bowler in match |
| `best_bowling_figure` | Wickets--Runs (e.g. 3--20) |

---

## 📈 Visualizations Included

1. **Most Player of the Match Awards** — Top 5 players with most POTM awards
2. **Most Won Matches** — Teams with highest wins in IPL 2022
3. **Most Won Toss** — Teams that won toss most often
4. **Toss vs Match Win %** — Does winning toss help win the match?
5. **Top Run Scorers** — Players with highest individual scores
6. **Best Bowling Figures** — Top 5 bowlers by total wickets

---

## 🛠️ Libraries Used

```python
import numpy as np
import pandas as pd
import seaborn as sns
import matplotlib.pyplot as plt
import warnings
```

---

## ▶️ How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/ipl-2022-visualization.git
   ```

2. Open the notebook:
   ```bash
   jupyter notebook data_visualization.ipynb
   ```

3. Make sure `IPL.csv` is in the **same folder** as the notebook.

4. Run all cells: **Kernel → Restart & Run All**

---

## 🔍 Key Insights

- Toss win does **not guarantee** match win — only ~50% correlation found
- **Jos Buttler** was the most dominant batter of IPL 2022
- **Yuzvendra Chahal** was the standout bowler of the season
- **Gujarat Titans** won the most matches in their debut season

---

## 👤 Author

**Hassan**  
BS Computer Science — 6th Semester  
Data Analysis Project | IPL 2022

---

## 📌 Note

> Dataset contains IPL 2022 season data only (March–May 2022).  
> All 74 matches included from group stage to final.
