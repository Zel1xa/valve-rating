### Roster Details<br />
Team Name: Endpoint<br />
Roster: AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal<br />
Global Rank: [103](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [74]( ../standings_europe.md)<br />
<br />
Final Rank Value:  852.4<br />
<br />
Final Rank Value (852.4) = Starting Rank Value (891.1) + Head To Head Adjustments (-38.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.341[<sup>1</sup>](#table2)
- Bounty Collected: 0.370[<sup>2</sup>](#table1)
- Opponent Network: 0.248[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.240<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 891.1
- 400 + ( ( 0.240 - 0.000 ) / ( 0.781 - 0.000 ) ) * 1600 = 891.1


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
|           56 |      180 | 2024-07-31 | K27              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.76 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           55 |      190 | 2024-07-31 | Permitta         | W   | 1.000      | 0.426        | 0.024 (0.010)    | 0.873 (0.372)    | 0 (0.000) |    19.54 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           54 |      235 | 2024-07-30 | GUN5             | L   | 1.000      | -            | -                | -                | -         |   -13.20 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           53 |      304 | 2024-07-28 | Space            | W   | 1.000      | 0.435        | -                | 0.445 (0.193)    | 0 (0.000) |    17.71 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           52 |      337 | 2024-07-26 | Sampi            | L   | 1.000      | -            | -                | -                | -         |   -12.73 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           51 |      389 | 2024-07-25 | Monte            | L   | 1.000      | -            | -                | -                | -         |    -7.36 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           50 |      508 | 2024-07-21 | GUN5             | L   | 1.000      | -            | -                | -                | -         |   -12.52 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           49 |      581 | 2024-07-19 | ALTERNATE aTTaX  | W   | 1.000      | 0.435        | 0.031 (0.014)    | 0.557 (0.242)    | 0 (0.000) |    15.83 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           48 |      695 | 2024-07-17 | SINNERS          | L   | 1.000      | -            | -                | -                | -         |   -10.39 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           47 |      704 | 2024-07-17 | 9INE             | L   | 1.000      | -            | -                | -                | -         |   -13.50 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           46 |      755 | 2024-07-16 | Metizport        | L   | 1.000      | -            | -                | -                | -         |   -17.77 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           45 |      802 | 2024-07-15 | Johnny Speeds    | L   | 1.000      | -            | -                | -                | -         |    -3.94 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           44 |      863 | 2024-07-11 | Sashi            | L   | 1.000      | -            | -                | -                | -         |    -4.75 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           43 |      868 | 2024-07-11 | 9INE             | W   | 1.000      | 0.358        | 0.022 (0.008)    | 0.539 (0.193)    | 0 (0.000) |    17.08 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           42 |      888 | 2024-07-10 | Johnny Speeds    | L   | 1.000      | -            | -                | -                | -         |    -3.64 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           41 |      908 | 2024-07-09 | ROSOMAHA         | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.05 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           40 |     1089 | 2024-06-14 | GamerLegion      | L   | 0.854      | -            | -                | -                | -         |    -4.33 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           39 |     1199 | 2024-06-10 | MOUZ NXT         | W   | 0.827      | 0.450        | 0.139 (0.052)    | 1.000 (0.372)    | 0 (0.000) |    20.28 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           38 |     1329 | 2024-06-08 | Entropiq         | W   | 0.812      | -            | -                | -                | 0 (0.000) |     1.83 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           37 |     1353 | 2024-06-07 | 9INE             | L   | 0.808      | -            | -                | -                | -         |   -11.27 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           36 |     1441 | 2024-06-06 | NAVI Junior      | L   | 0.800      | -            | -                | -                | -         |   -21.45 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           35 |     1453 | 2024-06-06 | 5W               | L   | 0.799      | -            | -                | -                | -         |   -11.33 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           34 |     1527 | 2024-06-04 | Rhyno            | L   | 0.788      | -            | -                | -                | -         |    -9.79 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           33 |     1748 | 2024-05-27 | Rhyno            | L   | 0.733      | -            | -                | -                | -         |    -9.27 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           32 |     1800 | 2024-05-24 | ALTERNATE aTTaX  | W   | 0.713      | 0.435        | 0.031 (0.010)    | 0.557 (0.173)    | 0 (0.000) |    10.84 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           31 |     1854 | 2024-05-22 | Permitta         | L   | 0.701      | -            | -                | -                | -         |   -11.88 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           30 |     1904 | 2024-05-21 | RUBY             | L   | 0.692      | -            | -                | -                | -         |   -10.42 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           29 |     1957 | 2024-05-19 | Sangal           | L   | 0.680      | -            | -                | -                | -         |    -6.20 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           28 |     2022 | 2024-05-17 | Zero Tenacity    | L   | 0.667      | -            | -                | -                | -         |    -6.76 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           27 |     2108 | 2024-05-15 | Passion UA       | W   | 0.654      | 0.435        | 0.173 (0.049)    | 1.000 (0.284)    | 0 (0.000) |    12.79 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           26 |     2116 | 2024-05-15 | Sashi            | L   | 0.652      | -            | -                | -                | -         |    -3.51 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           25 |     2172 | 2024-05-14 | ALTERNATE aTTaX  | L   | 0.646      | -            | -                | -                | -         |    -9.20 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           24 |     2234 | 2024-05-11 | MOUZ NXT         | L   | 0.628      | -            | -                | -                | -         |    -6.98 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           23 |     2285 | 2024-05-09 | PARIVISION       | W   | 0.614      | -            | -                | -                | -         |    13.20 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           22 |     2367 | 2024-05-05 | SINNERS          | L   | 0.587      | -            | -                | -                | -         |    -6.01 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           21 |     2388 | 2024-05-04 | Sampi            | W   | 0.579      | 0.435        | 0.027 (0.007)    | 1.000 (0.252)    | -         |     8.83 | AZUWU, CRUC1AL, Frøg, MiGHTYMAX, Surreal  |
|           20 |     2414 | 2024-05-02 | MOUZ NXT         | W   | 0.568      | 0.435        | 0.139 (0.034)    | 1.000 (0.247)    | -         |    12.03 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           19 |     2426 | 2024-05-02 | Grannys Knockers | W   | 0.566      | -            | -                | -                | -         |     5.37 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           18 |     2465 | 2024-04-30 | ALTERNATE aTTaX  | W   | 0.554      | 0.396        | 0.031 (0.007)    | -                | -         |    10.19 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           17 |     2470 | 2024-04-30 | ENCE Academy     | W   | 0.553      | -            | -                | -                | -         |     4.50 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           16 |     2485 | 2024-04-29 | Nexus            | W   | 0.548      | -            | -                | -                | -         |     7.14 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           15 |     2499 | 2024-04-29 | Alliance         | L   | 0.546      | -            | -                | -                | -         |    -9.31 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           14 |     2609 | 2024-04-24 | SINNERS          | W   | 0.513      | 0.384        | 0.037 (0.007)    | 0.794 (0.157)    | -         |    12.77 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           13 |     2841 | 2024-04-17 | EYEBALLERS       | W   | 0.466      | -            | -                | -                | -         |     7.40 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           12 |     3556 | 2024-03-15 | ex-sYnck         | W   | 0.247      | -            | -                | -                | -         |     0.83 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|           11 |     3587 | 2024-03-14 | The Chosen Few   | L   | 0.241      | -            | -                | -                | -         |    -5.76 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|           10 |     3659 | 2024-03-12 | Secret           | W   | 0.226      | -            | -                | -                | -         |     0.88 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|            9 |     3694 | 2024-03-10 | Nemiga           | L   | 0.214      | -            | -                | -                | -         |    -1.15 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|            8 |     3730 | 2024-03-09 | BLEED            | L   | 0.206      | -            | -                | -                | -         |    -2.53 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|            7 |     3762 | 2024-03-07 | kONO             | W   | 0.195      | -            | -                | -                | -         |     2.35 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|            6 |     3798 | 2024-03-06 | V1dar            | W   | 0.187      | -            | -                | -                | -         |     0.68 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|            5 |     3841 | 2024-03-05 | AURA             | W   | 0.180      | -            | -                | -                | -         |     0.57 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|            4 |     3936 | 2024-02-29 | Metizport        | L   | 0.147      | -            | -                | -                | -         |    -2.68 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|            3 |     3993 | 2024-02-26 | ALTERNATE aTTaX  | L   | 0.126      | -            | -                | -                | -         |    -1.49 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|            2 |     4371 | 2024-02-09 | 3DMAX            | L   | 0.014      | -            | -                | -                | -         |    -0.01 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|            1 |     4377 | 2024-02-09 | fnatic           | L   | 0.013      | -            | -                | -                | -         |    -0.01 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,787.92)
- Divide that value by the 5th highest value among all rosters ($322,333.56)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-17 |      0.873 | $2,500.00      | $2,181.94       |
| 2024-05-18 |      0.674 | $500.00        | $337.22         |
| 2024-05-12 |      0.634 | $2,000.00      | $1,268.75       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
