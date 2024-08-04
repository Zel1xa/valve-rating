### Roster Details<br />
Team Name: RED Canids<br />
Roster: coldzera, dav1deuS, HEN1, nython, venomzera<br />
Global Rank: [39](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [9]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1144.8<br />
<br />
Final Rank Value (1144.8) = Starting Rank Value (1077.5) + Head To Head Adjustments (67.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.473[<sup>1</sup>](#table2)
- Bounty Collected: 0.482[<sup>2</sup>](#table1)
- Opponent Network: 0.253[<sup>2</sup>](#table1)
- LAN Wins: 0.117[<sup>2</sup>](#table1)

The average of these factors is 0.331<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1077.5
- 400 + ( ( 0.331 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 1077.5


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
|           88 |       22 | 2024-08-03 | ODDIK           | L   | 1.000      | -            | -                | -                | -         |   -18.26 | coldzera, dav1deuS, HEN1, nython, venomzera    |
|           87 |       29 | 2024-08-03 | Vikings KR      | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.70 | coldzera, dav1deuS, HEN1, nython, venomzera    |
|           86 |      257 | 2024-07-28 | MIBR            | L   | 1.000      | -            | -                | -                | -         |    -7.38 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           85 |      262 | 2024-07-28 | paiN            | L   | 1.000      | -            | -                | -                | -         |    -8.04 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           84 |      317 | 2024-07-26 | ODDIK           | L   | 1.000      | -            | -                | -                | -         |   -22.52 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           83 |      384 | 2024-07-24 | Fluxo           | W   | 1.000      | -            | -                | -                | 0 (0.000) |    15.47 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           82 |      386 | 2024-07-24 | ODDIK           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.66 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           81 |      418 | 2024-07-23 | KRÜ             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.05 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           80 |      421 | 2024-07-23 | LaChampionsLiga | W   | 1.000      | -            | -                | -                | 0 (0.000) |     0.41 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           79 |      459 | 2024-07-22 | paiN Academy    | W   | 1.000      | -            | -                | -                | 0 (0.000) |     0.41 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           78 |      482 | 2024-07-21 | BESTIA          | L   | 1.000      | -            | -                | -                | -         |   -23.61 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           77 |      513 | 2024-07-20 | Case            | W   | 1.000      | 0.384        | -                | 0.805 (0.309)    | 0 (0.000) |     5.28 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           76 |      548 | 2024-07-19 | Intense         | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.33 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           75 |      653 | 2024-07-17 | Hype            | W   | 1.000      | 0.450        | -                | 0.489 (0.220)    | -         |     5.33 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           74 |      658 | 2024-07-17 | Hype            | W   | 1.000      | 0.450        | -                | 0.489 (0.220)    | -         |     5.60 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           73 |      713 | 2024-07-16 | Sharks          | W   | 1.000      | 0.450        | -                | 0.565 (0.254)    | -         |     7.81 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           72 |      719 | 2024-07-16 | Sharks          | W   | 1.000      | 0.450        | -                | 0.565 (0.254)    | -         |     8.36 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           71 |      811 | 2024-07-13 | Legacy          | L   | 1.000      | -            | -                | -                | -         |   -19.42 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           70 |      840 | 2024-07-11 | KRÜ             | W   | 1.000      | -            | -                | -                | -         |     5.23 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           69 |      875 | 2024-07-09 | Bounty Hunters  | W   | 1.000      | -            | -                | -                | -         |     7.66 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           68 |      898 | 2024-07-08 | SPORT           | W   | 1.000      | -            | -                | -                | -         |     2.44 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           67 |     1014 | 2024-06-15 | fnatic          | L   | 0.869      | -            | -                | -                | -         |    -4.53 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           66 |     1047 | 2024-06-14 | KOI             | L   | 0.863      | -            | -                | -                | -         |   -16.42 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           65 |     1053 | 2024-06-14 | fnatic          | W   | 0.862      | 0.548        | 0.371 (0.175)    | 0.708 (0.335)    | 1 (0.862) |    22.62 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           64 |     1201 | 2024-06-09 | BESTIA          | L   | 0.829      | -            | -                | -                | -         |   -17.66 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           63 |     1206 | 2024-06-09 | Imperial        | L   | 0.828      | -            | -                | -                | -         |    -8.71 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           62 |     1339 | 2024-06-07 | Intense         | W   | 0.814      | -            | -                | -                | -         |     2.35 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           61 |     1379 | 2024-06-06 | Imperial        | W   | 0.809      | 0.450        | 0.236 (0.086)    | 0.685 (0.249)    | -         |    16.66 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           60 |     1450 | 2024-06-05 | 9z              | W   | 0.802      | 0.450        | 0.405 (0.146)    | 0.618 (0.223)    | -         |    21.71 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           59 |     1864 | 2024-05-21 | Sharks          | L   | 0.702      | -            | -                | -                | -         |   -15.42 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           58 |     1866 | 2024-05-21 | Sharks          | W   | 0.702      | -            | -                | -                | -         |     6.63 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           57 |     1897 | 2024-05-20 | Fluxo           | L   | 0.696      | -            | -                | -                | -         |   -12.72 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           56 |     1900 | 2024-05-20 | Fluxo           | W   | 0.695      | 0.450        | 0.124 (0.039)    | 0.724 (0.226)    | -         |     9.28 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           55 |     1933 | 2024-05-19 | 9z              | W   | 0.687      | 0.371        | 0.405 (0.103)    | -                | -         |    18.89 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           54 |     1954 | 2024-05-18 | ODDIK           | W   | 0.682      | 0.371        | 0.099 (0.025)    | -                | -         |     6.11 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           53 |     2026 | 2024-05-16 | Fluxo           | W   | 0.668      | 0.371        | 0.124 (0.031)    | -                | -         |    10.14 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           52 |     2068 | 2024-05-15 | 9z              | L   | 0.663      | -            | -                | -                | -         |    -2.20 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           51 |     2070 | 2024-05-15 | 9z              | W   | 0.662      | 0.450        | 0.405 (0.121)    | -                | -         |    18.91 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           50 |     2127 | 2024-05-14 | Corinthians     | W   | 0.655      | -            | -                | -                | -         |     0.72 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           49 |     2132 | 2024-05-14 | Corinthians     | W   | 0.655      | -            | -                | -                | -         |     0.73 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           48 |     2145 | 2024-05-14 | BESTIA          | W   | 0.654      | 0.371        | 0.095 (0.023)    | -                | -         |     7.00 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           47 |     2163 | 2024-05-13 | Sharks          | L   | 0.648      | -            | -                | -                | -         |   -13.26 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           46 |     2183 | 2024-05-12 | Vikings KR      | W   | 0.642      | -            | -                | -                | -         |     3.53 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           45 |     2191 | 2024-05-12 | FURIA Academy   | W   | 0.641      | -            | -                | -                | -         |     0.76 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           44 |     2247 | 2024-05-10 | paiN            | L   | 0.626      | -            | -                | -                | -         |    -3.46 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           43 |     2263 | 2024-05-09 | Intense         | W   | 0.621      | -            | -                | -                | -         |     2.39 | dav1deuS, destiny, hardzao, nython, venomzera  |
|           42 |     2281 | 2024-05-08 | paiN            | L   | 0.616      | -            | -                | -                | -         |    -3.25 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           41 |     2283 | 2024-05-08 | paiN            | W   | 0.615      | 0.450        | 0.327 (0.091)    | 0.867 (0.240)    | -         |    16.44 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           40 |     2284 | 2024-05-08 | Solid           | L   | 0.615      | -            | -                | -                | -         |   -14.82 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           39 |     2327 | 2024-05-06 | Intense         | W   | 0.600      | -            | -                | -                | -         |     2.29 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           38 |     2559 | 2024-04-25 | BESTIA          | W   | 0.529      | -            | -                | -                | -         |     5.02 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           37 |     2561 | 2024-04-25 | BESTIA          | W   | 0.529      | -            | -                | -                | -         |     5.22 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           36 |     2788 | 2024-04-17 | MIBR            | L   | 0.475      | -            | -                | -                | -         |    -1.91 | dav1deuS, hardzao, nython, righi, venomzera    |
|           35 |     2796 | 2024-04-17 | O PLANO         | W   | 0.475      | -            | -                | -                | -         |     0.64 | dav1deuS, hardzao, nython, righi, venomzera    |
|           34 |     2829 | 2024-04-16 | LaChampionsLiga | W   | 0.469      | -            | -                | -                | -         |     0.30 | dav1deuS, hardzao, nython, righi, venomzera    |
|           33 |     2879 | 2024-04-13 | Imperial        | L   | 0.449      | -            | -                | -                | -         |    -3.73 | dav1deuS, hardzao, nython, righi, venomzera    |
|           32 |     2898 | 2024-04-12 | W7M             | W   | 0.440      | -            | -                | -                | -         |     2.65 | dav1deuS, hardzao, nython, righi, venomzera    |
|           31 |     2954 | 2024-04-10 | 2GAME           | W   | 0.429      | -            | -                | -                | -         |     1.17 | dav1deuS, hardzao, nython, righi, venomzera    |
|           30 |     2957 | 2024-04-10 | 2GAME           | W   | 0.429      | -            | -                | -                | -         |     1.18 | dav1deuS, hardzao, nython, righi, venomzera    |
|           29 |     2960 | 2024-04-10 | paiN            | L   | 0.428      | -            | -                | -                | -         |    -1.92 | dav1deuS, hardzao, nython, righi, venomzera    |
|           28 |     3007 | 2024-04-09 | W7M             | W   | 0.422      | -            | -                | -                | -         |     2.61 | dav1deuS, hardzao, nython, righi, venomzera    |
|           27 |     3012 | 2024-04-09 | W7M             | W   | 0.422      | -            | -                | -                | -         |     2.67 | dav1deuS, hardzao, nython, righi, venomzera    |
|           26 |     3015 | 2024-04-09 | MIBR            | L   | 0.421      | -            | -                | -                | -         |    -1.85 | dav1deuS, hardzao, nython, righi, venomzera    |
|           25 |     3046 | 2024-04-08 | BESTIA          | W   | 0.415      | -            | -                | -                | -         |     4.70 | dav1deuS, hardzao, nython, righi, venomzera    |
|           24 |     3052 | 2024-04-08 | Bounty Hunters  | W   | 0.414      | -            | -                | -                | -         |     3.44 | dav1deuS, hardzao, nython, righi, venomzera    |
|           23 |     3082 | 2024-04-07 | Imperial        | L   | 0.408      | -            | -                | -                | -         |    -3.22 | dav1deuS, hardzao, nython, righi, venomzera    |
|           22 |     3101 | 2024-04-06 | W7M             | L   | 0.400      | -            | -                | -                | -         |   -10.21 | dav1deuS, hardzao, nython, righi, venomzera    |
|           21 |     3140 | 2024-04-04 | Case            | L   | 0.389      | -            | -                | -                | -         |    -9.12 | dav1deuS, hardzao, nython, righi, venomzera    |
|           20 |     3145 | 2024-04-04 | Case            | W   | 0.389      | -            | -                | -                | -         |     3.15 | dav1deuS, hardzao, nython, righi, venomzera    |
|           19 |     3161 | 2024-04-04 | Fluxo           | W   | 0.387      | -            | -                | -                | -         |     5.40 | dav1deuS, hardzao, nython, righi, venomzera    |
|           18 |     3181 | 2024-04-03 | ODDIK           | W   | 0.382      | -            | -                | -                | -         |     4.25 | dav1deuS, hardzao, nython, righi, venomzera    |
|           17 |     3184 | 2024-04-03 | ODDIK           | W   | 0.382      | -            | -                | -                | -         |     4.38 | dav1deuS, hardzao, nython, righi, venomzera    |
|           16 |     3469 | 2024-03-18 | ODDIK           | W   | 0.274      | -            | -                | -                | -         |     3.25 | dav1deuS, destiny, hardzao, nython, venomzera  |
|           15 |     3512 | 2024-03-16 | ODDIK           | W   | 0.262      | -            | -                | -                | -         |     3.13 | dav1deuS, destiny, hardzao, nython, venomzera  |
|           14 |     3529 | 2024-03-15 | Case            | W   | 0.255      | -            | -                | -                | -         |     2.35 | dav1deuS, destiny, hardzao, nython, venomzera  |
|           13 |     3561 | 2024-03-14 | Solid           | L   | 0.248      | -            | -                | -                | -         |    -5.78 | dav1deuS, destiny, hardzao, nython, venomzera  |
|           12 |     3570 | 2024-03-14 | Flamengo        | W   | 0.247      | -            | -                | -                | -         |     0.28 | dav1deuS, destiny, hardzao, nython, venomzera  |
|           11 |     3589 | 2024-03-13 | Case            | W   | 0.241      | -            | -                | -                | -         |     2.22 | dav1deuS, destiny, hardzao, nython, venomzera  |
|           10 |     3601 | 2024-03-13 | Galorys         | W   | 0.241      | -            | -                | -                | -         |     1.94 | dav1deuS, destiny, hardzao, nython, venomzera  |
|            9 |     3633 | 2024-03-12 | BESTIA          | W   | 0.234      | -            | -                | -                | -         |     3.04 | dav1deuS, destiny, hardzao, nython, venomzera  |
|            8 |     3651 | 2024-03-11 | Corinthians     | W   | 0.227      | -            | -                | -                | -         |     0.29 | dav1deuS, destiny, hardzao, nython, venomzera  |
|            7 |     3687 | 2024-03-09 | W7M             | W   | 0.215      | -            | -                | -                | -         |     1.43 | dav1deuS, destiny, hardzao, nython, venomzera  |
|            6 |     3734 | 2024-03-07 | VELOX           | W   | 0.202      | -            | -                | -                | -         |     0.14 | dav1deuS, destiny, hardzao, nython, venomzera  |
|            5 |     3852 | 2024-03-03 | ODDIK           | L   | 0.174      | -            | -                | -                | -         |    -3.35 | dav1deuS, destiny, hardzao, nython, venomzera  |
|            4 |     3884 | 2024-03-02 | paiN            | L   | 0.167      | -            | -                | -                | -         |    -0.71 | dav1deuS, destiny, hardzao, nython, venomzera  |
|            3 |     3899 | 2024-03-01 | Wildcard        | W   | 0.162      | -            | -                | -                | 1 (0.162) |     1.25 | dav1deuS, destiny, hardzao, nython, venomzera  |
|            2 |     4300 | 2024-02-13 | Imperial        | L   | 0.049      | -            | -                | -                | -         |    -0.40 | dav1deuS, destiny, hardzao, nython, venomzera  |
|            1 |     4303 | 2024-02-13 | Imperial        | W   | 0.049      | -            | -                | -                | -         |     1.14 | dav1deuS, destiny, hardzao, nython, venomzera  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($25,017.44)
- Divide that value by the 5th highest value among all rosters ($324,118.06)
- The final value (0.08) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-14 |      1.000 | $2,000.00      | $2,000.00       |
| 2024-06-16 |      0.876 | $1,500.00      | $1,313.47       |
| 2024-06-10 |      0.835 | $750.00        | $626.51         |
| 2024-06-09 |      0.828 | $11,500.00     | $9,523.70       |
| 2024-05-19 |      0.687 | $10,000.00     | $6,874.07       |
| 2024-03-18 |      0.274 | $3,500.00      | $960.23         |
| 2024-03-14 |      0.248 | $15,000.00     | $3,719.44       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
