### Roster Details<br />
Team Name: Virtus.pro<br />
Roster: electroNic, fame, FL1T, Jame, n0rb3r7<br />
Global Rank: [9](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [8]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1644.1<br />
<br />
Final Rank Value (1644.1) = Starting Rank Value (1702.0) + Head To Head Adjustments (-57.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.767[<sup>1</sup>](#table2)
- Bounty Collected: 0.639[<sup>2</sup>](#table1)
- Opponent Network: 0.293[<sup>2</sup>](#table1)
- LAN Wins: 0.850[<sup>2</sup>](#table1)

The average of these factors is 0.637<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1702.0
- 400 + ( ( 0.637 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 1702.0


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
|           38 |       71 | 2024-08-01 | BIG           | L   | 1.000      | -            | -                | -                | -         |   -27.73 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           37 |      121 | 2024-07-31 | Liquid        | L   | 1.000      | -            | -                | -                | -         |   -21.58 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           36 |      490 | 2024-07-20 | G2            | L   | 1.000      | -            | -                | -                | -         |    -5.82 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           35 |      532 | 2024-07-19 | Vitality      | W   | 1.000      | 1.000        | 0.649 (0.649)    | 0.383 (0.383)    | 1 (1.000) |    22.16 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           34 |      637 | 2024-07-17 | Complexity    | W   | 1.000      | 1.000        | 0.311 (0.311)    | 0.380 (0.380)    | 1 (1.000) |    12.80 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           33 |      985 | 2024-06-15 | Natus Vincere | L   | 0.872      | -            | -                | -                | -         |    -5.26 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           32 |     1022 | 2024-06-14 | Astralis      | W   | 0.865      | 0.729        | 0.353 (0.223)    | 0.382 (0.241)    | 1 (0.865) |    14.34 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           31 |     1059 | 2024-06-13 | Spirit        | L   | 0.859      | -            | -                | -                | -         |    -5.42 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           30 |     1099 | 2024-06-12 | Vitality      | W   | 0.851      | 0.729        | 0.649 (0.403)    | 0.383 (0.238)    | 1 (0.851) |    20.24 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           29 |     1645 | 2024-05-29 | BIG           | L   | 0.758      | -            | -                | -                | -         |   -20.85 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           28 |     1660 | 2024-05-28 | FaZe          | L   | 0.752      | -            | -                | -                | -         |    -9.52 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           27 |     1681 | 2024-05-27 | HEROIC        | W   | 0.746      | 0.624        | 0.229 (0.107)    | 0.375 (0.175)    | 1 (0.746) |     8.18 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           26 |     1973 | 2024-05-17 | Falcons       | L   | 0.677      | -            | -                | -                | -         |   -17.22 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           25 |     2012 | 2024-05-16 | MOUZ          | L   | 0.670      | -            | -                | -                | -         |    -5.15 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           24 |     2111 | 2024-05-14 | Falcons       | W   | 0.658      | 0.769        | 0.225 (0.114)    | -                | 1 (0.658) |     3.62 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           23 |     2233 | 2024-05-09 | Complexity    | L   | 0.624      | -            | -                | -                | -         |   -10.55 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           22 |     2252 | 2024-05-08 | The MongolZ   | W   | 0.619      | 0.889        | 1.000 (0.550)    | 0.720 (0.396)    | 1 (0.619) |    15.03 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           21 |     2268 | 2024-05-07 | GamerLegion   | W   | 0.612      | 0.889        | 0.174 (0.095)    | -                | 1 (0.612) |     0.95 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           20 |     2456 | 2024-04-28 | SAW           | W   | 0.551      | 0.889        | -                | 0.541 (0.265)    | 1 (0.551) |     1.10 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           19 |     2487 | 2024-04-27 | fnatic        | W   | 0.543      | 0.889        | 0.371 (0.179)    | 0.709 (0.342)    | 1 (0.543) |     5.11 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           18 |     2529 | 2024-04-25 | FaZe          | L   | 0.532      | -            | -                | -                | -         |    -7.53 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           17 |     2552 | 2024-04-24 | SAW           | W   | 0.524      | 0.889        | -                | 0.541 (0.252)    | -         |     0.90 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           16 |     2575 | 2024-04-23 | fnatic        | L   | 0.517      | -            | -                | -                | -         |   -11.61 | electroNic, fame, FL1T, Jame, n0rb3r7 |
|           15 |     2871 | 2024-04-12 | G2            | L   | 0.442      | -            | -                | -                | -         |    -2.33 | fame, FL1T, Jame, mir, n0rb3r7        |
|           14 |     2955 | 2024-04-10 | Astralis      | L   | 0.429      | -            | -                | -                | -         |    -6.93 | fame, FL1T, Jame, mir, n0rb3r7        |
|           13 |     3007 | 2024-04-08 | FlyQuest      | W   | 0.422      | -            | -                | -                | -         |     0.65 | fame, FL1T, Jame, mir, n0rb3r7        |
|           12 |     3037 | 2024-04-08 | Wildcard      | W   | 0.416      | -            | -                | -                | -         |     0.02 | fame, FL1T, Jame, mir, n0rb3r7        |
|           11 |     3337 | 2024-03-24 | G2            | L   | 0.317      | -            | -                | -                | -         |    -1.65 | fame, FL1T, Jame, mir, n0rb3r7        |
|           10 |     3351 | 2024-03-23 | Eternal Fire  | L   | 0.310      | -            | -                | -                | -         |    -4.81 | fame, FL1T, Jame, mir, n0rb3r7        |
|            9 |     3368 | 2024-03-22 | HEROIC        | W   | 0.304      | -            | -                | -                | -         |     3.10 | fame, FL1T, Jame, mir, n0rb3r7        |
|            8 |     3382 | 2024-03-21 | paiN          | W   | 0.299      | 1.000        | 0.328 (0.098)    | 0.865 (0.258)    | -         |     1.59 | fame, FL1T, Jame, mir, n0rb3r7        |
|            7 |     3392 | 2024-03-21 | Imperial      | L   | 0.297      | -            | -                | -                | -         |    -8.62 | fame, FL1T, Jame, mir, n0rb3r7        |
|            6 |     3593 | 2024-03-12 | HEROIC        | W   | 0.239      | -            | -                | -                | -         |     2.32 | fame, FL1T, Jame, mir, n0rb3r7        |
|            5 |     3609 | 2024-03-11 | Apeks         | W   | 0.232      | -            | -                | -                | -         |     0.09 | fame, FL1T, Jame, mir, n0rb3r7        |
|            4 |     3620 | 2024-03-11 | B8            | W   | 0.231      | -            | -                | -                | -         |     0.22 | fame, FL1T, Jame, mir, n0rb3r7        |
|            3 |     4201 | 2024-02-15 | Natus Vincere | W   | 0.065      | -            | -                | -                | -         |     1.66 | fame, FL1T, Jame, mir, n0rb3r7        |
|            2 |     4233 | 2024-02-14 | fnatic        | W   | 0.059      | -            | -                | -                | -         |     0.58 | fame, FL1T, Jame, mir, n0rb3r7        |
|            1 |     4252 | 2024-02-14 | SAW           | W   | 0.057      | -            | -                | -                | -         |     0.08 | fame, FL1T, Jame, mir, n0rb3r7        |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($161,519.68)
- Divide that value by the 5th highest value among all rosters ($325,463.29)
- The final value (0.50) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-03 |      1.000 | $5,000.00      | $5,000.00       |
| 2024-07-21 |      1.000 | $85,000.00     | $85,000.00      |
| 2024-06-16 |      0.877 | $40,000.00     | $35,100.00      |
| 2024-06-02 |      0.785 | $5,000.00      | $3,926.39       |
| 2024-05-12 |      0.644 | $32,000.00     | $20,622.22      |
| 2024-04-14 |      0.457 | $10,000.00     | $4,565.51       |
| 2024-03-31 |      0.365 | $20,000.00     | $7,305.56       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
