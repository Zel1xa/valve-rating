### Roster Details<br />
Team Name: RED Canids<br />
Roster: coldzera, dav1deuS, hardzao, nython, venomzera<br />
Global Rank: [37](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [9]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1158.6<br />
<br />
Final Rank Value (1158.6) = Starting Rank Value (1078.2) + Head To Head Adjustments (80.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.474[<sup>1</sup>](#table2)
- Bounty Collected: 0.482[<sup>2</sup>](#table1)
- Opponent Network: 0.254[<sup>2</sup>](#table1)
- LAN Wins: 0.118[<sup>2</sup>](#table1)

The average of these factors is 0.332<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1078.2
- 400 + ( ( 0.332 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 1078.2


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
|           86 |      223 | 2024-07-28 | MIBR            | L   | 1.000      | -            | -                | -                | -         |    -7.39 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           85 |      228 | 2024-07-28 | paiN            | L   | 1.000      | -            | -                | -                | -         |    -8.03 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           84 |      283 | 2024-07-26 | ODDIK           | L   | 1.000      | -            | -                | -                | -         |   -22.71 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           83 |      350 | 2024-07-24 | Fluxo           | W   | 1.000      | -            | -                | -                | 0 (0.000) |    15.46 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           82 |      352 | 2024-07-24 | ODDIK           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.44 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           81 |      384 | 2024-07-23 | KRÜ             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.15 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           80 |      387 | 2024-07-23 | LaChampionsLiga | W   | 1.000      | -            | -                | -                | 0 (0.000) |     0.41 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           79 |      425 | 2024-07-22 | paiN Academy    | W   | 1.000      | -            | -                | -                | 0 (0.000) |     0.41 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           78 |      448 | 2024-07-21 | BESTIA          | L   | 1.000      | -            | -                | -                | -         |   -23.65 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           77 |      479 | 2024-07-20 | Case            | W   | 1.000      | 0.384        | -                | 0.804 (0.309)    | 0 (0.000) |     5.24 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           76 |      514 | 2024-07-19 | Intense         | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.31 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           75 |      619 | 2024-07-17 | Hype            | W   | 1.000      | 0.450        | -                | 0.487 (0.219)    | 0 (0.000) |     5.32 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           74 |      624 | 2024-07-17 | Hype            | W   | 1.000      | 0.450        | -                | 0.487 (0.219)    | -         |     5.60 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           73 |      679 | 2024-07-16 | Sharks          | W   | 1.000      | 0.450        | -                | 0.564 (0.254)    | -         |     7.82 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           72 |      685 | 2024-07-16 | Sharks          | W   | 1.000      | 0.450        | -                | 0.564 (0.254)    | -         |     8.36 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           71 |      777 | 2024-07-13 | Legacy          | L   | 1.000      | -            | -                | -                | -         |   -19.43 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           70 |      805 | 2024-07-11 | KRÜ             | W   | 1.000      | -            | -                | -                | -         |     5.21 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           69 |      840 | 2024-07-09 | Bounty Hunters  | W   | 1.000      | -            | -                | -                | -         |     7.65 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           68 |      863 | 2024-07-08 | SPORT           | W   | 1.000      | -            | -                | -                | -         |     2.43 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           67 |      979 | 2024-06-15 | fnatic          | L   | 0.873      | -            | -                | -                | -         |    -4.61 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           66 |     1012 | 2024-06-14 | KOI             | L   | 0.868      | -            | -                | -                | -         |   -16.55 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           65 |     1018 | 2024-06-14 | fnatic          | W   | 0.866      | 0.548        | 0.371 (0.176)    | 0.709 (0.336)    | 1 (0.866) |    22.67 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           64 |     1166 | 2024-06-09 | BESTIA          | L   | 0.834      | -            | -                | -                | -         |   -17.79 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           63 |     1171 | 2024-06-09 | Imperial        | L   | 0.833      | -            | -                | -                | -         |    -8.74 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           62 |     1304 | 2024-06-07 | Intense         | W   | 0.818      | -            | -                | -                | -         |     2.35 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           61 |     1344 | 2024-06-06 | Imperial        | W   | 0.813      | 0.450        | 0.238 (0.087)    | 0.685 (0.251)    | -         |    16.78 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           60 |     1415 | 2024-06-05 | 9z              | W   | 0.806      | 0.450        | 0.406 (0.147)    | 0.619 (0.225)    | -         |    21.77 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           59 |     1829 | 2024-05-21 | Sharks          | L   | 0.706      | -            | -                | -                | -         |   -15.54 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           58 |     1831 | 2024-05-21 | Sharks          | W   | 0.706      | -            | -                | -                | -         |     6.65 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           57 |     1862 | 2024-05-20 | Fluxo           | L   | 0.700      | -            | -                | -                | -         |   -12.82 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           56 |     1865 | 2024-05-20 | Fluxo           | W   | 0.700      | 0.450        | 0.124 (0.039)    | 0.722 (0.227)    | -         |     9.33 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           55 |     1898 | 2024-05-19 | 9z              | W   | 0.692      | 0.371        | 0.406 (0.104)    | -                | -         |    18.99 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           54 |     1919 | 2024-05-18 | ODDIK           | W   | 0.686      | 0.371        | 0.098 (0.025)    | -                | -         |     6.13 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           53 |     1991 | 2024-05-16 | Fluxo           | W   | 0.673      | 0.371        | 0.124 (0.031)    | -                | -         |    10.20 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           52 |     2033 | 2024-05-15 | 9z              | L   | 0.667      | -            | -                | -                | -         |    -2.23 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           51 |     2035 | 2024-05-15 | 9z              | W   | 0.667      | 0.450        | 0.406 (0.122)    | -                | -         |    19.02 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           50 |     2092 | 2024-05-14 | Corinthians     | W   | 0.660      | -            | -                | -                | -         |     0.72 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           49 |     2097 | 2024-05-14 | Corinthians     | W   | 0.660      | -            | -                | -                | -         |     0.73 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           48 |     2110 | 2024-05-14 | BESTIA          | W   | 0.658      | 0.371        | 0.095 (0.023)    | -                | -         |     7.01 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           47 |     2128 | 2024-05-13 | Sharks          | L   | 0.653      | -            | -                | -                | -         |   -13.37 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           46 |     2148 | 2024-05-12 | Vikings KR      | W   | 0.647      | -            | -                | -                | -         |     3.54 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           45 |     2156 | 2024-05-12 | FURIA Academy   | W   | 0.645      | -            | -                | -                | -         |     0.76 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           44 |     2212 | 2024-05-10 | paiN            | L   | 0.631      | -            | -                | -                | -         |    -3.48 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           43 |     2228 | 2024-05-09 | Intense         | W   | 0.626      | -            | -                | -                | -         |     2.39 | dav1deuS, destiny, hardzao, nython, venomzera  |
|           42 |     2246 | 2024-05-08 | paiN            | L   | 0.620      | -            | -                | -                | -         |    -3.27 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           41 |     2248 | 2024-05-08 | paiN            | W   | 0.620      | 0.450        | 0.328 (0.091)    | 0.865 (0.241)    | -         |    16.57 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           40 |     2249 | 2024-05-08 | Solid           | L   | 0.619      | -            | -                | -                | -         |   -14.95 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           39 |     2292 | 2024-05-06 | Intense         | W   | 0.604      | -            | -                | -                | -         |     2.29 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           38 |     2523 | 2024-04-25 | BESTIA          | W   | 0.533      | -            | -                | -                | -         |     5.03 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           37 |     2525 | 2024-04-25 | BESTIA          | W   | 0.533      | -            | -                | -                | -         |     5.23 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           36 |     2752 | 2024-04-17 | MIBR            | L   | 0.480      | -            | -                | -                | -         |    -1.92 | dav1deuS, hardzao, nython, righi, venomzera    |
|           35 |     2760 | 2024-04-17 | O PLANO         | W   | 0.479      | -            | -                | -                | -         |     0.64 | dav1deuS, hardzao, nython, righi, venomzera    |
|           34 |     2793 | 2024-04-16 | LaChampionsLiga | W   | 0.474      | -            | -                | -                | -         |     0.30 | dav1deuS, hardzao, nython, righi, venomzera    |
|           33 |     2843 | 2024-04-13 | Imperial        | L   | 0.453      | -            | -                | -                | -         |    -3.74 | dav1deuS, hardzao, nython, righi, venomzera    |
|           32 |     2862 | 2024-04-12 | W7M             | W   | 0.445      | -            | -                | -                | -         |     2.66 | dav1deuS, hardzao, nython, righi, venomzera    |
|           31 |     2918 | 2024-04-10 | 2GAME           | W   | 0.433      | -            | -                | -                | -         |     1.18 | dav1deuS, hardzao, nython, righi, venomzera    |
|           30 |     2921 | 2024-04-10 | 2GAME           | W   | 0.433      | -            | -                | -                | -         |     1.19 | dav1deuS, hardzao, nython, righi, venomzera    |
|           29 |     2924 | 2024-04-10 | paiN            | L   | 0.432      | -            | -                | -                | -         |    -1.93 | dav1deuS, hardzao, nython, righi, venomzera    |
|           28 |     2971 | 2024-04-09 | W7M             | W   | 0.427      | -            | -                | -                | -         |     2.62 | dav1deuS, hardzao, nython, righi, venomzera    |
|           27 |     2976 | 2024-04-09 | W7M             | W   | 0.426      | -            | -                | -                | -         |     2.68 | dav1deuS, hardzao, nython, righi, venomzera    |
|           26 |     2979 | 2024-04-09 | MIBR            | L   | 0.425      | -            | -                | -                | -         |    -1.87 | dav1deuS, hardzao, nython, righi, venomzera    |
|           25 |     3010 | 2024-04-08 | BESTIA          | W   | 0.420      | -            | -                | -                | -         |     4.72 | dav1deuS, hardzao, nython, righi, venomzera    |
|           24 |     3016 | 2024-04-08 | Bounty Hunters  | W   | 0.418      | -            | -                | -                | -         |     3.47 | dav1deuS, hardzao, nython, righi, venomzera    |
|           23 |     3046 | 2024-04-07 | Imperial        | L   | 0.413      | -            | -                | -                | -         |    -3.23 | dav1deuS, hardzao, nython, righi, venomzera    |
|           22 |     3065 | 2024-04-06 | W7M             | L   | 0.405      | -            | -                | -                | -         |   -10.34 | dav1deuS, hardzao, nython, righi, venomzera    |
|           21 |     3104 | 2024-04-04 | Case            | L   | 0.393      | -            | -                | -                | -         |    -9.24 | dav1deuS, hardzao, nython, righi, venomzera    |
|           20 |     3109 | 2024-04-04 | Case            | W   | 0.393      | -            | -                | -                | -         |     3.17 | dav1deuS, hardzao, nython, righi, venomzera    |
|           19 |     3125 | 2024-04-04 | Fluxo           | W   | 0.391      | -            | -                | -                | -         |     5.44 | dav1deuS, hardzao, nython, righi, venomzera    |
|           18 |     3145 | 2024-04-03 | ODDIK           | W   | 0.387      | -            | -                | -                | -         |     4.29 | dav1deuS, hardzao, nython, righi, venomzera    |
|           17 |     3148 | 2024-04-03 | ODDIK           | W   | 0.386      | -            | -                | -                | -         |     4.42 | dav1deuS, hardzao, nython, righi, venomzera    |
|           16 |     3433 | 2024-03-18 | ODDIK           | W   | 0.279      | -            | -                | -                | -         |     3.29 | dav1deuS, destiny, hardzao, nython, venomzera  |
|           15 |     3476 | 2024-03-16 | ODDIK           | W   | 0.266      | -            | -                | -                | -         |     3.18 | dav1deuS, destiny, hardzao, nython, venomzera  |
|           14 |     3493 | 2024-03-15 | Case            | W   | 0.259      | -            | -                | -                | -         |     2.39 | dav1deuS, destiny, hardzao, nython, venomzera  |
|           13 |     3525 | 2024-03-14 | Solid           | L   | 0.253      | -            | -                | -                | -         |    -5.89 | dav1deuS, destiny, hardzao, nython, venomzera  |
|           12 |     3534 | 2024-03-14 | Flamengo        | W   | 0.251      | -            | -                | -                | -         |     0.28 | dav1deuS, destiny, hardzao, nython, venomzera  |
|           11 |     3553 | 2024-03-13 | Case            | W   | 0.246      | -            | -                | -                | -         |     2.25 | dav1deuS, destiny, hardzao, nython, venomzera  |
|           10 |     3564 | 2024-03-13 | Galorys         | W   | 0.245      | -            | -                | -                | -         |     1.97 | dav1deuS, destiny, hardzao, nython, venomzera  |
|            9 |     3596 | 2024-03-12 | BESTIA          | W   | 0.238      | -            | -                | -                | -         |     3.08 | dav1deuS, destiny, hardzao, nython, venomzera  |
|            8 |     3614 | 2024-03-11 | Corinthians     | W   | 0.232      | -            | -                | -                | -         |     0.29 | dav1deuS, destiny, hardzao, nython, venomzera  |
|            7 |     3650 | 2024-03-09 | W7M             | W   | 0.220      | -            | -                | -                | -         |     1.45 | dav1deuS, destiny, hardzao, nython, venomzera  |
|            6 |     3697 | 2024-03-07 | VELOX           | W   | 0.207      | -            | -                | -                | -         |     0.14 | dav1deuS, destiny, hardzao, nython, venomzera  |
|            5 |     3815 | 2024-03-03 | ODDIK           | L   | 0.179      | -            | -                | -                | -         |    -3.44 | dav1deuS, destiny, hardzao, nython, venomzera  |
|            4 |     3847 | 2024-03-02 | paiN            | L   | 0.171      | -            | -                | -                | -         |    -0.73 | dav1deuS, destiny, hardzao, nython, venomzera  |
|            3 |     3862 | 2024-03-01 | Wildcard        | W   | 0.166      | -            | -                | -                | 1 (0.166) |     1.46 | dav1deuS, destiny, hardzao, nython, venomzera  |
|            2 |     4262 | 2024-02-13 | Imperial        | L   | 0.054      | -            | -                | -                | -         |    -0.44 | dav1deuS, destiny, hardzao, nython, venomzera  |
|            1 |     4265 | 2024-02-13 | Imperial        | W   | 0.053      | -            | -                | -                | -         |     1.25 | dav1deuS, destiny, hardzao, nython, venomzera  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($25,209.13)
- Divide that value by the 5th highest value among all rosters ($325,463.29)
- The final value (0.08) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-14 |      1.000 | $2,000.00      | $2,000.00       |
| 2024-06-16 |      0.880 | $1,500.00      | $1,320.28       |
| 2024-06-10 |      0.840 | $750.00        | $629.91         |
| 2024-06-09 |      0.833 | $11,500.00     | $9,575.88       |
| 2024-05-19 |      0.692 | $10,000.00     | $6,919.44       |
| 2024-03-18 |      0.279 | $3,500.00      | $976.11         |
| 2024-03-14 |      0.253 | $15,000.00     | $3,787.50       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
