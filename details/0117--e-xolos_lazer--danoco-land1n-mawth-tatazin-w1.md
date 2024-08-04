### Roster Details<br />
Team Name: E-Xolos LAZER<br />
Roster: danoco, land1n, mawth, tatazin, w1<br />
Global Rank: [117](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [29]( ../standings_americas.md)<br />
<br />
Final Rank Value:  825.5<br />
<br />
Final Rank Value (825.5) = Starting Rank Value (775.0) + Head To Head Adjustments (50.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.336[<sup>1</sup>](#table2)
- Bounty Collected: 0.304[<sup>2</sup>](#table1)
- Opponent Network: 0.094[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.183<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 775.0
- 400 + ( ( 0.183 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 775.0


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
|           28 |      108 | 2024-07-31 | LAG              | W   | 1.000      | 0.477        | 0.012 (0.006)    | 0.340 (0.162)    | 0 (0.000) |    13.89 | danoco, land1n, mawth, tatazin, w1   |
|           27 |      113 | 2024-07-31 | LAG              | W   | 1.000      | 0.477        | 0.012 (0.006)    | 0.340 (0.162)    | 0 (0.000) |    15.17 | danoco, land1n, mawth, tatazin, w1   |
|           26 |      159 | 2024-07-30 | M80              | L   | 1.000      | -            | -                | -                | -         |    -2.06 | danoco, land1n, mawth, tatazin, w1   |
|           25 |      163 | 2024-07-30 | M80              | L   | 1.000      | -            | -                | -                | -         |    -2.11 | danoco, land1n, mawth, tatazin, w1   |
|           24 |      289 | 2024-07-26 | Vibe             | W   | 1.000      | 0.371        | -                | 0.070 (0.026)    | 0 (0.000) |     3.04 | danoco, land1n, mawth, tatazin, w1   |
|           23 |      354 | 2024-07-24 | FLUFFY AIMERS    | W   | 1.000      | 0.477        | 0.003 (0.001)    | 0.274 (0.131)    | 0 (0.000) |    12.54 | danoco, land1n, mawth, tatazin, w1   |
|           22 |      357 | 2024-07-24 | FLUFFY AIMERS    | L   | 1.000      | -            | -                | -                | -         |   -19.25 | danoco, land1n, mawth, tatazin, w1   |
|           21 |      549 | 2024-07-18 | NRG              | L   | 1.000      | -            | -                | -                | -         |    -8.26 | danoco, land1n, mawth, tatazin, w1   |
|           20 |      553 | 2024-07-18 | NRG              | L   | 1.000      | -            | -                | -                | -         |    -8.86 | danoco, land1n, mawth, tatazin, w1   |
|           19 |      675 | 2024-07-16 | Nouns            | W   | 1.000      | 0.477        | 0.057 (0.027)    | 0.548 (0.261)    | 0 (0.000) |    23.06 | danoco, land1n, mawth, tatazin, w1   |
|           18 |      681 | 2024-07-16 | Nouns            | L   | 1.000      | -            | -                | -                | -         |    -7.95 | danoco, land1n, mawth, tatazin, w1   |
|           17 |      962 | 2024-06-16 | Akimbo           | W   | 0.877      | 0.143        | 0.015 (0.002)    | 0.274 (0.034)    | 0 (0.000) |    12.92 | land1n, mawth, RenanZin, tatazin, w1 |
|           16 |      990 | 2024-06-15 | Homyno           | W   | 0.870      | 0.143        | 0.007 (0.001)    | -                | 0 (0.000) |     9.24 | land1n, mawth, RenanZin, tatazin, w1 |
|           15 |     1025 | 2024-06-14 | Take Flyte       | L   | 0.863      | -            | -                | -                | -         |   -18.32 | land1n, mawth, RenanZin, tatazin, w1 |
|           14 |     1076 | 2024-06-13 | Limitless        | W   | 0.855      | 0.371        | 0.005 (0.002)    | 0.134 (0.042)    | 0 (0.000) |    12.13 | land1n, mawth, RenanZin, tatazin, w1 |
|           13 |     1099 | 2024-06-12 | Homyno           | W   | 0.850      | -            | -                | -                | 0 (0.000) |     9.49 | land1n, mawth, RenanZin, tatazin, w1 |
|           12 |     1100 | 2024-06-12 | Limitless        | W   | 0.849      | -            | -                | -                | 0 (0.000) |     7.42 | land1n, mawth, RenanZin, tatazin, w1 |
|           11 |     1151 | 2024-06-10 | Homyno           | W   | 0.835      | 0.371        | 0.007 (0.002)    | 0.159 (0.049)    | -         |    10.51 | land1n, mawth, RenanZin, tatazin, w1 |
|           10 |     1175 | 2024-06-09 | Akimbo           | L   | 0.830      | -            | -                | -                | -         |   -12.62 | land1n, mawth, RenanZin, tatazin, w1 |
|            9 |     1237 | 2024-06-08 | straykids        | W   | 0.824      | 0.368        | 0.005 (0.002)    | -                | -         |     9.16 | land1n, mawth, RenanZin, tatazin, w1 |
|            8 |     1246 | 2024-06-08 | Akimbo           | W   | 0.822      | 0.371        | -                | 0.075 (0.023)    | -         |     9.32 | land1n, mawth, RenanZin, tatazin, w1 |
|            7 |     1293 | 2024-06-07 | Homyno           | W   | 0.817      | 0.368        | 0.007 (0.002)    | 0.159 (0.048)    | -         |    11.59 | land1n, mawth, RenanZin, tatazin, w1 |
|            6 |     1355 | 2024-06-06 | Final Form       | L   | 0.810      | -            | -                | -                | -         |   -19.70 | land1n, mawth, RenanZin, tatazin, w1 |
|            5 |     1371 | 2024-06-06 | Party Astronauts | L   | 0.808      | -            | -                | -                | -         |    -6.73 | land1n, mawth, RenanZin, tatazin, w1 |
|            4 |     1472 | 2024-06-04 | Legacy           | L   | 0.797      | -            | -                | -                | -         |    -5.45 | land1n, mawth, RenanZin, tatazin, w1 |
|            3 |     1513 | 2024-06-03 | Perseverance     | W   | 0.789      | -            | -                | -                | -         |     4.88 | land1n, mawth, RenanZin, tatazin, w1 |
|            2 |     1881 | 2024-05-20 | M80              | L   | 0.695      | -            | -                | -                | -         |    -1.45 | land1n, mawth, RenanZin, tatazin, w1 |
|            1 |     4174 | 2024-02-16 | Mythic           | L   | 0.070      | -            | -                | -                | -         |    -1.04 | land1n, mawth, RenanZin, tatazin, w1 |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,419.53)
- Divide that value by the 5th highest value among all rosters ($324,344.55)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.877 | $750.00        | $657.69         |
| 2024-06-10 |      0.837 | $3,300.00      | $2,761.84       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
