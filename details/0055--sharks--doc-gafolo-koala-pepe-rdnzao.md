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
|           93 |       78 | 2024-08-02 | paiN              | L   | 1.000      | -            | -                | -                | -         |    -3.50 | doc, gafolo, koala, pepe, rdnzao |
|           92 |      108 | 2024-08-01 | Hype              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.06 | doc, gafolo, koala, pepe, rdnzao |
|           91 |      116 | 2024-08-01 | paiN              | L   | 1.000      | -            | -                | -                | -         |    -3.46 | doc, gafolo, koala, pepe, rdnzao |
|           90 |      149 | 2024-07-31 | MIBR              | L   | 1.000      | -            | -                | -                | -         |    -4.61 | doc, gafolo, koala, pepe, rdnzao |
|           89 |      159 | 2024-07-31 | Solid             | W   | 1.000      | 0.371        | -                | 0.836 (0.310)    | 0 (0.000) |    12.30 | doc, gafolo, koala, pepe, rdnzao |
|           88 |      193 | 2024-07-30 | Hype              | W   | 1.000      | -            | -                | -                | 0 (0.000) |    10.24 | doc, gafolo, koala, pepe, rdnzao |
|           87 |      266 | 2024-07-28 | Bad News Chickens | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.46 | doc, gafolo, koala, pepe, rdnzao |
|           86 |      314 | 2024-07-26 | Imperial          | L   | 1.000      | -            | -                | -                | -         |    -8.51 | doc, gafolo, koala, pepe, rdnzao |
|           85 |      341 | 2024-07-25 | BESTIA            | W   | 1.000      | -            | -                | -                | 0 (0.000) |    16.14 | doc, gafolo, koala, pepe, rdnzao |
|           84 |      348 | 2024-07-25 | Patins da Ferrari | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.21 | doc, gafolo, koala, pepe, rdnzao |
|           83 |      390 | 2024-07-24 | Bad News Chickens | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.41 | doc, gafolo, koala, pepe, rdnzao |
|           82 |      397 | 2024-07-24 | Yawara            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.00 | doc, gafolo, koala, pepe, rdnzao |
|           81 |      417 | 2024-07-23 | ODDIK             | L   | 1.000      | -            | -                | -                | -         |   -14.08 | doc, gafolo, koala, pepe, rdnzao |
|           80 |      420 | 2024-07-23 | W7M               | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.11 | doc, gafolo, koala, pepe, rdnzao |
|           79 |      506 | 2024-07-20 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |    -7.58 | doc, gafolo, koala, pepe, rdnzao |
|           78 |      559 | 2024-07-19 | Hype              | W   | 1.000      | -            | -                | -                | 0 (0.000) |    12.48 | doc, gafolo, koala, pepe, rdnzao |
|           77 |      584 | 2024-07-18 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |    -8.02 | doc, gafolo, koala, pepe, rdnzao |
|           76 |      586 | 2024-07-18 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |    -8.58 | doc, gafolo, koala, pepe, rdnzao |
|           75 |      649 | 2024-07-17 | ODDIK             | W   | 1.000      | 0.450        | 0.099 (0.044)    | 0.832 (0.374)    | -         |    17.41 | doc, gafolo, koala, pepe, rdnzao |
|           74 |      660 | 2024-07-17 | ODDIK             | W   | 1.000      | 0.450        | 0.099 (0.044)    | 0.832 (0.374)    | -         |    18.98 | doc, gafolo, koala, pepe, rdnzao |
|           73 |      714 | 2024-07-16 | RED Canids        | L   | 1.000      | -            | -                | -                | -         |    -7.81 | doc, gafolo, koala, pepe, rdnzao |
|           72 |      720 | 2024-07-16 | RED Canids        | L   | 1.000      | -            | -                | -                | -         |    -8.36 | doc, gafolo, koala, pepe, rdnzao |
|           71 |      764 | 2024-07-15 | KRÜ               | L   | 1.000      | -            | -                | -                | -         |   -20.61 | doc, gafolo, koala, pepe, rdnzao |
|           70 |      768 | 2024-07-15 | KRÜ               | W   | 1.000      | 0.450        | -                | 0.493 (0.222)    | -         |    10.50 | doc, gafolo, koala, pepe, rdnzao |
|           69 |      840 | 2024-07-11 | Bounty Hunters    | L   | 1.000      | -            | -                | -                | -         |   -16.70 | doc, gafolo, koala, pepe, rdnzao |
|           68 |      855 | 2024-07-10 | BESTIA            | W   | 1.000      | 0.371        | 0.095 (0.035)    | 0.801 (0.297)    | -         |    16.99 | doc, gafolo, koala, pepe, rdnzao |
|           67 |      875 | 2024-07-09 | KRÜ               | L   | 1.000      | -            | -                | -                | -         |   -21.11 | doc, gafolo, koala, pepe, rdnzao |
|           66 |      897 | 2024-07-08 | Patins da Ferrari | W   | 1.000      | -            | -                | -                | -         |     8.92 | doc, gafolo, koala, pepe, rdnzao |
|           65 |      933 | 2024-06-30 | Patins da Ferrari | L   | 0.968      | -            | -                | -                | -         |   -21.94 | doc, gafolo, koala, pepe, rdnzao |
|           64 |      947 | 2024-06-28 | KRÜ               | W   | 0.955      | -            | -                | -                | -         |     8.98 | doc, gafolo, koala, pepe, rdnzao |
|           63 |      948 | 2024-06-28 | Bounty Hunters    | L   | 0.954      | -            | -                | -                | -         |   -18.59 | doc, gafolo, koala, pepe, rdnzao |
|           62 |      952 | 2024-06-27 | Galorys           | W   | 0.948      | -            | -                | -                | -         |     8.63 | doc, gafolo, koala, pepe, rdnzao |
|           61 |      955 | 2024-06-27 | inSanitY          | L   | 0.947      | -            | -                | -                | -         |   -15.82 | doc, gafolo, koala, pepe, rdnzao |
|           60 |     1056 | 2024-06-14 | Fluxo             | L   | 0.861      | -            | -                | -                | -         |   -11.62 | doc, gafolo, koala, pepe, rdnzao |
|           59 |     1178 | 2024-06-10 | Vikings KR        | W   | 0.833      | -            | -                | -                | -         |     5.31 | doc, gafolo, koala, pepe, rdnzao |
|           58 |     1211 | 2024-06-09 | paiN              | L   | 0.827      | -            | -                | -                | -         |    -4.17 | doc, gafolo, koala, pepe, rdnzao |
|           57 |     1230 | 2024-06-09 | BESTIA            | W   | 0.826      | 0.450        | 0.095 (0.035)    | 0.801 (0.298)    | -         |    12.69 | doc, gafolo, koala, pepe, rdnzao |
|           56 |     1282 | 2024-06-08 | Hype              | W   | 0.820      | -            | -                | -                | -         |     8.71 | doc, gafolo, koala, pepe, rdnzao |
|           55 |     1297 | 2024-06-08 | Patins da Ferrari | L   | 0.819      | -            | -                | -                | -         |   -20.16 | doc, gafolo, koala, pepe, rdnzao |
|           54 |     1324 | 2024-06-07 | 9z                | L   | 0.815      | -            | -                | -                | -         |    -2.21 | doc, gafolo, koala, pepe, rdnzao |
|           53 |     1383 | 2024-06-06 | paiN              | W   | 0.808      | 0.450        | 0.327 (0.119)    | 0.867 (0.315)    | -         |    21.67 | doc, gafolo, koala, pepe, rdnzao |
|           52 |     1452 | 2024-06-05 | Imperial          | L   | 0.802      | -            | -                | -                | -         |    -4.91 | doc, gafolo, koala, pepe, rdnzao |
|           51 |     1502 | 2024-06-04 | BESTIA            | W   | 0.795      | 0.450        | 0.095 (0.034)    | 0.801 (0.287)    | -         |    14.04 | doc, gafolo, koala, pepe, rdnzao |
|           50 |     1829 | 2024-05-22 | Imperial          | W   | 0.707      | 0.450        | 0.236 (0.075)    | -                | -         |    17.98 | doc, drg, gafolo, pepe, rdnzao   |
|           49 |     1833 | 2024-05-22 | Imperial          | L   | 0.707      | -            | -                | -                | -         |    -4.17 | doc, drg, gafolo, pepe, rdnzao   |
|           48 |     1860 | 2024-05-21 | Case              | L   | 0.702      | -            | -                | -                | -         |   -13.60 | doc, drg, gafolo, pepe, rdnzao   |
|           47 |     1861 | 2024-05-21 | Case              | W   | 0.702      | 0.450        | -                | 0.805 (0.254)    | -         |     8.56 | doc, drg, gafolo, pepe, rdnzao   |
|           46 |     1865 | 2024-05-21 | RED Canids        | W   | 0.702      | 0.450        | 0.077 (0.024)    | 0.758 (0.239)    | -         |    15.41 | doc, drg, gafolo, pepe, rdnzao   |
|           45 |     1867 | 2024-05-21 | RED Canids        | L   | 0.701      | -            | -                | -                | -         |    -6.63 | doc, drg, gafolo, pepe, rdnzao   |
|           44 |     1998 | 2024-05-17 | ODDIK             | L   | 0.674      | -            | -                | -                | -         |   -12.46 | doc, drg, gafolo, rdnzao, togs   |
|           43 |     2023 | 2024-05-16 | W7M               | W   | 0.668      | -            | -                | -                | -         |     4.86 | doc, drg, gafolo, rdnzao, togs   |
|           42 |     2026 | 2024-05-16 | W7M               | W   | 0.668      | -            | -                | -                | -         |     5.07 | doc, drg, gafolo, rdnzao, togs   |
|           41 |     2031 | 2024-05-16 | Hype              | W   | 0.667      | -            | -                | -                | -         |     7.38 | doc, drg, gafolo, rdnzao, togs   |
|           40 |     2070 | 2024-05-15 | Vikings KR        | W   | 0.662      | -            | -                | -                | -         |     5.83 | doc, drg, gafolo, rdnzao, togs   |
|           39 |     2078 | 2024-05-15 | 9z                | L   | 0.661      | -            | -                | -                | -         |    -1.04 | doc, drg, gafolo, rdnzao, togs   |
|           38 |     2137 | 2024-05-14 | Fluxo             | L   | 0.654      | -            | -                | -                | -         |    -7.23 | doc, drg, gafolo, rdnzao, togs   |
|           37 |     2164 | 2024-05-13 | RED Canids        | W   | 0.648      | 0.384        | 0.077 (0.019)    | -                | -         |    13.25 | doc, drg, gafolo, rdnzao, togs   |
|           36 |     2171 | 2024-05-13 | W7M               | W   | 0.647      | -            | -                | -                | -         |     5.80 | doc, drg, gafolo, rdnzao, togs   |
|           35 |     2219 | 2024-05-11 | W7M               | W   | 0.634      | -            | -                | -                | -         |     5.96 | doc, drg, gafolo, rdnzao, togs   |
|           34 |     2263 | 2024-05-09 | BESTIA            | L   | 0.622      | -            | -                | -                | -         |   -10.80 | doc, drg, gafolo, rdnzao, togs   |
|           33 |     2283 | 2024-05-08 | 9z                | L   | 0.615      | -            | -                | -                | -         |    -0.90 | doc, drg, gafolo, rdnzao, togs   |
|           32 |     2321 | 2024-05-06 | BESTIA            | W   | 0.602      | 0.435        | 0.095 (0.025)    | -                | -         |     8.43 | doc, drg, gafolo, rdnzao, togs   |
|           31 |     2920 | 2024-04-11 | paiN              | L   | 0.434      | -            | -                | -                | -         |    -1.08 | doc, drg, gafolo, rdnzao, togs   |
|           30 |     3183 | 2024-04-03 | 2GAME             | W   | 0.382      | -            | -                | -                | -         |     1.87 | doc, drg, gafolo, rdnzao, togs   |
|           29 |     3186 | 2024-04-03 | 2GAME             | W   | 0.382      | -            | -                | -                | -         |     1.90 | doc, drg, gafolo, rdnzao, togs   |
|           28 |     3555 | 2024-03-14 | MIBR              | L   | 0.249      | -            | -                | -                | -         |    -0.65 | doc, drg, gafolo, rdnzao, togs   |
|           27 |     3557 | 2024-03-14 | MIBR              | L   | 0.249      | -            | -                | -                | -         |    -0.66 | doc, drg, gafolo, rdnzao, togs   |
|           26 |     3585 | 2024-03-13 | Yawara            | W   | 0.242      | -            | -                | -                | -         |     0.55 | doc, drg, gafolo, rdnzao, togs   |
|           25 |     3588 | 2024-03-13 | ODDIK             | W   | 0.241      | -            | -                | -                | -         |     4.03 | doc, drg, gafolo, rdnzao, togs   |
|           24 |     3661 | 2024-03-11 | Fluxo             | L   | 0.226      | -            | -                | -                | -         |    -2.83 | doc, drg, gafolo, rdnzao, togs   |
|           23 |     3689 | 2024-03-09 | Case              | L   | 0.214      | -            | -                | -                | -         |    -3.85 | doc, drg, gafolo, rdnzao, togs   |
|           22 |     3753 | 2024-03-07 | Corinthians       | W   | 0.199      | -            | -                | -                | -         |     0.42 | doc, drg, gafolo, rdnzao, togs   |
|           21 |     3807 | 2024-03-05 | Solid             | W   | 0.187      | -            | -                | -                | -         |     2.31 | doc, drg, gafolo, rdnzao, togs   |
|           20 |     3813 | 2024-03-05 | Solid             | W   | 0.187      | -            | -                | -                | -         |     2.35 | doc, drg, gafolo, rdnzao, togs   |
|           19 |     4007 | 2024-02-24 | Galorys           | W   | 0.122      | -            | -                | -                | -         |     1.50 | doc, drg, gafolo, rdnzao, togs   |
|           18 |     4015 | 2024-02-24 | Galorys           | W   | 0.122      | -            | -                | -                | -         |     1.51 | doc, drg, gafolo, rdnzao, togs   |
|           17 |     4019 | 2024-02-24 | Fluxo             | L   | 0.121      | -            | -                | -                | -         |    -1.52 | doc, drg, gafolo, rdnzao, togs   |
|           16 |     4072 | 2024-02-21 | Corinthians       | W   | 0.102      | -            | -                | -                | -         |     0.22 | doc, drg, gafolo, rdnzao, togs   |
|           15 |     4077 | 2024-02-21 | Case              | W   | 0.101      | -            | -                | -                | -         |     1.47 | doc, drg, gafolo, rdnzao, togs   |
|           14 |     4082 | 2024-02-21 | Galorys           | W   | 0.100      | -            | -                | -                | -         |     1.29 | doc, drg, gafolo, rdnzao, togs   |
|           13 |     4107 | 2024-02-20 | Flamengo          | L   | 0.095      | -            | -                | -                | -         |    -2.79 | doc, drg, gafolo, rdnzao, togs   |
|           12 |     4112 | 2024-02-20 | Case              | W   | 0.093      | -            | -                | -                | -         |     1.35 | doc, drg, gafolo, rdnzao, togs   |
|           11 |     4136 | 2024-02-19 | Solid             | W   | 0.087      | -            | -                | -                | -         |     1.10 | doc, drg, gafolo, rdnzao, togs   |
|           10 |     4150 | 2024-02-18 | Galorys           | W   | 0.082      | -            | -                | -                | -         |     1.06 | doc, drg, gafolo, rdnzao, togs   |
|            9 |     4173 | 2024-02-17 | W7M               | L   | 0.075      | -            | -                | -                | -         |    -1.59 | doc, drg, gafolo, rdnzao, togs   |
|            8 |     4178 | 2024-02-17 | Galorys           | L   | 0.074      | -            | -                | -                | -         |    -1.39 | doc, drg, gafolo, rdnzao, togs   |
|            7 |     4213 | 2024-02-16 | W7M               | W   | 0.067      | -            | -                | -                | -         |     0.69 | doc, drg, gafolo, rdnzao, togs   |
|            6 |     4231 | 2024-02-15 | Case              | L   | 0.061      | -            | -                | -                | -         |    -1.05 | doc, drg, gafolo, rdnzao, togs   |
|            5 |     4237 | 2024-02-15 | Fluxo             | L   | 0.060      | -            | -                | -                | -         |    -0.76 | doc, drg, gafolo, rdnzao, togs   |
|            4 |     4238 | 2024-02-15 | Fluxo             | L   | 0.060      | -            | -                | -                | -         |    -0.76 | doc, drg, gafolo, rdnzao, togs   |
|            3 |     4266 | 2024-02-14 | Hype              | W   | 0.055      | -            | -                | -                | -         |     0.07 | doc, drg, gafolo, rdnzao, togs   |
|            2 |     4277 | 2024-02-14 | Galorys           | W   | 0.053      | -            | -                | -                | -         |     0.68 | doc, drg, gafolo, rdnzao, togs   |
|            1 |     4321 | 2024-02-12 | Solid             | W   | 0.042      | -            | -                | -                | -         |     0.53 | doc, drg, gafolo, rdnzao, togs   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($9,851.82)
- Divide that value by the 5th highest value among all rosters ($324,028.83)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-02 |      1.000 | $750.00        | $750.00         |
| 2024-06-28 |      0.954 | $500.00        | $476.85         |
| 2024-06-16 |      0.874 | $2,500.00      | $2,184.43       |
| 2024-06-10 |      0.835 | $750.00        | $626.28         |
| 2024-06-09 |      0.828 | $5,000.00      | $4,139.24       |
| 2024-05-19 |      0.687 | $1,000.00      | $687.11         |
| 2024-02-25 |      0.128 | $5,000.00      | $638.31         |
| 2024-02-21 |      0.100 | $3,500.00      | $349.59         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
