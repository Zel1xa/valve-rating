### Roster Details<br />
Team Name: Homyno<br />
Roster: BiNoX, J0LZ, Melio, Sup3rant, TENSKEE<br />
Global Rank: [168](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [47]( ../standings_americas.md)<br />
<br />
Final Rank Value:  666.5<br />
<br />
Final Rank Value (666.5) = Starting Rank Value (699.5) + Head To Head Adjustments (-33.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.318[<sup>1</sup>](#table2)
- Bounty Collected: 0.247[<sup>2</sup>](#table1)
- Opponent Network: 0.017[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.146<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 699.5
- 400 + ( ( 0.146 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 699.5


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
|           17 |       32 | 2024-08-04 | FLUFFY AIMERS  | L   | 1.000      | -            | -                | -                | -         |   -13.38 | BiNoX, J0LZ, Melio, Sup3rant, TENSKEE |
|           16 |      329 | 2024-07-27 | Revenge Nation | W   | 1.000      | 0.371        | 0.006 (0.002)    | 0.097 (0.036)    | 0 (0.000) |    17.22 | BiNoX, Gabie, J0LZ, Melio, TENSKEE    |
|           15 |     1050 | 2024-06-15 | E-Xolos LAZER  | L   | 0.857      | -            | -                | -                | -         |    -9.04 | Gabie, J0LZ, Melio, TENSKEE, YuZ      |
|           14 |     1086 | 2024-06-14 | Akimbo         | L   | 0.851      | -            | -                | -                | -         |    -8.96 | Gabie, J0LZ, Melio, TENSKEE, YuZ      |
|           13 |     1127 | 2024-06-13 | DETONATE       | W   | 0.844      | 0.143        | 0.000 (0.000)    | 0.071 (0.009)    | 0 (0.000) |     8.17 | Gabie, J0LZ, Melio, TENSKEE, YuZ      |
|           12 |     1159 | 2024-06-12 | E-Xolos LAZER  | L   | 0.837      | -            | -                | -                | -         |    -9.27 | Gabie, J0LZ, Melio, TENSKEE, YuZ      |
|           11 |     1161 | 2024-06-12 | DETONATE       | W   | 0.836      | 0.143        | 0.000 (0.000)    | 0.071 (0.008)    | 0 (0.000) |     7.82 | Gabie, J0LZ, Melio, TENSKEE, YuZ      |
|           10 |     1182 | 2024-06-11 | Final Form     | L   | 0.829      | -            | -                | -                | -         |   -14.50 | Gabie, J0LZ, Melio, TENSKEE, YuZ      |
|            9 |     1211 | 2024-06-10 | E-Xolos LAZER  | L   | 0.822      | -            | -                | -                | -         |   -10.24 | Gabie, J0LZ, Melio, TENSKEE, YuZ      |
|            8 |     1300 | 2024-06-08 | LAG            | L   | 0.810      | -            | -                | -                | -         |    -8.71 | Gabie, J0LZ, Melio, TENSKEE, YuZ      |
|            7 |     1353 | 2024-06-07 | E-Xolos LAZER  | L   | 0.804      | -            | -                | -                | -         |   -11.26 | Gabie, J0LZ, Melio, TENSKEE, YuZ      |
|            6 |     1423 | 2024-06-06 | Limitless      | W   | 0.796      | 0.371        | 0.001 (0.000)    | 0.159 (0.047)    | 0 (0.000) |     9.06 | Gabie, J0LZ, Melio, TENSKEE, YuZ      |
|            5 |     1536 | 2024-06-04 | Wildcard       | L   | 0.784      | -            | -                | -                | -         |    -5.60 | Gabie, J0LZ, Melio, TENSKEE, YuZ      |
|            4 |     1544 | 2024-06-04 | TSM Shimmer    | W   | 0.782      | 0.371        | 0.020 (0.006)    | 0.191 (0.055)    | 0 (0.000) |    12.56 | Gabie, J0LZ, Melio, TENSKEE, YuZ      |
|            3 |     3416 | 2024-03-23 | Revenge Nation | L   | 0.297      | -            | -                | -                | -         |    -4.65 | Gabie, J0LZ, Melio, TENSKEE, YuZ      |
|            2 |     3443 | 2024-03-21 | Final Form     | W   | 0.284      | 0.359        | 0.003 (0.000)    | 0.063 (0.006)    | 0 (0.000) |     3.86 | Gabie, J0LZ, Melio, TENSKEE, YuZ      |
|            1 |     3494 | 2024-03-19 | Akimbo         | W   | 0.271      | 0.359        | 0.003 (0.000)    | 0.071 (0.007)    | 0 (0.000) |     3.83 | Gabie, J0LZ, Melio, TENSKEE, YuZ      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,308.29)
- Divide that value by the 5th highest value among all rosters ($320,521.62)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-10 |      0.824 | $1,250.00      | $1,030.03       |
| 2024-03-23 |      0.297 | $4,300.00      | $1,278.25       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
