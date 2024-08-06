### Roster Details<br />
Team Name: RED Canids<br />
Roster: coldzera, dav1deuS, HEN1, nython, venomzera<br />
Global Rank: [38](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [9]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1142.1<br />
<br />
Final Rank Value (1142.1) = Starting Rank Value (1074.9) + Head To Head Adjustments (67.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.472[<sup>1</sup>](#table2)
- Bounty Collected: 0.480[<sup>2</sup>](#table1)
- Opponent Network: 0.248[<sup>2</sup>](#table1)
- LAN Wins: 0.115[<sup>2</sup>](#table1)

The average of these factors is 0.329<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1074.9
- 400 + ( ( 0.329 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 1074.9


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
|           88 |       55 | 2024-08-03 | ODDIK           | L   | 1.000      | -            | -                | -                | -         |   -18.21 | coldzera, dav1deuS, HEN1, nython, venomzera    |
|           87 |       62 | 2024-08-03 | Vikings KR      | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.74 | coldzera, dav1deuS, HEN1, nython, venomzera    |
|           86 |      290 | 2024-07-28 | MIBR            | L   | 1.000      | -            | -                | -                | -         |    -7.39 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           85 |      295 | 2024-07-28 | paiN            | L   | 1.000      | -            | -                | -                | -         |    -8.06 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           84 |      350 | 2024-07-26 | ODDIK           | L   | 1.000      | -            | -                | -                | -         |   -22.48 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           83 |      417 | 2024-07-24 | Fluxo           | W   | 1.000      | -            | -                | -                | 0 (0.000) |    15.48 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           82 |      419 | 2024-07-24 | ODDIK           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.71 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           81 |      451 | 2024-07-23 | KRÜ             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.10 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           80 |      454 | 2024-07-23 | LaChampionsLiga | W   | 1.000      | -            | -                | -                | 0 (0.000) |     0.42 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           79 |      492 | 2024-07-22 | paiN Academy    | W   | 1.000      | -            | -                | -                | 0 (0.000) |     0.41 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           78 |      515 | 2024-07-21 | BESTIA          | L   | 1.000      | -            | -                | -                | -         |   -23.58 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           77 |      546 | 2024-07-20 | Case            | W   | 1.000      | 0.384        | -                | 0.795 (0.306)    | 0 (0.000) |     5.33 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           76 |      581 | 2024-07-19 | Intense         | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.37 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           75 |      686 | 2024-07-17 | Hype            | W   | 1.000      | 0.450        | -                | 0.486 (0.219)    | -         |     5.39 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           74 |      691 | 2024-07-17 | Hype            | W   | 1.000      | 0.450        | -                | 0.486 (0.219)    | -         |     5.67 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           73 |      746 | 2024-07-16 | Sharks          | W   | 1.000      | 0.450        | -                | 0.558 (0.251)    | -         |     7.86 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           72 |      752 | 2024-07-16 | Sharks          | W   | 1.000      | 0.450        | -                | 0.558 (0.251)    | -         |     8.40 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           71 |      844 | 2024-07-13 | Legacy          | L   | 1.000      | -            | -                | -                | -         |   -19.40 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           70 |      873 | 2024-07-11 | KRÜ             | W   | 1.000      | -            | -                | -                | -         |     5.29 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           69 |      908 | 2024-07-09 | Bounty Hunters  | W   | 1.000      | -            | -                | -                | -         |     7.72 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           68 |      931 | 2024-07-08 | SPORT           | W   | 1.000      | -            | -                | -                | -         |     2.50 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           67 |     1047 | 2024-06-15 | fnatic          | L   | 0.857      | -            | -                | -                | -         |    -4.38 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           66 |     1080 | 2024-06-14 | KOI             | L   | 0.851      | -            | -                | -                | -         |   -16.16 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           65 |     1086 | 2024-06-14 | fnatic          | W   | 0.850      | 0.548        | 0.371 (0.173)    | 0.695 (0.324)    | 1 (0.850) |    22.41 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           64 |     1234 | 2024-06-09 | BESTIA          | L   | 0.817      | -            | -                | -                | -         |   -17.35 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           63 |     1239 | 2024-06-09 | Imperial        | L   | 0.816      | -            | -                | -                | -         |    -8.64 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           62 |     1372 | 2024-06-07 | Intense         | W   | 0.802      | -            | -                | -                | -         |     2.37 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           61 |     1412 | 2024-06-06 | Imperial        | W   | 0.797      | 0.450        | 0.233 (0.084)    | 0.673 (0.241)    | -         |    16.37 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           60 |     1483 | 2024-06-05 | 9z              | W   | 0.790      | 0.450        | 0.404 (0.144)    | 0.604 (0.215)    | -         |    21.42 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           59 |     1897 | 2024-05-21 | Sharks          | L   | 0.690      | -            | -                | -                | -         |   -15.12 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           58 |     1899 | 2024-05-21 | Sharks          | W   | 0.690      | -            | -                | -                | -         |     6.57 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           57 |     1930 | 2024-05-20 | Fluxo           | L   | 0.684      | -            | -                | -                | -         |   -12.48 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           56 |     1933 | 2024-05-20 | Fluxo           | W   | 0.683      | 0.450        | 0.123 (0.038)    | 0.716 (0.220)    | -         |     9.15 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           55 |     1966 | 2024-05-19 | 9z              | W   | 0.676      | 0.371        | 0.404 (0.101)    | -                | -         |    18.59 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           54 |     1987 | 2024-05-18 | ODDIK           | W   | 0.670      | 0.371        | 0.099 (0.025)    | -                | -         |     6.06 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           53 |     2059 | 2024-05-16 | Fluxo           | W   | 0.656      | 0.371        | 0.123 (0.030)    | -                | -         |     9.97 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           52 |     2101 | 2024-05-15 | 9z              | L   | 0.651      | -            | -                | -                | -         |    -2.15 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           51 |     2103 | 2024-05-15 | 9z              | W   | 0.650      | 0.450        | 0.404 (0.118)    | -                | -         |    18.58 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           50 |     2160 | 2024-05-14 | Corinthians     | W   | 0.644      | -            | -                | -                | -         |     0.72 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           49 |     2165 | 2024-05-14 | Corinthians     | W   | 0.643      | -            | -                | -                | -         |     0.72 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           48 |     2178 | 2024-05-14 | BESTIA          | W   | 0.642      | 0.371        | 0.096 (0.023)    | -                | -         |     6.94 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           47 |     2196 | 2024-05-13 | Sharks          | L   | 0.636      | -            | -                | -                | -         |   -12.99 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           46 |     2216 | 2024-05-12 | Vikings KR      | W   | 0.630      | -            | -                | -                | -         |     3.51 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           45 |     2224 | 2024-05-12 | FURIA Academy   | W   | 0.629      | -            | -                | -                | -         |     0.76 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           44 |     2280 | 2024-05-10 | paiN            | L   | 0.614      | -            | -                | -                | -         |    -3.43 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           43 |     2296 | 2024-05-09 | Intense         | W   | 0.609      | -            | -                | -                | -         |     2.38 | dav1deuS, destiny, hardzao, nython, venomzera  |
|           42 |     2314 | 2024-05-08 | paiN            | L   | 0.604      | -            | -                | -                | -         |    -3.23 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           41 |     2316 | 2024-05-08 | paiN            | W   | 0.604      | 0.450        | 0.324 (0.088)    | 0.857 (0.233)    | -         |    16.08 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           40 |     2317 | 2024-05-08 | Solid           | L   | 0.603      | -            | -                | -                | -         |   -14.50 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           39 |     2360 | 2024-05-06 | Intense         | W   | 0.588      | -            | -                | -                | -         |     2.29 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           38 |     2592 | 2024-04-25 | BESTIA          | W   | 0.517      | -            | -                | -                | -         |     4.98 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           37 |     2594 | 2024-04-25 | BESTIA          | W   | 0.517      | -            | -                | -                | -         |     5.17 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           36 |     2821 | 2024-04-17 | MIBR            | L   | 0.463      | -            | -                | -                | -         |    -1.89 | dav1deuS, hardzao, nython, righi, venomzera    |
|           35 |     2829 | 2024-04-17 | O PLANO         | W   | 0.463      | -            | -                | -                | -         |     0.63 | dav1deuS, hardzao, nython, righi, venomzera    |
|           34 |     2862 | 2024-04-16 | LaChampionsLiga | W   | 0.457      | -            | -                | -                | -         |     0.29 | dav1deuS, hardzao, nython, righi, venomzera    |
|           33 |     2912 | 2024-04-13 | Imperial        | L   | 0.437      | -            | -                | -                | -         |    -3.69 | dav1deuS, hardzao, nython, righi, venomzera    |
|           32 |     2931 | 2024-04-12 | W7M             | W   | 0.429      | -            | -                | -                | -         |     2.61 | dav1deuS, hardzao, nython, righi, venomzera    |
|           31 |     2987 | 2024-04-10 | 2GAME           | W   | 0.417      | -            | -                | -                | -         |     1.14 | dav1deuS, hardzao, nython, righi, venomzera    |
|           30 |     2990 | 2024-04-10 | 2GAME           | W   | 0.417      | -            | -                | -                | -         |     1.16 | dav1deuS, hardzao, nython, righi, venomzera    |
|           29 |     2993 | 2024-04-10 | paiN            | L   | 0.416      | -            | -                | -                | -         |    -1.90 | dav1deuS, hardzao, nython, righi, venomzera    |
|           28 |     3040 | 2024-04-09 | W7M             | W   | 0.410      | -            | -                | -                | -         |     2.56 | dav1deuS, hardzao, nython, righi, venomzera    |
|           27 |     3045 | 2024-04-09 | W7M             | W   | 0.410      | -            | -                | -                | -         |     2.62 | dav1deuS, hardzao, nython, righi, venomzera    |
|           26 |     3048 | 2024-04-09 | MIBR            | L   | 0.409      | -            | -                | -                | -         |    -1.82 | dav1deuS, hardzao, nython, righi, venomzera    |
|           25 |     3079 | 2024-04-08 | BESTIA          | W   | 0.403      | -            | -                | -                | -         |     4.61 | dav1deuS, hardzao, nython, righi, venomzera    |
|           24 |     3085 | 2024-04-08 | Bounty Hunters  | W   | 0.402      | -            | -                | -                | -         |     3.37 | dav1deuS, hardzao, nython, righi, venomzera    |
|           23 |     3115 | 2024-04-07 | Imperial        | L   | 0.397      | -            | -                | -                | -         |    -3.19 | dav1deuS, hardzao, nython, righi, venomzera    |
|           22 |     3134 | 2024-04-06 | W7M             | L   | 0.389      | -            | -                | -                | -         |    -9.88 | dav1deuS, hardzao, nython, righi, venomzera    |
|           21 |     3173 | 2024-04-04 | Case            | L   | 0.377      | -            | -                | -                | -         |    -8.80 | dav1deuS, hardzao, nython, righi, venomzera    |
|           20 |     3178 | 2024-04-04 | Case            | W   | 0.377      | -            | -                | -                | -         |     3.09 | dav1deuS, hardzao, nython, righi, venomzera    |
|           19 |     3194 | 2024-04-04 | Fluxo           | W   | 0.375      | -            | -                | -                | -         |     5.25 | dav1deuS, hardzao, nython, righi, venomzera    |
|           18 |     3214 | 2024-04-03 | ODDIK           | W   | 0.370      | -            | -                | -                | -         |     4.15 | dav1deuS, hardzao, nython, righi, venomzera    |
|           17 |     3217 | 2024-04-03 | ODDIK           | W   | 0.370      | -            | -                | -                | -         |     4.27 | dav1deuS, hardzao, nython, righi, venomzera    |
|           16 |     3502 | 2024-03-18 | ODDIK           | W   | 0.263      | -            | -                | -                | -         |     3.13 | dav1deuS, destiny, hardzao, nython, venomzera  |
|           15 |     3545 | 2024-03-16 | ODDIK           | W   | 0.250      | -            | -                | -                | -         |     3.00 | dav1deuS, destiny, hardzao, nython, venomzera  |
|           14 |     3562 | 2024-03-15 | Case            | W   | 0.243      | -            | -                | -                | -         |     2.27 | dav1deuS, destiny, hardzao, nython, venomzera  |
|           13 |     3594 | 2024-03-14 | Solid           | L   | 0.236      | -            | -                | -                | -         |    -5.49 | dav1deuS, destiny, hardzao, nython, venomzera  |
|           12 |     3603 | 2024-03-14 | Flamengo        | W   | 0.235      | -            | -                | -                | -         |     0.27 | dav1deuS, destiny, hardzao, nython, venomzera  |
|           11 |     3622 | 2024-03-13 | Case            | W   | 0.230      | -            | -                | -                | -         |     2.13 | dav1deuS, destiny, hardzao, nython, venomzera  |
|           10 |     3634 | 2024-03-13 | Galorys         | W   | 0.229      | -            | -                | -                | -         |     1.87 | dav1deuS, destiny, hardzao, nython, venomzera  |
|            9 |     3666 | 2024-03-12 | BESTIA          | W   | 0.222      | -            | -                | -                | -         |     2.90 | dav1deuS, destiny, hardzao, nython, venomzera  |
|            8 |     3684 | 2024-03-11 | Corinthians     | W   | 0.216      | -            | -                | -                | -         |     0.28 | dav1deuS, destiny, hardzao, nython, venomzera  |
|            7 |     3720 | 2024-03-09 | W7M             | W   | 0.204      | -            | -                | -                | -         |     1.36 | dav1deuS, destiny, hardzao, nython, venomzera  |
|            6 |     3767 | 2024-03-07 | VELOX           | W   | 0.190      | -            | -                | -                | -         |     0.14 | dav1deuS, destiny, hardzao, nython, venomzera  |
|            5 |     3885 | 2024-03-03 | ODDIK           | L   | 0.162      | -            | -                | -                | -         |    -3.12 | dav1deuS, destiny, hardzao, nython, venomzera  |
|            4 |     3917 | 2024-03-02 | paiN            | L   | 0.155      | -            | -                | -                | -         |    -0.67 | dav1deuS, destiny, hardzao, nython, venomzera  |
|            3 |     3932 | 2024-03-01 | Wildcard        | W   | 0.150      | -            | -                | -                | 1 (0.150) |     1.16 | dav1deuS, destiny, hardzao, nython, venomzera  |
|            2 |     4333 | 2024-02-13 | Imperial        | L   | 0.037      | -            | -                | -                | -         |    -0.31 | dav1deuS, destiny, hardzao, nython, venomzera  |
|            1 |     4336 | 2024-02-13 | Imperial        | W   | 0.037      | -            | -                | -                | -         |     0.86 | dav1deuS, destiny, hardzao, nython, venomzera  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($24,516.70)
- Divide that value by the 5th highest value among all rosters ($320,603.98)
- The final value (0.08) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-14 |      1.000 | $2,000.00      | $2,000.00       |
| 2024-06-16 |      0.864 | $1,500.00      | $1,295.69       |
| 2024-06-10 |      0.823 | $750.00        | $617.62         |
| 2024-06-09 |      0.816 | $11,500.00     | $9,387.41       |
| 2024-05-19 |      0.676 | $10,000.00     | $6,755.56       |
| 2024-03-18 |      0.263 | $3,500.00      | $918.75         |
| 2024-03-14 |      0.236 | $15,000.00     | $3,541.67       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
