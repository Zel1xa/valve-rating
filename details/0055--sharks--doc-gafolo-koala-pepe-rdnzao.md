### Roster Details<br />
Team Name: Sharks<br />
Roster: doc, gafolo, koala, pepe, rdnzao<br />
Global Rank: [55](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [15]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1025.0<br />
<br />
Final Rank Value (1025.0) = Starting Rank Value (973.0) + Head To Head Adjustments (51.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.399[<sup>1</sup>](#table2)
- Bounty Collected: 0.430[<sup>2</sup>](#table1)
- Opponent Network: 0.283[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.278<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 973.0
- 400 + ( ( 0.278 - 0.000 ) / ( 0.776 - 0.000 ) ) * 1600 = 973.0


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
|           90 |        0 | 2024-07-31 | MIBR              | L   | 1.000      | -            | -                | -                | -         |    -4.44 | doc, gafolo, koala, pepe, rdnzao |
|           89 |       10 | 2024-07-31 | Solid             | W   | 1.000      | 0.371        | -                | 0.817 (0.303)    | 0 (0.000) |    12.16 | doc, gafolo, koala, pepe, rdnzao |
|           88 |       44 | 2024-07-30 | Hype              | W   | 1.000      | -            | -                | -                | 0 (0.000) |    10.15 | doc, gafolo, koala, pepe, rdnzao |
|           87 |      117 | 2024-07-28 | Bad News Chickens | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.45 | doc, gafolo, koala, pepe, rdnzao |
|           86 |      165 | 2024-07-26 | Imperial          | L   | 1.000      | -            | -                | -                | -         |    -8.13 | doc, gafolo, koala, pepe, rdnzao |
|           85 |      192 | 2024-07-25 | BESTIA            | W   | 1.000      | -            | -                | -                | 0 (0.000) |    16.18 | doc, gafolo, koala, pepe, rdnzao |
|           84 |      199 | 2024-07-25 | Patins da Ferrari | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.20 | doc, gafolo, koala, pepe, rdnzao |
|           83 |      241 | 2024-07-24 | Bad News Chickens | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.40 | doc, gafolo, koala, pepe, rdnzao |
|           82 |      248 | 2024-07-24 | Yawara            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     1.99 | doc, gafolo, koala, pepe, rdnzao |
|           81 |      268 | 2024-07-23 | ODDIK             | L   | 1.000      | -            | -                | -                | -         |   -14.15 | doc, gafolo, koala, pepe, rdnzao |
|           80 |      271 | 2024-07-23 | W7M               | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.01 | doc, gafolo, koala, pepe, rdnzao |
|           79 |      357 | 2024-07-20 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |    -7.52 | doc, gafolo, koala, pepe, rdnzao |
|           78 |      410 | 2024-07-19 | Hype              | W   | 1.000      | -            | -                | -                | 0 (0.000) |    12.38 | doc, gafolo, koala, pepe, rdnzao |
|           77 |      435 | 2024-07-18 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |    -7.95 | doc, gafolo, koala, pepe, rdnzao |
|           76 |      437 | 2024-07-18 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |    -8.50 | doc, gafolo, koala, pepe, rdnzao |
|           75 |      500 | 2024-07-17 | ODDIK             | W   | 1.000      | 0.450        | 0.097 (0.044)    | 0.781 (0.352)    | 0 (0.000) |    17.30 | doc, gafolo, koala, pepe, rdnzao |
|           74 |      511 | 2024-07-17 | ODDIK             | W   | 1.000      | 0.450        | 0.097 (0.044)    | 0.781 (0.352)    | -         |    18.86 | doc, gafolo, koala, pepe, rdnzao |
|           73 |      565 | 2024-07-16 | RED Canids        | L   | 1.000      | -            | -                | -                | -         |    -7.61 | doc, gafolo, koala, pepe, rdnzao |
|           72 |      571 | 2024-07-16 | RED Canids        | L   | 1.000      | -            | -                | -                | -         |    -8.13 | doc, gafolo, koala, pepe, rdnzao |
|           71 |      615 | 2024-07-15 | KRÜ               | L   | 1.000      | -            | -                | -                | -         |   -20.84 | doc, gafolo, koala, pepe, rdnzao |
|           70 |      619 | 2024-07-15 | KRÜ               | W   | 1.000      | -            | -                | -                | -         |    10.26 | doc, gafolo, koala, pepe, rdnzao |
|           69 |      691 | 2024-07-11 | Bounty Hunters    | L   | 1.000      | -            | -                | -                | -         |   -16.75 | doc, gafolo, koala, pepe, rdnzao |
|           68 |      706 | 2024-07-10 | BESTIA            | W   | 1.000      | 0.371        | 0.095 (0.035)    | 0.731 (0.271)    | -         |    17.05 | doc, gafolo, koala, pepe, rdnzao |
|           67 |      726 | 2024-07-09 | KRÜ               | L   | 1.000      | -            | -                | -                | -         |   -21.40 | doc, gafolo, koala, pepe, rdnzao |
|           66 |      748 | 2024-07-08 | Patins da Ferrari | W   | 1.000      | -            | -                | -                | -         |     8.92 | doc, gafolo, koala, pepe, rdnzao |
|           65 |      784 | 2024-06-30 | Patins da Ferrari | L   | 0.993      | -            | -                | -                | -         |   -22.49 | doc, gafolo, koala, pepe, rdnzao |
|           64 |      798 | 2024-06-28 | KRÜ               | W   | 0.980      | -            | -                | -                | -         |     8.89 | doc, gafolo, koala, pepe, rdnzao |
|           63 |      799 | 2024-06-28 | Bounty Hunters    | L   | 0.979      | -            | -                | -                | -         |   -19.19 | doc, gafolo, koala, pepe, rdnzao |
|           62 |      803 | 2024-06-27 | Galorys           | W   | 0.974      | -            | -                | -                | -         |     8.64 | doc, gafolo, koala, pepe, rdnzao |
|           61 |      806 | 2024-06-27 | inSanitY          | L   | 0.972      | -            | -                | -                | -         |   -16.28 | doc, gafolo, koala, pepe, rdnzao |
|           60 |      907 | 2024-06-14 | Fluxo             | L   | 0.887      | -            | -                | -                | -         |   -11.97 | doc, gafolo, koala, pepe, rdnzao |
|           59 |     1029 | 2024-06-10 | Vikings KR        | W   | 0.859      | -            | -                | -                | -         |     5.33 | doc, gafolo, koala, pepe, rdnzao |
|           58 |     1062 | 2024-06-09 | paiN              | L   | 0.853      | -            | -                | -                | -         |    -4.12 | doc, gafolo, koala, pepe, rdnzao |
|           57 |     1081 | 2024-06-09 | BESTIA            | W   | 0.852      | 0.450        | 0.095 (0.036)    | 0.731 (0.280)    | -         |    13.02 | doc, gafolo, koala, pepe, rdnzao |
|           56 |     1133 | 2024-06-08 | Hype              | W   | 0.846      | -            | -                | -                | -         |     8.83 | doc, gafolo, koala, pepe, rdnzao |
|           55 |     1148 | 2024-06-08 | Patins da Ferrari | L   | 0.845      | -            | -                | -                | -         |   -20.82 | doc, gafolo, koala, pepe, rdnzao |
|           54 |     1175 | 2024-06-07 | 9z                | L   | 0.840      | -            | -                | -                | -         |    -2.19 | doc, gafolo, koala, pepe, rdnzao |
|           53 |     1234 | 2024-06-06 | paiN              | W   | 0.834      | 0.450        | 0.333 (0.125)    | 0.797 (0.299)    | -         |    22.53 | doc, gafolo, koala, pepe, rdnzao |
|           52 |     1303 | 2024-06-05 | Imperial          | L   | 0.827      | -            | -                | -                | -         |    -4.71 | doc, gafolo, koala, pepe, rdnzao |
|           51 |     1353 | 2024-06-04 | BESTIA            | W   | 0.821      | 0.450        | 0.095 (0.035)    | 0.731 (0.270)    | -         |    14.52 | doc, gafolo, koala, pepe, rdnzao |
|           50 |     1680 | 2024-05-22 | Imperial          | W   | 0.733      | 0.450        | 0.243 (0.080)    | 0.685 (0.226)    | -         |    18.95 | doc, drg, gafolo, pepe, rdnzao   |
|           49 |     1684 | 2024-05-22 | Imperial          | L   | 0.733      | -            | -                | -                | -         |    -3.98 | doc, drg, gafolo, pepe, rdnzao   |
|           48 |     1711 | 2024-05-21 | Case              | L   | 0.728      | -            | -                | -                | -         |   -14.09 | doc, drg, gafolo, pepe, rdnzao   |
|           47 |     1712 | 2024-05-21 | Case              | W   | 0.727      | 0.450        | -                | 0.720 (0.236)    | -         |     8.86 | doc, drg, gafolo, pepe, rdnzao   |
|           46 |     1716 | 2024-05-21 | RED Canids        | W   | 0.727      | 0.450        | 0.079 (0.026)    | 0.738 (0.242)    | -         |    16.16 | doc, drg, gafolo, pepe, rdnzao   |
|           45 |     1718 | 2024-05-21 | RED Canids        | L   | 0.727      | -            | -                | -                | -         |    -6.66 | doc, drg, gafolo, pepe, rdnzao   |
|           44 |     1849 | 2024-05-17 | ODDIK             | L   | 0.699      | -            | -                | -                | -         |   -12.99 | doc, drg, gafolo, rdnzao, togs   |
|           43 |     1874 | 2024-05-16 | W7M               | W   | 0.694      | -            | -                | -                | -         |     4.97 | doc, drg, gafolo, rdnzao, togs   |
|           42 |     1877 | 2024-05-16 | W7M               | W   | 0.694      | -            | -                | -                | -         |     5.19 | doc, drg, gafolo, rdnzao, togs   |
|           41 |     1882 | 2024-05-16 | Hype              | W   | 0.693      | -            | -                | -                | -         |     7.58 | doc, drg, gafolo, rdnzao, togs   |
|           40 |     1921 | 2024-05-15 | Vikings KR        | W   | 0.688      | -            | -                | -                | -         |     5.99 | doc, drg, gafolo, rdnzao, togs   |
|           39 |     1929 | 2024-05-15 | 9z                | L   | 0.687      | -            | -                | -                | -         |    -0.99 | doc, drg, gafolo, rdnzao, togs   |
|           38 |     1988 | 2024-05-14 | Fluxo             | L   | 0.680      | -            | -                | -                | -         |    -7.46 | doc, drg, gafolo, rdnzao, togs   |
|           37 |     2015 | 2024-05-13 | RED Canids        | W   | 0.674      | 0.384        | 0.079 (0.020)    | -                | -         |    13.96 | doc, drg, gafolo, rdnzao, togs   |
|           36 |     2022 | 2024-05-13 | W7M               | W   | 0.672      | -            | -                | -                | -         |     5.98 | doc, drg, gafolo, rdnzao, togs   |
|           35 |     2070 | 2024-05-11 | W7M               | W   | 0.659      | -            | -                | -                | -         |     6.16 | doc, drg, gafolo, rdnzao, togs   |
|           34 |     2114 | 2024-05-09 | BESTIA            | L   | 0.647      | -            | -                | -                | -         |   -11.31 | doc, drg, gafolo, rdnzao, togs   |
|           33 |     2134 | 2024-05-08 | 9z                | L   | 0.641      | -            | -                | -                | -         |    -0.85 | doc, drg, gafolo, rdnzao, togs   |
|           32 |     2172 | 2024-05-06 | BESTIA            | W   | 0.627      | 0.435        | 0.095 (0.026)    | -                | -         |     8.71 | doc, drg, gafolo, rdnzao, togs   |
|           31 |     2771 | 2024-04-11 | paiN              | L   | 0.460      | -            | -                | -                | -         |    -1.03 | doc, drg, gafolo, rdnzao, togs   |
|           30 |     3034 | 2024-04-03 | 2GAME             | W   | 0.407      | -            | -                | -                | -         |     2.04 | doc, drg, gafolo, rdnzao, togs   |
|           29 |     3037 | 2024-04-03 | 2GAME             | W   | 0.407      | -            | -                | -                | -         |     2.08 | doc, drg, gafolo, rdnzao, togs   |
|           28 |     3406 | 2024-03-14 | MIBR              | L   | 0.274      | -            | -                | -                | -         |    -0.68 | doc, drg, gafolo, rdnzao, togs   |
|           27 |     3408 | 2024-03-14 | MIBR              | L   | 0.274      | -            | -                | -                | -         |    -0.69 | doc, drg, gafolo, rdnzao, togs   |
|           26 |     3436 | 2024-03-13 | Yawara            | W   | 0.267      | -            | -                | -                | -         |     0.62 | doc, drg, gafolo, rdnzao, togs   |
|           25 |     3439 | 2024-03-13 | ODDIK             | W   | 0.267      | -            | -                | -                | -         |     4.45 | doc, drg, gafolo, rdnzao, togs   |
|           24 |     3512 | 2024-03-11 | Fluxo             | L   | 0.252      | -            | -                | -                | -         |    -3.17 | doc, drg, gafolo, rdnzao, togs   |
|           23 |     3540 | 2024-03-09 | Case              | L   | 0.240      | -            | -                | -                | -         |    -4.28 | doc, drg, gafolo, rdnzao, togs   |
|           22 |     3604 | 2024-03-07 | Corinthians       | W   | 0.225      | -            | -                | -                | -         |     0.48 | doc, drg, gafolo, rdnzao, togs   |
|           21 |     3658 | 2024-03-05 | Solid             | W   | 0.213      | -            | -                | -                | -         |     2.61 | doc, drg, gafolo, rdnzao, togs   |
|           20 |     3664 | 2024-03-05 | Solid             | W   | 0.213      | -            | -                | -                | -         |     2.66 | doc, drg, gafolo, rdnzao, togs   |
|           19 |     3858 | 2024-02-24 | Galorys           | W   | 0.148      | -            | -                | -                | -         |     1.79 | doc, drg, gafolo, rdnzao, togs   |
|           18 |     3866 | 2024-02-24 | Galorys           | W   | 0.147      | -            | -                | -                | -         |     1.81 | doc, drg, gafolo, rdnzao, togs   |
|           17 |     3870 | 2024-02-24 | Fluxo             | L   | 0.147      | -            | -                | -                | -         |    -1.85 | doc, drg, gafolo, rdnzao, togs   |
|           16 |     3923 | 2024-02-21 | Corinthians       | W   | 0.128      | -            | -                | -                | -         |     0.28 | doc, drg, gafolo, rdnzao, togs   |
|           15 |     3928 | 2024-02-21 | Case              | W   | 0.127      | -            | -                | -                | -         |     1.87 | doc, drg, gafolo, rdnzao, togs   |
|           14 |     3933 | 2024-02-21 | Galorys           | W   | 0.125      | -            | -                | -                | -         |     1.61 | doc, drg, gafolo, rdnzao, togs   |
|           13 |     3958 | 2024-02-20 | Flamengo          | L   | 0.120      | -            | -                | -                | -         |    -3.54 | doc, drg, gafolo, rdnzao, togs   |
|           12 |     3963 | 2024-02-20 | Case              | W   | 0.119      | -            | -                | -                | -         |     1.75 | doc, drg, gafolo, rdnzao, togs   |
|           11 |     3987 | 2024-02-19 | Solid             | W   | 0.112      | -            | -                | -                | -         |     1.43 | doc, drg, gafolo, rdnzao, togs   |
|           10 |     4001 | 2024-02-18 | Galorys           | W   | 0.108      | -            | -                | -                | -         |     1.39 | doc, drg, gafolo, rdnzao, togs   |
|            9 |     4024 | 2024-02-17 | W7M               | L   | 0.101      | -            | -                | -                | -         |    -2.13 | doc, drg, gafolo, rdnzao, togs   |
|            8 |     4029 | 2024-02-17 | Galorys           | L   | 0.100      | -            | -                | -                | -         |    -1.88 | doc, drg, gafolo, rdnzao, togs   |
|            7 |     4064 | 2024-02-16 | W7M               | W   | 0.092      | -            | -                | -                | -         |     0.95 | doc, drg, gafolo, rdnzao, togs   |
|            6 |     4082 | 2024-02-15 | Case              | L   | 0.087      | -            | -                | -                | -         |    -1.47 | doc, drg, gafolo, rdnzao, togs   |
|            5 |     4088 | 2024-02-15 | Fluxo             | L   | 0.086      | -            | -                | -                | -         |    -1.09 | doc, drg, gafolo, rdnzao, togs   |
|            4 |     4089 | 2024-02-15 | Fluxo             | L   | 0.086      | -            | -                | -                | -         |    -1.09 | doc, drg, gafolo, rdnzao, togs   |
|            3 |     4117 | 2024-02-14 | Hype              | W   | 0.081      | -            | -                | -                | -         |     0.10 | doc, drg, gafolo, rdnzao, togs   |
|            2 |     4128 | 2024-02-14 | Galorys           | W   | 0.079      | -            | -                | -                | -         |     1.00 | doc, drg, gafolo, rdnzao, togs   |
|            1 |     4172 | 2024-02-12 | Solid             | W   | 0.067      | -            | -                | -                | -         |     0.85 | doc, drg, gafolo, rdnzao, togs   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($10,318.38)
- Divide that value by the 5th highest value among all rosters ($331,608.80)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-31 |      1.000 | $750.00        | $750.00         |
| 2024-06-28 |      0.979 | $500.00        | $489.63         |
| 2024-06-16 |      0.899 | $2,500.00      | $2,248.34       |
| 2024-06-10 |      0.861 | $750.00        | $645.46         |
| 2024-06-09 |      0.853 | $5,000.00      | $4,267.06       |
| 2024-05-19 |      0.713 | $1,000.00      | $712.67         |
| 2024-02-25 |      0.153 | $5,000.00      | $766.13         |
| 2024-02-21 |      0.125 | $3,500.00      | $439.07         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
