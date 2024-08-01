### Roster Details<br />
Team Name: Sharks<br />
Roster: doc, gafolo, koala, pepe, rdnzao<br />
Global Rank: [55](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [15]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1020.7<br />
<br />
Final Rank Value (1020.7) = Starting Rank Value (973.2) + Head To Head Adjustments (47.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.394[<sup>1</sup>](#table2)
- Bounty Collected: 0.427[<sup>2</sup>](#table1)
- Opponent Network: 0.294[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.279<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 973.2
- 400 + ( ( 0.279 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 973.2


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
|           95 |       32 | 2024-07-31 | MIBR              | L   | 1.000      | -            | -                | -                | -         |    -5.61 | doc, gafolo, koala, pepe, rdnzao |
|           94 |       41 | 2024-07-31 | Solid             | W   | 1.000      | 0.371        | -                | 0.844 (0.313)    | 0 (0.000) |    12.57 | doc, gafolo, koala, pepe, rdnzao |
|           93 |       75 | 2024-07-30 | Hype              | W   | 1.000      | -            | -                | -                | 0 (0.000) |    11.01 | doc, gafolo, koala, pepe, rdnzao |
|           92 |      150 | 2024-07-28 | Bad News Chickens | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.54 | doc, gafolo, koala, pepe, rdnzao |
|           91 |      198 | 2024-07-26 | Imperial          | L   | 1.000      | -            | -                | -                | -         |    -9.26 | doc, gafolo, koala, pepe, rdnzao |
|           90 |      225 | 2024-07-25 | BESTIA            | W   | 1.000      | -            | -                | -                | 0 (0.000) |    15.87 | doc, gafolo, koala, pepe, rdnzao |
|           89 |      232 | 2024-07-25 | Patins da Ferrari | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.03 | doc, gafolo, koala, pepe, rdnzao |
|           88 |      274 | 2024-07-24 | Bad News Chickens | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.46 | doc, gafolo, koala, pepe, rdnzao |
|           87 |      282 | 2024-07-24 | Yawara            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.00 | doc, gafolo, koala, pepe, rdnzao |
|           86 |      301 | 2024-07-23 | ODDIK             | L   | 1.000      | -            | -                | -                | -         |   -13.76 | doc, gafolo, koala, pepe, rdnzao |
|           85 |      304 | 2024-07-23 | W7M               | W   | 1.000      | -            | -                | -                | 0 (0.000) |    10.83 | doc, gafolo, koala, pepe, rdnzao |
|           84 |      393 | 2024-07-20 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |    -7.70 | doc, gafolo, koala, pepe, rdnzao |
|           83 |      448 | 2024-07-19 | Hype              | W   | 1.000      | -            | -                | -                | 0 (0.000) |    13.51 | doc, gafolo, koala, pepe, rdnzao |
|           82 |      475 | 2024-07-18 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |    -8.10 | doc, gafolo, koala, pepe, rdnzao |
|           81 |      477 | 2024-07-18 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |    -8.67 | doc, gafolo, koala, pepe, rdnzao |
|           80 |      543 | 2024-07-17 | ODDIK             | W   | 1.000      | 0.450        | 0.096 (0.043)    | 0.822 (0.370)    | 0 (0.000) |    18.55 | doc, gafolo, koala, pepe, rdnzao |
|           79 |      553 | 2024-07-17 | ODDIK             | W   | 1.000      | 0.450        | 0.096 (0.043)    | 0.822 (0.370)    | -         |    20.18 | doc, gafolo, koala, pepe, rdnzao |
|           78 |      607 | 2024-07-16 | RED Canids        | L   | 1.000      | -            | -                | -                | -         |   -10.09 | doc, gafolo, koala, pepe, rdnzao |
|           77 |      614 | 2024-07-16 | RED Canids        | L   | 1.000      | -            | -                | -                | -         |   -10.91 | doc, gafolo, koala, pepe, rdnzao |
|           76 |      664 | 2024-07-15 | KRÜ               | L   | 1.000      | -            | -                | -                | -         |   -19.39 | doc, gafolo, koala, pepe, rdnzao |
|           75 |      667 | 2024-07-15 | KRÜ               | W   | 1.000      | -            | -                | -                | -         |    11.80 | doc, gafolo, koala, pepe, rdnzao |
|           74 |      741 | 2024-07-11 | Bounty Hunters    | L   | 1.000      | -            | -                | -                | -         |   -16.61 | doc, gafolo, koala, pepe, rdnzao |
|           73 |      756 | 2024-07-10 | BESTIA            | W   | 1.000      | 0.371        | 0.089 (0.033)    | 0.738 (0.274)    | -         |    17.06 | doc, gafolo, koala, pepe, rdnzao |
|           72 |      776 | 2024-07-09 | KRÜ               | L   | 1.000      | -            | -                | -                | -         |   -19.98 | doc, gafolo, koala, pepe, rdnzao |
|           71 |      798 | 2024-07-08 | Patins da Ferrari | W   | 1.000      | -            | -                | -                | -         |     9.17 | doc, gafolo, koala, pepe, rdnzao |
|           70 |      835 | 2024-06-30 | Patins da Ferrari | L   | 0.988      | -            | -                | -                | -         |   -22.11 | doc, gafolo, koala, pepe, rdnzao |
|           69 |      849 | 2024-06-28 | KRÜ               | W   | 0.974      | -            | -                | -                | -         |    10.39 | doc, gafolo, koala, pepe, rdnzao |
|           68 |      850 | 2024-06-28 | Bounty Hunters    | L   | 0.974      | -            | -                | -                | -         |   -18.63 | doc, gafolo, koala, pepe, rdnzao |
|           67 |      854 | 2024-06-27 | Galorys           | W   | 0.968      | -            | -                | -                | -         |     9.29 | doc, gafolo, koala, pepe, rdnzao |
|           66 |      857 | 2024-06-27 | inSanitY          | L   | 0.967      | -            | -                | -                | -         |   -16.25 | doc, gafolo, koala, pepe, rdnzao |
|           65 |      948 | 2024-06-14 | Fluxo             | L   | 0.881      | -            | -                | -                | -         |   -11.84 | doc, gafolo, koala, pepe, rdnzao |
|           64 |     1070 | 2024-06-10 | Vikings KR        | W   | 0.853      | -            | -                | -                | -         |     5.66 | doc, gafolo, koala, pepe, rdnzao |
|           63 |     1103 | 2024-06-09 | paiN              | L   | 0.847      | -            | -                | -                | -         |    -6.21 | doc, gafolo, koala, pepe, rdnzao |
|           62 |     1122 | 2024-06-09 | BESTIA            | W   | 0.846      | 0.450        | 0.089 (0.034)    | 0.738 (0.281)    | -         |    13.09 | doc, gafolo, koala, pepe, rdnzao |
|           61 |     1176 | 2024-06-08 | Hype              | W   | 0.840      | -            | -                | -                | -         |     9.97 | doc, gafolo, koala, pepe, rdnzao |
|           60 |     1191 | 2024-06-08 | Patins da Ferrari | L   | 0.839      | -            | -                | -                | -         |   -20.43 | doc, gafolo, koala, pepe, rdnzao |
|           59 |     1222 | 2024-06-07 | 9z                | L   | 0.835      | -            | -                | -                | -         |    -6.51 | doc, gafolo, koala, pepe, rdnzao |
|           58 |     1223 | 2024-06-07 | RED Canids        | W   | 0.835      | 0.450        | 0.075 (0.028)    | 0.754 (0.283)    | -         |    16.16 | doc, gafolo, koala, pepe, rdnzao |
|           57 |     1285 | 2024-06-06 | paiN              | W   | 0.828      | 0.450        | 0.300 (0.112)    | 0.801 (0.299)    | -         |    20.52 | doc, gafolo, koala, pepe, rdnzao |
|           56 |     1287 | 2024-06-06 | Hype              | L   | 0.828      | -            | -                | -                | -         |   -16.80 | doc, gafolo, koala, pepe, rdnzao |
|           55 |     1357 | 2024-06-05 | Imperial          | L   | 0.821      | -            | -                | -                | -         |    -5.07 | doc, gafolo, koala, pepe, rdnzao |
|           54 |     1408 | 2024-06-04 | BESTIA            | W   | 0.815      | 0.450        | 0.089 (0.033)    | 0.738 (0.271)    | -         |    14.36 | doc, gafolo, koala, pepe, rdnzao |
|           53 |     1738 | 2024-05-22 | Imperial          | W   | 0.727      | 0.450        | 0.239 (0.078)    | 0.719 (0.235)    | -         |    18.77 | doc, drg, gafolo, pepe, rdnzao   |
|           52 |     1742 | 2024-05-22 | Imperial          | L   | 0.727      | -            | -                | -                | -         |    -3.98 | doc, drg, gafolo, pepe, rdnzao   |
|           51 |     1781 | 2024-05-21 | Case              | L   | 0.722      | -            | -                | -                | -         |   -13.90 | doc, drg, gafolo, pepe, rdnzao   |
|           50 |     1782 | 2024-05-21 | Case              | W   | 0.722      | -            | -                | -                | -         |     8.88 | doc, drg, gafolo, pepe, rdnzao   |
|           49 |     1786 | 2024-05-21 | RED Canids        | W   | 0.721      | 0.450        | 0.075 (0.024)    | 0.754 (0.245)    | -         |    14.78 | doc, drg, gafolo, pepe, rdnzao   |
|           48 |     1788 | 2024-05-21 | RED Canids        | L   | 0.721      | -            | -                | -                | -         |    -7.93 | doc, drg, gafolo, pepe, rdnzao   |
|           47 |     1933 | 2024-05-17 | ODDIK             | L   | 0.694      | -            | -                | -                | -         |   -12.63 | doc, drg, gafolo, rdnzao, togs   |
|           46 |     1958 | 2024-05-16 | W7M               | W   | 0.688      | -            | -                | -                | -         |     5.61 | doc, drg, gafolo, rdnzao, togs   |
|           45 |     1961 | 2024-05-16 | W7M               | W   | 0.688      | -            | -                | -                | -         |     5.88 | doc, drg, gafolo, rdnzao, togs   |
|           44 |     1966 | 2024-05-16 | Hype              | W   | 0.687      | -            | -                | -                | -         |     7.86 | doc, drg, gafolo, rdnzao, togs   |
|           43 |     2005 | 2024-05-15 | Vikings KR        | W   | 0.682      | -            | -                | -                | -         |     5.97 | doc, drg, gafolo, rdnzao, togs   |
|           42 |     2013 | 2024-05-15 | 9z                | L   | 0.681      | -            | -                | -                | -         |    -5.15 | doc, drg, gafolo, rdnzao, togs   |
|           41 |     2078 | 2024-05-14 | Fluxo             | L   | 0.674      | -            | -                | -                | -         |    -7.31 | doc, drg, gafolo, rdnzao, togs   |
|           40 |     2106 | 2024-05-13 | RED Canids        | W   | 0.668      | -            | -                | -                | -         |    12.65 | doc, drg, gafolo, rdnzao, togs   |
|           39 |     2115 | 2024-05-13 | W7M               | W   | 0.667      | -            | -                | -                | -         |     6.32 | doc, drg, gafolo, rdnzao, togs   |
|           38 |     2163 | 2024-05-11 | W7M               | W   | 0.654      | -            | -                | -                | -         |     6.52 | doc, drg, gafolo, rdnzao, togs   |
|           37 |     2207 | 2024-05-09 | BESTIA            | L   | 0.642      | -            | -                | -                | -         |   -11.28 | doc, drg, gafolo, rdnzao, togs   |
|           36 |     2229 | 2024-05-08 | 9z                | L   | 0.635      | -            | -                | -                | -         |    -5.38 | doc, drg, gafolo, rdnzao, togs   |
|           35 |     2267 | 2024-05-06 | BESTIA            | W   | 0.622      | 0.435        | 0.089 (0.024)    | -                | -         |     8.43 | doc, drg, gafolo, rdnzao, togs   |
|           34 |     2880 | 2024-04-11 | paiN              | L   | 0.454      | -            | -                | -                | -         |    -1.44 | doc, drg, gafolo, rdnzao, togs   |
|           33 |     3144 | 2024-04-03 | 2GAME             | W   | 0.402      | -            | -                | -                | -         |     1.96 | doc, drg, gafolo, rdnzao, togs   |
|           32 |     3147 | 2024-04-03 | 2GAME             | W   | 0.401      | -            | -                | -                | -         |     2.00 | doc, drg, gafolo, rdnzao, togs   |
|           31 |     3528 | 2024-03-14 | MIBR              | L   | 0.269      | -            | -                | -                | -         |    -0.75 | doc, drg, gafolo, rdnzao, togs   |
|           30 |     3531 | 2024-03-14 | MIBR              | L   | 0.268      | -            | -                | -                | -         |    -0.76 | doc, drg, gafolo, rdnzao, togs   |
|           29 |     3562 | 2024-03-13 | Yawara            | W   | 0.261      | -            | -                | -                | -         |     0.58 | doc, drg, gafolo, rdnzao, togs   |
|           28 |     3566 | 2024-03-13 | ODDIK             | W   | 0.261      | -            | -                | -                | -         |     4.44 | doc, drg, gafolo, rdnzao, togs   |
|           27 |     3639 | 2024-03-11 | Fluxo             | L   | 0.246      | -            | -                | -                | -         |    -3.13 | doc, drg, gafolo, rdnzao, togs   |
|           26 |     3668 | 2024-03-09 | Case              | L   | 0.234      | -            | -                | -                | -         |    -4.21 | doc, drg, gafolo, rdnzao, togs   |
|           25 |     3732 | 2024-03-07 | Corinthians       | W   | 0.219      | -            | -                | -                | -         |     0.48 | doc, drg, gafolo, rdnzao, togs   |
|           24 |     3786 | 2024-03-05 | Solid             | W   | 0.207      | -            | -                | -                | -         |     2.52 | doc, drg, gafolo, rdnzao, togs   |
|           23 |     3791 | 2024-03-05 | 9z                | W   | 0.207      | -            | -                | -                | -         |     5.17 | doc, drg, gafolo, rdnzao, togs   |
|           22 |     3792 | 2024-03-05 | 9z                | W   | 0.207      | -            | -                | -                | -         |     5.23 | doc, drg, gafolo, rdnzao, togs   |
|           21 |     3796 | 2024-03-05 | Solid             | W   | 0.207      | -            | -                | -                | -         |     2.65 | doc, drg, gafolo, rdnzao, togs   |
|           20 |     3995 | 2024-02-24 | Galorys           | W   | 0.142      | -            | -                | -                | -         |     1.76 | doc, drg, gafolo, rdnzao, togs   |
|           19 |     4003 | 2024-02-24 | Galorys           | W   | 0.142      | -            | -                | -                | -         |     1.78 | doc, drg, gafolo, rdnzao, togs   |
|           18 |     4007 | 2024-02-24 | Fluxo             | L   | 0.141      | -            | -                | -                | -         |    -1.79 | doc, drg, gafolo, rdnzao, togs   |
|           17 |     4065 | 2024-02-21 | Corinthians       | W   | 0.122      | -            | -                | -                | -         |     0.29 | doc, drg, gafolo, rdnzao, togs   |
|           16 |     4070 | 2024-02-21 | Corinthians       | L   | 0.122      | -            | -                | -                | -         |    -3.55 | doc, drg, gafolo, rdnzao, togs   |
|           15 |     4071 | 2024-02-21 | Case              | W   | 0.121      | -            | -                | -                | -         |     1.80 | doc, drg, gafolo, rdnzao, togs   |
|           14 |     4076 | 2024-02-21 | Galorys           | W   | 0.120      | -            | -                | -                | -         |     1.55 | doc, drg, gafolo, rdnzao, togs   |
|           13 |     4101 | 2024-02-20 | Flamengo          | L   | 0.114      | -            | -                | -                | -         |    -3.37 | doc, drg, gafolo, rdnzao, togs   |
|           12 |     4106 | 2024-02-20 | Case              | W   | 0.113      | -            | -                | -                | -         |     1.68 | doc, drg, gafolo, rdnzao, togs   |
|           11 |     4130 | 2024-02-19 | Solid             | W   | 0.107      | -            | -                | -                | -         |     1.38 | doc, drg, gafolo, rdnzao, togs   |
|           10 |     4144 | 2024-02-18 | Galorys           | W   | 0.102      | -            | -                | -                | -         |     1.33 | doc, drg, gafolo, rdnzao, togs   |
|            9 |     4166 | 2024-02-17 | W7M               | L   | 0.095      | -            | -                | -                | -         |    -1.91 | doc, drg, gafolo, rdnzao, togs   |
|            8 |     4171 | 2024-02-17 | Galorys           | L   | 0.094      | -            | -                | -                | -         |    -1.76 | doc, drg, gafolo, rdnzao, togs   |
|            7 |     4207 | 2024-02-16 | W7M               | W   | 0.086      | -            | -                | -                | -         |     0.98 | doc, drg, gafolo, rdnzao, togs   |
|            6 |     4225 | 2024-02-15 | Case              | L   | 0.081      | -            | -                | -                | -         |    -1.35 | doc, drg, gafolo, rdnzao, togs   |
|            5 |     4231 | 2024-02-15 | Fluxo             | L   | 0.080      | -            | -                | -                | -         |    -1.03 | doc, drg, gafolo, rdnzao, togs   |
|            4 |     4232 | 2024-02-15 | Fluxo             | L   | 0.080      | -            | -                | -                | -         |    -1.04 | doc, drg, gafolo, rdnzao, togs   |
|            3 |     4260 | 2024-02-14 | Hype              | W   | 0.075      | -            | -                | -                | -         |     0.09 | doc, drg, gafolo, rdnzao, togs   |
|            2 |     4271 | 2024-02-14 | Galorys           | W   | 0.073      | -            | -                | -                | -         |     0.94 | doc, drg, gafolo, rdnzao, togs   |
|            1 |     4323 | 2024-02-12 | Solid             | W   | 0.061      | -            | -                | -                | -         |     0.79 | doc, drg, gafolo, rdnzao, togs   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($9,463.86)
- Divide that value by the 5th highest value among all rosters ($327,030.46)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-28 |      0.974 | $500.00        | $486.77         |
| 2024-06-16 |      0.894 | $2,500.00      | $2,234.03       |
| 2024-06-10 |      0.855 | $750.00        | $641.16         |
| 2024-06-09 |      0.848 | $5,000.00      | $4,238.43       |
| 2024-05-19 |      0.707 | $1,000.00      | $706.94         |
| 2024-02-25 |      0.147 | $5,000.00      | $737.50         |
| 2024-02-21 |      0.120 | $3,500.00      | $419.03         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
