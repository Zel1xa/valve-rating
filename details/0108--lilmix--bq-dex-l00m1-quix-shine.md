### Roster Details<br />
Team Name: Lilmix<br />
Roster: bq, dex, L00m1, quix, SHiNE<br />
Global Rank: [108](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [79]( ../standings_europe.md)<br />
<br />
Final Rank Value:  848.0<br />
<br />
Final Rank Value (848.0) = Starting Rank Value (875.6) + Head To Head Adjustments (-27.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.379[<sup>1</sup>](#table2)
- Bounty Collected: 0.257[<sup>2</sup>](#table1)
- Opponent Network: 0.011[<sup>2</sup>](#table1)
- LAN Wins: 0.277[<sup>2</sup>](#table1)

The average of these factors is 0.231<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 875.6
- 400 + ( ( 0.231 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 875.6


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
|           10 |      101 | 2024-07-30 | INFINITE        | L   | 1.000      | -            | -                | -                | -         |   -25.37 | bq, dex, L00m1, quix, SHiNE |
|            9 |      287 | 2024-07-24 | ALTERNATE aTTaX | L   | 1.000      | -            | -                | -                | -         |   -17.99 | bq, dex, L00m1, quix, SHiNE |
|            8 |      522 | 2024-07-18 | kONO            | W   | 1.000      | 0.143        | 0.029 (0.004)    | 0.547 (0.078)    | 0 (0.000) |    14.06 | bq, dex, L00m1, quix, SHiNE |
|            7 |      933 | 2024-06-15 | Johnny Speeds   | L   | 0.886      | -            | -                | -                | -         |    -3.19 | bq, dex, poiii, quix, zyyx  |
|            6 |      950 | 2024-06-14 | Young Gods      | W   | 0.880      | 0.377        | 0.007 (0.002)    | 0.034 (0.011)    | 1 (0.880) |     8.15 | bq, dex, poiii, quix, zyyx  |
|            5 |      968 | 2024-06-14 | Johnny Speeds   | L   | 0.879      | -            | -                | -                | -         |    -3.14 | bq, dex, poiii, quix, zyyx  |
|            4 |     1000 | 2024-06-13 | Young Gods      | W   | 0.872      | 0.377        | 0.007 (0.002)    | 0.034 (0.011)    | 1 (0.872) |     8.25 | bq, dex, poiii, quix, zyyx  |
|            3 |     1137 | 2024-06-09 | Alliance        | L   | 0.845      | -            | -                | -                | -         |   -13.97 | bq, dex, poiii, quix, zyyx  |
|            2 |     2165 | 2024-05-11 | Johnny Speeds   | L   | 0.653      | -            | -                | -                | -         |    -1.92 | bq, dex, poiii, quix, zyyx  |
|            1 |     2174 | 2024-05-11 | AURA            | W   | 0.652      | 0.319        | 0.017 (0.004)    | 0.060 (0.012)    | 1 (0.652) |     7.54 | bq, dex, poiii, quix, zyyx  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($7,576.49)
- Divide that value by the 5th highest value among all rosters ($327,030.46)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-15 |      0.886 | $5,808.00      | $5,145.19       |
| 2024-06-09 |      0.846 | $1,445.00      | $1,222.63       |
| 2024-05-11 |      0.653 | $1,850.00      | $1,208.67       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
