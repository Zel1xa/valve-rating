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
Final Rank Value (666.2) = Starting Rank Value (699.1) + Head To Head Adjustments (-33.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.318[<sup>1</sup>](#table2)
- Bounty Collected: 0.248[<sup>2</sup>](#table1)
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
|           17 |       24 | 2024-08-04 | FLUFFY AIMERS  | L   | 1.000      | -            | -                | -                | -         |   -13.36 | BiNoX, J0LZ, Melio, Sup3rant, TENSKEE |
|           16 |      321 | 2024-07-27 | Revenge Nation | W   | 1.000      | 0.371        | 0.007 (0.002)    | 0.099 (0.037)    | 0 (0.000) |    17.23 | BiNoX, Gabie, J0LZ, Melio, TENSKEE    |
|           15 |     1042 | 2024-06-15 | E-Xolos LAZER  | L   | 0.860      | -            | -                | -                | -         |    -9.05 | Gabie, J0LZ, Melio, TENSKEE, YuZ      |
|           14 |     1078 | 2024-06-14 | Akimbo         | L   | 0.853      | -            | -                | -                | -         |    -8.97 | Gabie, J0LZ, Melio, TENSKEE, YuZ      |
|           13 |     1119 | 2024-06-13 | DETONATE       | W   | 0.847      | 0.143        | 0.000 (0.000)    | 0.072 (0.009)    | 0 (0.000) |     8.20 | Gabie, J0LZ, Melio, TENSKEE, YuZ      |
|           12 |     1151 | 2024-06-12 | E-Xolos LAZER  | L   | 0.840      | -            | -                | -                | -         |    -9.28 | Gabie, J0LZ, Melio, TENSKEE, YuZ      |
|           11 |     1153 | 2024-06-12 | DETONATE       | W   | 0.839      | 0.143        | 0.000 (0.000)    | 0.072 (0.009)    | 0 (0.000) |     7.85 | Gabie, J0LZ, Melio, TENSKEE, YuZ      |
|           10 |     1174 | 2024-06-11 | Final Form     | L   | 0.832      | -            | -                | -                | -         |   -14.55 | Gabie, J0LZ, Melio, TENSKEE, YuZ      |
|            9 |     1203 | 2024-06-10 | E-Xolos LAZER  | L   | 0.825      | -            | -                | -                | -         |   -10.26 | Gabie, J0LZ, Melio, TENSKEE, YuZ      |
|            8 |     1292 | 2024-06-08 | LAG            | L   | 0.813      | -            | -                | -                | -         |    -8.70 | Gabie, J0LZ, Melio, TENSKEE, YuZ      |
|            7 |     1345 | 2024-06-07 | E-Xolos LAZER  | L   | 0.807      | -            | -                | -                | -         |   -11.28 | Gabie, J0LZ, Melio, TENSKEE, YuZ      |
|            6 |     1415 | 2024-06-06 | Limitless      | W   | 0.799      | 0.371        | 0.001 (0.000)    | 0.163 (0.048)    | 0 (0.000) |     9.10 | Gabie, J0LZ, Melio, TENSKEE, YuZ      |
|            5 |     1528 | 2024-06-04 | Wildcard       | L   | 0.787      | -            | -                | -                | -         |    -5.59 | Gabie, J0LZ, Melio, TENSKEE, YuZ      |
|            4 |     1536 | 2024-06-04 | TSM Shimmer    | W   | 0.785      | 0.371        | 0.020 (0.006)    | 0.195 (0.057)    | 0 (0.000) |    12.60 | Gabie, J0LZ, Melio, TENSKEE, YuZ      |
|            3 |     3408 | 2024-03-23 | Revenge Nation | L   | 0.300      | -            | -                | -                | -         |    -4.69 | Gabie, J0LZ, Melio, TENSKEE, YuZ      |
|            2 |     3435 | 2024-03-21 | Final Form     | W   | 0.287      | 0.359        | 0.003 (0.000)    | 0.065 (0.007)    | 0 (0.000) |     3.90 | Gabie, J0LZ, Melio, TENSKEE, YuZ      |
|            1 |     3486 | 2024-03-19 | Akimbo         | W   | 0.274      | 0.359        | 0.003 (0.000)    | 0.073 (0.007)    | 0 (0.000) |     3.87 | Gabie, J0LZ, Melio, TENSKEE, YuZ      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,323.71)
- Divide that value by the 5th highest value among all rosters ($321,345.23)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-10 |      0.827 | $1,250.00      | $1,033.51       |
| 2024-03-23 |      0.300 | $4,300.00      | $1,290.20       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
