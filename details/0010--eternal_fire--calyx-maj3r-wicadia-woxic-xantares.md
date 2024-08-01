### Roster Details<br />
Team Name: Eternal Fire<br />
Roster: Calyx, MAJ3R, Wicadia, woxic, XANTARES<br />
Global Rank: [10](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [9]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1624.6<br />
<br />
Final Rank Value (1624.6) = Starting Rank Value (1715.0) + Head To Head Adjustments (-90.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.892[<sup>1</sup>](#table2)
- Bounty Collected: 0.560[<sup>2</sup>](#table1)
- Opponent Network: 0.313[<sup>2</sup>](#table1)
- LAN Wins: 0.793[<sup>2</sup>](#table1)

The average of these factors is 0.639<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1715.0
- 400 + ( ( 0.639 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1715.0


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
|           39 |      173 | 2024-07-28 | The MongolZ       | L   | 1.000      | -            | -                | -                | -         |   -12.21 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           38 |      209 | 2024-07-26 | 3DMAX             | W   | 1.000      | 0.650        | 0.505 (0.329)    | 1.000 (0.650)    | 1 (1.000) |     5.50 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           37 |      254 | 2024-07-25 | AMKAL             | W   | 1.000      | 0.650        | 0.132 (0.086)    | 0.482 (0.313)    | 1 (1.000) |     2.68 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           36 |      285 | 2024-07-24 | DMS               | W   | 1.000      | 0.650        | -                | 0.447 (0.291)    | 1 (1.000) |     0.47 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           35 |      294 | 2024-07-24 | Revenant          | W   | 1.000      | -            | -                | -                | 1 (1.000) |     0.40 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           34 |     1314 | 2024-06-06 | BetBoom           | L   | 0.826      | -            | -                | -                | -         |   -20.37 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           33 |     1336 | 2024-06-06 | BIG               | W   | 0.825      | 0.715        | -                | 0.299 (0.176)    | 1 (0.825) |     2.78 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           32 |     1345 | 2024-06-06 | FURIA             | L   | 0.824      | -            | -                | -                | -         |   -16.03 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           31 |     1369 | 2024-06-05 | fnatic            | L   | 0.820      | -            | -                | -                | -         |   -22.97 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           30 |     1397 | 2024-06-05 | Complexity        | L   | 0.818      | -            | -                | -                | -         |   -14.51 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           29 |     1706 | 2024-05-23 | Liquid            | W   | 0.732      | 0.769        | 0.321 (0.181)    | 0.467 (0.263)    | -         |     7.15 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           28 |     1747 | 2024-05-22 | GamerLegion       | W   | 0.726      | 0.769        | 0.176 (0.098)    | -                | -         |     1.28 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           27 |     1802 | 2024-05-21 | BetBoom           | W   | 0.720      | 0.769        | 0.257 (0.142)    | 0.551 (0.305)    | -         |     3.57 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           26 |     1970 | 2024-05-16 | SAW               | W   | 0.687      | 0.769        | -                | 0.544 (0.287)    | -         |     1.51 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           25 |     1979 | 2024-05-16 | PARIVISION        | W   | 0.685      | 0.769        | -                | 0.451 (0.238)    | -         |     0.70 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           24 |     2457 | 2024-04-27 | SAW               | L   | 0.560      | -            | -                | -                | -         |   -16.64 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           23 |     2487 | 2024-04-26 | FaZe              | L   | 0.553      | -            | -                | -                | -         |    -7.80 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           22 |     2513 | 2024-04-25 | fnatic            | W   | 0.547      | 0.889        | 0.292 (0.142)    | 0.529 (0.257)    | 1 (0.547) |     2.03 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           21 |     2533 | 2024-04-24 | Imperial          | W   | 0.540      | 0.889        | 0.239 (0.115)    | 0.719 (0.345)    | 1 (0.540) |     1.56 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           20 |     2556 | 2024-04-23 | Astralis          | L   | 0.533      | -            | -                | -                | -         |    -8.91 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           19 |     2621 | 2024-04-20 | Sashi             | L   | 0.513      | -            | -                | -                | -         |   -15.56 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           18 |     2668 | 2024-04-19 | Sashi             | W   | 0.507      | -            | -                | -                | -         |     0.56 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           17 |     2678 | 2024-04-19 | BetBoom           | W   | 0.506      | -            | -                | -                | -         |     2.39 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           16 |     3248 | 2024-03-29 | Natus Vincere     | L   | 0.366      | -            | -                | -                | -         |    -2.31 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           15 |     3361 | 2024-03-23 | Virtus.pro        | W   | 0.325      | 1.000        | 0.484 (0.157)    | -                | 1 (0.325) |     4.94 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           14 |     3376 | 2024-03-22 | FaZe              | W   | 0.319      | 1.000        | 0.637 (0.203)    | -                | 1 (0.319) |     4.94 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           13 |     3393 | 2024-03-21 | MOUZ              | L   | 0.313      | -            | -                | -                | -         |    -2.99 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           12 |     3401 | 2024-03-21 | Vitality          | W   | 0.312      | 1.000        | 0.590 (0.184)    | -                | 1 (0.312) |     6.54 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           11 |     3440 | 2024-03-19 | GamerLegion       | W   | 0.299      | -            | -                | -                | -         |     0.06 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           10 |     3448 | 2024-03-18 | HEROIC            | L   | 0.292      | -            | -                | -                | -         |    -6.40 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            9 |     3470 | 2024-03-17 | paiN              | W   | 0.287      | -            | -                | -                | -         |     1.05 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            8 |     3482 | 2024-03-17 | The MongolZ       | W   | 0.285      | -            | -                | -                | -         |     7.13 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            7 |     4176 | 2024-02-17 | BetBoom           | W   | 0.093      | -            | -                | -                | -         |     0.52 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            6 |     4211 | 2024-02-16 | FaZe              | L   | 0.086      | -            | -                | -                | -         |    -1.35 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            5 |     4241 | 2024-02-15 | Falcons           | W   | 0.078      | -            | -                | -                | -         |     0.44 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            4 |     4267 | 2024-02-14 | G2                | L   | 0.074      | -            | -                | -                | -         |    -0.39 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            3 |     4278 | 2024-02-14 | Ninjas in Pyjamas | W   | 0.072      | -            | -                | -                | -         |     0.00 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            2 |     4397 | 2024-02-05 | Natus Vincere     | L   | 0.014      | -            | -                | -                | -         |    -0.08 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            1 |     4410 | 2024-02-04 | FaZe              | L   | 0.007      | -            | -                | -                | -         |    -0.12 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($247,436.67)
- Divide that value by the 5th highest value among all rosters ($327,030.46)
- The final value (0.76) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $35,000.00     | $35,000.00      |
| 2024-06-09 |      0.846 | $8,000.00      | $6,768.89       |
| 2024-05-23 |      0.732 | $250,000.00    | $183,090.28     |
| 2024-05-12 |      0.659 | $7,000.00      | $4,616.11       |
| 2024-03-31 |      0.380 | $45,000.00     | $17,112.50      |
| 2024-02-11 |      0.053 | $16,000.00     | $848.89         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
