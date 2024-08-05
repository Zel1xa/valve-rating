### Roster Details<br />
Team Name: RED Canids<br />
Roster: coldzera, dav1deuS, HEN1, nython, venomzera<br />
Global Rank: [39](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [9]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1144.4<br />
<br />
Final Rank Value (1144.4) = Starting Rank Value (1077.2) + Head To Head Adjustments (67.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.473[<sup>1</sup>](#table2)
- Bounty Collected: 0.481[<sup>2</sup>](#table1)
- Opponent Network: 0.253[<sup>2</sup>](#table1)
- LAN Wins: 0.117[<sup>2</sup>](#table1)

The average of these factors is 0.331<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1077.2
- 400 + ( ( 0.331 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 1077.2


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
|           88 |       27 | 2024-08-03 | ODDIK           | L   | 1.000      | -            | -                | -                | -         |   -18.25 | coldzera, dav1deuS, HEN1, nython, venomzera    |
|           87 |       34 | 2024-08-03 | Vikings KR      | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.71 | coldzera, dav1deuS, HEN1, nython, venomzera    |
|           86 |      262 | 2024-07-28 | MIBR            | L   | 1.000      | -            | -                | -                | -         |    -7.39 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           85 |      267 | 2024-07-28 | paiN            | L   | 1.000      | -            | -                | -                | -         |    -8.04 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           84 |      322 | 2024-07-26 | ODDIK           | L   | 1.000      | -            | -                | -                | -         |   -22.51 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           83 |      389 | 2024-07-24 | Fluxo           | W   | 1.000      | -            | -                | -                | 0 (0.000) |    15.47 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           82 |      391 | 2024-07-24 | ODDIK           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.67 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           81 |      423 | 2024-07-23 | KRÜ             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.07 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           80 |      426 | 2024-07-23 | LaChampionsLiga | W   | 1.000      | -            | -                | -                | 0 (0.000) |     0.41 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           79 |      464 | 2024-07-22 | paiN Academy    | W   | 1.000      | -            | -                | -                | 0 (0.000) |     0.41 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           78 |      487 | 2024-07-21 | BESTIA          | L   | 1.000      | -            | -                | -                | -         |   -23.61 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           77 |      518 | 2024-07-20 | Case            | W   | 1.000      | 0.384        | -                | 0.806 (0.310)    | 0 (0.000) |     5.29 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           76 |      553 | 2024-07-19 | Intense         | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.33 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           75 |      658 | 2024-07-17 | Hype            | W   | 1.000      | 0.450        | -                | 0.490 (0.221)    | -         |     5.34 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           74 |      663 | 2024-07-17 | Hype            | W   | 1.000      | 0.450        | -                | 0.490 (0.221)    | -         |     5.62 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           73 |      718 | 2024-07-16 | Sharks          | W   | 1.000      | 0.450        | -                | 0.566 (0.255)    | -         |     7.82 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           72 |      724 | 2024-07-16 | Sharks          | W   | 1.000      | 0.450        | -                | 0.566 (0.255)    | -         |     8.37 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           71 |      816 | 2024-07-13 | Legacy          | L   | 1.000      | -            | -                | -                | -         |   -19.41 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           70 |      845 | 2024-07-11 | KRÜ             | W   | 1.000      | -            | -                | -                | -         |     5.25 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           69 |      880 | 2024-07-09 | Bounty Hunters  | W   | 1.000      | -            | -                | -                | -         |     7.68 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           68 |      903 | 2024-07-08 | SPORT           | W   | 1.000      | -            | -                | -                | -         |     2.45 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           67 |     1019 | 2024-06-15 | fnatic          | L   | 0.866      | -            | -                | -                | -         |    -4.49 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           66 |     1052 | 2024-06-14 | KOI             | L   | 0.860      | -            | -                | -                | -         |   -16.37 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           65 |     1058 | 2024-06-14 | fnatic          | W   | 0.859      | 0.548        | 0.371 (0.175)    | 0.708 (0.333)    | 1 (0.859) |    22.57 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           64 |     1206 | 2024-06-09 | BESTIA          | L   | 0.826      | -            | -                | -                | -         |   -17.59 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           63 |     1211 | 2024-06-09 | Imperial        | L   | 0.825      | -            | -                | -                | -         |    -8.70 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           62 |     1344 | 2024-06-07 | Intense         | W   | 0.811      | -            | -                | -                | -         |     2.35 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           61 |     1384 | 2024-06-06 | Imperial        | W   | 0.806      | 0.450        | 0.236 (0.085)    | 0.685 (0.248)    | -         |    16.59 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           60 |     1455 | 2024-06-05 | 9z              | W   | 0.799      | 0.450        | 0.405 (0.146)    | 0.617 (0.222)    | -         |    21.64 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           59 |     1869 | 2024-05-21 | Sharks          | L   | 0.699      | -            | -                | -                | -         |   -15.35 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           58 |     1871 | 2024-05-21 | Sharks          | W   | 0.699      | -            | -                | -                | -         |     6.62 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           57 |     1902 | 2024-05-20 | Fluxo           | L   | 0.693      | -            | -                | -                | -         |   -12.66 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           56 |     1905 | 2024-05-20 | Fluxo           | W   | 0.693      | 0.450        | 0.124 (0.039)    | 0.725 (0.226)    | -         |     9.25 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           55 |     1938 | 2024-05-19 | 9z              | W   | 0.685      | 0.371        | 0.405 (0.103)    | -                | -         |    18.82 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           54 |     1959 | 2024-05-18 | ODDIK           | W   | 0.679      | 0.371        | 0.099 (0.025)    | -                | -         |     6.10 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           53 |     2031 | 2024-05-16 | Fluxo           | W   | 0.666      | 0.371        | 0.124 (0.031)    | -                | -         |    10.10 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           52 |     2073 | 2024-05-15 | 9z              | L   | 0.660      | -            | -                | -                | -         |    -2.19 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           51 |     2075 | 2024-05-15 | 9z              | W   | 0.659      | 0.450        | 0.405 (0.120)    | -                | -         |    18.84 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           50 |     2132 | 2024-05-14 | Corinthians     | W   | 0.653      | -            | -                | -                | -         |     0.72 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           49 |     2137 | 2024-05-14 | Corinthians     | W   | 0.652      | -            | -                | -                | -         |     0.72 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           48 |     2150 | 2024-05-14 | BESTIA          | W   | 0.651      | 0.371        | 0.095 (0.023)    | -                | -         |     6.98 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           47 |     2168 | 2024-05-13 | Sharks          | L   | 0.646      | -            | -                | -                | -         |   -13.20 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           46 |     2188 | 2024-05-12 | Vikings KR      | W   | 0.639      | -            | -                | -                | -         |     3.53 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           45 |     2196 | 2024-05-12 | FURIA Academy   | W   | 0.638      | -            | -                | -                | -         |     0.76 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           44 |     2252 | 2024-05-10 | paiN            | L   | 0.624      | -            | -                | -                | -         |    -3.45 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           43 |     2268 | 2024-05-09 | Intense         | W   | 0.619      | -            | -                | -                | -         |     2.38 | dav1deuS, destiny, hardzao, nython, venomzera  |
|           42 |     2286 | 2024-05-08 | paiN            | L   | 0.613      | -            | -                | -                | -         |    -3.25 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           41 |     2288 | 2024-05-08 | paiN            | W   | 0.613      | 0.450        | 0.326 (0.090)    | 0.868 (0.239)    | -         |    16.36 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           40 |     2289 | 2024-05-08 | Solid           | L   | 0.612      | -            | -                | -                | -         |   -14.75 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           39 |     2332 | 2024-05-06 | Intense         | W   | 0.597      | -            | -                | -                | -         |     2.29 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           38 |     2564 | 2024-04-25 | BESTIA          | W   | 0.526      | -            | -                | -                | -         |     5.01 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           37 |     2566 | 2024-04-25 | BESTIA          | W   | 0.526      | -            | -                | -                | -         |     5.21 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           36 |     2793 | 2024-04-17 | MIBR            | L   | 0.473      | -            | -                | -                | -         |    -1.91 | dav1deuS, hardzao, nython, righi, venomzera    |
|           35 |     2801 | 2024-04-17 | O PLANO         | W   | 0.472      | -            | -                | -                | -         |     0.64 | dav1deuS, hardzao, nython, righi, venomzera    |
|           34 |     2834 | 2024-04-16 | LaChampionsLiga | W   | 0.466      | -            | -                | -                | -         |     0.30 | dav1deuS, hardzao, nython, righi, venomzera    |
|           33 |     2884 | 2024-04-13 | Imperial        | L   | 0.446      | -            | -                | -                | -         |    -3.72 | dav1deuS, hardzao, nython, righi, venomzera    |
|           32 |     2903 | 2024-04-12 | W7M             | W   | 0.438      | -            | -                | -                | -         |     2.64 | dav1deuS, hardzao, nython, righi, venomzera    |
|           31 |     2959 | 2024-04-10 | 2GAME           | W   | 0.426      | -            | -                | -                | -         |     1.16 | dav1deuS, hardzao, nython, righi, venomzera    |
|           30 |     2962 | 2024-04-10 | 2GAME           | W   | 0.426      | -            | -                | -                | -         |     1.17 | dav1deuS, hardzao, nython, righi, venomzera    |
|           29 |     2965 | 2024-04-10 | paiN            | L   | 0.425      | -            | -                | -                | -         |    -1.92 | dav1deuS, hardzao, nython, righi, venomzera    |
|           28 |     3012 | 2024-04-09 | W7M             | W   | 0.419      | -            | -                | -                | -         |     2.60 | dav1deuS, hardzao, nython, righi, venomzera    |
|           27 |     3017 | 2024-04-09 | W7M             | W   | 0.419      | -            | -                | -                | -         |     2.66 | dav1deuS, hardzao, nython, righi, venomzera    |
|           26 |     3020 | 2024-04-09 | MIBR            | L   | 0.418      | -            | -                | -                | -         |    -1.85 | dav1deuS, hardzao, nython, righi, venomzera    |
|           25 |     3051 | 2024-04-08 | BESTIA          | W   | 0.412      | -            | -                | -                | -         |     4.68 | dav1deuS, hardzao, nython, righi, venomzera    |
|           24 |     3057 | 2024-04-08 | Bounty Hunters  | W   | 0.411      | -            | -                | -                | -         |     3.43 | dav1deuS, hardzao, nython, righi, venomzera    |
|           23 |     3087 | 2024-04-07 | Imperial        | L   | 0.406      | -            | -                | -                | -         |    -3.22 | dav1deuS, hardzao, nython, righi, venomzera    |
|           22 |     3106 | 2024-04-06 | W7M             | L   | 0.398      | -            | -                | -                | -         |   -10.14 | dav1deuS, hardzao, nython, righi, venomzera    |
|           21 |     3145 | 2024-04-04 | Case            | L   | 0.386      | -            | -                | -                | -         |    -9.04 | dav1deuS, hardzao, nython, righi, venomzera    |
|           20 |     3150 | 2024-04-04 | Case            | W   | 0.386      | -            | -                | -                | -         |     3.14 | dav1deuS, hardzao, nython, righi, venomzera    |
|           19 |     3166 | 2024-04-04 | Fluxo           | W   | 0.384      | -            | -                | -                | -         |     5.36 | dav1deuS, hardzao, nython, righi, venomzera    |
|           18 |     3186 | 2024-04-03 | ODDIK           | W   | 0.379      | -            | -                | -                | -         |     4.23 | dav1deuS, hardzao, nython, righi, venomzera    |
|           17 |     3189 | 2024-04-03 | ODDIK           | W   | 0.379      | -            | -                | -                | -         |     4.36 | dav1deuS, hardzao, nython, righi, venomzera    |
|           16 |     3474 | 2024-03-18 | ODDIK           | W   | 0.272      | -            | -                | -                | -         |     3.22 | dav1deuS, destiny, hardzao, nython, venomzera  |
|           15 |     3517 | 2024-03-16 | ODDIK           | W   | 0.259      | -            | -                | -                | -         |     3.10 | dav1deuS, destiny, hardzao, nython, venomzera  |
|           14 |     3534 | 2024-03-15 | Case            | W   | 0.252      | -            | -                | -                | -         |     2.33 | dav1deuS, destiny, hardzao, nython, venomzera  |
|           13 |     3566 | 2024-03-14 | Solid           | L   | 0.245      | -            | -                | -                | -         |    -5.71 | dav1deuS, destiny, hardzao, nython, venomzera  |
|           12 |     3575 | 2024-03-14 | Flamengo        | W   | 0.244      | -            | -                | -                | -         |     0.28 | dav1deuS, destiny, hardzao, nython, venomzera  |
|           11 |     3594 | 2024-03-13 | Case            | W   | 0.239      | -            | -                | -                | -         |     2.20 | dav1deuS, destiny, hardzao, nython, venomzera  |
|           10 |     3606 | 2024-03-13 | Galorys         | W   | 0.238      | -            | -                | -                | -         |     1.93 | dav1deuS, destiny, hardzao, nython, venomzera  |
|            9 |     3638 | 2024-03-12 | BESTIA          | W   | 0.231      | -            | -                | -                | -         |     3.01 | dav1deuS, destiny, hardzao, nython, venomzera  |
|            8 |     3656 | 2024-03-11 | Corinthians     | W   | 0.225      | -            | -                | -                | -         |     0.28 | dav1deuS, destiny, hardzao, nython, venomzera  |
|            7 |     3692 | 2024-03-09 | W7M             | W   | 0.213      | -            | -                | -                | -         |     1.41 | dav1deuS, destiny, hardzao, nython, venomzera  |
|            6 |     3739 | 2024-03-07 | VELOX           | W   | 0.199      | -            | -                | -                | -         |     0.14 | dav1deuS, destiny, hardzao, nython, venomzera  |
|            5 |     3857 | 2024-03-03 | ODDIK           | L   | 0.172      | -            | -                | -                | -         |    -3.30 | dav1deuS, destiny, hardzao, nython, venomzera  |
|            4 |     3889 | 2024-03-02 | paiN            | L   | 0.164      | -            | -                | -                | -         |    -0.70 | dav1deuS, destiny, hardzao, nython, venomzera  |
|            3 |     3904 | 2024-03-01 | Wildcard        | W   | 0.159      | -            | -                | -                | 1 (0.159) |     1.23 | dav1deuS, destiny, hardzao, nython, venomzera  |
|            2 |     4305 | 2024-02-13 | Imperial        | L   | 0.047      | -            | -                | -                | -         |    -0.38 | dav1deuS, destiny, hardzao, nython, venomzera  |
|            1 |     4308 | 2024-02-13 | Imperial        | W   | 0.046      | -            | -                | -                | -         |     1.08 | dav1deuS, destiny, hardzao, nython, venomzera  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($24,903.99)
- Divide that value by the 5th highest value among all rosters ($323,321.90)
- The final value (0.08) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-14 |      1.000 | $2,000.00      | $2,000.00       |
| 2024-06-16 |      0.873 | $1,500.00      | $1,309.44       |
| 2024-06-10 |      0.833 | $750.00        | $624.50         |
| 2024-06-09 |      0.825 | $11,500.00     | $9,492.82       |
| 2024-05-19 |      0.685 | $10,000.00     | $6,847.22       |
| 2024-03-18 |      0.272 | $3,500.00      | $950.83         |
| 2024-03-14 |      0.245 | $15,000.00     | $3,679.17       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
