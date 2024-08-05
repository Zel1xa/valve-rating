### Roster Details<br />
Team Name: Homyno<br />
Roster: BiNoX, J0LZ, Melio, Sup3rant, TENSKEE<br />
Global Rank: [168](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [47]( ../standings_americas.md)<br />
<br />
Final Rank Value:  665.9<br />
<br />
Final Rank Value (665.9) = Starting Rank Value (699.2) + Head To Head Adjustments (-33.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.319[<sup>1</sup>](#table2)
- Bounty Collected: 0.248[<sup>2</sup>](#table1)
- Opponent Network: 0.017[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.146<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 699.2
- 400 + ( ( 0.146 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 699.2


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
|           17 |       21 | 2024-08-04 | FLUFFY AIMERS  | L   | 1.000      | -            | -                | -                | -         |   -13.35 | BiNoX, J0LZ, Melio, Sup3rant, TENSKEE |
|           16 |      318 | 2024-07-27 | Revenge Nation | W   | 1.000      | 0.371        | 0.007 (0.002)    | 0.099 (0.037)    | 0 (0.000) |    17.22 | BiNoX, Gabie, J0LZ, Melio, TENSKEE    |
|           15 |     1039 | 2024-06-15 | E-Xolos LAZER  | L   | 0.862      | -            | -                | -                | -         |    -9.11 | Gabie, J0LZ, Melio, TENSKEE, YuZ      |
|           14 |     1075 | 2024-06-14 | Akimbo         | L   | 0.856      | -            | -                | -                | -         |    -8.98 | Gabie, J0LZ, Melio, TENSKEE, YuZ      |
|           13 |     1116 | 2024-06-13 | Detonate       | W   | 0.849      | 0.143        | 0.000 (0.000)    | 0.072 (0.009)    | 0 (0.000) |     8.21 | Gabie, J0LZ, Melio, TENSKEE, YuZ      |
|           12 |     1148 | 2024-06-12 | E-Xolos LAZER  | L   | 0.842      | -            | -                | -                | -         |    -9.34 | Gabie, J0LZ, Melio, TENSKEE, YuZ      |
|           11 |     1150 | 2024-06-12 | Detonate       | W   | 0.841      | 0.143        | 0.000 (0.000)    | 0.072 (0.009)    | 0 (0.000) |     7.85 | Gabie, J0LZ, Melio, TENSKEE, YuZ      |
|           10 |     1171 | 2024-06-11 | Final Form     | L   | 0.834      | -            | -                | -                | -         |   -14.59 | Gabie, J0LZ, Melio, TENSKEE, YuZ      |
|            9 |     1200 | 2024-06-10 | E-Xolos LAZER  | L   | 0.827      | -            | -                | -                | -         |   -10.33 | Gabie, J0LZ, Melio, TENSKEE, YuZ      |
|            8 |     1289 | 2024-06-08 | LAG            | L   | 0.815      | -            | -                | -                | -         |    -8.73 | Gabie, J0LZ, Melio, TENSKEE, YuZ      |
|            7 |     1342 | 2024-06-07 | E-Xolos LAZER  | L   | 0.809      | -            | -                | -                | -         |   -11.38 | Gabie, J0LZ, Melio, TENSKEE, YuZ      |
|            6 |     1412 | 2024-06-06 | Limitless      | W   | 0.801      | 0.371        | 0.001 (0.000)    | 0.164 (0.049)    | 0 (0.000) |     9.11 | Gabie, J0LZ, Melio, TENSKEE, YuZ      |
|            5 |     1525 | 2024-06-04 | Wildcard       | L   | 0.789      | -            | -                | -                | -         |    -5.61 | Gabie, J0LZ, Melio, TENSKEE, YuZ      |
|            4 |     1533 | 2024-06-04 | TSM Shimmer    | W   | 0.787      | 0.371        | 0.020 (0.006)    | 0.196 (0.057)    | 0 (0.000) |    12.63 | Gabie, J0LZ, Melio, TENSKEE, YuZ      |
|            3 |     3405 | 2024-03-23 | Revenge Nation | L   | 0.302      | -            | -                | -                | -         |    -4.73 | Gabie, J0LZ, Melio, TENSKEE, YuZ      |
|            2 |     3432 | 2024-03-21 | Final Form     | W   | 0.289      | 0.359        | 0.003 (0.000)    | 0.065 (0.007)    | 0 (0.000) |     3.93 | Gabie, J0LZ, Melio, TENSKEE, YuZ      |
|            1 |     3483 | 2024-03-19 | Akimbo         | W   | 0.276      | 0.359        | 0.003 (0.000)    | 0.073 (0.007)    | 0 (0.000) |     3.90 | Gabie, J0LZ, Melio, TENSKEE, YuZ      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,336.04)
- Divide that value by the 5th highest value among all rosters ($322,004.12)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-10 |      0.829 | $1,250.00      | $1,036.28       |
| 2024-03-23 |      0.302 | $4,300.00      | $1,299.75       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
