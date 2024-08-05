### Roster Details<br />
Team Name: Natus Vincere<br />
Roster: Aleksib, b1t, iM, jL, w0nderful<br />
Global Rank: [3](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [3]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1912.0<br />
<br />
Final Rank Value (1912.0) = Starting Rank Value (1973.3) + Head To Head Adjustments (-61.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 1.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.759[<sup>2</sup>](#table1)
- Opponent Network: 0.317[<sup>2</sup>](#table1)
- LAN Wins: 1.000[<sup>2</sup>](#table1)

The average of these factors is 0.769<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1973.3
- 400 + ( ( 0.769 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 1973.3


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
|           32 |        8 | 2024-08-04 | Complexity   | W   | 1.000      | 0.581        | -                | 0.380 (0.221)    | 1 (1.000) |     4.14 | Aleksib, b1t, iM, jL, w0nderful |
|           31 |       37 | 2024-08-03 | Liquid       | L   | 1.000      | -            | -                | -                | -         |   -25.59 | Aleksib, b1t, iM, jL, w0nderful |
|           30 |       71 | 2024-08-02 | BIG          | W   | 1.000      | -            | -                | -                | 1 (1.000) |     0.97 | Aleksib, b1t, iM, jL, w0nderful |
|           29 |      116 | 2024-08-01 | Liquid       | L   | 1.000      | -            | -                | -                | -         |   -26.85 | Aleksib, b1t, iM, jL, w0nderful |
|           28 |      166 | 2024-07-31 | BIG          | W   | 1.000      | -            | -                | -                | 1 (1.000) |     0.72 | Aleksib, b1t, iM, jL, w0nderful |
|           27 |      484 | 2024-07-21 | G2           | W   | 1.000      | 1.000        | 1.000 (1.000)    | 0.498 (0.498)    | 1 (1.000) |    16.13 | Aleksib, b1t, iM, jL, w0nderful |
|           26 |      517 | 2024-07-20 | MOUZ         | W   | 1.000      | 1.000        | 1.000 (1.000)    | 0.373 (0.373)    | 1 (1.000) |    13.15 | Aleksib, b1t, iM, jL, w0nderful |
|           25 |      547 | 2024-07-19 | FaZe         | W   | 1.000      | 1.000        | 0.635 (0.635)    | 0.401 (0.401)    | 1 (1.000) |     7.46 | Aleksib, b1t, iM, jL, w0nderful |
|           24 |      686 | 2024-07-17 | FURIA        | W   | 1.000      | 1.000        | 0.284 (0.284)    | 0.490 (0.490)    | 1 (1.000) |     4.20 | Aleksib, b1t, iM, jL, w0nderful |
|           23 |     1004 | 2024-06-16 | Spirit       | L   | 0.870      | -            | -                | -                | -         |   -13.63 | Aleksib, b1t, iM, jL, w0nderful |
|           22 |     1025 | 2024-06-15 | Virtus.pro   | W   | 0.865      | 0.729        | 0.497 (0.314)    | 0.323 (0.203)    | 1 (0.865) |     5.20 | Aleksib, b1t, iM, jL, w0nderful |
|           21 |     1115 | 2024-06-13 | FaZe         | W   | 0.850      | 0.729        | 0.635 (0.394)    | 0.401 (0.249)    | 1 (0.850) |     6.84 | Aleksib, b1t, iM, jL, w0nderful |
|           20 |     1144 | 2024-06-12 | Astralis     | W   | 0.843      | 0.729        | -                | 0.421 (0.259)    | 1 (0.843) |     6.72 | Aleksib, b1t, iM, jL, w0nderful |
|           19 |     1686 | 2024-05-29 | HEROIC       | L   | 0.751      | -            | -                | -                | -         |   -20.94 | Aleksib, b1t, iM, jL, w0nderful |
|           18 |     1707 | 2024-05-28 | Spirit       | L   | 0.744      | -            | -                | -                | -         |   -12.97 | Aleksib, b1t, iM, jL, w0nderful |
|           17 |     1725 | 2024-05-27 | BIG          | W   | 0.739      | -            | -                | -                | -         |     0.58 | Aleksib, b1t, iM, jL, w0nderful |
|           16 |     2291 | 2024-05-08 | FaZe         | L   | 0.611      | -            | -                | -                | -         |   -15.01 | Aleksib, b1t, iM, jL, w0nderful |
|           15 |     2341 | 2024-05-05 | Complexity   | L   | 0.591      | -            | -                | -                | -         |   -15.92 | Aleksib, b1t, iM, jL, w0nderful |
|           14 |     2415 | 2024-05-02 | BIG          | W   | 0.570      | -            | -                | -                | -         |     0.36 | Aleksib, b1t, iM, jL, w0nderful |
|           13 |     2438 | 2024-05-01 | FlyQuest     | W   | 0.563      | -            | -                | -                | -         |     0.20 | Aleksib, b1t, iM, jL, w0nderful |
|           12 |     3269 | 2024-03-31 | FaZe         | W   | 0.358      | -            | -                | -                | -         |     2.00 | Aleksib, b1t, iM, jL, w0nderful |
|           11 |     3274 | 2024-03-30 | G2           | W   | 0.352      | 1.000        | 1.000 (0.352)    | -                | -         |     5.88 | Aleksib, b1t, iM, jL, w0nderful |
|           10 |     3284 | 2024-03-29 | Eternal Fire | W   | 0.344      | 1.000        | 0.741 (0.255)    | -                | -         |     2.09 | Aleksib, b1t, iM, jL, w0nderful |
|            9 |     3377 | 2024-03-24 | paiN         | W   | 0.311      | 1.000        | -                | 0.868 (0.270)    | -         |     0.45 | Aleksib, b1t, iM, jL, w0nderful |
|            8 |     3386 | 2024-03-23 | Cloud9       | L   | 0.305      | -            | -                | -                | -         |    -9.55 | Aleksib, b1t, iM, jL, w0nderful |
|            7 |     3402 | 2024-03-22 | Spirit       | L   | 0.298      | -            | -                | -                | -         |    -5.65 | Aleksib, b1t, iM, jL, w0nderful |
|            6 |     3418 | 2024-03-21 | G2           | W   | 0.292      | 1.000        | 1.000 (0.292)    | -                | -         |     4.91 | Aleksib, b1t, iM, jL, w0nderful |
|            5 |     3435 | 2024-03-21 | The MongolZ  | W   | 0.290      | 1.000        | 1.000 (0.290)    | 0.721 (0.209)    | -         |     4.10 | Aleksib, b1t, iM, jL, w0nderful |
|            4 |     4215 | 2024-02-16 | BetBoom      | W   | 0.064      | -            | -                | -                | -         |     0.09 | Aleksib, b1t, iM, jL, w0nderful |
|            3 |     4244 | 2024-02-15 | Virtus.pro   | L   | 0.057      | -            | -                | -                | -         |    -1.48 | Aleksib, b1t, iM, jL, w0nderful |
|            2 |     4275 | 2024-02-14 | Enterprise   | W   | 0.052      | -            | -                | -                | -         |     0.00 | Aleksib, b1t, iM, jL, w0nderful |
|            1 |     4293 | 2024-02-14 | KOI          | W   | 0.050      | -            | -                | -                | -         |     0.01 | Aleksib, b1t, iM, jL, w0nderful |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($684,366.39)
- Divide that value by the 5th highest value among all rosters ($323,321.90)
- The final value (1.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-04 |      1.000 | $12,500.00     | $12,500.00      |
| 2024-07-21 |      1.000 | $400,000.00    | $400,000.00     |
| 2024-06-16 |      0.870 | $85,000.00     | $73,973.61      |
| 2024-06-02 |      0.778 | $5,000.00      | $3,890.28       |
| 2024-05-12 |      0.637 | $23,500.00     | $14,974.72      |
| 2024-03-31 |      0.358 | $500,000.00    | $179,027.78     |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
