### Roster Details<br />
Team Name: Homyno<br />
Roster: BiNoX, J0LZ, Melio, Sup3rant, TENSKEE<br />
Global Rank: [168](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [47]( ../standings_americas.md)<br />
<br />
Final Rank Value:  666.2<br />
<br />
Final Rank Value (666.2) = Starting Rank Value (699.1) + Head To Head Adjustments (-32.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.318[<sup>1</sup>](#table2)
- Bounty Collected: 0.247[<sup>2</sup>](#table1)
- Opponent Network: 0.017[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.146<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 699.1
- 400 + ( ( 0.146 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 699.1


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
|           17 |       28 | 2024-08-04 | FLUFFY AIMERS  | L   | 1.000      | -            | -                | -                | -         |   -13.36 | BiNoX, J0LZ, Melio, Sup3rant, TENSKEE |
|           16 |      325 | 2024-07-27 | Revenge Nation | W   | 1.000      | 0.371        | 0.006 (0.002)    | 0.099 (0.037)    | 0 (0.000) |    17.23 | BiNoX, Gabie, J0LZ, Melio, TENSKEE    |
|           15 |     1046 | 2024-06-15 | E-Xolos LAZER  | L   | 0.858      | -            | -                | -                | -         |    -9.03 | Gabie, J0LZ, Melio, TENSKEE, YuZ      |
|           14 |     1082 | 2024-06-14 | Akimbo         | L   | 0.851      | -            | -                | -                | -         |    -8.95 | Gabie, J0LZ, Melio, TENSKEE, YuZ      |
|           13 |     1123 | 2024-06-13 | DETONATE       | W   | 0.844      | 0.143        | 0.000 (0.000)    | 0.072 (0.009)    | 0 (0.000) |     8.18 | Gabie, J0LZ, Melio, TENSKEE, YuZ      |
|           12 |     1155 | 2024-06-12 | E-Xolos LAZER  | L   | 0.838      | -            | -                | -                | -         |    -9.25 | Gabie, J0LZ, Melio, TENSKEE, YuZ      |
|           11 |     1157 | 2024-06-12 | DETONATE       | W   | 0.837      | 0.143        | 0.000 (0.000)    | 0.072 (0.009)    | 0 (0.000) |     7.83 | Gabie, J0LZ, Melio, TENSKEE, YuZ      |
|           10 |     1178 | 2024-06-11 | Final Form     | L   | 0.830      | -            | -                | -                | -         |   -14.51 | Gabie, J0LZ, Melio, TENSKEE, YuZ      |
|            9 |     1207 | 2024-06-10 | E-Xolos LAZER  | L   | 0.822      | -            | -                | -                | -         |   -10.22 | Gabie, J0LZ, Melio, TENSKEE, YuZ      |
|            8 |     1296 | 2024-06-08 | LAG            | L   | 0.810      | -            | -                | -                | -         |    -8.69 | Gabie, J0LZ, Melio, TENSKEE, YuZ      |
|            7 |     1349 | 2024-06-07 | E-Xolos LAZER  | L   | 0.804      | -            | -                | -                | -         |   -11.24 | Gabie, J0LZ, Melio, TENSKEE, YuZ      |
|            6 |     1419 | 2024-06-06 | Limitless      | W   | 0.796      | 0.371        | 0.001 (0.000)    | 0.163 (0.048)    | 0 (0.000) |     9.07 | Gabie, J0LZ, Melio, TENSKEE, YuZ      |
|            5 |     1532 | 2024-06-04 | Wildcard       | L   | 0.784      | -            | -                | -                | -         |    -5.58 | Gabie, J0LZ, Melio, TENSKEE, YuZ      |
|            4 |     1540 | 2024-06-04 | TSM Shimmer    | W   | 0.782      | 0.371        | 0.020 (0.006)    | 0.195 (0.057)    | 0 (0.000) |    12.56 | Gabie, J0LZ, Melio, TENSKEE, YuZ      |
|            3 |     3412 | 2024-03-23 | Revenge Nation | L   | 0.298      | -            | -                | -                | -         |    -4.65 | Gabie, J0LZ, Melio, TENSKEE, YuZ      |
|            2 |     3439 | 2024-03-21 | Final Form     | W   | 0.284      | 0.359        | 0.003 (0.000)    | 0.065 (0.007)    | 0 (0.000) |     3.87 | Gabie, J0LZ, Melio, TENSKEE, YuZ      |
|            1 |     3490 | 2024-03-19 | Akimbo         | W   | 0.271      | 0.359        | 0.003 (0.000)    | 0.073 (0.007)    | 0 (0.000) |     3.83 | Gabie, J0LZ, Melio, TENSKEE, YuZ      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,309.83)
- Divide that value by the 5th highest value among all rosters ($320,603.98)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-10 |      0.824 | $1,250.00      | $1,030.38       |
| 2024-03-23 |      0.298 | $4,300.00      | $1,279.45       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
