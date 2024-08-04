### Roster Details<br />
Team Name: Sharks<br />
Roster: doc, gafolo, koala, pepe, rdnzao<br />
Global Rank: [56](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [15]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1024.9<br />
<br />
Final Rank Value (1024.9) = Starting Rank Value (973.2) + Head To Head Adjustments (51.8)<br />

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
|           93 |       48 | 2024-08-02 | paiN              | L   | 1.000      | -            | -                | -                | -         |    -3.50 | doc, gafolo, koala, pepe, rdnzao |
|           92 |       78 | 2024-08-01 | Hype              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.06 | doc, gafolo, koala, pepe, rdnzao |
|           91 |       85 | 2024-08-01 | paiN              | L   | 1.000      | -            | -                | -                | -         |    -3.46 | doc, gafolo, koala, pepe, rdnzao |
|           90 |      117 | 2024-07-31 | MIBR              | L   | 1.000      | -            | -                | -                | -         |    -4.62 | doc, gafolo, koala, pepe, rdnzao |
|           89 |      127 | 2024-07-31 | Solid             | W   | 1.000      | 0.371        | -                | 0.835 (0.309)    | 0 (0.000) |    12.30 | doc, gafolo, koala, pepe, rdnzao |
|           88 |      161 | 2024-07-30 | Hype              | W   | 1.000      | -            | -                | -                | 0 (0.000) |    10.24 | doc, gafolo, koala, pepe, rdnzao |
|           87 |      234 | 2024-07-28 | Bad News Chickens | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.46 | doc, gafolo, koala, pepe, rdnzao |
|           86 |      282 | 2024-07-26 | Imperial          | L   | 1.000      | -            | -                | -                | -         |    -8.50 | doc, gafolo, koala, pepe, rdnzao |
|           85 |      309 | 2024-07-25 | BESTIA            | W   | 1.000      | -            | -                | -                | 0 (0.000) |    16.14 | doc, gafolo, koala, pepe, rdnzao |
|           84 |      316 | 2024-07-25 | Patins da Ferrari | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.21 | doc, gafolo, koala, pepe, rdnzao |
|           83 |      358 | 2024-07-24 | Bad News Chickens | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.41 | doc, gafolo, koala, pepe, rdnzao |
|           82 |      366 | 2024-07-24 | Yawara            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.00 | doc, gafolo, koala, pepe, rdnzao |
|           81 |      385 | 2024-07-23 | ODDIK             | L   | 1.000      | -            | -                | -                | -         |   -14.08 | doc, gafolo, koala, pepe, rdnzao |
|           80 |      388 | 2024-07-23 | W7M               | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.11 | doc, gafolo, koala, pepe, rdnzao |
|           79 |      474 | 2024-07-20 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |    -7.58 | doc, gafolo, koala, pepe, rdnzao |
|           78 |      527 | 2024-07-19 | Hype              | W   | 1.000      | -            | -                | -                | 0 (0.000) |    12.48 | doc, gafolo, koala, pepe, rdnzao |
|           77 |      552 | 2024-07-18 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |    -8.01 | doc, gafolo, koala, pepe, rdnzao |
|           76 |      554 | 2024-07-18 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |    -8.58 | doc, gafolo, koala, pepe, rdnzao |
|           75 |      617 | 2024-07-17 | ODDIK             | W   | 1.000      | 0.450        | 0.098 (0.044)    | 0.831 (0.374)    | -         |    17.41 | doc, gafolo, koala, pepe, rdnzao |
|           74 |      628 | 2024-07-17 | ODDIK             | W   | 1.000      | 0.450        | 0.098 (0.044)    | 0.831 (0.374)    | -         |    18.98 | doc, gafolo, koala, pepe, rdnzao |
|           73 |      682 | 2024-07-16 | RED Canids        | L   | 1.000      | -            | -                | -                | -         |    -7.81 | doc, gafolo, koala, pepe, rdnzao |
|           72 |      688 | 2024-07-16 | RED Canids        | L   | 1.000      | -            | -                | -                | -         |    -8.35 | doc, gafolo, koala, pepe, rdnzao |
|           71 |      732 | 2024-07-15 | KRÜ               | L   | 1.000      | -            | -                | -                | -         |   -20.61 | doc, gafolo, koala, pepe, rdnzao |
|           70 |      736 | 2024-07-15 | KRÜ               | W   | 1.000      | 0.450        | -                | 0.492 (0.221)    | -         |    10.50 | doc, gafolo, koala, pepe, rdnzao |
|           69 |      808 | 2024-07-11 | Bounty Hunters    | L   | 1.000      | -            | -                | -                | -         |   -16.70 | doc, gafolo, koala, pepe, rdnzao |
|           68 |      823 | 2024-07-10 | BESTIA            | W   | 1.000      | 0.371        | 0.095 (0.035)    | 0.801 (0.297)    | -         |    16.99 | doc, gafolo, koala, pepe, rdnzao |
|           67 |      843 | 2024-07-09 | KRÜ               | L   | 1.000      | -            | -                | -                | -         |   -21.11 | doc, gafolo, koala, pepe, rdnzao |
|           66 |      865 | 2024-07-08 | Patins da Ferrari | W   | 1.000      | -            | -                | -                | -         |     8.92 | doc, gafolo, koala, pepe, rdnzao |
|           65 |      901 | 2024-06-30 | Patins da Ferrari | L   | 0.970      | -            | -                | -                | -         |   -21.97 | doc, gafolo, koala, pepe, rdnzao |
|           64 |      915 | 2024-06-28 | KRÜ               | W   | 0.956      | -            | -                | -                | -         |     8.99 | doc, gafolo, koala, pepe, rdnzao |
|           63 |      916 | 2024-06-28 | Bounty Hunters    | L   | 0.955      | -            | -                | -                | -         |   -18.62 | doc, gafolo, koala, pepe, rdnzao |
|           62 |      920 | 2024-06-27 | Galorys           | W   | 0.950      | -            | -                | -                | -         |     8.64 | doc, gafolo, koala, pepe, rdnzao |
|           61 |      923 | 2024-06-27 | inSanitY          | L   | 0.949      | -            | -                | -                | -         |   -15.85 | doc, gafolo, koala, pepe, rdnzao |
|           60 |     1024 | 2024-06-14 | Fluxo             | L   | 0.863      | -            | -                | -                | -         |   -11.64 | doc, gafolo, koala, pepe, rdnzao |
|           59 |     1146 | 2024-06-10 | Vikings KR        | W   | 0.835      | -            | -                | -                | -         |     5.32 | doc, gafolo, koala, pepe, rdnzao |
|           58 |     1179 | 2024-06-09 | paiN              | L   | 0.829      | -            | -                | -                | -         |    -4.17 | doc, gafolo, koala, pepe, rdnzao |
|           57 |     1198 | 2024-06-09 | BESTIA            | W   | 0.828      | 0.450        | 0.095 (0.036)    | 0.801 (0.298)    | -         |    12.71 | doc, gafolo, koala, pepe, rdnzao |
|           56 |     1250 | 2024-06-08 | Hype              | W   | 0.822      | -            | -                | -                | -         |     8.72 | doc, gafolo, koala, pepe, rdnzao |
|           55 |     1265 | 2024-06-08 | Patins da Ferrari | L   | 0.821      | -            | -                | -                | -         |   -20.21 | doc, gafolo, koala, pepe, rdnzao |
|           54 |     1292 | 2024-06-07 | 9z                | L   | 0.817      | -            | -                | -                | -         |    -2.25 | doc, gafolo, koala, pepe, rdnzao |
|           53 |     1351 | 2024-06-06 | paiN              | W   | 0.810      | 0.450        | 0.327 (0.119)    | 0.866 (0.316)    | -         |    21.72 | doc, gafolo, koala, pepe, rdnzao |
|           52 |     1420 | 2024-06-05 | Imperial          | L   | 0.803      | -            | -                | -                | -         |    -4.90 | doc, gafolo, koala, pepe, rdnzao |
|           51 |     1470 | 2024-06-04 | BESTIA            | W   | 0.797      | 0.450        | 0.095 (0.034)    | 0.801 (0.287)    | -         |    14.07 | doc, gafolo, koala, pepe, rdnzao |
|           50 |     1797 | 2024-05-22 | Imperial          | W   | 0.709      | 0.450        | 0.237 (0.076)    | -                | -         |    18.04 | doc, drg, gafolo, pepe, rdnzao   |
|           49 |     1801 | 2024-05-22 | Imperial          | L   | 0.709      | -            | -                | -                | -         |    -4.16 | doc, drg, gafolo, pepe, rdnzao   |
|           48 |     1828 | 2024-05-21 | Case              | L   | 0.704      | -            | -                | -                | -         |   -13.63 | doc, drg, gafolo, pepe, rdnzao   |
|           47 |     1829 | 2024-05-21 | Case              | W   | 0.704      | 0.450        | -                | 0.805 (0.255)    | -         |     8.58 | doc, drg, gafolo, pepe, rdnzao   |
|           46 |     1833 | 2024-05-21 | RED Canids        | W   | 0.703      | 0.450        | 0.077 (0.024)    | 0.743 (0.235)    | -         |    15.46 | doc, drg, gafolo, pepe, rdnzao   |
|           45 |     1835 | 2024-05-21 | RED Canids        | L   | 0.703      | -            | -                | -                | -         |    -6.64 | doc, drg, gafolo, pepe, rdnzao   |
|           44 |     1966 | 2024-05-17 | ODDIK             | L   | 0.676      | -            | -                | -                | -         |   -12.50 | doc, drg, gafolo, rdnzao, togs   |
|           43 |     1991 | 2024-05-16 | W7M               | W   | 0.670      | -            | -                | -                | -         |     4.87 | doc, drg, gafolo, rdnzao, togs   |
|           42 |     1994 | 2024-05-16 | W7M               | W   | 0.670      | -            | -                | -                | -         |     5.08 | doc, drg, gafolo, rdnzao, togs   |
|           41 |     1999 | 2024-05-16 | Hype              | W   | 0.669      | -            | -                | -                | -         |     7.39 | doc, drg, gafolo, rdnzao, togs   |
|           40 |     2038 | 2024-05-15 | Vikings KR        | W   | 0.664      | -            | -                | -                | -         |     5.85 | doc, drg, gafolo, rdnzao, togs   |
|           39 |     2046 | 2024-05-15 | 9z                | L   | 0.663      | -            | -                | -                | -         |    -1.05 | doc, drg, gafolo, rdnzao, togs   |
|           38 |     2105 | 2024-05-14 | Fluxo             | L   | 0.656      | -            | -                | -                | -         |    -7.24 | doc, drg, gafolo, rdnzao, togs   |
|           37 |     2132 | 2024-05-13 | RED Canids        | W   | 0.650      | 0.384        | 0.077 (0.019)    | -                | -         |    13.30 | doc, drg, gafolo, rdnzao, togs   |
|           36 |     2139 | 2024-05-13 | W7M               | W   | 0.649      | -            | -                | -                | -         |     5.81 | doc, drg, gafolo, rdnzao, togs   |
|           35 |     2187 | 2024-05-11 | W7M               | W   | 0.636      | -            | -                | -                | -         |     5.97 | doc, drg, gafolo, rdnzao, togs   |
|           34 |     2231 | 2024-05-09 | BESTIA            | L   | 0.624      | -            | -                | -                | -         |   -10.84 | doc, drg, gafolo, rdnzao, togs   |
|           33 |     2251 | 2024-05-08 | 9z                | L   | 0.617      | -            | -                | -                | -         |    -0.90 | doc, drg, gafolo, rdnzao, togs   |
|           32 |     2289 | 2024-05-06 | BESTIA            | W   | 0.604      | 0.435        | 0.095 (0.025)    | -                | -         |     8.45 | doc, drg, gafolo, rdnzao, togs   |
|           31 |     2888 | 2024-04-11 | paiN              | L   | 0.436      | -            | -                | -                | -         |    -1.08 | doc, drg, gafolo, rdnzao, togs   |
|           30 |     3151 | 2024-04-03 | 2GAME             | W   | 0.384      | -            | -                | -                | -         |     1.88 | doc, drg, gafolo, rdnzao, togs   |
|           29 |     3154 | 2024-04-03 | 2GAME             | W   | 0.383      | -            | -                | -                | -         |     1.91 | doc, drg, gafolo, rdnzao, togs   |
|           28 |     3523 | 2024-03-14 | MIBR              | L   | 0.251      | -            | -                | -                | -         |    -0.65 | doc, drg, gafolo, rdnzao, togs   |
|           27 |     3525 | 2024-03-14 | MIBR              | L   | 0.250      | -            | -                | -                | -         |    -0.66 | doc, drg, gafolo, rdnzao, togs   |
|           26 |     3553 | 2024-03-13 | Yawara            | W   | 0.243      | -            | -                | -                | -         |     0.56 | doc, drg, gafolo, rdnzao, togs   |
|           25 |     3556 | 2024-03-13 | ODDIK             | W   | 0.243      | -            | -                | -                | -         |     4.06 | doc, drg, gafolo, rdnzao, togs   |
|           24 |     3629 | 2024-03-11 | Fluxo             | L   | 0.228      | -            | -                | -                | -         |    -2.85 | doc, drg, gafolo, rdnzao, togs   |
|           23 |     3657 | 2024-03-09 | Case              | L   | 0.216      | -            | -                | -                | -         |    -3.88 | doc, drg, gafolo, rdnzao, togs   |
|           22 |     3721 | 2024-03-07 | Corinthians       | W   | 0.201      | -            | -                | -                | -         |     0.43 | doc, drg, gafolo, rdnzao, togs   |
|           21 |     3775 | 2024-03-05 | Solid             | W   | 0.189      | -            | -                | -                | -         |     2.34 | doc, drg, gafolo, rdnzao, togs   |
|           20 |     3781 | 2024-03-05 | Solid             | W   | 0.189      | -            | -                | -                | -         |     2.37 | doc, drg, gafolo, rdnzao, togs   |
|           19 |     3975 | 2024-02-24 | Galorys           | W   | 0.124      | -            | -                | -                | -         |     1.52 | doc, drg, gafolo, rdnzao, togs   |
|           18 |     3983 | 2024-02-24 | Galorys           | W   | 0.124      | -            | -                | -                | -         |     1.54 | doc, drg, gafolo, rdnzao, togs   |
|           17 |     3987 | 2024-02-24 | Fluxo             | L   | 0.123      | -            | -                | -                | -         |    -1.54 | doc, drg, gafolo, rdnzao, togs   |
|           16 |     4040 | 2024-02-21 | Corinthians       | W   | 0.104      | -            | -                | -                | -         |     0.23 | doc, drg, gafolo, rdnzao, togs   |
|           15 |     4045 | 2024-02-21 | Case              | W   | 0.103      | -            | -                | -                | -         |     1.49 | doc, drg, gafolo, rdnzao, togs   |
|           14 |     4050 | 2024-02-21 | Galorys           | W   | 0.102      | -            | -                | -                | -         |     1.31 | doc, drg, gafolo, rdnzao, togs   |
|           13 |     4075 | 2024-02-20 | Flamengo          | L   | 0.096      | -            | -                | -                | -         |    -2.84 | doc, drg, gafolo, rdnzao, togs   |
|           12 |     4080 | 2024-02-20 | Case              | W   | 0.095      | -            | -                | -                | -         |     1.38 | doc, drg, gafolo, rdnzao, togs   |
|           11 |     4104 | 2024-02-19 | Solid             | W   | 0.089      | -            | -                | -                | -         |     1.13 | doc, drg, gafolo, rdnzao, togs   |
|           10 |     4118 | 2024-02-18 | Galorys           | W   | 0.084      | -            | -                | -                | -         |     1.09 | doc, drg, gafolo, rdnzao, togs   |
|            9 |     4141 | 2024-02-17 | W7M               | L   | 0.077      | -            | -                | -                | -         |    -1.63 | doc, drg, gafolo, rdnzao, togs   |
|            8 |     4146 | 2024-02-17 | Galorys           | L   | 0.076      | -            | -                | -                | -         |    -1.43 | doc, drg, gafolo, rdnzao, togs   |
|            7 |     4181 | 2024-02-16 | W7M               | W   | 0.068      | -            | -                | -                | -         |     0.70 | doc, drg, gafolo, rdnzao, togs   |
|            6 |     4199 | 2024-02-15 | Case              | L   | 0.063      | -            | -                | -                | -         |    -1.08 | doc, drg, gafolo, rdnzao, togs   |
|            5 |     4205 | 2024-02-15 | Fluxo             | L   | 0.062      | -            | -                | -                | -         |    -0.78 | doc, drg, gafolo, rdnzao, togs   |
|            4 |     4206 | 2024-02-15 | Fluxo             | L   | 0.062      | -            | -                | -                | -         |    -0.78 | doc, drg, gafolo, rdnzao, togs   |
|            3 |     4234 | 2024-02-14 | Hype              | W   | 0.057      | -            | -                | -                | -         |     0.07 | doc, drg, gafolo, rdnzao, togs   |
|            2 |     4245 | 2024-02-14 | Galorys           | W   | 0.055      | -            | -                | -                | -         |     0.70 | doc, drg, gafolo, rdnzao, togs   |
|            1 |     4289 | 2024-02-12 | Solid             | W   | 0.043      | -            | -                | -                | -         |     0.55 | doc, drg, gafolo, rdnzao, togs   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($9,884.35)
- Divide that value by the 5th highest value among all rosters ($324,557.31)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-02 |      1.000 | $750.00        | $750.00         |
| 2024-06-28 |      0.955 | $500.00        | $477.74         |
| 2024-06-16 |      0.876 | $2,500.00      | $2,188.89       |
| 2024-06-10 |      0.837 | $750.00        | $627.62         |
| 2024-06-09 |      0.830 | $5,000.00      | $4,148.15       |
| 2024-05-19 |      0.689 | $1,000.00      | $688.89         |
| 2024-02-25 |      0.129 | $5,000.00      | $647.22         |
| 2024-02-21 |      0.102 | $3,500.00      | $355.83         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
