### Roster Details<br />
Team Name: Eternal Fire<br />
Roster: Calyx, MAJ3R, Wicadia, woxic, XANTARES<br />
Global Rank: [11](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [10]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1621.5<br />
<br />
Final Rank Value (1621.5) = Starting Rank Value (1696.4) + Head To Head Adjustments (-74.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.884[<sup>1</sup>](#table2)
- Bounty Collected: 0.561[<sup>2</sup>](#table1)
- Opponent Network: 0.312[<sup>2</sup>](#table1)
- LAN Wins: 0.772[<sup>2</sup>](#table1)

The average of these factors is 0.632<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1696.4
- 400 + ( ( 0.632 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 1696.4


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
|           37 |      314 | 2024-07-28 | The MongolZ       | L   | 1.000      | -            | -                | -                | -         |   -11.78 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           36 |      350 | 2024-07-26 | 3DMAX             | W   | 1.000      | 0.650        | 0.508 (0.330)    | 1.000 (0.650)    | 1 (1.000) |     5.88 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           35 |      395 | 2024-07-25 | AMKAL             | W   | 1.000      | 0.650        | -                | 0.465 (0.303)    | 1 (1.000) |     2.73 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           34 |      426 | 2024-07-24 | DMS               | W   | 1.000      | 0.650        | -                | 0.438 (0.285)    | 1 (1.000) |     0.54 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           33 |      435 | 2024-07-24 | Revenant          | W   | 1.000      | 0.650        | -                | 0.264 (0.172)    | 1 (1.000) |     0.47 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           32 |     1436 | 2024-06-06 | BetBoom           | L   | 0.800      | -            | -                | -                | -         |   -19.63 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           31 |     1457 | 2024-06-06 | BIG               | W   | 0.798      | 0.715        | 0.154 (0.088)    | -                | 1 (0.798) |     3.59 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           30 |     1466 | 2024-06-06 | FURIA             | L   | 0.797      | -            | -                | -                | -         |   -15.28 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           29 |     1489 | 2024-06-05 | fnatic            | L   | 0.793      | -            | -                | -                | -         |   -19.48 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           28 |     1516 | 2024-06-05 | Complexity        | L   | 0.791      | -            | -                | -                | -         |   -13.30 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           27 |     1822 | 2024-05-23 | Liquid            | W   | 0.706      | 0.769        | 0.383 (0.208)    | 0.450 (0.244)    | -         |     8.80 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           26 |     1863 | 2024-05-22 | GamerLegion       | W   | 0.699      | 0.769        | 0.173 (0.093)    | -                | -         |     1.28 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           25 |     1903 | 2024-05-21 | BetBoom           | W   | 0.693      | 0.769        | 0.249 (0.133)    | 0.529 (0.282)    | -         |     3.52 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           24 |     2060 | 2024-05-16 | SAW               | W   | 0.660      | 0.769        | -                | 0.530 (0.269)    | -         |     1.43 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           23 |     2069 | 2024-05-16 | PARIVISION        | W   | 0.659      | 0.769        | -                | 0.565 (0.286)    | -         |     0.73 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           22 |     2533 | 2024-04-27 | SAW               | L   | 0.533      | -            | -                | -                | -         |   -15.86 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           21 |     2562 | 2024-04-26 | FaZe              | L   | 0.526      | -            | -                | -                | -         |    -7.74 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           20 |     2589 | 2024-04-25 | fnatic            | W   | 0.520      | 0.889        | 0.371 (0.171)    | 0.697 (0.322)    | 1 (0.520) |     4.61 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           19 |     2609 | 2024-04-24 | Imperial          | W   | 0.513      | 0.889        | 0.235 (0.107)    | 0.674 (0.308)    | 1 (0.513) |     1.58 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           18 |     2630 | 2024-04-23 | Astralis          | L   | 0.506      | -            | -                | -                | -         |    -7.23 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           17 |     2691 | 2024-04-20 | Sashi             | L   | 0.487      | -            | -                | -                | -         |   -14.71 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           16 |     2737 | 2024-04-19 | Sashi             | W   | 0.480      | -            | -                | -                | -         |     0.58 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           15 |     2747 | 2024-04-19 | BetBoom           | W   | 0.479      | -            | -                | -                | -         |     2.37 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           14 |     3305 | 2024-03-29 | Natus Vincere     | L   | 0.340      | -            | -                | -                | -         |    -2.06 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           13 |     3413 | 2024-03-23 | Virtus.pro        | W   | 0.299      | 1.000        | 0.498 (0.149)    | -                | 1 (0.299) |     4.64 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           12 |     3428 | 2024-03-22 | FaZe              | W   | 0.292      | 1.000        | 0.631 (0.184)    | -                | 1 (0.292) |     4.32 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           11 |     3445 | 2024-03-21 | MOUZ              | L   | 0.287      | -            | -                | -                | -         |    -2.81 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           10 |     3453 | 2024-03-21 | Vitality          | W   | 0.286      | 1.000        | 0.648 (0.185)    | -                | 1 (0.286) |     6.29 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            9 |     3492 | 2024-03-19 | GamerLegion       | W   | 0.272      | -            | -                | -                | -         |     0.05 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            8 |     3500 | 2024-03-18 | HEROIC            | L   | 0.266      | -            | -                | -                | -         |    -5.77 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            7 |     3522 | 2024-03-17 | paiN              | W   | 0.260      | -            | -                | -                | -         |     1.29 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            6 |     3534 | 2024-03-17 | The MongolZ       | W   | 0.259      | -            | -                | -                | -         |     6.57 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            5 |     4208 | 2024-02-17 | BetBoom           | W   | 0.066      | -            | -                | -                | -         |     0.37 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            4 |     4242 | 2024-02-16 | FaZe              | L   | 0.059      | -            | -                | -                | -         |    -0.97 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            3 |     4272 | 2024-02-15 | Falcons           | W   | 0.052      | -            | -                | -                | -         |     0.29 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            2 |     4298 | 2024-02-14 | G2                | L   | 0.047      | -            | -                | -                | -         |    -0.23 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            1 |     4309 | 2024-02-14 | Ninjas in Pyjamas | W   | 0.046      | -            | -                | -                | -         |     0.00 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($238,321.11)
- Divide that value by the 5th highest value among all rosters ($322,004.12)
- The final value (0.74) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $35,000.00     | $35,000.00      |
| 2024-06-09 |      0.819 | $8,000.00      | $6,555.56       |
| 2024-05-23 |      0.706 | $250,000.00    | $176,423.61     |
| 2024-05-12 |      0.633 | $7,000.00      | $4,429.44       |
| 2024-03-31 |      0.354 | $45,000.00     | $15,912.50      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
