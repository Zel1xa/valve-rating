### Roster Details<br />
Team Name: Sharks<br />
Roster: doc, gafolo, koala, pepe, rdnzao<br />
Global Rank: [56](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [15]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1025.0<br />
<br />
Final Rank Value (1025.0) = Starting Rank Value (973.2) + Head To Head Adjustments (51.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.398[<sup>1</sup>](#table2)
- Bounty Collected: 0.428[<sup>2</sup>](#table1)
- Opponent Network: 0.297[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.281<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 973.2
- 400 + ( ( 0.281 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 973.2


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
|           93 |       45 | 2024-08-02 | paiN              | L   | 1.000      | -            | -                | -                | -         |    -3.49 | doc, gafolo, koala, pepe, rdnzao |
|           92 |       75 | 2024-08-01 | Hype              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.07 | doc, gafolo, koala, pepe, rdnzao |
|           91 |       82 | 2024-08-01 | paiN              | L   | 1.000      | -            | -                | -                | -         |    -3.45 | doc, gafolo, koala, pepe, rdnzao |
|           90 |      114 | 2024-07-31 | MIBR              | L   | 1.000      | -            | -                | -                | -         |    -4.60 | doc, gafolo, koala, pepe, rdnzao |
|           89 |      124 | 2024-07-31 | Solid             | W   | 1.000      | 0.371        | -                | 0.835 (0.309)    | 0 (0.000) |    12.31 | doc, gafolo, koala, pepe, rdnzao |
|           88 |      158 | 2024-07-30 | Hype              | W   | 1.000      | -            | -                | -                | 0 (0.000) |    10.26 | doc, gafolo, koala, pepe, rdnzao |
|           87 |      231 | 2024-07-28 | Bad News Chickens | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.46 | doc, gafolo, koala, pepe, rdnzao |
|           86 |      279 | 2024-07-26 | Imperial          | L   | 1.000      | -            | -                | -                | -         |    -8.47 | doc, gafolo, koala, pepe, rdnzao |
|           85 |      306 | 2024-07-25 | BESTIA            | W   | 1.000      | -            | -                | -                | 0 (0.000) |    16.13 | doc, gafolo, koala, pepe, rdnzao |
|           84 |      313 | 2024-07-25 | Patins da Ferrari | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.21 | doc, gafolo, koala, pepe, rdnzao |
|           83 |      355 | 2024-07-24 | Bad News Chickens | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.41 | doc, gafolo, koala, pepe, rdnzao |
|           82 |      363 | 2024-07-24 | Yawara            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.00 | doc, gafolo, koala, pepe, rdnzao |
|           81 |      382 | 2024-07-23 | ODDIK             | L   | 1.000      | -            | -                | -                | -         |   -14.32 | doc, gafolo, koala, pepe, rdnzao |
|           80 |      385 | 2024-07-23 | W7M               | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.10 | doc, gafolo, koala, pepe, rdnzao |
|           79 |      471 | 2024-07-20 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |    -7.58 | doc, gafolo, koala, pepe, rdnzao |
|           78 |      524 | 2024-07-19 | Hype              | W   | 1.000      | -            | -                | -                | 0 (0.000) |    12.50 | doc, gafolo, koala, pepe, rdnzao |
|           77 |      549 | 2024-07-18 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |    -8.00 | doc, gafolo, koala, pepe, rdnzao |
|           76 |      551 | 2024-07-18 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |    -8.57 | doc, gafolo, koala, pepe, rdnzao |
|           75 |      614 | 2024-07-17 | ODDIK             | W   | 1.000      | 0.450        | 0.098 (0.044)    | 0.829 (0.373)    | -         |    17.07 | doc, gafolo, koala, pepe, rdnzao |
|           74 |      625 | 2024-07-17 | ODDIK             | W   | 1.000      | 0.450        | 0.098 (0.044)    | 0.829 (0.373)    | -         |    18.62 | doc, gafolo, koala, pepe, rdnzao |
|           73 |      679 | 2024-07-16 | RED Canids        | L   | 1.000      | -            | -                | -                | -         |    -7.82 | doc, gafolo, koala, pepe, rdnzao |
|           72 |      685 | 2024-07-16 | RED Canids        | L   | 1.000      | -            | -                | -                | -         |    -8.36 | doc, gafolo, koala, pepe, rdnzao |
|           71 |      729 | 2024-07-15 | KRÜ               | L   | 1.000      | -            | -                | -                | -         |   -20.30 | doc, gafolo, koala, pepe, rdnzao |
|           70 |      733 | 2024-07-15 | KRÜ               | W   | 1.000      | 0.450        | -                | 0.491 (0.221)    | -         |    10.84 | doc, gafolo, koala, pepe, rdnzao |
|           69 |      804 | 2024-07-11 | Bounty Hunters    | L   | 1.000      | -            | -                | -                | -         |   -16.70 | doc, gafolo, koala, pepe, rdnzao |
|           68 |      819 | 2024-07-10 | BESTIA            | W   | 1.000      | 0.371        | 0.095 (0.035)    | 0.799 (0.296)    | -         |    16.99 | doc, gafolo, koala, pepe, rdnzao |
|           67 |      839 | 2024-07-09 | KRÜ               | L   | 1.000      | -            | -                | -                | -         |   -21.13 | doc, gafolo, koala, pepe, rdnzao |
|           66 |      861 | 2024-07-08 | Patins da Ferrari | W   | 1.000      | -            | -                | -                | -         |     8.92 | doc, gafolo, koala, pepe, rdnzao |
|           65 |      897 | 2024-06-30 | Patins da Ferrari | L   | 0.973      | -            | -                | -                | -         |   -22.04 | doc, gafolo, koala, pepe, rdnzao |
|           64 |      911 | 2024-06-28 | KRÜ               | W   | 0.959      | -            | -                | -                | -         |     9.00 | doc, gafolo, koala, pepe, rdnzao |
|           63 |      912 | 2024-06-28 | Bounty Hunters    | L   | 0.959      | -            | -                | -                | -         |   -18.68 | doc, gafolo, koala, pepe, rdnzao |
|           62 |      916 | 2024-06-27 | Galorys           | W   | 0.953      | -            | -                | -                | -         |     8.64 | doc, gafolo, koala, pepe, rdnzao |
|           61 |      919 | 2024-06-27 | inSanitY          | L   | 0.952      | -            | -                | -                | -         |   -15.90 | doc, gafolo, koala, pepe, rdnzao |
|           60 |     1020 | 2024-06-14 | Fluxo             | L   | 0.866      | -            | -                | -                | -         |   -11.68 | doc, gafolo, koala, pepe, rdnzao |
|           59 |     1142 | 2024-06-10 | Vikings KR        | W   | 0.838      | -            | -                | -                | -         |     5.33 | doc, gafolo, koala, pepe, rdnzao |
|           58 |     1175 | 2024-06-09 | paiN              | L   | 0.832      | -            | -                | -                | -         |    -4.18 | doc, gafolo, koala, pepe, rdnzao |
|           57 |     1194 | 2024-06-09 | BESTIA            | W   | 0.831      | 0.450        | 0.095 (0.036)    | 0.799 (0.299)    | -         |    12.75 | doc, gafolo, koala, pepe, rdnzao |
|           56 |     1246 | 2024-06-08 | Hype              | W   | 0.825      | -            | -                | -                | -         |     8.74 | doc, gafolo, koala, pepe, rdnzao |
|           55 |     1261 | 2024-06-08 | Patins da Ferrari | L   | 0.824      | -            | -                | -                | -         |   -20.29 | doc, gafolo, koala, pepe, rdnzao |
|           54 |     1288 | 2024-06-07 | 9z                | L   | 0.820      | -            | -                | -                | -         |    -2.26 | doc, gafolo, koala, pepe, rdnzao |
|           53 |     1347 | 2024-06-06 | paiN              | W   | 0.813      | 0.450        | 0.328 (0.120)    | 0.865 (0.316)    | -         |    21.81 | doc, gafolo, koala, pepe, rdnzao |
|           52 |     1416 | 2024-06-05 | Imperial          | L   | 0.806      | -            | -                | -                | -         |    -4.90 | doc, gafolo, koala, pepe, rdnzao |
|           51 |     1466 | 2024-06-04 | BESTIA            | W   | 0.800      | 0.450        | 0.095 (0.034)    | 0.799 (0.288)    | -         |    14.12 | doc, gafolo, koala, pepe, rdnzao |
|           50 |     1793 | 2024-05-22 | Imperial          | W   | 0.712      | 0.450        | 0.238 (0.076)    | -                | -         |    18.14 | doc, drg, gafolo, pepe, rdnzao   |
|           49 |     1797 | 2024-05-22 | Imperial          | L   | 0.712      | -            | -                | -                | -         |    -4.16 | doc, drg, gafolo, pepe, rdnzao   |
|           48 |     1824 | 2024-05-21 | Case              | L   | 0.707      | -            | -                | -                | -         |   -13.70 | doc, drg, gafolo, pepe, rdnzao   |
|           47 |     1825 | 2024-05-21 | Case              | W   | 0.707      | 0.450        | -                | 0.804 (0.256)    | -         |     8.61 | doc, drg, gafolo, pepe, rdnzao   |
|           46 |     1829 | 2024-05-21 | RED Canids        | W   | 0.706      | 0.450        | 0.077 (0.025)    | 0.743 (0.236)    | -         |    15.54 | doc, drg, gafolo, pepe, rdnzao   |
|           45 |     1831 | 2024-05-21 | RED Canids        | L   | 0.706      | -            | -                | -                | -         |    -6.65 | doc, drg, gafolo, pepe, rdnzao   |
|           44 |     1962 | 2024-05-17 | ODDIK             | L   | 0.679      | -            | -                | -                | -         |   -12.56 | doc, drg, gafolo, rdnzao, togs   |
|           43 |     1987 | 2024-05-16 | W7M               | W   | 0.673      | -            | -                | -                | -         |     4.88 | doc, drg, gafolo, rdnzao, togs   |
|           42 |     1990 | 2024-05-16 | W7M               | W   | 0.673      | -            | -                | -                | -         |     5.09 | doc, drg, gafolo, rdnzao, togs   |
|           41 |     1995 | 2024-05-16 | Hype              | W   | 0.672      | -            | -                | -                | -         |     7.41 | doc, drg, gafolo, rdnzao, togs   |
|           40 |     2034 | 2024-05-15 | Vikings KR        | W   | 0.667      | -            | -                | -                | -         |     5.87 | doc, drg, gafolo, rdnzao, togs   |
|           39 |     2042 | 2024-05-15 | 9z                | L   | 0.666      | -            | -                | -                | -         |    -1.05 | doc, drg, gafolo, rdnzao, togs   |
|           38 |     2101 | 2024-05-14 | Fluxo             | L   | 0.659      | -            | -                | -                | -         |    -7.26 | doc, drg, gafolo, rdnzao, togs   |
|           37 |     2128 | 2024-05-13 | RED Canids        | W   | 0.653      | 0.384        | 0.077 (0.019)    | -                | -         |    13.37 | doc, drg, gafolo, rdnzao, togs   |
|           36 |     2135 | 2024-05-13 | W7M               | W   | 0.652      | -            | -                | -                | -         |     5.83 | doc, drg, gafolo, rdnzao, togs   |
|           35 |     2183 | 2024-05-11 | W7M               | W   | 0.639      | -            | -                | -                | -         |     5.99 | doc, drg, gafolo, rdnzao, togs   |
|           34 |     2227 | 2024-05-09 | BESTIA            | L   | 0.627      | -            | -                | -                | -         |   -10.90 | doc, drg, gafolo, rdnzao, togs   |
|           33 |     2247 | 2024-05-08 | 9z                | L   | 0.620      | -            | -                | -                | -         |    -0.91 | doc, drg, gafolo, rdnzao, togs   |
|           32 |     2285 | 2024-05-06 | BESTIA            | W   | 0.607      | 0.435        | 0.095 (0.025)    | -                | -         |     8.48 | doc, drg, gafolo, rdnzao, togs   |
|           31 |     2883 | 2024-04-11 | paiN              | L   | 0.439      | -            | -                | -                | -         |    -1.08 | doc, drg, gafolo, rdnzao, togs   |
|           30 |     3146 | 2024-04-03 | 2GAME             | W   | 0.387      | -            | -                | -                | -         |     1.90 | doc, drg, gafolo, rdnzao, togs   |
|           29 |     3149 | 2024-04-03 | 2GAME             | W   | 0.386      | -            | -                | -                | -         |     1.93 | doc, drg, gafolo, rdnzao, togs   |
|           28 |     3518 | 2024-03-14 | MIBR              | L   | 0.254      | -            | -                | -                | -         |    -0.66 | doc, drg, gafolo, rdnzao, togs   |
|           27 |     3520 | 2024-03-14 | MIBR              | L   | 0.253      | -            | -                | -                | -         |    -0.66 | doc, drg, gafolo, rdnzao, togs   |
|           26 |     3548 | 2024-03-13 | Yawara            | W   | 0.246      | -            | -                | -                | -         |     0.56 | doc, drg, gafolo, rdnzao, togs   |
|           25 |     3551 | 2024-03-13 | ODDIK             | W   | 0.246      | -            | -                | -                | -         |     4.11 | doc, drg, gafolo, rdnzao, togs   |
|           24 |     3623 | 2024-03-11 | Fluxo             | L   | 0.231      | -            | -                | -                | -         |    -2.89 | doc, drg, gafolo, rdnzao, togs   |
|           23 |     3651 | 2024-03-09 | Case              | L   | 0.219      | -            | -                | -                | -         |    -3.94 | doc, drg, gafolo, rdnzao, togs   |
|           22 |     3715 | 2024-03-07 | Corinthians       | W   | 0.204      | -            | -                | -                | -         |     0.43 | doc, drg, gafolo, rdnzao, togs   |
|           21 |     3769 | 2024-03-05 | Solid             | W   | 0.192      | -            | -                | -                | -         |     2.38 | doc, drg, gafolo, rdnzao, togs   |
|           20 |     3775 | 2024-03-05 | Solid             | W   | 0.192      | -            | -                | -                | -         |     2.41 | doc, drg, gafolo, rdnzao, togs   |
|           19 |     3969 | 2024-02-24 | Galorys           | W   | 0.127      | -            | -                | -                | -         |     1.56 | doc, drg, gafolo, rdnzao, togs   |
|           18 |     3977 | 2024-02-24 | Galorys           | W   | 0.127      | -            | -                | -                | -         |     1.57 | doc, drg, gafolo, rdnzao, togs   |
|           17 |     3981 | 2024-02-24 | Fluxo             | L   | 0.126      | -            | -                | -                | -         |    -1.58 | doc, drg, gafolo, rdnzao, togs   |
|           16 |     4034 | 2024-02-21 | Corinthians       | W   | 0.107      | -            | -                | -                | -         |     0.23 | doc, drg, gafolo, rdnzao, togs   |
|           15 |     4039 | 2024-02-21 | Case              | W   | 0.106      | -            | -                | -                | -         |     1.54 | doc, drg, gafolo, rdnzao, togs   |
|           14 |     4044 | 2024-02-21 | Galorys           | W   | 0.105      | -            | -                | -                | -         |     1.35 | doc, drg, gafolo, rdnzao, togs   |
|           13 |     4069 | 2024-02-20 | Flamengo          | L   | 0.099      | -            | -                | -                | -         |    -2.93 | doc, drg, gafolo, rdnzao, togs   |
|           12 |     4074 | 2024-02-20 | Case              | W   | 0.098      | -            | -                | -                | -         |     1.42 | doc, drg, gafolo, rdnzao, togs   |
|           11 |     4098 | 2024-02-19 | Solid             | W   | 0.092      | -            | -                | -                | -         |     1.17 | doc, drg, gafolo, rdnzao, togs   |
|           10 |     4112 | 2024-02-18 | Galorys           | W   | 0.087      | -            | -                | -                | -         |     1.13 | doc, drg, gafolo, rdnzao, togs   |
|            9 |     4134 | 2024-02-17 | W7M               | L   | 0.080      | -            | -                | -                | -         |    -1.70 | doc, drg, gafolo, rdnzao, togs   |
|            8 |     4139 | 2024-02-17 | Galorys           | L   | 0.079      | -            | -                | -                | -         |    -1.48 | doc, drg, gafolo, rdnzao, togs   |
|            7 |     4174 | 2024-02-16 | W7M               | W   | 0.071      | -            | -                | -                | -         |     0.74 | doc, drg, gafolo, rdnzao, togs   |
|            6 |     4192 | 2024-02-15 | Case              | L   | 0.066      | -            | -                | -                | -         |    -1.13 | doc, drg, gafolo, rdnzao, togs   |
|            5 |     4198 | 2024-02-15 | Fluxo             | L   | 0.065      | -            | -                | -                | -         |    -0.82 | doc, drg, gafolo, rdnzao, togs   |
|            4 |     4199 | 2024-02-15 | Fluxo             | L   | 0.065      | -            | -                | -                | -         |    -0.82 | doc, drg, gafolo, rdnzao, togs   |
|            3 |     4227 | 2024-02-14 | Hype              | W   | 0.060      | -            | -                | -                | -         |     0.07 | doc, drg, gafolo, rdnzao, togs   |
|            2 |     4238 | 2024-02-14 | Galorys           | W   | 0.058      | -            | -                | -                | -         |     0.74 | doc, drg, gafolo, rdnzao, togs   |
|            1 |     4282 | 2024-02-12 | Solid             | W   | 0.046      | -            | -                | -                | -         |     0.59 | doc, drg, gafolo, rdnzao, togs   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($9,940.11)
- Divide that value by the 5th highest value among all rosters ($325,463.29)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-02 |      1.000 | $750.00        | $750.00         |
| 2024-06-28 |      0.959 | $500.00        | $479.27         |
| 2024-06-16 |      0.879 | $2,500.00      | $2,196.53       |
| 2024-06-10 |      0.840 | $750.00        | $629.91         |
| 2024-06-09 |      0.833 | $5,000.00      | $4,163.43       |
| 2024-05-19 |      0.692 | $1,000.00      | $691.94         |
| 2024-02-25 |      0.133 | $5,000.00      | $662.50         |
| 2024-02-21 |      0.105 | $3,500.00      | $366.53         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
