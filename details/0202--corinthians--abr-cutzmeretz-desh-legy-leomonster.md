### Roster Details<br />
Team Name: Corinthians<br />
Roster: abr, CutzMeretz, desh, legy, Leomonster<br />
Global Rank: [202](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [57]( ../standings_americas.md)<br />
<br />
Final Rank Value:  511.6<br />
<br />
Final Rank Value (511.6) = Starting Rank Value (511.3) + Head To Head Adjustments (0.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.212[<sup>2</sup>](#table1)
- Opponent Network: 0.006[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.054<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 511.3
- 400 + ( ( 0.054 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 511.3


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
|           26 |     1654 | 2024-05-29 | 9z Academy   | W   | 0.755      | 0.371        | 0.000 (0.000)    | 0.070 (0.019)    | 0 (0.000) |    11.81 | abr, CutzMeretz, desh, legy, Leomonster |
|           25 |     1669 | 2024-05-28 | Hype         | L   | 0.749      | -            | -                | -                | -         |    -2.56 | abr, CutzMeretz, desh, legy, Leomonster |
|           24 |     1870 | 2024-05-20 | BESTIA       | L   | 0.697      | -            | -                | -                | -         |    -1.33 | abr, CutzMeretz, desh, legy, Leomonster |
|           23 |     2044 | 2024-05-15 | Case         | L   | 0.663      | -            | -                | -                | -         |    -2.12 | abr, CutzMeretz, desh, legy, Leomonster |
|           22 |     2047 | 2024-05-15 | Case         | L   | 0.663      | -            | -                | -                | -         |    -2.17 | abr, CutzMeretz, desh, legy, Leomonster |
|           21 |     2096 | 2024-05-14 | RED Canids   | L   | 0.657      | -            | -                | -                | -         |    -0.72 | abr, CutzMeretz, desh, legy, Leomonster |
|           20 |     2101 | 2024-05-14 | RED Canids   | L   | 0.657      | -            | -                | -                | -         |    -0.73 | abr, CutzMeretz, desh, legy, Leomonster |
|           19 |     3110 | 2024-04-04 | Fluxo        | L   | 0.390      | -            | -                | -                | -         |    -0.56 | abr, CutzMeretz, desh, legy, Leomonster |
|           18 |     3116 | 2024-04-04 | Fluxo        | L   | 0.390      | -            | -                | -                | -         |    -0.56 | abr, CutzMeretz, desh, legy, Leomonster |
|           17 |     3286 | 2024-03-27 | 2GAME        | L   | 0.337      | -            | -                | -                | -         |    -3.04 | abr, CutzMeretz, desh, legy, Leomonster |
|           16 |     3290 | 2024-03-27 | 2GAME        | W   | 0.337      | 0.450        | 0.002 (0.000)    | 0.053 (0.008)    | 0 (0.000) |     7.72 | abr, CutzMeretz, desh, legy, Leomonster |
|           15 |     3565 | 2024-03-13 | MIBR Academy | L   | 0.242      | -            | -                | -                | -         |    -3.84 | abr, CutzMeretz, desh, legy, Leomonster |
|           14 |     3620 | 2024-03-11 | RED Canids   | L   | 0.229      | -            | -                | -                | -         |    -0.29 | abr, CutzMeretz, desh, legy, Leomonster |
|           13 |     3672 | 2024-03-09 | Fluxo        | L   | 0.214      | -            | -                | -                | -         |    -0.32 | abr, CutzMeretz, desh, legy, Leomonster |
|           12 |     3721 | 2024-03-07 | Sharks       | L   | 0.201      | -            | -                | -                | -         |    -0.43 | abr, CutzMeretz, desh, legy, Leomonster |
|           11 |     3977 | 2024-02-24 | W7M          | L   | 0.124      | -            | -                | -                | -         |    -0.53 | abr, CutzMeretz, desh, legy, Leomonster |
|           10 |     3984 | 2024-02-24 | W7M          | L   | 0.124      | -            | -                | -                | -         |    -0.53 | abr, CutzMeretz, desh, legy, Leomonster |
|            9 |     4006 | 2024-02-23 | Galorys      | W   | 0.117      | 0.450        | 0.030 (0.002)    | 0.552 (0.029)    | 0 (0.000) |     3.31 | abr, CutzMeretz, desh, legy, Leomonster |
|            8 |     4007 | 2024-02-23 | Galorys      | L   | 0.117      | -            | -                | -                | -         |    -0.37 | abr, CutzMeretz, desh, legy, Leomonster |
|            7 |     4040 | 2024-02-21 | Sharks       | L   | 0.104      | -            | -                | -                | -         |    -0.23 | abr, CutzMeretz, desh, legy, Leomonster |
|            6 |     4149 | 2024-02-17 | Galorys      | L   | 0.075      | -            | -                | -                | -         |    -0.23 | abr, CutzMeretz, desh, legy, Leomonster |
|            5 |     4228 | 2024-02-14 | adalYamigos  | L   | 0.057      | -            | -                | -                | -         |    -0.71 | abr, CutzMeretz, desh, legy, Leomonster |
|            4 |     4235 | 2024-02-14 | adalYamigos  | L   | 0.057      | -            | -                | -                | -         |    -0.71 | abr, CutzMeretz, desh, legy, Leomonster |
|            3 |     4242 | 2024-02-14 | Solid        | L   | 0.056      | -            | -                | -                | -         |    -0.18 | abr, CutzMeretz, desh, legy, Leomonster |
|            2 |     4281 | 2024-02-13 | W7M          | L   | 0.049      | -            | -                | -                | -         |    -0.21 | abr, CutzMeretz, desh, legy, Leomonster |
|            1 |     4292 | 2024-02-12 | W7M          | L   | 0.042      | -            | -                | -                | -         |    -0.18 | abr, CutzMeretz, desh, legy, Leomonster |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($324,557.31)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
