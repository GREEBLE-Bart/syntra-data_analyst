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

ACTIONS:
1. Clean NBA_team_payroll.xlsx (TO DO)
    - Merge into 1 file
    - Add Team_ID
    - Add Team_Abbreviation
    - Export to "team_payroll_2010-2020.xlsx"
2. Clean NBA_player_salary.xlsx (TO DO)
    - Merge into 1 file
    - Add Player_ID
    - Add Team_Abbreviation
    - Export to "player_salaris_2010-2020.xlsx"
