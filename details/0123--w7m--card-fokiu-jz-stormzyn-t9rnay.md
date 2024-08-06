### Roster Details<br />
Team Name: W7M<br />
Roster: card, fokiu, jz, stormzyn, t9rnay<br />
Global Rank: [123](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [32]( ../standings_americas.md)<br />
<br />
Final Rank Value:  803.4<br />
<br />
Final Rank Value (803.4) = Starting Rank Value (841.0) + Head To Head Adjustments (-37.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.317[<sup>1</sup>](#table2)
- Bounty Collected: 0.346[<sup>2</sup>](#table1)
- Opponent Network: 0.195[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.214<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 841.0
- 400 + ( ( 0.214 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 841.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                 |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           81 |      149 | 2024-08-01 | Dusty Roots       | L   | 1.000      | -            | -                | -                | -         |   -15.72 | card, fokiu, jz, stormzyn, t9rnay      |
|           80 |      349 | 2024-07-27 | Bad News Chickens | L   | 1.000      | -            | -                | -                | -         |   -26.11 | card, fokiu, jz, stormzyn, t9rnay      |
|           79 |      364 | 2024-07-26 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |    -4.80 | card, fokiu, jz, stormzyn, t9rnay      |
|           78 |      393 | 2024-07-25 | ODDIK             | W   | 1.000      | 0.143        | 0.099 (0.014)    | -                | 0 (0.000) |    22.88 | card, fokiu, jz, stormzyn, t9rnay      |
|           77 |      400 | 2024-07-25 | Bounty Hunters    | W   | 1.000      | -            | -                | -                | 0 (0.000) |    22.13 | card, fokiu, jz, stormzyn, t9rnay      |
|           76 |      440 | 2024-07-24 | Yawara            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.89 | card, fokiu, jz, stormzyn, t9rnay      |
|           75 |      445 | 2024-07-24 | Bad News Chickens | L   | 1.000      | -            | -                | -                | -         |   -26.17 | card, fokiu, jz, stormzyn, t9rnay      |
|           74 |      469 | 2024-07-23 | Sharks            | L   | 1.000      | -            | -                | -                | -         |    -9.18 | card, fokiu, jz, stormzyn, t9rnay      |
|           73 |      530 | 2024-07-21 | Hype              | L   | 1.000      | -            | -                | -                | -         |   -13.78 | card, fokiu, jz, stormzyn, t9rnay      |
|           72 |      565 | 2024-07-20 | KRÜ               | W   | 1.000      | 0.333        | 0.023 (0.008)    | 0.479 (0.160)    | 0 (0.000) |    15.90 | card, fokiu, jz, stormzyn, t9rnay      |
|           71 |      600 | 2024-07-19 | BESTIA            | W   | 1.000      | 0.333        | 0.096 (0.032)    | 0.776 (0.259)    | 0 (0.000) |    21.83 | card, fokiu, jz, stormzyn, t9rnay      |
|           70 |      711 | 2024-07-17 | SPORT             | W   | 1.000      | -            | -                | -                | 0 (0.000) |    11.92 | card, fokiu, jz, stormzyn, t9rnay      |
|           69 |      728 | 2024-07-17 | paiN              | L   | 1.000      | -            | -                | -                | -         |    -1.50 | card, fokiu, jz, stormzyn, t9rnay      |
|           68 |      772 | 2024-07-16 | Hype              | L   | 1.000      | -            | -                | -                | -         |   -11.79 | card, fokiu, jz, stormzyn, t9rnay      |
|           67 |      876 | 2024-07-12 | KRÜ               | L   | 1.000      | -            | -                | -                | -         |   -12.95 | card, fokiu, jz, stormzyn, t9rnay      |
|           66 |      886 | 2024-07-11 | Case              | W   | 1.000      | 0.371        | 0.029 (0.011)    | 0.778 (0.288)    | 0 (0.000) |    18.12 | card, fokiu, jz, stormzyn, t9rnay      |
|           65 |      893 | 2024-07-11 | Hype              | W   | 1.000      | 0.371        | 0.025 (0.009)    | 0.476 (0.176)    | 0 (0.000) |    20.01 | card, fokiu, jz, stormzyn, t9rnay      |
|           64 |      905 | 2024-07-10 | Vikings KR        | W   | 1.000      | 0.371        | -                | 0.490 (0.182)    | 0 (0.000) |    18.22 | card, fokiu, jz, stormzyn, t9rnay      |
|           63 |      912 | 2024-07-10 | 9z Academy        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.70 | card, fokiu, jz, stormzyn, t9rnay      |
|           62 |      935 | 2024-07-09 | Case              | L   | 1.000      | -            | -                | -                | -         |   -11.69 | card, fokiu, jz, stormzyn, t9rnay      |
|           61 |      970 | 2024-07-06 | ODDIK             | L   | 0.994      | -            | -                | -                | -         |    -8.21 | card, fokiu, jz, stormzyn, t9rnay      |
|           60 |     1002 | 2024-06-27 | Bounty Hunters    | L   | 0.934      | -            | -                | -                | -         |    -9.48 | card, fokiu, jz, stormzyn, t9rnay      |
|           59 |     1222 | 2024-06-10 | ODDIK             | L   | 0.821      | -            | -                | -                | -         |    -7.83 | card, fokiu, jz, stormzyn, t9rnay      |
|           58 |     1264 | 2024-06-09 | Solid             | W   | 0.814      | 0.450        | 0.024 (0.009)    | 0.807 (0.295)    | -         |    15.78 | card, fokiu, jz, stormzyn, t9rnay      |
|           57 |     1312 | 2024-06-08 | ODDIK             | L   | 0.809      | -            | -                | -                | -         |    -7.94 | card, fokiu, jz, stormzyn, t9rnay      |
|           56 |     1321 | 2024-06-08 | Bounty Hunters    | L   | 0.808      | -            | -                | -                | -         |    -8.53 | card, fokiu, jz, stormzyn, t9rnay      |
|           55 |     1404 | 2024-06-07 | Galorys           | W   | 0.799      | 0.450        | 0.030 (0.011)    | 0.530 (0.191)    | -         |    15.42 | card, fokiu, jz, stormzyn, t9rnay      |
|           54 |     1458 | 2024-06-06 | Fluxo             | L   | 0.794      | -            | -                | -                | -         |    -4.22 | card, fokiu, jz, stormzyn, t9rnay      |
|           53 |     1584 | 2024-06-03 | Vikings KR        | W   | 0.776      | 0.371        | -                | 0.490 (0.141)    | -         |    13.11 | card, fokiu, jz, stormzyn, t9rnay      |
|           52 |     1649 | 2024-06-01 | ex-Corinthians    | W   | 0.760      | -            | -                | -                | -         |     5.26 | card, fokiu, jz, stormzyn, t9rnay      |
|           51 |     1692 | 2024-05-30 | Hype              | L   | 0.749      | -            | -                | -                | -         |    -8.46 | card, fokiu, jz, stormzyn, t9rnay      |
|           50 |     1744 | 2024-05-28 | Yawara            | W   | 0.735      | -            | -                | -                | -         |     4.21 | card, fokiu, jz, stormzyn, t9rnay      |
|           49 |     1869 | 2024-05-22 | Solid             | L   | 0.695      | -            | -                | -                | -         |    -7.76 | card, fokiu, jz, stormzyn, t9rnay      |
|           48 |     1872 | 2024-05-22 | Solid             | L   | 0.695      | -            | -                | -                | -         |    -8.21 | card, fokiu, stormzyn, t9rnay, zede    |
|           47 |     1949 | 2024-05-20 | 9z                | L   | 0.682      | -            | -                | -                | -         |    -0.53 | card, fokiu, stormzyn, t9rnay, zede    |
|           46 |     1952 | 2024-05-20 | 9z                | L   | 0.682      | -            | -                | -                | -         |    -0.53 | card, fokiu, stormzyn, t9rnay, zede    |
|           45 |     2072 | 2024-05-16 | Sharks            | L   | 0.655      | -            | -                | -                | -         |    -4.83 | card, fokiu, stormzyn, t9rnay, zede    |
|           44 |     2075 | 2024-05-16 | Sharks            | L   | 0.655      | -            | -                | -                | -         |    -5.03 | card, fokiu, stormzyn, t9rnay, zede    |
|           43 |     2171 | 2024-05-14 | Imperial          | L   | 0.642      | -            | -                | -                | -         |    -1.37 | card, fokiu, stormzyn, t9rnay, zede    |
|           42 |     2174 | 2024-05-14 | Imperial          | L   | 0.642      | -            | -                | -                | -         |    -1.39 | card, fokiu, stormzyn, t9rnay, zede    |
|           41 |     2187 | 2024-05-14 | Hype              | L   | 0.641      | -            | -                | -                | -         |    -8.04 | card, fokiu, stormzyn, t9rnay, zede    |
|           40 |     2220 | 2024-05-13 | Sharks            | L   | 0.634      | -            | -                | -                | -         |    -5.74 | fokiu, saadzin, stormzyn, t9rnay, zede |
|           39 |     2268 | 2024-05-11 | Sharks            | L   | 0.621      | -            | -                | -                | -         |    -5.89 | card, fokiu, stormzyn, t9rnay, zede    |
|           38 |     2319 | 2024-05-09 | KRÜ               | L   | 0.606      | -            | -                | -                | -         |    -7.41 | fokiu, saadzin, stormzyn, t9rnay, zede |
|           37 |     2352 | 2024-05-07 | paiN              | L   | 0.594      | -            | -                | -                | -         |    -0.77 | fokiu, saadzin, stormzyn, t9rnay, zede |
|           36 |     2372 | 2024-05-06 | paiN              | L   | 0.588      | -            | -                | -                | -         |    -0.77 | fokiu, jz, saadzin, stormzyn, zede     |
|           35 |     2373 | 2024-05-06 | paiN              | L   | 0.587      | -            | -                | -                | -         |    -0.77 | fokiu, jz, saadzin, stormzyn, zede     |
|           34 |     2395 | 2024-05-05 | Galorys           | W   | 0.579      | 0.435        | 0.030 (0.007)    | 0.530 (0.133)    | -         |    11.08 | fokiu, saadzin, stormzyn, t9rnay, zede |
|           33 |     2580 | 2024-04-26 | ODDIK             | L   | 0.522      | -            | -                | -                | -         |    -5.05 | fokiu, saadzin, stormzyn, t9rnay, zede |
|           32 |     2581 | 2024-04-26 | ODDIK             | L   | 0.521      | -            | -                | -                | -         |    -5.25 | fokiu, saadzin, stormzyn, t9rnay, zede |
|           31 |     2845 | 2024-04-17 | ODDIK             | L   | 0.461      | -            | -                | -                | -         |    -4.99 | fokiu, saadzin, stormzyn, t9rnay, zede |
|           30 |     2881 | 2024-04-16 | Sharks            | W   | 0.455      | -            | -                | -                | -         |     5.96 | fokiu, saadzin, stormzyn, t9rnay, zede |
|           29 |     2948 | 2024-04-12 | RED Canids        | L   | 0.427      | -            | -                | -                | -         |    -2.61 | fokiu, saadzin, stormzyn, t9rnay, zede |
|           28 |     3057 | 2024-04-09 | RED Canids        | L   | 0.409      | -            | -                | -                | -         |    -2.56 | fokiu, jz, saadzin, stormzyn, zede     |
|           27 |     3062 | 2024-04-09 | RED Canids        | L   | 0.408      | -            | -                | -                | -         |    -2.62 | fokiu, jz, saadzin, stormzyn, zede     |
|           26 |     3095 | 2024-04-08 | MIBR              | L   | 0.402      | -            | -                | -                | -         |    -0.51 | fokiu, jz, saadzin, stormzyn, zede     |
|           25 |     3151 | 2024-04-06 | RED Canids        | W   | 0.387      | 0.435        | 0.076 (0.013)    | 0.732 (0.123)    | -         |     9.83 | fokiu, jz, saadzin, stormzyn, zede     |
|           24 |     3368 | 2024-03-27 | BESTIA            | W   | 0.322      | 0.450        | 0.096 (0.014)    | -                | -         |     7.49 | fokiu, jz, saadzin, stormzyn, zede     |
|           23 |     3372 | 2024-03-27 | BESTIA            | L   | 0.322      | -            | -                | -                | -         |    -2.68 | fokiu, jz, saadzin, stormzyn, zede     |
|           22 |     3605 | 2024-03-14 | Galorys           | L   | 0.236      | -            | -                | -                | -         |    -3.08 | fokiu, jz, saadzin, stormzyn, zede     |
|           21 |     3607 | 2024-03-14 | Galorys           | L   | 0.235      | -            | -                | -                | -         |    -3.14 | fokiu, jz, saadzin, stormzyn, zede     |
|           20 |     3702 | 2024-03-11 | Solid             | L   | 0.214      | -            | -                | -                | -         |    -2.85 | fokiu, jz, saadzin, stormzyn, zede     |
|           19 |     3737 | 2024-03-09 | RED Canids        | L   | 0.202      | -            | -                | -                | -         |    -1.35 | fokiu, jz, saadzin, stormzyn, zede     |
|           18 |     3797 | 2024-03-07 | Solid             | W   | 0.187      | -            | -                | -                | -         |     3.45 | fokiu, jz, saadzin, stormzyn, zede     |
|           17 |     3851 | 2024-03-05 | 2GAME             | L   | 0.176      | -            | -                | -                | -         |    -3.91 | fokiu, jz, saadzin, stormzyn, zede     |
|           16 |     3853 | 2024-03-05 | 2GAME             | L   | 0.175      | -            | -                | -                | -         |    -3.95 | fokiu, jz, saadzin, stormzyn, zede     |
|           15 |     4058 | 2024-02-24 | Corinthians       | W   | 0.109      | -            | -                | -                | -         |     0.46 | fokiu, jz, saadzin, stormzyn, zede     |
|           14 |     4065 | 2024-02-24 | Corinthians       | W   | 0.109      | -            | -                | -                | -         |     0.47 | fokiu, jz, saadzin, stormzyn, zede     |
|           13 |     4118 | 2024-02-21 | Fluxo             | W   | 0.089      | -            | -                | -                | -         |     2.13 | fokiu, jz, saadzin, stormzyn, zede     |
|           12 |     4123 | 2024-02-21 | Fluxo             | L   | 0.089      | -            | -                | -                | -         |    -0.67 | fokiu, jz, saadzin, stormzyn, zede     |
|           11 |     4128 | 2024-02-21 | BESTIA            | L   | 0.087      | -            | -                | -                | -         |    -0.74 | fokiu, jz, saadzin, stormzyn, zede     |
|           10 |     4157 | 2024-02-20 | Case              | L   | 0.081      | -            | -                | -                | -         |    -0.94 | fokiu, jz, saadzin, stormzyn, zede     |
|            9 |     4222 | 2024-02-17 | Sharks            | W   | 0.062      | -            | -                | -                | -         |     1.31 | fokiu, jz, saadzin, stormzyn, zede     |
|            8 |     4253 | 2024-02-16 | Solid             | L   | 0.054      | -            | -                | -                | -         |    -0.72 | fokiu, jz, saadzin, stormzyn, zede     |
|            7 |     4262 | 2024-02-16 | Sharks            | L   | 0.053      | -            | -                | -                | -         |    -0.55 | fokiu, jz, saadzin, stormzyn, zede     |
|            6 |     4281 | 2024-02-15 | Fluxo             | L   | 0.048      | -            | -                | -                | -         |    -0.37 | fokiu, jz, saadzin, stormzyn, zede     |
|            5 |     4311 | 2024-02-14 | Hawks             | W   | 0.042      | -            | -                | -                | -         |     0.20 | fokiu, jz, saadzin, stormzyn, zede     |
|            4 |     4351 | 2024-02-13 | Case              | L   | 0.036      | -            | -                | -                | -         |    -0.41 | fokiu, jz, saadzin, stormzyn, zede     |
|            3 |     4356 | 2024-02-13 | Case              | W   | 0.035      | -            | -                | -                | -         |     0.70 | fokiu, jz, saadzin, stormzyn, zede     |
|            2 |     4362 | 2024-02-13 | Corinthians       | W   | 0.034      | -            | -                | -                | -         |     0.14 | fokiu, jz, saadzin, stormzyn, zede     |
|            1 |     4373 | 2024-02-12 | Corinthians       | W   | 0.027      | -            | -                | -                | -         |     0.12 | fokiu, jz, saadzin, stormzyn, zede     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,244.39)
- Divide that value by the 5th highest value among all rosters ($320,109.81)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-22 |      1.000 | $1,000.00      | $1,000.00       |
| 2024-07-14 |      1.000 | $1,000.00      | $1,000.00       |
| 2024-06-09 |      0.815 | $300.00        | $244.39         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
