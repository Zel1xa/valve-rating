### Roster Details<br />
Team Name: Homyno<br />
Roster: BiNoX, Gabie, J0LZ, Melio, TENSKEE<br />
Global Rank: [163](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [45]( ../standings_americas.md)<br />
<br />
Final Rank Value:  679.9<br />
<br />
Final Rank Value (679.9) = Starting Rank Value (700.0) + Head To Head Adjustments (-20.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.319[<sup>1</sup>](#table2)
- Bounty Collected: 0.248[<sup>2</sup>](#table1)
- Opponent Network: 0.019[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.147<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 700.0
- 400 + ( ( 0.147 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 700.0


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
|           16 |      235 | 2024-07-27 | Revenge Nation | W   | 1.000      | 0.371        | 0.007 (0.003)    | 0.104 (0.038)    | 0 (0.000) |    17.26 | BiNoX, Gabie, J0LZ, Melio, TENSKEE |
|           15 |      940 | 2024-06-15 | E-Xolos LAZER  | L   | 0.876      | -            | -                | -                | -         |    -9.49 | Gabie, J0LZ, Melio, TENSKEE, YuZ   |
|           14 |      970 | 2024-06-14 | Akimbo         | L   | 0.869      | -            | -                | -                | -         |    -9.12 | Gabie, J0LZ, Melio, TENSKEE, YuZ   |
|           13 |     1005 | 2024-06-13 | Detonate       | W   | 0.862      | 0.143        | 0.000 (0.000)    | 0.075 (0.009)    | 0 (0.000) |     8.32 | Gabie, J0LZ, Melio, TENSKEE, YuZ   |
|           12 |     1037 | 2024-06-12 | E-Xolos LAZER  | L   | 0.856      | -            | -                | -                | -         |    -9.77 | Gabie, J0LZ, Melio, TENSKEE, YuZ   |
|           11 |     1038 | 2024-06-12 | Detonate       | W   | 0.855      | 0.143        | 0.000 (0.000)    | 0.075 (0.009)    | 0 (0.000) |     7.93 | Gabie, J0LZ, Melio, TENSKEE, YuZ   |
|           10 |     1058 | 2024-06-11 | Final Form     | L   | 0.848      | -            | -                | -                | -         |   -14.86 | Gabie, J0LZ, Melio, TENSKEE, YuZ   |
|            9 |     1085 | 2024-06-10 | E-Xolos LAZER  | L   | 0.840      | -            | -                | -                | -         |   -10.56 | Gabie, J0LZ, Melio, TENSKEE, YuZ   |
|            8 |     1173 | 2024-06-08 | LAG            | L   | 0.829      | -            | -                | -                | -         |    -8.45 | Gabie, J0LZ, Melio, TENSKEE, YuZ   |
|            7 |     1221 | 2024-06-07 | E-Xolos LAZER  | L   | 0.822      | -            | -                | -                | -         |   -11.64 | Gabie, J0LZ, Melio, TENSKEE, YuZ   |
|            6 |     1291 | 2024-06-06 | Limitless      | W   | 0.814      | 0.371        | 0.001 (0.000)    | 0.174 (0.052)    | 0 (0.000) |     9.23 | Gabie, J0LZ, Melio, TENSKEE, YuZ   |
|            5 |     1404 | 2024-06-04 | Wildcard       | L   | 0.802      | -            | -                | -                | -         |    -5.05 | Gabie, J0LZ, Melio, TENSKEE, YuZ   |
|            4 |     1412 | 2024-06-04 | TSM Shimmer    | W   | 0.800      | 0.371        | 0.020 (0.006)    | 0.206 (0.061)    | 0 (0.000) |    12.82 | Gabie, J0LZ, Melio, TENSKEE, YuZ   |
|            3 |     3274 | 2024-03-23 | Revenge Nation | L   | 0.316      | -            | -                | -                | -         |    -4.94 | Gabie, J0LZ, Melio, TENSKEE, YuZ   |
|            2 |     3299 | 2024-03-21 | Final Form     | W   | 0.302      | 0.359        | 0.003 (0.000)    | 0.068 (0.007)    | 0 (0.000) |     4.10 | Gabie, J0LZ, Melio, TENSKEE, YuZ   |
|            1 |     3350 | 2024-03-19 | Akimbo         | W   | 0.289      | 0.359        | 0.003 (0.000)    | 0.078 (0.008)    | 0 (0.000) |     4.10 | Gabie, J0LZ, Melio, TENSKEE, YuZ   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,410.30)
- Divide that value by the 5th highest value among all rosters ($325,971.18)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-10 |      0.842 | $1,250.00      | $1,053.01       |
| 2024-03-23 |      0.316 | $4,300.00      | $1,357.29       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
