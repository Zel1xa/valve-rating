### Roster Details<br />
Team Name: Natus Vincere<br />
Roster: Aleksib, b1t, iM, jL, w0nderful<br />
Global Rank: [3](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [3]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1906.1<br />
<br />
Final Rank Value (1906.1) = Starting Rank Value (1971.4) + Head To Head Adjustments (-65.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 1.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.760[<sup>2</sup>](#table1)
- Opponent Network: 0.314[<sup>2</sup>](#table1)
- LAN Wins: 1.000[<sup>2</sup>](#table1)

The average of these factors is 0.769<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1971.4
- 400 + ( ( 0.769 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 1971.4


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
|           32 |       11 | 2024-08-03 | Liquid       | L   | 1.000      | -            | -                | -                | -         |   -25.61 | Aleksib, b1t, iM, jL, w0nderful |
|           31 |       45 | 2024-08-02 | BIG          | W   | 1.000      | -            | -                | -                | 1 (1.000) |     0.98 | Aleksib, b1t, iM, jL, w0nderful |
|           30 |       90 | 2024-08-01 | Liquid       | L   | 1.000      | -            | -                | -                | -         |   -26.87 | Aleksib, b1t, iM, jL, w0nderful |
|           29 |      138 | 2024-07-31 | BIG          | W   | 1.000      | -            | -                | -                | 1 (1.000) |     0.73 | Aleksib, b1t, iM, jL, w0nderful |
|           28 |      456 | 2024-07-21 | G2           | W   | 1.000      | 1.000        | 1.000 (1.000)    | 0.498 (0.498)    | 1 (1.000) |    16.18 | Aleksib, b1t, iM, jL, w0nderful |
|           27 |      489 | 2024-07-20 | MOUZ         | W   | 1.000      | 1.000        | 1.000 (1.000)    | 0.374 (0.374)    | 1 (1.000) |    13.23 | Aleksib, b1t, iM, jL, w0nderful |
|           26 |      519 | 2024-07-19 | FaZe         | W   | 1.000      | 1.000        | 0.639 (0.639)    | 0.402 (0.402)    | 1 (1.000) |     7.53 | Aleksib, b1t, iM, jL, w0nderful |
|           25 |      658 | 2024-07-17 | FURIA        | W   | 1.000      | 1.000        | 0.284 (0.284)    | 0.490 (0.490)    | 1 (1.000) |     4.20 | Aleksib, b1t, iM, jL, w0nderful |
|           24 |      976 | 2024-06-16 | Spirit       | L   | 0.874      | -            | -                | -                | -         |   -13.65 | Aleksib, b1t, iM, jL, w0nderful |
|           23 |      997 | 2024-06-15 | Virtus.pro   | W   | 0.868      | 0.729        | 0.497 (0.315)    | 0.323 (0.205)    | 1 (0.868) |     5.26 | Aleksib, b1t, iM, jL, w0nderful |
|           22 |     1087 | 2024-06-13 | FaZe         | W   | 0.853      | 0.729        | 0.639 (0.397)    | 0.402 (0.250)    | 1 (0.853) |     6.94 | Aleksib, b1t, iM, jL, w0nderful |
|           21 |     1116 | 2024-06-12 | Astralis     | W   | 0.847      | 0.729        | -                | 0.421 (0.260)    | 1 (0.847) |     6.79 | Aleksib, b1t, iM, jL, w0nderful |
|           20 |     1658 | 2024-05-29 | HEROIC       | L   | 0.755      | -            | -                | -                | -         |   -21.01 | Aleksib, b1t, iM, jL, w0nderful |
|           19 |     1679 | 2024-05-28 | Spirit       | L   | 0.748      | -            | -                | -                | -         |   -13.01 | Aleksib, b1t, iM, jL, w0nderful |
|           18 |     1697 | 2024-05-27 | BIG          | W   | 0.742      | -            | -                | -                | 1 (0.742) |     0.59 | Aleksib, b1t, iM, jL, w0nderful |
|           17 |     2263 | 2024-05-08 | FaZe         | L   | 0.615      | -            | -                | -                | -         |   -15.05 | Aleksib, b1t, iM, jL, w0nderful |
|           16 |     2313 | 2024-05-05 | Complexity   | L   | 0.595      | -            | -                | -                | -         |   -16.10 | Aleksib, b1t, iM, jL, w0nderful |
|           15 |     2387 | 2024-05-02 | BIG          | W   | 0.573      | -            | -                | -                | -         |     0.37 | Aleksib, b1t, iM, jL, w0nderful |
|           14 |     2410 | 2024-05-01 | FlyQuest     | W   | 0.566      | -            | -                | -                | -         |     0.20 | Aleksib, b1t, iM, jL, w0nderful |
|           13 |     3241 | 2024-03-31 | FaZe         | W   | 0.362      | -            | -                | -                | -         |     2.04 | Aleksib, b1t, iM, jL, w0nderful |
|           12 |     3246 | 2024-03-30 | G2           | W   | 0.355      | 1.000        | 1.000 (0.355)    | 0.498 (0.177)    | -         |     5.97 | Aleksib, b1t, iM, jL, w0nderful |
|           11 |     3256 | 2024-03-29 | Eternal Fire | W   | 0.348      | 1.000        | 0.742 (0.258)    | -                | -         |     2.14 | Aleksib, b1t, iM, jL, w0nderful |
|           10 |     3349 | 2024-03-24 | paiN         | W   | 0.315      | 1.000        | -                | 0.866 (0.273)    | -         |     0.47 | Aleksib, b1t, iM, jL, w0nderful |
|            9 |     3358 | 2024-03-23 | Cloud9       | L   | 0.309      | -            | -                | -                | -         |    -9.66 | Aleksib, b1t, iM, jL, w0nderful |
|            8 |     3374 | 2024-03-22 | Spirit       | L   | 0.301      | -            | -                | -                | -         |    -5.71 | Aleksib, b1t, iM, jL, w0nderful |
|            7 |     3390 | 2024-03-21 | G2           | W   | 0.295      | 1.000        | 1.000 (0.295)    | -                | -         |     4.99 | Aleksib, b1t, iM, jL, w0nderful |
|            6 |     3407 | 2024-03-21 | The MongolZ  | W   | 0.293      | 1.000        | 1.000 (0.293)    | 0.721 (0.211)    | -         |     4.16 | Aleksib, b1t, iM, jL, w0nderful |
|            5 |     4187 | 2024-02-16 | BetBoom      | W   | 0.068      | -            | -                | -                | -         |     0.10 | Aleksib, b1t, iM, jL, w0nderful |
|            4 |     4216 | 2024-02-15 | Virtus.pro   | L   | 0.061      | -            | -                | -                | -         |    -1.57 | Aleksib, b1t, iM, jL, w0nderful |
|            3 |     4247 | 2024-02-14 | Enterprise   | W   | 0.055      | -            | -                | -                | -         |     0.01 | Aleksib, b1t, iM, jL, w0nderful |
|            2 |     4265 | 2024-02-14 | KOI          | W   | 0.053      | -            | -                | -                | -         |     0.01 | Aleksib, b1t, iM, jL, w0nderful |
|            1 |     4361 | 2024-02-06 | Falcons      | L   | 0.001      | -            | -                | -                | -         |    -0.02 | Aleksib, b1t, iM, jL, w0nderful |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($674,805.17)
- Divide that value by the 5th highest value among all rosters ($324,344.55)
- The final value (1.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-21 |      1.000 | $400,000.00    | $400,000.00     |
| 2024-06-16 |      0.874 | $85,000.00     | $74,266.78      |
| 2024-06-02 |      0.782 | $5,000.00      | $3,907.52       |
| 2024-05-12 |      0.641 | $23,500.00     | $15,055.78      |
| 2024-03-31 |      0.362 | $500,000.00    | $180,752.31     |
| 2024-02-11 |      0.034 | $24,000.00     | $822.78         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
