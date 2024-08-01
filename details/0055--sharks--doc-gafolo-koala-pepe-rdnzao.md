### Roster Details<br />
Team Name: Sharks<br />
Roster: doc, gafolo, koala, pepe, rdnzao<br />
Global Rank: [55](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [15]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1021.5<br />
<br />
Final Rank Value (1021.5) = Starting Rank Value (974.0) + Head To Head Adjustments (47.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.394[<sup>1</sup>](#table2)
- Bounty Collected: 0.427[<sup>2</sup>](#table1)
- Opponent Network: 0.294[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.279<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 974.0
- 400 + ( ( 0.279 - 0.000 ) / ( 0.777 - 0.000 ) ) * 1600 = 974.0


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
|           95 |       28 | 2024-07-31 | MIBR              | L   | 1.000      | -            | -                | -                | -         |    -5.61 | doc, gafolo, koala, pepe, rdnzao |
|           94 |       37 | 2024-07-31 | Solid             | W   | 1.000      | 0.371        | -                | 0.843 (0.312)    | 0 (0.000) |    12.56 | doc, gafolo, koala, pepe, rdnzao |
|           93 |       71 | 2024-07-30 | Hype              | W   | 1.000      | -            | -                | -                | 0 (0.000) |    11.00 | doc, gafolo, koala, pepe, rdnzao |
|           92 |      146 | 2024-07-28 | Bad News Chickens | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.53 | doc, gafolo, koala, pepe, rdnzao |
|           91 |      194 | 2024-07-26 | Imperial          | L   | 1.000      | -            | -                | -                | -         |    -9.25 | doc, gafolo, koala, pepe, rdnzao |
|           90 |      221 | 2024-07-25 | BESTIA            | W   | 1.000      | -            | -                | -                | 0 (0.000) |    15.88 | doc, gafolo, koala, pepe, rdnzao |
|           89 |      228 | 2024-07-25 | Patins da Ferrari | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.02 | doc, gafolo, koala, pepe, rdnzao |
|           88 |      270 | 2024-07-24 | Bad News Chickens | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.45 | doc, gafolo, koala, pepe, rdnzao |
|           87 |      278 | 2024-07-24 | Yawara            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.00 | doc, gafolo, koala, pepe, rdnzao |
|           86 |      297 | 2024-07-23 | ODDIK             | L   | 1.000      | -            | -                | -                | -         |   -13.76 | doc, gafolo, koala, pepe, rdnzao |
|           85 |      300 | 2024-07-23 | W7M               | W   | 1.000      | -            | -                | -                | 0 (0.000) |    10.83 | doc, gafolo, koala, pepe, rdnzao |
|           84 |      389 | 2024-07-20 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |    -7.69 | doc, gafolo, koala, pepe, rdnzao |
|           83 |      444 | 2024-07-19 | Hype              | W   | 1.000      | -            | -                | -                | 0 (0.000) |    13.50 | doc, gafolo, koala, pepe, rdnzao |
|           82 |      471 | 2024-07-18 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |    -8.09 | doc, gafolo, koala, pepe, rdnzao |
|           81 |      473 | 2024-07-18 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |    -8.67 | doc, gafolo, koala, pepe, rdnzao |
|           80 |      539 | 2024-07-17 | ODDIK             | W   | 1.000      | 0.450        | 0.096 (0.043)    | 0.822 (0.370)    | 0 (0.000) |    18.55 | doc, gafolo, koala, pepe, rdnzao |
|           79 |      549 | 2024-07-17 | ODDIK             | W   | 1.000      | 0.450        | 0.096 (0.043)    | 0.822 (0.370)    | -         |    20.18 | doc, gafolo, koala, pepe, rdnzao |
|           78 |      603 | 2024-07-16 | RED Canids        | L   | 1.000      | -            | -                | -                | -         |   -10.08 | doc, gafolo, koala, pepe, rdnzao |
|           77 |      610 | 2024-07-16 | RED Canids        | L   | 1.000      | -            | -                | -                | -         |   -10.90 | doc, gafolo, koala, pepe, rdnzao |
|           76 |      660 | 2024-07-15 | KRÜ               | L   | 1.000      | -            | -                | -                | -         |   -19.39 | doc, gafolo, koala, pepe, rdnzao |
|           75 |      663 | 2024-07-15 | KRÜ               | W   | 1.000      | -            | -                | -                | -         |    11.80 | doc, gafolo, koala, pepe, rdnzao |
|           74 |      737 | 2024-07-11 | Bounty Hunters    | L   | 1.000      | -            | -                | -                | -         |   -16.61 | doc, gafolo, koala, pepe, rdnzao |
|           73 |      752 | 2024-07-10 | BESTIA            | W   | 1.000      | 0.371        | 0.089 (0.033)    | 0.738 (0.273)    | -         |    17.06 | doc, gafolo, koala, pepe, rdnzao |
|           72 |      772 | 2024-07-09 | KRÜ               | L   | 1.000      | -            | -                | -                | -         |   -19.98 | doc, gafolo, koala, pepe, rdnzao |
|           71 |      794 | 2024-07-08 | Patins da Ferrari | W   | 1.000      | -            | -                | -                | -         |     9.16 | doc, gafolo, koala, pepe, rdnzao |
|           70 |      831 | 2024-06-30 | Patins da Ferrari | L   | 0.989      | -            | -                | -                | -         |   -22.15 | doc, gafolo, koala, pepe, rdnzao |
|           69 |      845 | 2024-06-28 | KRÜ               | W   | 0.976      | -            | -                | -                | -         |    10.39 | doc, gafolo, koala, pepe, rdnzao |
|           68 |      846 | 2024-06-28 | Bounty Hunters    | L   | 0.975      | -            | -                | -                | -         |   -18.66 | doc, gafolo, koala, pepe, rdnzao |
|           67 |      850 | 2024-06-27 | Galorys           | W   | 0.970      | -            | -                | -                | -         |     9.29 | doc, gafolo, koala, pepe, rdnzao |
|           66 |      853 | 2024-06-27 | inSanitY          | L   | 0.968      | -            | -                | -                | -         |   -16.28 | doc, gafolo, koala, pepe, rdnzao |
|           65 |      944 | 2024-06-14 | Fluxo             | L   | 0.882      | -            | -                | -                | -         |   -11.85 | doc, gafolo, koala, pepe, rdnzao |
|           64 |     1066 | 2024-06-10 | Vikings KR        | W   | 0.854      | -            | -                | -                | -         |     5.66 | doc, gafolo, koala, pepe, rdnzao |
|           63 |     1099 | 2024-06-09 | paiN              | L   | 0.848      | -            | -                | -                | -         |    -6.21 | doc, gafolo, koala, pepe, rdnzao |
|           62 |     1118 | 2024-06-09 | BESTIA            | W   | 0.847      | 0.450        | 0.089 (0.034)    | 0.738 (0.281)    | -         |    13.11 | doc, gafolo, koala, pepe, rdnzao |
|           61 |     1172 | 2024-06-08 | Hype              | W   | 0.842      | -            | -                | -                | -         |     9.98 | doc, gafolo, koala, pepe, rdnzao |
|           60 |     1187 | 2024-06-08 | Patins da Ferrari | L   | 0.841      | -            | -                | -                | -         |   -20.47 | doc, gafolo, koala, pepe, rdnzao |
|           59 |     1218 | 2024-06-07 | 9z                | L   | 0.836      | -            | -                | -                | -         |    -6.54 | doc, gafolo, koala, pepe, rdnzao |
|           58 |     1219 | 2024-06-07 | RED Canids        | W   | 0.836      | 0.450        | 0.075 (0.028)    | 0.753 (0.284)    | -         |    16.18 | doc, gafolo, koala, pepe, rdnzao |
|           57 |     1281 | 2024-06-06 | paiN              | W   | 0.829      | 0.450        | 0.300 (0.112)    | 0.801 (0.299)    | -         |    20.56 | doc, gafolo, koala, pepe, rdnzao |
|           56 |     1283 | 2024-06-06 | Hype              | L   | 0.829      | -            | -                | -                | -         |   -16.83 | doc, gafolo, koala, pepe, rdnzao |
|           55 |     1353 | 2024-06-05 | Imperial          | L   | 0.823      | -            | -                | -                | -         |    -5.06 | doc, gafolo, koala, pepe, rdnzao |
|           54 |     1404 | 2024-06-04 | BESTIA            | W   | 0.816      | 0.450        | 0.089 (0.033)    | 0.738 (0.271)    | -         |    14.39 | doc, gafolo, koala, pepe, rdnzao |
|           53 |     1734 | 2024-05-22 | Imperial          | W   | 0.729      | 0.450        | 0.240 (0.079)    | 0.719 (0.236)    | -         |    18.82 | doc, drg, gafolo, pepe, rdnzao   |
|           52 |     1738 | 2024-05-22 | Imperial          | L   | 0.728      | -            | -                | -                | -         |    -3.98 | doc, drg, gafolo, pepe, rdnzao   |
|           51 |     1777 | 2024-05-21 | Case              | L   | 0.723      | -            | -                | -                | -         |   -13.94 | doc, drg, gafolo, pepe, rdnzao   |
|           50 |     1778 | 2024-05-21 | Case              | W   | 0.723      | -            | -                | -                | -         |     8.89 | doc, drg, gafolo, pepe, rdnzao   |
|           49 |     1782 | 2024-05-21 | RED Canids        | W   | 0.723      | 0.450        | 0.075 (0.024)    | 0.753 (0.245)    | -         |    14.81 | doc, drg, gafolo, pepe, rdnzao   |
|           48 |     1784 | 2024-05-21 | RED Canids        | L   | 0.723      | -            | -                | -                | -         |    -7.94 | doc, drg, gafolo, pepe, rdnzao   |
|           47 |     1929 | 2024-05-17 | ODDIK             | L   | 0.695      | -            | -                | -                | -         |   -12.65 | doc, drg, gafolo, rdnzao, togs   |
|           46 |     1954 | 2024-05-16 | W7M               | W   | 0.690      | -            | -                | -                | -         |     5.61 | doc, drg, gafolo, rdnzao, togs   |
|           45 |     1957 | 2024-05-16 | W7M               | W   | 0.689      | -            | -                | -                | -         |     5.88 | doc, drg, gafolo, rdnzao, togs   |
|           44 |     1962 | 2024-05-16 | Hype              | W   | 0.688      | -            | -                | -                | -         |     7.87 | doc, drg, gafolo, rdnzao, togs   |
|           43 |     2001 | 2024-05-15 | Vikings KR        | W   | 0.683      | -            | -                | -                | -         |     5.97 | doc, drg, gafolo, rdnzao, togs   |
|           42 |     2009 | 2024-05-15 | 9z                | L   | 0.682      | -            | -                | -                | -         |    -5.17 | doc, drg, gafolo, rdnzao, togs   |
|           41 |     2074 | 2024-05-14 | Fluxo             | L   | 0.675      | -            | -                | -                | -         |    -7.32 | doc, drg, gafolo, rdnzao, togs   |
|           40 |     2102 | 2024-05-13 | RED Canids        | W   | 0.669      | -            | -                | -                | -         |    12.68 | doc, drg, gafolo, rdnzao, togs   |
|           39 |     2111 | 2024-05-13 | W7M               | W   | 0.668      | -            | -                | -                | -         |     6.33 | doc, drg, gafolo, rdnzao, togs   |
|           38 |     2159 | 2024-05-11 | W7M               | W   | 0.655      | -            | -                | -                | -         |     6.53 | doc, drg, gafolo, rdnzao, togs   |
|           37 |     2203 | 2024-05-09 | BESTIA            | L   | 0.643      | -            | -                | -                | -         |   -11.31 | doc, drg, gafolo, rdnzao, togs   |
|           36 |     2225 | 2024-05-08 | 9z                | L   | 0.636      | -            | -                | -                | -         |    -5.40 | doc, drg, gafolo, rdnzao, togs   |
|           35 |     2263 | 2024-05-06 | BESTIA            | W   | 0.623      | 0.435        | 0.089 (0.024)    | -                | -         |     8.44 | doc, drg, gafolo, rdnzao, togs   |
|           34 |     2876 | 2024-04-11 | paiN              | L   | 0.456      | -            | -                | -                | -         |    -1.44 | doc, drg, gafolo, rdnzao, togs   |
|           33 |     3140 | 2024-04-03 | 2GAME             | W   | 0.403      | -            | -                | -                | -         |     1.96 | doc, drg, gafolo, rdnzao, togs   |
|           32 |     3143 | 2024-04-03 | 2GAME             | W   | 0.403      | -            | -                | -                | -         |     2.00 | doc, drg, gafolo, rdnzao, togs   |
|           31 |     3524 | 2024-03-14 | MIBR              | L   | 0.270      | -            | -                | -                | -         |    -0.75 | doc, drg, gafolo, rdnzao, togs   |
|           30 |     3527 | 2024-03-14 | MIBR              | L   | 0.270      | -            | -                | -                | -         |    -0.76 | doc, drg, gafolo, rdnzao, togs   |
|           29 |     3558 | 2024-03-13 | Yawara            | W   | 0.263      | -            | -                | -                | -         |     0.58 | doc, drg, gafolo, rdnzao, togs   |
|           28 |     3562 | 2024-03-13 | ODDIK             | W   | 0.263      | -            | -                | -                | -         |     4.47 | doc, drg, gafolo, rdnzao, togs   |
|           27 |     3635 | 2024-03-11 | Fluxo             | L   | 0.247      | -            | -                | -                | -         |    -3.14 | doc, drg, gafolo, rdnzao, togs   |
|           26 |     3664 | 2024-03-09 | Case              | L   | 0.236      | -            | -                | -                | -         |    -4.24 | doc, drg, gafolo, rdnzao, togs   |
|           25 |     3728 | 2024-03-07 | Corinthians       | W   | 0.221      | -            | -                | -                | -         |     0.48 | doc, drg, gafolo, rdnzao, togs   |
|           24 |     3782 | 2024-03-05 | Solid             | W   | 0.209      | -            | -                | -                | -         |     2.54 | doc, drg, gafolo, rdnzao, togs   |
|           23 |     3787 | 2024-03-05 | 9z                | W   | 0.208      | -            | -                | -                | -         |     5.21 | doc, drg, gafolo, rdnzao, togs   |
|           22 |     3788 | 2024-03-05 | 9z                | W   | 0.208      | -            | -                | -                | -         |     5.27 | doc, drg, gafolo, rdnzao, togs   |
|           21 |     3792 | 2024-03-05 | Solid             | W   | 0.208      | -            | -                | -                | -         |     2.67 | doc, drg, gafolo, rdnzao, togs   |
|           20 |     3991 | 2024-02-24 | Galorys           | W   | 0.143      | -            | -                | -                | -         |     1.78 | doc, drg, gafolo, rdnzao, togs   |
|           19 |     3999 | 2024-02-24 | Galorys           | W   | 0.143      | -            | -                | -                | -         |     1.80 | doc, drg, gafolo, rdnzao, togs   |
|           18 |     4003 | 2024-02-24 | Fluxo             | L   | 0.142      | -            | -                | -                | -         |    -1.80 | doc, drg, gafolo, rdnzao, togs   |
|           17 |     4061 | 2024-02-21 | Corinthians       | W   | 0.123      | -            | -                | -                | -         |     0.29 | doc, drg, gafolo, rdnzao, togs   |
|           16 |     4066 | 2024-02-21 | Corinthians       | L   | 0.123      | -            | -                | -                | -         |    -3.60 | doc, drg, gafolo, rdnzao, togs   |
|           15 |     4067 | 2024-02-21 | Case              | W   | 0.122      | -            | -                | -                | -         |     1.82 | doc, drg, gafolo, rdnzao, togs   |
|           14 |     4072 | 2024-02-21 | Galorys           | W   | 0.121      | -            | -                | -                | -         |     1.57 | doc, drg, gafolo, rdnzao, togs   |
|           13 |     4097 | 2024-02-20 | Flamengo          | L   | 0.116      | -            | -                | -                | -         |    -3.41 | doc, drg, gafolo, rdnzao, togs   |
|           12 |     4102 | 2024-02-20 | Case              | W   | 0.114      | -            | -                | -                | -         |     1.71 | doc, drg, gafolo, rdnzao, togs   |
|           11 |     4126 | 2024-02-19 | Solid             | W   | 0.108      | -            | -                | -                | -         |     1.39 | doc, drg, gafolo, rdnzao, togs   |
|           10 |     4140 | 2024-02-18 | Galorys           | W   | 0.103      | -            | -                | -                | -         |     1.35 | doc, drg, gafolo, rdnzao, togs   |
|            9 |     4162 | 2024-02-17 | W7M               | L   | 0.096      | -            | -                | -                | -         |    -1.94 | doc, drg, gafolo, rdnzao, togs   |
|            8 |     4167 | 2024-02-17 | Galorys           | L   | 0.095      | -            | -                | -                | -         |    -1.79 | doc, drg, gafolo, rdnzao, togs   |
|            7 |     4203 | 2024-02-16 | W7M               | W   | 0.088      | -            | -                | -                | -         |     1.00 | doc, drg, gafolo, rdnzao, togs   |
|            6 |     4221 | 2024-02-15 | Case              | L   | 0.083      | -            | -                | -                | -         |    -1.38 | doc, drg, gafolo, rdnzao, togs   |
|            5 |     4227 | 2024-02-15 | Fluxo             | L   | 0.082      | -            | -                | -                | -         |    -1.05 | doc, drg, gafolo, rdnzao, togs   |
|            4 |     4228 | 2024-02-15 | Fluxo             | L   | 0.081      | -            | -                | -                | -         |    -1.05 | doc, drg, gafolo, rdnzao, togs   |
|            3 |     4256 | 2024-02-14 | Hype              | W   | 0.077      | -            | -                | -                | -         |     0.09 | doc, drg, gafolo, rdnzao, togs   |
|            2 |     4267 | 2024-02-14 | Galorys           | W   | 0.075      | -            | -                | -                | -         |     0.96 | doc, drg, gafolo, rdnzao, togs   |
|            1 |     4319 | 2024-02-12 | Solid             | W   | 0.063      | -            | -                | -                | -         |     0.81 | doc, drg, gafolo, rdnzao, togs   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($9,489.21)
- Divide that value by the 5th highest value among all rosters ($327,422.13)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-28 |      0.975 | $500.00        | $487.47         |
| 2024-06-16 |      0.895 | $2,500.00      | $2,237.50       |
| 2024-06-10 |      0.856 | $750.00        | $642.20         |
| 2024-06-09 |      0.849 | $5,000.00      | $4,245.37       |
| 2024-05-19 |      0.708 | $1,000.00      | $708.33         |
| 2024-02-25 |      0.149 | $5,000.00      | $744.44         |
| 2024-02-21 |      0.121 | $3,500.00      | $423.89         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
