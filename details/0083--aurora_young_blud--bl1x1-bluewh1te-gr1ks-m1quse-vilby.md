### Roster Details<br />
Team Name: Aurora Young Blud<br />
Roster: bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy<br />
Global Rank: [83](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [62]( ../standings_europe.md)<br />
<br />
Final Rank Value:  918.9<br />
<br />
Final Rank Value (918.9) = Starting Rank Value (813.8) + Head To Head Adjustments (105.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.286[<sup>1</sup>](#table2)
- Bounty Collected: 0.314[<sup>2</sup>](#table1)
- Opponent Network: 0.209[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.202<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 813.8
- 400 + ( ( 0.202 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 813.8


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
|           29 |      125 | 2024-07-31 | Sampi            | W   | 1.000      | 0.435        | 0.027 (0.012)    | 1.000 (0.435)    | 0 (0.000) |    15.19 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy |
|           28 |      210 | 2024-07-29 | EYEBALLERS       | W   | 1.000      | 0.435        | 0.006 (0.002)    | 0.510 (0.221)    | 0 (0.000) |    11.76 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy |
|           27 |      275 | 2024-07-27 | 9INE             | L   | 1.000      | -            | -                | -                | -         |   -12.28 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy |
|           26 |      342 | 2024-07-25 | MOUZ NXT         | L   | 1.000      | -            | -                | -                | -         |    -7.74 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy |
|           25 |      357 | 2024-07-24 | Astralis Talent  | W   | 1.000      | 0.435        | 0.009 (0.004)    | 0.162 (0.071)    | 0 (0.000) |     8.47 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy |
|           24 |      480 | 2024-07-20 | BC.Game          | W   | 1.000      | 0.435        | -                | 0.275 (0.120)    | 0 (0.000) |     8.48 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy |
|           23 |      576 | 2024-07-18 | Sampi            | W   | 1.000      | 0.435        | 0.027 (0.012)    | 1.000 (0.435)    | 0 (0.000) |    16.46 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy |
|           22 |      658 | 2024-07-17 | Passion UA       | L   | 1.000      | -            | -                | -                | -         |    -9.60 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy |
|           21 |      744 | 2024-07-15 | VP.Prodigy       | W   | 1.000      | 0.435        | 0.026 (0.011)    | 0.401 (0.174)    | 0 (0.000) |    15.83 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy |
|           20 |      756 | 2024-07-15 | BLEED            | L   | 1.000      | -            | -                | -                | -         |    -2.35 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy |
|           19 |      977 | 2024-06-16 | Preasy           | W   | 0.873      | -            | -                | -                | 0 (0.000) |    10.86 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy |
|           18 |     1028 | 2024-06-14 | Verdant          | W   | 0.862      | 0.143        | 0.015 (0.002)    | -                | 0 (0.000) |    14.97 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy |
|           17 |     1066 | 2024-06-13 | Astralis Talent  | W   | 0.856      | -            | -                | -                | 0 (0.000) |     9.44 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy |
|           16 |     1083 | 2024-06-13 | BLEED            | L   | 0.854      | -            | -                | -                | -         |    -1.46 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy |
|           15 |     1193 | 2024-06-09 | Sampi            | W   | 0.828      | 0.435        | 0.027 (0.010)    | 1.000 (0.360)    | 0 (0.000) |    15.18 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy |
|           14 |     1307 | 2024-06-07 | Insilio          | L   | 0.815      | -            | -                | -                | -         |    -9.03 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy |
|           13 |     1335 | 2024-06-07 | Passion UA       | L   | 0.813      | -            | -                | -                | -         |    -5.71 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy |
|           12 |     1368 | 2024-06-06 | Verdant          | W   | 0.809      | 0.372        | 0.015 (0.004)    | 0.299 (0.090)    | -         |    15.08 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy |
|           11 |     1441 | 2024-06-05 | Zero Tenacity    | L   | 0.801      | -            | -                | -                | -         |    -3.83 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy |
|           10 |     1455 | 2024-06-05 | Illuminar        | W   | 0.800      | 0.435        | 0.012 (0.004)    | 0.352 (0.122)    | -         |    12.40 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy |
|            9 |     1489 | 2024-06-04 | Spirit Academy   | W   | 0.794      | 0.372        | 0.013 (0.004)    | -                | -         |     9.89 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy |
|            8 |     1501 | 2024-06-04 | MOUZ NXT         | L   | 0.793      | -            | -                | -                | -         |    -4.11 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy |
|            7 |     1512 | 2024-06-03 | FLuffy Gangsters | W   | 0.789      | 0.372        | -                | 0.222 (0.065)    | -         |     5.35 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy |
|            6 |     1541 | 2024-06-02 | ThunderFlash     | W   | 0.781      | -            | -                | -                | -         |     2.30 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy |
|            5 |     1570 | 2024-06-01 | LEON             | W   | 0.774      | -            | -                | -                | -         |     8.81 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy |
|            4 |     1651 | 2024-05-29 | FAVBET           | L   | 0.755      | -            | -                | -                | -         |   -12.39 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy |
|            3 |     2812 | 2024-04-16 | ALTERNATE aTTaX  | L   | 0.467      | -            | -                | -                | -         |    -4.28 | bl1x1, bluewh1te, easy, sh1geo, VILBy  |
|            2 |     2828 | 2024-04-15 | Sangal           | L   | 0.461      | -            | -                | -                | -         |    -2.21 | bl1x1, bluewh1te, easy, sh1geo, VILBy  |
|            1 |     3137 | 2024-04-04 | ENCE             | L   | 0.387      | -            | -                | -                | -         |    -0.34 | bl1x1, bluewh1te, easy, sh1geo, VILBy  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,044.62)
- Divide that value by the 5th highest value among all rosters ($324,557.31)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
