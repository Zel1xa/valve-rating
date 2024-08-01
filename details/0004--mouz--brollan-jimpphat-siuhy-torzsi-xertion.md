### Roster Details<br />
Team Name: MOUZ<br />
Roster: Brollan, Jimpphat, siuhy, torzsi, xertioN<br />
Global Rank: [4](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [4]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1885.9<br />
<br />
Final Rank Value (1885.9) = Starting Rank Value (1870.5) + Head To Head Adjustments (15.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 1.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.661[<sup>2</sup>](#table1)
- Opponent Network: 0.332[<sup>2</sup>](#table1)
- LAN Wins: 0.863[<sup>2</sup>](#table1)

The average of these factors is 0.714<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1870.5
- 400 + ( ( 0.714 - 0.000 ) / ( 0.777 - 0.000 ) ) * 1600 = 1870.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent           | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                    |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           32 |      396 | 2024-07-20 | Natus Vincere      | L   | 1.000      | -            | -                | -                | -         |   -13.46 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           31 |      440 | 2024-07-19 | FURIA              | W   | 1.000      | 1.000        | 0.286 (0.286)    | 0.495 (0.495)    | 1 (1.000) |     5.08 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           30 |      582 | 2024-07-17 | Sashi              | W   | 1.000      | 1.000        | 0.187 (0.187)    | 0.971 (0.971)    | 1 (1.000) |     0.56 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           29 |     1595 | 2024-05-28 | G2                 | L   | 0.770      | -            | -                | -                | -         |   -11.31 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           28 |     1616 | 2024-05-27 | Complexity         | W   | 0.763      | 0.624        | -                | 0.366 (0.175)    | 1 (0.763) |     4.58 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           27 |     1625 | 2024-05-27 | 9z                 | L   | 0.762      | -            | -                | -                | -         |   -23.63 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           26 |     1871 | 2024-05-19 | Spirit             | W   | 0.707      | 0.769        | 1.000 (0.543)    | 0.424 (0.230)    | 1 (0.707) |    11.03 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           25 |     1899 | 2024-05-18 | HEROIC             | W   | 0.701      | 0.769        | -                | 0.381 (0.205)    | 1 (0.701) |     2.65 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           24 |     1979 | 2024-05-16 | Virtus.pro         | W   | 0.686      | 0.769        | 0.483 (0.255)    | -                | 1 (0.686) |     4.93 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           23 |     2090 | 2024-05-14 | BetBoom            | W   | 0.673      | 0.769        | -                | 0.551 (0.285)    | 1 (0.673) |     1.05 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           22 |     2137 | 2024-05-12 | Vitality           | W   | 0.661      | 0.889        | 0.591 (0.347)    | 0.385 (0.226)    | 1 (0.661) |     9.33 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           21 |     2158 | 2024-05-11 | Complexity         | W   | 0.655      | 0.889        | 0.318 (0.185)    | 0.366 (0.213)    | 1 (0.655) |     4.54 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           20 |     2206 | 2024-05-09 | G2                 | W   | 0.642      | 0.889        | 1.000 (0.570)    | 0.500 (0.285)    | 1 (0.642) |    11.75 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           19 |     2301 | 2024-05-04 | Liquid             | W   | 0.608      | 0.889        | 0.322 (0.174)    | 0.429 (0.232)    | -         |     1.74 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           18 |     2371 | 2024-05-01 | GamerLegion        | W   | 0.587      | -            | -                | -                | -         |     0.28 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           17 |     2403 | 2024-04-30 | Bad News Kangaroos | W   | 0.580      | -            | -                | -                | -         |     0.04 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           16 |     2833 | 2024-04-14 | FaZe               | L   | 0.473      | -            | -                | -                | -         |   -10.37 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           15 |     2850 | 2024-04-13 | G2                 | W   | 0.465      | 0.624        | 1.000 (0.290)    | -                | -         |     9.23 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           14 |     2947 | 2024-04-10 | Liquid             | W   | 0.446      | -            | -                | -                | -         |     1.25 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           13 |     3021 | 2024-04-08 | FURIA              | W   | 0.433      | -            | -                | -                | -         |     3.85 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           12 |     3032 | 2024-04-07 | TYLOO              | W   | 0.432      | -            | -                | -                | -         |     0.03 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           11 |     3241 | 2024-03-29 | G2                 | L   | 0.369      | -            | -                | -                | -         |    -4.04 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           10 |     3369 | 2024-03-22 | Complexity         | W   | 0.321      | -            | -                | -                | -         |     2.13 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            9 |     3389 | 2024-03-21 | Eternal Fire       | W   | 0.315      | 1.000        | 0.757 (0.238)    | -                | -         |     3.00 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            8 |     3399 | 2024-03-21 | Gaimin Gladiators  | W   | 0.313      | -            | -                | -                | -         |     0.08 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            7 |     4101 | 2024-02-20 | Spirit             | W   | 0.115      | -            | -                | -                | -         |     2.03 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            6 |     4123 | 2024-02-19 | Gaimin Gladiators  | W   | 0.109      | -            | -                | -                | -         |     0.02 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            5 |     4136 | 2024-02-19 | ex-Guild Eagles    | W   | 0.106      | -            | -                | -                | -         |     0.01 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            4 |     4340 | 2024-02-10 | FaZe               | L   | 0.048      | -            | -                | -                | -         |    -1.05 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            3 |     4384 | 2024-02-06 | ENCE               | W   | 0.022      | -            | -                | -                | -         |     0.07 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            2 |     4396 | 2024-02-05 | GamerLegion        | W   | 0.014      | -            | -                | -                | -         |     0.00 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            1 |     4420 | 2024-02-04 | Cloud9             | W   | 0.007      | -            | -                | -                | -         |     0.00 | Brollan, Jimpphat, siuhy, torzsi, xertioN |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($454,827.36)
- Divide that value by the 5th highest value among all rosters ($327,422.13)
- The final value (1.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-21 |      1.000 | $85,000.00     | $85,000.00      |
| 2024-06-02 |      0.802 | $5,000.00      | $4,008.33       |
| 2024-05-19 |      0.707 | $300,000.00    | $212,083.33     |
| 2024-05-12 |      0.661 | $170,000.00    | $112,341.67     |
| 2024-04-14 |      0.473 | $42,000.00     | $19,863.47      |
| 2024-03-31 |      0.382 | $45,000.00     | $17,175.00      |
| 2024-02-11 |      0.054 | $80,000.00     | $4,355.56       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
