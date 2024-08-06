### Roster Details<br />
Team Name: E-Xolos LAZER<br />
Roster: danoco, land1n, mawth, tatazin, w1<br />
Global Rank: [125](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [33]( ../standings_americas.md)<br />
<br />
Final Rank Value:  800.7<br />
<br />
Final Rank Value (800.7) = Starting Rank Value (778.8) + Head To Head Adjustments (22.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.336[<sup>1</sup>](#table2)
- Bounty Collected: 0.303[<sup>2</sup>](#table1)
- Opponent Network: 0.100[<sup>2</sup>](#table1)
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
|           29 |       56 | 2024-08-03 | undefined        | L   | 1.000      | -            | -                | -                | -         |   -24.92 | danoco, land1n, mawth, tatazin, w1   |
|           28 |      160 | 2024-07-31 | LAG              | W   | 1.000      | 0.477        | 0.012 (0.006)    | 0.385 (0.184)    | 0 (0.000) |    13.23 | danoco, land1n, mawth, tatazin, w1   |
|           27 |      165 | 2024-07-31 | LAG              | W   | 1.000      | 0.477        | 0.012 (0.006)    | 0.385 (0.184)    | 0 (0.000) |    14.43 | danoco, land1n, mawth, tatazin, w1   |
|           26 |      211 | 2024-07-30 | M80              | L   | 1.000      | -            | -                | -                | -         |    -2.13 | danoco, land1n, mawth, tatazin, w1   |
|           25 |      215 | 2024-07-30 | M80              | L   | 1.000      | -            | -                | -                | -         |    -2.17 | danoco, land1n, mawth, tatazin, w1   |
|           24 |      341 | 2024-07-26 | Vibe             | W   | 1.000      | 0.371        | -                | 0.070 (0.026)    | 0 (0.000) |     3.03 | danoco, land1n, mawth, tatazin, w1   |
|           23 |      406 | 2024-07-24 | FLUFFY AIMERS    | W   | 1.000      | 0.477        | 0.003 (0.001)    | 0.311 (0.148)    | 0 (0.000) |    12.59 | danoco, land1n, mawth, tatazin, w1   |
|           22 |      409 | 2024-07-24 | FLUFFY AIMERS    | L   | 1.000      | -            | -                | -                | -         |   -19.20 | danoco, land1n, mawth, tatazin, w1   |
|           21 |      601 | 2024-07-18 | NRG              | L   | 1.000      | -            | -                | -                | -         |    -8.41 | danoco, land1n, mawth, tatazin, w1   |
|           20 |      605 | 2024-07-18 | NRG              | L   | 1.000      | -            | -                | -                | -         |    -9.03 | danoco, land1n, mawth, tatazin, w1   |
|           19 |      727 | 2024-07-16 | Nouns            | W   | 1.000      | 0.477        | 0.057 (0.027)    | 0.553 (0.264)    | 0 (0.000) |    23.02 | danoco, land1n, mawth, tatazin, w1   |
|           18 |      733 | 2024-07-16 | Nouns            | L   | 1.000      | -            | -                | -                | -         |    -7.99 | danoco, land1n, mawth, tatazin, w1   |
|           17 |     1014 | 2024-06-16 | Akimbo           | W   | 0.867      | 0.143        | 0.015 (0.002)    | 0.269 (0.033)    | 0 (0.000) |    12.70 | land1n, mawth, RenanZin, tatazin, w1 |
|           16 |     1042 | 2024-06-15 | Homyno           | W   | 0.860      | 0.143        | 0.007 (0.001)    | -                | 0 (0.000) |     9.05 | land1n, mawth, RenanZin, tatazin, w1 |
|           15 |     1077 | 2024-06-14 | Take Flyte       | L   | 0.853      | -            | -                | -                | -         |   -18.16 | land1n, mawth, RenanZin, tatazin, w1 |
|           14 |     1128 | 2024-06-13 | Limitless        | W   | 0.845      | 0.371        | 0.005 (0.002)    | 0.131 (0.041)    | 0 (0.000) |    11.82 | land1n, mawth, RenanZin, tatazin, w1 |
|           13 |     1151 | 2024-06-12 | Homyno           | W   | 0.840      | -            | -                | -                | 0 (0.000) |     9.28 | land1n, mawth, RenanZin, tatazin, w1 |
|           12 |     1152 | 2024-06-12 | Limitless        | W   | 0.839      | -            | -                | -                | 0 (0.000) |     7.23 | land1n, mawth, RenanZin, tatazin, w1 |
|           11 |     1203 | 2024-06-10 | Homyno           | W   | 0.825      | 0.371        | 0.007 (0.002)    | 0.156 (0.048)    | -         |    10.26 | land1n, mawth, RenanZin, tatazin, w1 |
|           10 |     1227 | 2024-06-09 | Akimbo           | L   | 0.820      | -            | -                | -                | -         |   -12.59 | land1n, mawth, RenanZin, tatazin, w1 |
|            9 |     1289 | 2024-06-08 | straykids        | W   | 0.814      | 0.368        | 0.005 (0.002)    | -                | -         |     8.96 | land1n, mawth, RenanZin, tatazin, w1 |
|            8 |     1298 | 2024-06-08 | Akimbo           | W   | 0.812      | 0.371        | -                | 0.073 (0.022)    | -         |     9.09 | land1n, mawth, RenanZin, tatazin, w1 |
|            7 |     1345 | 2024-06-07 | Homyno           | W   | 0.807      | 0.368        | 0.007 (0.002)    | 0.156 (0.046)    | -         |    11.28 | land1n, mawth, RenanZin, tatazin, w1 |
|            6 |     1407 | 2024-06-06 | Final Form       | L   | 0.800      | -            | -                | -                | -         |   -19.39 | land1n, mawth, RenanZin, tatazin, w1 |
|            5 |     1423 | 2024-06-06 | Party Astronauts | L   | 0.798      | -            | -                | -                | -         |    -6.85 | land1n, mawth, RenanZin, tatazin, w1 |
|            4 |     1524 | 2024-06-04 | Legacy           | L   | 0.787      | -            | -                | -                | -         |    -5.53 | land1n, mawth, RenanZin, tatazin, w1 |
|            3 |     1565 | 2024-06-03 | Perseverance     | W   | 0.779      | -            | -                | -                | -         |     4.74 | land1n, mawth, RenanZin, tatazin, w1 |
|            2 |     1933 | 2024-05-20 | M80              | L   | 0.685      | -            | -                | -                | -         |    -1.49 | land1n, mawth, RenanZin, tatazin, w1 |
|            1 |     4226 | 2024-02-16 | Mythic           | L   | 0.059      | -            | -                | -                | -         |    -0.90 | land1n, mawth, RenanZin, tatazin, w1 |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,378.56)
- Divide that value by the 5th highest value among all rosters ($321,345.23)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.867 | $750.00        | $650.10         |
| 2024-06-10 |      0.827 | $3,300.00      | $2,728.46       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
