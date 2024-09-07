### Roster Details<br />
Team Name: Eternal Fire<br />
Roster: Calyx, MAJ3R, Wicadia, woxic, XANTARES<br />
Global Rank: [6](../../standings_global_2024_09_07.md)<br />
<br />
Region: [Europe]( ../../standings_europe_2024_09_07.md)<br />
Regional Rank: [6]( ../../standings_europe_2024_09_07.md)<br />
<br />
Final Rank Value:  1762.1<br />
<br />
Final Rank Value (1762.1) = Starting Rank Value (1886.7) + Head To Head Adjustments (-124.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.987[<sup>1</sup>](#table2)
- Bounty Collected: 0.618[<sup>2</sup>](#table1)
- Opponent Network: 0.436[<sup>2</sup>](#table1)
- LAN Wins: 1.000[<sup>2</sup>](#table1)

The average of these factors is 0.760<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1886.7
- 400 + ( ( 0.760 - 0.000 ) / ( 0.818 - 0.000 ) ) * 1600 = 1886.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent      | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                 |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           49 |       88 | 2024-09-04 | Sangal        | W   | 1.000      | 0.889        | 0.248 (0.221)    | 0.869 (0.772)    | 1 (1.000) |     2.99 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           48 |      127 | 2024-09-03 | FlyQuest      | W   | 1.000      | 0.889        | -                | 0.345 (0.306)    | 1 (1.000) |     0.61 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           47 |      170 | 2024-09-01 | Spirit        | L   | 1.000      | -            | -                | -                | -         |    -7.84 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           46 |      182 | 2024-08-31 | MOUZ          | W   | 1.000      | 0.769        | 1.000 (0.769)    | 0.394 (0.303)    | 1 (1.000) |    20.84 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           45 |      187 | 2024-08-31 | paiN          | W   | 1.000      | 0.769        | 0.420 (0.322)    | 0.965 (0.742)    | 1 (1.000) |     9.89 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           44 |      207 | 2024-08-30 | FURIA         | W   | 1.000      | 0.769        | 0.319 (0.245)    | 0.530 (0.407)    | 1 (1.000) |     9.42 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           43 |      244 | 2024-08-29 | HEROIC        | W   | 1.000      | 0.769        | 0.206 (0.158)    | 0.401 (0.308)    | 1 (1.000) |     4.07 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           42 |      275 | 2024-08-28 | MOUZ          | L   | 1.000      | -            | -                | -                | -         |    -9.03 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           41 |      340 | 2024-08-27 | Falcons       | W   | 1.000      | -            | -                | -                | -         |     7.79 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           40 |      347 | 2024-08-27 | FURIA         | L   | 1.000      | -            | -                | -                | -         |   -22.78 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           39 |      396 | 2024-08-26 | 9 Pandas      | W   | 1.000      | -            | -                | -                | 1 (1.000) |     1.12 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           38 |      413 | 2024-08-26 | Cloud9        | W   | 1.000      | -            | -                | -                | -         |     0.65 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           37 |      429 | 2024-08-26 | B8            | W   | 1.000      | -            | -                | -                | -         |     1.01 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           36 |      473 | 2024-08-25 | Aurora        | W   | 1.000      | -            | -                | -                | 1 (1.000) |     2.01 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           35 |      966 | 2024-08-09 | The MongolZ   | L   | 1.000      | -            | -                | -                | -         |   -20.13 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           34 |      990 | 2024-08-08 | Complexity    | L   | 1.000      | -            | -                | -                | -         |   -25.97 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           33 |     1036 | 2024-08-07 | Falcons       | W   | 0.995      | -            | -                | -                | 1 (0.995) |     4.94 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           32 |     1421 | 2024-07-28 | The MongolZ   | L   | 0.926      | -            | -                | -                | -         |   -19.23 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           31 |     1457 | 2024-07-26 | 3DMAX         | W   | 0.915      | 0.650        | 0.470 (0.280)    | 0.945 (0.562)    | 1 (0.915) |     3.40 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           30 |     1502 | 2024-07-25 | AMKAL         | W   | 0.907      | -            | -                | -                | -         |     0.77 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           29 |     1533 | 2024-07-24 | DMS           | W   | 0.901      | 0.650        | -                | 0.502 (0.295)    | -         |     0.16 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           28 |     1542 | 2024-07-24 | Revenant      | W   | 0.900      | 0.650        | -                | 0.683 (0.400)    | -         |     0.22 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           27 |     2546 | 2024-06-06 | BetBoom       | L   | 0.582      | -            | -                | -                | -         |   -17.43 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           26 |     2567 | 2024-06-06 | BIG           | W   | 0.581      | -            | -                | -                | -         |     0.65 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           25 |     2576 | 2024-06-06 | FURIA         | L   | 0.580      | -            | -                | -                | -         |   -14.76 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           24 |     2599 | 2024-06-05 | fnatic        | L   | 0.576      | -            | -                | -                | -         |   -17.29 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           23 |     2626 | 2024-06-05 | Complexity    | L   | 0.573      | -            | -                | -                | -         |   -15.33 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           22 |     2932 | 2024-05-23 | Liquid        | W   | 0.488      | 0.769        | 0.370 (0.139)    | -                | -         |     2.79 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           21 |     2973 | 2024-05-22 | GamerLegion   | W   | 0.482      | -            | -                | -                | -         |     0.20 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           20 |     3013 | 2024-05-21 | BetBoom       | W   | 0.475      | 0.769        | 0.230 (0.084)    | -                | -         |     0.49 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           19 |     3170 | 2024-05-16 | SAW           | W   | 0.443      | 0.769        | 0.328 (0.111)    | 0.771 (0.262)    | -         |     1.91 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           18 |     3179 | 2024-05-16 | PARIVISION    | W   | 0.441      | -            | -                | -                | -         |     0.17 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           17 |     3643 | 2024-04-27 | SAW           | L   | 0.316      | -            | -                | -                | -         |    -8.67 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           16 |     3672 | 2024-04-26 | FaZe          | L   | 0.309      | -            | -                | -                | -         |    -6.17 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           15 |     3699 | 2024-04-25 | fnatic        | W   | 0.303      | 0.889        | 0.293 (0.079)    | -                | -         |     0.45 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           14 |     3719 | 2024-04-24 | Imperial      | W   | 0.296      | -            | -                | -                | -         |     0.11 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           13 |     3740 | 2024-04-23 | Astralis      | L   | 0.288      | -            | -                | -                | -         |    -7.91 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           12 |     3801 | 2024-04-20 | Sashi         | L   | 0.269      | -            | -                | -                | -         |    -8.39 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           11 |     3847 | 2024-04-19 | Sashi         | W   | 0.262      | -            | -                | -                | -         |     0.09 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|           10 |     3857 | 2024-04-19 | BetBoom       | W   | 0.261      | -            | -                | -                | -         |     0.22 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            9 |     4415 | 2024-03-29 | Natus Vincere | L   | 0.122      | -            | -                | -                | -         |    -1.39 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            8 |     4523 | 2024-03-23 | Virtus.pro    | W   | 0.081      | -            | -                | -                | -         |     0.31 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            7 |     4538 | 2024-03-22 | FaZe          | W   | 0.075      | -            | -                | -                | -         |     0.80 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            6 |     4555 | 2024-03-21 | MOUZ          | L   | 0.069      | -            | -                | -                | -         |    -1.11 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            5 |     4563 | 2024-03-21 | Vitality      | W   | 0.068      | -            | -                | -                | -         |     1.22 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            4 |     4602 | 2024-03-19 | GamerLegion   | W   | 0.054      | -            | -                | -                | -         |     0.00 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            3 |     4610 | 2024-03-18 | HEROIC        | L   | 0.048      | -            | -                | -                | -         |    -1.44 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            2 |     4632 | 2024-03-17 | paiN          | W   | 0.043      | -            | -                | -                | -         |     0.35 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |
|            1 |     4644 | 2024-03-17 | The MongolZ   | W   | 0.041      | -            | -                | -                | -         |     0.56 | Calyx, MAJ3R, Wicadia, woxic, XANTARES |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($297,859.31)
- Divide that value by the 5th highest value among all rosters ($307,186.12)
- The final value (0.97) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-09-01 |      1.000 | $125,000.00    | $125,000.00     |
| 2024-08-09 |      1.000 | $4,500.00      | $4,500.00       |
| 2024-07-28 |      0.929 | $35,000.00     | $32,506.25      |
| 2024-06-09 |      0.602 | $8,000.00      | $4,814.44       |
| 2024-05-23 |      0.488 | $250,000.00    | $122,013.89     |
| 2024-05-12 |      0.415 | $7,000.00      | $2,905.97       |
| 2024-03-31 |      0.136 | $45,000.00     | $6,118.75       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
