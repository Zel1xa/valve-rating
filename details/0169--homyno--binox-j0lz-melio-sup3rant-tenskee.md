### Roster Details<br />
Team Name: Homyno<br />
Roster: BiNoX, J0LZ, Melio, Sup3rant, TENSKEE<br />
Global Rank: [169](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [47]( ../standings_americas.md)<br />
<br />
Final Rank Value:  665.7<br />
<br />
Final Rank Value (665.7) = Starting Rank Value (699.0) + Head To Head Adjustments (-33.3)<br />

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


| Match Played | Match ID | Date       | Opponent       | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           17 |        1 | 2024-08-04 | FLUFFY AIMERS  | L   | 1.000      | -            | -                | -                | -         |   -13.33 | BiNoX, J0LZ, Melio, Sup3rant, TENSKEE |
|           16 |      297 | 2024-07-27 | Revenge Nation | W   | 1.000      | 0.371        | 0.007 (0.002)    | 0.101 (0.037)    | 0 (0.000) |    17.23 | BiNoX, Gabie, J0LZ, Melio, TENSKEE    |
|           15 |     1018 | 2024-06-15 | E-Xolos LAZER  | L   | 0.867      | -            | -                | -                | -         |    -9.15 | Gabie, J0LZ, Melio, TENSKEE, YuZ      |
|           14 |     1054 | 2024-06-14 | Akimbo         | L   | 0.860      | -            | -                | -                | -         |    -9.01 | Gabie, J0LZ, Melio, TENSKEE, YuZ      |
|           13 |     1095 | 2024-06-13 | Detonate       | W   | 0.853      | 0.143        | 0.000 (0.000)    | 0.073 (0.009)    | 0 (0.000) |     8.25 | Gabie, J0LZ, Melio, TENSKEE, YuZ      |
|           12 |     1127 | 2024-06-12 | E-Xolos LAZER  | L   | 0.847      | -            | -                | -                | -         |    -9.38 | Gabie, J0LZ, Melio, TENSKEE, YuZ      |
|           11 |     1129 | 2024-06-12 | Detonate       | W   | 0.846      | 0.143        | 0.000 (0.000)    | 0.073 (0.009)    | 0 (0.000) |     7.89 | Gabie, J0LZ, Melio, TENSKEE, YuZ      |
|           10 |     1150 | 2024-06-11 | Final Form     | L   | 0.839      | -            | -                | -                | -         |   -14.67 | Gabie, J0LZ, Melio, TENSKEE, YuZ      |
|            9 |     1179 | 2024-06-10 | E-Xolos LAZER  | L   | 0.831      | -            | -                | -                | -         |   -10.38 | Gabie, J0LZ, Melio, TENSKEE, YuZ      |
|            8 |     1268 | 2024-06-08 | LAG            | L   | 0.820      | -            | -                | -                | -         |    -8.75 | Gabie, J0LZ, Melio, TENSKEE, YuZ      |
|            7 |     1321 | 2024-06-07 | E-Xolos LAZER  | L   | 0.813      | -            | -                | -                | -         |   -11.44 | Gabie, J0LZ, Melio, TENSKEE, YuZ      |
|            6 |     1391 | 2024-06-06 | Limitless      | W   | 0.805      | 0.371        | 0.001 (0.000)    | 0.167 (0.050)    | 0 (0.000) |     9.15 | Gabie, J0LZ, Melio, TENSKEE, YuZ      |
|            5 |     1504 | 2024-06-04 | Wildcard       | L   | 0.793      | -            | -                | -                | -         |    -5.61 | Gabie, J0LZ, Melio, TENSKEE, YuZ      |
|            4 |     1512 | 2024-06-04 | TSM Shimmer    | W   | 0.792      | 0.371        | 0.020 (0.006)    | 0.199 (0.058)    | 0 (0.000) |    12.69 | Gabie, J0LZ, Melio, TENSKEE, YuZ      |
|            3 |     3384 | 2024-03-23 | Revenge Nation | L   | 0.307      | -            | -                | -                | -         |    -4.80 | Gabie, J0LZ, Melio, TENSKEE, YuZ      |
|            2 |     3411 | 2024-03-21 | Final Form     | W   | 0.294      | 0.359        | 0.003 (0.000)    | 0.066 (0.007)    | 0 (0.000) |     3.99 | Gabie, J0LZ, Melio, TENSKEE, YuZ      |
|            1 |     3462 | 2024-03-19 | Akimbo         | W   | 0.280      | 0.359        | 0.003 (0.000)    | 0.075 (0.008)    | 0 (0.000) |     3.97 | Gabie, J0LZ, Melio, TENSKEE, YuZ      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,360.71)
- Divide that value by the 5th highest value among all rosters ($323,321.90)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-10 |      0.833 | $1,250.00      | $1,041.84       |
| 2024-03-23 |      0.307 | $4,300.00      | $1,318.87       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
