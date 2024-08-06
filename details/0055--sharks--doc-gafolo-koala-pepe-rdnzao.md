### Roster Details<br />
Team Name: Sharks<br />
Roster: doc, gafolo, koala, pepe, rdnzao<br />
Global Rank: [55](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [14]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1021.9<br />
<br />
Final Rank Value (1021.9) = Starting Rank Value (969.7) + Head To Head Adjustments (52.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.396[<sup>1</sup>](#table2)
- Bounty Collected: 0.426[<sup>2</sup>](#table1)
- Opponent Network: 0.285[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.277<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 969.7
- 400 + ( ( 0.277 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 969.7


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
|           93 |      116 | 2024-08-02 | paiN              | L   | 1.000      | -            | -                | -                | -         |    -3.52 | doc, gafolo, koala, pepe, rdnzao |
|           92 |      146 | 2024-08-01 | Hype              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.10 | doc, gafolo, koala, pepe, rdnzao |
|           91 |      154 | 2024-08-01 | paiN              | L   | 1.000      | -            | -                | -                | -         |    -3.49 | doc, gafolo, koala, pepe, rdnzao |
|           90 |      187 | 2024-07-31 | MIBR              | L   | 1.000      | -            | -                | -                | -         |    -4.63 | doc, gafolo, koala, pepe, rdnzao |
|           89 |      197 | 2024-07-31 | Solid             | W   | 1.000      | 0.371        | -                | 0.807 (0.299)    | 0 (0.000) |    12.34 | doc, gafolo, koala, pepe, rdnzao |
|           88 |      231 | 2024-07-30 | Hype              | W   | 1.000      | -            | -                | -                | 0 (0.000) |    10.29 | doc, gafolo, koala, pepe, rdnzao |
|           87 |      304 | 2024-07-28 | Bad News Chickens | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.51 | doc, gafolo, koala, pepe, rdnzao |
|           86 |      352 | 2024-07-26 | Imperial          | L   | 1.000      | -            | -                | -                | -         |    -8.57 | doc, gafolo, koala, pepe, rdnzao |
|           85 |      379 | 2024-07-25 | BESTIA            | W   | 1.000      | -            | -                | -                | 0 (0.000) |    16.14 | doc, gafolo, koala, pepe, rdnzao |
|           84 |      386 | 2024-07-25 | Patins da Ferrari | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.25 | doc, gafolo, koala, pepe, rdnzao |
|           83 |      428 | 2024-07-24 | Bad News Chickens | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.45 | doc, gafolo, koala, pepe, rdnzao |
|           82 |      435 | 2024-07-24 | Yawara            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     2.03 | doc, gafolo, koala, pepe, rdnzao |
|           81 |      455 | 2024-07-23 | ODDIK             | L   | 1.000      | -            | -                | -                | -         |   -14.05 | doc, gafolo, koala, pepe, rdnzao |
|           80 |      458 | 2024-07-23 | W7M               | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.18 | doc, gafolo, koala, pepe, rdnzao |
|           79 |      544 | 2024-07-20 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |    -7.61 | doc, gafolo, koala, pepe, rdnzao |
|           78 |      597 | 2024-07-19 | Hype              | W   | 1.000      | -            | -                | -                | 0 (0.000) |    12.55 | doc, gafolo, koala, pepe, rdnzao |
|           77 |      622 | 2024-07-18 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |    -8.05 | doc, gafolo, koala, pepe, rdnzao |
|           76 |      624 | 2024-07-18 | Fluxo             | L   | 1.000      | -            | -                | -                | -         |    -8.62 | doc, gafolo, koala, pepe, rdnzao |
|           75 |      687 | 2024-07-17 | ODDIK             | W   | 1.000      | 0.450        | 0.099 (0.045)    | 0.805 (0.362)    | -         |    17.45 | doc, gafolo, koala, pepe, rdnzao |
|           74 |      698 | 2024-07-17 | ODDIK             | W   | 1.000      | 0.450        | 0.099 (0.045)    | 0.805 (0.362)    | -         |    19.02 | doc, gafolo, koala, pepe, rdnzao |
|           73 |      752 | 2024-07-16 | RED Canids        | L   | 1.000      | -            | -                | -                | -         |    -7.85 | doc, gafolo, koala, pepe, rdnzao |
|           72 |      758 | 2024-07-16 | RED Canids        | L   | 1.000      | -            | -                | -                | -         |    -8.40 | doc, gafolo, koala, pepe, rdnzao |
|           71 |      802 | 2024-07-15 | KRÜ               | L   | 1.000      | -            | -                | -                | -         |   -20.57 | doc, gafolo, koala, pepe, rdnzao |
|           70 |      806 | 2024-07-15 | KRÜ               | W   | 1.000      | 0.450        | -                | 0.479 (0.215)    | -         |    10.54 | doc, gafolo, koala, pepe, rdnzao |
|           69 |      878 | 2024-07-11 | Bounty Hunters    | L   | 1.000      | -            | -                | -                | -         |   -16.69 | doc, gafolo, koala, pepe, rdnzao |
|           68 |      893 | 2024-07-10 | BESTIA            | W   | 1.000      | 0.371        | 0.096 (0.035)    | 0.776 (0.287)    | -         |    17.00 | doc, gafolo, koala, pepe, rdnzao |
|           67 |      913 | 2024-07-09 | KRÜ               | L   | 1.000      | -            | -                | -                | -         |   -21.06 | doc, gafolo, koala, pepe, rdnzao |
|           66 |      935 | 2024-07-08 | Patins da Ferrari | W   | 1.000      | -            | -                | -                | -         |     8.99 | doc, gafolo, koala, pepe, rdnzao |
|           65 |      971 | 2024-06-30 | Patins da Ferrari | L   | 0.956      | -            | -                | -                | -         |   -21.59 | doc, gafolo, koala, pepe, rdnzao |
|           64 |      985 | 2024-06-28 | KRÜ               | W   | 0.942      | -            | -                | -                | -         |     8.93 | doc, gafolo, koala, pepe, rdnzao |
|           63 |      986 | 2024-06-28 | Bounty Hunters    | L   | 0.942      | -            | -                | -                | -         |   -18.32 | doc, gafolo, koala, pepe, rdnzao |
|           62 |      990 | 2024-06-27 | Galorys           | W   | 0.936      | -            | -                | -                | -         |     8.61 | doc, gafolo, koala, pepe, rdnzao |
|           61 |      993 | 2024-06-27 | inSanitY          | L   | 0.935      | -            | -                | -                | -         |   -15.61 | doc, gafolo, koala, pepe, rdnzao |
|           60 |     1094 | 2024-06-14 | Fluxo             | L   | 0.849      | -            | -                | -                | -         |   -11.46 | doc, gafolo, koala, pepe, rdnzao |
|           59 |     1216 | 2024-06-10 | Vikings KR        | W   | 0.821      | -            | -                | -                | -         |     5.31 | doc, gafolo, koala, pepe, rdnzao |
|           58 |     1249 | 2024-06-09 | paiN              | L   | 0.815      | -            | -                | -                | -         |    -4.13 | doc, gafolo, koala, pepe, rdnzao |
|           57 |     1268 | 2024-06-09 | BESTIA            | W   | 0.814      | 0.450        | 0.096 (0.035)    | 0.776 (0.284)    | -         |    12.55 | doc, gafolo, koala, pepe, rdnzao |
|           56 |     1320 | 2024-06-08 | Hype              | W   | 0.808      | -            | -                | -                | -         |     8.66 | doc, gafolo, koala, pepe, rdnzao |
|           55 |     1335 | 2024-06-08 | Patins da Ferrari | L   | 0.807      | -            | -                | -                | -         |   -19.78 | doc, gafolo, koala, pepe, rdnzao |
|           54 |     1362 | 2024-06-07 | 9z                | L   | 0.803      | -            | -                | -                | -         |    -2.15 | doc, gafolo, koala, pepe, rdnzao |
|           53 |     1421 | 2024-06-06 | paiN              | W   | 0.796      | 0.450        | 0.324 (0.116)    | 0.838 (0.300)    | -         |    21.33 | doc, gafolo, koala, pepe, rdnzao |
|           52 |     1490 | 2024-06-05 | Imperial          | L   | 0.789      | -            | -                | -                | -         |    -4.88 | doc, gafolo, koala, pepe, rdnzao |
|           51 |     1540 | 2024-06-04 | BESTIA            | W   | 0.783      | 0.450        | 0.096 (0.034)    | 0.776 (0.273)    | -         |    13.85 | doc, gafolo, koala, pepe, rdnzao |
|           50 |     1867 | 2024-05-22 | Imperial          | W   | 0.695      | 0.450        | 0.233 (0.073)    | -                | -         |    17.62 | doc, drg, gafolo, pepe, rdnzao   |
|           49 |     1871 | 2024-05-22 | Imperial          | L   | 0.695      | -            | -                | -                | -         |    -4.15 | doc, drg, gafolo, pepe, rdnzao   |
|           48 |     1898 | 2024-05-21 | Case              | L   | 0.690      | -            | -                | -                | -         |   -13.32 | doc, drg, gafolo, pepe, rdnzao   |
|           47 |     1899 | 2024-05-21 | Case              | W   | 0.690      | 0.450        | -                | 0.778 (0.241)    | -         |     8.46 | doc, drg, gafolo, pepe, rdnzao   |
|           46 |     1903 | 2024-05-21 | RED Canids        | W   | 0.689      | 0.450        | 0.076 (0.024)    | 0.732 (0.227)    | -         |    15.12 | doc, drg, gafolo, pepe, rdnzao   |
|           45 |     1905 | 2024-05-21 | RED Canids        | L   | 0.689      | -            | -                | -                | -         |    -6.55 | doc, drg, gafolo, pepe, rdnzao   |
|           44 |     2036 | 2024-05-17 | ODDIK             | L   | 0.662      | -            | -                | -                | -         |   -12.18 | doc, drg, gafolo, rdnzao, togs   |
|           43 |     2061 | 2024-05-16 | W7M               | W   | 0.656      | -            | -                | -                | -         |     4.83 | doc, drg, gafolo, rdnzao, togs   |
|           42 |     2064 | 2024-05-16 | W7M               | W   | 0.656      | -            | -                | -                | -         |     5.04 | doc, drg, gafolo, rdnzao, togs   |
|           41 |     2069 | 2024-05-16 | Hype              | W   | 0.655      | -            | -                | -                | -         |     7.31 | doc, drg, gafolo, rdnzao, togs   |
|           40 |     2108 | 2024-05-15 | Vikings KR        | W   | 0.650      | -            | -                | -                | -         |     5.78 | doc, drg, gafolo, rdnzao, togs   |
|           39 |     2116 | 2024-05-15 | 9z                | L   | 0.649      | -            | -                | -                | -         |    -1.02 | doc, drg, gafolo, rdnzao, togs   |
|           38 |     2175 | 2024-05-14 | Fluxo             | L   | 0.642      | -            | -                | -                | -         |    -7.12 | doc, drg, gafolo, rdnzao, togs   |
|           37 |     2202 | 2024-05-13 | RED Canids        | W   | 0.636      | 0.384        | 0.076 (0.019)    | -                | -         |    12.99 | doc, drg, gafolo, rdnzao, togs   |
|           36 |     2209 | 2024-05-13 | W7M               | W   | 0.635      | -            | -                | -                | -         |     5.74 | doc, drg, gafolo, rdnzao, togs   |
|           35 |     2257 | 2024-05-11 | W7M               | W   | 0.622      | -            | -                | -                | -         |     5.89 | doc, drg, gafolo, rdnzao, togs   |
|           34 |     2301 | 2024-05-09 | BESTIA            | L   | 0.610      | -            | -                | -                | -         |   -10.52 | doc, drg, gafolo, rdnzao, togs   |
|           33 |     2321 | 2024-05-08 | 9z                | L   | 0.603      | -            | -                | -                | -         |    -0.88 | doc, drg, gafolo, rdnzao, togs   |
|           32 |     2359 | 2024-05-06 | BESTIA            | W   | 0.590      | 0.435        | 0.096 (0.025)    | -                | -         |     8.34 | doc, drg, gafolo, rdnzao, togs   |
|           31 |     2958 | 2024-04-11 | paiN              | L   | 0.422      | -            | -                | -                | -         |    -1.07 | doc, drg, gafolo, rdnzao, togs   |
|           30 |     3221 | 2024-04-03 | 2GAME             | W   | 0.370      | -            | -                | -                | -         |     1.83 | doc, drg, gafolo, rdnzao, togs   |
|           29 |     3224 | 2024-04-03 | 2GAME             | W   | 0.369      | -            | -                | -                | -         |     1.86 | doc, drg, gafolo, rdnzao, togs   |
|           28 |     3593 | 2024-03-14 | MIBR              | L   | 0.237      | -            | -                | -                | -         |    -0.63 | doc, drg, gafolo, rdnzao, togs   |
|           27 |     3595 | 2024-03-14 | MIBR              | L   | 0.236      | -            | -                | -                | -         |    -0.63 | doc, drg, gafolo, rdnzao, togs   |
|           26 |     3623 | 2024-03-13 | Yawara            | W   | 0.229      | -            | -                | -                | -         |     0.53 | doc, drg, gafolo, rdnzao, togs   |
|           25 |     3626 | 2024-03-13 | ODDIK             | W   | 0.229      | -            | -                | -                | -         |     3.83 | doc, drg, gafolo, rdnzao, togs   |
|           24 |     3699 | 2024-03-11 | Fluxo             | L   | 0.214      | -            | -                | -                | -         |    -2.68 | doc, drg, gafolo, rdnzao, togs   |
|           23 |     3727 | 2024-03-09 | Case              | L   | 0.202      | -            | -                | -                | -         |    -3.61 | doc, drg, gafolo, rdnzao, togs   |
|           22 |     3791 | 2024-03-07 | Corinthians       | W   | 0.187      | -            | -                | -                | -         |     0.41 | doc, drg, gafolo, rdnzao, togs   |
|           21 |     3845 | 2024-03-05 | Solid             | W   | 0.175      | -            | -                | -                | -         |     2.17 | doc, drg, gafolo, rdnzao, togs   |
|           20 |     3851 | 2024-03-05 | Solid             | W   | 0.175      | -            | -                | -                | -         |     2.20 | doc, drg, gafolo, rdnzao, togs   |
|           19 |     4045 | 2024-02-24 | Galorys           | W   | 0.110      | -            | -                | -                | -         |     1.36 | doc, drg, gafolo, rdnzao, togs   |
|           18 |     4053 | 2024-02-24 | Galorys           | W   | 0.110      | -            | -                | -                | -         |     1.37 | doc, drg, gafolo, rdnzao, togs   |
|           17 |     4057 | 2024-02-24 | Fluxo             | L   | 0.109      | -            | -                | -                | -         |    -1.36 | doc, drg, gafolo, rdnzao, togs   |
|           16 |     4110 | 2024-02-21 | Corinthians       | W   | 0.090      | -            | -                | -                | -         |     0.20 | doc, drg, gafolo, rdnzao, togs   |
|           15 |     4115 | 2024-02-21 | Case              | W   | 0.089      | -            | -                | -                | -         |     1.29 | doc, drg, gafolo, rdnzao, togs   |
|           14 |     4120 | 2024-02-21 | Galorys           | W   | 0.088      | -            | -                | -                | -         |     1.13 | doc, drg, gafolo, rdnzao, togs   |
|           13 |     4145 | 2024-02-20 | Flamengo          | L   | 0.082      | -            | -                | -                | -         |    -2.43 | doc, drg, gafolo, rdnzao, togs   |
|           12 |     4150 | 2024-02-20 | Case              | W   | 0.081      | -            | -                | -                | -         |     1.17 | doc, drg, gafolo, rdnzao, togs   |
|           11 |     4174 | 2024-02-19 | Solid             | W   | 0.075      | -            | -                | -                | -         |     0.95 | doc, drg, gafolo, rdnzao, togs   |
|           10 |     4188 | 2024-02-18 | Galorys           | W   | 0.070      | -            | -                | -                | -         |     0.91 | doc, drg, gafolo, rdnzao, togs   |
|            9 |     4211 | 2024-02-17 | W7M               | L   | 0.063      | -            | -                | -                | -         |    -1.33 | doc, drg, gafolo, rdnzao, togs   |
|            8 |     4216 | 2024-02-17 | Galorys           | L   | 0.062      | -            | -                | -                | -         |    -1.16 | doc, drg, gafolo, rdnzao, togs   |
|            7 |     4251 | 2024-02-16 | W7M               | W   | 0.054      | -            | -                | -                | -         |     0.56 | doc, drg, gafolo, rdnzao, togs   |
|            6 |     4269 | 2024-02-15 | Case              | L   | 0.049      | -            | -                | -                | -         |    -0.84 | doc, drg, gafolo, rdnzao, togs   |
|            5 |     4275 | 2024-02-15 | Fluxo             | L   | 0.048      | -            | -                | -                | -         |    -0.60 | doc, drg, gafolo, rdnzao, togs   |
|            4 |     4276 | 2024-02-15 | Fluxo             | L   | 0.048      | -            | -                | -                | -         |    -0.60 | doc, drg, gafolo, rdnzao, togs   |
|            3 |     4304 | 2024-02-14 | Hype              | W   | 0.043      | -            | -                | -                | -         |     0.05 | doc, drg, gafolo, rdnzao, togs   |
|            2 |     4315 | 2024-02-14 | Galorys           | W   | 0.041      | -            | -                | -                | -         |     0.53 | doc, drg, gafolo, rdnzao, togs   |
|            1 |     4359 | 2024-02-12 | Solid             | W   | 0.029      | -            | -                | -                | -         |     0.37 | doc, drg, gafolo, rdnzao, togs   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($9,629.18)
- Divide that value by the 5th highest value among all rosters ($320,411.81)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-02 |      1.000 | $750.00        | $750.00         |
| 2024-06-28 |      0.942 | $500.00        | $470.75         |
| 2024-06-16 |      0.862 | $2,500.00      | $2,153.94       |
| 2024-06-10 |      0.823 | $750.00        | $617.14         |
| 2024-06-09 |      0.816 | $5,000.00      | $4,078.24       |
| 2024-05-19 |      0.675 | $1,000.00      | $674.91         |
| 2024-02-25 |      0.115 | $5,000.00      | $577.31         |
| 2024-02-21 |      0.088 | $3,500.00      | $306.90         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
