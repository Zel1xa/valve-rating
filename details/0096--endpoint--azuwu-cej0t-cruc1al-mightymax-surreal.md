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
Final Rank Value (879.7) = Starting Rank Value (893.2) + Head To Head Adjustments (-13.6)<br />

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
|           57 |        4 | 2024-08-06 | DMS              | W   | 1.000      | 0.435        | -                | 0.428 (0.186)    | 0 (0.000) |    17.11 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           56 |      207 | 2024-07-31 | K27              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.51 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           55 |      217 | 2024-07-31 | Permitta         | W   | 1.000      | 0.426        | 0.039 (0.017)    | 0.919 (0.392)    | 0 (0.000) |    19.69 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           54 |      262 | 2024-07-30 | GUN5             | L   | 1.000      | -            | -                | -                | -         |   -13.48 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           53 |      331 | 2024-07-28 | Space            | W   | 1.000      | 0.435        | -                | 0.429 (0.187)    | 0 (0.000) |    17.59 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           52 |      364 | 2024-07-26 | Sampi            | L   | 1.000      | -            | -                | -                | -         |   -12.70 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           51 |      416 | 2024-07-25 | Monte            | L   | 1.000      | -            | -                | -                | -         |    -7.66 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           50 |      535 | 2024-07-21 | GUN5             | L   | 1.000      | -            | -                | -                | -         |   -12.86 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           49 |      608 | 2024-07-19 | ALTERNATE aTTaX  | W   | 1.000      | 0.435        | 0.031 (0.014)    | 0.537 (0.233)    | 0 (0.000) |    15.51 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           48 |      722 | 2024-07-17 | SINNERS          | L   | 1.000      | -            | -                | -                | -         |   -10.66 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           47 |      731 | 2024-07-17 | 9INE             | L   | 1.000      | -            | -                | -                | -         |   -13.88 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           46 |      782 | 2024-07-16 | Metizport        | L   | 1.000      | -            | -                | -                | -         |   -11.79 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           45 |      829 | 2024-07-15 | Johnny Speeds    | L   | 1.000      | -            | -                | -                | -         |    -4.01 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           44 |      890 | 2024-07-11 | Sashi            | L   | 1.000      | -            | -                | -                | -         |    -4.86 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           43 |      895 | 2024-07-11 | 9INE             | W   | 1.000      | 0.358        | 0.022 (0.008)    | 0.523 (0.187)    | 0 (0.000) |    16.94 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           42 |      915 | 2024-07-10 | Johnny Speeds    | L   | 1.000      | -            | -                | -                | -         |    -3.71 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           41 |      935 | 2024-07-09 | ROSOMAHA         | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.93 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           40 |     1116 | 2024-06-14 | GamerLegion      | L   | 0.847      | -            | -                | -                | -         |    -4.46 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           39 |     1226 | 2024-06-10 | MOUZ NXT         | W   | 0.820      | 0.450        | 0.139 (0.051)    | 0.962 (0.355)    | 0 (0.000) |    20.04 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           38 |     1356 | 2024-06-08 | Entropiq         | W   | 0.805      | -            | -                | -                | 0 (0.000) |     1.78 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           37 |     1380 | 2024-06-07 | 9INE             | L   | 0.801      | -            | -                | -                | -         |   -11.31 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           36 |     1468 | 2024-06-06 | NAVI Junior      | L   | 0.793      | -            | -                | -                | -         |   -17.57 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           35 |     1480 | 2024-06-06 | 5W               | L   | 0.792      | -            | -                | -                | -         |   -11.30 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           34 |     1554 | 2024-06-04 | Rhyno            | L   | 0.781      | -            | -                | -                | -         |    -9.78 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           33 |     1775 | 2024-05-27 | Rhyno            | L   | 0.726      | -            | -                | -                | -         |    -9.26 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           32 |     1827 | 2024-05-24 | ALTERNATE aTTaX  | W   | 0.706      | 0.435        | 0.031 (0.010)    | 0.537 (0.165)    | 0 (0.000) |    10.76 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           31 |     1881 | 2024-05-22 | Permitta         | L   | 0.694      | -            | -                | -                | -         |   -11.31 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           30 |     1931 | 2024-05-21 | RUBY             | L   | 0.685      | -            | -                | -                | -         |   -10.15 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           29 |     1984 | 2024-05-19 | Sangal           | L   | 0.673      | -            | -                | -                | -         |    -6.01 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           28 |     2049 | 2024-05-17 | Zero Tenacity    | L   | 0.660      | -            | -                | -                | -         |    -6.72 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           27 |     2135 | 2024-05-15 | Passion UA       | W   | 0.647      | 0.435        | 0.173 (0.049)    | 1.000 (0.281)    | -         |    12.74 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           26 |     2143 | 2024-05-15 | Sashi            | L   | 0.645      | -            | -                | -                | -         |    -3.50 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           25 |     2199 | 2024-05-14 | ALTERNATE aTTaX  | L   | 0.639      | -            | -                | -                | -         |    -9.07 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           24 |     2261 | 2024-05-11 | MOUZ NXT         | L   | 0.621      | -            | -                | -                | -         |    -6.92 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           23 |     2312 | 2024-05-09 | PARIVISION       | W   | 0.607      | -            | -                | -                | -         |    13.14 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           22 |     2394 | 2024-05-05 | SINNERS          | L   | 0.580      | -            | -                | -                | -         |    -5.84 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           21 |     2415 | 2024-05-04 | Sampi            | W   | 0.572      | 0.435        | 0.027 (0.007)    | 1.000 (0.249)    | -         |     8.72 | AZUWU, CRUC1AL, Frøg, MiGHTYMAX, Surreal  |
|           20 |     2441 | 2024-05-02 | MOUZ NXT         | W   | 0.561      | 0.435        | 0.139 (0.034)    | 0.962 (0.234)    | -         |    11.87 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           19 |     2453 | 2024-05-02 | Grannys Knockers | W   | 0.559      | -            | -                | -                | -         |     5.26 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           18 |     2492 | 2024-04-30 | ALTERNATE aTTaX  | W   | 0.547      | 0.396        | 0.031 (0.007)    | -                | -         |    10.09 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           17 |     2497 | 2024-04-30 | ENCE Academy     | W   | 0.546      | -            | -                | -                | -         |     4.39 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           16 |     2512 | 2024-04-29 | Nexus            | W   | 0.541      | -            | -                | -                | -         |     7.10 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           15 |     2526 | 2024-04-29 | Alliance         | L   | 0.539      | -            | -                | -                | -         |    -9.23 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           14 |     2636 | 2024-04-24 | SINNERS          | W   | 0.506      | 0.384        | 0.037 (0.007)    | -                | -         |    12.65 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           13 |     2868 | 2024-04-17 | EYEBALLERS       | W   | 0.459      | -            | -                | -                | -         |     7.30 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           12 |     3583 | 2024-03-15 | ex-sYnck         | W   | 0.240      | -            | -                | -                | -         |     0.79 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|           11 |     3614 | 2024-03-14 | The Chosen Few   | L   | 0.234      | -            | -                | -                | -         |    -5.60 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|           10 |     3686 | 2024-03-12 | Secret           | W   | 0.219      | -            | -                | -                | -         |     0.84 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|            9 |     3721 | 2024-03-10 | Nemiga           | L   | 0.207      | -            | -                | -                | -         |    -1.14 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|            8 |     3757 | 2024-03-09 | BLEED            | L   | 0.199      | -            | -                | -                | -         |    -2.48 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|            7 |     3789 | 2024-03-07 | kONO             | W   | 0.188      | -            | -                | -                | -         |     2.29 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|            6 |     3825 | 2024-03-06 | V1dar            | W   | 0.180      | -            | -                | -                | -         |     0.65 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|            5 |     3868 | 2024-03-05 | AURA             | W   | 0.173      | -            | -                | -                | -         |     0.53 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|            4 |     3963 | 2024-02-29 | Metizport        | L   | 0.140      | -            | -                | -                | -         |    -2.13 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|            3 |     4020 | 2024-02-26 | ALTERNATE aTTaX  | L   | 0.119      | -            | -                | -                | -         |    -1.41 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|            2 |     4398 | 2024-02-09 | 3DMAX            | L   | 0.007      | -            | -                | -                | -         |    -0.00 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|            1 |     4404 | 2024-02-09 | fnatic           | L   | 0.006      | -            | -                | -                | -         |    -0.01 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,752.73)
- Divide that value by the 5th highest value among all rosters ($320,247.08)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-17 |      0.866 | $2,500.00      | $2,164.35       |
| 2024-05-18 |      0.667 | $500.00        | $333.70         |
| 2024-05-12 |      0.627 | $2,000.00      | $1,254.68       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
