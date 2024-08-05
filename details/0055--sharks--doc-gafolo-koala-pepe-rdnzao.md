### Roster Details<br />
Team Name: Sharks<br />
Roster: doc, gafolo, koala, pepe, rdnzao<br />
Global Rank: [55](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [14]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1024.4<br />
<br />
Final Rank Value (1024.4) = Starting Rank Value (973.1) + Head To Head Adjustments (51.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.397[<sup>1</sup>](#table2)
- Bounty Collected: 0.427[<sup>2</sup>](#table1)
- Opponent Network: 0.296[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.280<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 973.1
- 400 + ( ( 0.280 - 0.000 ) / ( 0.781 - 0.000 ) ) * 1600 = 973.1


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
|           93 |       95 | 2024-08-02 | paiN              | L   | 1.000      | -            | -                | -                | -         |    -3.51 | doc, gafolo, koala, pepe, rdnzao |
|           92 |      125 | 2024-08-01 | Hype              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.07 | doc, gafolo, koala, pepe, rdnzao |
|           91 |      133 | 2024-08-01 | paiN              | L   | 1.000      | -            | -                | -                | -         |    -3.47 | doc, gafolo, koala, pepe, rdnzao |
|           90 |      166 | 2024-07-31 | MIBR              | L   | 1.000      | -            | -                | -                | -         |    -4.62 | doc, gafolo, koala, pepe, rdnzao |
|           89 |      176 | 2024-07-31 | Solid             | W   | 1.000      | 0.371        | -                | 0.835 (0.309)    | 0 (0.000) |    12.31 | doc, gafolo, koala, pepe, rdnzao |
|           88 |      210 | 2024-07-30 | Hype              | W   | 1.000      | -            | -                | -                | 0 (0.000) |    10.26 | doc, gafolo, koala, pepe, rdnzao |
|           87 |      283 | 2024-07-28 | Bad News Chickens | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.47 | doc, gafolo, koala, pepe, rdnzao |
|           86 |      331 | 2024-07-26 | Imperial          | L   | 1.000      | -            | -                | -                | -         |    -8.55 | doc, gafolo, koala, pepe, rdnzao |
|           85 |      358 | 2024-07-25 | BESTIA            | W   | 1.000      | -            | -                | -                | 0 (0.000) |    16.14 | doc, gafolo, koala, pepe, rdnzao |
|           84 |      365 | 2024-07-25 | Patins da Ferrari | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.21 | doc, gafolo, koala, pepe, rdnzao |
|           83 |      407 | 2024-07-24 | Bad News Chickens | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.42 | doc, gafolo, koala, pepe, rdnzao |
|           82 |      414 | 2024-07-24 | Yawara            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.00 | doc, gafolo, koala, pepe, rdnzao |
|           81 |      434 | 2024-07-23 | ODDIK             | L   | 1.000      | -            | -                | -                | -         |   -14.07 | doc, gafolo, koala, pepe, rdnzao |
|           80 |      437 | 2024-07-23 | W7M               | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.14 | doc, gafolo, koala, pepe, rdnzao |
|           79 |      523 | 2024-07-20 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |    -7.59 | doc, gafolo, koala, pepe, rdnzao |
|           78 |      576 | 2024-07-19 | Hype              | W   | 1.000      | -            | -                | -                | 0 (0.000) |    12.51 | doc, gafolo, koala, pepe, rdnzao |
|           77 |      601 | 2024-07-18 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |    -8.03 | doc, gafolo, koala, pepe, rdnzao |
|           76 |      603 | 2024-07-18 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |    -8.60 | doc, gafolo, koala, pepe, rdnzao |
|           75 |      666 | 2024-07-17 | ODDIK             | W   | 1.000      | 0.450        | 0.099 (0.044)    | 0.832 (0.374)    | -         |    17.42 | doc, gafolo, koala, pepe, rdnzao |
|           74 |      677 | 2024-07-17 | ODDIK             | W   | 1.000      | 0.450        | 0.099 (0.044)    | 0.832 (0.374)    | -         |    18.99 | doc, gafolo, koala, pepe, rdnzao |
|           73 |      731 | 2024-07-16 | RED Canids        | L   | 1.000      | -            | -                | -                | -         |    -7.84 | doc, gafolo, koala, pepe, rdnzao |
|           72 |      737 | 2024-07-16 | RED Canids        | L   | 1.000      | -            | -                | -                | -         |    -8.38 | doc, gafolo, koala, pepe, rdnzao |
|           71 |      781 | 2024-07-15 | KRÜ               | L   | 1.000      | -            | -                | -                | -         |   -20.59 | doc, gafolo, koala, pepe, rdnzao |
|           70 |      785 | 2024-07-15 | KRÜ               | W   | 1.000      | 0.450        | -                | 0.493 (0.222)    | -         |    10.52 | doc, gafolo, koala, pepe, rdnzao |
|           69 |      857 | 2024-07-11 | Bounty Hunters    | L   | 1.000      | -            | -                | -                | -         |   -16.70 | doc, gafolo, koala, pepe, rdnzao |
|           68 |      872 | 2024-07-10 | BESTIA            | W   | 1.000      | 0.371        | 0.096 (0.035)    | 0.801 (0.297)    | -         |    16.99 | doc, gafolo, koala, pepe, rdnzao |
|           67 |      892 | 2024-07-09 | KRÜ               | L   | 1.000      | -            | -                | -                | -         |   -21.09 | doc, gafolo, koala, pepe, rdnzao |
|           66 |      914 | 2024-07-08 | Patins da Ferrari | W   | 1.000      | -            | -                | -                | -         |     8.93 | doc, gafolo, koala, pepe, rdnzao |
|           65 |      950 | 2024-06-30 | Patins da Ferrari | L   | 0.962      | -            | -                | -                | -         |   -21.80 | doc, gafolo, koala, pepe, rdnzao |
|           64 |      964 | 2024-06-28 | KRÜ               | W   | 0.949      | -            | -                | -                | -         |     8.96 | doc, gafolo, koala, pepe, rdnzao |
|           63 |      965 | 2024-06-28 | Bounty Hunters    | L   | 0.948      | -            | -                | -                | -         |   -18.46 | doc, gafolo, koala, pepe, rdnzao |
|           62 |      969 | 2024-06-27 | Galorys           | W   | 0.943      | -            | -                | -                | -         |     8.61 | doc, gafolo, koala, pepe, rdnzao |
|           61 |      972 | 2024-06-27 | inSanitY          | L   | 0.941      | -            | -                | -                | -         |   -15.73 | doc, gafolo, koala, pepe, rdnzao |
|           60 |     1073 | 2024-06-14 | Fluxo             | L   | 0.855      | -            | -                | -                | -         |   -11.54 | doc, gafolo, koala, pepe, rdnzao |
|           59 |     1195 | 2024-06-10 | Vikings KR        | W   | 0.827      | -            | -                | -                | -         |     5.30 | doc, gafolo, koala, pepe, rdnzao |
|           58 |     1228 | 2024-06-09 | paiN              | L   | 0.821      | -            | -                | -                | -         |    -4.15 | doc, gafolo, koala, pepe, rdnzao |
|           57 |     1247 | 2024-06-09 | BESTIA            | W   | 0.820      | 0.450        | 0.096 (0.035)    | 0.801 (0.296)    | -         |    12.62 | doc, gafolo, koala, pepe, rdnzao |
|           56 |     1299 | 2024-06-08 | Hype              | W   | 0.815      | -            | -                | -                | -         |     8.68 | doc, gafolo, koala, pepe, rdnzao |
|           55 |     1314 | 2024-06-08 | Patins da Ferrari | L   | 0.814      | -            | -                | -                | -         |   -20.00 | doc, gafolo, koala, pepe, rdnzao |
|           54 |     1341 | 2024-06-07 | 9z                | L   | 0.809      | -            | -                | -                | -         |    -2.19 | doc, gafolo, koala, pepe, rdnzao |
|           53 |     1400 | 2024-06-06 | paiN              | W   | 0.802      | 0.450        | 0.325 (0.118)    | 0.867 (0.313)    | -         |    21.50 | doc, gafolo, koala, pepe, rdnzao |
|           52 |     1469 | 2024-06-05 | Imperial          | L   | 0.796      | -            | -                | -                | -         |    -4.91 | doc, gafolo, koala, pepe, rdnzao |
|           51 |     1519 | 2024-06-04 | BESTIA            | W   | 0.789      | 0.450        | 0.096 (0.034)    | 0.801 (0.285)    | -         |    13.94 | doc, gafolo, koala, pepe, rdnzao |
|           50 |     1846 | 2024-05-22 | Imperial          | W   | 0.702      | 0.450        | 0.235 (0.074)    | -                | -         |    17.80 | doc, drg, gafolo, pepe, rdnzao   |
|           49 |     1850 | 2024-05-22 | Imperial          | L   | 0.701      | -            | -                | -                | -         |    -4.17 | doc, drg, gafolo, pepe, rdnzao   |
|           48 |     1877 | 2024-05-21 | Case              | L   | 0.696      | -            | -                | -                | -         |   -13.48 | doc, drg, gafolo, pepe, rdnzao   |
|           47 |     1878 | 2024-05-21 | Case              | W   | 0.696      | 0.450        | -                | 0.805 (0.252)    | -         |     8.51 | doc, drg, gafolo, pepe, rdnzao   |
|           46 |     1882 | 2024-05-21 | RED Canids        | W   | 0.696      | 0.450        | 0.077 (0.024)    | 0.757 (0.237)    | -         |    15.26 | doc, drg, gafolo, pepe, rdnzao   |
|           45 |     1884 | 2024-05-21 | RED Canids        | L   | 0.696      | -            | -                | -                | -         |    -6.60 | doc, drg, gafolo, pepe, rdnzao   |
|           44 |     2015 | 2024-05-17 | ODDIK             | L   | 0.668      | -            | -                | -                | -         |   -12.34 | doc, drg, gafolo, rdnzao, togs   |
|           43 |     2040 | 2024-05-16 | W7M               | W   | 0.663      | -            | -                | -                | -         |     4.84 | doc, drg, gafolo, rdnzao, togs   |
|           42 |     2043 | 2024-05-16 | W7M               | W   | 0.662      | -            | -                | -                | -         |     5.05 | doc, drg, gafolo, rdnzao, togs   |
|           41 |     2048 | 2024-05-16 | Hype              | W   | 0.661      | -            | -                | -                | -         |     7.34 | doc, drg, gafolo, rdnzao, togs   |
|           40 |     2087 | 2024-05-15 | Vikings KR        | W   | 0.656      | -            | -                | -                | -         |     5.79 | doc, drg, gafolo, rdnzao, togs   |
|           39 |     2095 | 2024-05-15 | 9z                | L   | 0.655      | -            | -                | -                | -         |    -1.04 | doc, drg, gafolo, rdnzao, togs   |
|           38 |     2154 | 2024-05-14 | Fluxo             | L   | 0.648      | -            | -                | -                | -         |    -7.18 | doc, drg, gafolo, rdnzao, togs   |
|           37 |     2181 | 2024-05-13 | RED Canids        | W   | 0.642      | 0.384        | 0.077 (0.019)    | -                | -         |    13.12 | doc, drg, gafolo, rdnzao, togs   |
|           36 |     2188 | 2024-05-13 | W7M               | W   | 0.641      | -            | -                | -                | -         |     5.76 | doc, drg, gafolo, rdnzao, togs   |
|           35 |     2236 | 2024-05-11 | W7M               | W   | 0.628      | -            | -                | -                | -         |     5.92 | doc, drg, gafolo, rdnzao, togs   |
|           34 |     2280 | 2024-05-09 | BESTIA            | L   | 0.616      | -            | -                | -                | -         |   -10.67 | doc, drg, gafolo, rdnzao, togs   |
|           33 |     2300 | 2024-05-08 | 9z                | L   | 0.609      | -            | -                | -                | -         |    -0.89 | doc, drg, gafolo, rdnzao, togs   |
|           32 |     2338 | 2024-05-06 | BESTIA            | W   | 0.596      | 0.435        | 0.096 (0.025)    | -                | -         |     8.38 | doc, drg, gafolo, rdnzao, togs   |
|           31 |     2937 | 2024-04-11 | paiN              | L   | 0.429      | -            | -                | -                | -         |    -1.08 | doc, drg, gafolo, rdnzao, togs   |
|           30 |     3200 | 2024-04-03 | 2GAME             | W   | 0.376      | -            | -                | -                | -         |     1.84 | doc, drg, gafolo, rdnzao, togs   |
|           29 |     3203 | 2024-04-03 | 2GAME             | W   | 0.376      | -            | -                | -                | -         |     1.87 | doc, drg, gafolo, rdnzao, togs   |
|           28 |     3572 | 2024-03-14 | MIBR              | L   | 0.243      | -            | -                | -                | -         |    -0.64 | doc, drg, gafolo, rdnzao, togs   |
|           27 |     3574 | 2024-03-14 | MIBR              | L   | 0.243      | -            | -                | -                | -         |    -0.64 | doc, drg, gafolo, rdnzao, togs   |
|           26 |     3602 | 2024-03-13 | Yawara            | W   | 0.236      | -            | -                | -                | -         |     0.54 | doc, drg, gafolo, rdnzao, togs   |
|           25 |     3605 | 2024-03-13 | ODDIK             | W   | 0.236      | -            | -                | -                | -         |     3.93 | doc, drg, gafolo, rdnzao, togs   |
|           24 |     3678 | 2024-03-11 | Fluxo             | L   | 0.220      | -            | -                | -                | -         |    -2.76 | doc, drg, gafolo, rdnzao, togs   |
|           23 |     3706 | 2024-03-09 | Case              | L   | 0.209      | -            | -                | -                | -         |    -3.74 | doc, drg, gafolo, rdnzao, togs   |
|           22 |     3770 | 2024-03-07 | Corinthians       | W   | 0.194      | -            | -                | -                | -         |     0.41 | doc, drg, gafolo, rdnzao, togs   |
|           21 |     3824 | 2024-03-05 | Solid             | W   | 0.182      | -            | -                | -                | -         |     2.25 | doc, drg, gafolo, rdnzao, togs   |
|           20 |     3830 | 2024-03-05 | Solid             | W   | 0.181      | -            | -                | -                | -         |     2.28 | doc, drg, gafolo, rdnzao, togs   |
|           19 |     4024 | 2024-02-24 | Galorys           | W   | 0.116      | -            | -                | -                | -         |     1.44 | doc, drg, gafolo, rdnzao, togs   |
|           18 |     4032 | 2024-02-24 | Galorys           | W   | 0.116      | -            | -                | -                | -         |     1.45 | doc, drg, gafolo, rdnzao, togs   |
|           17 |     4036 | 2024-02-24 | Fluxo             | L   | 0.115      | -            | -                | -                | -         |    -1.44 | doc, drg, gafolo, rdnzao, togs   |
|           16 |     4089 | 2024-02-21 | Corinthians       | W   | 0.096      | -            | -                | -                | -         |     0.21 | doc, drg, gafolo, rdnzao, togs   |
|           15 |     4094 | 2024-02-21 | Case              | W   | 0.095      | -            | -                | -                | -         |     1.38 | doc, drg, gafolo, rdnzao, togs   |
|           14 |     4099 | 2024-02-21 | Galorys           | W   | 0.094      | -            | -                | -                | -         |     1.21 | doc, drg, gafolo, rdnzao, togs   |
|           13 |     4124 | 2024-02-20 | Flamengo          | L   | 0.089      | -            | -                | -                | -         |    -2.62 | doc, drg, gafolo, rdnzao, togs   |
|           12 |     4129 | 2024-02-20 | Case              | W   | 0.087      | -            | -                | -                | -         |     1.26 | doc, drg, gafolo, rdnzao, togs   |
|           11 |     4153 | 2024-02-19 | Solid             | W   | 0.081      | -            | -                | -                | -         |     1.03 | doc, drg, gafolo, rdnzao, togs   |
|           10 |     4167 | 2024-02-18 | Galorys           | W   | 0.076      | -            | -                | -                | -         |     0.99 | doc, drg, gafolo, rdnzao, togs   |
|            9 |     4190 | 2024-02-17 | W7M               | L   | 0.069      | -            | -                | -                | -         |    -1.47 | doc, drg, gafolo, rdnzao, togs   |
|            8 |     4195 | 2024-02-17 | Galorys           | L   | 0.068      | -            | -                | -                | -         |    -1.28 | doc, drg, gafolo, rdnzao, togs   |
|            7 |     4230 | 2024-02-16 | W7M               | W   | 0.061      | -            | -                | -                | -         |     0.63 | doc, drg, gafolo, rdnzao, togs   |
|            6 |     4248 | 2024-02-15 | Case              | L   | 0.056      | -            | -                | -                | -         |    -0.95 | doc, drg, gafolo, rdnzao, togs   |
|            5 |     4254 | 2024-02-15 | Fluxo             | L   | 0.055      | -            | -                | -                | -         |    -0.69 | doc, drg, gafolo, rdnzao, togs   |
|            4 |     4255 | 2024-02-15 | Fluxo             | L   | 0.054      | -            | -                | -                | -         |    -0.69 | doc, drg, gafolo, rdnzao, togs   |
|            3 |     4283 | 2024-02-14 | Hype              | W   | 0.050      | -            | -                | -                | -         |     0.06 | doc, drg, gafolo, rdnzao, togs   |
|            2 |     4294 | 2024-02-14 | Galorys           | W   | 0.048      | -            | -                | -                | -         |     0.61 | doc, drg, gafolo, rdnzao, togs   |
|            1 |     4338 | 2024-02-12 | Solid             | W   | 0.036      | -            | -                | -                | -         |     0.45 | doc, drg, gafolo, rdnzao, togs   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($9,747.47)
- Divide that value by the 5th highest value among all rosters ($322,333.56)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-02 |      1.000 | $750.00        | $750.00         |
| 2024-06-28 |      0.948 | $500.00        | $473.99         |
| 2024-06-16 |      0.868 | $2,500.00      | $2,170.14       |
| 2024-06-10 |      0.829 | $750.00        | $622.00         |
| 2024-06-09 |      0.822 | $5,000.00      | $4,110.65       |
| 2024-05-19 |      0.681 | $1,000.00      | $681.39         |
| 2024-02-25 |      0.122 | $5,000.00      | $609.72         |
| 2024-02-21 |      0.094 | $3,500.00      | $329.58         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
