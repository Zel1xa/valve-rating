### Roster Details<br />
Team Name: Eternal Fire<br />
Roster: Calyx, MAJ3R, Wicadia, woxic, XANTARES<br />
Global Rank: [10](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [9]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1638.0<br />
<br />
Final Rank Value (1638.0) = Starting Rank Value (1724.7) + Head To Head Adjustments (-86.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.890[<sup>1</sup>](#table2)
- Bounty Collected: 0.570[<sup>2</sup>](#table1)
- Opponent Network: 0.316[<sup>2</sup>](#table1)
- LAN Wins: 0.793[<sup>2</sup>](#table1)

The average of these factors is 0.642<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1724.7
- 400 + ( ( 0.642 - 0.000 ) / ( 0.776 - 0.000 ) ) * 1600 = 1724.7


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
|           40 |      140 | 2024-07-28 | The MongolZ       | L   | 1.000      | -            | -                | -                | -         |   -12.39 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           39 |      176 | 2024-07-26 | 3DMAX             | W   | 1.000      | 0.650        | 0.499 (0.325)    | 1.000 (0.650)    | 1 (1.000) |     5.33 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           38 |      221 | 2024-07-25 | AMKAL             | W   | 1.000      | 0.650        | -                | 0.484 (0.315)    | 1 (1.000) |     2.64 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           37 |      252 | 2024-07-24 | DMS               | W   | 1.000      | 0.650        | -                | 0.447 (0.291)    | 1 (1.000) |     0.49 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           36 |      261 | 2024-07-24 | Revenant          | W   | 1.000      | -            | -                | -                | 1 (1.000) |     0.43 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           35 |     1262 | 2024-06-06 | BetBoom           | L   | 0.832      | -            | -                | -                | -         |   -20.44 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           34 |     1283 | 2024-06-06 | BIG               | W   | 0.831      | 0.715        | 0.157 (0.094)    | 0.300 (0.178)    | 1 (0.831) |     2.82 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           33 |     1292 | 2024-06-06 | FURIA             | L   | 0.830      | -            | -                | -                | -         |   -16.24 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           32 |     1315 | 2024-06-05 | fnatic            | L   | 0.826      | -            | -                | -                | -         |   -20.41 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           31 |     1342 | 2024-06-05 | Complexity        | L   | 0.823      | -            | -                | -                | -         |   -14.51 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           30 |     1648 | 2024-05-23 | Liquid            | W   | 0.738      | 0.769        | 0.387 (0.220)    | 0.430 (0.244)    | -         |     5.99 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           29 |     1689 | 2024-05-22 | GamerLegion       | W   | 0.732      | 0.769        | 0.175 (0.098)    | -                | -         |     1.28 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           28 |     1729 | 2024-05-21 | BetBoom           | W   | 0.725      | 0.769        | 0.256 (0.143)    | 0.554 (0.309)    | -         |     3.58 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           27 |     1886 | 2024-05-16 | SAW               | W   | 0.693      | 0.769        | -                | 0.545 (0.290)    | -         |     1.47 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           26 |     1895 | 2024-05-16 | PARIVISION        | W   | 0.691      | 0.769        | -                | 0.452 (0.240)    | -         |     0.63 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           25 |     2359 | 2024-04-27 | SAW               | L   | 0.566      | -            | -                | -                | -         |   -16.85 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           24 |     2388 | 2024-04-26 | FaZe              | L   | 0.559      | -            | -                | -                | -         |    -7.94 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           23 |     2415 | 2024-04-25 | fnatic            | W   | 0.553      | 0.889        | 0.371 (0.182)    | 0.633 (0.311)    | 1 (0.553) |     4.77 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           22 |     2435 | 2024-04-24 | Imperial          | W   | 0.546      | 0.889        | 0.243 (0.118)    | 0.685 (0.332)    | 1 (0.546) |     1.70 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           21 |     2456 | 2024-04-23 | Astralis          | L   | 0.539      | -            | -                | -                | -         |    -8.83 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           20 |     2517 | 2024-04-20 | Sashi             | L   | 0.519      | -            | -                | -                | -         |   -15.76 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           19 |     2563 | 2024-04-19 | Sashi             | W   | 0.512      | -            | -                | -                | -         |     0.54 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           18 |     2573 | 2024-04-19 | BetBoom           | W   | 0.511      | -            | -                | -                | -         |     2.43 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           17 |     3131 | 2024-03-29 | Natus Vincere     | L   | 0.372      | -            | -                | -                | -         |    -2.39 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           16 |     3239 | 2024-03-23 | Virtus.pro        | W   | 0.331      | 1.000        | 0.494 (0.163)    | -                | 1 (0.331) |     5.17 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           15 |     3254 | 2024-03-22 | FaZe              | W   | 0.325      | 1.000        | 0.663 (0.215)    | -                | 1 (0.325) |     5.02 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           14 |     3271 | 2024-03-21 | MOUZ              | L   | 0.319      | -            | -                | -                | -         |    -3.07 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           13 |     3279 | 2024-03-21 | Vitality          | W   | 0.318      | 1.000        | 0.654 (0.208)    | -                | 1 (0.318) |     6.76 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           12 |     3318 | 2024-03-19 | GamerLegion       | W   | 0.304      | -            | -                | -                | -         |     0.06 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           11 |     3326 | 2024-03-18 | HEROIC            | L   | 0.298      | -            | -                | -                | -         |    -6.44 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           10 |     3348 | 2024-03-17 | paiN              | W   | 0.293      | -            | -                | -                | -         |     1.42 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            9 |     3360 | 2024-03-17 | The MongolZ       | W   | 0.291      | -            | -                | -                | -         |     7.24 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            8 |     4034 | 2024-02-17 | BetBoom           | W   | 0.099      | -            | -                | -                | -         |     0.55 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            7 |     4068 | 2024-02-16 | FaZe              | L   | 0.091      | -            | -                | -                | -         |    -1.44 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            6 |     4098 | 2024-02-15 | Falcons           | W   | 0.084      | -            | -                | -                | -         |     0.49 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            5 |     4124 | 2024-02-14 | G2                | L   | 0.080      | -            | -                | -                | -         |    -0.44 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            4 |     4135 | 2024-02-14 | Ninjas in Pyjamas | W   | 0.078      | -            | -                | -                | -         |     0.00 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            3 |     4244 | 2024-02-05 | Natus Vincere     | L   | 0.020      | -            | -                | -                | -         |    -0.11 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            2 |     4257 | 2024-02-04 | FaZe              | L   | 0.013      | -            | -                | -                | -         |    -0.21 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            1 |     4302 | 2024-02-03 | Falcons           | W   | 0.004      | -            | -                | -                | -         |     0.03 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($249,303.62)
- Divide that value by the 5th highest value among all rosters ($331,608.80)
- The final value (0.75) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $35,000.00     | $35,000.00      |
| 2024-06-09 |      0.852 | $8,000.00      | $6,814.70       |
| 2024-05-23 |      0.738 | $250,000.00    | $184,521.99     |
| 2024-05-12 |      0.665 | $7,000.00      | $4,656.20       |
| 2024-03-31 |      0.386 | $45,000.00     | $17,370.21      |
| 2024-02-11 |      0.059 | $16,000.00     | $940.52         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
