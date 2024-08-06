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
Final Rank Value (800.4) = Starting Rank Value (778.6) + Head To Head Adjustments (21.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.336[<sup>1</sup>](#table2)
- Bounty Collected: 0.303[<sup>2</sup>](#table1)
- Opponent Network: 0.097[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.184<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 778.6
- 400 + ( ( 0.184 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 778.6


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
|           29 |       75 | 2024-08-03 | undefined        | L   | 1.000      | -            | -                | -                | -         |   -24.91 | danoco, land1n, mawth, tatazin, w1   |
|           28 |      179 | 2024-07-31 | LAG              | W   | 1.000      | 0.477        | 0.012 (0.006)    | 0.376 (0.179)    | 0 (0.000) |    13.22 | danoco, land1n, mawth, tatazin, w1   |
|           27 |      184 | 2024-07-31 | LAG              | W   | 1.000      | 0.477        | 0.012 (0.006)    | 0.376 (0.179)    | 0 (0.000) |    14.42 | danoco, land1n, mawth, tatazin, w1   |
|           26 |      230 | 2024-07-30 | M80              | L   | 1.000      | -            | -                | -                | -         |    -2.14 | danoco, land1n, mawth, tatazin, w1   |
|           25 |      234 | 2024-07-30 | M80              | L   | 1.000      | -            | -                | -                | -         |    -2.19 | danoco, land1n, mawth, tatazin, w1   |
|           24 |      360 | 2024-07-26 | Vibe             | W   | 1.000      | 0.371        | -                | 0.068 (0.025)    | 0 (0.000) |     3.03 | danoco, land1n, mawth, tatazin, w1   |
|           23 |      425 | 2024-07-24 | FLUFFY AIMERS    | W   | 1.000      | 0.477        | 0.003 (0.001)    | 0.304 (0.145)    | 0 (0.000) |    12.59 | danoco, land1n, mawth, tatazin, w1   |
|           22 |      428 | 2024-07-24 | FLUFFY AIMERS    | L   | 1.000      | -            | -                | -                | -         |   -19.19 | danoco, land1n, mawth, tatazin, w1   |
|           21 |      620 | 2024-07-18 | NRG              | L   | 1.000      | -            | -                | -                | -         |    -8.44 | danoco, land1n, mawth, tatazin, w1   |
|           20 |      624 | 2024-07-18 | NRG              | L   | 1.000      | -            | -                | -                | -         |    -9.06 | danoco, land1n, mawth, tatazin, w1   |
|           19 |      746 | 2024-07-16 | Nouns            | W   | 1.000      | 0.477        | 0.057 (0.027)    | 0.541 (0.258)    | 0 (0.000) |    22.99 | danoco, land1n, mawth, tatazin, w1   |
|           18 |      752 | 2024-07-16 | Nouns            | L   | 1.000      | -            | -                | -                | -         |    -8.02 | danoco, land1n, mawth, tatazin, w1   |
|           17 |     1033 | 2024-06-16 | Akimbo           | W   | 0.863      | 0.143        | 0.015 (0.002)    | 0.263 (0.032)    | 0 (0.000) |    12.64 | land1n, mawth, RenanZin, tatazin, w1 |
|           16 |     1061 | 2024-06-15 | Homyno           | W   | 0.856      | 0.143        | 0.007 (0.001)    | -                | 0 (0.000) |     9.03 | land1n, mawth, RenanZin, tatazin, w1 |
|           15 |     1096 | 2024-06-14 | Take Flyte       | L   | 0.849      | -            | -                | -                | -         |   -18.06 | land1n, mawth, RenanZin, tatazin, w1 |
|           14 |     1147 | 2024-06-13 | Limitless        | W   | 0.840      | 0.371        | 0.005 (0.002)    | 0.128 (0.040)    | 0 (0.000) |    11.76 | land1n, mawth, RenanZin, tatazin, w1 |
|           13 |     1170 | 2024-06-12 | Homyno           | W   | 0.836      | -            | -                | -                | 0 (0.000) |     9.25 | land1n, mawth, RenanZin, tatazin, w1 |
|           12 |     1171 | 2024-06-12 | Limitless        | W   | 0.835      | -            | -                | -                | 0 (0.000) |     7.20 | land1n, mawth, RenanZin, tatazin, w1 |
|           11 |     1222 | 2024-06-10 | Homyno           | W   | 0.820      | 0.371        | 0.007 (0.002)    | 0.153 (0.046)    | -         |    10.22 | land1n, mawth, RenanZin, tatazin, w1 |
|           10 |     1246 | 2024-06-09 | Akimbo           | L   | 0.816      | -            | -                | -                | -         |   -12.53 | land1n, mawth, RenanZin, tatazin, w1 |
|            9 |     1308 | 2024-06-08 | straykids        | W   | 0.809      | 0.368        | 0.005 (0.002)    | -                | -         |     8.95 | land1n, mawth, RenanZin, tatazin, w1 |
|            8 |     1317 | 2024-06-08 | Akimbo           | W   | 0.808      | 0.371        | -                | 0.071 (0.021)    | -         |     9.05 | land1n, mawth, RenanZin, tatazin, w1 |
|            7 |     1364 | 2024-06-07 | Homyno           | W   | 0.803      | 0.368        | 0.007 (0.002)    | 0.153 (0.045)    | -         |    11.24 | land1n, mawth, RenanZin, tatazin, w1 |
|            6 |     1426 | 2024-06-06 | Final Form       | L   | 0.795      | -            | -                | -                | -         |   -19.29 | land1n, mawth, RenanZin, tatazin, w1 |
|            5 |     1442 | 2024-06-06 | Party Astronauts | L   | 0.794      | -            | -                | -                | -         |    -6.84 | land1n, mawth, RenanZin, tatazin, w1 |
|            4 |     1543 | 2024-06-04 | Legacy           | L   | 0.783      | -            | -                | -                | -         |    -5.54 | land1n, mawth, RenanZin, tatazin, w1 |
|            3 |     1584 | 2024-06-03 | Perseverance     | W   | 0.775      | -            | -                | -                | -         |     4.72 | land1n, mawth, RenanZin, tatazin, w1 |
|            2 |     1952 | 2024-05-20 | M80              | L   | 0.681      | -            | -                | -                | -         |    -1.49 | land1n, mawth, RenanZin, tatazin, w1 |
|            1 |     4245 | 2024-02-16 | Mythic           | L   | 0.055      | -            | -                | -                | -         |    -0.84 | land1n, mawth, RenanZin, tatazin, w1 |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,361.69)
- Divide that value by the 5th highest value among all rosters ($320,109.81)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.863 | $750.00        | $646.98         |
| 2024-06-10 |      0.823 | $3,300.00      | $2,714.71       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
