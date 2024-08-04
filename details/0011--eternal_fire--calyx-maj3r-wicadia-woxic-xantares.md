### Roster Details<br />
Team Name: Eternal Fire<br />
Roster: Calyx, MAJ3R, Wicadia, woxic, XANTARES<br />
Global Rank: [11](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [10]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1621.6<br />
<br />
Final Rank Value (1621.6) = Starting Rank Value (1697.3) + Head To Head Adjustments (-75.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.885[<sup>1</sup>](#table2)
- Bounty Collected: 0.563[<sup>2</sup>](#table1)
- Opponent Network: 0.317[<sup>2</sup>](#table1)
- LAN Wins: 0.773[<sup>2</sup>](#table1)

The average of these factors is 0.634<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1697.3
- 400 + ( ( 0.634 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 1697.3


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
|           37 |      289 | 2024-07-28 | The MongolZ       | L   | 1.000      | -            | -                | -                | -         |   -11.89 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           36 |      325 | 2024-07-26 | 3DMAX             | W   | 1.000      | 0.650        | 0.506 (0.329)    | 1.000 (0.650)    | 1 (1.000) |     5.76 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           35 |      370 | 2024-07-25 | AMKAL             | W   | 1.000      | 0.650        | -                | 0.475 (0.309)    | 1 (1.000) |     2.74 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           34 |      401 | 2024-07-24 | DMS               | W   | 1.000      | 0.650        | -                | 0.446 (0.290)    | 1 (1.000) |     0.53 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           33 |      410 | 2024-07-24 | Revenant          | W   | 1.000      | -            | -                | -                | 1 (1.000) |     0.47 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           32 |     1411 | 2024-06-06 | BetBoom           | L   | 0.806      | -            | -                | -                | -         |   -19.77 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           31 |     1432 | 2024-06-06 | BIG               | W   | 0.805      | 0.715        | 0.155 (0.089)    | 0.304 (0.175)    | 1 (0.805) |     3.63 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           30 |     1441 | 2024-06-06 | FURIA             | L   | 0.804      | -            | -                | -                | -         |   -15.52 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           29 |     1464 | 2024-06-05 | fnatic            | L   | 0.800      | -            | -                | -                | -         |   -19.69 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           28 |     1491 | 2024-06-05 | Complexity        | L   | 0.798      | -            | -                | -                | -         |   -13.38 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           27 |     1797 | 2024-05-23 | Liquid            | W   | 0.713      | 0.769        | 0.384 (0.210)    | 0.460 (0.252)    | -         |     8.85 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           26 |     1838 | 2024-05-22 | GamerLegion       | W   | 0.706      | 0.769        | 0.173 (0.094)    | -                | -         |     1.29 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           25 |     1878 | 2024-05-21 | BetBoom           | W   | 0.700      | 0.769        | 0.251 (0.135)    | 0.541 (0.291)    | -         |     3.57 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           24 |     2035 | 2024-05-16 | SAW               | W   | 0.667      | 0.769        | -                | 0.540 (0.277)    | -         |     1.47 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           23 |     2044 | 2024-05-16 | PARIVISION        | W   | 0.666      | 0.769        | -                | 0.534 (0.273)    | -         |     0.72 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           22 |     2508 | 2024-04-27 | SAW               | L   | 0.540      | -            | -                | -                | -         |   -16.05 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           21 |     2537 | 2024-04-26 | FaZe              | L   | 0.533      | -            | -                | -                | -         |    -7.76 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           20 |     2564 | 2024-04-25 | fnatic            | W   | 0.527      | 0.889        | 0.371 (0.174)    | 0.708 (0.332)    | 1 (0.527) |     4.66 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           19 |     2584 | 2024-04-24 | Imperial          | W   | 0.520      | 0.889        | 0.236 (0.109)    | 0.685 (0.317)    | 1 (0.520) |     1.63 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           18 |     2605 | 2024-04-23 | Astralis          | L   | 0.513      | -            | -                | -                | -         |    -7.32 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           17 |     2666 | 2024-04-20 | Sashi             | L   | 0.494      | -            | -                | -                | -         |   -14.92 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           16 |     2712 | 2024-04-19 | Sashi             | W   | 0.487      | -            | -                | -                | -         |     0.58 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           15 |     2722 | 2024-04-19 | BetBoom           | W   | 0.486      | -            | -                | -                | -         |     2.41 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           14 |     3280 | 2024-03-29 | Natus Vincere     | L   | 0.347      | -            | -                | -                | -         |    -2.11 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           13 |     3388 | 2024-03-23 | Virtus.pro        | W   | 0.305      | 1.000        | 0.497 (0.152)    | -                | 1 (0.305) |     4.76 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           12 |     3403 | 2024-03-22 | FaZe              | W   | 0.299      | 1.000        | 0.638 (0.191)    | -                | 1 (0.299) |     4.47 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           11 |     3420 | 2024-03-21 | MOUZ              | L   | 0.294      | -            | -                | -                | -         |    -2.88 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           10 |     3428 | 2024-03-21 | Vitality          | W   | 0.292      | 1.000        | 0.649 (0.190)    | -                | 1 (0.292) |     6.45 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            9 |     3467 | 2024-03-19 | GamerLegion       | W   | 0.279      | -            | -                | -                | -         |     0.06 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            8 |     3475 | 2024-03-18 | HEROIC            | L   | 0.273      | -            | -                | -                | -         |    -5.91 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            7 |     3497 | 2024-03-17 | paiN              | W   | 0.267      | -            | -                | -                | -         |     1.35 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            6 |     3509 | 2024-03-17 | The MongolZ       | W   | 0.265      | -            | -                | -                | -         |     6.72 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            5 |     4183 | 2024-02-17 | BetBoom           | W   | 0.073      | -            | -                | -                | -         |     0.41 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            4 |     4217 | 2024-02-16 | FaZe              | L   | 0.066      | -            | -                | -                | -         |    -1.07 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            3 |     4247 | 2024-02-15 | Falcons           | W   | 0.058      | -            | -                | -                | -         |     0.33 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            2 |     4273 | 2024-02-14 | G2                | L   | 0.054      | -            | -                | -                | -         |    -0.26 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            1 |     4284 | 2024-02-14 | Ninjas in Pyjamas | W   | 0.052      | -            | -                | -                | -         |     0.00 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($240,438.01)
- Divide that value by the 5th highest value among all rosters ($324,028.83)
- The final value (0.74) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $35,000.00     | $35,000.00      |
| 2024-06-09 |      0.826 | $8,000.00      | $6,610.19       |
| 2024-05-23 |      0.713 | $250,000.00    | $178,130.79     |
| 2024-05-12 |      0.640 | $7,000.00      | $4,477.25       |
| 2024-03-31 |      0.360 | $45,000.00     | $16,219.79      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
