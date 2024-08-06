### Roster Details<br />
Team Name: Aurora Young Blud<br />
Roster: bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy<br />
Global Rank: [63](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [46]( ../standings_europe.md)<br />
<br />
Final Rank Value:  996.3<br />
<br />
Final Rank Value (996.3) = Starting Rank Value (867.9) + Head To Head Adjustments (128.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.286[<sup>1</sup>](#table2)
- Bounty Collected: 0.366[<sup>2</sup>](#table1)
- Opponent Network: 0.258[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.227<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 867.9
- 400 + ( ( 0.227 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 867.9


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
|           33 |        2 | 2024-08-06 | PARIVISION       | L   | 1.000      | -            | -                | -                | -         |   -11.27 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy |
|           32 |       13 | 2024-08-05 | Zero Tenacity    | W   | 1.000      | 0.435        | 0.143 (0.062)    | 1.000 (0.435)    | 0 (0.000) |    22.58 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy |
|           31 |       29 | 2024-08-05 | The Suspect      | W   | 1.000      | 0.435        | -                | 0.223 (0.097)    | 0 (0.000) |    11.18 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy |
|           30 |       53 | 2024-08-04 | AMKAL            | W   | 1.000      | 0.435        | 0.130 (0.056)    | 0.453 (0.197)    | 0 (0.000) |    23.63 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy |
|           29 |      193 | 2024-07-31 | Sampi            | W   | 1.000      | 0.435        | 0.027 (0.012)    | 1.000 (0.435)    | 0 (0.000) |    14.17 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy |
|           28 |      279 | 2024-07-29 | EYEBALLERS       | W   | 1.000      | 0.435        | -                | 0.488 (0.212)    | 0 (0.000) |    10.61 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy |
|           27 |      343 | 2024-07-27 | 9INE             | L   | 1.000      | -            | -                | -                | -         |   -13.55 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy |
|           26 |      409 | 2024-07-25 | MOUZ NXT         | L   | 1.000      | -            | -                | -                | -         |    -8.74 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy |
|           25 |      425 | 2024-07-24 | Astralis Talent  | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.34 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy |
|           24 |      548 | 2024-07-20 | BC.Game          | W   | 1.000      | 0.435        | 0.022 (0.009)    | 0.307 (0.133)    | 0 (0.000) |    14.68 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy |
|           23 |      644 | 2024-07-18 | Sampi            | W   | 1.000      | 0.435        | 0.027 (0.012)    | 1.000 (0.435)    | 0 (0.000) |    15.41 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy |
|           22 |      725 | 2024-07-17 | Passion UA       | L   | 1.000      | -            | -                | -                | -         |   -10.54 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy |
|           21 |      809 | 2024-07-15 | VP.Prodigy       | W   | 1.000      | 0.435        | 0.025 (0.011)    | 0.383 (0.166)    | 0 (0.000) |    14.57 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy |
|           20 |      823 | 2024-07-15 | BLEED            | L   | 1.000      | -            | -                | -                | -         |    -2.70 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy |
|           19 |     1045 | 2024-06-16 | Preasy           | W   | 0.859      | -            | -                | -                | 0 (0.000) |     9.48 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy |
|           18 |     1096 | 2024-06-14 | Verdant          | W   | 0.849      | -            | -                | -                | -         |    13.58 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy |
|           17 |     1134 | 2024-06-13 | Astralis Talent  | W   | 0.842      | -            | -                | -                | -         |     8.07 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy |
|           16 |     1151 | 2024-06-13 | BLEED            | L   | 0.840      | -            | -                | -                | -         |    -1.71 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy |
|           15 |     1261 | 2024-06-09 | Sampi            | W   | 0.814      | 0.435        | 0.027 (0.010)    | 1.000 (0.354)    | -         |    13.80 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy |
|           14 |     1375 | 2024-06-07 | Insilio          | L   | 0.802      | -            | -                | -                | -         |   -10.08 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy |
|           13 |     1403 | 2024-06-07 | Passion UA       | L   | 0.799      | -            | -                | -                | -         |    -6.45 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy |
|           12 |     1436 | 2024-06-06 | Verdant          | W   | 0.795      | 0.372        | 0.015 (0.004)    | -                | -         |    13.49 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy |
|           11 |     1509 | 2024-06-05 | Zero Tenacity    | L   | 0.788      | -            | -                | -                | -         |    -4.55 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy |
|           10 |     1523 | 2024-06-05 | Illuminar        | W   | 0.787      | 0.435        | 0.012 (0.004)    | 0.340 (0.116)    | -         |    10.80 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy |
|            9 |     1557 | 2024-06-04 | Spirit Academy   | W   | 0.781      | 0.372        | 0.013 (0.004)    | -                | -         |     8.28 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy |
|            8 |     1569 | 2024-06-04 | MOUZ NXT         | L   | 0.779      | -            | -                | -                | -         |    -4.91 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy |
|            7 |     1580 | 2024-06-03 | FLuffy Gangsters | W   | 0.775      | -            | -                | -                | -         |     4.27 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy |
|            6 |     1609 | 2024-06-02 | ThunderFlash     | W   | 0.767      | -            | -                | -                | -         |     1.75 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy |
|            5 |     1638 | 2024-06-01 | LEON             | W   | 0.761      | -            | -                | -                | -         |     7.20 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy |
|            4 |     1719 | 2024-05-29 | FAVBET           | L   | 0.741      | -            | -                | -                | -         |   -13.76 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy |
|            3 |     2880 | 2024-04-16 | ALTERNATE aTTaX  | L   | 0.453      | -            | -                | -                | -         |    -5.05 | bl1x1, bluewh1te, easy, sh1geo, VILBy  |
|            2 |     2896 | 2024-04-15 | Sangal           | L   | 0.448      | -            | -                | -                | -         |    -2.67 | bl1x1, bluewh1te, easy, sh1geo, VILBy  |
|            1 |     3205 | 2024-04-04 | ENCE             | L   | 0.374      | -            | -                | -                | -         |    -0.41 | bl1x1, bluewh1te, easy, sh1geo, VILBy  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,027.60)
- Divide that value by the 5th highest value among all rosters ($320,521.62)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
