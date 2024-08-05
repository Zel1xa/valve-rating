### Roster Details<br />
Team Name: Corinthians<br />
Roster: abr, CutzMeretz, desh, legy, Leomonster<br />
Global Rank: [203](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [58]( ../standings_americas.md)<br />
<br />
Final Rank Value:  511.4<br />
<br />
Final Rank Value (511.4) = Starting Rank Value (510.9) + Head To Head Adjustments (0.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.211[<sup>2</sup>](#table1)
- Opponent Network: 0.006[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.054<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 510.9
- 400 + ( ( 0.054 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 510.9


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
|           26 |     1690 | 2024-05-29 | 9z Academy   | W   | 0.750      | 0.371        | 0.000 (0.000)    | 0.070 (0.019)    | 0 (0.000) |    11.75 | abr, CutzMeretz, desh, legy, Leomonster |
|           25 |     1705 | 2024-05-28 | Hype         | L   | 0.745      | -            | -                | -                | -         |    -2.54 | abr, CutzMeretz, desh, legy, Leomonster |
|           24 |     1906 | 2024-05-20 | BESTIA       | L   | 0.693      | -            | -                | -                | -         |    -1.32 | abr, CutzMeretz, desh, legy, Leomonster |
|           23 |     2080 | 2024-05-15 | Case         | L   | 0.659      | -            | -                | -                | -         |    -2.11 | abr, CutzMeretz, desh, legy, Leomonster |
|           22 |     2083 | 2024-05-15 | Case         | L   | 0.659      | -            | -                | -                | -         |    -2.15 | abr, CutzMeretz, desh, legy, Leomonster |
|           21 |     2132 | 2024-05-14 | RED Canids   | L   | 0.653      | -            | -                | -                | -         |    -0.72 | abr, CutzMeretz, desh, legy, Leomonster |
|           20 |     2137 | 2024-05-14 | RED Canids   | L   | 0.652      | -            | -                | -                | -         |    -0.72 | abr, CutzMeretz, desh, legy, Leomonster |
|           19 |     3146 | 2024-04-04 | Fluxo        | L   | 0.386      | -            | -                | -                | -         |    -0.55 | abr, CutzMeretz, desh, legy, Leomonster |
|           18 |     3152 | 2024-04-04 | Fluxo        | L   | 0.386      | -            | -                | -                | -         |    -0.56 | abr, CutzMeretz, desh, legy, Leomonster |
|           17 |     3322 | 2024-03-27 | 2GAME        | L   | 0.333      | -            | -                | -                | -         |    -3.00 | abr, CutzMeretz, desh, legy, Leomonster |
|           16 |     3326 | 2024-03-27 | 2GAME        | W   | 0.333      | 0.450        | 0.002 (0.000)    | 0.052 (0.008)    | 0 (0.000) |     7.62 | abr, CutzMeretz, desh, legy, Leomonster |
|           15 |     3601 | 2024-03-13 | MIBR Academy | L   | 0.238      | -            | -                | -                | -         |    -3.78 | abr, CutzMeretz, desh, legy, Leomonster |
|           14 |     3656 | 2024-03-11 | RED Canids   | L   | 0.225      | -            | -                | -                | -         |    -0.28 | abr, CutzMeretz, desh, legy, Leomonster |
|           13 |     3708 | 2024-03-09 | Fluxo        | L   | 0.210      | -            | -                | -                | -         |    -0.31 | abr, CutzMeretz, desh, legy, Leomonster |
|           12 |     3757 | 2024-03-07 | Sharks       | L   | 0.197      | -            | -                | -                | -         |    -0.42 | abr, CutzMeretz, desh, legy, Leomonster |
|           11 |     4013 | 2024-02-24 | W7M          | L   | 0.120      | -            | -                | -                | -         |    -0.51 | abr, CutzMeretz, desh, legy, Leomonster |
|           10 |     4020 | 2024-02-24 | W7M          | L   | 0.119      | -            | -                | -                | -         |    -0.51 | abr, CutzMeretz, desh, legy, Leomonster |
|            9 |     4042 | 2024-02-23 | Galorys      | W   | 0.113      | 0.450        | 0.030 (0.002)    | 0.552 (0.028)    | 0 (0.000) |     3.20 | abr, CutzMeretz, desh, legy, Leomonster |
|            8 |     4043 | 2024-02-23 | Galorys      | L   | 0.113      | -            | -                | -                | -         |    -0.36 | abr, CutzMeretz, desh, legy, Leomonster |
|            7 |     4076 | 2024-02-21 | Sharks       | L   | 0.100      | -            | -                | -                | -         |    -0.22 | abr, CutzMeretz, desh, legy, Leomonster |
|            6 |     4185 | 2024-02-17 | Galorys      | L   | 0.071      | -            | -                | -                | -         |    -0.22 | abr, CutzMeretz, desh, legy, Leomonster |
|            5 |     4264 | 2024-02-14 | adalYamigos  | L   | 0.053      | -            | -                | -                | -         |    -0.67 | abr, CutzMeretz, desh, legy, Leomonster |
|            4 |     4271 | 2024-02-14 | adalYamigos  | L   | 0.053      | -            | -                | -                | -         |    -0.66 | abr, CutzMeretz, desh, legy, Leomonster |
|            3 |     4278 | 2024-02-14 | Solid        | L   | 0.051      | -            | -                | -                | -         |    -0.16 | abr, CutzMeretz, desh, legy, Leomonster |
|            2 |     4317 | 2024-02-13 | W7M          | L   | 0.044      | -            | -                | -                | -         |    -0.19 | abr, CutzMeretz, desh, legy, Leomonster |
|            1 |     4328 | 2024-02-12 | W7M          | L   | 0.038      | -            | -                | -                | -         |    -0.16 | abr, CutzMeretz, desh, legy, Leomonster |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($323,321.90)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
