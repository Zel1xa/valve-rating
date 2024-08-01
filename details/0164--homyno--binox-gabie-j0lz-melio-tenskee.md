### Roster Details<br />
Team Name: Homyno<br />
Roster: BiNoX, Gabie, J0LZ, Melio, TENSKEE<br />
Global Rank: [164](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [46]( ../standings_americas.md)<br />
<br />
Final Rank Value:  683.7<br />
<br />
Final Rank Value (683.7) = Starting Rank Value (703.4) + Head To Head Adjustments (-19.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.321[<sup>1</sup>](#table2)
- Bounty Collected: 0.250[<sup>2</sup>](#table1)
- Opponent Network: 0.019[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.147<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 703.4
- 400 + ( ( 0.147 - 0.000 ) / ( 0.777 - 0.000 ) ) * 1600 = 703.4


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
|           16 |      173 | 2024-07-27 | Revenge Nation | W   | 1.000      | 0.371        | 0.007 (0.003)    | 0.100 (0.037)    | 0 (0.000) |    17.26 | BiNoX, Gabie, J0LZ, Melio, TENSKEE |
|           15 |      909 | 2024-06-15 | E-Xolos LAZER  | L   | 0.890      | -            | -                | -                | -         |    -9.62 | Gabie, J0LZ, Melio, TENSKEE, YuZ   |
|           14 |      941 | 2024-06-14 | Akimbo         | L   | 0.884      | -            | -                | -                | -         |    -9.16 | Gabie, J0LZ, Melio, TENSKEE, YuZ   |
|           13 |      977 | 2024-06-13 | Detonate       | W   | 0.877      | 0.143        | 0.000 (0.000)    | 0.072 (0.009)    | 0 (0.000) |     8.37 | Gabie, J0LZ, Melio, TENSKEE, YuZ   |
|           12 |     1009 | 2024-06-12 | E-Xolos LAZER  | L   | 0.870      | -            | -                | -                | -         |    -9.64 | Gabie, J0LZ, Melio, TENSKEE, YuZ   |
|           11 |     1011 | 2024-06-12 | Detonate       | W   | 0.869      | 0.143        | 0.000 (0.000)    | 0.072 (0.009)    | 0 (0.000) |     7.99 | Gabie, J0LZ, Melio, TENSKEE, YuZ   |
|           10 |     1033 | 2024-06-11 | Final Form     | L   | 0.862      | -            | -                | -                | -         |   -14.97 | Gabie, J0LZ, Melio, TENSKEE, YuZ   |
|            9 |     1063 | 2024-06-10 | E-Xolos LAZER  | L   | 0.855      | -            | -                | -                | -         |   -10.71 | Gabie, J0LZ, Melio, TENSKEE, YuZ   |
|            8 |     1154 | 2024-06-08 | LAG            | L   | 0.843      | -            | -                | -                | -         |    -8.34 | Gabie, J0LZ, Melio, TENSKEE, YuZ   |
|            7 |     1210 | 2024-06-07 | E-Xolos LAZER  | L   | 0.837      | -            | -                | -                | -         |   -11.82 | Gabie, J0LZ, Melio, TENSKEE, YuZ   |
|            6 |     1286 | 2024-06-06 | Limitless      | W   | 0.829      | 0.371        | 0.001 (0.000)    | 0.170 (0.052)    | 0 (0.000) |     9.40 | Gabie, J0LZ, Melio, TENSKEE, YuZ   |
|            5 |     1402 | 2024-06-04 | Wildcard       | L   | 0.817      | -            | -                | -                | -         |    -4.99 | Gabie, J0LZ, Melio, TENSKEE, YuZ   |
|            4 |     1410 | 2024-06-04 | TSM Shimmer    | W   | 0.815      | 0.371        | 0.021 (0.006)    | 0.200 (0.060)    | 0 (0.000) |    13.04 | Gabie, J0LZ, Melio, TENSKEE, YuZ   |
|            3 |     3349 | 2024-03-23 | Revenge Nation | L   | 0.330      | -            | -                | -                | -         |    -5.17 | Gabie, J0LZ, Melio, TENSKEE, YuZ   |
|            2 |     3376 | 2024-03-21 | Final Form     | W   | 0.317      | 0.359        | 0.003 (0.000)    | 0.098 (0.011)    | 0 (0.000) |     4.29 | Gabie, J0LZ, Melio, TENSKEE, YuZ   |
|            1 |     3427 | 2024-03-19 | Akimbo         | W   | 0.304      | 0.359        | 0.003 (0.000)    | 0.109 (0.012)    | 0 (0.000) |     4.34 | Gabie, J0LZ, Melio, TENSKEE, YuZ   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,491.75)
- Divide that value by the 5th highest value among all rosters ($327,422.13)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-10 |      0.857 | $1,250.00      | $1,071.35       |
| 2024-03-23 |      0.330 | $4,300.00      | $1,420.39       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
