### Roster Details<br />
Team Name: E-Xolos LAZER<br />
Roster: danoco, land1n, mawth, tatazin, w1<br />
Global Rank: [114](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [28]( ../standings_americas.md)<br />
<br />
Final Rank Value:  822.1<br />
<br />
Final Rank Value (822.1) = Starting Rank Value (777.1) + Head To Head Adjustments (45.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.336[<sup>1</sup>](#table2)
- Bounty Collected: 0.304[<sup>2</sup>](#table1)
- Opponent Network: 0.097[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.184<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 777.1
- 400 + ( ( 0.184 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 777.1


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
|           27 |       75 | 2024-07-31 | LAG              | W   | 1.000      | 0.477        | 0.012 (0.006)    | 0.353 (0.168)    | 0 (0.000) |    14.10 | danoco, land1n, mawth, tatazin, w1   |
|           26 |       80 | 2024-07-31 | LAG              | W   | 1.000      | 0.477        | 0.012 (0.006)    | 0.353 (0.168)    | 0 (0.000) |    15.40 | danoco, land1n, mawth, tatazin, w1   |
|           25 |      125 | 2024-07-30 | M80              | L   | 1.000      | -            | -                | -                | -         |    -2.02 | danoco, land1n, mawth, tatazin, w1   |
|           24 |      129 | 2024-07-30 | M80              | L   | 1.000      | -            | -                | -                | -         |    -2.07 | danoco, land1n, mawth, tatazin, w1   |
|           23 |      255 | 2024-07-26 | Vibe             | W   | 1.000      | 0.371        | -                | 0.073 (0.027)    | 0 (0.000) |     3.11 | danoco, land1n, mawth, tatazin, w1   |
|           22 |      320 | 2024-07-24 | FLUFFY AIMERS    | W   | 1.000      | 0.477        | 0.003 (0.001)    | 0.283 (0.135)    | 0 (0.000) |    12.65 | danoco, land1n, mawth, tatazin, w1   |
|           21 |      323 | 2024-07-24 | FLUFFY AIMERS    | L   | 1.000      | -            | -                | -                | -         |   -19.13 | danoco, land1n, mawth, tatazin, w1   |
|           20 |      515 | 2024-07-18 | NRG              | L   | 1.000      | -            | -                | -                | -         |    -8.14 | danoco, land1n, mawth, tatazin, w1   |
|           19 |      519 | 2024-07-18 | NRG              | L   | 1.000      | -            | -                | -                | -         |    -8.72 | danoco, land1n, mawth, tatazin, w1   |
|           18 |      638 | 2024-07-16 | Nouns            | W   | 1.000      | 0.477        | 0.057 (0.027)    | 0.566 (0.270)    | 0 (0.000) |    23.04 | danoco, land1n, mawth, tatazin, w1   |
|           17 |      644 | 2024-07-16 | Nouns            | L   | 1.000      | -            | -                | -                | -         |    -7.97 | danoco, land1n, mawth, tatazin, w1   |
|           16 |      916 | 2024-06-16 | Akimbo           | W   | 0.882      | 0.143        | 0.015 (0.002)    | 0.284 (0.036)    | 0 (0.000) |    13.42 | land1n, mawth, RenanZin, tatazin, w1 |
|           15 |      940 | 2024-06-15 | Homyno           | W   | 0.876      | 0.143        | 0.007 (0.001)    | -                | 0 (0.000) |     9.49 | land1n, mawth, RenanZin, tatazin, w1 |
|           14 |      969 | 2024-06-14 | Take Flyte       | L   | 0.869      | -            | -                | -                | -         |   -18.26 | land1n, mawth, RenanZin, tatazin, w1 |
|           13 |     1014 | 2024-06-13 | Limitless        | W   | 0.860      | 0.371        | 0.005 (0.002)    | 0.139 (0.044)    | 0 (0.000) |    12.48 | land1n, mawth, RenanZin, tatazin, w1 |
|           12 |     1037 | 2024-06-12 | Homyno           | W   | 0.856      | -            | -                | -                | 0 (0.000) |     9.77 | land1n, mawth, RenanZin, tatazin, w1 |
|           11 |     1085 | 2024-06-10 | Homyno           | W   | 0.840      | 0.371        | 0.007 (0.002)    | 0.165 (0.051)    | 0 (0.000) |    10.56 | land1n, mawth, RenanZin, tatazin, w1 |
|           10 |     1109 | 2024-06-09 | Akimbo           | L   | 0.836      | -            | -                | -                | -         |   -12.73 | land1n, mawth, RenanZin, tatazin, w1 |
|            9 |     1170 | 2024-06-08 | straykids        | W   | 0.829      | 0.368        | 0.005 (0.002)    | -                | -         |     9.18 | land1n, mawth, RenanZin, tatazin, w1 |
|            8 |     1177 | 2024-06-08 | Akimbo           | W   | 0.828      | 0.371        | -                | 0.078 (0.024)    | -         |     9.35 | land1n, mawth, RenanZin, tatazin, w1 |
|            7 |     1221 | 2024-06-07 | Homyno           | W   | 0.822      | 0.368        | 0.007 (0.002)    | 0.165 (0.050)    | -         |    11.64 | land1n, mawth, RenanZin, tatazin, w1 |
|            6 |     1283 | 2024-06-06 | Final Form       | L   | 0.815      | -            | -                | -                | -         |   -19.87 | land1n, mawth, RenanZin, tatazin, w1 |
|            5 |     1299 | 2024-06-06 | Party Astronauts | L   | 0.814      | -            | -                | -                | -         |    -6.90 | land1n, mawth, RenanZin, tatazin, w1 |
|            4 |     1400 | 2024-06-04 | Legacy           | L   | 0.802      | -            | -                | -                | -         |    -5.58 | land1n, mawth, RenanZin, tatazin, w1 |
|            3 |     1440 | 2024-06-03 | Perseverance     | W   | 0.795      | -            | -                | -                | -         |     4.88 | land1n, mawth, RenanZin, tatazin, w1 |
|            2 |     1805 | 2024-05-20 | M80              | L   | 0.701      | -            | -                | -                | -         |    -1.47 | land1n, mawth, RenanZin, tatazin, w1 |
|            1 |     4086 | 2024-02-16 | Mythic           | L   | 0.075      | -            | -                | -                | -         |    -1.13 | land1n, mawth, RenanZin, tatazin, w1 |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,441.75)
- Divide that value by the 5th highest value among all rosters ($325,971.18)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-16 |      0.882 | $750.00        | $661.81         |
| 2024-06-10 |      0.842 | $3,300.00      | $2,779.94       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
