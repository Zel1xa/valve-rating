### Roster Details<br />
Team Name: RED Canids<br />
Roster: coldzera, dav1deuS, HEN1, nython, venomzera<br />
Global Rank: [38](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [9]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1140.8<br />
<br />
Final Rank Value (1140.8) = Starting Rank Value (1073.4) + Head To Head Adjustments (67.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.472[<sup>1</sup>](#table2)
- Bounty Collected: 0.479[<sup>2</sup>](#table1)
- Opponent Network: 0.242[<sup>2</sup>](#table1)
- LAN Wins: 0.115[<sup>2</sup>](#table1)

The average of these factors is 0.327<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1073.4
- 400 + ( ( 0.327 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1073.4


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
|           86 |      292 | 2024-07-28 | MIBR            | L   | 1.000      | -            | -                | -                | -         |    -7.39 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           85 |      297 | 2024-07-28 | paiN            | L   | 1.000      | -            | -                | -                | -         |    -8.06 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           84 |      352 | 2024-07-26 | ODDIK           | L   | 1.000      | -            | -                | -                | -         |   -22.47 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           83 |      419 | 2024-07-24 | Fluxo           | W   | 1.000      | -            | -                | -                | 0 (0.000) |    15.48 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           82 |      421 | 2024-07-24 | ODDIK           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.72 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           81 |      453 | 2024-07-23 | KRÜ             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.11 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           80 |      456 | 2024-07-23 | LaChampionsLiga | W   | 1.000      | -            | -                | -                | 0 (0.000) |     0.42 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           79 |      494 | 2024-07-22 | paiN Academy    | W   | 1.000      | -            | -                | -                | 0 (0.000) |     0.42 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           78 |      517 | 2024-07-21 | BESTIA          | L   | 1.000      | -            | -                | -                | -         |   -23.57 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           77 |      548 | 2024-07-20 | Case            | W   | 1.000      | 0.384        | -                | 0.778 (0.299)    | 0 (0.000) |     5.34 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           76 |      583 | 2024-07-19 | Intense         | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.38 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           75 |      688 | 2024-07-17 | Hype            | W   | 1.000      | 0.450        | -                | 0.476 (0.214)    | -         |     5.40 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           74 |      693 | 2024-07-17 | Hype            | W   | 1.000      | 0.450        | -                | 0.476 (0.214)    | -         |     5.68 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           73 |      748 | 2024-07-16 | Sharks          | W   | 1.000      | 0.450        | -                | 0.546 (0.246)    | -         |     7.85 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           72 |      754 | 2024-07-16 | Sharks          | W   | 1.000      | 0.450        | -                | 0.546 (0.246)    | -         |     8.40 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           71 |      846 | 2024-07-13 | Legacy          | L   | 1.000      | -            | -                | -                | -         |   -19.39 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           70 |      875 | 2024-07-11 | KRÜ             | W   | 1.000      | -            | -                | -                | -         |     5.29 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           69 |      910 | 2024-07-09 | Bounty Hunters  | W   | 1.000      | -            | -                | -                | -         |     7.72 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           68 |      933 | 2024-07-08 | SPORT           | W   | 1.000      | -            | -                | -                | -         |     2.52 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           67 |     1049 | 2024-06-15 | fnatic          | L   | 0.856      | -            | -                | -                | -         |    -4.35 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           66 |     1082 | 2024-06-14 | KOI             | L   | 0.850      | -            | -                | -                | -         |   -16.12 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           65 |     1088 | 2024-06-14 | fnatic          | W   | 0.849      | 0.548        | 0.371 (0.172)    | 0.680 (0.317)    | 1 (0.849) |    22.41 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           64 |     1236 | 2024-06-09 | BESTIA          | L   | 0.816      | -            | -                | -                | -         |   -17.33 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           63 |     1241 | 2024-06-09 | Imperial        | L   | 0.815      | -            | -                | -                | -         |    -8.63 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           62 |     1374 | 2024-06-07 | Intense         | W   | 0.801      | -            | -                | -                | -         |     2.37 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           61 |     1414 | 2024-06-06 | Imperial        | W   | 0.796      | 0.450        | 0.233 (0.084)    | 0.658 (0.236)    | -         |    16.36 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           60 |     1485 | 2024-06-05 | 9z              | W   | 0.789      | 0.450        | 0.404 (0.143)    | 0.591 (0.210)    | -         |    21.41 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           59 |     1899 | 2024-05-21 | Sharks          | L   | 0.689      | -            | -                | -                | -         |   -15.11 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           58 |     1901 | 2024-05-21 | Sharks          | W   | 0.689      | -            | -                | -                | -         |     6.55 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           57 |     1932 | 2024-05-20 | Fluxo           | L   | 0.683      | -            | -                | -                | -         |   -12.47 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           56 |     1935 | 2024-05-20 | Fluxo           | W   | 0.682      | 0.450        | 0.123 (0.038)    | 0.701 (0.215)    | -         |     9.13 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           55 |     1968 | 2024-05-19 | 9z              | W   | 0.675      | 0.371        | 0.404 (0.101)    | -                | -         |    18.57 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           54 |     1989 | 2024-05-18 | ODDIK           | W   | 0.669      | 0.371        | 0.099 (0.025)    | -                | -         |     6.06 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           53 |     2061 | 2024-05-16 | Fluxo           | W   | 0.655      | 0.371        | 0.123 (0.030)    | -                | -         |     9.95 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           52 |     2103 | 2024-05-15 | 9z              | L   | 0.650      | -            | -                | -                | -         |    -2.14 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           51 |     2105 | 2024-05-15 | 9z              | W   | 0.649      | 0.450        | 0.404 (0.118)    | -                | -         |    18.56 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           50 |     2162 | 2024-05-14 | Corinthians     | W   | 0.643      | -            | -                | -                | -         |     0.72 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           49 |     2167 | 2024-05-14 | Corinthians     | W   | 0.642      | -            | -                | -                | -         |     0.73 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           48 |     2180 | 2024-05-14 | BESTIA          | W   | 0.641      | 0.371        | 0.096 (0.023)    | -                | -         |     6.93 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           47 |     2198 | 2024-05-13 | Sharks          | L   | 0.635      | -            | -                | -                | -         |   -12.99 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           46 |     2218 | 2024-05-12 | Vikings KR      | W   | 0.629      | -            | -                | -                | -         |     3.51 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           45 |     2226 | 2024-05-12 | FURIA Academy   | W   | 0.628      | -            | -                | -                | -         |     0.76 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           44 |     2282 | 2024-05-10 | paiN            | L   | 0.614      | -            | -                | -                | -         |    -3.43 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           43 |     2298 | 2024-05-09 | Intense         | W   | 0.609      | -            | -                | -                | -         |     2.39 | dav1deuS, destiny, hardzao, nython, venomzera  |
|           42 |     2316 | 2024-05-08 | paiN            | L   | 0.603      | -            | -                | -                | -         |    -3.23 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           41 |     2318 | 2024-05-08 | paiN            | W   | 0.603      | 0.450        | 0.324 (0.088)    | 0.839 (0.227)    | -         |    16.06 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           40 |     2319 | 2024-05-08 | Solid           | L   | 0.602      | -            | -                | -                | -         |   -14.48 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           39 |     2362 | 2024-05-06 | Intense         | W   | 0.587      | -            | -                | -                | -         |     2.29 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           38 |     2594 | 2024-04-25 | BESTIA          | W   | 0.516      | -            | -                | -                | -         |     4.97 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           37 |     2596 | 2024-04-25 | BESTIA          | W   | 0.516      | -            | -                | -                | -         |     5.17 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           36 |     2823 | 2024-04-17 | MIBR            | L   | 0.463      | -            | -                | -                | -         |    -1.88 | dav1deuS, hardzao, nython, righi, venomzera    |
|           35 |     2831 | 2024-04-17 | O PLANO         | W   | 0.462      | -            | -                | -                | -         |     0.64 | dav1deuS, hardzao, nython, righi, venomzera    |
|           34 |     2864 | 2024-04-16 | LaChampionsLiga | W   | 0.456      | -            | -                | -                | -         |     0.30 | dav1deuS, hardzao, nython, righi, venomzera    |
|           33 |     2914 | 2024-04-13 | Imperial        | L   | 0.436      | -            | -                | -                | -         |    -3.68 | dav1deuS, hardzao, nython, righi, venomzera    |
|           32 |     2933 | 2024-04-12 | W7M             | W   | 0.428      | -            | -                | -                | -         |     2.61 | dav1deuS, hardzao, nython, righi, venomzera    |
|           31 |     2989 | 2024-04-10 | 2GAME           | W   | 0.416      | -            | -                | -                | -         |     1.15 | dav1deuS, hardzao, nython, righi, venomzera    |
|           30 |     2992 | 2024-04-10 | 2GAME           | W   | 0.416      | -            | -                | -                | -         |     1.16 | dav1deuS, hardzao, nython, righi, venomzera    |
|           29 |     2995 | 2024-04-10 | paiN            | L   | 0.415      | -            | -                | -                | -         |    -1.90 | dav1deuS, hardzao, nython, righi, venomzera    |
|           28 |     3042 | 2024-04-09 | W7M             | W   | 0.409      | -            | -                | -                | -         |     2.56 | dav1deuS, hardzao, nython, righi, venomzera    |
|           27 |     3047 | 2024-04-09 | W7M             | W   | 0.409      | -            | -                | -                | -         |     2.62 | dav1deuS, hardzao, nython, righi, venomzera    |
|           26 |     3050 | 2024-04-09 | MIBR            | L   | 0.408      | -            | -                | -                | -         |    -1.81 | dav1deuS, hardzao, nython, righi, venomzera    |
|           25 |     3081 | 2024-04-08 | BESTIA          | W   | 0.402      | -            | -                | -                | -         |     4.60 | dav1deuS, hardzao, nython, righi, venomzera    |
|           24 |     3087 | 2024-04-08 | Bounty Hunters  | W   | 0.401      | -            | -                | -                | -         |     3.36 | dav1deuS, hardzao, nython, righi, venomzera    |
|           23 |     3117 | 2024-04-07 | Imperial        | L   | 0.396      | -            | -                | -                | -         |    -3.18 | dav1deuS, hardzao, nython, righi, venomzera    |
|           22 |     3136 | 2024-04-06 | W7M             | L   | 0.388      | -            | -                | -                | -         |    -9.85 | dav1deuS, hardzao, nython, righi, venomzera    |
|           21 |     3175 | 2024-04-04 | Case            | L   | 0.376      | -            | -                | -                | -         |    -8.78 | dav1deuS, hardzao, nython, righi, venomzera    |
|           20 |     3180 | 2024-04-04 | Case            | W   | 0.376      | -            | -                | -                | -         |     3.09 | dav1deuS, hardzao, nython, righi, venomzera    |
|           19 |     3196 | 2024-04-04 | Fluxo           | W   | 0.374      | -            | -                | -                | -         |     5.23 | dav1deuS, hardzao, nython, righi, venomzera    |
|           18 |     3216 | 2024-04-03 | ODDIK           | W   | 0.369      | -            | -                | -                | -         |     4.14 | dav1deuS, hardzao, nython, righi, venomzera    |
|           17 |     3219 | 2024-04-03 | ODDIK           | W   | 0.369      | -            | -                | -                | -         |     4.27 | dav1deuS, hardzao, nython, righi, venomzera    |
|           16 |     3504 | 2024-03-18 | ODDIK           | W   | 0.262      | -            | -                | -                | -         |     3.12 | dav1deuS, destiny, hardzao, nython, venomzera  |
|           15 |     3547 | 2024-03-16 | ODDIK           | W   | 0.249      | -            | -                | -                | -         |     3.00 | dav1deuS, destiny, hardzao, nython, venomzera  |
|           14 |     3564 | 2024-03-15 | Case            | W   | 0.242      | -            | -                | -                | -         |     2.26 | dav1deuS, destiny, hardzao, nython, venomzera  |
|           13 |     3596 | 2024-03-14 | Solid           | L   | 0.235      | -            | -                | -                | -         |    -5.46 | dav1deuS, destiny, hardzao, nython, venomzera  |
|           12 |     3605 | 2024-03-14 | Flamengo        | W   | 0.234      | -            | -                | -                | -         |     0.27 | dav1deuS, destiny, hardzao, nython, venomzera  |
|           11 |     3624 | 2024-03-13 | Case            | W   | 0.229      | -            | -                | -                | -         |     2.12 | dav1deuS, destiny, hardzao, nython, venomzera  |
|           10 |     3636 | 2024-03-13 | Galorys         | W   | 0.228      | -            | -                | -                | -         |     1.86 | dav1deuS, destiny, hardzao, nython, venomzera  |
|            9 |     3668 | 2024-03-12 | BESTIA          | W   | 0.221      | -            | -                | -                | -         |     2.88 | dav1deuS, destiny, hardzao, nython, venomzera  |
|            8 |     3686 | 2024-03-11 | Corinthians     | W   | 0.215      | -            | -                | -                | -         |     0.28 | dav1deuS, destiny, hardzao, nython, venomzera  |
|            7 |     3722 | 2024-03-09 | W7M             | W   | 0.203      | -            | -                | -                | -         |     1.36 | dav1deuS, destiny, hardzao, nython, venomzera  |
|            6 |     3769 | 2024-03-07 | VELOX           | W   | 0.189      | -            | -                | -                | -         |     0.14 | dav1deuS, destiny, hardzao, nython, venomzera  |
|            5 |     3887 | 2024-03-03 | ODDIK           | L   | 0.161      | -            | -                | -                | -         |    -3.10 | dav1deuS, destiny, hardzao, nython, venomzera  |
|            4 |     3919 | 2024-03-02 | paiN            | L   | 0.154      | -            | -                | -                | -         |    -0.67 | dav1deuS, destiny, hardzao, nython, venomzera  |
|            3 |     3934 | 2024-03-01 | Wildcard        | W   | 0.149      | -            | -                | -                | 1 (0.149) |     1.16 | dav1deuS, destiny, hardzao, nython, venomzera  |
|            2 |     4335 | 2024-02-13 | Imperial        | L   | 0.036      | -            | -                | -                | -         |    -0.30 | dav1deuS, destiny, hardzao, nython, venomzera  |
|            1 |     4338 | 2024-02-13 | Imperial        | W   | 0.036      | -            | -                | -                | -         |     0.84 | dav1deuS, destiny, hardzao, nython, venomzera  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($24,477.58)
- Divide that value by the 5th highest value among all rosters ($320,329.44)
- The final value (0.08) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-14 |      1.000 | $2,000.00      | $2,000.00       |
| 2024-06-16 |      0.863 | $1,500.00      | $1,294.31       |
| 2024-06-10 |      0.823 | $750.00        | $616.93         |
| 2024-06-09 |      0.815 | $11,500.00     | $9,376.76       |
| 2024-05-19 |      0.675 | $10,000.00     | $6,746.30       |
| 2024-03-18 |      0.262 | $3,500.00      | $915.51         |
| 2024-03-14 |      0.235 | $15,000.00     | $3,527.78       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
