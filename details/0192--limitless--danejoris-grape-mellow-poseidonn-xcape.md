### Roster Details<br />
Team Name: Limitless<br />
Roster: Danejoris, grape, Mellow, PoseidoNN, xCAPE<br />
Global Rank: [192](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [53]( ../standings_americas.md)<br />
<br />
Final Rank Value:  582.0<br />
<br />
Final Rank Value (582.0) = Starting Rank Value (656.7) + Head To Head Adjustments (-74.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.251[<sup>1</sup>](#table2)
- Bounty Collected: 0.232[<sup>2</sup>](#table1)
- Opponent Network: 0.018[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.125<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 656.7
- 400 + ( ( 0.125 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 656.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent         | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                      |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           40 |     1119 | 2024-06-13 | Nouns            | L   | 0.847      | -            | -                | -                | -         |    -2.61 | Danejoris, grape, Mellow, PoseidoNN, xCAPE  |
|           39 |     1148 | 2024-06-12 | Detonate         | L   | 0.842      | -            | -                | -                | -         |   -15.81 | Danejoris, DooM, grape, PoseidoNN, xCAPE    |
|           38 |     1150 | 2024-06-12 | E-Xolos LAZER    | L   | 0.841      | -            | -                | -                | -         |    -7.28 | Coastal, Danejoris, grape, PoseidoNN, xCAPE |
|           37 |     1177 | 2024-06-11 | Perseverance     | W   | 0.833      | 0.371        | 0.000 (0.000)    | 0.063 (0.019)    | 0 (0.000) |    10.69 | Danejoris, grape, Mellow, PoseidoNN, xCAPE  |
|           36 |     1195 | 2024-06-10 | Final Form       | L   | 0.827      | -            | -                | -                | -         |   -14.95 | Danejoris, grape, Mellow, PoseidoNN, xCAPE  |
|           35 |     1346 | 2024-06-07 | Vibe             | W   | 0.808      | 0.371        | 0.000 (0.000)    | 0.070 (0.021)    | 0 (0.000) |     6.33 | Danejoris, grape, Mellow, PoseidoNN, xCAPE  |
|           34 |     1413 | 2024-06-06 | Homyno           | L   | 0.801      | -            | -                | -                | -         |    -9.11 | Danejoris, grape, Mellow, PoseidoNN, xCAPE  |
|           33 |     1573 | 2024-06-03 | Asian Kings      | W   | 0.779      | 0.371        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     5.70 | Danejoris, grape, Mellow, PoseidoNN, xCAPE  |
|           32 |     1836 | 2024-05-22 | LAG              | L   | 0.702      | -            | -                | -                | -         |    -5.56 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|           31 |     1839 | 2024-05-22 | LAG              | L   | 0.702      | -            | -                | -                | -         |    -5.83 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|           30 |     1879 | 2024-05-21 | Party Astronauts | L   | 0.696      | -            | -                | -                | -         |    -3.20 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|           29 |     1882 | 2024-05-21 | Party Astronauts | L   | 0.695      | -            | -                | -                | -         |    -3.30 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|           28 |     1953 | 2024-05-19 | Wildcard         | L   | 0.681      | -            | -                | -                | -         |    -3.85 | CAJUN, Danejoris, Mellow, PoseidoNN, xCAPE  |
|           27 |     2083 | 2024-05-15 | Elevate          | L   | 0.655      | -            | -                | -                | -         |    -2.61 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|           26 |     2090 | 2024-05-15 | Elevate          | L   | 0.655      | -            | -                | -                | -         |    -2.67 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|           25 |     2265 | 2024-05-10 | M80              | L   | 0.622      | -            | -                | -                | -         |    -0.62 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|           24 |     2266 | 2024-05-10 | M80              | L   | 0.622      | -            | -                | -                | -         |    -0.62 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|           23 |     2279 | 2024-05-09 | FLUFFY AIMERS    | L   | 0.616      | -            | -                | -                | -         |    -6.96 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|           22 |     2282 | 2024-05-09 | FLUFFY AIMERS    | W   | 0.615      | 0.477        | 0.010 (0.003)    | 0.098 (0.029)    | 0 (0.000) |    12.75 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|           21 |     2300 | 2024-05-08 | Wildcard         | L   | 0.609      | -            | -                | -                | -         |    -3.65 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|           20 |     2303 | 2024-05-08 | Wildcard         | L   | 0.608      | -            | -                | -                | -         |    -3.77 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|           19 |     2877 | 2024-04-15 | Nouns            | L   | 0.456      | -            | -                | -                | -         |    -2.31 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|           18 |     2878 | 2024-04-15 | Nouns            | L   | 0.455      | -            | -                | -                | -         |    -2.36 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|           17 |     2936 | 2024-04-11 | BOSS             | L   | 0.429      | -            | -                | -                | -         |    -3.70 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|           16 |     2938 | 2024-04-11 | BOSS             | L   | 0.428      | -            | -                | -                | -         |    -3.81 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|           15 |     3154 | 2024-04-04 | Take Flyte       | L   | 0.382      | -            | -                | -                | -         |    -5.29 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|           14 |     3158 | 2024-04-04 | Take Flyte       | W   | 0.382      | 0.477        | 0.002 (0.000)    | 0.236 (0.043)    | 0 (0.000) |     6.89 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|           13 |     3200 | 2024-04-03 | Phoenix          | L   | 0.375      | -            | -                | -                | -         |    -4.67 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|           12 |     3202 | 2024-04-03 | Phoenix          | L   | 0.375      | -            | -                | -                | -         |    -4.82 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|           11 |     3329 | 2024-03-27 | MIGHT            | W   | 0.329      | 0.477        | 0.000 (0.000)    | 0.058 (0.009)    | 0 (0.000) |     3.50 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|           10 |     3335 | 2024-03-27 | MIGHT            | W   | 0.329      | 0.477        | 0.000 (0.000)    | 0.058 (0.009)    | 0 (0.000) |     3.60 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|            9 |     3379 | 2024-03-26 | Mythic           | L   | 0.322      | -            | -                | -                | -         |    -3.24 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|            8 |     3384 | 2024-03-26 | Mythic           | W   | 0.322      | 0.477        | 0.010 (0.001)    | 0.293 (0.045)    | 0 (0.000) |     7.04 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|            7 |     3571 | 2024-03-14 | NRG              | L   | 0.242      | -            | -                | -                | -         |    -1.89 | Danejoris, grape, Mellow, PoseidoNN, RiFT   |
|            6 |     3575 | 2024-03-14 | NRG              | L   | 0.242      | -            | -                | -                | -         |    -1.91 | Danejoris, grape, Mellow, PoseidoNN, RiFT   |
|            5 |     3784 | 2024-03-06 | Carpe Diem       | L   | 0.189      | -            | -                | -                | -         |    -2.79 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|            4 |     3787 | 2024-03-06 | Carpe Diem       | L   | 0.189      | -            | -                | -                | -         |    -2.83 | Danejoris, DooM, grape, Mellow, PoseidoNN   |
|            3 |     4032 | 2024-02-24 | NRG              | L   | 0.115      | -            | -                | -                | -         |    -0.91 | Danejoris, DooM, grape, Mellow, RiFT        |
|            2 |     4036 | 2024-02-24 | LAG              | W   | 0.115      | 0.143        | 0.012 (0.000)    | 0.347 (0.006)    | 0 (0.000) |     2.65 | Danejoris, DooM, grape, Mellow, RiFT        |
|            1 |     4253 | 2024-02-15 | OMiT             | L   | 0.055      | -            | -                | -                | -         |    -0.98 | Danejoris, DooM, grape, Mellow, RiFT        |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($328.61)
- Divide that value by the 5th highest value among all rosters ($321,880.58)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
