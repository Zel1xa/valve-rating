### Roster Details<br />
Team Name: Sharks<br />
Roster: doc, gafolo, koala, pepe, rdnzao<br />
Global Rank: [55](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [14]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1023.4<br />
<br />
Final Rank Value (1023.4) = Starting Rank Value (971.8) + Head To Head Adjustments (51.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.397[<sup>1</sup>](#table2)
- Bounty Collected: 0.426[<sup>2</sup>](#table1)
- Opponent Network: 0.292[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.279<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 971.8
- 400 + ( ( 0.279 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 971.8


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
|           93 |      106 | 2024-08-02 | paiN              | L   | 1.000      | -            | -                | -                | -         |    -3.52 | doc, gafolo, koala, pepe, rdnzao |
|           92 |      136 | 2024-08-01 | Hype              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.08 | doc, gafolo, koala, pepe, rdnzao |
|           91 |      144 | 2024-08-01 | paiN              | L   | 1.000      | -            | -                | -                | -         |    -3.48 | doc, gafolo, koala, pepe, rdnzao |
|           90 |      177 | 2024-07-31 | MIBR              | L   | 1.000      | -            | -                | -                | -         |    -4.63 | doc, gafolo, koala, pepe, rdnzao |
|           89 |      187 | 2024-07-31 | Solid             | W   | 1.000      | 0.371        | -                | 0.825 (0.306)    | 0 (0.000) |    12.32 | doc, gafolo, koala, pepe, rdnzao |
|           88 |      221 | 2024-07-30 | Hype              | W   | 1.000      | -            | -                | -                | 0 (0.000) |    10.27 | doc, gafolo, koala, pepe, rdnzao |
|           87 |      294 | 2024-07-28 | Bad News Chickens | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.49 | doc, gafolo, koala, pepe, rdnzao |
|           86 |      342 | 2024-07-26 | Imperial          | L   | 1.000      | -            | -                | -                | -         |    -8.57 | doc, gafolo, koala, pepe, rdnzao |
|           85 |      369 | 2024-07-25 | BESTIA            | W   | 1.000      | -            | -                | -                | 0 (0.000) |    16.14 | doc, gafolo, koala, pepe, rdnzao |
|           84 |      376 | 2024-07-25 | Patins da Ferrari | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.23 | doc, gafolo, koala, pepe, rdnzao |
|           83 |      418 | 2024-07-24 | Bad News Chickens | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.43 | doc, gafolo, koala, pepe, rdnzao |
|           82 |      425 | 2024-07-24 | Yawara            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.02 | doc, gafolo, koala, pepe, rdnzao |
|           81 |      445 | 2024-07-23 | ODDIK             | L   | 1.000      | -            | -                | -                | -         |   -14.06 | doc, gafolo, koala, pepe, rdnzao |
|           80 |      448 | 2024-07-23 | W7M               | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.16 | doc, gafolo, koala, pepe, rdnzao |
|           79 |      534 | 2024-07-20 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |    -7.60 | doc, gafolo, koala, pepe, rdnzao |
|           78 |      587 | 2024-07-19 | Hype              | W   | 1.000      | -            | -                | -                | 0 (0.000) |    12.52 | doc, gafolo, koala, pepe, rdnzao |
|           77 |      612 | 2024-07-18 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |    -8.04 | doc, gafolo, koala, pepe, rdnzao |
|           76 |      614 | 2024-07-18 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |    -8.61 | doc, gafolo, koala, pepe, rdnzao |
|           75 |      677 | 2024-07-17 | ODDIK             | W   | 1.000      | 0.450        | 0.099 (0.045)    | 0.822 (0.370)    | -         |    17.43 | doc, gafolo, koala, pepe, rdnzao |
|           74 |      688 | 2024-07-17 | ODDIK             | W   | 1.000      | 0.450        | 0.099 (0.045)    | 0.822 (0.370)    | -         |    19.00 | doc, gafolo, koala, pepe, rdnzao |
|           73 |      742 | 2024-07-16 | RED Canids        | L   | 1.000      | -            | -                | -                | -         |    -7.84 | doc, gafolo, koala, pepe, rdnzao |
|           72 |      748 | 2024-07-16 | RED Canids        | L   | 1.000      | -            | -                | -                | -         |    -8.39 | doc, gafolo, koala, pepe, rdnzao |
|           71 |      792 | 2024-07-15 | KRÜ               | L   | 1.000      | -            | -                | -                | -         |   -20.58 | doc, gafolo, koala, pepe, rdnzao |
|           70 |      796 | 2024-07-15 | KRÜ               | W   | 1.000      | 0.450        | -                | 0.488 (0.220)    | -         |    10.53 | doc, gafolo, koala, pepe, rdnzao |
|           69 |      868 | 2024-07-11 | Bounty Hunters    | L   | 1.000      | -            | -                | -                | -         |   -16.69 | doc, gafolo, koala, pepe, rdnzao |
|           68 |      883 | 2024-07-10 | BESTIA            | W   | 1.000      | 0.371        | 0.096 (0.035)    | 0.792 (0.294)    | -         |    16.99 | doc, gafolo, koala, pepe, rdnzao |
|           67 |      903 | 2024-07-09 | KRÜ               | L   | 1.000      | -            | -                | -                | -         |   -21.07 | doc, gafolo, koala, pepe, rdnzao |
|           66 |      925 | 2024-07-08 | Patins da Ferrari | W   | 1.000      | -            | -                | -                | -         |     8.95 | doc, gafolo, koala, pepe, rdnzao |
|           65 |      961 | 2024-06-30 | Patins da Ferrari | L   | 0.959      | -            | -                | -                | -         |   -21.70 | doc, gafolo, koala, pepe, rdnzao |
|           64 |      975 | 2024-06-28 | KRÜ               | W   | 0.946      | -            | -                | -                | -         |     8.94 | doc, gafolo, koala, pepe, rdnzao |
|           63 |      976 | 2024-06-28 | Bounty Hunters    | L   | 0.945      | -            | -                | -                | -         |   -18.39 | doc, gafolo, koala, pepe, rdnzao |
|           62 |      980 | 2024-06-27 | Galorys           | W   | 0.939      | -            | -                | -                | -         |     8.61 | doc, gafolo, koala, pepe, rdnzao |
|           61 |      983 | 2024-06-27 | inSanitY          | L   | 0.938      | -            | -                | -                | -         |   -15.67 | doc, gafolo, koala, pepe, rdnzao |
|           60 |     1084 | 2024-06-14 | Fluxo             | L   | 0.852      | -            | -                | -                | -         |   -11.50 | doc, gafolo, koala, pepe, rdnzao |
|           59 |     1206 | 2024-06-10 | Vikings KR        | W   | 0.824      | -            | -                | -                | -         |     5.30 | doc, gafolo, koala, pepe, rdnzao |
|           58 |     1239 | 2024-06-09 | paiN              | L   | 0.818      | -            | -                | -                | -         |    -4.14 | doc, gafolo, koala, pepe, rdnzao |
|           57 |     1258 | 2024-06-09 | BESTIA            | W   | 0.817      | 0.450        | 0.096 (0.035)    | 0.792 (0.291)    | -         |    12.58 | doc, gafolo, koala, pepe, rdnzao |
|           56 |     1310 | 2024-06-08 | Hype              | W   | 0.811      | -            | -                | -                | -         |     8.67 | doc, gafolo, koala, pepe, rdnzao |
|           55 |     1325 | 2024-06-08 | Patins da Ferrari | L   | 0.810      | -            | -                | -                | -         |   -19.90 | doc, gafolo, koala, pepe, rdnzao |
|           54 |     1352 | 2024-06-07 | 9z                | L   | 0.806      | -            | -                | -                | -         |    -2.18 | doc, gafolo, koala, pepe, rdnzao |
|           53 |     1411 | 2024-06-06 | paiN              | W   | 0.799      | 0.450        | 0.325 (0.117)    | 0.857 (0.308)    | -         |    21.41 | doc, gafolo, koala, pepe, rdnzao |
|           52 |     1480 | 2024-06-05 | Imperial          | L   | 0.792      | -            | -                | -                | -         |    -4.90 | doc, gafolo, koala, pepe, rdnzao |
|           51 |     1530 | 2024-06-04 | BESTIA            | W   | 0.786      | 0.450        | 0.096 (0.034)    | 0.792 (0.280)    | -         |    13.89 | doc, gafolo, koala, pepe, rdnzao |
|           50 |     1857 | 2024-05-22 | Imperial          | W   | 0.698      | 0.450        | 0.234 (0.074)    | -                | -         |    17.70 | doc, drg, gafolo, pepe, rdnzao   |
|           49 |     1861 | 2024-05-22 | Imperial          | L   | 0.698      | -            | -                | -                | -         |    -4.17 | doc, drg, gafolo, pepe, rdnzao   |
|           48 |     1888 | 2024-05-21 | Case              | L   | 0.693      | -            | -                | -                | -         |   -13.40 | doc, drg, gafolo, pepe, rdnzao   |
|           47 |     1889 | 2024-05-21 | Case              | W   | 0.693      | 0.450        | -                | 0.795 (0.248)    | -         |     8.48 | doc, drg, gafolo, pepe, rdnzao   |
|           46 |     1893 | 2024-05-21 | RED Canids        | W   | 0.693      | 0.450        | 0.077 (0.024)    | 0.748 (0.233)    | -         |    15.19 | doc, drg, gafolo, pepe, rdnzao   |
|           45 |     1895 | 2024-05-21 | RED Canids        | L   | 0.692      | -            | -                | -                | -         |    -6.58 | doc, drg, gafolo, pepe, rdnzao   |
|           44 |     2026 | 2024-05-17 | ODDIK             | L   | 0.665      | -            | -                | -                | -         |   -12.26 | doc, drg, gafolo, rdnzao, togs   |
|           43 |     2051 | 2024-05-16 | W7M               | W   | 0.659      | -            | -                | -                | -         |     4.83 | doc, drg, gafolo, rdnzao, togs   |
|           42 |     2054 | 2024-05-16 | W7M               | W   | 0.659      | -            | -                | -                | -         |     5.04 | doc, drg, gafolo, rdnzao, togs   |
|           41 |     2059 | 2024-05-16 | Hype              | W   | 0.658      | -            | -                | -                | -         |     7.32 | doc, drg, gafolo, rdnzao, togs   |
|           40 |     2098 | 2024-05-15 | Vikings KR        | W   | 0.653      | -            | -                | -                | -         |     5.78 | doc, drg, gafolo, rdnzao, togs   |
|           39 |     2106 | 2024-05-15 | 9z                | L   | 0.652      | -            | -                | -                | -         |    -1.03 | doc, drg, gafolo, rdnzao, togs   |
|           38 |     2165 | 2024-05-14 | Fluxo             | L   | 0.645      | -            | -                | -                | -         |    -7.15 | doc, drg, gafolo, rdnzao, togs   |
|           37 |     2192 | 2024-05-13 | RED Canids        | W   | 0.639      | 0.384        | 0.077 (0.019)    | -                | -         |    13.05 | doc, drg, gafolo, rdnzao, togs   |
|           36 |     2199 | 2024-05-13 | W7M               | W   | 0.638      | -            | -                | -                | -         |     5.75 | doc, drg, gafolo, rdnzao, togs   |
|           35 |     2247 | 2024-05-11 | W7M               | W   | 0.625      | -            | -                | -                | -         |     5.90 | doc, drg, gafolo, rdnzao, togs   |
|           34 |     2291 | 2024-05-09 | BESTIA            | L   | 0.613      | -            | -                | -                | -         |   -10.59 | doc, drg, gafolo, rdnzao, togs   |
|           33 |     2311 | 2024-05-08 | 9z                | L   | 0.606      | -            | -                | -                | -         |    -0.88 | doc, drg, gafolo, rdnzao, togs   |
|           32 |     2349 | 2024-05-06 | BESTIA            | W   | 0.593      | 0.435        | 0.096 (0.025)    | -                | -         |     8.36 | doc, drg, gafolo, rdnzao, togs   |
|           31 |     2948 | 2024-04-11 | paiN              | L   | 0.425      | -            | -                | -                | -         |    -1.07 | doc, drg, gafolo, rdnzao, togs   |
|           30 |     3211 | 2024-04-03 | 2GAME             | W   | 0.373      | -            | -                | -                | -         |     1.83 | doc, drg, gafolo, rdnzao, togs   |
|           29 |     3214 | 2024-04-03 | 2GAME             | W   | 0.372      | -            | -                | -                | -         |     1.86 | doc, drg, gafolo, rdnzao, togs   |
|           28 |     3583 | 2024-03-14 | MIBR              | L   | 0.240      | -            | -                | -                | -         |    -0.63 | doc, drg, gafolo, rdnzao, togs   |
|           27 |     3585 | 2024-03-14 | MIBR              | L   | 0.240      | -            | -                | -                | -         |    -0.64 | doc, drg, gafolo, rdnzao, togs   |
|           26 |     3613 | 2024-03-13 | Yawara            | W   | 0.233      | -            | -                | -                | -         |     0.54 | doc, drg, gafolo, rdnzao, togs   |
|           25 |     3616 | 2024-03-13 | ODDIK             | W   | 0.232      | -            | -                | -                | -         |     3.88 | doc, drg, gafolo, rdnzao, togs   |
|           24 |     3689 | 2024-03-11 | Fluxo             | L   | 0.217      | -            | -                | -                | -         |    -2.72 | doc, drg, gafolo, rdnzao, togs   |
|           23 |     3717 | 2024-03-09 | Case              | L   | 0.205      | -            | -                | -                | -         |    -3.67 | doc, drg, gafolo, rdnzao, togs   |
|           22 |     3781 | 2024-03-07 | Corinthians       | W   | 0.190      | -            | -                | -                | -         |     0.41 | doc, drg, gafolo, rdnzao, togs   |
|           21 |     3835 | 2024-03-05 | Solid             | W   | 0.178      | -            | -                | -                | -         |     2.21 | doc, drg, gafolo, rdnzao, togs   |
|           20 |     3841 | 2024-03-05 | Solid             | W   | 0.178      | -            | -                | -                | -         |     2.24 | doc, drg, gafolo, rdnzao, togs   |
|           19 |     4035 | 2024-02-24 | Galorys           | W   | 0.113      | -            | -                | -                | -         |     1.40 | doc, drg, gafolo, rdnzao, togs   |
|           18 |     4043 | 2024-02-24 | Galorys           | W   | 0.113      | -            | -                | -                | -         |     1.41 | doc, drg, gafolo, rdnzao, togs   |
|           17 |     4047 | 2024-02-24 | Fluxo             | L   | 0.112      | -            | -                | -                | -         |    -1.40 | doc, drg, gafolo, rdnzao, togs   |
|           16 |     4100 | 2024-02-21 | Corinthians       | W   | 0.093      | -            | -                | -                | -         |     0.20 | doc, drg, gafolo, rdnzao, togs   |
|           15 |     4105 | 2024-02-21 | Case              | W   | 0.092      | -            | -                | -                | -         |     1.33 | doc, drg, gafolo, rdnzao, togs   |
|           14 |     4110 | 2024-02-21 | Galorys           | W   | 0.091      | -            | -                | -                | -         |     1.17 | doc, drg, gafolo, rdnzao, togs   |
|           13 |     4135 | 2024-02-20 | Flamengo          | L   | 0.086      | -            | -                | -                | -         |    -2.52 | doc, drg, gafolo, rdnzao, togs   |
|           12 |     4140 | 2024-02-20 | Case              | W   | 0.084      | -            | -                | -                | -         |     1.22 | doc, drg, gafolo, rdnzao, togs   |
|           11 |     4164 | 2024-02-19 | Solid             | W   | 0.078      | -            | -                | -                | -         |     0.99 | doc, drg, gafolo, rdnzao, togs   |
|           10 |     4178 | 2024-02-18 | Galorys           | W   | 0.073      | -            | -                | -                | -         |     0.95 | doc, drg, gafolo, rdnzao, togs   |
|            9 |     4201 | 2024-02-17 | W7M               | L   | 0.066      | -            | -                | -                | -         |    -1.40 | doc, drg, gafolo, rdnzao, togs   |
|            8 |     4206 | 2024-02-17 | Galorys           | L   | 0.065      | -            | -                | -                | -         |    -1.22 | doc, drg, gafolo, rdnzao, togs   |
|            7 |     4241 | 2024-02-16 | W7M               | W   | 0.058      | -            | -                | -                | -         |     0.59 | doc, drg, gafolo, rdnzao, togs   |
|            6 |     4259 | 2024-02-15 | Case              | L   | 0.052      | -            | -                | -                | -         |    -0.90 | doc, drg, gafolo, rdnzao, togs   |
|            5 |     4265 | 2024-02-15 | Fluxo             | L   | 0.051      | -            | -                | -                | -         |    -0.64 | doc, drg, gafolo, rdnzao, togs   |
|            4 |     4266 | 2024-02-15 | Fluxo             | L   | 0.051      | -            | -                | -                | -         |    -0.64 | doc, drg, gafolo, rdnzao, togs   |
|            3 |     4294 | 2024-02-14 | Hype              | W   | 0.046      | -            | -                | -                | -         |     0.06 | doc, drg, gafolo, rdnzao, togs   |
|            2 |     4305 | 2024-02-14 | Galorys           | W   | 0.044      | -            | -                | -                | -         |     0.57 | doc, drg, gafolo, rdnzao, togs   |
|            1 |     4349 | 2024-02-12 | Solid             | W   | 0.032      | -            | -                | -                | -         |     0.41 | doc, drg, gafolo, rdnzao, togs   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($9,686.64)
- Divide that value by the 5th highest value among all rosters ($321,345.23)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-02 |      1.000 | $750.00        | $750.00         |
| 2024-06-28 |      0.945 | $500.00        | $472.33         |
| 2024-06-16 |      0.865 | $2,500.00      | $2,161.81       |
| 2024-06-10 |      0.826 | $750.00        | $619.50         |
| 2024-06-09 |      0.819 | $5,000.00      | $4,093.98       |
| 2024-05-19 |      0.678 | $1,000.00      | $678.06         |
| 2024-02-25 |      0.119 | $5,000.00      | $593.06         |
| 2024-02-21 |      0.091 | $3,500.00      | $317.92         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
