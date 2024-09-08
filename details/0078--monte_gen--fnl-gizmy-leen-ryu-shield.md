### Roster Details<br />
Team Name: Monte Gen<br />
Roster: fnl, Gizmy, leen, ryu, shield<br />
Global Rank: [78](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [57]( ../standings_europe.md)<br />
<br />
Final Rank Value:  913.2<br />
<br />
Final Rank Value (913.2) = Starting Rank Value (861.5) + Head To Head Adjustments (51.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.359[<sup>1</sup>](#table2)
- Bounty Collected: 0.352[<sup>2</sup>](#table1)
- Opponent Network: 0.243[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.238<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 861.5
- 400 + ( ( 0.238 - 0.000 ) / ( 0.826 - 0.000 ) ) * 1600 = 861.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                         |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           18 |       30 | 2024-09-07 | Insilio           | W   | 1.000      | 0.435        | 0.023 (0.010)    | 0.654 (0.284)    | 0 (0.000) |    15.63 | fnl, Gizmy, leen, ryu, shield  |
|           17 |      117 | 2024-09-04 | Aurora Young Blud | W   | 1.000      | 0.435        | 0.019 (0.008)    | 0.711 (0.309)    | 0 (0.000) |    13.41 | fnl, Gizmy, leen, ryu, shield  |
|           16 |      161 | 2024-09-03 | EYEBALLERS        | L   | 1.000      | -            | -                | -                | -         |   -21.16 | fnl, Gizmy, leen, ryu, shield  |
|           15 |      194 | 2024-09-01 | CPH Wolves        | W   | 1.000      | 0.143        | 0.003 (0.000)    | 0.510 (0.073)    | 0 (0.000) |    11.51 | fnl, Gizmy, leen, ryu, shield  |
|           14 |      335 | 2024-08-28 | ALTERNATE aTTaX   | L   | 1.000      | -            | -                | -                | -         |   -14.11 | fnl, Gizmy, leen, ryu, shield  |
|           13 |      376 | 2024-08-27 | TSM               | W   | 1.000      | 0.435        | 0.058 (0.025)    | 0.900 (0.391)    | 0 (0.000) |    22.91 | fnl, Gizmy, leen, ryu, shield  |
|           12 |      499 | 2024-08-25 | PARIVISION        | W   | 1.000      | 0.435        | 0.046 (0.020)    | 0.730 (0.317)    | 0 (0.000) |    25.50 | fnl, Gizmy, leen, ryu, shield  |
|           11 |      687 | 2024-08-20 | Revenant          | W   | 1.000      | 0.435        | 0.042 (0.018)    | 0.666 (0.289)    | 0 (0.000) |    19.36 | fnl, Gizmy, leen, ryu, shield  |
|           10 |      758 | 2024-08-17 | Insilio           | W   | 1.000      | 0.435        | 0.023 (0.010)    | 0.654 (0.284)    | 0 (0.000) |    18.32 | fnl, Gizmy, leen, ryu, shield  |
|            9 |      792 | 2024-08-16 | Permitta          | L   | 1.000      | -            | -                | -                | -         |   -12.84 | AiyvaN, fnl, leen, ryu, shield |
|            8 |      894 | 2024-08-13 | ALTERNATE aTTaX   | W   | 1.000      | 0.435        | 0.102 (0.044)    | 0.837 (0.364)    | 0 (0.000) |    17.16 | fnl, Gizmy, leen, ryu, shield  |
|            7 |      933 | 2024-08-12 | Preasy            | W   | 1.000      | 0.143        | 0.007 (0.001)    | 0.162 (0.023)    | 0 (0.000) |    10.51 | fnl, Gizmy, leen, ryu, shield  |
|            6 |     1006 | 2024-08-09 | HAVU              | L   | 1.000      | -            | -                | -                | -         |   -25.66 | fnl, Gizmy, leen, ryu, shield  |
|            5 |     1088 | 2024-08-07 | DMS               | L   | 0.986      | -            | -                | -                | -         |   -14.02 | fnl, Gizmy, leen, ryu, shield  |
|            4 |     1117 | 2024-08-06 | CYBERSHOKE        | L   | 0.981      | -            | -                | -                | -         |   -11.70 | fnl, Gizmy, leen, ryu, shield  |
|            3 |     1168 | 2024-08-04 | Revenant          | W   | 0.967      | 0.143        | 0.042 (0.006)    | 0.666 (0.092)    | 0 (0.000) |    17.15 | fnl, Gizmy, leen, ryu, shield  |
|            2 |     1388 | 2024-07-30 | Sampi             | L   | 0.932      | -            | -                | -                | -         |   -12.56 | fnl, Gizmy, leen, ryu, shield  |
|            1 |     1407 | 2024-07-29 | MOUZ NXT          | L   | 0.927      | -            | -                | -                | -         |    -7.71 | fnl, Gizmy, leen, ryu, shield  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($5,000.00)
- Divide that value by the 5th highest value among all rosters ($303,706.75)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
