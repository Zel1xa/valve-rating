### Roster Details<br />
Team Name: RED Canids<br />
Roster: coldzera, dav1deuS, HEN1, nython, venomzera<br />
Global Rank: [38](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [9]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1140.9<br />
<br />
Final Rank Value (1140.9) = Starting Rank Value (1073.5) + Head To Head Adjustments (67.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.472[<sup>1</sup>](#table2)
- Bounty Collected: 0.480[<sup>2</sup>](#table1)
- Opponent Network: 0.242[<sup>2</sup>](#table1)
- LAN Wins: 0.115[<sup>2</sup>](#table1)

The average of these factors is 0.327<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1073.5
- 400 + ( ( 0.327 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1073.5


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
|           88 |       59 | 2024-08-03 | ODDIK           | L   | 1.000      | -            | -                | -                | -         |   -18.21 | coldzera, dav1deuS, HEN1, nython, venomzera    |
|           87 |       66 | 2024-08-03 | Vikings KR      | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.74 | coldzera, dav1deuS, HEN1, nython, venomzera    |
|           86 |      294 | 2024-07-28 | MIBR            | L   | 1.000      | -            | -                | -                | -         |    -7.38 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           85 |      299 | 2024-07-28 | paiN            | L   | 1.000      | -            | -                | -                | -         |    -8.06 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           84 |      354 | 2024-07-26 | ODDIK           | L   | 1.000      | -            | -                | -                | -         |   -22.47 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           83 |      421 | 2024-07-24 | Fluxo           | W   | 1.000      | -            | -                | -                | 0 (0.000) |    15.47 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           82 |      423 | 2024-07-24 | ODDIK           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.71 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           81 |      455 | 2024-07-23 | KRÜ             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.10 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           80 |      458 | 2024-07-23 | LaChampionsLiga | W   | 1.000      | -            | -                | -                | 0 (0.000) |     0.42 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           79 |      496 | 2024-07-22 | paiN Academy    | W   | 1.000      | -            | -                | -                | 0 (0.000) |     0.42 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           78 |      519 | 2024-07-21 | BESTIA          | L   | 1.000      | -            | -                | -                | -         |   -23.58 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           77 |      550 | 2024-07-20 | Case            | W   | 1.000      | 0.384        | -                | 0.778 (0.299)    | 0 (0.000) |     5.34 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           76 |      585 | 2024-07-19 | Intense         | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.38 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           75 |      690 | 2024-07-17 | Hype            | W   | 1.000      | 0.450        | -                | 0.475 (0.214)    | -         |     5.39 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           74 |      695 | 2024-07-17 | Hype            | W   | 1.000      | 0.450        | -                | 0.475 (0.214)    | -         |     5.67 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           73 |      750 | 2024-07-16 | Sharks          | W   | 1.000      | 0.450        | -                | 0.546 (0.246)    | -         |     7.85 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           72 |      756 | 2024-07-16 | Sharks          | W   | 1.000      | 0.450        | -                | 0.546 (0.246)    | -         |     8.40 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           71 |      848 | 2024-07-13 | Legacy          | L   | 1.000      | -            | -                | -                | -         |   -19.39 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           70 |      877 | 2024-07-11 | KRÜ             | W   | 1.000      | -            | -                | -                | -         |     5.29 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           69 |      912 | 2024-07-09 | Bounty Hunters  | W   | 1.000      | -            | -                | -                | -         |     7.71 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           68 |      935 | 2024-07-08 | SPORT           | W   | 1.000      | -            | -                | -                | -         |     2.52 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           67 |     1051 | 2024-06-15 | fnatic          | L   | 0.857      | -            | -                | -                | -         |    -4.36 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           66 |     1084 | 2024-06-14 | KOI             | L   | 0.851      | -            | -                | -                | -         |   -16.13 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           65 |     1090 | 2024-06-14 | fnatic          | W   | 0.849      | 0.548        | 0.371 (0.173)    | 0.680 (0.317)    | 1 (0.849) |    22.42 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           64 |     1238 | 2024-06-09 | BESTIA          | L   | 0.817      | -            | -                | -                | -         |   -17.35 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           63 |     1243 | 2024-06-09 | Imperial        | L   | 0.816      | -            | -                | -                | -         |    -8.63 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           62 |     1376 | 2024-06-07 | Intense         | W   | 0.802      | -            | -                | -                | -         |     2.37 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           61 |     1416 | 2024-06-06 | Imperial        | W   | 0.796      | 0.450        | 0.233 (0.084)    | 0.658 (0.236)    | -         |    16.38 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           60 |     1487 | 2024-06-05 | 9z              | W   | 0.790      | 0.450        | 0.404 (0.144)    | 0.591 (0.210)    | -         |    21.43 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           59 |     1901 | 2024-05-21 | Sharks          | L   | 0.690      | -            | -                | -                | -         |   -15.13 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           58 |     1903 | 2024-05-21 | Sharks          | W   | 0.689      | -            | -                | -                | -         |     6.55 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           57 |     1934 | 2024-05-20 | Fluxo           | L   | 0.683      | -            | -                | -                | -         |   -12.48 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           56 |     1937 | 2024-05-20 | Fluxo           | W   | 0.683      | 0.450        | 0.123 (0.038)    | 0.701 (0.215)    | -         |     9.14 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           55 |     1970 | 2024-05-19 | 9z              | W   | 0.675      | 0.371        | 0.404 (0.101)    | -                | -         |    18.59 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           54 |     1991 | 2024-05-18 | ODDIK           | W   | 0.669      | 0.371        | 0.099 (0.025)    | -                | -         |     6.06 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           53 |     2063 | 2024-05-16 | Fluxo           | W   | 0.656      | 0.371        | 0.123 (0.030)    | -                | -         |     9.96 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           52 |     2105 | 2024-05-15 | 9z              | L   | 0.650      | -            | -                | -                | -         |    -2.14 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           51 |     2107 | 2024-05-15 | 9z              | W   | 0.650      | 0.450        | 0.404 (0.118)    | -                | -         |    18.58 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           50 |     2164 | 2024-05-14 | Corinthians     | W   | 0.643      | -            | -                | -                | -         |     0.72 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           49 |     2169 | 2024-05-14 | Corinthians     | W   | 0.643      | -            | -                | -                | -         |     0.73 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           48 |     2182 | 2024-05-14 | BESTIA          | W   | 0.642      | 0.371        | 0.096 (0.023)    | -                | -         |     6.93 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           47 |     2200 | 2024-05-13 | Sharks          | L   | 0.636      | -            | -                | -                | -         |   -13.00 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           46 |     2220 | 2024-05-12 | Vikings KR      | W   | 0.630      | -            | -                | -                | -         |     3.51 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           45 |     2228 | 2024-05-12 | FURIA Academy   | W   | 0.629      | -            | -                | -                | -         |     0.76 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           44 |     2284 | 2024-05-10 | paiN            | L   | 0.614      | -            | -                | -                | -         |    -3.43 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           43 |     2300 | 2024-05-09 | Intense         | W   | 0.609      | -            | -                | -                | -         |     2.39 | dav1deuS, destiny, hardzao, nython, venomzera  |
|           42 |     2318 | 2024-05-08 | paiN            | L   | 0.604      | -            | -                | -                | -         |    -3.23 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           41 |     2320 | 2024-05-08 | paiN            | W   | 0.603      | 0.450        | 0.324 (0.088)    | 0.838 (0.228)    | -         |    16.08 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           40 |     2321 | 2024-05-08 | Solid           | L   | 0.603      | -            | -                | -                | -         |   -14.50 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           39 |     2364 | 2024-05-06 | Intense         | W   | 0.588      | -            | -                | -                | -         |     2.30 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           38 |     2596 | 2024-04-25 | BESTIA          | W   | 0.517      | -            | -                | -                | -         |     4.97 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           37 |     2598 | 2024-04-25 | BESTIA          | W   | 0.516      | -            | -                | -                | -         |     5.17 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           36 |     2825 | 2024-04-17 | MIBR            | L   | 0.463      | -            | -                | -                | -         |    -1.88 | dav1deuS, hardzao, nython, righi, venomzera    |
|           35 |     2833 | 2024-04-17 | O PLANO         | W   | 0.463      | -            | -                | -                | -         |     0.64 | dav1deuS, hardzao, nython, righi, venomzera    |
|           34 |     2866 | 2024-04-16 | LaChampionsLiga | W   | 0.457      | -            | -                | -                | -         |     0.30 | dav1deuS, hardzao, nython, righi, venomzera    |
|           33 |     2916 | 2024-04-13 | Imperial        | L   | 0.437      | -            | -                | -                | -         |    -3.68 | dav1deuS, hardzao, nython, righi, venomzera    |
|           32 |     2935 | 2024-04-12 | W7M             | W   | 0.428      | -            | -                | -                | -         |     2.61 | dav1deuS, hardzao, nython, righi, venomzera    |
|           31 |     2991 | 2024-04-10 | 2GAME           | W   | 0.417      | -            | -                | -                | -         |     1.15 | dav1deuS, hardzao, nython, righi, venomzera    |
|           30 |     2994 | 2024-04-10 | 2GAME           | W   | 0.416      | -            | -                | -                | -         |     1.16 | dav1deuS, hardzao, nython, righi, venomzera    |
|           29 |     2997 | 2024-04-10 | paiN            | L   | 0.415      | -            | -                | -                | -         |    -1.90 | dav1deuS, hardzao, nython, righi, venomzera    |
|           28 |     3044 | 2024-04-09 | W7M             | W   | 0.410      | -            | -                | -                | -         |     2.56 | dav1deuS, hardzao, nython, righi, venomzera    |
|           27 |     3049 | 2024-04-09 | W7M             | W   | 0.410      | -            | -                | -                | -         |     2.62 | dav1deuS, hardzao, nython, righi, venomzera    |
|           26 |     3052 | 2024-04-09 | MIBR            | L   | 0.409      | -            | -                | -                | -         |    -1.82 | dav1deuS, hardzao, nython, righi, venomzera    |
|           25 |     3083 | 2024-04-08 | BESTIA          | W   | 0.403      | -            | -                | -                | -         |     4.60 | dav1deuS, hardzao, nython, righi, venomzera    |
|           24 |     3089 | 2024-04-08 | Bounty Hunters  | W   | 0.402      | -            | -                | -                | -         |     3.37 | dav1deuS, hardzao, nython, righi, venomzera    |
|           23 |     3119 | 2024-04-07 | Imperial        | L   | 0.396      | -            | -                | -                | -         |    -3.19 | dav1deuS, hardzao, nython, righi, venomzera    |
|           22 |     3138 | 2024-04-06 | W7M             | L   | 0.388      | -            | -                | -                | -         |    -9.87 | dav1deuS, hardzao, nython, righi, venomzera    |
|           21 |     3177 | 2024-04-04 | Case            | L   | 0.377      | -            | -                | -                | -         |    -8.80 | dav1deuS, hardzao, nython, righi, venomzera    |
|           20 |     3182 | 2024-04-04 | Case            | W   | 0.376      | -            | -                | -                | -         |     3.09 | dav1deuS, hardzao, nython, righi, venomzera    |
|           19 |     3198 | 2024-04-04 | Fluxo           | W   | 0.374      | -            | -                | -                | -         |     5.24 | dav1deuS, hardzao, nython, righi, venomzera    |
|           18 |     3218 | 2024-04-03 | ODDIK           | W   | 0.370      | -            | -                | -                | -         |     4.15 | dav1deuS, hardzao, nython, righi, venomzera    |
|           17 |     3221 | 2024-04-03 | ODDIK           | W   | 0.370      | -            | -                | -                | -         |     4.27 | dav1deuS, hardzao, nython, righi, venomzera    |
|           16 |     3506 | 2024-03-18 | ODDIK           | W   | 0.262      | -            | -                | -                | -         |     3.13 | dav1deuS, destiny, hardzao, nython, venomzera  |
|           15 |     3549 | 2024-03-16 | ODDIK           | W   | 0.249      | -            | -                | -                | -         |     3.00 | dav1deuS, destiny, hardzao, nython, venomzera  |
|           14 |     3566 | 2024-03-15 | Case            | W   | 0.242      | -            | -                | -                | -         |     2.26 | dav1deuS, destiny, hardzao, nython, venomzera  |
|           13 |     3598 | 2024-03-14 | Solid           | L   | 0.236      | -            | -                | -                | -         |    -5.48 | dav1deuS, destiny, hardzao, nython, venomzera  |
|           12 |     3607 | 2024-03-14 | Flamengo        | W   | 0.235      | -            | -                | -                | -         |     0.27 | dav1deuS, destiny, hardzao, nython, venomzera  |
|           11 |     3626 | 2024-03-13 | Case            | W   | 0.229      | -            | -                | -                | -         |     2.13 | dav1deuS, destiny, hardzao, nython, venomzera  |
|           10 |     3638 | 2024-03-13 | Galorys         | W   | 0.229      | -            | -                | -                | -         |     1.87 | dav1deuS, destiny, hardzao, nython, venomzera  |
|            9 |     3670 | 2024-03-12 | BESTIA          | W   | 0.222      | -            | -                | -                | -         |     2.89 | dav1deuS, destiny, hardzao, nython, venomzera  |
|            8 |     3688 | 2024-03-11 | Corinthians     | W   | 0.215      | -            | -                | -                | -         |     0.28 | dav1deuS, destiny, hardzao, nython, venomzera  |
|            7 |     3724 | 2024-03-09 | W7M             | W   | 0.203      | -            | -                | -                | -         |     1.36 | dav1deuS, destiny, hardzao, nython, venomzera  |
|            6 |     3771 | 2024-03-07 | VELOX           | W   | 0.190      | -            | -                | -                | -         |     0.14 | dav1deuS, destiny, hardzao, nython, venomzera  |
|            5 |     3889 | 2024-03-03 | ODDIK           | L   | 0.162      | -            | -                | -                | -         |    -3.11 | dav1deuS, destiny, hardzao, nython, venomzera  |
|            4 |     3921 | 2024-03-02 | paiN            | L   | 0.155      | -            | -                | -                | -         |    -0.67 | dav1deuS, destiny, hardzao, nython, venomzera  |
|            3 |     3936 | 2024-03-01 | Wildcard        | W   | 0.149      | -            | -                | -                | 1 (0.149) |     1.17 | dav1deuS, destiny, hardzao, nython, venomzera  |
|            2 |     4337 | 2024-02-13 | Imperial        | L   | 0.037      | -            | -                | -                | -         |    -0.31 | dav1deuS, destiny, hardzao, nython, venomzera  |
|            1 |     4340 | 2024-02-13 | Imperial        | W   | 0.037      | -            | -                | -                | -         |     0.85 | dav1deuS, destiny, hardzao, nython, venomzera  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($24,504.96)
- Divide that value by the 5th highest value among all rosters ($320,521.62)
- The final value (0.08) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-14 |      1.000 | $2,000.00      | $2,000.00       |
| 2024-06-16 |      0.864 | $1,500.00      | $1,295.28       |
| 2024-06-10 |      0.823 | $750.00        | $617.41         |
| 2024-06-09 |      0.816 | $11,500.00     | $9,384.21       |
| 2024-05-19 |      0.675 | $10,000.00     | $6,752.78       |
| 2024-03-18 |      0.262 | $3,500.00      | $917.78         |
| 2024-03-14 |      0.236 | $15,000.00     | $3,537.50       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
