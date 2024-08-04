### Roster Details<br />
Team Name: Corinthians<br />
Roster: abr, CutzMeretz, desh, legy, Leomonster<br />
Global Rank: [203](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [58]( ../standings_americas.md)<br />
<br />
Final Rank Value:  511.5<br />
<br />
Final Rank Value (511.5) = Starting Rank Value (511.1) + Head To Head Adjustments (0.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.212[<sup>2</sup>](#table1)
- Opponent Network: 0.006[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.054<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 511.1
- 400 + ( ( 0.054 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 511.1


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
|           26 |     1686 | 2024-05-29 | 9z Academy   | W   | 0.753      | 0.371        | 0.000 (0.000)    | 0.070 (0.019)    | 0 (0.000) |    11.79 | abr, CutzMeretz, desh, legy, Leomonster |
|           25 |     1701 | 2024-05-28 | Hype         | L   | 0.747      | -            | -                | -                | -         |    -2.55 | abr, CutzMeretz, desh, legy, Leomonster |
|           24 |     1902 | 2024-05-20 | BESTIA       | L   | 0.695      | -            | -                | -                | -         |    -1.33 | abr, CutzMeretz, desh, legy, Leomonster |
|           23 |     2076 | 2024-05-15 | Case         | L   | 0.661      | -            | -                | -                | -         |    -2.12 | abr, CutzMeretz, desh, legy, Leomonster |
|           22 |     2079 | 2024-05-15 | Case         | L   | 0.661      | -            | -                | -                | -         |    -2.16 | abr, CutzMeretz, desh, legy, Leomonster |
|           21 |     2128 | 2024-05-14 | RED Canids   | L   | 0.655      | -            | -                | -                | -         |    -0.72 | abr, CutzMeretz, desh, legy, Leomonster |
|           20 |     2133 | 2024-05-14 | RED Canids   | L   | 0.655      | -            | -                | -                | -         |    -0.73 | abr, CutzMeretz, desh, legy, Leomonster |
|           19 |     3142 | 2024-04-04 | Fluxo        | L   | 0.388      | -            | -                | -                | -         |    -0.56 | abr, CutzMeretz, desh, legy, Leomonster |
|           18 |     3148 | 2024-04-04 | Fluxo        | L   | 0.388      | -            | -                | -                | -         |    -0.56 | abr, CutzMeretz, desh, legy, Leomonster |
|           17 |     3318 | 2024-03-27 | 2GAME        | L   | 0.335      | -            | -                | -                | -         |    -3.02 | abr, CutzMeretz, desh, legy, Leomonster |
|           16 |     3322 | 2024-03-27 | 2GAME        | W   | 0.335      | 0.450        | 0.002 (0.000)    | 0.052 (0.008)    | 0 (0.000) |     7.68 | abr, CutzMeretz, desh, legy, Leomonster |
|           15 |     3597 | 2024-03-13 | MIBR Academy | L   | 0.241      | -            | -                | -                | -         |    -3.81 | abr, CutzMeretz, desh, legy, Leomonster |
|           14 |     3652 | 2024-03-11 | RED Canids   | L   | 0.227      | -            | -                | -                | -         |    -0.29 | abr, CutzMeretz, desh, legy, Leomonster |
|           13 |     3704 | 2024-03-09 | Fluxo        | L   | 0.213      | -            | -                | -                | -         |    -0.31 | abr, CutzMeretz, desh, legy, Leomonster |
|           12 |     3753 | 2024-03-07 | Sharks       | L   | 0.199      | -            | -                | -                | -         |    -0.42 | abr, CutzMeretz, desh, legy, Leomonster |
|           11 |     4009 | 2024-02-24 | W7M          | L   | 0.122      | -            | -                | -                | -         |    -0.52 | abr, CutzMeretz, desh, legy, Leomonster |
|           10 |     4016 | 2024-02-24 | W7M          | L   | 0.122      | -            | -                | -                | -         |    -0.52 | abr, CutzMeretz, desh, legy, Leomonster |
|            9 |     4038 | 2024-02-23 | Galorys      | W   | 0.115      | 0.450        | 0.030 (0.002)    | 0.552 (0.029)    | 0 (0.000) |     3.27 | abr, CutzMeretz, desh, legy, Leomonster |
|            8 |     4039 | 2024-02-23 | Galorys      | L   | 0.115      | -            | -                | -                | -         |    -0.37 | abr, CutzMeretz, desh, legy, Leomonster |
|            7 |     4072 | 2024-02-21 | Sharks       | L   | 0.102      | -            | -                | -                | -         |    -0.22 | abr, CutzMeretz, desh, legy, Leomonster |
|            6 |     4181 | 2024-02-17 | Galorys      | L   | 0.073      | -            | -                | -                | -         |    -0.23 | abr, CutzMeretz, desh, legy, Leomonster |
|            5 |     4260 | 2024-02-14 | adalYamigos  | L   | 0.056      | -            | -                | -                | -         |    -0.69 | abr, CutzMeretz, desh, legy, Leomonster |
|            4 |     4267 | 2024-02-14 | adalYamigos  | L   | 0.055      | -            | -                | -                | -         |    -0.69 | abr, CutzMeretz, desh, legy, Leomonster |
|            3 |     4274 | 2024-02-14 | Solid        | L   | 0.054      | -            | -                | -                | -         |    -0.17 | abr, CutzMeretz, desh, legy, Leomonster |
|            2 |     4313 | 2024-02-13 | W7M          | L   | 0.047      | -            | -                | -                | -         |    -0.20 | abr, CutzMeretz, desh, legy, Leomonster |
|            1 |     4324 | 2024-02-12 | W7M          | L   | 0.040      | -            | -                | -                | -         |    -0.17 | abr, CutzMeretz, desh, legy, Leomonster |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($324,028.83)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
