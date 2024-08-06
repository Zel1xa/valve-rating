### Roster Details<br />
Team Name: Aurora Young Blud<br />
Roster: bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy<br />
Global Rank: [58](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [42]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1012.3<br />
<br />
Final Rank Value (1012.3) = Starting Rank Value (909.4) + Head To Head Adjustments (103.0)<br />

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
|           33 |        4 | 2024-08-06 | PARIVISION       | L   | 1.000      | -            | -                | -                | -         |   -11.92 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy |
|           32 |       16 | 2024-08-05 | Zero Tenacity    | W   | 1.000      | 0.435        | 0.143 (0.062)    | 1.000 (0.435)    | 0 (0.000) |    22.00 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy |
|           31 |       32 | 2024-08-05 | The Suspect      | W   | 1.000      | 0.435        | -                | 0.223 (0.097)    | 0 (0.000) |    10.49 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy |
|           30 |       56 | 2024-08-04 | AMKAL            | W   | 1.000      | 0.435        | 0.130 (0.056)    | 0.453 (0.197)    | 0 (0.000) |    23.02 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy |
|           29 |      196 | 2024-07-31 | Sampi            | W   | 1.000      | 0.435        | 0.027 (0.012)    | 1.000 (0.435)    | 0 (0.000) |    13.49 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy |
|           28 |      282 | 2024-07-29 | EYEBALLERS       | W   | 1.000      | 0.435        | -                | 0.488 (0.212)    | 0 (0.000) |     9.88 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy |
|           27 |      346 | 2024-07-27 | 9INE             | L   | 1.000      | -            | -                | -                | -         |   -14.37 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy |
|           26 |      412 | 2024-07-25 | MOUZ NXT         | L   | 1.000      | -            | -                | -                | -         |    -9.41 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy |
|           25 |      428 | 2024-07-24 | Astralis Talent  | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.71 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy |
|           24 |      551 | 2024-07-20 | BC.Game          | W   | 1.000      | 0.435        | 0.022 (0.009)    | 0.307 (0.133)    | 0 (0.000) |    13.72 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy |
|           23 |      647 | 2024-07-18 | Sampi            | W   | 1.000      | 0.435        | 0.027 (0.012)    | 1.000 (0.435)    | 0 (0.000) |    14.53 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy |
|           22 |      728 | 2024-07-17 | Passion UA       | L   | 1.000      | -            | -                | -                | -         |   -11.46 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy |
|           21 |      812 | 2024-07-15 | VP.Prodigy       | W   | 1.000      | 0.435        | 0.025 (0.011)    | 0.383 (0.166)    | 0 (0.000) |    13.50 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy |
|           20 |      826 | 2024-07-15 | BLEED            | L   | 1.000      | -            | -                | -                | -         |    -3.08 | bl1x1, bluewh1te, gr1ks, m1QUSE, VILBy |
|           19 |     1048 | 2024-06-16 | Preasy           | W   | 0.859      | -            | -                | -                | 0 (0.000) |     8.59 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy |
|           18 |     1099 | 2024-06-14 | Verdant          | W   | 0.848      | -            | -                | -                | -         |    12.59 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy |
|           17 |     1137 | 2024-06-13 | Astralis Talent  | W   | 0.842      | -            | -                | -                | -         |     7.21 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy |
|           16 |     1154 | 2024-06-13 | BLEED            | L   | 0.840      | -            | -                | -                | -         |    -1.98 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy |
|           15 |     1264 | 2024-06-09 | Sampi            | W   | 0.814      | 0.435        | 0.027 (0.010)    | 1.000 (0.354)    | -         |    12.84 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy |
|           14 |     1378 | 2024-06-07 | Insilio          | L   | 0.801      | -            | -                | -                | -         |   -11.11 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy |
|           13 |     1406 | 2024-06-07 | Passion UA       | L   | 0.799      | -            | -                | -                | -         |    -7.32 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy |
|           12 |     1439 | 2024-06-06 | Verdant          | W   | 0.795      | 0.372        | 0.015 (0.004)    | -                | -         |    12.36 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy |
|           11 |     1512 | 2024-06-05 | Zero Tenacity    | L   | 0.787      | -            | -                | -                | -         |    -5.29 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy |
|           10 |     1526 | 2024-06-05 | Illuminar        | W   | 0.786      | 0.435        | 0.012 (0.004)    | 0.340 (0.116)    | -         |     9.74 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy |
|            9 |     1560 | 2024-06-04 | Spirit Academy   | W   | 0.780      | 0.372        | 0.013 (0.004)    | -                | -         |     7.23 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy |
|            8 |     1572 | 2024-06-04 | MOUZ NXT         | L   | 0.779      | -            | -                | -                | -         |    -5.75 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy |
|            7 |     1583 | 2024-06-03 | FLuffy Gangsters | W   | 0.775      | -            | -                | -                | -         |     3.58 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy |
|            6 |     1612 | 2024-06-02 | ThunderFlash     | W   | 0.767      | -            | -                | -                | -         |     1.44 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy |
|            5 |     1641 | 2024-06-01 | LEON             | W   | 0.760      | -            | -                | -                | -         |     6.17 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy |
|            4 |     1722 | 2024-05-29 | FAVBET           | L   | 0.741      | -            | -                | -                | -         |   -14.93 | bl1x1, bluewh1te, gr1ks, sh1geo, VILBy |
|            3 |     2883 | 2024-04-16 | ALTERNATE aTTaX  | L   | 0.453      | -            | -                | -                | -         |    -5.80 | bl1x1, bluewh1te, easy, sh1geo, VILBy  |
|            2 |     2899 | 2024-04-15 | Sangal           | L   | 0.447      | -            | -                | -                | -         |    -3.20 | bl1x1, bluewh1te, easy, sh1geo, VILBy  |
|            1 |     3208 | 2024-04-04 | ENCE             | L   | 0.373      | -            | -                | -                | -         |    -0.52 | bl1x1, bluewh1te, easy, sh1geo, VILBy  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($6,027.14)
- Divide that value by the 5th highest value among all rosters ($320,411.81)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-06 |      1.000 | $5,000.00      | $5,000.00       |
| 2024-06-10 |      0.822 | $1,250.00      | $1,027.14       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
