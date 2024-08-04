### Roster Details<br />
Team Name: Corinthians<br />
Roster: abr, CutzMeretz, desh, legy, Leomonster<br />
Global Rank: [201](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [57]( ../standings_americas.md)<br />
<br />
Final Rank Value:  511.5<br />
<br />
Final Rank Value (511.5) = Starting Rank Value (511.2) + Head To Head Adjustments (0.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.212[<sup>2</sup>](#table1)
- Opponent Network: 0.006[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.054<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 511.2
- 400 + ( ( 0.054 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 511.2


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
|           26 |     1662 | 2024-05-29 | 9z Academy   | W   | 0.754      | 0.371        | 0.000 (0.000)    | 0.070 (0.019)    | 0 (0.000) |    11.80 | abr, CutzMeretz, desh, legy, Leomonster |
|           25 |     1677 | 2024-05-28 | Hype         | L   | 0.748      | -            | -                | -                | -         |    -2.56 | abr, CutzMeretz, desh, legy, Leomonster |
|           24 |     1878 | 2024-05-20 | BESTIA       | L   | 0.696      | -            | -                | -                | -         |    -1.33 | abr, CutzMeretz, desh, legy, Leomonster |
|           23 |     2052 | 2024-05-15 | Case         | L   | 0.662      | -            | -                | -                | -         |    -2.12 | abr, CutzMeretz, desh, legy, Leomonster |
|           22 |     2055 | 2024-05-15 | Case         | L   | 0.662      | -            | -                | -                | -         |    -2.17 | abr, CutzMeretz, desh, legy, Leomonster |
|           21 |     2104 | 2024-05-14 | RED Canids   | L   | 0.656      | -            | -                | -                | -         |    -0.72 | abr, CutzMeretz, desh, legy, Leomonster |
|           20 |     2109 | 2024-05-14 | RED Canids   | L   | 0.656      | -            | -                | -                | -         |    -0.73 | abr, CutzMeretz, desh, legy, Leomonster |
|           19 |     3118 | 2024-04-04 | Fluxo        | L   | 0.390      | -            | -                | -                | -         |    -0.56 | abr, CutzMeretz, desh, legy, Leomonster |
|           18 |     3124 | 2024-04-04 | Fluxo        | L   | 0.389      | -            | -                | -                | -         |    -0.56 | abr, CutzMeretz, desh, legy, Leomonster |
|           17 |     3294 | 2024-03-27 | 2GAME        | L   | 0.337      | -            | -                | -                | -         |    -3.03 | abr, CutzMeretz, desh, legy, Leomonster |
|           16 |     3298 | 2024-03-27 | 2GAME        | W   | 0.336      | 0.450        | 0.002 (0.000)    | 0.053 (0.008)    | 0 (0.000) |     7.70 | abr, CutzMeretz, desh, legy, Leomonster |
|           15 |     3573 | 2024-03-13 | MIBR Academy | L   | 0.242      | -            | -                | -                | -         |    -3.83 | abr, CutzMeretz, desh, legy, Leomonster |
|           14 |     3628 | 2024-03-11 | RED Canids   | L   | 0.228      | -            | -                | -                | -         |    -0.29 | abr, CutzMeretz, desh, legy, Leomonster |
|           13 |     3680 | 2024-03-09 | Fluxo        | L   | 0.214      | -            | -                | -                | -         |    -0.31 | abr, CutzMeretz, desh, legy, Leomonster |
|           12 |     3729 | 2024-03-07 | Sharks       | L   | 0.200      | -            | -                | -                | -         |    -0.43 | abr, CutzMeretz, desh, legy, Leomonster |
|           11 |     3985 | 2024-02-24 | W7M          | L   | 0.123      | -            | -                | -                | -         |    -0.52 | abr, CutzMeretz, desh, legy, Leomonster |
|           10 |     3992 | 2024-02-24 | W7M          | L   | 0.123      | -            | -                | -                | -         |    -0.52 | abr, CutzMeretz, desh, legy, Leomonster |
|            9 |     4014 | 2024-02-23 | Galorys      | W   | 0.116      | 0.450        | 0.030 (0.002)    | 0.552 (0.029)    | 0 (0.000) |     3.29 | abr, CutzMeretz, desh, legy, Leomonster |
|            8 |     4015 | 2024-02-23 | Galorys      | L   | 0.116      | -            | -                | -                | -         |    -0.37 | abr, CutzMeretz, desh, legy, Leomonster |
|            7 |     4048 | 2024-02-21 | Sharks       | L   | 0.103      | -            | -                | -                | -         |    -0.23 | abr, CutzMeretz, desh, legy, Leomonster |
|            6 |     4157 | 2024-02-17 | Galorys      | L   | 0.075      | -            | -                | -                | -         |    -0.23 | abr, CutzMeretz, desh, legy, Leomonster |
|            5 |     4236 | 2024-02-14 | adalYamigos  | L   | 0.057      | -            | -                | -                | -         |    -0.71 | abr, CutzMeretz, desh, legy, Leomonster |
|            4 |     4243 | 2024-02-14 | adalYamigos  | L   | 0.056      | -            | -                | -                | -         |    -0.70 | abr, CutzMeretz, desh, legy, Leomonster |
|            3 |     4250 | 2024-02-14 | Solid        | L   | 0.055      | -            | -                | -                | -         |    -0.18 | abr, CutzMeretz, desh, legy, Leomonster |
|            2 |     4289 | 2024-02-13 | W7M          | L   | 0.048      | -            | -                | -                | -         |    -0.20 | abr, CutzMeretz, desh, legy, Leomonster |
|            1 |     4300 | 2024-02-12 | W7M          | L   | 0.042      | -            | -                | -                | -         |    -0.18 | abr, CutzMeretz, desh, legy, Leomonster |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($324,344.55)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
