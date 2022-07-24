Train data based on game results (score differential) and roster ratings from the 2020-2021 NFL Season and 2021-2022 NFL season to create a model to predict game results in the 2022-2023 NFL season

Roster Rating Source (Pro Football Focus):
7/1/2022

2020 Roster Ratings:
https://www.pff.com/news/nfl-roster-rankings-all-32-teams-ravens-first-jaguars-last\

2021 Roster Ratings:
https://www.pff.com/news/nfl-roster-rankings-for-all-32-teams-for-2021-strengths-weaknesses-and-x-factors-for-every-teams-starting-lineup\

2022 Roster Ratings:
https://www.pff.com/news/nfl-roster-rankings-all-32-teams-2022-strengths-weaknesses-x-factors-every-starting-lineup}

Game Schedule Source (Pro Football Reference):
7/13/2022 (Trimmed in excel)

2020:
https://www.pro-football-reference.com/years/2020/games.htm

2021:
https://www.pro-football-reference.com/years/2021/games.htm

2022:
https://www.pro-football-reference.com/years/2022/games.htm

Roster Rating Source (Madden):
7/23/2022

2020 (Madden 2021):
https://maddenratings.weebly.com/madden-nfl-21.html

2021 (Madden 2022):
https://maddenratings.weebly.com/madden-nfl-22.html

2022 (Madden 2023):
https://www.maddenratings.com/

The first model used was a bagged kernelized SVM, which ended up having accurate predictions on average 64-66% of the time - not bad, this actually improves upon FiveThirtyEight's 61% accuracy in the 2021 season (https://nflpickwatch.com/profile/nfl/157).

After that, I reran the machine learning analysis using data from Madden's NFL video games for more comprehensive and empirical player ratings, which yielded an even higher accuracy of 68.5%.

Predictions for the 2022 Season:
https://docs.google.com/spreadsheets/d/1aRLdwXeRXysy-ymcKTt-cJpC9Ny-r5m6es5Bt-mOXSs/edit?usp=sharing

Check out how accurate my predictions are live!:
https://nflpickwatch.com/profile/nfl/syanrun
