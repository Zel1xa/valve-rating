### Roster Details<br />
Team Name: Eternal Fire<br />
Roster: Calyx, MAJ3R, Wicadia, woxic, XANTARES<br />
Global Rank: [11](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [10]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1621.0<br />
<br />
Final Rank Value (1621.0) = Starting Rank Value (1695.6) + Head To Head Adjustments (-74.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.885[<sup>1</sup>](#table2)
- Bounty Collected: 0.561[<sup>2</sup>](#table1)
- Opponent Network: 0.314[<sup>2</sup>](#table1)
- LAN Wins: 0.772[<sup>2</sup>](#table1)

The average of these factors is 0.633<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1695.6
- 400 + ( ( 0.633 - 0.000 ) / ( 0.781 - 0.000 ) ) * 1600 = 1695.6


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
|           37 |      306 | 2024-07-28 | The MongolZ       | L   | 1.000      | -            | -                | -                | -         |   -11.76 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           36 |      342 | 2024-07-26 | 3DMAX             | W   | 1.000      | 0.650        | 0.508 (0.330)    | 1.000 (0.650)    | 1 (1.000) |     5.87 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           35 |      387 | 2024-07-25 | AMKAL             | W   | 1.000      | 0.650        | -                | 0.472 (0.307)    | 1 (1.000) |     2.74 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           34 |      418 | 2024-07-24 | DMS               | W   | 1.000      | 0.650        | -                | 0.444 (0.289)    | 1 (1.000) |     0.54 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           33 |      427 | 2024-07-24 | Revenant          | W   | 1.000      | 0.650        | -                | 0.267 (0.174)    | 1 (1.000) |     0.47 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           32 |     1428 | 2024-06-06 | BetBoom           | L   | 0.801      | -            | -                | -                | -         |   -19.63 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           31 |     1449 | 2024-06-06 | BIG               | W   | 0.799      | 0.715        | 0.155 (0.088)    | -                | 1 (0.799) |     3.61 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           30 |     1458 | 2024-06-06 | FURIA             | L   | 0.799      | -            | -                | -                | -         |   -15.28 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           29 |     1481 | 2024-06-05 | fnatic            | L   | 0.794      | -            | -                | -                | -         |   -19.49 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           28 |     1508 | 2024-06-05 | Complexity        | L   | 0.792      | -            | -                | -                | -         |   -13.30 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           27 |     1814 | 2024-05-23 | Liquid            | W   | 0.707      | 0.769        | 0.384 (0.208)    | 0.456 (0.248)    | -         |     8.83 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           26 |     1855 | 2024-05-22 | GamerLegion       | W   | 0.700      | 0.769        | 0.173 (0.093)    | -                | -         |     1.29 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           25 |     1895 | 2024-05-21 | BetBoom           | W   | 0.694      | 0.769        | 0.249 (0.133)    | 0.536 (0.286)    | -         |     3.54 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           24 |     2052 | 2024-05-16 | SAW               | W   | 0.661      | 0.769        | -                | 0.537 (0.273)    | -         |     1.44 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           23 |     2061 | 2024-05-16 | PARIVISION        | W   | 0.660      | 0.769        | -                | 0.532 (0.270)    | -         |     0.72 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           22 |     2525 | 2024-04-27 | SAW               | L   | 0.535      | -            | -                | -                | -         |   -15.89 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           21 |     2554 | 2024-04-26 | FaZe              | L   | 0.527      | -            | -                | -                | -         |    -7.73 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           20 |     2581 | 2024-04-25 | fnatic            | W   | 0.521      | 0.889        | 0.371 (0.172)    | 0.706 (0.327)    | 1 (0.521) |     4.64 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           19 |     2601 | 2024-04-24 | Imperial          | W   | 0.515      | 0.889        | 0.235 (0.107)    | 0.683 (0.312)    | 1 (0.515) |     1.60 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           18 |     2622 | 2024-04-23 | Astralis          | L   | 0.507      | -            | -                | -                | -         |    -7.22 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           17 |     2683 | 2024-04-20 | Sashi             | L   | 0.488      | -            | -                | -                | -         |   -14.74 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           16 |     2729 | 2024-04-19 | Sashi             | W   | 0.481      | -            | -                | -                | -         |     0.58 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           15 |     2739 | 2024-04-19 | BetBoom           | W   | 0.480      | -            | -                | -                | -         |     2.39 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           14 |     3297 | 2024-03-29 | Natus Vincere     | L   | 0.341      | -            | -                | -                | -         |    -2.06 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           13 |     3405 | 2024-03-23 | Virtus.pro        | W   | 0.300      | 1.000        | 0.498 (0.149)    | -                | 1 (0.300) |     4.67 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           12 |     3420 | 2024-03-22 | FaZe              | W   | 0.293      | 1.000        | 0.632 (0.185)    | -                | 1 (0.293) |     4.36 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           11 |     3437 | 2024-03-21 | MOUZ              | L   | 0.288      | -            | -                | -                | -         |    -2.80 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           10 |     3445 | 2024-03-21 | Vitality          | W   | 0.287      | 1.000        | 0.648 (0.186)    | -                | 1 (0.287) |     6.33 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            9 |     3484 | 2024-03-19 | GamerLegion       | W   | 0.273      | -            | -                | -                | -         |     0.05 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            8 |     3492 | 2024-03-18 | HEROIC            | L   | 0.267      | -            | -                | -                | -         |    -5.78 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            7 |     3514 | 2024-03-17 | paiN              | W   | 0.261      | -            | -                | -                | -         |     1.31 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            6 |     3526 | 2024-03-17 | The MongolZ       | W   | 0.260      | -            | -                | -                | -         |     6.60 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            5 |     4200 | 2024-02-17 | BetBoom           | W   | 0.068      | -            | -                | -                | -         |     0.38 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            4 |     4234 | 2024-02-16 | FaZe              | L   | 0.060      | -            | -                | -                | -         |    -0.98 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            3 |     4264 | 2024-02-15 | Falcons           | W   | 0.053      | -            | -                | -                | -         |     0.29 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            2 |     4290 | 2024-02-14 | G2                | L   | 0.048      | -            | -                | -                | -         |    -0.23 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            1 |     4301 | 2024-02-14 | Ninjas in Pyjamas | W   | 0.047      | -            | -                | -                | -         |     0.00 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($238,665.56)
- Divide that value by the 5th highest value among all rosters ($322,333.56)
- The final value (0.74) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $35,000.00     | $35,000.00      |
| 2024-06-09 |      0.821 | $8,000.00      | $6,564.44       |
| 2024-05-23 |      0.707 | $250,000.00    | $176,701.39     |
| 2024-05-12 |      0.634 | $7,000.00      | $4,437.22       |
| 2024-03-31 |      0.355 | $45,000.00     | $15,962.50      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
