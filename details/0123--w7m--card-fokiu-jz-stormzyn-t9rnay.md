### Roster Details<br />
Team Name: W7M<br />
Roster: card, fokiu, jz, stormzyn, t9rnay<br />
Global Rank: [123](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [32]( ../standings_americas.md)<br />
<br />
Final Rank Value:  805.0<br />
<br />
Final Rank Value (805.0) = Starting Rank Value (842.9) + Head To Head Adjustments (-37.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.317[<sup>1</sup>](#table2)
- Bounty Collected: 0.346[<sup>2</sup>](#table1)
- Opponent Network: 0.203[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.216<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 842.9
- 400 + ( ( 0.216 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 842.9


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
|           81 |      104 | 2024-08-01 | Dusty Roots       | L   | 1.000      | -            | -                | -                | -         |   -15.75 | card, fokiu, jz, stormzyn, t9rnay      |
|           80 |      304 | 2024-07-27 | Bad News Chickens | L   | 1.000      | -            | -                | -                | -         |   -26.15 | card, fokiu, jz, stormzyn, t9rnay      |
|           79 |      319 | 2024-07-26 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |    -4.75 | card, fokiu, jz, stormzyn, t9rnay      |
|           78 |      348 | 2024-07-25 | ODDIK             | W   | 1.000      | 0.143        | 0.099 (0.014)    | -                | 0 (0.000) |    22.92 | card, fokiu, jz, stormzyn, t9rnay      |
|           77 |      355 | 2024-07-25 | Bounty Hunters    | W   | 1.000      | -            | -                | -                | 0 (0.000) |    22.17 | card, fokiu, jz, stormzyn, t9rnay      |
|           76 |      395 | 2024-07-24 | Yawara            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.85 | card, fokiu, jz, stormzyn, t9rnay      |
|           75 |      400 | 2024-07-24 | Bad News Chickens | L   | 1.000      | -            | -                | -                | -         |   -26.22 | card, fokiu, jz, stormzyn, t9rnay      |
|           74 |      424 | 2024-07-23 | Sharks            | L   | 1.000      | -            | -                | -                | -         |    -9.12 | card, fokiu, jz, stormzyn, t9rnay      |
|           73 |      485 | 2024-07-21 | Hype              | L   | 1.000      | -            | -                | -                | -         |   -13.77 | card, fokiu, jz, stormzyn, t9rnay      |
|           72 |      520 | 2024-07-20 | KRÜ               | W   | 1.000      | 0.333        | 0.023 (0.008)    | 0.494 (0.165)    | 0 (0.000) |    15.93 | card, fokiu, jz, stormzyn, t9rnay      |
|           71 |      555 | 2024-07-19 | BESTIA            | W   | 1.000      | 0.333        | 0.095 (0.032)    | 0.802 (0.267)    | 0 (0.000) |    21.89 | card, fokiu, jz, stormzyn, t9rnay      |
|           70 |      666 | 2024-07-17 | SPORT             | W   | 1.000      | -            | -                | -                | 0 (0.000) |    11.83 | card, fokiu, jz, stormzyn, t9rnay      |
|           69 |      683 | 2024-07-17 | paiN              | L   | 1.000      | -            | -                | -                | -         |    -1.48 | card, fokiu, jz, stormzyn, t9rnay      |
|           68 |      727 | 2024-07-16 | Hype              | L   | 1.000      | -            | -                | -                | -         |   -11.79 | card, fokiu, jz, stormzyn, t9rnay      |
|           67 |      831 | 2024-07-12 | KRÜ               | L   | 1.000      | -            | -                | -                | -         |   -12.91 | card, fokiu, jz, stormzyn, t9rnay      |
|           66 |      841 | 2024-07-11 | Case              | W   | 1.000      | 0.371        | 0.029 (0.011)    | 0.806 (0.299)    | 0 (0.000) |    18.13 | card, fokiu, jz, stormzyn, t9rnay      |
|           65 |      848 | 2024-07-11 | Hype              | W   | 1.000      | 0.371        | 0.025 (0.009)    | 0.490 (0.182)    | 0 (0.000) |    20.03 | card, fokiu, jz, stormzyn, t9rnay      |
|           64 |      860 | 2024-07-10 | Vikings KR        | W   | 1.000      | 0.371        | -                | 0.507 (0.188)    | 0 (0.000) |    18.24 | card, fokiu, jz, stormzyn, t9rnay      |
|           63 |      867 | 2024-07-10 | 9z Academy        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.65 | card, fokiu, jz, stormzyn, t9rnay      |
|           62 |      890 | 2024-07-09 | Case              | L   | 1.000      | -            | -                | -                | -         |   -11.69 | card, fokiu, jz, stormzyn, t9rnay      |
|           61 |      925 | 2024-07-06 | ODDIK             | L   | 1.000      | -            | -                | -                | -         |    -8.23 | card, fokiu, jz, stormzyn, t9rnay      |
|           60 |      957 | 2024-06-27 | Bounty Hunters    | L   | 0.945      | -            | -                | -                | -         |    -9.55 | card, fokiu, jz, stormzyn, t9rnay      |
|           59 |     1177 | 2024-06-10 | ODDIK             | L   | 0.831      | -            | -                | -                | -         |    -7.91 | card, fokiu, jz, stormzyn, t9rnay      |
|           58 |     1219 | 2024-06-09 | Solid             | W   | 0.824      | 0.450        | 0.025 (0.009)    | 0.836 (0.310)    | -         |    16.01 | card, fokiu, jz, stormzyn, t9rnay      |
|           57 |     1267 | 2024-06-08 | ODDIK             | L   | 0.820      | -            | -                | -                | -         |    -8.03 | card, fokiu, jz, stormzyn, t9rnay      |
|           56 |     1276 | 2024-06-08 | Bounty Hunters    | L   | 0.819      | -            | -                | -                | -         |    -8.60 | card, fokiu, jz, stormzyn, t9rnay      |
|           55 |     1359 | 2024-06-07 | Galorys           | W   | 0.810      | 0.450        | 0.030 (0.011)    | 0.552 (0.201)    | -         |    15.62 | card, fokiu, jz, stormzyn, t9rnay      |
|           54 |     1413 | 2024-06-06 | Fluxo             | L   | 0.804      | -            | -                | -                | -         |    -4.22 | card, fokiu, jz, stormzyn, t9rnay      |
|           53 |     1539 | 2024-06-03 | Vikings KR        | W   | 0.787      | 0.371        | -                | 0.507 (0.148)    | -         |    13.30 | card, fokiu, jz, stormzyn, t9rnay      |
|           52 |     1604 | 2024-06-01 | ex-Corinthians    | W   | 0.770      | -            | -                | -                | -         |     5.29 | card, fokiu, jz, stormzyn, t9rnay      |
|           51 |     1647 | 2024-05-30 | Hype              | L   | 0.760      | -            | -                | -                | -         |    -8.57 | card, fokiu, jz, stormzyn, t9rnay      |
|           50 |     1699 | 2024-05-28 | Yawara            | W   | 0.745      | -            | -                | -                | -         |     4.25 | card, fokiu, jz, stormzyn, t9rnay      |
|           49 |     1824 | 2024-05-22 | Solid             | L   | 0.706      | -            | -                | -                | -         |    -7.84 | card, fokiu, jz, stormzyn, t9rnay      |
|           48 |     1827 | 2024-05-22 | Solid             | L   | 0.706      | -            | -                | -                | -         |    -8.31 | card, fokiu, stormzyn, t9rnay, zede    |
|           47 |     1904 | 2024-05-20 | 9z                | L   | 0.693      | -            | -                | -                | -         |    -0.53 | card, fokiu, stormzyn, t9rnay, zede    |
|           46 |     1907 | 2024-05-20 | 9z                | L   | 0.693      | -            | -                | -                | -         |    -0.54 | card, fokiu, stormzyn, t9rnay, zede    |
|           45 |     2027 | 2024-05-16 | Sharks            | L   | 0.666      | -            | -                | -                | -         |    -4.85 | card, fokiu, stormzyn, t9rnay, zede    |
|           44 |     2030 | 2024-05-16 | Sharks            | L   | 0.666      | -            | -                | -                | -         |    -5.06 | card, fokiu, stormzyn, t9rnay, zede    |
|           43 |     2126 | 2024-05-14 | Imperial          | L   | 0.653      | -            | -                | -                | -         |    -1.35 | card, fokiu, stormzyn, t9rnay, zede    |
|           42 |     2129 | 2024-05-14 | Imperial          | L   | 0.653      | -            | -                | -                | -         |    -1.37 | card, fokiu, stormzyn, t9rnay, zede    |
|           41 |     2142 | 2024-05-14 | Hype              | L   | 0.652      | -            | -                | -                | -         |    -8.18 | card, fokiu, stormzyn, t9rnay, zede    |
|           40 |     2175 | 2024-05-13 | Sharks            | L   | 0.644      | -            | -                | -                | -         |    -5.78 | fokiu, saadzin, stormzyn, t9rnay, zede |
|           39 |     2223 | 2024-05-11 | Sharks            | L   | 0.631      | -            | -                | -                | -         |    -5.94 | card, fokiu, stormzyn, t9rnay, zede    |
|           38 |     2274 | 2024-05-09 | KRÜ               | L   | 0.617      | -            | -                | -                | -         |    -7.51 | fokiu, saadzin, stormzyn, t9rnay, zede |
|           37 |     2307 | 2024-05-07 | paiN              | L   | 0.605      | -            | -                | -                | -         |    -0.76 | fokiu, saadzin, stormzyn, t9rnay, zede |
|           36 |     2327 | 2024-05-06 | paiN              | L   | 0.598      | -            | -                | -                | -         |    -0.76 | fokiu, jz, saadzin, stormzyn, zede     |
|           35 |     2328 | 2024-05-06 | paiN              | L   | 0.598      | -            | -                | -                | -         |    -0.77 | fokiu, jz, saadzin, stormzyn, zede     |
|           34 |     2350 | 2024-05-05 | Galorys           | W   | 0.590      | 0.435        | 0.030 (0.008)    | 0.552 (0.142)    | -         |    11.30 | fokiu, saadzin, stormzyn, t9rnay, zede |
|           33 |     2535 | 2024-04-26 | ODDIK             | L   | 0.532      | -            | -                | -                | -         |    -5.13 | fokiu, saadzin, stormzyn, t9rnay, zede |
|           32 |     2536 | 2024-04-26 | ODDIK             | L   | 0.532      | -            | -                | -                | -         |    -5.34 | fokiu, saadzin, stormzyn, t9rnay, zede |
|           31 |     2800 | 2024-04-17 | ODDIK             | L   | 0.472      | -            | -                | -                | -         |    -5.10 | fokiu, saadzin, stormzyn, t9rnay, zede |
|           30 |     2836 | 2024-04-16 | Sharks            | W   | 0.466      | -            | -                | -                | -         |     6.07 | fokiu, saadzin, stormzyn, t9rnay, zede |
|           29 |     2903 | 2024-04-12 | RED Canids        | L   | 0.438      | -            | -                | -                | -         |    -2.64 | fokiu, saadzin, stormzyn, t9rnay, zede |
|           28 |     3012 | 2024-04-09 | RED Canids        | L   | 0.419      | -            | -                | -                | -         |    -2.60 | fokiu, jz, saadzin, stormzyn, zede     |
|           27 |     3017 | 2024-04-09 | RED Canids        | L   | 0.419      | -            | -                | -                | -         |    -2.66 | fokiu, jz, saadzin, stormzyn, zede     |
|           26 |     3050 | 2024-04-08 | MIBR              | L   | 0.413      | -            | -                | -                | -         |    -0.52 | fokiu, jz, saadzin, stormzyn, zede     |
|           25 |     3106 | 2024-04-06 | RED Canids        | W   | 0.398      | 0.435        | 0.077 (0.013)    | 0.758 (0.131)    | -         |    10.14 | fokiu, jz, saadzin, stormzyn, zede     |
|           24 |     3323 | 2024-03-27 | BESTIA            | W   | 0.333      | 0.450        | 0.095 (0.014)    | -                | -         |     7.75 | fokiu, jz, saadzin, stormzyn, zede     |
|           23 |     3327 | 2024-03-27 | BESTIA            | L   | 0.333      | -            | -                | -                | -         |    -2.76 | fokiu, jz, saadzin, stormzyn, zede     |
|           22 |     3560 | 2024-03-14 | Galorys           | L   | 0.246      | -            | -                | -                | -         |    -3.23 | fokiu, jz, saadzin, stormzyn, zede     |
|           21 |     3562 | 2024-03-14 | Galorys           | L   | 0.246      | -            | -                | -                | -         |    -3.29 | fokiu, jz, saadzin, stormzyn, zede     |
|           20 |     3657 | 2024-03-11 | Solid             | L   | 0.225      | -            | -                | -                | -         |    -2.98 | fokiu, jz, saadzin, stormzyn, zede     |
|           19 |     3692 | 2024-03-09 | RED Canids        | L   | 0.213      | -            | -                | -                | -         |    -1.41 | fokiu, jz, saadzin, stormzyn, zede     |
|           18 |     3752 | 2024-03-07 | Solid             | W   | 0.198      | -            | -                | -                | -         |     3.66 | fokiu, jz, saadzin, stormzyn, zede     |
|           17 |     3806 | 2024-03-05 | 2GAME             | L   | 0.186      | -            | -                | -                | -         |    -4.16 | fokiu, jz, saadzin, stormzyn, zede     |
|           16 |     3808 | 2024-03-05 | 2GAME             | L   | 0.186      | -            | -                | -                | -         |    -4.21 | fokiu, jz, saadzin, stormzyn, zede     |
|           15 |     4013 | 2024-02-24 | Corinthians       | W   | 0.120      | -            | -                | -                | -         |     0.51 | fokiu, jz, saadzin, stormzyn, zede     |
|           14 |     4020 | 2024-02-24 | Corinthians       | W   | 0.119      | -            | -                | -                | -         |     0.51 | fokiu, jz, saadzin, stormzyn, zede     |
|           13 |     4073 | 2024-02-21 | Fluxo             | W   | 0.100      | -            | -                | -                | -         |     2.40 | fokiu, jz, saadzin, stormzyn, zede     |
|           12 |     4078 | 2024-02-21 | Fluxo             | L   | 0.099      | -            | -                | -                | -         |    -0.75 | fokiu, jz, saadzin, stormzyn, zede     |
|           11 |     4083 | 2024-02-21 | BESTIA            | L   | 0.098      | -            | -                | -                | -         |    -0.83 | fokiu, jz, saadzin, stormzyn, zede     |
|           10 |     4112 | 2024-02-20 | Case              | L   | 0.092      | -            | -                | -                | -         |    -1.06 | fokiu, jz, saadzin, stormzyn, zede     |
|            9 |     4177 | 2024-02-17 | Sharks            | W   | 0.073      | -            | -                | -                | -         |     1.54 | fokiu, jz, saadzin, stormzyn, zede     |
|            8 |     4208 | 2024-02-16 | Solid             | L   | 0.065      | -            | -                | -                | -         |    -0.86 | fokiu, jz, saadzin, stormzyn, zede     |
|            7 |     4217 | 2024-02-16 | Sharks            | L   | 0.064      | -            | -                | -                | -         |    -0.66 | fokiu, jz, saadzin, stormzyn, zede     |
|            6 |     4236 | 2024-02-15 | Fluxo             | L   | 0.059      | -            | -                | -                | -         |    -0.45 | fokiu, jz, saadzin, stormzyn, zede     |
|            5 |     4266 | 2024-02-14 | Hawks             | W   | 0.053      | -            | -                | -                | -         |     0.25 | fokiu, jz, saadzin, stormzyn, zede     |
|            4 |     4306 | 2024-02-13 | Case              | L   | 0.046      | -            | -                | -                | -         |    -0.54 | fokiu, jz, saadzin, stormzyn, zede     |
|            3 |     4311 | 2024-02-13 | Case              | W   | 0.046      | -            | -                | -                | -         |     0.92 | fokiu, jz, saadzin, stormzyn, zede     |
|            2 |     4317 | 2024-02-13 | Corinthians       | W   | 0.044      | -            | -                | -                | -         |     0.19 | fokiu, jz, saadzin, stormzyn, zede     |
|            1 |     4328 | 2024-02-12 | Corinthians       | W   | 0.038      | -            | -                | -                | -         |     0.16 | fokiu, jz, saadzin, stormzyn, zede     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,247.64)
- Divide that value by the 5th highest value among all rosters ($323,321.90)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-22 |      1.000 | $1,000.00      | $1,000.00       |
| 2024-07-14 |      1.000 | $1,000.00      | $1,000.00       |
| 2024-06-09 |      0.825 | $300.00        | $247.64         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
