### Roster Details<br />
Team Name: Aurora Young Blud<br />
Roster: bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy<br />
Global Rank: [83](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [62]( ../standings_europe.md)<br />
<br />
Final Rank Value:  919.0<br />
<br />
Final Rank Value (919.0) = Starting Rank Value (813.8) + Head To Head Adjustments (105.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.286[<sup>1</sup>](#table2)
- Bounty Collected: 0.314[<sup>2</sup>](#table1)
- Opponent Network: 0.209[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.203<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 813.8
- 400 + ( ( 0.203 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 813.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent         | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                 |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           29 |      122 | 2024-07-31 | Sampi            | W   | 1.000      | 0.435        | 0.027 (0.012)    | 1.000 (0.435)    | 0 (0.000) |    15.20 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy |
|           28 |      207 | 2024-07-29 | EYEBALLERS       | W   | 1.000      | 0.435        | 0.006 (0.002)    | 0.510 (0.222)    | 0 (0.000) |    11.76 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy |
|           27 |      272 | 2024-07-27 | 9INE             | L   | 1.000      | -            | -                | -                | -         |   -12.29 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy |
|           26 |      339 | 2024-07-25 | MOUZ NXT         | L   | 1.000      | -            | -                | -                | -         |    -7.72 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy |
|           25 |      354 | 2024-07-24 | Astralis Talent  | W   | 1.000      | 0.435        | 0.009 (0.004)    | 0.162 (0.071)    | 0 (0.000) |     8.47 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy |
|           24 |      477 | 2024-07-20 | BC.Game          | W   | 1.000      | 0.435        | -                | 0.274 (0.119)    | 0 (0.000) |     8.48 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy |
|           23 |      573 | 2024-07-18 | Sampi            | W   | 1.000      | 0.435        | 0.027 (0.012)    | 1.000 (0.435)    | 0 (0.000) |    16.47 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy |
|           22 |      655 | 2024-07-17 | Passion UA       | L   | 1.000      | -            | -                | -                | -         |    -9.69 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy |
|           21 |      741 | 2024-07-15 | VP.Prodigy       | W   | 1.000      | 0.435        | 0.026 (0.011)    | 0.402 (0.175)    | 0 (0.000) |    15.83 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy |
|           20 |      753 | 2024-07-15 | BLEED            | L   | 1.000      | -            | -                | -                | -         |    -2.36 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy |
|           19 |      973 | 2024-06-16 | Preasy           | W   | 0.876      | -            | -                | -                | 0 (0.000) |    10.90 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy |
|           18 |     1024 | 2024-06-14 | Verdant          | W   | 0.865      | 0.143        | 0.015 (0.002)    | -                | 0 (0.000) |    15.01 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy |
|           17 |     1062 | 2024-06-13 | Astralis Talent  | W   | 0.859      | -            | -                | -                | 0 (0.000) |     9.47 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy |
|           16 |     1079 | 2024-06-13 | BLEED            | L   | 0.857      | -            | -                | -                | -         |    -1.47 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy |
|           15 |     1189 | 2024-06-09 | Sampi            | W   | 0.831      | 0.435        | 0.027 (0.010)    | 1.000 (0.361)    | 0 (0.000) |    15.24 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy |
|           14 |     1303 | 2024-06-07 | Insilio          | L   | 0.818      | -            | -                | -                | -         |    -9.04 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy |
|           13 |     1331 | 2024-06-07 | Passion UA       | L   | 0.816      | -            | -                | -                | -         |    -5.82 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy |
|           12 |     1364 | 2024-06-06 | Verdant          | W   | 0.812      | 0.372        | 0.015 (0.004)    | 0.299 (0.090)    | -         |    15.13 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy |
|           11 |     1437 | 2024-06-05 | Zero Tenacity    | L   | 0.804      | -            | -                | -                | -         |    -3.84 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy |
|           10 |     1451 | 2024-06-05 | Illuminar        | W   | 0.803      | 0.435        | 0.012 (0.004)    | 0.351 (0.123)    | -         |    12.43 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy |
|            9 |     1485 | 2024-06-04 | Spirit Academy   | W   | 0.797      | 0.372        | 0.013 (0.004)    | -                | -         |     9.92 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy |
|            8 |     1497 | 2024-06-04 | MOUZ NXT         | L   | 0.796      | -            | -                | -                | -         |    -4.11 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy |
|            7 |     1508 | 2024-06-03 | FLuffy Gangsters | W   | 0.792      | 0.372        | -                | 0.222 (0.065)    | -         |     5.37 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy |
|            6 |     1537 | 2024-06-02 | ThunderFlash     | W   | 0.784      | -            | -                | -                | -         |     2.31 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy |
|            5 |     1566 | 2024-06-01 | LEON             | W   | 0.777      | -            | -                | -                | -         |     8.85 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy |
|            4 |     1647 | 2024-05-29 | FAVBET           | L   | 0.758      | -            | -                | -                | -         |   -12.42 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy |
|            3 |     2807 | 2024-04-16 | ALTERNATE aTTaX  | L   | 0.470      | -            | -                | -                | -         |    -4.31 | bl1x1, bluewh1te, easy, sh1geo, VILBy  |
|            2 |     2823 | 2024-04-15 | Sangal           | L   | 0.464      | -            | -                | -                | -         |    -2.23 | bl1x1, bluewh1te, easy, sh1geo, VILBy  |
|            1 |     3132 | 2024-04-04 | ENCE             | L   | 0.390      | -            | -                | -                | -         |    -0.34 | bl1x1, bluewh1te, easy, sh1geo, VILBy  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,048.44)
- Divide that value by the 5th highest value among all rosters ($325,463.29)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
