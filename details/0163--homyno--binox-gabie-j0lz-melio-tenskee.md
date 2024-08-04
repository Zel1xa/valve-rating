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
Final Rank Value (679.4) = Starting Rank Value (699.2) + Head To Head Adjustments (-19.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.319[<sup>1</sup>](#table2)
- Bounty Collected: 0.248[<sup>2</sup>](#table1)
- Opponent Network: 0.018[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.146<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 699.2
- 400 + ( ( 0.146 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 699.2


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
|           16 |      258 | 2024-07-27 | Revenge Nation | W   | 1.000      | 0.371        | 0.007 (0.003)    | 0.100 (0.037)    | 0 (0.000) |    17.23 | BiNoX, Gabie, J0LZ, Melio, TENSKEE |
|           15 |      978 | 2024-06-15 | E-Xolos LAZER  | L   | 0.874      | -            | -                | -                | -         |    -9.28 | Gabie, J0LZ, Melio, TENSKEE, YuZ   |
|           14 |     1014 | 2024-06-14 | Akimbo         | L   | 0.867      | -            | -                | -                | -         |    -9.10 | Gabie, J0LZ, Melio, TENSKEE, YuZ   |
|           13 |     1055 | 2024-06-13 | Detonate       | W   | 0.861      | 0.143        | 0.000 (0.000)    | 0.073 (0.009)    | 0 (0.000) |     8.30 | Gabie, J0LZ, Melio, TENSKEE, YuZ   |
|           12 |     1087 | 2024-06-12 | E-Xolos LAZER  | L   | 0.854      | -            | -                | -                | -         |    -9.53 | Gabie, J0LZ, Melio, TENSKEE, YuZ   |
|           11 |     1089 | 2024-06-12 | Detonate       | W   | 0.853      | 0.143        | 0.000 (0.000)    | 0.073 (0.009)    | 0 (0.000) |     7.93 | Gabie, J0LZ, Melio, TENSKEE, YuZ   |
|           10 |     1110 | 2024-06-11 | Final Form     | L   | 0.846      | -            | -                | -                | -         |   -14.82 | Gabie, J0LZ, Melio, TENSKEE, YuZ   |
|            9 |     1139 | 2024-06-10 | E-Xolos LAZER  | L   | 0.838      | -            | -                | -                | -         |   -10.56 | Gabie, J0LZ, Melio, TENSKEE, YuZ   |
|            8 |     1228 | 2024-06-08 | LAG            | L   | 0.827      | -            | -                | -                | -         |    -8.56 | Gabie, J0LZ, Melio, TENSKEE, YuZ   |
|            7 |     1281 | 2024-06-07 | E-Xolos LAZER  | L   | 0.821      | -            | -                | -                | -         |   -11.65 | Gabie, J0LZ, Melio, TENSKEE, YuZ   |
|            6 |     1351 | 2024-06-06 | Limitless      | W   | 0.813      | 0.371        | 0.001 (0.000)    | 0.168 (0.051)    | 0 (0.000) |     9.24 | Gabie, J0LZ, Melio, TENSKEE, YuZ   |
|            5 |     1464 | 2024-06-04 | Wildcard       | L   | 0.800      | -            | -                | -                | -         |    -5.00 | Gabie, J0LZ, Melio, TENSKEE, YuZ   |
|            4 |     1472 | 2024-06-04 | TSM Shimmer    | W   | 0.799      | 0.371        | 0.020 (0.006)    | 0.199 (0.059)    | 0 (0.000) |    12.80 | Gabie, J0LZ, Melio, TENSKEE, YuZ   |
|            3 |     3343 | 2024-03-23 | Revenge Nation | L   | 0.314      | -            | -                | -                | -         |    -4.92 | Gabie, J0LZ, Melio, TENSKEE, YuZ   |
|            2 |     3370 | 2024-03-21 | Final Form     | W   | 0.301      | 0.359        | 0.003 (0.000)    | 0.066 (0.007)    | 0 (0.000) |     4.08 | Gabie, J0LZ, Melio, TENSKEE, YuZ   |
|            1 |     3421 | 2024-03-19 | Akimbo         | W   | 0.287      | 0.359        | 0.003 (0.000)    | 0.075 (0.008)    | 0 (0.000) |     4.08 | Gabie, J0LZ, Melio, TENSKEE, YuZ   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,400.79)
- Divide that value by the 5th highest value among all rosters ($325,463.29)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-10 |      0.841 | $1,250.00      | $1,050.87       |
| 2024-03-23 |      0.314 | $4,300.00      | $1,349.92       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
