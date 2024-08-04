### Roster Details<br />
Team Name: Natus Vincere<br />
Roster: Aleksib, b1t, iM, jL, w0nderful<br />
Global Rank: [3](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [3]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1912.1<br />
<br />
Final Rank Value (1912.1) = Starting Rank Value (1973.6) + Head To Head Adjustments (-61.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 1.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.760[<sup>2</sup>](#table1)
- Opponent Network: 0.318[<sup>2</sup>](#table1)
- LAN Wins: 1.000[<sup>2</sup>](#table1)

The average of these factors is 0.769<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1973.6
- 400 + ( ( 0.769 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 1973.6


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
|           32 |        4 | 2024-08-04 | Complexity   | W   | 1.000      | 0.581        | -                | 0.380 (0.221)    | 1 (1.000) |     4.15 | Aleksib, b1t, iM, jL, w0nderful |
|           31 |       33 | 2024-08-03 | Liquid       | L   | 1.000      | -            | -                | -                | -         |   -25.60 | Aleksib, b1t, iM, jL, w0nderful |
|           30 |       67 | 2024-08-02 | BIG          | W   | 1.000      | -            | -                | -                | 1 (1.000) |     0.97 | Aleksib, b1t, iM, jL, w0nderful |
|           29 |      112 | 2024-08-01 | Liquid       | L   | 1.000      | -            | -                | -                | -         |   -26.86 | Aleksib, b1t, iM, jL, w0nderful |
|           28 |      162 | 2024-07-31 | BIG          | W   | 1.000      | -            | -                | -                | 1 (1.000) |     0.72 | Aleksib, b1t, iM, jL, w0nderful |
|           27 |      480 | 2024-07-21 | G2           | W   | 1.000      | 1.000        | 1.000 (1.000)    | 0.498 (0.498)    | 1 (1.000) |    16.12 | Aleksib, b1t, iM, jL, w0nderful |
|           26 |      513 | 2024-07-20 | MOUZ         | W   | 1.000      | 1.000        | 1.000 (1.000)    | 0.374 (0.374)    | 1 (1.000) |    13.18 | Aleksib, b1t, iM, jL, w0nderful |
|           25 |      543 | 2024-07-19 | FaZe         | W   | 1.000      | 1.000        | 0.638 (0.638)    | 0.402 (0.402)    | 1 (1.000) |     7.50 | Aleksib, b1t, iM, jL, w0nderful |
|           24 |      682 | 2024-07-17 | FURIA        | W   | 1.000      | 1.000        | 0.284 (0.284)    | 0.490 (0.490)    | 1 (1.000) |     4.18 | Aleksib, b1t, iM, jL, w0nderful |
|           23 |     1000 | 2024-06-16 | Spirit       | L   | 0.873      | -            | -                | -                | -         |   -13.65 | Aleksib, b1t, iM, jL, w0nderful |
|           22 |     1021 | 2024-06-15 | Virtus.pro   | W   | 0.867      | 0.729        | 0.497 (0.314)    | 0.323 (0.204)    | 1 (0.867) |     5.23 | Aleksib, b1t, iM, jL, w0nderful |
|           21 |     1111 | 2024-06-13 | FaZe         | W   | 0.852      | 0.729        | 0.638 (0.396)    | 0.402 (0.250)    | 1 (0.852) |     6.90 | Aleksib, b1t, iM, jL, w0nderful |
|           20 |     1140 | 2024-06-12 | Astralis     | W   | 0.846      | 0.729        | -                | 0.421 (0.260)    | 1 (0.846) |     6.72 | Aleksib, b1t, iM, jL, w0nderful |
|           19 |     1682 | 2024-05-29 | HEROIC       | L   | 0.753      | -            | -                | -                | -         |   -21.00 | Aleksib, b1t, iM, jL, w0nderful |
|           18 |     1703 | 2024-05-28 | Spirit       | L   | 0.747      | -            | -                | -                | -         |   -13.01 | Aleksib, b1t, iM, jL, w0nderful |
|           17 |     1721 | 2024-05-27 | BIG          | W   | 0.741      | -            | -                | -                | -         |     0.59 | Aleksib, b1t, iM, jL, w0nderful |
|           16 |     2287 | 2024-05-08 | FaZe         | L   | 0.614      | -            | -                | -                | -         |   -15.04 | Aleksib, b1t, iM, jL, w0nderful |
|           15 |     2337 | 2024-05-05 | Complexity   | L   | 0.594      | -            | -                | -                | -         |   -15.97 | Aleksib, b1t, iM, jL, w0nderful |
|           14 |     2411 | 2024-05-02 | BIG          | W   | 0.572      | -            | -                | -                | -         |     0.37 | Aleksib, b1t, iM, jL, w0nderful |
|           13 |     2434 | 2024-05-01 | FlyQuest     | W   | 0.565      | -            | -                | -                | -         |     0.20 | Aleksib, b1t, iM, jL, w0nderful |
|           12 |     3265 | 2024-03-31 | FaZe         | W   | 0.360      | -            | -                | -                | -         |     2.03 | Aleksib, b1t, iM, jL, w0nderful |
|           11 |     3270 | 2024-03-30 | G2           | W   | 0.354      | 1.000        | 1.000 (0.354)    | -                | -         |     5.92 | Aleksib, b1t, iM, jL, w0nderful |
|           10 |     3280 | 2024-03-29 | Eternal Fire | W   | 0.347      | 1.000        | 0.742 (0.257)    | -                | -         |     2.11 | Aleksib, b1t, iM, jL, w0nderful |
|            9 |     3373 | 2024-03-24 | paiN         | W   | 0.314      | 1.000        | -                | 0.867 (0.272)    | -         |     0.46 | Aleksib, b1t, iM, jL, w0nderful |
|            8 |     3382 | 2024-03-23 | Cloud9       | L   | 0.307      | -            | -                | -                | -         |    -9.63 | Aleksib, b1t, iM, jL, w0nderful |
|            7 |     3398 | 2024-03-22 | Spirit       | L   | 0.300      | -            | -                | -                | -         |    -5.69 | Aleksib, b1t, iM, jL, w0nderful |
|            6 |     3414 | 2024-03-21 | G2           | W   | 0.294      | 1.000        | 1.000 (0.294)    | -                | -         |     4.95 | Aleksib, b1t, iM, jL, w0nderful |
|            5 |     3431 | 2024-03-21 | The MongolZ  | W   | 0.292      | 1.000        | 1.000 (0.292)    | 0.721 (0.211)    | -         |     4.11 | Aleksib, b1t, iM, jL, w0nderful |
|            4 |     4211 | 2024-02-16 | BetBoom      | W   | 0.067      | -            | -                | -                | -         |     0.09 | Aleksib, b1t, iM, jL, w0nderful |
|            3 |     4240 | 2024-02-15 | Virtus.pro   | L   | 0.060      | -            | -                | -                | -         |    -1.54 | Aleksib, b1t, iM, jL, w0nderful |
|            2 |     4271 | 2024-02-14 | Enterprise   | W   | 0.054      | -            | -                | -                | -         |     0.01 | Aleksib, b1t, iM, jL, w0nderful |
|            1 |     4289 | 2024-02-14 | KOI          | W   | 0.052      | -            | -                | -                | -         |     0.01 | Aleksib, b1t, iM, jL, w0nderful |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($685,829.13)
- Divide that value by the 5th highest value among all rosters ($324,028.83)
- The final value (1.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-04 |      1.000 | $12,500.00     | $12,500.00      |
| 2024-07-21 |      1.000 | $400,000.00    | $400,000.00     |
| 2024-06-16 |      0.873 | $85,000.00     | $74,176.27      |
| 2024-06-02 |      0.780 | $5,000.00      | $3,902.20       |
| 2024-05-12 |      0.640 | $23,500.00     | $15,030.75      |
| 2024-03-31 |      0.360 | $500,000.00    | $180,219.91     |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
