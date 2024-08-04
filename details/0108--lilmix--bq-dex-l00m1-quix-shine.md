### Roster Details<br />
Team Name: Lilmix<br />
Roster: bq, dex, L00m1, quix, SHiNE<br />
Global Rank: [108](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [79]( ../standings_europe.md)<br />
<br />
Final Rank Value:  840.6<br />
<br />
Final Rank Value (840.6) = Starting Rank Value (867.3) + Head To Head Adjustments (-26.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.379[<sup>1</sup>](#table2)
- Bounty Collected: 0.256[<sup>2</sup>](#table1)
- Opponent Network: 0.011[<sup>2</sup>](#table1)
- LAN Wins: 0.269[<sup>2</sup>](#table1)

The average of these factors is 0.229<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 867.3
- 400 + ( ( 0.229 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 867.3


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
|           10 |      181 | 2024-07-30 | INFINITE        | L   | 1.000      | -            | -                | -                | -         |   -25.22 | bq, dex, L00m1, quix, SHiNE |
|            9 |      368 | 2024-07-24 | ALTERNATE aTTaX | L   | 1.000      | -            | -                | -                | -         |   -17.06 | bq, dex, L00m1, quix, SHiNE |
|            8 |      594 | 2024-07-18 | kONO            | W   | 1.000      | 0.143        | 0.028 (0.004)    | 0.536 (0.077)    | 0 (0.000) |    13.37 | bq, dex, L00m1, quix, SHiNE |
|            7 |     1000 | 2024-06-15 | Johnny Speeds   | L   | 0.871      | -            | -                | -                | -         |    -3.10 | bq, dex, poiii, quix, zyyx  |
|            6 |     1023 | 2024-06-14 | Young Gods      | W   | 0.865      | 0.377        | 0.007 (0.002)    | 0.034 (0.011)    | 1 (0.865) |     8.13 | bq, dex, poiii, quix, zyyx  |
|            5 |     1042 | 2024-06-14 | Johnny Speeds   | L   | 0.864      | -            | -                | -                | -         |    -3.05 | bq, dex, poiii, quix, zyyx  |
|            4 |     1074 | 2024-06-13 | Young Gods      | W   | 0.857      | 0.377        | 0.007 (0.002)    | 0.034 (0.011)    | 1 (0.857) |     8.23 | bq, dex, poiii, quix, zyyx  |
|            3 |     1209 | 2024-06-09 | Alliance        | L   | 0.830      | -            | -                | -                | -         |   -13.55 | bq, dex, poiii, quix, zyyx  |
|            2 |     2185 | 2024-05-11 | Johnny Speeds   | L   | 0.638      | -            | -                | -                | -         |    -1.88 | bq, dex, poiii, quix, zyyx  |
|            1 |     2194 | 2024-05-11 | AURA            | W   | 0.637      | 0.319        | 0.017 (0.004)    | 0.059 (0.012)    | 1 (0.637) |     7.44 | bq, dex, poiii, quix, zyyx  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($7,439.94)
- Divide that value by the 5th highest value among all rosters ($325,463.29)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-15 |      0.871 | $5,808.00      | $5,058.07       |
| 2024-06-09 |      0.831 | $1,445.00      | $1,200.96       |
| 2024-05-11 |      0.638 | $1,850.00      | $1,180.92       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
