### Roster Details<br />
Team Name: Virtus.pro<br />
Roster: electroNic, fame, FL1T, Jame, n0rb3r7<br />
Global Rank: [10](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [9]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1648.5<br />
<br />
Final Rank Value (1648.5) = Starting Rank Value (1701.0) + Head To Head Adjustments (-52.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.768[<sup>1</sup>](#table2)
- Bounty Collected: 0.640[<sup>2</sup>](#table1)
- Opponent Network: 0.285[<sup>2</sup>](#table1)
- LAN Wins: 0.845[<sup>2</sup>](#table1)

The average of these factors is 0.634<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1701.0
- 400 + ( ( 0.634 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 1701.0


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
|           38 |      132 | 2024-08-01 | BIG           | L   | 1.000      | -            | -                | -                | -         |   -27.82 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           37 |      184 | 2024-07-31 | Liquid        | L   | 1.000      | -            | -                | -                | -         |   -19.04 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           36 |      553 | 2024-07-20 | G2            | L   | 1.000      | -            | -                | -                | -         |    -5.78 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           35 |      595 | 2024-07-19 | Vitality      | W   | 1.000      | 1.000        | 0.647 (0.647)    | 0.376 (0.376)    | 1 (1.000) |    22.18 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           34 |      697 | 2024-07-17 | Complexity    | W   | 1.000      | 1.000        | 0.342 (0.342)    | 0.373 (0.373)    | 1 (1.000) |    13.04 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           33 |     1049 | 2024-06-15 | Natus Vincere | L   | 0.858      | -            | -                | -                | -         |    -5.13 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           32 |     1086 | 2024-06-14 | Astralis      | W   | 0.852      | 0.729        | 0.389 (0.242)    | 0.413 (0.256)    | 1 (0.852) |    15.24 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           31 |     1123 | 2024-06-13 | Spirit        | L   | 0.845      | -            | -                | -                | -         |    -5.33 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           30 |     1163 | 2024-06-12 | Vitality      | W   | 0.837      | 0.729        | 0.647 (0.395)    | 0.376 (0.229)    | 1 (0.837) |    19.98 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           29 |     1709 | 2024-05-29 | BIG           | L   | 0.744      | -            | -                | -                | -         |   -20.50 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           28 |     1724 | 2024-05-28 | FaZe          | L   | 0.739      | -            | -                | -                | -         |    -9.46 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           27 |     1745 | 2024-05-27 | HEROIC        | W   | 0.732      | 0.624        | 0.225 (0.103)    | 0.364 (0.166)    | 1 (0.732) |     8.02 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           26 |     2037 | 2024-05-17 | Falcons       | L   | 0.663      | -            | -                | -                | -         |   -16.96 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           25 |     2076 | 2024-05-16 | MOUZ          | L   | 0.656      | -            | -                | -                | -         |    -5.04 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           24 |     2175 | 2024-05-14 | Falcons       | W   | 0.644      | 0.769        | 0.221 (0.109)    | -                | 1 (0.644) |     3.47 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           23 |     2297 | 2024-05-09 | Complexity    | L   | 0.610      | -            | -                | -                | -         |   -10.15 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           22 |     2316 | 2024-05-08 | The MongolZ   | W   | 0.605      | 0.889        | 1.000 (0.538)    | 0.710 (0.382)    | 1 (0.605) |    14.79 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           21 |     2332 | 2024-05-07 | GamerLegion   | W   | 0.598      | 0.889        | 0.173 (0.092)    | -                | 1 (0.598) |     0.92 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           20 |     2520 | 2024-04-28 | SAW           | W   | 0.537      | 0.889        | -                | 0.529 (0.253)    | 1 (0.537) |     1.05 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           19 |     2551 | 2024-04-27 | fnatic        | W   | 0.530      | 0.889        | 0.371 (0.174)    | 0.696 (0.328)    | 1 (0.530) |     5.00 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           18 |     2594 | 2024-04-25 | FaZe          | L   | 0.518      | -            | -                | -                | -         |    -7.41 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           17 |     2617 | 2024-04-24 | SAW           | W   | 0.510      | 0.889        | -                | 0.529 (0.240)    | -         |     0.86 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           16 |     2640 | 2024-04-23 | fnatic        | L   | 0.503      | -            | -                | -                | -         |   -11.28 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           15 |     2936 | 2024-04-12 | G2            | L   | 0.428      | -            | -                | -                | -         |    -2.24 | fame, FL1T, Jame, mir, n0rb3r7        |
|           14 |     3020 | 2024-04-10 | Astralis      | L   | 0.415      | -            | -                | -                | -         |    -5.93 | fame, FL1T, Jame, mir, n0rb3r7        |
|           13 |     3072 | 2024-04-08 | FlyQuest      | W   | 0.408      | -            | -                | -                | -         |     0.62 | fame, FL1T, Jame, mir, n0rb3r7        |
|           12 |     3102 | 2024-04-08 | Wildcard      | W   | 0.402      | -            | -                | -                | -         |     0.14 | fame, FL1T, Jame, mir, n0rb3r7        |
|           11 |     3402 | 2024-03-24 | G2            | L   | 0.304      | -            | -                | -                | -         |    -1.56 | fame, FL1T, Jame, mir, n0rb3r7        |
|           10 |     3416 | 2024-03-23 | Eternal Fire  | L   | 0.296      | -            | -                | -                | -         |    -4.60 | fame, FL1T, Jame, mir, n0rb3r7        |
|            9 |     3433 | 2024-03-22 | HEROIC        | W   | 0.290      | -            | -                | -                | -         |     2.94 | fame, FL1T, Jame, mir, n0rb3r7        |
|            8 |     3447 | 2024-03-21 | paiN          | W   | 0.285      | 1.000        | 0.325 (0.092)    | 0.857 (0.244)    | -         |     1.47 | fame, FL1T, Jame, mir, n0rb3r7        |
|            7 |     3457 | 2024-03-21 | Imperial      | L   | 0.283      | -            | -                | -                | -         |    -8.24 | fame, FL1T, Jame, mir, n0rb3r7        |
|            6 |     3659 | 2024-03-12 | HEROIC        | W   | 0.225      | -            | -                | -                | -         |     2.18 | fame, FL1T, Jame, mir, n0rb3r7        |
|            5 |     3675 | 2024-03-11 | Apeks         | W   | 0.218      | -            | -                | -                | -         |     0.08 | fame, FL1T, Jame, mir, n0rb3r7        |
|            4 |     3686 | 2024-03-11 | B8            | W   | 0.217      | -            | -                | -                | -         |     0.21 | fame, FL1T, Jame, mir, n0rb3r7        |
|            3 |     4268 | 2024-02-15 | Natus Vincere | W   | 0.051      | -            | -                | -                | -         |     1.31 | fame, FL1T, Jame, mir, n0rb3r7        |
|            2 |     4300 | 2024-02-14 | fnatic        | W   | 0.045      | -            | -                | -                | -         |     0.44 | fame, FL1T, Jame, mir, n0rb3r7        |
|            1 |     4319 | 2024-02-14 | SAW           | W   | 0.043      | -            | -                | -                | -         |     0.06 | fame, FL1T, Jame, mir, n0rb3r7        |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($160,033.56)
- Divide that value by the 5th highest value among all rosters ($321,345.23)
- The final value (0.50) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-04 |      1.000 | $5,000.00      | $5,000.00       |
| 2024-07-21 |      1.000 | $85,000.00     | $85,000.00      |
| 2024-06-16 |      0.864 | $40,000.00     | $34,544.44      |
| 2024-06-02 |      0.771 | $5,000.00      | $3,856.94       |
| 2024-05-12 |      0.631 | $32,000.00     | $20,177.78      |
| 2024-04-14 |      0.443 | $10,000.00     | $4,426.62       |
| 2024-03-31 |      0.351 | $20,000.00     | $7,027.78       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
