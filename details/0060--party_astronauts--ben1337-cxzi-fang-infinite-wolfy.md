### Roster Details<br />
Team Name: Party Astronauts<br />
Roster: ben1337, cxzi, FaNg, Infinite, WolfY<br />
Global Rank: [60](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [17]( ../standings_americas.md)<br />
<br />
Final Rank Value:  993.9<br />
<br />
Final Rank Value (993.9) = Starting Rank Value (926.4) + Head To Head Adjustments (67.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.419[<sup>1</sup>](#table2)
- Bounty Collected: 0.364[<sup>2</sup>](#table1)
- Opponent Network: 0.185[<sup>2</sup>](#table1)
- LAN Wins: 0.062[<sup>2</sup>](#table1)

The average of these factors is 0.257<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 926.4
- 400 + ( ( 0.257 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 926.4


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
|           72 |      150 | 2024-07-30 | NRG           | W   | 1.000      | 0.477        | 0.020 (0.010)    | 0.521 (0.248)    | 0 (0.000) |    15.48 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           71 |      154 | 2024-07-30 | NRG           | W   | 1.000      | 0.477        | 0.020 (0.010)    | 0.521 (0.248)    | 0 (0.000) |    16.91 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           70 |      381 | 2024-07-23 | FLUFFY AIMERS | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.21 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           69 |      383 | 2024-07-23 | FLUFFY AIMERS | L   | 1.000      | -            | -                | -                | -         |   -25.85 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           68 |      469 | 2024-07-20 | Wildcard      | L   | 1.000      | -            | -                | -                | -         |   -15.65 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           67 |      605 | 2024-07-17 | Take Flyte    | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.29 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           66 |      609 | 2024-07-17 | Take Flyte    | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.56 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           65 |      671 | 2024-07-16 | Limitless     | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.10 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           64 |      677 | 2024-07-16 | Limitless     | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.45 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           63 |     1013 | 2024-06-15 | Falcons       | L   | 0.866      | -            | -                | -                | -         |    -2.23 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           62 |     1057 | 2024-06-14 | The MongolZ   | L   | 0.859      | -            | -                | -                | -         |    -0.16 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           61 |     1168 | 2024-06-09 | Legacy        | L   | 0.831      | -            | -                | -                | -         |   -11.85 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           60 |     1236 | 2024-06-08 | Wildcard      | W   | 0.823      | 0.384        | 0.055 (0.017)    | 0.503 (0.159)    | 0 (0.000) |    12.47 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           59 |     1254 | 2024-06-08 | NRG           | L   | 0.822      | -            | -                | -                | -         |   -15.75 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           58 |     1286 | 2024-06-07 | Nouns         | L   | 0.818      | -            | -                | -                | -         |   -13.44 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           57 |     1294 | 2024-06-07 | Legacy        | W   | 0.817      | 0.143        | 0.122 (0.014)    | -                | 0 (0.000) |    13.90 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           56 |     1300 | 2024-06-07 | NRG           | W   | 0.816      | 0.384        | -                | 0.521 (0.163)    | -         |    10.04 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           55 |     1313 | 2024-06-07 | Nouns         | W   | 0.815      | -            | -                | -                | -         |    13.30 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           54 |     1344 | 2024-06-06 | NRG           | W   | 0.811      | 0.477        | 0.020 (0.008)    | 0.521 (0.201)    | -         |    11.19 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           53 |     1363 | 2024-06-06 | E-Xolos LAZER | W   | 0.809      | -            | -                | -                | -         |     6.74 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           52 |     1414 | 2024-06-05 | Wildcard      | L   | 0.804      | -            | -                | -                | -         |   -12.18 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           51 |     1465 | 2024-06-04 | Elevate       | W   | 0.797      | 0.477        | 0.027 (0.010)    | 0.505 (0.192)    | -         |    13.90 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           50 |     1774 | 2024-05-22 | Nouns         | L   | 0.711      | -            | -                | -                | -         |   -11.18 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           49 |     1783 | 2024-05-22 | M80           | W   | 0.711      | 0.477        | 0.188 (0.064)    | 0.587 (0.199)    | -         |    18.93 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           48 |     1787 | 2024-05-22 | M80           | L   | 0.710      | -            | -                | -                | -         |    -3.31 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           47 |     1821 | 2024-05-21 | Limitless     | W   | 0.705      | -            | -                | -                | -         |     3.21 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           46 |     1824 | 2024-05-21 | Limitless     | W   | 0.704      | -            | -                | -                | -         |     3.31 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           45 |     1857 | 2024-05-20 | Akimbo        | W   | 0.698      | -            | -                | -                | -         |     6.12 | ben1337, cxzi, FaNg, Infinite, WolfY |
|           44 |     1926 | 2024-05-18 | NRG           | L   | 0.682      | -            | -                | -                | -         |   -10.77 | ben1337, chop, cxzi, Infinite, WolfY |
|           43 |     1959 | 2024-05-17 | Legacy        | W   | 0.677      | 0.303        | 0.122 (0.025)    | -                | -         |    13.21 | ben1337, chop, cxzi, Infinite, WolfY |
|           42 |     1987 | 2024-05-16 | FLUFFY AIMERS | W   | 0.671      | -            | -                | -                | -         |     5.38 | ben1337, chop, cxzi, Infinite, WolfY |
|           41 |     1990 | 2024-05-16 | FLUFFY AIMERS | W   | 0.671      | -            | -                | -                | -         |     5.63 | ben1337, chop, cxzi, Infinite, WolfY |
|           40 |     2080 | 2024-05-14 | Mythic        | W   | 0.658      | -            | -                | -                | -         |     7.00 | ben1337, chop, cxzi, RUSH, WolfY     |
|           39 |     2087 | 2024-05-14 | Mythic        | L   | 0.657      | -            | -                | -                | -         |   -14.08 | ben1337, chop, cxzi, RUSH, WolfY     |
|           38 |     2180 | 2024-05-11 | BOSS          | L   | 0.636      | -            | -                | -                | -         |   -13.58 | ben1337, chop, cxzi, RUSH, WolfY     |
|           37 |     2184 | 2024-05-11 | Perseverance  | L   | 0.636      | -            | -                | -                | -         |   -15.50 | ben1337, chop, cxzi, RUSH, WolfY     |
|           36 |     2243 | 2024-05-08 | LAG           | W   | 0.618      | -            | -                | -                | -         |     7.00 | ben1337, chop, cxzi, RUSH, WolfY     |
|           35 |     2248 | 2024-05-08 | LAG           | W   | 0.618      | -            | -                | -                | -         |     7.37 | ben1337, chop, cxzi, RUSH, WolfY     |
|           34 |     2268 | 2024-05-07 | Elevate       | L   | 0.611      | -            | -                | -                | -         |    -8.96 | ben1337, chop, cxzi, RUSH, WolfY     |
|           33 |     2269 | 2024-05-07 | Elevate       | W   | 0.611      | 0.477        | 0.027 (0.008)    | 0.505 (0.147)    | -         |    10.54 | ben1337, chop, cxzi, RUSH, WolfY     |
|           32 |     2287 | 2024-05-06 | NRG           | L   | 0.604      | -            | -                | -                | -         |   -11.78 | ben1337, chop, cxzi, RUSH, WolfY     |
|           31 |     2288 | 2024-05-06 | NRG           | W   | 0.604      | 0.477        | -                | 0.521 (0.150)    | -         |     7.33 | ben1337, chop, cxzi, RUSH, WolfY     |
|           30 |     2359 | 2024-05-02 | Wildcard      | L   | 0.578      | -            | -                | -                | -         |   -10.06 | ben1337, chop, cxzi, RUSH, WolfY     |
|           29 |     2360 | 2024-05-02 | Wildcard      | W   | 0.577      | 0.477        | 0.055 (0.015)    | 0.503 (0.138)    | -         |     8.28 | ben1337, chop, cxzi, RUSH, WolfY     |
|           28 |     2496 | 2024-04-27 | Aurora        | L   | 0.539      | -            | -                | -                | -         |    -0.40 | ben1337, chop, cxzi, RUSH, WolfY     |
|           27 |     2498 | 2024-04-26 | sunday school | W   | 0.538      | -            | -                | -                | 1 (0.538) |     2.53 | ben1337, chop, cxzi, RUSH, WolfY     |
|           26 |     2525 | 2024-04-25 | Aurora        | L   | 0.531      | -            | -                | -                | -         |    -0.36 | ben1337, chop, cxzi, RUSH, WolfY     |
|           25 |     2965 | 2024-04-09 | Take Flyte    | W   | 0.424      | -            | -                | -                | -         |     2.75 | ben1337, chop, cxzi, RUSH, WolfY     |
|           24 |     2971 | 2024-04-09 | Take Flyte    | W   | 0.424      | -            | -                | -                | -         |     2.81 | ben1337, chop, cxzi, RUSH, WolfY     |
|           23 |     3095 | 2024-04-04 | MIGHT         | W   | 0.391      | -            | -                | -                | -         |     1.17 | ben1337, chop, cxzi, RUSH, WolfY     |
|           22 |     3102 | 2024-04-04 | MIGHT         | W   | 0.391      | -            | -                | -                | -         |     1.18 | ben1337, chop, cxzi, RUSH, WolfY     |
|           21 |     3192 | 2024-04-02 | Perseverance  | W   | 0.378      | -            | -                | -                | -         |     2.87 | ben1337, chop, CLASIA, cxzi, WolfY   |
|           20 |     3195 | 2024-04-02 | Nouns         | L   | 0.377      | -            | -                | -                | -         |    -6.19 | ben1337, chop, CLASIA, cxzi, WolfY   |
|           19 |     3273 | 2024-03-27 | Carpe Diem    | W   | 0.338      | -            | -                | -                | -         |     2.05 | ben1337, chop, cxzi, RUSH, WolfY     |
|           18 |     3276 | 2024-03-27 | Carpe Diem    | W   | 0.338      | -            | -                | -                | -         |     2.08 | ben1337, chop, cxzi, RUSH, WolfY     |
|           17 |     3318 | 2024-03-26 | Nouns         | L   | 0.331      | -            | -                | -                | -         |    -5.53 | ben1337, chop, cxzi, RUSH, WolfY     |
|           16 |     3323 | 2024-03-26 | Nouns         | L   | 0.331      | -            | -                | -                | -         |    -5.68 | ben1337, chop, cxzi, RUSH, WolfY     |
|           15 |     3401 | 2024-03-20 | BOSS          | W   | 0.291      | -            | -                | -                | -         |     2.95 | ben1337, chop, cxzi, RUSH, WolfY     |
|           14 |     3403 | 2024-03-20 | BOSS          | W   | 0.291      | -            | -                | -                | -         |     3.02 | ben1337, chop, cxzi, RUSH, WolfY     |
|           13 |     3422 | 2024-03-19 | Perseverance  | W   | 0.285      | -            | -                | -                | -         |     2.17 | ben1337, chop, cxzi, RUSH, WolfY     |
|           12 |     3424 | 2024-03-19 | Perseverance  | W   | 0.284      | -            | -                | -                | -         |     2.21 | ben1337, chop, cxzi, RUSH, WolfY     |
|           11 |     3552 | 2024-03-13 | Carpe Diem    | W   | 0.243      | -            | -                | -                | -         |     1.54 | ben1337, chop, cxzi, RUSH, WolfY     |
|           10 |     3593 | 2024-03-12 | Elevate       | W   | 0.238      | -            | -                | -                | -         |     4.43 | ben1337, chop, cxzi, RUSH, WolfY     |
|            9 |     3973 | 2024-02-24 | Wildcard      | L   | 0.124      | -            | -                | -                | -         |    -2.06 | ben1337, chop, cxzi, Walco, WolfY    |
|            8 |     3979 | 2024-02-24 | ex-CatEvil    | W   | 0.124      | -            | -                | -                | -         |     0.19 | ben1337, chop, cxzi, Walco, WolfY    |
|            7 |     4015 | 2024-02-22 | Liquid        | L   | 0.111      | -            | -                | -                | -         |    -0.14 | ben1337, chop, cxzi, Walco, WolfY    |
|            6 |     4016 | 2024-02-22 | NRG           | W   | 0.111      | -            | -                | -                | -         |     1.38 | ben1337, chop, cxzi, Walco, WolfY    |
|            5 |     4022 | 2024-02-22 | Take Flyte    | W   | 0.110      | -            | -                | -                | -         |     0.80 | ben1337, chop, cxzi, Walco, WolfY    |
|            4 |     4069 | 2024-02-20 | NRG           | W   | 0.098      | -            | -                | -                | -         |     1.23 | ben1337, chop, cxzi, Walco, WolfY    |
|            3 |     4071 | 2024-02-20 | Mythic        | W   | 0.097      | -            | -                | -                | -         |     0.99 | ben1337, chop, cxzi, Walco, WolfY    |
|            2 |     4094 | 2024-02-19 | NRG           | L   | 0.091      | -            | -                | -                | -         |    -1.74 | ben1337, chop, cxzi, Walco, WolfY    |
|            1 |     4097 | 2024-02-19 | Akimbo        | W   | 0.090      | -            | -                | -                | -         |     0.80 | ben1337, chop, cxzi, Walco, WolfY    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($13,356.25)
- Divide that value by the 5th highest value among all rosters ($324,557.31)
- The final value (0.04) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.874 | $2,000.00      | $1,748.89       |
| 2024-06-09 |      0.831 | $5,000.00      | $4,154.17       |
| 2024-06-09 |      0.831 | $7,000.00      | $5,813.89       |
| 2024-04-28 |      0.546 | $3,000.00      | $1,639.31       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
