### Roster Details<br />
Team Name: E-Xolos LAZER<br />
Roster: danoco, land1n, mawth, tatazin, w1<br />
Global Rank: [124](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [33]( ../standings_americas.md)<br />
<br />
Final Rank Value:  799.5<br />
<br />
Final Rank Value (799.5) = Starting Rank Value (775.9) + Head To Head Adjustments (23.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.336[<sup>1</sup>](#table2)
- Bounty Collected: 0.304[<sup>2</sup>](#table1)
- Opponent Network: 0.096[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.184<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 775.9
- 400 + ( ( 0.184 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 775.9


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
|           29 |       28 | 2024-08-03 | undefined        | L   | 1.000      | -            | -                | -                | -         |   -24.89 | danoco, land1n, mawth, tatazin, w1   |
|           28 |      132 | 2024-07-31 | LAG              | W   | 1.000      | 0.477        | 0.012 (0.006)    | 0.353 (0.168)    | 0 (0.000) |    13.30 | danoco, land1n, mawth, tatazin, w1   |
|           27 |      137 | 2024-07-31 | LAG              | W   | 1.000      | 0.477        | 0.012 (0.006)    | 0.353 (0.168)    | 0 (0.000) |    14.51 | danoco, land1n, mawth, tatazin, w1   |
|           26 |      183 | 2024-07-30 | M80              | L   | 1.000      | -            | -                | -                | -         |    -2.09 | danoco, land1n, mawth, tatazin, w1   |
|           25 |      187 | 2024-07-30 | M80              | L   | 1.000      | -            | -                | -                | -         |    -2.14 | danoco, land1n, mawth, tatazin, w1   |
|           24 |      313 | 2024-07-26 | Vibe             | W   | 1.000      | 0.371        | -                | 0.071 (0.026)    | 0 (0.000) |     3.04 | danoco, land1n, mawth, tatazin, w1   |
|           23 |      378 | 2024-07-24 | FLUFFY AIMERS    | W   | 1.000      | 0.477        | 0.003 (0.001)    | 0.275 (0.131)    | 0 (0.000) |    12.54 | danoco, land1n, mawth, tatazin, w1   |
|           22 |      381 | 2024-07-24 | FLUFFY AIMERS    | L   | 1.000      | -            | -                | -                | -         |   -19.26 | danoco, land1n, mawth, tatazin, w1   |
|           21 |      573 | 2024-07-18 | NRG              | L   | 1.000      | -            | -                | -                | -         |    -8.35 | danoco, land1n, mawth, tatazin, w1   |
|           20 |      577 | 2024-07-18 | NRG              | L   | 1.000      | -            | -                | -                | -         |    -8.96 | danoco, land1n, mawth, tatazin, w1   |
|           19 |      699 | 2024-07-16 | Nouns            | W   | 1.000      | 0.477        | 0.057 (0.027)    | 0.561 (0.267)    | 0 (0.000) |    23.11 | danoco, land1n, mawth, tatazin, w1   |
|           18 |      705 | 2024-07-16 | Nouns            | L   | 1.000      | -            | -                | -                | -         |    -7.90 | danoco, land1n, mawth, tatazin, w1   |
|           17 |      986 | 2024-06-16 | Akimbo           | W   | 0.876      | 0.143        | 0.015 (0.002)    | 0.274 (0.034)    | 0 (0.000) |    12.89 | land1n, mawth, RenanZin, tatazin, w1 |
|           16 |     1014 | 2024-06-15 | Homyno           | W   | 0.869      | 0.143        | 0.007 (0.001)    | -                | 0 (0.000) |     9.19 | land1n, mawth, RenanZin, tatazin, w1 |
|           15 |     1049 | 2024-06-14 | Take Flyte       | L   | 0.862      | -            | -                | -                | -         |   -18.30 | land1n, mawth, RenanZin, tatazin, w1 |
|           14 |     1100 | 2024-06-13 | Limitless        | W   | 0.854      | 0.371        | 0.005 (0.002)    | 0.134 (0.042)    | 0 (0.000) |    12.03 | land1n, mawth, RenanZin, tatazin, w1 |
|           13 |     1123 | 2024-06-12 | Homyno           | W   | 0.849      | -            | -                | -                | 0 (0.000) |     9.43 | land1n, mawth, RenanZin, tatazin, w1 |
|           12 |     1124 | 2024-06-12 | Limitless        | W   | 0.848      | -            | -                | -                | 0 (0.000) |     7.35 | land1n, mawth, RenanZin, tatazin, w1 |
|           11 |     1175 | 2024-06-10 | Homyno           | W   | 0.834      | 0.371        | 0.007 (0.002)    | 0.159 (0.049)    | -         |    10.44 | land1n, mawth, RenanZin, tatazin, w1 |
|           10 |     1199 | 2024-06-09 | Akimbo           | L   | 0.829      | -            | -                | -                | -         |   -12.63 | land1n, mawth, RenanZin, tatazin, w1 |
|            9 |     1261 | 2024-06-08 | straykids        | W   | 0.823      | 0.368        | 0.005 (0.002)    | -                | -         |     9.13 | land1n, mawth, RenanZin, tatazin, w1 |
|            8 |     1270 | 2024-06-08 | Akimbo           | W   | 0.821      | 0.371        | -                | 0.075 (0.023)    | -         |     9.28 | land1n, mawth, RenanZin, tatazin, w1 |
|            7 |     1317 | 2024-06-07 | Homyno           | W   | 0.816      | 0.368        | 0.007 (0.002)    | 0.159 (0.048)    | -         |    11.52 | land1n, mawth, RenanZin, tatazin, w1 |
|            6 |     1379 | 2024-06-06 | Final Form       | L   | 0.809      | -            | -                | -                | -         |   -19.70 | land1n, mawth, RenanZin, tatazin, w1 |
|            5 |     1395 | 2024-06-06 | Party Astronauts | L   | 0.807      | -            | -                | -                | -         |    -6.83 | land1n, mawth, RenanZin, tatazin, w1 |
|            4 |     1496 | 2024-06-04 | Legacy           | L   | 0.796      | -            | -                | -                | -         |    -5.46 | land1n, mawth, RenanZin, tatazin, w1 |
|            3 |     1537 | 2024-06-03 | Perseverance     | W   | 0.788      | -            | -                | -                | -         |     4.85 | land1n, mawth, RenanZin, tatazin, w1 |
|            2 |     1905 | 2024-05-20 | M80              | L   | 0.694      | -            | -                | -                | -         |    -1.47 | land1n, mawth, RenanZin, tatazin, w1 |
|            1 |     4198 | 2024-02-16 | Mythic           | L   | 0.069      | -            | -                | -                | -         |    -1.03 | land1n, mawth, RenanZin, tatazin, w1 |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,415.22)
- Divide that value by the 5th highest value among all rosters ($324,028.83)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.876 | $750.00        | $656.89         |
| 2024-06-10 |      0.836 | $3,300.00      | $2,758.33       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
