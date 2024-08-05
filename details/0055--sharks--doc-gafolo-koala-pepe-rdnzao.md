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
|           93 |      103 | 2024-08-02 | paiN              | L   | 1.000      | -            | -                | -                | -         |    -3.51 | doc, gafolo, koala, pepe, rdnzao |
|           92 |      133 | 2024-08-01 | Hype              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.08 | doc, gafolo, koala, pepe, rdnzao |
|           91 |      141 | 2024-08-01 | paiN              | L   | 1.000      | -            | -                | -                | -         |    -3.48 | doc, gafolo, koala, pepe, rdnzao |
|           90 |      174 | 2024-07-31 | MIBR              | L   | 1.000      | -            | -                | -                | -         |    -4.62 | doc, gafolo, koala, pepe, rdnzao |
|           89 |      184 | 2024-07-31 | Solid             | W   | 1.000      | 0.371        | -                | 0.825 (0.306)    | 0 (0.000) |    12.32 | doc, gafolo, koala, pepe, rdnzao |
|           88 |      218 | 2024-07-30 | Hype              | W   | 1.000      | -            | -                | -                | 0 (0.000) |    10.27 | doc, gafolo, koala, pepe, rdnzao |
|           87 |      291 | 2024-07-28 | Bad News Chickens | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.48 | doc, gafolo, koala, pepe, rdnzao |
|           86 |      339 | 2024-07-26 | Imperial          | L   | 1.000      | -            | -                | -                | -         |    -8.55 | doc, gafolo, koala, pepe, rdnzao |
|           85 |      366 | 2024-07-25 | BESTIA            | W   | 1.000      | -            | -                | -                | 0 (0.000) |    16.14 | doc, gafolo, koala, pepe, rdnzao |
|           84 |      373 | 2024-07-25 | Patins da Ferrari | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.23 | doc, gafolo, koala, pepe, rdnzao |
|           83 |      415 | 2024-07-24 | Bad News Chickens | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.43 | doc, gafolo, koala, pepe, rdnzao |
|           82 |      422 | 2024-07-24 | Yawara            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.01 | doc, gafolo, koala, pepe, rdnzao |
|           81 |      442 | 2024-07-23 | ODDIK             | L   | 1.000      | -            | -                | -                | -         |   -14.07 | doc, gafolo, koala, pepe, rdnzao |
|           80 |      445 | 2024-07-23 | W7M               | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.15 | doc, gafolo, koala, pepe, rdnzao |
|           79 |      531 | 2024-07-20 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |    -7.60 | doc, gafolo, koala, pepe, rdnzao |
|           78 |      584 | 2024-07-19 | Hype              | W   | 1.000      | -            | -                | -                | 0 (0.000) |    12.52 | doc, gafolo, koala, pepe, rdnzao |
|           77 |      609 | 2024-07-18 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |    -8.04 | doc, gafolo, koala, pepe, rdnzao |
|           76 |      611 | 2024-07-18 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |    -8.61 | doc, gafolo, koala, pepe, rdnzao |
|           75 |      674 | 2024-07-17 | ODDIK             | W   | 1.000      | 0.450        | 0.099 (0.045)    | 0.822 (0.370)    | -         |    17.43 | doc, gafolo, koala, pepe, rdnzao |
|           74 |      685 | 2024-07-17 | ODDIK             | W   | 1.000      | 0.450        | 0.099 (0.045)    | 0.822 (0.370)    | -         |    19.00 | doc, gafolo, koala, pepe, rdnzao |
|           73 |      739 | 2024-07-16 | RED Canids        | L   | 1.000      | -            | -                | -                | -         |    -7.83 | doc, gafolo, koala, pepe, rdnzao |
|           72 |      745 | 2024-07-16 | RED Canids        | L   | 1.000      | -            | -                | -                | -         |    -8.38 | doc, gafolo, koala, pepe, rdnzao |
|           71 |      789 | 2024-07-15 | KRÜ               | L   | 1.000      | -            | -                | -                | -         |   -20.59 | doc, gafolo, koala, pepe, rdnzao |
|           70 |      793 | 2024-07-15 | KRÜ               | W   | 1.000      | 0.450        | -                | 0.488 (0.220)    | -         |    10.53 | doc, gafolo, koala, pepe, rdnzao |
|           69 |      865 | 2024-07-11 | Bounty Hunters    | L   | 1.000      | -            | -                | -                | -         |   -16.70 | doc, gafolo, koala, pepe, rdnzao |
|           68 |      880 | 2024-07-10 | BESTIA            | W   | 1.000      | 0.371        | 0.096 (0.035)    | 0.792 (0.293)    | -         |    16.99 | doc, gafolo, koala, pepe, rdnzao |
|           67 |      900 | 2024-07-09 | KRÜ               | L   | 1.000      | -            | -                | -                | -         |   -21.08 | doc, gafolo, koala, pepe, rdnzao |
|           66 |      922 | 2024-07-08 | Patins da Ferrari | W   | 1.000      | -            | -                | -                | -         |     8.95 | doc, gafolo, koala, pepe, rdnzao |
|           65 |      958 | 2024-06-30 | Patins da Ferrari | L   | 0.961      | -            | -                | -                | -         |   -21.75 | doc, gafolo, koala, pepe, rdnzao |
|           64 |      972 | 2024-06-28 | KRÜ               | W   | 0.948      | -            | -                | -                | -         |     8.95 | doc, gafolo, koala, pepe, rdnzao |
|           63 |      973 | 2024-06-28 | Bounty Hunters    | L   | 0.947      | -            | -                | -                | -         |   -18.44 | doc, gafolo, koala, pepe, rdnzao |
|           62 |      977 | 2024-06-27 | Galorys           | W   | 0.942      | -            | -                | -                | -         |     8.61 | doc, gafolo, koala, pepe, rdnzao |
|           61 |      980 | 2024-06-27 | inSanitY          | L   | 0.940      | -            | -                | -                | -         |   -15.71 | doc, gafolo, koala, pepe, rdnzao |
|           60 |     1081 | 2024-06-14 | Fluxo             | L   | 0.854      | -            | -                | -                | -         |   -11.53 | doc, gafolo, koala, pepe, rdnzao |
|           59 |     1203 | 2024-06-10 | Vikings KR        | W   | 0.826      | -            | -                | -                | -         |     5.30 | doc, gafolo, koala, pepe, rdnzao |
|           58 |     1236 | 2024-06-09 | paiN              | L   | 0.820      | -            | -                | -                | -         |    -4.15 | doc, gafolo, koala, pepe, rdnzao |
|           57 |     1255 | 2024-06-09 | BESTIA            | W   | 0.819      | 0.450        | 0.096 (0.035)    | 0.792 (0.292)    | -         |    12.61 | doc, gafolo, koala, pepe, rdnzao |
|           56 |     1307 | 2024-06-08 | Hype              | W   | 0.813      | -            | -                | -                | -         |     8.68 | doc, gafolo, koala, pepe, rdnzao |
|           55 |     1322 | 2024-06-08 | Patins da Ferrari | L   | 0.813      | -            | -                | -                | -         |   -19.96 | doc, gafolo, koala, pepe, rdnzao |
|           54 |     1349 | 2024-06-07 | 9z                | L   | 0.808      | -            | -                | -                | -         |    -2.18 | doc, gafolo, koala, pepe, rdnzao |
|           53 |     1408 | 2024-06-06 | paiN              | W   | 0.801      | 0.450        | 0.325 (0.117)    | 0.856 (0.309)    | -         |    21.48 | doc, gafolo, koala, pepe, rdnzao |
|           52 |     1477 | 2024-06-05 | Imperial          | L   | 0.795      | -            | -                | -                | -         |    -4.90 | doc, gafolo, koala, pepe, rdnzao |
|           51 |     1527 | 2024-06-04 | BESTIA            | W   | 0.788      | 0.450        | 0.096 (0.034)    | 0.792 (0.281)    | -         |    13.93 | doc, gafolo, koala, pepe, rdnzao |
|           50 |     1854 | 2024-05-22 | Imperial          | W   | 0.701      | 0.450        | 0.235 (0.074)    | -                | -         |    17.77 | doc, drg, gafolo, pepe, rdnzao   |
|           49 |     1858 | 2024-05-22 | Imperial          | L   | 0.700      | -            | -                | -                | -         |    -4.17 | doc, drg, gafolo, pepe, rdnzao   |
|           48 |     1885 | 2024-05-21 | Case              | L   | 0.695      | -            | -                | -                | -         |   -13.45 | doc, drg, gafolo, pepe, rdnzao   |
|           47 |     1886 | 2024-05-21 | Case              | W   | 0.695      | 0.450        | -                | 0.795 (0.249)    | -         |     8.50 | doc, drg, gafolo, pepe, rdnzao   |
|           46 |     1890 | 2024-05-21 | RED Canids        | W   | 0.695      | 0.450        | 0.077 (0.024)    | 0.748 (0.234)    | -         |    15.24 | doc, drg, gafolo, pepe, rdnzao   |
|           45 |     1892 | 2024-05-21 | RED Canids        | L   | 0.694      | -            | -                | -                | -         |    -6.59 | doc, drg, gafolo, pepe, rdnzao   |
|           44 |     2023 | 2024-05-17 | ODDIK             | L   | 0.667      | -            | -                | -                | -         |   -12.31 | doc, drg, gafolo, rdnzao, togs   |
|           43 |     2048 | 2024-05-16 | W7M               | W   | 0.662      | -            | -                | -                | -         |     4.84 | doc, drg, gafolo, rdnzao, togs   |
|           42 |     2051 | 2024-05-16 | W7M               | W   | 0.661      | -            | -                | -                | -         |     5.05 | doc, drg, gafolo, rdnzao, togs   |
|           41 |     2056 | 2024-05-16 | Hype              | W   | 0.660      | -            | -                | -                | -         |     7.34 | doc, drg, gafolo, rdnzao, togs   |
|           40 |     2095 | 2024-05-15 | Vikings KR        | W   | 0.655      | -            | -                | -                | -         |     5.80 | doc, drg, gafolo, rdnzao, togs   |
|           39 |     2103 | 2024-05-15 | 9z                | L   | 0.654      | -            | -                | -                | -         |    -1.03 | doc, drg, gafolo, rdnzao, togs   |
|           38 |     2162 | 2024-05-14 | Fluxo             | L   | 0.647      | -            | -                | -                | -         |    -7.17 | doc, drg, gafolo, rdnzao, togs   |
|           37 |     2189 | 2024-05-13 | RED Canids        | W   | 0.641      | 0.384        | 0.077 (0.019)    | -                | -         |    13.10 | doc, drg, gafolo, rdnzao, togs   |
|           36 |     2196 | 2024-05-13 | W7M               | W   | 0.640      | -            | -                | -                | -         |     5.76 | doc, drg, gafolo, rdnzao, togs   |
|           35 |     2244 | 2024-05-11 | W7M               | W   | 0.627      | -            | -                | -                | -         |     5.92 | doc, drg, gafolo, rdnzao, togs   |
|           34 |     2288 | 2024-05-09 | BESTIA            | L   | 0.615      | -            | -                | -                | -         |   -10.64 | doc, drg, gafolo, rdnzao, togs   |
|           33 |     2308 | 2024-05-08 | 9z                | L   | 0.608      | -            | -                | -                | -         |    -0.89 | doc, drg, gafolo, rdnzao, togs   |
|           32 |     2346 | 2024-05-06 | BESTIA            | W   | 0.595      | 0.435        | 0.096 (0.025)    | -                | -         |     8.38 | doc, drg, gafolo, rdnzao, togs   |
|           31 |     2945 | 2024-04-11 | paiN              | L   | 0.427      | -            | -                | -                | -         |    -1.07 | doc, drg, gafolo, rdnzao, togs   |
|           30 |     3208 | 2024-04-03 | 2GAME             | W   | 0.375      | -            | -                | -                | -         |     1.84 | doc, drg, gafolo, rdnzao, togs   |
|           29 |     3211 | 2024-04-03 | 2GAME             | W   | 0.375      | -            | -                | -                | -         |     1.87 | doc, drg, gafolo, rdnzao, togs   |
|           28 |     3580 | 2024-03-14 | MIBR              | L   | 0.242      | -            | -                | -                | -         |    -0.64 | doc, drg, gafolo, rdnzao, togs   |
|           27 |     3582 | 2024-03-14 | MIBR              | L   | 0.242      | -            | -                | -                | -         |    -0.64 | doc, drg, gafolo, rdnzao, togs   |
|           26 |     3610 | 2024-03-13 | Yawara            | W   | 0.235      | -            | -                | -                | -         |     0.54 | doc, drg, gafolo, rdnzao, togs   |
|           25 |     3613 | 2024-03-13 | ODDIK             | W   | 0.234      | -            | -                | -                | -         |     3.92 | doc, drg, gafolo, rdnzao, togs   |
|           24 |     3686 | 2024-03-11 | Fluxo             | L   | 0.219      | -            | -                | -                | -         |    -2.75 | doc, drg, gafolo, rdnzao, togs   |
|           23 |     3714 | 2024-03-09 | Case              | L   | 0.207      | -            | -                | -                | -         |    -3.72 | doc, drg, gafolo, rdnzao, togs   |
|           22 |     3778 | 2024-03-07 | Corinthians       | W   | 0.193      | -            | -                | -                | -         |     0.41 | doc, drg, gafolo, rdnzao, togs   |
|           21 |     3832 | 2024-03-05 | Solid             | W   | 0.181      | -            | -                | -                | -         |     2.23 | doc, drg, gafolo, rdnzao, togs   |
|           20 |     3838 | 2024-03-05 | Solid             | W   | 0.180      | -            | -                | -                | -         |     2.27 | doc, drg, gafolo, rdnzao, togs   |
|           19 |     4032 | 2024-02-24 | Galorys           | W   | 0.115      | -            | -                | -                | -         |     1.42 | doc, drg, gafolo, rdnzao, togs   |
|           18 |     4040 | 2024-02-24 | Galorys           | W   | 0.115      | -            | -                | -                | -         |     1.44 | doc, drg, gafolo, rdnzao, togs   |
|           17 |     4044 | 2024-02-24 | Fluxo             | L   | 0.114      | -            | -                | -                | -         |    -1.43 | doc, drg, gafolo, rdnzao, togs   |
|           16 |     4097 | 2024-02-21 | Corinthians       | W   | 0.095      | -            | -                | -                | -         |     0.21 | doc, drg, gafolo, rdnzao, togs   |
|           15 |     4102 | 2024-02-21 | Case              | W   | 0.094      | -            | -                | -                | -         |     1.37 | doc, drg, gafolo, rdnzao, togs   |
|           14 |     4107 | 2024-02-21 | Galorys           | W   | 0.093      | -            | -                | -                | -         |     1.20 | doc, drg, gafolo, rdnzao, togs   |
|           13 |     4132 | 2024-02-20 | Flamengo          | L   | 0.088      | -            | -                | -                | -         |    -2.59 | doc, drg, gafolo, rdnzao, togs   |
|           12 |     4137 | 2024-02-20 | Case              | W   | 0.086      | -            | -                | -                | -         |     1.25 | doc, drg, gafolo, rdnzao, togs   |
|           11 |     4161 | 2024-02-19 | Solid             | W   | 0.080      | -            | -                | -                | -         |     1.02 | doc, drg, gafolo, rdnzao, togs   |
|           10 |     4175 | 2024-02-18 | Galorys           | W   | 0.075      | -            | -                | -                | -         |     0.97 | doc, drg, gafolo, rdnzao, togs   |
|            9 |     4198 | 2024-02-17 | W7M               | L   | 0.068      | -            | -                | -                | -         |    -1.45 | doc, drg, gafolo, rdnzao, togs   |
|            8 |     4203 | 2024-02-17 | Galorys           | L   | 0.067      | -            | -                | -                | -         |    -1.26 | doc, drg, gafolo, rdnzao, togs   |
|            7 |     4238 | 2024-02-16 | W7M               | W   | 0.060      | -            | -                | -                | -         |     0.62 | doc, drg, gafolo, rdnzao, togs   |
|            6 |     4256 | 2024-02-15 | Case              | L   | 0.054      | -            | -                | -                | -         |    -0.93 | doc, drg, gafolo, rdnzao, togs   |
|            5 |     4262 | 2024-02-15 | Fluxo             | L   | 0.054      | -            | -                | -                | -         |    -0.67 | doc, drg, gafolo, rdnzao, togs   |
|            4 |     4263 | 2024-02-15 | Fluxo             | L   | 0.053      | -            | -                | -                | -         |    -0.67 | doc, drg, gafolo, rdnzao, togs   |
|            3 |     4291 | 2024-02-14 | Hype              | W   | 0.048      | -            | -                | -                | -         |     0.06 | doc, drg, gafolo, rdnzao, togs   |
|            2 |     4302 | 2024-02-14 | Galorys           | W   | 0.047      | -            | -                | -                | -         |     0.60 | doc, drg, gafolo, rdnzao, togs   |
|            1 |     4346 | 2024-02-12 | Solid             | W   | 0.035      | -            | -                | -                | -         |     0.44 | doc, drg, gafolo, rdnzao, togs   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($9,727.19)
- Divide that value by the 5th highest value among all rosters ($322,004.12)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-02 |      1.000 | $750.00        | $750.00         |
| 2024-06-28 |      0.947 | $500.00        | $473.44         |
| 2024-06-16 |      0.867 | $2,500.00      | $2,167.36       |
| 2024-06-10 |      0.828 | $750.00        | $621.16         |
| 2024-06-09 |      0.821 | $5,000.00      | $4,105.09       |
| 2024-05-19 |      0.680 | $1,000.00      | $680.28         |
| 2024-02-25 |      0.121 | $5,000.00      | $604.17         |
| 2024-02-21 |      0.093 | $3,500.00      | $325.69         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
