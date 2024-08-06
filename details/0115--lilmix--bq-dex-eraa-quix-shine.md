### Roster Details<br />
Team Name: Lilmix<br />
Roster: bq, dex, eraa, quix, SHiNE<br />
Global Rank: [115](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [82]( ../standings_europe.md)<br />
<br />
Final Rank Value:  826.8<br />
<br />
Final Rank Value (826.8) = Starting Rank Value (868.6) + Head To Head Adjustments (-41.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.378[<sup>1</sup>](#table2)
- Bounty Collected: 0.255[<sup>2</sup>](#table1)
- Opponent Network: 0.011[<sup>2</sup>](#table1)
- LAN Wins: 0.267[<sup>2</sup>](#table1)

The average of these factors is 0.228<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 868.6
- 400 + ( ( 0.228 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 868.6


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
|           11 |        5 | 2024-08-06 | FAVBET          | L   | 1.000      | -            | -                | -                | -         |   -15.54 | bq, dex, eraa, quix, SHiNE  |
|           10 |      253 | 2024-07-30 | INFINITE        | L   | 1.000      | -            | -                | -                | -         |   -25.23 | bq, dex, L00m1, quix, SHiNE |
|            9 |      439 | 2024-07-24 | ALTERNATE aTTaX | L   | 1.000      | -            | -                | -                | -         |   -16.80 | bq, dex, L00m1, quix, SHiNE |
|            8 |      670 | 2024-07-18 | kONO            | W   | 1.000      | 0.143        | 0.028 (0.004)    | 0.553 (0.079)    | 0 (0.000) |    13.43 | bq, dex, L00m1, quix, SHiNE |
|            7 |     1072 | 2024-06-15 | Johnny Speeds   | L   | 0.854      | -            | -                | -                | -         |    -2.94 | bq, dex, poiii, quix, zyyx  |
|            6 |     1095 | 2024-06-14 | Young Gods      | W   | 0.849      | 0.377        | 0.007 (0.002)    | 0.032 (0.010)    | 1 (0.849) |     7.98 | bq, dex, poiii, quix, zyyx  |
|            5 |     1114 | 2024-06-14 | Johnny Speeds   | L   | 0.847      | -            | -                | -                | -         |    -2.89 | bq, dex, poiii, quix, zyyx  |
|            4 |     1146 | 2024-06-13 | Young Gods      | W   | 0.841      | 0.377        | 0.007 (0.002)    | 0.032 (0.010)    | 1 (0.841) |     8.08 | bq, dex, poiii, quix, zyyx  |
|            3 |     1281 | 2024-06-09 | Alliance        | L   | 0.813      | -            | -                | -                | -         |   -13.32 | bq, dex, poiii, quix, zyyx  |
|            2 |     2257 | 2024-05-11 | Johnny Speeds   | L   | 0.622      | -            | -                | -                | -         |    -1.75 | bq, dex, poiii, quix, zyyx  |
|            1 |     2266 | 2024-05-11 | AURA            | W   | 0.621      | 0.319        | 0.017 (0.003)    | 0.057 (0.011)    | 1 (0.621) |     7.25 | bq, dex, poiii, quix, zyyx  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($7,288.22)
- Divide that value by the 5th highest value among all rosters ($320,521.62)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-15 |      0.854 | $5,808.00      | $4,961.27       |
| 2024-06-09 |      0.814 | $1,445.00      | $1,176.87       |
| 2024-05-11 |      0.622 | $1,850.00      | $1,150.08       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
