### Roster Details<br />
Team Name: Homyno<br />
Roster: BiNoX, Gabie, J0LZ, Melio, TENSKEE<br />
Global Rank: [163](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [45]( ../standings_americas.md)<br />
<br />
Final Rank Value:  679.4<br />
<br />
Final Rank Value (679.4) = Starting Rank Value (699.1) + Head To Head Adjustments (-19.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.319[<sup>1</sup>](#table2)
- Bounty Collected: 0.248[<sup>2</sup>](#table1)
- Opponent Network: 0.018[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.146<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 699.1
- 400 + ( ( 0.146 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 699.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent       | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                             |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           16 |      261 | 2024-07-27 | Revenge Nation | W   | 1.000      | 0.371        | 0.007 (0.002)    | 0.101 (0.037)    | 0 (0.000) |    17.22 | BiNoX, Gabie, J0LZ, Melio, TENSKEE |
|           15 |      982 | 2024-06-15 | E-Xolos LAZER  | L   | 0.871      | -            | -                | -                | -         |    -9.25 | Gabie, J0LZ, Melio, TENSKEE, YuZ   |
|           14 |     1018 | 2024-06-14 | Akimbo         | L   | 0.864      | -            | -                | -                | -         |    -9.08 | Gabie, J0LZ, Melio, TENSKEE, YuZ   |
|           13 |     1059 | 2024-06-13 | Detonate       | W   | 0.858      | 0.143        | 0.000 (0.000)    | 0.073 (0.009)    | 0 (0.000) |     8.27 | Gabie, J0LZ, Melio, TENSKEE, YuZ   |
|           12 |     1091 | 2024-06-12 | E-Xolos LAZER  | L   | 0.851      | -            | -                | -                | -         |    -9.50 | Gabie, J0LZ, Melio, TENSKEE, YuZ   |
|           11 |     1093 | 2024-06-12 | Detonate       | W   | 0.850      | 0.143        | 0.000 (0.000)    | 0.073 (0.009)    | 0 (0.000) |     7.90 | Gabie, J0LZ, Melio, TENSKEE, YuZ   |
|           10 |     1114 | 2024-06-11 | Final Form     | L   | 0.843      | -            | -                | -                | -         |   -14.77 | Gabie, J0LZ, Melio, TENSKEE, YuZ   |
|            9 |     1143 | 2024-06-10 | E-Xolos LAZER  | L   | 0.835      | -            | -                | -                | -         |   -10.52 | Gabie, J0LZ, Melio, TENSKEE, YuZ   |
|            8 |     1232 | 2024-06-08 | LAG            | L   | 0.824      | -            | -                | -                | -         |    -8.54 | Gabie, J0LZ, Melio, TENSKEE, YuZ   |
|            7 |     1285 | 2024-06-07 | E-Xolos LAZER  | L   | 0.818      | -            | -                | -                | -         |   -11.60 | Gabie, J0LZ, Melio, TENSKEE, YuZ   |
|            6 |     1355 | 2024-06-06 | Limitless      | W   | 0.810      | 0.371        | 0.001 (0.000)    | 0.167 (0.050)    | 0 (0.000) |     9.22 | Gabie, J0LZ, Melio, TENSKEE, YuZ   |
|            5 |     1468 | 2024-06-04 | Wildcard       | L   | 0.797      | -            | -                | -                | -         |    -4.98 | Gabie, J0LZ, Melio, TENSKEE, YuZ   |
|            4 |     1476 | 2024-06-04 | TSM Shimmer    | W   | 0.796      | 0.371        | 0.020 (0.006)    | 0.199 (0.059)    | 0 (0.000) |    12.75 | Gabie, J0LZ, Melio, TENSKEE, YuZ   |
|            3 |     3348 | 2024-03-23 | Revenge Nation | L   | 0.311      | -            | -                | -                | -         |    -4.87 | Gabie, J0LZ, Melio, TENSKEE, YuZ   |
|            2 |     3375 | 2024-03-21 | Final Form     | W   | 0.298      | 0.359        | 0.003 (0.000)    | 0.066 (0.007)    | 0 (0.000) |     4.04 | Gabie, J0LZ, Melio, TENSKEE, YuZ   |
|            1 |     3426 | 2024-03-19 | Akimbo         | W   | 0.284      | 0.359        | 0.003 (0.000)    | 0.075 (0.008)    | 0 (0.000) |     4.03 | Gabie, J0LZ, Melio, TENSKEE, YuZ   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,383.83)
- Divide that value by the 5th highest value among all rosters ($324,557.31)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-10 |      0.838 | $1,250.00      | $1,047.05       |
| 2024-03-23 |      0.311 | $4,300.00      | $1,336.78       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
