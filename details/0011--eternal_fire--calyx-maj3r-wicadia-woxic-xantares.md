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
Final Rank Value (1621.2) = Starting Rank Value (1697.6) + Head To Head Adjustments (-76.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.885[<sup>1</sup>](#table2)
- Bounty Collected: 0.563[<sup>2</sup>](#table1)
- Opponent Network: 0.317[<sup>2</sup>](#table1)
- LAN Wins: 0.773[<sup>2</sup>](#table1)

The average of these factors is 0.635<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1697.6
- 400 + ( ( 0.635 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 1697.6


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
|           37 |      265 | 2024-07-28 | The MongolZ       | L   | 1.000      | -            | -                | -                | -         |   -11.89 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           36 |      301 | 2024-07-26 | 3DMAX             | W   | 1.000      | 0.650        | 0.506 (0.329)    | 1.000 (0.650)    | 1 (1.000) |     5.73 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           35 |      346 | 2024-07-25 | AMKAL             | W   | 1.000      | 0.650        | -                | 0.475 (0.309)    | 1 (1.000) |     2.75 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           34 |      377 | 2024-07-24 | DMS               | W   | 1.000      | 0.650        | -                | 0.446 (0.290)    | 1 (1.000) |     0.53 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           33 |      386 | 2024-07-24 | Revenant          | W   | 1.000      | -            | -                | -                | 1 (1.000) |     0.47 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           32 |     1387 | 2024-06-06 | BetBoom           | L   | 0.808      | -            | -                | -                | -         |   -19.78 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           31 |     1408 | 2024-06-06 | BIG               | W   | 0.806      | 0.715        | 0.155 (0.089)    | 0.304 (0.175)    | 1 (0.806) |     3.64 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           30 |     1417 | 2024-06-06 | FURIA             | L   | 0.805      | -            | -                | -                | -         |   -15.56 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           29 |     1440 | 2024-06-05 | fnatic            | L   | 0.801      | -            | -                | -                | -         |   -19.73 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           28 |     1467 | 2024-06-05 | Complexity        | L   | 0.799      | -            | -                | -                | -         |   -13.71 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           27 |     1773 | 2024-05-23 | Liquid            | W   | 0.714      | 0.769        | 0.384 (0.211)    | 0.460 (0.252)    | -         |     8.80 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           26 |     1814 | 2024-05-22 | GamerLegion       | W   | 0.707      | 0.769        | 0.174 (0.094)    | -                | -         |     1.30 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           25 |     1854 | 2024-05-21 | BetBoom           | W   | 0.701      | 0.769        | 0.251 (0.135)    | 0.541 (0.292)    | -         |     3.58 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           24 |     2011 | 2024-05-16 | SAW               | W   | 0.668      | 0.769        | -                | 0.540 (0.277)    | -         |     1.46 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           23 |     2020 | 2024-05-16 | PARIVISION        | W   | 0.667      | 0.769        | -                | 0.534 (0.274)    | -         |     0.71 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           22 |     2484 | 2024-04-27 | SAW               | L   | 0.541      | -            | -                | -                | -         |   -16.09 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           21 |     2513 | 2024-04-26 | FaZe              | L   | 0.534      | -            | -                | -                | -         |    -7.80 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           20 |     2540 | 2024-04-25 | fnatic            | W   | 0.528      | 0.889        | 0.371 (0.174)    | 0.708 (0.333)    | 1 (0.528) |     4.64 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           19 |     2560 | 2024-04-24 | Imperial          | W   | 0.521      | 0.889        | 0.237 (0.110)    | 0.685 (0.317)    | 1 (0.521) |     1.64 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           18 |     2581 | 2024-04-23 | Astralis          | L   | 0.514      | -            | -                | -                | -         |    -7.34 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           17 |     2642 | 2024-04-20 | Sashi             | L   | 0.495      | -            | -                | -                | -         |   -14.95 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           16 |     2688 | 2024-04-19 | Sashi             | W   | 0.488      | -            | -                | -                | -         |     0.58 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           15 |     2698 | 2024-04-19 | BetBoom           | W   | 0.487      | -            | -                | -                | -         |     2.41 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           14 |     3256 | 2024-03-29 | Natus Vincere     | L   | 0.348      | -            | -                | -                | -         |    -2.14 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           13 |     3364 | 2024-03-23 | Virtus.pro        | W   | 0.307      | 1.000        | 0.497 (0.152)    | -                | 1 (0.307) |     4.76 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           12 |     3379 | 2024-03-22 | FaZe              | W   | 0.300      | 1.000        | 0.639 (0.192)    | -                | 1 (0.300) |     4.47 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           11 |     3396 | 2024-03-21 | MOUZ              | L   | 0.295      | -            | -                | -                | -         |    -2.90 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           10 |     3404 | 2024-03-21 | Vitality          | W   | 0.294      | 1.000        | 0.649 (0.190)    | -                | 1 (0.294) |     6.47 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            9 |     3443 | 2024-03-19 | GamerLegion       | W   | 0.280      | -            | -                | -                | -         |     0.06 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            8 |     3451 | 2024-03-18 | HEROIC            | L   | 0.274      | -            | -                | -                | -         |    -5.95 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            7 |     3473 | 2024-03-17 | paiN              | W   | 0.268      | -            | -                | -                | -         |     1.36 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            6 |     3485 | 2024-03-17 | The MongolZ       | W   | 0.267      | -            | -                | -                | -         |     6.75 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            5 |     4159 | 2024-02-17 | BetBoom           | W   | 0.074      | -            | -                | -                | -         |     0.41 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            4 |     4193 | 2024-02-16 | FaZe              | L   | 0.067      | -            | -                | -                | -         |    -1.09 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            3 |     4223 | 2024-02-15 | Falcons           | W   | 0.060      | -            | -                | -                | -         |     0.33 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            2 |     4249 | 2024-02-14 | G2                | L   | 0.055      | -            | -                | -                | -         |    -0.27 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            1 |     4260 | 2024-02-14 | Ninjas in Pyjamas | W   | 0.053      | -            | -                | -                | -         |     0.00 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($240,768.10)
- Divide that value by the 5th highest value among all rosters ($324,344.55)
- The final value (0.74) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-28 |      1.000 | $35,000.00     | $35,000.00      |
| 2024-06-09 |      0.827 | $8,000.00      | $6,618.70       |
| 2024-05-23 |      0.714 | $250,000.00    | $178,396.99     |
| 2024-05-12 |      0.641 | $7,000.00      | $4,484.70       |
| 2024-03-31 |      0.362 | $45,000.00     | $16,267.71      |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
