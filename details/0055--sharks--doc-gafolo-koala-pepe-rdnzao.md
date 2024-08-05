### Roster Details<br />
Team Name: Sharks<br />
Roster: doc, gafolo, koala, pepe, rdnzao<br />
Global Rank: [55](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [14]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1024.8<br />
<br />
Final Rank Value (1024.8) = Starting Rank Value (973.4) + Head To Head Adjustments (51.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.397[<sup>1</sup>](#table2)
- Bounty Collected: 0.427[<sup>2</sup>](#table1)
- Opponent Network: 0.297[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.280<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 973.4
- 400 + ( ( 0.280 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 973.4


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
|           93 |       82 | 2024-08-02 | paiN              | L   | 1.000      | -            | -                | -                | -         |    -3.50 | doc, gafolo, koala, pepe, rdnzao |
|           92 |      112 | 2024-08-01 | Hype              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.06 | doc, gafolo, koala, pepe, rdnzao |
|           91 |      120 | 2024-08-01 | paiN              | L   | 1.000      | -            | -                | -                | -         |    -3.47 | doc, gafolo, koala, pepe, rdnzao |
|           90 |      153 | 2024-07-31 | MIBR              | L   | 1.000      | -            | -                | -                | -         |    -4.61 | doc, gafolo, koala, pepe, rdnzao |
|           89 |      163 | 2024-07-31 | Solid             | W   | 1.000      | 0.371        | -                | 0.836 (0.310)    | 0 (0.000) |    12.31 | doc, gafolo, koala, pepe, rdnzao |
|           88 |      197 | 2024-07-30 | Hype              | W   | 1.000      | -            | -                | -                | 0 (0.000) |    10.25 | doc, gafolo, koala, pepe, rdnzao |
|           87 |      270 | 2024-07-28 | Bad News Chickens | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.47 | doc, gafolo, koala, pepe, rdnzao |
|           86 |      318 | 2024-07-26 | Imperial          | L   | 1.000      | -            | -                | -                | -         |    -8.53 | doc, gafolo, koala, pepe, rdnzao |
|           85 |      345 | 2024-07-25 | BESTIA            | W   | 1.000      | -            | -                | -                | 0 (0.000) |    16.14 | doc, gafolo, koala, pepe, rdnzao |
|           84 |      352 | 2024-07-25 | Patins da Ferrari | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.21 | doc, gafolo, koala, pepe, rdnzao |
|           83 |      394 | 2024-07-24 | Bad News Chickens | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.41 | doc, gafolo, koala, pepe, rdnzao |
|           82 |      401 | 2024-07-24 | Yawara            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.00 | doc, gafolo, koala, pepe, rdnzao |
|           81 |      421 | 2024-07-23 | ODDIK             | L   | 1.000      | -            | -                | -                | -         |   -14.08 | doc, gafolo, koala, pepe, rdnzao |
|           80 |      424 | 2024-07-23 | W7M               | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.12 | doc, gafolo, koala, pepe, rdnzao |
|           79 |      510 | 2024-07-20 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |    -7.59 | doc, gafolo, koala, pepe, rdnzao |
|           78 |      563 | 2024-07-19 | Hype              | W   | 1.000      | -            | -                | -                | 0 (0.000) |    12.49 | doc, gafolo, koala, pepe, rdnzao |
|           77 |      588 | 2024-07-18 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |    -8.02 | doc, gafolo, koala, pepe, rdnzao |
|           76 |      590 | 2024-07-18 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |    -8.59 | doc, gafolo, koala, pepe, rdnzao |
|           75 |      653 | 2024-07-17 | ODDIK             | W   | 1.000      | 0.450        | 0.099 (0.044)    | 0.833 (0.375)    | -         |    17.42 | doc, gafolo, koala, pepe, rdnzao |
|           74 |      664 | 2024-07-17 | ODDIK             | W   | 1.000      | 0.450        | 0.099 (0.044)    | 0.833 (0.375)    | -         |    18.99 | doc, gafolo, koala, pepe, rdnzao |
|           73 |      718 | 2024-07-16 | RED Canids        | L   | 1.000      | -            | -                | -                | -         |    -7.82 | doc, gafolo, koala, pepe, rdnzao |
|           72 |      724 | 2024-07-16 | RED Canids        | L   | 1.000      | -            | -                | -                | -         |    -8.37 | doc, gafolo, koala, pepe, rdnzao |
|           71 |      768 | 2024-07-15 | KRÜ               | L   | 1.000      | -            | -                | -                | -         |   -20.60 | doc, gafolo, koala, pepe, rdnzao |
|           70 |      772 | 2024-07-15 | KRÜ               | W   | 1.000      | 0.450        | -                | 0.494 (0.222)    | -         |    10.51 | doc, gafolo, koala, pepe, rdnzao |
|           69 |      844 | 2024-07-11 | Bounty Hunters    | L   | 1.000      | -            | -                | -                | -         |   -16.70 | doc, gafolo, koala, pepe, rdnzao |
|           68 |      859 | 2024-07-10 | BESTIA            | W   | 1.000      | 0.371        | 0.095 (0.035)    | 0.802 (0.297)    | -         |    16.99 | doc, gafolo, koala, pepe, rdnzao |
|           67 |      879 | 2024-07-09 | KRÜ               | L   | 1.000      | -            | -                | -                | -         |   -21.10 | doc, gafolo, koala, pepe, rdnzao |
|           66 |      901 | 2024-07-08 | Patins da Ferrari | W   | 1.000      | -            | -                | -                | -         |     8.92 | doc, gafolo, koala, pepe, rdnzao |
|           65 |      937 | 2024-06-30 | Patins da Ferrari | L   | 0.965      | -            | -                | -                | -         |   -21.88 | doc, gafolo, koala, pepe, rdnzao |
|           64 |      951 | 2024-06-28 | KRÜ               | W   | 0.952      | -            | -                | -                | -         |     8.97 | doc, gafolo, koala, pepe, rdnzao |
|           63 |      952 | 2024-06-28 | Bounty Hunters    | L   | 0.951      | -            | -                | -                | -         |   -18.54 | doc, gafolo, koala, pepe, rdnzao |
|           62 |      956 | 2024-06-27 | Galorys           | W   | 0.946      | -            | -                | -                | -         |     8.62 | doc, gafolo, koala, pepe, rdnzao |
|           61 |      959 | 2024-06-27 | inSanitY          | L   | 0.944      | -            | -                | -                | -         |   -15.79 | doc, gafolo, koala, pepe, rdnzao |
|           60 |     1060 | 2024-06-14 | Fluxo             | L   | 0.859      | -            | -                | -                | -         |   -11.59 | doc, gafolo, koala, pepe, rdnzao |
|           59 |     1182 | 2024-06-10 | Vikings KR        | W   | 0.831      | -            | -                | -                | -         |     5.31 | doc, gafolo, koala, pepe, rdnzao |
|           58 |     1215 | 2024-06-09 | paiN              | L   | 0.825      | -            | -                | -                | -         |    -4.16 | doc, gafolo, koala, pepe, rdnzao |
|           57 |     1234 | 2024-06-09 | BESTIA            | W   | 0.824      | 0.450        | 0.095 (0.035)    | 0.802 (0.297)    | -         |    12.66 | doc, gafolo, koala, pepe, rdnzao |
|           56 |     1286 | 2024-06-08 | Hype              | W   | 0.818      | -            | -                | -                | -         |     8.70 | doc, gafolo, koala, pepe, rdnzao |
|           55 |     1301 | 2024-06-08 | Patins da Ferrari | L   | 0.817      | -            | -                | -                | -         |   -20.10 | doc, gafolo, koala, pepe, rdnzao |
|           54 |     1328 | 2024-06-07 | 9z                | L   | 0.813      | -            | -                | -                | -         |    -2.20 | doc, gafolo, koala, pepe, rdnzao |
|           53 |     1387 | 2024-06-06 | paiN              | W   | 0.806      | 0.450        | 0.326 (0.118)    | 0.868 (0.315)    | -         |    21.60 | doc, gafolo, koala, pepe, rdnzao |
|           52 |     1456 | 2024-06-05 | Imperial          | L   | 0.799      | -            | -                | -                | -         |    -4.91 | doc, gafolo, koala, pepe, rdnzao |
|           51 |     1506 | 2024-06-04 | BESTIA            | W   | 0.793      | 0.450        | 0.095 (0.034)    | 0.802 (0.286)    | -         |    14.00 | doc, gafolo, koala, pepe, rdnzao |
|           50 |     1833 | 2024-05-22 | Imperial          | W   | 0.705      | 0.450        | 0.236 (0.075)    | -                | -         |    17.90 | doc, drg, gafolo, pepe, rdnzao   |
|           49 |     1837 | 2024-05-22 | Imperial          | L   | 0.705      | -            | -                | -                | -         |    -4.17 | doc, drg, gafolo, pepe, rdnzao   |
|           48 |     1864 | 2024-05-21 | Case              | L   | 0.700      | -            | -                | -                | -         |   -13.55 | doc, drg, gafolo, pepe, rdnzao   |
|           47 |     1865 | 2024-05-21 | Case              | W   | 0.699      | 0.450        | -                | 0.806 (0.254)    | -         |     8.54 | doc, drg, gafolo, pepe, rdnzao   |
|           46 |     1869 | 2024-05-21 | RED Canids        | W   | 0.699      | 0.450        | 0.077 (0.024)    | 0.758 (0.239)    | -         |    15.35 | doc, drg, gafolo, pepe, rdnzao   |
|           45 |     1871 | 2024-05-21 | RED Canids        | L   | 0.699      | -            | -                | -                | -         |    -6.62 | doc, drg, gafolo, pepe, rdnzao   |
|           44 |     2002 | 2024-05-17 | ODDIK             | L   | 0.671      | -            | -                | -                | -         |   -12.41 | doc, drg, gafolo, rdnzao, togs   |
|           43 |     2027 | 2024-05-16 | W7M               | W   | 0.666      | -            | -                | -                | -         |     4.85 | doc, drg, gafolo, rdnzao, togs   |
|           42 |     2030 | 2024-05-16 | W7M               | W   | 0.666      | -            | -                | -                | -         |     5.06 | doc, drg, gafolo, rdnzao, togs   |
|           41 |     2035 | 2024-05-16 | Hype              | W   | 0.665      | -            | -                | -                | -         |     7.36 | doc, drg, gafolo, rdnzao, togs   |
|           40 |     2074 | 2024-05-15 | Vikings KR        | W   | 0.660      | -            | -                | -                | -         |     5.82 | doc, drg, gafolo, rdnzao, togs   |
|           39 |     2082 | 2024-05-15 | 9z                | L   | 0.659      | -            | -                | -                | -         |    -1.04 | doc, drg, gafolo, rdnzao, togs   |
|           38 |     2141 | 2024-05-14 | Fluxo             | L   | 0.652      | -            | -                | -                | -         |    -7.21 | doc, drg, gafolo, rdnzao, togs   |
|           37 |     2168 | 2024-05-13 | RED Canids        | W   | 0.646      | 0.384        | 0.077 (0.019)    | -                | -         |    13.20 | doc, drg, gafolo, rdnzao, togs   |
|           36 |     2175 | 2024-05-13 | W7M               | W   | 0.644      | -            | -                | -                | -         |     5.78 | doc, drg, gafolo, rdnzao, togs   |
|           35 |     2223 | 2024-05-11 | W7M               | W   | 0.631      | -            | -                | -                | -         |     5.94 | doc, drg, gafolo, rdnzao, togs   |
|           34 |     2267 | 2024-05-09 | BESTIA            | L   | 0.619      | -            | -                | -                | -         |   -10.75 | doc, drg, gafolo, rdnzao, togs   |
|           33 |     2287 | 2024-05-08 | 9z                | L   | 0.613      | -            | -                | -                | -         |    -0.89 | doc, drg, gafolo, rdnzao, togs   |
|           32 |     2325 | 2024-05-06 | BESTIA            | W   | 0.599      | 0.435        | 0.095 (0.025)    | -                | -         |     8.41 | doc, drg, gafolo, rdnzao, togs   |
|           31 |     2924 | 2024-04-11 | paiN              | L   | 0.432      | -            | -                | -                | -         |    -1.08 | doc, drg, gafolo, rdnzao, togs   |
|           30 |     3187 | 2024-04-03 | 2GAME             | W   | 0.379      | -            | -                | -                | -         |     1.85 | doc, drg, gafolo, rdnzao, togs   |
|           29 |     3190 | 2024-04-03 | 2GAME             | W   | 0.379      | -            | -                | -                | -         |     1.89 | doc, drg, gafolo, rdnzao, togs   |
|           28 |     3559 | 2024-03-14 | MIBR              | L   | 0.246      | -            | -                | -                | -         |    -0.65 | doc, drg, gafolo, rdnzao, togs   |
|           27 |     3561 | 2024-03-14 | MIBR              | L   | 0.246      | -            | -                | -                | -         |    -0.65 | doc, drg, gafolo, rdnzao, togs   |
|           26 |     3589 | 2024-03-13 | Yawara            | W   | 0.239      | -            | -                | -                | -         |     0.55 | doc, drg, gafolo, rdnzao, togs   |
|           25 |     3592 | 2024-03-13 | ODDIK             | W   | 0.239      | -            | -                | -                | -         |     3.99 | doc, drg, gafolo, rdnzao, togs   |
|           24 |     3665 | 2024-03-11 | Fluxo             | L   | 0.224      | -            | -                | -                | -         |    -2.80 | doc, drg, gafolo, rdnzao, togs   |
|           23 |     3693 | 2024-03-09 | Case              | L   | 0.212      | -            | -                | -                | -         |    -3.80 | doc, drg, gafolo, rdnzao, togs   |
|           22 |     3757 | 2024-03-07 | Corinthians       | W   | 0.197      | -            | -                | -                | -         |     0.42 | doc, drg, gafolo, rdnzao, togs   |
|           21 |     3811 | 2024-03-05 | Solid             | W   | 0.185      | -            | -                | -                | -         |     2.29 | doc, drg, gafolo, rdnzao, togs   |
|           20 |     3817 | 2024-03-05 | Solid             | W   | 0.185      | -            | -                | -                | -         |     2.32 | doc, drg, gafolo, rdnzao, togs   |
|           19 |     4011 | 2024-02-24 | Galorys           | W   | 0.120      | -            | -                | -                | -         |     1.48 | doc, drg, gafolo, rdnzao, togs   |
|           18 |     4019 | 2024-02-24 | Galorys           | W   | 0.119      | -            | -                | -                | -         |     1.49 | doc, drg, gafolo, rdnzao, togs   |
|           17 |     4023 | 2024-02-24 | Fluxo             | L   | 0.119      | -            | -                | -                | -         |    -1.49 | doc, drg, gafolo, rdnzao, togs   |
|           16 |     4076 | 2024-02-21 | Corinthians       | W   | 0.100      | -            | -                | -                | -         |     0.22 | doc, drg, gafolo, rdnzao, togs   |
|           15 |     4081 | 2024-02-21 | Case              | W   | 0.099      | -            | -                | -                | -         |     1.43 | doc, drg, gafolo, rdnzao, togs   |
|           14 |     4086 | 2024-02-21 | Galorys           | W   | 0.098      | -            | -                | -                | -         |     1.26 | doc, drg, gafolo, rdnzao, togs   |
|           13 |     4111 | 2024-02-20 | Flamengo          | L   | 0.092      | -            | -                | -                | -         |    -2.72 | doc, drg, gafolo, rdnzao, togs   |
|           12 |     4116 | 2024-02-20 | Case              | W   | 0.091      | -            | -                | -                | -         |     1.31 | doc, drg, gafolo, rdnzao, togs   |
|           11 |     4140 | 2024-02-19 | Solid             | W   | 0.084      | -            | -                | -                | -         |     1.07 | doc, drg, gafolo, rdnzao, togs   |
|           10 |     4154 | 2024-02-18 | Galorys           | W   | 0.080      | -            | -                | -                | -         |     1.03 | doc, drg, gafolo, rdnzao, togs   |
|            9 |     4177 | 2024-02-17 | W7M               | L   | 0.073      | -            | -                | -                | -         |    -1.54 | doc, drg, gafolo, rdnzao, togs   |
|            8 |     4182 | 2024-02-17 | Galorys           | L   | 0.072      | -            | -                | -                | -         |    -1.35 | doc, drg, gafolo, rdnzao, togs   |
|            7 |     4217 | 2024-02-16 | W7M               | W   | 0.064      | -            | -                | -                | -         |     0.66 | doc, drg, gafolo, rdnzao, togs   |
|            6 |     4235 | 2024-02-15 | Case              | L   | 0.059      | -            | -                | -                | -         |    -1.01 | doc, drg, gafolo, rdnzao, togs   |
|            5 |     4241 | 2024-02-15 | Fluxo             | L   | 0.058      | -            | -                | -                | -         |    -0.73 | doc, drg, gafolo, rdnzao, togs   |
|            4 |     4242 | 2024-02-15 | Fluxo             | L   | 0.058      | -            | -                | -                | -         |    -0.73 | doc, drg, gafolo, rdnzao, togs   |
|            3 |     4270 | 2024-02-14 | Hype              | W   | 0.053      | -            | -                | -                | -         |     0.06 | doc, drg, gafolo, rdnzao, togs   |
|            2 |     4281 | 2024-02-14 | Galorys           | W   | 0.051      | -            | -                | -                | -         |     0.65 | doc, drg, gafolo, rdnzao, togs   |
|            1 |     4325 | 2024-02-12 | Solid             | W   | 0.039      | -            | -                | -                | -         |     0.50 | doc, drg, gafolo, rdnzao, togs   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($9,808.30)
- Divide that value by the 5th highest value among all rosters ($323,321.90)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-02 |      1.000 | $750.00        | $750.00         |
| 2024-06-28 |      0.951 | $500.00        | $475.66         |
| 2024-06-16 |      0.871 | $2,500.00      | $2,178.47       |
| 2024-06-10 |      0.833 | $750.00        | $624.50         |
| 2024-06-09 |      0.825 | $5,000.00      | $4,127.31       |
| 2024-05-19 |      0.685 | $1,000.00      | $684.72         |
| 2024-02-25 |      0.125 | $5,000.00      | $626.39         |
| 2024-02-21 |      0.098 | $3,500.00      | $341.25         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
