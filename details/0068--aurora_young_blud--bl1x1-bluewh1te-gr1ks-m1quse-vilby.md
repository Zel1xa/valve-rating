### Roster Details<br />
Team Name: Aurora Young Blud<br />
Roster: bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy<br />
Global Rank: [68](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [47]( ../standings_europe.md)<br />
<br />
Final Rank Value:  959.5<br />
<br />
Final Rank Value (959.5) = Starting Rank Value (837.9) + Head To Head Adjustments (121.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.286[<sup>1</sup>](#table2)
- Bounty Collected: 0.345[<sup>2</sup>](#table1)
- Opponent Network: 0.225[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.214<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 837.9
- 400 + ( ( 0.214 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 837.9


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
|           30 |       21 | 2024-08-04 | AMKAL            | W   | 1.000      | 0.435        | 0.130 (0.056)    | 0.474 (0.206)    | 0 (0.000) |    24.07 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy |
|           29 |      161 | 2024-07-31 | Sampi            | W   | 1.000      | 0.435        | 0.027 (0.012)    | 1.000 (0.435)    | 0 (0.000) |    14.46 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy |
|           28 |      247 | 2024-07-29 | EYEBALLERS       | W   | 1.000      | 0.435        | -                | 0.509 (0.221)    | 0 (0.000) |    11.02 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy |
|           27 |      311 | 2024-07-27 | 9INE             | L   | 1.000      | -            | -                | -                | -         |   -12.99 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy |
|           26 |      377 | 2024-07-25 | MOUZ NXT         | L   | 1.000      | -            | -                | -                | -         |    -8.31 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy |
|           25 |      393 | 2024-07-24 | Astralis Talent  | W   | 1.000      | 0.435        | 0.009 (0.004)    | 0.163 (0.071)    | 0 (0.000) |     7.85 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy |
|           24 |      516 | 2024-07-20 | BC.Game          | W   | 1.000      | 0.435        | 0.022 (0.009)    | 0.316 (0.137)    | 0 (0.000) |    14.78 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy |
|           23 |      612 | 2024-07-18 | Sampi            | W   | 1.000      | 0.435        | 0.027 (0.012)    | 1.000 (0.435)    | 0 (0.000) |    15.98 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy |
|           22 |      693 | 2024-07-17 | Passion UA       | L   | 1.000      | -            | -                | -                | -         |    -9.99 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy |
|           21 |      777 | 2024-07-15 | VP.Prodigy       | W   | 1.000      | 0.435        | 0.025 (0.011)    | 0.400 (0.174)    | 0 (0.000) |    15.26 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy |
|           20 |      791 | 2024-07-15 | BLEED            | L   | 1.000      | -            | -                | -                | -         |    -2.51 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy |
|           19 |     1013 | 2024-06-16 | Preasy           | W   | 0.869      | -            | -                | -                | 0 (0.000) |    10.28 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy |
|           18 |     1064 | 2024-06-14 | Verdant          | W   | 0.858      | -            | -                | -                | 0 (0.000) |    14.36 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy |
|           17 |     1102 | 2024-06-13 | Astralis Talent  | W   | 0.851      | -            | -                | -                | 0 (0.000) |     8.85 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy |
|           16 |     1119 | 2024-06-13 | BLEED            | L   | 0.849      | -            | -                | -                | -         |    -1.57 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy |
|           15 |     1229 | 2024-06-09 | Sampi            | W   | 0.824      | 0.435        | 0.027 (0.010)    | 1.000 (0.358)    | -         |    14.58 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy |
|           14 |     1343 | 2024-06-07 | Insilio          | L   | 0.811      | -            | -                | -                | -         |    -9.53 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy |
|           13 |     1371 | 2024-06-07 | Passion UA       | L   | 0.809      | -            | -                | -                | -         |    -6.04 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy |
|           12 |     1404 | 2024-06-06 | Verdant          | W   | 0.805      | 0.372        | 0.015 (0.004)    | 0.299 (0.090)    | -         |    14.38 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy |
|           11 |     1477 | 2024-06-05 | Zero Tenacity    | L   | 0.797      | -            | -                | -                | -         |    -4.18 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy |
|           10 |     1491 | 2024-06-05 | Illuminar        | W   | 0.796      | 0.435        | 0.012 (0.004)    | 0.352 (0.122)    | -         |    11.68 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy |
|            9 |     1525 | 2024-06-04 | Spirit Academy   | W   | 0.790      | 0.372        | 0.013 (0.004)    | -                | -         |     9.17 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy |
|            8 |     1537 | 2024-06-04 | MOUZ NXT         | L   | 0.789      | -            | -                | -                | -         |    -4.48 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy |
|            7 |     1548 | 2024-06-03 | FLuffy Gangsters | W   | 0.784      | -            | -                | -                | -         |     4.85 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy |
|            6 |     1577 | 2024-06-02 | ThunderFlash     | W   | 0.776      | -            | -                | -                | -         |     2.04 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy |
|            5 |     1606 | 2024-06-01 | LEON             | W   | 0.770      | -            | -                | -                | -         |     8.08 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy |
|            4 |     1687 | 2024-05-29 | FAVBET           | L   | 0.751      | -            | -                | -                | -         |   -13.06 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy |
|            3 |     2848 | 2024-04-16 | ALTERNATE aTTaX  | L   | 0.463      | -            | -                | -                | -         |    -4.65 | bl1x1, bluewh1te, easy, sh1geo, VILBy  |
|            2 |     2864 | 2024-04-15 | Sangal           | L   | 0.457      | -            | -                | -                | -         |    -2.40 | bl1x1, bluewh1te, easy, sh1geo, VILBy  |
|            1 |     3173 | 2024-04-04 | ENCE             | L   | 0.383      | -            | -                | -                | -         |    -0.37 | bl1x1, bluewh1te, easy, sh1geo, VILBy  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,039.41)
- Divide that value by the 5th highest value among all rosters ($323,321.90)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
