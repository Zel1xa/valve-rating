### Roster Details<br />
Team Name: Natus Vincere<br />
Roster: Aleksib, b1t, iM, jL, w0nderful<br />
Global Rank: [2](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [2]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1928.5<br />
<br />
Final Rank Value (1928.5) = Starting Rank Value (1970.6) + Head To Head Adjustments (-42.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 1.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.761[<sup>2</sup>](#table1)
- Opponent Network: 0.313[<sup>2</sup>](#table1)
- LAN Wins: 1.000[<sup>2</sup>](#table1)

The average of these factors is 0.769<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1970.6
- 400 + ( ( 0.769 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 1970.6


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
|           31 |       34 | 2024-08-02 | BIG          | W   | 1.000      | -            | -                | -                | 1 (1.000) |     0.99 | Aleksib, b1t, iM, jL, w0nderful |
|           30 |       79 | 2024-08-01 | Liquid       | L   | 1.000      | -            | -                | -                | -         |   -28.05 | Aleksib, b1t, iM, jL, w0nderful |
|           29 |      127 | 2024-07-31 | BIG          | W   | 1.000      | -            | -                | -                | 1 (1.000) |     0.74 | Aleksib, b1t, iM, jL, w0nderful |
|           28 |      445 | 2024-07-21 | G2           | W   | 1.000      | 1.000        | 1.000 (1.000)    | 0.498 (0.498)    | 1 (1.000) |    16.17 | Aleksib, b1t, iM, jL, w0nderful |
|           27 |      478 | 2024-07-20 | MOUZ         | W   | 1.000      | 1.000        | 1.000 (1.000)    | 0.374 (0.374)    | 1 (1.000) |    13.24 | Aleksib, b1t, iM, jL, w0nderful |
|           26 |      508 | 2024-07-19 | FaZe         | W   | 1.000      | 1.000        | 0.643 (0.643)    | 0.403 (0.403)    | 1 (1.000) |     7.53 | Aleksib, b1t, iM, jL, w0nderful |
|           25 |      647 | 2024-07-17 | FURIA        | W   | 1.000      | 1.000        | 0.284 (0.284)    | 0.491 (0.491)    | 1 (1.000) |     4.18 | Aleksib, b1t, iM, jL, w0nderful |
|           24 |      964 | 2024-06-16 | Spirit       | L   | 0.877      | -            | -                | -                | -         |   -13.64 | Aleksib, b1t, iM, jL, w0nderful |
|           23 |      985 | 2024-06-15 | Virtus.pro   | W   | 0.872      | 0.729        | 0.496 (0.316)    | 0.324 (0.206)    | 1 (0.872) |     5.26 | Aleksib, b1t, iM, jL, w0nderful |
|           22 |     1075 | 2024-06-13 | FaZe         | W   | 0.857      | 0.729        | 0.643 (0.402)    | 0.403 (0.252)    | 1 (0.857) |     6.98 | Aleksib, b1t, iM, jL, w0nderful |
|           21 |     1104 | 2024-06-12 | Astralis     | W   | 0.851      | 0.729        | -                | 0.382 (0.237)    | 1 (0.851) |     5.96 | Aleksib, b1t, iM, jL, w0nderful |
|           20 |     1646 | 2024-05-29 | HEROIC       | L   | 0.758      | -            | -                | -                | -         |   -21.12 | Aleksib, b1t, iM, jL, w0nderful |
|           19 |     1667 | 2024-05-28 | Spirit       | L   | 0.752      | -            | -                | -                | -         |   -13.03 | Aleksib, b1t, iM, jL, w0nderful |
|           18 |     1685 | 2024-05-27 | BIG          | W   | 0.746      | -            | -                | -                | 1 (0.746) |     0.60 | Aleksib, b1t, iM, jL, w0nderful |
|           17 |     2251 | 2024-05-08 | FaZe         | L   | 0.619      | -            | -                | -                | -         |   -15.15 | Aleksib, b1t, iM, jL, w0nderful |
|           16 |     2301 | 2024-05-05 | Complexity   | L   | 0.599      | -            | -                | -                | -         |   -16.19 | Aleksib, b1t, iM, jL, w0nderful |
|           15 |     2375 | 2024-05-02 | BIG          | W   | 0.577      | -            | -                | -                | -         |     0.38 | Aleksib, b1t, iM, jL, w0nderful |
|           14 |     2398 | 2024-05-01 | FlyQuest     | W   | 0.570      | -            | -                | -                | -         |     0.20 | Aleksib, b1t, iM, jL, w0nderful |
|           13 |     3228 | 2024-03-31 | FaZe         | W   | 0.365      | -            | -                | -                | -         |     2.09 | Aleksib, b1t, iM, jL, w0nderful |
|           12 |     3233 | 2024-03-30 | G2           | W   | 0.359      | 1.000        | 1.000 (0.359)    | 0.498 (0.179)    | -         |     6.04 | Aleksib, b1t, iM, jL, w0nderful |
|           11 |     3243 | 2024-03-29 | Eternal Fire | W   | 0.351      | 1.000        | 0.743 (0.261)    | -                | -         |     2.17 | Aleksib, b1t, iM, jL, w0nderful |
|           10 |     3336 | 2024-03-24 | paiN         | W   | 0.319      | 1.000        | -                | 0.865 (0.276)    | -         |     0.48 | Aleksib, b1t, iM, jL, w0nderful |
|            9 |     3345 | 2024-03-23 | Cloud9       | L   | 0.312      | -            | -                | -                | -         |    -9.78 | Aleksib, b1t, iM, jL, w0nderful |
|            8 |     3361 | 2024-03-22 | Spirit       | L   | 0.305      | -            | -                | -                | -         |    -5.76 | Aleksib, b1t, iM, jL, w0nderful |
|            7 |     3377 | 2024-03-21 | G2           | W   | 0.299      | 1.000        | 1.000 (0.299)    | -                | -         |     5.07 | Aleksib, b1t, iM, jL, w0nderful |
|            6 |     3394 | 2024-03-21 | The MongolZ  | W   | 0.297      | 1.000        | 1.000 (0.297)    | 0.720 (0.214)    | -         |     4.19 | Aleksib, b1t, iM, jL, w0nderful |
|            5 |     4172 | 2024-02-16 | BetBoom      | W   | 0.071      | -            | -                | -                | -         |     0.10 | Aleksib, b1t, iM, jL, w0nderful |
|            4 |     4201 | 2024-02-15 | Virtus.pro   | L   | 0.065      | -            | -                | -                | -         |    -1.66 | Aleksib, b1t, iM, jL, w0nderful |
|            3 |     4232 | 2024-02-14 | Enterprise   | W   | 0.059      | -            | -                | -                | -         |     0.01 | Aleksib, b1t, iM, jL, w0nderful |
|            2 |     4250 | 2024-02-14 | KOI          | W   | 0.057      | -            | -                | -                | -         |     0.01 | Aleksib, b1t, iM, jL, w0nderful |
|            1 |     4346 | 2024-02-06 | Falcons      | L   | 0.005      | -            | -                | -                | -         |    -0.14 | Aleksib, b1t, iM, jL, w0nderful |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($677,210.56)
- Divide that value by the 5th highest value among all rosters ($325,463.29)
- The final value (1.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-21 |      1.000 | $400,000.00    | $400,000.00     |
| 2024-06-16 |      0.877 | $85,000.00     | $74,587.50      |
| 2024-06-02 |      0.785 | $5,000.00      | $3,926.39       |
| 2024-05-12 |      0.644 | $23,500.00     | $15,144.44      |
| 2024-03-31 |      0.365 | $500,000.00    | $182,638.89     |
| 2024-02-11 |      0.038 | $24,000.00     | $913.33         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
