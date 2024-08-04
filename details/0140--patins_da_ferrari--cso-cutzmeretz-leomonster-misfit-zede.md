### Roster Details<br />
Team Name: Patins da Ferrari<br />
Roster: CSO, CutzMeretz, Leomonster, Misfit, zede<br />
Global Rank: [140](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [38]( ../standings_americas.md)<br />
<br />
Final Rank Value:  749.2<br />
<br />
Final Rank Value (749.2) = Starting Rank Value (789.7) + Head To Head Adjustments (-40.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.344[<sup>1</sup>](#table2)
- Bounty Collected: 0.312[<sup>2</sup>](#table1)
- Opponent Network: 0.107[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.191<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 789.7
- 400 + ( ( 0.191 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 789.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent       | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                    |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           24 |      264 | 2024-07-27 | Case           | L   | 1.000      | -            | -                | -                | -         |    -9.41 | CSO, CutzMeretz, Leomonster, Misfit, zede |
|           23 |      280 | 2024-07-26 | ODDIK          | L   | 1.000      | -            | -                | -                | -         |    -5.59 | CSO, CutzMeretz, Leomonster, Misfit, zede |
|           22 |      292 | 2024-07-26 | ODDIK          | L   | 1.000      | -            | -                | -                | -         |    -6.54 | CSO, CutzMeretz, Leomonster, Misfit, zede |
|           21 |      316 | 2024-07-25 | Sharks         | L   | 1.000      | -            | -                | -                | -         |    -7.21 | CSO, CutzMeretz, Leomonster, MTGG, zede   |
|           20 |      395 | 2024-07-23 | Galorys        | L   | 1.000      | -            | -                | -                | -         |   -14.58 | CSO, CutzMeretz, Leomonster, MTGG, zede   |
|           19 |      422 | 2024-07-22 | paiN Academy   | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     3.00 | CSO, CutzMeretz, Leomonster, MTGG, zede   |
|           18 |      432 | 2024-07-22 | ODDIK          | L   | 1.000      | -            | -                | -                | -         |    -6.33 | CSO, CutzMeretz, Leomonster, MTGG, zede   |
|           17 |      457 | 2024-07-21 | FURIA Academy  | W   | 1.000      | 0.371        | 0.000 (0.000)    | 0.105 (0.039)    | 0 (0.000) |     5.94 | CSO, CutzMeretz, Leomonster, MTGG, zede   |
|           16 |      494 | 2024-07-20 | KRÜ            | L   | 1.000      | -            | -                | -                | -         |   -13.50 | CSO, CutzMeretz, Leomonster, MTGG, zede   |
|           15 |      623 | 2024-07-17 | Hawks          | W   | 1.000      | 0.371        | 0.000 (0.000)    | 0.029 (0.011)    | 0 (0.000) |     5.69 | CSO, CutzMeretz, Leomonster, MTGG, zede   |
|           14 |      686 | 2024-07-16 | Vikings KR     | L   | 1.000      | -            | -                | -                | -         |   -14.80 | CSO, CutzMeretz, Leomonster, MTGG, zede   |
|           13 |      825 | 2024-07-10 | ODDIK          | L   | 1.000      | -            | -                | -                | -         |    -8.57 | bsd, CSO, CutzMeretz, Leomonster, zede    |
|           12 |      847 | 2024-07-09 | Solid          | L   | 1.000      | -            | -                | -                | -         |   -14.78 | bsd, CSO, CutzMeretz, Leomonster, zede    |
|           11 |      865 | 2024-07-08 | Sharks         | L   | 1.000      | -            | -                | -                | -         |    -8.92 | bsd, CSO, CutzMeretz, Leomonster, zede    |
|           10 |      888 | 2024-07-06 | 9z Academy     | W   | 1.000      | 0.333        | 0.000 (0.000)    | 0.070 (0.023)    | 0 (0.000) |     4.05 | bsd, CSO, CutzMeretz, Leomonster, zede    |
|            9 |      898 | 2024-07-01 | Vikings KR     | L   | 0.976      | -            | -                | -                | -         |   -15.96 | bsd, CutzMeretz, Leomonster, perez, zede  |
|            8 |      901 | 2024-06-30 | Sharks         | W   | 0.970      | 0.333        | 0.030 (0.010)    | 0.565 (0.182)    | 0 (0.000) |    21.97 | bsd, CutzMeretz, Leomonster, perez, zede  |
|            7 |      911 | 2024-06-29 | Bounty Hunters | L   | 0.962      | -            | -                | -                | -         |   -10.51 | bsd, CutzMeretz, Leomonster, perez, zede  |
|            6 |      928 | 2024-06-26 | Dusty Roots    | W   | 0.942      | 0.333        | 0.006 (0.002)    | 0.369 (0.116)    | 0 (0.000) |    14.68 | bsd, CutzMeretz, Leomonster, perez, zede  |
|            5 |     1032 | 2024-06-14 | inSanitY       | L   | 0.862      | -            | -                | -                | -         |    -8.32 | CutzMeretz, desh, Leomonster, roz, zede   |
|            4 |     1199 | 2024-06-09 | Vikings KR     | W   | 0.828      | 0.450        | 0.008 (0.003)    | 0.505 (0.188)    | 0 (0.000) |    12.38 | CutzMeretz, desh, Leomonster, roz, zede   |
|            3 |     1265 | 2024-06-08 | Sharks         | W   | 0.821      | 0.450        | 0.030 (0.011)    | 0.565 (0.209)    | 0 (0.000) |    20.21 | CutzMeretz, desh, Leomonster, roz, zede   |
|            2 |     1290 | 2024-06-07 | paiN           | L   | 0.817      | -            | -                | -                | -         |    -1.24 | CutzMeretz, desh, Leomonster, roz, zede   |
|            1 |     1374 | 2024-06-06 | ODDIK          | W   | 0.809      | 0.450        | 0.098 (0.036)    | 0.831 (0.302)    | 0 (0.000) |    17.87 | CutzMeretz, desh, Leomonster, roz, zede   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,988.89)
- Divide that value by the 5th highest value among all rosters ($324,557.31)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-27 |      1.000 | $1,800.00      | $1,800.00       |
| 2024-06-16 |      0.876 | $2,500.00      | $2,188.89       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
