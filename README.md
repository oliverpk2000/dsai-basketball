# dsai-basketball

## description
dsai stands for data science and artificial intelligence

School project where we will analyse player data and (later) try to accurately predict what stats you need to become an MVP

## dataset features

the observations are ordered by NBA season, so players that played in more than one season will show up more times

### rk
row number / id

### name
full player name, (first + last name)

### Pos
player position

### Age
player age

### Tm
which NBA team the player played for

Edge case: if the player was traded during the season, there will be an observation per team that he played for, along with a total observation that averages out his statistics. This total observation marked with TOT in the team column.

### G, GS
- G: games played
- GS: games started

### MPG
minutes per game

### FG, FGA, FG%, eFG%
- FG: field goals made per game
- FGA: field goals attempted per game
- FG%: FG/FGA
- eFG%: FG% but weighted to account for 3-pointers being more efficient than 2-pointers

null if none attempted, 0.0 if no FG made

### 3P, 3PA, 3P%
- 3P: 3-pointers made per game
- 3PA: 3-pointers attempted per game
- 3P%: 3P/3PA

null if none attempted, 0.0 if no 3P made

### 2P, 2PA, 2P%
- 2P: 2-pointers made per game
- 2PA: 2-pointers attempted per game
- 2P%: 2P/2PA

null if none attempted, 0.0 if no 2P made

### FT, FTA, FT%
- FT: free throws made per game
- FTA: free throws attempted per game
- FT%: FT/FTA 

null if none attempted, 0.0 if no FT made

### ORB, DRB, TRB
- ORB: offensive rebounds per game
- DRB: defensive rebounds per game
- TRB: total rebounds per game

### AST
assists per game

### STL
steals per game

### BLK
blocks per game

### TOV
turnovers per game

### PF
personal fouls committed per game

### PTS
points per game

### Season
NBA season in which the player recorded these statistics

### MVP
true if player was voted MVP that season