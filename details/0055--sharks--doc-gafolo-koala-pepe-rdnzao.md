### Roster Details<br />
Team Name: Sharks<br />
Roster: doc, gafolo, koala, pepe, rdnzao<br />
Global Rank: [55](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [15]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1020.6<br />
<br />
Final Rank Value (1020.6) = Starting Rank Value (973.2) + Head To Head Adjustments (47.5)<br />

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
|           95 |       35 | 2024-07-31 | MIBR              | L   | 1.000      | -            | -                | -                | -         |    -5.66 | doc, gafolo, koala, pepe, rdnzao |
|           94 |       44 | 2024-07-31 | Solid             | W   | 1.000      | 0.371        | -                | 0.844 (0.313)    | 0 (0.000) |    12.57 | doc, gafolo, koala, pepe, rdnzao |
|           93 |       78 | 2024-07-30 | Hype              | W   | 1.000      | -            | -                | -                | 0 (0.000) |    11.01 | doc, gafolo, koala, pepe, rdnzao |
|           92 |      152 | 2024-07-28 | Bad News Chickens | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.54 | doc, gafolo, koala, pepe, rdnzao |
|           91 |      200 | 2024-07-26 | Imperial          | L   | 1.000      | -            | -                | -                | -         |    -9.27 | doc, gafolo, koala, pepe, rdnzao |
|           90 |      227 | 2024-07-25 | BESTIA            | W   | 1.000      | -            | -                | -                | 0 (0.000) |    15.87 | doc, gafolo, koala, pepe, rdnzao |
|           89 |      234 | 2024-07-25 | Patins da Ferrari | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.03 | doc, gafolo, koala, pepe, rdnzao |
|           88 |      276 | 2024-07-24 | Bad News Chickens | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.46 | doc, gafolo, koala, pepe, rdnzao |
|           87 |      283 | 2024-07-24 | Yawara            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.00 | doc, gafolo, koala, pepe, rdnzao |
|           86 |      303 | 2024-07-23 | ODDIK             | L   | 1.000      | -            | -                | -                | -         |   -13.76 | doc, gafolo, koala, pepe, rdnzao |
|           85 |      306 | 2024-07-23 | W7M               | W   | 1.000      | -            | -                | -                | 0 (0.000) |    10.83 | doc, gafolo, koala, pepe, rdnzao |
|           84 |      395 | 2024-07-20 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |    -7.70 | doc, gafolo, koala, pepe, rdnzao |
|           83 |      450 | 2024-07-19 | Hype              | W   | 1.000      | -            | -                | -                | 0 (0.000) |    13.51 | doc, gafolo, koala, pepe, rdnzao |
|           82 |      477 | 2024-07-18 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |    -8.10 | doc, gafolo, koala, pepe, rdnzao |
|           81 |      479 | 2024-07-18 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |    -8.67 | doc, gafolo, koala, pepe, rdnzao |
|           80 |      545 | 2024-07-17 | ODDIK             | W   | 1.000      | 0.450        | 0.096 (0.043)    | 0.822 (0.370)    | 0 (0.000) |    18.55 | doc, gafolo, koala, pepe, rdnzao |
|           79 |      555 | 2024-07-17 | ODDIK             | W   | 1.000      | 0.450        | 0.096 (0.043)    | 0.822 (0.370)    | -         |    20.18 | doc, gafolo, koala, pepe, rdnzao |
|           78 |      609 | 2024-07-16 | RED Canids        | L   | 1.000      | -            | -                | -                | -         |   -10.09 | doc, gafolo, koala, pepe, rdnzao |
|           77 |      616 | 2024-07-16 | RED Canids        | L   | 1.000      | -            | -                | -                | -         |   -10.91 | doc, gafolo, koala, pepe, rdnzao |
|           76 |      666 | 2024-07-15 | KRÜ               | L   | 1.000      | -            | -                | -                | -         |   -19.39 | doc, gafolo, koala, pepe, rdnzao |
|           75 |      669 | 2024-07-15 | KRÜ               | W   | 1.000      | -            | -                | -                | -         |    11.80 | doc, gafolo, koala, pepe, rdnzao |
|           74 |      743 | 2024-07-11 | Bounty Hunters    | L   | 1.000      | -            | -                | -                | -         |   -16.61 | doc, gafolo, koala, pepe, rdnzao |
|           73 |      758 | 2024-07-10 | BESTIA            | W   | 1.000      | 0.371        | 0.089 (0.033)    | 0.738 (0.274)    | -         |    17.06 | doc, gafolo, koala, pepe, rdnzao |
|           72 |      778 | 2024-07-09 | KRÜ               | L   | 1.000      | -            | -                | -                | -         |   -19.98 | doc, gafolo, koala, pepe, rdnzao |
|           71 |      800 | 2024-07-08 | Patins da Ferrari | W   | 1.000      | -            | -                | -                | -         |     9.17 | doc, gafolo, koala, pepe, rdnzao |
|           70 |      837 | 2024-06-30 | Patins da Ferrari | L   | 0.987      | -            | -                | -                | -         |   -22.11 | doc, gafolo, koala, pepe, rdnzao |
|           69 |      851 | 2024-06-28 | KRÜ               | W   | 0.974      | -            | -                | -                | -         |    10.38 | doc, gafolo, koala, pepe, rdnzao |
|           68 |      852 | 2024-06-28 | Bounty Hunters    | L   | 0.973      | -            | -                | -                | -         |   -18.62 | doc, gafolo, koala, pepe, rdnzao |
|           67 |      856 | 2024-06-27 | Galorys           | W   | 0.968      | -            | -                | -                | -         |     9.29 | doc, gafolo, koala, pepe, rdnzao |
|           66 |      859 | 2024-06-27 | inSanitY          | L   | 0.966      | -            | -                | -                | -         |   -16.25 | doc, gafolo, koala, pepe, rdnzao |
|           65 |      950 | 2024-06-14 | Fluxo             | L   | 0.881      | -            | -                | -                | -         |   -11.83 | doc, gafolo, koala, pepe, rdnzao |
|           64 |     1072 | 2024-06-10 | Vikings KR        | W   | 0.853      | -            | -                | -                | -         |     5.66 | doc, gafolo, koala, pepe, rdnzao |
|           63 |     1105 | 2024-06-09 | paiN              | L   | 0.847      | -            | -                | -                | -         |    -6.21 | doc, gafolo, koala, pepe, rdnzao |
|           62 |     1124 | 2024-06-09 | BESTIA            | W   | 0.846      | 0.450        | 0.089 (0.034)    | 0.738 (0.281)    | -         |    13.09 | doc, gafolo, koala, pepe, rdnzao |
|           61 |     1178 | 2024-06-08 | Hype              | W   | 0.840      | -            | -                | -                | -         |     9.97 | doc, gafolo, koala, pepe, rdnzao |
|           60 |     1193 | 2024-06-08 | Patins da Ferrari | L   | 0.839      | -            | -                | -                | -         |   -20.42 | doc, gafolo, koala, pepe, rdnzao |
|           59 |     1224 | 2024-06-07 | 9z                | L   | 0.834      | -            | -                | -                | -         |    -6.51 | doc, gafolo, koala, pepe, rdnzao |
|           58 |     1225 | 2024-06-07 | RED Canids        | W   | 0.834      | 0.450        | 0.075 (0.028)    | 0.754 (0.283)    | -         |    16.15 | doc, gafolo, koala, pepe, rdnzao |
|           57 |     1287 | 2024-06-06 | paiN              | W   | 0.828      | 0.450        | 0.300 (0.112)    | 0.801 (0.299)    | -         |    20.51 | doc, gafolo, koala, pepe, rdnzao |
|           56 |     1289 | 2024-06-06 | Hype              | L   | 0.828      | -            | -                | -                | -         |   -16.79 | doc, gafolo, koala, pepe, rdnzao |
|           55 |     1359 | 2024-06-05 | Imperial          | L   | 0.821      | -            | -                | -                | -         |    -5.07 | doc, gafolo, koala, pepe, rdnzao |
|           54 |     1410 | 2024-06-04 | BESTIA            | W   | 0.815      | 0.450        | 0.089 (0.033)    | 0.738 (0.271)    | -         |    14.36 | doc, gafolo, koala, pepe, rdnzao |
|           53 |     1740 | 2024-05-22 | Imperial          | W   | 0.727      | 0.450        | 0.239 (0.078)    | 0.719 (0.235)    | -         |    18.76 | doc, drg, gafolo, pepe, rdnzao   |
|           52 |     1744 | 2024-05-22 | Imperial          | L   | 0.727      | -            | -                | -                | -         |    -3.98 | doc, drg, gafolo, pepe, rdnzao   |
|           51 |     1783 | 2024-05-21 | Case              | L   | 0.722      | -            | -                | -                | -         |   -13.90 | doc, drg, gafolo, pepe, rdnzao   |
|           50 |     1784 | 2024-05-21 | Case              | W   | 0.721      | -            | -                | -                | -         |     8.87 | doc, drg, gafolo, pepe, rdnzao   |
|           49 |     1788 | 2024-05-21 | RED Canids        | W   | 0.721      | 0.450        | 0.075 (0.024)    | 0.754 (0.245)    | -         |    14.77 | doc, drg, gafolo, pepe, rdnzao   |
|           48 |     1790 | 2024-05-21 | RED Canids        | L   | 0.721      | -            | -                | -                | -         |    -7.93 | doc, drg, gafolo, pepe, rdnzao   |
|           47 |     1935 | 2024-05-17 | ODDIK             | L   | 0.693      | -            | -                | -                | -         |   -12.62 | doc, drg, gafolo, rdnzao, togs   |
|           46 |     1960 | 2024-05-16 | W7M               | W   | 0.688      | -            | -                | -                | -         |     5.60 | doc, drg, gafolo, rdnzao, togs   |
|           45 |     1963 | 2024-05-16 | W7M               | W   | 0.688      | -            | -                | -                | -         |     5.88 | doc, drg, gafolo, rdnzao, togs   |
|           44 |     1968 | 2024-05-16 | Hype              | W   | 0.687      | -            | -                | -                | -         |     7.86 | doc, drg, gafolo, rdnzao, togs   |
|           43 |     2007 | 2024-05-15 | Vikings KR        | W   | 0.682      | -            | -                | -                | -         |     5.97 | doc, drg, gafolo, rdnzao, togs   |
|           42 |     2015 | 2024-05-15 | 9z                | L   | 0.681      | -            | -                | -                | -         |    -5.15 | doc, drg, gafolo, rdnzao, togs   |
|           41 |     2080 | 2024-05-14 | Fluxo             | L   | 0.674      | -            | -                | -                | -         |    -7.31 | doc, drg, gafolo, rdnzao, togs   |
|           40 |     2108 | 2024-05-13 | RED Canids        | W   | 0.667      | -            | -                | -                | -         |    12.64 | doc, drg, gafolo, rdnzao, togs   |
|           39 |     2117 | 2024-05-13 | W7M               | W   | 0.666      | -            | -                | -                | -         |     6.32 | doc, drg, gafolo, rdnzao, togs   |
|           38 |     2165 | 2024-05-11 | W7M               | W   | 0.653      | -            | -                | -                | -         |     6.51 | doc, drg, gafolo, rdnzao, togs   |
|           37 |     2209 | 2024-05-09 | BESTIA            | L   | 0.641      | -            | -                | -                | -         |   -11.28 | doc, drg, gafolo, rdnzao, togs   |
|           36 |     2231 | 2024-05-08 | 9z                | L   | 0.635      | -            | -                | -                | -         |    -5.38 | doc, drg, gafolo, rdnzao, togs   |
|           35 |     2269 | 2024-05-06 | BESTIA            | W   | 0.621      | 0.435        | 0.089 (0.024)    | -                | -         |     8.43 | doc, drg, gafolo, rdnzao, togs   |
|           34 |     2882 | 2024-04-11 | paiN              | L   | 0.454      | -            | -                | -                | -         |    -1.44 | doc, drg, gafolo, rdnzao, togs   |
|           33 |     3146 | 2024-04-03 | 2GAME             | W   | 0.401      | -            | -                | -                | -         |     1.96 | doc, drg, gafolo, rdnzao, togs   |
|           32 |     3149 | 2024-04-03 | 2GAME             | W   | 0.401      | -            | -                | -                | -         |     1.99 | doc, drg, gafolo, rdnzao, togs   |
|           31 |     3530 | 2024-03-14 | MIBR              | L   | 0.268      | -            | -                | -                | -         |    -0.75 | doc, drg, gafolo, rdnzao, togs   |
|           30 |     3533 | 2024-03-14 | MIBR              | L   | 0.268      | -            | -                | -                | -         |    -0.76 | doc, drg, gafolo, rdnzao, togs   |
|           29 |     3564 | 2024-03-13 | Yawara            | W   | 0.261      | -            | -                | -                | -         |     0.58 | doc, drg, gafolo, rdnzao, togs   |
|           28 |     3568 | 2024-03-13 | ODDIK             | W   | 0.261      | -            | -                | -                | -         |     4.44 | doc, drg, gafolo, rdnzao, togs   |
|           27 |     3641 | 2024-03-11 | Fluxo             | L   | 0.246      | -            | -                | -                | -         |    -3.12 | doc, drg, gafolo, rdnzao, togs   |
|           26 |     3670 | 2024-03-09 | Case              | L   | 0.234      | -            | -                | -                | -         |    -4.20 | doc, drg, gafolo, rdnzao, togs   |
|           25 |     3734 | 2024-03-07 | Corinthians       | W   | 0.219      | -            | -                | -                | -         |     0.48 | doc, drg, gafolo, rdnzao, togs   |
|           24 |     3788 | 2024-03-05 | Solid             | W   | 0.207      | -            | -                | -                | -         |     2.52 | doc, drg, gafolo, rdnzao, togs   |
|           23 |     3793 | 2024-03-05 | 9z                | W   | 0.207      | -            | -                | -                | -         |     5.17 | doc, drg, gafolo, rdnzao, togs   |
|           22 |     3794 | 2024-03-05 | 9z                | W   | 0.207      | -            | -                | -                | -         |     5.23 | doc, drg, gafolo, rdnzao, togs   |
|           21 |     3798 | 2024-03-05 | Solid             | W   | 0.207      | -            | -                | -                | -         |     2.65 | doc, drg, gafolo, rdnzao, togs   |
|           20 |     3997 | 2024-02-24 | Galorys           | W   | 0.142      | -            | -                | -                | -         |     1.76 | doc, drg, gafolo, rdnzao, togs   |
|           19 |     4005 | 2024-02-24 | Galorys           | W   | 0.141      | -            | -                | -                | -         |     1.78 | doc, drg, gafolo, rdnzao, togs   |
|           18 |     4009 | 2024-02-24 | Fluxo             | L   | 0.141      | -            | -                | -                | -         |    -1.78 | doc, drg, gafolo, rdnzao, togs   |
|           17 |     4067 | 2024-02-21 | Corinthians       | W   | 0.122      | -            | -                | -                | -         |     0.29 | doc, drg, gafolo, rdnzao, togs   |
|           16 |     4072 | 2024-02-21 | Corinthians       | L   | 0.121      | -            | -                | -                | -         |    -3.55 | doc, drg, gafolo, rdnzao, togs   |
|           15 |     4073 | 2024-02-21 | Case              | W   | 0.121      | -            | -                | -                | -         |     1.80 | doc, drg, gafolo, rdnzao, togs   |
|           14 |     4078 | 2024-02-21 | Galorys           | W   | 0.119      | -            | -                | -                | -         |     1.55 | doc, drg, gafolo, rdnzao, togs   |
|           13 |     4103 | 2024-02-20 | Flamengo          | L   | 0.114      | -            | -                | -                | -         |    -3.36 | doc, drg, gafolo, rdnzao, togs   |
|           12 |     4108 | 2024-02-20 | Case              | W   | 0.113      | -            | -                | -                | -         |     1.68 | doc, drg, gafolo, rdnzao, togs   |
|           11 |     4132 | 2024-02-19 | Solid             | W   | 0.106      | -            | -                | -                | -         |     1.37 | doc, drg, gafolo, rdnzao, togs   |
|           10 |     4146 | 2024-02-18 | Galorys           | W   | 0.102      | -            | -                | -                | -         |     1.33 | doc, drg, gafolo, rdnzao, togs   |
|            9 |     4168 | 2024-02-17 | W7M               | L   | 0.095      | -            | -                | -                | -         |    -1.91 | doc, drg, gafolo, rdnzao, togs   |
|            8 |     4173 | 2024-02-17 | Galorys           | L   | 0.094      | -            | -                | -                | -         |    -1.75 | doc, drg, gafolo, rdnzao, togs   |
|            7 |     4209 | 2024-02-16 | W7M               | W   | 0.086      | -            | -                | -                | -         |     0.98 | doc, drg, gafolo, rdnzao, togs   |
|            6 |     4227 | 2024-02-15 | Case              | L   | 0.081      | -            | -                | -                | -         |    -1.35 | doc, drg, gafolo, rdnzao, togs   |
|            5 |     4233 | 2024-02-15 | Fluxo             | L   | 0.080      | -            | -                | -                | -         |    -1.03 | doc, drg, gafolo, rdnzao, togs   |
|            4 |     4234 | 2024-02-15 | Fluxo             | L   | 0.080      | -            | -                | -                | -         |    -1.03 | doc, drg, gafolo, rdnzao, togs   |
|            3 |     4262 | 2024-02-14 | Hype              | W   | 0.075      | -            | -                | -                | -         |     0.09 | doc, drg, gafolo, rdnzao, togs   |
|            2 |     4273 | 2024-02-14 | Galorys           | W   | 0.073      | -            | -                | -                | -         |     0.94 | doc, drg, gafolo, rdnzao, togs   |
|            1 |     4325 | 2024-02-12 | Solid             | W   | 0.061      | -            | -                | -                | -         |     0.79 | doc, drg, gafolo, rdnzao, togs   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($9,458.79)
- Divide that value by the 5th highest value among all rosters ($326,952.13)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-28 |      0.973 | $500.00        | $486.63         |
| 2024-06-16 |      0.893 | $2,500.00      | $2,233.33       |
| 2024-06-10 |      0.855 | $750.00        | $640.95         |
| 2024-06-09 |      0.847 | $5,000.00      | $4,237.04       |
| 2024-05-19 |      0.707 | $1,000.00      | $706.67         |
| 2024-02-25 |      0.147 | $5,000.00      | $736.11         |
| 2024-02-21 |      0.119 | $3,500.00      | $418.06         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
