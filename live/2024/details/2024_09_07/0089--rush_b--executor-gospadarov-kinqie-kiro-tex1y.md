### Roster Details<br />
Team Name: RUSH B<br />
Roster: executor, Gospadarov, kinqie, Kiro, tex1y<br />
Global Rank: [89](../../standings_global_2024_09_07.md)<br />
<br />
Region: [Europe]( ../../standings_europe_2024_09_07.md)<br />
Regional Rank: [65]( ../../standings_europe_2024_09_07.md)<br />
<br />
Final Rank Value:  889.8<br />
<br />
Final Rank Value (889.8) = Starting Rank Value (852.3) + Head To Head Adjustments (37.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.386[<sup>1</sup>](#table2)
- Bounty Collected: 0.375[<sup>2</sup>](#table1)
- Opponent Network: 0.165[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.231<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 852.3
- 400 + ( ( 0.231 - 0.000 ) / ( 0.818 - 0.000 ) ) * 1600 = 852.3


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
|           34 |       52 | 2024-09-05 | HOTU            | L   | 1.000      | -            | -                | -                | -         |   -21.74 | executor, Gospadarov, kinqie, Kiro, tex1y |
|           33 |      166 | 2024-09-01 | Insilio         | L   | 1.000      | -            | -                | -                | -         |   -15.28 | executor, Gospadarov, kinqie, Kiro, tex1y |
|           32 |      652 | 2024-08-20 | B8              | L   | 1.000      | -            | -                | -                | -         |    -7.56 | executor, kinqie, Kiro, nota, tex1y       |
|           31 |      839 | 2024-08-13 | PARIVISION      | L   | 1.000      | -            | -                | -                | -         |    -8.49 | executor, kinqie, Kiro, nota, tex1y       |
|           30 |      891 | 2024-08-12 | ARCRED          | W   | 1.000      | 0.500        | 0.036 (0.018)    | 0.441 (0.220)    | 0 (0.000) |    17.25 | executor, kinqie, Kiro, nota, tex1y       |
|           29 |     1145 | 2024-08-04 | BC.Game         | L   | 0.974      | -            | -                | -                | -         |   -14.79 | executor, kinqie, Kiro, nota, tex1y       |
|           28 |     1183 | 2024-08-03 | Alliance        | W   | 0.967      | 0.342        | 0.014 (0.005)    | 0.375 (0.124)    | 0 (0.000) |    11.08 | executor, kinqie, Kiro, nota, tex1y       |
|           27 |     1221 | 2024-08-02 | Astralis Talent | W   | 0.960      | 0.342        | -                | 0.115 (0.038)    | 0 (0.000) |     5.83 | executor, kinqie, Kiro, nota, tex1y       |
|           26 |     1332 | 2024-07-30 | Rebels          | W   | 0.943      | 0.500        | 0.028 (0.013)    | 0.677 (0.319)    | 0 (0.000) |    17.57 | executor, kinqie, Kiro, nota, tex1y       |
|           25 |     1563 | 2024-07-23 | SINNERS         | W   | 0.896      | 0.500        | 0.081 (0.036)    | 1.000 (0.448)    | 0 (0.000) |    18.77 | executor, kinqie, Kiro, nota, tex1y       |
|           24 |     1687 | 2024-07-19 | SAW             | L   | 0.869      | -            | -                | -                | -         |    -1.24 | executor, kinqie, Kiro, nota, tex1y       |
|           23 |     1805 | 2024-07-17 | Apogee          | L   | 0.856      | -            | -                | -                | -         |   -17.70 | executor, kinqie, Kiro, nota, tex1y       |
|           22 |     1909 | 2024-07-15 | Sangal          | L   | 0.843      | -            | -                | -                | -         |    -2.95 | executor, kinqie, Kiro, nota, tex1y       |
|           21 |     2319 | 2024-06-10 | PARIVISION      | L   | 0.608      | -            | -                | -                | -         |    -5.38 | executor, kinqie, Kiro, nota, tex1y       |
|           20 |     2327 | 2024-06-10 | SAW             | L   | 0.608      | -            | -                | -                | -         |    -0.98 | executor, kinqie, Kiro, nota, tex1y       |
|           19 |     2332 | 2024-06-10 | Monte           | W   | 0.607      | 0.143        | 0.076 (0.007)    | -                | 0 (0.000) |    11.93 | executor, kinqie, Kiro, nota, tex1y       |
|           18 |     2361 | 2024-06-09 | 9 Pandas        | W   | 0.602      | 0.143        | 0.059 (0.005)    | 0.757 (0.065)    | 0 (0.000) |    13.80 | executor, kinqie, Kiro, nota, tex1y       |
|           17 |     2370 | 2024-06-09 | Aurora          | W   | 0.601      | 0.143        | 0.293 (0.025)    | 0.627 (0.054)    | 0 (0.000) |    17.65 | executor, kinqie, Kiro, nota, tex1y       |
|           16 |     2377 | 2024-06-09 | SINNERS         | W   | 0.601      | 0.143        | 0.081 (0.007)    | 1.000 (0.086)    | 0 (0.000) |    14.15 | executor, kinqie, Kiro, nota, tex1y       |
|           15 |     2388 | 2024-06-09 | 3DMAX           | L   | 0.600      | -            | -                | -                | -         |    -0.40 | executor, kinqie, Kiro, nota, tex1y       |
|           14 |     2539 | 2024-06-06 | Aurora          | L   | 0.582      | -            | -                | -                | -         |    -0.94 | executor, kinqie, Kiro, nota, tex1y       |
|           13 |     2602 | 2024-06-05 | SINNERS         | L   | 0.576      | -            | -                | -                | -         |    -4.68 | executor, kinqie, Kiro, nota, tex1y       |
|           12 |     2650 | 2024-06-04 | SAW             | W   | 0.569      | 0.500        | 0.328 (0.093)    | 0.771 (0.219)    | 0 (0.000) |    17.43 | executor, kinqie, Kiro, nota, tex1y       |
|           11 |     3448 | 2024-05-07 | MOUZ NXT        | L   | 0.381      | -            | -                | -                | -         |    -3.84 | executor, kinqie, Kiro, nota, tex1y       |
|           10 |     3477 | 2024-05-05 | Sampi           | L   | 0.369      | -            | -                | -                | -         |    -4.80 | executor, kinqie, Kiro, nota, tex1y       |
|            9 |     3498 | 2024-05-04 | HAVU            | W   | 0.362      | -            | -                | -                | -         |     2.01 | executor, kinqie, Kiro, nota, tex1y       |
|            8 |     3543 | 2024-05-02 | EYEBALLERS      | L   | 0.348      | -            | -                | -                | -         |    -6.11 | executor, kinqie, Kiro, nota, tex1y       |
|            7 |     3600 | 2024-04-29 | ENCE Academy    | W   | 0.330      | -            | -                | -                | -         |     2.68 | executor, kinqie, Kiro, nota, tex1y       |
|            6 |     4103 | 2024-04-10 | KOI             | L   | 0.203      | -            | -                | -                | -         |    -2.31 | executor, kinqie, Kiro, nota, tex1y       |
|            5 |     4157 | 2024-04-09 | PARIVISION      | W   | 0.196      | 0.500        | -                | 0.754 (0.074)    | -         |     4.85 | executor, kinqie, Kiro, nota, tex1y       |
|            4 |     4392 | 2024-04-01 | Qiang           | L   | 0.142      | -            | -                | -                | -         |    -2.09 | executor, kinqie, Kiro, nota, tex1y       |
|            3 |     4401 | 2024-03-31 | Monte           | W   | 0.135      | 0.500        | 0.076 (0.005)    | -                | -         |     2.69 | executor, kinqie, Kiro, nota, tex1y       |
|            2 |     4413 | 2024-03-29 | System5         | W   | 0.123      | -            | -                | -                | -         |     0.91 | executor, kinqie, Kiro, nota, tex1y       |
|            1 |     4730 | 2024-03-13 | Betera          | W   | 0.016      | -            | -                | -                | -         |     0.13 | executor, kinqie, Kiro, nota, tex1y       |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($7,836.01)
- Divide that value by the 5th highest value among all rosters ($307,186.12)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-09-06 |      1.000 | $1,000.00      | $1,000.00       |
| 2024-08-04 |      0.974 | $3,000.00      | $2,922.92       |
| 2024-06-09 |      0.602 | $6,500.00      | $3,913.09       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
