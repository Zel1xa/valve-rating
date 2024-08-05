### Roster Details<br />
Team Name: Endpoint<br />
Roster: AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal<br />
Global Rank: [103](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [74]( ../standings_europe.md)<br />
<br />
Final Rank Value:  852.7<br />
<br />
Final Rank Value (852.7) = Starting Rank Value (890.7) + Head To Head Adjustments (-37.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.341[<sup>1</sup>](#table2)
- Bounty Collected: 0.370[<sup>2</sup>](#table1)
- Opponent Network: 0.246[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.239<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 890.7
- 400 + ( ( 0.239 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 890.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent         | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                    |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           56 |      188 | 2024-07-31 | K27              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.75 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           55 |      198 | 2024-07-31 | Permitta         | W   | 1.000      | 0.426        | 0.024 (0.010)    | 0.863 (0.368)    | 0 (0.000) |    19.55 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           54 |      243 | 2024-07-30 | GUN5             | L   | 1.000      | -            | -                | -                | -         |   -13.18 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           53 |      312 | 2024-07-28 | Space            | W   | 1.000      | 0.435        | -                | 0.439 (0.191)    | 0 (0.000) |    17.69 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           52 |      345 | 2024-07-26 | Sampi            | L   | 1.000      | -            | -                | -                | -         |   -12.69 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           51 |      397 | 2024-07-25 | Monte            | L   | 1.000      | -            | -                | -                | -         |    -7.37 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           50 |      516 | 2024-07-21 | GUN5             | L   | 1.000      | -            | -                | -                | -         |   -12.50 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           49 |      589 | 2024-07-19 | ALTERNATE aTTaX  | W   | 1.000      | 0.435        | 0.031 (0.014)    | 0.550 (0.239)    | 0 (0.000) |    15.85 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           48 |      703 | 2024-07-17 | SINNERS          | L   | 1.000      | -            | -                | -                | -         |   -10.31 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           47 |      712 | 2024-07-17 | 9INE             | L   | 1.000      | -            | -                | -                | -         |   -13.49 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           46 |      763 | 2024-07-16 | Metizport        | L   | 1.000      | -            | -                | -                | -         |   -17.78 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           45 |      810 | 2024-07-15 | Johnny Speeds    | L   | 1.000      | -            | -                | -                | -         |    -3.95 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           44 |      871 | 2024-07-11 | Sashi            | L   | 1.000      | -            | -                | -                | -         |    -4.75 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           43 |      876 | 2024-07-11 | 9INE             | W   | 1.000      | 0.358        | 0.022 (0.008)    | 0.533 (0.191)    | 0 (0.000) |    17.09 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           42 |      896 | 2024-07-10 | Johnny Speeds    | L   | 1.000      | -            | -                | -                | -         |    -3.66 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           41 |      916 | 2024-07-09 | ROSOMAHA         | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.05 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           40 |     1097 | 2024-06-14 | GamerLegion      | L   | 0.853      | -            | -                | -                | -         |    -4.33 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           39 |     1207 | 2024-06-10 | MOUZ NXT         | W   | 0.826      | 0.450        | 0.139 (0.052)    | 0.987 (0.367)    | 0 (0.000) |    20.27 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           38 |     1337 | 2024-06-08 | Entropiq         | W   | 0.811      | -            | -                | -                | 0 (0.000) |     1.82 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           37 |     1361 | 2024-06-07 | 9INE             | L   | 0.807      | -            | -                | -                | -         |   -11.24 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           36 |     1449 | 2024-06-06 | NAVI Junior      | L   | 0.799      | -            | -                | -                | -         |   -21.42 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           35 |     1461 | 2024-06-06 | 5W               | L   | 0.798      | -            | -                | -                | -         |   -11.30 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           34 |     1535 | 2024-06-04 | Rhyno            | L   | 0.787      | -            | -                | -                | -         |    -9.79 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           33 |     1756 | 2024-05-27 | Rhyno            | L   | 0.732      | -            | -                | -                | -         |    -9.27 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           32 |     1808 | 2024-05-24 | ALTERNATE aTTaX  | W   | 0.712      | 0.435        | 0.031 (0.010)    | 0.550 (0.170)    | 0 (0.000) |    10.85 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           31 |     1862 | 2024-05-22 | Permitta         | L   | 0.699      | -            | -                | -                | -         |   -11.83 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           30 |     1912 | 2024-05-21 | RUBY             | L   | 0.691      | -            | -                | -                | -         |   -10.38 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           29 |     1965 | 2024-05-19 | Sangal           | L   | 0.679      | -            | -                | -                | -         |    -6.16 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           28 |     2030 | 2024-05-17 | Zero Tenacity    | L   | 0.666      | -            | -                | -                | -         |    -6.77 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           27 |     2116 | 2024-05-15 | Passion UA       | W   | 0.653      | 0.435        | 0.173 (0.049)    | 1.000 (0.284)    | 0 (0.000) |    12.81 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           26 |     2124 | 2024-05-15 | Sashi            | L   | 0.651      | -            | -                | -                | -         |    -3.50 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           25 |     2180 | 2024-05-14 | ALTERNATE aTTaX  | L   | 0.645      | -            | -                | -                | -         |    -9.16 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           24 |     2242 | 2024-05-11 | MOUZ NXT         | L   | 0.627      | -            | -                | -                | -         |    -6.95 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           23 |     2293 | 2024-05-09 | PARIVISION       | W   | 0.613      | -            | -                | -                | -         |    13.24 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           22 |     2375 | 2024-05-05 | SINNERS          | L   | 0.586      | -            | -                | -                | -         |    -5.88 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           21 |     2396 | 2024-05-04 | Sampi            | W   | 0.578      | 0.435        | 0.027 (0.007)    | 1.000 (0.251)    | -         |     8.82 | AZUWU, CRUC1AL, Frøg, MiGHTYMAX, Surreal  |
|           20 |     2422 | 2024-05-02 | MOUZ NXT         | W   | 0.567      | 0.435        | 0.139 (0.034)    | 0.987 (0.243)    | -         |    12.03 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           19 |     2434 | 2024-05-02 | Grannys Knockers | W   | 0.565      | -            | -                | -                | -         |     5.36 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           18 |     2473 | 2024-04-30 | ALTERNATE aTTaX  | W   | 0.553      | 0.396        | 0.031 (0.007)    | -                | -         |    10.20 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           17 |     2478 | 2024-04-30 | ENCE Academy     | W   | 0.552      | -            | -                | -                | -         |     4.50 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           16 |     2493 | 2024-04-29 | Nexus            | W   | 0.546      | -            | -                | -                | -         |     7.14 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           15 |     2507 | 2024-04-29 | Alliance         | L   | 0.544      | -            | -                | -                | -         |    -9.28 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           14 |     2617 | 2024-04-24 | SINNERS          | W   | 0.512      | 0.384        | 0.037 (0.007)    | 0.809 (0.159)    | -         |    12.83 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           13 |     2849 | 2024-04-17 | EYEBALLERS       | W   | 0.464      | -            | -                | -                | -         |     7.40 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           12 |     3564 | 2024-03-15 | ex-sYnck         | W   | 0.246      | -            | -                | -                | -         |     0.82 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|           11 |     3595 | 2024-03-14 | The Chosen Few   | L   | 0.240      | -            | -                | -                | -         |    -5.72 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|           10 |     3667 | 2024-03-12 | Secret           | W   | 0.225      | -            | -                | -                | -         |     0.87 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|            9 |     3702 | 2024-03-10 | Nemiga           | L   | 0.213      | -            | -                | -                | -         |    -1.14 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|            8 |     3738 | 2024-03-09 | BLEED            | L   | 0.205      | -            | -                | -                | -         |    -2.52 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|            7 |     3770 | 2024-03-07 | kONO             | W   | 0.194      | -            | -                | -                | -         |     2.35 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|            6 |     3806 | 2024-03-06 | V1dar            | W   | 0.186      | -            | -                | -                | -         |     0.68 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|            5 |     3849 | 2024-03-05 | AURA             | W   | 0.179      | -            | -                | -                | -         |     0.56 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|            4 |     3944 | 2024-02-29 | Metizport        | L   | 0.146      | -            | -                | -                | -         |    -2.66 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|            3 |     4001 | 2024-02-26 | ALTERNATE aTTaX  | L   | 0.125      | -            | -                | -                | -         |    -1.47 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|            2 |     4379 | 2024-02-09 | 3DMAX            | L   | 0.013      | -            | -                | -                | -         |    -0.01 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|            1 |     4385 | 2024-02-09 | fnatic           | L   | 0.012      | -            | -                | -                | -         |    -0.01 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,782.36)
- Divide that value by the 5th highest value among all rosters ($322,004.12)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-17 |      0.872 | $2,500.00      | $2,179.17       |
| 2024-05-18 |      0.673 | $500.00        | $336.67         |
| 2024-05-12 |      0.633 | $2,000.00      | $1,266.53       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
