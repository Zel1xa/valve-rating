### Roster Details<br />
Team Name: E-Xolos LAZER<br />
Roster: danoco, land1n, mawth, tatazin, w1<br />
Global Rank: [125](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [33]( ../standings_americas.md)<br />
<br />
Final Rank Value:  800.6<br />
<br />
Final Rank Value (800.6) = Starting Rank Value (778.8) + Head To Head Adjustments (21.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.336[<sup>1</sup>](#table2)
- Bounty Collected: 0.303[<sup>2</sup>](#table1)
- Opponent Network: 0.099[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.185<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 778.8
- 400 + ( ( 0.185 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 778.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent         | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                               |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           29 |       60 | 2024-08-03 | undefined        | L   | 1.000      | -            | -                | -                | -         |   -24.92 | danoco, land1n, mawth, tatazin, w1   |
|           28 |      164 | 2024-07-31 | LAG              | W   | 1.000      | 0.477        | 0.012 (0.006)    | 0.385 (0.183)    | 0 (0.000) |    13.23 | danoco, land1n, mawth, tatazin, w1   |
|           27 |      169 | 2024-07-31 | LAG              | W   | 1.000      | 0.477        | 0.012 (0.006)    | 0.385 (0.183)    | 0 (0.000) |    14.43 | danoco, land1n, mawth, tatazin, w1   |
|           26 |      215 | 2024-07-30 | M80              | L   | 1.000      | -            | -                | -                | -         |    -2.13 | danoco, land1n, mawth, tatazin, w1   |
|           25 |      219 | 2024-07-30 | M80              | L   | 1.000      | -            | -                | -                | -         |    -2.18 | danoco, land1n, mawth, tatazin, w1   |
|           24 |      345 | 2024-07-26 | Vibe             | W   | 1.000      | 0.371        | -                | 0.070 (0.026)    | 0 (0.000) |     3.03 | danoco, land1n, mawth, tatazin, w1   |
|           23 |      410 | 2024-07-24 | FLUFFY AIMERS    | W   | 1.000      | 0.477        | 0.003 (0.001)    | 0.311 (0.148)    | 0 (0.000) |    12.59 | danoco, land1n, mawth, tatazin, w1   |
|           22 |      413 | 2024-07-24 | FLUFFY AIMERS    | L   | 1.000      | -            | -                | -                | -         |   -19.19 | danoco, land1n, mawth, tatazin, w1   |
|           21 |      605 | 2024-07-18 | NRG              | L   | 1.000      | -            | -                | -                | -         |    -8.42 | danoco, land1n, mawth, tatazin, w1   |
|           20 |      609 | 2024-07-18 | NRG              | L   | 1.000      | -            | -                | -                | -         |    -9.04 | danoco, land1n, mawth, tatazin, w1   |
|           19 |      731 | 2024-07-16 | Nouns            | W   | 1.000      | 0.477        | 0.057 (0.027)    | 0.553 (0.264)    | 0 (0.000) |    23.01 | danoco, land1n, mawth, tatazin, w1   |
|           18 |      737 | 2024-07-16 | Nouns            | L   | 1.000      | -            | -                | -                | -         |    -8.00 | danoco, land1n, mawth, tatazin, w1   |
|           17 |     1018 | 2024-06-16 | Akimbo           | W   | 0.864      | 0.143        | 0.015 (0.002)    | 0.269 (0.033)    | 0 (0.000) |    12.66 | land1n, mawth, RenanZin, tatazin, w1 |
|           16 |     1046 | 2024-06-15 | Homyno           | W   | 0.858      | 0.143        | 0.007 (0.001)    | -                | 0 (0.000) |     9.03 | land1n, mawth, RenanZin, tatazin, w1 |
|           15 |     1081 | 2024-06-14 | Take Flyte       | L   | 0.851      | -            | -                | -                | -         |   -18.10 | land1n, mawth, RenanZin, tatazin, w1 |
|           14 |     1132 | 2024-06-13 | Limitless        | W   | 0.842      | 0.371        | 0.005 (0.002)    | 0.131 (0.041)    | 0 (0.000) |    11.78 | land1n, mawth, RenanZin, tatazin, w1 |
|           13 |     1155 | 2024-06-12 | Homyno           | W   | 0.838      | -            | -                | -                | 0 (0.000) |     9.25 | land1n, mawth, RenanZin, tatazin, w1 |
|           12 |     1156 | 2024-06-12 | Limitless        | W   | 0.837      | -            | -                | -                | 0 (0.000) |     7.21 | land1n, mawth, RenanZin, tatazin, w1 |
|           11 |     1207 | 2024-06-10 | Homyno           | W   | 0.822      | 0.371        | 0.007 (0.002)    | 0.156 (0.048)    | -         |    10.22 | land1n, mawth, RenanZin, tatazin, w1 |
|           10 |     1231 | 2024-06-09 | Akimbo           | L   | 0.818      | -            | -                | -                | -         |   -12.56 | land1n, mawth, RenanZin, tatazin, w1 |
|            9 |     1293 | 2024-06-08 | straykids        | W   | 0.811      | 0.368        | 0.005 (0.002)    | -                | -         |     8.94 | land1n, mawth, RenanZin, tatazin, w1 |
|            8 |     1302 | 2024-06-08 | Akimbo           | W   | 0.810      | 0.371        | -                | 0.073 (0.022)    | -         |     9.05 | land1n, mawth, RenanZin, tatazin, w1 |
|            7 |     1349 | 2024-06-07 | Homyno           | W   | 0.804      | 0.368        | 0.007 (0.002)    | 0.156 (0.046)    | -         |    11.24 | land1n, mawth, RenanZin, tatazin, w1 |
|            6 |     1411 | 2024-06-06 | Final Form       | L   | 0.797      | -            | -                | -                | -         |   -19.34 | land1n, mawth, RenanZin, tatazin, w1 |
|            5 |     1427 | 2024-06-06 | Party Astronauts | L   | 0.796      | -            | -                | -                | -         |    -6.84 | land1n, mawth, RenanZin, tatazin, w1 |
|            4 |     1528 | 2024-06-04 | Legacy           | L   | 0.784      | -            | -                | -                | -         |    -5.53 | land1n, mawth, RenanZin, tatazin, w1 |
|            3 |     1569 | 2024-06-03 | Perseverance     | W   | 0.777      | -            | -                | -                | -         |     4.72 | land1n, mawth, RenanZin, tatazin, w1 |
|            2 |     1937 | 2024-05-20 | M80              | L   | 0.683      | -            | -                | -                | -         |    -1.49 | land1n, mawth, RenanZin, tatazin, w1 |
|            1 |     4230 | 2024-02-16 | Mythic           | L   | 0.057      | -            | -                | -                | -         |    -0.86 | land1n, mawth, RenanZin, tatazin, w1 |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,368.44)
- Divide that value by the 5th highest value among all rosters ($320,603.98)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.864 | $750.00        | $648.23         |
| 2024-06-10 |      0.824 | $3,300.00      | $2,720.21       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
