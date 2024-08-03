### Roster Details<br />
Team Name: Eternal Fire<br />
Roster: Calyx, MAJ3R, Wicadia, woxic, XANTARES<br />
Global Rank: [10](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [9]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1615.0<br />
<br />
Final Rank Value (1615.0) = Starting Rank Value (1700.2) + Head To Head Adjustments (-85.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.887[<sup>1</sup>](#table2)
- Bounty Collected: 0.558[<sup>2</sup>](#table1)
- Opponent Network: 0.323[<sup>2</sup>](#table1)
- LAN Wins: 0.774[<sup>2</sup>](#table1)

The average of these factors is 0.635<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1700.2
- 400 + ( ( 0.635 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 1700.2


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
|           38 |      231 | 2024-07-28 | The MongolZ       | L   | 1.000      | -            | -                | -                | -         |   -11.77 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           37 |      267 | 2024-07-26 | 3DMAX             | W   | 1.000      | 0.650        | 0.504 (0.328)    | 1.000 (0.650)    | 1 (1.000) |     5.73 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           36 |      312 | 2024-07-25 | AMKAL             | W   | 1.000      | 0.650        | -                | 0.494 (0.321)    | 1 (1.000) |     2.80 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           35 |      343 | 2024-07-24 | DMS               | W   | 1.000      | 0.650        | -                | 0.462 (0.300)    | 1 (1.000) |     0.57 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           34 |      351 | 2024-07-24 | Revenant          | W   | 1.000      | -            | -                | -                | 1 (1.000) |     0.47 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           33 |     1315 | 2024-06-06 | BetBoom           | L   | 0.813      | -            | -                | -                | -         |   -19.89 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           32 |     1336 | 2024-06-06 | BIG               | W   | 0.812      | 0.715        | 0.156 (0.090)    | 0.316 (0.183)    | 1 (0.812) |     3.83 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           31 |     1345 | 2024-06-06 | FURIA             | L   | 0.811      | -            | -                | -                | -         |   -15.67 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           30 |     1368 | 2024-06-05 | fnatic            | L   | 0.807      | -            | -                | -                | -         |   -22.48 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           29 |     1395 | 2024-06-05 | Complexity        | L   | 0.804      | -            | -                | -                | -         |   -13.65 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           28 |     1697 | 2024-05-23 | Liquid            | W   | 0.719      | 0.769        | 0.316 (0.175)    | 0.478 (0.264)    | -         |     6.92 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           27 |     1738 | 2024-05-22 | GamerLegion       | W   | 0.713      | 0.769        | 0.174 (0.095)    | -                | -         |     1.30 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           26 |     1778 | 2024-05-21 | BetBoom           | W   | 0.706      | 0.769        | 0.252 (0.137)    | 0.563 (0.306)    | -         |     3.62 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           25 |     1934 | 2024-05-16 | SAW               | W   | 0.674      | 0.769        | -                | 0.560 (0.290)    | -         |     1.50 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           24 |     1943 | 2024-05-16 | PARIVISION        | W   | 0.672      | 0.769        | -                | 0.553 (0.286)    | -         |     0.72 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           23 |     2406 | 2024-04-27 | SAW               | L   | 0.547      | -            | -                | -                | -         |   -16.23 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           22 |     2435 | 2024-04-26 | FaZe              | L   | 0.540      | -            | -                | -                | -         |    -7.75 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           21 |     2461 | 2024-04-25 | fnatic            | W   | 0.534      | 0.889        | 0.290 (0.137)    | 0.627 (0.297)    | 1 (0.534) |     2.07 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           20 |     2481 | 2024-04-24 | Imperial          | W   | 0.527      | 0.889        | 0.234 (0.110)    | 0.708 (0.332)    | 1 (0.527) |     1.42 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           19 |     2502 | 2024-04-23 | Astralis          | L   | 0.520      | -            | -                | -                | -         |    -8.26 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           18 |     2563 | 2024-04-20 | Sashi             | L   | 0.500      | -            | -                | -                | -         |   -15.10 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           17 |     2609 | 2024-04-19 | Sashi             | W   | 0.493      | -            | -                | -                | -         |     0.60 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           16 |     2619 | 2024-04-19 | BetBoom           | W   | 0.492      | -            | -                | -                | -         |     2.41 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           15 |     3177 | 2024-03-29 | Natus Vincere     | L   | 0.353      | -            | -                | -                | -         |    -2.15 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           14 |     3281 | 2024-03-23 | Virtus.pro        | W   | 0.312      | 1.000        | 0.496 (0.155)    | -                | 1 (0.312) |     4.84 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           13 |     3295 | 2024-03-22 | FaZe              | W   | 0.306      | 1.000        | 0.644 (0.197)    | -                | 1 (0.306) |     4.65 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           12 |     3312 | 2024-03-21 | MOUZ              | L   | 0.300      | -            | -                | -                | -         |    -3.67 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           11 |     3320 | 2024-03-21 | Vitality          | W   | 0.299      | 1.000        | 0.650 (0.194)    | -                | 1 (0.299) |     6.60 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           10 |     3359 | 2024-03-19 | GamerLegion       | W   | 0.285      | -            | -                | -                | -         |     0.06 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            9 |     3367 | 2024-03-18 | HEROIC            | L   | 0.279      | -            | -                | -                | -         |    -6.06 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            8 |     3389 | 2024-03-17 | paiN              | W   | 0.274      | -            | -                | -                | -         |     1.09 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            7 |     3401 | 2024-03-17 | The MongolZ       | W   | 0.272      | -            | -                | -                | -         |     6.88 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            6 |     4071 | 2024-02-17 | BetBoom           | W   | 0.080      | -            | -                | -                | -         |     0.45 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            5 |     4105 | 2024-02-16 | FaZe              | L   | 0.072      | -            | -                | -                | -         |    -1.16 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            4 |     4135 | 2024-02-15 | Falcons           | W   | 0.065      | -            | -                | -                | -         |     0.37 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            3 |     4161 | 2024-02-14 | G2                | L   | 0.061      | -            | -                | -                | -         |    -0.30 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            2 |     4172 | 2024-02-14 | Ninjas in Pyjamas | W   | 0.059      | -            | -                | -                | -         |     0.00 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            1 |     4281 | 2024-02-05 | Natus Vincere     | L   | 0.001      | -            | -                | -                | -         |    -0.00 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($243,105.09)
- Divide that value by the 5th highest value among all rosters ($325,971.18)
- The final value (0.75) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $35,000.00     | $35,000.00      |
| 2024-06-09 |      0.833 | $8,000.00      | $6,662.59       |
| 2024-05-23 |      0.719 | $250,000.00    | $179,768.52     |
| 2024-05-12 |      0.646 | $7,000.00      | $4,523.10       |
| 2024-03-31 |      0.367 | $45,000.00     | $16,514.58      |
| 2024-02-11 |      0.040 | $16,000.00     | $636.30         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
