### Roster Details<br />
Team Name: RED Canids<br />
Roster: coldzera, dav1deuS, HEN1, nython, venomzera<br />
Global Rank: [38](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [9]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1142.9<br />
<br />
Final Rank Value (1142.9) = Starting Rank Value (1075.6) + Head To Head Adjustments (67.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.473[<sup>1</sup>](#table2)
- Bounty Collected: 0.480[<sup>2</sup>](#table1)
- Opponent Network: 0.249[<sup>2</sup>](#table1)
- LAN Wins: 0.116[<sup>2</sup>](#table1)

The average of these factors is 0.330<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1075.6
- 400 + ( ( 0.330 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 1075.6


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
|           88 |       48 | 2024-08-03 | ODDIK           | L   | 1.000      | -            | -                | -                | -         |   -18.23 | coldzera, dav1deuS, HEN1, nython, venomzera    |
|           87 |       55 | 2024-08-03 | Vikings KR      | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.72 | coldzera, dav1deuS, HEN1, nython, venomzera    |
|           86 |      283 | 2024-07-28 | MIBR            | L   | 1.000      | -            | -                | -                | -         |    -7.38 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           85 |      288 | 2024-07-28 | paiN            | L   | 1.000      | -            | -                | -                | -         |    -8.05 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           84 |      343 | 2024-07-26 | ODDIK           | L   | 1.000      | -            | -                | -                | -         |   -22.50 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           83 |      410 | 2024-07-24 | Fluxo           | W   | 1.000      | -            | -                | -                | 0 (0.000) |    15.47 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           82 |      412 | 2024-07-24 | ODDIK           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.69 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           81 |      444 | 2024-07-23 | KRÜ             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.08 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           80 |      447 | 2024-07-23 | LaChampionsLiga | W   | 1.000      | -            | -                | -                | 0 (0.000) |     0.42 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           79 |      485 | 2024-07-22 | paiN Academy    | W   | 1.000      | -            | -                | -                | 0 (0.000) |     0.41 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           78 |      508 | 2024-07-21 | BESTIA          | L   | 1.000      | -            | -                | -                | -         |   -23.59 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           77 |      539 | 2024-07-20 | Case            | W   | 1.000      | 0.384        | -                | 0.795 (0.306)    | 0 (0.000) |     5.31 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           76 |      574 | 2024-07-19 | Intense         | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.35 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           75 |      679 | 2024-07-17 | Hype            | W   | 1.000      | 0.450        | -                | 0.485 (0.218)    | -         |     5.37 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           74 |      684 | 2024-07-17 | Hype            | W   | 1.000      | 0.450        | -                | 0.485 (0.218)    | -         |     5.64 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           73 |      739 | 2024-07-16 | Sharks          | W   | 1.000      | 0.450        | -                | 0.558 (0.251)    | -         |     7.83 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           72 |      745 | 2024-07-16 | Sharks          | W   | 1.000      | 0.450        | -                | 0.558 (0.251)    | -         |     8.38 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           71 |      837 | 2024-07-13 | Legacy          | L   | 1.000      | -            | -                | -                | -         |   -19.41 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           70 |      866 | 2024-07-11 | KRÜ             | W   | 1.000      | -            | -                | -                | -         |     5.27 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           69 |      901 | 2024-07-09 | Bounty Hunters  | W   | 1.000      | -            | -                | -                | -         |     7.70 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           68 |      924 | 2024-07-08 | SPORT           | W   | 1.000      | -            | -                | -                | -         |     2.48 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           67 |     1040 | 2024-06-15 | fnatic          | L   | 0.862      | -            | -                | -                | -         |    -4.42 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           66 |     1073 | 2024-06-14 | KOI             | L   | 0.856      | -            | -                | -                | -         |   -16.25 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           65 |     1079 | 2024-06-14 | fnatic          | W   | 0.854      | 0.548        | 0.371 (0.174)    | 0.697 (0.326)    | 1 (0.854) |    22.51 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           64 |     1227 | 2024-06-09 | BESTIA          | L   | 0.822      | -            | -                | -                | -         |   -17.48 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           63 |     1232 | 2024-06-09 | Imperial        | L   | 0.821      | -            | -                | -                | -         |    -8.67 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           62 |     1365 | 2024-06-07 | Intense         | W   | 0.807      | -            | -                | -                | -         |     2.36 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           61 |     1405 | 2024-06-06 | Imperial        | W   | 0.801      | 0.450        | 0.235 (0.085)    | 0.674 (0.243)    | -         |    16.49 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           60 |     1476 | 2024-06-05 | 9z              | W   | 0.795      | 0.450        | 0.404 (0.145)    | 0.607 (0.217)    | -         |    21.54 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           59 |     1890 | 2024-05-21 | Sharks          | L   | 0.695      | -            | -                | -                | -         |   -15.24 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           58 |     1892 | 2024-05-21 | Sharks          | W   | 0.694      | -            | -                | -                | -         |     6.59 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           57 |     1923 | 2024-05-20 | Fluxo           | L   | 0.688      | -            | -                | -                | -         |   -12.58 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           56 |     1926 | 2024-05-20 | Fluxo           | W   | 0.688      | 0.450        | 0.123 (0.038)    | 0.716 (0.222)    | -         |     9.20 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           55 |     1959 | 2024-05-19 | 9z              | W   | 0.680      | 0.371        | 0.404 (0.102)    | -                | -         |    18.71 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           54 |     1980 | 2024-05-18 | ODDIK           | W   | 0.674      | 0.371        | 0.099 (0.025)    | -                | -         |     6.08 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           53 |     2052 | 2024-05-16 | Fluxo           | W   | 0.661      | 0.371        | 0.123 (0.030)    | -                | -         |    10.03 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           52 |     2094 | 2024-05-15 | 9z              | L   | 0.655      | -            | -                | -                | -         |    -2.17 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           51 |     2096 | 2024-05-15 | 9z              | W   | 0.655      | 0.450        | 0.404 (0.119)    | -                | -         |    18.71 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           50 |     2153 | 2024-05-14 | Corinthians     | W   | 0.648      | -            | -                | -                | -         |     0.72 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           49 |     2158 | 2024-05-14 | Corinthians     | W   | 0.648      | -            | -                | -                | -         |     0.73 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           48 |     2171 | 2024-05-14 | BESTIA          | W   | 0.647      | 0.371        | 0.096 (0.023)    | -                | -         |     6.96 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           47 |     2189 | 2024-05-13 | Sharks          | L   | 0.641      | -            | -                | -                | -         |   -13.10 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           46 |     2209 | 2024-05-12 | Vikings KR      | W   | 0.635      | -            | -                | -                | -         |     3.52 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           45 |     2217 | 2024-05-12 | FURIA Academy   | W   | 0.634      | -            | -                | -                | -         |     0.76 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           44 |     2273 | 2024-05-10 | paiN            | L   | 0.619      | -            | -                | -                | -         |    -3.44 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           43 |     2289 | 2024-05-09 | Intense         | W   | 0.614      | -            | -                | -                | -         |     2.39 | dav1deuS, destiny, hardzao, nython, venomzera  |
|           42 |     2307 | 2024-05-08 | paiN            | L   | 0.609      | -            | -                | -                | -         |    -3.24 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           41 |     2309 | 2024-05-08 | paiN            | W   | 0.608      | 0.450        | 0.325 (0.089)    | 0.856 (0.234)    | -         |    16.23 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           40 |     2310 | 2024-05-08 | Solid           | L   | 0.608      | -            | -                | -                | -         |   -14.63 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           39 |     2353 | 2024-05-06 | Intense         | W   | 0.593      | -            | -                | -                | -         |     2.29 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           38 |     2585 | 2024-04-25 | BESTIA          | W   | 0.522      | -            | -                | -                | -         |     4.99 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           37 |     2587 | 2024-04-25 | BESTIA          | W   | 0.521      | -            | -                | -                | -         |     5.19 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           36 |     2814 | 2024-04-17 | MIBR            | L   | 0.468      | -            | -                | -                | -         |    -1.90 | dav1deuS, hardzao, nython, righi, venomzera    |
|           35 |     2822 | 2024-04-17 | O PLANO         | W   | 0.468      | -            | -                | -                | -         |     0.64 | dav1deuS, hardzao, nython, righi, venomzera    |
|           34 |     2855 | 2024-04-16 | LaChampionsLiga | W   | 0.462      | -            | -                | -                | -         |     0.30 | dav1deuS, hardzao, nython, righi, venomzera    |
|           33 |     2905 | 2024-04-13 | Imperial        | L   | 0.442      | -            | -                | -                | -         |    -3.70 | dav1deuS, hardzao, nython, righi, venomzera    |
|           32 |     2924 | 2024-04-12 | W7M             | W   | 0.433      | -            | -                | -                | -         |     2.63 | dav1deuS, hardzao, nython, righi, venomzera    |
|           31 |     2980 | 2024-04-10 | 2GAME           | W   | 0.422      | -            | -                | -                | -         |     1.15 | dav1deuS, hardzao, nython, righi, venomzera    |
|           30 |     2983 | 2024-04-10 | 2GAME           | W   | 0.421      | -            | -                | -                | -         |     1.17 | dav1deuS, hardzao, nython, righi, venomzera    |
|           29 |     2986 | 2024-04-10 | paiN            | L   | 0.420      | -            | -                | -                | -         |    -1.91 | dav1deuS, hardzao, nython, righi, venomzera    |
|           28 |     3033 | 2024-04-09 | W7M             | W   | 0.415      | -            | -                | -                | -         |     2.58 | dav1deuS, hardzao, nython, righi, venomzera    |
|           27 |     3038 | 2024-04-09 | W7M             | W   | 0.415      | -            | -                | -                | -         |     2.64 | dav1deuS, hardzao, nython, righi, venomzera    |
|           26 |     3041 | 2024-04-09 | MIBR            | L   | 0.414      | -            | -                | -                | -         |    -1.83 | dav1deuS, hardzao, nython, righi, venomzera    |
|           25 |     3072 | 2024-04-08 | BESTIA          | W   | 0.408      | -            | -                | -                | -         |     4.64 | dav1deuS, hardzao, nython, righi, venomzera    |
|           24 |     3078 | 2024-04-08 | Bounty Hunters  | W   | 0.407      | -            | -                | -                | -         |     3.40 | dav1deuS, hardzao, nython, righi, venomzera    |
|           23 |     3108 | 2024-04-07 | Imperial        | L   | 0.401      | -            | -                | -                | -         |    -3.20 | dav1deuS, hardzao, nython, righi, venomzera    |
|           22 |     3127 | 2024-04-06 | W7M             | L   | 0.393      | -            | -                | -                | -         |   -10.01 | dav1deuS, hardzao, nython, righi, venomzera    |
|           21 |     3166 | 2024-04-04 | Case            | L   | 0.382      | -            | -                | -                | -         |    -8.93 | dav1deuS, hardzao, nython, righi, venomzera    |
|           20 |     3171 | 2024-04-04 | Case            | W   | 0.381      | -            | -                | -                | -         |     3.12 | dav1deuS, hardzao, nython, righi, venomzera    |
|           19 |     3187 | 2024-04-04 | Fluxo           | W   | 0.379      | -            | -                | -                | -         |     5.31 | dav1deuS, hardzao, nython, righi, venomzera    |
|           18 |     3207 | 2024-04-03 | ODDIK           | W   | 0.375      | -            | -                | -                | -         |     4.19 | dav1deuS, hardzao, nython, righi, venomzera    |
|           17 |     3210 | 2024-04-03 | ODDIK           | W   | 0.375      | -            | -                | -                | -         |     4.32 | dav1deuS, hardzao, nython, righi, venomzera    |
|           16 |     3495 | 2024-03-18 | ODDIK           | W   | 0.267      | -            | -                | -                | -         |     3.18 | dav1deuS, destiny, hardzao, nython, venomzera  |
|           15 |     3538 | 2024-03-16 | ODDIK           | W   | 0.254      | -            | -                | -                | -         |     3.06 | dav1deuS, destiny, hardzao, nython, venomzera  |
|           14 |     3555 | 2024-03-15 | Case            | W   | 0.247      | -            | -                | -                | -         |     2.30 | dav1deuS, destiny, hardzao, nython, venomzera  |
|           13 |     3587 | 2024-03-14 | Solid           | L   | 0.241      | -            | -                | -                | -         |    -5.60 | dav1deuS, destiny, hardzao, nython, venomzera  |
|           12 |     3596 | 2024-03-14 | Flamengo        | W   | 0.240      | -            | -                | -                | -         |     0.27 | dav1deuS, destiny, hardzao, nython, venomzera  |
|           11 |     3615 | 2024-03-13 | Case            | W   | 0.234      | -            | -                | -                | -         |     2.16 | dav1deuS, destiny, hardzao, nython, venomzera  |
|           10 |     3627 | 2024-03-13 | Galorys         | W   | 0.234      | -            | -                | -                | -         |     1.90 | dav1deuS, destiny, hardzao, nython, venomzera  |
|            9 |     3659 | 2024-03-12 | BESTIA          | W   | 0.227      | -            | -                | -                | -         |     2.95 | dav1deuS, destiny, hardzao, nython, venomzera  |
|            8 |     3677 | 2024-03-11 | Corinthians     | W   | 0.220      | -            | -                | -                | -         |     0.28 | dav1deuS, destiny, hardzao, nython, venomzera  |
|            7 |     3713 | 2024-03-09 | W7M             | W   | 0.208      | -            | -                | -                | -         |     1.39 | dav1deuS, destiny, hardzao, nython, venomzera  |
|            6 |     3760 | 2024-03-07 | VELOX           | W   | 0.195      | -            | -                | -                | -         |     0.14 | dav1deuS, destiny, hardzao, nython, venomzera  |
|            5 |     3878 | 2024-03-03 | ODDIK           | L   | 0.167      | -            | -                | -                | -         |    -3.21 | dav1deuS, destiny, hardzao, nython, venomzera  |
|            4 |     3910 | 2024-03-02 | paiN            | L   | 0.160      | -            | -                | -                | -         |    -0.69 | dav1deuS, destiny, hardzao, nython, venomzera  |
|            3 |     3925 | 2024-03-01 | Wildcard        | W   | 0.154      | -            | -                | -                | 1 (0.154) |     1.19 | dav1deuS, destiny, hardzao, nython, venomzera  |
|            2 |     4326 | 2024-02-13 | Imperial        | L   | 0.042      | -            | -                | -                | -         |    -0.35 | dav1deuS, destiny, hardzao, nython, venomzera  |
|            1 |     4329 | 2024-02-13 | Imperial        | W   | 0.042      | -            | -                | -                | -         |     0.97 | dav1deuS, destiny, hardzao, nython, venomzera  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($24,716.21)
- Divide that value by the 5th highest value among all rosters ($322,004.12)
- The final value (0.08) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-14 |      1.000 | $2,000.00      | $2,000.00       |
| 2024-06-16 |      0.869 | $1,500.00      | $1,302.78       |
| 2024-06-10 |      0.828 | $750.00        | $621.16         |
| 2024-06-09 |      0.821 | $11,500.00     | $9,441.71       |
| 2024-05-19 |      0.680 | $10,000.00     | $6,802.78       |
| 2024-03-18 |      0.267 | $3,500.00      | $935.28         |
| 2024-03-14 |      0.241 | $15,000.00     | $3,612.50       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
