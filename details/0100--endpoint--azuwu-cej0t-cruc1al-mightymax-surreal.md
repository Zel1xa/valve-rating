### Roster Details<br />
Team Name: Endpoint<br />
Roster: AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal<br />
Global Rank: [100](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [74]( ../standings_europe.md)<br />
<br />
Final Rank Value:  855.0<br />
<br />
Final Rank Value (855.0) = Starting Rank Value (890.5) + Head To Head Adjustments (-35.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.341[<sup>1</sup>](#table2)
- Bounty Collected: 0.370[<sup>2</sup>](#table1)
- Opponent Network: 0.248[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.240<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 890.5
- 400 + ( ( 0.240 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 890.5


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
|           57 |      139 | 2024-07-31 | K27              | W   | 1.000      | -            | -                | -                | 0 (0.000) |     5.69 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           56 |      149 | 2024-07-31 | Permitta         | W   | 1.000      | 0.426        | 0.024 (0.010)    | 0.876 (0.373)    | 0 (0.000) |    19.56 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           55 |      194 | 2024-07-30 | GUN5             | L   | 1.000      | -            | -                | -                | -         |   -13.27 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           54 |      263 | 2024-07-28 | Space            | W   | 1.000      | 0.435        | -                | 0.406 (0.177)    | 0 (0.000) |    17.64 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           53 |      296 | 2024-07-26 | Sampi            | L   | 1.000      | -            | -                | -                | -         |   -12.79 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           52 |      348 | 2024-07-25 | Monte            | L   | 1.000      | -            | -                | -                | -         |    -7.50 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           51 |      467 | 2024-07-21 | GUN5             | L   | 1.000      | -            | -                | -                | -         |   -12.59 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           50 |      540 | 2024-07-19 | ALTERNATE aTTaX  | W   | 1.000      | 0.435        | 0.031 (0.014)    | 0.560 (0.243)    | 0 (0.000) |    15.49 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           49 |      654 | 2024-07-17 | SINNERS          | L   | 1.000      | -            | -                | -                | -         |   -11.18 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           48 |      664 | 2024-07-17 | 9INE             | L   | 1.000      | -            | -                | -                | -         |   -13.73 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           47 |      715 | 2024-07-16 | Metizport        | L   | 1.000      | -            | -                | -                | -         |   -11.62 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           46 |      761 | 2024-07-15 | Johnny Speeds    | L   | 1.000      | -            | -                | -                | -         |    -4.04 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           45 |      822 | 2024-07-11 | Sashi            | L   | 1.000      | -            | -                | -                | -         |    -4.74 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           44 |      827 | 2024-07-11 | 9INE             | W   | 1.000      | 0.358        | 0.022 (0.008)    | 0.537 (0.192)    | 0 (0.000) |    17.11 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           43 |      847 | 2024-07-10 | Johnny Speeds    | L   | 1.000      | -            | -                | -                | -         |    -3.74 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           42 |      867 | 2024-07-09 | ROSOMAHA         | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.08 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           41 |     1048 | 2024-06-14 | GamerLegion      | L   | 0.861      | -            | -                | -                | -         |    -4.33 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           40 |     1158 | 2024-06-10 | MOUZ NXT         | W   | 0.833      | 0.450        | 0.139 (0.052)    | 1.000 (0.375)    | 0 (0.000) |    20.40 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           39 |     1288 | 2024-06-08 | Entropiq         | W   | 0.819      | -            | -                | -                | 0 (0.000) |     1.86 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           38 |     1312 | 2024-06-07 | 9INE             | L   | 0.815      | -            | -                | -                | -         |   -11.33 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           37 |     1400 | 2024-06-06 | NAVI Junior      | L   | 0.807      | -            | -                | -                | -         |   -21.59 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           36 |     1412 | 2024-06-06 | 5W               | L   | 0.806      | -            | -                | -                | -         |   -11.35 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           35 |     1486 | 2024-06-04 | Rhyno            | L   | 0.795      | -            | -                | -                | -         |    -9.80 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           34 |     1707 | 2024-05-27 | Rhyno            | L   | 0.740      | -            | -                | -                | -         |    -9.28 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           33 |     1759 | 2024-05-24 | ALTERNATE aTTaX  | W   | 0.720      | 0.435        | 0.031 (0.010)    | 0.560 (0.175)    | 0 (0.000) |    10.93 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           32 |     1813 | 2024-05-22 | Permitta         | L   | 0.707      | -            | -                | -                | -         |   -11.99 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           31 |     1863 | 2024-05-21 | RUBY             | L   | 0.699      | -            | -                | -                | -         |   -10.34 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           30 |     1916 | 2024-05-19 | Sangal           | L   | 0.687      | -            | -                | -                | -         |    -6.37 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           29 |     1981 | 2024-05-17 | Zero Tenacity    | L   | 0.674      | -            | -                | -                | -         |    -6.86 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           28 |     2067 | 2024-05-15 | Passion UA       | W   | 0.660      | 0.435        | 0.172 (0.049)    | 1.000 (0.287)    | 0 (0.000) |    12.81 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           27 |     2075 | 2024-05-15 | Sashi            | L   | 0.659      | -            | -                | -                | -         |    -3.52 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           26 |     2131 | 2024-05-14 | ALTERNATE aTTaX  | L   | 0.653      | -            | -                | -                | -         |    -9.27 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           25 |     2193 | 2024-05-11 | MOUZ NXT         | L   | 0.635      | -            | -                | -                | -         |    -7.09 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           24 |     2244 | 2024-05-09 | PARIVISION       | W   | 0.621      | -            | -                | -                | -         |    13.27 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           23 |     2326 | 2024-05-05 | SINNERS          | L   | 0.593      | -            | -                | -                | -         |    -7.01 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           22 |     2347 | 2024-05-04 | Sampi            | W   | 0.586      | 0.435        | 0.027 (0.007)    | 1.000 (0.255)    | -         |     8.96 | AZUWU, CRUC1AL, Frøg, MiGHTYMAX, Surreal  |
|           21 |     2373 | 2024-05-02 | MOUZ NXT         | W   | 0.575      | 0.435        | 0.139 (0.035)    | 1.000 (0.250)    | -         |    12.13 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           20 |     2385 | 2024-05-02 | Grannys Knockers | W   | 0.573      | -            | -                | -                | -         |     5.44 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           19 |     2424 | 2024-04-30 | ALTERNATE aTTaX  | W   | 0.561      | 0.396        | 0.031 (0.007)    | -                | -         |    10.32 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           18 |     2429 | 2024-04-30 | ENCE Academy     | W   | 0.560      | -            | -                | -                | -         |     4.57 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           17 |     2444 | 2024-04-29 | Nexus            | W   | 0.554      | -            | -                | -                | -         |     7.25 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           16 |     2458 | 2024-04-29 | Alliance         | L   | 0.552      | -            | -                | -                | -         |    -9.39 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           15 |     2568 | 2024-04-24 | SINNERS          | W   | 0.520      | 0.384        | 0.037 (0.007)    | 0.757 (0.151)    | -         |    12.19 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           14 |     2800 | 2024-04-17 | EYEBALLERS       | W   | 0.472      | -            | -                | -                | -         |     7.54 | AZUWU, cej0t, CRUC1AL, MiGHTYMAX, Surreal |
|           13 |     3515 | 2024-03-15 | ex-sYnck         | W   | 0.253      | -            | -                | -                | -         |     0.85 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|           12 |     3546 | 2024-03-14 | The Chosen Few   | L   | 0.248      | -            | -                | -                | -         |    -5.91 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|           11 |     3618 | 2024-03-12 | Secret           | W   | 0.233      | -            | -                | -                | -         |     0.90 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|           10 |     3653 | 2024-03-10 | Nemiga           | L   | 0.221      | -            | -                | -                | -         |    -1.30 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|            9 |     3689 | 2024-03-09 | BLEED            | L   | 0.213      | -            | -                | -                | -         |    -2.61 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|            8 |     3721 | 2024-03-07 | kONO             | W   | 0.202      | -            | -                | -                | -         |     2.44 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|            7 |     3757 | 2024-03-06 | V1dar            | W   | 0.194      | -            | -                | -                | -         |     0.71 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|            6 |     3800 | 2024-03-05 | AURA             | W   | 0.187      | -            | -                | -                | -         |     0.60 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|            5 |     3895 | 2024-02-29 | Metizport        | L   | 0.154      | -            | -                | -                | -         |    -2.33 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|            4 |     3952 | 2024-02-26 | ALTERNATE aTTaX  | L   | 0.133      | -            | -                | -                | -         |    -1.56 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|            3 |     4330 | 2024-02-09 | 3DMAX            | L   | 0.021      | -            | -                | -                | -         |    -0.01 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|            2 |     4336 | 2024-02-09 | fnatic           | L   | 0.020      | -            | -                | -                | -         |    -0.01 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |
|            1 |     4357 | 2024-02-07 | Permitta         | W   | 0.006      | -            | -                | -                | -         |     0.11 | AZUWU, MiGHTYMAX, sl3nd, Surreal, swicher |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,821.83)
- Divide that value by the 5th highest value among all rosters ($324,344.55)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-17 |      0.880 | $2,500.00      | $2,198.90       |
| 2024-05-18 |      0.681 | $500.00        | $340.61         |
| 2024-05-12 |      0.641 | $2,000.00      | $1,282.31       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
