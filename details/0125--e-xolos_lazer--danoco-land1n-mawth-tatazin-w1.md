### Roster Details<br />
Team Name: E-Xolos LAZER<br />
Roster: danoco, land1n, mawth, tatazin, w1<br />
Global Rank: [125](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [33]( ../standings_americas.md)<br />
<br />
Final Rank Value:  800.0<br />
<br />
Final Rank Value (800.0) = Starting Rank Value (777.0) + Head To Head Adjustments (23.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.336[<sup>1</sup>](#table2)
- Bounty Collected: 0.303[<sup>2</sup>](#table1)
- Opponent Network: 0.097[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.184<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 777.0
- 400 + ( ( 0.184 - 0.000 ) / ( 0.781 - 0.000 ) ) * 1600 = 777.0


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
|           29 |       45 | 2024-08-03 | undefined        | L   | 1.000      | -            | -                | -                | -         |   -24.91 | danoco, land1n, mawth, tatazin, w1   |
|           28 |      149 | 2024-07-31 | LAG              | W   | 1.000      | 0.477        | 0.012 (0.006)    | 0.351 (0.167)    | 0 (0.000) |    13.26 | danoco, land1n, mawth, tatazin, w1   |
|           27 |      154 | 2024-07-31 | LAG              | W   | 1.000      | 0.477        | 0.012 (0.006)    | 0.351 (0.167)    | 0 (0.000) |    14.47 | danoco, land1n, mawth, tatazin, w1   |
|           26 |      200 | 2024-07-30 | M80              | L   | 1.000      | -            | -                | -                | -         |    -2.11 | danoco, land1n, mawth, tatazin, w1   |
|           25 |      204 | 2024-07-30 | M80              | L   | 1.000      | -            | -                | -                | -         |    -2.16 | danoco, land1n, mawth, tatazin, w1   |
|           24 |      330 | 2024-07-26 | Vibe             | W   | 1.000      | 0.371        | -                | 0.070 (0.026)    | 0 (0.000) |     3.03 | danoco, land1n, mawth, tatazin, w1   |
|           23 |      395 | 2024-07-24 | FLUFFY AIMERS    | W   | 1.000      | 0.477        | 0.003 (0.001)    | 0.314 (0.150)    | 0 (0.000) |    12.62 | danoco, land1n, mawth, tatazin, w1   |
|           22 |      398 | 2024-07-24 | FLUFFY AIMERS    | L   | 1.000      | -            | -                | -                | -         |   -19.16 | danoco, land1n, mawth, tatazin, w1   |
|           21 |      590 | 2024-07-18 | NRG              | L   | 1.000      | -            | -                | -                | -         |    -8.37 | danoco, land1n, mawth, tatazin, w1   |
|           20 |      594 | 2024-07-18 | NRG              | L   | 1.000      | -            | -                | -                | -         |    -8.98 | danoco, land1n, mawth, tatazin, w1   |
|           19 |      716 | 2024-07-16 | Nouns            | W   | 1.000      | 0.477        | 0.057 (0.027)    | 0.560 (0.267)    | 0 (0.000) |    23.07 | danoco, land1n, mawth, tatazin, w1   |
|           18 |      722 | 2024-07-16 | Nouns            | L   | 1.000      | -            | -                | -                | -         |    -7.94 | danoco, land1n, mawth, tatazin, w1   |
|           17 |     1003 | 2024-06-16 | Akimbo           | W   | 0.870      | 0.143        | 0.015 (0.002)    | 0.273 (0.034)    | 0 (0.000) |    12.79 | land1n, mawth, RenanZin, tatazin, w1 |
|           16 |     1031 | 2024-06-15 | Homyno           | W   | 0.863      | 0.143        | 0.007 (0.001)    | -                | 0 (0.000) |     9.12 | land1n, mawth, RenanZin, tatazin, w1 |
|           15 |     1066 | 2024-06-14 | Take Flyte       | L   | 0.857      | -            | -                | -                | -         |   -18.20 | land1n, mawth, RenanZin, tatazin, w1 |
|           14 |     1117 | 2024-06-13 | Limitless        | W   | 0.848      | 0.371        | 0.005 (0.002)    | 0.133 (0.042)    | 0 (0.000) |    11.91 | land1n, mawth, RenanZin, tatazin, w1 |
|           13 |     1140 | 2024-06-12 | Homyno           | W   | 0.843      | -            | -                | -                | 0 (0.000) |     9.35 | land1n, mawth, RenanZin, tatazin, w1 |
|           12 |     1141 | 2024-06-12 | Limitless        | W   | 0.843      | -            | -                | -                | 0 (0.000) |     7.29 | land1n, mawth, RenanZin, tatazin, w1 |
|           11 |     1192 | 2024-06-10 | Homyno           | W   | 0.828      | 0.371        | 0.007 (0.002)    | 0.158 (0.049)    | -         |    10.34 | land1n, mawth, RenanZin, tatazin, w1 |
|           10 |     1216 | 2024-06-09 | Akimbo           | L   | 0.823      | -            | -                | -                | -         |   -12.58 | land1n, mawth, RenanZin, tatazin, w1 |
|            9 |     1278 | 2024-06-08 | straykids        | W   | 0.817      | 0.368        | 0.005 (0.002)    | -                | -         |     9.04 | land1n, mawth, RenanZin, tatazin, w1 |
|            8 |     1287 | 2024-06-08 | Akimbo           | W   | 0.815      | 0.371        | -                | 0.074 (0.022)    | -         |     9.17 | land1n, mawth, RenanZin, tatazin, w1 |
|            7 |     1334 | 2024-06-07 | Homyno           | W   | 0.810      | 0.368        | 0.007 (0.002)    | 0.158 (0.047)    | -         |    11.38 | land1n, mawth, RenanZin, tatazin, w1 |
|            6 |     1396 | 2024-06-06 | Final Form       | L   | 0.803      | -            | -                | -                | -         |   -19.43 | land1n, mawth, RenanZin, tatazin, w1 |
|            5 |     1412 | 2024-06-06 | Party Astronauts | L   | 0.802      | -            | -                | -                | -         |    -6.81 | land1n, mawth, RenanZin, tatazin, w1 |
|            4 |     1513 | 2024-06-04 | Legacy           | L   | 0.790      | -            | -                | -                | -         |    -5.48 | land1n, mawth, RenanZin, tatazin, w1 |
|            3 |     1554 | 2024-06-03 | Perseverance     | W   | 0.782      | -            | -                | -                | -         |     4.80 | land1n, mawth, RenanZin, tatazin, w1 |
|            2 |     1922 | 2024-05-20 | M80              | L   | 0.689      | -            | -                | -                | -         |    -1.47 | land1n, mawth, RenanZin, tatazin, w1 |
|            1 |     4215 | 2024-02-16 | Mythic           | L   | 0.063      | -            | -                | -                | -         |    -0.95 | land1n, mawth, RenanZin, tatazin, w1 |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,392.06)
- Divide that value by the 5th highest value among all rosters ($322,333.56)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.870 | $750.00        | $652.60         |
| 2024-06-10 |      0.830 | $3,300.00      | $2,739.46       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
