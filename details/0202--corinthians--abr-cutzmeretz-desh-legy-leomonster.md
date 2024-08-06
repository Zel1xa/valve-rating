### Roster Details<br />
Team Name: Corinthians<br />
Roster: abr, CutzMeretz, desh, legy, Leomonster<br />
Global Rank: [202](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [58]( ../standings_americas.md)<br />
<br />
Final Rank Value:  511.1<br />
<br />
Final Rank Value (511.1) = Starting Rank Value (510.5) + Head To Head Adjustments (0.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.210[<sup>2</sup>](#table1)
- Opponent Network: 0.005[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.054<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 510.5
- 400 + ( ( 0.054 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 510.5


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
|           26 |     1724 | 2024-05-29 | 9z Academy   | W   | 0.741      | 0.371        | 0.000 (0.000)    | 0.067 (0.018)    | 0 (0.000) |    11.63 | abr, CutzMeretz, desh, legy, Leomonster |
|           25 |     1739 | 2024-05-28 | Hype         | L   | 0.735      | -            | -                | -                | -         |    -2.52 | abr, CutzMeretz, desh, legy, Leomonster |
|           24 |     1940 | 2024-05-20 | BESTIA       | L   | 0.683      | -            | -                | -                | -         |    -1.32 | abr, CutzMeretz, desh, legy, Leomonster |
|           23 |     2114 | 2024-05-15 | Case         | L   | 0.649      | -            | -                | -                | -         |    -2.09 | abr, CutzMeretz, desh, legy, Leomonster |
|           22 |     2117 | 2024-05-15 | Case         | L   | 0.649      | -            | -                | -                | -         |    -2.14 | abr, CutzMeretz, desh, legy, Leomonster |
|           21 |     2166 | 2024-05-14 | RED Canids   | L   | 0.643      | -            | -                | -                | -         |    -0.72 | abr, CutzMeretz, desh, legy, Leomonster |
|           20 |     2171 | 2024-05-14 | RED Canids   | L   | 0.643      | -            | -                | -                | -         |    -0.73 | abr, CutzMeretz, desh, legy, Leomonster |
|           19 |     3180 | 2024-04-04 | Fluxo        | L   | 0.376      | -            | -                | -                | -         |    -0.55 | abr, CutzMeretz, desh, legy, Leomonster |
|           18 |     3186 | 2024-04-04 | Fluxo        | L   | 0.376      | -            | -                | -                | -         |    -0.55 | abr, CutzMeretz, desh, legy, Leomonster |
|           17 |     3356 | 2024-03-27 | 2GAME        | L   | 0.323      | -            | -                | -                | -         |    -2.92 | abr, CutzMeretz, desh, legy, Leomonster |
|           16 |     3360 | 2024-03-27 | 2GAME        | W   | 0.323      | 0.450        | 0.002 (0.000)    | 0.049 (0.007)    | 0 (0.000) |     7.39 | abr, CutzMeretz, desh, legy, Leomonster |
|           15 |     3635 | 2024-03-13 | MIBR Academy | L   | 0.228      | -            | -                | -                | -         |    -3.62 | abr, CutzMeretz, desh, legy, Leomonster |
|           14 |     3690 | 2024-03-11 | RED Canids   | L   | 0.215      | -            | -                | -                | -         |    -0.28 | abr, CutzMeretz, desh, legy, Leomonster |
|           13 |     3742 | 2024-03-09 | Fluxo        | L   | 0.200      | -            | -                | -                | -         |    -0.30 | abr, CutzMeretz, desh, legy, Leomonster |
|           12 |     3791 | 2024-03-07 | Sharks       | L   | 0.187      | -            | -                | -                | -         |    -0.41 | abr, CutzMeretz, desh, legy, Leomonster |
|           11 |     4047 | 2024-02-24 | W7M          | L   | 0.110      | -            | -                | -                | -         |    -0.47 | abr, CutzMeretz, desh, legy, Leomonster |
|           10 |     4054 | 2024-02-24 | W7M          | L   | 0.110      | -            | -                | -                | -         |    -0.47 | abr, CutzMeretz, desh, legy, Leomonster |
|            9 |     4076 | 2024-02-23 | Galorys      | W   | 0.103      | 0.450        | 0.030 (0.001)    | 0.530 (0.025)    | 0 (0.000) |     2.92 | abr, CutzMeretz, desh, legy, Leomonster |
|            8 |     4077 | 2024-02-23 | Galorys      | L   | 0.103      | -            | -                | -                | -         |    -0.33 | abr, CutzMeretz, desh, legy, Leomonster |
|            7 |     4110 | 2024-02-21 | Sharks       | L   | 0.090      | -            | -                | -                | -         |    -0.20 | abr, CutzMeretz, desh, legy, Leomonster |
|            6 |     4219 | 2024-02-17 | Galorys      | L   | 0.061      | -            | -                | -                | -         |    -0.19 | abr, CutzMeretz, desh, legy, Leomonster |
|            5 |     4298 | 2024-02-14 | adalYamigos  | L   | 0.043      | -            | -                | -                | -         |    -0.55 | abr, CutzMeretz, desh, legy, Leomonster |
|            4 |     4305 | 2024-02-14 | adalYamigos  | L   | 0.043      | -            | -                | -                | -         |    -0.55 | abr, CutzMeretz, desh, legy, Leomonster |
|            3 |     4312 | 2024-02-14 | Solid        | L   | 0.042      | -            | -                | -                | -         |    -0.13 | abr, CutzMeretz, desh, legy, Leomonster |
|            2 |     4351 | 2024-02-13 | W7M          | L   | 0.035      | -            | -                | -                | -         |    -0.15 | abr, CutzMeretz, desh, legy, Leomonster |
|            1 |     4362 | 2024-02-12 | W7M          | L   | 0.028      | -            | -                | -                | -         |    -0.12 | abr, CutzMeretz, desh, legy, Leomonster |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($320,411.81)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
