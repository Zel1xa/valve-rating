### Roster Details<br />
Team Name: Sharks<br />
Roster: doc, gafolo, koala, pepe, rdnzao<br />
Global Rank: [56](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [15]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1009.2<br />
<br />
Final Rank Value (1009.2) = Starting Rank Value (971.8) + Head To Head Adjustments (37.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.398[<sup>1</sup>](#table2)
- Bounty Collected: 0.426[<sup>2</sup>](#table1)
- Opponent Network: 0.294[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.279<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 971.8
- 400 + ( ( 0.279 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 971.8


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
|           93 |       38 | 2024-08-02 | paiN              | L   | 1.000      | -            | -                | -                | -         |    -3.60 | doc, gafolo, koala, pepe, rdnzao |
|           92 |       56 | 2024-08-01 | Hype              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.03 | doc, gafolo, koala, pepe, rdnzao |
|           91 |       61 | 2024-08-01 | paiN              | L   | 1.000      | -            | -                | -                | -         |    -3.57 | doc, gafolo, koala, pepe, rdnzao |
|           90 |       92 | 2024-07-31 | MIBR              | L   | 1.000      | -            | -                | -                | -         |    -4.55 | doc, gafolo, koala, pepe, rdnzao |
|           89 |      102 | 2024-07-31 | Solid             | W   | 1.000      | 0.371        | -                | 0.863 (0.320)    | 0 (0.000) |    12.79 | doc, gafolo, koala, pepe, rdnzao |
|           88 |      135 | 2024-07-30 | Hype              | W   | 1.000      | -            | -                | -                | 0 (0.000) |    10.22 | doc, gafolo, koala, pepe, rdnzao |
|           87 |      208 | 2024-07-28 | Bad News Chickens | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.67 | doc, gafolo, koala, pepe, rdnzao |
|           86 |      256 | 2024-07-26 | Imperial          | L   | 1.000      | -            | -                | -                | -         |    -8.52 | doc, gafolo, koala, pepe, rdnzao |
|           85 |      283 | 2024-07-25 | BESTIA            | W   | 1.000      | -            | -                | -                | 0 (0.000) |    16.08 | doc, gafolo, koala, pepe, rdnzao |
|           84 |      290 | 2024-07-25 | Patins da Ferrari | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.61 | doc, gafolo, koala, pepe, rdnzao |
|           83 |      332 | 2024-07-24 | Bad News Chickens | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.63 | doc, gafolo, koala, pepe, rdnzao |
|           82 |      339 | 2024-07-24 | Yawara            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.17 | doc, gafolo, koala, pepe, rdnzao |
|           81 |      359 | 2024-07-23 | ODDIK             | L   | 1.000      | -            | -                | -                | -         |   -14.68 | doc, gafolo, koala, pepe, rdnzao |
|           80 |      362 | 2024-07-23 | W7M               | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.40 | doc, gafolo, koala, pepe, rdnzao |
|           79 |      448 | 2024-07-20 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |    -7.62 | doc, gafolo, koala, pepe, rdnzao |
|           78 |      501 | 2024-07-19 | Hype              | W   | 1.000      | -            | -                | -                | 0 (0.000) |    12.39 | doc, gafolo, koala, pepe, rdnzao |
|           77 |      526 | 2024-07-18 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |    -8.05 | doc, gafolo, koala, pepe, rdnzao |
|           76 |      528 | 2024-07-18 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |    -8.63 | doc, gafolo, koala, pepe, rdnzao |
|           75 |      591 | 2024-07-17 | ODDIK             | W   | 1.000      | 0.450        | 0.098 (0.044)    | 0.857 (0.386)    | -         |    16.54 | doc, gafolo, koala, pepe, rdnzao |
|           74 |      602 | 2024-07-17 | ODDIK             | W   | 1.000      | 0.450        | 0.098 (0.044)    | 0.857 (0.386)    | -         |    18.05 | doc, gafolo, koala, pepe, rdnzao |
|           73 |      653 | 2024-07-16 | RED Canids        | L   | 1.000      | -            | -                | -                | -         |    -9.30 | doc, gafolo, koala, pepe, rdnzao |
|           72 |      659 | 2024-07-16 | RED Canids        | L   | 1.000      | -            | -                | -                | -         |   -10.03 | doc, gafolo, koala, pepe, rdnzao |
|           71 |      703 | 2024-07-15 | KRÜ               | L   | 1.000      | -            | -                | -                | -         |   -19.52 | doc, gafolo, koala, pepe, rdnzao |
|           70 |      707 | 2024-07-15 | KRÜ               | W   | 1.000      | -            | -                | -                | -         |    11.67 | doc, gafolo, koala, pepe, rdnzao |
|           69 |      775 | 2024-07-11 | Bounty Hunters    | L   | 1.000      | -            | -                | -                | -         |   -16.46 | doc, gafolo, koala, pepe, rdnzao |
|           68 |      789 | 2024-07-10 | BESTIA            | W   | 1.000      | 0.371        | 0.091 (0.034)    | 0.756 (0.280)    | -         |    16.87 | doc, gafolo, koala, pepe, rdnzao |
|           67 |      809 | 2024-07-09 | KRÜ               | L   | 1.000      | -            | -                | -                | -         |   -20.38 | doc, gafolo, koala, pepe, rdnzao |
|           66 |      831 | 2024-07-08 | Patins da Ferrari | W   | 1.000      | -            | -                | -                | -         |     9.38 | doc, gafolo, koala, pepe, rdnzao |
|           65 |      867 | 2024-06-30 | Patins da Ferrari | L   | 0.974      | -            | -                | -                | -         |   -21.59 | doc, gafolo, koala, pepe, rdnzao |
|           64 |      881 | 2024-06-28 | KRÜ               | W   | 0.961      | -            | -                | -                | -         |     9.82 | doc, gafolo, koala, pepe, rdnzao |
|           63 |      882 | 2024-06-28 | Bounty Hunters    | L   | 0.960      | -            | -                | -                | -         |   -18.31 | doc, gafolo, koala, pepe, rdnzao |
|           62 |      886 | 2024-06-27 | Galorys           | W   | 0.955      | -            | -                | -                | -         |     8.79 | doc, gafolo, koala, pepe, rdnzao |
|           61 |      889 | 2024-06-27 | inSanitY          | L   | 0.953      | -            | -                | -                | -         |   -15.49 | doc, gafolo, koala, pepe, rdnzao |
|           60 |      973 | 2024-06-14 | Fluxo             | L   | 0.868      | -            | -                | -                | -         |   -11.77 | doc, gafolo, koala, pepe, rdnzao |
|           59 |     1088 | 2024-06-10 | Vikings KR        | W   | 0.839      | -            | -                | -                | -         |     5.61 | doc, gafolo, koala, pepe, rdnzao |
|           58 |     1120 | 2024-06-09 | paiN              | L   | 0.834      | -            | -                | -                | -         |    -4.61 | doc, gafolo, koala, pepe, rdnzao |
|           57 |     1139 | 2024-06-09 | BESTIA            | W   | 0.833      | 0.450        | 0.091 (0.034)    | 0.756 (0.283)    | -         |    12.51 | doc, gafolo, koala, pepe, rdnzao |
|           56 |     1189 | 2024-06-08 | Hype              | W   | 0.827      | -            | -                | -                | -         |     8.74 | doc, gafolo, koala, pepe, rdnzao |
|           55 |     1202 | 2024-06-08 | Patins da Ferrari | L   | 0.826      | -            | -                | -                | -         |   -19.90 | doc, gafolo, koala, pepe, rdnzao |
|           54 |     1228 | 2024-06-07 | 9z                | L   | 0.821      | -            | -                | -                | -         |    -5.69 | doc, gafolo, koala, pepe, rdnzao |
|           53 |     1287 | 2024-06-06 | paiN              | W   | 0.815      | 0.450        | 0.324 (0.119)    | 0.859 (0.315)    | -         |    21.41 | doc, gafolo, koala, pepe, rdnzao |
|           52 |     1356 | 2024-06-05 | Imperial          | L   | 0.808      | -            | -                | -                | -         |    -5.65 | doc, gafolo, koala, pepe, rdnzao |
|           51 |     1406 | 2024-06-04 | BESTIA            | W   | 0.802      | 0.450        | 0.091 (0.033)    | 0.756 (0.273)    | -         |    13.99 | doc, gafolo, koala, pepe, rdnzao |
|           50 |     1729 | 2024-05-22 | Imperial          | W   | 0.714      | 0.450        | 0.234 (0.075)    | 0.708 (0.228)    | -         |    17.75 | doc, drg, gafolo, pepe, rdnzao   |
|           49 |     1733 | 2024-05-22 | Imperial          | L   | 0.714      | -            | -                | -                | -         |    -4.60 | doc, drg, gafolo, pepe, rdnzao   |
|           48 |     1760 | 2024-05-21 | Case              | L   | 0.709      | -            | -                | -                | -         |   -13.60 | doc, drg, gafolo, pepe, rdnzao   |
|           47 |     1761 | 2024-05-21 | Case              | W   | 0.708      | 0.450        | -                | 0.750 (0.239)    | -         |     8.77 | doc, drg, gafolo, pepe, rdnzao   |
|           46 |     1765 | 2024-05-21 | RED Canids        | W   | 0.708      | 0.450        | 0.073 (0.023)    | 0.733 (0.234)    | -         |    14.29 | doc, drg, gafolo, pepe, rdnzao   |
|           45 |     1767 | 2024-05-21 | RED Canids        | L   | 0.708      | -            | -                | -                | -         |    -8.02 | doc, drg, gafolo, pepe, rdnzao   |
|           44 |     1897 | 2024-05-17 | ODDIK             | L   | 0.680      | -            | -                | -                | -         |   -12.65 | doc, drg, gafolo, rdnzao, togs   |
|           43 |     1922 | 2024-05-16 | W7M               | W   | 0.675      | -            | -                | -                | -         |     4.95 | doc, drg, gafolo, rdnzao, togs   |
|           42 |     1925 | 2024-05-16 | W7M               | W   | 0.675      | -            | -                | -                | -         |     5.16 | doc, drg, gafolo, rdnzao, togs   |
|           41 |     1930 | 2024-05-16 | Hype              | W   | 0.674      | -            | -                | -                | -         |     7.56 | doc, drg, gafolo, rdnzao, togs   |
|           40 |     1969 | 2024-05-15 | Vikings KR        | W   | 0.669      | -            | -                | -                | -         |     5.97 | doc, drg, gafolo, rdnzao, togs   |
|           39 |     1977 | 2024-05-15 | 9z                | L   | 0.668      | -            | -                | -                | -         |    -4.13 | doc, drg, gafolo, rdnzao, togs   |
|           38 |     2036 | 2024-05-14 | Fluxo             | L   | 0.661      | -            | -                | -                | -         |    -7.27 | doc, drg, gafolo, rdnzao, togs   |
|           37 |     2063 | 2024-05-13 | RED Canids        | W   | 0.654      | 0.384        | 0.073 (0.018)    | -                | -         |    12.02 | doc, drg, gafolo, rdnzao, togs   |
|           36 |     2070 | 2024-05-13 | W7M               | W   | 0.653      | -            | -                | -                | -         |     5.82 | doc, drg, gafolo, rdnzao, togs   |
|           35 |     2118 | 2024-05-11 | W7M               | W   | 0.640      | -            | -                | -                | -         |     5.98 | doc, drg, gafolo, rdnzao, togs   |
|           34 |     2162 | 2024-05-09 | BESTIA            | L   | 0.628      | -            | -                | -                | -         |   -11.12 | doc, drg, gafolo, rdnzao, togs   |
|           33 |     2181 | 2024-05-08 | 9z                | L   | 0.622      | -            | -                | -                | -         |    -4.09 | doc, drg, gafolo, rdnzao, togs   |
|           32 |     2219 | 2024-05-06 | BESTIA            | W   | 0.608      | 0.435        | 0.091 (0.024)    | -                | -         |     8.21 | doc, drg, gafolo, rdnzao, togs   |
|           31 |     2817 | 2024-04-11 | paiN              | L   | 0.441      | -            | -                | -                | -         |    -1.34 | doc, drg, gafolo, rdnzao, togs   |
|           30 |     3080 | 2024-04-03 | 2GAME             | W   | 0.388      | -            | -                | -                | -         |     1.99 | doc, drg, gafolo, rdnzao, togs   |
|           29 |     3083 | 2024-04-03 | 2GAME             | W   | 0.388      | -            | -                | -                | -         |     2.03 | doc, drg, gafolo, rdnzao, togs   |
|           28 |     3446 | 2024-03-14 | MIBR              | L   | 0.255      | -            | -                | -                | -         |    -0.64 | doc, drg, gafolo, rdnzao, togs   |
|           27 |     3448 | 2024-03-14 | MIBR              | L   | 0.255      | -            | -                | -                | -         |    -0.65 | doc, drg, gafolo, rdnzao, togs   |
|           26 |     3476 | 2024-03-13 | Yawara            | W   | 0.248      | -            | -                | -                | -         |     0.57 | doc, drg, gafolo, rdnzao, togs   |
|           25 |     3479 | 2024-03-13 | ODDIK             | W   | 0.248      | -            | -                | -                | -         |     4.08 | doc, drg, gafolo, rdnzao, togs   |
|           24 |     3550 | 2024-03-11 | Fluxo             | L   | 0.233      | -            | -                | -                | -         |    -2.92 | doc, drg, gafolo, rdnzao, togs   |
|           23 |     3578 | 2024-03-09 | Case              | L   | 0.221      | -            | -                | -                | -         |    -3.92 | doc, drg, gafolo, rdnzao, togs   |
|           22 |     3642 | 2024-03-07 | Corinthians       | W   | 0.206      | -            | -                | -                | -         |     0.44 | doc, drg, gafolo, rdnzao, togs   |
|           21 |     3696 | 2024-03-05 | Solid             | W   | 0.194      | -            | -                | -                | -         |     2.37 | doc, drg, gafolo, rdnzao, togs   |
|           20 |     3702 | 2024-03-05 | Solid             | W   | 0.194      | -            | -                | -                | -         |     2.41 | doc, drg, gafolo, rdnzao, togs   |
|           19 |     3896 | 2024-02-24 | Galorys           | W   | 0.129      | -            | -                | -                | -         |     1.52 | doc, drg, gafolo, rdnzao, togs   |
|           18 |     3904 | 2024-02-24 | Galorys           | W   | 0.128      | -            | -                | -                | -         |     1.53 | doc, drg, gafolo, rdnzao, togs   |
|           17 |     3908 | 2024-02-24 | Fluxo             | L   | 0.128      | -            | -                | -                | -         |    -1.60 | doc, drg, gafolo, rdnzao, togs   |
|           16 |     3961 | 2024-02-21 | Corinthians       | W   | 0.109      | -            | -                | -                | -         |     0.24 | doc, drg, gafolo, rdnzao, togs   |
|           15 |     3966 | 2024-02-21 | Case              | W   | 0.108      | -            | -                | -                | -         |     1.59 | doc, drg, gafolo, rdnzao, togs   |
|           14 |     3971 | 2024-02-21 | Galorys           | W   | 0.106      | -            | -                | -                | -         |     1.32 | doc, drg, gafolo, rdnzao, togs   |
|           13 |     3996 | 2024-02-20 | Flamengo          | L   | 0.101      | -            | -                | -                | -         |    -2.98 | doc, drg, gafolo, rdnzao, togs   |
|           12 |     4001 | 2024-02-20 | Case              | W   | 0.099      | -            | -                | -                | -         |     1.47 | doc, drg, gafolo, rdnzao, togs   |
|           11 |     4025 | 2024-02-19 | Solid             | W   | 0.093      | -            | -                | -                | -         |     1.18 | doc, drg, gafolo, rdnzao, togs   |
|           10 |     4039 | 2024-02-18 | Galorys           | W   | 0.089      | -            | -                | -                | -         |     1.11 | doc, drg, gafolo, rdnzao, togs   |
|            9 |     4061 | 2024-02-17 | W7M               | L   | 0.082      | -            | -                | -                | -         |    -1.73 | doc, drg, gafolo, rdnzao, togs   |
|            8 |     4066 | 2024-02-17 | Galorys           | L   | 0.081      | -            | -                | -                | -         |    -1.55 | doc, drg, gafolo, rdnzao, togs   |
|            7 |     4101 | 2024-02-16 | W7M               | W   | 0.073      | -            | -                | -                | -         |     0.75 | doc, drg, gafolo, rdnzao, togs   |
|            6 |     4119 | 2024-02-15 | Case              | L   | 0.068      | -            | -                | -                | -         |    -1.14 | doc, drg, gafolo, rdnzao, togs   |
|            5 |     4125 | 2024-02-15 | Fluxo             | L   | 0.067      | -            | -                | -                | -         |    -0.84 | doc, drg, gafolo, rdnzao, togs   |
|            4 |     4126 | 2024-02-15 | Fluxo             | L   | 0.067      | -            | -                | -                | -         |    -0.84 | doc, drg, gafolo, rdnzao, togs   |
|            3 |     4154 | 2024-02-14 | Hype              | W   | 0.062      | -            | -                | -                | -         |     0.08 | doc, drg, gafolo, rdnzao, togs   |
|            2 |     4165 | 2024-02-14 | Galorys           | W   | 0.060      | -            | -                | -                | -         |     0.74 | doc, drg, gafolo, rdnzao, togs   |
|            1 |     4209 | 2024-02-12 | Solid             | W   | 0.048      | -            | -                | -                | -         |     0.61 | doc, drg, gafolo, rdnzao, togs   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($9,971.37)
- Divide that value by the 5th highest value among all rosters ($325,971.18)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-02 |      1.000 | $750.00        | $750.00         |
| 2024-06-28 |      0.960 | $500.00        | $480.13         |
| 2024-06-16 |      0.880 | $2,500.00      | $2,200.81       |
| 2024-06-10 |      0.842 | $750.00        | $631.20         |
| 2024-06-09 |      0.834 | $5,000.00      | $4,171.99       |
| 2024-05-19 |      0.694 | $1,000.00      | $693.66         |
| 2024-02-25 |      0.134 | $5,000.00      | $671.06         |
| 2024-02-21 |      0.106 | $3,500.00      | $372.52         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
