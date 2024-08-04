### Roster Details<br />
Team Name: Rooster<br />
Roster: asap, chelleos, dangeR, Hatz, TjP<br />
Global Rank: [121](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [7]( ../standings_asia.md)<br />
<br />
Final Rank Value:  812.2<br />
<br />
Final Rank Value (812.2) = Starting Rank Value (778.8) + Head To Head Adjustments (33.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.334[<sup>1</sup>](#table2)
- Bounty Collected: 0.297[<sup>2</sup>](#table1)
- Opponent Network: 0.049[<sup>2</sup>](#table1)
- LAN Wins: 0.061[<sup>2</sup>](#table1)

The average of these factors is 0.185<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 778.8
- 400 + ( ( 0.185 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 778.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent           | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                              |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           37 |      441 | 2024-07-23 | The Art of War     | L   | 1.000      | -            | -                | -                | -         |   -25.40 | asap, chelleos, dangeR, Hatz, TjP   |
|           36 |      445 | 2024-07-23 | The Art of War     | L   | 1.000      | -            | -                | -                | -         |   -26.71 | asap, chelleos, dangeR, Hatz, TjP   |
|           35 |      625 | 2024-07-18 | DXA                | W   | 1.000      | 0.333        | 0.002 (0.001)    | 0.226 (0.075)    | 0 (0.000) |     8.61 | asap, chelleos, dangeR, Hatz, TjP   |
|           34 |      630 | 2024-07-18 | DXA                | L   | 1.000      | -            | -                | -                | -         |   -23.42 | asap, chelleos, dangeR, Hatz, TjP   |
|           33 |      743 | 2024-07-16 | Mindfreak          | W   | 1.000      | 0.333        | 0.004 (0.001)    | 0.227 (0.076)    | 0 (0.000) |     9.69 | asap, chelleos, dangeR, Hatz, TjP   |
|           32 |      745 | 2024-07-16 | Mindfreak          | W   | 1.000      | 0.333        | 0.004 (0.001)    | 0.227 (0.076)    | 0 (0.000) |    10.47 | asap, chelleos, dangeR, Hatz, TjP   |
|           31 |     1258 | 2024-06-08 | FlyQuest           | L   | 0.824      | -            | -                | -                | -         |    -3.64 | asap, chelleos, dangeR, nettik, TjP |
|           30 |     1368 | 2024-06-07 | FlyQuest           | W   | 0.811      | 0.333        | 0.104 (0.028)    | 0.294 (0.079)    | 0 (0.000) |    22.34 | asap, chelleos, dangeR, nettik, TjP |
|           29 |     1439 | 2024-06-06 | Bad News Kangaroos | W   | 0.805      | 0.333        | 0.017 (0.004)    | 0.226 (0.061)    | 0 (0.000) |    12.16 | asap, chelleos, dangeR, nettik, TjP |
|           28 |     1843 | 2024-05-22 | Vantage            | W   | 0.705      | 0.333        | -                | 0.070 (0.016)    | 0 (0.000) |     6.07 | asap, chelleos, dangeR, nettik, TjP |
|           27 |     1848 | 2024-05-22 | Vantage            | W   | 0.705      | -            | -                | -                | 0 (0.000) |     6.38 | asap, chelleos, dangeR, nettik, TjP |
|           26 |     2101 | 2024-05-15 | Canon Event        | W   | 0.658      | -            | -                | -                | 0 (0.000) |     2.78 | asap, chelleos, dangeR, nettik, TjP |
|           25 |     2106 | 2024-05-15 | Canon Event        | W   | 0.658      | -            | -                | -                | 0 (0.000) |     2.86 | asap, chelleos, dangeR, nettik, TjP |
|           24 |     2294 | 2024-05-08 | KZG                | W   | 0.612      | 0.333        | 0.005 (0.001)    | 0.112 (0.023)    | -         |     5.95 | asap, chelleos, dangeR, nettik, TjP |
|           23 |     2297 | 2024-05-08 | KZG                | W   | 0.612      | 0.333        | 0.005 (0.001)    | 0.112 (0.023)    | -         |     6.23 | asap, chelleos, dangeR, nettik, TjP |
|           22 |     2528 | 2024-04-26 | MIBR               | L   | 0.537      | -            | -                | -                | -         |    -0.46 | asap, chelleos, dangeR, nettik, TjP |
|           21 |     2550 | 2024-04-26 | KZG                | W   | 0.532      | 0.500        | 0.005 (0.001)    | 0.112 (0.030)    | 1 (0.532) |     5.66 | asap, chelleos, dangeR, nettik, TjP |
|           20 |     2553 | 2024-04-25 | Rebels             | L   | 0.530      | -            | -                | -                | -         |    -4.29 | asap, chelleos, dangeR, nettik, TjP |
|           19 |     2684 | 2024-04-19 | Bad News Kangaroos | L   | 0.491      | -            | -                | -                | -         |    -7.92 | asap, chelleos, dangeR, nettik, TjP |
|           18 |     2726 | 2024-04-19 | FlyQuest           | L   | 0.485      | -            | -                | -                | -         |    -1.73 | asap, chelleos, dangeR, nettik, TjP |
|           17 |     2732 | 2024-04-18 | Bad News Kangaroos | W   | 0.484      | 0.143        | 0.017 (0.001)    | -                | -         |     7.44 | asap, chelleos, dangeR, nettik, TjP |
|           16 |     2808 | 2024-04-17 | Arcade             | W   | 0.472      | -            | -                | -                | -         |     4.81 | asap, chelleos, dangeR, nettik, TjP |
|           15 |     2812 | 2024-04-17 | Canon Event        | W   | 0.472      | -            | -                | -                | -         |     2.27 | asap, chelleos, dangeR, nettik, TjP |
|           14 |     2981 | 2024-04-10 | Bad News Kangaroos | L   | 0.425      | -            | -                | -                | -         |    -6.86 | asap, chelleos, dangeR, nettik, TjP |
|           13 |     2988 | 2024-04-10 | Bad News Kangaroos | W   | 0.425      | 0.333        | 0.017 (0.002)    | 0.226 (0.032)    | -         |     6.67 | asap, chelleos, dangeR, nettik, TjP |
|           12 |     3341 | 2024-03-27 | Arcade             | W   | 0.332      | -            | -                | -                | -         |     3.61 | asap, chelleos, dangeR, nettik, TjP |
|           11 |     3346 | 2024-03-27 | Arcade             | W   | 0.332      | -            | -                | -                | -         |     3.70 | asap, chelleos, dangeR, nettik, TjP |
|           10 |     3613 | 2024-03-13 | FlyQuest           | L   | 0.239      | -            | -                | -                | -         |    -0.83 | asap, chelleos, dangeR, nettik, TjP |
|            9 |     3621 | 2024-03-13 | FlyQuest           | L   | 0.239      | -            | -                | -                | -         |    -0.83 | asap, chelleos, dangeR, nettik, TjP |
|            8 |     3788 | 2024-03-06 | Mindfreak          | W   | 0.192      | -            | -                | -                | -         |     2.06 | asap, chelleos, dangeR, nettik, TjP |
|            7 |     3794 | 2024-03-06 | Mindfreak          | W   | 0.192      | -            | -                | -                | -         |     2.09 | asap, chelleos, dangeR, nettik, TjP |
|            6 |     4043 | 2024-02-23 | FlyQuest           | L   | 0.112      | -            | -                | -                | -         |    -0.38 | asap, chelleos, dangeR, nettik, TjP |
|            5 |     4045 | 2024-02-22 | Bad News Kangaroos | W   | 0.111      | -            | -                | -                | -         |     1.01 | asap, chelleos, dangeR, nettik, TjP |
|            4 |     4062 | 2024-02-22 | FlyQuest           | L   | 0.105      | -            | -                | -                | -         |    -0.36 | asap, chelleos, dangeR, nettik, TjP |
|            3 |     4065 | 2024-02-21 | Vantage            | W   | 0.104      | -            | -                | -                | -         |     1.08 | asap, chelleos, dangeR, nettik, TjP |
|            2 |     4092 | 2024-02-21 | DXA                | W   | 0.099      | -            | -                | -                | -         |     1.19 | asap, chelleos, dangeR, nettik, TjP |
|            1 |     4096 | 2024-02-21 | DXA                | W   | 0.099      | -            | -                | -                | -         |     1.20 | asap, chelleos, dangeR, nettik, TjP |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,283.01)
- Divide that value by the 5th highest value among all rosters ($324,118.06)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-08 |      0.824 | $2,000.00      | $1,648.15       |
| 2024-04-28 |      0.545 | $3,000.00      | $1,634.86       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
