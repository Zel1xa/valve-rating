### Roster Details<br />
Team Name: Lilmix<br />
Roster: bq, dex, L00m1, quix, SHiNE<br />
Global Rank: [109](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [78]( ../standings_europe.md)<br />
<br />
Final Rank Value:  840.7<br />
<br />
Final Rank Value (840.7) = Starting Rank Value (867.0) + Head To Head Adjustments (-26.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.379[<sup>1</sup>](#table2)
- Bounty Collected: 0.256[<sup>2</sup>](#table1)
- Opponent Network: 0.011[<sup>2</sup>](#table1)
- LAN Wins: 0.268[<sup>2</sup>](#table1)

The average of these factors is 0.228<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 867.0
- 400 + ( ( 0.228 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 867.0


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
|           10 |      220 | 2024-07-30 | INFINITE        | L   | 1.000      | -            | -                | -                | -         |   -25.22 | bq, dex, L00m1, quix, SHiNE |
|            9 |      407 | 2024-07-24 | ALTERNATE aTTaX | L   | 1.000      | -            | -                | -                | -         |   -16.87 | bq, dex, L00m1, quix, SHiNE |
|            8 |      638 | 2024-07-18 | kONO            | W   | 1.000      | 0.143        | 0.028 (0.004)    | 0.536 (0.077)    | 0 (0.000) |    13.37 | bq, dex, L00m1, quix, SHiNE |
|            7 |     1040 | 2024-06-15 | Johnny Speeds   | L   | 0.864      | -            | -                | -                | -         |    -2.98 | bq, dex, poiii, quix, zyyx  |
|            6 |     1063 | 2024-06-14 | Young Gods      | W   | 0.858      | 0.377        | 0.007 (0.002)    | 0.034 (0.011)    | 1 (0.858) |     8.05 | bq, dex, poiii, quix, zyyx  |
|            5 |     1082 | 2024-06-14 | Johnny Speeds   | L   | 0.857      | -            | -                | -                | -         |    -2.92 | bq, dex, poiii, quix, zyyx  |
|            4 |     1114 | 2024-06-13 | Young Gods      | W   | 0.850      | 0.377        | 0.007 (0.002)    | 0.034 (0.011)    | 1 (0.850) |     8.15 | bq, dex, poiii, quix, zyyx  |
|            3 |     1249 | 2024-06-09 | Alliance        | L   | 0.823      | -            | -                | -                | -         |   -13.46 | bq, dex, poiii, quix, zyyx  |
|            2 |     2225 | 2024-05-11 | Johnny Speeds   | L   | 0.631      | -            | -                | -                | -         |    -1.79 | bq, dex, poiii, quix, zyyx  |
|            1 |     2234 | 2024-05-11 | AURA            | W   | 0.630      | 0.319        | 0.017 (0.003)    | 0.059 (0.012)    | 1 (0.630) |     7.36 | bq, dex, poiii, quix, zyyx  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($7,374.20)
- Divide that value by the 5th highest value among all rosters ($323,321.90)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-15 |      0.864 | $5,808.00      | $5,016.12       |
| 2024-06-09 |      0.824 | $1,445.00      | $1,190.52       |
| 2024-05-11 |      0.631 | $1,850.00      | $1,167.56       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
