### Roster Details<br />
Team Name: Endpoint<br />
Roster: AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal<br />
Global Rank: [93](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [66]( ../standings_europe.md)<br />
<br />
Final Rank Value:  872.8<br />
<br />
Final Rank Value (872.8) = Starting Rank Value (913.3) + Head To Head Adjustments (-40.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.342[<sup>1</sup>](#table2)
- Bounty Collected: 0.385[<sup>2</sup>](#table1)
- Opponent Network: 0.271[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.250<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 913.3
- 400 + ( ( 0.250 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 913.3


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
|           58 |       46 | 2024-07-31 | K27              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.26 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           57 |       56 | 2024-07-31 | Permitta         | W   | 1.000      | 0.426        | 0.024 (0.010)    | 0.801 (0.341)    | 0 (0.000) |    18.54 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           56 |      102 | 2024-07-30 | GUN5             | L   | 1.000      | -            | -                | -                | -         |   -14.07 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           55 |      171 | 2024-07-28 | Space            | W   | 1.000      | 0.435        | -                | 0.406 (0.177)    | 0 (0.000) |    16.83 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           54 |      204 | 2024-07-26 | Sampi            | L   | 1.000      | -            | -                | -                | -         |   -13.73 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           53 |      256 | 2024-07-25 | Monte            | L   | 1.000      | -            | -                | -                | -         |    -8.61 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           52 |      377 | 2024-07-21 | GUN5             | L   | 1.000      | -            | -                | -                | -         |   -12.92 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           51 |      453 | 2024-07-19 | ALTERNATE aTTaX  | W   | 1.000      | 0.435        | 0.032 (0.014)    | 0.563 (0.245)    | 0 (0.000) |    13.76 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           50 |      571 | 2024-07-17 | SINNERS          | L   | 1.000      | -            | -                | -                | -         |   -12.61 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           49 |      580 | 2024-07-17 | 9INE             | L   | 1.000      | -            | -                | -                | -         |   -13.45 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           48 |      633 | 2024-07-16 | Metizport        | L   | 1.000      | -            | -                | -                | -         |   -12.65 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           47 |      685 | 2024-07-15 | Johnny Speeds    | L   | 1.000      | -            | -                | -                | -         |    -4.46 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           46 |      747 | 2024-07-11 | Sashi            | L   | 1.000      | -            | -                | -                | -         |    -5.36 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           45 |      752 | 2024-07-11 | 9INE             | W   | 1.000      | 0.358        | 0.022 (0.008)    | 0.521 (0.187)    | 0 (0.000) |    17.56 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           44 |      772 | 2024-07-10 | Johnny Speeds    | L   | 1.000      | -            | -                | -                | -         |    -4.14 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           43 |      792 | 2024-07-09 | ROSOMAHA         | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.57 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           42 |      961 | 2024-06-14 | GamerLegion      | L   | 0.879      | -            | -                | -                | -         |    -5.00 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           41 |     1074 | 2024-06-10 | MOUZ NXT         | W   | 0.852      | 0.450        | 0.141 (0.054)    | 1.000 (0.384)    | 0 (0.000) |    20.27 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           40 |     1138 | 2024-06-09 | Zero Tenacity    | W   | 0.845      | 0.450        | 0.139 (0.053)    | 1.000 (0.380)    | 0 (0.000) |    18.62 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           39 |     1207 | 2024-06-08 | Entropiq         | W   | 0.838      | -            | -                | -                | 0 (0.000) |     1.80 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           38 |     1237 | 2024-06-07 | 9INE             | L   | 0.834      | -            | -                | -                | -         |   -11.12 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           37 |     1327 | 2024-06-06 | NAVI Junior      | L   | 0.825      | -            | -                | -                | -         |   -22.23 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           36 |     1340 | 2024-06-06 | 5W               | L   | 0.824      | -            | -                | -                | -         |   -11.79 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           35 |     1416 | 2024-06-04 | Rhyno            | L   | 0.814      | -            | -                | -                | -         |   -10.08 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           34 |     1639 | 2024-05-27 | Rhyno            | L   | 0.759      | -            | -                | -                | -         |    -9.56 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           33 |     1692 | 2024-05-24 | ALTERNATE aTTaX  | W   | 0.739      | 0.435        | 0.032 (0.010)    | 0.563 (0.181)    | 0 (0.000) |    10.50 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           32 |     1746 | 2024-05-22 | Permitta         | L   | 0.726      | -            | -                | -                | -         |   -12.85 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           31 |     1811 | 2024-05-21 | RUBY             | L   | 0.718      | -            | -                | -                | -         |   -10.70 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           30 |     1874 | 2024-05-19 | Sangal           | L   | 0.706      | -            | -                | -                | -         |    -7.13 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           29 |     1940 | 2024-05-17 | Zero Tenacity    | L   | 0.693      | -            | -                | -                | -         |    -7.53 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           28 |     2026 | 2024-05-15 | Passion UA       | W   | 0.679      | 0.435        | 0.173 (0.051)    | 1.000 (0.295)    | -         |    12.66 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           27 |     2038 | 2024-05-15 | Sashi            | L   | 0.678      | -            | -                | -                | -         |    -3.81 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           26 |     2097 | 2024-05-14 | ALTERNATE aTTaX  | L   | 0.672      | -            | -                | -                | -         |   -10.33 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           25 |     2161 | 2024-05-11 | MOUZ NXT         | L   | 0.654      | -            | -                | -                | -         |    -8.27 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           24 |     2212 | 2024-05-09 | PARIVISION       | W   | 0.639      | -            | -                | -                | -         |    13.29 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           23 |     2296 | 2024-05-05 | SINNERS          | L   | 0.612      | -            | -                | -                | -         |    -8.08 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           22 |     2317 | 2024-05-04 | Sampi            | W   | 0.604      | 0.435        | -                | 1.000 (0.263)    | -         |     8.56 | AZUWU, CRUC1AL, Frøg, MiGHTYMAX, Surreal  |
|           21 |     2343 | 2024-05-02 | MOUZ NXT         | W   | 0.594      | 0.435        | 0.141 (0.036)    | 1.000 (0.258)    | -         |    11.54 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           20 |     2356 | 2024-05-02 | Grannys Knockers | W   | 0.592      | -            | -                | -                | -         |     5.77 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           19 |     2397 | 2024-04-30 | ALTERNATE aTTaX  | W   | 0.579      | 0.396        | 0.032 (0.007)    | -                | -         |    10.20 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           18 |     2402 | 2024-04-30 | ENCE Academy     | W   | 0.579      | -            | -                | -                | -         |     4.63 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           17 |     2417 | 2024-04-29 | Nexus            | W   | 0.573      | -            | -                | -                | -         |     7.14 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           16 |     2431 | 2024-04-29 | Alliance         | L   | 0.571      | -            | -                | -                | -         |   -10.13 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           15 |     2541 | 2024-04-24 | SINNERS          | W   | 0.539      | 0.384        | 0.038 (0.008)    | -                | -         |    11.93 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           14 |     2782 | 2024-04-17 | EYEBALLERS       | W   | 0.491      | -            | -                | -                | -         |     7.46 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           13 |     3512 | 2024-03-15 | ex-sYnck         | W   | 0.272      | -            | -                | -                | -         |     0.83 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|           12 |     3545 | 2024-03-14 | The Chosen Few   | L   | 0.267      | -            | -                | -                | -         |    -6.50 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|           11 |     3620 | 2024-03-12 | Secret           | W   | 0.251      | -            | -                | -                | -         |     0.89 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|           10 |     3655 | 2024-03-10 | Nemiga           | L   | 0.240      | -            | -                | -                | -         |    -1.47 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|            9 |     3692 | 2024-03-09 | BLEED            | L   | 0.231      | -            | -                | -                | -         |    -2.97 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|            8 |     3724 | 2024-03-07 | kONO             | W   | 0.220      | -            | -                | -                | -         |     2.54 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|            7 |     3760 | 2024-03-06 | V1dar            | W   | 0.213      | -            | -                | -                | -         |     0.71 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|            6 |     3808 | 2024-03-05 | AURA             | W   | 0.206      | -            | -                | -                | -         |     0.61 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|            5 |     3904 | 2024-02-29 | Metizport        | L   | 0.172      | -            | -                | -                | -         |    -2.79 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|            4 |     3963 | 2024-02-26 | ALTERNATE aTTaX  | L   | 0.151      | -            | -                | -                | -         |    -1.87 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|            3 |     4358 | 2024-02-09 | 3DMAX            | L   | 0.040      | -            | -                | -                | -         |    -0.02 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|            2 |     4364 | 2024-02-09 | fnatic           | L   | 0.039      | -            | -                | -                | -         |    -0.09 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|            1 |     4385 | 2024-02-07 | Permitta         | W   | 0.025      | -            | -                | -                | -         |     0.42 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,915.69)
- Divide that value by the 5th highest value among all rosters ($327,030.46)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-17 |      0.898 | $2,500.00      | $2,245.83       |
| 2024-05-18 |      0.700 | $500.00        | $350.00         |
| 2024-05-12 |      0.660 | $2,000.00      | $1,319.86       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
