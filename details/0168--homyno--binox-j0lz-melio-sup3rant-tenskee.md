### Roster Details<br />
Team Name: Homyno<br />
Roster: BiNoX, J0LZ, Melio, Sup3rant, TENSKEE<br />
Global Rank: [168](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [47]( ../standings_americas.md)<br />
<br />
Final Rank Value:  665.7<br />
<br />
Final Rank Value (665.7) = Starting Rank Value (699.0) + Head To Head Adjustments (-33.2)<br />

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
- 400 + ( ( 0.146 - 0.000 ) / ( 0.781 - 0.000 ) ) * 1600 = 699.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent       | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           17 |       13 | 2024-08-04 | FLUFFY AIMERS  | L   | 1.000      | -            | -                | -                | -         |   -13.34 | BiNoX, J0LZ, Melio, Sup3rant, TENSKEE |
|           16 |      310 | 2024-07-27 | Revenge Nation | W   | 1.000      | 0.371        | 0.007 (0.002)    | 0.100 (0.037)    | 0 (0.000) |    17.23 | BiNoX, Gabie, J0LZ, Melio, TENSKEE    |
|           15 |     1031 | 2024-06-15 | E-Xolos LAZER  | L   | 0.863      | -            | -                | -                | -         |    -9.12 | Gabie, J0LZ, Melio, TENSKEE, YuZ      |
|           14 |     1067 | 2024-06-14 | Akimbo         | L   | 0.857      | -            | -                | -                | -         |    -8.98 | Gabie, J0LZ, Melio, TENSKEE, YuZ      |
|           13 |     1108 | 2024-06-13 | Detonate       | W   | 0.850      | 0.143        | 0.000 (0.000)    | 0.073 (0.009)    | 0 (0.000) |     8.22 | Gabie, J0LZ, Melio, TENSKEE, YuZ      |
|           12 |     1140 | 2024-06-12 | E-Xolos LAZER  | L   | 0.843      | -            | -                | -                | -         |    -9.35 | Gabie, J0LZ, Melio, TENSKEE, YuZ      |
|           11 |     1142 | 2024-06-12 | Detonate       | W   | 0.843      | 0.143        | 0.000 (0.000)    | 0.073 (0.009)    | 0 (0.000) |     7.87 | Gabie, J0LZ, Melio, TENSKEE, YuZ      |
|           10 |     1163 | 2024-06-11 | Final Form     | L   | 0.835      | -            | -                | -                | -         |   -14.61 | Gabie, J0LZ, Melio, TENSKEE, YuZ      |
|            9 |     1192 | 2024-06-10 | E-Xolos LAZER  | L   | 0.828      | -            | -                | -                | -         |   -10.34 | Gabie, J0LZ, Melio, TENSKEE, YuZ      |
|            8 |     1281 | 2024-06-08 | LAG            | L   | 0.816      | -            | -                | -                | -         |    -8.72 | Gabie, J0LZ, Melio, TENSKEE, YuZ      |
|            7 |     1334 | 2024-06-07 | E-Xolos LAZER  | L   | 0.810      | -            | -                | -                | -         |   -11.38 | Gabie, J0LZ, Melio, TENSKEE, YuZ      |
|            6 |     1404 | 2024-06-06 | Limitless      | W   | 0.802      | 0.371        | 0.001 (0.000)    | 0.166 (0.049)    | 0 (0.000) |     9.13 | Gabie, J0LZ, Melio, TENSKEE, YuZ      |
|            5 |     1517 | 2024-06-04 | Wildcard       | L   | 0.790      | -            | -                | -                | -         |    -5.61 | Gabie, J0LZ, Melio, TENSKEE, YuZ      |
|            4 |     1525 | 2024-06-04 | TSM Shimmer    | W   | 0.788      | 0.371        | 0.020 (0.006)    | 0.198 (0.058)    | 0 (0.000) |    12.64 | Gabie, J0LZ, Melio, TENSKEE, YuZ      |
|            3 |     3397 | 2024-03-23 | Revenge Nation | L   | 0.303      | -            | -                | -                | -         |    -4.75 | Gabie, J0LZ, Melio, TENSKEE, YuZ      |
|            2 |     3424 | 2024-03-21 | Final Form     | W   | 0.290      | 0.359        | 0.003 (0.000)    | 0.066 (0.007)    | 0 (0.000) |     3.94 | Gabie, J0LZ, Melio, TENSKEE, YuZ      |
|            1 |     3475 | 2024-03-19 | Akimbo         | W   | 0.277      | 0.359        | 0.003 (0.000)    | 0.074 (0.007)    | 0 (0.000) |     3.92 | Gabie, J0LZ, Melio, TENSKEE, YuZ      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,342.21)
- Divide that value by the 5th highest value among all rosters ($322,333.56)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-10 |      0.830 | $1,250.00      | $1,037.67       |
| 2024-03-23 |      0.303 | $4,300.00      | $1,304.53       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
