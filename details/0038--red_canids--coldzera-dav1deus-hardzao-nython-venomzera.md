### Roster Details<br />
Team Name: RED Canids<br />
Roster: coldzera, dav1deuS, hardzao, nython, venomzera<br />
Global Rank: [38](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [9]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1144.2<br />
<br />
Final Rank Value (1144.2) = Starting Rank Value (1025.2) + Head To Head Adjustments (119.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.470[<sup>1</sup>](#table2)
- Bounty Collected: 0.452[<sup>2</sup>](#table1)
- Opponent Network: 0.272[<sup>2</sup>](#table1)
- LAN Wins: 0.021[<sup>2</sup>](#table1)

The average of these factors is 0.304<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1025.2
- 400 + ( ( 0.304 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1025.2


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
|           93 |      142 | 2024-07-28 | MIBR            | L   | 1.000      | -            | -                | -                | -         |    -8.67 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           92 |      147 | 2024-07-28 | paiN            | L   | 1.000      | -            | -                | -                | -         |    -9.37 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           91 |      202 | 2024-07-26 | ODDIK           | L   | 1.000      | -            | -                | -                | -         |   -21.87 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           90 |      269 | 2024-07-24 | Fluxo           | W   | 1.000      | -            | -                | -                | 0 (0.000) |    15.64 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           89 |      271 | 2024-07-24 | ODDIK           | W   | 1.000      | -            | -                | -                | 0 (0.000) |    10.36 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           88 |      303 | 2024-07-23 | KRÜ             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.20 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           87 |      306 | 2024-07-23 | LaChampionsLiga | W   | 1.000      | -            | -                | -                | 0 (0.000) |     0.44 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           86 |      337 | 2024-07-22 | ODDIK           | W   | 1.000      | -            | -                | -                | 0 (0.000) |    10.92 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           85 |      345 | 2024-07-22 | paiN Academy    | W   | 1.000      | -            | -                | -                | 0 (0.000) |     0.46 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           84 |      369 | 2024-07-21 | BESTIA          | L   | 1.000      | -            | -                | -                | -         |   -23.03 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           83 |      401 | 2024-07-20 | Case            | W   | 1.000      | 0.384        | -                | 0.722 (0.277)    | 0 (0.000) |     6.00 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           82 |      437 | 2024-07-19 | Intense         | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.27 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           81 |      479 | 2024-07-18 | Imperial        | W   | 1.000      | 0.450        | 0.239 (0.108)    | 0.719 (0.324)    | 0 (0.000) |    17.68 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           80 |      480 | 2024-07-18 | Imperial        | W   | 1.000      | 0.450        | 0.239 (0.108)    | 0.719 (0.324)    | -         |    19.27 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           79 |      548 | 2024-07-17 | Hype            | W   | 1.000      | 0.450        | -                | 0.512 (0.230)    | -         |     7.83 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           78 |      552 | 2024-07-17 | Hype            | W   | 1.000      | 0.450        | -                | 0.512 (0.230)    | -         |     8.38 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           77 |      607 | 2024-07-16 | Sharks          | W   | 1.000      | 0.450        | -                | 0.572 (0.258)    | -         |    10.09 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           76 |      614 | 2024-07-16 | Sharks          | W   | 1.000      | 0.450        | -                | 0.572 (0.258)    | -         |    10.91 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           75 |      713 | 2024-07-13 | Legacy          | L   | 1.000      | -            | -                | -                | -         |   -15.16 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           74 |      742 | 2024-07-11 | KRÜ             | W   | 1.000      | -            | -                | -                | -         |     8.13 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           73 |      777 | 2024-07-09 | Bounty Hunters  | W   | 1.000      | -            | -                | -                | -         |    10.56 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           72 |      800 | 2024-07-08 | SPORT           | W   | 1.000      | -            | -                | -                | -         |     3.78 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           71 |     1094 | 2024-06-09 | BESTIA          | L   | 0.849      | -            | -                | -                | -         |   -15.27 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           70 |     1099 | 2024-06-09 | Imperial        | L   | 0.848      | -            | -                | -                | -         |    -6.62 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           69 |     1212 | 2024-06-07 | ODDIK           | L   | 0.836      | -            | -                | -                | -         |   -18.78 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           68 |     1223 | 2024-06-07 | Sharks          | L   | 0.835      | -            | -                | -                | -         |   -16.16 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           67 |     1241 | 2024-06-07 | Intense         | W   | 0.833      | -            | -                | -                | -         |     1.72 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           66 |     1282 | 2024-06-06 | Imperial        | W   | 0.828      | 0.450        | 0.239 (0.089)    | 0.719 (0.268)    | -         |    18.62 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           65 |     1329 | 2024-06-06 | KRÜ             | L   | 0.825      | -            | -                | -                | -         |   -19.88 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           64 |     1356 | 2024-06-05 | 9z              | W   | 0.821      | 0.450        | 0.138 (0.051)    | -                | -         |    16.95 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           63 |     1748 | 2024-05-22 | Solid           | W   | 0.726      | 0.450        | -                | 0.844 (0.275)    | -         |     4.94 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           62 |     1749 | 2024-05-22 | Solid           | W   | 0.726      | 0.450        | -                | 0.844 (0.275)    | -         |     5.17 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           61 |     1786 | 2024-05-21 | Sharks          | L   | 0.721      | -            | -                | -                | -         |   -14.78 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           60 |     1788 | 2024-05-21 | Sharks          | W   | 0.721      | -            | -                | -                | -         |     7.93 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           59 |     1823 | 2024-05-20 | Fluxo           | L   | 0.715      | -            | -                | -                | -         |   -11.80 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           58 |     1827 | 2024-05-20 | Fluxo           | W   | 0.715      | 0.450        | 0.122 (0.039)    | -                | -         |    10.89 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           57 |     1868 | 2024-05-19 | 9z              | W   | 0.707      | 0.371        | 0.138 (0.036)    | -                | -         |    14.07 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           56 |     1889 | 2024-05-18 | ODDIK           | W   | 0.701      | 0.371        | 0.096 (0.025)    | -                | -         |     7.50 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           55 |     1962 | 2024-05-16 | Fluxo           | W   | 0.688      | 0.371        | 0.122 (0.031)    | -                | -         |    11.93 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           54 |     2004 | 2024-05-15 | 9z              | L   | 0.682      | -            | -                | -                | -         |    -7.53 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           53 |     2006 | 2024-05-15 | 9z              | W   | 0.682      | 0.450        | 0.138 (0.042)    | -                | -         |    14.32 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           52 |     2069 | 2024-05-14 | Corinthians     | W   | 0.675      | -            | -                | -                | -         |     0.94 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           51 |     2074 | 2024-05-14 | Corinthians     | W   | 0.675      | -            | -                | -                | -         |     0.95 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           50 |     2087 | 2024-05-14 | BESTIA          | W   | 0.673      | -            | -                | -                | -         |     8.04 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           49 |     2106 | 2024-05-13 | Sharks          | L   | 0.668      | -            | -                | -                | -         |   -12.65 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           48 |     2128 | 2024-05-12 | Vikings KR      | W   | 0.662      | -            | -                | -                | -         |     4.20 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           47 |     2136 | 2024-05-12 | FURIA Academy   | W   | 0.660      | -            | -                | -                | -         |     0.95 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           46 |     2192 | 2024-05-10 | paiN            | L   | 0.646      | -            | -                | -                | -         |    -3.51 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           45 |     2208 | 2024-05-09 | Intense         | W   | 0.641      | -            | -                | -                | -         |     1.47 | dav1deuS, destiny, hardzao, nython, venomzera  |
|           44 |     2226 | 2024-05-08 | paiN            | L   | 0.635      | -            | -                | -                | -         |    -3.33 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           43 |     2230 | 2024-05-08 | paiN            | W   | 0.635      | 0.450        | 0.300 (0.086)    | -                | -         |    17.00 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           42 |     2231 | 2024-05-08 | Solid           | L   | 0.634      | -            | -                | -                | -         |   -14.56 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           41 |     2274 | 2024-05-06 | Intense         | W   | 0.619      | -            | -                | -                | -         |     1.38 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           40 |     2509 | 2024-04-25 | BESTIA          | W   | 0.548      | -            | -                | -                | -         |     5.86 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           39 |     2511 | 2024-04-25 | BESTIA          | W   | 0.548      | -            | -                | -                | -         |     6.13 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           38 |     2746 | 2024-04-17 | MIBR            | L   | 0.495      | -            | -                | -                | -         |    -1.71 | dav1deuS, hardzao, nython, righi, venomzera    |
|           37 |     2755 | 2024-04-17 | O PLANO         | W   | 0.494      | -            | -                | -                | -         |     0.80 | dav1deuS, hardzao, nython, righi, venomzera    |
|           36 |     2788 | 2024-04-16 | LaChampionsLiga | W   | 0.489      | -            | -                | -                | -         |     0.38 | dav1deuS, hardzao, nython, righi, venomzera    |
|           35 |     2839 | 2024-04-13 | Imperial        | L   | 0.468      | -            | -                | -                | -         |    -3.20 | dav1deuS, hardzao, nython, righi, venomzera    |
|           34 |     2858 | 2024-04-12 | W7M             | W   | 0.460      | -            | -                | -                | -         |     3.55 | dav1deuS, hardzao, nython, righi, venomzera    |
|           33 |     2915 | 2024-04-10 | 2GAME           | W   | 0.448      | -            | -                | -                | -         |     1.53 | dav1deuS, hardzao, nython, righi, venomzera    |
|           32 |     2918 | 2024-04-10 | 2GAME           | W   | 0.448      | -            | -                | -                | -         |     1.55 | dav1deuS, hardzao, nython, righi, venomzera    |
|           31 |     2921 | 2024-04-10 | paiN            | L   | 0.447      | -            | -                | -                | -         |    -2.06 | dav1deuS, hardzao, nython, righi, venomzera    |
|           30 |     2968 | 2024-04-09 | W7M             | W   | 0.442      | -            | -                | -                | -         |     3.53 | dav1deuS, hardzao, nython, righi, venomzera    |
|           29 |     2973 | 2024-04-09 | W7M             | W   | 0.441      | -            | -                | -                | -         |     3.64 | dav1deuS, hardzao, nython, righi, venomzera    |
|           28 |     2976 | 2024-04-09 | MIBR            | L   | 0.440      | -            | -                | -                | -         |    -1.64 | dav1deuS, hardzao, nython, righi, venomzera    |
|           27 |     3007 | 2024-04-08 | BESTIA          | W   | 0.435      | -            | -                | -                | -         |     5.64 | dav1deuS, hardzao, nython, righi, venomzera    |
|           26 |     3013 | 2024-04-08 | Bounty Hunters  | W   | 0.433      | -            | -                | -                | -         |     4.26 | dav1deuS, hardzao, nython, righi, venomzera    |
|           25 |     3043 | 2024-04-07 | Imperial        | L   | 0.428      | -            | -                | -                | -         |    -2.66 | dav1deuS, hardzao, nython, righi, venomzera    |
|           24 |     3062 | 2024-04-06 | W7M             | L   | 0.420      | -            | -                | -                | -         |    -9.88 | dav1deuS, hardzao, nython, righi, venomzera    |
|           23 |     3101 | 2024-04-04 | Case            | L   | 0.408      | -            | -                | -                | -         |    -8.89 | dav1deuS, hardzao, nython, righi, venomzera    |
|           22 |     3106 | 2024-04-04 | Case            | W   | 0.408      | -            | -                | -                | -         |     4.01 | dav1deuS, hardzao, nython, righi, venomzera    |
|           21 |     3123 | 2024-04-04 | Fluxo           | W   | 0.406      | -            | -                | -                | -         |     6.59 | dav1deuS, hardzao, nython, righi, venomzera    |
|           20 |     3143 | 2024-04-03 | ODDIK           | W   | 0.402      | -            | -                | -                | -         |     5.61 | dav1deuS, hardzao, nython, righi, venomzera    |
|           19 |     3146 | 2024-04-03 | ODDIK           | W   | 0.401      | -            | -                | -                | -         |     5.81 | dav1deuS, hardzao, nython, righi, venomzera    |
|           18 |     3288 | 2024-03-27 | adalYamigos     | W   | 0.355      | -            | -                | -                | -         |     1.06 | dav1deuS, destiny, hardzao, nython, venomzera  |
|           17 |     3443 | 2024-03-18 | ODDIK           | W   | 0.294      | -            | -                | -                | -         |     4.42 | dav1deuS, destiny, hardzao, nython, venomzera  |
|           16 |     3486 | 2024-03-16 | ODDIK           | W   | 0.281      | -            | -                | -                | -         |     4.30 | dav1deuS, destiny, hardzao, nython, venomzera  |
|           15 |     3503 | 2024-03-15 | Case            | W   | 0.274      | -            | -                | -                | -         |     3.15 | dav1deuS, destiny, hardzao, nython, venomzera  |
|           14 |     3537 | 2024-03-14 | Solid           | L   | 0.268      | -            | -                | -                | -         |    -5.69 | dav1deuS, destiny, hardzao, nython, venomzera  |
|           13 |     3548 | 2024-03-14 | Flamengo        | W   | 0.266      | -            | -                | -                | -         |     0.40 | dav1deuS, destiny, hardzao, nython, venomzera  |
|           12 |     3563 | 2024-03-13 | Fluxo           | L   | 0.261      | -            | -                | -                | -         |    -3.87 | dav1deuS, destiny, hardzao, nython, venomzera  |
|           11 |     3568 | 2024-03-13 | Case            | W   | 0.261      | -            | -                | -                | -         |     2.95 | dav1deuS, destiny, hardzao, nython, venomzera  |
|           10 |     3579 | 2024-03-13 | Galorys         | W   | 0.260      | -            | -                | -                | -         |     2.55 | dav1deuS, destiny, hardzao, nython, venomzera  |
|            9 |     3612 | 2024-03-12 | BESTIA          | W   | 0.253      | -            | -                | -                | -         |     3.83 | dav1deuS, destiny, hardzao, nython, venomzera  |
|            8 |     3630 | 2024-03-11 | Corinthians     | W   | 0.247      | -            | -                | -                | -         |     0.44 | dav1deuS, destiny, hardzao, nython, venomzera  |
|            7 |     3666 | 2024-03-09 | W7M             | W   | 0.235      | -            | -                | -                | -         |     2.14 | dav1deuS, destiny, hardzao, nython, venomzera  |
|            6 |     3714 | 2024-03-07 | VELOX           | W   | 0.222      | -            | -                | -                | -         |     0.20 | dav1deuS, destiny, hardzao, nython, venomzera  |
|            5 |     3837 | 2024-03-03 | ODDIK           | L   | 0.194      | -            | -                | -                | -         |    -3.17 | dav1deuS, destiny, hardzao, nython, venomzera  |
|            4 |     3869 | 2024-03-02 | paiN            | L   | 0.186      | -            | -                | -                | -         |    -0.79 | dav1deuS, destiny, hardzao, nython, venomzera  |
|            3 |     3885 | 2024-03-01 | Wildcard        | W   | 0.181      | -            | -                | -                | 1 (0.181) |     2.01 | dav1deuS, destiny, hardzao, nython, venomzera  |
|            2 |     4295 | 2024-02-13 | Imperial        | L   | 0.069      | -            | -                | -                | -         |    -0.44 | dav1deuS, destiny, hardzao, nython, venomzera  |
|            1 |     4298 | 2024-02-13 | Imperial        | W   | 0.068      | -            | -                | -                | -         |     1.73 | dav1deuS, destiny, hardzao, nython, venomzera  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($24,500.10)
- Divide that value by the 5th highest value among all rosters ($327,030.46)
- The final value (0.07) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-14 |      1.000 | $2,000.00      | $2,000.00       |
| 2024-06-10 |      0.855 | $750.00        | $641.16         |
| 2024-06-09 |      0.848 | $11,500.00     | $9,748.38       |
| 2024-05-19 |      0.707 | $10,000.00     | $7,069.44       |
| 2024-03-18 |      0.294 | $3,500.00      | $1,028.61       |
| 2024-03-14 |      0.268 | $15,000.00     | $4,012.50       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
