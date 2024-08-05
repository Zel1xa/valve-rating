### Roster Details<br />
Team Name: Sharks<br />
Roster: doc, gafolo, koala, pepe, rdnzao<br />
Global Rank: [55](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [14]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1023.6<br />
<br />
Final Rank Value (1023.6) = Starting Rank Value (971.9) + Head To Head Adjustments (51.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.397[<sup>1</sup>](#table2)
- Bounty Collected: 0.427[<sup>2</sup>](#table1)
- Opponent Network: 0.292[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.279<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 971.9
- 400 + ( ( 0.279 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 971.9


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
|           93 |      104 | 2024-08-02 | paiN              | L   | 1.000      | -            | -                | -                | -         |    -3.51 | doc, gafolo, koala, pepe, rdnzao |
|           92 |      134 | 2024-08-01 | Hype              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.08 | doc, gafolo, koala, pepe, rdnzao |
|           91 |      142 | 2024-08-01 | paiN              | L   | 1.000      | -            | -                | -                | -         |    -3.48 | doc, gafolo, koala, pepe, rdnzao |
|           90 |      175 | 2024-07-31 | MIBR              | L   | 1.000      | -            | -                | -                | -         |    -4.62 | doc, gafolo, koala, pepe, rdnzao |
|           89 |      185 | 2024-07-31 | Solid             | W   | 1.000      | 0.371        | -                | 0.825 (0.306)    | 0 (0.000) |    12.32 | doc, gafolo, koala, pepe, rdnzao |
|           88 |      219 | 2024-07-30 | Hype              | W   | 1.000      | -            | -                | -                | 0 (0.000) |    10.27 | doc, gafolo, koala, pepe, rdnzao |
|           87 |      292 | 2024-07-28 | Bad News Chickens | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.48 | doc, gafolo, koala, pepe, rdnzao |
|           86 |      340 | 2024-07-26 | Imperial          | L   | 1.000      | -            | -                | -                | -         |    -8.55 | doc, gafolo, koala, pepe, rdnzao |
|           85 |      367 | 2024-07-25 | BESTIA            | W   | 1.000      | -            | -                | -                | 0 (0.000) |    16.14 | doc, gafolo, koala, pepe, rdnzao |
|           84 |      374 | 2024-07-25 | Patins da Ferrari | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.23 | doc, gafolo, koala, pepe, rdnzao |
|           83 |      416 | 2024-07-24 | Bad News Chickens | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.43 | doc, gafolo, koala, pepe, rdnzao |
|           82 |      423 | 2024-07-24 | Yawara            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.01 | doc, gafolo, koala, pepe, rdnzao |
|           81 |      443 | 2024-07-23 | ODDIK             | L   | 1.000      | -            | -                | -                | -         |   -14.07 | doc, gafolo, koala, pepe, rdnzao |
|           80 |      446 | 2024-07-23 | W7M               | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.15 | doc, gafolo, koala, pepe, rdnzao |
|           79 |      532 | 2024-07-20 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |    -7.60 | doc, gafolo, koala, pepe, rdnzao |
|           78 |      585 | 2024-07-19 | Hype              | W   | 1.000      | -            | -                | -                | 0 (0.000) |    12.52 | doc, gafolo, koala, pepe, rdnzao |
|           77 |      610 | 2024-07-18 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |    -8.04 | doc, gafolo, koala, pepe, rdnzao |
|           76 |      612 | 2024-07-18 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |    -8.61 | doc, gafolo, koala, pepe, rdnzao |
|           75 |      675 | 2024-07-17 | ODDIK             | W   | 1.000      | 0.450        | 0.099 (0.045)    | 0.822 (0.370)    | -         |    17.43 | doc, gafolo, koala, pepe, rdnzao |
|           74 |      686 | 2024-07-17 | ODDIK             | W   | 1.000      | 0.450        | 0.099 (0.045)    | 0.822 (0.370)    | -         |    19.00 | doc, gafolo, koala, pepe, rdnzao |
|           73 |      740 | 2024-07-16 | RED Canids        | L   | 1.000      | -            | -                | -                | -         |    -7.84 | doc, gafolo, koala, pepe, rdnzao |
|           72 |      746 | 2024-07-16 | RED Canids        | L   | 1.000      | -            | -                | -                | -         |    -8.38 | doc, gafolo, koala, pepe, rdnzao |
|           71 |      790 | 2024-07-15 | KRÜ               | L   | 1.000      | -            | -                | -                | -         |   -20.59 | doc, gafolo, koala, pepe, rdnzao |
|           70 |      794 | 2024-07-15 | KRÜ               | W   | 1.000      | 0.450        | -                | 0.488 (0.220)    | -         |    10.53 | doc, gafolo, koala, pepe, rdnzao |
|           69 |      866 | 2024-07-11 | Bounty Hunters    | L   | 1.000      | -            | -                | -                | -         |   -16.70 | doc, gafolo, koala, pepe, rdnzao |
|           68 |      881 | 2024-07-10 | BESTIA            | W   | 1.000      | 0.371        | 0.096 (0.035)    | 0.792 (0.293)    | -         |    16.99 | doc, gafolo, koala, pepe, rdnzao |
|           67 |      901 | 2024-07-09 | KRÜ               | L   | 1.000      | -            | -                | -                | -         |   -21.08 | doc, gafolo, koala, pepe, rdnzao |
|           66 |      923 | 2024-07-08 | Patins da Ferrari | W   | 1.000      | -            | -                | -                | -         |     8.95 | doc, gafolo, koala, pepe, rdnzao |
|           65 |      959 | 2024-06-30 | Patins da Ferrari | L   | 0.961      | -            | -                | -                | -         |   -21.75 | doc, gafolo, koala, pepe, rdnzao |
|           64 |      973 | 2024-06-28 | KRÜ               | W   | 0.947      | -            | -                | -                | -         |     8.95 | doc, gafolo, koala, pepe, rdnzao |
|           63 |      974 | 2024-06-28 | Bounty Hunters    | L   | 0.946      | -            | -                | -                | -         |   -18.43 | doc, gafolo, koala, pepe, rdnzao |
|           62 |      978 | 2024-06-27 | Galorys           | W   | 0.941      | -            | -                | -                | -         |     8.61 | doc, gafolo, koala, pepe, rdnzao |
|           61 |      981 | 2024-06-27 | inSanitY          | L   | 0.940      | -            | -                | -                | -         |   -15.70 | doc, gafolo, koala, pepe, rdnzao |
|           60 |     1082 | 2024-06-14 | Fluxo             | L   | 0.854      | -            | -                | -                | -         |   -11.52 | doc, gafolo, koala, pepe, rdnzao |
|           59 |     1204 | 2024-06-10 | Vikings KR        | W   | 0.826      | -            | -                | -                | -         |     5.30 | doc, gafolo, koala, pepe, rdnzao |
|           58 |     1237 | 2024-06-09 | paiN              | L   | 0.820      | -            | -                | -                | -         |    -4.15 | doc, gafolo, koala, pepe, rdnzao |
|           57 |     1256 | 2024-06-09 | BESTIA            | W   | 0.819      | 0.450        | 0.096 (0.035)    | 0.792 (0.292)    | -         |    12.60 | doc, gafolo, koala, pepe, rdnzao |
|           56 |     1308 | 2024-06-08 | Hype              | W   | 0.813      | -            | -                | -                | -         |     8.68 | doc, gafolo, koala, pepe, rdnzao |
|           55 |     1323 | 2024-06-08 | Patins da Ferrari | L   | 0.812      | -            | -                | -                | -         |   -19.95 | doc, gafolo, koala, pepe, rdnzao |
|           54 |     1350 | 2024-06-07 | 9z                | L   | 0.808      | -            | -                | -                | -         |    -2.18 | doc, gafolo, koala, pepe, rdnzao |
|           53 |     1409 | 2024-06-06 | paiN              | W   | 0.801      | 0.450        | 0.325 (0.117)    | 0.856 (0.309)    | -         |    21.46 | doc, gafolo, koala, pepe, rdnzao |
|           52 |     1478 | 2024-06-05 | Imperial          | L   | 0.794      | -            | -                | -                | -         |    -4.90 | doc, gafolo, koala, pepe, rdnzao |
|           51 |     1528 | 2024-06-04 | BESTIA            | W   | 0.788      | 0.450        | 0.096 (0.034)    | 0.792 (0.281)    | -         |    13.92 | doc, gafolo, koala, pepe, rdnzao |
|           50 |     1855 | 2024-05-22 | Imperial          | W   | 0.700      | 0.450        | 0.234 (0.074)    | -                | -         |    17.76 | doc, drg, gafolo, pepe, rdnzao   |
|           49 |     1859 | 2024-05-22 | Imperial          | L   | 0.700      | -            | -                | -                | -         |    -4.17 | doc, drg, gafolo, pepe, rdnzao   |
|           48 |     1886 | 2024-05-21 | Case              | L   | 0.695      | -            | -                | -                | -         |   -13.44 | doc, drg, gafolo, pepe, rdnzao   |
|           47 |     1887 | 2024-05-21 | Case              | W   | 0.695      | 0.450        | -                | 0.795 (0.249)    | -         |     8.50 | doc, drg, gafolo, pepe, rdnzao   |
|           46 |     1891 | 2024-05-21 | RED Canids        | W   | 0.694      | 0.450        | 0.077 (0.024)    | 0.748 (0.234)    | -         |    15.23 | doc, drg, gafolo, pepe, rdnzao   |
|           45 |     1893 | 2024-05-21 | RED Canids        | L   | 0.694      | -            | -                | -                | -         |    -6.59 | doc, drg, gafolo, pepe, rdnzao   |
|           44 |     2024 | 2024-05-17 | ODDIK             | L   | 0.667      | -            | -                | -                | -         |   -12.30 | doc, drg, gafolo, rdnzao, togs   |
|           43 |     2049 | 2024-05-16 | W7M               | W   | 0.661      | -            | -                | -                | -         |     4.84 | doc, drg, gafolo, rdnzao, togs   |
|           42 |     2052 | 2024-05-16 | W7M               | W   | 0.661      | -            | -                | -                | -         |     5.05 | doc, drg, gafolo, rdnzao, togs   |
|           41 |     2057 | 2024-05-16 | Hype              | W   | 0.660      | -            | -                | -                | -         |     7.33 | doc, drg, gafolo, rdnzao, togs   |
|           40 |     2096 | 2024-05-15 | Vikings KR        | W   | 0.655      | -            | -                | -                | -         |     5.79 | doc, drg, gafolo, rdnzao, togs   |
|           39 |     2104 | 2024-05-15 | 9z                | L   | 0.654      | -            | -                | -                | -         |    -1.03 | doc, drg, gafolo, rdnzao, togs   |
|           38 |     2163 | 2024-05-14 | Fluxo             | L   | 0.647      | -            | -                | -                | -         |    -7.17 | doc, drg, gafolo, rdnzao, togs   |
|           37 |     2190 | 2024-05-13 | RED Canids        | W   | 0.641      | 0.384        | 0.077 (0.019)    | -                | -         |    13.09 | doc, drg, gafolo, rdnzao, togs   |
|           36 |     2197 | 2024-05-13 | W7M               | W   | 0.640      | -            | -                | -                | -         |     5.76 | doc, drg, gafolo, rdnzao, togs   |
|           35 |     2245 | 2024-05-11 | W7M               | W   | 0.627      | -            | -                | -                | -         |     5.91 | doc, drg, gafolo, rdnzao, togs   |
|           34 |     2289 | 2024-05-09 | BESTIA            | L   | 0.615      | -            | -                | -                | -         |   -10.63 | doc, drg, gafolo, rdnzao, togs   |
|           33 |     2309 | 2024-05-08 | 9z                | L   | 0.608      | -            | -                | -                | -         |    -0.89 | doc, drg, gafolo, rdnzao, togs   |
|           32 |     2347 | 2024-05-06 | BESTIA            | W   | 0.595      | 0.435        | 0.096 (0.025)    | -                | -         |     8.38 | doc, drg, gafolo, rdnzao, togs   |
|           31 |     2946 | 2024-04-11 | paiN              | L   | 0.427      | -            | -                | -                | -         |    -1.07 | doc, drg, gafolo, rdnzao, togs   |
|           30 |     3209 | 2024-04-03 | 2GAME             | W   | 0.375      | -            | -                | -                | -         |     1.84 | doc, drg, gafolo, rdnzao, togs   |
|           29 |     3212 | 2024-04-03 | 2GAME             | W   | 0.374      | -            | -                | -                | -         |     1.87 | doc, drg, gafolo, rdnzao, togs   |
|           28 |     3581 | 2024-03-14 | MIBR              | L   | 0.242      | -            | -                | -                | -         |    -0.64 | doc, drg, gafolo, rdnzao, togs   |
|           27 |     3583 | 2024-03-14 | MIBR              | L   | 0.241      | -            | -                | -                | -         |    -0.64 | doc, drg, gafolo, rdnzao, togs   |
|           26 |     3611 | 2024-03-13 | Yawara            | W   | 0.234      | -            | -                | -                | -         |     0.54 | doc, drg, gafolo, rdnzao, togs   |
|           25 |     3614 | 2024-03-13 | ODDIK             | W   | 0.234      | -            | -                | -                | -         |     3.91 | doc, drg, gafolo, rdnzao, togs   |
|           24 |     3687 | 2024-03-11 | Fluxo             | L   | 0.219      | -            | -                | -                | -         |    -2.74 | doc, drg, gafolo, rdnzao, togs   |
|           23 |     3715 | 2024-03-09 | Case              | L   | 0.207      | -            | -                | -                | -         |    -3.71 | doc, drg, gafolo, rdnzao, togs   |
|           22 |     3779 | 2024-03-07 | Corinthians       | W   | 0.192      | -            | -                | -                | -         |     0.41 | doc, drg, gafolo, rdnzao, togs   |
|           21 |     3833 | 2024-03-05 | Solid             | W   | 0.180      | -            | -                | -                | -         |     2.23 | doc, drg, gafolo, rdnzao, togs   |
|           20 |     3839 | 2024-03-05 | Solid             | W   | 0.180      | -            | -                | -                | -         |     2.26 | doc, drg, gafolo, rdnzao, togs   |
|           19 |     4033 | 2024-02-24 | Galorys           | W   | 0.115      | -            | -                | -                | -         |     1.42 | doc, drg, gafolo, rdnzao, togs   |
|           18 |     4041 | 2024-02-24 | Galorys           | W   | 0.115      | -            | -                | -                | -         |     1.43 | doc, drg, gafolo, rdnzao, togs   |
|           17 |     4045 | 2024-02-24 | Fluxo             | L   | 0.114      | -            | -                | -                | -         |    -1.43 | doc, drg, gafolo, rdnzao, togs   |
|           16 |     4098 | 2024-02-21 | Corinthians       | W   | 0.095      | -            | -                | -                | -         |     0.21 | doc, drg, gafolo, rdnzao, togs   |
|           15 |     4103 | 2024-02-21 | Case              | W   | 0.094      | -            | -                | -                | -         |     1.36 | doc, drg, gafolo, rdnzao, togs   |
|           14 |     4108 | 2024-02-21 | Galorys           | W   | 0.093      | -            | -                | -                | -         |     1.20 | doc, drg, gafolo, rdnzao, togs   |
|           13 |     4133 | 2024-02-20 | Flamengo          | L   | 0.087      | -            | -                | -                | -         |    -2.57 | doc, drg, gafolo, rdnzao, togs   |
|           12 |     4138 | 2024-02-20 | Case              | W   | 0.086      | -            | -                | -                | -         |     1.24 | doc, drg, gafolo, rdnzao, togs   |
|           11 |     4162 | 2024-02-19 | Solid             | W   | 0.080      | -            | -                | -                | -         |     1.01 | doc, drg, gafolo, rdnzao, togs   |
|           10 |     4176 | 2024-02-18 | Galorys           | W   | 0.075      | -            | -                | -                | -         |     0.97 | doc, drg, gafolo, rdnzao, togs   |
|            9 |     4199 | 2024-02-17 | W7M               | L   | 0.068      | -            | -                | -                | -         |    -1.44 | doc, drg, gafolo, rdnzao, togs   |
|            8 |     4204 | 2024-02-17 | Galorys           | L   | 0.067      | -            | -                | -                | -         |    -1.25 | doc, drg, gafolo, rdnzao, togs   |
|            7 |     4239 | 2024-02-16 | W7M               | W   | 0.059      | -            | -                | -                | -         |     0.61 | doc, drg, gafolo, rdnzao, togs   |
|            6 |     4257 | 2024-02-15 | Case              | L   | 0.054      | -            | -                | -                | -         |    -0.93 | doc, drg, gafolo, rdnzao, togs   |
|            5 |     4263 | 2024-02-15 | Fluxo             | L   | 0.053      | -            | -                | -                | -         |    -0.67 | doc, drg, gafolo, rdnzao, togs   |
|            4 |     4264 | 2024-02-15 | Fluxo             | L   | 0.053      | -            | -                | -                | -         |    -0.67 | doc, drg, gafolo, rdnzao, togs   |
|            3 |     4292 | 2024-02-14 | Hype              | W   | 0.048      | -            | -                | -                | -         |     0.06 | doc, drg, gafolo, rdnzao, togs   |
|            2 |     4303 | 2024-02-14 | Galorys           | W   | 0.046      | -            | -                | -                | -         |     0.59 | doc, drg, gafolo, rdnzao, togs   |
|            1 |     4347 | 2024-02-12 | Solid             | W   | 0.034      | -            | -                | -                | -         |     0.43 | doc, drg, gafolo, rdnzao, togs   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($9,719.59)
- Divide that value by the 5th highest value among all rosters ($321,880.58)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-02 |      1.000 | $750.00        | $750.00         |
| 2024-06-28 |      0.946 | $500.00        | $473.23         |
| 2024-06-16 |      0.867 | $2,500.00      | $2,166.32       |
| 2024-06-10 |      0.828 | $750.00        | $620.85         |
| 2024-06-09 |      0.821 | $5,000.00      | $4,103.01       |
| 2024-05-19 |      0.680 | $1,000.00      | $679.86         |
| 2024-02-25 |      0.120 | $5,000.00      | $602.08         |
| 2024-02-21 |      0.093 | $3,500.00      | $324.24         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
