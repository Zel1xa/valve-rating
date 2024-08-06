### Roster Details<br />
Team Name: RED Canids<br />
Roster: coldzera, dav1deuS, HEN1, nython, venomzera<br />
Global Rank: [38](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [9]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1140.7<br />
<br />
Final Rank Value (1140.7) = Starting Rank Value (1073.3) + Head To Head Adjustments (67.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.472[<sup>1</sup>](#table2)
- Bounty Collected: 0.479[<sup>2</sup>](#table1)
- Opponent Network: 0.242[<sup>2</sup>](#table1)
- LAN Wins: 0.115[<sup>2</sup>](#table1)

The average of these factors is 0.327<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1073.3
- 400 + ( ( 0.327 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1073.3


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
|           88 |       73 | 2024-08-03 | ODDIK           | L   | 1.000      | -            | -                | -                | -         |   -18.21 | coldzera, dav1deuS, HEN1, nython, venomzera    |
|           87 |       80 | 2024-08-03 | Vikings KR      | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.75 | coldzera, dav1deuS, HEN1, nython, venomzera    |
|           86 |      308 | 2024-07-28 | MIBR            | L   | 1.000      | -            | -                | -                | -         |    -7.39 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           85 |      313 | 2024-07-28 | paiN            | L   | 1.000      | -            | -                | -                | -         |    -8.06 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           84 |      368 | 2024-07-26 | ODDIK           | L   | 1.000      | -            | -                | -                | -         |   -22.47 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           83 |      435 | 2024-07-24 | Fluxo           | W   | 1.000      | -            | -                | -                | 0 (0.000) |    15.47 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           82 |      437 | 2024-07-24 | ODDIK           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.72 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           81 |      469 | 2024-07-23 | KRÜ             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.11 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           80 |      472 | 2024-07-23 | LaChampionsLiga | W   | 1.000      | -            | -                | -                | 0 (0.000) |     0.42 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           79 |      510 | 2024-07-22 | paiN Academy    | W   | 1.000      | -            | -                | -                | 0 (0.000) |     0.42 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           78 |      533 | 2024-07-21 | BESTIA          | L   | 1.000      | -            | -                | -                | -         |   -23.57 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           77 |      564 | 2024-07-20 | Case            | W   | 1.000      | 0.384        | -                | 0.778 (0.299)    | 0 (0.000) |     5.34 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           76 |      599 | 2024-07-19 | Intense         | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.38 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           75 |      704 | 2024-07-17 | Hype            | W   | 1.000      | 0.450        | -                | 0.476 (0.214)    | -         |     5.40 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           74 |      709 | 2024-07-17 | Hype            | W   | 1.000      | 0.450        | -                | 0.476 (0.214)    | -         |     5.68 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           73 |      764 | 2024-07-16 | Sharks          | W   | 1.000      | 0.450        | -                | 0.547 (0.246)    | -         |     7.85 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           72 |      770 | 2024-07-16 | Sharks          | W   | 1.000      | 0.450        | -                | 0.547 (0.246)    | -         |     8.40 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           71 |      862 | 2024-07-13 | Legacy          | L   | 1.000      | -            | -                | -                | -         |   -19.39 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           70 |      891 | 2024-07-11 | KRÜ             | W   | 1.000      | -            | -                | -                | -         |     5.29 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           69 |      926 | 2024-07-09 | Bounty Hunters  | W   | 1.000      | -            | -                | -                | -         |     7.72 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           68 |      949 | 2024-07-08 | SPORT           | W   | 1.000      | -            | -                | -                | -         |     2.52 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           67 |     1065 | 2024-06-15 | fnatic          | L   | 0.855      | -            | -                | -                | -         |    -4.31 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           66 |     1098 | 2024-06-14 | KOI             | L   | 0.849      | -            | -                | -                | -         |   -16.04 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           65 |     1104 | 2024-06-14 | fnatic          | W   | 0.848      | 0.548        | 0.371 (0.172)    | 0.680 (0.316)    | 1 (0.848) |    22.43 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           64 |     1252 | 2024-06-09 | BESTIA          | L   | 0.815      | -            | -                | -                | -         |   -17.31 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           63 |     1257 | 2024-06-09 | Imperial        | L   | 0.814      | -            | -                | -                | -         |    -8.62 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           62 |     1390 | 2024-06-07 | Intense         | W   | 0.800      | -            | -                | -                | -         |     2.38 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           61 |     1430 | 2024-06-06 | Imperial        | W   | 0.795      | 0.450        | 0.233 (0.083)    | 0.658 (0.236)    | -         |    16.34 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           60 |     1501 | 2024-06-05 | 9z              | W   | 0.788      | 0.450        | 0.404 (0.143)    | 0.591 (0.210)    | -         |    21.39 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           59 |     1915 | 2024-05-21 | Sharks          | L   | 0.688      | -            | -                | -                | -         |   -15.09 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           58 |     1917 | 2024-05-21 | Sharks          | W   | 0.688      | -            | -                | -                | -         |     6.55 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           57 |     1948 | 2024-05-20 | Fluxo           | L   | 0.682      | -            | -                | -                | -         |   -12.45 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           56 |     1951 | 2024-05-20 | Fluxo           | W   | 0.682      | 0.450        | 0.123 (0.038)    | 0.701 (0.215)    | -         |     9.12 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           55 |     1984 | 2024-05-19 | 9z              | W   | 0.674      | 0.371        | 0.404 (0.101)    | -                | -         |    18.55 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           54 |     2005 | 2024-05-18 | ODDIK           | W   | 0.668      | 0.371        | 0.099 (0.025)    | -                | -         |     6.06 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           53 |     2077 | 2024-05-16 | Fluxo           | W   | 0.655      | 0.371        | 0.123 (0.030)    | -                | -         |     9.93 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           52 |     2119 | 2024-05-15 | 9z              | L   | 0.649      | -            | -                | -                | -         |    -2.13 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           51 |     2121 | 2024-05-15 | 9z              | W   | 0.648      | 0.450        | 0.404 (0.118)    | -                | -         |    18.54 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           50 |     2178 | 2024-05-14 | Corinthians     | W   | 0.642      | -            | -                | -                | -         |     0.72 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           49 |     2183 | 2024-05-14 | Corinthians     | W   | 0.642      | -            | -                | -                | -         |     0.73 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           48 |     2196 | 2024-05-14 | BESTIA          | W   | 0.640      | 0.371        | 0.096 (0.023)    | -                | -         |     6.92 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           47 |     2214 | 2024-05-13 | Sharks          | L   | 0.635      | -            | -                | -                | -         |   -12.96 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           46 |     2234 | 2024-05-12 | Vikings KR      | W   | 0.628      | -            | -                | -                | -         |     3.51 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           45 |     2242 | 2024-05-12 | FURIA Academy   | W   | 0.627      | -            | -                | -                | -         |     0.76 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           44 |     2298 | 2024-05-10 | paiN            | L   | 0.613      | -            | -                | -                | -         |    -3.43 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           43 |     2314 | 2024-05-09 | Intense         | W   | 0.608      | -            | -                | -                | -         |     2.39 | dav1deuS, destiny, hardzao, nython, venomzera  |
|           42 |     2332 | 2024-05-08 | paiN            | L   | 0.602      | -            | -                | -                | -         |    -3.23 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           41 |     2334 | 2024-05-08 | paiN            | W   | 0.602      | 0.450        | 0.324 (0.088)    | 0.839 (0.227)    | -         |    16.03 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           40 |     2335 | 2024-05-08 | Solid           | L   | 0.601      | -            | -                | -                | -         |   -14.45 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           39 |     2378 | 2024-05-06 | Intense         | W   | 0.586      | -            | -                | -                | -         |     2.29 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           38 |     2610 | 2024-04-25 | BESTIA          | W   | 0.515      | -            | -                | -                | -         |     4.97 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           37 |     2612 | 2024-04-25 | BESTIA          | W   | 0.515      | -            | -                | -                | -         |     5.16 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           36 |     2839 | 2024-04-17 | MIBR            | L   | 0.462      | -            | -                | -                | -         |    -1.88 | dav1deuS, hardzao, nython, righi, venomzera    |
|           35 |     2847 | 2024-04-17 | O PLANO         | W   | 0.461      | -            | -                | -                | -         |     0.63 | dav1deuS, hardzao, nython, righi, venomzera    |
|           34 |     2880 | 2024-04-16 | LaChampionsLiga | W   | 0.455      | -            | -                | -                | -         |     0.30 | dav1deuS, hardzao, nython, righi, venomzera    |
|           33 |     2930 | 2024-04-13 | Imperial        | L   | 0.435      | -            | -                | -                | -         |    -3.68 | dav1deuS, hardzao, nython, righi, venomzera    |
|           32 |     2949 | 2024-04-12 | W7M             | W   | 0.427      | -            | -                | -                | -         |     2.61 | dav1deuS, hardzao, nython, righi, venomzera    |
|           31 |     3005 | 2024-04-10 | 2GAME           | W   | 0.415      | -            | -                | -                | -         |     1.15 | dav1deuS, hardzao, nython, righi, venomzera    |
|           30 |     3008 | 2024-04-10 | 2GAME           | W   | 0.415      | -            | -                | -                | -         |     1.16 | dav1deuS, hardzao, nython, righi, venomzera    |
|           29 |     3011 | 2024-04-10 | paiN            | L   | 0.414      | -            | -                | -                | -         |    -1.90 | dav1deuS, hardzao, nython, righi, venomzera    |
|           28 |     3058 | 2024-04-09 | W7M             | W   | 0.408      | -            | -                | -                | -         |     2.56 | dav1deuS, hardzao, nython, righi, venomzera    |
|           27 |     3063 | 2024-04-09 | W7M             | W   | 0.408      | -            | -                | -                | -         |     2.62 | dav1deuS, hardzao, nython, righi, venomzera    |
|           26 |     3066 | 2024-04-09 | MIBR            | L   | 0.407      | -            | -                | -                | -         |    -1.81 | dav1deuS, hardzao, nython, righi, venomzera    |
|           25 |     3097 | 2024-04-08 | BESTIA          | W   | 0.401      | -            | -                | -                | -         |     4.59 | dav1deuS, hardzao, nython, righi, venomzera    |
|           24 |     3103 | 2024-04-08 | Bounty Hunters  | W   | 0.400      | -            | -                | -                | -         |     3.36 | dav1deuS, hardzao, nython, righi, venomzera    |
|           23 |     3133 | 2024-04-07 | Imperial        | L   | 0.395      | -            | -                | -                | -         |    -3.18 | dav1deuS, hardzao, nython, righi, venomzera    |
|           22 |     3152 | 2024-04-06 | W7M             | L   | 0.387      | -            | -                | -                | -         |    -9.83 | dav1deuS, hardzao, nython, righi, venomzera    |
|           21 |     3191 | 2024-04-04 | Case            | L   | 0.375      | -            | -                | -                | -         |    -8.76 | dav1deuS, hardzao, nython, righi, venomzera    |
|           20 |     3196 | 2024-04-04 | Case            | W   | 0.375      | -            | -                | -                | -         |     3.08 | dav1deuS, hardzao, nython, righi, venomzera    |
|           19 |     3212 | 2024-04-04 | Fluxo           | W   | 0.373      | -            | -                | -                | -         |     5.22 | dav1deuS, hardzao, nython, righi, venomzera    |
|           18 |     3232 | 2024-04-03 | ODDIK           | W   | 0.368      | -            | -                | -                | -         |     4.13 | dav1deuS, hardzao, nython, righi, venomzera    |
|           17 |     3235 | 2024-04-03 | ODDIK           | W   | 0.368      | -            | -                | -                | -         |     4.26 | dav1deuS, hardzao, nython, righi, venomzera    |
|           16 |     3520 | 2024-03-18 | ODDIK           | W   | 0.261      | -            | -                | -                | -         |     3.11 | dav1deuS, destiny, hardzao, nython, venomzera  |
|           15 |     3563 | 2024-03-16 | ODDIK           | W   | 0.248      | -            | -                | -                | -         |     2.98 | dav1deuS, destiny, hardzao, nython, venomzera  |
|           14 |     3580 | 2024-03-15 | Case            | W   | 0.241      | -            | -                | -                | -         |     2.25 | dav1deuS, destiny, hardzao, nython, venomzera  |
|           13 |     3612 | 2024-03-14 | Solid           | L   | 0.234      | -            | -                | -                | -         |    -5.44 | dav1deuS, destiny, hardzao, nython, venomzera  |
|           12 |     3621 | 2024-03-14 | Flamengo        | W   | 0.233      | -            | -                | -                | -         |     0.27 | dav1deuS, destiny, hardzao, nython, venomzera  |
|           11 |     3640 | 2024-03-13 | Case            | W   | 0.228      | -            | -                | -                | -         |     2.11 | dav1deuS, destiny, hardzao, nython, venomzera  |
|           10 |     3652 | 2024-03-13 | Galorys         | W   | 0.227      | -            | -                | -                | -         |     1.86 | dav1deuS, destiny, hardzao, nython, venomzera  |
|            9 |     3684 | 2024-03-12 | BESTIA          | W   | 0.220      | -            | -                | -                | -         |     2.88 | dav1deuS, destiny, hardzao, nython, venomzera  |
|            8 |     3702 | 2024-03-11 | Corinthians     | W   | 0.214      | -            | -                | -                | -         |     0.28 | dav1deuS, destiny, hardzao, nython, venomzera  |
|            7 |     3738 | 2024-03-09 | W7M             | W   | 0.202      | -            | -                | -                | -         |     1.35 | dav1deuS, destiny, hardzao, nython, venomzera  |
|            6 |     3785 | 2024-03-07 | VELOX           | W   | 0.188      | -            | -                | -                | -         |     0.14 | dav1deuS, destiny, hardzao, nython, venomzera  |
|            5 |     3903 | 2024-03-03 | ODDIK           | L   | 0.161      | -            | -                | -                | -         |    -3.08 | dav1deuS, destiny, hardzao, nython, venomzera  |
|            4 |     3935 | 2024-03-02 | paiN            | L   | 0.153      | -            | -                | -                | -         |    -0.67 | dav1deuS, destiny, hardzao, nython, venomzera  |
|            3 |     3950 | 2024-03-01 | Wildcard        | W   | 0.148      | -            | -                | -                | 1 (0.148) |     1.15 | dav1deuS, destiny, hardzao, nython, venomzera  |
|            2 |     4351 | 2024-02-13 | Imperial        | L   | 0.036      | -            | -                | -                | -         |    -0.30 | dav1deuS, destiny, hardzao, nython, venomzera  |
|            1 |     4354 | 2024-02-13 | Imperial        | W   | 0.035      | -            | -                | -                | -         |     0.82 | dav1deuS, destiny, hardzao, nython, venomzera  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($24,440.41)
- Divide that value by the 5th highest value among all rosters ($320,068.63)
- The final value (0.08) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-14 |      1.000 | $2,000.00      | $2,000.00       |
| 2024-06-16 |      0.862 | $1,500.00      | $1,292.99       |
| 2024-06-10 |      0.822 | $750.00        | $616.27         |
| 2024-06-09 |      0.814 | $11,500.00     | $9,366.64       |
| 2024-05-19 |      0.674 | $10,000.00     | $6,737.50       |
| 2024-03-18 |      0.261 | $3,500.00      | $912.43         |
| 2024-03-14 |      0.234 | $15,000.00     | $3,514.58       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
