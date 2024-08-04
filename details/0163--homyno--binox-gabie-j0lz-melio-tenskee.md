### Roster Details<br />
Team Name: Homyno<br />
Roster: BiNoX, Gabie, J0LZ, Melio, TENSKEE<br />
Global Rank: [163](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [45]( ../standings_americas.md)<br />
<br />
Final Rank Value:  678.8<br />
<br />
Final Rank Value (678.8) = Starting Rank Value (699.0) + Head To Head Adjustments (-20.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.319[<sup>1</sup>](#table2)
- Bounty Collected: 0.248[<sup>2</sup>](#table1)
- Opponent Network: 0.018[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.146<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 699.0
- 400 + ( ( 0.146 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 699.0


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
|           16 |      293 | 2024-07-27 | Revenge Nation | W   | 1.000      | 0.371        | 0.007 (0.002)    | 0.101 (0.037)    | 0 (0.000) |    17.25 | BiNoX, Gabie, J0LZ, Melio, TENSKEE |
|           15 |     1014 | 2024-06-15 | E-Xolos LAZER  | L   | 0.869      | -            | -                | -                | -         |    -9.19 | Gabie, J0LZ, Melio, TENSKEE, YuZ   |
|           14 |     1050 | 2024-06-14 | Akimbo         | L   | 0.862      | -            | -                | -                | -         |    -9.04 | Gabie, J0LZ, Melio, TENSKEE, YuZ   |
|           13 |     1091 | 2024-06-13 | Detonate       | W   | 0.856      | 0.143        | 0.000 (0.000)    | 0.073 (0.009)    | 0 (0.000) |     8.28 | Gabie, J0LZ, Melio, TENSKEE, YuZ   |
|           12 |     1123 | 2024-06-12 | E-Xolos LAZER  | L   | 0.849      | -            | -                | -                | -         |    -9.43 | Gabie, J0LZ, Melio, TENSKEE, YuZ   |
|           11 |     1125 | 2024-06-12 | Detonate       | W   | 0.848      | 0.143        | 0.000 (0.000)    | 0.073 (0.009)    | 0 (0.000) |     7.92 | Gabie, J0LZ, Melio, TENSKEE, YuZ   |
|           10 |     1146 | 2024-06-11 | Final Form     | L   | 0.841      | -            | -                | -                | -         |   -14.71 | Gabie, J0LZ, Melio, TENSKEE, YuZ   |
|            9 |     1175 | 2024-06-10 | E-Xolos LAZER  | L   | 0.834      | -            | -                | -                | -         |   -10.44 | Gabie, J0LZ, Melio, TENSKEE, YuZ   |
|            8 |     1264 | 2024-06-08 | LAG            | L   | 0.822      | -            | -                | -                | -         |    -8.77 | Gabie, J0LZ, Melio, TENSKEE, YuZ   |
|            7 |     1317 | 2024-06-07 | E-Xolos LAZER  | L   | 0.816      | -            | -                | -                | -         |   -11.52 | Gabie, J0LZ, Melio, TENSKEE, YuZ   |
|            6 |     1387 | 2024-06-06 | Limitless      | W   | 0.808      | 0.371        | 0.001 (0.000)    | 0.167 (0.050)    | 0 (0.000) |     9.17 | Gabie, J0LZ, Melio, TENSKEE, YuZ   |
|            5 |     1500 | 2024-06-04 | Wildcard       | L   | 0.796      | -            | -                | -                | -         |    -5.62 | Gabie, J0LZ, Melio, TENSKEE, YuZ   |
|            4 |     1508 | 2024-06-04 | TSM Shimmer    | W   | 0.794      | 0.371        | 0.020 (0.006)    | 0.199 (0.059)    | 0 (0.000) |    12.73 | Gabie, J0LZ, Melio, TENSKEE, YuZ   |
|            3 |     3380 | 2024-03-23 | Revenge Nation | L   | 0.309      | -            | -                | -                | -         |    -4.84 | Gabie, J0LZ, Melio, TENSKEE, YuZ   |
|            2 |     3407 | 2024-03-21 | Final Form     | W   | 0.296      | 0.359        | 0.003 (0.000)    | 0.066 (0.007)    | 0 (0.000) |     4.02 | Gabie, J0LZ, Melio, TENSKEE, YuZ   |
|            1 |     3458 | 2024-03-19 | Akimbo         | W   | 0.283      | 0.359        | 0.003 (0.000)    | 0.075 (0.008)    | 0 (0.000) |     4.00 | Gabie, J0LZ, Melio, TENSKEE, YuZ   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,373.94)
- Divide that value by the 5th highest value among all rosters ($324,028.83)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-10 |      0.836 | $1,250.00      | $1,044.82       |
| 2024-03-23 |      0.309 | $4,300.00      | $1,329.12       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
