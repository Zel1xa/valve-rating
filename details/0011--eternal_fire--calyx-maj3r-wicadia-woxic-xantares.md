### Roster Details<br />
Team Name: Eternal Fire<br />
Roster: Calyx, MAJ3R, Wicadia, woxic, XANTARES<br />
Global Rank: [11](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [10]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1620.9<br />
<br />
Final Rank Value (1620.9) = Starting Rank Value (1695.1) + Head To Head Adjustments (-74.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.884[<sup>1</sup>](#table2)
- Bounty Collected: 0.560[<sup>2</sup>](#table1)
- Opponent Network: 0.310[<sup>2</sup>](#table1)
- LAN Wins: 0.771[<sup>2</sup>](#table1)

The average of these factors is 0.631<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1695.1
- 400 + ( ( 0.631 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 1695.1


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
|           37 |      321 | 2024-07-28 | The MongolZ       | L   | 1.000      | -            | -                | -                | -         |   -11.73 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           36 |      357 | 2024-07-26 | 3DMAX             | W   | 1.000      | 0.650        | 0.509 (0.331)    | 1.000 (0.650)    | 1 (1.000) |     5.98 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           35 |      402 | 2024-07-25 | AMKAL             | W   | 1.000      | 0.650        | -                | 0.463 (0.301)    | 1 (1.000) |     2.76 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           34 |      433 | 2024-07-24 | DMS               | W   | 1.000      | 0.650        | -                | 0.437 (0.284)    | 1 (1.000) |     0.55 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           33 |      442 | 2024-07-24 | Revenant          | W   | 1.000      | 0.650        | -                | 0.265 (0.172)    | 1 (1.000) |     0.48 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           32 |     1443 | 2024-06-06 | BetBoom           | L   | 0.795      | -            | -                | -                | -         |   -19.51 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           31 |     1464 | 2024-06-06 | BIG               | W   | 0.794      | 0.715        | 0.154 (0.087)    | -                | 1 (0.794) |     3.57 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           30 |     1473 | 2024-06-06 | FURIA             | L   | 0.793      | -            | -                | -                | -         |   -15.14 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           29 |     1496 | 2024-06-05 | fnatic            | L   | 0.789      | -            | -                | -                | -         |   -19.33 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           28 |     1523 | 2024-06-05 | Complexity        | L   | 0.786      | -            | -                | -                | -         |   -13.23 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           27 |     1829 | 2024-05-23 | Liquid            | W   | 0.701      | 0.769        | 0.383 (0.206)    | 0.448 (0.241)    | -         |     8.76 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           26 |     1870 | 2024-05-22 | GamerLegion       | W   | 0.695      | 0.769        | 0.173 (0.092)    | -                | -         |     1.27 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           25 |     1910 | 2024-05-21 | BetBoom           | W   | 0.688      | 0.769        | 0.248 (0.131)    | 0.526 (0.278)    | -         |     3.51 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           24 |     2067 | 2024-05-16 | SAW               | W   | 0.655      | 0.769        | -                | 0.528 (0.266)    | -         |     1.41 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           23 |     2076 | 2024-05-16 | PARIVISION        | W   | 0.654      | 0.769        | -                | 0.564 (0.284)    | -         |     0.74 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           22 |     2540 | 2024-04-27 | SAW               | L   | 0.529      | -            | -                | -                | -         |   -15.73 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           21 |     2569 | 2024-04-26 | FaZe              | L   | 0.522      | -            | -                | -                | -         |    -7.71 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           20 |     2596 | 2024-04-25 | fnatic            | W   | 0.516      | 0.889        | 0.371 (0.170)    | 0.695 (0.319)    | 1 (0.516) |     4.59 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           19 |     2616 | 2024-04-24 | Imperial          | W   | 0.509      | 0.889        | 0.233 (0.106)    | 0.673 (0.304)    | 1 (0.509) |     1.56 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           18 |     2637 | 2024-04-23 | Astralis          | L   | 0.501      | -            | -                | -                | -         |    -7.17 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           17 |     2698 | 2024-04-20 | Sashi             | L   | 0.482      | -            | -                | -                | -         |   -14.56 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           16 |     2744 | 2024-04-19 | Sashi             | W   | 0.475      | -            | -                | -                | -         |     0.58 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           15 |     2754 | 2024-04-19 | BetBoom           | W   | 0.474      | -            | -                | -                | -         |     2.34 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           14 |     3312 | 2024-03-29 | Natus Vincere     | L   | 0.335      | -            | -                | -                | -         |    -2.02 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           13 |     3420 | 2024-03-23 | Virtus.pro        | W   | 0.294      | 1.000        | 0.498 (0.146)    | -                | 1 (0.294) |     4.56 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           12 |     3435 | 2024-03-22 | FaZe              | W   | 0.288      | 1.000        | 0.626 (0.180)    | -                | 1 (0.288) |     4.23 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           11 |     3452 | 2024-03-21 | MOUZ              | L   | 0.282      | -            | -                | -                | -         |    -2.76 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           10 |     3460 | 2024-03-21 | Vitality          | W   | 0.281      | 1.000        | 0.647 (0.182)    | -                | 1 (0.281) |     6.20 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            9 |     3499 | 2024-03-19 | GamerLegion       | W   | 0.267      | -            | -                | -                | -         |     0.05 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            8 |     3507 | 2024-03-18 | HEROIC            | L   | 0.261      | -            | -                | -                | -         |    -5.68 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            7 |     3529 | 2024-03-17 | paiN              | W   | 0.256      | -            | -                | -                | -         |     1.27 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            6 |     3541 | 2024-03-17 | The MongolZ       | W   | 0.254      | -            | -                | -                | -         |     6.45 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            5 |     4215 | 2024-02-17 | BetBoom           | W   | 0.062      | -            | -                | -                | -         |     0.34 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            4 |     4249 | 2024-02-16 | FaZe              | L   | 0.054      | -            | -                | -                | -         |    -0.90 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            3 |     4279 | 2024-02-15 | Falcons           | W   | 0.047      | -            | -                | -                | -         |     0.26 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            2 |     4305 | 2024-02-14 | G2                | L   | 0.042      | -            | -                | -                | -         |    -0.20 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            1 |     4316 | 2024-02-14 | Ninjas in Pyjamas | W   | 0.041      | -            | -                | -                | -         |     0.00 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($236,857.22)
- Divide that value by the 5th highest value among all rosters ($320,603.98)
- The final value (0.74) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $35,000.00     | $35,000.00      |
| 2024-06-09 |      0.815 | $8,000.00      | $6,517.78       |
| 2024-05-23 |      0.701 | $250,000.00    | $175,243.06     |
| 2024-05-12 |      0.628 | $7,000.00      | $4,396.39       |
| 2024-03-31 |      0.349 | $45,000.00     | $15,700.00      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
