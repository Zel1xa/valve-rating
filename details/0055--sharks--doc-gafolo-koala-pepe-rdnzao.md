### Roster Details<br />
Team Name: Sharks<br />
Roster: doc, gafolo, koala, pepe, rdnzao<br />
Global Rank: [55](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [14]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1025.0<br />
<br />
Final Rank Value (1025.0) = Starting Rank Value (973.4) + Head To Head Adjustments (51.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.397[<sup>1</sup>](#table2)
- Bounty Collected: 0.427[<sup>2</sup>](#table1)
- Opponent Network: 0.297[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.280<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 973.4
- 400 + ( ( 0.280 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 973.4


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
|           93 |       77 | 2024-08-02 | paiN              | L   | 1.000      | -            | -                | -                | -         |    -3.50 | doc, gafolo, koala, pepe, rdnzao |
|           92 |      107 | 2024-08-01 | Hype              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.06 | doc, gafolo, koala, pepe, rdnzao |
|           91 |      115 | 2024-08-01 | paiN              | L   | 1.000      | -            | -                | -                | -         |    -3.46 | doc, gafolo, koala, pepe, rdnzao |
|           90 |      148 | 2024-07-31 | MIBR              | L   | 1.000      | -            | -                | -                | -         |    -4.61 | doc, gafolo, koala, pepe, rdnzao |
|           89 |      158 | 2024-07-31 | Solid             | W   | 1.000      | 0.371        | -                | 0.836 (0.310)    | 0 (0.000) |    12.30 | doc, gafolo, koala, pepe, rdnzao |
|           88 |      192 | 2024-07-30 | Hype              | W   | 1.000      | -            | -                | -                | 0 (0.000) |    10.24 | doc, gafolo, koala, pepe, rdnzao |
|           87 |      265 | 2024-07-28 | Bad News Chickens | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.46 | doc, gafolo, koala, pepe, rdnzao |
|           86 |      313 | 2024-07-26 | Imperial          | L   | 1.000      | -            | -                | -                | -         |    -8.51 | doc, gafolo, koala, pepe, rdnzao |
|           85 |      340 | 2024-07-25 | BESTIA            | W   | 1.000      | -            | -                | -                | 0 (0.000) |    16.14 | doc, gafolo, koala, pepe, rdnzao |
|           84 |      347 | 2024-07-25 | Patins da Ferrari | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.21 | doc, gafolo, koala, pepe, rdnzao |
|           83 |      389 | 2024-07-24 | Bad News Chickens | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.41 | doc, gafolo, koala, pepe, rdnzao |
|           82 |      396 | 2024-07-24 | Yawara            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.00 | doc, gafolo, koala, pepe, rdnzao |
|           81 |      416 | 2024-07-23 | ODDIK             | L   | 1.000      | -            | -                | -                | -         |   -14.08 | doc, gafolo, koala, pepe, rdnzao |
|           80 |      419 | 2024-07-23 | W7M               | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.11 | doc, gafolo, koala, pepe, rdnzao |
|           79 |      505 | 2024-07-20 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |    -7.58 | doc, gafolo, koala, pepe, rdnzao |
|           78 |      558 | 2024-07-19 | Hype              | W   | 1.000      | -            | -                | -                | 0 (0.000) |    12.48 | doc, gafolo, koala, pepe, rdnzao |
|           77 |      583 | 2024-07-18 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |    -8.01 | doc, gafolo, koala, pepe, rdnzao |
|           76 |      585 | 2024-07-18 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |    -8.58 | doc, gafolo, koala, pepe, rdnzao |
|           75 |      648 | 2024-07-17 | ODDIK             | W   | 1.000      | 0.450        | 0.099 (0.044)    | 0.831 (0.374)    | -         |    17.41 | doc, gafolo, koala, pepe, rdnzao |
|           74 |      659 | 2024-07-17 | ODDIK             | W   | 1.000      | 0.450        | 0.099 (0.044)    | 0.831 (0.374)    | -         |    18.98 | doc, gafolo, koala, pepe, rdnzao |
|           73 |      713 | 2024-07-16 | RED Canids        | L   | 1.000      | -            | -                | -                | -         |    -7.81 | doc, gafolo, koala, pepe, rdnzao |
|           72 |      719 | 2024-07-16 | RED Canids        | L   | 1.000      | -            | -                | -                | -         |    -8.36 | doc, gafolo, koala, pepe, rdnzao |
|           71 |      763 | 2024-07-15 | KRÜ               | L   | 1.000      | -            | -                | -                | -         |   -20.61 | doc, gafolo, koala, pepe, rdnzao |
|           70 |      767 | 2024-07-15 | KRÜ               | W   | 1.000      | 0.450        | -                | 0.493 (0.222)    | -         |    10.50 | doc, gafolo, koala, pepe, rdnzao |
|           69 |      839 | 2024-07-11 | Bounty Hunters    | L   | 1.000      | -            | -                | -                | -         |   -16.70 | doc, gafolo, koala, pepe, rdnzao |
|           68 |      854 | 2024-07-10 | BESTIA            | W   | 1.000      | 0.371        | 0.095 (0.035)    | 0.801 (0.297)    | -         |    16.99 | doc, gafolo, koala, pepe, rdnzao |
|           67 |      874 | 2024-07-09 | KRÜ               | L   | 1.000      | -            | -                | -                | -         |   -21.11 | doc, gafolo, koala, pepe, rdnzao |
|           66 |      896 | 2024-07-08 | Patins da Ferrari | W   | 1.000      | -            | -                | -                | -         |     8.92 | doc, gafolo, koala, pepe, rdnzao |
|           65 |      932 | 2024-06-30 | Patins da Ferrari | L   | 0.968      | -            | -                | -                | -         |   -21.94 | doc, gafolo, koala, pepe, rdnzao |
|           64 |      946 | 2024-06-28 | KRÜ               | W   | 0.955      | -            | -                | -                | -         |     8.98 | doc, gafolo, koala, pepe, rdnzao |
|           63 |      947 | 2024-06-28 | Bounty Hunters    | L   | 0.954      | -            | -                | -                | -         |   -18.59 | doc, gafolo, koala, pepe, rdnzao |
|           62 |      951 | 2024-06-27 | Galorys           | W   | 0.949      | -            | -                | -                | -         |     8.63 | doc, gafolo, koala, pepe, rdnzao |
|           61 |      954 | 2024-06-27 | inSanitY          | L   | 0.947      | -            | -                | -                | -         |   -15.83 | doc, gafolo, koala, pepe, rdnzao |
|           60 |     1055 | 2024-06-14 | Fluxo             | L   | 0.861      | -            | -                | -                | -         |   -11.62 | doc, gafolo, koala, pepe, rdnzao |
|           59 |     1177 | 2024-06-10 | Vikings KR        | W   | 0.833      | -            | -                | -                | -         |     5.31 | doc, gafolo, koala, pepe, rdnzao |
|           58 |     1210 | 2024-06-09 | paiN              | L   | 0.827      | -            | -                | -                | -         |    -4.17 | doc, gafolo, koala, pepe, rdnzao |
|           57 |     1229 | 2024-06-09 | BESTIA            | W   | 0.826      | 0.450        | 0.095 (0.035)    | 0.801 (0.298)    | -         |    12.69 | doc, gafolo, koala, pepe, rdnzao |
|           56 |     1281 | 2024-06-08 | Hype              | W   | 0.821      | -            | -                | -                | -         |     8.71 | doc, gafolo, koala, pepe, rdnzao |
|           55 |     1296 | 2024-06-08 | Patins da Ferrari | L   | 0.820      | -            | -                | -                | -         |   -20.17 | doc, gafolo, koala, pepe, rdnzao |
|           54 |     1323 | 2024-06-07 | 9z                | L   | 0.815      | -            | -                | -                | -         |    -2.21 | doc, gafolo, koala, pepe, rdnzao |
|           53 |     1382 | 2024-06-06 | paiN              | W   | 0.809      | 0.450        | 0.327 (0.119)    | 0.867 (0.315)    | -         |    21.68 | doc, gafolo, koala, pepe, rdnzao |
|           52 |     1451 | 2024-06-05 | Imperial          | L   | 0.802      | -            | -                | -                | -         |    -4.91 | doc, gafolo, koala, pepe, rdnzao |
|           51 |     1501 | 2024-06-04 | BESTIA            | W   | 0.795      | 0.450        | 0.095 (0.034)    | 0.801 (0.287)    | -         |    14.05 | doc, gafolo, koala, pepe, rdnzao |
|           50 |     1828 | 2024-05-22 | Imperial          | W   | 0.708      | 0.450        | 0.236 (0.075)    | -                | -         |    17.99 | doc, drg, gafolo, pepe, rdnzao   |
|           49 |     1832 | 2024-05-22 | Imperial          | L   | 0.707      | -            | -                | -                | -         |    -4.17 | doc, drg, gafolo, pepe, rdnzao   |
|           48 |     1859 | 2024-05-21 | Case              | L   | 0.702      | -            | -                | -                | -         |   -13.61 | doc, drg, gafolo, pepe, rdnzao   |
|           47 |     1860 | 2024-05-21 | Case              | W   | 0.702      | 0.450        | -                | 0.805 (0.254)    | -         |     8.56 | doc, drg, gafolo, pepe, rdnzao   |
|           46 |     1864 | 2024-05-21 | RED Canids        | W   | 0.702      | 0.450        | 0.077 (0.024)    | 0.758 (0.239)    | -         |    15.42 | doc, drg, gafolo, pepe, rdnzao   |
|           45 |     1866 | 2024-05-21 | RED Canids        | L   | 0.702      | -            | -                | -                | -         |    -6.63 | doc, drg, gafolo, pepe, rdnzao   |
|           44 |     1997 | 2024-05-17 | ODDIK             | L   | 0.674      | -            | -                | -                | -         |   -12.47 | doc, drg, gafolo, rdnzao, togs   |
|           43 |     2022 | 2024-05-16 | W7M               | W   | 0.669      | -            | -                | -                | -         |     4.86 | doc, drg, gafolo, rdnzao, togs   |
|           42 |     2025 | 2024-05-16 | W7M               | W   | 0.668      | -            | -                | -                | -         |     5.07 | doc, drg, gafolo, rdnzao, togs   |
|           41 |     2030 | 2024-05-16 | Hype              | W   | 0.667      | -            | -                | -                | -         |     7.38 | doc, drg, gafolo, rdnzao, togs   |
|           40 |     2069 | 2024-05-15 | Vikings KR        | W   | 0.662      | -            | -                | -                | -         |     5.83 | doc, drg, gafolo, rdnzao, togs   |
|           39 |     2077 | 2024-05-15 | 9z                | L   | 0.661      | -            | -                | -                | -         |    -1.04 | doc, drg, gafolo, rdnzao, togs   |
|           38 |     2136 | 2024-05-14 | Fluxo             | L   | 0.654      | -            | -                | -                | -         |    -7.23 | doc, drg, gafolo, rdnzao, togs   |
|           37 |     2163 | 2024-05-13 | RED Canids        | W   | 0.648      | 0.384        | 0.077 (0.019)    | -                | -         |    13.26 | doc, drg, gafolo, rdnzao, togs   |
|           36 |     2170 | 2024-05-13 | W7M               | W   | 0.647      | -            | -                | -                | -         |     5.80 | doc, drg, gafolo, rdnzao, togs   |
|           35 |     2218 | 2024-05-11 | W7M               | W   | 0.634      | -            | -                | -                | -         |     5.96 | doc, drg, gafolo, rdnzao, togs   |
|           34 |     2262 | 2024-05-09 | BESTIA            | L   | 0.622      | -            | -                | -                | -         |   -10.80 | doc, drg, gafolo, rdnzao, togs   |
|           33 |     2282 | 2024-05-08 | 9z                | L   | 0.615      | -            | -                | -                | -         |    -0.90 | doc, drg, gafolo, rdnzao, togs   |
|           32 |     2320 | 2024-05-06 | BESTIA            | W   | 0.602      | 0.435        | 0.095 (0.025)    | -                | -         |     8.44 | doc, drg, gafolo, rdnzao, togs   |
|           31 |     2919 | 2024-04-11 | paiN              | L   | 0.435      | -            | -                | -                | -         |    -1.08 | doc, drg, gafolo, rdnzao, togs   |
|           30 |     3182 | 2024-04-03 | 2GAME             | W   | 0.382      | -            | -                | -                | -         |     1.87 | doc, drg, gafolo, rdnzao, togs   |
|           29 |     3185 | 2024-04-03 | 2GAME             | W   | 0.382      | -            | -                | -                | -         |     1.90 | doc, drg, gafolo, rdnzao, togs   |
|           28 |     3554 | 2024-03-14 | MIBR              | L   | 0.249      | -            | -                | -                | -         |    -0.65 | doc, drg, gafolo, rdnzao, togs   |
|           27 |     3556 | 2024-03-14 | MIBR              | L   | 0.249      | -            | -                | -                | -         |    -0.66 | doc, drg, gafolo, rdnzao, togs   |
|           26 |     3584 | 2024-03-13 | Yawara            | W   | 0.242      | -            | -                | -                | -         |     0.55 | doc, drg, gafolo, rdnzao, togs   |
|           25 |     3587 | 2024-03-13 | ODDIK             | W   | 0.242      | -            | -                | -                | -         |     4.04 | doc, drg, gafolo, rdnzao, togs   |
|           24 |     3660 | 2024-03-11 | Fluxo             | L   | 0.226      | -            | -                | -                | -         |    -2.84 | doc, drg, gafolo, rdnzao, togs   |
|           23 |     3688 | 2024-03-09 | Case              | L   | 0.215      | -            | -                | -                | -         |    -3.85 | doc, drg, gafolo, rdnzao, togs   |
|           22 |     3752 | 2024-03-07 | Corinthians       | W   | 0.200      | -            | -                | -                | -         |     0.42 | doc, drg, gafolo, rdnzao, togs   |
|           21 |     3806 | 2024-03-05 | Solid             | W   | 0.188      | -            | -                | -                | -         |     2.32 | doc, drg, gafolo, rdnzao, togs   |
|           20 |     3812 | 2024-03-05 | Solid             | W   | 0.187      | -            | -                | -                | -         |     2.35 | doc, drg, gafolo, rdnzao, togs   |
|           19 |     4006 | 2024-02-24 | Galorys           | W   | 0.122      | -            | -                | -                | -         |     1.51 | doc, drg, gafolo, rdnzao, togs   |
|           18 |     4014 | 2024-02-24 | Galorys           | W   | 0.122      | -            | -                | -                | -         |     1.52 | doc, drg, gafolo, rdnzao, togs   |
|           17 |     4018 | 2024-02-24 | Fluxo             | L   | 0.121      | -            | -                | -                | -         |    -1.52 | doc, drg, gafolo, rdnzao, togs   |
|           16 |     4071 | 2024-02-21 | Corinthians       | W   | 0.102      | -            | -                | -                | -         |     0.22 | doc, drg, gafolo, rdnzao, togs   |
|           15 |     4076 | 2024-02-21 | Case              | W   | 0.101      | -            | -                | -                | -         |     1.47 | doc, drg, gafolo, rdnzao, togs   |
|           14 |     4081 | 2024-02-21 | Galorys           | W   | 0.100      | -            | -                | -                | -         |     1.29 | doc, drg, gafolo, rdnzao, togs   |
|           13 |     4106 | 2024-02-20 | Flamengo          | L   | 0.095      | -            | -                | -                | -         |    -2.80 | doc, drg, gafolo, rdnzao, togs   |
|           12 |     4111 | 2024-02-20 | Case              | W   | 0.093      | -            | -                | -                | -         |     1.35 | doc, drg, gafolo, rdnzao, togs   |
|           11 |     4135 | 2024-02-19 | Solid             | W   | 0.087      | -            | -                | -                | -         |     1.11 | doc, drg, gafolo, rdnzao, togs   |
|           10 |     4149 | 2024-02-18 | Galorys           | W   | 0.082      | -            | -                | -                | -         |     1.07 | doc, drg, gafolo, rdnzao, togs   |
|            9 |     4172 | 2024-02-17 | W7M               | L   | 0.075      | -            | -                | -                | -         |    -1.60 | doc, drg, gafolo, rdnzao, togs   |
|            8 |     4177 | 2024-02-17 | Galorys           | L   | 0.074      | -            | -                | -                | -         |    -1.40 | doc, drg, gafolo, rdnzao, togs   |
|            7 |     4212 | 2024-02-16 | W7M               | W   | 0.067      | -            | -                | -                | -         |     0.69 | doc, drg, gafolo, rdnzao, togs   |
|            6 |     4230 | 2024-02-15 | Case              | L   | 0.062      | -            | -                | -                | -         |    -1.05 | doc, drg, gafolo, rdnzao, togs   |
|            5 |     4236 | 2024-02-15 | Fluxo             | L   | 0.061      | -            | -                | -                | -         |    -0.76 | doc, drg, gafolo, rdnzao, togs   |
|            4 |     4237 | 2024-02-15 | Fluxo             | L   | 0.060      | -            | -                | -                | -         |    -0.76 | doc, drg, gafolo, rdnzao, togs   |
|            3 |     4265 | 2024-02-14 | Hype              | W   | 0.056      | -            | -                | -                | -         |     0.07 | doc, drg, gafolo, rdnzao, togs   |
|            2 |     4276 | 2024-02-14 | Galorys           | W   | 0.054      | -            | -                | -                | -         |     0.69 | doc, drg, gafolo, rdnzao, togs   |
|            1 |     4320 | 2024-02-12 | Solid             | W   | 0.042      | -            | -                | -                | -         |     0.53 | doc, drg, gafolo, rdnzao, togs   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($9,857.31)
- Divide that value by the 5th highest value among all rosters ($324,118.06)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-02 |      1.000 | $750.00        | $750.00         |
| 2024-06-28 |      0.954 | $500.00        | $477.00         |
| 2024-06-16 |      0.874 | $2,500.00      | $2,185.19       |
| 2024-06-10 |      0.835 | $750.00        | $626.51         |
| 2024-06-09 |      0.828 | $5,000.00      | $4,140.74       |
| 2024-05-19 |      0.687 | $1,000.00      | $687.41         |
| 2024-02-25 |      0.128 | $5,000.00      | $639.81         |
| 2024-02-21 |      0.100 | $3,500.00      | $350.65         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
