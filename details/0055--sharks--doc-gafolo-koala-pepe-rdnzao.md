### Roster Details<br />
Team Name: Sharks<br />
Roster: doc, gafolo, koala, pepe, rdnzao<br />
Global Rank: [55](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [14]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1023.2<br />
<br />
Final Rank Value (1023.2) = Starting Rank Value (971.7) + Head To Head Adjustments (51.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.397[<sup>1</sup>](#table2)
- Bounty Collected: 0.426[<sup>2</sup>](#table1)
- Opponent Network: 0.292[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.279<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 971.7
- 400 + ( ( 0.279 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 971.7


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
|           93 |      110 | 2024-08-02 | paiN              | L   | 1.000      | -            | -                | -                | -         |    -3.52 | doc, gafolo, koala, pepe, rdnzao |
|           92 |      140 | 2024-08-01 | Hype              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.09 | doc, gafolo, koala, pepe, rdnzao |
|           91 |      148 | 2024-08-01 | paiN              | L   | 1.000      | -            | -                | -                | -         |    -3.49 | doc, gafolo, koala, pepe, rdnzao |
|           90 |      181 | 2024-07-31 | MIBR              | L   | 1.000      | -            | -                | -                | -         |    -4.63 | doc, gafolo, koala, pepe, rdnzao |
|           89 |      191 | 2024-07-31 | Solid             | W   | 1.000      | 0.371        | -                | 0.825 (0.306)    | 0 (0.000) |    12.33 | doc, gafolo, koala, pepe, rdnzao |
|           88 |      225 | 2024-07-30 | Hype              | W   | 1.000      | -            | -                | -                | 0 (0.000) |    10.28 | doc, gafolo, koala, pepe, rdnzao |
|           87 |      298 | 2024-07-28 | Bad News Chickens | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.49 | doc, gafolo, koala, pepe, rdnzao |
|           86 |      346 | 2024-07-26 | Imperial          | L   | 1.000      | -            | -                | -                | -         |    -8.59 | doc, gafolo, koala, pepe, rdnzao |
|           85 |      373 | 2024-07-25 | BESTIA            | W   | 1.000      | -            | -                | -                | 0 (0.000) |    16.14 | doc, gafolo, koala, pepe, rdnzao |
|           84 |      380 | 2024-07-25 | Patins da Ferrari | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.23 | doc, gafolo, koala, pepe, rdnzao |
|           83 |      422 | 2024-07-24 | Bad News Chickens | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.44 | doc, gafolo, koala, pepe, rdnzao |
|           82 |      429 | 2024-07-24 | Yawara            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.02 | doc, gafolo, koala, pepe, rdnzao |
|           81 |      449 | 2024-07-23 | ODDIK             | L   | 1.000      | -            | -                | -                | -         |   -14.06 | doc, gafolo, koala, pepe, rdnzao |
|           80 |      452 | 2024-07-23 | W7M               | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.17 | doc, gafolo, koala, pepe, rdnzao |
|           79 |      538 | 2024-07-20 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |    -7.61 | doc, gafolo, koala, pepe, rdnzao |
|           78 |      591 | 2024-07-19 | Hype              | W   | 1.000      | -            | -                | -                | 0 (0.000) |    12.54 | doc, gafolo, koala, pepe, rdnzao |
|           77 |      616 | 2024-07-18 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |    -8.05 | doc, gafolo, koala, pepe, rdnzao |
|           76 |      618 | 2024-07-18 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |    -8.62 | doc, gafolo, koala, pepe, rdnzao |
|           75 |      681 | 2024-07-17 | ODDIK             | W   | 1.000      | 0.450        | 0.099 (0.045)    | 0.823 (0.370)    | -         |    17.44 | doc, gafolo, koala, pepe, rdnzao |
|           74 |      692 | 2024-07-17 | ODDIK             | W   | 1.000      | 0.450        | 0.099 (0.045)    | 0.823 (0.370)    | -         |    19.01 | doc, gafolo, koala, pepe, rdnzao |
|           73 |      746 | 2024-07-16 | RED Canids        | L   | 1.000      | -            | -                | -                | -         |    -7.86 | doc, gafolo, koala, pepe, rdnzao |
|           72 |      752 | 2024-07-16 | RED Canids        | L   | 1.000      | -            | -                | -                | -         |    -8.40 | doc, gafolo, koala, pepe, rdnzao |
|           71 |      796 | 2024-07-15 | KRÜ               | L   | 1.000      | -            | -                | -                | -         |   -20.57 | doc, gafolo, koala, pepe, rdnzao |
|           70 |      800 | 2024-07-15 | KRÜ               | W   | 1.000      | 0.450        | -                | 0.489 (0.220)    | -         |    10.54 | doc, gafolo, koala, pepe, rdnzao |
|           69 |      872 | 2024-07-11 | Bounty Hunters    | L   | 1.000      | -            | -                | -                | -         |   -16.69 | doc, gafolo, koala, pepe, rdnzao |
|           68 |      887 | 2024-07-10 | BESTIA            | W   | 1.000      | 0.371        | 0.096 (0.035)    | 0.793 (0.294)    | -         |    16.99 | doc, gafolo, koala, pepe, rdnzao |
|           67 |      907 | 2024-07-09 | KRÜ               | L   | 1.000      | -            | -                | -                | -         |   -21.06 | doc, gafolo, koala, pepe, rdnzao |
|           66 |      929 | 2024-07-08 | Patins da Ferrari | W   | 1.000      | -            | -                | -                | -         |     8.95 | doc, gafolo, koala, pepe, rdnzao |
|           65 |      965 | 2024-06-30 | Patins da Ferrari | L   | 0.956      | -            | -                | -                | -         |   -21.64 | doc, gafolo, koala, pepe, rdnzao |
|           64 |      979 | 2024-06-28 | KRÜ               | W   | 0.943      | -            | -                | -                | -         |     8.93 | doc, gafolo, koala, pepe, rdnzao |
|           63 |      980 | 2024-06-28 | Bounty Hunters    | L   | 0.942      | -            | -                | -                | -         |   -18.33 | doc, gafolo, koala, pepe, rdnzao |
|           62 |      984 | 2024-06-27 | Galorys           | W   | 0.937      | -            | -                | -                | -         |     8.60 | doc, gafolo, koala, pepe, rdnzao |
|           61 |      987 | 2024-06-27 | inSanitY          | L   | 0.935      | -            | -                | -                | -         |   -15.63 | doc, gafolo, koala, pepe, rdnzao |
|           60 |     1088 | 2024-06-14 | Fluxo             | L   | 0.849      | -            | -                | -                | -         |   -11.47 | doc, gafolo, koala, pepe, rdnzao |
|           59 |     1210 | 2024-06-10 | Vikings KR        | W   | 0.821      | -            | -                | -                | -         |     5.30 | doc, gafolo, koala, pepe, rdnzao |
|           58 |     1243 | 2024-06-09 | paiN              | L   | 0.816      | -            | -                | -                | -         |    -4.14 | doc, gafolo, koala, pepe, rdnzao |
|           57 |     1262 | 2024-06-09 | BESTIA            | W   | 0.814      | 0.450        | 0.096 (0.035)    | 0.793 (0.291)    | -         |    12.55 | doc, gafolo, koala, pepe, rdnzao |
|           56 |     1314 | 2024-06-08 | Hype              | W   | 0.809      | -            | -                | -                | -         |     8.66 | doc, gafolo, koala, pepe, rdnzao |
|           55 |     1329 | 2024-06-08 | Patins da Ferrari | L   | 0.808      | -            | -                | -                | -         |   -19.83 | doc, gafolo, koala, pepe, rdnzao |
|           54 |     1356 | 2024-06-07 | 9z                | L   | 0.803      | -            | -                | -                | -         |    -2.17 | doc, gafolo, koala, pepe, rdnzao |
|           53 |     1415 | 2024-06-06 | paiN              | W   | 0.797      | 0.450        | 0.324 (0.116)    | 0.857 (0.307)    | -         |    21.34 | doc, gafolo, koala, pepe, rdnzao |
|           52 |     1484 | 2024-06-05 | Imperial          | L   | 0.790      | -            | -                | -                | -         |    -4.91 | doc, gafolo, koala, pepe, rdnzao |
|           51 |     1534 | 2024-06-04 | BESTIA            | W   | 0.783      | 0.450        | 0.096 (0.034)    | 0.793 (0.280)    | -         |    13.85 | doc, gafolo, koala, pepe, rdnzao |
|           50 |     1861 | 2024-05-22 | Imperial          | W   | 0.696      | 0.450        | 0.233 (0.073)    | -                | -         |    17.62 | doc, drg, gafolo, pepe, rdnzao   |
|           49 |     1865 | 2024-05-22 | Imperial          | L   | 0.695      | -            | -                | -                | -         |    -4.17 | doc, drg, gafolo, pepe, rdnzao   |
|           48 |     1892 | 2024-05-21 | Case              | L   | 0.691      | -            | -                | -                | -         |   -13.35 | doc, drg, gafolo, pepe, rdnzao   |
|           47 |     1893 | 2024-05-21 | Case              | W   | 0.690      | 0.450        | -                | 0.795 (0.247)    | -         |     8.46 | doc, drg, gafolo, pepe, rdnzao   |
|           46 |     1897 | 2024-05-21 | RED Canids        | W   | 0.690      | 0.450        | 0.076 (0.024)    | 0.748 (0.232)    | -         |    15.12 | doc, drg, gafolo, pepe, rdnzao   |
|           45 |     1899 | 2024-05-21 | RED Canids        | L   | 0.690      | -            | -                | -                | -         |    -6.57 | doc, drg, gafolo, pepe, rdnzao   |
|           44 |     2030 | 2024-05-17 | ODDIK             | L   | 0.662      | -            | -                | -                | -         |   -12.21 | doc, drg, gafolo, rdnzao, togs   |
|           43 |     2055 | 2024-05-16 | W7M               | W   | 0.657      | -            | -                | -                | -         |     4.82 | doc, drg, gafolo, rdnzao, togs   |
|           42 |     2058 | 2024-05-16 | W7M               | W   | 0.657      | -            | -                | -                | -         |     5.03 | doc, drg, gafolo, rdnzao, togs   |
|           41 |     2063 | 2024-05-16 | Hype              | W   | 0.656      | -            | -                | -                | -         |     7.30 | doc, drg, gafolo, rdnzao, togs   |
|           40 |     2102 | 2024-05-15 | Vikings KR        | W   | 0.650      | -            | -                | -                | -         |     5.76 | doc, drg, gafolo, rdnzao, togs   |
|           39 |     2110 | 2024-05-15 | 9z                | L   | 0.649      | -            | -                | -                | -         |    -1.03 | doc, drg, gafolo, rdnzao, togs   |
|           38 |     2169 | 2024-05-14 | Fluxo             | L   | 0.643      | -            | -                | -                | -         |    -7.13 | doc, drg, gafolo, rdnzao, togs   |
|           37 |     2196 | 2024-05-13 | RED Canids        | W   | 0.636      | 0.384        | 0.076 (0.019)    | -                | -         |    12.99 | doc, drg, gafolo, rdnzao, togs   |
|           36 |     2203 | 2024-05-13 | W7M               | W   | 0.635      | -            | -                | -                | -         |     5.73 | doc, drg, gafolo, rdnzao, togs   |
|           35 |     2251 | 2024-05-11 | W7M               | W   | 0.622      | -            | -                | -                | -         |     5.88 | doc, drg, gafolo, rdnzao, togs   |
|           34 |     2295 | 2024-05-09 | BESTIA            | L   | 0.610      | -            | -                | -                | -         |   -10.54 | doc, drg, gafolo, rdnzao, togs   |
|           33 |     2315 | 2024-05-08 | 9z                | L   | 0.604      | -            | -                | -                | -         |    -0.88 | doc, drg, gafolo, rdnzao, togs   |
|           32 |     2353 | 2024-05-06 | BESTIA            | W   | 0.590      | 0.435        | 0.096 (0.025)    | -                | -         |     8.34 | doc, drg, gafolo, rdnzao, togs   |
|           31 |     2952 | 2024-04-11 | paiN              | L   | 0.423      | -            | -                | -                | -         |    -1.07 | doc, drg, gafolo, rdnzao, togs   |
|           30 |     3215 | 2024-04-03 | 2GAME             | W   | 0.370      | -            | -                | -                | -         |     1.82 | doc, drg, gafolo, rdnzao, togs   |
|           29 |     3218 | 2024-04-03 | 2GAME             | W   | 0.370      | -            | -                | -                | -         |     1.85 | doc, drg, gafolo, rdnzao, togs   |
|           28 |     3587 | 2024-03-14 | MIBR              | L   | 0.237      | -            | -                | -                | -         |    -0.63 | doc, drg, gafolo, rdnzao, togs   |
|           27 |     3589 | 2024-03-14 | MIBR              | L   | 0.237      | -            | -                | -                | -         |    -0.63 | doc, drg, gafolo, rdnzao, togs   |
|           26 |     3617 | 2024-03-13 | Yawara            | W   | 0.230      | -            | -                | -                | -         |     0.53 | doc, drg, gafolo, rdnzao, togs   |
|           25 |     3620 | 2024-03-13 | ODDIK             | W   | 0.230      | -            | -                | -                | -         |     3.84 | doc, drg, gafolo, rdnzao, togs   |
|           24 |     3693 | 2024-03-11 | Fluxo             | L   | 0.214      | -            | -                | -                | -         |    -2.69 | doc, drg, gafolo, rdnzao, togs   |
|           23 |     3721 | 2024-03-09 | Case              | L   | 0.203      | -            | -                | -                | -         |    -3.63 | doc, drg, gafolo, rdnzao, togs   |
|           22 |     3785 | 2024-03-07 | Corinthians       | W   | 0.188      | -            | -                | -                | -         |     0.40 | doc, drg, gafolo, rdnzao, togs   |
|           21 |     3839 | 2024-03-05 | Solid             | W   | 0.176      | -            | -                | -                | -         |     2.18 | doc, drg, gafolo, rdnzao, togs   |
|           20 |     3845 | 2024-03-05 | Solid             | W   | 0.176      | -            | -                | -                | -         |     2.21 | doc, drg, gafolo, rdnzao, togs   |
|           19 |     4039 | 2024-02-24 | Galorys           | W   | 0.111      | -            | -                | -                | -         |     1.37 | doc, drg, gafolo, rdnzao, togs   |
|           18 |     4047 | 2024-02-24 | Galorys           | W   | 0.110      | -            | -                | -                | -         |     1.38 | doc, drg, gafolo, rdnzao, togs   |
|           17 |     4051 | 2024-02-24 | Fluxo             | L   | 0.109      | -            | -                | -                | -         |    -1.37 | doc, drg, gafolo, rdnzao, togs   |
|           16 |     4104 | 2024-02-21 | Corinthians       | W   | 0.091      | -            | -                | -                | -         |     0.20 | doc, drg, gafolo, rdnzao, togs   |
|           15 |     4109 | 2024-02-21 | Case              | W   | 0.090      | -            | -                | -                | -         |     1.30 | doc, drg, gafolo, rdnzao, togs   |
|           14 |     4114 | 2024-02-21 | Galorys           | W   | 0.088      | -            | -                | -                | -         |     1.14 | doc, drg, gafolo, rdnzao, togs   |
|           13 |     4139 | 2024-02-20 | Flamengo          | L   | 0.083      | -            | -                | -                | -         |    -2.45 | doc, drg, gafolo, rdnzao, togs   |
|           12 |     4144 | 2024-02-20 | Case              | W   | 0.081      | -            | -                | -                | -         |     1.18 | doc, drg, gafolo, rdnzao, togs   |
|           11 |     4168 | 2024-02-19 | Solid             | W   | 0.075      | -            | -                | -                | -         |     0.96 | doc, drg, gafolo, rdnzao, togs   |
|           10 |     4182 | 2024-02-18 | Galorys           | W   | 0.070      | -            | -                | -                | -         |     0.91 | doc, drg, gafolo, rdnzao, togs   |
|            9 |     4205 | 2024-02-17 | W7M               | L   | 0.064      | -            | -                | -                | -         |    -1.35 | doc, drg, gafolo, rdnzao, togs   |
|            8 |     4210 | 2024-02-17 | Galorys           | L   | 0.063      | -            | -                | -                | -         |    -1.17 | doc, drg, gafolo, rdnzao, togs   |
|            7 |     4245 | 2024-02-16 | W7M               | W   | 0.055      | -            | -                | -                | -         |     0.57 | doc, drg, gafolo, rdnzao, togs   |
|            6 |     4263 | 2024-02-15 | Case              | L   | 0.050      | -            | -                | -                | -         |    -0.85 | doc, drg, gafolo, rdnzao, togs   |
|            5 |     4269 | 2024-02-15 | Fluxo             | L   | 0.049      | -            | -                | -                | -         |    -0.61 | doc, drg, gafolo, rdnzao, togs   |
|            4 |     4270 | 2024-02-15 | Fluxo             | L   | 0.049      | -            | -                | -                | -         |    -0.61 | doc, drg, gafolo, rdnzao, togs   |
|            3 |     4298 | 2024-02-14 | Hype              | W   | 0.044      | -            | -                | -                | -         |     0.05 | doc, drg, gafolo, rdnzao, togs   |
|            2 |     4309 | 2024-02-14 | Galorys           | W   | 0.042      | -            | -                | -                | -         |     0.54 | doc, drg, gafolo, rdnzao, togs   |
|            1 |     4353 | 2024-02-12 | Solid             | W   | 0.030      | -            | -                | -                | -         |     0.38 | doc, drg, gafolo, rdnzao, togs   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($9,641.01)
- Divide that value by the 5th highest value among all rosters ($320,603.98)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-02 |      1.000 | $750.00        | $750.00         |
| 2024-06-28 |      0.942 | $500.00        | $471.08         |
| 2024-06-16 |      0.862 | $2,500.00      | $2,155.56       |
| 2024-06-10 |      0.823 | $750.00        | $617.62         |
| 2024-06-09 |      0.816 | $5,000.00      | $4,081.48       |
| 2024-05-19 |      0.676 | $1,000.00      | $675.56         |
| 2024-02-25 |      0.116 | $5,000.00      | $580.56         |
| 2024-02-21 |      0.088 | $3,500.00      | $309.17         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
