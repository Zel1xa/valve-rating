### Roster Details<br />
Team Name: Natus Vincere<br />
Roster: Aleksib, b1t, iM, jL, w0nderful<br />
Global Rank: [3](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [3]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1911.2<br />
<br />
Final Rank Value (1911.2) = Starting Rank Value (1972.3) + Head To Head Adjustments (-61.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 1.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.756[<sup>2</sup>](#table1)
- Opponent Network: 0.301[<sup>2</sup>](#table1)
- LAN Wins: 1.000[<sup>2</sup>](#table1)

The average of these factors is 0.764<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1972.3
- 400 + ( ( 0.764 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1972.3


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent     | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                          |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           32 |       51 | 2024-08-04 | Complexity   | W   | 1.000      | 0.581        | -                | 0.364 (0.211)    | 1 (1.000) |     4.12 | Aleksib, b1t, iM, jL, w0nderful |
|           31 |       80 | 2024-08-03 | Liquid       | L   | 1.000      | -            | -                | -                | -         |   -25.60 | Aleksib, b1t, iM, jL, w0nderful |
|           30 |      114 | 2024-08-02 | BIG          | W   | 1.000      | -            | -                | -                | 1 (1.000) |     0.97 | Aleksib, b1t, iM, jL, w0nderful |
|           29 |      159 | 2024-08-01 | Liquid       | L   | 1.000      | -            | -                | -                | -         |   -26.86 | Aleksib, b1t, iM, jL, w0nderful |
|           28 |      209 | 2024-07-31 | BIG          | W   | 1.000      | -            | -                | -                | 1 (1.000) |     0.72 | Aleksib, b1t, iM, jL, w0nderful |
|           27 |      527 | 2024-07-21 | G2           | W   | 1.000      | 1.000        | 1.000 (1.000)    | 0.478 (0.478)    | 1 (1.000) |    16.18 | Aleksib, b1t, iM, jL, w0nderful |
|           26 |      560 | 2024-07-20 | MOUZ         | W   | 1.000      | 1.000        | 1.000 (1.000)    | 0.357 (0.357)    | 1 (1.000) |    13.08 | Aleksib, b1t, iM, jL, w0nderful |
|           25 |      590 | 2024-07-19 | FaZe         | W   | 1.000      | 1.000        | 0.624 (0.624)    | 0.382 (0.382)    | 1 (1.000) |     7.29 | Aleksib, b1t, iM, jL, w0nderful |
|           24 |      729 | 2024-07-17 | FURIA        | W   | 1.000      | 1.000        | 0.284 (0.284)    | 0.468 (0.468)    | 1 (1.000) |     4.24 | Aleksib, b1t, iM, jL, w0nderful |
|           23 |     1047 | 2024-06-16 | Spirit       | L   | 0.859      | -            | -                | -                | -         |   -13.49 | Aleksib, b1t, iM, jL, w0nderful |
|           22 |     1068 | 2024-06-15 | Virtus.pro   | W   | 0.854      | 0.729        | 0.499 (0.310)    | 0.308 (0.192)    | 1 (0.854) |     5.08 | Aleksib, b1t, iM, jL, w0nderful |
|           21 |     1158 | 2024-06-13 | FaZe         | W   | 0.839      | 0.729        | 0.624 (0.382)    | 0.382 (0.234)    | 1 (0.839) |     6.59 | Aleksib, b1t, iM, jL, w0nderful |
|           20 |     1187 | 2024-06-12 | Astralis     | W   | 0.833      | 0.729        | -                | 0.403 (0.245)    | 1 (0.833) |     6.57 | Aleksib, b1t, iM, jL, w0nderful |
|           19 |     1729 | 2024-05-29 | HEROIC       | L   | 0.740      | -            | -                | -                | -         |   -20.68 | Aleksib, b1t, iM, jL, w0nderful |
|           18 |     1750 | 2024-05-28 | Spirit       | L   | 0.734      | -            | -                | -                | -         |   -12.79 | Aleksib, b1t, iM, jL, w0nderful |
|           17 |     1768 | 2024-05-27 | BIG          | W   | 0.728      | -            | -                | -                | -         |     0.57 | Aleksib, b1t, iM, jL, w0nderful |
|           16 |     2334 | 2024-05-08 | FaZe         | L   | 0.601      | -            | -                | -                | -         |   -14.87 | Aleksib, b1t, iM, jL, w0nderful |
|           15 |     2384 | 2024-05-05 | Complexity   | L   | 0.581      | -            | -                | -                | -         |   -15.65 | Aleksib, b1t, iM, jL, w0nderful |
|           14 |     2458 | 2024-05-02 | BIG          | W   | 0.559      | -            | -                | -                | -         |     0.36 | Aleksib, b1t, iM, jL, w0nderful |
|           13 |     2481 | 2024-05-01 | FlyQuest     | W   | 0.552      | -            | -                | -                | -         |     0.19 | Aleksib, b1t, iM, jL, w0nderful |
|           12 |     3312 | 2024-03-31 | FaZe         | W   | 0.347      | -            | -                | -                | -         |     1.88 | Aleksib, b1t, iM, jL, w0nderful |
|           11 |     3317 | 2024-03-30 | G2           | W   | 0.341      | 1.000        | 1.000 (0.341)    | -                | -         |     5.72 | Aleksib, b1t, iM, jL, w0nderful |
|           10 |     3327 | 2024-03-29 | Eternal Fire | W   | 0.333      | 1.000        | 0.738 (0.246)    | -                | -         |     2.01 | Aleksib, b1t, iM, jL, w0nderful |
|            9 |     3420 | 2024-03-24 | paiN         | W   | 0.301      | 1.000        | -                | 0.839 (0.252)    | -         |     0.42 | Aleksib, b1t, iM, jL, w0nderful |
|            8 |     3429 | 2024-03-23 | Cloud9       | L   | 0.294      | -            | -                | -                | -         |    -9.21 | Aleksib, b1t, iM, jL, w0nderful |
|            7 |     3445 | 2024-03-22 | Spirit       | L   | 0.287      | -            | -                | -                | -         |    -5.44 | Aleksib, b1t, iM, jL, w0nderful |
|            6 |     3461 | 2024-03-21 | G2           | W   | 0.281      | 1.000        | 1.000 (0.281)    | -                | -         |     4.74 | Aleksib, b1t, iM, jL, w0nderful |
|            5 |     3478 | 2024-03-21 | The MongolZ  | W   | 0.279      | 1.000        | 1.000 (0.279)    | 0.694 (0.193)    | -         |     3.95 | Aleksib, b1t, iM, jL, w0nderful |
|            4 |     4258 | 2024-02-16 | BetBoom      | W   | 0.053      | -            | -                | -                | -         |     0.07 | Aleksib, b1t, iM, jL, w0nderful |
|            3 |     4287 | 2024-02-15 | Virtus.pro   | L   | 0.047      | -            | -                | -                | -         |    -1.20 | Aleksib, b1t, iM, jL, w0nderful |
|            2 |     4318 | 2024-02-14 | Enterprise   | W   | 0.041      | -            | -                | -                | -         |     0.00 | Aleksib, b1t, iM, jL, w0nderful |
|            1 |     4336 | 2024-02-14 | KOI          | W   | 0.039      | -            | -                | -                | -         |     0.01 | Aleksib, b1t, iM, jL, w0nderful |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($677,720.14)
- Divide that value by the 5th highest value among all rosters ($320,109.81)
- The final value (1.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-04 |      1.000 | $12,500.00     | $12,500.00      |
| 2024-07-21 |      1.000 | $400,000.00    | $400,000.00     |
| 2024-06-16 |      0.859 | $85,000.00     | $73,052.78      |
| 2024-06-02 |      0.767 | $5,000.00      | $3,836.11       |
| 2024-05-12 |      0.626 | $23,500.00     | $14,720.14      |
| 2024-03-31 |      0.347 | $500,000.00    | $173,611.11     |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
