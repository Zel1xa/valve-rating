### Roster Details<br />
Team Name: RED Canids<br />
Roster: coldzera, dav1deuS, hardzao, nython, venomzera<br />
Global Rank: [38](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [9]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1164.9<br />
<br />
Final Rank Value (1164.9) = Starting Rank Value (1085.9) + Head To Head Adjustments (79.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.475[<sup>1</sup>](#table2)
- Bounty Collected: 0.486[<sup>2</sup>](#table1)
- Opponent Network: 0.246[<sup>2</sup>](#table1)
- LAN Wins: 0.123[<sup>2</sup>](#table1)

The average of these factors is 0.333<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1085.9
- 400 + ( ( 0.333 - 0.000 ) / ( 0.776 - 0.000 ) ) * 1600 = 1085.9


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
|           86 |      109 | 2024-07-28 | MIBR            | L   | 1.000      | -            | -                | -                | -         |    -7.27 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           85 |      114 | 2024-07-28 | paiN            | L   | 1.000      | -            | -                | -                | -         |    -7.94 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           84 |      169 | 2024-07-26 | ODDIK           | L   | 1.000      | -            | -                | -                | -         |   -22.74 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           83 |      236 | 2024-07-24 | Fluxo           | W   | 1.000      | -            | -                | -                | 0 (0.000) |    15.34 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           82 |      238 | 2024-07-24 | ODDIK           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.42 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           81 |      270 | 2024-07-23 | KRÜ             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.85 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           80 |      273 | 2024-07-23 | LaChampionsLiga | W   | 1.000      | -            | -                | -                | 0 (0.000) |     0.39 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           79 |      311 | 2024-07-22 | paiN Academy    | W   | 1.000      | -            | -                | -                | 0 (0.000) |     0.39 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           78 |      334 | 2024-07-21 | BESTIA          | L   | 1.000      | -            | -                | -                | -         |   -23.76 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           77 |      365 | 2024-07-20 | Case            | W   | 1.000      | 0.384        | -                | 0.720 (0.277)    | 0 (0.000) |     5.09 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           76 |      400 | 2024-07-19 | Intense         | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.21 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           75 |      505 | 2024-07-17 | Hype            | W   | 1.000      | 0.450        | -                | 0.478 (0.215)    | 0 (0.000) |     5.13 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           74 |      510 | 2024-07-17 | Hype            | W   | 1.000      | 0.450        | -                | 0.478 (0.215)    | -         |     5.38 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           73 |      565 | 2024-07-16 | Sharks          | W   | 1.000      | 0.450        | -                | 0.558 (0.251)    | -         |     7.61 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           72 |      571 | 2024-07-16 | Sharks          | W   | 1.000      | 0.450        | -                | 0.558 (0.251)    | -         |     8.13 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           71 |      663 | 2024-07-13 | Legacy          | L   | 1.000      | -            | -                | -                | -         |   -19.77 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           70 |      692 | 2024-07-11 | KRÜ             | W   | 1.000      | -            | -                | -                | -         |     4.90 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           69 |      727 | 2024-07-09 | Bounty Hunters  | W   | 1.000      | -            | -                | -                | -         |     7.40 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           68 |      750 | 2024-07-08 | SPORT           | W   | 1.000      | -            | -                | -                | -         |     2.34 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           67 |      866 | 2024-06-15 | fnatic          | L   | 0.894      | -            | -                | -                | -         |    -4.58 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           66 |      899 | 2024-06-14 | KOI             | L   | 0.888      | -            | -                | -                | -         |   -16.78 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           65 |      905 | 2024-06-14 | fnatic          | W   | 0.887      | 0.548        | 0.371 (0.180)    | 0.633 (0.308)    | 1 (0.887) |    23.35 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           64 |     1053 | 2024-06-09 | BESTIA          | L   | 0.854      | -            | -                | -                | -         |   -18.41 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           63 |     1058 | 2024-06-09 | Imperial        | L   | 0.853      | -            | -                | -                | -         |    -8.69 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           62 |     1191 | 2024-06-07 | Intense         | W   | 0.839      | -            | -                | -                | -         |     2.31 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           61 |     1231 | 2024-06-06 | Imperial        | W   | 0.834      | 0.450        | 0.243 (0.091)    | 0.685 (0.257)    | -         |    17.48 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           60 |     1302 | 2024-06-05 | 9z              | W   | 0.827      | 0.450        | 0.408 (0.152)    | 0.625 (0.233)    | -         |    22.45 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           59 |     1716 | 2024-05-21 | Sharks          | L   | 0.727      | -            | -                | -                | -         |   -16.16 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           58 |     1718 | 2024-05-21 | Sharks          | W   | 0.727      | -            | -                | -                | -         |     6.66 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           57 |     1749 | 2024-05-20 | Fluxo           | L   | 0.721      | -            | -                | -                | -         |   -13.35 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           56 |     1752 | 2024-05-20 | Fluxo           | W   | 0.720      | 0.450        | 0.126 (0.041)    | 0.685 (0.222)    | -         |     9.42 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           55 |     1785 | 2024-05-19 | 9z              | W   | 0.713      | 0.371        | 0.408 (0.108)    | -                | -         |    19.67 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           54 |     1806 | 2024-05-18 | ODDIK           | W   | 0.707      | 0.371        | 0.097 (0.025)    | -                | -         |     6.11 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           53 |     1878 | 2024-05-16 | Fluxo           | W   | 0.694      | 0.371        | 0.126 (0.032)    | -                | -         |    10.36 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           52 |     1920 | 2024-05-15 | 9z              | L   | 0.688      | -            | -                | -                | -         |    -2.19 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           51 |     1922 | 2024-05-15 | 9z              | W   | 0.687      | 0.450        | 0.408 (0.126)    | -                | -         |    19.72 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           50 |     1979 | 2024-05-14 | Corinthians     | W   | 0.681      | -            | -                | -                | -         |     0.73 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           49 |     1984 | 2024-05-14 | Corinthians     | W   | 0.680      | -            | -                | -                | -         |     0.73 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           48 |     1997 | 2024-05-14 | BESTIA          | W   | 0.679      | 0.371        | 0.095 (0.024)    | -                | -         |     7.05 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           47 |     2015 | 2024-05-13 | Sharks          | L   | 0.674      | -            | -                | -                | -         |   -13.96 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           46 |     2035 | 2024-05-12 | Vikings KR      | W   | 0.667      | -            | -                | -                | -         |     3.50 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           45 |     2043 | 2024-05-12 | FURIA Academy   | W   | 0.666      | -            | -                | -                | -         |     0.76 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           44 |     2099 | 2024-05-10 | paiN            | L   | 0.652      | -            | -                | -                | -         |    -3.48 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           43 |     2115 | 2024-05-09 | Intense         | W   | 0.647      | -            | -                | -                | -         |     2.37 | dav1deuS, destiny, hardzao, nython, venomzera  |
|           42 |     2133 | 2024-05-08 | paiN            | L   | 0.641      | -            | -                | -                | -         |    -3.26 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           41 |     2135 | 2024-05-08 | paiN            | W   | 0.641      | 0.450        | 0.333 (0.096)    | 0.797 (0.230)    | -         |    17.24 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           40 |     2136 | 2024-05-08 | Solid           | L   | 0.640      | -            | -                | -                | -         |   -15.62 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           39 |     2179 | 2024-05-06 | Intense         | W   | 0.625      | -            | -                | -                | -         |     2.28 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           38 |     2411 | 2024-04-25 | BESTIA          | W   | 0.554      | -            | -                | -                | -         |     5.04 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           37 |     2413 | 2024-04-25 | BESTIA          | W   | 0.554      | -            | -                | -                | -         |     5.25 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           36 |     2640 | 2024-04-17 | MIBR            | L   | 0.501      | -            | -                | -                | -         |    -1.98 | dav1deuS, hardzao, nython, righi, venomzera    |
|           35 |     2648 | 2024-04-17 | O PLANO         | W   | 0.500      | -            | -                | -                | -         |     0.65 | dav1deuS, hardzao, nython, righi, venomzera    |
|           34 |     2681 | 2024-04-16 | LaChampionsLiga | W   | 0.494      | -            | -                | -                | -         |     0.30 | dav1deuS, hardzao, nython, righi, venomzera    |
|           33 |     2731 | 2024-04-13 | Imperial        | L   | 0.474      | -            | -                | -                | -         |    -3.69 | dav1deuS, hardzao, nython, righi, venomzera    |
|           32 |     2750 | 2024-04-12 | W7M             | W   | 0.466      | -            | -                | -                | -         |     2.69 | dav1deuS, hardzao, nython, righi, venomzera    |
|           31 |     2806 | 2024-04-10 | 2GAME           | W   | 0.454      | -            | -                | -                | -         |     1.22 | dav1deuS, hardzao, nython, righi, venomzera    |
|           30 |     2809 | 2024-04-10 | 2GAME           | W   | 0.454      | -            | -                | -                | -         |     1.23 | dav1deuS, hardzao, nython, righi, venomzera    |
|           29 |     2812 | 2024-04-10 | paiN            | L   | 0.453      | -            | -                | -                | -         |    -1.93 | dav1deuS, hardzao, nython, righi, venomzera    |
|           28 |     2859 | 2024-04-09 | W7M             | W   | 0.447      | -            | -                | -                | -         |     2.65 | dav1deuS, hardzao, nython, righi, venomzera    |
|           27 |     2864 | 2024-04-09 | W7M             | W   | 0.447      | -            | -                | -                | -         |     2.72 | dav1deuS, hardzao, nython, righi, venomzera    |
|           26 |     2867 | 2024-04-09 | MIBR            | L   | 0.446      | -            | -                | -                | -         |    -1.95 | dav1deuS, hardzao, nython, righi, venomzera    |
|           25 |     2898 | 2024-04-08 | BESTIA          | W   | 0.440      | -            | -                | -                | -         |     4.83 | dav1deuS, hardzao, nython, righi, venomzera    |
|           24 |     2904 | 2024-04-08 | Bounty Hunters  | W   | 0.439      | -            | -                | -                | -         |     3.51 | dav1deuS, hardzao, nython, righi, venomzera    |
|           23 |     2934 | 2024-04-07 | Imperial        | L   | 0.434      | -            | -                | -                | -         |    -3.17 | dav1deuS, hardzao, nython, righi, venomzera    |
|           22 |     2953 | 2024-04-06 | W7M             | L   | 0.426      | -            | -                | -                | -         |   -10.96 | dav1deuS, hardzao, nython, righi, venomzera    |
|           21 |     2992 | 2024-04-04 | Case            | L   | 0.414      | -            | -                | -                | -         |    -9.81 | dav1deuS, hardzao, nython, righi, venomzera    |
|           20 |     2997 | 2024-04-04 | Case            | W   | 0.414      | -            | -                | -                | -         |     3.25 | dav1deuS, hardzao, nython, righi, venomzera    |
|           19 |     3013 | 2024-04-04 | Fluxo           | W   | 0.412      | -            | -                | -                | -         |     5.57 | dav1deuS, hardzao, nython, righi, venomzera    |
|           18 |     3033 | 2024-04-03 | ODDIK           | W   | 0.407      | -            | -                | -                | -         |     4.37 | dav1deuS, hardzao, nython, righi, venomzera    |
|           17 |     3036 | 2024-04-03 | ODDIK           | W   | 0.407      | -            | -                | -                | -         |     4.51 | dav1deuS, hardzao, nython, righi, venomzera    |
|           16 |     3321 | 2024-03-18 | ODDIK           | W   | 0.300      | -            | -                | -                | -         |     3.44 | dav1deuS, destiny, hardzao, nython, venomzera  |
|           15 |     3364 | 2024-03-16 | ODDIK           | W   | 0.287      | -            | -                | -                | -         |     3.33 | dav1deuS, destiny, hardzao, nython, venomzera  |
|           14 |     3381 | 2024-03-15 | Case            | W   | 0.280      | -            | -                | -                | -         |     2.52 | dav1deuS, destiny, hardzao, nython, venomzera  |
|           13 |     3413 | 2024-03-14 | Solid           | L   | 0.273      | -            | -                | -                | -         |    -6.46 | dav1deuS, destiny, hardzao, nython, venomzera  |
|           12 |     3422 | 2024-03-14 | Flamengo        | W   | 0.272      | -            | -                | -                | -         |     0.30 | dav1deuS, destiny, hardzao, nython, venomzera  |
|           11 |     3441 | 2024-03-13 | Case            | W   | 0.267      | -            | -                | -                | -         |     2.38 | dav1deuS, destiny, hardzao, nython, venomzera  |
|           10 |     3453 | 2024-03-13 | Galorys         | W   | 0.266      | -            | -                | -                | -         |     2.02 | dav1deuS, destiny, hardzao, nython, venomzera  |
|            9 |     3485 | 2024-03-12 | BESTIA          | W   | 0.259      | -            | -                | -                | -         |     3.28 | dav1deuS, destiny, hardzao, nython, venomzera  |
|            8 |     3503 | 2024-03-11 | Corinthians     | W   | 0.253      | -            | -                | -                | -         |     0.31 | dav1deuS, destiny, hardzao, nython, venomzera  |
|            7 |     3539 | 2024-03-09 | W7M             | W   | 0.241      | -            | -                | -                | -         |     1.53 | dav1deuS, destiny, hardzao, nython, venomzera  |
|            6 |     3586 | 2024-03-07 | VELOX           | W   | 0.227      | -            | -                | -                | -         |     0.15 | dav1deuS, destiny, hardzao, nython, venomzera  |
|            5 |     3704 | 2024-03-03 | ODDIK           | L   | 0.200      | -            | -                | -                | -         |    -3.91 | dav1deuS, destiny, hardzao, nython, venomzera  |
|            4 |     3736 | 2024-03-02 | paiN            | L   | 0.192      | -            | -                | -                | -         |    -0.78 | dav1deuS, destiny, hardzao, nython, venomzera  |
|            3 |     3751 | 2024-03-01 | Wildcard        | W   | 0.187      | -            | -                | -                | 1 (0.187) |     1.56 | dav1deuS, destiny, hardzao, nython, venomzera  |
|            2 |     4152 | 2024-02-13 | Imperial        | L   | 0.074      | -            | -                | -                | -         |    -0.57 | dav1deuS, destiny, hardzao, nython, venomzera  |
|            1 |     4155 | 2024-02-13 | Imperial        | W   | 0.074      | -            | -                | -                | -         |     1.78 | dav1deuS, destiny, hardzao, nython, venomzera  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($26,084.84)
- Divide that value by the 5th highest value among all rosters ($331,608.80)
- The final value (0.08) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-14 |      1.000 | $2,000.00      | $2,000.00       |
| 2024-06-16 |      0.901 | $1,500.00      | $1,351.37       |
| 2024-06-10 |      0.861 | $750.00        | $645.46         |
| 2024-06-09 |      0.853 | $11,500.00     | $9,814.24       |
| 2024-05-19 |      0.713 | $10,000.00     | $7,126.71       |
| 2024-03-18 |      0.300 | $3,500.00      | $1,048.66       |
| 2024-03-14 |      0.273 | $15,000.00     | $4,098.40       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
