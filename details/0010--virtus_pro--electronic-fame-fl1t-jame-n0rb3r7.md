### Roster Details<br />
Team Name: Virtus.pro<br />
Roster: electroNic, fame, FL1T, Jame, n0rb3r7<br />
Global Rank: [10](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [9]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1649.4<br />
<br />
Final Rank Value (1649.4) = Starting Rank Value (1702.1) + Head To Head Adjustments (-52.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.767[<sup>1</sup>](#table2)
- Bounty Collected: 0.640[<sup>2</sup>](#table1)
- Opponent Network: 0.290[<sup>2</sup>](#table1)
- LAN Wins: 0.846[<sup>2</sup>](#table1)

The average of these factors is 0.636<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1702.1
- 400 + ( ( 0.636 - 0.000 ) / ( 0.781 - 0.000 ) ) * 1600 = 1702.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent      | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           38 |      121 | 2024-08-01 | BIG           | L   | 1.000      | -            | -                | -                | -         |   -27.83 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           37 |      173 | 2024-07-31 | Liquid        | L   | 1.000      | -            | -                | -                | -         |   -19.07 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           36 |      542 | 2024-07-20 | G2            | L   | 1.000      | -            | -                | -                | -         |    -5.81 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           35 |      584 | 2024-07-19 | Vitality      | W   | 1.000      | 1.000        | 0.648 (0.648)    | 0.381 (0.381)    | 1 (1.000) |    22.18 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           34 |      686 | 2024-07-17 | Complexity    | W   | 1.000      | 1.000        | 0.342 (0.342)    | 0.378 (0.378)    | 1 (1.000) |    13.03 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           33 |     1038 | 2024-06-15 | Natus Vincere | L   | 0.862      | -            | -                | -                | -         |    -5.17 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           32 |     1075 | 2024-06-14 | Astralis      | W   | 0.855      | 0.729        | 0.390 (0.243)    | 0.419 (0.261)    | 1 (0.855) |    15.29 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           31 |     1112 | 2024-06-13 | Spirit        | L   | 0.848      | -            | -                | -                | -         |    -5.37 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           30 |     1152 | 2024-06-12 | Vitality      | W   | 0.841      | 0.729        | 0.648 (0.397)    | 0.381 (0.233)    | 1 (0.841) |    20.05 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           29 |     1698 | 2024-05-29 | BIG           | L   | 0.748      | -            | -                | -                | -         |   -20.60 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           28 |     1713 | 2024-05-28 | FaZe          | L   | 0.742      | -            | -                | -                | -         |    -9.46 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           27 |     1734 | 2024-05-27 | HEROIC        | W   | 0.736      | 0.624        | 0.225 (0.103)    | 0.370 (0.170)    | 1 (0.736) |     8.07 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           26 |     2026 | 2024-05-17 | Falcons       | L   | 0.666      | -            | -                | -                | -         |   -17.05 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           25 |     2065 | 2024-05-16 | MOUZ          | L   | 0.659      | -            | -                | -                | -         |    -5.06 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           24 |     2164 | 2024-05-14 | Falcons       | W   | 0.648      | 0.769        | 0.222 (0.110)    | -                | 1 (0.648) |     3.49 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           23 |     2286 | 2024-05-09 | Complexity    | L   | 0.614      | -            | -                | -                | -         |   -10.21 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           22 |     2305 | 2024-05-08 | The MongolZ   | W   | 0.608      | 0.889        | 1.000 (0.541)    | 0.719 (0.389)    | 1 (0.608) |    14.86 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           21 |     2321 | 2024-05-07 | GamerLegion   | W   | 0.601      | 0.889        | 0.173 (0.093)    | -                | 1 (0.601) |     0.92 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           20 |     2509 | 2024-04-28 | SAW           | W   | 0.540      | 0.889        | -                | 0.537 (0.258)    | 1 (0.540) |     1.06 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           19 |     2540 | 2024-04-27 | fnatic        | W   | 0.533      | 0.889        | 0.371 (0.176)    | 0.706 (0.334)    | 1 (0.533) |     5.02 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           18 |     2583 | 2024-04-25 | FaZe          | L   | 0.521      | -            | -                | -                | -         |    -7.43 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           17 |     2606 | 2024-04-24 | SAW           | W   | 0.514      | 0.889        | -                | 0.537 (0.245)    | -         |     0.87 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           16 |     2629 | 2024-04-23 | fnatic        | L   | 0.506      | -            | -                | -                | -         |   -11.37 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           15 |     2925 | 2024-04-12 | G2            | L   | 0.432      | -            | -                | -                | -         |    -2.27 | fame, FL1T, Jame, mir, n0rb3r7        |
|           14 |     3009 | 2024-04-10 | Astralis      | L   | 0.419      | -            | -                | -                | -         |    -5.98 | fame, FL1T, Jame, mir, n0rb3r7        |
|           13 |     3061 | 2024-04-08 | FlyQuest      | W   | 0.411      | -            | -                | -                | -         |     0.62 | fame, FL1T, Jame, mir, n0rb3r7        |
|           12 |     3091 | 2024-04-08 | Wildcard      | W   | 0.405      | -            | -                | -                | -         |     0.14 | fame, FL1T, Jame, mir, n0rb3r7        |
|           11 |     3391 | 2024-03-24 | G2            | L   | 0.307      | -            | -                | -                | -         |    -1.59 | fame, FL1T, Jame, mir, n0rb3r7        |
|           10 |     3405 | 2024-03-23 | Eternal Fire  | L   | 0.300      | -            | -                | -                | -         |    -4.67 | fame, FL1T, Jame, mir, n0rb3r7        |
|            9 |     3422 | 2024-03-22 | HEROIC        | W   | 0.293      | -            | -                | -                | -         |     2.98 | fame, FL1T, Jame, mir, n0rb3r7        |
|            8 |     3436 | 2024-03-21 | paiN          | W   | 0.288      | 1.000        | 0.325 (0.094)    | 0.867 (0.250)    | -         |     1.50 | fame, FL1T, Jame, mir, n0rb3r7        |
|            7 |     3446 | 2024-03-21 | Imperial      | L   | 0.287      | -            | -                | -                | -         |    -8.34 | fame, FL1T, Jame, mir, n0rb3r7        |
|            6 |     3648 | 2024-03-12 | HEROIC        | W   | 0.228      | -            | -                | -                | -         |     2.22 | fame, FL1T, Jame, mir, n0rb3r7        |
|            5 |     3664 | 2024-03-11 | Apeks         | W   | 0.222      | -            | -                | -                | -         |     0.08 | fame, FL1T, Jame, mir, n0rb3r7        |
|            4 |     3675 | 2024-03-11 | B8            | W   | 0.220      | -            | -                | -                | -         |     0.21 | fame, FL1T, Jame, mir, n0rb3r7        |
|            3 |     4257 | 2024-02-15 | Natus Vincere | W   | 0.054      | -            | -                | -                | -         |     1.40 | fame, FL1T, Jame, mir, n0rb3r7        |
|            2 |     4289 | 2024-02-14 | fnatic        | W   | 0.048      | -            | -                | -                | -         |     0.47 | fame, FL1T, Jame, mir, n0rb3r7        |
|            1 |     4308 | 2024-02-14 | SAW           | W   | 0.046      | -            | -                | -                | -         |     0.07 | fame, FL1T, Jame, mir, n0rb3r7        |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($160,390.23)
- Divide that value by the 5th highest value among all rosters ($322,333.56)
- The final value (0.50) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-04 |      1.000 | $5,000.00      | $5,000.00       |
| 2024-07-21 |      1.000 | $85,000.00     | $85,000.00      |
| 2024-06-16 |      0.867 | $40,000.00     | $34,677.78      |
| 2024-06-02 |      0.775 | $5,000.00      | $3,873.61       |
| 2024-05-12 |      0.634 | $32,000.00     | $20,284.44      |
| 2024-04-14 |      0.446 | $10,000.00     | $4,459.95       |
| 2024-03-31 |      0.355 | $20,000.00     | $7,094.44       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
