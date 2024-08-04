### Roster Details<br />
Team Name: Virtus.pro<br />
Roster: electroNic, fame, FL1T, Jame, n0rb3r7<br />
Global Rank: [10](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [9]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1650.5<br />
<br />
Final Rank Value (1650.5) = Starting Rank Value (1703.9) + Head To Head Adjustments (-53.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.767[<sup>1</sup>](#table2)
- Bounty Collected: 0.642[<sup>2</sup>](#table1)
- Opponent Network: 0.293[<sup>2</sup>](#table1)
- LAN Wins: 0.848[<sup>2</sup>](#table1)

The average of these factors is 0.638<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1703.9
- 400 + ( ( 0.638 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 1703.9


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
|           38 |      103 | 2024-08-01 | BIG           | L   | 1.000      | -            | -                | -                | -         |   -27.84 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           37 |      155 | 2024-07-31 | Liquid        | L   | 1.000      | -            | -                | -                | -         |   -19.12 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           36 |      524 | 2024-07-20 | G2            | L   | 1.000      | -            | -                | -                | -         |    -5.86 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           35 |      566 | 2024-07-19 | Vitality      | W   | 1.000      | 1.000        | 0.649 (0.649)    | 0.383 (0.383)    | 1 (1.000) |    22.16 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           34 |      668 | 2024-07-17 | Complexity    | W   | 1.000      | 1.000        | 0.342 (0.342)    | 0.380 (0.380)    | 1 (1.000) |    13.01 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           33 |     1020 | 2024-06-15 | Natus Vincere | L   | 0.868      | -            | -                | -                | -         |    -5.23 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           32 |     1057 | 2024-06-14 | Astralis      | W   | 0.861      | 0.729        | 0.391 (0.245)    | 0.421 (0.264)    | 1 (0.861) |    15.36 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           31 |     1094 | 2024-06-13 | Spirit        | L   | 0.854      | -            | -                | -                | -         |    -5.42 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           30 |     1134 | 2024-06-12 | Vitality      | W   | 0.847      | 0.729        | 0.649 (0.400)    | 0.383 (0.236)    | 1 (0.847) |    20.18 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           29 |     1680 | 2024-05-29 | BIG           | L   | 0.754      | -            | -                | -                | -         |   -20.77 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           28 |     1695 | 2024-05-28 | FaZe          | L   | 0.748      | -            | -                | -                | -         |    -9.46 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           27 |     1716 | 2024-05-27 | HEROIC        | W   | 0.742      | 0.624        | 0.229 (0.106)    | 0.373 (0.173)    | 1 (0.742) |     8.13 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           26 |     2008 | 2024-05-17 | Falcons       | L   | 0.672      | -            | -                | -                | -         |   -17.20 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           25 |     2047 | 2024-05-16 | MOUZ          | L   | 0.665      | -            | -                | -                | -         |    -5.13 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           24 |     2146 | 2024-05-14 | Falcons       | W   | 0.654      | 0.769        | 0.223 (0.112)    | -                | 1 (0.654) |     3.52 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           23 |     2268 | 2024-05-09 | Complexity    | L   | 0.620      | -            | -                | -                | -         |   -10.30 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           22 |     2287 | 2024-05-08 | The MongolZ   | W   | 0.614      | 0.889        | 1.000 (0.546)    | 0.721 (0.393)    | 1 (0.614) |    14.92 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           21 |     2303 | 2024-05-07 | GamerLegion   | W   | 0.607      | 0.889        | 0.173 (0.094)    | -                | 1 (0.607) |     0.92 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           20 |     2491 | 2024-04-28 | SAW           | W   | 0.546      | 0.889        | -                | 0.540 (0.262)    | 1 (0.546) |     1.07 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           19 |     2522 | 2024-04-27 | fnatic        | W   | 0.539      | 0.889        | 0.371 (0.178)    | 0.708 (0.339)    | 1 (0.539) |     5.04 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           18 |     2565 | 2024-04-25 | FaZe          | L   | 0.527      | -            | -                | -                | -         |    -7.46 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           17 |     2588 | 2024-04-24 | SAW           | W   | 0.520      | 0.889        | -                | 0.540 (0.249)    | -         |     0.88 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           16 |     2611 | 2024-04-23 | fnatic        | L   | 0.512      | -            | -                | -                | -         |   -11.53 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           15 |     2907 | 2024-04-12 | G2            | L   | 0.438      | -            | -                | -                | -         |    -2.32 | fame, FL1T, Jame, mir, n0rb3r7        |
|           14 |     2991 | 2024-04-10 | Astralis      | L   | 0.425      | -            | -                | -                | -         |    -6.08 | fame, FL1T, Jame, mir, n0rb3r7        |
|           13 |     3043 | 2024-04-08 | FlyQuest      | W   | 0.417      | -            | -                | -                | -         |     0.64 | fame, FL1T, Jame, mir, n0rb3r7        |
|           12 |     3073 | 2024-04-08 | Wildcard      | W   | 0.411      | -            | -                | -                | -         |     0.14 | fame, FL1T, Jame, mir, n0rb3r7        |
|           11 |     3373 | 2024-03-24 | G2            | L   | 0.313      | -            | -                | -                | -         |    -1.64 | fame, FL1T, Jame, mir, n0rb3r7        |
|           10 |     3387 | 2024-03-23 | Eternal Fire  | L   | 0.306      | -            | -                | -                | -         |    -4.76 | fame, FL1T, Jame, mir, n0rb3r7        |
|            9 |     3404 | 2024-03-22 | HEROIC        | W   | 0.299      | -            | -                | -                | -         |     3.04 | fame, FL1T, Jame, mir, n0rb3r7        |
|            8 |     3418 | 2024-03-21 | paiN          | W   | 0.294      | 1.000        | 0.327 (0.096)    | 0.867 (0.255)    | -         |     1.53 | fame, FL1T, Jame, mir, n0rb3r7        |
|            7 |     3428 | 2024-03-21 | Imperial      | L   | 0.293      | -            | -                | -                | -         |    -8.51 | fame, FL1T, Jame, mir, n0rb3r7        |
|            6 |     3630 | 2024-03-12 | HEROIC        | W   | 0.234      | -            | -                | -                | -         |     2.27 | fame, FL1T, Jame, mir, n0rb3r7        |
|            5 |     3646 | 2024-03-11 | Apeks         | W   | 0.228      | -            | -                | -                | -         |     0.08 | fame, FL1T, Jame, mir, n0rb3r7        |
|            4 |     3657 | 2024-03-11 | B8            | W   | 0.226      | -            | -                | -                | -         |     0.21 | fame, FL1T, Jame, mir, n0rb3r7        |
|            3 |     4239 | 2024-02-15 | Natus Vincere | W   | 0.060      | -            | -                | -                | -         |     1.55 | fame, FL1T, Jame, mir, n0rb3r7        |
|            2 |     4271 | 2024-02-14 | fnatic        | W   | 0.054      | -            | -                | -                | -         |     0.53 | fame, FL1T, Jame, mir, n0rb3r7        |
|            1 |     4290 | 2024-02-14 | SAW           | W   | 0.052      | -            | -                | -                | -         |     0.08 | fame, FL1T, Jame, mir, n0rb3r7        |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($161,034.21)
- Divide that value by the 5th highest value among all rosters ($324,118.06)
- The final value (0.50) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-04 |      1.000 | $5,000.00      | $5,000.00       |
| 2024-07-21 |      1.000 | $85,000.00     | $85,000.00      |
| 2024-06-16 |      0.873 | $40,000.00     | $34,918.52      |
| 2024-06-02 |      0.781 | $5,000.00      | $3,903.70       |
| 2024-05-12 |      0.640 | $32,000.00     | $20,477.04      |
| 2024-04-14 |      0.452 | $10,000.00     | $4,520.14       |
| 2024-03-31 |      0.361 | $20,000.00     | $7,214.81       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
