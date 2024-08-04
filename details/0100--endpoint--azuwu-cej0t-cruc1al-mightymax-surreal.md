### Roster Details<br />
Team Name: Endpoint<br />
Roster: AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal<br />
Global Rank: [100](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [74]( ../standings_europe.md)<br />
<br />
Final Rank Value:  853.7<br />
<br />
Final Rank Value (853.7) = Starting Rank Value (890.6) + Head To Head Adjustments (-36.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.341[<sup>1</sup>](#table2)
- Bounty Collected: 0.370[<sup>2</sup>](#table1)
- Opponent Network: 0.248[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.240<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 890.6
- 400 + ( ( 0.240 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 890.6


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
|           57 |      131 | 2024-07-31 | K27              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.72 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           56 |      141 | 2024-07-31 | Permitta         | W   | 1.000      | 0.426        | 0.024 (0.010)    | 0.876 (0.373)    | 0 (0.000) |    19.35 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           55 |      186 | 2024-07-30 | GUN5             | L   | 1.000      | -            | -                | -                | -         |   -13.73 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           54 |      255 | 2024-07-28 | Space            | W   | 1.000      | 0.435        | -                | 0.406 (0.177)    | 0 (0.000) |    17.66 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           53 |      287 | 2024-07-26 | Sampi            | L   | 1.000      | -            | -                | -                | -         |   -12.83 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           52 |      340 | 2024-07-25 | Monte            | L   | 1.000      | -            | -                | -                | -         |    -7.51 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           51 |      459 | 2024-07-21 | GUN5             | L   | 1.000      | -            | -                | -                | -         |   -12.57 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           50 |      532 | 2024-07-19 | ALTERNATE aTTaX  | W   | 1.000      | 0.435        | 0.031 (0.014)    | 0.560 (0.244)    | 0 (0.000) |    15.49 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           49 |      646 | 2024-07-17 | SINNERS          | L   | 1.000      | -            | -                | -                | -         |   -11.48 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           48 |      656 | 2024-07-17 | 9INE             | L   | 1.000      | -            | -                | -                | -         |   -13.74 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           47 |      707 | 2024-07-16 | Metizport        | L   | 1.000      | -            | -                | -                | -         |   -11.64 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           46 |      753 | 2024-07-15 | Johnny Speeds    | L   | 1.000      | -            | -                | -                | -         |    -4.03 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           45 |      814 | 2024-07-11 | Sashi            | L   | 1.000      | -            | -                | -                | -         |    -4.77 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           44 |      819 | 2024-07-11 | 9INE             | W   | 1.000      | 0.358        | 0.022 (0.008)    | 0.537 (0.192)    | 0 (0.000) |    17.08 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           43 |      839 | 2024-07-10 | Johnny Speeds    | L   | 1.000      | -            | -                | -                | -         |    -3.73 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           42 |      859 | 2024-07-09 | ROSOMAHA         | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.08 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           41 |     1040 | 2024-06-14 | GamerLegion      | L   | 0.861      | -            | -                | -                | -         |    -4.33 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           40 |     1150 | 2024-06-10 | MOUZ NXT         | W   | 0.834      | 0.450        | 0.139 (0.052)    | 1.000 (0.375)    | 0 (0.000) |    20.40 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           39 |     1280 | 2024-06-08 | Entropiq         | W   | 0.820      | -            | -                | -                | 0 (0.000) |     1.86 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           38 |     1304 | 2024-06-07 | 9INE             | L   | 0.816      | -            | -                | -                | -         |   -11.37 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           37 |     1392 | 2024-06-06 | NAVI Junior      | L   | 0.807      | -            | -                | -                | -         |   -21.61 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           36 |     1404 | 2024-06-06 | 5W               | L   | 0.806      | -            | -                | -                | -         |   -11.35 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           35 |     1478 | 2024-06-04 | Rhyno            | L   | 0.796      | -            | -                | -                | -         |    -9.80 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           34 |     1699 | 2024-05-27 | Rhyno            | L   | 0.741      | -            | -                | -                | -         |    -9.28 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           33 |     1751 | 2024-05-24 | ALTERNATE aTTaX  | W   | 0.721      | 0.435        | 0.031 (0.010)    | 0.560 (0.175)    | 0 (0.000) |    10.93 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           32 |     1805 | 2024-05-22 | Permitta         | L   | 0.708      | -            | -                | -                | -         |   -12.04 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           31 |     1855 | 2024-05-21 | RUBY             | L   | 0.700      | -            | -                | -                | -         |   -10.35 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           30 |     1908 | 2024-05-19 | Sangal           | L   | 0.688      | -            | -                | -                | -         |    -6.40 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           29 |     1973 | 2024-05-17 | Zero Tenacity    | L   | 0.674      | -            | -                | -                | -         |    -6.88 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           28 |     2059 | 2024-05-15 | Passion UA       | W   | 0.661      | 0.435        | 0.172 (0.049)    | 1.000 (0.287)    | 0 (0.000) |    12.80 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           27 |     2067 | 2024-05-15 | Sashi            | L   | 0.660      | -            | -                | -                | -         |    -3.56 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           26 |     2123 | 2024-05-14 | ALTERNATE aTTaX  | L   | 0.654      | -            | -                | -                | -         |    -9.29 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           25 |     2185 | 2024-05-11 | MOUZ NXT         | L   | 0.636      | -            | -                | -                | -         |    -7.12 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           24 |     2236 | 2024-05-09 | PARIVISION       | W   | 0.621      | -            | -                | -                | -         |    13.28 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           23 |     2318 | 2024-05-05 | SINNERS          | L   | 0.594      | -            | -                | -                | -         |    -7.03 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           22 |     2339 | 2024-05-04 | Sampi            | W   | 0.586      | 0.435        | 0.027 (0.007)    | 1.000 (0.255)    | -         |     8.96 | AZUWU, CRUC1AL, Frøg, MiGHTYMAX, Surreal  |
|           21 |     2365 | 2024-05-02 | MOUZ NXT         | W   | 0.576      | 0.435        | 0.139 (0.035)    | 1.000 (0.250)    | -         |    12.13 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           20 |     2377 | 2024-05-02 | Grannys Knockers | W   | 0.574      | -            | -                | -                | -         |     5.45 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           19 |     2416 | 2024-04-30 | ALTERNATE aTTaX  | W   | 0.561      | 0.396        | 0.031 (0.007)    | -                | -         |    10.32 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           18 |     2421 | 2024-04-30 | ENCE Academy     | W   | 0.561      | -            | -                | -                | -         |     4.57 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           17 |     2436 | 2024-04-29 | Nexus            | W   | 0.555      | -            | -                | -                | -         |     7.26 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           16 |     2450 | 2024-04-29 | Alliance         | L   | 0.553      | -            | -                | -                | -         |    -9.40 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           15 |     2560 | 2024-04-24 | SINNERS          | W   | 0.521      | 0.384        | 0.037 (0.007)    | 0.758 (0.152)    | -         |    12.21 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           14 |     2792 | 2024-04-17 | EYEBALLERS       | W   | 0.473      | -            | -                | -                | -         |     7.55 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           13 |     3507 | 2024-03-15 | ex-sYnck         | W   | 0.254      | -            | -                | -                | -         |     0.86 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|           12 |     3538 | 2024-03-14 | The Chosen Few   | L   | 0.249      | -            | -                | -                | -         |    -5.92 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|           11 |     3610 | 2024-03-12 | Secret           | W   | 0.233      | -            | -                | -                | -         |     0.91 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|           10 |     3645 | 2024-03-10 | Nemiga           | L   | 0.222      | -            | -                | -                | -         |    -1.31 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|            9 |     3681 | 2024-03-09 | BLEED            | L   | 0.213      | -            | -                | -                | -         |    -2.61 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|            8 |     3713 | 2024-03-07 | kONO             | W   | 0.202      | -            | -                | -                | -         |     2.44 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|            7 |     3749 | 2024-03-06 | V1dar            | W   | 0.195      | -            | -                | -                | -         |     0.71 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|            6 |     3792 | 2024-03-05 | AURA             | W   | 0.188      | -            | -                | -                | -         |     0.60 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|            5 |     3887 | 2024-02-29 | Metizport        | L   | 0.154      | -            | -                | -                | -         |    -2.35 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|            4 |     3944 | 2024-02-26 | ALTERNATE aTTaX  | L   | 0.133      | -            | -                | -                | -         |    -1.57 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|            3 |     4322 | 2024-02-09 | 3DMAX            | L   | 0.022      | -            | -                | -                | -         |    -0.01 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|            2 |     4328 | 2024-02-09 | fnatic           | L   | 0.021      | -            | -                | -                | -         |    -0.01 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|            1 |     4349 | 2024-02-07 | Permitta         | W   | 0.007      | -            | -                | -                | -         |     0.13 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,825.42)
- Divide that value by the 5th highest value among all rosters ($324,557.31)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-17 |      0.880 | $2,500.00      | $2,200.69       |
| 2024-05-18 |      0.682 | $500.00        | $340.97         |
| 2024-05-12 |      0.642 | $2,000.00      | $1,283.75       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
