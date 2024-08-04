### Roster Details<br />
Team Name: Eternal Fire<br />
Roster: Calyx, MAJ3R, Wicadia, woxic, XANTARES<br />
Global Rank: [10](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [9]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1617.3<br />
<br />
Final Rank Value (1617.3) = Starting Rank Value (1696.2) + Head To Head Adjustments (-78.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.886[<sup>1</sup>](#table2)
- Bounty Collected: 0.560[<sup>2</sup>](#table1)
- Opponent Network: 0.317[<sup>2</sup>](#table1)
- LAN Wins: 0.773[<sup>2</sup>](#table1)

The average of these factors is 0.634<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1696.2
- 400 + ( ( 0.634 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 1696.2


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
|           37 |      257 | 2024-07-28 | The MongolZ       | L   | 1.000      | -            | -                | -                | -         |   -11.90 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           36 |      293 | 2024-07-26 | 3DMAX             | W   | 1.000      | 0.650        | 0.506 (0.329)    | 1.000 (0.650)    | 1 (1.000) |     5.80 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           35 |      338 | 2024-07-25 | AMKAL             | W   | 1.000      | 0.650        | -                | 0.476 (0.309)    | 1 (1.000) |     2.79 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           34 |      369 | 2024-07-24 | DMS               | W   | 1.000      | 0.650        | -                | 0.446 (0.290)    | 1 (1.000) |     0.54 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           33 |      378 | 2024-07-24 | Revenant          | W   | 1.000      | -            | -                | -                | 1 (1.000) |     0.48 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           32 |     1379 | 2024-06-06 | BetBoom           | L   | 0.808      | -            | -                | -                | -         |   -19.72 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           31 |     1400 | 2024-06-06 | BIG               | W   | 0.807      | 0.715        | 0.155 (0.090)    | 0.304 (0.176)    | 1 (0.807) |     3.70 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           30 |     1409 | 2024-06-06 | FURIA             | L   | 0.806      | -            | -                | -                | -         |   -15.53 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           29 |     1432 | 2024-06-05 | fnatic            | L   | 0.802      | -            | -                | -                | -         |   -19.67 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           28 |     1459 | 2024-06-05 | Complexity        | L   | 0.799      | -            | -                | -                | -         |   -13.67 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           27 |     1765 | 2024-05-23 | Liquid            | W   | 0.714      | 0.769        | 0.315 (0.173)    | 0.460 (0.253)    | -         |     6.77 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           26 |     1806 | 2024-05-22 | GamerLegion       | W   | 0.708      | 0.769        | 0.174 (0.094)    | -                | -         |     1.31 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           25 |     1846 | 2024-05-21 | BetBoom           | W   | 0.702      | 0.769        | 0.251 (0.135)    | 0.542 (0.292)    | -         |     3.61 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           24 |     2003 | 2024-05-16 | SAW               | W   | 0.669      | 0.769        | -                | 0.540 (0.278)    | -         |     1.47 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           23 |     2012 | 2024-05-16 | PARIVISION        | W   | 0.667      | 0.769        | -                | 0.534 (0.274)    | -         |     0.72 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           22 |     2476 | 2024-04-27 | SAW               | L   | 0.542      | -            | -                | -                | -         |   -16.11 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           21 |     2505 | 2024-04-26 | FaZe              | L   | 0.535      | -            | -                | -                | -         |    -7.85 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           20 |     2532 | 2024-04-25 | fnatic            | W   | 0.529      | 0.889        | 0.371 (0.174)    | 0.708 (0.333)    | 1 (0.529) |     4.68 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           19 |     2552 | 2024-04-24 | Imperial          | W   | 0.522      | 0.889        | 0.237 (0.110)    | 0.685 (0.318)    | 1 (0.522) |     1.66 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           18 |     2573 | 2024-04-23 | Astralis          | L   | 0.515      | -            | -                | -                | -         |    -8.30 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           17 |     2634 | 2024-04-20 | Sashi             | L   | 0.495      | -            | -                | -                | -         |   -14.98 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           16 |     2680 | 2024-04-19 | Sashi             | W   | 0.489      | -            | -                | -                | -         |     0.58 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           15 |     2690 | 2024-04-19 | BetBoom           | W   | 0.488      | -            | -                | -                | -         |     2.43 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           14 |     3248 | 2024-03-29 | Natus Vincere     | L   | 0.348      | -            | -                | -                | -         |    -2.14 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           13 |     3356 | 2024-03-23 | Virtus.pro        | W   | 0.307      | 1.000        | 0.497 (0.153)    | -                | 1 (0.307) |     4.77 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           12 |     3371 | 2024-03-22 | FaZe              | W   | 0.301      | 1.000        | 0.640 (0.192)    | -                | 1 (0.301) |     4.50 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           11 |     3388 | 2024-03-21 | MOUZ              | L   | 0.295      | -            | -                | -                | -         |    -2.90 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           10 |     3396 | 2024-03-21 | Vitality          | W   | 0.294      | 1.000        | 0.649 (0.191)    | -                | 1 (0.294) |     6.45 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            9 |     3435 | 2024-03-19 | GamerLegion       | W   | 0.281      | -            | -                | -                | -         |     0.06 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            8 |     3443 | 2024-03-18 | HEROIC            | L   | 0.274      | -            | -                | -                | -         |    -5.96 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            7 |     3465 | 2024-03-17 | paiN              | W   | 0.269      | -            | -                | -                | -         |     1.37 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            6 |     3477 | 2024-03-17 | The MongolZ       | W   | 0.267      | -            | -                | -                | -         |     6.76 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            5 |     4151 | 2024-02-17 | BetBoom           | W   | 0.075      | -            | -                | -                | -         |     0.42 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            4 |     4185 | 2024-02-16 | FaZe              | L   | 0.068      | -            | -                | -                | -         |    -1.10 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            3 |     4215 | 2024-02-15 | Falcons           | W   | 0.060      | -            | -                | -                | -         |     0.34 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            2 |     4241 | 2024-02-14 | G2                | L   | 0.056      | -            | -                | -                | -         |    -0.27 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            1 |     4252 | 2024-02-14 | Ninjas in Pyjamas | W   | 0.054      | -            | -                | -                | -         |     0.00 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($240,990.56)
- Divide that value by the 5th highest value among all rosters ($324,557.31)
- The final value (0.74) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $35,000.00     | $35,000.00      |
| 2024-06-09 |      0.828 | $8,000.00      | $6,624.44       |
| 2024-05-23 |      0.714 | $250,000.00    | $178,576.39     |
| 2024-05-12 |      0.641 | $7,000.00      | $4,489.72       |
| 2024-03-31 |      0.362 | $45,000.00     | $16,300.00      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
