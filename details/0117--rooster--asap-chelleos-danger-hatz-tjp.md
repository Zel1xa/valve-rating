### Roster Details<br />
Team Name: Rooster<br />
Roster: asap, chelleos, dangeR, Hatz, TjP<br />
Global Rank: [117](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [5]( ../standings_asia.md)<br />
<br />
Final Rank Value:  814.7<br />
<br />
Final Rank Value (814.7) = Starting Rank Value (780.9) + Head To Head Adjustments (33.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.335[<sup>1</sup>](#table2)
- Bounty Collected: 0.295[<sup>2</sup>](#table1)
- Opponent Network: 0.047[<sup>2</sup>](#table1)
- LAN Wins: 0.064[<sup>2</sup>](#table1)

The average of these factors is 0.185<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 780.9
- 400 + ( ( 0.185 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 780.9


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
|           39 |      328 | 2024-07-23 | The Art of War     | L   | 1.000      | -            | -                | -                | -         |   -25.41 | asap, chelleos, dangeR, Hatz, TjP   |
|           38 |      333 | 2024-07-23 | The Art of War     | L   | 1.000      | -            | -                | -                | -         |   -26.72 | asap, chelleos, dangeR, Hatz, TjP   |
|           37 |      521 | 2024-07-18 | DXA                | W   | 1.000      | 0.333        | 0.002 (0.001)    | 0.228 (0.076)    | 0 (0.000) |     8.11 | asap, chelleos, dangeR, Hatz, TjP   |
|           36 |      529 | 2024-07-18 | DXA                | L   | 1.000      | -            | -                | -                | -         |   -23.93 | asap, chelleos, dangeR, Hatz, TjP   |
|           35 |      642 | 2024-07-16 | Mindfreak          | W   | 1.000      | 0.333        | 0.004 (0.001)    | 0.227 (0.076)    | 0 (0.000) |     9.34 | asap, chelleos, dangeR, Hatz, TjP   |
|           34 |      648 | 2024-07-16 | Mindfreak          | W   | 1.000      | 0.333        | 0.004 (0.001)    | 0.227 (0.076)    | 0 (0.000) |    10.07 | asap, chelleos, dangeR, Hatz, TjP   |
|           33 |     1154 | 2024-06-08 | FlyQuest           | L   | 0.843      | -            | -                | -                | -         |    -3.58 | asap, chelleos, dangeR, nettik, TjP |
|           32 |     1272 | 2024-06-07 | FlyQuest           | W   | 0.831      | 0.333        | 0.106 (0.029)    | 0.322 (0.089)    | 0 (0.000) |    23.00 | asap, chelleos, dangeR, nettik, TjP |
|           31 |     1346 | 2024-06-06 | Bad News Kangaroos | W   | 0.824      | 0.333        | 0.003 (0.001)    | 0.144 (0.039)    | 0 (0.000) |     8.61 | asap, chelleos, dangeR, nettik, TjP |
|           30 |     1765 | 2024-05-22 | Vantage            | W   | 0.724      | 0.333        | -                | 0.074 (0.018)    | 0 (0.000) |     6.09 | asap, chelleos, dangeR, nettik, TjP |
|           29 |     1770 | 2024-05-22 | Vantage            | W   | 0.724      | 0.333        | -                | 0.074 (0.018)    | 0 (0.000) |     6.40 | asap, chelleos, dangeR, nettik, TjP |
|           28 |     2043 | 2024-05-15 | Canon Event        | W   | 0.678      | -            | -                | -                | 0 (0.000) |     2.75 | asap, chelleos, dangeR, nettik, TjP |
|           27 |     2048 | 2024-05-15 | Canon Event        | W   | 0.677      | -            | -                | -                | 0 (0.000) |     2.83 | asap, chelleos, dangeR, nettik, TjP |
|           26 |     2243 | 2024-05-08 | KZG                | W   | 0.631      | 0.333        | 0.006 (0.001)    | 0.113 (0.024)    | -         |     6.00 | asap, chelleos, dangeR, nettik, TjP |
|           25 |     2246 | 2024-05-08 | KZG                | W   | 0.631      | 0.333        | 0.006 (0.001)    | 0.113 (0.024)    | -         |     6.29 | asap, chelleos, dangeR, nettik, TjP |
|           24 |     2481 | 2024-04-26 | MIBR               | L   | 0.556      | -            | -                | -                | -         |    -0.51 | asap, chelleos, dangeR, nettik, TjP |
|           23 |     2502 | 2024-04-26 | KZG                | W   | 0.551      | 0.500        | 0.006 (0.002)    | 0.113 (0.031)    | 1 (0.551) |     5.75 | asap, chelleos, dangeR, nettik, TjP |
|           22 |     2505 | 2024-04-25 | Rebels             | L   | 0.550      | -            | -                | -                | -         |    -4.44 | asap, chelleos, dangeR, nettik, TjP |
|           21 |     2642 | 2024-04-19 | Bad News Kangaroos | L   | 0.510      | -            | -                | -                | -         |    -8.54 | asap, chelleos, dangeR, nettik, TjP |
|           20 |     2685 | 2024-04-19 | FlyQuest           | L   | 0.505      | -            | -                | -                | -         |    -1.72 | asap, chelleos, dangeR, nettik, TjP |
|           19 |     2691 | 2024-04-18 | Bad News Kangaroos | W   | 0.503      | 0.143        | 0.017 (0.001)    | -                | -         |     7.41 | asap, chelleos, dangeR, nettik, TjP |
|           18 |     2769 | 2024-04-17 | Arcade             | W   | 0.491      | -            | -                | -                | -         |     4.76 | asap, chelleos, dangeR, nettik, TjP |
|           17 |     2773 | 2024-04-17 | Canon Event        | W   | 0.491      | -            | -                | -                | -         |     2.26 | asap, chelleos, dangeR, nettik, TjP |
|           16 |     2944 | 2024-04-10 | Bad News Kangaroos | L   | 0.444      | -            | -                | -                | -         |    -7.48 | asap, chelleos, dangeR, nettik, TjP |
|           15 |     2951 | 2024-04-10 | Bad News Kangaroos | W   | 0.444      | 0.333        | 0.017 (0.003)    | -                | -         |     6.66 | asap, chelleos, dangeR, nettik, TjP |
|           14 |     3190 | 2024-04-03 | RKON               | W   | 0.397      | -            | -                | -                | -         |     2.12 | asap, chelleos, dangeR, nettik, TjP |
|           13 |     3191 | 2024-04-03 | RKON               | W   | 0.397      | -            | -                | -                | -         |     2.16 | asap, chelleos, dangeR, nettik, TjP |
|           12 |     3313 | 2024-03-27 | Arcade             | W   | 0.351      | -            | -                | -                | -         |     3.68 | asap, chelleos, dangeR, nettik, TjP |
|           11 |     3318 | 2024-03-27 | Arcade             | W   | 0.351      | -            | -                | -                | -         |     3.78 | asap, chelleos, dangeR, nettik, TjP |
|           10 |     3593 | 2024-03-13 | FlyQuest           | L   | 0.258      | -            | -                | -                | -         |    -0.84 | asap, chelleos, dangeR, nettik, TjP |
|            9 |     3601 | 2024-03-13 | FlyQuest           | L   | 0.258      | -            | -                | -                | -         |    -0.85 | asap, chelleos, dangeR, nettik, TjP |
|            8 |     3770 | 2024-03-06 | Mindfreak          | W   | 0.211      | -            | -                | -                | -         |     2.26 | asap, chelleos, dangeR, nettik, TjP |
|            7 |     3776 | 2024-03-06 | Mindfreak          | W   | 0.211      | -            | -                | -                | -         |     2.29 | asap, chelleos, dangeR, nettik, TjP |
|            6 |     4038 | 2024-02-23 | FlyQuest           | L   | 0.131      | -            | -                | -                | -         |    -0.42 | asap, chelleos, dangeR, nettik, TjP |
|            5 |     4040 | 2024-02-22 | Bad News Kangaroos | W   | 0.130      | -            | -                | -                | -         |     1.96 | asap, chelleos, dangeR, nettik, TjP |
|            4 |     4058 | 2024-02-22 | FlyQuest           | L   | 0.124      | -            | -                | -                | -         |    -0.40 | asap, chelleos, dangeR, nettik, TjP |
|            3 |     4061 | 2024-02-21 | Vantage            | W   | 0.123      | -            | -                | -                | -         |     1.29 | asap, chelleos, dangeR, nettik, TjP |
|            2 |     4089 | 2024-02-21 | DXA                | W   | 0.118      | -            | -                | -                | -         |     1.38 | asap, chelleos, dangeR, nettik, TjP |
|            1 |     4093 | 2024-02-21 | DXA                | W   | 0.118      | -            | -                | -                | -         |     1.40 | asap, chelleos, dangeR, nettik, TjP |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,379.31)
- Divide that value by the 5th highest value among all rosters ($326,952.13)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-08 |      0.843 | $2,000.00      | $1,686.67       |
| 2024-04-28 |      0.564 | $3,000.00      | $1,692.64       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
