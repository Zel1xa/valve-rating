### Roster Details<br />
Team Name: Virtus.pro<br />
Roster: electroNic, fame, FL1T, Jame, n0rb3r7<br />
Global Rank: [10](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [9]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1650.0<br />
<br />
Final Rank Value (1650.0) = Starting Rank Value (1703.1) + Head To Head Adjustments (-53.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.767[<sup>1</sup>](#table2)
- Bounty Collected: 0.641[<sup>2</sup>](#table1)
- Opponent Network: 0.292[<sup>2</sup>](#table1)
- LAN Wins: 0.847[<sup>2</sup>](#table1)

The average of these factors is 0.637<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1703.1
- 400 + ( ( 0.637 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 1703.1


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
|           38 |      108 | 2024-08-01 | BIG           | L   | 1.000      | -            | -                | -                | -         |   -27.84 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           37 |      160 | 2024-07-31 | Liquid        | L   | 1.000      | -            | -                | -                | -         |   -19.08 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           36 |      529 | 2024-07-20 | G2            | L   | 1.000      | -            | -                | -                | -         |    -5.84 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           35 |      571 | 2024-07-19 | Vitality      | W   | 1.000      | 1.000        | 0.648 (0.648)    | 0.382 (0.382)    | 1 (1.000) |    22.17 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           34 |      673 | 2024-07-17 | Complexity    | W   | 1.000      | 1.000        | 0.342 (0.342)    | 0.380 (0.380)    | 1 (1.000) |    13.02 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           33 |     1025 | 2024-06-15 | Natus Vincere | L   | 0.865      | -            | -                | -                | -         |    -5.20 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           32 |     1062 | 2024-06-14 | Astralis      | W   | 0.858      | 0.729        | 0.390 (0.244)    | 0.421 (0.263)    | 1 (0.858) |    15.35 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           31 |     1099 | 2024-06-13 | Spirit        | L   | 0.852      | -            | -                | -                | -         |    -5.40 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           30 |     1139 | 2024-06-12 | Vitality      | W   | 0.844      | 0.729        | 0.648 (0.399)    | 0.382 (0.235)    | 1 (0.844) |    20.12 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           29 |     1685 | 2024-05-29 | BIG           | L   | 0.751      | -            | -                | -                | -         |   -20.70 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           28 |     1700 | 2024-05-28 | FaZe          | L   | 0.745      | -            | -                | -                | -         |    -9.46 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           27 |     1721 | 2024-05-27 | HEROIC        | W   | 0.739      | 0.624        | 0.226 (0.104)    | 0.372 (0.172)    | 1 (0.739) |     8.10 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           26 |     2013 | 2024-05-17 | Falcons       | L   | 0.670      | -            | -                | -                | -         |   -17.12 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           25 |     2052 | 2024-05-16 | MOUZ          | L   | 0.663      | -            | -                | -                | -         |    -5.11 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           24 |     2151 | 2024-05-14 | Falcons       | W   | 0.651      | 0.769        | 0.223 (0.111)    | -                | 1 (0.651) |     3.51 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           23 |     2273 | 2024-05-09 | Complexity    | L   | 0.617      | -            | -                | -                | -         |   -10.26 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           22 |     2292 | 2024-05-08 | The MongolZ   | W   | 0.611      | 0.889        | 1.000 (0.544)    | 0.721 (0.392)    | 1 (0.611) |    14.90 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           21 |     2308 | 2024-05-07 | GamerLegion   | W   | 0.605      | 0.889        | 0.173 (0.093)    | -                | 1 (0.605) |     0.93 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           20 |     2496 | 2024-04-28 | SAW           | W   | 0.544      | 0.889        | -                | 0.539 (0.261)    | 1 (0.544) |     1.06 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           19 |     2527 | 2024-04-27 | fnatic        | W   | 0.536      | 0.889        | 0.371 (0.177)    | 0.708 (0.338)    | 1 (0.536) |     5.03 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           18 |     2570 | 2024-04-25 | FaZe          | L   | 0.525      | -            | -                | -                | -         |    -7.45 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           17 |     2593 | 2024-04-24 | SAW           | W   | 0.517      | 0.889        | -                | 0.539 (0.248)    | -         |     0.88 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           16 |     2616 | 2024-04-23 | fnatic        | L   | 0.510      | -            | -                | -                | -         |   -11.46 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           15 |     2912 | 2024-04-12 | G2            | L   | 0.435      | -            | -                | -                | -         |    -2.30 | fame, FL1T, Jame, mir, n0rb3r7        |
|           14 |     2996 | 2024-04-10 | Astralis      | L   | 0.422      | -            | -                | -                | -         |    -6.02 | fame, FL1T, Jame, mir, n0rb3r7        |
|           13 |     3048 | 2024-04-08 | FlyQuest      | W   | 0.415      | -            | -                | -                | -         |     0.63 | fame, FL1T, Jame, mir, n0rb3r7        |
|           12 |     3078 | 2024-04-08 | Wildcard      | W   | 0.408      | -            | -                | -                | -         |     0.14 | fame, FL1T, Jame, mir, n0rb3r7        |
|           11 |     3378 | 2024-03-24 | G2            | L   | 0.310      | -            | -                | -                | -         |    -1.62 | fame, FL1T, Jame, mir, n0rb3r7        |
|           10 |     3392 | 2024-03-23 | Eternal Fire  | L   | 0.303      | -            | -                | -                | -         |    -4.72 | fame, FL1T, Jame, mir, n0rb3r7        |
|            9 |     3409 | 2024-03-22 | HEROIC        | W   | 0.296      | -            | -                | -                | -         |     3.01 | fame, FL1T, Jame, mir, n0rb3r7        |
|            8 |     3423 | 2024-03-21 | paiN          | W   | 0.292      | 1.000        | 0.326 (0.095)    | 0.868 (0.253)    | -         |     1.52 | fame, FL1T, Jame, mir, n0rb3r7        |
|            7 |     3433 | 2024-03-21 | Imperial      | L   | 0.290      | -            | -                | -                | -         |    -8.43 | fame, FL1T, Jame, mir, n0rb3r7        |
|            6 |     3635 | 2024-03-12 | HEROIC        | W   | 0.232      | -            | -                | -                | -         |     2.24 | fame, FL1T, Jame, mir, n0rb3r7        |
|            5 |     3651 | 2024-03-11 | Apeks         | W   | 0.225      | -            | -                | -                | -         |     0.08 | fame, FL1T, Jame, mir, n0rb3r7        |
|            4 |     3662 | 2024-03-11 | B8            | W   | 0.224      | -            | -                | -                | -         |     0.21 | fame, FL1T, Jame, mir, n0rb3r7        |
|            3 |     4244 | 2024-02-15 | Natus Vincere | W   | 0.057      | -            | -                | -                | -         |     1.48 | fame, FL1T, Jame, mir, n0rb3r7        |
|            2 |     4276 | 2024-02-14 | fnatic        | W   | 0.052      | -            | -                | -                | -         |     0.50 | fame, FL1T, Jame, mir, n0rb3r7        |
|            1 |     4295 | 2024-02-14 | SAW           | W   | 0.049      | -            | -                | -                | -         |     0.07 | fame, FL1T, Jame, mir, n0rb3r7        |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($160,746.90)
- Divide that value by the 5th highest value among all rosters ($323,321.90)
- The final value (0.50) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-04 |      1.000 | $5,000.00      | $5,000.00       |
| 2024-07-21 |      1.000 | $85,000.00     | $85,000.00      |
| 2024-06-16 |      0.870 | $40,000.00     | $34,811.11      |
| 2024-06-02 |      0.778 | $5,000.00      | $3,890.28       |
| 2024-05-12 |      0.637 | $32,000.00     | $20,391.11      |
| 2024-04-14 |      0.449 | $10,000.00     | $4,493.29       |
| 2024-03-31 |      0.358 | $20,000.00     | $7,161.11       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
