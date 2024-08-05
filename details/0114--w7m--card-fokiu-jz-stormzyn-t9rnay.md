### Roster Details<br />
Team Name: W7M<br />
Roster: card, fokiu, jz, stormzyn, t9rnay<br />
Global Rank: [114](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [28]( ../standings_americas.md)<br />
<br />
Final Rank Value:  820.0<br />
<br />
Final Rank Value (820.0) = Starting Rank Value (842.5) + Head To Head Adjustments (-22.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.316[<sup>1</sup>](#table2)
- Bounty Collected: 0.348[<sup>2</sup>](#table1)
- Opponent Network: 0.195[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.215<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 842.5
- 400 + ( ( 0.215 - 0.000 ) / ( 0.776 - 0.000 ) ) * 1600 = 842.5


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
|           81 |      151 | 2024-07-27 | Bad News Chickens | L   | 1.000      | -            | -                | -                | -         |   -26.12 | card, fokiu, jz, stormzyn, t9rnay      |
|           80 |      166 | 2024-07-26 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |    -4.65 | card, fokiu, jz, stormzyn, t9rnay      |
|           79 |      195 | 2024-07-25 | ODDIK             | W   | 1.000      | 0.143        | 0.097 (0.014)    | -                | 0 (0.000) |    22.97 | card, fokiu, jz, stormzyn, t9rnay      |
|           78 |      202 | 2024-07-25 | Bounty Hunters    | W   | 1.000      | -            | -                | -                | 0 (0.000) |    22.24 | card, fokiu, jz, stormzyn, t9rnay      |
|           77 |      242 | 2024-07-24 | Yawara            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.89 | card, fokiu, jz, stormzyn, t9rnay      |
|           76 |      247 | 2024-07-24 | Bad News Chickens | L   | 1.000      | -            | -                | -                | -         |   -26.18 | card, fokiu, jz, stormzyn, t9rnay      |
|           75 |      271 | 2024-07-23 | Sharks            | L   | 1.000      | -            | -                | -                | -         |    -9.01 | card, fokiu, jz, stormzyn, t9rnay      |
|           74 |      332 | 2024-07-21 | Hype              | L   | 1.000      | -            | -                | -                | -         |   -13.74 | card, fokiu, jz, stormzyn, t9rnay      |
|           73 |      367 | 2024-07-20 | KRÜ               | W   | 1.000      | 0.333        | 0.023 (0.008)    | 0.444 (0.148)    | 0 (0.000) |    15.89 | card, fokiu, jz, stormzyn, t9rnay      |
|           72 |      402 | 2024-07-19 | BESTIA            | W   | 1.000      | 0.333        | 0.095 (0.032)    | 0.731 (0.244)    | 0 (0.000) |    22.05 | card, fokiu, jz, stormzyn, t9rnay      |
|           71 |      513 | 2024-07-17 | SPORT             | W   | 1.000      | -            | -                | -                | 0 (0.000) |    11.93 | card, fokiu, jz, stormzyn, t9rnay      |
|           70 |      530 | 2024-07-17 | paiN              | L   | 1.000      | -            | -                | -                | -         |    -1.38 | card, fokiu, jz, stormzyn, t9rnay      |
|           69 |      574 | 2024-07-16 | Hype              | L   | 1.000      | -            | -                | -                | -         |   -11.75 | card, fokiu, jz, stormzyn, t9rnay      |
|           68 |      678 | 2024-07-12 | KRÜ               | L   | 1.000      | -            | -                | -                | -         |   -13.06 | card, fokiu, jz, stormzyn, t9rnay      |
|           67 |      688 | 2024-07-11 | Case              | W   | 1.000      | 0.371        | 0.030 (0.011)    | 0.720 (0.267)    | 0 (0.000) |    18.14 | card, fokiu, jz, stormzyn, t9rnay      |
|           66 |      695 | 2024-07-11 | Hype              | W   | 1.000      | 0.371        | 0.025 (0.009)    | 0.478 (0.177)    | 0 (0.000) |    20.06 | card, fokiu, jz, stormzyn, t9rnay      |
|           65 |      707 | 2024-07-10 | Vikings KR        | W   | 1.000      | 0.371        | -                | 0.458 (0.170)    | 0 (0.000) |    18.27 | card, fokiu, jz, stormzyn, t9rnay      |
|           64 |      714 | 2024-07-10 | 9z Academy        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.69 | card, fokiu, jz, stormzyn, t9rnay      |
|           63 |      737 | 2024-07-09 | Case              | L   | 1.000      | -            | -                | -                | -         |   -11.67 | card, fokiu, jz, stormzyn, t9rnay      |
|           62 |      772 | 2024-07-06 | ODDIK             | L   | 1.000      | -            | -                | -                | -         |    -8.15 | card, fokiu, jz, stormzyn, t9rnay      |
|           61 |      804 | 2024-06-27 | Bounty Hunters    | L   | 0.973      | -            | -                | -                | -         |    -9.77 | card, fokiu, jz, stormzyn, t9rnay      |
|           60 |     1024 | 2024-06-10 | ODDIK             | L   | 0.859      | -            | -                | -                | -         |    -8.13 | card, fokiu, jz, stormzyn, t9rnay      |
|           59 |     1066 | 2024-06-09 | Solid             | W   | 0.852      | 0.450        | 0.027 (0.010)    | 0.817 (0.314)    | -         |    16.55 | card, fokiu, jz, stormzyn, t9rnay      |
|           58 |     1114 | 2024-06-08 | ODDIK             | L   | 0.848      | -            | -                | -                | -         |    -8.27 | card, fokiu, jz, stormzyn, t9rnay      |
|           57 |     1123 | 2024-06-08 | Bounty Hunters    | L   | 0.847      | -            | -                | -                | -         |    -8.84 | card, fokiu, jz, stormzyn, t9rnay      |
|           56 |     1206 | 2024-06-07 | Galorys           | W   | 0.838      | 0.450        | 0.030 (0.011)    | 0.553 (0.208)    | -         |    16.10 | card, fokiu, jz, stormzyn, t9rnay      |
|           55 |     1260 | 2024-06-06 | Fluxo             | L   | 0.832      | -            | -                | -                | -         |    -4.26 | card, fokiu, jz, stormzyn, t9rnay      |
|           54 |     1386 | 2024-06-03 | Vikings KR        | W   | 0.815      | 0.371        | -                | 0.458 (0.138)    | -         |    13.76 | card, fokiu, jz, stormzyn, t9rnay      |
|           53 |     1451 | 2024-06-01 | ex-Corinthians    | W   | 0.798      | -            | -                | -                | -         |     5.56 | card, fokiu, jz, stormzyn, t9rnay      |
|           52 |     1494 | 2024-05-30 | Hype              | L   | 0.788      | -            | -                | -                | -         |    -8.86 | card, fokiu, jz, stormzyn, t9rnay      |
|           51 |     1546 | 2024-05-28 | Yawara            | W   | 0.773      | -            | -                | -                | -         |     4.48 | card, fokiu, jz, stormzyn, t9rnay      |
|           50 |     1671 | 2024-05-22 | Solid             | L   | 0.734      | -            | -                | -                | -         |    -8.12 | card, fokiu, jz, stormzyn, t9rnay      |
|           49 |     1674 | 2024-05-22 | Solid             | L   | 0.734      | -            | -                | -                | -         |    -8.62 | card, fokiu, stormzyn, t9rnay, zede    |
|           48 |     1751 | 2024-05-20 | 9z                | L   | 0.721      | -            | -                | -                | -         |    -0.51 | card, fokiu, stormzyn, t9rnay, zede    |
|           47 |     1754 | 2024-05-20 | 9z                | L   | 0.720      | -            | -                | -                | -         |    -0.51 | card, fokiu, stormzyn, t9rnay, zede    |
|           46 |     1874 | 2024-05-16 | Sharks            | L   | 0.694      | -            | -                | -                | -         |    -4.97 | card, fokiu, stormzyn, t9rnay, zede    |
|           45 |     1877 | 2024-05-16 | Sharks            | L   | 0.694      | -            | -                | -                | -         |    -5.19 | card, fokiu, stormzyn, t9rnay, zede    |
|           44 |     1973 | 2024-05-14 | Imperial          | L   | 0.681      | -            | -                | -                | -         |    -1.24 | card, fokiu, stormzyn, t9rnay, zede    |
|           43 |     1976 | 2024-05-14 | Imperial          | L   | 0.681      | -            | -                | -                | -         |    -1.26 | card, fokiu, stormzyn, t9rnay, zede    |
|           42 |     1989 | 2024-05-14 | Hype              | L   | 0.680      | -            | -                | -                | -         |    -8.53 | card, fokiu, stormzyn, t9rnay, zede    |
|           41 |     2022 | 2024-05-13 | Sharks            | L   | 0.672      | -            | -                | -                | -         |    -5.98 | fokiu, saadzin, stormzyn, t9rnay, zede |
|           40 |     2070 | 2024-05-11 | Sharks            | L   | 0.659      | -            | -                | -                | -         |    -6.16 | card, fokiu, stormzyn, t9rnay, zede    |
|           39 |     2121 | 2024-05-09 | KRÜ               | L   | 0.645      | -            | -                | -                | -         |    -8.04 | fokiu, saadzin, stormzyn, t9rnay, zede |
|           38 |     2154 | 2024-05-07 | paiN              | L   | 0.633      | -            | -                | -                | -         |    -0.72 | fokiu, saadzin, stormzyn, t9rnay, zede |
|           37 |     2174 | 2024-05-06 | paiN              | L   | 0.626      | -            | -                | -                | -         |    -0.71 | fokiu, jz, saadzin, stormzyn, zede     |
|           36 |     2175 | 2024-05-06 | paiN              | L   | 0.626      | -            | -                | -                | -         |    -0.72 | fokiu, jz, saadzin, stormzyn, zede     |
|           35 |     2197 | 2024-05-05 | Galorys           | W   | 0.618      | 0.435        | 0.030 (0.008)    | 0.553 (0.148)    | -         |    11.78 | fokiu, saadzin, stormzyn, t9rnay, zede |
|           34 |     2382 | 2024-04-26 | ODDIK             | L   | 0.560      | -            | -                | -                | -         |    -5.38 | fokiu, saadzin, stormzyn, t9rnay, zede |
|           33 |     2383 | 2024-04-26 | ODDIK             | L   | 0.560      | -            | -                | -                | -         |    -5.61 | fokiu, saadzin, stormzyn, t9rnay, zede |
|           32 |     2647 | 2024-04-17 | ODDIK             | L   | 0.500      | -            | -                | -                | -         |    -5.42 | fokiu, saadzin, stormzyn, t9rnay, zede |
|           31 |     2683 | 2024-04-16 | Sharks            | W   | 0.494      | -            | -                | -                | -         |     6.54 | fokiu, saadzin, stormzyn, t9rnay, zede |
|           30 |     2750 | 2024-04-12 | RED Canids        | L   | 0.466      | -            | -                | -                | -         |    -2.69 | fokiu, saadzin, stormzyn, t9rnay, zede |
|           29 |     2859 | 2024-04-09 | RED Canids        | L   | 0.447      | -            | -                | -                | -         |    -2.65 | fokiu, jz, saadzin, stormzyn, zede     |
|           28 |     2864 | 2024-04-09 | RED Canids        | L   | 0.447      | -            | -                | -                | -         |    -2.72 | fokiu, jz, saadzin, stormzyn, zede     |
|           27 |     2897 | 2024-04-08 | MIBR              | L   | 0.441      | -            | -                | -                | -         |    -0.52 | fokiu, jz, saadzin, stormzyn, zede     |
|           26 |     2953 | 2024-04-06 | RED Canids        | W   | 0.426      | 0.435        | 0.079 (0.015)    | 0.738 (0.137)    | -         |    10.96 | fokiu, jz, saadzin, stormzyn, zede     |
|           25 |     3170 | 2024-03-27 | BESTIA            | W   | 0.361      | 0.450        | 0.095 (0.015)    | -                | -         |     8.44 | fokiu, jz, saadzin, stormzyn, zede     |
|           24 |     3174 | 2024-03-27 | BESTIA            | L   | 0.361      | -            | -                | -                | -         |    -2.95 | fokiu, jz, saadzin, stormzyn, zede     |
|           23 |     3407 | 2024-03-14 | Galorys           | L   | 0.274      | -            | -                | -                | -         |    -3.63 | fokiu, jz, saadzin, stormzyn, zede     |
|           22 |     3409 | 2024-03-14 | Galorys           | L   | 0.274      | -            | -                | -                | -         |    -3.72 | fokiu, jz, saadzin, stormzyn, zede     |
|           21 |     3504 | 2024-03-11 | Solid             | L   | 0.253      | -            | -                | -                | -         |    -3.37 | fokiu, jz, saadzin, stormzyn, zede     |
|           20 |     3539 | 2024-03-09 | RED Canids        | L   | 0.241      | -            | -                | -                | -         |    -1.53 | fokiu, jz, saadzin, stormzyn, zede     |
|           19 |     3599 | 2024-03-07 | Solid             | W   | 0.226      | -            | -                | -                | -         |     4.17 | fokiu, jz, saadzin, stormzyn, zede     |
|           18 |     3653 | 2024-03-05 | 2GAME             | L   | 0.214      | -            | -                | -                | -         |    -4.72 | fokiu, jz, saadzin, stormzyn, zede     |
|           17 |     3655 | 2024-03-05 | 2GAME             | L   | 0.214      | -            | -                | -                | -         |    -4.79 | fokiu, jz, saadzin, stormzyn, zede     |
|           16 |     3860 | 2024-02-24 | Corinthians       | W   | 0.148      | -            | -                | -                | -         |     0.63 | fokiu, jz, saadzin, stormzyn, zede     |
|           15 |     3867 | 2024-02-24 | Corinthians       | W   | 0.147      | -            | -                | -                | -         |     0.64 | fokiu, jz, saadzin, stormzyn, zede     |
|           14 |     3920 | 2024-02-21 | Fluxo             | W   | 0.128      | -            | -                | -                | -         |     3.07 | fokiu, jz, saadzin, stormzyn, zede     |
|           13 |     3925 | 2024-02-21 | Fluxo             | L   | 0.127      | -            | -                | -                | -         |    -0.96 | fokiu, jz, saadzin, stormzyn, zede     |
|           12 |     3930 | 2024-02-21 | BESTIA            | L   | 0.126      | -            | -                | -                | -         |    -1.05 | fokiu, jz, saadzin, stormzyn, zede     |
|           11 |     3959 | 2024-02-20 | Case              | L   | 0.120      | -            | -                | -                | -         |    -1.35 | fokiu, jz, saadzin, stormzyn, zede     |
|           10 |     4024 | 2024-02-17 | Sharks            | W   | 0.101      | -            | -                | -                | -         |     2.13 | fokiu, jz, saadzin, stormzyn, zede     |
|            9 |     4055 | 2024-02-16 | Solid             | L   | 0.093      | -            | -                | -                | -         |    -1.24 | fokiu, jz, saadzin, stormzyn, zede     |
|            8 |     4064 | 2024-02-16 | Sharks            | L   | 0.092      | -            | -                | -                | -         |    -0.95 | fokiu, jz, saadzin, stormzyn, zede     |
|            7 |     4083 | 2024-02-15 | Fluxo             | L   | 0.087      | -            | -                | -                | -         |    -0.67 | fokiu, jz, saadzin, stormzyn, zede     |
|            6 |     4113 | 2024-02-14 | Hawks             | W   | 0.081      | -            | -                | -                | -         |     0.39 | fokiu, jz, saadzin, stormzyn, zede     |
|            5 |     4153 | 2024-02-13 | Case              | L   | 0.074      | -            | -                | -                | -         |    -0.85 | fokiu, jz, saadzin, stormzyn, zede     |
|            4 |     4158 | 2024-02-13 | Case              | W   | 0.074      | -            | -                | -                | -         |     1.50 | fokiu, jz, saadzin, stormzyn, zede     |
|            3 |     4164 | 2024-02-13 | Corinthians       | W   | 0.072      | -            | -                | -                | -         |     0.31 | fokiu, jz, saadzin, stormzyn, zede     |
|            2 |     4175 | 2024-02-12 | Corinthians       | W   | 0.066      | -            | -                | -                | -         |     0.28 | fokiu, jz, saadzin, stormzyn, zede     |
|            1 |     4277 | 2024-02-03 | 9z                | L   | 0.008      | -            | -                | -                | -         |    -0.00 | fokiu, jz, saadzin, stormzyn, zede     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,256.02)
- Divide that value by the 5th highest value among all rosters ($331,608.80)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-22 |      1.000 | $1,000.00      | $1,000.00       |
| 2024-07-14 |      1.000 | $1,000.00      | $1,000.00       |
| 2024-06-09 |      0.853 | $300.00        | $256.02         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
