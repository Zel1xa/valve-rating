### Roster Details<br />
Team Name: E-Xolos LAZER<br />
Roster: danoco, land1n, mawth, tatazin, w1<br />
Global Rank: [125](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [33]( ../standings_americas.md)<br />
<br />
Final Rank Value:  799.9<br />
<br />
Final Rank Value (799.9) = Starting Rank Value (776.8) + Head To Head Adjustments (23.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.336[<sup>1</sup>](#table2)
- Bounty Collected: 0.303[<sup>2</sup>](#table1)
- Opponent Network: 0.096[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.184<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 776.8
- 400 + ( ( 0.184 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 776.8


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
|           29 |       54 | 2024-08-03 | undefined        | L   | 1.000      | -            | -                | -                | -         |   -24.90 | danoco, land1n, mawth, tatazin, w1   |
|           28 |      158 | 2024-07-31 | LAG              | W   | 1.000      | 0.477        | 0.012 (0.006)    | 0.347 (0.165)    | 0 (0.000) |    13.26 | danoco, land1n, mawth, tatazin, w1   |
|           27 |      163 | 2024-07-31 | LAG              | W   | 1.000      | 0.477        | 0.012 (0.006)    | 0.347 (0.165)    | 0 (0.000) |    14.46 | danoco, land1n, mawth, tatazin, w1   |
|           26 |      209 | 2024-07-30 | M80              | L   | 1.000      | -            | -                | -                | -         |    -2.11 | danoco, land1n, mawth, tatazin, w1   |
|           25 |      213 | 2024-07-30 | M80              | L   | 1.000      | -            | -                | -                | -         |    -2.16 | danoco, land1n, mawth, tatazin, w1   |
|           24 |      339 | 2024-07-26 | Vibe             | W   | 1.000      | 0.371        | -                | 0.070 (0.026)    | 0 (0.000) |     3.03 | danoco, land1n, mawth, tatazin, w1   |
|           23 |      404 | 2024-07-24 | FLUFFY AIMERS    | W   | 1.000      | 0.477        | 0.003 (0.001)    | 0.310 (0.148)    | 0 (0.000) |    12.62 | danoco, land1n, mawth, tatazin, w1   |
|           22 |      407 | 2024-07-24 | FLUFFY AIMERS    | L   | 1.000      | -            | -                | -                | -         |   -19.16 | danoco, land1n, mawth, tatazin, w1   |
|           21 |      599 | 2024-07-18 | NRG              | L   | 1.000      | -            | -                | -                | -         |    -8.38 | danoco, land1n, mawth, tatazin, w1   |
|           20 |      603 | 2024-07-18 | NRG              | L   | 1.000      | -            | -                | -                | -         |    -8.99 | danoco, land1n, mawth, tatazin, w1   |
|           19 |      725 | 2024-07-16 | Nouns            | W   | 1.000      | 0.477        | 0.057 (0.027)    | 0.553 (0.264)    | 0 (0.000) |    23.06 | danoco, land1n, mawth, tatazin, w1   |
|           18 |      731 | 2024-07-16 | Nouns            | L   | 1.000      | -            | -                | -                | -         |    -7.95 | danoco, land1n, mawth, tatazin, w1   |
|           17 |     1012 | 2024-06-16 | Akimbo           | W   | 0.868      | 0.143        | 0.015 (0.002)    | 0.270 (0.033)    | 0 (0.000) |    12.77 | land1n, mawth, RenanZin, tatazin, w1 |
|           16 |     1040 | 2024-06-15 | Homyno           | W   | 0.862      | 0.143        | 0.007 (0.001)    | -                | 0 (0.000) |     9.11 | land1n, mawth, RenanZin, tatazin, w1 |
|           15 |     1075 | 2024-06-14 | Take Flyte       | L   | 0.855      | -            | -                | -                | -         |   -18.17 | land1n, mawth, RenanZin, tatazin, w1 |
|           14 |     1126 | 2024-06-13 | Limitless        | W   | 0.846      | 0.371        | 0.005 (0.002)    | 0.131 (0.041)    | 0 (0.000) |    11.88 | land1n, mawth, RenanZin, tatazin, w1 |
|           13 |     1149 | 2024-06-12 | Homyno           | W   | 0.842      | -            | -                | -                | 0 (0.000) |     9.34 | land1n, mawth, RenanZin, tatazin, w1 |
|           12 |     1150 | 2024-06-12 | Limitless        | W   | 0.841      | -            | -                | -                | 0 (0.000) |     7.28 | land1n, mawth, RenanZin, tatazin, w1 |
|           11 |     1201 | 2024-06-10 | Homyno           | W   | 0.826      | 0.371        | 0.007 (0.002)    | 0.156 (0.048)    | -         |    10.33 | land1n, mawth, RenanZin, tatazin, w1 |
|           10 |     1225 | 2024-06-09 | Akimbo           | L   | 0.822      | -            | -                | -                | -         |   -12.55 | land1n, mawth, RenanZin, tatazin, w1 |
|            9 |     1287 | 2024-06-08 | straykids        | W   | 0.815      | 0.368        | 0.005 (0.002)    | -                | -         |     9.04 | land1n, mawth, RenanZin, tatazin, w1 |
|            8 |     1296 | 2024-06-08 | Akimbo           | W   | 0.814      | 0.371        | -                | 0.073 (0.022)    | -         |     9.16 | land1n, mawth, RenanZin, tatazin, w1 |
|            7 |     1343 | 2024-06-07 | Homyno           | W   | 0.809      | 0.368        | 0.007 (0.002)    | 0.156 (0.047)    | -         |    11.37 | land1n, mawth, RenanZin, tatazin, w1 |
|            6 |     1405 | 2024-06-06 | Final Form       | L   | 0.801      | -            | -                | -                | -         |   -19.39 | land1n, mawth, RenanZin, tatazin, w1 |
|            5 |     1421 | 2024-06-06 | Party Astronauts | L   | 0.800      | -            | -                | -                | -         |    -6.81 | land1n, mawth, RenanZin, tatazin, w1 |
|            4 |     1522 | 2024-06-04 | Legacy           | L   | 0.789      | -            | -                | -                | -         |    -5.49 | land1n, mawth, RenanZin, tatazin, w1 |
|            3 |     1563 | 2024-06-03 | Perseverance     | W   | 0.781      | -            | -                | -                | -         |     4.79 | land1n, mawth, RenanZin, tatazin, w1 |
|            2 |     1931 | 2024-05-20 | M80              | L   | 0.687      | -            | -                | -                | -         |    -1.47 | land1n, mawth, RenanZin, tatazin, w1 |
|            1 |     4224 | 2024-02-16 | Mythic           | L   | 0.061      | -            | -                | -                | -         |    -0.92 | land1n, mawth, RenanZin, tatazin, w1 |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,385.88)
- Divide that value by the 5th highest value among all rosters ($321,880.58)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.869 | $750.00        | $651.46         |
| 2024-06-10 |      0.829 | $3,300.00      | $2,734.42       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
