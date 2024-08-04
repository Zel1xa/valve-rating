### Roster Details<br />
Team Name: RED Canids<br />
Roster: coldzera, dav1deuS, hardzao, nython, venomzera<br />
Global Rank: [36](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [9]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1158.3<br />
<br />
Final Rank Value (1158.3) = Starting Rank Value (1077.6) + Head To Head Adjustments (80.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.473[<sup>1</sup>](#table2)
- Bounty Collected: 0.482[<sup>2</sup>](#table1)
- Opponent Network: 0.253[<sup>2</sup>](#table1)
- LAN Wins: 0.117[<sup>2</sup>](#table1)

The average of these factors is 0.331<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1077.6
- 400 + ( ( 0.331 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 1077.6


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
|           86 |      234 | 2024-07-28 | MIBR            | L   | 1.000      | -            | -                | -                | -         |    -7.39 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           85 |      239 | 2024-07-28 | paiN            | L   | 1.000      | -            | -                | -                | -         |    -8.04 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           84 |      294 | 2024-07-26 | ODDIK           | L   | 1.000      | -            | -                | -                | -         |   -22.53 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           83 |      361 | 2024-07-24 | Fluxo           | W   | 1.000      | -            | -                | -                | 0 (0.000) |    15.47 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           82 |      363 | 2024-07-24 | ODDIK           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.66 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           81 |      395 | 2024-07-23 | KRÜ             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.05 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           80 |      398 | 2024-07-23 | LaChampionsLiga | W   | 1.000      | -            | -                | -                | 0 (0.000) |     0.41 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           79 |      436 | 2024-07-22 | paiN Academy    | W   | 1.000      | -            | -                | -                | 0 (0.000) |     0.41 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           78 |      459 | 2024-07-21 | BESTIA          | L   | 1.000      | -            | -                | -                | -         |   -23.62 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           77 |      490 | 2024-07-20 | Case            | W   | 1.000      | 0.384        | -                | 0.805 (0.309)    | 0 (0.000) |     5.27 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           76 |      525 | 2024-07-19 | Intense         | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.32 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           75 |      630 | 2024-07-17 | Hype            | W   | 1.000      | 0.450        | -                | 0.488 (0.220)    | 0 (0.000) |     5.32 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           74 |      635 | 2024-07-17 | Hype            | W   | 1.000      | 0.450        | -                | 0.488 (0.220)    | -         |     5.60 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           73 |      690 | 2024-07-16 | Sharks          | W   | 1.000      | 0.450        | -                | 0.565 (0.254)    | -         |     7.81 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           72 |      696 | 2024-07-16 | Sharks          | W   | 1.000      | 0.450        | -                | 0.565 (0.254)    | -         |     8.35 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           71 |      788 | 2024-07-13 | Legacy          | L   | 1.000      | -            | -                | -                | -         |   -19.43 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           70 |      817 | 2024-07-11 | KRÜ             | W   | 1.000      | -            | -                | -                | -         |     5.23 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           69 |      852 | 2024-07-09 | Bounty Hunters  | W   | 1.000      | -            | -                | -                | -         |     7.66 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           68 |      875 | 2024-07-08 | SPORT           | W   | 1.000      | -            | -                | -                | -         |     2.44 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           67 |      991 | 2024-06-15 | fnatic          | L   | 0.870      | -            | -                | -                | -         |    -4.55 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           66 |     1024 | 2024-06-14 | KOI             | L   | 0.864      | -            | -                | -                | -         |   -16.49 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           65 |     1030 | 2024-06-14 | fnatic          | W   | 0.862      | 0.548        | 0.371 (0.175)    | 0.708 (0.335)    | 1 (0.862) |    22.61 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           64 |     1178 | 2024-06-09 | BESTIA          | L   | 0.830      | -            | -                | -                | -         |   -17.69 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           63 |     1183 | 2024-06-09 | Imperial        | L   | 0.829      | -            | -                | -                | -         |    -8.71 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           62 |     1316 | 2024-06-07 | Intense         | W   | 0.815      | -            | -                | -                | -         |     2.35 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           61 |     1356 | 2024-06-06 | Imperial        | W   | 0.809      | 0.450        | 0.237 (0.086)    | 0.685 (0.249)    | -         |    16.68 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           60 |     1427 | 2024-06-05 | 9z              | W   | 0.803      | 0.450        | 0.405 (0.146)    | 0.618 (0.223)    | -         |    21.73 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           59 |     1841 | 2024-05-21 | Sharks          | L   | 0.703      | -            | -                | -                | -         |   -15.44 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           58 |     1843 | 2024-05-21 | Sharks          | W   | 0.702      | -            | -                | -                | -         |     6.63 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           57 |     1874 | 2024-05-20 | Fluxo           | L   | 0.696      | -            | -                | -                | -         |   -12.74 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           56 |     1877 | 2024-05-20 | Fluxo           | W   | 0.696      | 0.450        | 0.124 (0.039)    | 0.723 (0.227)    | -         |     9.29 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           55 |     1910 | 2024-05-19 | 9z              | W   | 0.688      | 0.371        | 0.405 (0.103)    | -                | -         |    18.91 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           54 |     1931 | 2024-05-18 | ODDIK           | W   | 0.682      | 0.371        | 0.098 (0.025)    | -                | -         |     6.11 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           53 |     2003 | 2024-05-16 | Fluxo           | W   | 0.669      | 0.371        | 0.124 (0.031)    | -                | -         |    10.14 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           52 |     2045 | 2024-05-15 | 9z              | L   | 0.663      | -            | -                | -                | -         |    -2.21 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           51 |     2047 | 2024-05-15 | 9z              | W   | 0.663      | 0.450        | 0.405 (0.121)    | -                | -         |    18.93 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           50 |     2104 | 2024-05-14 | Corinthians     | W   | 0.656      | -            | -                | -                | -         |     0.72 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           49 |     2109 | 2024-05-14 | Corinthians     | W   | 0.656      | -            | -                | -                | -         |     0.73 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           48 |     2122 | 2024-05-14 | BESTIA          | W   | 0.655      | 0.371        | 0.095 (0.023)    | -                | -         |     7.00 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           47 |     2140 | 2024-05-13 | Sharks          | L   | 0.649      | -            | -                | -                | -         |   -13.28 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           46 |     2160 | 2024-05-12 | Vikings KR      | W   | 0.643      | -            | -                | -                | -         |     3.53 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           45 |     2168 | 2024-05-12 | FURIA Academy   | W   | 0.642      | -            | -                | -                | -         |     0.76 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           44 |     2224 | 2024-05-10 | paiN            | L   | 0.627      | -            | -                | -                | -         |    -3.46 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           43 |     2240 | 2024-05-09 | Intense         | W   | 0.622      | -            | -                | -                | -         |     2.39 | dav1deuS, destiny, hardzao, nython, venomzera  |
|           42 |     2258 | 2024-05-08 | paiN            | L   | 0.617      | -            | -                | -                | -         |    -3.26 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           41 |     2260 | 2024-05-08 | paiN            | W   | 0.616      | 0.450        | 0.327 (0.091)    | 0.866 (0.240)    | -         |    16.46 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           40 |     2261 | 2024-05-08 | Solid           | L   | 0.615      | -            | -                | -                | -         |   -14.85 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           39 |     2304 | 2024-05-06 | Intense         | W   | 0.600      | -            | -                | -                | -         |     2.29 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           38 |     2536 | 2024-04-25 | BESTIA          | W   | 0.530      | -            | -                | -                | -         |     5.02 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           37 |     2538 | 2024-04-25 | BESTIA          | W   | 0.529      | -            | -                | -                | -         |     5.22 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           36 |     2765 | 2024-04-17 | MIBR            | L   | 0.476      | -            | -                | -                | -         |    -1.92 | dav1deuS, hardzao, nython, righi, venomzera    |
|           35 |     2773 | 2024-04-17 | O PLANO         | W   | 0.476      | -            | -                | -                | -         |     0.64 | dav1deuS, hardzao, nython, righi, venomzera    |
|           34 |     2806 | 2024-04-16 | LaChampionsLiga | W   | 0.470      | -            | -                | -                | -         |     0.30 | dav1deuS, hardzao, nython, righi, venomzera    |
|           33 |     2856 | 2024-04-13 | Imperial        | L   | 0.450      | -            | -                | -                | -         |    -3.73 | dav1deuS, hardzao, nython, righi, venomzera    |
|           32 |     2875 | 2024-04-12 | W7M             | W   | 0.441      | -            | -                | -                | -         |     2.65 | dav1deuS, hardzao, nython, righi, venomzera    |
|           31 |     2931 | 2024-04-10 | 2GAME           | W   | 0.430      | -            | -                | -                | -         |     1.17 | dav1deuS, hardzao, nython, righi, venomzera    |
|           30 |     2934 | 2024-04-10 | 2GAME           | W   | 0.429      | -            | -                | -                | -         |     1.18 | dav1deuS, hardzao, nython, righi, venomzera    |
|           29 |     2937 | 2024-04-10 | paiN            | L   | 0.428      | -            | -                | -                | -         |    -1.93 | dav1deuS, hardzao, nython, righi, venomzera    |
|           28 |     2984 | 2024-04-09 | W7M             | W   | 0.423      | -            | -                | -                | -         |     2.61 | dav1deuS, hardzao, nython, righi, venomzera    |
|           27 |     2989 | 2024-04-09 | W7M             | W   | 0.423      | -            | -                | -                | -         |     2.67 | dav1deuS, hardzao, nython, righi, venomzera    |
|           26 |     2992 | 2024-04-09 | MIBR            | L   | 0.422      | -            | -                | -                | -         |    -1.86 | dav1deuS, hardzao, nython, righi, venomzera    |
|           25 |     3023 | 2024-04-08 | BESTIA          | W   | 0.416      | -            | -                | -                | -         |     4.70 | dav1deuS, hardzao, nython, righi, venomzera    |
|           24 |     3029 | 2024-04-08 | Bounty Hunters  | W   | 0.415      | -            | -                | -                | -         |     3.44 | dav1deuS, hardzao, nython, righi, venomzera    |
|           23 |     3059 | 2024-04-07 | Imperial        | L   | 0.409      | -            | -                | -                | -         |    -3.23 | dav1deuS, hardzao, nython, righi, venomzera    |
|           22 |     3078 | 2024-04-06 | W7M             | L   | 0.401      | -            | -                | -                | -         |   -10.23 | dav1deuS, hardzao, nython, righi, venomzera    |
|           21 |     3117 | 2024-04-04 | Case            | L   | 0.390      | -            | -                | -                | -         |    -9.14 | dav1deuS, hardzao, nython, righi, venomzera    |
|           20 |     3122 | 2024-04-04 | Case            | W   | 0.389      | -            | -                | -                | -         |     3.15 | dav1deuS, hardzao, nython, righi, venomzera    |
|           19 |     3138 | 2024-04-04 | Fluxo           | W   | 0.387      | -            | -                | -                | -         |     5.40 | dav1deuS, hardzao, nython, righi, venomzera    |
|           18 |     3158 | 2024-04-03 | ODDIK           | W   | 0.383      | -            | -                | -                | -         |     4.25 | dav1deuS, hardzao, nython, righi, venomzera    |
|           17 |     3161 | 2024-04-03 | ODDIK           | W   | 0.383      | -            | -                | -                | -         |     4.38 | dav1deuS, hardzao, nython, righi, venomzera    |
|           16 |     3446 | 2024-03-18 | ODDIK           | W   | 0.275      | -            | -                | -                | -         |     3.25 | dav1deuS, destiny, hardzao, nython, venomzera  |
|           15 |     3489 | 2024-03-16 | ODDIK           | W   | 0.262      | -            | -                | -                | -         |     3.14 | dav1deuS, destiny, hardzao, nython, venomzera  |
|           14 |     3506 | 2024-03-15 | Case            | W   | 0.255      | -            | -                | -                | -         |     2.36 | dav1deuS, destiny, hardzao, nython, venomzera  |
|           13 |     3538 | 2024-03-14 | Solid           | L   | 0.249      | -            | -                | -                | -         |    -5.80 | dav1deuS, destiny, hardzao, nython, venomzera  |
|           12 |     3547 | 2024-03-14 | Flamengo        | W   | 0.247      | -            | -                | -                | -         |     0.28 | dav1deuS, destiny, hardzao, nython, venomzera  |
|           11 |     3566 | 2024-03-13 | Case            | W   | 0.242      | -            | -                | -                | -         |     2.22 | dav1deuS, destiny, hardzao, nython, venomzera  |
|           10 |     3578 | 2024-03-13 | Galorys         | W   | 0.242      | -            | -                | -                | -         |     1.94 | dav1deuS, destiny, hardzao, nython, venomzera  |
|            9 |     3610 | 2024-03-12 | BESTIA          | W   | 0.235      | -            | -                | -                | -         |     3.04 | dav1deuS, destiny, hardzao, nython, venomzera  |
|            8 |     3628 | 2024-03-11 | Corinthians     | W   | 0.228      | -            | -                | -                | -         |     0.29 | dav1deuS, destiny, hardzao, nython, venomzera  |
|            7 |     3664 | 2024-03-09 | W7M             | W   | 0.216      | -            | -                | -                | -         |     1.43 | dav1deuS, destiny, hardzao, nython, venomzera  |
|            6 |     3711 | 2024-03-07 | VELOX           | W   | 0.203      | -            | -                | -                | -         |     0.14 | dav1deuS, destiny, hardzao, nython, venomzera  |
|            5 |     3829 | 2024-03-03 | ODDIK           | L   | 0.175      | -            | -                | -                | -         |    -3.37 | dav1deuS, destiny, hardzao, nython, venomzera  |
|            4 |     3861 | 2024-03-02 | paiN            | L   | 0.168      | -            | -                | -                | -         |    -0.71 | dav1deuS, destiny, hardzao, nython, venomzera  |
|            3 |     3876 | 2024-03-01 | Wildcard        | W   | 0.162      | -            | -                | -                | 1 (0.162) |     1.43 | dav1deuS, destiny, hardzao, nython, venomzera  |
|            2 |     4277 | 2024-02-13 | Imperial        | L   | 0.050      | -            | -                | -                | -         |    -0.41 | dav1deuS, destiny, hardzao, nython, venomzera  |
|            1 |     4280 | 2024-02-13 | Imperial        | W   | 0.050      | -            | -                | -                | -         |     1.16 | dav1deuS, destiny, hardzao, nython, venomzera  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($25,049.71)
- Divide that value by the 5th highest value among all rosters ($324,344.55)
- The final value (0.08) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-14 |      1.000 | $2,000.00      | $2,000.00       |
| 2024-06-16 |      0.876 | $1,500.00      | $1,314.62       |
| 2024-06-10 |      0.836 | $750.00        | $627.08         |
| 2024-06-09 |      0.829 | $11,500.00     | $9,532.49       |
| 2024-05-19 |      0.688 | $10,000.00     | $6,881.71       |
| 2024-03-18 |      0.275 | $3,500.00      | $962.91         |
| 2024-03-14 |      0.249 | $15,000.00     | $3,730.90       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
