### Roster Details<br />
Team Name: E-Xolos LAZER<br />
Roster: danoco, land1n, mawth, tatazin, w1<br />
Global Rank: [115](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [29]( ../standings_americas.md)<br />
<br />
Final Rank Value:  825.5<br />
<br />
Final Rank Value (825.5) = Starting Rank Value (774.9) + Head To Head Adjustments (50.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.336[<sup>1</sup>](#table2)
- Bounty Collected: 0.304[<sup>2</sup>](#table1)
- Opponent Network: 0.094[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.183<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 774.9
- 400 + ( ( 0.183 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 774.9


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
|           28 |      100 | 2024-07-31 | LAG              | W   | 1.000      | 0.477        | 0.012 (0.006)    | 0.341 (0.162)    | 0 (0.000) |    13.90 | danoco, land1n, mawth, tatazin, w1   |
|           27 |      105 | 2024-07-31 | LAG              | W   | 1.000      | 0.477        | 0.012 (0.006)    | 0.341 (0.162)    | 0 (0.000) |    15.17 | danoco, land1n, mawth, tatazin, w1   |
|           26 |      151 | 2024-07-30 | M80              | L   | 1.000      | -            | -                | -                | -         |    -2.08 | danoco, land1n, mawth, tatazin, w1   |
|           25 |      155 | 2024-07-30 | M80              | L   | 1.000      | -            | -                | -                | -         |    -2.12 | danoco, land1n, mawth, tatazin, w1   |
|           24 |      281 | 2024-07-26 | Vibe             | W   | 1.000      | 0.371        | -                | 0.070 (0.026)    | 0 (0.000) |     3.04 | danoco, land1n, mawth, tatazin, w1   |
|           23 |      346 | 2024-07-24 | FLUFFY AIMERS    | W   | 1.000      | 0.477        | 0.003 (0.001)    | 0.274 (0.131)    | 0 (0.000) |    12.54 | danoco, land1n, mawth, tatazin, w1   |
|           22 |      349 | 2024-07-24 | FLUFFY AIMERS    | L   | 1.000      | -            | -                | -                | -         |   -19.25 | danoco, land1n, mawth, tatazin, w1   |
|           21 |      541 | 2024-07-18 | NRG              | L   | 1.000      | -            | -                | -                | -         |    -8.26 | danoco, land1n, mawth, tatazin, w1   |
|           20 |      545 | 2024-07-18 | NRG              | L   | 1.000      | -            | -                | -                | -         |    -8.86 | danoco, land1n, mawth, tatazin, w1   |
|           19 |      667 | 2024-07-16 | Nouns            | W   | 1.000      | 0.477        | 0.057 (0.027)    | 0.548 (0.261)    | 0 (0.000) |    23.06 | danoco, land1n, mawth, tatazin, w1   |
|           18 |      673 | 2024-07-16 | Nouns            | L   | 1.000      | -            | -                | -                | -         |    -7.95 | danoco, land1n, mawth, tatazin, w1   |
|           17 |      954 | 2024-06-16 | Akimbo           | W   | 0.877      | 0.143        | 0.015 (0.002)    | 0.274 (0.034)    | 0 (0.000) |    12.93 | land1n, mawth, RenanZin, tatazin, w1 |
|           16 |      982 | 2024-06-15 | Homyno           | W   | 0.871      | 0.143        | 0.007 (0.001)    | -                | 0 (0.000) |     9.25 | land1n, mawth, RenanZin, tatazin, w1 |
|           15 |     1017 | 2024-06-14 | Take Flyte       | L   | 0.864      | -            | -                | -                | -         |   -18.33 | land1n, mawth, RenanZin, tatazin, w1 |
|           14 |     1068 | 2024-06-13 | Limitless        | W   | 0.855      | 0.371        | 0.005 (0.002)    | 0.134 (0.042)    | 0 (0.000) |    12.14 | land1n, mawth, RenanZin, tatazin, w1 |
|           13 |     1091 | 2024-06-12 | Homyno           | W   | 0.851      | -            | -                | -                | 0 (0.000) |     9.50 | land1n, mawth, RenanZin, tatazin, w1 |
|           12 |     1092 | 2024-06-12 | Limitless        | W   | 0.850      | -            | -                | -                | 0 (0.000) |     7.42 | land1n, mawth, RenanZin, tatazin, w1 |
|           11 |     1143 | 2024-06-10 | Homyno           | W   | 0.835      | 0.371        | 0.007 (0.002)    | 0.159 (0.049)    | -         |    10.52 | land1n, mawth, RenanZin, tatazin, w1 |
|           10 |     1167 | 2024-06-09 | Akimbo           | L   | 0.831      | -            | -                | -                | -         |   -12.63 | land1n, mawth, RenanZin, tatazin, w1 |
|            9 |     1229 | 2024-06-08 | straykids        | W   | 0.824      | 0.368        | 0.005 (0.002)    | -                | -         |     9.17 | land1n, mawth, RenanZin, tatazin, w1 |
|            8 |     1238 | 2024-06-08 | Akimbo           | W   | 0.823      | 0.371        | -                | 0.075 (0.023)    | -         |     9.33 | land1n, mawth, RenanZin, tatazin, w1 |
|            7 |     1285 | 2024-06-07 | Homyno           | W   | 0.818      | 0.368        | 0.007 (0.002)    | 0.159 (0.048)    | -         |    11.60 | land1n, mawth, RenanZin, tatazin, w1 |
|            6 |     1347 | 2024-06-06 | Final Form       | L   | 0.810      | -            | -                | -                | -         |   -19.71 | land1n, mawth, RenanZin, tatazin, w1 |
|            5 |     1363 | 2024-06-06 | Party Astronauts | L   | 0.809      | -            | -                | -                | -         |    -6.74 | land1n, mawth, RenanZin, tatazin, w1 |
|            4 |     1464 | 2024-06-04 | Legacy           | L   | 0.798      | -            | -                | -                | -         |    -5.46 | land1n, mawth, RenanZin, tatazin, w1 |
|            3 |     1505 | 2024-06-03 | Perseverance     | W   | 0.790      | -            | -                | -                | -         |     4.89 | land1n, mawth, RenanZin, tatazin, w1 |
|            2 |     1873 | 2024-05-20 | M80              | L   | 0.696      | -            | -                | -                | -         |    -1.46 | land1n, mawth, RenanZin, tatazin, w1 |
|            1 |     4166 | 2024-02-16 | Mythic           | L   | 0.070      | -            | -                | -                | -         |    -1.05 | land1n, mawth, RenanZin, tatazin, w1 |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,422.44)
- Divide that value by the 5th highest value among all rosters ($324,557.31)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.878 | $750.00        | $658.23         |
| 2024-06-10 |      0.838 | $3,300.00      | $2,764.21       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
