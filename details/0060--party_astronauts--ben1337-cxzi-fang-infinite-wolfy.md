### Roster Details<br />
Team Name: Party Astronauts<br />
Roster: ben1337, cxzi, FaNg, Infinite, WolfY<br />
Global Rank: [60](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [17]( ../standings_americas.md)<br />
<br />
Final Rank Value:  994.3<br />
<br />
Final Rank Value (994.3) = Starting Rank Value (926.7) + Head To Head Adjustments (67.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.419[<sup>1</sup>](#table2)
- Bounty Collected: 0.365[<sup>2</sup>](#table1)
- Opponent Network: 0.185[<sup>2</sup>](#table1)
- LAN Wins: 0.062[<sup>2</sup>](#table1)

The average of these factors is 0.258<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 926.7
- 400 + ( ( 0.258 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 926.7


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
|           72 |      147 | 2024-07-30 | NRG           | W   | 1.000      | 0.477        | 0.020 (0.010)    | 0.521 (0.248)    | 0 (0.000) |    15.48 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           71 |      151 | 2024-07-30 | NRG           | W   | 1.000      | 0.477        | 0.020 (0.010)    | 0.521 (0.248)    | 0 (0.000) |    16.91 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           70 |      378 | 2024-07-23 | FLUFFY AIMERS | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.20 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           69 |      380 | 2024-07-23 | FLUFFY AIMERS | L   | 1.000      | -            | -                | -                | -         |   -25.86 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           68 |      466 | 2024-07-20 | Wildcard      | L   | 1.000      | -            | -                | -                | -         |   -15.65 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           67 |      602 | 2024-07-17 | Take Flyte    | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.28 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           66 |      606 | 2024-07-17 | Take Flyte    | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.55 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           65 |      668 | 2024-07-16 | Limitless     | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.09 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           64 |      674 | 2024-07-16 | Limitless     | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.45 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           63 |     1009 | 2024-06-15 | Falcons       | L   | 0.869      | -            | -                | -                | -         |    -2.23 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           62 |     1053 | 2024-06-14 | The MongolZ   | L   | 0.863      | -            | -                | -                | -         |    -0.16 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           61 |     1164 | 2024-06-09 | Legacy        | L   | 0.834      | -            | -                | -                | -         |   -11.89 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           60 |     1232 | 2024-06-08 | Wildcard      | W   | 0.826      | 0.384        | 0.055 (0.017)    | 0.502 (0.159)    | 0 (0.000) |    12.51 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           59 |     1250 | 2024-06-08 | NRG           | L   | 0.825      | -            | -                | -                | -         |   -15.81 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           58 |     1282 | 2024-06-07 | Nouns         | L   | 0.821      | -            | -                | -                | -         |   -13.49 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           57 |     1290 | 2024-06-07 | Legacy        | W   | 0.820      | 0.143        | 0.122 (0.014)    | -                | 0 (0.000) |    13.96 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           56 |     1296 | 2024-06-07 | NRG           | W   | 0.819      | 0.384        | -                | 0.521 (0.164)    | -         |    10.08 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           55 |     1309 | 2024-06-07 | Nouns         | W   | 0.818      | -            | -                | -                | -         |    13.35 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           54 |     1340 | 2024-06-06 | NRG           | W   | 0.814      | 0.477        | 0.020 (0.008)    | 0.521 (0.202)    | -         |    11.23 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           53 |     1359 | 2024-06-06 | E-Xolos LAZER | W   | 0.812      | -            | -                | -                | -         |     6.75 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           52 |     1410 | 2024-06-05 | Wildcard      | L   | 0.807      | -            | -                | -                | -         |   -12.22 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           51 |     1461 | 2024-06-04 | Elevate       | W   | 0.801      | 0.477        | 0.027 (0.010)    | 0.505 (0.193)    | -         |    13.95 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           50 |     1770 | 2024-05-22 | Nouns         | L   | 0.714      | -            | -                | -                | -         |   -11.23 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           49 |     1779 | 2024-05-22 | M80           | W   | 0.714      | 0.477        | 0.188 (0.064)    | 0.587 (0.200)    | -         |    19.01 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           48 |     1783 | 2024-05-22 | M80           | L   | 0.713      | -            | -                | -                | -         |    -3.32 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           47 |     1817 | 2024-05-21 | Limitless     | W   | 0.708      | -            | -                | -                | -         |     3.21 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           46 |     1820 | 2024-05-21 | Limitless     | W   | 0.708      | -            | -                | -                | -         |     3.32 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           45 |     1853 | 2024-05-20 | Akimbo        | W   | 0.701      | -            | -                | -                | -         |     6.14 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           44 |     1922 | 2024-05-18 | NRG           | L   | 0.686      | -            | -                | -                | -         |   -10.81 | ben1337, chop, cxzi, Infinite, WolfY |
|           43 |     1955 | 2024-05-17 | Legacy        | W   | 0.680      | 0.303        | 0.122 (0.025)    | -                | -         |    13.28 | ben1337, chop, cxzi, Infinite, WolfY |
|           42 |     1983 | 2024-05-16 | FLUFFY AIMERS | W   | 0.674      | -            | -                | -                | -         |     5.39 | ben1337, chop, cxzi, Infinite, WolfY |
|           41 |     1986 | 2024-05-16 | FLUFFY AIMERS | W   | 0.674      | -            | -                | -                | -         |     5.64 | ben1337, chop, cxzi, Infinite, WolfY |
|           40 |     2076 | 2024-05-14 | Mythic        | W   | 0.661      | -            | -                | -                | -         |     7.03 | ben1337, chop, cxzi, RUSH, WolfY     |
|           39 |     2083 | 2024-05-14 | Mythic        | L   | 0.661      | -            | -                | -                | -         |   -14.15 | ben1337, chop, cxzi, RUSH, WolfY     |
|           38 |     2176 | 2024-05-11 | BOSS          | L   | 0.639      | -            | -                | -                | -         |   -13.65 | ben1337, chop, cxzi, RUSH, WolfY     |
|           37 |     2180 | 2024-05-11 | Perseverance  | L   | 0.639      | -            | -                | -                | -         |   -15.58 | ben1337, chop, cxzi, RUSH, WolfY     |
|           36 |     2239 | 2024-05-08 | LAG           | W   | 0.621      | -            | -                | -                | -         |     7.04 | ben1337, chop, cxzi, RUSH, WolfY     |
|           35 |     2244 | 2024-05-08 | LAG           | W   | 0.621      | -            | -                | -                | -         |     7.41 | ben1337, chop, cxzi, RUSH, WolfY     |
|           34 |     2264 | 2024-05-07 | Elevate       | L   | 0.614      | -            | -                | -                | -         |    -9.02 | ben1337, chop, cxzi, RUSH, WolfY     |
|           33 |     2265 | 2024-05-07 | Elevate       | W   | 0.614      | 0.477        | 0.027 (0.008)    | 0.505 (0.148)    | -         |    10.58 | ben1337, chop, cxzi, RUSH, WolfY     |
|           32 |     2283 | 2024-05-06 | NRG           | L   | 0.607      | -            | -                | -                | -         |   -11.85 | ben1337, chop, cxzi, RUSH, WolfY     |
|           31 |     2284 | 2024-05-06 | NRG           | W   | 0.607      | 0.477        | -                | 0.521 (0.151)    | -         |     7.36 | ben1337, chop, cxzi, RUSH, WolfY     |
|           30 |     2355 | 2024-05-02 | Wildcard      | L   | 0.581      | -            | -                | -                | -         |   -10.12 | ben1337, chop, cxzi, RUSH, WolfY     |
|           29 |     2356 | 2024-05-02 | Wildcard      | W   | 0.580      | 0.477        | 0.055 (0.015)    | 0.502 (0.139)    | -         |     8.32 | ben1337, chop, cxzi, RUSH, WolfY     |
|           28 |     2492 | 2024-04-27 | Aurora        | L   | 0.542      | -            | -                | -                | -         |    -0.41 | ben1337, chop, cxzi, RUSH, WolfY     |
|           27 |     2494 | 2024-04-26 | sunday school | W   | 0.541      | -            | -                | -                | 1 (0.541) |     2.55 | ben1337, chop, cxzi, RUSH, WolfY     |
|           26 |     2520 | 2024-04-25 | Aurora        | L   | 0.534      | -            | -                | -                | -         |    -0.36 | ben1337, chop, cxzi, RUSH, WolfY     |
|           25 |     2960 | 2024-04-09 | Take Flyte    | W   | 0.427      | -            | -                | -                | -         |     2.76 | ben1337, chop, cxzi, RUSH, WolfY     |
|           24 |     2966 | 2024-04-09 | Take Flyte    | W   | 0.427      | -            | -                | -                | -         |     2.83 | ben1337, chop, cxzi, RUSH, WolfY     |
|           23 |     3090 | 2024-04-04 | MIGHT         | W   | 0.394      | -            | -                | -                | -         |     1.18 | ben1337, chop, cxzi, RUSH, WolfY     |
|           22 |     3097 | 2024-04-04 | MIGHT         | W   | 0.394      | -            | -                | -                | -         |     1.19 | ben1337, chop, cxzi, RUSH, WolfY     |
|           21 |     3187 | 2024-04-02 | Perseverance  | W   | 0.381      | -            | -                | -                | -         |     2.89 | ben1337, chop, CLASIA, cxzi, WolfY   |
|           20 |     3190 | 2024-04-02 | Nouns         | L   | 0.380      | -            | -                | -                | -         |    -6.24 | ben1337, chop, CLASIA, cxzi, WolfY   |
|           19 |     3268 | 2024-03-27 | Carpe Diem    | W   | 0.341      | -            | -                | -                | -         |     2.06 | ben1337, chop, cxzi, RUSH, WolfY     |
|           18 |     3271 | 2024-03-27 | Carpe Diem    | W   | 0.341      | -            | -                | -                | -         |     2.10 | ben1337, chop, cxzi, RUSH, WolfY     |
|           17 |     3313 | 2024-03-26 | Nouns         | L   | 0.335      | -            | -                | -                | -         |    -5.58 | ben1337, chop, cxzi, RUSH, WolfY     |
|           16 |     3318 | 2024-03-26 | Nouns         | L   | 0.334      | -            | -                | -                | -         |    -5.74 | ben1337, chop, cxzi, RUSH, WolfY     |
|           15 |     3396 | 2024-03-20 | BOSS          | W   | 0.294      | -            | -                | -                | -         |     2.98 | ben1337, chop, cxzi, RUSH, WolfY     |
|           14 |     3398 | 2024-03-20 | BOSS          | W   | 0.294      | -            | -                | -                | -         |     3.05 | ben1337, chop, cxzi, RUSH, WolfY     |
|           13 |     3417 | 2024-03-19 | Perseverance  | W   | 0.288      | -            | -                | -                | -         |     2.19 | ben1337, chop, cxzi, RUSH, WolfY     |
|           12 |     3419 | 2024-03-19 | Perseverance  | W   | 0.287      | -            | -                | -                | -         |     2.23 | ben1337, chop, cxzi, RUSH, WolfY     |
|           11 |     3547 | 2024-03-13 | Carpe Diem    | W   | 0.246      | -            | -                | -                | -         |     1.55 | ben1337, chop, cxzi, RUSH, WolfY     |
|           10 |     3587 | 2024-03-12 | Elevate       | W   | 0.241      | -            | -                | -                | -         |     4.48 | ben1337, chop, cxzi, RUSH, WolfY     |
|            9 |     3967 | 2024-02-24 | Wildcard      | L   | 0.127      | -            | -                | -                | -         |    -2.12 | ben1337, chop, cxzi, Walco, WolfY    |
|            8 |     3973 | 2024-02-24 | ex-CatEvil    | W   | 0.127      | -            | -                | -                | -         |     0.20 | ben1337, chop, cxzi, Walco, WolfY    |
|            7 |     4009 | 2024-02-22 | Liquid        | L   | 0.114      | -            | -                | -                | -         |    -0.14 | ben1337, chop, cxzi, Walco, WolfY    |
|            6 |     4010 | 2024-02-22 | NRG           | W   | 0.114      | -            | -                | -                | -         |     1.42 | ben1337, chop, cxzi, Walco, WolfY    |
|            5 |     4016 | 2024-02-22 | Take Flyte    | W   | 0.113      | -            | -                | -                | -         |     0.82 | ben1337, chop, cxzi, Walco, WolfY    |
|            4 |     4063 | 2024-02-20 | NRG           | W   | 0.101      | -            | -                | -                | -         |     1.26 | ben1337, chop, cxzi, Walco, WolfY    |
|            3 |     4065 | 2024-02-20 | Mythic        | W   | 0.100      | -            | -                | -                | -         |     1.02 | ben1337, chop, cxzi, Walco, WolfY    |
|            2 |     4088 | 2024-02-19 | NRG           | L   | 0.094      | -            | -                | -                | -         |    -1.80 | ben1337, chop, cxzi, Walco, WolfY    |
|            1 |     4091 | 2024-02-19 | Akimbo        | W   | 0.093      | -            | -                | -                | -         |     0.82 | ben1337, chop, cxzi, Walco, WolfY    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($13,408.19)
- Divide that value by the 5th highest value among all rosters ($325,463.29)
- The final value (0.04) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.877 | $2,000.00      | $1,755.00       |
| 2024-06-09 |      0.834 | $5,000.00      | $4,169.44       |
| 2024-06-09 |      0.834 | $7,000.00      | $5,835.28       |
| 2024-04-28 |      0.549 | $3,000.00      | $1,648.47       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
