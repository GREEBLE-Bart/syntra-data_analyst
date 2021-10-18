# Details betreffende eindwerk opdracht Syntra Data Analist opleiding


Datasets used:
  1. kaggle.com : NBA games data -> url: https://www.kaggle.com/nathanlauga/nba-game
      - 5 files stored in zip archive :
          1) games.csv : all games from 2004 season to last update with the date, teams and some details like number of points, etc.
          2) games_details.csv : details of games dataset, all statistics of players for a given game
          3) players.csv : players details (name)
          4) ranking.csv : ranking of NBA given a day (split into west and east on CONFERENCE column
          5) teams.csv : all teams of NBA
  2. Budget & Salary information collected from https://hoopshype.com/salaries/
      - 2 files created :
          1) NBA_team__payroll.xlsx : NBA team payrolls 2010 - 2020 (per team)
             - 1 xlsx file with 11 tabs (1 per year)
          3) NBA_player_salary.xlsx : NBA player salries 2010 - 2020 (individual players)
             - 1 xlsx files with 11 tabs (1 per year)
             
Questions to be analyzed :
- For seasons 2010 to 2020:
  - Evolution of team budgets
    - team with biggest evolution (increase/decrease)
  - Evolution of player salaries
    - player with biggest evolation (increase/decrease)
  - Most profitable (top 5) and least profitable (bottom 5) team
    - budget vs. points made
  - Most profitable player (top 10) and least profitable (bottom 10) player
    - minutes played vs. salary
    - points made vs. salary
  - Impact field goals/3 pointers/ free throw on total points scored (average)
  - Most effective player
    - %FG vs total FG made
    - %3p vs total 3p made
    - %FT vs total FT made
    - overall (FG/3p/FT)
    
