### Roster Details<br />
Team Name: Endpoint<br />
Roster: AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal<br />
Global Rank: [96](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [68]( ../standings_europe.md)<br />
<br />
Final Rank Value:  879.7<br />
<br />
Final Rank Value (879.7) = Starting Rank Value (893.2) + Head To Head Adjustments (-13.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.341[<sup>1</sup>](#table2)
- Bounty Collected: 0.371[<sup>2</sup>](#table1)
- Opponent Network: 0.247[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.240<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 893.2
- 400 + ( ( 0.240 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 893.2


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
|           57 |        7 | 2024-08-06 | DMS              | W   | 1.000      | 0.435        | -                | 0.428 (0.186)    | 0 (0.000) |    17.11 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           56 |      210 | 2024-07-31 | K27              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.51 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           55 |      220 | 2024-07-31 | Permitta         | W   | 1.000      | 0.426        | 0.039 (0.017)    | 0.919 (0.392)    | 0 (0.000) |    19.69 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           54 |      265 | 2024-07-30 | GUN5             | L   | 1.000      | -            | -                | -                | -         |   -13.47 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           53 |      334 | 2024-07-28 | Space            | W   | 1.000      | 0.435        | -                | 0.429 (0.187)    | 0 (0.000) |    17.59 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           52 |      367 | 2024-07-26 | Sampi            | L   | 1.000      | -            | -                | -                | -         |   -12.70 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           51 |      419 | 2024-07-25 | Monte            | L   | 1.000      | -            | -                | -                | -         |    -7.66 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           50 |      538 | 2024-07-21 | GUN5             | L   | 1.000      | -            | -                | -                | -         |   -12.86 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           49 |      611 | 2024-07-19 | ALTERNATE aTTaX  | W   | 1.000      | 0.435        | 0.031 (0.014)    | 0.537 (0.233)    | 0 (0.000) |    15.51 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           48 |      725 | 2024-07-17 | SINNERS          | L   | 1.000      | -            | -                | -                | -         |   -10.65 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           47 |      734 | 2024-07-17 | 9INE             | L   | 1.000      | -            | -                | -                | -         |   -13.88 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           46 |      785 | 2024-07-16 | Metizport        | L   | 1.000      | -            | -                | -                | -         |   -11.79 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           45 |      832 | 2024-07-15 | Johnny Speeds    | L   | 1.000      | -            | -                | -                | -         |    -4.01 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           44 |      893 | 2024-07-11 | Sashi            | L   | 1.000      | -            | -                | -                | -         |    -4.86 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           43 |      898 | 2024-07-11 | 9INE             | W   | 1.000      | 0.358        | 0.022 (0.008)    | 0.523 (0.187)    | 0 (0.000) |    16.94 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           42 |      918 | 2024-07-10 | Johnny Speeds    | L   | 1.000      | -            | -                | -                | -         |    -3.71 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           41 |      938 | 2024-07-09 | ROSOMAHA         | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.93 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           40 |     1119 | 2024-06-14 | GamerLegion      | L   | 0.846      | -            | -                | -                | -         |    -4.46 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           39 |     1229 | 2024-06-10 | MOUZ NXT         | W   | 0.819      | 0.450        | 0.139 (0.051)    | 0.961 (0.354)    | 0 (0.000) |    20.03 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           38 |     1359 | 2024-06-08 | Entropiq         | W   | 0.805      | -            | -                | -                | 0 (0.000) |     1.78 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           37 |     1383 | 2024-06-07 | 9INE             | L   | 0.801      | -            | -                | -                | -         |   -11.30 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           36 |     1471 | 2024-06-06 | NAVI Junior      | L   | 0.792      | -            | -                | -                | -         |   -17.56 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           35 |     1483 | 2024-06-06 | 5W               | L   | 0.791      | -            | -                | -                | -         |   -11.30 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           34 |     1557 | 2024-06-04 | Rhyno            | L   | 0.781      | -            | -                | -                | -         |    -9.77 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           33 |     1778 | 2024-05-27 | Rhyno            | L   | 0.726      | -            | -                | -                | -         |    -9.25 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           32 |     1830 | 2024-05-24 | ALTERNATE aTTaX  | W   | 0.706      | 0.435        | 0.031 (0.010)    | 0.537 (0.165)    | 0 (0.000) |    10.76 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           31 |     1884 | 2024-05-22 | Permitta         | L   | 0.693      | -            | -                | -                | -         |   -11.30 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           30 |     1934 | 2024-05-21 | RUBY             | L   | 0.685      | -            | -                | -                | -         |   -10.14 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           29 |     1987 | 2024-05-19 | Sangal           | L   | 0.673      | -            | -                | -                | -         |    -5.99 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           28 |     2052 | 2024-05-17 | Zero Tenacity    | L   | 0.659      | -            | -                | -                | -         |    -6.71 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           27 |     2138 | 2024-05-15 | Passion UA       | W   | 0.646      | 0.435        | 0.173 (0.049)    | 1.000 (0.281)    | -         |    12.75 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           26 |     2146 | 2024-05-15 | Sashi            | L   | 0.645      | -            | -                | -                | -         |    -3.49 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           25 |     2202 | 2024-05-14 | ALTERNATE aTTaX  | L   | 0.639      | -            | -                | -                | -         |    -9.06 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           24 |     2264 | 2024-05-11 | MOUZ NXT         | L   | 0.621      | -            | -                | -                | -         |    -6.91 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           23 |     2315 | 2024-05-09 | PARIVISION       | W   | 0.606      | -            | -                | -                | -         |    13.15 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           22 |     2397 | 2024-05-05 | SINNERS          | L   | 0.579      | -            | -                | -                | -         |    -5.83 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           21 |     2418 | 2024-05-04 | Sampi            | W   | 0.571      | 0.435        | 0.027 (0.007)    | 1.000 (0.248)    | -         |     8.71 | AZUWU, CRUC1AL, Frøg, MiGHTYMAX, Surreal  |
|           20 |     2444 | 2024-05-02 | MOUZ NXT         | W   | 0.561      | 0.435        | 0.139 (0.034)    | 0.961 (0.234)    | -         |    11.86 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           19 |     2456 | 2024-05-02 | Grannys Knockers | W   | 0.559      | -            | -                | -                | -         |     5.25 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           18 |     2495 | 2024-04-30 | ALTERNATE aTTaX  | W   | 0.546      | 0.396        | 0.031 (0.007)    | -                | -         |    10.08 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           17 |     2500 | 2024-04-30 | ENCE Academy     | W   | 0.546      | -            | -                | -                | -         |     4.39 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           16 |     2515 | 2024-04-29 | Nexus            | W   | 0.540      | -            | -                | -                | -         |     7.10 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           15 |     2529 | 2024-04-29 | Alliance         | L   | 0.538      | -            | -                | -                | -         |    -9.22 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           14 |     2639 | 2024-04-24 | SINNERS          | W   | 0.506      | 0.384        | 0.037 (0.007)    | -                | -         |    12.64 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           13 |     2871 | 2024-04-17 | EYEBALLERS       | W   | 0.458      | -            | -                | -                | -         |     7.30 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           12 |     3586 | 2024-03-15 | ex-sYnck         | W   | 0.239      | -            | -                | -                | -         |     0.79 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|           11 |     3617 | 2024-03-14 | The Chosen Few   | L   | 0.234      | -            | -                | -                | -         |    -5.59 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|           10 |     3689 | 2024-03-12 | Secret           | W   | 0.218      | -            | -                | -                | -         |     0.84 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|            9 |     3724 | 2024-03-10 | Nemiga           | L   | 0.207      | -            | -                | -                | -         |    -1.14 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|            8 |     3760 | 2024-03-09 | BLEED            | L   | 0.198      | -            | -                | -                | -         |    -2.47 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|            7 |     3792 | 2024-03-07 | kONO             | W   | 0.187      | -            | -                | -                | -         |     2.28 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|            6 |     3828 | 2024-03-06 | V1dar            | W   | 0.180      | -            | -                | -                | -         |     0.65 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|            5 |     3871 | 2024-03-05 | AURA             | W   | 0.173      | -            | -                | -                | -         |     0.52 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|            4 |     3966 | 2024-02-29 | Metizport        | L   | 0.139      | -            | -                | -                | -         |    -2.12 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|            3 |     4023 | 2024-02-26 | ALTERNATE aTTaX  | L   | 0.118      | -            | -                | -                | -         |    -1.40 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|            2 |     4401 | 2024-02-09 | 3DMAX            | L   | 0.007      | -            | -                | -                | -         |    -0.00 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|            1 |     4407 | 2024-02-09 | fnatic           | L   | 0.006      | -            | -                | -                | -         |    -0.00 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,750.42)
- Divide that value by the 5th highest value among all rosters ($320,109.81)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-17 |      0.865 | $2,500.00      | $2,163.19       |
| 2024-05-18 |      0.667 | $500.00        | $333.47         |
| 2024-05-12 |      0.627 | $2,000.00      | $1,253.75       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
