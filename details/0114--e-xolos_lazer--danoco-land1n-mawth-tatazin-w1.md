### Roster Details<br />
Team Name: E-Xolos LAZER<br />
Roster: danoco, land1n, mawth, tatazin, w1<br />
Global Rank: [114](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [28]( ../standings_americas.md)<br />
<br />
Final Rank Value:  788.0<br />
<br />
Final Rank Value (788.0) = Starting Rank Value (767.8) + Head To Head Adjustments (20.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.324[<sup>1</sup>](#table2)
- Bounty Collected: 0.301[<sup>2</sup>](#table1)
- Opponent Network: 0.135[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.190<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 767.8
- 400 + ( ( 0.190 - 0.000 ) / ( 0.826 - 0.000 ) ) * 1600 = 767.8


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
|           41 |      133 | 2024-09-03 | Mythic           | W   | 1.000      | 0.477        | 0.007 (0.004)    | 0.276 (0.132)    | 0 (0.000) |    12.23 | danoco, land1n, mawth, tatazin, w1   |
|           40 |      135 | 2024-09-03 | Mythic           | W   | 1.000      | 0.477        | 0.007 (0.004)    | 0.276 (0.132)    | 0 (0.000) |    13.32 | danoco, land1n, mawth, tatazin, w1   |
|           39 |      306 | 2024-08-28 | FLUFFY AIMERS    | L   | 1.000      | -            | -                | -                | -         |   -16.68 | danoco, land1n, mawth, tatazin, w1   |
|           38 |      362 | 2024-08-27 | Mythic           | W   | 1.000      | 0.143        | 0.007 (0.001)    | 0.276 (0.039)    | 0 (0.000) |    13.77 | danoco, land1n, mawth, tatazin, w1   |
|           37 |      418 | 2024-08-26 | Wildcard         | L   | 1.000      | -            | -                | -                | -         |    -3.77 | danoco, land1n, mawth, tatazin, w1   |
|           36 |      423 | 2024-08-26 | Homyno           | W   | 1.000      | -            | -                | -                | 0 (0.000) |     8.94 | danoco, land1n, mawth, tatazin, w1   |
|           35 |      604 | 2024-08-21 | BOSS             | W   | 1.000      | 0.477        | 0.013 (0.006)    | 0.401 (0.191)    | 0 (0.000) |    16.25 | danoco, land1n, mawth, tatazin, w1   |
|           34 |      606 | 2024-08-21 | BOSS             | L   | 1.000      | -            | -                | -                | -         |   -15.21 | danoco, land1n, mawth, tatazin, w1   |
|           33 |      756 | 2024-08-17 | Party Astronauts | L   | 1.000      | -            | -                | -                | -         |    -9.69 | danoco, land1n, mawth, tatazin, w1   |
|           32 |      804 | 2024-08-15 | Party Astronauts | L   | 1.000      | -            | -                | -                | -         |   -10.14 | danoco, land1n, mawth, tatazin, w1   |
|           31 |      855 | 2024-08-13 | timbermen        | L   | 1.000      | -            | -                | -                | -         |   -10.81 | danoco, land1n, mawth, tatazin, w1   |
|           30 |      966 | 2024-08-10 | NoVum            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.35 | danoco, land1n, mawth, tatazin, w1   |
|           29 |     1045 | 2024-08-07 | Revenge Nation   | W   | 0.990      | 0.371        | -                | 0.149 (0.055)    | 0 (0.000) |    11.73 | danoco, land1n, mawth, tatazin, w1   |
|           28 |     1192 | 2024-08-03 | undefined        | L   | 0.963      | -            | -                | -                | -         |   -18.94 | danoco, land1n, mawth, tatazin, w1   |
|           27 |     1296 | 2024-07-31 | LAG              | W   | 0.944      | 0.477        | 0.007 (0.003)    | 0.371 (0.167)    | 0 (0.000) |    12.06 | danoco, land1n, mawth, tatazin, w1   |
|           26 |     1301 | 2024-07-31 | LAG              | W   | 0.943      | 0.477        | 0.007 (0.003)    | 0.371 (0.167)    | 0 (0.000) |    13.08 | danoco, land1n, mawth, tatazin, w1   |
|           25 |     1347 | 2024-07-30 | M80              | L   | 0.937      | -            | -                | -                | -         |    -3.04 | danoco, land1n, mawth, tatazin, w1   |
|           24 |     1351 | 2024-07-30 | M80              | L   | 0.937      | -            | -                | -                | -         |    -3.13 | danoco, land1n, mawth, tatazin, w1   |
|           23 |     1477 | 2024-07-26 | Vibe             | W   | 0.909      | -            | -                | -                | 0 (0.000) |     2.98 | danoco, land1n, mawth, tatazin, w1   |
|           22 |     1542 | 2024-07-24 | FLUFFY AIMERS    | W   | 0.897      | 0.477        | 0.006 (0.003)    | 0.540 (0.231)    | -         |    12.56 | danoco, land1n, mawth, tatazin, w1   |
|           21 |     1546 | 2024-07-24 | FLUFFY AIMERS    | L   | 0.897      | -            | -                | -                | -         |   -15.94 | danoco, land1n, mawth, tatazin, w1   |
|           20 |     1737 | 2024-07-18 | NRG              | L   | 0.857      | -            | -                | -                | -         |    -8.20 | danoco, land1n, mawth, tatazin, w1   |
|           19 |     1741 | 2024-07-18 | NRG              | L   | 0.857      | -            | -                | -                | -         |    -8.76 | danoco, land1n, mawth, tatazin, w1   |
|           18 |     1863 | 2024-07-16 | Nouns            | W   | 0.844      | 0.477        | 0.056 (0.023)    | 0.519 (0.209)    | -         |    18.85 | danoco, land1n, mawth, tatazin, w1   |
|           17 |     1869 | 2024-07-16 | Nouns            | L   | 0.843      | -            | -                | -                | -         |    -7.52 | danoco, land1n, mawth, tatazin, w1   |
|           16 |     2153 | 2024-06-16 | Akimbo           | W   | 0.643      | 0.143        | 0.010 (0.001)    | -                | -         |     8.44 | land1n, mawth, RenanZin, tatazin, w1 |
|           15 |     2181 | 2024-06-15 | Homyno           | W   | 0.637      | -            | -                | -                | -         |     6.48 | land1n, mawth, RenanZin, tatazin, w1 |
|           14 |     2216 | 2024-06-14 | Take Flyte       | L   | 0.630      | -            | -                | -                | -         |   -13.12 | land1n, mawth, RenanZin, tatazin, w1 |
|           13 |     2267 | 2024-06-13 | Carpe Diem       | W   | 0.621      | 0.371        | 0.004 (0.001)    | -                | -         |     8.01 | land1n, mawth, RenanZin, tatazin, w1 |
|           12 |     2290 | 2024-06-12 | Homyno           | W   | 0.617      | -            | -                | -                | -         |     6.51 | land1n, mawth, RenanZin, tatazin, w1 |
|           11 |     2291 | 2024-06-12 | Limitless        | W   | 0.616      | -            | -                | -                | -         |     5.52 | land1n, mawth, RenanZin, tatazin, w1 |
|           10 |     2342 | 2024-06-10 | Homyno           | W   | 0.601      | 0.371        | -                | 0.143 (0.032)    | -         |     6.94 | land1n, mawth, RenanZin, tatazin, w1 |
|            9 |     2366 | 2024-06-09 | Akimbo           | L   | 0.597      | -            | -                | -                | -         |   -10.58 | land1n, mawth, RenanZin, tatazin, w1 |
|            8 |     2428 | 2024-06-08 | straykids        | W   | 0.590      | -            | -                | -                | -         |     6.30 | land1n, mawth, RenanZin, tatazin, w1 |
|            7 |     2437 | 2024-06-08 | Akimbo           | W   | 0.589      | -            | -                | -                | -         |     5.62 | land1n, mawth, RenanZin, tatazin, w1 |
|            6 |     2484 | 2024-06-07 | Homyno           | W   | 0.583      | -            | -                | -                | -         |     7.28 | land1n, mawth, RenanZin, tatazin, w1 |
|            5 |     2546 | 2024-06-06 | Final Form       | L   | 0.576      | -            | -                | -                | -         |   -14.20 | land1n, mawth, RenanZin, tatazin, w1 |
|            4 |     2562 | 2024-06-06 | Party Astronauts | L   | 0.575      | -            | -                | -                | -         |    -5.97 | land1n, mawth, RenanZin, tatazin, w1 |
|            3 |     2663 | 2024-06-04 | Legacy           | L   | 0.564      | -            | -                | -                | -         |    -5.84 | land1n, mawth, RenanZin, tatazin, w1 |
|            2 |     2704 | 2024-06-03 | Perseverance     | W   | 0.556      | -            | -                | -                | -         |     3.36 | land1n, mawth, RenanZin, tatazin, w1 |
|            1 |     3072 | 2024-05-20 | M80              | L   | 0.462      | -            | -                | -                | -         |    -1.87 | land1n, mawth, RenanZin, tatazin, w1 |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,474.06)
- Divide that value by the 5th highest value among all rosters ($303,706.75)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.643 | $750.00        | $482.60         |
| 2024-06-10 |      0.603 | $3,300.00      | $1,991.46       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
