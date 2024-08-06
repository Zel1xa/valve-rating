### Roster Details<br />
Team Name: E-Xolos LAZER<br />
Roster: danoco, land1n, mawth, tatazin, w1<br />
Global Rank: [124](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [33]( ../standings_americas.md)<br />
<br />
Final Rank Value:  800.4<br />
<br />
Final Rank Value (800.4) = Starting Rank Value (778.5) + Head To Head Adjustments (21.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.336[<sup>1</sup>](#table2)
- Bounty Collected: 0.303[<sup>2</sup>](#table1)
- Opponent Network: 0.097[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.184<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 778.5
- 400 + ( ( 0.184 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 778.5


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
|           29 |       64 | 2024-08-03 | undefined        | L   | 1.000      | -            | -                | -                | -         |   -24.91 | danoco, land1n, mawth, tatazin, w1   |
|           28 |      168 | 2024-07-31 | LAG              | W   | 1.000      | 0.477        | 0.012 (0.006)    | 0.376 (0.179)    | 0 (0.000) |    13.22 | danoco, land1n, mawth, tatazin, w1   |
|           27 |      173 | 2024-07-31 | LAG              | W   | 1.000      | 0.477        | 0.012 (0.006)    | 0.376 (0.179)    | 0 (0.000) |    14.42 | danoco, land1n, mawth, tatazin, w1   |
|           26 |      219 | 2024-07-30 | M80              | L   | 1.000      | -            | -                | -                | -         |    -2.13 | danoco, land1n, mawth, tatazin, w1   |
|           25 |      223 | 2024-07-30 | M80              | L   | 1.000      | -            | -                | -                | -         |    -2.18 | danoco, land1n, mawth, tatazin, w1   |
|           24 |      349 | 2024-07-26 | Vibe             | W   | 1.000      | 0.371        | -                | 0.068 (0.025)    | 0 (0.000) |     3.03 | danoco, land1n, mawth, tatazin, w1   |
|           23 |      414 | 2024-07-24 | FLUFFY AIMERS    | W   | 1.000      | 0.477        | 0.003 (0.001)    | 0.304 (0.145)    | 0 (0.000) |    12.59 | danoco, land1n, mawth, tatazin, w1   |
|           22 |      417 | 2024-07-24 | FLUFFY AIMERS    | L   | 1.000      | -            | -                | -                | -         |   -19.20 | danoco, land1n, mawth, tatazin, w1   |
|           21 |      609 | 2024-07-18 | NRG              | L   | 1.000      | -            | -                | -                | -         |    -8.44 | danoco, land1n, mawth, tatazin, w1   |
|           20 |      613 | 2024-07-18 | NRG              | L   | 1.000      | -            | -                | -                | -         |    -9.05 | danoco, land1n, mawth, tatazin, w1   |
|           19 |      735 | 2024-07-16 | Nouns            | W   | 1.000      | 0.477        | 0.057 (0.027)    | 0.541 (0.258)    | 0 (0.000) |    22.99 | danoco, land1n, mawth, tatazin, w1   |
|           18 |      741 | 2024-07-16 | Nouns            | L   | 1.000      | -            | -                | -                | -         |    -8.02 | danoco, land1n, mawth, tatazin, w1   |
|           17 |     1022 | 2024-06-16 | Akimbo           | W   | 0.864      | 0.143        | 0.015 (0.002)    | 0.263 (0.032)    | 0 (0.000) |    12.66 | land1n, mawth, RenanZin, tatazin, w1 |
|           16 |     1050 | 2024-06-15 | Homyno           | W   | 0.857      | 0.143        | 0.007 (0.001)    | -                | 0 (0.000) |     9.04 | land1n, mawth, RenanZin, tatazin, w1 |
|           15 |     1085 | 2024-06-14 | Take Flyte       | L   | 0.851      | -            | -                | -                | -         |   -18.09 | land1n, mawth, RenanZin, tatazin, w1 |
|           14 |     1136 | 2024-06-13 | Limitless        | W   | 0.842      | 0.371        | 0.005 (0.002)    | 0.128 (0.040)    | 0 (0.000) |    11.78 | land1n, mawth, RenanZin, tatazin, w1 |
|           13 |     1159 | 2024-06-12 | Homyno           | W   | 0.837      | -            | -                | -                | 0 (0.000) |     9.27 | land1n, mawth, RenanZin, tatazin, w1 |
|           12 |     1160 | 2024-06-12 | Limitless        | W   | 0.836      | -            | -                | -                | 0 (0.000) |     7.21 | land1n, mawth, RenanZin, tatazin, w1 |
|           11 |     1211 | 2024-06-10 | Homyno           | W   | 0.822      | 0.371        | 0.007 (0.002)    | 0.153 (0.046)    | -         |    10.24 | land1n, mawth, RenanZin, tatazin, w1 |
|           10 |     1235 | 2024-06-09 | Akimbo           | L   | 0.817      | -            | -                | -                | -         |   -12.54 | land1n, mawth, RenanZin, tatazin, w1 |
|            9 |     1297 | 2024-06-08 | straykids        | W   | 0.811      | 0.368        | 0.005 (0.002)    | -                | -         |     8.96 | land1n, mawth, RenanZin, tatazin, w1 |
|            8 |     1306 | 2024-06-08 | Akimbo           | W   | 0.809      | 0.371        | -                | 0.071 (0.021)    | -         |     9.07 | land1n, mawth, RenanZin, tatazin, w1 |
|            7 |     1353 | 2024-06-07 | Homyno           | W   | 0.804      | 0.368        | 0.007 (0.002)    | 0.153 (0.045)    | -         |    11.26 | land1n, mawth, RenanZin, tatazin, w1 |
|            6 |     1415 | 2024-06-06 | Final Form       | L   | 0.797      | -            | -                | -                | -         |   -19.32 | land1n, mawth, RenanZin, tatazin, w1 |
|            5 |     1431 | 2024-06-06 | Party Astronauts | L   | 0.795      | -            | -                | -                | -         |    -6.85 | land1n, mawth, RenanZin, tatazin, w1 |
|            4 |     1532 | 2024-06-04 | Legacy           | L   | 0.784      | -            | -                | -                | -         |    -5.54 | land1n, mawth, RenanZin, tatazin, w1 |
|            3 |     1573 | 2024-06-03 | Perseverance     | W   | 0.776      | -            | -                | -                | -         |     4.73 | land1n, mawth, RenanZin, tatazin, w1 |
|            2 |     1941 | 2024-05-20 | M80              | L   | 0.682      | -            | -                | -                | -         |    -1.49 | land1n, mawth, RenanZin, tatazin, w1 |
|            1 |     4234 | 2024-02-16 | Mythic           | L   | 0.057      | -            | -                | -                | -         |    -0.86 | land1n, mawth, RenanZin, tatazin, w1 |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,367.31)
- Divide that value by the 5th highest value among all rosters ($320,521.62)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.864 | $750.00        | $648.02         |
| 2024-06-10 |      0.824 | $3,300.00      | $2,719.29       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
