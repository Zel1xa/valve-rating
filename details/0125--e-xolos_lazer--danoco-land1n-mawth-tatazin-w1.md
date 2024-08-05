### Roster Details<br />
Team Name: E-Xolos LAZER<br />
Roster: danoco, land1n, mawth, tatazin, w1<br />
Global Rank: [125](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [34]( ../standings_americas.md)<br />
<br />
Final Rank Value:  791.1<br />
<br />
Final Rank Value (791.1) = Starting Rank Value (759.1) + Head To Head Adjustments (32.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.336[<sup>1</sup>](#table2)
- Bounty Collected: 0.296[<sup>2</sup>](#table1)
- Opponent Network: 0.064[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.174<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 759.1
- 400 + ( ( 0.174 - 0.000 ) / ( 0.776 - 0.000 ) ) * 1600 = 759.1


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
|           26 |       34 | 2024-07-30 | M80              | L   | 1.000      | -            | -                | -                | -         |    -1.89 | danoco, land1n, mawth, tatazin, w1   |
|           25 |       38 | 2024-07-30 | M80              | L   | 1.000      | -            | -                | -                | -         |    -1.93 | danoco, land1n, mawth, tatazin, w1   |
|           24 |      164 | 2024-07-26 | Vibe             | W   | 1.000      | 0.371        | -                | 0.070 (0.026)    | 0 (0.000) |     3.14 | danoco, land1n, mawth, tatazin, w1   |
|           23 |      229 | 2024-07-24 | FLUFFY AIMERS    | W   | 1.000      | 0.477        | 0.003 (0.001)    | 0.233 (0.111)    | 0 (0.000) |    12.65 | danoco, land1n, mawth, tatazin, w1   |
|           22 |      232 | 2024-07-24 | FLUFFY AIMERS    | L   | 1.000      | -            | -                | -                | -         |   -19.13 | danoco, land1n, mawth, tatazin, w1   |
|           21 |      424 | 2024-07-18 | NRG              | L   | 1.000      | -            | -                | -                | -         |    -7.93 | danoco, land1n, mawth, tatazin, w1   |
|           20 |      428 | 2024-07-18 | NRG              | L   | 1.000      | -            | -                | -                | -         |    -8.48 | danoco, land1n, mawth, tatazin, w1   |
|           19 |      550 | 2024-07-16 | Nouns            | W   | 1.000      | 0.477        | 0.058 (0.028)    | 0.546 (0.260)    | 0 (0.000) |    23.52 | danoco, land1n, mawth, tatazin, w1   |
|           18 |      556 | 2024-07-16 | Nouns            | L   | 1.000      | -            | -                | -                | -         |    -7.47 | danoco, land1n, mawth, tatazin, w1   |
|           17 |      837 | 2024-06-16 | Akimbo           | W   | 0.901      | 0.143        | 0.015 (0.002)    | 0.276 (0.035)    | 0 (0.000) |    13.75 | land1n, mawth, RenanZin, tatazin, w1 |
|           16 |      865 | 2024-06-15 | Homyno           | W   | 0.895      | 0.143        | 0.008 (0.001)    | 0.160 (0.020)    | 0 (0.000) |     9.85 | land1n, mawth, RenanZin, tatazin, w1 |
|           15 |      900 | 2024-06-14 | Take Flyte       | L   | 0.888      | -            | -                | -                | -         |   -18.40 | land1n, mawth, RenanZin, tatazin, w1 |
|           14 |      951 | 2024-06-13 | Limitless        | W   | 0.879      | 0.371        | 0.005 (0.002)    | 0.135 (0.044)    | 0 (0.000) |    13.04 | land1n, mawth, RenanZin, tatazin, w1 |
|           13 |      974 | 2024-06-12 | Homyno           | W   | 0.875      | 0.143        | 0.008 (0.001)    | -                | 0 (0.000) |    10.18 | land1n, mawth, RenanZin, tatazin, w1 |
|           12 |      975 | 2024-06-12 | Limitless        | W   | 0.874      | 0.143        | -                | 0.170 (0.021)    | 0 (0.000) |     8.02 | land1n, mawth, RenanZin, tatazin, w1 |
|           11 |     1026 | 2024-06-10 | Homyno           | W   | 0.859      | 0.371        | 0.008 (0.002)    | 0.160 (0.051)    | 0 (0.000) |    11.34 | land1n, mawth, RenanZin, tatazin, w1 |
|           10 |     1050 | 2024-06-09 | Akimbo           | L   | 0.855      | -            | -                | -                | -         |   -12.32 | land1n, mawth, RenanZin, tatazin, w1 |
|            9 |     1112 | 2024-06-08 | straykids        | W   | 0.848      | 0.368        | 0.005 (0.002)    | -                | 0 (0.000) |     9.96 | land1n, mawth, RenanZin, tatazin, w1 |
|            8 |     1121 | 2024-06-08 | Akimbo           | W   | 0.847      | 0.371        | 0.003 (0.001)    | 0.076 (0.024)    | -         |    10.22 | land1n, mawth, RenanZin, tatazin, w1 |
|            7 |     1168 | 2024-06-07 | Homyno           | W   | 0.841      | 0.368        | 0.008 (0.002)    | 0.160 (0.049)    | -         |    12.60 | land1n, mawth, RenanZin, tatazin, w1 |
|            6 |     1230 | 2024-06-06 | Final Form       | L   | 0.834      | -            | -                | -                | -         |   -19.85 | land1n, mawth, RenanZin, tatazin, w1 |
|            5 |     1246 | 2024-06-06 | Party Astronauts | L   | 0.833      | -            | -                | -                | -         |    -6.32 | land1n, mawth, RenanZin, tatazin, w1 |
|            4 |     1347 | 2024-06-04 | Legacy           | L   | 0.821      | -            | -                | -                | -         |    -5.34 | land1n, mawth, RenanZin, tatazin, w1 |
|            3 |     1388 | 2024-06-03 | Perseverance     | W   | 0.814      | -            | -                | -                | -         |     5.43 | land1n, mawth, RenanZin, tatazin, w1 |
|            2 |     1756 | 2024-05-20 | M80              | L   | 0.720      | -            | -                | -                | -         |    -1.28 | land1n, mawth, RenanZin, tatazin, w1 |
|            1 |     4049 | 2024-02-16 | Mythic           | L   | 0.094      | -            | -                | -                | -         |    -1.32 | land1n, mawth, RenanZin, tatazin, w1 |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,518.76)
- Divide that value by the 5th highest value among all rosters ($331,608.80)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.901 | $750.00        | $676.07         |
| 2024-06-10 |      0.861 | $3,300.00      | $2,842.69       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
