### Roster Details<br />
Team Name: Homyno<br />
Roster: BiNoX, Gabie, J0LZ, Melio, TENSKEE<br />
Global Rank: [164](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [46]( ../standings_americas.md)<br />
<br />
Final Rank Value:  683.3<br />
<br />
Final Rank Value (683.3) = Starting Rank Value (702.9) + Head To Head Adjustments (-19.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.321[<sup>1</sup>](#table2)
- Bounty Collected: 0.249[<sup>2</sup>](#table1)
- Opponent Network: 0.019[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.147<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 702.9
- 400 + ( ( 0.147 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 702.9


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
|           16 |      179 | 2024-07-27 | Revenge Nation | W   | 1.000      | 0.371        | 0.007 (0.003)    | 0.100 (0.037)    | 0 (0.000) |    17.26 | BiNoX, Gabie, J0LZ, Melio, TENSKEE |
|           15 |      915 | 2024-06-15 | E-Xolos LAZER  | L   | 0.889      | -            | -                | -                | -         |    -9.60 | Gabie, J0LZ, Melio, TENSKEE, YuZ   |
|           14 |      947 | 2024-06-14 | Akimbo         | L   | 0.882      | -            | -                | -                | -         |    -9.15 | Gabie, J0LZ, Melio, TENSKEE, YuZ   |
|           13 |      983 | 2024-06-13 | Detonate       | W   | 0.875      | 0.143        | 0.000 (0.000)    | 0.072 (0.009)    | 0 (0.000) |     8.36 | Gabie, J0LZ, Melio, TENSKEE, YuZ   |
|           12 |     1015 | 2024-06-12 | E-Xolos LAZER  | L   | 0.869      | -            | -                | -                | -         |    -9.62 | Gabie, J0LZ, Melio, TENSKEE, YuZ   |
|           11 |     1017 | 2024-06-12 | Detonate       | W   | 0.868      | 0.143        | 0.000 (0.000)    | 0.072 (0.009)    | 0 (0.000) |     7.98 | Gabie, J0LZ, Melio, TENSKEE, YuZ   |
|           10 |     1039 | 2024-06-11 | Final Form     | L   | 0.861      | -            | -                | -                | -         |   -14.94 | Gabie, J0LZ, Melio, TENSKEE, YuZ   |
|            9 |     1069 | 2024-06-10 | E-Xolos LAZER  | L   | 0.853      | -            | -                | -                | -         |   -10.69 | Gabie, J0LZ, Melio, TENSKEE, YuZ   |
|            8 |     1160 | 2024-06-08 | LAG            | L   | 0.842      | -            | -                | -                | -         |    -8.33 | Gabie, J0LZ, Melio, TENSKEE, YuZ   |
|            7 |     1216 | 2024-06-07 | E-Xolos LAZER  | L   | 0.835      | -            | -                | -                | -         |   -11.80 | Gabie, J0LZ, Melio, TENSKEE, YuZ   |
|            6 |     1292 | 2024-06-06 | Limitless      | W   | 0.827      | 0.371        | 0.001 (0.000)    | 0.170 (0.052)    | 0 (0.000) |     9.38 | Gabie, J0LZ, Melio, TENSKEE, YuZ   |
|            5 |     1408 | 2024-06-04 | Wildcard       | L   | 0.815      | -            | -                | -                | -         |    -4.99 | Gabie, J0LZ, Melio, TENSKEE, YuZ   |
|            4 |     1416 | 2024-06-04 | TSM Shimmer    | W   | 0.813      | 0.371        | 0.021 (0.006)    | 0.200 (0.060)    | 0 (0.000) |    13.01 | Gabie, J0LZ, Melio, TENSKEE, YuZ   |
|            3 |     3355 | 2024-03-23 | Revenge Nation | L   | 0.329      | -            | -                | -                | -         |    -5.14 | Gabie, J0LZ, Melio, TENSKEE, YuZ   |
|            2 |     3382 | 2024-03-21 | Final Form     | W   | 0.315      | 0.359        | 0.003 (0.000)    | 0.098 (0.011)    | 0 (0.000) |     4.26 | Gabie, J0LZ, Melio, TENSKEE, YuZ   |
|            1 |     3433 | 2024-03-19 | Akimbo         | W   | 0.302      | 0.359        | 0.003 (0.000)    | 0.109 (0.012)    | 0 (0.000) |     4.32 | Gabie, J0LZ, Melio, TENSKEE, YuZ   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,482.50)
- Divide that value by the 5th highest value among all rosters ($326,952.13)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-10 |      0.855 | $1,250.00      | $1,069.27       |
| 2024-03-23 |      0.329 | $4,300.00      | $1,413.23       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
