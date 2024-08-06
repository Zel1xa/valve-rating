### Roster Details<br />
Team Name: Eternal Fire<br />
Roster: Calyx, MAJ3R, Wicadia, woxic, XANTARES<br />
Global Rank: [11](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [10]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1621.2<br />
<br />
Final Rank Value (1621.2) = Starting Rank Value (1695.8) + Head To Head Adjustments (-74.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.884[<sup>1</sup>](#table2)
- Bounty Collected: 0.560[<sup>2</sup>](#table1)
- Opponent Network: 0.311[<sup>2</sup>](#table1)
- LAN Wins: 0.771[<sup>2</sup>](#table1)

The average of these factors is 0.632<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1695.8
- 400 + ( ( 0.632 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 1695.8


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
|           37 |      317 | 2024-07-28 | The MongolZ       | L   | 1.000      | -            | -                | -                | -         |   -11.76 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           36 |      353 | 2024-07-26 | 3DMAX             | W   | 1.000      | 0.650        | 0.509 (0.331)    | 1.000 (0.650)    | 1 (1.000) |     5.92 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           35 |      398 | 2024-07-25 | AMKAL             | W   | 1.000      | 0.650        | -                | 0.464 (0.302)    | 1 (1.000) |     2.74 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           34 |      429 | 2024-07-24 | DMS               | W   | 1.000      | 0.650        | -                | 0.438 (0.285)    | 1 (1.000) |     0.55 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           33 |      438 | 2024-07-24 | Revenant          | W   | 1.000      | 0.650        | -                | 0.265 (0.172)    | 1 (1.000) |     0.48 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           32 |     1439 | 2024-06-06 | BetBoom           | L   | 0.797      | -            | -                | -                | -         |   -19.58 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           31 |     1460 | 2024-06-06 | BIG               | W   | 0.796      | 0.715        | 0.154 (0.088)    | -                | 1 (0.796) |     3.58 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           30 |     1469 | 2024-06-06 | FURIA             | L   | 0.795      | -            | -                | -                | -         |   -15.21 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           29 |     1492 | 2024-06-05 | fnatic            | L   | 0.791      | -            | -                | -                | -         |   -19.41 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           28 |     1519 | 2024-06-05 | Complexity        | L   | 0.789      | -            | -                | -                | -         |   -13.27 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           27 |     1825 | 2024-05-23 | Liquid            | W   | 0.703      | 0.769        | 0.383 (0.207)    | 0.449 (0.243)    | -         |     8.78 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           26 |     1866 | 2024-05-22 | GamerLegion       | W   | 0.697      | 0.769        | 0.173 (0.093)    | -                | -         |     1.28 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           25 |     1906 | 2024-05-21 | BetBoom           | W   | 0.691      | 0.769        | 0.249 (0.132)    | 0.527 (0.280)    | -         |     3.51 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           24 |     2063 | 2024-05-16 | SAW               | W   | 0.658      | 0.769        | -                | 0.529 (0.268)    | -         |     1.42 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           23 |     2072 | 2024-05-16 | PARIVISION        | W   | 0.657      | 0.769        | -                | 0.565 (0.285)    | -         |     0.73 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           22 |     2536 | 2024-04-27 | SAW               | L   | 0.531      | -            | -                | -                | -         |   -15.80 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           21 |     2565 | 2024-04-26 | FaZe              | L   | 0.524      | -            | -                | -                | -         |    -7.73 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           20 |     2592 | 2024-04-25 | fnatic            | W   | 0.518      | 0.889        | 0.371 (0.171)    | 0.696 (0.321)    | 1 (0.518) |     4.60 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           19 |     2612 | 2024-04-24 | Imperial          | W   | 0.511      | 0.889        | 0.234 (0.106)    | 0.674 (0.306)    | 1 (0.511) |     1.57 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           18 |     2633 | 2024-04-23 | Astralis          | L   | 0.504      | -            | -                | -                | -         |    -7.20 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           17 |     2694 | 2024-04-20 | Sashi             | L   | 0.485      | -            | -                | -                | -         |   -14.64 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           16 |     2740 | 2024-04-19 | Sashi             | W   | 0.478      | -            | -                | -                | -         |     0.58 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           15 |     2750 | 2024-04-19 | BetBoom           | W   | 0.477      | -            | -                | -                | -         |     2.35 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           14 |     3308 | 2024-03-29 | Natus Vincere     | L   | 0.338      | -            | -                | -                | -         |    -2.04 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           13 |     3416 | 2024-03-23 | Virtus.pro        | W   | 0.296      | 1.000        | 0.498 (0.148)    | -                | 1 (0.296) |     4.60 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           12 |     3431 | 2024-03-22 | FaZe              | W   | 0.290      | 1.000        | 0.629 (0.182)    | -                | 1 (0.290) |     4.28 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           11 |     3448 | 2024-03-21 | MOUZ              | L   | 0.285      | -            | -                | -                | -         |    -2.79 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           10 |     3456 | 2024-03-21 | Vitality          | W   | 0.283      | 1.000        | 0.647 (0.183)    | -                | 1 (0.283) |     6.25 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            9 |     3495 | 2024-03-19 | GamerLegion       | W   | 0.270      | -            | -                | -                | -         |     0.05 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            8 |     3503 | 2024-03-18 | HEROIC            | L   | 0.264      | -            | -                | -                | -         |    -5.73 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            7 |     3525 | 2024-03-17 | paiN              | W   | 0.258      | -            | -                | -                | -         |     1.28 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            6 |     3537 | 2024-03-17 | The MongolZ       | W   | 0.256      | -            | -                | -                | -         |     6.51 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            5 |     4211 | 2024-02-17 | BetBoom           | W   | 0.064      | -            | -                | -                | -         |     0.35 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            4 |     4245 | 2024-02-16 | FaZe              | L   | 0.057      | -            | -                | -                | -         |    -0.94 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            3 |     4275 | 2024-02-15 | Falcons           | W   | 0.049      | -            | -                | -                | -         |     0.27 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            2 |     4301 | 2024-02-14 | G2                | L   | 0.045      | -            | -                | -                | -         |    -0.22 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            1 |     4312 | 2024-02-14 | Ninjas in Pyjamas | W   | 0.043      | -            | -                | -                | -         |     0.00 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($237,632.22)
- Divide that value by the 5th highest value among all rosters ($321,345.23)
- The final value (0.74) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $35,000.00     | $35,000.00      |
| 2024-06-09 |      0.817 | $8,000.00      | $6,537.78       |
| 2024-05-23 |      0.703 | $250,000.00    | $175,868.06     |
| 2024-05-12 |      0.631 | $7,000.00      | $4,413.89       |
| 2024-03-31 |      0.351 | $45,000.00     | $15,812.50      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
