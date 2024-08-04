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
Final Rank Value (1650.5) = Starting Rank Value (1703.8) + Head To Head Adjustments (-53.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.767[<sup>1</sup>](#table2)
- Bounty Collected: 0.642[<sup>2</sup>](#table1)
- Opponent Network: 0.293[<sup>2</sup>](#table1)
- LAN Wins: 0.848[<sup>2</sup>](#table1)

The average of these factors is 0.638<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1703.8
- 400 + ( ( 0.638 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 1703.8


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
|           38 |      104 | 2024-08-01 | BIG           | L   | 1.000      | -            | -                | -                | -         |   -27.84 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           37 |      156 | 2024-07-31 | Liquid        | L   | 1.000      | -            | -                | -                | -         |   -19.11 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           36 |      525 | 2024-07-20 | G2            | L   | 1.000      | -            | -                | -                | -         |    -5.85 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           35 |      567 | 2024-07-19 | Vitality      | W   | 1.000      | 1.000        | 0.649 (0.649)    | 0.383 (0.383)    | 1 (1.000) |    22.16 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           34 |      669 | 2024-07-17 | Complexity    | W   | 1.000      | 1.000        | 0.342 (0.342)    | 0.380 (0.380)    | 1 (1.000) |    13.01 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           33 |     1021 | 2024-06-15 | Natus Vincere | L   | 0.867      | -            | -                | -                | -         |    -5.23 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           32 |     1058 | 2024-06-14 | Astralis      | W   | 0.861      | 0.729        | 0.390 (0.245)    | 0.421 (0.264)    | 1 (0.861) |    15.35 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           31 |     1095 | 2024-06-13 | Spirit        | L   | 0.854      | -            | -                | -                | -         |    -5.42 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           30 |     1135 | 2024-06-12 | Vitality      | W   | 0.846      | 0.729        | 0.649 (0.400)    | 0.383 (0.236)    | 1 (0.846) |    20.17 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           29 |     1681 | 2024-05-29 | BIG           | L   | 0.753      | -            | -                | -                | -         |   -20.77 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           28 |     1696 | 2024-05-28 | FaZe          | L   | 0.748      | -            | -                | -                | -         |    -9.46 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           27 |     1717 | 2024-05-27 | HEROIC        | W   | 0.741      | 0.624        | 0.229 (0.106)    | 0.373 (0.173)    | 1 (0.741) |     8.13 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           26 |     2009 | 2024-05-17 | Falcons       | L   | 0.672      | -            | -                | -                | -         |   -17.19 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           25 |     2048 | 2024-05-16 | MOUZ          | L   | 0.665      | -            | -                | -                | -         |    -5.13 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           24 |     2147 | 2024-05-14 | Falcons       | W   | 0.653      | 0.769        | 0.223 (0.112)    | -                | 1 (0.653) |     3.52 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           23 |     2269 | 2024-05-09 | Complexity    | L   | 0.619      | -            | -                | -                | -         |   -10.29 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           22 |     2288 | 2024-05-08 | The MongolZ   | W   | 0.614      | 0.889        | 1.000 (0.546)    | 0.721 (0.393)    | 1 (0.614) |    14.91 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           21 |     2304 | 2024-05-07 | GamerLegion   | W   | 0.607      | 0.889        | 0.173 (0.094)    | -                | 1 (0.607) |     0.92 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           20 |     2492 | 2024-04-28 | SAW           | W   | 0.546      | 0.889        | -                | 0.540 (0.262)    | 1 (0.546) |     1.07 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           19 |     2523 | 2024-04-27 | fnatic        | W   | 0.539      | 0.889        | 0.371 (0.177)    | 0.708 (0.339)    | 1 (0.539) |     5.04 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           18 |     2566 | 2024-04-25 | FaZe          | L   | 0.527      | -            | -                | -                | -         |    -7.46 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           17 |     2589 | 2024-04-24 | SAW           | W   | 0.519      | 0.889        | -                | 0.540 (0.249)    | -         |     0.88 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           16 |     2612 | 2024-04-23 | fnatic        | L   | 0.512      | -            | -                | -                | -         |   -11.53 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           15 |     2908 | 2024-04-12 | G2            | L   | 0.437      | -            | -                | -                | -         |    -2.32 | fame, FL1T, Jame, mir, n0rb3r7        |
|           14 |     2992 | 2024-04-10 | Astralis      | L   | 0.424      | -            | -                | -                | -         |    -6.08 | fame, FL1T, Jame, mir, n0rb3r7        |
|           13 |     3044 | 2024-04-08 | FlyQuest      | W   | 0.417      | -            | -                | -                | -         |     0.64 | fame, FL1T, Jame, mir, n0rb3r7        |
|           12 |     3074 | 2024-04-08 | Wildcard      | W   | 0.411      | -            | -                | -                | -         |     0.14 | fame, FL1T, Jame, mir, n0rb3r7        |
|           11 |     3374 | 2024-03-24 | G2            | L   | 0.313      | -            | -                | -                | -         |    -1.64 | fame, FL1T, Jame, mir, n0rb3r7        |
|           10 |     3388 | 2024-03-23 | Eternal Fire  | L   | 0.305      | -            | -                | -                | -         |    -4.76 | fame, FL1T, Jame, mir, n0rb3r7        |
|            9 |     3405 | 2024-03-22 | HEROIC        | W   | 0.299      | -            | -                | -                | -         |     3.03 | fame, FL1T, Jame, mir, n0rb3r7        |
|            8 |     3419 | 2024-03-21 | paiN          | W   | 0.294      | 1.000        | 0.327 (0.096)    | 0.867 (0.255)    | -         |     1.53 | fame, FL1T, Jame, mir, n0rb3r7        |
|            7 |     3429 | 2024-03-21 | Imperial      | L   | 0.292      | -            | -                | -                | -         |    -8.50 | fame, FL1T, Jame, mir, n0rb3r7        |
|            6 |     3631 | 2024-03-12 | HEROIC        | W   | 0.234      | -            | -                | -                | -         |     2.27 | fame, FL1T, Jame, mir, n0rb3r7        |
|            5 |     3647 | 2024-03-11 | Apeks         | W   | 0.227      | -            | -                | -                | -         |     0.08 | fame, FL1T, Jame, mir, n0rb3r7        |
|            4 |     3658 | 2024-03-11 | B8            | W   | 0.226      | -            | -                | -                | -         |     0.21 | fame, FL1T, Jame, mir, n0rb3r7        |
|            3 |     4240 | 2024-02-15 | Natus Vincere | W   | 0.060      | -            | -                | -                | -         |     1.54 | fame, FL1T, Jame, mir, n0rb3r7        |
|            2 |     4272 | 2024-02-14 | fnatic        | W   | 0.054      | -            | -                | -                | -         |     0.53 | fame, FL1T, Jame, mir, n0rb3r7        |
|            1 |     4291 | 2024-02-14 | SAW           | W   | 0.052      | -            | -                | -                | -         |     0.08 | fame, FL1T, Jame, mir, n0rb3r7        |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($161,002.01)
- Divide that value by the 5th highest value among all rosters ($324,028.83)
- The final value (0.50) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-04 |      1.000 | $5,000.00      | $5,000.00       |
| 2024-07-21 |      1.000 | $85,000.00     | $85,000.00      |
| 2024-06-16 |      0.873 | $40,000.00     | $34,906.48      |
| 2024-06-02 |      0.780 | $5,000.00      | $3,902.20       |
| 2024-05-12 |      0.640 | $32,000.00     | $20,467.41      |
| 2024-04-14 |      0.452 | $10,000.00     | $4,517.13       |
| 2024-03-31 |      0.360 | $20,000.00     | $7,208.80       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
