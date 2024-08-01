### Roster Details<br />
Team Name: Natus Vincere<br />
Roster: Aleksib, b1t, iM, jL, w0nderful<br />
Global Rank: [2](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [2]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1938.2<br />
<br />
Final Rank Value (1938.2) = Starting Rank Value (1984.8) + Head To Head Adjustments (-46.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 1.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.764[<sup>2</sup>](#table1)
- Opponent Network: 0.317[<sup>2</sup>](#table1)
- LAN Wins: 1.000[<sup>2</sup>](#table1)

The average of these factors is 0.770<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1984.8
- 400 + ( ( 0.770 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1984.8


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
|           32 |        4 | 2024-08-01 | Liquid       | L   | 1.000      | -            | -                | -                | -         |   -28.00 | Aleksib, b1t, iM, jL, w0nderful |
|           31 |       48 | 2024-07-31 | BIG          | W   | 1.000      | -            | -                | -                | 1 (1.000) |     0.52 | Aleksib, b1t, iM, jL, w0nderful |
|           30 |      367 | 2024-07-21 | G2           | W   | 1.000      | 1.000        | 1.000 (1.000)    | 0.500 (0.500)    | 1 (1.000) |    15.67 | Aleksib, b1t, iM, jL, w0nderful |
|           29 |      402 | 2024-07-20 | MOUZ         | W   | 1.000      | 1.000        | 1.000 (1.000)    | 0.378 (0.378)    | 1 (1.000) |    13.52 | Aleksib, b1t, iM, jL, w0nderful |
|           28 |      433 | 2024-07-19 | FaZe         | W   | 1.000      | 1.000        | 0.637 (0.637)    | 0.408 (0.408)    | 1 (1.000) |     7.86 | Aleksib, b1t, iM, jL, w0nderful |
|           27 |      577 | 2024-07-17 | FURIA        | W   | 1.000      | 1.000        | 0.286 (0.286)    | 0.494 (0.494)    | 1 (1.000) |     3.96 | Aleksib, b1t, iM, jL, w0nderful |
|           26 |      902 | 2024-06-16 | Spirit       | L   | 0.892      | -            | -                | -                | -         |   -14.00 | Aleksib, b1t, iM, jL, w0nderful |
|           25 |      920 | 2024-06-15 | Virtus.pro   | W   | 0.887      | 0.729        | 0.484 (0.313)    | 0.326 (0.211)    | 1 (0.887) |     5.19 | Aleksib, b1t, iM, jL, w0nderful |
|           24 |     1003 | 2024-06-13 | FaZe         | W   | 0.872      | 0.729        | 0.637 (0.405)    | 0.408 (0.259)    | 1 (0.872) |     7.43 | Aleksib, b1t, iM, jL, w0nderful |
|           23 |     1032 | 2024-06-12 | Astralis     | W   | 0.865      | 0.729        | -                | 0.385 (0.243)    | 1 (0.865) |     5.79 | Aleksib, b1t, iM, jL, w0nderful |
|           22 |     1591 | 2024-05-29 | HEROIC       | L   | 0.773      | -            | -                | -                | -         |   -21.68 | Aleksib, b1t, iM, jL, w0nderful |
|           21 |     1612 | 2024-05-28 | Spirit       | L   | 0.766      | -            | -                | -                | -         |   -13.43 | Aleksib, b1t, iM, jL, w0nderful |
|           20 |     1630 | 2024-05-27 | BIG          | W   | 0.761      | -            | -                | -                | 1 (0.761) |     0.40 | Aleksib, b1t, iM, jL, w0nderful |
|           19 |     2235 | 2024-05-08 | FaZe         | L   | 0.633      | -            | -                | -                | -         |   -15.25 | Aleksib, b1t, iM, jL, w0nderful |
|           18 |     2285 | 2024-05-05 | Complexity   | L   | 0.613      | -            | -                | -                | -         |   -16.81 | Aleksib, b1t, iM, jL, w0nderful |
|           17 |     2360 | 2024-05-02 | BIG          | W   | 0.592      | -            | -                | -                | 1 (0.592) |     0.25 | Aleksib, b1t, iM, jL, w0nderful |
|           16 |     2384 | 2024-05-01 | FlyQuest     | W   | 0.585      | -            | -                | -                | -         |     0.21 | Aleksib, b1t, iM, jL, w0nderful |
|           15 |     3235 | 2024-03-31 | FaZe         | W   | 0.380      | -            | -                | -                | -         |     2.33 | Aleksib, b1t, iM, jL, w0nderful |
|           14 |     3240 | 2024-03-30 | G2           | W   | 0.374      | 1.000        | 1.000 (0.374)    | 0.500 (0.187)    | -         |     6.08 | Aleksib, b1t, iM, jL, w0nderful |
|           13 |     3250 | 2024-03-29 | Eternal Fire | W   | 0.366      | 1.000        | 0.757 (0.277)    | -                | -         |     2.32 | Aleksib, b1t, iM, jL, w0nderful |
|           12 |     3348 | 2024-03-24 | paiN         | W   | 0.333      | 1.000        | -                | 0.801 (0.267)    | -         |     0.36 | Aleksib, b1t, iM, jL, w0nderful |
|           11 |     3357 | 2024-03-23 | Cloud9       | L   | 0.327      | -            | -                | -                | -         |   -10.23 | Aleksib, b1t, iM, jL, w0nderful |
|           10 |     3373 | 2024-03-22 | Spirit       | L   | 0.320      | -            | -                | -                | -         |    -6.13 | Aleksib, b1t, iM, jL, w0nderful |
|            9 |     3389 | 2024-03-21 | G2           | W   | 0.314      | 1.000        | 1.000 (0.314)    | -                | -         |     5.12 | Aleksib, b1t, iM, jL, w0nderful |
|            8 |     3406 | 2024-03-21 | The MongolZ  | W   | 0.312      | 1.000        | 1.000 (0.312)    | 0.719 (0.224)    | -         |     4.31 | Aleksib, b1t, iM, jL, w0nderful |
|            7 |     4207 | 2024-02-16 | BetBoom      | W   | 0.086      | -            | -                | -                | -         |     0.12 | Aleksib, b1t, iM, jL, w0nderful |
|            6 |     4236 | 2024-02-15 | Virtus.pro   | L   | 0.079      | -            | -                | -                | -         |    -2.05 | Aleksib, b1t, iM, jL, w0nderful |
|            5 |     4267 | 2024-02-14 | Enterprise   | W   | 0.074      | -            | -                | -                | -         |     0.01 | Aleksib, b1t, iM, jL, w0nderful |
|            4 |     4285 | 2024-02-14 | KOI          | W   | 0.072      | -            | -                | -                | -         |     0.01 | Aleksib, b1t, iM, jL, w0nderful |
|            3 |     4391 | 2024-02-06 | Falcons      | L   | 0.019      | -            | -                | -                | -         |    -0.58 | Aleksib, b1t, iM, jL, w0nderful |
|            2 |     4399 | 2024-02-05 | Eternal Fire | W   | 0.014      | -            | -                | -                | -         |     0.08 | Aleksib, b1t, iM, jL, w0nderful |
|            1 |     4419 | 2024-02-04 | Apeks        | W   | 0.006      | -            | -                | -                | -         |     0.00 | Aleksib, b1t, iM, jL, w0nderful |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($686,595.97)
- Divide that value by the 5th highest value among all rosters ($326,952.13)
- The final value (1.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-21 |      1.000 | $400,000.00    | $400,000.00     |
| 2024-06-16 |      0.892 | $85,000.00     | $75,838.89      |
| 2024-06-02 |      0.800 | $5,000.00      | $4,000.00       |
| 2024-05-12 |      0.659 | $23,500.00     | $15,490.42      |
| 2024-03-31 |      0.380 | $500,000.00    | $190,000.00     |
| 2024-02-11 |      0.053 | $24,000.00     | $1,266.67       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
