### Roster Details<br />
Team Name: Aurora Young Blud<br />
Roster: bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy<br />
Global Rank: [80](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [58]( ../standings_europe.md)<br />
<br />
Final Rank Value:  927.7<br />
<br />
Final Rank Value (927.7) = Starting Rank Value (815.8) + Head To Head Adjustments (111.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.286[<sup>1</sup>](#table2)
- Bounty Collected: 0.314[<sup>2</sup>](#table1)
- Opponent Network: 0.213[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.203<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 815.8
- 400 + ( ( 0.203 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 815.8


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
|           28 |      100 | 2024-07-31 | Sampi            | W   | 1.000      | 0.435        | 0.028 (0.012)    | 1.000 (0.435)    | 0 (0.000) |    14.80 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy |
|           27 |      184 | 2024-07-29 | EYEBALLERS       | W   | 1.000      | 0.435        | 0.006 (0.002)    | 0.528 (0.229)    | 0 (0.000) |    11.20 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy |
|           26 |      249 | 2024-07-27 | 9INE             | L   | 1.000      | -            | -                | -                | -         |   -12.65 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy |
|           25 |      315 | 2024-07-25 | MOUZ NXT         | L   | 1.000      | -            | -                | -                | -         |    -8.38 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy |
|           24 |      331 | 2024-07-24 | Astralis Talent  | W   | 1.000      | 0.435        | 0.007 (0.003)    | 0.168 (0.073)    | 0 (0.000) |     8.28 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy |
|           23 |      454 | 2024-07-20 | BC.Game          | W   | 1.000      | 0.435        | -                | 0.283 (0.123)    | 0 (0.000) |     8.20 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy |
|           22 |      550 | 2024-07-18 | Sampi            | W   | 1.000      | 0.435        | 0.028 (0.012)    | 1.000 (0.435)    | 0 (0.000) |    15.98 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy |
|           21 |      712 | 2024-07-15 | VP.Prodigy       | W   | 1.000      | 0.435        | 0.026 (0.011)    | 0.416 (0.181)    | 0 (0.000) |    15.80 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy |
|           20 |      727 | 2024-07-15 | BLEED            | L   | 1.000      | -            | -                | -                | -         |    -2.35 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy |
|           19 |      936 | 2024-06-16 | Preasy           | W   | 0.878      | -            | -                | -                | 0 (0.000) |    10.90 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy |
|           18 |      976 | 2024-06-14 | Verdant          | W   | 0.867      | 0.143        | 0.015 (0.002)    | -                | 0 (0.000) |    15.00 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy |
|           17 |     1012 | 2024-06-13 | Astralis Talent  | W   | 0.860      | -            | -                | -                | 0 (0.000) |     9.63 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy |
|           16 |     1029 | 2024-06-13 | BLEED            | L   | 0.858      | -            | -                | -                | -         |    -1.46 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy |
|           15 |     1134 | 2024-06-09 | Sampi            | W   | 0.833      | 0.435        | 0.028 (0.010)    | 1.000 (0.362)    | 0 (0.000) |    15.51 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy |
|           14 |     1244 | 2024-06-07 | Insilio          | L   | 0.820      | -            | -                | -                | -         |    -9.04 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy |
|           13 |     1271 | 2024-06-07 | Passion UA       | L   | 0.818      | -            | -                | -                | -         |    -5.84 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy |
|           12 |     1305 | 2024-06-06 | Verdant          | W   | 0.814      | 0.372        | 0.015 (0.004)    | 0.310 (0.094)    | -         |    15.13 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy |
|           11 |     1377 | 2024-06-05 | Zero Tenacity    | L   | 0.806      | -            | -                | -                | -         |    -4.04 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy |
|           10 |     1391 | 2024-06-05 | Illuminar        | W   | 0.805      | 0.435        | 0.012 (0.004)    | 0.363 (0.127)    | -         |    12.47 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy |
|            9 |     1424 | 2024-06-04 | Spirit Academy   | W   | 0.799      | 0.372        | 0.013 (0.004)    | -                | -         |     9.92 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy |
|            8 |     1436 | 2024-06-04 | MOUZ NXT         | L   | 0.798      | -            | -                | -                | -         |    -4.19 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy |
|            7 |     1448 | 2024-06-03 | FLuffy Gangsters | W   | 0.793      | 0.372        | -                | 0.229 (0.068)    | -         |     5.36 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy |
|            6 |     1475 | 2024-06-02 | ThunderFlash     | W   | 0.785      | -            | -                | -                | -         |     2.29 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy |
|            5 |     1503 | 2024-06-01 | LEON             | W   | 0.779      | -            | -                | -                | -         |     8.84 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy |
|            4 |     1585 | 2024-05-29 | FAVBET           | L   | 0.760      | -            | -                | -                | -         |   -12.46 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy |
|            3 |     2741 | 2024-04-16 | ALTERNATE aTTaX  | L   | 0.472      | -            | -                | -                | -         |    -4.33 | bl1x1, bluewh1te, easy, sh1geo, VILBy  |
|            2 |     2757 | 2024-04-15 | Sangal           | L   | 0.466      | -            | -                | -                | -         |    -2.28 | bl1x1, bluewh1te, easy, sh1geo, VILBy  |
|            1 |     3066 | 2024-04-04 | ENCE             | L   | 0.392      | -            | -                | -                | -         |    -0.35 | bl1x1, bluewh1te, easy, sh1geo, VILBy  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,050.58)
- Divide that value by the 5th highest value among all rosters ($325,971.18)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
