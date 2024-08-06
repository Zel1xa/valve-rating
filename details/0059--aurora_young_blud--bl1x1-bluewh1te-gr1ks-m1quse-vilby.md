### Roster Details<br />
Team Name: Aurora Young Blud<br />
Roster: bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy<br />
Global Rank: [59](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [42]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1012.9<br />
<br />
Final Rank Value (1012.9) = Starting Rank Value (909.4) + Head To Head Adjustments (103.4)<br />

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
|           33 |        9 | 2024-08-06 | PARIVISION       | L   | 1.000      | -            | -                | -                | -         |   -11.90 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy |
|           32 |       22 | 2024-08-05 | Zero Tenacity    | W   | 1.000      | 0.435        | 0.143 (0.062)    | 1.000 (0.435)    | 0 (0.000) |    22.01 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy |
|           31 |       39 | 2024-08-05 | The Suspect      | W   | 1.000      | 0.435        | -                | 0.223 (0.097)    | 0 (0.000) |    10.48 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy |
|           30 |       62 | 2024-08-04 | AMKAL            | W   | 1.000      | 0.435        | 0.130 (0.056)    | 0.452 (0.197)    | 0 (0.000) |    23.03 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy |
|           29 |      202 | 2024-07-31 | Sampi            | W   | 1.000      | 0.435        | 0.027 (0.012)    | 1.000 (0.435)    | 0 (0.000) |    13.51 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy |
|           28 |      288 | 2024-07-29 | EYEBALLERS       | W   | 1.000      | 0.435        | -                | 0.488 (0.212)    | 0 (0.000) |     9.89 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy |
|           27 |      352 | 2024-07-27 | 9INE             | L   | 1.000      | -            | -                | -                | -         |   -14.34 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy |
|           26 |      418 | 2024-07-25 | MOUZ NXT         | L   | 1.000      | -            | -                | -                | -         |    -9.40 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy |
|           25 |      434 | 2024-07-24 | Astralis Talent  | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.70 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy |
|           24 |      557 | 2024-07-20 | BC.Game          | W   | 1.000      | 0.435        | 0.022 (0.010)    | 0.307 (0.134)    | 0 (0.000) |    13.78 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy |
|           23 |      653 | 2024-07-18 | Sampi            | W   | 1.000      | 0.435        | 0.027 (0.012)    | 1.000 (0.435)    | 0 (0.000) |    14.56 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy |
|           22 |      734 | 2024-07-17 | Passion UA       | L   | 1.000      | -            | -                | -                | -         |   -11.42 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy |
|           21 |      818 | 2024-07-15 | VP.Prodigy       | W   | 1.000      | 0.435        | 0.025 (0.011)    | 0.383 (0.166)    | 0 (0.000) |    13.53 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy |
|           20 |      832 | 2024-07-15 | BLEED            | L   | 1.000      | -            | -                | -                | -         |    -3.06 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy |
|           19 |     1054 | 2024-06-16 | Preasy           | W   | 0.858      | -            | -                | -                | 0 (0.000) |     8.58 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy |
|           18 |     1105 | 2024-06-14 | Verdant          | W   | 0.848      | -            | -                | -                | -         |    12.59 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy |
|           17 |     1143 | 2024-06-13 | Astralis Talent  | W   | 0.841      | -            | -                | -                | -         |     7.20 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy |
|           16 |     1160 | 2024-06-13 | BLEED            | L   | 0.839      | -            | -                | -                | -         |    -1.97 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy |
|           15 |     1270 | 2024-06-09 | Sampi            | W   | 0.813      | 0.435        | 0.027 (0.010)    | 1.000 (0.353)    | -         |    12.86 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy |
|           14 |     1384 | 2024-06-07 | Insilio          | L   | 0.801      | -            | -                | -                | -         |   -11.05 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy |
|           13 |     1412 | 2024-06-07 | Passion UA       | L   | 0.798      | -            | -                | -                | -         |    -7.28 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy |
|           12 |     1445 | 2024-06-06 | Verdant          | W   | 0.794      | 0.372        | 0.015 (0.004)    | -                | -         |    12.35 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy |
|           11 |     1518 | 2024-06-05 | Zero Tenacity    | L   | 0.787      | -            | -                | -                | -         |    -5.27 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy |
|           10 |     1532 | 2024-06-05 | Illuminar        | W   | 0.786      | 0.435        | 0.012 (0.004)    | 0.340 (0.116)    | -         |     9.74 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy |
|            9 |     1566 | 2024-06-04 | Spirit Academy   | W   | 0.780      | 0.372        | 0.013 (0.004)    | -                | -         |     7.22 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy |
|            8 |     1578 | 2024-06-04 | MOUZ NXT         | L   | 0.778      | -            | -                | -                | -         |    -5.73 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy |
|            7 |     1589 | 2024-06-03 | FLuffy Gangsters | W   | 0.774      | -            | -                | -                | -         |     3.58 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy |
|            6 |     1618 | 2024-06-02 | ThunderFlash     | W   | 0.766      | -            | -                | -                | -         |     1.44 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy |
|            5 |     1647 | 2024-06-01 | LEON             | W   | 0.760      | -            | -                | -                | -         |     6.16 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy |
|            4 |     1728 | 2024-05-29 | FAVBET           | L   | 0.740      | -            | -                | -                | -         |   -14.92 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy |
|            3 |     2889 | 2024-04-16 | ALTERNATE aTTaX  | L   | 0.452      | -            | -                | -                | -         |    -5.79 | bl1x1, bluewh1te, easy, sh1geo, VILBy  |
|            2 |     2905 | 2024-04-15 | Sangal           | L   | 0.446      | -            | -                | -                | -         |    -3.12 | bl1x1, bluewh1te, easy, sh1geo, VILBy  |
|            1 |     3214 | 2024-04-04 | ENCE             | L   | 0.373      | -            | -                | -                | -         |    -0.51 | bl1x1, bluewh1te, easy, sh1geo, VILBy  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($6,026.22)
- Divide that value by the 5th highest value among all rosters ($320,192.18)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-06 |      1.000 | $5,000.00      | $5,000.00       |
| 2024-06-10 |      0.821 | $1,250.00      | $1,026.22       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
