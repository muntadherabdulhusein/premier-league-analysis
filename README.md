# Premier League 2020/21 – Player Data Analysis

An exploratory analysis of every player in the 2020/21 English Premier League season with Python: goals, assists, penalties, ages, nationalities and discipline.

## Questions I looked at

- How many goals were scored, and how many came from penalties?
- Which clubs and players scored and assisted the most?
- How old are the squads, and which clubs give young players a chance?
- Where do the players come from?
- Who got the most yellow cards?

## Some results

- **986 goals** in the dataset, **102 of them from penalties** (out of 125 penalties taken, so about 82% scored)
- Players from **59 nationalities**
- **Top scorers:** Harry Kane (23), Mohamed Salah (22), Bruno Fernandes (18)
- **Top assists:** Harry Kane (14), Kevin De Bruyne (12), Bruno Fernandes (12)
- Harry Kane was also the best in goals per match (0.66)

## What I did

- Checked the data for missing values (none)
- Added new columns like minutes per match and goals per match
- Grouped the players by age (under 20, 20–25, 25–30, over 30) and by club
- Made bar charts, pie charts and box plots with Matplotlib and Seaborn

## Tools

Python, Pandas, NumPy, Matplotlib, Seaborn

## File

- `English premier league data analysis .ipynb`: the full analysis with all charts
