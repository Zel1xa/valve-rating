### Roster Details<br />
Team Name: W7M<br />
Roster: card, fokiu, jz, stormzyn, t9rnay<br />
Global Rank: [117](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [29]( ../standings_americas.md)<br />
<br />
Final Rank Value:  811.6<br />
<br />
Final Rank Value (811.6) = Starting Rank Value (841.0) + Head To Head Adjustments (-29.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.316[<sup>1</sup>](#table2)
- Bounty Collected: 0.346[<sup>2</sup>](#table1)
- Opponent Network: 0.200[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.216<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 841.0
- 400 + ( ( 0.216 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 841.0


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
|           80 |      242 | 2024-07-27 | Bad News Chickens | L   | 1.000      | -            | -                | -                | -         |   -25.93 | card, fokiu, jz, stormzyn, t9rnay      |
|           79 |      257 | 2024-07-26 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |    -4.94 | card, fokiu, jz, stormzyn, t9rnay      |
|           78 |      286 | 2024-07-25 | ODDIK             | W   | 1.000      | 0.143        | 0.098 (0.014)    | -                | 0 (0.000) |    22.15 | card, fokiu, jz, stormzyn, t9rnay      |
|           77 |      293 | 2024-07-25 | Bounty Hunters    | W   | 1.000      | -            | -                | -                | 0 (0.000) |    22.20 | card, fokiu, jz, stormzyn, t9rnay      |
|           76 |      333 | 2024-07-24 | Yawara            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.03 | card, fokiu, jz, stormzyn, t9rnay      |
|           75 |      338 | 2024-07-24 | Bad News Chickens | L   | 1.000      | -            | -                | -                | -         |   -26.00 | card, fokiu, jz, stormzyn, t9rnay      |
|           74 |      362 | 2024-07-23 | Sharks            | L   | 1.000      | -            | -                | -                | -         |    -9.40 | card, fokiu, jz, stormzyn, t9rnay      |
|           73 |      423 | 2024-07-21 | Hype              | L   | 1.000      | -            | -                | -                | -         |   -14.19 | card, fokiu, jz, stormzyn, t9rnay      |
|           72 |      458 | 2024-07-20 | KRÜ               | W   | 1.000      | 0.333        | 0.023 (0.008)    | 0.466 (0.155)    | 0 (0.000) |    16.51 | card, fokiu, jz, stormzyn, t9rnay      |
|           71 |      493 | 2024-07-19 | BESTIA            | W   | 1.000      | 0.333        | 0.091 (0.030)    | 0.756 (0.252)    | 0 (0.000) |    21.54 | card, fokiu, jz, stormzyn, t9rnay      |
|           70 |      604 | 2024-07-17 | SPORT             | W   | 1.000      | -            | -                | -                | 0 (0.000) |    12.04 | card, fokiu, jz, stormzyn, t9rnay      |
|           69 |      620 | 2024-07-17 | paiN              | L   | 1.000      | -            | -                | -                | -         |    -1.59 | card, fokiu, jz, stormzyn, t9rnay      |
|           68 |      662 | 2024-07-16 | Hype              | L   | 1.000      | -            | -                | -                | -         |   -12.36 | card, fokiu, jz, stormzyn, t9rnay      |
|           67 |      762 | 2024-07-12 | KRÜ               | L   | 1.000      | -            | -                | -                | -         |   -12.21 | card, fokiu, jz, stormzyn, t9rnay      |
|           66 |      772 | 2024-07-11 | Case              | W   | 1.000      | 0.371        | 0.029 (0.011)    | 0.750 (0.278)    | 0 (0.000) |    18.59 | card, fokiu, jz, stormzyn, t9rnay      |
|           65 |      778 | 2024-07-11 | Hype              | W   | 1.000      | 0.371        | 0.025 (0.009)    | 0.503 (0.186)    | 0 (0.000) |    19.34 | card, fokiu, jz, stormzyn, t9rnay      |
|           64 |      790 | 2024-07-10 | Vikings KR        | W   | 1.000      | 0.371        | -                | 0.479 (0.177)    | 0 (0.000) |    18.35 | card, fokiu, jz, stormzyn, t9rnay      |
|           63 |      797 | 2024-07-10 | 9z Academy        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.85 | card, fokiu, jz, stormzyn, t9rnay      |
|           62 |      820 | 2024-07-09 | Case              | L   | 1.000      | -            | -                | -                | -         |   -11.17 | card, fokiu, jz, stormzyn, t9rnay      |
|           61 |      855 | 2024-07-06 | ODDIK             | L   | 1.000      | -            | -                | -                | -         |    -8.38 | card, fokiu, jz, stormzyn, t9rnay      |
|           60 |      887 | 2024-06-27 | Bounty Hunters    | L   | 0.954      | -            | -                | -                | -         |    -9.53 | card, fokiu, jz, stormzyn, t9rnay      |
|           59 |     1083 | 2024-06-10 | ODDIK             | L   | 0.840      | -            | -                | -                | -         |    -8.12 | card, fokiu, jz, stormzyn, t9rnay      |
|           58 |     1124 | 2024-06-09 | Solid             | W   | 0.833      | 0.450        | 0.026 (0.010)    | 0.863 (0.324)    | -         |    16.61 | card, fokiu, jz, stormzyn, t9rnay      |
|           57 |     1172 | 2024-06-08 | ODDIK             | L   | 0.829      | -            | -                | -                | -         |    -8.22 | card, fokiu, jz, stormzyn, t9rnay      |
|           56 |     1179 | 2024-06-08 | Bounty Hunters    | L   | 0.828      | -            | -                | -                | -         |    -8.59 | card, fokiu, jz, stormzyn, t9rnay      |
|           55 |     1259 | 2024-06-07 | Galorys           | W   | 0.819      | 0.450        | 0.030 (0.011)    | 0.571 (0.211)    | -         |    16.07 | card, fokiu, jz, stormzyn, t9rnay      |
|           54 |     1313 | 2024-06-06 | Fluxo             | L   | 0.813      | -            | -                | -                | -         |    -4.47 | card, fokiu, jz, stormzyn, t9rnay      |
|           53 |     1438 | 2024-06-03 | Vikings KR        | W   | 0.796      | 0.371        | -                | 0.479 (0.141)    | -         |    13.57 | card, fokiu, jz, stormzyn, t9rnay      |
|           52 |     1501 | 2024-06-01 | ex-Corinthians    | W   | 0.779      | -            | -                | -                | -         |     5.58 | card, fokiu, jz, stormzyn, t9rnay      |
|           51 |     1544 | 2024-05-30 | Hype              | L   | 0.769      | -            | -                | -                | -         |    -8.54 | card, fokiu, jz, stormzyn, t9rnay      |
|           50 |     1596 | 2024-05-28 | Yawara            | W   | 0.754      | -            | -                | -                | -         |     4.50 | card, fokiu, jz, stormzyn, t9rnay      |
|           49 |     1720 | 2024-05-22 | Solid             | L   | 0.715      | -            | -                | -                | -         |    -7.76 | card, fokiu, jz, stormzyn, t9rnay      |
|           48 |     1723 | 2024-05-22 | Solid             | L   | 0.715      | -            | -                | -                | -         |    -8.22 | card, fokiu, stormzyn, t9rnay, zede    |
|           47 |     1800 | 2024-05-20 | 9z                | L   | 0.702      | -            | -                | -                | -         |    -1.91 | card, fokiu, stormzyn, t9rnay, zede    |
|           46 |     1803 | 2024-05-20 | 9z                | L   | 0.701      | -            | -                | -                | -         |    -1.95 | card, fokiu, stormzyn, t9rnay, zede    |
|           45 |     1922 | 2024-05-16 | Sharks            | L   | 0.675      | -            | -                | -                | -         |    -4.95 | card, fokiu, stormzyn, t9rnay, zede    |
|           44 |     1925 | 2024-05-16 | Sharks            | L   | 0.675      | -            | -                | -                | -         |    -5.16 | card, fokiu, stormzyn, t9rnay, zede    |
|           43 |     2021 | 2024-05-14 | Imperial          | L   | 0.662      | -            | -                | -                | -         |    -1.51 | card, fokiu, stormzyn, t9rnay, zede    |
|           42 |     2024 | 2024-05-14 | Imperial          | L   | 0.662      | -            | -                | -                | -         |    -1.53 | card, fokiu, stormzyn, t9rnay, zede    |
|           41 |     2037 | 2024-05-14 | Hype              | L   | 0.661      | -            | -                | -                | -         |    -8.23 | card, fokiu, stormzyn, t9rnay, zede    |
|           40 |     2070 | 2024-05-13 | Sharks            | L   | 0.653      | -            | -                | -                | -         |    -5.82 | fokiu, saadzin, stormzyn, t9rnay, zede |
|           39 |     2118 | 2024-05-11 | Sharks            | L   | 0.640      | -            | -                | -                | -         |    -5.98 | card, fokiu, stormzyn, t9rnay, zede    |
|           38 |     2169 | 2024-05-09 | KRÜ               | L   | 0.626      | -            | -                | -                | -         |    -7.43 | fokiu, saadzin, stormzyn, t9rnay, zede |
|           37 |     2201 | 2024-05-07 | paiN              | L   | 0.614      | -            | -                | -                | -         |    -0.89 | fokiu, saadzin, stormzyn, t9rnay, zede |
|           36 |     2221 | 2024-05-06 | paiN              | L   | 0.607      | -            | -                | -                | -         |    -0.89 | fokiu, jz, saadzin, stormzyn, zede     |
|           35 |     2222 | 2024-05-06 | paiN              | L   | 0.607      | -            | -                | -                | -         |    -0.90 | fokiu, jz, saadzin, stormzyn, zede     |
|           34 |     2244 | 2024-05-05 | Galorys           | W   | 0.599      | 0.435        | 0.030 (0.008)    | 0.571 (0.149)    | -         |    11.35 | fokiu, saadzin, stormzyn, t9rnay, zede |
|           33 |     2429 | 2024-04-26 | ODDIK             | L   | 0.541      | -            | -                | -                | -         |    -5.29 | fokiu, saadzin, stormzyn, t9rnay, zede |
|           32 |     2430 | 2024-04-26 | ODDIK             | L   | 0.541      | -            | -                | -                | -         |    -5.51 | fokiu, saadzin, stormzyn, t9rnay, zede |
|           31 |     2693 | 2024-04-17 | ODDIK             | L   | 0.481      | -            | -                | -                | -         |    -5.27 | fokiu, saadzin, stormzyn, t9rnay, zede |
|           30 |     2729 | 2024-04-16 | Sharks            | W   | 0.475      | -            | -                | -                | -         |     6.30 | fokiu, saadzin, stormzyn, t9rnay, zede |
|           29 |     2796 | 2024-04-12 | RED Canids        | L   | 0.447      | -            | -                | -                | -         |    -3.49 | fokiu, saadzin, stormzyn, t9rnay, zede |
|           28 |     2905 | 2024-04-09 | RED Canids        | L   | 0.428      | -            | -                | -                | -         |    -3.48 | fokiu, jz, saadzin, stormzyn, zede     |
|           27 |     2910 | 2024-04-09 | RED Canids        | L   | 0.428      | -            | -                | -                | -         |    -3.58 | fokiu, jz, saadzin, stormzyn, zede     |
|           26 |     2943 | 2024-04-08 | MIBR              | L   | 0.422      | -            | -                | -                | -         |    -0.50 | fokiu, jz, saadzin, stormzyn, zede     |
|           25 |     2999 | 2024-04-06 | RED Canids        | W   | 0.407      | 0.435        | 0.073 (0.013)    | 0.733 (0.130)    | -         |     9.51 | fokiu, jz, saadzin, stormzyn, zede     |
|           24 |     3216 | 2024-03-27 | BESTIA            | W   | 0.342      | 0.450        | 0.091 (0.014)    | -                | -         |     7.88 | fokiu, jz, saadzin, stormzyn, zede     |
|           23 |     3219 | 2024-03-27 | BESTIA            | L   | 0.342      | -            | -                | -                | -         |    -2.91 | fokiu, jz, saadzin, stormzyn, zede     |
|           22 |     3447 | 2024-03-14 | Galorys           | L   | 0.255      | -            | -                | -                | -         |    -3.46 | fokiu, jz, saadzin, stormzyn, zede     |
|           21 |     3449 | 2024-03-14 | Galorys           | L   | 0.255      | -            | -                | -                | -         |    -3.53 | fokiu, jz, saadzin, stormzyn, zede     |
|           20 |     3542 | 2024-03-11 | Solid             | L   | 0.234      | -            | -                | -                | -         |    -3.12 | fokiu, jz, saadzin, stormzyn, zede     |
|           19 |     3577 | 2024-03-09 | RED Canids        | L   | 0.222      | -            | -                | -                | -         |    -2.08 | fokiu, jz, saadzin, stormzyn, zede     |
|           18 |     3637 | 2024-03-07 | Solid             | W   | 0.207      | -            | -                | -                | -         |     3.81 | fokiu, jz, saadzin, stormzyn, zede     |
|           17 |     3691 | 2024-03-05 | 2GAME             | L   | 0.195      | -            | -                | -                | -         |    -4.33 | fokiu, jz, saadzin, stormzyn, zede     |
|           16 |     3693 | 2024-03-05 | 2GAME             | L   | 0.195      | -            | -                | -                | -         |    -4.38 | fokiu, jz, saadzin, stormzyn, zede     |
|           15 |     3898 | 2024-02-24 | Corinthians       | W   | 0.129      | -            | -                | -                | -         |     0.54 | fokiu, jz, saadzin, stormzyn, zede     |
|           14 |     3905 | 2024-02-24 | Corinthians       | W   | 0.128      | -            | -                | -                | -         |     0.55 | fokiu, jz, saadzin, stormzyn, zede     |
|           13 |     3958 | 2024-02-21 | Fluxo             | W   | 0.109      | -            | -                | -                | -         |     2.61 | fokiu, jz, saadzin, stormzyn, zede     |
|           12 |     3963 | 2024-02-21 | Fluxo             | L   | 0.108      | -            | -                | -                | -         |    -0.81 | fokiu, jz, saadzin, stormzyn, zede     |
|           11 |     3968 | 2024-02-21 | BESTIA            | L   | 0.107      | -            | -                | -                | -         |    -0.92 | fokiu, jz, saadzin, stormzyn, zede     |
|           10 |     3997 | 2024-02-20 | Case              | L   | 0.101      | -            | -                | -                | -         |    -1.14 | fokiu, jz, saadzin, stormzyn, zede     |
|            9 |     4061 | 2024-02-17 | Sharks            | W   | 0.082      | -            | -                | -                | -         |     1.73 | fokiu, jz, saadzin, stormzyn, zede     |
|            8 |     4092 | 2024-02-16 | Solid             | L   | 0.074      | -            | -                | -                | -         |    -0.99 | fokiu, jz, saadzin, stormzyn, zede     |
|            7 |     4101 | 2024-02-16 | Sharks            | L   | 0.073      | -            | -                | -                | -         |    -0.75 | fokiu, jz, saadzin, stormzyn, zede     |
|            6 |     4120 | 2024-02-15 | Fluxo             | L   | 0.068      | -            | -                | -                | -         |    -0.52 | fokiu, jz, saadzin, stormzyn, zede     |
|            5 |     4150 | 2024-02-14 | Hawks             | W   | 0.062      | -            | -                | -                | -         |     0.30 | fokiu, jz, saadzin, stormzyn, zede     |
|            4 |     4190 | 2024-02-13 | Case              | L   | 0.055      | -            | -                | -                | -         |    -0.63 | fokiu, jz, saadzin, stormzyn, zede     |
|            3 |     4195 | 2024-02-13 | Case              | W   | 0.055      | -            | -                | -                | -         |     1.12 | fokiu, jz, saadzin, stormzyn, zede     |
|            2 |     4201 | 2024-02-13 | Corinthians       | W   | 0.053      | -            | -                | -                | -         |     0.23 | fokiu, jz, saadzin, stormzyn, zede     |
|            1 |     4212 | 2024-02-12 | Corinthians       | W   | 0.047      | -            | -                | -                | -         |     0.20 | fokiu, jz, saadzin, stormzyn, zede     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,250.32)
- Divide that value by the 5th highest value among all rosters ($325,971.18)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-22 |      1.000 | $1,000.00      | $1,000.00       |
| 2024-07-13 |      1.000 | $1,000.00      | $1,000.00       |
| 2024-06-09 |      0.834 | $300.00        | $250.32         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
