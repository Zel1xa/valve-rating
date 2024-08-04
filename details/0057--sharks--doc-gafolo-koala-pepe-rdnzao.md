### Roster Details<br />
Team Name: Sharks<br />
Roster: doc, gafolo, koala, pepe, rdnzao<br />
Global Rank: [57](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [15]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1025.0<br />
<br />
Final Rank Value (1025.0) = Starting Rank Value (973.2) + Head To Head Adjustments (51.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.397[<sup>1</sup>](#table2)
- Bounty Collected: 0.427[<sup>2</sup>](#table1)
- Opponent Network: 0.297[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.280<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 973.2
- 400 + ( ( 0.280 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 973.2


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
|           93 |       56 | 2024-08-02 | paiN              | L   | 1.000      | -            | -                | -                | -         |    -3.50 | doc, gafolo, koala, pepe, rdnzao |
|           92 |       86 | 2024-08-01 | Hype              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.06 | doc, gafolo, koala, pepe, rdnzao |
|           91 |       93 | 2024-08-01 | paiN              | L   | 1.000      | -            | -                | -                | -         |    -3.46 | doc, gafolo, koala, pepe, rdnzao |
|           90 |      125 | 2024-07-31 | MIBR              | L   | 1.000      | -            | -                | -                | -         |    -4.61 | doc, gafolo, koala, pepe, rdnzao |
|           89 |      135 | 2024-07-31 | Solid             | W   | 1.000      | 0.371        | -                | 0.835 (0.310)    | 0 (0.000) |    12.30 | doc, gafolo, koala, pepe, rdnzao |
|           88 |      169 | 2024-07-30 | Hype              | W   | 1.000      | -            | -                | -                | 0 (0.000) |    10.24 | doc, gafolo, koala, pepe, rdnzao |
|           87 |      242 | 2024-07-28 | Bad News Chickens | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.46 | doc, gafolo, koala, pepe, rdnzao |
|           86 |      290 | 2024-07-26 | Imperial          | L   | 1.000      | -            | -                | -                | -         |    -8.50 | doc, gafolo, koala, pepe, rdnzao |
|           85 |      317 | 2024-07-25 | BESTIA            | W   | 1.000      | -            | -                | -                | 0 (0.000) |    16.14 | doc, gafolo, koala, pepe, rdnzao |
|           84 |      324 | 2024-07-25 | Patins da Ferrari | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.21 | doc, gafolo, koala, pepe, rdnzao |
|           83 |      366 | 2024-07-24 | Bad News Chickens | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.41 | doc, gafolo, koala, pepe, rdnzao |
|           82 |      374 | 2024-07-24 | Yawara            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.00 | doc, gafolo, koala, pepe, rdnzao |
|           81 |      393 | 2024-07-23 | ODDIK             | L   | 1.000      | -            | -                | -                | -         |   -14.08 | doc, gafolo, koala, pepe, rdnzao |
|           80 |      396 | 2024-07-23 | W7M               | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.11 | doc, gafolo, koala, pepe, rdnzao |
|           79 |      482 | 2024-07-20 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |    -7.58 | doc, gafolo, koala, pepe, rdnzao |
|           78 |      535 | 2024-07-19 | Hype              | W   | 1.000      | -            | -                | -                | 0 (0.000) |    12.48 | doc, gafolo, koala, pepe, rdnzao |
|           77 |      560 | 2024-07-18 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |    -8.01 | doc, gafolo, koala, pepe, rdnzao |
|           76 |      562 | 2024-07-18 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |    -8.58 | doc, gafolo, koala, pepe, rdnzao |
|           75 |      625 | 2024-07-17 | ODDIK             | W   | 1.000      | 0.450        | 0.098 (0.044)    | 0.831 (0.374)    | -         |    17.41 | doc, gafolo, koala, pepe, rdnzao |
|           74 |      636 | 2024-07-17 | ODDIK             | W   | 1.000      | 0.450        | 0.098 (0.044)    | 0.831 (0.374)    | -         |    18.98 | doc, gafolo, koala, pepe, rdnzao |
|           73 |      690 | 2024-07-16 | RED Canids        | L   | 1.000      | -            | -                | -                | -         |    -7.81 | doc, gafolo, koala, pepe, rdnzao |
|           72 |      696 | 2024-07-16 | RED Canids        | L   | 1.000      | -            | -                | -                | -         |    -8.35 | doc, gafolo, koala, pepe, rdnzao |
|           71 |      740 | 2024-07-15 | KRÜ               | L   | 1.000      | -            | -                | -                | -         |   -20.61 | doc, gafolo, koala, pepe, rdnzao |
|           70 |      744 | 2024-07-15 | KRÜ               | W   | 1.000      | 0.450        | -                | 0.492 (0.222)    | -         |    10.50 | doc, gafolo, koala, pepe, rdnzao |
|           69 |      816 | 2024-07-11 | Bounty Hunters    | L   | 1.000      | -            | -                | -                | -         |   -16.70 | doc, gafolo, koala, pepe, rdnzao |
|           68 |      831 | 2024-07-10 | BESTIA            | W   | 1.000      | 0.371        | 0.095 (0.035)    | 0.801 (0.297)    | -         |    16.99 | doc, gafolo, koala, pepe, rdnzao |
|           67 |      851 | 2024-07-09 | KRÜ               | L   | 1.000      | -            | -                | -                | -         |   -21.11 | doc, gafolo, koala, pepe, rdnzao |
|           66 |      873 | 2024-07-08 | Patins da Ferrari | W   | 1.000      | -            | -                | -                | -         |     8.92 | doc, gafolo, koala, pepe, rdnzao |
|           65 |      909 | 2024-06-30 | Patins da Ferrari | L   | 0.969      | -            | -                | -                | -         |   -21.96 | doc, gafolo, koala, pepe, rdnzao |
|           64 |      923 | 2024-06-28 | KRÜ               | W   | 0.956      | -            | -                | -                | -         |     8.99 | doc, gafolo, koala, pepe, rdnzao |
|           63 |      924 | 2024-06-28 | Bounty Hunters    | L   | 0.955      | -            | -                | -                | -         |   -18.61 | doc, gafolo, koala, pepe, rdnzao |
|           62 |      928 | 2024-06-27 | Galorys           | W   | 0.950      | -            | -                | -                | -         |     8.63 | doc, gafolo, koala, pepe, rdnzao |
|           61 |      931 | 2024-06-27 | inSanitY          | L   | 0.948      | -            | -                | -                | -         |   -15.84 | doc, gafolo, koala, pepe, rdnzao |
|           60 |     1032 | 2024-06-14 | Fluxo             | L   | 0.862      | -            | -                | -                | -         |   -11.63 | doc, gafolo, koala, pepe, rdnzao |
|           59 |     1154 | 2024-06-10 | Vikings KR        | W   | 0.834      | -            | -                | -                | -         |     5.32 | doc, gafolo, koala, pepe, rdnzao |
|           58 |     1187 | 2024-06-09 | paiN              | L   | 0.828      | -            | -                | -                | -         |    -4.17 | doc, gafolo, koala, pepe, rdnzao |
|           57 |     1206 | 2024-06-09 | BESTIA            | W   | 0.827      | 0.450        | 0.095 (0.035)    | 0.801 (0.298)    | -         |    12.70 | doc, gafolo, koala, pepe, rdnzao |
|           56 |     1258 | 2024-06-08 | Hype              | W   | 0.821      | -            | -                | -                | -         |     8.72 | doc, gafolo, koala, pepe, rdnzao |
|           55 |     1273 | 2024-06-08 | Patins da Ferrari | L   | 0.820      | -            | -                | -                | -         |   -20.19 | doc, gafolo, koala, pepe, rdnzao |
|           54 |     1300 | 2024-06-07 | 9z                | L   | 0.816      | -            | -                | -                | -         |    -2.21 | doc, gafolo, koala, pepe, rdnzao |
|           53 |     1359 | 2024-06-06 | paiN              | W   | 0.809      | 0.450        | 0.327 (0.119)    | 0.866 (0.316)    | -         |    21.70 | doc, gafolo, koala, pepe, rdnzao |
|           52 |     1428 | 2024-06-05 | Imperial          | L   | 0.803      | -            | -                | -                | -         |    -4.90 | doc, gafolo, koala, pepe, rdnzao |
|           51 |     1478 | 2024-06-04 | BESTIA            | W   | 0.796      | 0.450        | 0.095 (0.034)    | 0.801 (0.287)    | -         |    14.06 | doc, gafolo, koala, pepe, rdnzao |
|           50 |     1805 | 2024-05-22 | Imperial          | W   | 0.708      | 0.450        | 0.237 (0.075)    | -                | -         |    18.02 | doc, drg, gafolo, pepe, rdnzao   |
|           49 |     1809 | 2024-05-22 | Imperial          | L   | 0.708      | -            | -                | -                | -         |    -4.16 | doc, drg, gafolo, pepe, rdnzao   |
|           48 |     1836 | 2024-05-21 | Case              | L   | 0.703      | -            | -                | -                | -         |   -13.62 | doc, drg, gafolo, pepe, rdnzao   |
|           47 |     1837 | 2024-05-21 | Case              | W   | 0.703      | 0.450        | -                | 0.805 (0.255)    | -         |     8.58 | doc, drg, gafolo, pepe, rdnzao   |
|           46 |     1841 | 2024-05-21 | RED Canids        | W   | 0.703      | 0.450        | 0.077 (0.024)    | 0.743 (0.235)    | -         |    15.44 | doc, drg, gafolo, pepe, rdnzao   |
|           45 |     1843 | 2024-05-21 | RED Canids        | L   | 0.702      | -            | -                | -                | -         |    -6.63 | doc, drg, gafolo, pepe, rdnzao   |
|           44 |     1974 | 2024-05-17 | ODDIK             | L   | 0.675      | -            | -                | -                | -         |   -12.48 | doc, drg, gafolo, rdnzao, togs   |
|           43 |     1999 | 2024-05-16 | W7M               | W   | 0.669      | -            | -                | -                | -         |     4.87 | doc, drg, gafolo, rdnzao, togs   |
|           42 |     2002 | 2024-05-16 | W7M               | W   | 0.669      | -            | -                | -                | -         |     5.08 | doc, drg, gafolo, rdnzao, togs   |
|           41 |     2007 | 2024-05-16 | Hype              | W   | 0.668      | -            | -                | -                | -         |     7.39 | doc, drg, gafolo, rdnzao, togs   |
|           40 |     2046 | 2024-05-15 | Vikings KR        | W   | 0.663      | -            | -                | -                | -         |     5.84 | doc, drg, gafolo, rdnzao, togs   |
|           39 |     2054 | 2024-05-15 | 9z                | L   | 0.662      | -            | -                | -                | -         |    -1.04 | doc, drg, gafolo, rdnzao, togs   |
|           38 |     2113 | 2024-05-14 | Fluxo             | L   | 0.655      | -            | -                | -                | -         |    -7.24 | doc, drg, gafolo, rdnzao, togs   |
|           37 |     2140 | 2024-05-13 | RED Canids        | W   | 0.649      | 0.384        | 0.077 (0.019)    | -                | -         |    13.28 | doc, drg, gafolo, rdnzao, togs   |
|           36 |     2147 | 2024-05-13 | W7M               | W   | 0.648      | -            | -                | -                | -         |     5.81 | doc, drg, gafolo, rdnzao, togs   |
|           35 |     2195 | 2024-05-11 | W7M               | W   | 0.635      | -            | -                | -                | -         |     5.97 | doc, drg, gafolo, rdnzao, togs   |
|           34 |     2239 | 2024-05-09 | BESTIA            | L   | 0.623      | -            | -                | -                | -         |   -10.82 | doc, drg, gafolo, rdnzao, togs   |
|           33 |     2259 | 2024-05-08 | 9z                | L   | 0.616      | -            | -                | -                | -         |    -0.90 | doc, drg, gafolo, rdnzao, togs   |
|           32 |     2297 | 2024-05-06 | BESTIA            | W   | 0.603      | 0.435        | 0.095 (0.025)    | -                | -         |     8.45 | doc, drg, gafolo, rdnzao, togs   |
|           31 |     2896 | 2024-04-11 | paiN              | L   | 0.435      | -            | -                | -                | -         |    -1.08 | doc, drg, gafolo, rdnzao, togs   |
|           30 |     3159 | 2024-04-03 | 2GAME             | W   | 0.383      | -            | -                | -                | -         |     1.88 | doc, drg, gafolo, rdnzao, togs   |
|           29 |     3162 | 2024-04-03 | 2GAME             | W   | 0.383      | -            | -                | -                | -         |     1.91 | doc, drg, gafolo, rdnzao, togs   |
|           28 |     3531 | 2024-03-14 | MIBR              | L   | 0.250      | -            | -                | -                | -         |    -0.65 | doc, drg, gafolo, rdnzao, togs   |
|           27 |     3533 | 2024-03-14 | MIBR              | L   | 0.250      | -            | -                | -                | -         |    -0.66 | doc, drg, gafolo, rdnzao, togs   |
|           26 |     3561 | 2024-03-13 | Yawara            | W   | 0.243      | -            | -                | -                | -         |     0.55 | doc, drg, gafolo, rdnzao, togs   |
|           25 |     3564 | 2024-03-13 | ODDIK             | W   | 0.242      | -            | -                | -                | -         |     4.05 | doc, drg, gafolo, rdnzao, togs   |
|           24 |     3637 | 2024-03-11 | Fluxo             | L   | 0.227      | -            | -                | -                | -         |    -2.85 | doc, drg, gafolo, rdnzao, togs   |
|           23 |     3665 | 2024-03-09 | Case              | L   | 0.215      | -            | -                | -                | -         |    -3.86 | doc, drg, gafolo, rdnzao, togs   |
|           22 |     3729 | 2024-03-07 | Corinthians       | W   | 0.200      | -            | -                | -                | -         |     0.43 | doc, drg, gafolo, rdnzao, togs   |
|           21 |     3783 | 2024-03-05 | Solid             | W   | 0.188      | -            | -                | -                | -         |     2.33 | doc, drg, gafolo, rdnzao, togs   |
|           20 |     3789 | 2024-03-05 | Solid             | W   | 0.188      | -            | -                | -                | -         |     2.36 | doc, drg, gafolo, rdnzao, togs   |
|           19 |     3983 | 2024-02-24 | Galorys           | W   | 0.123      | -            | -                | -                | -         |     1.52 | doc, drg, gafolo, rdnzao, togs   |
|           18 |     3991 | 2024-02-24 | Galorys           | W   | 0.123      | -            | -                | -                | -         |     1.53 | doc, drg, gafolo, rdnzao, togs   |
|           17 |     3995 | 2024-02-24 | Fluxo             | L   | 0.122      | -            | -                | -                | -         |    -1.53 | doc, drg, gafolo, rdnzao, togs   |
|           16 |     4048 | 2024-02-21 | Corinthians       | W   | 0.103      | -            | -                | -                | -         |     0.23 | doc, drg, gafolo, rdnzao, togs   |
|           15 |     4053 | 2024-02-21 | Case              | W   | 0.102      | -            | -                | -                | -         |     1.48 | doc, drg, gafolo, rdnzao, togs   |
|           14 |     4058 | 2024-02-21 | Galorys           | W   | 0.101      | -            | -                | -                | -         |     1.30 | doc, drg, gafolo, rdnzao, togs   |
|           13 |     4083 | 2024-02-20 | Flamengo          | L   | 0.096      | -            | -                | -                | -         |    -2.82 | doc, drg, gafolo, rdnzao, togs   |
|           12 |     4088 | 2024-02-20 | Case              | W   | 0.094      | -            | -                | -                | -         |     1.36 | doc, drg, gafolo, rdnzao, togs   |
|           11 |     4112 | 2024-02-19 | Solid             | W   | 0.088      | -            | -                | -                | -         |     1.12 | doc, drg, gafolo, rdnzao, togs   |
|           10 |     4126 | 2024-02-18 | Galorys           | W   | 0.083      | -            | -                | -                | -         |     1.08 | doc, drg, gafolo, rdnzao, togs   |
|            9 |     4149 | 2024-02-17 | W7M               | L   | 0.076      | -            | -                | -                | -         |    -1.62 | doc, drg, gafolo, rdnzao, togs   |
|            8 |     4154 | 2024-02-17 | Galorys           | L   | 0.075      | -            | -                | -                | -         |    -1.41 | doc, drg, gafolo, rdnzao, togs   |
|            7 |     4189 | 2024-02-16 | W7M               | W   | 0.068      | -            | -                | -                | -         |     0.70 | doc, drg, gafolo, rdnzao, togs   |
|            6 |     4207 | 2024-02-15 | Case              | L   | 0.062      | -            | -                | -                | -         |    -1.07 | doc, drg, gafolo, rdnzao, togs   |
|            5 |     4213 | 2024-02-15 | Fluxo             | L   | 0.062      | -            | -                | -                | -         |    -0.77 | doc, drg, gafolo, rdnzao, togs   |
|            4 |     4214 | 2024-02-15 | Fluxo             | L   | 0.061      | -            | -                | -                | -         |    -0.77 | doc, drg, gafolo, rdnzao, togs   |
|            3 |     4242 | 2024-02-14 | Hype              | W   | 0.056      | -            | -                | -                | -         |     0.07 | doc, drg, gafolo, rdnzao, togs   |
|            2 |     4253 | 2024-02-14 | Galorys           | W   | 0.055      | -            | -                | -                | -         |     0.70 | doc, drg, gafolo, rdnzao, togs   |
|            1 |     4297 | 2024-02-12 | Solid             | W   | 0.043      | -            | -                | -                | -         |     0.54 | doc, drg, gafolo, rdnzao, togs   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($9,871.25)
- Divide that value by the 5th highest value among all rosters ($324,344.55)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-02 |      1.000 | $750.00        | $750.00         |
| 2024-06-28 |      0.955 | $500.00        | $477.38         |
| 2024-06-16 |      0.875 | $2,500.00      | $2,187.09       |
| 2024-06-10 |      0.836 | $750.00        | $627.08         |
| 2024-06-09 |      0.829 | $5,000.00      | $4,144.56       |
| 2024-05-19 |      0.688 | $1,000.00      | $688.17         |
| 2024-02-25 |      0.129 | $5,000.00      | $643.63         |
| 2024-02-21 |      0.101 | $3,500.00      | $353.32         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
