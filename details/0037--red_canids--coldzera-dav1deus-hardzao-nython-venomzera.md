### Roster Details<br />
Team Name: RED Canids<br />
Roster: coldzera, dav1deuS, hardzao, nython, venomzera<br />
Global Rank: [37](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [9]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1158.3<br />
<br />
Final Rank Value (1158.3) = Starting Rank Value (1077.7) + Head To Head Adjustments (80.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.473[<sup>1</sup>](#table2)
- Bounty Collected: 0.482[<sup>2</sup>](#table1)
- Opponent Network: 0.253[<sup>2</sup>](#table1)
- LAN Wins: 0.117[<sup>2</sup>](#table1)

The average of these factors is 0.332<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1077.7
- 400 + ( ( 0.332 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 1077.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent        | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                         |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           86 |      226 | 2024-07-28 | MIBR            | L   | 1.000      | -            | -                | -                | -         |    -7.40 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           85 |      231 | 2024-07-28 | paiN            | L   | 1.000      | -            | -                | -                | -         |    -8.04 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           84 |      286 | 2024-07-26 | ODDIK           | L   | 1.000      | -            | -                | -                | -         |   -22.53 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           83 |      353 | 2024-07-24 | Fluxo           | W   | 1.000      | -            | -                | -                | 0 (0.000) |    15.47 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           82 |      355 | 2024-07-24 | ODDIK           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.66 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           81 |      387 | 2024-07-23 | KRÜ             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.05 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           80 |      390 | 2024-07-23 | LaChampionsLiga | W   | 1.000      | -            | -                | -                | 0 (0.000) |     0.41 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           79 |      428 | 2024-07-22 | paiN Academy    | W   | 1.000      | -            | -                | -                | 0 (0.000) |     0.41 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           78 |      451 | 2024-07-21 | BESTIA          | L   | 1.000      | -            | -                | -                | -         |   -23.62 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           77 |      482 | 2024-07-20 | Case            | W   | 1.000      | 0.384        | -                | 0.805 (0.309)    | 0 (0.000) |     5.27 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           76 |      517 | 2024-07-19 | Intense         | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.32 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           75 |      622 | 2024-07-17 | Hype            | W   | 1.000      | 0.450        | -                | 0.488 (0.220)    | 0 (0.000) |     5.32 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           74 |      627 | 2024-07-17 | Hype            | W   | 1.000      | 0.450        | -                | 0.488 (0.220)    | -         |     5.60 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           73 |      682 | 2024-07-16 | Sharks          | W   | 1.000      | 0.450        | -                | 0.565 (0.254)    | -         |     7.81 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           72 |      688 | 2024-07-16 | Sharks          | W   | 1.000      | 0.450        | -                | 0.565 (0.254)    | -         |     8.35 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           71 |      780 | 2024-07-13 | Legacy          | L   | 1.000      | -            | -                | -                | -         |   -19.43 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           70 |      809 | 2024-07-11 | KRÜ             | W   | 1.000      | -            | -                | -                | -         |     5.23 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           69 |      844 | 2024-07-09 | Bounty Hunters  | W   | 1.000      | -            | -                | -                | -         |     7.66 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           68 |      867 | 2024-07-08 | SPORT           | W   | 1.000      | -            | -                | -                | -         |     2.44 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           67 |      983 | 2024-06-15 | fnatic          | L   | 0.870      | -            | -                | -                | -         |    -4.58 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           66 |     1016 | 2024-06-14 | KOI             | L   | 0.865      | -            | -                | -                | -         |   -16.51 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           65 |     1022 | 2024-06-14 | fnatic          | W   | 0.863      | 0.548        | 0.371 (0.175)    | 0.708 (0.335)    | 1 (0.863) |    22.61 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           64 |     1170 | 2024-06-09 | BESTIA          | L   | 0.831      | -            | -                | -                | -         |   -17.70 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           63 |     1175 | 2024-06-09 | Imperial        | L   | 0.830      | -            | -                | -                | -         |    -8.72 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           62 |     1308 | 2024-06-07 | Intense         | W   | 0.815      | -            | -                | -                | -         |     2.35 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           61 |     1348 | 2024-06-06 | Imperial        | W   | 0.810      | 0.450        | 0.237 (0.086)    | 0.685 (0.250)    | -         |    16.70 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           60 |     1419 | 2024-06-05 | 9z              | W   | 0.803      | 0.450        | 0.406 (0.147)    | 0.619 (0.224)    | -         |    21.69 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           59 |     1833 | 2024-05-21 | Sharks          | L   | 0.703      | -            | -                | -                | -         |   -15.46 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           58 |     1835 | 2024-05-21 | Sharks          | W   | 0.703      | -            | -                | -                | -         |     6.64 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           57 |     1866 | 2024-05-20 | Fluxo           | L   | 0.697      | -            | -                | -                | -         |   -12.76 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           56 |     1869 | 2024-05-20 | Fluxo           | W   | 0.697      | 0.450        | 0.124 (0.039)    | 0.723 (0.227)    | -         |     9.29 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           55 |     1902 | 2024-05-19 | 9z              | W   | 0.689      | 0.371        | 0.406 (0.104)    | -                | -         |    18.91 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           54 |     1923 | 2024-05-18 | ODDIK           | W   | 0.683      | 0.371        | 0.098 (0.025)    | -                | -         |     6.11 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           53 |     1995 | 2024-05-16 | Fluxo           | W   | 0.670      | 0.371        | 0.124 (0.031)    | -                | -         |    10.15 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           52 |     2037 | 2024-05-15 | 9z              | L   | 0.664      | -            | -                | -                | -         |    -2.22 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           51 |     2039 | 2024-05-15 | 9z              | W   | 0.664      | 0.450        | 0.406 (0.121)    | -                | -         |    18.94 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           50 |     2096 | 2024-05-14 | Corinthians     | W   | 0.657      | -            | -                | -                | -         |     0.72 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           49 |     2101 | 2024-05-14 | Corinthians     | W   | 0.657      | -            | -                | -                | -         |     0.73 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           48 |     2114 | 2024-05-14 | BESTIA          | W   | 0.655      | 0.371        | 0.095 (0.023)    | -                | -         |     7.00 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           47 |     2132 | 2024-05-13 | Sharks          | L   | 0.650      | -            | -                | -                | -         |   -13.30 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           46 |     2152 | 2024-05-12 | Vikings KR      | W   | 0.644      | -            | -                | -                | -         |     3.54 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           45 |     2160 | 2024-05-12 | FURIA Academy   | W   | 0.642      | -            | -                | -                | -         |     0.76 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           44 |     2216 | 2024-05-10 | paiN            | L   | 0.628      | -            | -                | -                | -         |    -3.47 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           43 |     2232 | 2024-05-09 | Intense         | W   | 0.623      | -            | -                | -                | -         |     2.39 | dav1deuS, destiny, hardzao, nython, venomzera  |
|           42 |     2250 | 2024-05-08 | paiN            | L   | 0.617      | -            | -                | -                | -         |    -3.26 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           41 |     2252 | 2024-05-08 | paiN            | W   | 0.617      | 0.450        | 0.327 (0.091)    | 0.866 (0.240)    | -         |    16.48 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           40 |     2253 | 2024-05-08 | Solid           | L   | 0.616      | -            | -                | -                | -         |   -14.87 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           39 |     2296 | 2024-05-06 | Intense         | W   | 0.601      | -            | -                | -                | -         |     2.29 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           38 |     2528 | 2024-04-25 | BESTIA          | W   | 0.530      | -            | -                | -                | -         |     5.02 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           37 |     2530 | 2024-04-25 | BESTIA          | W   | 0.530      | -            | -                | -                | -         |     5.22 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           36 |     2757 | 2024-04-17 | MIBR            | L   | 0.477      | -            | -                | -                | -         |    -1.92 | dav1deuS, hardzao, nython, righi, venomzera    |
|           35 |     2765 | 2024-04-17 | O PLANO         | W   | 0.476      | -            | -                | -                | -         |     0.64 | dav1deuS, hardzao, nython, righi, venomzera    |
|           34 |     2798 | 2024-04-16 | LaChampionsLiga | W   | 0.471      | -            | -                | -                | -         |     0.30 | dav1deuS, hardzao, nython, righi, venomzera    |
|           33 |     2848 | 2024-04-13 | Imperial        | L   | 0.450      | -            | -                | -                | -         |    -3.73 | dav1deuS, hardzao, nython, righi, venomzera    |
|           32 |     2867 | 2024-04-12 | W7M             | W   | 0.442      | -            | -                | -                | -         |     2.65 | dav1deuS, hardzao, nython, righi, venomzera    |
|           31 |     2923 | 2024-04-10 | 2GAME           | W   | 0.430      | -            | -                | -                | -         |     1.17 | dav1deuS, hardzao, nython, righi, venomzera    |
|           30 |     2926 | 2024-04-10 | 2GAME           | W   | 0.430      | -            | -                | -                | -         |     1.18 | dav1deuS, hardzao, nython, righi, venomzera    |
|           29 |     2929 | 2024-04-10 | paiN            | L   | 0.429      | -            | -                | -                | -         |    -1.93 | dav1deuS, hardzao, nython, righi, venomzera    |
|           28 |     2976 | 2024-04-09 | W7M             | W   | 0.424      | -            | -                | -                | -         |     2.61 | dav1deuS, hardzao, nython, righi, venomzera    |
|           27 |     2981 | 2024-04-09 | W7M             | W   | 0.423      | -            | -                | -                | -         |     2.67 | dav1deuS, hardzao, nython, righi, venomzera    |
|           26 |     2984 | 2024-04-09 | MIBR            | L   | 0.422      | -            | -                | -                | -         |    -1.86 | dav1deuS, hardzao, nython, righi, venomzera    |
|           25 |     3015 | 2024-04-08 | BESTIA          | W   | 0.417      | -            | -                | -                | -         |     4.70 | dav1deuS, hardzao, nython, righi, venomzera    |
|           24 |     3021 | 2024-04-08 | Bounty Hunters  | W   | 0.415      | -            | -                | -                | -         |     3.45 | dav1deuS, hardzao, nython, righi, venomzera    |
|           23 |     3051 | 2024-04-07 | Imperial        | L   | 0.410      | -            | -                | -                | -         |    -3.23 | dav1deuS, hardzao, nython, righi, venomzera    |
|           22 |     3070 | 2024-04-06 | W7M             | L   | 0.402      | -            | -                | -                | -         |   -10.26 | dav1deuS, hardzao, nython, righi, venomzera    |
|           21 |     3109 | 2024-04-04 | Case            | L   | 0.390      | -            | -                | -                | -         |    -9.16 | dav1deuS, hardzao, nython, righi, venomzera    |
|           20 |     3114 | 2024-04-04 | Case            | W   | 0.390      | -            | -                | -                | -         |     3.15 | dav1deuS, hardzao, nython, righi, venomzera    |
|           19 |     3130 | 2024-04-04 | Fluxo           | W   | 0.388      | -            | -                | -                | -         |     5.41 | dav1deuS, hardzao, nython, righi, venomzera    |
|           18 |     3150 | 2024-04-03 | ODDIK           | W   | 0.384      | -            | -                | -                | -         |     4.26 | dav1deuS, hardzao, nython, righi, venomzera    |
|           17 |     3153 | 2024-04-03 | ODDIK           | W   | 0.383      | -            | -                | -                | -         |     4.39 | dav1deuS, hardzao, nython, righi, venomzera    |
|           16 |     3438 | 2024-03-18 | ODDIK           | W   | 0.276      | -            | -                | -                | -         |     3.26 | dav1deuS, destiny, hardzao, nython, venomzera  |
|           15 |     3481 | 2024-03-16 | ODDIK           | W   | 0.263      | -            | -                | -                | -         |     3.14 | dav1deuS, destiny, hardzao, nython, venomzera  |
|           14 |     3498 | 2024-03-15 | Case            | W   | 0.256      | -            | -                | -                | -         |     2.36 | dav1deuS, destiny, hardzao, nython, venomzera  |
|           13 |     3530 | 2024-03-14 | Solid           | L   | 0.249      | -            | -                | -                | -         |    -5.82 | dav1deuS, destiny, hardzao, nython, venomzera  |
|           12 |     3539 | 2024-03-14 | Flamengo        | W   | 0.248      | -            | -                | -                | -         |     0.28 | dav1deuS, destiny, hardzao, nython, venomzera  |
|           11 |     3558 | 2024-03-13 | Case            | W   | 0.243      | -            | -                | -                | -         |     2.23 | dav1deuS, destiny, hardzao, nython, venomzera  |
|           10 |     3570 | 2024-03-13 | Galorys         | W   | 0.242      | -            | -                | -                | -         |     1.95 | dav1deuS, destiny, hardzao, nython, venomzera  |
|            9 |     3602 | 2024-03-12 | BESTIA          | W   | 0.235      | -            | -                | -                | -         |     3.05 | dav1deuS, destiny, hardzao, nython, venomzera  |
|            8 |     3620 | 2024-03-11 | Corinthians     | W   | 0.229      | -            | -                | -                | -         |     0.29 | dav1deuS, destiny, hardzao, nython, venomzera  |
|            7 |     3656 | 2024-03-09 | W7M             | W   | 0.217      | -            | -                | -                | -         |     1.43 | dav1deuS, destiny, hardzao, nython, venomzera  |
|            6 |     3703 | 2024-03-07 | VELOX           | W   | 0.204      | -            | -                | -                | -         |     0.14 | dav1deuS, destiny, hardzao, nython, venomzera  |
|            5 |     3821 | 2024-03-03 | ODDIK           | L   | 0.176      | -            | -                | -                | -         |    -3.38 | dav1deuS, destiny, hardzao, nython, venomzera  |
|            4 |     3853 | 2024-03-02 | paiN            | L   | 0.168      | -            | -                | -                | -         |    -0.72 | dav1deuS, destiny, hardzao, nython, venomzera  |
|            3 |     3868 | 2024-03-01 | Wildcard        | W   | 0.163      | -            | -                | -                | 1 (0.163) |     1.44 | dav1deuS, destiny, hardzao, nython, venomzera  |
|            2 |     4269 | 2024-02-13 | Imperial        | L   | 0.051      | -            | -                | -                | -         |    -0.41 | dav1deuS, destiny, hardzao, nython, venomzera  |
|            1 |     4272 | 2024-02-13 | Imperial        | W   | 0.050      | -            | -                | -                | -         |     1.18 | dav1deuS, destiny, hardzao, nython, venomzera  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($25,080.03)
- Divide that value by the 5th highest value among all rosters ($324,557.31)
- The final value (0.08) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-14 |      1.000 | $2,000.00      | $2,000.00       |
| 2024-06-16 |      0.877 | $1,500.00      | $1,315.69       |
| 2024-06-10 |      0.837 | $750.00        | $627.62         |
| 2024-06-09 |      0.830 | $11,500.00     | $9,540.74       |
| 2024-05-19 |      0.689 | $10,000.00     | $6,888.89       |
| 2024-03-18 |      0.276 | $3,500.00      | $965.42         |
| 2024-03-14 |      0.249 | $15,000.00     | $3,741.67       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
