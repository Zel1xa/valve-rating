### Roster Details<br />
Team Name: Lilmix<br />
Roster: bq, dex, L00m1, quix, SHiNE<br />
Global Rank: [109](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [78]( ../standings_europe.md)<br />
<br />
Final Rank Value:  841.4<br />
<br />
Final Rank Value (841.4) = Starting Rank Value (867.8) + Head To Head Adjustments (-26.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.378[<sup>1</sup>](#table2)
- Bounty Collected: 0.255[<sup>2</sup>](#table1)
- Opponent Network: 0.011[<sup>2</sup>](#table1)
- LAN Wins: 0.267[<sup>2</sup>](#table1)

The average of these factors is 0.228<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 867.8
- 400 + ( ( 0.228 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 867.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent        | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                      |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           10 |      242 | 2024-07-30 | INFINITE        | L   | 1.000      | -            | -                | -                | -         |   -25.23 | bq, dex, L00m1, quix, SHiNE |
|            9 |      428 | 2024-07-24 | ALTERNATE aTTaX | L   | 1.000      | -            | -                | -                | -         |   -16.84 | bq, dex, L00m1, quix, SHiNE |
|            8 |      659 | 2024-07-18 | kONO            | W   | 1.000      | 0.143        | 0.028 (0.004)    | 0.566 (0.081)    | 0 (0.000) |    13.36 | bq, dex, L00m1, quix, SHiNE |
|            7 |     1061 | 2024-06-15 | Johnny Speeds   | L   | 0.859      | -            | -                | -                | -         |    -2.97 | bq, dex, poiii, quix, zyyx  |
|            6 |     1084 | 2024-06-14 | Young Gods      | W   | 0.854      | 0.377        | 0.007 (0.002)    | 0.033 (0.011)    | 1 (0.854) |     8.01 | bq, dex, poiii, quix, zyyx  |
|            5 |     1103 | 2024-06-14 | Johnny Speeds   | L   | 0.852      | -            | -                | -                | -         |    -2.91 | bq, dex, poiii, quix, zyyx  |
|            4 |     1135 | 2024-06-13 | Young Gods      | W   | 0.846      | 0.377        | 0.007 (0.002)    | 0.033 (0.011)    | 1 (0.846) |     8.10 | bq, dex, poiii, quix, zyyx  |
|            3 |     1270 | 2024-06-09 | Alliance        | L   | 0.818      | -            | -                | -                | -         |   -13.41 | bq, dex, poiii, quix, zyyx  |
|            2 |     2246 | 2024-05-11 | Johnny Speeds   | L   | 0.627      | -            | -                | -                | -         |    -1.77 | bq, dex, poiii, quix, zyyx  |
|            1 |     2255 | 2024-05-11 | AURA            | W   | 0.626      | 0.319        | 0.017 (0.003)    | 0.058 (0.012)    | 1 (0.626) |     7.30 | bq, dex, poiii, quix, zyyx  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($7,333.74)
- Divide that value by the 5th highest value among all rosters ($322,004.12)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-15 |      0.859 | $5,808.00      | $4,990.31       |
| 2024-06-09 |      0.819 | $1,445.00      | $1,184.10       |
| 2024-05-11 |      0.627 | $1,850.00      | $1,159.33       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
