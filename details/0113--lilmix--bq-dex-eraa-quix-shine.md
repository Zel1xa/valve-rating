### Roster Details<br />
Team Name: Lilmix<br />
Roster: bq, dex, eraa, quix, SHiNE<br />
Global Rank: [113](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [82]( ../standings_europe.md)<br />
<br />
Final Rank Value:  827.0<br />
<br />
Final Rank Value (827.0) = Starting Rank Value (868.5) + Head To Head Adjustments (-41.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.378[<sup>1</sup>](#table2)
- Bounty Collected: 0.255[<sup>2</sup>](#table1)
- Opponent Network: 0.011[<sup>2</sup>](#table1)
- LAN Wins: 0.266[<sup>2</sup>](#table1)

The average of these factors is 0.228<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 868.5
- 400 + ( ( 0.228 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 868.5


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
|           11 |        9 | 2024-08-06 | FAVBET          | L   | 1.000      | -            | -                | -                | -         |   -15.46 | bq, dex, eraa, quix, SHiNE  |
|           10 |      251 | 2024-07-30 | INFINITE        | L   | 1.000      | -            | -                | -                | -         |   -25.24 | bq, dex, L00m1, quix, SHiNE |
|            9 |      437 | 2024-07-24 | ALTERNATE aTTaX | L   | 1.000      | -            | -                | -                | -         |   -16.79 | bq, dex, L00m1, quix, SHiNE |
|            8 |      668 | 2024-07-18 | kONO            | W   | 1.000      | 0.143        | 0.028 (0.004)    | 0.553 (0.079)    | 0 (0.000) |    13.45 | bq, dex, L00m1, quix, SHiNE |
|            7 |     1070 | 2024-06-15 | Johnny Speeds   | L   | 0.854      | -            | -                | -                | -         |    -2.93 | bq, dex, poiii, quix, zyyx  |
|            6 |     1093 | 2024-06-14 | Young Gods      | W   | 0.848      | 0.377        | 0.007 (0.002)    | 0.032 (0.010)    | 1 (0.848) |     7.98 | bq, dex, poiii, quix, zyyx  |
|            5 |     1112 | 2024-06-14 | Johnny Speeds   | L   | 0.847      | -            | -                | -                | -         |    -2.87 | bq, dex, poiii, quix, zyyx  |
|            4 |     1144 | 2024-06-13 | Young Gods      | W   | 0.840      | 0.377        | 0.007 (0.002)    | 0.032 (0.010)    | 1 (0.840) |     8.08 | bq, dex, poiii, quix, zyyx  |
|            3 |     1279 | 2024-06-09 | Alliance        | L   | 0.813      | -            | -                | -                | -         |   -13.31 | bq, dex, poiii, quix, zyyx  |
|            2 |     2255 | 2024-05-11 | Johnny Speeds   | L   | 0.621      | -            | -                | -                | -         |    -1.74 | bq, dex, poiii, quix, zyyx  |
|            1 |     2264 | 2024-05-11 | AURA            | W   | 0.620      | 0.319        | 0.017 (0.003)    | 0.057 (0.011)    | 1 (0.620) |     7.24 | bq, dex, poiii, quix, zyyx  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($7,282.32)
- Divide that value by the 5th highest value among all rosters ($320,329.44)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-15 |      0.854 | $5,808.00      | $4,957.50       |
| 2024-06-09 |      0.814 | $1,445.00      | $1,175.94       |
| 2024-05-11 |      0.621 | $1,850.00      | $1,148.88       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
