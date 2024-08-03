### Roster Details<br />
Team Name: Natus Vincere<br />
Roster: Aleksib, b1t, iM, jL, w0nderful<br />
Global Rank: [3](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [3]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1930.7<br />
<br />
Final Rank Value (1930.7) = Starting Rank Value (1976.1) + Head To Head Adjustments (-45.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 1.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.762[<sup>2</sup>](#table1)
- Opponent Network: 0.319[<sup>2</sup>](#table1)
- LAN Wins: 1.000[<sup>2</sup>](#table1)

The average of these factors is 0.770<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1976.1
- 400 + ( ( 0.770 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 1976.1


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
|           32 |       28 | 2024-08-02 | BIG          | W   | 1.000      | -            | -                | -                | 1 (1.000) |     0.97 | Aleksib, b1t, iM, jL, w0nderful |
|           31 |       59 | 2024-08-01 | Liquid       | L   | 1.000      | -            | -                | -                | -         |   -28.12 | Aleksib, b1t, iM, jL, w0nderful |
|           30 |      105 | 2024-07-31 | BIG          | W   | 1.000      | -            | -                | -                | 1 (1.000) |     0.72 | Aleksib, b1t, iM, jL, w0nderful |
|           29 |      422 | 2024-07-21 | G2           | W   | 1.000      | 1.000        | 1.000 (1.000)    | 0.516 (0.516)    | 1 (1.000) |    15.89 | Aleksib, b1t, iM, jL, w0nderful |
|           28 |      455 | 2024-07-20 | MOUZ         | W   | 1.000      | 1.000        | 1.000 (1.000)    | 0.347 (0.347)    | 1 (1.000) |    11.36 | Aleksib, b1t, iM, jL, w0nderful |
|           27 |      485 | 2024-07-19 | FaZe         | W   | 1.000      | 1.000        | 0.644 (0.644)    | 0.418 (0.418)    | 1 (1.000) |     7.54 | Aleksib, b1t, iM, jL, w0nderful |
|           26 |      623 | 2024-07-17 | FURIA        | W   | 1.000      | 1.000        | 0.284 (0.284)    | 0.508 (0.508)    | 1 (1.000) |     3.94 | Aleksib, b1t, iM, jL, w0nderful |
|           25 |      928 | 2024-06-16 | Spirit       | L   | 0.879      | -            | -                | -                | -         |   -13.66 | Aleksib, b1t, iM, jL, w0nderful |
|           24 |      944 | 2024-06-15 | Virtus.pro   | W   | 0.874      | 0.729        | 0.496 (0.316)    | 0.335 (0.214)    | 1 (0.874) |     5.11 | Aleksib, b1t, iM, jL, w0nderful |
|           23 |     1025 | 2024-06-13 | FaZe         | W   | 0.859      | 0.729        | 0.644 (0.403)    | 0.418 (0.262)    | 1 (0.859) |     6.99 | Aleksib, b1t, iM, jL, w0nderful |
|           22 |     1052 | 2024-06-12 | Astralis     | W   | 0.852      | 0.729        | -                | 0.396 (0.246)    | 1 (0.852) |     5.95 | Aleksib, b1t, iM, jL, w0nderful |
|           21 |     1583 | 2024-05-29 | HEROIC       | L   | 0.760      | -            | -                | -                | -         |   -21.30 | Aleksib, b1t, iM, jL, w0nderful |
|           20 |     1604 | 2024-05-28 | Spirit       | L   | 0.753      | -            | -                | -                | -         |   -13.06 | Aleksib, b1t, iM, jL, w0nderful |
|           19 |     1622 | 2024-05-27 | BIG          | W   | 0.748      | -            | -                | -                | 1 (0.748) |     0.60 | Aleksib, b1t, iM, jL, w0nderful |
|           18 |     2185 | 2024-05-08 | FaZe         | L   | 0.620      | -            | -                | -                | -         |   -15.19 | Aleksib, b1t, iM, jL, w0nderful |
|           17 |     2235 | 2024-05-05 | Complexity   | L   | 0.600      | -            | -                | -                | -         |   -16.24 | Aleksib, b1t, iM, jL, w0nderful |
|           16 |     2309 | 2024-05-02 | BIG          | W   | 0.579      | -            | -                | -                | -         |     0.38 | Aleksib, b1t, iM, jL, w0nderful |
|           15 |     2332 | 2024-05-01 | FlyQuest     | W   | 0.572      | -            | -                | -                | -         |     0.20 | Aleksib, b1t, iM, jL, w0nderful |
|           14 |     3162 | 2024-03-31 | FaZe         | W   | 0.367      | -            | -                | -                | -         |     2.12 | Aleksib, b1t, iM, jL, w0nderful |
|           13 |     3167 | 2024-03-30 | G2           | W   | 0.361      | 1.000        | 1.000 (0.361)    | 0.516 (0.186)    | -         |     5.98 | Aleksib, b1t, iM, jL, w0nderful |
|           12 |     3177 | 2024-03-29 | Eternal Fire | W   | 0.353      | 1.000        | 0.746 (0.263)    | -                | -         |     2.15 | Aleksib, b1t, iM, jL, w0nderful |
|           11 |     3267 | 2024-03-24 | paiN         | W   | 0.320      | 1.000        | -                | 0.859 (0.275)    | -         |     0.37 | Aleksib, b1t, iM, jL, w0nderful |
|           10 |     3276 | 2024-03-23 | Cloud9       | L   | 0.314      | -            | -                | -                | -         |    -9.83 | Aleksib, b1t, iM, jL, w0nderful |
|            9 |     3290 | 2024-03-22 | Spirit       | L   | 0.307      | -            | -                | -                | -         |    -5.78 | Aleksib, b1t, iM, jL, w0nderful |
|            8 |     3306 | 2024-03-21 | G2           | W   | 0.301      | 1.000        | 1.000 (0.301)    | -                | -         |     5.02 | Aleksib, b1t, iM, jL, w0nderful |
|            7 |     3323 | 2024-03-21 | The MongolZ  | W   | 0.299      | 1.000        | 1.000 (0.299)    | 0.745 (0.223)    | -         |     4.20 | Aleksib, b1t, iM, jL, w0nderful |
|            6 |     4099 | 2024-02-16 | BetBoom      | W   | 0.073      | -            | -                | -                | -         |     0.10 | Aleksib, b1t, iM, jL, w0nderful |
|            5 |     4128 | 2024-02-15 | Virtus.pro   | L   | 0.066      | -            | -                | -                | -         |    -1.71 | Aleksib, b1t, iM, jL, w0nderful |
|            4 |     4159 | 2024-02-14 | Enterprise   | W   | 0.061      | -            | -                | -                | -         |     0.01 | Aleksib, b1t, iM, jL, w0nderful |
|            3 |     4177 | 2024-02-14 | KOI          | W   | 0.059      | -            | -                | -                | -         |     0.01 | Aleksib, b1t, iM, jL, w0nderful |
|            2 |     4273 | 2024-02-06 | Falcons      | L   | 0.006      | -            | -                | -                | -         |    -0.19 | Aleksib, b1t, iM, jL, w0nderful |
|            1 |     4281 | 2024-02-05 | Eternal Fire | W   | 0.001      | -            | -                | -                | -         |     0.00 | Aleksib, b1t, iM, jL, w0nderful |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($678,302.57)
- Divide that value by the 5th highest value among all rosters ($325,971.18)
- The final value (1.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-21 |      1.000 | $400,000.00    | $400,000.00     |
| 2024-06-16 |      0.879 | $85,000.00     | $74,733.10      |
| 2024-06-02 |      0.787 | $5,000.00      | $3,934.95       |
| 2024-05-12 |      0.646 | $23,500.00     | $15,184.70      |
| 2024-03-31 |      0.367 | $500,000.00    | $183,495.37     |
| 2024-02-11 |      0.040 | $24,000.00     | $954.44         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
