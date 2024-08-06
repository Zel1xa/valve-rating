### Roster Details<br />
Team Name: Sharks<br />
Roster: doc, gafolo, koala, pepe, rdnzao<br />
Global Rank: [55](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [14]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1021.8<br />
<br />
Final Rank Value (1021.8) = Starting Rank Value (969.6) + Head To Head Adjustments (52.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.396[<sup>1</sup>](#table2)
- Bounty Collected: 0.426[<sup>2</sup>](#table1)
- Opponent Network: 0.285[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.277<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 969.6
- 400 + ( ( 0.277 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 969.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                           |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           93 |      127 | 2024-08-02 | paiN              | L   | 1.000      | -            | -                | -                | -         |    -3.52 | doc, gafolo, koala, pepe, rdnzao |
|           92 |      157 | 2024-08-01 | Hype              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.10 | doc, gafolo, koala, pepe, rdnzao |
|           91 |      165 | 2024-08-01 | paiN              | L   | 1.000      | -            | -                | -                | -         |    -3.49 | doc, gafolo, koala, pepe, rdnzao |
|           90 |      198 | 2024-07-31 | MIBR              | L   | 1.000      | -            | -                | -                | -         |    -4.63 | doc, gafolo, koala, pepe, rdnzao |
|           89 |      208 | 2024-07-31 | Solid             | W   | 1.000      | 0.371        | -                | 0.807 (0.299)    | 0 (0.000) |    12.34 | doc, gafolo, koala, pepe, rdnzao |
|           88 |      242 | 2024-07-30 | Hype              | W   | 1.000      | -            | -                | -                | 0 (0.000) |    10.29 | doc, gafolo, koala, pepe, rdnzao |
|           87 |      315 | 2024-07-28 | Bad News Chickens | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.51 | doc, gafolo, koala, pepe, rdnzao |
|           86 |      363 | 2024-07-26 | Imperial          | L   | 1.000      | -            | -                | -                | -         |    -8.58 | doc, gafolo, koala, pepe, rdnzao |
|           85 |      390 | 2024-07-25 | BESTIA            | W   | 1.000      | -            | -                | -                | 0 (0.000) |    16.14 | doc, gafolo, koala, pepe, rdnzao |
|           84 |      397 | 2024-07-25 | Patins da Ferrari | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.26 | doc, gafolo, koala, pepe, rdnzao |
|           83 |      439 | 2024-07-24 | Bad News Chickens | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.46 | doc, gafolo, koala, pepe, rdnzao |
|           82 |      446 | 2024-07-24 | Yawara            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.04 | doc, gafolo, koala, pepe, rdnzao |
|           81 |      466 | 2024-07-23 | ODDIK             | L   | 1.000      | -            | -                | -                | -         |   -14.05 | doc, gafolo, koala, pepe, rdnzao |
|           80 |      469 | 2024-07-23 | W7M               | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.18 | doc, gafolo, koala, pepe, rdnzao |
|           79 |      555 | 2024-07-20 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |    -7.61 | doc, gafolo, koala, pepe, rdnzao |
|           78 |      608 | 2024-07-19 | Hype              | W   | 1.000      | -            | -                | -                | 0 (0.000) |    12.55 | doc, gafolo, koala, pepe, rdnzao |
|           77 |      633 | 2024-07-18 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |    -8.05 | doc, gafolo, koala, pepe, rdnzao |
|           76 |      635 | 2024-07-18 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |    -8.63 | doc, gafolo, koala, pepe, rdnzao |
|           75 |      698 | 2024-07-17 | ODDIK             | W   | 1.000      | 0.450        | 0.099 (0.045)    | 0.805 (0.362)    | -         |    17.45 | doc, gafolo, koala, pepe, rdnzao |
|           74 |      709 | 2024-07-17 | ODDIK             | W   | 1.000      | 0.450        | 0.099 (0.045)    | 0.805 (0.362)    | -         |    19.02 | doc, gafolo, koala, pepe, rdnzao |
|           73 |      763 | 2024-07-16 | RED Canids        | L   | 1.000      | -            | -                | -                | -         |    -7.85 | doc, gafolo, koala, pepe, rdnzao |
|           72 |      769 | 2024-07-16 | RED Canids        | L   | 1.000      | -            | -                | -                | -         |    -8.40 | doc, gafolo, koala, pepe, rdnzao |
|           71 |      813 | 2024-07-15 | KRÜ               | L   | 1.000      | -            | -                | -                | -         |   -20.57 | doc, gafolo, koala, pepe, rdnzao |
|           70 |      817 | 2024-07-15 | KRÜ               | W   | 1.000      | 0.450        | -                | 0.479 (0.216)    | -         |    10.55 | doc, gafolo, koala, pepe, rdnzao |
|           69 |      889 | 2024-07-11 | Bounty Hunters    | L   | 1.000      | -            | -                | -                | -         |   -16.69 | doc, gafolo, koala, pepe, rdnzao |
|           68 |      904 | 2024-07-10 | BESTIA            | W   | 1.000      | 0.371        | 0.096 (0.036)    | 0.776 (0.288)    | -         |    17.00 | doc, gafolo, koala, pepe, rdnzao |
|           67 |      924 | 2024-07-09 | KRÜ               | L   | 1.000      | -            | -                | -                | -         |   -21.06 | doc, gafolo, koala, pepe, rdnzao |
|           66 |      946 | 2024-07-08 | Patins da Ferrari | W   | 1.000      | -            | -                | -                | -         |     8.99 | doc, gafolo, koala, pepe, rdnzao |
|           65 |      982 | 2024-06-30 | Patins da Ferrari | L   | 0.955      | -            | -                | -                | -         |   -21.57 | doc, gafolo, koala, pepe, rdnzao |
|           64 |      996 | 2024-06-28 | KRÜ               | W   | 0.941      | -            | -                | -                | -         |     8.92 | doc, gafolo, koala, pepe, rdnzao |
|           63 |      997 | 2024-06-28 | Bounty Hunters    | L   | 0.940      | -            | -                | -                | -         |   -18.29 | doc, gafolo, koala, pepe, rdnzao |
|           62 |     1001 | 2024-06-27 | Galorys           | W   | 0.935      | -            | -                | -                | -         |     8.60 | doc, gafolo, koala, pepe, rdnzao |
|           61 |     1004 | 2024-06-27 | inSanitY          | L   | 0.934      | -            | -                | -                | -         |   -15.60 | doc, gafolo, koala, pepe, rdnzao |
|           60 |     1105 | 2024-06-14 | Fluxo             | L   | 0.848      | -            | -                | -                | -         |   -11.44 | doc, gafolo, koala, pepe, rdnzao |
|           59 |     1227 | 2024-06-10 | Vikings KR        | W   | 0.820      | -            | -                | -                | -         |     5.30 | doc, gafolo, koala, pepe, rdnzao |
|           58 |     1260 | 2024-06-09 | paiN              | L   | 0.814      | -            | -                | -                | -         |    -4.12 | doc, gafolo, koala, pepe, rdnzao |
|           57 |     1279 | 2024-06-09 | BESTIA            | W   | 0.813      | 0.450        | 0.096 (0.035)    | 0.776 (0.284)    | -         |    12.54 | doc, gafolo, koala, pepe, rdnzao |
|           56 |     1331 | 2024-06-08 | Hype              | W   | 0.807      | -            | -                | -                | -         |     8.66 | doc, gafolo, koala, pepe, rdnzao |
|           55 |     1346 | 2024-06-08 | Patins da Ferrari | L   | 0.806      | -            | -                | -                | -         |   -19.75 | doc, gafolo, koala, pepe, rdnzao |
|           54 |     1373 | 2024-06-07 | 9z                | L   | 0.802      | -            | -                | -                | -         |    -2.15 | doc, gafolo, koala, pepe, rdnzao |
|           53 |     1432 | 2024-06-06 | paiN              | W   | 0.795      | 0.450        | 0.324 (0.116)    | 0.839 (0.300)    | -         |    21.30 | doc, gafolo, koala, pepe, rdnzao |
|           52 |     1501 | 2024-06-05 | Imperial          | L   | 0.788      | -            | -                | -                | -         |    -4.88 | doc, gafolo, koala, pepe, rdnzao |
|           51 |     1551 | 2024-06-04 | BESTIA            | W   | 0.782      | 0.450        | 0.096 (0.034)    | 0.776 (0.273)    | -         |    13.83 | doc, gafolo, koala, pepe, rdnzao |
|           50 |     1878 | 2024-05-22 | Imperial          | W   | 0.694      | 0.450        | 0.233 (0.073)    | -                | -         |    17.59 | doc, drg, gafolo, pepe, rdnzao   |
|           49 |     1882 | 2024-05-22 | Imperial          | L   | 0.694      | -            | -                | -                | -         |    -4.15 | doc, drg, gafolo, pepe, rdnzao   |
|           48 |     1909 | 2024-05-21 | Case              | L   | 0.689      | -            | -                | -                | -         |   -13.30 | doc, drg, gafolo, pepe, rdnzao   |
|           47 |     1910 | 2024-05-21 | Case              | W   | 0.689      | 0.450        | -                | 0.778 (0.241)    | -         |     8.45 | doc, drg, gafolo, pepe, rdnzao   |
|           46 |     1914 | 2024-05-21 | RED Canids        | W   | 0.688      | 0.450        | 0.076 (0.024)    | 0.732 (0.227)    | -         |    15.09 | doc, drg, gafolo, pepe, rdnzao   |
|           45 |     1916 | 2024-05-21 | RED Canids        | L   | 0.688      | -            | -                | -                | -         |    -6.55 | doc, drg, gafolo, pepe, rdnzao   |
|           44 |     2047 | 2024-05-17 | ODDIK             | L   | 0.661      | -            | -                | -                | -         |   -12.16 | doc, drg, gafolo, rdnzao, togs   |
|           43 |     2072 | 2024-05-16 | W7M               | W   | 0.655      | -            | -                | -                | -         |     4.83 | doc, drg, gafolo, rdnzao, togs   |
|           42 |     2075 | 2024-05-16 | W7M               | W   | 0.655      | -            | -                | -                | -         |     5.03 | doc, drg, gafolo, rdnzao, togs   |
|           41 |     2080 | 2024-05-16 | Hype              | W   | 0.654      | -            | -                | -                | -         |     7.30 | doc, drg, gafolo, rdnzao, togs   |
|           40 |     2119 | 2024-05-15 | Vikings KR        | W   | 0.649      | -            | -                | -                | -         |     5.77 | doc, drg, gafolo, rdnzao, togs   |
|           39 |     2127 | 2024-05-15 | 9z                | L   | 0.648      | -            | -                | -                | -         |    -1.02 | doc, drg, gafolo, rdnzao, togs   |
|           38 |     2186 | 2024-05-14 | Fluxo             | L   | 0.641      | -            | -                | -                | -         |    -7.11 | doc, drg, gafolo, rdnzao, togs   |
|           37 |     2213 | 2024-05-13 | RED Canids        | W   | 0.635      | 0.384        | 0.076 (0.019)    | -                | -         |    12.97 | doc, drg, gafolo, rdnzao, togs   |
|           36 |     2220 | 2024-05-13 | W7M               | W   | 0.634      | -            | -                | -                | -         |     5.74 | doc, drg, gafolo, rdnzao, togs   |
|           35 |     2268 | 2024-05-11 | W7M               | W   | 0.621      | -            | -                | -                | -         |     5.89 | doc, drg, gafolo, rdnzao, togs   |
|           34 |     2312 | 2024-05-09 | BESTIA            | L   | 0.609      | -            | -                | -                | -         |   -10.49 | doc, drg, gafolo, rdnzao, togs   |
|           33 |     2332 | 2024-05-08 | 9z                | L   | 0.602      | -            | -                | -                | -         |    -0.87 | doc, drg, gafolo, rdnzao, togs   |
|           32 |     2370 | 2024-05-06 | BESTIA            | W   | 0.589      | 0.435        | 0.096 (0.025)    | -                | -         |     8.34 | doc, drg, gafolo, rdnzao, togs   |
|           31 |     2969 | 2024-04-11 | paiN              | L   | 0.421      | -            | -                | -                | -         |    -1.07 | doc, drg, gafolo, rdnzao, togs   |
|           30 |     3232 | 2024-04-03 | 2GAME             | W   | 0.369      | -            | -                | -                | -         |     1.83 | doc, drg, gafolo, rdnzao, togs   |
|           29 |     3235 | 2024-04-03 | 2GAME             | W   | 0.368      | -            | -                | -                | -         |     1.86 | doc, drg, gafolo, rdnzao, togs   |
|           28 |     3604 | 2024-03-14 | MIBR              | L   | 0.236      | -            | -                | -                | -         |    -0.62 | doc, drg, gafolo, rdnzao, togs   |
|           27 |     3606 | 2024-03-14 | MIBR              | L   | 0.235      | -            | -                | -                | -         |    -0.63 | doc, drg, gafolo, rdnzao, togs   |
|           26 |     3634 | 2024-03-13 | Yawara            | W   | 0.228      | -            | -                | -                | -         |     0.53 | doc, drg, gafolo, rdnzao, togs   |
|           25 |     3637 | 2024-03-13 | ODDIK             | W   | 0.228      | -            | -                | -                | -         |     3.82 | doc, drg, gafolo, rdnzao, togs   |
|           24 |     3710 | 2024-03-11 | Fluxo             | L   | 0.213      | -            | -                | -                | -         |    -2.67 | doc, drg, gafolo, rdnzao, togs   |
|           23 |     3738 | 2024-03-09 | Case              | L   | 0.201      | -            | -                | -                | -         |    -3.59 | doc, drg, gafolo, rdnzao, togs   |
|           22 |     3802 | 2024-03-07 | Corinthians       | W   | 0.186      | -            | -                | -                | -         |     0.40 | doc, drg, gafolo, rdnzao, togs   |
|           21 |     3856 | 2024-03-05 | Solid             | W   | 0.174      | -            | -                | -                | -         |     2.16 | doc, drg, gafolo, rdnzao, togs   |
|           20 |     3862 | 2024-03-05 | Solid             | W   | 0.174      | -            | -                | -                | -         |     2.19 | doc, drg, gafolo, rdnzao, togs   |
|           19 |     4056 | 2024-02-24 | Galorys           | W   | 0.109      | -            | -                | -                | -         |     1.35 | doc, drg, gafolo, rdnzao, togs   |
|           18 |     4064 | 2024-02-24 | Galorys           | W   | 0.109      | -            | -                | -                | -         |     1.36 | doc, drg, gafolo, rdnzao, togs   |
|           17 |     4068 | 2024-02-24 | Fluxo             | L   | 0.108      | -            | -                | -                | -         |    -1.35 | doc, drg, gafolo, rdnzao, togs   |
|           16 |     4121 | 2024-02-21 | Corinthians       | W   | 0.089      | -            | -                | -                | -         |     0.20 | doc, drg, gafolo, rdnzao, togs   |
|           15 |     4126 | 2024-02-21 | Case              | W   | 0.088      | -            | -                | -                | -         |     1.27 | doc, drg, gafolo, rdnzao, togs   |
|           14 |     4131 | 2024-02-21 | Galorys           | W   | 0.087      | -            | -                | -                | -         |     1.12 | doc, drg, gafolo, rdnzao, togs   |
|           13 |     4156 | 2024-02-20 | Flamengo          | L   | 0.081      | -            | -                | -                | -         |    -2.40 | doc, drg, gafolo, rdnzao, togs   |
|           12 |     4161 | 2024-02-20 | Case              | W   | 0.080      | -            | -                | -                | -         |     1.16 | doc, drg, gafolo, rdnzao, togs   |
|           11 |     4185 | 2024-02-19 | Solid             | W   | 0.074      | -            | -                | -                | -         |     0.94 | doc, drg, gafolo, rdnzao, togs   |
|           10 |     4199 | 2024-02-18 | Galorys           | W   | 0.069      | -            | -                | -                | -         |     0.89 | doc, drg, gafolo, rdnzao, togs   |
|            9 |     4222 | 2024-02-17 | W7M               | L   | 0.062      | -            | -                | -                | -         |    -1.31 | doc, drg, gafolo, rdnzao, togs   |
|            8 |     4227 | 2024-02-17 | Galorys           | L   | 0.061      | -            | -                | -                | -         |    -1.14 | doc, drg, gafolo, rdnzao, togs   |
|            7 |     4262 | 2024-02-16 | W7M               | W   | 0.053      | -            | -                | -                | -         |     0.55 | doc, drg, gafolo, rdnzao, togs   |
|            6 |     4280 | 2024-02-15 | Case              | L   | 0.048      | -            | -                | -                | -         |    -0.82 | doc, drg, gafolo, rdnzao, togs   |
|            5 |     4286 | 2024-02-15 | Fluxo             | L   | 0.047      | -            | -                | -                | -         |    -0.59 | doc, drg, gafolo, rdnzao, togs   |
|            4 |     4287 | 2024-02-15 | Fluxo             | L   | 0.047      | -            | -                | -                | -         |    -0.59 | doc, drg, gafolo, rdnzao, togs   |
|            3 |     4315 | 2024-02-14 | Hype              | W   | 0.042      | -            | -                | -                | -         |     0.05 | doc, drg, gafolo, rdnzao, togs   |
|            2 |     4326 | 2024-02-14 | Galorys           | W   | 0.040      | -            | -                | -                | -         |     0.52 | doc, drg, gafolo, rdnzao, togs   |
|            1 |     4370 | 2024-02-12 | Solid             | W   | 0.028      | -            | -                | -                | -         |     0.36 | doc, drg, gafolo, rdnzao, togs   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($9,610.60)
- Divide that value by the 5th highest value among all rosters ($320,109.81)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-02 |      1.000 | $750.00        | $750.00         |
| 2024-06-28 |      0.940 | $500.00        | $470.24         |
| 2024-06-16 |      0.861 | $2,500.00      | $2,151.39       |
| 2024-06-10 |      0.822 | $750.00        | $616.37         |
| 2024-06-09 |      0.815 | $5,000.00      | $4,073.15       |
| 2024-05-19 |      0.674 | $1,000.00      | $673.89         |
| 2024-02-25 |      0.114 | $5,000.00      | $572.22         |
| 2024-02-21 |      0.087 | $3,500.00      | $303.33         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
