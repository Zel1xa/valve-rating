### Roster Details<br />
Team Name: RED Canids<br />
Roster: coldzera, dav1deuS, hardzao, nython, venomzera<br />
Global Rank: [40](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [11]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1113.6<br />
<br />
Final Rank Value (1113.6) = Starting Rank Value (990.0) + Head To Head Adjustments (123.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.469[<sup>1</sup>](#table2)
- Bounty Collected: 0.425[<sup>2</sup>](#table1)
- Opponent Network: 0.241[<sup>2</sup>](#table1)
- LAN Wins: 0.019[<sup>2</sup>](#table1)

The average of these factors is 0.288<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 990.0
- 400 + ( ( 0.288 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 990.0


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
|           82 |      200 | 2024-07-28 | MIBR            | L   | 1.000      | -            | -                | -                | -         |    -6.38 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           81 |      205 | 2024-07-28 | paiN            | L   | 1.000      | -            | -                | -                | -         |    -7.26 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           80 |      260 | 2024-07-26 | ODDIK           | L   | 1.000      | -            | -                | -                | -         |   -21.88 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           79 |      327 | 2024-07-24 | Fluxo           | W   | 1.000      | -            | -                | -                | 0 (0.000) |    16.81 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           78 |      329 | 2024-07-24 | ODDIK           | W   | 1.000      | -            | -                | -                | 0 (0.000) |    10.37 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           77 |      361 | 2024-07-23 | KRÜ             | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.42 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           76 |      364 | 2024-07-23 | LaChampionsLiga | W   | 1.000      | -            | -                | -                | 0 (0.000) |     0.54 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           75 |      402 | 2024-07-22 | paiN Academy    | W   | 1.000      | -            | -                | -                | 0 (0.000) |     0.54 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           74 |      425 | 2024-07-21 | BESTIA          | L   | 1.000      | -            | -                | -                | -         |   -22.42 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           73 |      456 | 2024-07-20 | Case            | W   | 1.000      | 0.384        | -                | 0.750 (0.288)    | 0 (0.000) |     6.56 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           72 |      491 | 2024-07-19 | Intense         | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.22 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           71 |      596 | 2024-07-17 | Hype            | W   | 1.000      | 0.450        | -                | 0.503 (0.226)    | 0 (0.000) |     6.23 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           70 |      601 | 2024-07-17 | Hype            | W   | 1.000      | 0.450        | -                | 0.503 (0.226)    | 0 (0.000) |     6.60 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           69 |      653 | 2024-07-16 | Sharks          | W   | 1.000      | 0.450        | -                | 0.583 (0.262)    | -         |     9.30 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           68 |      659 | 2024-07-16 | Sharks          | W   | 1.000      | 0.450        | -                | 0.583 (0.262)    | -         |    10.03 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           67 |      749 | 2024-07-13 | Legacy          | L   | 1.000      | -            | -                | -                | -         |   -17.22 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           66 |      810 | 2024-07-09 | Bounty Hunters  | W   | 1.000      | -            | -                | -                | -         |     9.38 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           65 |      833 | 2024-07-08 | SPORT           | W   | 1.000      | -            | -                | -                | -         |     3.25 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           64 |     1112 | 2024-06-09 | BESTIA          | L   | 0.835      | -            | -                | -                | -         |   -16.69 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           63 |     1116 | 2024-06-09 | Imperial        | L   | 0.834      | -            | -                | -                | -         |    -8.43 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           62 |     1243 | 2024-06-07 | Intense         | W   | 0.820      | -            | -                | -                | -         |     3.13 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           61 |     1284 | 2024-06-06 | Imperial        | W   | 0.815      | 0.450        | 0.234 (0.086)    | 0.708 (0.260)    | -         |    17.32 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           60 |     1355 | 2024-06-05 | 9z              | W   | 0.808      | 0.450        | 0.136 (0.049)    | 0.528 (0.192)    | -         |    18.06 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           59 |     1765 | 2024-05-21 | Sharks          | L   | 0.708      | -            | -                | -                | -         |   -14.29 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           58 |     1767 | 2024-05-21 | Sharks          | W   | 0.708      | -            | -                | -                | -         |     8.02 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           57 |     1798 | 2024-05-20 | Fluxo           | L   | 0.702      | -            | -                | -                | -         |   -11.46 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           56 |     1801 | 2024-05-20 | Fluxo           | W   | 0.701      | 0.450        | 0.125 (0.039)    | 0.746 (0.235)    | -         |    10.83 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           55 |     1833 | 2024-05-19 | 9z              | W   | 0.694      | 0.371        | 0.136 (0.035)    | -                | -         |    15.12 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           54 |     1854 | 2024-05-18 | ODDIK           | W   | 0.688      | 0.371        | 0.098 (0.025)    | 0.857 (0.218)    | -         |     7.38 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           53 |     1926 | 2024-05-16 | Fluxo           | W   | 0.674      | 0.371        | 0.125 (0.031)    | -                | -         |    11.82 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           52 |     1968 | 2024-05-15 | 9z              | L   | 0.669      | -            | -                | -                | -         |    -5.99 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           51 |     1970 | 2024-05-15 | 9z              | W   | 0.668      | 0.450        | 0.136 (0.041)    | -                | -         |    15.46 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           50 |     2027 | 2024-05-14 | Corinthians     | W   | 0.662      | -            | -                | -                | -         |     0.92 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           49 |     2032 | 2024-05-14 | Corinthians     | W   | 0.661      | -            | -                | -                | -         |     0.93 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           48 |     2045 | 2024-05-14 | BESTIA          | W   | 0.660      | 0.371        | 0.091 (0.022)    | -                | -         |     8.19 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           47 |     2063 | 2024-05-13 | Sharks          | L   | 0.654      | -            | -                | -                | -         |   -12.02 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           46 |     2083 | 2024-05-12 | Vikings KR      | W   | 0.648      | -            | -                | -                | -         |     4.49 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           45 |     2091 | 2024-05-12 | FURIA Academy   | W   | 0.647      | -            | -                | -                | -         |     1.04 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           44 |     2147 | 2024-05-10 | paiN            | L   | 0.633      | -            | -                | -                | -         |    -3.13 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           43 |     2163 | 2024-05-09 | Intense         | W   | 0.628      | -            | -                | -                | -         |     3.16 | dav1deuS, destiny, hardzao, nython, venomzera  |
|           42 |     2180 | 2024-05-08 | paiN            | L   | 0.622      | -            | -                | -                | -         |    -2.93 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           41 |     2182 | 2024-05-08 | paiN            | W   | 0.622      | 0.450        | 0.324 (0.091)    | 0.859 (0.240)    | -         |    16.95 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           40 |     2183 | 2024-05-08 | Solid           | L   | 0.621      | -            | -                | -                | -         |   -13.70 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           39 |     2226 | 2024-05-06 | Intense         | W   | 0.606      | -            | -                | -                | -         |     3.08 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           38 |     2457 | 2024-04-25 | BESTIA          | W   | 0.535      | 0.450        | 0.091 (0.022)    | -                | -         |     6.10 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           37 |     2459 | 2024-04-25 | BESTIA          | W   | 0.535      | -            | -                | -                | -         |     6.38 | coldzera, dav1deuS, hardzao, nython, venomzera |
|           36 |     2686 | 2024-04-17 | MIBR            | L   | 0.482      | -            | -                | -                | -         |    -1.39 | dav1deuS, hardzao, nython, righi, venomzera    |
|           35 |     2694 | 2024-04-17 | O PLANO         | W   | 0.481      | -            | -                | -                | -         |     0.91 | dav1deuS, hardzao, nython, righi, venomzera    |
|           34 |     2727 | 2024-04-16 | LaChampionsLiga | W   | 0.475      | -            | -                | -                | -         |     0.43 | dav1deuS, hardzao, nython, righi, venomzera    |
|           33 |     2777 | 2024-04-13 | Imperial        | L   | 0.455      | -            | -                | -                | -         |    -3.18 | dav1deuS, hardzao, nython, righi, venomzera    |
|           32 |     2796 | 2024-04-12 | W7M             | W   | 0.447      | -            | -                | -                | -         |     3.49 | dav1deuS, hardzao, nython, righi, venomzera    |
|           31 |     2852 | 2024-04-10 | 2GAME           | W   | 0.435      | -            | -                | -                | -         |     1.71 | dav1deuS, hardzao, nython, righi, venomzera    |
|           30 |     2855 | 2024-04-10 | 2GAME           | W   | 0.435      | -            | -                | -                | -         |     1.74 | dav1deuS, hardzao, nython, righi, venomzera    |
|           29 |     2858 | 2024-04-10 | paiN            | L   | 0.434      | -            | -                | -                | -         |    -1.72 | dav1deuS, hardzao, nython, righi, venomzera    |
|           28 |     2905 | 2024-04-09 | W7M             | W   | 0.428      | -            | -                | -                | -         |     3.48 | dav1deuS, hardzao, nython, righi, venomzera    |
|           27 |     2910 | 2024-04-09 | W7M             | W   | 0.428      | -            | -                | -                | -         |     3.58 | dav1deuS, hardzao, nython, righi, venomzera    |
|           26 |     2913 | 2024-04-09 | MIBR            | L   | 0.427      | -            | -                | -                | -         |    -1.31 | dav1deuS, hardzao, nython, righi, venomzera    |
|           25 |     2944 | 2024-04-08 | BESTIA          | W   | 0.421      | -            | -                | -                | -         |     5.84 | dav1deuS, hardzao, nython, righi, venomzera    |
|           24 |     2950 | 2024-04-08 | Bounty Hunters  | W   | 0.420      | -            | -                | -                | -         |     4.59 | dav1deuS, hardzao, nython, righi, venomzera    |
|           23 |     2980 | 2024-04-07 | Imperial        | L   | 0.415      | -            | -                | -                | -         |    -2.66 | dav1deuS, hardzao, nython, righi, venomzera    |
|           22 |     2999 | 2024-04-06 | W7M             | L   | 0.407      | -            | -                | -                | -         |    -9.51 | dav1deuS, hardzao, nython, righi, venomzera    |
|           21 |     3038 | 2024-04-04 | Case            | L   | 0.395      | -            | -                | -                | -         |    -8.21 | dav1deuS, hardzao, nython, righi, venomzera    |
|           20 |     3043 | 2024-04-04 | Case            | W   | 0.395      | -            | -                | -                | -         |     4.29 | dav1deuS, hardzao, nython, righi, venomzera    |
|           19 |     3059 | 2024-04-04 | Fluxo           | W   | 0.393      | -            | -                | -                | -         |     6.75 | dav1deuS, hardzao, nython, righi, venomzera    |
|           18 |     3079 | 2024-04-03 | ODDIK           | W   | 0.388      | -            | -                | -                | -         |     5.43 | dav1deuS, hardzao, nython, righi, venomzera    |
|           17 |     3082 | 2024-04-03 | ODDIK           | W   | 0.388      | -            | -                | -                | -         |     5.61 | dav1deuS, hardzao, nython, righi, venomzera    |
|           16 |     3362 | 2024-03-18 | ODDIK           | W   | 0.281      | -            | -                | -                | -         |     4.20 | dav1deuS, destiny, hardzao, nython, venomzera  |
|           15 |     3405 | 2024-03-16 | ODDIK           | W   | 0.268      | -            | -                | -                | -         |     4.06 | dav1deuS, destiny, hardzao, nython, venomzera  |
|           14 |     3421 | 2024-03-15 | Case            | W   | 0.261      | -            | -                | -                | -         |     3.27 | dav1deuS, destiny, hardzao, nython, venomzera  |
|           13 |     3453 | 2024-03-14 | Solid           | L   | 0.254      | -            | -                | -                | -         |    -5.12 | dav1deuS, destiny, hardzao, nython, venomzera  |
|           12 |     3462 | 2024-03-14 | Flamengo        | W   | 0.253      | -            | -                | -                | -         |     0.44 | dav1deuS, destiny, hardzao, nython, venomzera  |
|           11 |     3481 | 2024-03-13 | Case            | W   | 0.248      | -            | -                | -                | -         |     3.12 | dav1deuS, destiny, hardzao, nython, venomzera  |
|           10 |     3492 | 2024-03-13 | Galorys         | W   | 0.247      | -            | -                | -                | -         |     2.63 | dav1deuS, destiny, hardzao, nython, venomzera  |
|            9 |     3523 | 2024-03-12 | BESTIA          | W   | 0.240      | -            | -                | -                | -         |     3.91 | dav1deuS, destiny, hardzao, nython, venomzera  |
|            8 |     3541 | 2024-03-11 | Corinthians     | W   | 0.234      | -            | -                | -                | -         |     0.46 | dav1deuS, destiny, hardzao, nython, venomzera  |
|            7 |     3577 | 2024-03-09 | W7M             | W   | 0.222      | -            | -                | -                | -         |     2.08 | dav1deuS, destiny, hardzao, nython, venomzera  |
|            6 |     3624 | 2024-03-07 | VELOX           | W   | 0.208      | -            | -                | -                | -         |     0.23 | dav1deuS, destiny, hardzao, nython, venomzera  |
|            5 |     3742 | 2024-03-03 | ODDIK           | L   | 0.181      | -            | -                | -                | -         |    -2.84 | dav1deuS, destiny, hardzao, nython, venomzera  |
|            4 |     3774 | 2024-03-02 | paiN            | L   | 0.173      | -            | -                | -                | -         |    -0.61 | dav1deuS, destiny, hardzao, nython, venomzera  |
|            3 |     3789 | 2024-03-01 | Wildcard        | W   | 0.168      | -            | -                | -                | 1 (0.168) |     2.07 | dav1deuS, destiny, hardzao, nython, venomzera  |
|            2 |     4189 | 2024-02-13 | Imperial        | L   | 0.055      | -            | -                | -                | -         |    -0.35 | dav1deuS, destiny, hardzao, nython, venomzera  |
|            1 |     4192 | 2024-02-13 | Imperial        | W   | 0.055      | -            | -                | -                | -         |     1.39 | dav1deuS, destiny, hardzao, nython, venomzera  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($23,958.65)
- Divide that value by the 5th highest value among all rosters ($325,971.18)
- The final value (0.07) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-13 |      1.000 | $2,000.00      | $2,000.00       |
| 2024-06-10 |      0.842 | $750.00        | $631.20         |
| 2024-06-09 |      0.834 | $11,500.00     | $9,595.58       |
| 2024-05-19 |      0.694 | $10,000.00     | $6,936.57       |
| 2024-03-18 |      0.281 | $3,500.00      | $982.11         |
| 2024-03-14 |      0.254 | $15,000.00     | $3,813.19       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
