### Roster Details<br />
Team Name: Eternal Fire<br />
Roster: Calyx, MAJ3R, Wicadia, woxic, XANTARES<br />
Global Rank: [10](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [9]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1624.2<br />
<br />
Final Rank Value (1624.2) = Starting Rank Value (1716.0) + Head To Head Adjustments (-91.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.892[<sup>1</sup>](#table2)
- Bounty Collected: 0.560[<sup>2</sup>](#table1)
- Opponent Network: 0.311[<sup>2</sup>](#table1)
- LAN Wins: 0.793[<sup>2</sup>](#table1)

The average of these factors is 0.639<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1716.0
- 400 + ( ( 0.639 - 0.000 ) / ( 0.777 - 0.000 ) ) * 1600 = 1716.0


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
|           40 |      169 | 2024-07-28 | The MongolZ       | L   | 1.000      | -            | -                | -                | -         |   -12.24 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           39 |      205 | 2024-07-26 | 3DMAX             | W   | 1.000      | 0.650        | 0.505 (0.328)    | 1.000 (0.650)    | 1 (1.000) |     5.53 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           38 |      250 | 2024-07-25 | AMKAL             | W   | 1.000      | 0.650        | 0.132 (0.086)    | 0.482 (0.314)    | 1 (1.000) |     2.70 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           37 |      281 | 2024-07-24 | DMS               | W   | 1.000      | 0.650        | -                | 0.447 (0.291)    | 1 (1.000) |     0.47 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           36 |      290 | 2024-07-24 | Revenant          | W   | 1.000      | -            | -                | -                | 1 (1.000) |     0.40 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           35 |     1310 | 2024-06-06 | BetBoom           | L   | 0.828      | -            | -                | -                | -         |   -20.37 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           34 |     1332 | 2024-06-06 | BIG               | W   | 0.826      | 0.715        | -                | 0.299 (0.177)    | 1 (0.826) |     2.81 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           33 |     1341 | 2024-06-06 | FURIA             | L   | 0.826      | -            | -                | -                | -         |   -16.05 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           32 |     1365 | 2024-06-05 | fnatic            | L   | 0.821      | -            | -                | -                | -         |   -22.98 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           31 |     1393 | 2024-06-05 | Complexity        | L   | 0.819      | -            | -                | -                | -         |   -14.53 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           30 |     1702 | 2024-05-23 | Liquid            | W   | 0.734      | 0.769        | 0.322 (0.181)    | 0.429 (0.242)    | -         |     5.70 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           29 |     1743 | 2024-05-22 | GamerLegion       | W   | 0.727      | 0.769        | 0.176 (0.099)    | -                | -         |     1.28 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           28 |     1798 | 2024-05-21 | BetBoom           | W   | 0.721      | 0.769        | 0.257 (0.143)    | 0.551 (0.306)    | -         |     3.58 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           27 |     1966 | 2024-05-16 | SAW               | W   | 0.688      | 0.769        | -                | 0.544 (0.288)    | -         |     1.52 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           26 |     1975 | 2024-05-16 | PARIVISION        | W   | 0.687      | 0.769        | -                | 0.451 (0.238)    | -         |     0.70 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           25 |     2453 | 2024-04-27 | SAW               | L   | 0.562      | -            | -                | -                | -         |   -16.68 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           24 |     2483 | 2024-04-26 | FaZe              | L   | 0.554      | -            | -                | -                | -         |    -7.80 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           23 |     2509 | 2024-04-25 | fnatic            | W   | 0.548      | 0.889        | 0.292 (0.142)    | 0.529 (0.258)    | 1 (0.548) |     2.04 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           22 |     2529 | 2024-04-24 | Imperial          | W   | 0.542      | 0.889        | 0.240 (0.115)    | 0.719 (0.346)    | 1 (0.542) |     1.57 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           21 |     2552 | 2024-04-23 | Astralis          | L   | 0.534      | -            | -                | -                | -         |    -8.93 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           20 |     2617 | 2024-04-20 | Sashi             | L   | 0.515      | -            | -                | -                | -         |   -15.60 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           19 |     2664 | 2024-04-19 | Sashi             | W   | 0.508      | -            | -                | -                | -         |     0.56 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           18 |     2674 | 2024-04-19 | BetBoom           | W   | 0.507      | -            | -                | -                | -         |     2.39 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           17 |     3244 | 2024-03-29 | Natus Vincere     | L   | 0.368      | -            | -                | -                | -         |    -2.31 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           16 |     3357 | 2024-03-23 | Virtus.pro        | W   | 0.327      | 1.000        | 0.483 (0.158)    | -                | 1 (0.327) |     4.98 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           15 |     3372 | 2024-03-22 | FaZe              | W   | 0.320      | 1.000        | 0.638 (0.204)    | -                | 1 (0.320) |     4.98 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           14 |     3389 | 2024-03-21 | MOUZ              | L   | 0.315      | -            | -                | -                | -         |    -3.00 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           13 |     3397 | 2024-03-21 | Vitality          | W   | 0.314      | 1.000        | 0.591 (0.185)    | -                | 1 (0.314) |     6.59 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           12 |     3436 | 2024-03-19 | GamerLegion       | W   | 0.300      | -            | -                | -                | -         |     0.06 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           11 |     3444 | 2024-03-18 | HEROIC            | L   | 0.294      | -            | -                | -                | -         |    -6.43 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           10 |     3466 | 2024-03-17 | paiN              | W   | 0.288      | -            | -                | -                | -         |     1.06 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            9 |     3478 | 2024-03-17 | The MongolZ       | W   | 0.287      | -            | -                | -                | -         |     7.15 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            8 |     4172 | 2024-02-17 | BetBoom           | W   | 0.094      | -            | -                | -                | -         |     0.53 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            7 |     4207 | 2024-02-16 | FaZe              | L   | 0.087      | -            | -                | -                | -         |    -1.36 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            6 |     4237 | 2024-02-15 | Falcons           | W   | 0.080      | -            | -                | -                | -         |     0.45 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            5 |     4263 | 2024-02-14 | G2                | L   | 0.075      | -            | -                | -                | -         |    -0.40 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            4 |     4274 | 2024-02-14 | Ninjas in Pyjamas | W   | 0.074      | -            | -                | -                | -         |     0.00 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            3 |     4393 | 2024-02-05 | Natus Vincere     | L   | 0.015      | -            | -                | -                | -         |    -0.09 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            2 |     4406 | 2024-02-04 | FaZe              | L   | 0.009      | -            | -                | -                | -         |    -0.14 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            1 |     4451 | 2024-02-03 | Falcons           | W   | 0.000      | -            | -                | -                | -         |     0.00 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($247,889.44)
- Divide that value by the 5th highest value among all rosters ($327,422.13)
- The final value (0.76) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $35,000.00     | $35,000.00      |
| 2024-06-09 |      0.848 | $8,000.00      | $6,780.00       |
| 2024-05-23 |      0.734 | $250,000.00    | $183,437.50     |
| 2024-05-12 |      0.661 | $7,000.00      | $4,625.83       |
| 2024-03-31 |      0.382 | $45,000.00     | $17,175.00      |
| 2024-02-11 |      0.054 | $16,000.00     | $871.11         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
