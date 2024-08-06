### Roster Details<br />
Team Name: Natus Vincere<br />
Roster: Aleksib, b1t, iM, jL, w0nderful<br />
Global Rank: [3](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [3]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1911.6<br />
<br />
Final Rank Value (1911.6) = Starting Rank Value (1972.7) + Head To Head Adjustments (-61.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 1.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.757[<sup>2</sup>](#table1)
- Opponent Network: 0.310[<sup>2</sup>](#table1)
- LAN Wins: 1.000[<sup>2</sup>](#table1)

The average of these factors is 0.767<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1972.7
- 400 + ( ( 0.767 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 1972.7


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
|           32 |       32 | 2024-08-04 | Complexity   | W   | 1.000      | 0.581        | -                | 0.373 (0.217)    | 1 (1.000) |     4.13 | Aleksib, b1t, iM, jL, w0nderful |
|           31 |       61 | 2024-08-03 | Liquid       | L   | 1.000      | -            | -                | -                | -         |   -25.60 | Aleksib, b1t, iM, jL, w0nderful |
|           30 |       95 | 2024-08-02 | BIG          | W   | 1.000      | -            | -                | -                | 1 (1.000) |     0.97 | Aleksib, b1t, iM, jL, w0nderful |
|           29 |      140 | 2024-08-01 | Liquid       | L   | 1.000      | -            | -                | -                | -         |   -26.86 | Aleksib, b1t, iM, jL, w0nderful |
|           28 |      190 | 2024-07-31 | BIG          | W   | 1.000      | -            | -                | -                | 1 (1.000) |     0.72 | Aleksib, b1t, iM, jL, w0nderful |
|           27 |      508 | 2024-07-21 | G2           | W   | 1.000      | 1.000        | 1.000 (1.000)    | 0.489 (0.489)    | 1 (1.000) |    16.16 | Aleksib, b1t, iM, jL, w0nderful |
|           26 |      541 | 2024-07-20 | MOUZ         | W   | 1.000      | 1.000        | 1.000 (1.000)    | 0.366 (0.366)    | 1 (1.000) |    13.14 | Aleksib, b1t, iM, jL, w0nderful |
|           25 |      571 | 2024-07-19 | FaZe         | W   | 1.000      | 1.000        | 0.629 (0.629)    | 0.393 (0.393)    | 1 (1.000) |     7.35 | Aleksib, b1t, iM, jL, w0nderful |
|           24 |      710 | 2024-07-17 | FURIA        | W   | 1.000      | 1.000        | 0.284 (0.284)    | 0.480 (0.480)    | 1 (1.000) |     4.24 | Aleksib, b1t, iM, jL, w0nderful |
|           23 |     1028 | 2024-06-16 | Spirit       | L   | 0.864      | -            | -                | -                | -         |   -13.54 | Aleksib, b1t, iM, jL, w0nderful |
|           22 |     1049 | 2024-06-15 | Virtus.pro   | W   | 0.858      | 0.729        | 0.498 (0.312)    | 0.316 (0.198)    | 1 (0.858) |     5.13 | Aleksib, b1t, iM, jL, w0nderful |
|           21 |     1139 | 2024-06-13 | FaZe         | W   | 0.843      | 0.729        | 0.629 (0.387)    | 0.393 (0.241)    | 1 (0.843) |     6.68 | Aleksib, b1t, iM, jL, w0nderful |
|           20 |     1168 | 2024-06-12 | Astralis     | W   | 0.837      | 0.729        | -                | 0.413 (0.252)    | 1 (0.837) |     6.63 | Aleksib, b1t, iM, jL, w0nderful |
|           19 |     1710 | 2024-05-29 | HEROIC       | L   | 0.744      | -            | -                | -                | -         |   -20.77 | Aleksib, b1t, iM, jL, w0nderful |
|           18 |     1731 | 2024-05-28 | Spirit       | L   | 0.738      | -            | -                | -                | -         |   -12.86 | Aleksib, b1t, iM, jL, w0nderful |
|           17 |     1749 | 2024-05-27 | BIG          | W   | 0.732      | -            | -                | -                | -         |     0.58 | Aleksib, b1t, iM, jL, w0nderful |
|           16 |     2315 | 2024-05-08 | FaZe         | L   | 0.605      | -            | -                | -                | -         |   -14.93 | Aleksib, b1t, iM, jL, w0nderful |
|           15 |     2365 | 2024-05-05 | Complexity   | L   | 0.585      | -            | -                | -                | -         |   -15.76 | Aleksib, b1t, iM, jL, w0nderful |
|           14 |     2439 | 2024-05-02 | BIG          | W   | 0.563      | -            | -                | -                | -         |     0.36 | Aleksib, b1t, iM, jL, w0nderful |
|           13 |     2462 | 2024-05-01 | FlyQuest     | W   | 0.556      | -            | -                | -                | -         |     0.19 | Aleksib, b1t, iM, jL, w0nderful |
|           12 |     3293 | 2024-03-31 | FaZe         | W   | 0.351      | -            | -                | -                | -         |     1.93 | Aleksib, b1t, iM, jL, w0nderful |
|           11 |     3298 | 2024-03-30 | G2           | W   | 0.345      | 1.000        | 1.000 (0.345)    | -                | -         |     5.78 | Aleksib, b1t, iM, jL, w0nderful |
|           10 |     3308 | 2024-03-29 | Eternal Fire | W   | 0.338      | 1.000        | 0.739 (0.250)    | -                | -         |     2.04 | Aleksib, b1t, iM, jL, w0nderful |
|            9 |     3401 | 2024-03-24 | paiN         | W   | 0.305      | 1.000        | -                | 0.857 (0.261)    | -         |     0.43 | Aleksib, b1t, iM, jL, w0nderful |
|            8 |     3410 | 2024-03-23 | Cloud9       | L   | 0.298      | -            | -                | -                | -         |    -9.34 | Aleksib, b1t, iM, jL, w0nderful |
|            7 |     3426 | 2024-03-22 | Spirit       | L   | 0.291      | -            | -                | -                | -         |    -5.52 | Aleksib, b1t, iM, jL, w0nderful |
|            6 |     3442 | 2024-03-21 | G2           | W   | 0.285      | 1.000        | 1.000 (0.285)    | -                | -         |     4.80 | Aleksib, b1t, iM, jL, w0nderful |
|            5 |     3459 | 2024-03-21 | The MongolZ  | W   | 0.283      | 1.000        | 1.000 (0.283)    | 0.710 (0.201)    | -         |     4.02 | Aleksib, b1t, iM, jL, w0nderful |
|            4 |     4239 | 2024-02-16 | BetBoom      | W   | 0.058      | -            | -                | -                | -         |     0.08 | Aleksib, b1t, iM, jL, w0nderful |
|            3 |     4268 | 2024-02-15 | Virtus.pro   | L   | 0.051      | -            | -                | -                | -         |    -1.31 | Aleksib, b1t, iM, jL, w0nderful |
|            2 |     4299 | 2024-02-14 | Enterprise   | W   | 0.045      | -            | -                | -                | -         |     0.00 | Aleksib, b1t, iM, jL, w0nderful |
|            1 |     4317 | 2024-02-14 | KOI          | W   | 0.043      | -            | -                | -                | -         |     0.01 | Aleksib, b1t, iM, jL, w0nderful |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($680,276.39)
- Divide that value by the 5th highest value among all rosters ($321,345.23)
- The final value (1.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-04 |      1.000 | $12,500.00     | $12,500.00      |
| 2024-07-21 |      1.000 | $400,000.00    | $400,000.00     |
| 2024-06-16 |      0.864 | $85,000.00     | $73,406.94      |
| 2024-06-02 |      0.771 | $5,000.00      | $3,856.94       |
| 2024-05-12 |      0.631 | $23,500.00     | $14,818.06      |
| 2024-03-31 |      0.351 | $500,000.00    | $175,694.44     |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
