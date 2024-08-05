### Roster Details<br />
Team Name: Eternal Fire<br />
Roster: Calyx, MAJ3R, Wicadia, woxic, XANTARES<br />
Global Rank: [11](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [10]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1621.4<br />
<br />
Final Rank Value (1621.4) = Starting Rank Value (1696.3) + Head To Head Adjustments (-74.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.884[<sup>1</sup>](#table2)
- Bounty Collected: 0.561[<sup>2</sup>](#table1)
- Opponent Network: 0.312[<sup>2</sup>](#table1)
- LAN Wins: 0.772[<sup>2</sup>](#table1)

The average of these factors is 0.632<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1696.3
- 400 + ( ( 0.632 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 1696.3


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                 |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           37 |      315 | 2024-07-28 | The MongolZ       | L   | 1.000      | -            | -                | -                | -         |   -11.78 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           36 |      351 | 2024-07-26 | 3DMAX             | W   | 1.000      | 0.650        | 0.508 (0.331)    | 1.000 (0.650)    | 1 (1.000) |     5.90 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           35 |      396 | 2024-07-25 | AMKAL             | W   | 1.000      | 0.650        | -                | 0.465 (0.303)    | 1 (1.000) |     2.74 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           34 |      427 | 2024-07-24 | DMS               | W   | 1.000      | 0.650        | -                | 0.438 (0.285)    | 1 (1.000) |     0.55 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           33 |      436 | 2024-07-24 | Revenant          | W   | 1.000      | 0.650        | -                | 0.264 (0.172)    | 1 (1.000) |     0.47 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           32 |     1437 | 2024-06-06 | BetBoom           | L   | 0.799      | -            | -                | -                | -         |   -19.62 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           31 |     1458 | 2024-06-06 | BIG               | W   | 0.798      | 0.715        | 0.154 (0.088)    | -                | 1 (0.798) |     3.59 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           30 |     1467 | 2024-06-06 | FURIA             | L   | 0.797      | -            | -                | -                | -         |   -15.27 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           29 |     1490 | 2024-06-05 | fnatic            | L   | 0.793      | -            | -                | -                | -         |   -19.46 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           28 |     1517 | 2024-06-05 | Complexity        | L   | 0.790      | -            | -                | -                | -         |   -13.30 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           27 |     1823 | 2024-05-23 | Liquid            | W   | 0.705      | 0.769        | 0.383 (0.208)    | 0.450 (0.244)    | -         |     8.80 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           26 |     1864 | 2024-05-22 | GamerLegion       | W   | 0.699      | 0.769        | 0.173 (0.093)    | -                | -         |     1.28 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           25 |     1904 | 2024-05-21 | BetBoom           | W   | 0.693      | 0.769        | 0.249 (0.132)    | 0.529 (0.281)    | -         |     3.52 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           24 |     2061 | 2024-05-16 | SAW               | W   | 0.660      | 0.769        | -                | 0.530 (0.269)    | -         |     1.43 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           23 |     2070 | 2024-05-16 | PARIVISION        | W   | 0.658      | 0.769        | -                | 0.565 (0.286)    | -         |     0.73 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           22 |     2534 | 2024-04-27 | SAW               | L   | 0.533      | -            | -                | -                | -         |   -15.85 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           21 |     2563 | 2024-04-26 | FaZe              | L   | 0.526      | -            | -                | -                | -         |    -7.74 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           20 |     2590 | 2024-04-25 | fnatic            | W   | 0.520      | 0.889        | 0.371 (0.171)    | 0.697 (0.322)    | 1 (0.520) |     4.61 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           19 |     2610 | 2024-04-24 | Imperial          | W   | 0.513      | 0.889        | 0.234 (0.107)    | 0.674 (0.308)    | 1 (0.513) |     1.58 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           18 |     2631 | 2024-04-23 | Astralis          | L   | 0.506      | -            | -                | -                | -         |    -7.22 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           17 |     2692 | 2024-04-20 | Sashi             | L   | 0.486      | -            | -                | -                | -         |   -14.69 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           16 |     2738 | 2024-04-19 | Sashi             | W   | 0.480      | -            | -                | -                | -         |     0.58 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           15 |     2748 | 2024-04-19 | BetBoom           | W   | 0.479      | -            | -                | -                | -         |     2.37 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           14 |     3306 | 2024-03-29 | Natus Vincere     | L   | 0.339      | -            | -                | -                | -         |    -2.05 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           13 |     3414 | 2024-03-23 | Virtus.pro        | W   | 0.298      | 1.000        | 0.498 (0.148)    | -                | 1 (0.298) |     4.63 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           12 |     3429 | 2024-03-22 | FaZe              | W   | 0.292      | 1.000        | 0.630 (0.184)    | -                | 1 (0.292) |     4.32 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           11 |     3446 | 2024-03-21 | MOUZ              | L   | 0.286      | -            | -                | -                | -         |    -2.80 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           10 |     3454 | 2024-03-21 | Vitality          | W   | 0.285      | 1.000        | 0.648 (0.185)    | -                | 1 (0.285) |     6.29 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            9 |     3493 | 2024-03-19 | GamerLegion       | W   | 0.272      | -            | -                | -                | -         |     0.05 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            8 |     3501 | 2024-03-18 | HEROIC            | L   | 0.265      | -            | -                | -                | -         |    -5.76 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            7 |     3523 | 2024-03-17 | paiN              | W   | 0.260      | -            | -                | -                | -         |     1.29 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            6 |     3535 | 2024-03-17 | The MongolZ       | W   | 0.258      | -            | -                | -                | -         |     6.56 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            5 |     4209 | 2024-02-17 | BetBoom           | W   | 0.066      | -            | -                | -                | -         |     0.37 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            4 |     4243 | 2024-02-16 | FaZe              | L   | 0.059      | -            | -                | -                | -         |    -0.96 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            3 |     4273 | 2024-02-15 | Falcons           | W   | 0.051      | -            | -                | -                | -         |     0.28 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            2 |     4299 | 2024-02-14 | G2                | L   | 0.047      | -            | -                | -                | -         |    -0.23 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            1 |     4310 | 2024-02-14 | Ninjas in Pyjamas | W   | 0.045      | -            | -                | -                | -         |     0.00 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($238,191.94)
- Divide that value by the 5th highest value among all rosters ($321,880.58)
- The final value (0.74) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $35,000.00     | $35,000.00      |
| 2024-06-09 |      0.819 | $8,000.00      | $6,552.22       |
| 2024-05-23 |      0.705 | $250,000.00    | $176,319.44     |
| 2024-05-12 |      0.632 | $7,000.00      | $4,426.53       |
| 2024-03-31 |      0.353 | $45,000.00     | $15,893.75      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
