### Roster Details<br />
Team Name: Natus Vincere<br />
Roster: Aleksib, b1t, iM, jL, w0nderful<br />
Global Rank: [3](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [3]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1911.8<br />
<br />
Final Rank Value (1911.8) = Starting Rank Value (1972.9) + Head To Head Adjustments (-61.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 1.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.758[<sup>2</sup>](#table1)
- Opponent Network: 0.311[<sup>2</sup>](#table1)
- LAN Wins: 1.000[<sup>2</sup>](#table1)

The average of these factors is 0.767<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1972.9
- 400 + ( ( 0.767 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 1972.9


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
|           32 |       29 | 2024-08-04 | Complexity   | W   | 1.000      | 0.581        | -                | 0.373 (0.217)    | 1 (1.000) |     4.13 | Aleksib, b1t, iM, jL, w0nderful |
|           31 |       58 | 2024-08-03 | Liquid       | L   | 1.000      | -            | -                | -                | -         |   -25.59 | Aleksib, b1t, iM, jL, w0nderful |
|           30 |       92 | 2024-08-02 | BIG          | W   | 1.000      | -            | -                | -                | 1 (1.000) |     0.97 | Aleksib, b1t, iM, jL, w0nderful |
|           29 |      137 | 2024-08-01 | Liquid       | L   | 1.000      | -            | -                | -                | -         |   -26.86 | Aleksib, b1t, iM, jL, w0nderful |
|           28 |      187 | 2024-07-31 | BIG          | W   | 1.000      | -            | -                | -                | 1 (1.000) |     0.72 | Aleksib, b1t, iM, jL, w0nderful |
|           27 |      505 | 2024-07-21 | G2           | W   | 1.000      | 1.000        | 1.000 (1.000)    | 0.490 (0.490)    | 1 (1.000) |    16.15 | Aleksib, b1t, iM, jL, w0nderful |
|           26 |      538 | 2024-07-20 | MOUZ         | W   | 1.000      | 1.000        | 1.000 (1.000)    | 0.367 (0.367)    | 1 (1.000) |    13.16 | Aleksib, b1t, iM, jL, w0nderful |
|           25 |      568 | 2024-07-19 | FaZe         | W   | 1.000      | 1.000        | 0.631 (0.631)    | 0.394 (0.394)    | 1 (1.000) |     7.39 | Aleksib, b1t, iM, jL, w0nderful |
|           24 |      707 | 2024-07-17 | FURIA        | W   | 1.000      | 1.000        | 0.284 (0.284)    | 0.481 (0.481)    | 1 (1.000) |     4.24 | Aleksib, b1t, iM, jL, w0nderful |
|           23 |     1025 | 2024-06-16 | Spirit       | L   | 0.866      | -            | -                | -                | -         |   -13.57 | Aleksib, b1t, iM, jL, w0nderful |
|           22 |     1046 | 2024-06-15 | Virtus.pro   | W   | 0.861      | 0.729        | 0.498 (0.312)    | 0.317 (0.199)    | 1 (0.861) |     5.16 | Aleksib, b1t, iM, jL, w0nderful |
|           21 |     1136 | 2024-06-13 | FaZe         | W   | 0.846      | 0.729        | 0.631 (0.389)    | 0.394 (0.243)    | 1 (0.846) |     6.74 | Aleksib, b1t, iM, jL, w0nderful |
|           20 |     1165 | 2024-06-12 | Astralis     | W   | 0.839      | 0.729        | -                | 0.413 (0.253)    | 1 (0.839) |     6.66 | Aleksib, b1t, iM, jL, w0nderful |
|           19 |     1707 | 2024-05-29 | HEROIC       | L   | 0.747      | -            | -                | -                | -         |   -20.83 | Aleksib, b1t, iM, jL, w0nderful |
|           18 |     1728 | 2024-05-28 | Spirit       | L   | 0.740      | -            | -                | -                | -         |   -12.90 | Aleksib, b1t, iM, jL, w0nderful |
|           17 |     1746 | 2024-05-27 | BIG          | W   | 0.734      | -            | -                | -                | -         |     0.58 | Aleksib, b1t, iM, jL, w0nderful |
|           16 |     2312 | 2024-05-08 | FaZe         | L   | 0.607      | -            | -                | -                | -         |   -14.96 | Aleksib, b1t, iM, jL, w0nderful |
|           15 |     2362 | 2024-05-05 | Complexity   | L   | 0.587      | -            | -                | -                | -         |   -15.81 | Aleksib, b1t, iM, jL, w0nderful |
|           14 |     2436 | 2024-05-02 | BIG          | W   | 0.565      | -            | -                | -                | -         |     0.36 | Aleksib, b1t, iM, jL, w0nderful |
|           13 |     2459 | 2024-05-01 | FlyQuest     | W   | 0.558      | -            | -                | -                | -         |     0.19 | Aleksib, b1t, iM, jL, w0nderful |
|           12 |     3290 | 2024-03-31 | FaZe         | W   | 0.354      | -            | -                | -                | -         |     1.95 | Aleksib, b1t, iM, jL, w0nderful |
|           11 |     3295 | 2024-03-30 | G2           | W   | 0.347      | 1.000        | 1.000 (0.347)    | -                | -         |     5.82 | Aleksib, b1t, iM, jL, w0nderful |
|           10 |     3305 | 2024-03-29 | Eternal Fire | W   | 0.340      | 1.000        | 0.740 (0.251)    | -                | -         |     2.06 | Aleksib, b1t, iM, jL, w0nderful |
|            9 |     3398 | 2024-03-24 | paiN         | W   | 0.307      | 1.000        | -                | 0.856 (0.263)    | -         |     0.44 | Aleksib, b1t, iM, jL, w0nderful |
|            8 |     3407 | 2024-03-23 | Cloud9       | L   | 0.301      | -            | -                | -                | -         |    -9.41 | Aleksib, b1t, iM, jL, w0nderful |
|            7 |     3423 | 2024-03-22 | Spirit       | L   | 0.293      | -            | -                | -                | -         |    -5.56 | Aleksib, b1t, iM, jL, w0nderful |
|            6 |     3439 | 2024-03-21 | G2           | W   | 0.288      | 1.000        | 1.000 (0.288)    | -                | -         |     4.84 | Aleksib, b1t, iM, jL, w0nderful |
|            5 |     3456 | 2024-03-21 | The MongolZ  | W   | 0.285      | 1.000        | 1.000 (0.285)    | 0.710 (0.203)    | -         |     4.05 | Aleksib, b1t, iM, jL, w0nderful |
|            4 |     4236 | 2024-02-16 | BetBoom      | W   | 0.060      | -            | -                | -                | -         |     0.08 | Aleksib, b1t, iM, jL, w0nderful |
|            3 |     4265 | 2024-02-15 | Virtus.pro   | L   | 0.053      | -            | -                | -                | -         |    -1.37 | Aleksib, b1t, iM, jL, w0nderful |
|            2 |     4296 | 2024-02-14 | Enterprise   | W   | 0.048      | -            | -                | -                | -         |     0.00 | Aleksib, b1t, iM, jL, w0nderful |
|            1 |     4314 | 2024-02-14 | KOI          | W   | 0.045      | -            | -                | -                | -         |     0.01 | Aleksib, b1t, iM, jL, w0nderful |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($681,639.72)
- Divide that value by the 5th highest value among all rosters ($322,004.12)
- The final value (1.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-04 |      1.000 | $12,500.00     | $12,500.00      |
| 2024-07-21 |      1.000 | $400,000.00    | $400,000.00     |
| 2024-06-16 |      0.866 | $85,000.00     | $73,595.83      |
| 2024-06-02 |      0.774 | $5,000.00      | $3,868.06       |
| 2024-05-12 |      0.633 | $23,500.00     | $14,870.28      |
| 2024-03-31 |      0.354 | $500,000.00    | $176,805.56     |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
