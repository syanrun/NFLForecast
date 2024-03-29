Train data based on game results (score differential) and roster ratings from the 2020-2021 NFL Season and 2021-2022 NFL season to create a model to predict game results.

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

The model used was a bagged kernelized SVM, which ended up having accurate predictions on average 64-66% of the time.

After that, I reran the machine learning analysis using data from Madden's NFL video games for more comprehensive and empirical player ratings, which yielded an even higher accuracy of 68.5%.
