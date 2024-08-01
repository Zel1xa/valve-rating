### Roster Details<br />
Team Name: Endpoint<br />
Roster: AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal<br />
Global Rank: [94](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [67]( ../standings_europe.md)<br />
<br />
Final Rank Value:  873.4<br />
<br />
Final Rank Value (873.4) = Starting Rank Value (914.1) + Head To Head Adjustments (-40.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.342[<sup>1</sup>](#table2)
- Bounty Collected: 0.385[<sup>2</sup>](#table1)
- Opponent Network: 0.271[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.250<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 914.1
- 400 + ( ( 0.250 - 0.000 ) / ( 0.777 - 0.000 ) ) * 1600 = 914.1


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
|           58 |       42 | 2024-07-31 | K27              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.25 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           57 |       52 | 2024-07-31 | Permitta         | W   | 1.000      | 0.426        | 0.024 (0.010)    | 0.801 (0.341)    | 0 (0.000) |    18.49 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           56 |       98 | 2024-07-30 | GUN5             | L   | 1.000      | -            | -                | -                | -         |   -14.12 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           55 |      167 | 2024-07-28 | Space            | W   | 1.000      | 0.435        | -                | 0.406 (0.177)    | 0 (0.000) |    16.83 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           54 |      200 | 2024-07-26 | Sampi            | L   | 1.000      | -            | -                | -                | -         |   -13.74 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           53 |      252 | 2024-07-25 | Monte            | L   | 1.000      | -            | -                | -                | -         |    -8.61 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           52 |      373 | 2024-07-21 | GUN5             | L   | 1.000      | -            | -                | -                | -         |   -12.91 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           51 |      449 | 2024-07-19 | ALTERNATE aTTaX  | W   | 1.000      | 0.435        | 0.032 (0.014)    | 0.564 (0.245)    | 0 (0.000) |    13.75 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           50 |      567 | 2024-07-17 | SINNERS          | L   | 1.000      | -            | -                | -                | -         |   -12.63 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           49 |      576 | 2024-07-17 | 9INE             | L   | 1.000      | -            | -                | -                | -         |   -13.45 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           48 |      629 | 2024-07-16 | Metizport        | L   | 1.000      | -            | -                | -                | -         |   -12.68 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           47 |      681 | 2024-07-15 | Johnny Speeds    | L   | 1.000      | -            | -                | -                | -         |    -4.46 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           46 |      743 | 2024-07-11 | Sashi            | L   | 1.000      | -            | -                | -                | -         |    -5.38 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           45 |      748 | 2024-07-11 | 9INE             | W   | 1.000      | 0.358        | 0.022 (0.008)    | 0.521 (0.186)    | 0 (0.000) |    17.55 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           44 |      768 | 2024-07-10 | Johnny Speeds    | L   | 1.000      | -            | -                | -                | -         |    -4.14 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           43 |      788 | 2024-07-09 | ROSOMAHA         | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.56 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           42 |      957 | 2024-06-14 | GamerLegion      | L   | 0.881      | -            | -                | -                | -         |    -4.99 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           41 |     1070 | 2024-06-10 | MOUZ NXT         | W   | 0.854      | 0.450        | 0.141 (0.054)    | 1.000 (0.384)    | 0 (0.000) |    20.31 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           40 |     1134 | 2024-06-09 | Zero Tenacity    | W   | 0.846      | 0.450        | 0.139 (0.053)    | 1.000 (0.381)    | 0 (0.000) |    18.65 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           39 |     1203 | 2024-06-08 | Entropiq         | W   | 0.839      | -            | -                | -                | 0 (0.000) |     1.79 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           38 |     1233 | 2024-06-07 | 9INE             | L   | 0.835      | -            | -                | -                | -         |   -11.14 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           37 |     1323 | 2024-06-06 | NAVI Junior      | L   | 0.827      | -            | -                | -                | -         |   -22.27 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           36 |     1336 | 2024-06-06 | 5W               | L   | 0.826      | -            | -                | -                | -         |   -11.81 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           35 |     1412 | 2024-06-04 | Rhyno            | L   | 0.815      | -            | -                | -                | -         |   -10.09 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           34 |     1635 | 2024-05-27 | Rhyno            | L   | 0.760      | -            | -                | -                | -         |    -9.57 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           33 |     1688 | 2024-05-24 | ALTERNATE aTTaX  | W   | 0.740      | 0.435        | 0.032 (0.010)    | 0.564 (0.181)    | 0 (0.000) |    10.52 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           32 |     1742 | 2024-05-22 | Permitta         | L   | 0.728      | -            | -                | -                | -         |   -12.88 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           31 |     1807 | 2024-05-21 | RUBY             | L   | 0.719      | -            | -                | -                | -         |   -10.72 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           30 |     1870 | 2024-05-19 | Sangal           | L   | 0.707      | -            | -                | -                | -         |    -7.16 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           29 |     1936 | 2024-05-17 | Zero Tenacity    | L   | 0.694      | -            | -                | -                | -         |    -7.54 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           28 |     2022 | 2024-05-15 | Passion UA       | W   | 0.681      | 0.435        | 0.172 (0.051)    | 1.000 (0.296)    | -         |    12.68 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           27 |     2034 | 2024-05-15 | Sashi            | L   | 0.679      | -            | -                | -                | -         |    -3.82 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           26 |     2093 | 2024-05-14 | ALTERNATE aTTaX  | L   | 0.673      | -            | -                | -                | -         |   -10.35 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           25 |     2157 | 2024-05-11 | MOUZ NXT         | L   | 0.655      | -            | -                | -                | -         |    -8.28 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           24 |     2208 | 2024-05-09 | PARIVISION       | W   | 0.641      | -            | -                | -                | -         |    13.32 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           23 |     2292 | 2024-05-05 | SINNERS          | L   | 0.614      | -            | -                | -                | -         |    -8.10 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           22 |     2313 | 2024-05-04 | Sampi            | W   | 0.606      | 0.435        | 0.028 (0.007)    | 1.000 (0.263)    | -         |     8.58 | AZUWU, CRUC1AL, Frøg, MiGHTYMAX, Surreal  |
|           21 |     2339 | 2024-05-02 | MOUZ NXT         | W   | 0.595      | 0.435        | 0.141 (0.036)    | 1.000 (0.259)    | -         |    11.57 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           20 |     2352 | 2024-05-02 | Grannys Knockers | W   | 0.593      | -            | -                | -                | -         |     5.78 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           19 |     2393 | 2024-04-30 | ALTERNATE aTTaX  | W   | 0.581      | -            | -                | -                | -         |    10.23 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           18 |     2398 | 2024-04-30 | ENCE Academy     | W   | 0.580      | -            | -                | -                | -         |     4.64 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           17 |     2413 | 2024-04-29 | Nexus            | W   | 0.575      | -            | -                | -                | -         |     7.15 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           16 |     2427 | 2024-04-29 | Alliance         | L   | 0.573      | -            | -                | -                | -         |   -10.15 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           15 |     2537 | 2024-04-24 | SINNERS          | W   | 0.540      | 0.384        | 0.038 (0.008)    | -                | -         |    11.97 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           14 |     2778 | 2024-04-17 | EYEBALLERS       | W   | 0.492      | -            | -                | -                | -         |     7.48 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           13 |     3508 | 2024-03-15 | ex-sYnck         | W   | 0.274      | -            | -                | -                | -         |     0.84 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|           12 |     3541 | 2024-03-14 | The Chosen Few   | L   | 0.268      | -            | -                | -                | -         |    -6.54 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|           11 |     3616 | 2024-03-12 | Secret           | W   | 0.253      | -            | -                | -                | -         |     0.89 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|           10 |     3651 | 2024-03-10 | Nemiga           | L   | 0.241      | -            | -                | -                | -         |    -1.48 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|            9 |     3688 | 2024-03-09 | BLEED            | L   | 0.233      | -            | -                | -                | -         |    -2.99 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|            8 |     3720 | 2024-03-07 | kONO             | W   | 0.222      | -            | -                | -                | -         |     2.55 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|            7 |     3756 | 2024-03-06 | V1dar            | W   | 0.214      | -            | -                | -                | -         |     0.71 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|            6 |     3804 | 2024-03-05 | AURA             | W   | 0.207      | -            | -                | -                | -         |     0.61 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|            5 |     3900 | 2024-02-29 | Metizport        | L   | 0.174      | -            | -                | -                | -         |    -2.82 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|            4 |     3959 | 2024-02-26 | ALTERNATE aTTaX  | L   | 0.153      | -            | -                | -                | -         |    -1.88 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|            3 |     4354 | 2024-02-09 | 3DMAX            | L   | 0.041      | -            | -                | -                | -         |    -0.02 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|            2 |     4360 | 2024-02-09 | fnatic           | L   | 0.040      | -            | -                | -                | -         |    -0.09 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|            1 |     4381 | 2024-02-07 | Permitta         | W   | 0.026      | -            | -                | -                | -         |     0.44 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,922.64)
- Divide that value by the 5th highest value among all rosters ($327,422.13)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-17 |      0.900 | $2,500.00      | $2,249.31       |
| 2024-05-18 |      0.701 | $500.00        | $350.69         |
| 2024-05-12 |      0.661 | $2,000.00      | $1,322.64       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
