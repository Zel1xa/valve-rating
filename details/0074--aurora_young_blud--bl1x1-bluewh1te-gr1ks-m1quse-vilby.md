### Roster Details<br />
Team Name: Aurora Young Blud<br />
Roster: bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy<br />
Global Rank: [74](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [53]( ../standings_europe.md)<br />
<br />
Final Rank Value:  946.9<br />
<br />
Final Rank Value (946.9) = Starting Rank Value (845.9) + Head To Head Adjustments (101.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.287[<sup>1</sup>](#table2)
- Bounty Collected: 0.341[<sup>2</sup>](#table1)
- Opponent Network: 0.240[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.217<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 845.9
- 400 + ( ( 0.217 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 845.9


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
|           30 |       43 | 2024-07-31 | Sampi            | W   | 1.000      | 0.435        | 0.028 (0.012)    | 1.000 (0.435)    | 0 (0.000) |    14.06 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy |
|           29 |      129 | 2024-07-29 | EYEBALLERS       | W   | 1.000      | 0.435        | 0.006 (0.002)    | 0.512 (0.223)    | 0 (0.000) |    10.48 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy |
|           28 |      193 | 2024-07-27 | 9INE             | L   | 1.000      | -            | -                | -                | -         |   -12.58 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy |
|           27 |      259 | 2024-07-25 | MOUZ NXT         | L   | 1.000      | -            | -                | -                | -         |    -8.63 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy |
|           26 |      275 | 2024-07-24 | Astralis Talent  | W   | 1.000      | 0.435        | 0.009 (0.004)    | 0.201 (0.087)    | 0 (0.000) |     7.66 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy |
|           25 |      401 | 2024-07-20 | BC.Game          | W   | 1.000      | 0.435        | -                | 0.193 (0.084)    | 0 (0.000) |     6.97 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy |
|           24 |      503 | 2024-07-18 | Sampi            | W   | 1.000      | 0.435        | 0.028 (0.012)    | 1.000 (0.435)    | 0 (0.000) |    14.91 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy |
|           23 |      585 | 2024-07-17 | Passion UA       | L   | 1.000      | -            | -                | -                | -         |   -11.27 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy |
|           22 |      674 | 2024-07-15 | VP.Prodigy       | W   | 1.000      | 0.435        | 0.026 (0.011)    | 0.405 (0.176)    | 0 (0.000) |    14.43 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy |
|           21 |      690 | 2024-07-15 | BLEED            | L   | 1.000      | -            | -                | -                | -         |    -2.76 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy |
|           20 |      910 | 2024-06-16 | Preasy           | W   | 0.891      | -            | -                | -                | 0 (0.000) |     9.76 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy |
|           19 |      953 | 2024-06-14 | Verdant          | W   | 0.880      | -            | -                | -                | 0 (0.000) |    13.94 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy |
|           18 |      990 | 2024-06-13 | Astralis Talent  | W   | 0.873      | -            | -                | -                | 0 (0.000) |     7.89 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy |
|           17 |     1007 | 2024-06-13 | BLEED            | L   | 0.871      | -            | -                | -                | -         |    -1.78 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy |
|           16 |     1119 | 2024-06-09 | Sampi            | W   | 0.846      | 0.435        | 0.028 (0.010)    | 1.000 (0.368)    | 0 (0.000) |    13.76 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy |
|           15 |     1226 | 2024-06-07 | Zero Tenacity    | W   | 0.834      | 0.435        | 0.139 (0.050)    | 1.000 (0.363)    | -         |    20.27 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy |
|           14 |     1242 | 2024-06-07 | Insilio          | L   | 0.833      | -            | -                | -                | -         |    -9.86 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy |
|           13 |     1270 | 2024-06-07 | Passion UA       | L   | 0.831      | -            | -                | -                | -         |    -6.75 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy |
|           12 |     1305 | 2024-06-06 | Verdant          | W   | 0.827      | 0.372        | 0.015 (0.005)    | 0.305 (0.094)    | -         |    14.72 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy |
|           11 |     1381 | 2024-06-05 | Zero Tenacity    | L   | 0.819      | -            | -                | -                | -         |    -4.65 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy |
|           10 |     1395 | 2024-06-05 | Illuminar        | W   | 0.818      | 0.435        | 0.012 (0.004)    | 0.376 (0.134)    | -         |    12.48 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy |
|            9 |     1429 | 2024-06-04 | Spirit Academy   | W   | 0.812      | 0.372        | 0.014 (0.004)    | -                | -         |     9.29 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy |
|            8 |     1441 | 2024-06-04 | MOUZ NXT         | L   | 0.811      | -            | -                | -                | -         |    -4.76 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy |
|            7 |     1452 | 2024-06-03 | FLuffy Gangsters | W   | 0.806      | -            | -                | -                | -         |     4.85 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy |
|            6 |     1482 | 2024-06-02 | ThunderFlash     | W   | 0.798      | -            | -                | -                | -         |     2.03 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy |
|            5 |     1511 | 2024-06-01 | LEON             | W   | 0.792      | -            | -                | -                | -         |     8.19 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy |
|            4 |     1592 | 2024-05-29 | FAVBET           | L   | 0.773      | -            | -                | -                | -         |   -13.46 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy |
|            3 |     2805 | 2024-04-16 | ALTERNATE aTTaX  | L   | 0.485      | -            | -                | -                | -         |    -5.00 | bl1x1, bluewh1te, easy, sh1geo, VILBy  |
|            2 |     2821 | 2024-04-15 | Sangal           | L   | 0.479      | -            | -                | -                | -         |    -2.77 | bl1x1, bluewh1te, easy, sh1geo, VILBy  |
|            1 |     3132 | 2024-04-04 | ENCE             | L   | 0.405      | -            | -                | -                | -         |    -0.40 | bl1x1, bluewh1te, easy, sh1geo, VILBy  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,066.84)
- Divide that value by the 5th highest value among all rosters ($326,952.13)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
