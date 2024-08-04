### Roster Details<br />
Team Name: Eternal Fire<br />
Roster: Calyx, MAJ3R, Wicadia, woxic, XANTARES<br />
Global Rank: [10](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [9]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1617.8<br />
<br />
Final Rank Value (1617.8) = Starting Rank Value (1697.1) + Head To Head Adjustments (-79.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.886[<sup>1</sup>](#table2)
- Bounty Collected: 0.561[<sup>2</sup>](#table1)
- Opponent Network: 0.319[<sup>2</sup>](#table1)
- LAN Wins: 0.773[<sup>2</sup>](#table1)

The average of these factors is 0.635<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1697.1
- 400 + ( ( 0.635 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 1697.1


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
|           37 |      254 | 2024-07-28 | The MongolZ       | L   | 1.000      | -            | -                | -                | -         |   -11.93 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           36 |      290 | 2024-07-26 | 3DMAX             | W   | 1.000      | 0.650        | 0.505 (0.328)    | 1.000 (0.650)    | 1 (1.000) |     5.75 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           35 |      335 | 2024-07-25 | AMKAL             | W   | 1.000      | 0.650        | -                | 0.477 (0.310)    | 1 (1.000) |     2.79 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           34 |      366 | 2024-07-24 | DMS               | W   | 1.000      | 0.650        | -                | 0.446 (0.290)    | 1 (1.000) |     0.54 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           33 |      375 | 2024-07-24 | Revenant          | W   | 1.000      | -            | -                | -                | 1 (1.000) |     0.48 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           32 |     1375 | 2024-06-06 | BetBoom           | L   | 0.811      | -            | -                | -                | -         |   -19.78 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           31 |     1396 | 2024-06-06 | BIG               | W   | 0.810      | 0.715        | 0.155 (0.090)    | 0.305 (0.177)    | 1 (0.810) |     3.72 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           30 |     1405 | 2024-06-06 | FURIA             | L   | 0.809      | -            | -                | -                | -         |   -15.62 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           29 |     1428 | 2024-06-05 | fnatic            | L   | 0.805      | -            | -                | -                | -         |   -19.76 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           28 |     1455 | 2024-06-05 | Complexity        | L   | 0.803      | -            | -                | -                | -         |   -13.71 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           27 |     1761 | 2024-05-23 | Liquid            | W   | 0.717      | 0.769        | 0.316 (0.174)    | 0.461 (0.254)    | -         |     6.80 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           26 |     1802 | 2024-05-22 | GamerLegion       | W   | 0.711      | 0.769        | 0.174 (0.095)    | -                | -         |     1.32 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           25 |     1842 | 2024-05-21 | BetBoom           | W   | 0.705      | 0.769        | 0.252 (0.136)    | 0.543 (0.294)    | -         |     3.63 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           24 |     1999 | 2024-05-16 | SAW               | W   | 0.672      | 0.769        | -                | 0.541 (0.279)    | -         |     1.49 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           23 |     2008 | 2024-05-16 | PARIVISION        | W   | 0.670      | 0.769        | -                | 0.534 (0.275)    | -         |     0.72 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           22 |     2472 | 2024-04-27 | SAW               | L   | 0.545      | -            | -                | -                | -         |   -16.19 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           21 |     2501 | 2024-04-26 | FaZe              | L   | 0.538      | -            | -                | -                | -         |    -7.87 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           20 |     2527 | 2024-04-25 | fnatic            | W   | 0.532      | 0.889        | 0.371 (0.175)    | 0.709 (0.335)    | 1 (0.532) |     4.69 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           19 |     2547 | 2024-04-24 | Imperial          | W   | 0.525      | 0.889        | 0.238 (0.111)    | 0.685 (0.320)    | 1 (0.525) |     1.68 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           18 |     2568 | 2024-04-23 | Astralis          | L   | 0.518      | -            | -                | -                | -         |    -8.34 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           17 |     2629 | 2024-04-20 | Sashi             | L   | 0.498      | -            | -                | -                | -         |   -15.07 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           16 |     2675 | 2024-04-19 | Sashi             | W   | 0.492      | -            | -                | -                | -         |     0.58 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           15 |     2685 | 2024-04-19 | BetBoom           | W   | 0.491      | -            | -                | -                | -         |     2.44 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           14 |     3243 | 2024-03-29 | Natus Vincere     | L   | 0.351      | -            | -                | -                | -         |    -2.17 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           13 |     3351 | 2024-03-23 | Virtus.pro        | W   | 0.310      | 1.000        | 0.496 (0.154)    | -                | 1 (0.310) |     4.81 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           12 |     3366 | 2024-03-22 | FaZe              | W   | 0.304      | 1.000        | 0.643 (0.195)    | -                | 1 (0.304) |     4.56 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           11 |     3383 | 2024-03-21 | MOUZ              | L   | 0.298      | -            | -                | -                | -         |    -2.93 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           10 |     3391 | 2024-03-21 | Vitality          | W   | 0.297      | 1.000        | 0.649 (0.193)    | -                | 1 (0.297) |     6.51 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            9 |     3430 | 2024-03-19 | GamerLegion       | W   | 0.284      | -            | -                | -                | -         |     0.06 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            8 |     3438 | 2024-03-18 | HEROIC            | L   | 0.277      | -            | -                | -                | -         |    -6.02 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            7 |     3460 | 2024-03-17 | paiN              | W   | 0.272      | -            | -                | -                | -         |     1.39 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            6 |     3472 | 2024-03-17 | The MongolZ       | W   | 0.270      | -            | -                | -                | -         |     6.83 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            5 |     4144 | 2024-02-17 | BetBoom           | W   | 0.078      | -            | -                | -                | -         |     0.44 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            4 |     4178 | 2024-02-16 | FaZe              | L   | 0.071      | -            | -                | -                | -         |    -1.15 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            3 |     4208 | 2024-02-15 | Falcons           | W   | 0.063      | -            | -                | -                | -         |     0.36 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            2 |     4234 | 2024-02-14 | G2                | L   | 0.059      | -            | -                | -                | -         |    -0.29 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            1 |     4245 | 2024-02-14 | Ninjas in Pyjamas | W   | 0.057      | -            | -                | -                | -         |     0.00 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($241,937.78)
- Divide that value by the 5th highest value among all rosters ($325,463.29)
- The final value (0.74) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $35,000.00     | $35,000.00      |
| 2024-06-09 |      0.831 | $8,000.00      | $6,648.89       |
| 2024-05-23 |      0.717 | $250,000.00    | $179,340.28     |
| 2024-05-12 |      0.644 | $7,000.00      | $4,511.11       |
| 2024-03-31 |      0.365 | $45,000.00     | $16,437.50      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
