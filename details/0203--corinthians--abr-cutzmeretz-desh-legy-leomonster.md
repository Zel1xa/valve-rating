### Roster Details<br />
Team Name: Corinthians<br />
Roster: abr, CutzMeretz, desh, legy, Leomonster<br />
Global Rank: [203](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [58]( ../standings_americas.md)<br />
<br />
Final Rank Value:  511.3<br />
<br />
Final Rank Value (511.3) = Starting Rank Value (510.7) + Head To Head Adjustments (0.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.211[<sup>2</sup>](#table1)
- Opponent Network: 0.005[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.054<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 510.7
- 400 + ( ( 0.054 - 0.000 ) / ( 0.781 - 0.000 ) ) * 1600 = 510.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent     | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                  |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           26 |     1703 | 2024-05-29 | 9z Academy   | W   | 0.747      | 0.371        | 0.000 (0.000)    | 0.070 (0.019)    | 0 (0.000) |    11.71 | abr, CutzMeretz, desh, legy, Leomonster |
|           25 |     1718 | 2024-05-28 | Hype         | L   | 0.741      | -            | -                | -                | -         |    -2.52 | abr, CutzMeretz, desh, legy, Leomonster |
|           24 |     1919 | 2024-05-20 | BESTIA       | L   | 0.689      | -            | -                | -                | -         |    -1.32 | abr, CutzMeretz, desh, legy, Leomonster |
|           23 |     2093 | 2024-05-15 | Case         | L   | 0.656      | -            | -                | -                | -         |    -2.09 | abr, CutzMeretz, desh, legy, Leomonster |
|           22 |     2096 | 2024-05-15 | Case         | L   | 0.655      | -            | -                | -                | -         |    -2.14 | abr, CutzMeretz, desh, legy, Leomonster |
|           21 |     2145 | 2024-05-14 | RED Canids   | L   | 0.649      | -            | -                | -                | -         |    -0.72 | abr, CutzMeretz, desh, legy, Leomonster |
|           20 |     2150 | 2024-05-14 | RED Canids   | L   | 0.649      | -            | -                | -                | -         |    -0.72 | abr, CutzMeretz, desh, legy, Leomonster |
|           19 |     3159 | 2024-04-04 | Fluxo        | L   | 0.383      | -            | -                | -                | -         |    -0.55 | abr, CutzMeretz, desh, legy, Leomonster |
|           18 |     3165 | 2024-04-04 | Fluxo        | L   | 0.383      | -            | -                | -                | -         |    -0.55 | abr, CutzMeretz, desh, legy, Leomonster |
|           17 |     3335 | 2024-03-27 | 2GAME        | L   | 0.330      | -            | -                | -                | -         |    -2.98 | abr, CutzMeretz, desh, legy, Leomonster |
|           16 |     3339 | 2024-03-27 | 2GAME        | W   | 0.329      | 0.450        | 0.002 (0.000)    | 0.051 (0.008)    | 0 (0.000) |     7.54 | abr, CutzMeretz, desh, legy, Leomonster |
|           15 |     3614 | 2024-03-13 | MIBR Academy | L   | 0.235      | -            | -                | -                | -         |    -3.73 | abr, CutzMeretz, desh, legy, Leomonster |
|           14 |     3669 | 2024-03-11 | RED Canids   | L   | 0.221      | -            | -                | -                | -         |    -0.28 | abr, CutzMeretz, desh, legy, Leomonster |
|           13 |     3721 | 2024-03-09 | Fluxo        | L   | 0.207      | -            | -                | -                | -         |    -0.30 | abr, CutzMeretz, desh, legy, Leomonster |
|           12 |     3770 | 2024-03-07 | Sharks       | L   | 0.194      | -            | -                | -                | -         |    -0.41 | abr, CutzMeretz, desh, legy, Leomonster |
|           11 |     4026 | 2024-02-24 | W7M          | L   | 0.116      | -            | -                | -                | -         |    -0.49 | abr, CutzMeretz, desh, legy, Leomonster |
|           10 |     4033 | 2024-02-24 | W7M          | L   | 0.116      | -            | -                | -                | -         |    -0.49 | abr, CutzMeretz, desh, legy, Leomonster |
|            9 |     4055 | 2024-02-23 | Galorys      | W   | 0.110      | 0.450        | 0.030 (0.001)    | 0.550 (0.027)    | 0 (0.000) |     3.10 | abr, CutzMeretz, desh, legy, Leomonster |
|            8 |     4056 | 2024-02-23 | Galorys      | L   | 0.109      | -            | -                | -                | -         |    -0.35 | abr, CutzMeretz, desh, legy, Leomonster |
|            7 |     4089 | 2024-02-21 | Sharks       | L   | 0.096      | -            | -                | -                | -         |    -0.21 | abr, CutzMeretz, desh, legy, Leomonster |
|            6 |     4198 | 2024-02-17 | Galorys      | L   | 0.068      | -            | -                | -                | -         |    -0.21 | abr, CutzMeretz, desh, legy, Leomonster |
|            5 |     4277 | 2024-02-14 | adalYamigos  | L   | 0.050      | -            | -                | -                | -         |    -0.63 | abr, CutzMeretz, desh, legy, Leomonster |
|            4 |     4284 | 2024-02-14 | adalYamigos  | L   | 0.049      | -            | -                | -                | -         |    -0.62 | abr, CutzMeretz, desh, legy, Leomonster |
|            3 |     4291 | 2024-02-14 | Solid        | L   | 0.048      | -            | -                | -                | -         |    -0.15 | abr, CutzMeretz, desh, legy, Leomonster |
|            2 |     4330 | 2024-02-13 | W7M          | L   | 0.041      | -            | -                | -                | -         |    -0.17 | abr, CutzMeretz, desh, legy, Leomonster |
|            1 |     4341 | 2024-02-12 | W7M          | L   | 0.035      | -            | -                | -                | -         |    -0.15 | abr, CutzMeretz, desh, legy, Leomonster |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($322,333.56)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
