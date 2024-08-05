### Roster Details<br />
Team Name: Eternal Fire<br />
Roster: Calyx, MAJ3R, Wicadia, woxic, XANTARES<br />
Global Rank: [11](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [10]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1621.3<br />
<br />
Final Rank Value (1621.3) = Starting Rank Value (1696.5) + Head To Head Adjustments (-75.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.885[<sup>1</sup>](#table2)
- Bounty Collected: 0.562[<sup>2</sup>](#table1)
- Opponent Network: 0.316[<sup>2</sup>](#table1)
- LAN Wins: 0.772[<sup>2</sup>](#table1)

The average of these factors is 0.634<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1696.5
- 400 + ( ( 0.634 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 1696.5


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
|           37 |      293 | 2024-07-28 | The MongolZ       | L   | 1.000      | -            | -                | -                | -         |   -11.82 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           36 |      329 | 2024-07-26 | 3DMAX             | W   | 1.000      | 0.650        | 0.507 (0.330)    | 1.000 (0.650)    | 1 (1.000) |     5.79 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           35 |      374 | 2024-07-25 | AMKAL             | W   | 1.000      | 0.650        | -                | 0.474 (0.308)    | 1 (1.000) |     2.74 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           34 |      405 | 2024-07-24 | DMS               | W   | 1.000      | 0.650        | -                | 0.446 (0.290)    | 1 (1.000) |     0.54 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           33 |      414 | 2024-07-24 | Revenant          | W   | 1.000      | -            | -                | -                | 1 (1.000) |     0.47 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           32 |     1415 | 2024-06-06 | BetBoom           | L   | 0.804      | -            | -                | -                | -         |   -19.72 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           31 |     1436 | 2024-06-06 | BIG               | W   | 0.803      | 0.715        | 0.155 (0.089)    | 0.303 (0.174)    | 1 (0.803) |     3.62 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           30 |     1445 | 2024-06-06 | FURIA             | L   | 0.802      | -            | -                | -                | -         |   -15.43 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           29 |     1468 | 2024-06-05 | fnatic            | L   | 0.798      | -            | -                | -                | -         |   -19.61 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           28 |     1495 | 2024-06-05 | Complexity        | L   | 0.795      | -            | -                | -                | -         |   -13.35 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           27 |     1801 | 2024-05-23 | Liquid            | W   | 0.710      | 0.769        | 0.384 (0.210)    | 0.459 (0.250)    | -         |     8.86 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           26 |     1842 | 2024-05-22 | GamerLegion       | W   | 0.704      | 0.769        | 0.173 (0.094)    | -                | -         |     1.30 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           25 |     1882 | 2024-05-21 | BetBoom           | W   | 0.697      | 0.769        | 0.250 (0.134)    | 0.540 (0.289)    | -         |     3.55 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           24 |     2039 | 2024-05-16 | SAW               | W   | 0.665      | 0.769        | -                | 0.539 (0.275)    | -         |     1.45 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           23 |     2048 | 2024-05-16 | PARIVISION        | W   | 0.663      | 0.769        | -                | 0.534 (0.272)    | -         |     0.72 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           22 |     2512 | 2024-04-27 | SAW               | L   | 0.538      | -            | -                | -                | -         |   -15.99 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           21 |     2541 | 2024-04-26 | FaZe              | L   | 0.531      | -            | -                | -                | -         |    -7.74 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           20 |     2568 | 2024-04-25 | fnatic            | W   | 0.525      | 0.889        | 0.371 (0.173)    | 0.708 (0.330)    | 1 (0.525) |     4.65 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           19 |     2588 | 2024-04-24 | Imperial          | W   | 0.518      | 0.889        | 0.236 (0.109)    | 0.685 (0.315)    | 1 (0.518) |     1.62 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           18 |     2609 | 2024-04-23 | Astralis          | L   | 0.511      | -            | -                | -                | -         |    -7.27 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           17 |     2670 | 2024-04-20 | Sashi             | L   | 0.491      | -            | -                | -                | -         |   -14.84 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           16 |     2716 | 2024-04-19 | Sashi             | W   | 0.485      | -            | -                | -                | -         |     0.58 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           15 |     2726 | 2024-04-19 | BetBoom           | W   | 0.483      | -            | -                | -                | -         |     2.40 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           14 |     3284 | 2024-03-29 | Natus Vincere     | L   | 0.344      | -            | -                | -                | -         |    -2.09 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           13 |     3392 | 2024-03-23 | Virtus.pro        | W   | 0.303      | 1.000        | 0.497 (0.151)    | -                | 1 (0.303) |     4.72 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           12 |     3407 | 2024-03-22 | FaZe              | W   | 0.297      | 1.000        | 0.635 (0.189)    | -                | 1 (0.297) |     4.42 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           11 |     3424 | 2024-03-21 | MOUZ              | L   | 0.291      | -            | -                | -                | -         |    -2.86 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           10 |     3432 | 2024-03-21 | Vitality          | W   | 0.290      | 1.000        | 0.648 (0.188)    | -                | 1 (0.290) |     6.40 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            9 |     3471 | 2024-03-19 | GamerLegion       | W   | 0.276      | -            | -                | -                | -         |     0.05 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            8 |     3479 | 2024-03-18 | HEROIC            | L   | 0.270      | -            | -                | -                | -         |    -5.86 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            7 |     3501 | 2024-03-17 | paiN              | W   | 0.265      | -            | -                | -                | -         |     1.33 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            6 |     3513 | 2024-03-17 | The MongolZ       | W   | 0.263      | -            | -                | -                | -         |     6.67 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            5 |     4187 | 2024-02-17 | BetBoom           | W   | 0.071      | -            | -                | -                | -         |     0.40 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            4 |     4221 | 2024-02-16 | FaZe              | L   | 0.064      | -            | -                | -                | -         |    -1.04 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            3 |     4251 | 2024-02-15 | Falcons           | W   | 0.056      | -            | -                | -                | -         |     0.31 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            2 |     4277 | 2024-02-14 | G2                | L   | 0.052      | -            | -                | -                | -         |    -0.25 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            1 |     4288 | 2024-02-14 | Ninjas in Pyjamas | W   | 0.050      | -            | -                | -                | -         |     0.00 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($239,698.89)
- Divide that value by the 5th highest value among all rosters ($323,321.90)
- The final value (0.74) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $35,000.00     | $35,000.00      |
| 2024-06-09 |      0.824 | $8,000.00      | $6,591.11       |
| 2024-05-23 |      0.710 | $250,000.00    | $177,534.72     |
| 2024-05-12 |      0.637 | $7,000.00      | $4,460.56       |
| 2024-03-31 |      0.358 | $45,000.00     | $16,112.50      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
