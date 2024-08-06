### Roster Details<br />
Team Name: Natus Vincere<br />
Roster: Aleksib, b1t, iM, jL, w0nderful<br />
Global Rank: [3](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [3]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1911.4<br />
<br />
Final Rank Value (1911.4) = Starting Rank Value (1972.5) + Head To Head Adjustments (-61.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 1.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.756[<sup>2</sup>](#table1)
- Opponent Network: 0.309[<sup>2</sup>](#table1)
- LAN Wins: 1.000[<sup>2</sup>](#table1)

The average of these factors is 0.766<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1972.5
- 400 + ( ( 0.766 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 1972.5


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
|           32 |       36 | 2024-08-04 | Complexity   | W   | 1.000      | 0.581        | -                | 0.372 (0.216)    | 1 (1.000) |     4.12 | Aleksib, b1t, iM, jL, w0nderful |
|           31 |       65 | 2024-08-03 | Liquid       | L   | 1.000      | -            | -                | -                | -         |   -25.60 | Aleksib, b1t, iM, jL, w0nderful |
|           30 |       99 | 2024-08-02 | BIG          | W   | 1.000      | -            | -                | -                | 1 (1.000) |     0.96 | Aleksib, b1t, iM, jL, w0nderful |
|           29 |      144 | 2024-08-01 | Liquid       | L   | 1.000      | -            | -                | -                | -         |   -26.87 | Aleksib, b1t, iM, jL, w0nderful |
|           28 |      194 | 2024-07-31 | BIG          | W   | 1.000      | -            | -                | -                | 1 (1.000) |     0.72 | Aleksib, b1t, iM, jL, w0nderful |
|           27 |      512 | 2024-07-21 | G2           | W   | 1.000      | 1.000        | 1.000 (1.000)    | 0.489 (0.489)    | 1 (1.000) |    16.18 | Aleksib, b1t, iM, jL, w0nderful |
|           26 |      545 | 2024-07-20 | MOUZ         | W   | 1.000      | 1.000        | 1.000 (1.000)    | 0.365 (0.365)    | 1 (1.000) |    13.11 | Aleksib, b1t, iM, jL, w0nderful |
|           25 |      575 | 2024-07-19 | FaZe         | W   | 1.000      | 1.000        | 0.626 (0.626)    | 0.391 (0.391)    | 1 (1.000) |     7.31 | Aleksib, b1t, iM, jL, w0nderful |
|           24 |      714 | 2024-07-17 | FURIA        | W   | 1.000      | 1.000        | 0.284 (0.284)    | 0.479 (0.479)    | 1 (1.000) |     4.25 | Aleksib, b1t, iM, jL, w0nderful |
|           23 |     1032 | 2024-06-16 | Spirit       | L   | 0.861      | -            | -                | -                | -         |   -13.52 | Aleksib, b1t, iM, jL, w0nderful |
|           22 |     1053 | 2024-06-15 | Virtus.pro   | W   | 0.856      | 0.729        | 0.498 (0.311)    | 0.316 (0.197)    | 1 (0.856) |     5.11 | Aleksib, b1t, iM, jL, w0nderful |
|           21 |     1143 | 2024-06-13 | FaZe         | W   | 0.841      | 0.729        | 0.626 (0.384)    | 0.391 (0.240)    | 1 (0.841) |     6.62 | Aleksib, b1t, iM, jL, w0nderful |
|           20 |     1172 | 2024-06-12 | Astralis     | W   | 0.834      | 0.729        | -                | 0.412 (0.251)    | 1 (0.834) |     6.59 | Aleksib, b1t, iM, jL, w0nderful |
|           19 |     1714 | 2024-05-29 | HEROIC       | L   | 0.742      | -            | -                | -                | -         |   -20.72 | Aleksib, b1t, iM, jL, w0nderful |
|           18 |     1735 | 2024-05-28 | Spirit       | L   | 0.735      | -            | -                | -                | -         |   -12.82 | Aleksib, b1t, iM, jL, w0nderful |
|           17 |     1753 | 2024-05-27 | BIG          | W   | 0.729      | -            | -                | -                | -         |     0.57 | Aleksib, b1t, iM, jL, w0nderful |
|           16 |     2319 | 2024-05-08 | FaZe         | L   | 0.602      | -            | -                | -                | -         |   -14.90 | Aleksib, b1t, iM, jL, w0nderful |
|           15 |     2369 | 2024-05-05 | Complexity   | L   | 0.582      | -            | -                | -                | -         |   -15.70 | Aleksib, b1t, iM, jL, w0nderful |
|           14 |     2443 | 2024-05-02 | BIG          | W   | 0.560      | -            | -                | -                | -         |     0.36 | Aleksib, b1t, iM, jL, w0nderful |
|           13 |     2466 | 2024-05-01 | FlyQuest     | W   | 0.554      | -            | -                | -                | -         |     0.19 | Aleksib, b1t, iM, jL, w0nderful |
|           12 |     3297 | 2024-03-31 | FaZe         | W   | 0.349      | -            | -                | -                | -         |     1.90 | Aleksib, b1t, iM, jL, w0nderful |
|           11 |     3302 | 2024-03-30 | G2           | W   | 0.343      | 1.000        | 1.000 (0.343)    | -                | -         |     5.75 | Aleksib, b1t, iM, jL, w0nderful |
|           10 |     3312 | 2024-03-29 | Eternal Fire | W   | 0.335      | 1.000        | 0.739 (0.247)    | -                | -         |     2.02 | Aleksib, b1t, iM, jL, w0nderful |
|            9 |     3405 | 2024-03-24 | paiN         | W   | 0.302      | 1.000        | -                | 0.857 (0.259)    | -         |     0.43 | Aleksib, b1t, iM, jL, w0nderful |
|            8 |     3414 | 2024-03-23 | Cloud9       | L   | 0.296      | -            | -                | -                | -         |    -9.27 | Aleksib, b1t, iM, jL, w0nderful |
|            7 |     3430 | 2024-03-22 | Spirit       | L   | 0.288      | -            | -                | -                | -         |    -5.47 | Aleksib, b1t, iM, jL, w0nderful |
|            6 |     3446 | 2024-03-21 | G2           | W   | 0.283      | 1.000        | 1.000 (0.283)    | -                | -         |     4.76 | Aleksib, b1t, iM, jL, w0nderful |
|            5 |     3463 | 2024-03-21 | The MongolZ  | W   | 0.281      | 1.000        | 1.000 (0.281)    | 0.709 (0.199)    | -         |     3.99 | Aleksib, b1t, iM, jL, w0nderful |
|            4 |     4243 | 2024-02-16 | BetBoom      | W   | 0.055      | -            | -                | -                | -         |     0.07 | Aleksib, b1t, iM, jL, w0nderful |
|            3 |     4272 | 2024-02-15 | Virtus.pro   | L   | 0.048      | -            | -                | -                | -         |    -1.25 | Aleksib, b1t, iM, jL, w0nderful |
|            2 |     4303 | 2024-02-14 | Enterprise   | W   | 0.043      | -            | -                | -                | -         |     0.00 | Aleksib, b1t, iM, jL, w0nderful |
|            1 |     4321 | 2024-02-14 | KOI          | W   | 0.041      | -            | -                | -                | -         |     0.01 | Aleksib, b1t, iM, jL, w0nderful |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($678,742.64)
- Divide that value by the 5th highest value among all rosters ($320,603.98)
- The final value (1.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-04 |      1.000 | $12,500.00     | $12,500.00      |
| 2024-07-21 |      1.000 | $400,000.00    | $400,000.00     |
| 2024-06-16 |      0.861 | $85,000.00     | $73,194.44      |
| 2024-06-02 |      0.769 | $5,000.00      | $3,844.44       |
| 2024-05-12 |      0.628 | $23,500.00     | $14,759.31      |
| 2024-03-31 |      0.349 | $500,000.00    | $174,444.44     |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
