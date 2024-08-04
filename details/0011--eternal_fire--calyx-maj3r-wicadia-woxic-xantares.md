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
|           37 |      288 | 2024-07-28 | The MongolZ       | L   | 1.000      | -            | -                | -                | -         |   -11.89 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           36 |      324 | 2024-07-26 | 3DMAX             | W   | 1.000      | 0.650        | 0.506 (0.329)    | 1.000 (0.650)    | 1 (1.000) |     5.75 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           35 |      369 | 2024-07-25 | AMKAL             | W   | 1.000      | 0.650        | -                | 0.475 (0.309)    | 1 (1.000) |     2.74 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           34 |      400 | 2024-07-24 | DMS               | W   | 1.000      | 0.650        | -                | 0.446 (0.290)    | 1 (1.000) |     0.53 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           33 |      409 | 2024-07-24 | Revenant          | W   | 1.000      | -            | -                | -                | 1 (1.000) |     0.47 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           32 |     1410 | 2024-06-06 | BetBoom           | L   | 0.807      | -            | -                | -                | -         |   -19.78 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           31 |     1431 | 2024-06-06 | BIG               | W   | 0.805      | 0.715        | 0.155 (0.089)    | 0.304 (0.175)    | 1 (0.805) |     3.63 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           30 |     1440 | 2024-06-06 | FURIA             | L   | 0.805      | -            | -                | -                | -         |   -15.53 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           29 |     1463 | 2024-06-05 | fnatic            | L   | 0.801      | -            | -                | -                | -         |   -19.70 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           28 |     1490 | 2024-06-05 | Complexity        | L   | 0.798      | -            | -                | -                | -         |   -13.39 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           27 |     1796 | 2024-05-23 | Liquid            | W   | 0.713      | 0.769        | 0.384 (0.211)    | 0.460 (0.252)    | -         |     8.86 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           26 |     1837 | 2024-05-22 | GamerLegion       | W   | 0.706      | 0.769        | 0.173 (0.094)    | -                | -         |     1.29 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           25 |     1877 | 2024-05-21 | BetBoom           | W   | 0.700      | 0.769        | 0.251 (0.135)    | 0.541 (0.291)    | -         |     3.57 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           24 |     2034 | 2024-05-16 | SAW               | W   | 0.667      | 0.769        | -                | 0.540 (0.277)    | -         |     1.47 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           23 |     2043 | 2024-05-16 | PARIVISION        | W   | 0.666      | 0.769        | -                | 0.534 (0.273)    | -         |     0.71 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           22 |     2507 | 2024-04-27 | SAW               | L   | 0.541      | -            | -                | -                | -         |   -16.06 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           21 |     2536 | 2024-04-26 | FaZe              | L   | 0.533      | -            | -                | -                | -         |    -7.76 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           20 |     2563 | 2024-04-25 | fnatic            | W   | 0.527      | 0.889        | 0.371 (0.174)    | 0.708 (0.332)    | 1 (0.527) |     4.66 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           19 |     2583 | 2024-04-24 | Imperial          | W   | 0.521      | 0.889        | 0.236 (0.109)    | 0.685 (0.317)    | 1 (0.521) |     1.63 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           18 |     2604 | 2024-04-23 | Astralis          | L   | 0.513      | -            | -                | -                | -         |    -7.33 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           17 |     2665 | 2024-04-20 | Sashi             | L   | 0.494      | -            | -                | -                | -         |   -14.93 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           16 |     2711 | 2024-04-19 | Sashi             | W   | 0.487      | -            | -                | -                | -         |     0.58 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           15 |     2721 | 2024-04-19 | BetBoom           | W   | 0.486      | -            | -                | -                | -         |     2.41 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           14 |     3279 | 2024-03-29 | Natus Vincere     | L   | 0.347      | -            | -                | -                | -         |    -2.11 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           13 |     3387 | 2024-03-23 | Virtus.pro        | W   | 0.306      | 1.000        | 0.497 (0.152)    | -                | 1 (0.306) |     4.76 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           12 |     3402 | 2024-03-22 | FaZe              | W   | 0.299      | 1.000        | 0.638 (0.191)    | -                | 1 (0.299) |     4.48 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           11 |     3419 | 2024-03-21 | MOUZ              | L   | 0.294      | -            | -                | -                | -         |    -2.88 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           10 |     3427 | 2024-03-21 | Vitality          | W   | 0.293      | 1.000        | 0.649 (0.190)    | -                | 1 (0.293) |     6.45 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            9 |     3466 | 2024-03-19 | GamerLegion       | W   | 0.279      | -            | -                | -                | -         |     0.06 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            8 |     3474 | 2024-03-18 | HEROIC            | L   | 0.273      | -            | -                | -                | -         |    -5.92 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            7 |     3496 | 2024-03-17 | paiN              | W   | 0.267      | -            | -                | -                | -         |     1.35 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            6 |     3508 | 2024-03-17 | The MongolZ       | W   | 0.266      | -            | -                | -                | -         |     6.73 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            5 |     4182 | 2024-02-17 | BetBoom           | W   | 0.074      | -            | -                | -                | -         |     0.41 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            4 |     4216 | 2024-02-16 | FaZe              | L   | 0.066      | -            | -                | -                | -         |    -1.08 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            3 |     4246 | 2024-02-15 | Falcons           | W   | 0.059      | -            | -                | -                | -         |     0.33 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            2 |     4272 | 2024-02-14 | G2                | L   | 0.054      | -            | -                | -                | -         |    -0.27 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            1 |     4283 | 2024-02-14 | Ninjas in Pyjamas | W   | 0.053      | -            | -                | -                | -         |     0.00 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($240,531.30)
- Divide that value by the 5th highest value among all rosters ($324,118.06)
- The final value (0.74) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $35,000.00     | $35,000.00      |
| 2024-06-09 |      0.827 | $8,000.00      | $6,612.59       |
| 2024-05-23 |      0.713 | $250,000.00    | $178,206.02     |
| 2024-05-12 |      0.640 | $7,000.00      | $4,479.35       |
| 2024-03-31 |      0.361 | $45,000.00     | $16,233.33      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
