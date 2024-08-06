### Roster Details<br />
Team Name: Aurora Young Blud<br />
Roster: bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy<br />
Global Rank: [59](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [42]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1014.1<br />
<br />
Final Rank Value (1014.1) = Starting Rank Value (909.4) + Head To Head Adjustments (104.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.367[<sup>1</sup>](#table2)
- Bounty Collected: 0.366[<sup>2</sup>](#table1)
- Opponent Network: 0.258[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.248<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 909.4
- 400 + ( ( 0.248 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 909.4


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
|           33 |       14 | 2024-08-06 | PARIVISION       | L   | 1.000      | -            | -                | -                | -         |   -11.34 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy |
|           32 |       27 | 2024-08-05 | Zero Tenacity    | W   | 1.000      | 0.435        | 0.143 (0.062)    | 1.000 (0.435)    | 0 (0.000) |    22.05 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy |
|           31 |       44 | 2024-08-05 | The Suspect      | W   | 1.000      | 0.435        | -                | 0.223 (0.097)    | 0 (0.000) |    10.46 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy |
|           30 |       67 | 2024-08-04 | AMKAL            | W   | 1.000      | 0.435        | 0.130 (0.056)    | 0.452 (0.196)    | 0 (0.000) |    23.04 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy |
|           29 |      207 | 2024-07-31 | Sampi            | W   | 1.000      | 0.435        | 0.027 (0.012)    | 1.000 (0.435)    | 0 (0.000) |    13.51 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy |
|           28 |      293 | 2024-07-29 | EYEBALLERS       | W   | 1.000      | 0.435        | -                | 0.488 (0.212)    | 0 (0.000) |     9.90 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy |
|           27 |      357 | 2024-07-27 | 9INE             | L   | 1.000      | -            | -                | -                | -         |   -14.35 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy |
|           26 |      423 | 2024-07-25 | MOUZ NXT         | L   | 1.000      | -            | -                | -                | -         |    -9.35 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy |
|           25 |      439 | 2024-07-24 | Astralis Talent  | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.69 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy |
|           24 |      562 | 2024-07-20 | BC.Game          | W   | 1.000      | 0.435        | 0.022 (0.010)    | 0.308 (0.134)    | 0 (0.000) |    13.76 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy |
|           23 |      658 | 2024-07-18 | Sampi            | W   | 1.000      | 0.435        | 0.027 (0.012)    | 1.000 (0.435)    | 0 (0.000) |    14.56 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy |
|           22 |      739 | 2024-07-17 | Passion UA       | L   | 1.000      | -            | -                | -                | -         |   -11.39 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy |
|           21 |      823 | 2024-07-15 | VP.Prodigy       | W   | 1.000      | 0.435        | 0.025 (0.011)    | 0.383 (0.166)    | 0 (0.000) |    13.53 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy |
|           20 |      837 | 2024-07-15 | BLEED            | L   | 1.000      | -            | -                | -                | -         |    -3.05 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy |
|           19 |     1059 | 2024-06-16 | Preasy           | W   | 0.858      | -            | -                | -                | 0 (0.000) |     8.55 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy |
|           18 |     1110 | 2024-06-14 | Verdant          | W   | 0.847      | -            | -                | -                | -         |    12.67 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy |
|           17 |     1148 | 2024-06-13 | Astralis Talent  | W   | 0.840      | -            | -                | -                | -         |     7.18 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy |
|           16 |     1165 | 2024-06-13 | BLEED            | L   | 0.838      | -            | -                | -                | -         |    -1.96 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy |
|           15 |     1275 | 2024-06-09 | Sampi            | W   | 0.813      | 0.435        | 0.027 (0.010)    | 1.000 (0.353)    | -         |    12.87 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy |
|           14 |     1389 | 2024-06-07 | Insilio          | L   | 0.800      | -            | -                | -                | -         |   -11.05 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy |
|           13 |     1417 | 2024-06-07 | Passion UA       | L   | 0.798      | -            | -                | -                | -         |    -7.25 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy |
|           12 |     1450 | 2024-06-06 | Verdant          | W   | 0.794      | 0.372        | 0.015 (0.004)    | -                | -         |    12.46 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy |
|           11 |     1523 | 2024-06-05 | Zero Tenacity    | L   | 0.786      | -            | -                | -                | -         |    -5.22 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy |
|           10 |     1537 | 2024-06-05 | Illuminar        | W   | 0.785      | 0.435        | 0.012 (0.004)    | 0.340 (0.116)    | -         |     9.75 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy |
|            9 |     1571 | 2024-06-04 | Spirit Academy   | W   | 0.779      | 0.372        | 0.013 (0.004)    | -                | -         |     7.21 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy |
|            8 |     1583 | 2024-06-04 | MOUZ NXT         | L   | 0.778      | -            | -                | -                | -         |    -5.68 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy |
|            7 |     1594 | 2024-06-03 | FLuffy Gangsters | W   | 0.773      | -            | -                | -                | -         |     3.58 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy |
|            6 |     1623 | 2024-06-02 | ThunderFlash     | W   | 0.765      | -            | -                | -                | -         |     1.43 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy |
|            5 |     1652 | 2024-06-01 | LEON             | W   | 0.759      | -            | -                | -                | -         |     6.15 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy |
|            4 |     1733 | 2024-05-29 | FAVBET           | L   | 0.740      | -            | -                | -                | -         |   -14.92 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy |
|            3 |     2894 | 2024-04-16 | ALTERNATE aTTaX  | L   | 0.452      | -            | -                | -                | -         |    -5.74 | bl1x1, bluewh1te, easy, sh1geo, VILBy  |
|            2 |     2910 | 2024-04-15 | Sangal           | L   | 0.446      | -            | -                | -                | -         |    -2.83 | bl1x1, bluewh1te, easy, sh1geo, VILBy  |
|            1 |     3219 | 2024-04-04 | ENCE             | L   | 0.372      | -            | -                | -                | -         |    -0.51 | bl1x1, bluewh1te, easy, sh1geo, VILBy  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($6,025.69)
- Divide that value by the 5th highest value among all rosters ($320,068.63)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-06 |      1.000 | $5,000.00      | $5,000.00       |
| 2024-06-10 |      0.821 | $1,250.00      | $1,025.69       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
