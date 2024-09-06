### Roster Details<br />
Team Name: RUSH B<br />
Roster: executor, Gospadarov, kinqie, Kiro, tex1y<br />
Global Rank: [89](../../standings_global_2024_09_06.md)<br />
<br />
Region: [Europe]( ../../standings_europe_2024_09_06.md)<br />
Regional Rank: [65]( ../../standings_europe_2024_09_06.md)<br />
<br />
Final Rank Value:  890.2<br />
<br />
Final Rank Value (890.2) = Starting Rank Value (852.5) + Head To Head Adjustments (37.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.386[<sup>1</sup>](#table2)
- Bounty Collected: 0.375[<sup>2</sup>](#table1)
- Opponent Network: 0.166[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.232<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 852.5
- 400 + ( ( 0.232 - 0.000 ) / ( 0.819 - 0.000 ) ) * 1600 = 852.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent        | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                    |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           34 |       48 | 2024-09-05 | HOTU            | L   | 1.000      | -            | -                | -                | -         |   -21.76 | executor, Gospadarov, kinqie, Kiro, tex1y |
|           33 |      161 | 2024-09-01 | Insilio         | L   | 1.000      | -            | -                | -                | -         |   -15.32 | executor, Gospadarov, kinqie, Kiro, tex1y |
|           32 |      647 | 2024-08-20 | B8              | L   | 1.000      | -            | -                | -                | -         |    -7.57 | executor, kinqie, Kiro, nota, tex1y       |
|           31 |      834 | 2024-08-13 | PARIVISION      | L   | 1.000      | -            | -                | -                | -         |    -8.51 | executor, kinqie, Kiro, nota, tex1y       |
|           30 |      886 | 2024-08-12 | ARCRED          | W   | 1.000      | 0.500        | 0.036 (0.018)    | 0.440 (0.220)    | 0 (0.000) |    17.23 | executor, kinqie, Kiro, nota, tex1y       |
|           29 |     1140 | 2024-08-04 | BC.Game         | L   | 0.978      | -            | -                | -                | -         |   -14.91 | executor, kinqie, Kiro, nota, tex1y       |
|           28 |     1178 | 2024-08-03 | Alliance        | W   | 0.971      | 0.342        | 0.014 (0.005)    | 0.375 (0.125)    | 0 (0.000) |    11.11 | executor, kinqie, Kiro, nota, tex1y       |
|           27 |     1216 | 2024-08-02 | Astralis Talent | W   | 0.964      | 0.342        | -                | 0.115 (0.038)    | 0 (0.000) |     5.85 | executor, kinqie, Kiro, nota, tex1y       |
|           26 |     1327 | 2024-07-30 | Rebels          | W   | 0.947      | 0.500        | 0.028 (0.013)    | 0.677 (0.320)    | 0 (0.000) |    17.64 | executor, kinqie, Kiro, nota, tex1y       |
|           25 |     1558 | 2024-07-23 | SINNERS         | W   | 0.900      | 0.500        | 0.081 (0.036)    | 1.000 (0.450)    | 0 (0.000) |    18.81 | executor, kinqie, Kiro, nota, tex1y       |
|           24 |     1682 | 2024-07-19 | SAW             | L   | 0.873      | -            | -                | -                | -         |    -1.26 | executor, kinqie, Kiro, nota, tex1y       |
|           23 |     1800 | 2024-07-17 | Apogee          | L   | 0.860      | -            | -                | -                | -         |   -17.77 | executor, kinqie, Kiro, nota, tex1y       |
|           22 |     1904 | 2024-07-15 | Sangal          | L   | 0.847      | -            | -                | -                | -         |    -2.97 | executor, kinqie, Kiro, nota, tex1y       |
|           21 |     2314 | 2024-06-10 | PARIVISION      | L   | 0.612      | -            | -                | -                | -         |    -5.42 | executor, kinqie, Kiro, nota, tex1y       |
|           20 |     2322 | 2024-06-10 | SAW             | L   | 0.612      | -            | -                | -                | -         |    -0.99 | executor, kinqie, Kiro, nota, tex1y       |
|           19 |     2327 | 2024-06-10 | Monte           | W   | 0.611      | 0.143        | 0.076 (0.007)    | -                | 0 (0.000) |    12.02 | executor, kinqie, Kiro, nota, tex1y       |
|           18 |     2356 | 2024-06-09 | 9 Pandas        | W   | 0.606      | 0.143        | 0.059 (0.005)    | 0.756 (0.065)    | 0 (0.000) |    13.88 | executor, kinqie, Kiro, nota, tex1y       |
|           17 |     2365 | 2024-06-09 | Aurora          | W   | 0.605      | 0.143        | 0.294 (0.025)    | 0.629 (0.054)    | 0 (0.000) |    17.77 | executor, kinqie, Kiro, nota, tex1y       |
|           16 |     2372 | 2024-06-09 | SINNERS         | W   | 0.605      | 0.143        | 0.081 (0.007)    | 1.000 (0.086)    | 0 (0.000) |    14.22 | executor, kinqie, Kiro, nota, tex1y       |
|           15 |     2383 | 2024-06-09 | 3DMAX           | L   | 0.604      | -            | -                | -                | -         |    -0.41 | executor, kinqie, Kiro, nota, tex1y       |
|           14 |     2534 | 2024-06-06 | Aurora          | L   | 0.586      | -            | -                | -                | -         |    -0.94 | executor, kinqie, Kiro, nota, tex1y       |
|           13 |     2597 | 2024-06-05 | SINNERS         | L   | 0.580      | -            | -                | -                | -         |    -4.74 | executor, kinqie, Kiro, nota, tex1y       |
|           12 |     2645 | 2024-06-04 | SAW             | W   | 0.573      | 0.500        | 0.326 (0.094)    | 0.770 (0.220)    | 0 (0.000) |    17.55 | executor, kinqie, Kiro, nota, tex1y       |
|           11 |     3443 | 2024-05-07 | MOUZ NXT        | L   | 0.385      | -            | -                | -                | -         |    -3.88 | executor, kinqie, Kiro, nota, tex1y       |
|           10 |     3472 | 2024-05-05 | Sampi           | L   | 0.373      | -            | -                | -                | -         |    -4.86 | executor, kinqie, Kiro, nota, tex1y       |
|            9 |     3493 | 2024-05-04 | HAVU            | W   | 0.366      | -            | -                | -                | -         |     2.03 | executor, kinqie, Kiro, nota, tex1y       |
|            8 |     3538 | 2024-05-02 | EYEBALLERS      | L   | 0.352      | -            | -                | -                | -         |    -6.17 | executor, kinqie, Kiro, nota, tex1y       |
|            7 |     3595 | 2024-04-29 | ENCE Academy    | W   | 0.334      | -            | -                | -                | -         |     2.71 | executor, kinqie, Kiro, nota, tex1y       |
|            6 |     4098 | 2024-04-10 | KOI             | L   | 0.207      | -            | -                | -                | -         |    -2.35 | executor, kinqie, Kiro, nota, tex1y       |
|            5 |     4152 | 2024-04-09 | PARIVISION      | W   | 0.200      | 0.500        | -                | 0.753 (0.075)    | -         |     4.95 | executor, kinqie, Kiro, nota, tex1y       |
|            4 |     4387 | 2024-04-01 | Qiang           | L   | 0.146      | -            | -                | -                | -         |    -2.15 | executor, kinqie, Kiro, nota, tex1y       |
|            3 |     4396 | 2024-03-31 | Monte           | W   | 0.139      | 0.500        | 0.076 (0.005)    | -                | -         |     2.78 | executor, kinqie, Kiro, nota, tex1y       |
|            2 |     4408 | 2024-03-29 | System5         | W   | 0.127      | -            | -                | -                | -         |     0.94 | executor, kinqie, Kiro, nota, tex1y       |
|            1 |     4725 | 2024-03-13 | Betera          | W   | 0.020      | -            | -                | -                | -         |     0.16 | executor, kinqie, Kiro, nota, tex1y       |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($7,874.05)
- Divide that value by the 5th highest value among all rosters ($308,946.16)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-09-06 |      1.000 | $1,000.00      | $1,000.00       |
| 2024-08-04 |      0.978 | $3,000.00      | $2,934.93       |
| 2024-06-09 |      0.606 | $6,500.00      | $3,939.12       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
