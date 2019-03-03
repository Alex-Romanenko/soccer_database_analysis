# soccer_database_analysis
At the beginning I have no idea what soccer is and what its system is. This is my attempt to understand the game.
<br>
## Introduction

The database contents:

- +25,000 matches
- +10,000 players
- 11 European Countries with their lead championship
- Seasons 2008 to 2016
- Players and Teams' attributes* sourced from EA Sports' FIFA video game series, including the weekly updates
- Team line up with squad formation (X, Y coordinates)
- Betting odds from up to 10 providers
- Detailed match events (goal types, possession, corner, cross, fouls, cards etc...) for +10,000 matches

After review database description in <a href = https://www.kaggle.com/hugomathien/soccer/home> Kaggle </a> we decided to download it and get closer look with <a href = https://sqlitebrowser.org/> DB browser </a>.
Then the following questions were raised:
> 1. Is it more likely for a team to win in the home matches than in a way? 
> 2. If we form a Combined Overall Rating(Team_COR) of a team as a sum of Overall Ratings of each its players is it more likely for a team with a bigger COR to win a match?
> 3. How the match results correlate with COR?

##Technologies
To find the answers we use following techs and lybrories:
- Python 3
- Pandas
- NumPy
- Matplotlib
- Sqlite3
- Seaborn
- Jupyter Notebook
