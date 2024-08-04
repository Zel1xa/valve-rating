### Roster Details<br />
Team Name: Corinthians<br />
Roster: abr, CutzMeretz, desh, legy, Leomonster<br />
Global Rank: [203](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [57]( ../standings_americas.md)<br />
<br />
Final Rank Value:  511.7<br />
<br />
Final Rank Value (511.7) = Starting Rank Value (511.5) + Head To Head Adjustments (0.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.212[<sup>2</sup>](#table1)
- Opponent Network: 0.006[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.055<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 511.5
- 400 + ( ( 0.055 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 511.5


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
|           26 |     1650 | 2024-05-29 | 9z Academy   | W   | 0.758      | 0.371        | 0.000 (0.000)    | 0.069 (0.019)    | 0 (0.000) |    11.85 | abr, CutzMeretz, desh, legy, Leomonster |
|           25 |     1665 | 2024-05-28 | Hype         | L   | 0.752      | -            | -                | -                | -         |    -2.57 | abr, CutzMeretz, desh, legy, Leomonster |
|           24 |     1866 | 2024-05-20 | BESTIA       | L   | 0.700      | -            | -                | -                | -         |    -1.34 | abr, CutzMeretz, desh, legy, Leomonster |
|           23 |     2040 | 2024-05-15 | Case         | L   | 0.666      | -            | -                | -                | -         |    -2.14 | abr, CutzMeretz, desh, legy, Leomonster |
|           22 |     2043 | 2024-05-15 | Case         | L   | 0.666      | -            | -                | -                | -         |    -2.18 | abr, CutzMeretz, desh, legy, Leomonster |
|           21 |     2092 | 2024-05-14 | RED Canids   | L   | 0.660      | -            | -                | -                | -         |    -0.72 | abr, CutzMeretz, desh, legy, Leomonster |
|           20 |     2097 | 2024-05-14 | RED Canids   | L   | 0.660      | -            | -                | -                | -         |    -0.73 | abr, CutzMeretz, desh, legy, Leomonster |
|           19 |     3105 | 2024-04-04 | Fluxo        | L   | 0.393      | -            | -                | -                | -         |    -0.56 | abr, CutzMeretz, desh, legy, Leomonster |
|           18 |     3111 | 2024-04-04 | Fluxo        | L   | 0.393      | -            | -                | -                | -         |    -0.57 | abr, CutzMeretz, desh, legy, Leomonster |
|           17 |     3281 | 2024-03-27 | 2GAME        | L   | 0.340      | -            | -                | -                | -         |    -3.06 | abr, CutzMeretz, desh, legy, Leomonster |
|           16 |     3285 | 2024-03-27 | 2GAME        | W   | 0.340      | 0.450        | 0.002 (0.000)    | 0.053 (0.008)    | 0 (0.000) |     7.79 | abr, CutzMeretz, desh, legy, Leomonster |
|           15 |     3560 | 2024-03-13 | MIBR Academy | L   | 0.245      | -            | -                | -                | -         |    -3.89 | abr, CutzMeretz, desh, legy, Leomonster |
|           14 |     3614 | 2024-03-11 | RED Canids   | L   | 0.232      | -            | -                | -                | -         |    -0.29 | abr, CutzMeretz, desh, legy, Leomonster |
|           13 |     3666 | 2024-03-09 | Fluxo        | L   | 0.217      | -            | -                | -                | -         |    -0.32 | abr, CutzMeretz, desh, legy, Leomonster |
|           12 |     3715 | 2024-03-07 | Sharks       | L   | 0.204      | -            | -                | -                | -         |    -0.43 | abr, CutzMeretz, desh, legy, Leomonster |
|           11 |     3971 | 2024-02-24 | W7M          | L   | 0.127      | -            | -                | -                | -         |    -0.54 | abr, CutzMeretz, desh, legy, Leomonster |
|           10 |     3978 | 2024-02-24 | W7M          | L   | 0.127      | -            | -                | -                | -         |    -0.54 | abr, CutzMeretz, desh, legy, Leomonster |
|            9 |     4000 | 2024-02-23 | Galorys      | W   | 0.120      | 0.450        | 0.030 (0.002)    | 0.552 (0.030)    | 0 (0.000) |     3.40 | abr, CutzMeretz, desh, legy, Leomonster |
|            8 |     4001 | 2024-02-23 | Galorys      | L   | 0.120      | -            | -                | -                | -         |    -0.38 | abr, CutzMeretz, desh, legy, Leomonster |
|            7 |     4034 | 2024-02-21 | Sharks       | L   | 0.107      | -            | -                | -                | -         |    -0.23 | abr, CutzMeretz, desh, legy, Leomonster |
|            6 |     4142 | 2024-02-17 | Galorys      | L   | 0.078      | -            | -                | -                | -         |    -0.24 | abr, CutzMeretz, desh, legy, Leomonster |
|            5 |     4221 | 2024-02-14 | adalYamigos  | L   | 0.060      | -            | -                | -                | -         |    -0.75 | abr, CutzMeretz, desh, legy, Leomonster |
|            4 |     4228 | 2024-02-14 | adalYamigos  | L   | 0.060      | -            | -                | -                | -         |    -0.75 | abr, CutzMeretz, desh, legy, Leomonster |
|            3 |     4235 | 2024-02-14 | Solid        | L   | 0.059      | -            | -                | -                | -         |    -0.19 | abr, CutzMeretz, desh, legy, Leomonster |
|            2 |     4274 | 2024-02-13 | W7M          | L   | 0.052      | -            | -                | -                | -         |    -0.22 | abr, CutzMeretz, desh, legy, Leomonster |
|            1 |     4285 | 2024-02-12 | W7M          | L   | 0.045      | -            | -                | -                | -         |    -0.19 | abr, CutzMeretz, desh, legy, Leomonster |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($325,463.29)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
