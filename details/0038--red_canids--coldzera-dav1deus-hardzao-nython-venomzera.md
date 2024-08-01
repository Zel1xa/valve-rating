### Roster Details<br />
Team Name: RED Canids<br />
Roster: coldzera, dav1deuS, hardzao, nython, venomzera<br />
Global Rank: [38](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [9]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1145.0<br />
<br />
Final Rank Value (1145.0) = Starting Rank Value (1026.1) + Head To Head Adjustments (119.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.471[<sup>1</sup>](#table2)
- Bounty Collected: 0.452[<sup>2</sup>](#table1)
- Opponent Network: 0.272[<sup>2</sup>](#table1)
- LAN Wins: 0.021[<sup>2</sup>](#table1)

The average of these factors is 0.304<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1026.1
- 400 + ( ( 0.304 - 0.000 ) / ( 0.777 - 0.000 ) ) * 1600 = 1026.1


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
|           93 |      138 | 2024-07-28 | MIBR            | L   | 1.000      | -            | -                | -                | -         |    -8.67 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           92 |      143 | 2024-07-28 | paiN            | L   | 1.000      | -            | -                | -                | -         |    -9.36 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           91 |      198 | 2024-07-26 | ODDIK           | L   | 1.000      | -            | -                | -                | -         |   -21.88 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           90 |      265 | 2024-07-24 | Fluxo           | W   | 1.000      | -            | -                | -                | 0 (0.000) |    15.64 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           89 |      267 | 2024-07-24 | ODDIK           | W   | 1.000      | -            | -                | -                | 0 (0.000) |    10.36 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           88 |      299 | 2024-07-23 | KRÜ             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.20 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           87 |      302 | 2024-07-23 | LaChampionsLiga | W   | 1.000      | -            | -                | -                | 0 (0.000) |     0.44 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           86 |      333 | 2024-07-22 | ODDIK           | W   | 1.000      | -            | -                | -                | 0 (0.000) |    10.92 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           85 |      341 | 2024-07-22 | paiN Academy    | W   | 1.000      | -            | -                | -                | 0 (0.000) |     0.46 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           84 |      365 | 2024-07-21 | BESTIA          | L   | 1.000      | -            | -                | -                | -         |   -23.04 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           83 |      397 | 2024-07-20 | Case            | W   | 1.000      | 0.384        | -                | 0.721 (0.277)    | 0 (0.000) |     5.99 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           82 |      433 | 2024-07-19 | Intense         | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.26 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           81 |      475 | 2024-07-18 | Imperial        | W   | 1.000      | 0.450        | 0.240 (0.108)    | 0.719 (0.324)    | 0 (0.000) |    17.70 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           80 |      476 | 2024-07-18 | Imperial        | W   | 1.000      | 0.450        | 0.240 (0.108)    | 0.719 (0.324)    | -         |    19.28 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           79 |      544 | 2024-07-17 | Hype            | W   | 1.000      | 0.450        | -                | 0.511 (0.230)    | -         |     7.83 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           78 |      548 | 2024-07-17 | Hype            | W   | 1.000      | 0.450        | -                | 0.511 (0.230)    | -         |     8.37 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           77 |      603 | 2024-07-16 | Sharks          | W   | 1.000      | 0.450        | -                | 0.572 (0.257)    | -         |    10.08 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           76 |      610 | 2024-07-16 | Sharks          | W   | 1.000      | 0.450        | -                | 0.572 (0.257)    | -         |    10.90 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           75 |      709 | 2024-07-13 | Legacy          | L   | 1.000      | -            | -                | -                | -         |   -15.16 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           74 |      738 | 2024-07-11 | KRÜ             | W   | 1.000      | -            | -                | -                | -         |     8.12 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           73 |      773 | 2024-07-09 | Bounty Hunters  | W   | 1.000      | -            | -                | -                | -         |    10.56 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           72 |      796 | 2024-07-08 | SPORT           | W   | 1.000      | -            | -                | -                | -         |     3.77 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           71 |     1090 | 2024-06-09 | BESTIA          | L   | 0.850      | -            | -                | -                | -         |   -15.30 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           70 |     1095 | 2024-06-09 | Imperial        | L   | 0.849      | -            | -                | -                | -         |    -6.62 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           69 |     1208 | 2024-06-07 | ODDIK           | L   | 0.837      | -            | -                | -                | -         |   -18.81 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           68 |     1219 | 2024-06-07 | Sharks          | L   | 0.836      | -            | -                | -                | -         |   -16.18 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           67 |     1237 | 2024-06-07 | Intense         | W   | 0.835      | -            | -                | -                | -         |     1.72 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           66 |     1278 | 2024-06-06 | Imperial        | W   | 0.829      | 0.450        | 0.240 (0.089)    | 0.719 (0.268)    | -         |    18.66 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           65 |     1325 | 2024-06-06 | KRÜ             | L   | 0.827      | -            | -                | -                | -         |   -19.92 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           64 |     1352 | 2024-06-05 | 9z              | W   | 0.823      | 0.450        | 0.138 (0.051)    | -                | -         |    16.95 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           63 |     1744 | 2024-05-22 | Solid           | W   | 0.727      | 0.450        | -                | 0.843 (0.276)    | -         |     4.94 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           62 |     1745 | 2024-05-22 | Solid           | W   | 0.727      | 0.450        | -                | 0.843 (0.276)    | -         |     5.17 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           61 |     1782 | 2024-05-21 | Sharks          | L   | 0.723      | -            | -                | -                | -         |   -14.81 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           60 |     1784 | 2024-05-21 | Sharks          | W   | 0.723      | -            | -                | -                | -         |     7.94 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           59 |     1819 | 2024-05-20 | Fluxo           | L   | 0.716      | -            | -                | -                | -         |   -11.82 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           58 |     1823 | 2024-05-20 | Fluxo           | W   | 0.716      | 0.450        | 0.122 (0.039)    | -                | -         |    10.91 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           57 |     1864 | 2024-05-19 | 9z              | W   | 0.708      | 0.371        | 0.138 (0.036)    | -                | -         |    14.08 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           56 |     1885 | 2024-05-18 | ODDIK           | W   | 0.703      | 0.371        | 0.096 (0.025)    | -                | -         |     7.51 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           55 |     1958 | 2024-05-16 | Fluxo           | W   | 0.689      | 0.371        | 0.122 (0.031)    | -                | -         |    11.96 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           54 |     2000 | 2024-05-15 | 9z              | L   | 0.683      | -            | -                | -                | -         |    -7.56 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           53 |     2002 | 2024-05-15 | 9z              | W   | 0.683      | 0.450        | 0.138 (0.042)    | -                | -         |    14.33 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           52 |     2065 | 2024-05-14 | Corinthians     | W   | 0.676      | -            | -                | -                | -         |     0.94 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           51 |     2070 | 2024-05-14 | Corinthians     | W   | 0.676      | -            | -                | -                | -         |     0.95 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           50 |     2083 | 2024-05-14 | BESTIA          | W   | 0.675      | -            | -                | -                | -         |     8.04 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           49 |     2102 | 2024-05-13 | Sharks          | L   | 0.669      | -            | -                | -                | -         |   -12.68 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           48 |     2124 | 2024-05-12 | Vikings KR      | W   | 0.663      | -            | -                | -                | -         |     4.20 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           47 |     2132 | 2024-05-12 | FURIA Academy   | W   | 0.662      | -            | -                | -                | -         |     0.95 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           46 |     2188 | 2024-05-10 | paiN            | L   | 0.647      | -            | -                | -                | -         |    -3.50 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           45 |     2204 | 2024-05-09 | Intense         | W   | 0.642      | -            | -                | -                | -         |     1.47 | dav1deuS, destiny, hardzao, nython, venomzera  |
|           44 |     2222 | 2024-05-08 | paiN            | L   | 0.637      | -            | -                | -                | -         |    -3.32 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           43 |     2226 | 2024-05-08 | paiN            | W   | 0.636      | 0.450        | 0.300 (0.086)    | -                | -         |    17.04 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           42 |     2227 | 2024-05-08 | Solid           | L   | 0.636      | -            | -                | -                | -         |   -14.60 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           41 |     2270 | 2024-05-06 | Intense         | W   | 0.621      | -            | -                | -                | -         |     1.38 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           40 |     2505 | 2024-04-25 | BESTIA          | W   | 0.550      | -            | -                | -                | -         |     5.87 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           39 |     2507 | 2024-04-25 | BESTIA          | W   | 0.549      | -            | -                | -                | -         |     6.13 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           38 |     2742 | 2024-04-17 | MIBR            | L   | 0.496      | -            | -                | -                | -         |    -1.71 | dav1deuS, hardzao, nython, righi, venomzera    |
|           37 |     2751 | 2024-04-17 | O PLANO         | W   | 0.496      | -            | -                | -                | -         |     0.80 | dav1deuS, hardzao, nython, righi, venomzera    |
|           36 |     2784 | 2024-04-16 | LaChampionsLiga | W   | 0.490      | -            | -                | -                | -         |     0.38 | dav1deuS, hardzao, nython, righi, venomzera    |
|           35 |     2835 | 2024-04-13 | Imperial        | L   | 0.470      | -            | -                | -                | -         |    -3.20 | dav1deuS, hardzao, nython, righi, venomzera    |
|           34 |     2854 | 2024-04-12 | W7M             | W   | 0.461      | -            | -                | -                | -         |     3.56 | dav1deuS, hardzao, nython, righi, venomzera    |
|           33 |     2911 | 2024-04-10 | 2GAME           | W   | 0.450      | -            | -                | -                | -         |     1.53 | dav1deuS, hardzao, nython, righi, venomzera    |
|           32 |     2914 | 2024-04-10 | 2GAME           | W   | 0.449      | -            | -                | -                | -         |     1.55 | dav1deuS, hardzao, nython, righi, venomzera    |
|           31 |     2917 | 2024-04-10 | paiN            | L   | 0.448      | -            | -                | -                | -         |    -2.06 | dav1deuS, hardzao, nython, righi, venomzera    |
|           30 |     2964 | 2024-04-09 | W7M             | W   | 0.443      | -            | -                | -                | -         |     3.54 | dav1deuS, hardzao, nython, righi, venomzera    |
|           29 |     2969 | 2024-04-09 | W7M             | W   | 0.443      | -            | -                | -                | -         |     3.64 | dav1deuS, hardzao, nython, righi, venomzera    |
|           28 |     2972 | 2024-04-09 | MIBR            | L   | 0.442      | -            | -                | -                | -         |    -1.64 | dav1deuS, hardzao, nython, righi, venomzera    |
|           27 |     3003 | 2024-04-08 | BESTIA          | W   | 0.436      | -            | -                | -                | -         |     5.65 | dav1deuS, hardzao, nython, righi, venomzera    |
|           26 |     3009 | 2024-04-08 | Bounty Hunters  | W   | 0.435      | -            | -                | -                | -         |     4.27 | dav1deuS, hardzao, nython, righi, venomzera    |
|           25 |     3039 | 2024-04-07 | Imperial        | L   | 0.429      | -            | -                | -                | -         |    -2.66 | dav1deuS, hardzao, nython, righi, venomzera    |
|           24 |     3058 | 2024-04-06 | W7M             | L   | 0.421      | -            | -                | -                | -         |    -9.92 | dav1deuS, hardzao, nython, righi, venomzera    |
|           23 |     3097 | 2024-04-04 | Case            | L   | 0.410      | -            | -                | -                | -         |    -8.93 | dav1deuS, hardzao, nython, righi, venomzera    |
|           22 |     3102 | 2024-04-04 | Case            | W   | 0.409      | -            | -                | -                | -         |     4.01 | dav1deuS, hardzao, nython, righi, venomzera    |
|           21 |     3119 | 2024-04-04 | Fluxo           | W   | 0.407      | -            | -                | -                | -         |     6.61 | dav1deuS, hardzao, nython, righi, venomzera    |
|           20 |     3139 | 2024-04-03 | ODDIK           | W   | 0.403      | -            | -                | -                | -         |     5.63 | dav1deuS, hardzao, nython, righi, venomzera    |
|           19 |     3142 | 2024-04-03 | ODDIK           | W   | 0.403      | -            | -                | -                | -         |     5.83 | dav1deuS, hardzao, nython, righi, venomzera    |
|           18 |     3284 | 2024-03-27 | adalYamigos     | W   | 0.356      | -            | -                | -                | -         |     1.06 | dav1deuS, destiny, hardzao, nython, venomzera  |
|           17 |     3439 | 2024-03-18 | ODDIK           | W   | 0.295      | -            | -                | -                | -         |     4.45 | dav1deuS, destiny, hardzao, nython, venomzera  |
|           16 |     3482 | 2024-03-16 | ODDIK           | W   | 0.282      | -            | -                | -                | -         |     4.32 | dav1deuS, destiny, hardzao, nython, venomzera  |
|           15 |     3499 | 2024-03-15 | Case            | W   | 0.276      | -            | -                | -                | -         |     3.16 | dav1deuS, destiny, hardzao, nython, venomzera  |
|           14 |     3533 | 2024-03-14 | Solid           | L   | 0.269      | -            | -                | -                | -         |    -5.72 | dav1deuS, destiny, hardzao, nython, venomzera  |
|           13 |     3544 | 2024-03-14 | Flamengo        | W   | 0.268      | -            | -                | -                | -         |     0.40 | dav1deuS, destiny, hardzao, nython, venomzera  |
|           12 |     3559 | 2024-03-13 | Fluxo           | L   | 0.263      | -            | -                | -                | -         |    -3.89 | dav1deuS, destiny, hardzao, nython, venomzera  |
|           11 |     3564 | 2024-03-13 | Case            | W   | 0.262      | -            | -                | -                | -         |     2.96 | dav1deuS, destiny, hardzao, nython, venomzera  |
|           10 |     3575 | 2024-03-13 | Galorys         | W   | 0.262      | -            | -                | -                | -         |     2.56 | dav1deuS, destiny, hardzao, nython, venomzera  |
|            9 |     3608 | 2024-03-12 | BESTIA          | W   | 0.255      | -            | -                | -                | -         |     3.85 | dav1deuS, destiny, hardzao, nython, venomzera  |
|            8 |     3626 | 2024-03-11 | Corinthians     | W   | 0.248      | -            | -                | -                | -         |     0.44 | dav1deuS, destiny, hardzao, nython, venomzera  |
|            7 |     3662 | 2024-03-09 | W7M             | W   | 0.236      | -            | -                | -                | -         |     2.15 | dav1deuS, destiny, hardzao, nython, venomzera  |
|            6 |     3710 | 2024-03-07 | VELOX           | W   | 0.223      | -            | -                | -                | -         |     0.20 | dav1deuS, destiny, hardzao, nython, venomzera  |
|            5 |     3833 | 2024-03-03 | ODDIK           | L   | 0.195      | -            | -                | -                | -         |    -3.19 | dav1deuS, destiny, hardzao, nython, venomzera  |
|            4 |     3865 | 2024-03-02 | paiN            | L   | 0.188      | -            | -                | -                | -         |    -0.79 | dav1deuS, destiny, hardzao, nython, venomzera  |
|            3 |     3881 | 2024-03-01 | Wildcard        | W   | 0.182      | -            | -                | -                | 1 (0.182) |     2.02 | dav1deuS, destiny, hardzao, nython, venomzera  |
|            2 |     4291 | 2024-02-13 | Imperial        | L   | 0.070      | -            | -                | -                | -         |    -0.45 | dav1deuS, destiny, hardzao, nython, venomzera  |
|            1 |     4294 | 2024-02-13 | Imperial        | W   | 0.070      | -            | -                | -                | -         |     1.76 | dav1deuS, destiny, hardzao, nython, venomzera  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($24,556.70)
- Divide that value by the 5th highest value among all rosters ($327,422.13)
- The final value (0.08) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-14 |      1.000 | $2,000.00      | $2,000.00       |
| 2024-06-10 |      0.856 | $750.00        | $642.20         |
| 2024-06-09 |      0.849 | $11,500.00     | $9,764.35       |
| 2024-05-19 |      0.708 | $10,000.00     | $7,083.33       |
| 2024-03-18 |      0.295 | $3,500.00      | $1,033.47       |
| 2024-03-14 |      0.269 | $15,000.00     | $4,033.33       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
