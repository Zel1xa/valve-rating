### Roster Details<br />
Team Name: RED Canids<br />
Roster: coldzera, dav1deuS, HEN1, nython, venomzera<br />
Global Rank: [38](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [9]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1142.5<br />
<br />
Final Rank Value (1142.5) = Starting Rank Value (1075.3) + Head To Head Adjustments (67.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.473[<sup>1</sup>](#table2)
- Bounty Collected: 0.480[<sup>2</sup>](#table1)
- Opponent Network: 0.248[<sup>2</sup>](#table1)
- LAN Wins: 0.116[<sup>2</sup>](#table1)

The average of these factors is 0.329<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1075.3
- 400 + ( ( 0.329 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 1075.3


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
|           88 |       51 | 2024-08-03 | ODDIK           | L   | 1.000      | -            | -                | -                | -         |   -18.22 | coldzera, dav1deuS, HEN1, nython, venomzera    |
|           87 |       58 | 2024-08-03 | Vikings KR      | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.73 | coldzera, dav1deuS, HEN1, nython, venomzera    |
|           86 |      286 | 2024-07-28 | MIBR            | L   | 1.000      | -            | -                | -                | -         |    -7.39 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           85 |      291 | 2024-07-28 | paiN            | L   | 1.000      | -            | -                | -                | -         |    -8.06 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           84 |      346 | 2024-07-26 | ODDIK           | L   | 1.000      | -            | -                | -                | -         |   -22.49 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           83 |      413 | 2024-07-24 | Fluxo           | W   | 1.000      | -            | -                | -                | 0 (0.000) |    15.48 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           82 |      415 | 2024-07-24 | ODDIK           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.70 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           81 |      447 | 2024-07-23 | KRÜ             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.09 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           80 |      450 | 2024-07-23 | LaChampionsLiga | W   | 1.000      | -            | -                | -                | 0 (0.000) |     0.42 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           79 |      488 | 2024-07-22 | paiN Academy    | W   | 1.000      | -            | -                | -                | 0 (0.000) |     0.41 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           78 |      511 | 2024-07-21 | BESTIA          | L   | 1.000      | -            | -                | -                | -         |   -23.59 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           77 |      542 | 2024-07-20 | Case            | W   | 1.000      | 0.384        | -                | 0.795 (0.306)    | 0 (0.000) |     5.32 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           76 |      577 | 2024-07-19 | Intense         | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.36 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           75 |      682 | 2024-07-17 | Hype            | W   | 1.000      | 0.450        | -                | 0.485 (0.218)    | -         |     5.38 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           74 |      687 | 2024-07-17 | Hype            | W   | 1.000      | 0.450        | -                | 0.485 (0.218)    | -         |     5.66 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           73 |      742 | 2024-07-16 | Sharks          | W   | 1.000      | 0.450        | -                | 0.558 (0.251)    | -         |     7.84 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           72 |      748 | 2024-07-16 | Sharks          | W   | 1.000      | 0.450        | -                | 0.558 (0.251)    | -         |     8.39 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           71 |      840 | 2024-07-13 | Legacy          | L   | 1.000      | -            | -                | -                | -         |   -19.40 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           70 |      869 | 2024-07-11 | KRÜ             | W   | 1.000      | -            | -                | -                | -         |     5.28 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           69 |      904 | 2024-07-09 | Bounty Hunters  | W   | 1.000      | -            | -                | -                | -         |     7.71 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           68 |      927 | 2024-07-08 | SPORT           | W   | 1.000      | -            | -                | -                | -         |     2.48 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           67 |     1043 | 2024-06-15 | fnatic          | L   | 0.860      | -            | -                | -                | -         |    -4.40 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           66 |     1076 | 2024-06-14 | KOI             | L   | 0.854      | -            | -                | -                | -         |   -16.21 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           65 |     1082 | 2024-06-14 | fnatic          | W   | 0.852      | 0.548        | 0.371 (0.173)    | 0.696 (0.325)    | 1 (0.852) |    22.46 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           64 |     1230 | 2024-06-09 | BESTIA          | L   | 0.820      | -            | -                | -                | -         |   -17.42 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           63 |     1235 | 2024-06-09 | Imperial        | L   | 0.819      | -            | -                | -                | -         |    -8.66 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           62 |     1368 | 2024-06-07 | Intense         | W   | 0.805      | -            | -                | -                | -         |     2.36 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           61 |     1408 | 2024-06-06 | Imperial        | W   | 0.799      | 0.450        | 0.234 (0.084)    | 0.674 (0.242)    | -         |    16.43 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           60 |     1479 | 2024-06-05 | 9z              | W   | 0.792      | 0.450        | 0.404 (0.144)    | 0.606 (0.216)    | -         |    21.48 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           59 |     1893 | 2024-05-21 | Sharks          | L   | 0.693      | -            | -                | -                | -         |   -15.19 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           58 |     1895 | 2024-05-21 | Sharks          | W   | 0.692      | -            | -                | -                | -         |     6.58 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           57 |     1926 | 2024-05-20 | Fluxo           | L   | 0.686      | -            | -                | -                | -         |   -12.54 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           56 |     1929 | 2024-05-20 | Fluxo           | W   | 0.686      | 0.450        | 0.123 (0.038)    | 0.716 (0.221)    | -         |     9.18 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           55 |     1962 | 2024-05-19 | 9z              | W   | 0.678      | 0.371        | 0.404 (0.102)    | -                | -         |    18.65 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           54 |     1983 | 2024-05-18 | ODDIK           | W   | 0.672      | 0.371        | 0.099 (0.025)    | -                | -         |     6.07 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           53 |     2055 | 2024-05-16 | Fluxo           | W   | 0.659      | 0.371        | 0.123 (0.030)    | -                | -         |    10.00 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           52 |     2097 | 2024-05-15 | 9z              | L   | 0.653      | -            | -                | -                | -         |    -2.16 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           51 |     2099 | 2024-05-15 | 9z              | W   | 0.653      | 0.450        | 0.404 (0.119)    | -                | -         |    18.65 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           50 |     2156 | 2024-05-14 | Corinthians     | W   | 0.646      | -            | -                | -                | -         |     0.72 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           49 |     2161 | 2024-05-14 | Corinthians     | W   | 0.646      | -            | -                | -                | -         |     0.72 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           48 |     2174 | 2024-05-14 | BESTIA          | W   | 0.644      | 0.371        | 0.096 (0.023)    | -                | -         |     6.95 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           47 |     2192 | 2024-05-13 | Sharks          | L   | 0.639      | -            | -                | -                | -         |   -13.05 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           46 |     2212 | 2024-05-12 | Vikings KR      | W   | 0.633      | -            | -                | -                | -         |     3.52 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           45 |     2220 | 2024-05-12 | FURIA Academy   | W   | 0.631      | -            | -                | -                | -         |     0.76 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           44 |     2276 | 2024-05-10 | paiN            | L   | 0.617      | -            | -                | -                | -         |    -3.44 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           43 |     2292 | 2024-05-09 | Intense         | W   | 0.612      | -            | -                | -                | -         |     2.38 | dav1deuS, destiny, hardzao, nython, venomzera  |
|           42 |     2310 | 2024-05-08 | paiN            | L   | 0.606      | -            | -                | -                | -         |    -3.23 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           41 |     2312 | 2024-05-08 | paiN            | W   | 0.606      | 0.450        | 0.325 (0.089)    | 0.857 (0.234)    | -         |    16.16 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           40 |     2313 | 2024-05-08 | Solid           | L   | 0.605      | -            | -                | -                | -         |   -14.57 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           39 |     2356 | 2024-05-06 | Intense         | W   | 0.590      | -            | -                | -                | -         |     2.29 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           38 |     2588 | 2024-04-25 | BESTIA          | W   | 0.519      | -            | -                | -                | -         |     4.98 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           37 |     2590 | 2024-04-25 | BESTIA          | W   | 0.519      | -            | -                | -                | -         |     5.18 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           36 |     2817 | 2024-04-17 | MIBR            | L   | 0.466      | -            | -                | -                | -         |    -1.89 | dav1deuS, hardzao, nython, righi, venomzera    |
|           35 |     2825 | 2024-04-17 | O PLANO         | W   | 0.466      | -            | -                | -                | -         |     0.63 | dav1deuS, hardzao, nython, righi, venomzera    |
|           34 |     2858 | 2024-04-16 | LaChampionsLiga | W   | 0.460      | -            | -                | -                | -         |     0.30 | dav1deuS, hardzao, nython, righi, venomzera    |
|           33 |     2908 | 2024-04-13 | Imperial        | L   | 0.439      | -            | -                | -                | -         |    -3.70 | dav1deuS, hardzao, nython, righi, venomzera    |
|           32 |     2927 | 2024-04-12 | W7M             | W   | 0.431      | -            | -                | -                | -         |     2.62 | dav1deuS, hardzao, nython, righi, venomzera    |
|           31 |     2983 | 2024-04-10 | 2GAME           | W   | 0.419      | -            | -                | -                | -         |     1.15 | dav1deuS, hardzao, nython, righi, venomzera    |
|           30 |     2986 | 2024-04-10 | 2GAME           | W   | 0.419      | -            | -                | -                | -         |     1.16 | dav1deuS, hardzao, nython, righi, venomzera    |
|           29 |     2989 | 2024-04-10 | paiN            | L   | 0.418      | -            | -                | -                | -         |    -1.91 | dav1deuS, hardzao, nython, righi, venomzera    |
|           28 |     3036 | 2024-04-09 | W7M             | W   | 0.413      | -            | -                | -                | -         |     2.57 | dav1deuS, hardzao, nython, righi, venomzera    |
|           27 |     3041 | 2024-04-09 | W7M             | W   | 0.412      | -            | -                | -                | -         |     2.63 | dav1deuS, hardzao, nython, righi, venomzera    |
|           26 |     3044 | 2024-04-09 | MIBR            | L   | 0.412      | -            | -                | -                | -         |    -1.83 | dav1deuS, hardzao, nython, righi, venomzera    |
|           25 |     3075 | 2024-04-08 | BESTIA          | W   | 0.406      | -            | -                | -                | -         |     4.63 | dav1deuS, hardzao, nython, righi, venomzera    |
|           24 |     3081 | 2024-04-08 | Bounty Hunters  | W   | 0.404      | -            | -                | -                | -         |     3.39 | dav1deuS, hardzao, nython, righi, venomzera    |
|           23 |     3111 | 2024-04-07 | Imperial        | L   | 0.399      | -            | -                | -                | -         |    -3.20 | dav1deuS, hardzao, nython, righi, venomzera    |
|           22 |     3130 | 2024-04-06 | W7M             | L   | 0.391      | -            | -                | -                | -         |    -9.95 | dav1deuS, hardzao, nython, righi, venomzera    |
|           21 |     3169 | 2024-04-04 | Case            | L   | 0.380      | -            | -                | -                | -         |    -8.87 | dav1deuS, hardzao, nython, righi, venomzera    |
|           20 |     3174 | 2024-04-04 | Case            | W   | 0.379      | -            | -                | -                | -         |     3.11 | dav1deuS, hardzao, nython, righi, venomzera    |
|           19 |     3190 | 2024-04-04 | Fluxo           | W   | 0.377      | -            | -                | -                | -         |     5.28 | dav1deuS, hardzao, nython, righi, venomzera    |
|           18 |     3210 | 2024-04-03 | ODDIK           | W   | 0.373      | -            | -                | -                | -         |     4.17 | dav1deuS, hardzao, nython, righi, venomzera    |
|           17 |     3213 | 2024-04-03 | ODDIK           | W   | 0.372      | -            | -                | -                | -         |     4.30 | dav1deuS, hardzao, nython, righi, venomzera    |
|           16 |     3498 | 2024-03-18 | ODDIK           | W   | 0.265      | -            | -                | -                | -         |     3.15 | dav1deuS, destiny, hardzao, nython, venomzera  |
|           15 |     3541 | 2024-03-16 | ODDIK           | W   | 0.252      | -            | -                | -                | -         |     3.03 | dav1deuS, destiny, hardzao, nython, venomzera  |
|           14 |     3558 | 2024-03-15 | Case            | W   | 0.245      | -            | -                | -                | -         |     2.29 | dav1deuS, destiny, hardzao, nython, venomzera  |
|           13 |     3590 | 2024-03-14 | Solid           | L   | 0.239      | -            | -                | -                | -         |    -5.55 | dav1deuS, destiny, hardzao, nython, venomzera  |
|           12 |     3599 | 2024-03-14 | Flamengo        | W   | 0.237      | -            | -                | -                | -         |     0.27 | dav1deuS, destiny, hardzao, nython, venomzera  |
|           11 |     3618 | 2024-03-13 | Case            | W   | 0.232      | -            | -                | -                | -         |     2.15 | dav1deuS, destiny, hardzao, nython, venomzera  |
|           10 |     3630 | 2024-03-13 | Galorys         | W   | 0.231      | -            | -                | -                | -         |     1.89 | dav1deuS, destiny, hardzao, nython, venomzera  |
|            9 |     3662 | 2024-03-12 | BESTIA          | W   | 0.224      | -            | -                | -                | -         |     2.93 | dav1deuS, destiny, hardzao, nython, venomzera  |
|            8 |     3680 | 2024-03-11 | Corinthians     | W   | 0.218      | -            | -                | -                | -         |     0.28 | dav1deuS, destiny, hardzao, nython, venomzera  |
|            7 |     3716 | 2024-03-09 | W7M             | W   | 0.206      | -            | -                | -                | -         |     1.38 | dav1deuS, destiny, hardzao, nython, venomzera  |
|            6 |     3763 | 2024-03-07 | VELOX           | W   | 0.193      | -            | -                | -                | -         |     0.14 | dav1deuS, destiny, hardzao, nython, venomzera  |
|            5 |     3881 | 2024-03-03 | ODDIK           | L   | 0.165      | -            | -                | -                | -         |    -3.17 | dav1deuS, destiny, hardzao, nython, venomzera  |
|            4 |     3913 | 2024-03-02 | paiN            | L   | 0.158      | -            | -                | -                | -         |    -0.68 | dav1deuS, destiny, hardzao, nython, venomzera  |
|            3 |     3928 | 2024-03-01 | Wildcard        | W   | 0.152      | -            | -                | -                | 1 (0.152) |     1.18 | dav1deuS, destiny, hardzao, nython, venomzera  |
|            2 |     4329 | 2024-02-13 | Imperial        | L   | 0.040      | -            | -                | -                | -         |    -0.33 | dav1deuS, destiny, hardzao, nython, venomzera  |
|            1 |     4332 | 2024-02-13 | Imperial        | W   | 0.040      | -            | -                | -                | -         |     0.92 | dav1deuS, destiny, hardzao, nython, venomzera  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($24,622.32)
- Divide that value by the 5th highest value among all rosters ($321,345.23)
- The final value (0.08) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-14 |      1.000 | $2,000.00      | $2,000.00       |
| 2024-06-16 |      0.866 | $1,500.00      | $1,299.44       |
| 2024-06-10 |      0.826 | $750.00        | $619.50         |
| 2024-06-09 |      0.819 | $11,500.00     | $9,416.16       |
| 2024-05-19 |      0.678 | $10,000.00     | $6,780.56       |
| 2024-03-18 |      0.265 | $3,500.00      | $927.50         |
| 2024-03-14 |      0.239 | $15,000.00     | $3,579.17       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
