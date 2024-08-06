### Roster Details<br />
Team Name: Endpoint<br />
Roster: AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal<br />
Global Rank: [102](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [73]( ../standings_europe.md)<br />
<br />
Final Rank Value:  858.7<br />
<br />
Final Rank Value (858.7) = Starting Rank Value (891.8) + Head To Head Adjustments (-33.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.341[<sup>1</sup>](#table2)
- Bounty Collected: 0.369[<sup>2</sup>](#table1)
- Opponent Network: 0.248[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.240<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 891.8
- 400 + ( ( 0.240 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 891.8


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
|           56 |      195 | 2024-07-31 | K27              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.60 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           55 |      205 | 2024-07-31 | Permitta         | W   | 1.000      | 0.426        | 0.023 (0.010)    | 0.940 (0.400)    | 0 (0.000) |    19.63 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           54 |      250 | 2024-07-30 | GUN5             | L   | 1.000      | -            | -                | -                | -         |   -13.39 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           53 |      319 | 2024-07-28 | Space            | W   | 1.000      | 0.435        | -                | 0.439 (0.191)    | 0 (0.000) |    17.67 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           52 |      352 | 2024-07-26 | Sampi            | L   | 1.000      | -            | -                | -                | -         |   -12.71 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           51 |      404 | 2024-07-25 | Monte            | L   | 1.000      | -            | -                | -                | -         |    -7.54 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           50 |      523 | 2024-07-21 | GUN5             | L   | 1.000      | -            | -                | -                | -         |   -12.76 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           49 |      596 | 2024-07-19 | ALTERNATE aTTaX  | W   | 1.000      | 0.435        | 0.031 (0.014)    | 0.549 (0.239)    | 0 (0.000) |    15.61 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           48 |      710 | 2024-07-17 | SINNERS          | L   | 1.000      | -            | -                | -                | -         |   -10.53 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           47 |      719 | 2024-07-17 | 9INE             | L   | 1.000      | -            | -                | -                | -         |   -13.78 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           46 |      770 | 2024-07-16 | Metizport        | L   | 1.000      | -            | -                | -                | -         |   -11.69 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           45 |      817 | 2024-07-15 | Johnny Speeds    | L   | 1.000      | -            | -                | -                | -         |    -3.96 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           44 |      878 | 2024-07-11 | Sashi            | L   | 1.000      | -            | -                | -                | -         |    -4.77 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           43 |      883 | 2024-07-11 | 9INE             | W   | 1.000      | 0.358        | 0.022 (0.008)    | 0.534 (0.191)    | 0 (0.000) |    17.05 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           42 |      903 | 2024-07-10 | Johnny Speeds    | L   | 1.000      | -            | -                | -                | -         |    -3.66 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           41 |      923 | 2024-07-09 | ROSOMAHA         | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.02 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           40 |     1104 | 2024-06-14 | GamerLegion      | L   | 0.848      | -            | -                | -                | -         |    -4.36 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           39 |     1214 | 2024-06-10 | MOUZ NXT         | W   | 0.821      | 0.450        | 0.139 (0.051)    | 0.984 (0.363)    | 0 (0.000) |    20.13 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           38 |     1344 | 2024-06-08 | Entropiq         | W   | 0.806      | -            | -                | -                | 0 (0.000) |     1.80 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           37 |     1368 | 2024-06-07 | 9INE             | L   | 0.802      | -            | -                | -                | -         |   -11.22 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           36 |     1456 | 2024-06-06 | NAVI Junior      | L   | 0.794      | -            | -                | -                | -         |   -21.33 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           35 |     1468 | 2024-06-06 | 5W               | L   | 0.793      | -            | -                | -                | -         |   -11.30 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           34 |     1542 | 2024-06-04 | Rhyno            | L   | 0.782      | -            | -                | -                | -         |    -9.79 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           33 |     1763 | 2024-05-27 | Rhyno            | L   | 0.727      | -            | -                | -                | -         |    -9.27 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           32 |     1815 | 2024-05-24 | ALTERNATE aTTaX  | W   | 0.707      | 0.435        | 0.031 (0.010)    | 0.549 (0.169)    | 0 (0.000) |    10.77 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           31 |     1869 | 2024-05-22 | Permitta         | L   | 0.695      | -            | -                | -                | -         |   -11.56 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           30 |     1919 | 2024-05-21 | RUBY             | L   | 0.686      | -            | -                | -                | -         |   -10.19 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           29 |     1972 | 2024-05-19 | Sangal           | L   | 0.674      | -            | -                | -                | -         |    -6.08 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           28 |     2037 | 2024-05-17 | Zero Tenacity    | L   | 0.661      | -            | -                | -                | -         |    -6.71 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           27 |     2123 | 2024-05-15 | Passion UA       | W   | 0.648      | 0.435        | 0.173 (0.049)    | 1.000 (0.282)    | 0 (0.000) |    12.77 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           26 |     2131 | 2024-05-15 | Sashi            | L   | 0.647      | -            | -                | -                | -         |    -3.49 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           25 |     2187 | 2024-05-14 | ALTERNATE aTTaX  | L   | 0.640      | -            | -                | -                | -         |    -9.11 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           24 |     2249 | 2024-05-11 | MOUZ NXT         | L   | 0.622      | -            | -                | -                | -         |    -6.91 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           23 |     2300 | 2024-05-09 | PARIVISION       | W   | 0.608      | -            | -                | -                | -         |    13.16 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           22 |     2382 | 2024-05-05 | SINNERS          | L   | 0.581      | -            | -                | -                | -         |    -5.85 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           21 |     2403 | 2024-05-04 | Sampi            | W   | 0.573      | 0.435        | 0.027 (0.007)    | 1.000 (0.249)    | -         |     8.75 | AZUWU, CRUC1AL, Frøg, MiGHTYMAX, Surreal  |
|           20 |     2429 | 2024-05-02 | MOUZ NXT         | W   | 0.562      | 0.435        | 0.139 (0.034)    | 0.984 (0.240)    | -         |    11.92 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           19 |     2441 | 2024-05-02 | Grannys Knockers | W   | 0.561      | -            | -                | -                | -         |     5.29 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           18 |     2480 | 2024-04-30 | ALTERNATE aTTaX  | W   | 0.548      | 0.396        | 0.031 (0.007)    | -                | -         |    10.09 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           17 |     2485 | 2024-04-30 | ENCE Academy     | W   | 0.547      | -            | -                | -                | -         |     4.42 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           16 |     2500 | 2024-04-29 | Nexus            | W   | 0.542      | -            | -                | -                | -         |     7.12 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           15 |     2514 | 2024-04-29 | Alliance         | L   | 0.540      | -            | -                | -                | -         |    -9.23 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           14 |     2624 | 2024-04-24 | SINNERS          | W   | 0.507      | 0.384        | 0.037 (0.007)    | 0.808 (0.158)    | -         |    12.69 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           13 |     2856 | 2024-04-17 | EYEBALLERS       | W   | 0.460      | -            | -                | -                | -         |     7.34 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           12 |     3571 | 2024-03-15 | ex-sYnck         | W   | 0.241      | -            | -                | -                | -         |     0.80 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|           11 |     3602 | 2024-03-14 | The Chosen Few   | L   | 0.235      | -            | -                | -                | -         |    -5.63 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|           10 |     3674 | 2024-03-12 | Secret           | W   | 0.220      | -            | -                | -                | -         |     0.85 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|            9 |     3709 | 2024-03-10 | Nemiga           | L   | 0.208      | -            | -                | -                | -         |    -1.13 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|            8 |     3745 | 2024-03-09 | BLEED            | L   | 0.200      | -            | -                | -                | -         |    -2.48 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|            7 |     3777 | 2024-03-07 | kONO             | W   | 0.189      | -            | -                | -                | -         |     2.31 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|            6 |     3813 | 2024-03-06 | V1dar            | W   | 0.181      | -            | -                | -                | -         |     0.66 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|            5 |     3856 | 2024-03-05 | AURA             | W   | 0.174      | -            | -                | -                | -         |     0.54 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|            4 |     3951 | 2024-02-29 | Metizport        | L   | 0.141      | -            | -                | -                | -         |    -2.15 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|            3 |     4008 | 2024-02-26 | ALTERNATE aTTaX  | L   | 0.120      | -            | -                | -                | -         |    -1.42 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|            2 |     4386 | 2024-02-09 | 3DMAX            | L   | 0.008      | -            | -                | -                | -         |    -0.00 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|            1 |     4392 | 2024-02-09 | fnatic           | L   | 0.007      | -            | -                | -                | -         |    -0.01 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,758.75)
- Divide that value by the 5th highest value among all rosters ($320,603.98)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-17 |      0.867 | $2,500.00      | $2,167.36       |
| 2024-05-18 |      0.669 | $500.00        | $334.31         |
| 2024-05-12 |      0.629 | $2,000.00      | $1,257.08       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
