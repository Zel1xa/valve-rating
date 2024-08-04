### Roster Details<br />
Team Name: Virtus.pro<br />
Roster: electroNic, fame, FL1T, Jame, n0rb3r7<br />
Global Rank: [10](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [9]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1649.2<br />
<br />
Final Rank Value (1649.2) = Starting Rank Value (1703.0) + Head To Head Adjustments (-53.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.767[<sup>1</sup>](#table2)
- Bounty Collected: 0.640[<sup>2</sup>](#table1)
- Opponent Network: 0.294[<sup>2</sup>](#table1)
- LAN Wins: 0.848[<sup>2</sup>](#table1)

The average of these factors is 0.637<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1703.0
- 400 + ( ( 0.637 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 1703.0


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
|           38 |       82 | 2024-08-01 | BIG           | L   | 1.000      | -            | -                | -                | -         |   -27.82 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           37 |      132 | 2024-07-31 | Liquid        | L   | 1.000      | -            | -                | -                | -         |   -19.16 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           36 |      501 | 2024-07-20 | G2            | L   | 1.000      | -            | -                | -                | -         |    -5.83 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           35 |      543 | 2024-07-19 | Vitality      | W   | 1.000      | 1.000        | 0.649 (0.649)    | 0.383 (0.383)    | 1 (1.000) |    22.20 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           34 |      648 | 2024-07-17 | Complexity    | W   | 1.000      | 1.000        | 0.310 (0.310)    | 0.380 (0.380)    | 1 (1.000) |    12.77 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           33 |      997 | 2024-06-15 | Natus Vincere | L   | 0.868      | -            | -                | -                | -         |    -5.26 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           32 |     1034 | 2024-06-14 | Astralis      | W   | 0.862      | 0.729        | 0.391 (0.245)    | 0.421 (0.264)    | 1 (0.862) |    15.40 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           31 |     1071 | 2024-06-13 | Spirit        | L   | 0.855      | -            | -                | -                | -         |    -5.44 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           30 |     1111 | 2024-06-12 | Vitality      | W   | 0.848      | 0.729        | 0.649 (0.401)    | 0.383 (0.236)    | 1 (0.848) |    20.22 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           29 |     1657 | 2024-05-29 | BIG           | L   | 0.755      | -            | -                | -                | -         |   -20.78 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           28 |     1672 | 2024-05-28 | FaZe          | L   | 0.749      | -            | -                | -                | -         |    -9.46 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           27 |     1693 | 2024-05-27 | HEROIC        | W   | 0.742      | 0.624        | 0.229 (0.106)    | 0.373 (0.173)    | 1 (0.742) |     8.13 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           26 |     1985 | 2024-05-17 | Falcons       | L   | 0.673      | -            | -                | -                | -         |   -17.19 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           25 |     2024 | 2024-05-16 | MOUZ          | L   | 0.666      | -            | -                | -                | -         |    -5.12 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           24 |     2123 | 2024-05-14 | Falcons       | W   | 0.654      | 0.769        | 0.224 (0.113)    | -                | 1 (0.654) |     3.55 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           23 |     2245 | 2024-05-09 | Complexity    | L   | 0.620      | -            | -                | -                | -         |   -10.55 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           22 |     2264 | 2024-05-08 | The MongolZ   | W   | 0.615      | 0.889        | 1.000 (0.547)    | 0.721 (0.394)    | 1 (0.615) |    14.95 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           21 |     2280 | 2024-05-07 | GamerLegion   | W   | 0.608      | 0.889        | 0.174 (0.094)    | -                | 1 (0.608) |     0.93 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           20 |     2468 | 2024-04-28 | SAW           | W   | 0.547      | 0.889        | -                | 0.540 (0.263)    | 1 (0.547) |     1.08 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           19 |     2499 | 2024-04-27 | fnatic        | W   | 0.540      | 0.889        | 0.371 (0.178)    | 0.708 (0.340)    | 1 (0.540) |     5.05 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           18 |     2542 | 2024-04-25 | FaZe          | L   | 0.528      | -            | -                | -                | -         |    -7.47 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           17 |     2565 | 2024-04-24 | SAW           | W   | 0.521      | 0.889        | -                | 0.540 (0.250)    | -         |     0.89 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           16 |     2588 | 2024-04-23 | fnatic        | L   | 0.513      | -            | -                | -                | -         |   -11.55 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           15 |     2884 | 2024-04-12 | G2            | L   | 0.438      | -            | -                | -                | -         |    -2.32 | fame, FL1T, Jame, mir, n0rb3r7        |
|           14 |     2968 | 2024-04-10 | Astralis      | L   | 0.426      | -            | -                | -                | -         |    -6.07 | fame, FL1T, Jame, mir, n0rb3r7        |
|           13 |     3020 | 2024-04-08 | FlyQuest      | W   | 0.418      | -            | -                | -                | -         |     0.64 | fame, FL1T, Jame, mir, n0rb3r7        |
|           12 |     3050 | 2024-04-08 | Wildcard      | W   | 0.412      | -            | -                | -                | -         |     0.02 | fame, FL1T, Jame, mir, n0rb3r7        |
|           11 |     3350 | 2024-03-24 | G2            | L   | 0.314      | -            | -                | -                | -         |    -1.64 | fame, FL1T, Jame, mir, n0rb3r7        |
|           10 |     3364 | 2024-03-23 | Eternal Fire  | L   | 0.307      | -            | -                | -                | -         |    -4.76 | fame, FL1T, Jame, mir, n0rb3r7        |
|            9 |     3381 | 2024-03-22 | HEROIC        | W   | 0.300      | -            | -                | -                | -         |     3.04 | fame, FL1T, Jame, mir, n0rb3r7        |
|            8 |     3395 | 2024-03-21 | paiN          | W   | 0.295      | 1.000        | 0.327 (0.096)    | 0.866 (0.256)    | -         |     1.55 | fame, FL1T, Jame, mir, n0rb3r7        |
|            7 |     3405 | 2024-03-21 | Imperial      | L   | 0.293      | -            | -                | -                | -         |    -8.52 | fame, FL1T, Jame, mir, n0rb3r7        |
|            6 |     3607 | 2024-03-12 | HEROIC        | W   | 0.235      | -            | -                | -                | -         |     2.27 | fame, FL1T, Jame, mir, n0rb3r7        |
|            5 |     3623 | 2024-03-11 | Apeks         | W   | 0.228      | -            | -                | -                | -         |     0.08 | fame, FL1T, Jame, mir, n0rb3r7        |
|            4 |     3634 | 2024-03-11 | B8            | W   | 0.227      | -            | -                | -                | -         |     0.21 | fame, FL1T, Jame, mir, n0rb3r7        |
|            3 |     4216 | 2024-02-15 | Natus Vincere | W   | 0.061      | -            | -                | -                | -         |     1.57 | fame, FL1T, Jame, mir, n0rb3r7        |
|            2 |     4248 | 2024-02-14 | fnatic        | W   | 0.055      | -            | -                | -                | -         |     0.54 | fame, FL1T, Jame, mir, n0rb3r7        |
|            1 |     4267 | 2024-02-14 | SAW           | W   | 0.053      | -            | -                | -                | -         |     0.08 | fame, FL1T, Jame, mir, n0rb3r7        |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($161,115.95)
- Divide that value by the 5th highest value among all rosters ($324,344.55)
- The final value (0.50) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-04 |      1.000 | $5,000.00      | $5,000.00       |
| 2024-07-21 |      1.000 | $85,000.00     | $85,000.00      |
| 2024-06-16 |      0.874 | $40,000.00     | $34,949.07      |
| 2024-06-02 |      0.782 | $5,000.00      | $3,907.52       |
| 2024-05-12 |      0.641 | $32,000.00     | $20,501.48      |
| 2024-04-14 |      0.453 | $10,000.00     | $4,527.78       |
| 2024-03-31 |      0.362 | $20,000.00     | $7,230.09       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
