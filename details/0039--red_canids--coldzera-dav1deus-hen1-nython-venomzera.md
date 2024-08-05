### Roster Details<br />
Team Name: RED Canids<br />
Roster: coldzera, dav1deuS, HEN1, nython, venomzera<br />
Global Rank: [39](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [9]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1143.7<br />
<br />
Final Rank Value (1143.7) = Starting Rank Value (1076.5) + Head To Head Adjustments (67.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.473[<sup>1</sup>](#table2)
- Bounty Collected: 0.481[<sup>2</sup>](#table1)
- Opponent Network: 0.252[<sup>2</sup>](#table1)
- LAN Wins: 0.116[<sup>2</sup>](#table1)

The average of these factors is 0.330<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1076.5
- 400 + ( ( 0.330 - 0.000 ) / ( 0.781 - 0.000 ) ) * 1600 = 1076.5


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
|           88 |       40 | 2024-08-03 | ODDIK           | L   | 1.000      | -            | -                | -                | -         |   -18.24 | coldzera, dav1deuS, HEN1, nython, venomzera    |
|           87 |       47 | 2024-08-03 | Vikings KR      | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.72 | coldzera, dav1deuS, HEN1, nython, venomzera    |
|           86 |      275 | 2024-07-28 | MIBR            | L   | 1.000      | -            | -                | -                | -         |    -7.39 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           85 |      280 | 2024-07-28 | paiN            | L   | 1.000      | -            | -                | -                | -         |    -8.05 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           84 |      335 | 2024-07-26 | ODDIK           | L   | 1.000      | -            | -                | -                | -         |   -22.50 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           83 |      402 | 2024-07-24 | Fluxo           | W   | 1.000      | -            | -                | -                | 0 (0.000) |    15.48 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           82 |      404 | 2024-07-24 | ODDIK           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.69 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           81 |      436 | 2024-07-23 | KRÜ             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.08 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           80 |      439 | 2024-07-23 | LaChampionsLiga | W   | 1.000      | -            | -                | -                | 0 (0.000) |     0.41 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           79 |      477 | 2024-07-22 | paiN Academy    | W   | 1.000      | -            | -                | -                | 0 (0.000) |     0.41 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           78 |      500 | 2024-07-21 | BESTIA          | L   | 1.000      | -            | -                | -                | -         |   -23.59 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           77 |      531 | 2024-07-20 | Case            | W   | 1.000      | 0.384        | -                | 0.805 (0.309)    | 0 (0.000) |     5.30 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           76 |      566 | 2024-07-19 | Intense         | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.35 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           75 |      671 | 2024-07-17 | Hype            | W   | 1.000      | 0.450        | -                | 0.490 (0.221)    | -         |     5.36 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           74 |      676 | 2024-07-17 | Hype            | W   | 1.000      | 0.450        | -                | 0.490 (0.221)    | -         |     5.64 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           73 |      731 | 2024-07-16 | Sharks          | W   | 1.000      | 0.450        | -                | 0.565 (0.254)    | -         |     7.84 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           72 |      737 | 2024-07-16 | Sharks          | W   | 1.000      | 0.450        | -                | 0.565 (0.254)    | -         |     8.38 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           71 |      829 | 2024-07-13 | Legacy          | L   | 1.000      | -            | -                | -                | -         |   -19.41 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           70 |      858 | 2024-07-11 | KRÜ             | W   | 1.000      | -            | -                | -                | -         |     5.26 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           69 |      893 | 2024-07-09 | Bounty Hunters  | W   | 1.000      | -            | -                | -                | -         |     7.69 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           68 |      916 | 2024-07-08 | SPORT           | W   | 1.000      | -            | -                | -                | -         |     2.46 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           67 |     1032 | 2024-06-15 | fnatic          | L   | 0.863      | -            | -                | -                | -         |    -4.45 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           66 |     1065 | 2024-06-14 | KOI             | L   | 0.857      | -            | -                | -                | -         |   -16.30 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           65 |     1071 | 2024-06-14 | fnatic          | W   | 0.856      | 0.548        | 0.371 (0.174)    | 0.706 (0.331)    | 1 (0.856) |    22.52 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           64 |     1219 | 2024-06-09 | BESTIA          | L   | 0.823      | -            | -                | -                | -         |   -17.50 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           63 |     1224 | 2024-06-09 | Imperial        | L   | 0.822      | -            | -                | -                | -         |    -8.68 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           62 |     1357 | 2024-06-07 | Intense         | W   | 0.808      | -            | -                | -                | -         |     2.36 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           61 |     1397 | 2024-06-06 | Imperial        | W   | 0.803      | 0.450        | 0.235 (0.085)    | 0.683 (0.247)    | -         |    16.51 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           60 |     1468 | 2024-06-05 | 9z              | W   | 0.796      | 0.450        | 0.405 (0.145)    | 0.615 (0.220)    | -         |    21.56 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           59 |     1882 | 2024-05-21 | Sharks          | L   | 0.696      | -            | -                | -                | -         |   -15.26 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           58 |     1884 | 2024-05-21 | Sharks          | W   | 0.696      | -            | -                | -                | -         |     6.60 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           57 |     1915 | 2024-05-20 | Fluxo           | L   | 0.689      | -            | -                | -                | -         |   -12.60 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           56 |     1918 | 2024-05-20 | Fluxo           | W   | 0.689      | 0.450        | 0.123 (0.038)    | 0.724 (0.225)    | -         |     9.22 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           55 |     1951 | 2024-05-19 | 9z              | W   | 0.681      | 0.371        | 0.405 (0.102)    | -                | -         |    18.73 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           54 |     1972 | 2024-05-18 | ODDIK           | W   | 0.676      | 0.371        | 0.099 (0.025)    | -                | -         |     6.09 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           53 |     2044 | 2024-05-16 | Fluxo           | W   | 0.662      | 0.371        | 0.123 (0.030)    | -                | -         |    10.05 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           52 |     2086 | 2024-05-15 | 9z              | L   | 0.657      | -            | -                | -                | -         |    -2.17 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           51 |     2088 | 2024-05-15 | 9z              | W   | 0.656      | 0.450        | 0.405 (0.119)    | -                | -         |    18.74 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           50 |     2145 | 2024-05-14 | Corinthians     | W   | 0.649      | -            | -                | -                | -         |     0.72 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           49 |     2150 | 2024-05-14 | Corinthians     | W   | 0.649      | -            | -                | -                | -         |     0.72 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           48 |     2163 | 2024-05-14 | BESTIA          | W   | 0.648      | 0.371        | 0.096 (0.023)    | -                | -         |     6.97 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           47 |     2181 | 2024-05-13 | Sharks          | L   | 0.642      | -            | -                | -                | -         |   -13.12 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           46 |     2201 | 2024-05-12 | Vikings KR      | W   | 0.636      | -            | -                | -                | -         |     3.52 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           45 |     2209 | 2024-05-12 | FURIA Academy   | W   | 0.635      | -            | -                | -                | -         |     0.76 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           44 |     2265 | 2024-05-10 | paiN            | L   | 0.620      | -            | -                | -                | -         |    -3.44 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           43 |     2281 | 2024-05-09 | Intense         | W   | 0.615      | -            | -                | -                | -         |     2.38 | dav1deuS, destiny, hardzao, nython, venomzera  |
|           42 |     2299 | 2024-05-08 | paiN            | L   | 0.610      | -            | -                | -                | -         |    -3.24 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           41 |     2301 | 2024-05-08 | paiN            | W   | 0.609      | 0.450        | 0.325 (0.089)    | 0.867 (0.238)    | -         |    16.26 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           40 |     2302 | 2024-05-08 | Solid           | L   | 0.609      | -            | -                | -                | -         |   -14.66 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           39 |     2345 | 2024-05-06 | Intense         | W   | 0.594      | -            | -                | -                | -         |     2.29 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           38 |     2577 | 2024-04-25 | BESTIA          | W   | 0.523      | -            | -                | -                | -         |     5.00 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           37 |     2579 | 2024-04-25 | BESTIA          | W   | 0.522      | -            | -                | -                | -         |     5.20 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           36 |     2806 | 2024-04-17 | MIBR            | L   | 0.469      | -            | -                | -                | -         |    -1.90 | dav1deuS, hardzao, nython, righi, venomzera    |
|           35 |     2814 | 2024-04-17 | O PLANO         | W   | 0.469      | -            | -                | -                | -         |     0.63 | dav1deuS, hardzao, nython, righi, venomzera    |
|           34 |     2847 | 2024-04-16 | LaChampionsLiga | W   | 0.463      | -            | -                | -                | -         |     0.30 | dav1deuS, hardzao, nython, righi, venomzera    |
|           33 |     2897 | 2024-04-13 | Imperial        | L   | 0.443      | -            | -                | -                | -         |    -3.71 | dav1deuS, hardzao, nython, righi, venomzera    |
|           32 |     2916 | 2024-04-12 | W7M             | W   | 0.434      | -            | -                | -                | -         |     2.63 | dav1deuS, hardzao, nython, righi, venomzera    |
|           31 |     2972 | 2024-04-10 | 2GAME           | W   | 0.423      | -            | -                | -                | -         |     1.15 | dav1deuS, hardzao, nython, righi, venomzera    |
|           30 |     2975 | 2024-04-10 | 2GAME           | W   | 0.422      | -            | -                | -                | -         |     1.16 | dav1deuS, hardzao, nython, righi, venomzera    |
|           29 |     2978 | 2024-04-10 | paiN            | L   | 0.422      | -            | -                | -                | -         |    -1.91 | dav1deuS, hardzao, nython, righi, venomzera    |
|           28 |     3025 | 2024-04-09 | W7M             | W   | 0.416      | -            | -                | -                | -         |     2.58 | dav1deuS, hardzao, nython, righi, venomzera    |
|           27 |     3030 | 2024-04-09 | W7M             | W   | 0.416      | -            | -                | -                | -         |     2.65 | dav1deuS, hardzao, nython, righi, venomzera    |
|           26 |     3033 | 2024-04-09 | MIBR            | L   | 0.415      | -            | -                | -                | -         |    -1.84 | dav1deuS, hardzao, nython, righi, venomzera    |
|           25 |     3064 | 2024-04-08 | BESTIA          | W   | 0.409      | -            | -                | -                | -         |     4.65 | dav1deuS, hardzao, nython, righi, venomzera    |
|           24 |     3070 | 2024-04-08 | Bounty Hunters  | W   | 0.408      | -            | -                | -                | -         |     3.41 | dav1deuS, hardzao, nython, righi, venomzera    |
|           23 |     3100 | 2024-04-07 | Imperial        | L   | 0.402      | -            | -                | -                | -         |    -3.21 | dav1deuS, hardzao, nython, righi, venomzera    |
|           22 |     3119 | 2024-04-06 | W7M             | L   | 0.394      | -            | -                | -                | -         |   -10.04 | dav1deuS, hardzao, nython, righi, venomzera    |
|           21 |     3158 | 2024-04-04 | Case            | L   | 0.383      | -            | -                | -                | -         |    -8.96 | dav1deuS, hardzao, nython, righi, venomzera    |
|           20 |     3163 | 2024-04-04 | Case            | W   | 0.383      | -            | -                | -                | -         |     3.12 | dav1deuS, hardzao, nython, righi, venomzera    |
|           19 |     3179 | 2024-04-04 | Fluxo           | W   | 0.381      | -            | -                | -                | -         |     5.32 | dav1deuS, hardzao, nython, righi, venomzera    |
|           18 |     3199 | 2024-04-03 | ODDIK           | W   | 0.376      | -            | -                | -                | -         |     4.20 | dav1deuS, hardzao, nython, righi, venomzera    |
|           17 |     3202 | 2024-04-03 | ODDIK           | W   | 0.376      | -            | -                | -                | -         |     4.33 | dav1deuS, hardzao, nython, righi, venomzera    |
|           16 |     3487 | 2024-03-18 | ODDIK           | W   | 0.268      | -            | -                | -                | -         |     3.19 | dav1deuS, destiny, hardzao, nython, venomzera  |
|           15 |     3530 | 2024-03-16 | ODDIK           | W   | 0.256      | -            | -                | -                | -         |     3.07 | dav1deuS, destiny, hardzao, nython, venomzera  |
|           14 |     3547 | 2024-03-15 | Case            | W   | 0.249      | -            | -                | -                | -         |     2.31 | dav1deuS, destiny, hardzao, nython, venomzera  |
|           13 |     3579 | 2024-03-14 | Solid           | L   | 0.242      | -            | -                | -                | -         |    -5.63 | dav1deuS, destiny, hardzao, nython, venomzera  |
|           12 |     3588 | 2024-03-14 | Flamengo        | W   | 0.241      | -            | -                | -                | -         |     0.27 | dav1deuS, destiny, hardzao, nython, venomzera  |
|           11 |     3607 | 2024-03-13 | Case            | W   | 0.235      | -            | -                | -                | -         |     2.17 | dav1deuS, destiny, hardzao, nython, venomzera  |
|           10 |     3619 | 2024-03-13 | Galorys         | W   | 0.235      | -            | -                | -                | -         |     1.91 | dav1deuS, destiny, hardzao, nython, venomzera  |
|            9 |     3651 | 2024-03-12 | BESTIA          | W   | 0.228      | -            | -                | -                | -         |     2.97 | dav1deuS, destiny, hardzao, nython, venomzera  |
|            8 |     3669 | 2024-03-11 | Corinthians     | W   | 0.221      | -            | -                | -                | -         |     0.28 | dav1deuS, destiny, hardzao, nython, venomzera  |
|            7 |     3705 | 2024-03-09 | W7M             | W   | 0.209      | -            | -                | -                | -         |     1.39 | dav1deuS, destiny, hardzao, nython, venomzera  |
|            6 |     3752 | 2024-03-07 | VELOX           | W   | 0.196      | -            | -                | -                | -         |     0.14 | dav1deuS, destiny, hardzao, nython, venomzera  |
|            5 |     3870 | 2024-03-03 | ODDIK           | L   | 0.168      | -            | -                | -                | -         |    -3.23 | dav1deuS, destiny, hardzao, nython, venomzera  |
|            4 |     3902 | 2024-03-02 | paiN            | L   | 0.161      | -            | -                | -                | -         |    -0.69 | dav1deuS, destiny, hardzao, nython, venomzera  |
|            3 |     3917 | 2024-03-01 | Wildcard        | W   | 0.156      | -            | -                | -                | 1 (0.156) |     1.20 | dav1deuS, destiny, hardzao, nython, venomzera  |
|            2 |     4318 | 2024-02-13 | Imperial        | L   | 0.043      | -            | -                | -                | -         |    -0.36 | dav1deuS, destiny, hardzao, nython, venomzera  |
|            1 |     4321 | 2024-02-13 | Imperial        | W   | 0.043      | -            | -                | -                | -         |     1.00 | dav1deuS, destiny, hardzao, nython, venomzera  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($24,763.15)
- Divide that value by the 5th highest value among all rosters ($322,333.56)
- The final value (0.08) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-14 |      1.000 | $2,000.00      | $2,000.00       |
| 2024-06-16 |      0.870 | $1,500.00      | $1,304.44       |
| 2024-06-10 |      0.829 | $750.00        | $622.00         |
| 2024-06-09 |      0.822 | $11,500.00     | $9,454.49       |
| 2024-05-19 |      0.681 | $10,000.00     | $6,813.89       |
| 2024-03-18 |      0.268 | $3,500.00      | $939.17         |
| 2024-03-14 |      0.242 | $15,000.00     | $3,629.17       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
