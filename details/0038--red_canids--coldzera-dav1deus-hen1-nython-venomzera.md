### Roster Details<br />
Team Name: RED Canids<br />
Roster: coldzera, dav1deuS, HEN1, nython, venomzera<br />
Global Rank: [38](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [9]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1142.8<br />
<br />
Final Rank Value (1142.8) = Starting Rank Value (1075.6) + Head To Head Adjustments (67.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.473[<sup>1</sup>](#table2)
- Bounty Collected: 0.480[<sup>2</sup>](#table1)
- Opponent Network: 0.249[<sup>2</sup>](#table1)
- LAN Wins: 0.116[<sup>2</sup>](#table1)

The average of these factors is 0.329<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1075.6
- 400 + ( ( 0.329 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 1075.6


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
|           88 |       49 | 2024-08-03 | ODDIK           | L   | 1.000      | -            | -                | -                | -         |   -18.23 | coldzera, dav1deuS, HEN1, nython, venomzera    |
|           87 |       56 | 2024-08-03 | Vikings KR      | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.72 | coldzera, dav1deuS, HEN1, nython, venomzera    |
|           86 |      284 | 2024-07-28 | MIBR            | L   | 1.000      | -            | -                | -                | -         |    -7.38 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           85 |      289 | 2024-07-28 | paiN            | L   | 1.000      | -            | -                | -                | -         |    -8.05 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           84 |      344 | 2024-07-26 | ODDIK           | L   | 1.000      | -            | -                | -                | -         |   -22.49 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           83 |      411 | 2024-07-24 | Fluxo           | W   | 1.000      | -            | -                | -                | 0 (0.000) |    15.48 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           82 |      413 | 2024-07-24 | ODDIK           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.69 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           81 |      445 | 2024-07-23 | KRÜ             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.08 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           80 |      448 | 2024-07-23 | LaChampionsLiga | W   | 1.000      | -            | -                | -                | 0 (0.000) |     0.42 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           79 |      486 | 2024-07-22 | paiN Academy    | W   | 1.000      | -            | -                | -                | 0 (0.000) |     0.41 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           78 |      509 | 2024-07-21 | BESTIA          | L   | 1.000      | -            | -                | -                | -         |   -23.59 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           77 |      540 | 2024-07-20 | Case            | W   | 1.000      | 0.384        | -                | 0.795 (0.306)    | 0 (0.000) |     5.31 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           76 |      575 | 2024-07-19 | Intense         | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.36 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           75 |      680 | 2024-07-17 | Hype            | W   | 1.000      | 0.450        | -                | 0.485 (0.218)    | -         |     5.37 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           74 |      685 | 2024-07-17 | Hype            | W   | 1.000      | 0.450        | -                | 0.485 (0.218)    | -         |     5.65 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           73 |      740 | 2024-07-16 | Sharks          | W   | 1.000      | 0.450        | -                | 0.558 (0.251)    | -         |     7.84 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           72 |      746 | 2024-07-16 | Sharks          | W   | 1.000      | 0.450        | -                | 0.558 (0.251)    | -         |     8.38 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           71 |      838 | 2024-07-13 | Legacy          | L   | 1.000      | -            | -                | -                | -         |   -19.41 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           70 |      867 | 2024-07-11 | KRÜ             | W   | 1.000      | -            | -                | -                | -         |     5.27 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           69 |      902 | 2024-07-09 | Bounty Hunters  | W   | 1.000      | -            | -                | -                | -         |     7.70 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           68 |      925 | 2024-07-08 | SPORT           | W   | 1.000      | -            | -                | -                | -         |     2.48 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           67 |     1041 | 2024-06-15 | fnatic          | L   | 0.861      | -            | -                | -                | -         |    -4.42 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           66 |     1074 | 2024-06-14 | KOI             | L   | 0.856      | -            | -                | -                | -         |   -16.24 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           65 |     1080 | 2024-06-14 | fnatic          | W   | 0.854      | 0.548        | 0.371 (0.174)    | 0.697 (0.326)    | 1 (0.854) |    22.50 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           64 |     1228 | 2024-06-09 | BESTIA          | L   | 0.822      | -            | -                | -                | -         |   -17.47 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           63 |     1233 | 2024-06-09 | Imperial        | L   | 0.821      | -            | -                | -                | -         |    -8.67 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           62 |     1366 | 2024-06-07 | Intense         | W   | 0.806      | -            | -                | -                | -         |     2.36 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           61 |     1406 | 2024-06-06 | Imperial        | W   | 0.801      | 0.450        | 0.234 (0.085)    | 0.674 (0.243)    | -         |    16.48 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           60 |     1477 | 2024-06-05 | 9z              | W   | 0.794      | 0.450        | 0.404 (0.145)    | 0.607 (0.217)    | -         |    21.53 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           59 |     1891 | 2024-05-21 | Sharks          | L   | 0.694      | -            | -                | -                | -         |   -15.23 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           58 |     1893 | 2024-05-21 | Sharks          | W   | 0.694      | -            | -                | -                | -         |     6.59 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           57 |     1924 | 2024-05-20 | Fluxo           | L   | 0.688      | -            | -                | -                | -         |   -12.57 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           56 |     1927 | 2024-05-20 | Fluxo           | W   | 0.688      | 0.450        | 0.123 (0.038)    | 0.716 (0.221)    | -         |     9.20 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           55 |     1960 | 2024-05-19 | 9z              | W   | 0.680      | 0.371        | 0.404 (0.102)    | -                | -         |    18.70 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           54 |     1981 | 2024-05-18 | ODDIK           | W   | 0.674      | 0.371        | 0.099 (0.025)    | -                | -         |     6.08 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           53 |     2053 | 2024-05-16 | Fluxo           | W   | 0.661      | 0.371        | 0.123 (0.030)    | -                | -         |    10.03 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           52 |     2095 | 2024-05-15 | 9z              | L   | 0.655      | -            | -                | -                | -         |    -2.17 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           51 |     2097 | 2024-05-15 | 9z              | W   | 0.655      | 0.450        | 0.404 (0.119)    | -                | -         |    18.70 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           50 |     2154 | 2024-05-14 | Corinthians     | W   | 0.648      | -            | -                | -                | -         |     0.72 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           49 |     2159 | 2024-05-14 | Corinthians     | W   | 0.648      | -            | -                | -                | -         |     0.72 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           48 |     2172 | 2024-05-14 | BESTIA          | W   | 0.646      | 0.371        | 0.096 (0.023)    | -                | -         |     6.96 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           47 |     2190 | 2024-05-13 | Sharks          | L   | 0.641      | -            | -                | -                | -         |   -13.09 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           46 |     2210 | 2024-05-12 | Vikings KR      | W   | 0.635      | -            | -                | -                | -         |     3.52 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           45 |     2218 | 2024-05-12 | FURIA Academy   | W   | 0.633      | -            | -                | -                | -         |     0.76 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           44 |     2274 | 2024-05-10 | paiN            | L   | 0.619      | -            | -                | -                | -         |    -3.44 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           43 |     2290 | 2024-05-09 | Intense         | W   | 0.614      | -            | -                | -                | -         |     2.39 | dav1deuS, destiny, hardzao, nython, venomzera  |
|           42 |     2308 | 2024-05-08 | paiN            | L   | 0.608      | -            | -                | -                | -         |    -3.24 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           41 |     2310 | 2024-05-08 | paiN            | W   | 0.608      | 0.450        | 0.325 (0.089)    | 0.856 (0.234)    | -         |    16.21 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           40 |     2311 | 2024-05-08 | Solid           | L   | 0.607      | -            | -                | -                | -         |   -14.62 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           39 |     2354 | 2024-05-06 | Intense         | W   | 0.592      | -            | -                | -                | -         |     2.29 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           38 |     2586 | 2024-04-25 | BESTIA          | W   | 0.521      | -            | -                | -                | -         |     4.99 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           37 |     2588 | 2024-04-25 | BESTIA          | W   | 0.521      | -            | -                | -                | -         |     5.19 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           36 |     2815 | 2024-04-17 | MIBR            | L   | 0.468      | -            | -                | -                | -         |    -1.90 | dav1deuS, hardzao, nython, righi, venomzera    |
|           35 |     2823 | 2024-04-17 | O PLANO         | W   | 0.467      | -            | -                | -                | -         |     0.63 | dav1deuS, hardzao, nython, righi, venomzera    |
|           34 |     2856 | 2024-04-16 | LaChampionsLiga | W   | 0.461      | -            | -                | -                | -         |     0.30 | dav1deuS, hardzao, nython, righi, venomzera    |
|           33 |     2906 | 2024-04-13 | Imperial        | L   | 0.441      | -            | -                | -                | -         |    -3.70 | dav1deuS, hardzao, nython, righi, venomzera    |
|           32 |     2925 | 2024-04-12 | W7M             | W   | 0.433      | -            | -                | -                | -         |     2.63 | dav1deuS, hardzao, nython, righi, venomzera    |
|           31 |     2981 | 2024-04-10 | 2GAME           | W   | 0.421      | -            | -                | -                | -         |     1.15 | dav1deuS, hardzao, nython, righi, venomzera    |
|           30 |     2984 | 2024-04-10 | 2GAME           | W   | 0.421      | -            | -                | -                | -         |     1.17 | dav1deuS, hardzao, nython, righi, venomzera    |
|           29 |     2987 | 2024-04-10 | paiN            | L   | 0.420      | -            | -                | -                | -         |    -1.91 | dav1deuS, hardzao, nython, righi, venomzera    |
|           28 |     3034 | 2024-04-09 | W7M             | W   | 0.415      | -            | -                | -                | -         |     2.58 | dav1deuS, hardzao, nython, righi, venomzera    |
|           27 |     3039 | 2024-04-09 | W7M             | W   | 0.414      | -            | -                | -                | -         |     2.64 | dav1deuS, hardzao, nython, righi, venomzera    |
|           26 |     3042 | 2024-04-09 | MIBR            | L   | 0.413      | -            | -                | -                | -         |    -1.83 | dav1deuS, hardzao, nython, righi, venomzera    |
|           25 |     3073 | 2024-04-08 | BESTIA          | W   | 0.407      | -            | -                | -                | -         |     4.64 | dav1deuS, hardzao, nython, righi, venomzera    |
|           24 |     3079 | 2024-04-08 | Bounty Hunters  | W   | 0.406      | -            | -                | -                | -         |     3.40 | dav1deuS, hardzao, nython, righi, venomzera    |
|           23 |     3109 | 2024-04-07 | Imperial        | L   | 0.401      | -            | -                | -                | -         |    -3.20 | dav1deuS, hardzao, nython, righi, venomzera    |
|           22 |     3128 | 2024-04-06 | W7M             | L   | 0.393      | -            | -                | -                | -         |   -10.00 | dav1deuS, hardzao, nython, righi, venomzera    |
|           21 |     3167 | 2024-04-04 | Case            | L   | 0.381      | -            | -                | -                | -         |    -8.92 | dav1deuS, hardzao, nython, righi, venomzera    |
|           20 |     3172 | 2024-04-04 | Case            | W   | 0.381      | -            | -                | -                | -         |     3.11 | dav1deuS, hardzao, nython, righi, venomzera    |
|           19 |     3188 | 2024-04-04 | Fluxo           | W   | 0.379      | -            | -                | -                | -         |     5.30 | dav1deuS, hardzao, nython, righi, venomzera    |
|           18 |     3208 | 2024-04-03 | ODDIK           | W   | 0.375      | -            | -                | -                | -         |     4.19 | dav1deuS, hardzao, nython, righi, venomzera    |
|           17 |     3211 | 2024-04-03 | ODDIK           | W   | 0.374      | -            | -                | -                | -         |     4.31 | dav1deuS, hardzao, nython, righi, venomzera    |
|           16 |     3496 | 2024-03-18 | ODDIK           | W   | 0.267      | -            | -                | -                | -         |     3.17 | dav1deuS, destiny, hardzao, nython, venomzera  |
|           15 |     3539 | 2024-03-16 | ODDIK           | W   | 0.254      | -            | -                | -                | -         |     3.05 | dav1deuS, destiny, hardzao, nython, venomzera  |
|           14 |     3556 | 2024-03-15 | Case            | W   | 0.247      | -            | -                | -                | -         |     2.30 | dav1deuS, destiny, hardzao, nython, venomzera  |
|           13 |     3588 | 2024-03-14 | Solid           | L   | 0.240      | -            | -                | -                | -         |    -5.59 | dav1deuS, destiny, hardzao, nython, venomzera  |
|           12 |     3597 | 2024-03-14 | Flamengo        | W   | 0.239      | -            | -                | -                | -         |     0.27 | dav1deuS, destiny, hardzao, nython, venomzera  |
|           11 |     3616 | 2024-03-13 | Case            | W   | 0.234      | -            | -                | -                | -         |     2.16 | dav1deuS, destiny, hardzao, nython, venomzera  |
|           10 |     3628 | 2024-03-13 | Galorys         | W   | 0.233      | -            | -                | -                | -         |     1.90 | dav1deuS, destiny, hardzao, nython, venomzera  |
|            9 |     3660 | 2024-03-12 | BESTIA          | W   | 0.226      | -            | -                | -                | -         |     2.95 | dav1deuS, destiny, hardzao, nython, venomzera  |
|            8 |     3678 | 2024-03-11 | Corinthians     | W   | 0.220      | -            | -                | -                | -         |     0.28 | dav1deuS, destiny, hardzao, nython, venomzera  |
|            7 |     3714 | 2024-03-09 | W7M             | W   | 0.208      | -            | -                | -                | -         |     1.39 | dav1deuS, destiny, hardzao, nython, venomzera  |
|            6 |     3761 | 2024-03-07 | VELOX           | W   | 0.195      | -            | -                | -                | -         |     0.14 | dav1deuS, destiny, hardzao, nython, venomzera  |
|            5 |     3879 | 2024-03-03 | ODDIK           | L   | 0.167      | -            | -                | -                | -         |    -3.20 | dav1deuS, destiny, hardzao, nython, venomzera  |
|            4 |     3911 | 2024-03-02 | paiN            | L   | 0.159      | -            | -                | -                | -         |    -0.69 | dav1deuS, destiny, hardzao, nython, venomzera  |
|            3 |     3926 | 2024-03-01 | Wildcard        | W   | 0.154      | -            | -                | -                | 1 (0.154) |     1.19 | dav1deuS, destiny, hardzao, nython, venomzera  |
|            2 |     4327 | 2024-02-13 | Imperial        | L   | 0.042      | -            | -                | -                | -         |    -0.35 | dav1deuS, destiny, hardzao, nython, venomzera  |
|            1 |     4330 | 2024-02-13 | Imperial        | W   | 0.041      | -            | -                | -                | -         |     0.96 | dav1deuS, destiny, hardzao, nython, venomzera  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($24,698.61)
- Divide that value by the 5th highest value among all rosters ($321,880.58)
- The final value (0.08) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-14 |      1.000 | $2,000.00      | $2,000.00       |
| 2024-06-16 |      0.868 | $1,500.00      | $1,302.15       |
| 2024-06-10 |      0.828 | $750.00        | $620.85         |
| 2024-06-09 |      0.821 | $11,500.00     | $9,436.92       |
| 2024-05-19 |      0.680 | $10,000.00     | $6,798.61       |
| 2024-03-18 |      0.267 | $3,500.00      | $933.82         |
| 2024-03-14 |      0.240 | $15,000.00     | $3,606.25       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
