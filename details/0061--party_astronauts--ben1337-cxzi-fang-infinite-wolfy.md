### Roster Details<br />
Team Name: Party Astronauts<br />
Roster: ben1337, cxzi, FaNg, Infinite, WolfY<br />
Global Rank: [61](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [17]( ../standings_americas.md)<br />
<br />
Final Rank Value:  993.9<br />
<br />
Final Rank Value (993.9) = Starting Rank Value (926.3) + Head To Head Adjustments (67.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.419[<sup>1</sup>](#table2)
- Bounty Collected: 0.364[<sup>2</sup>](#table1)
- Opponent Network: 0.185[<sup>2</sup>](#table1)
- LAN Wins: 0.061[<sup>2</sup>](#table1)

The average of these factors is 0.257<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 926.3
- 400 + ( ( 0.257 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 926.3


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent      | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                               |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           72 |      158 | 2024-07-30 | NRG           | W   | 1.000      | 0.477        | 0.020 (0.010)    | 0.521 (0.248)    | 0 (0.000) |    15.48 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           71 |      162 | 2024-07-30 | NRG           | W   | 1.000      | 0.477        | 0.020 (0.010)    | 0.521 (0.248)    | 0 (0.000) |    16.91 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           70 |      389 | 2024-07-23 | FLUFFY AIMERS | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.21 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           69 |      391 | 2024-07-23 | FLUFFY AIMERS | L   | 1.000      | -            | -                | -                | -         |   -25.85 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           68 |      477 | 2024-07-20 | Wildcard      | L   | 1.000      | -            | -                | -                | -         |   -15.65 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           67 |      613 | 2024-07-17 | Take Flyte    | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.28 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           66 |      617 | 2024-07-17 | Take Flyte    | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.56 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           65 |      679 | 2024-07-16 | Limitless     | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.10 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           64 |      685 | 2024-07-16 | Limitless     | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.45 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           63 |     1021 | 2024-06-15 | Falcons       | L   | 0.865      | -            | -                | -                | -         |    -2.21 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           62 |     1065 | 2024-06-14 | The MongolZ   | L   | 0.859      | -            | -                | -                | -         |    -0.15 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           61 |     1176 | 2024-06-09 | Legacy        | L   | 0.830      | -            | -                | -                | -         |   -11.84 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           60 |     1244 | 2024-06-08 | Wildcard      | W   | 0.822      | 0.384        | 0.055 (0.017)    | 0.503 (0.159)    | 0 (0.000) |    12.46 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           59 |     1262 | 2024-06-08 | NRG           | L   | 0.821      | -            | -                | -                | -         |   -15.74 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           58 |     1294 | 2024-06-07 | Nouns         | L   | 0.817      | -            | -                | -                | -         |   -13.42 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           57 |     1302 | 2024-06-07 | Legacy        | W   | 0.816      | 0.143        | 0.122 (0.014)    | -                | 0 (0.000) |    13.90 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           56 |     1308 | 2024-06-07 | NRG           | W   | 0.815      | 0.384        | -                | 0.521 (0.163)    | -         |    10.04 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           55 |     1321 | 2024-06-07 | Nouns         | W   | 0.815      | -            | -                | -                | -         |    13.29 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           54 |     1352 | 2024-06-06 | NRG           | W   | 0.810      | 0.477        | 0.020 (0.008)    | 0.521 (0.201)    | -         |    11.18 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           53 |     1371 | 2024-06-06 | E-Xolos LAZER | W   | 0.808      | -            | -                | -                | -         |     6.73 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           52 |     1422 | 2024-06-05 | Wildcard      | L   | 0.803      | -            | -                | -                | -         |   -12.17 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           51 |     1473 | 2024-06-04 | Elevate       | W   | 0.797      | 0.477        | 0.027 (0.010)    | 0.505 (0.192)    | -         |    13.89 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           50 |     1782 | 2024-05-22 | Nouns         | L   | 0.710      | -            | -                | -                | -         |   -11.17 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           49 |     1791 | 2024-05-22 | M80           | W   | 0.710      | 0.477        | 0.188 (0.064)    | 0.587 (0.199)    | -         |    18.93 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           48 |     1795 | 2024-05-22 | M80           | L   | 0.710      | -            | -                | -                | -         |    -3.28 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           47 |     1829 | 2024-05-21 | Limitless     | W   | 0.704      | -            | -                | -                | -         |     3.21 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           46 |     1832 | 2024-05-21 | Limitless     | W   | 0.704      | -            | -                | -                | -         |     3.31 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           45 |     1865 | 2024-05-20 | Akimbo        | W   | 0.697      | -            | -                | -                | -         |     6.11 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           44 |     1934 | 2024-05-18 | NRG           | L   | 0.682      | -            | -                | -                | -         |   -10.76 | ben1337, chop, cxzi, Infinite, WolfY |
|           43 |     1967 | 2024-05-17 | Legacy        | W   | 0.676      | 0.303        | 0.122 (0.025)    | -                | -         |    13.20 | ben1337, chop, cxzi, Infinite, WolfY |
|           42 |     1995 | 2024-05-16 | FLUFFY AIMERS | W   | 0.670      | -            | -                | -                | -         |     5.37 | ben1337, chop, cxzi, Infinite, WolfY |
|           41 |     1998 | 2024-05-16 | FLUFFY AIMERS | W   | 0.670      | -            | -                | -                | -         |     5.62 | ben1337, chop, cxzi, Infinite, WolfY |
|           40 |     2088 | 2024-05-14 | Mythic        | W   | 0.657      | -            | -                | -                | -         |     6.99 | ben1337, chop, cxzi, RUSH, WolfY     |
|           39 |     2095 | 2024-05-14 | Mythic        | L   | 0.657      | -            | -                | -                | -         |   -14.07 | ben1337, chop, cxzi, RUSH, WolfY     |
|           38 |     2188 | 2024-05-11 | BOSS          | L   | 0.636      | -            | -                | -                | -         |   -13.57 | ben1337, chop, cxzi, RUSH, WolfY     |
|           37 |     2192 | 2024-05-11 | Perseverance  | L   | 0.635      | -            | -                | -                | -         |   -15.48 | ben1337, chop, cxzi, RUSH, WolfY     |
|           36 |     2251 | 2024-05-08 | LAG           | W   | 0.617      | -            | -                | -                | -         |     6.99 | ben1337, chop, cxzi, RUSH, WolfY     |
|           35 |     2256 | 2024-05-08 | LAG           | W   | 0.617      | -            | -                | -                | -         |     7.36 | ben1337, chop, cxzi, RUSH, WolfY     |
|           34 |     2276 | 2024-05-07 | Elevate       | L   | 0.611      | -            | -                | -                | -         |    -8.95 | ben1337, chop, cxzi, RUSH, WolfY     |
|           33 |     2277 | 2024-05-07 | Elevate       | W   | 0.610      | 0.477        | 0.027 (0.008)    | 0.505 (0.147)    | -         |    10.53 | ben1337, chop, cxzi, RUSH, WolfY     |
|           32 |     2295 | 2024-05-06 | NRG           | L   | 0.604      | -            | -                | -                | -         |   -11.77 | ben1337, chop, cxzi, RUSH, WolfY     |
|           31 |     2296 | 2024-05-06 | NRG           | W   | 0.603      | 0.477        | -                | 0.521 (0.150)    | -         |     7.32 | ben1337, chop, cxzi, RUSH, WolfY     |
|           30 |     2367 | 2024-05-02 | Wildcard      | L   | 0.577      | -            | -                | -                | -         |   -10.05 | ben1337, chop, cxzi, RUSH, WolfY     |
|           29 |     2368 | 2024-05-02 | Wildcard      | W   | 0.577      | 0.477        | 0.055 (0.015)    | 0.503 (0.138)    | -         |     8.27 | ben1337, chop, cxzi, RUSH, WolfY     |
|           28 |     2504 | 2024-04-27 | Aurora        | L   | 0.539      | -            | -                | -                | -         |    -0.40 | ben1337, chop, cxzi, RUSH, WolfY     |
|           27 |     2506 | 2024-04-26 | sunday school | W   | 0.537      | -            | -                | -                | 1 (0.537) |     2.53 | ben1337, chop, cxzi, RUSH, WolfY     |
|           26 |     2533 | 2024-04-25 | Aurora        | L   | 0.530      | -            | -                | -                | -         |    -0.36 | ben1337, chop, cxzi, RUSH, WolfY     |
|           25 |     2973 | 2024-04-09 | Take Flyte    | W   | 0.424      | -            | -                | -                | -         |     2.74 | ben1337, chop, cxzi, RUSH, WolfY     |
|           24 |     2979 | 2024-04-09 | Take Flyte    | W   | 0.423      | -            | -                | -                | -         |     2.81 | ben1337, chop, cxzi, RUSH, WolfY     |
|           23 |     3103 | 2024-04-04 | MIGHT         | W   | 0.390      | -            | -                | -                | -         |     1.17 | ben1337, chop, cxzi, RUSH, WolfY     |
|           22 |     3110 | 2024-04-04 | MIGHT         | W   | 0.390      | -            | -                | -                | -         |     1.18 | ben1337, chop, cxzi, RUSH, WolfY     |
|           21 |     3200 | 2024-04-02 | Perseverance  | W   | 0.377      | -            | -                | -                | -         |     2.86 | ben1337, chop, CLASIA, cxzi, WolfY   |
|           20 |     3203 | 2024-04-02 | Nouns         | L   | 0.376      | -            | -                | -                | -         |    -6.18 | ben1337, chop, CLASIA, cxzi, WolfY   |
|           19 |     3281 | 2024-03-27 | Carpe Diem    | W   | 0.337      | -            | -                | -                | -         |     2.04 | ben1337, chop, cxzi, RUSH, WolfY     |
|           18 |     3284 | 2024-03-27 | Carpe Diem    | W   | 0.337      | -            | -                | -                | -         |     2.08 | ben1337, chop, cxzi, RUSH, WolfY     |
|           17 |     3326 | 2024-03-26 | Nouns         | L   | 0.331      | -            | -                | -                | -         |    -5.51 | ben1337, chop, cxzi, RUSH, WolfY     |
|           16 |     3331 | 2024-03-26 | Nouns         | L   | 0.330      | -            | -                | -                | -         |    -5.67 | ben1337, chop, cxzi, RUSH, WolfY     |
|           15 |     3409 | 2024-03-20 | BOSS          | W   | 0.291      | -            | -                | -                | -         |     2.95 | ben1337, chop, cxzi, RUSH, WolfY     |
|           14 |     3411 | 2024-03-20 | BOSS          | W   | 0.290      | -            | -                | -                | -         |     3.01 | ben1337, chop, cxzi, RUSH, WolfY     |
|           13 |     3430 | 2024-03-19 | Perseverance  | W   | 0.284      | -            | -                | -                | -         |     2.16 | ben1337, chop, cxzi, RUSH, WolfY     |
|           12 |     3432 | 2024-03-19 | Perseverance  | W   | 0.284      | -            | -                | -                | -         |     2.20 | ben1337, chop, cxzi, RUSH, WolfY     |
|           11 |     3560 | 2024-03-13 | Carpe Diem    | W   | 0.243      | -            | -                | -                | -         |     1.53 | ben1337, chop, cxzi, RUSH, WolfY     |
|           10 |     3601 | 2024-03-12 | Elevate       | W   | 0.237      | -            | -                | -                | -         |     4.41 | ben1337, chop, cxzi, RUSH, WolfY     |
|            9 |     3981 | 2024-02-24 | Wildcard      | L   | 0.123      | -            | -                | -                | -         |    -2.05 | ben1337, chop, cxzi, Walco, WolfY    |
|            8 |     3987 | 2024-02-24 | ex-CatEvil    | W   | 0.123      | -            | -                | -                | -         |     0.19 | ben1337, chop, cxzi, Walco, WolfY    |
|            7 |     4023 | 2024-02-22 | Liquid        | L   | 0.110      | -            | -                | -                | -         |    -0.08 | ben1337, chop, cxzi, Walco, WolfY    |
|            6 |     4024 | 2024-02-22 | NRG           | W   | 0.110      | -            | -                | -                | -         |     1.37 | ben1337, chop, cxzi, Walco, WolfY    |
|            5 |     4030 | 2024-02-22 | Take Flyte    | W   | 0.110      | -            | -                | -                | -         |     0.79 | ben1337, chop, cxzi, Walco, WolfY    |
|            4 |     4077 | 2024-02-20 | NRG           | W   | 0.097      | -            | -                | -                | -         |     1.22 | ben1337, chop, cxzi, Walco, WolfY    |
|            3 |     4079 | 2024-02-20 | Mythic        | W   | 0.096      | -            | -                | -                | -         |     0.98 | ben1337, chop, cxzi, Walco, WolfY    |
|            2 |     4102 | 2024-02-19 | NRG           | L   | 0.091      | -            | -                | -                | -         |    -1.73 | ben1337, chop, cxzi, Walco, WolfY    |
|            1 |     4105 | 2024-02-19 | Akimbo        | W   | 0.089      | -            | -                | -                | -         |     0.79 | ben1337, chop, cxzi, Walco, WolfY    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($13,344.05)
- Divide that value by the 5th highest value among all rosters ($324,344.55)
- The final value (0.04) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.874 | $2,000.00      | $1,747.45       |
| 2024-06-09 |      0.830 | $5,000.00      | $4,150.58       |
| 2024-06-09 |      0.830 | $7,000.00      | $5,808.87       |
| 2024-04-28 |      0.546 | $3,000.00      | $1,637.15       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
