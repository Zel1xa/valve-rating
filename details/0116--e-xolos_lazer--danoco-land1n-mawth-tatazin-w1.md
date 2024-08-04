### Roster Details<br />
Team Name: E-Xolos LAZER<br />
Roster: danoco, land1n, mawth, tatazin, w1<br />
Global Rank: [116](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [29]( ../standings_americas.md)<br />
<br />
Final Rank Value:  825.6<br />
<br />
Final Rank Value (825.6) = Starting Rank Value (774.9) + Head To Head Adjustments (50.8)<br />

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
|           28 |       97 | 2024-07-31 | LAG              | W   | 1.000      | 0.477        | 0.012 (0.006)    | 0.341 (0.163)    | 0 (0.000) |    13.90 | danoco, land1n, mawth, tatazin, w1   |
|           27 |      102 | 2024-07-31 | LAG              | W   | 1.000      | 0.477        | 0.012 (0.006)    | 0.341 (0.163)    | 0 (0.000) |    15.18 | danoco, land1n, mawth, tatazin, w1   |
|           26 |      148 | 2024-07-30 | M80              | L   | 1.000      | -            | -                | -                | -         |    -2.07 | danoco, land1n, mawth, tatazin, w1   |
|           25 |      152 | 2024-07-30 | M80              | L   | 1.000      | -            | -                | -                | -         |    -2.12 | danoco, land1n, mawth, tatazin, w1   |
|           24 |      278 | 2024-07-26 | Vibe             | W   | 1.000      | 0.371        | -                | 0.070 (0.026)    | 0 (0.000) |     3.04 | danoco, land1n, mawth, tatazin, w1   |
|           23 |      343 | 2024-07-24 | FLUFFY AIMERS    | W   | 1.000      | 0.477        | 0.003 (0.001)    | 0.274 (0.131)    | 0 (0.000) |    12.54 | danoco, land1n, mawth, tatazin, w1   |
|           22 |      346 | 2024-07-24 | FLUFFY AIMERS    | L   | 1.000      | -            | -                | -                | -         |   -19.25 | danoco, land1n, mawth, tatazin, w1   |
|           21 |      538 | 2024-07-18 | NRG              | L   | 1.000      | -            | -                | -                | -         |    -8.25 | danoco, land1n, mawth, tatazin, w1   |
|           20 |      542 | 2024-07-18 | NRG              | L   | 1.000      | -            | -                | -                | -         |    -8.85 | danoco, land1n, mawth, tatazin, w1   |
|           19 |      664 | 2024-07-16 | Nouns            | W   | 1.000      | 0.477        | 0.057 (0.027)    | 0.547 (0.261)    | 0 (0.000) |    23.07 | danoco, land1n, mawth, tatazin, w1   |
|           18 |      670 | 2024-07-16 | Nouns            | L   | 1.000      | -            | -                | -                | -         |    -7.94 | danoco, land1n, mawth, tatazin, w1   |
|           17 |      950 | 2024-06-16 | Akimbo           | W   | 0.881      | 0.143        | 0.015 (0.002)    | 0.275 (0.035)    | 0 (0.000) |    12.98 | land1n, mawth, RenanZin, tatazin, w1 |
|           16 |      978 | 2024-06-15 | Homyno           | W   | 0.874      | 0.143        | 0.007 (0.001)    | -                | 0 (0.000) |     9.28 | land1n, mawth, RenanZin, tatazin, w1 |
|           15 |     1013 | 2024-06-14 | Take Flyte       | L   | 0.867      | -            | -                | -                | -         |   -18.40 | land1n, mawth, RenanZin, tatazin, w1 |
|           14 |     1064 | 2024-06-13 | Limitless        | W   | 0.858      | 0.371        | 0.005 (0.002)    | 0.134 (0.043)    | 0 (0.000) |    12.19 | land1n, mawth, RenanZin, tatazin, w1 |
|           13 |     1087 | 2024-06-12 | Homyno           | W   | 0.854      | -            | -                | -                | 0 (0.000) |     9.53 | land1n, mawth, RenanZin, tatazin, w1 |
|           12 |     1088 | 2024-06-12 | Limitless        | W   | 0.853      | -            | -                | -                | 0 (0.000) |     7.44 | land1n, mawth, RenanZin, tatazin, w1 |
|           11 |     1139 | 2024-06-10 | Homyno           | W   | 0.838      | 0.371        | 0.007 (0.002)    | 0.159 (0.049)    | -         |    10.56 | land1n, mawth, RenanZin, tatazin, w1 |
|           10 |     1163 | 2024-06-09 | Akimbo           | L   | 0.834      | -            | -                | -                | -         |   -12.66 | land1n, mawth, RenanZin, tatazin, w1 |
|            9 |     1225 | 2024-06-08 | straykids        | W   | 0.827      | 0.368        | 0.005 (0.002)    | -                | -         |     9.20 | land1n, mawth, RenanZin, tatazin, w1 |
|            8 |     1234 | 2024-06-08 | Akimbo           | W   | 0.826      | 0.371        | -                | 0.075 (0.023)    | -         |     9.37 | land1n, mawth, RenanZin, tatazin, w1 |
|            7 |     1281 | 2024-06-07 | Homyno           | W   | 0.821      | 0.368        | 0.007 (0.002)    | 0.159 (0.048)    | -         |    11.65 | land1n, mawth, RenanZin, tatazin, w1 |
|            6 |     1343 | 2024-06-06 | Final Form       | L   | 0.813      | -            | -                | -                | -         |   -19.78 | land1n, mawth, RenanZin, tatazin, w1 |
|            5 |     1359 | 2024-06-06 | Party Astronauts | L   | 0.812      | -            | -                | -                | -         |    -6.75 | land1n, mawth, RenanZin, tatazin, w1 |
|            4 |     1460 | 2024-06-04 | Legacy           | L   | 0.801      | -            | -                | -                | -         |    -5.46 | land1n, mawth, RenanZin, tatazin, w1 |
|            3 |     1501 | 2024-06-03 | Perseverance     | W   | 0.793      | -            | -                | -                | -         |     4.91 | land1n, mawth, RenanZin, tatazin, w1 |
|            2 |     1869 | 2024-05-20 | M80              | L   | 0.699      | -            | -                | -                | -         |    -1.47 | land1n, mawth, RenanZin, tatazin, w1 |
|            1 |     4159 | 2024-02-16 | Mythic           | L   | 0.073      | -            | -                | -                | -         |    -1.10 | land1n, mawth, RenanZin, tatazin, w1 |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,434.81)
- Divide that value by the 5th highest value among all rosters ($325,463.29)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.881 | $750.00        | $660.52         |
| 2024-06-10 |      0.841 | $3,300.00      | $2,774.29       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
