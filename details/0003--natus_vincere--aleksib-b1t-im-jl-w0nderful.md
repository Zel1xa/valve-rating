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
Final Rank Value (1911.8) = Starting Rank Value (1973.0) + Head To Head Adjustments (-61.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 1.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.758[<sup>2</sup>](#table1)
- Opponent Network: 0.315[<sup>2</sup>](#table1)
- LAN Wins: 1.000[<sup>2</sup>](#table1)

The average of these factors is 0.768<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1973.0
- 400 + ( ( 0.768 - 0.000 ) / ( 0.781 - 0.000 ) ) * 1600 = 1973.0


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
|           32 |       21 | 2024-08-04 | Complexity   | W   | 1.000      | 0.581        | -                | 0.378 (0.220)    | 1 (1.000) |     4.13 | Aleksib, b1t, iM, jL, w0nderful |
|           31 |       50 | 2024-08-03 | Liquid       | L   | 1.000      | -            | -                | -                | -         |   -25.59 | Aleksib, b1t, iM, jL, w0nderful |
|           30 |       84 | 2024-08-02 | BIG          | W   | 1.000      | -            | -                | -                | 1 (1.000) |     0.97 | Aleksib, b1t, iM, jL, w0nderful |
|           29 |      129 | 2024-08-01 | Liquid       | L   | 1.000      | -            | -                | -                | -         |   -26.86 | Aleksib, b1t, iM, jL, w0nderful |
|           28 |      179 | 2024-07-31 | BIG          | W   | 1.000      | -            | -                | -                | 1 (1.000) |     0.72 | Aleksib, b1t, iM, jL, w0nderful |
|           27 |      497 | 2024-07-21 | G2           | W   | 1.000      | 1.000        | 1.000 (1.000)    | 0.496 (0.496)    | 1 (1.000) |    16.15 | Aleksib, b1t, iM, jL, w0nderful |
|           26 |      530 | 2024-07-20 | MOUZ         | W   | 1.000      | 1.000        | 1.000 (1.000)    | 0.371 (0.371)    | 1 (1.000) |    13.18 | Aleksib, b1t, iM, jL, w0nderful |
|           25 |      560 | 2024-07-19 | FaZe         | W   | 1.000      | 1.000        | 0.632 (0.632)    | 0.399 (0.399)    | 1 (1.000) |     7.40 | Aleksib, b1t, iM, jL, w0nderful |
|           24 |      699 | 2024-07-17 | FURIA        | W   | 1.000      | 1.000        | 0.284 (0.284)    | 0.487 (0.487)    | 1 (1.000) |     4.24 | Aleksib, b1t, iM, jL, w0nderful |
|           23 |     1017 | 2024-06-16 | Spirit       | L   | 0.867      | -            | -                | -                | -         |   -13.59 | Aleksib, b1t, iM, jL, w0nderful |
|           22 |     1038 | 2024-06-15 | Virtus.pro   | W   | 0.862      | 0.729        | 0.498 (0.313)    | 0.321 (0.202)    | 1 (0.862) |     5.17 | Aleksib, b1t, iM, jL, w0nderful |
|           21 |     1128 | 2024-06-13 | FaZe         | W   | 0.847      | 0.729        | 0.632 (0.390)    | 0.399 (0.246)    | 1 (0.847) |     6.76 | Aleksib, b1t, iM, jL, w0nderful |
|           20 |     1157 | 2024-06-12 | Astralis     | W   | 0.840      | 0.729        | -                | 0.419 (0.256)    | 1 (0.840) |     6.67 | Aleksib, b1t, iM, jL, w0nderful |
|           19 |     1699 | 2024-05-29 | HEROIC       | L   | 0.748      | -            | -                | -                | -         |   -20.85 | Aleksib, b1t, iM, jL, w0nderful |
|           18 |     1720 | 2024-05-28 | Spirit       | L   | 0.741      | -            | -                | -                | -         |   -12.92 | Aleksib, b1t, iM, jL, w0nderful |
|           17 |     1738 | 2024-05-27 | BIG          | W   | 0.735      | -            | -                | -                | -         |     0.58 | Aleksib, b1t, iM, jL, w0nderful |
|           16 |     2304 | 2024-05-08 | FaZe         | L   | 0.608      | -            | -                | -                | -         |   -14.97 | Aleksib, b1t, iM, jL, w0nderful |
|           15 |     2354 | 2024-05-05 | Complexity   | L   | 0.588      | -            | -                | -                | -         |   -15.84 | Aleksib, b1t, iM, jL, w0nderful |
|           14 |     2428 | 2024-05-02 | BIG          | W   | 0.566      | -            | -                | -                | -         |     0.36 | Aleksib, b1t, iM, jL, w0nderful |
|           13 |     2451 | 2024-05-01 | FlyQuest     | W   | 0.560      | -            | -                | -                | -         |     0.20 | Aleksib, b1t, iM, jL, w0nderful |
|           12 |     3282 | 2024-03-31 | FaZe         | W   | 0.355      | -            | -                | -                | -         |     1.96 | Aleksib, b1t, iM, jL, w0nderful |
|           11 |     3287 | 2024-03-30 | G2           | W   | 0.349      | 1.000        | 1.000 (0.349)    | -                | -         |     5.83 | Aleksib, b1t, iM, jL, w0nderful |
|           10 |     3297 | 2024-03-29 | Eternal Fire | W   | 0.341      | 1.000        | 0.740 (0.252)    | -                | -         |     2.06 | Aleksib, b1t, iM, jL, w0nderful |
|            9 |     3390 | 2024-03-24 | paiN         | W   | 0.308      | 1.000        | -                | 0.867 (0.267)    | -         |     0.44 | Aleksib, b1t, iM, jL, w0nderful |
|            8 |     3399 | 2024-03-23 | Cloud9       | L   | 0.302      | -            | -                | -                | -         |    -9.45 | Aleksib, b1t, iM, jL, w0nderful |
|            7 |     3415 | 2024-03-22 | Spirit       | L   | 0.294      | -            | -                | -                | -         |    -5.58 | Aleksib, b1t, iM, jL, w0nderful |
|            6 |     3431 | 2024-03-21 | G2           | W   | 0.289      | 1.000        | 1.000 (0.289)    | -                | -         |     4.86 | Aleksib, b1t, iM, jL, w0nderful |
|            5 |     3448 | 2024-03-21 | The MongolZ  | W   | 0.286      | 1.000        | 1.000 (0.286)    | 0.719 (0.206)    | -         |     4.07 | Aleksib, b1t, iM, jL, w0nderful |
|            4 |     4228 | 2024-02-16 | BetBoom      | W   | 0.061      | -            | -                | -                | -         |     0.08 | Aleksib, b1t, iM, jL, w0nderful |
|            3 |     4257 | 2024-02-15 | Virtus.pro   | L   | 0.054      | -            | -                | -                | -         |    -1.40 | Aleksib, b1t, iM, jL, w0nderful |
|            2 |     4288 | 2024-02-14 | Enterprise   | W   | 0.049      | -            | -                | -                | -         |     0.00 | Aleksib, b1t, iM, jL, w0nderful |
|            1 |     4306 | 2024-02-14 | KOI          | W   | 0.046      | -            | -                | -                | -         |     0.01 | Aleksib, b1t, iM, jL, w0nderful |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($682,321.39)
- Divide that value by the 5th highest value among all rosters ($322,333.56)
- The final value (1.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-04 |      1.000 | $12,500.00     | $12,500.00      |
| 2024-07-21 |      1.000 | $400,000.00    | $400,000.00     |
| 2024-06-16 |      0.867 | $85,000.00     | $73,690.28      |
| 2024-06-02 |      0.775 | $5,000.00      | $3,873.61       |
| 2024-05-12 |      0.634 | $23,500.00     | $14,896.39      |
| 2024-03-31 |      0.355 | $500,000.00    | $177,361.11     |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
