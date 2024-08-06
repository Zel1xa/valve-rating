### Roster Details<br />
Team Name: Sharks<br />
Roster: doc, gafolo, koala, pepe, rdnzao<br />
Global Rank: [56](../standings_global.md)<br />
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
|           93 |      129 | 2024-08-02 | paiN              | L   | 1.000      | -            | -                | -                | -         |    -3.52 | doc, gafolo, koala, pepe, rdnzao |
|           92 |      159 | 2024-08-01 | Hype              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.10 | doc, gafolo, koala, pepe, rdnzao |
|           91 |      167 | 2024-08-01 | paiN              | L   | 1.000      | -            | -                | -                | -         |    -3.49 | doc, gafolo, koala, pepe, rdnzao |
|           90 |      200 | 2024-07-31 | MIBR              | L   | 1.000      | -            | -                | -                | -         |    -4.63 | doc, gafolo, koala, pepe, rdnzao |
|           89 |      210 | 2024-07-31 | Solid             | W   | 1.000      | 0.371        | -                | 0.807 (0.299)    | 0 (0.000) |    12.34 | doc, gafolo, koala, pepe, rdnzao |
|           88 |      244 | 2024-07-30 | Hype              | W   | 1.000      | -            | -                | -                | 0 (0.000) |    10.29 | doc, gafolo, koala, pepe, rdnzao |
|           87 |      317 | 2024-07-28 | Bad News Chickens | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.51 | doc, gafolo, koala, pepe, rdnzao |
|           86 |      365 | 2024-07-26 | Imperial          | L   | 1.000      | -            | -                | -                | -         |    -8.58 | doc, gafolo, koala, pepe, rdnzao |
|           85 |      392 | 2024-07-25 | BESTIA            | W   | 1.000      | -            | -                | -                | 0 (0.000) |    16.14 | doc, gafolo, koala, pepe, rdnzao |
|           84 |      399 | 2024-07-25 | Patins da Ferrari | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.26 | doc, gafolo, koala, pepe, rdnzao |
|           83 |      441 | 2024-07-24 | Bad News Chickens | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.46 | doc, gafolo, koala, pepe, rdnzao |
|           82 |      448 | 2024-07-24 | Yawara            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.04 | doc, gafolo, koala, pepe, rdnzao |
|           81 |      468 | 2024-07-23 | ODDIK             | L   | 1.000      | -            | -                | -                | -         |   -14.05 | doc, gafolo, koala, pepe, rdnzao |
|           80 |      471 | 2024-07-23 | W7M               | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.18 | doc, gafolo, koala, pepe, rdnzao |
|           79 |      557 | 2024-07-20 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |    -7.61 | doc, gafolo, koala, pepe, rdnzao |
|           78 |      610 | 2024-07-19 | Hype              | W   | 1.000      | -            | -                | -                | 0 (0.000) |    12.55 | doc, gafolo, koala, pepe, rdnzao |
|           77 |      635 | 2024-07-18 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |    -8.05 | doc, gafolo, koala, pepe, rdnzao |
|           76 |      637 | 2024-07-18 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |    -8.63 | doc, gafolo, koala, pepe, rdnzao |
|           75 |      700 | 2024-07-17 | ODDIK             | W   | 1.000      | 0.450        | 0.099 (0.045)    | 0.805 (0.362)    | -         |    17.45 | doc, gafolo, koala, pepe, rdnzao |
|           74 |      711 | 2024-07-17 | ODDIK             | W   | 1.000      | 0.450        | 0.099 (0.045)    | 0.805 (0.362)    | -         |    19.02 | doc, gafolo, koala, pepe, rdnzao |
|           73 |      765 | 2024-07-16 | RED Canids        | L   | 1.000      | -            | -                | -                | -         |    -7.85 | doc, gafolo, koala, pepe, rdnzao |
|           72 |      771 | 2024-07-16 | RED Canids        | L   | 1.000      | -            | -                | -                | -         |    -8.40 | doc, gafolo, koala, pepe, rdnzao |
|           71 |      815 | 2024-07-15 | KRÜ               | L   | 1.000      | -            | -                | -                | -         |   -20.57 | doc, gafolo, koala, pepe, rdnzao |
|           70 |      819 | 2024-07-15 | KRÜ               | W   | 1.000      | 0.450        | -                | 0.479 (0.216)    | -         |    10.55 | doc, gafolo, koala, pepe, rdnzao |
|           69 |      891 | 2024-07-11 | Bounty Hunters    | L   | 1.000      | -            | -                | -                | -         |   -16.69 | doc, gafolo, koala, pepe, rdnzao |
|           68 |      906 | 2024-07-10 | BESTIA            | W   | 1.000      | 0.371        | 0.096 (0.036)    | 0.776 (0.288)    | -         |    17.00 | doc, gafolo, koala, pepe, rdnzao |
|           67 |      926 | 2024-07-09 | KRÜ               | L   | 1.000      | -            | -                | -                | -         |   -21.05 | doc, gafolo, koala, pepe, rdnzao |
|           66 |      948 | 2024-07-08 | Patins da Ferrari | W   | 1.000      | -            | -                | -                | -         |     8.99 | doc, gafolo, koala, pepe, rdnzao |
|           65 |      984 | 2024-06-30 | Patins da Ferrari | L   | 0.954      | -            | -                | -                | -         |   -21.57 | doc, gafolo, koala, pepe, rdnzao |
|           64 |      998 | 2024-06-28 | KRÜ               | W   | 0.941      | -            | -                | -                | -         |     8.92 | doc, gafolo, koala, pepe, rdnzao |
|           63 |      999 | 2024-06-28 | Bounty Hunters    | L   | 0.940      | -            | -                | -                | -         |   -18.29 | doc, gafolo, koala, pepe, rdnzao |
|           62 |     1003 | 2024-06-27 | Galorys           | W   | 0.935      | -            | -                | -                | -         |     8.60 | doc, gafolo, koala, pepe, rdnzao |
|           61 |     1006 | 2024-06-27 | inSanitY          | L   | 0.933      | -            | -                | -                | -         |   -15.59 | doc, gafolo, koala, pepe, rdnzao |
|           60 |     1107 | 2024-06-14 | Fluxo             | L   | 0.848      | -            | -                | -                | -         |   -11.44 | doc, gafolo, koala, pepe, rdnzao |
|           59 |     1229 | 2024-06-10 | Vikings KR        | W   | 0.820      | -            | -                | -                | -         |     5.30 | doc, gafolo, koala, pepe, rdnzao |
|           58 |     1262 | 2024-06-09 | paiN              | L   | 0.814      | -            | -                | -                | -         |    -4.12 | doc, gafolo, koala, pepe, rdnzao |
|           57 |     1281 | 2024-06-09 | BESTIA            | W   | 0.813      | 0.450        | 0.096 (0.035)    | 0.776 (0.284)    | -         |    12.54 | doc, gafolo, koala, pepe, rdnzao |
|           56 |     1333 | 2024-06-08 | Hype              | W   | 0.807      | -            | -                | -                | -         |     8.66 | doc, gafolo, koala, pepe, rdnzao |
|           55 |     1348 | 2024-06-08 | Patins da Ferrari | L   | 0.806      | -            | -                | -                | -         |   -19.75 | doc, gafolo, koala, pepe, rdnzao |
|           54 |     1375 | 2024-06-07 | 9z                | L   | 0.802      | -            | -                | -                | -         |    -2.15 | doc, gafolo, koala, pepe, rdnzao |
|           53 |     1434 | 2024-06-06 | paiN              | W   | 0.795      | 0.450        | 0.324 (0.116)    | 0.839 (0.300)    | -         |    21.29 | doc, gafolo, koala, pepe, rdnzao |
|           52 |     1503 | 2024-06-05 | Imperial          | L   | 0.788      | -            | -                | -                | -         |    -4.88 | doc, gafolo, koala, pepe, rdnzao |
|           51 |     1553 | 2024-06-04 | BESTIA            | W   | 0.782      | 0.450        | 0.096 (0.034)    | 0.776 (0.273)    | -         |    13.83 | doc, gafolo, koala, pepe, rdnzao |
|           50 |     1880 | 2024-05-22 | Imperial          | W   | 0.694      | 0.450        | 0.233 (0.073)    | -                | -         |    17.59 | doc, drg, gafolo, pepe, rdnzao   |
|           49 |     1884 | 2024-05-22 | Imperial          | L   | 0.694      | -            | -                | -                | -         |    -4.15 | doc, drg, gafolo, pepe, rdnzao   |
|           48 |     1911 | 2024-05-21 | Case              | L   | 0.689      | -            | -                | -                | -         |   -13.30 | doc, drg, gafolo, pepe, rdnzao   |
|           47 |     1912 | 2024-05-21 | Case              | W   | 0.689      | 0.450        | -                | 0.778 (0.241)    | -         |     8.45 | doc, drg, gafolo, pepe, rdnzao   |
|           46 |     1916 | 2024-05-21 | RED Canids        | W   | 0.688      | 0.450        | 0.076 (0.024)    | 0.732 (0.227)    | -         |    15.09 | doc, drg, gafolo, pepe, rdnzao   |
|           45 |     1918 | 2024-05-21 | RED Canids        | L   | 0.688      | -            | -                | -                | -         |    -6.55 | doc, drg, gafolo, pepe, rdnzao   |
|           44 |     2049 | 2024-05-17 | ODDIK             | L   | 0.660      | -            | -                | -                | -         |   -12.16 | doc, drg, gafolo, rdnzao, togs   |
|           43 |     2074 | 2024-05-16 | W7M               | W   | 0.655      | -            | -                | -                | -         |     4.83 | doc, drg, gafolo, rdnzao, togs   |
|           42 |     2077 | 2024-05-16 | W7M               | W   | 0.655      | -            | -                | -                | -         |     5.03 | doc, drg, gafolo, rdnzao, togs   |
|           41 |     2082 | 2024-05-16 | Hype              | W   | 0.654      | -            | -                | -                | -         |     7.30 | doc, drg, gafolo, rdnzao, togs   |
|           40 |     2121 | 2024-05-15 | Vikings KR        | W   | 0.649      | -            | -                | -                | -         |     5.77 | doc, drg, gafolo, rdnzao, togs   |
|           39 |     2129 | 2024-05-15 | 9z                | L   | 0.648      | -            | -                | -                | -         |    -1.02 | doc, drg, gafolo, rdnzao, togs   |
|           38 |     2188 | 2024-05-14 | Fluxo             | L   | 0.641      | -            | -                | -                | -         |    -7.11 | doc, drg, gafolo, rdnzao, togs   |
|           37 |     2215 | 2024-05-13 | RED Canids        | W   | 0.635      | 0.384        | 0.076 (0.019)    | -                | -         |    12.96 | doc, drg, gafolo, rdnzao, togs   |
|           36 |     2222 | 2024-05-13 | W7M               | W   | 0.633      | -            | -                | -                | -         |     5.74 | doc, drg, gafolo, rdnzao, togs   |
|           35 |     2270 | 2024-05-11 | W7M               | W   | 0.620      | -            | -                | -                | -         |     5.88 | doc, drg, gafolo, rdnzao, togs   |
|           34 |     2314 | 2024-05-09 | BESTIA            | L   | 0.608      | -            | -                | -                | -         |   -10.49 | doc, drg, gafolo, rdnzao, togs   |
|           33 |     2334 | 2024-05-08 | 9z                | L   | 0.602      | -            | -                | -                | -         |    -0.87 | doc, drg, gafolo, rdnzao, togs   |
|           32 |     2372 | 2024-05-06 | BESTIA            | W   | 0.588      | 0.435        | 0.096 (0.025)    | -                | -         |     8.33 | doc, drg, gafolo, rdnzao, togs   |
|           31 |     2971 | 2024-04-11 | paiN              | L   | 0.421      | -            | -                | -                | -         |    -1.07 | doc, drg, gafolo, rdnzao, togs   |
|           30 |     3234 | 2024-04-03 | 2GAME             | W   | 0.368      | -            | -                | -                | -         |     1.82 | doc, drg, gafolo, rdnzao, togs   |
|           29 |     3237 | 2024-04-03 | 2GAME             | W   | 0.368      | -            | -                | -                | -         |     1.86 | doc, drg, gafolo, rdnzao, togs   |
|           28 |     3606 | 2024-03-14 | MIBR              | L   | 0.236      | -            | -                | -                | -         |    -0.62 | doc, drg, gafolo, rdnzao, togs   |
|           27 |     3608 | 2024-03-14 | MIBR              | L   | 0.235      | -            | -                | -                | -         |    -0.63 | doc, drg, gafolo, rdnzao, togs   |
|           26 |     3636 | 2024-03-13 | Yawara            | W   | 0.228      | -            | -                | -                | -         |     0.53 | doc, drg, gafolo, rdnzao, togs   |
|           25 |     3639 | 2024-03-13 | ODDIK             | W   | 0.228      | -            | -                | -                | -         |     3.81 | doc, drg, gafolo, rdnzao, togs   |
|           24 |     3712 | 2024-03-11 | Fluxo             | L   | 0.213      | -            | -                | -                | -         |    -2.67 | doc, drg, gafolo, rdnzao, togs   |
|           23 |     3740 | 2024-03-09 | Case              | L   | 0.201      | -            | -                | -                | -         |    -3.59 | doc, drg, gafolo, rdnzao, togs   |
|           22 |     3804 | 2024-03-07 | Corinthians       | W   | 0.186      | -            | -                | -                | -         |     0.40 | doc, drg, gafolo, rdnzao, togs   |
|           21 |     3858 | 2024-03-05 | Solid             | W   | 0.174      | -            | -                | -                | -         |     2.16 | doc, drg, gafolo, rdnzao, togs   |
|           20 |     3864 | 2024-03-05 | Solid             | W   | 0.174      | -            | -                | -                | -         |     2.19 | doc, drg, gafolo, rdnzao, togs   |
|           19 |     4058 | 2024-02-24 | Galorys           | W   | 0.109      | -            | -                | -                | -         |     1.35 | doc, drg, gafolo, rdnzao, togs   |
|           18 |     4066 | 2024-02-24 | Galorys           | W   | 0.108      | -            | -                | -                | -         |     1.36 | doc, drg, gafolo, rdnzao, togs   |
|           17 |     4070 | 2024-02-24 | Fluxo             | L   | 0.108      | -            | -                | -                | -         |    -1.35 | doc, drg, gafolo, rdnzao, togs   |
|           16 |     4123 | 2024-02-21 | Corinthians       | W   | 0.089      | -            | -                | -                | -         |     0.20 | doc, drg, gafolo, rdnzao, togs   |
|           15 |     4128 | 2024-02-21 | Case              | W   | 0.088      | -            | -                | -                | -         |     1.27 | doc, drg, gafolo, rdnzao, togs   |
|           14 |     4133 | 2024-02-21 | Galorys           | W   | 0.087      | -            | -                | -                | -         |     1.12 | doc, drg, gafolo, rdnzao, togs   |
|           13 |     4158 | 2024-02-20 | Flamengo          | L   | 0.081      | -            | -                | -                | -         |    -2.39 | doc, drg, gafolo, rdnzao, togs   |
|           12 |     4163 | 2024-02-20 | Case              | W   | 0.080      | -            | -                | -                | -         |     1.15 | doc, drg, gafolo, rdnzao, togs   |
|           11 |     4187 | 2024-02-19 | Solid             | W   | 0.073      | -            | -                | -                | -         |     0.94 | doc, drg, gafolo, rdnzao, togs   |
|           10 |     4201 | 2024-02-18 | Galorys           | W   | 0.069      | -            | -                | -                | -         |     0.89 | doc, drg, gafolo, rdnzao, togs   |
|            9 |     4224 | 2024-02-17 | W7M               | L   | 0.062      | -            | -                | -                | -         |    -1.31 | doc, drg, gafolo, rdnzao, togs   |
|            8 |     4229 | 2024-02-17 | Galorys           | L   | 0.061      | -            | -                | -                | -         |    -1.14 | doc, drg, gafolo, rdnzao, togs   |
|            7 |     4264 | 2024-02-16 | W7M               | W   | 0.053      | -            | -                | -                | -         |     0.55 | doc, drg, gafolo, rdnzao, togs   |
|            6 |     4282 | 2024-02-15 | Case              | L   | 0.048      | -            | -                | -                | -         |    -0.82 | doc, drg, gafolo, rdnzao, togs   |
|            5 |     4288 | 2024-02-15 | Fluxo             | L   | 0.047      | -            | -                | -                | -         |    -0.59 | doc, drg, gafolo, rdnzao, togs   |
|            4 |     4289 | 2024-02-15 | Fluxo             | L   | 0.047      | -            | -                | -                | -         |    -0.59 | doc, drg, gafolo, rdnzao, togs   |
|            3 |     4317 | 2024-02-14 | Hype              | W   | 0.042      | -            | -                | -                | -         |     0.05 | doc, drg, gafolo, rdnzao, togs   |
|            2 |     4328 | 2024-02-14 | Galorys           | W   | 0.040      | -            | -                | -                | -         |     0.51 | doc, drg, gafolo, rdnzao, togs   |
|            1 |     4372 | 2024-02-12 | Solid             | W   | 0.028      | -            | -                | -                | -         |     0.36 | doc, drg, gafolo, rdnzao, togs   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($9,608.06)
- Divide that value by the 5th highest value among all rosters ($320,068.63)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-02 |      1.000 | $750.00        | $750.00         |
| 2024-06-28 |      0.940 | $500.00        | $470.17         |
| 2024-06-16 |      0.860 | $2,500.00      | $2,151.04       |
| 2024-06-10 |      0.822 | $750.00        | $616.27         |
| 2024-06-09 |      0.814 | $5,000.00      | $4,072.45       |
| 2024-05-19 |      0.674 | $1,000.00      | $673.75         |
| 2024-02-25 |      0.114 | $5,000.00      | $571.53         |
| 2024-02-21 |      0.087 | $3,500.00      | $302.85         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
