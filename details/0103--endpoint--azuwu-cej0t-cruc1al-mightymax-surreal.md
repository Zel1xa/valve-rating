### Roster Details<br />
Team Name: Endpoint<br />
Roster: AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal<br />
Global Rank: [103](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [74]( ../standings_europe.md)<br />
<br />
Final Rank Value:  853.3<br />
<br />
Final Rank Value (853.3) = Starting Rank Value (891.2) + Head To Head Adjustments (-38.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.341[<sup>1</sup>](#table2)
- Bounty Collected: 0.369[<sup>2</sup>](#table1)
- Opponent Network: 0.247[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.239<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 891.2
- 400 + ( ( 0.239 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 891.2


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
|           56 |      191 | 2024-07-31 | K27              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.74 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           55 |      201 | 2024-07-31 | Permitta         | W   | 1.000      | 0.426        | 0.023 (0.010)    | 0.901 (0.384)    | 0 (0.000) |    19.63 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           54 |      246 | 2024-07-30 | GUN5             | L   | 1.000      | -            | -                | -                | -         |   -13.19 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           53 |      315 | 2024-07-28 | Space            | W   | 1.000      | 0.435        | -                | 0.439 (0.191)    | 0 (0.000) |    17.70 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           52 |      348 | 2024-07-26 | Sampi            | L   | 1.000      | -            | -                | -                | -         |   -12.69 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           51 |      400 | 2024-07-25 | Monte            | L   | 1.000      | -            | -                | -                | -         |    -7.38 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           50 |      519 | 2024-07-21 | GUN5             | L   | 1.000      | -            | -                | -                | -         |   -12.51 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           49 |      592 | 2024-07-19 | ALTERNATE aTTaX  | W   | 1.000      | 0.435        | 0.031 (0.014)    | 0.550 (0.239)    | 0 (0.000) |    15.85 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           48 |      706 | 2024-07-17 | SINNERS          | L   | 1.000      | -            | -                | -                | -         |   -10.32 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           47 |      715 | 2024-07-17 | 9INE             | L   | 1.000      | -            | -                | -                | -         |   -13.51 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           46 |      766 | 2024-07-16 | Metizport        | L   | 1.000      | -            | -                | -                | -         |   -17.81 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           45 |      813 | 2024-07-15 | Johnny Speeds    | L   | 1.000      | -            | -                | -                | -         |    -3.96 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           44 |      874 | 2024-07-11 | Sashi            | L   | 1.000      | -            | -                | -                | -         |    -4.76 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           43 |      879 | 2024-07-11 | 9INE             | W   | 1.000      | 0.358        | 0.022 (0.008)    | 0.533 (0.191)    | 0 (0.000) |    17.07 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           42 |      899 | 2024-07-10 | Johnny Speeds    | L   | 1.000      | -            | -                | -                | -         |    -3.66 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           41 |      919 | 2024-07-09 | ROSOMAHA         | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.04 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           40 |     1100 | 2024-06-14 | GamerLegion      | L   | 0.851      | -            | -                | -                | -         |    -4.34 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           39 |     1210 | 2024-06-10 | MOUZ NXT         | W   | 0.823      | 0.450        | 0.139 (0.051)    | 0.986 (0.365)    | 0 (0.000) |    20.20 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           38 |     1340 | 2024-06-08 | Entropiq         | W   | 0.809      | -            | -                | -                | 0 (0.000) |     1.81 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           37 |     1364 | 2024-06-07 | 9INE             | L   | 0.805      | -            | -                | -                | -         |   -11.23 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           36 |     1452 | 2024-06-06 | NAVI Junior      | L   | 0.796      | -            | -                | -                | -         |   -21.37 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           35 |     1464 | 2024-06-06 | 5W               | L   | 0.796      | -            | -                | -                | -         |   -11.30 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           34 |     1538 | 2024-06-04 | Rhyno            | L   | 0.785      | -            | -                | -                | -         |    -9.79 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           33 |     1759 | 2024-05-27 | Rhyno            | L   | 0.730      | -            | -                | -                | -         |    -9.27 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           32 |     1811 | 2024-05-24 | ALTERNATE aTTaX  | W   | 0.710      | 0.435        | 0.031 (0.010)    | 0.550 (0.170)    | 0 (0.000) |    10.81 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           31 |     1865 | 2024-05-22 | Permitta         | L   | 0.697      | -            | -                | -                | -         |   -11.60 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           30 |     1915 | 2024-05-21 | RUBY             | L   | 0.689      | -            | -                | -                | -         |   -10.35 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           29 |     1968 | 2024-05-19 | Sangal           | L   | 0.677      | -            | -                | -                | -         |    -6.13 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           28 |     2033 | 2024-05-17 | Zero Tenacity    | L   | 0.664      | -            | -                | -                | -         |    -6.75 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           27 |     2119 | 2024-05-15 | Passion UA       | W   | 0.650      | 0.435        | 0.173 (0.049)    | 1.000 (0.283)    | 0 (0.000) |    12.81 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           26 |     2127 | 2024-05-15 | Sashi            | L   | 0.649      | -            | -                | -                | -         |    -3.49 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           25 |     2183 | 2024-05-14 | ALTERNATE aTTaX  | L   | 0.643      | -            | -                | -                | -         |    -9.13 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           24 |     2245 | 2024-05-11 | MOUZ NXT         | L   | 0.625      | -            | -                | -                | -         |    -6.93 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           23 |     2296 | 2024-05-09 | PARIVISION       | W   | 0.611      | -            | -                | -                | -         |    13.19 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           22 |     2378 | 2024-05-05 | SINNERS          | L   | 0.583      | -            | -                | -                | -         |    -5.87 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           21 |     2399 | 2024-05-04 | Sampi            | W   | 0.576      | 0.435        | 0.027 (0.007)    | 1.000 (0.250)    | -         |     8.80 | AZUWU, CRUC1AL, Frøg, MiGHTYMAX, Surreal  |
|           20 |     2425 | 2024-05-02 | MOUZ NXT         | W   | 0.565      | 0.435        | 0.139 (0.034)    | 0.986 (0.242)    | -         |    11.97 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           19 |     2437 | 2024-05-02 | Grannys Knockers | W   | 0.563      | -            | -                | -                | -         |     5.33 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           18 |     2476 | 2024-04-30 | ALTERNATE aTTaX  | W   | 0.551      | 0.396        | 0.031 (0.007)    | -                | -         |    10.15 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           17 |     2481 | 2024-04-30 | ENCE Academy     | W   | 0.550      | -            | -                | -                | -         |     4.46 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           16 |     2496 | 2024-04-29 | Nexus            | W   | 0.544      | -            | -                | -                | -         |     7.11 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           15 |     2510 | 2024-04-29 | Alliance         | L   | 0.542      | -            | -                | -                | -         |    -9.27 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           14 |     2620 | 2024-04-24 | SINNERS          | W   | 0.510      | 0.384        | 0.037 (0.007)    | 0.808 (0.158)    | -         |    12.77 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           13 |     2852 | 2024-04-17 | EYEBALLERS       | W   | 0.462      | -            | -                | -                | -         |     7.37 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           12 |     3567 | 2024-03-15 | ex-sYnck         | W   | 0.243      | -            | -                | -                | -         |     0.81 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|           11 |     3598 | 2024-03-14 | The Chosen Few   | L   | 0.238      | -            | -                | -                | -         |    -5.68 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|           10 |     3670 | 2024-03-12 | Secret           | W   | 0.223      | -            | -                | -                | -         |     0.86 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|            9 |     3705 | 2024-03-10 | Nemiga           | L   | 0.211      | -            | -                | -                | -         |    -1.14 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|            8 |     3741 | 2024-03-09 | BLEED            | L   | 0.203      | -            | -                | -                | -         |    -2.50 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|            7 |     3773 | 2024-03-07 | kONO             | W   | 0.191      | -            | -                | -                | -         |     2.31 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|            6 |     3809 | 2024-03-06 | V1dar            | W   | 0.184      | -            | -                | -                | -         |     0.67 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|            5 |     3852 | 2024-03-05 | AURA             | W   | 0.177      | -            | -                | -                | -         |     0.55 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|            4 |     3947 | 2024-02-29 | Metizport        | L   | 0.144      | -            | -                | -                | -         |    -2.62 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|            3 |     4004 | 2024-02-26 | ALTERNATE aTTaX  | L   | 0.122      | -            | -                | -                | -         |    -1.45 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|            2 |     4382 | 2024-02-09 | 3DMAX            | L   | 0.011      | -            | -                | -                | -         |    -0.00 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|            1 |     4388 | 2024-02-09 | fnatic           | L   | 0.010      | -            | -                | -                | -         |    -0.01 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,771.25)
- Divide that value by the 5th highest value among all rosters ($321,345.23)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-17 |      0.869 | $2,500.00      | $2,173.61       |
| 2024-05-18 |      0.671 | $500.00        | $335.56         |
| 2024-05-12 |      0.631 | $2,000.00      | $1,262.08       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
