### Roster Details<br />
Team Name: RUSH B<br />
Roster: executor, Gospadarov, kinqie, Kiro, tex1y<br />
Global Rank: [90](../../standings_global_2024_09_08.md)<br />
<br />
Region: [Europe]( ../../standings_europe_2024_09_08.md)<br />
Regional Rank: [66]( ../../standings_europe_2024_09_08.md)<br />
<br />
Final Rank Value:  882.9<br />
<br />
Final Rank Value (882.9) = Starting Rank Value (845.0) + Head To Head Adjustments (37.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.386[<sup>1</sup>](#table2)
- Bounty Collected: 0.374[<sup>2</sup>](#table1)
- Opponent Network: 0.160[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.230<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 845.0
- 400 + ( ( 0.230 - 0.000 ) / ( 0.826 - 0.000 ) ) * 1600 = 845.0


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
|           34 |       85 | 2024-09-05 | HOTU            | L   | 1.000      | -            | -                | -                | -         |   -21.64 | executor, Gospadarov, kinqie, Kiro, tex1y |
|           33 |      198 | 2024-09-01 | Insilio         | L   | 1.000      | -            | -                | -                | -         |   -15.05 | executor, Gospadarov, kinqie, Kiro, tex1y |
|           32 |      684 | 2024-08-20 | B8              | L   | 1.000      | -            | -                | -                | -         |    -7.42 | executor, kinqie, Kiro, nota, tex1y       |
|           31 |      871 | 2024-08-13 | PARIVISION      | L   | 1.000      | -            | -                | -                | -         |    -8.44 | executor, kinqie, Kiro, nota, tex1y       |
|           30 |      923 | 2024-08-12 | ARCRED          | W   | 1.000      | 0.500        | 0.036 (0.018)    | 0.427 (0.213)    | 0 (0.000) |    17.24 | executor, kinqie, Kiro, nota, tex1y       |
|           29 |     1177 | 2024-08-04 | BC.Game         | L   | 0.966      | -            | -                | -                | -         |   -14.65 | executor, kinqie, Kiro, nota, tex1y       |
|           28 |     1215 | 2024-08-03 | Alliance        | W   | 0.959      | 0.342        | 0.014 (0.005)    | 0.363 (0.119)    | 0 (0.000) |    11.04 | executor, kinqie, Kiro, nota, tex1y       |
|           27 |     1253 | 2024-08-02 | Astralis Talent | W   | 0.952      | 0.342        | -                | 0.110 (0.036)    | 0 (0.000) |     5.86 | executor, kinqie, Kiro, nota, tex1y       |
|           26 |     1364 | 2024-07-30 | Rebels          | W   | 0.935      | 0.500        | 0.028 (0.013)    | 0.656 (0.306)    | 0 (0.000) |    17.42 | executor, kinqie, Kiro, nota, tex1y       |
|           25 |     1595 | 2024-07-23 | SINNERS         | W   | 0.888      | 0.500        | 0.081 (0.036)    | 1.000 (0.444)    | 0 (0.000) |    18.70 | executor, kinqie, Kiro, nota, tex1y       |
|           24 |     1719 | 2024-07-19 | SAW             | L   | 0.861      | -            | -                | -                | -         |    -1.24 | executor, kinqie, Kiro, nota, tex1y       |
|           23 |     1837 | 2024-07-17 | Apogee          | L   | 0.848      | -            | -                | -                | -         |   -17.50 | executor, kinqie, Kiro, nota, tex1y       |
|           22 |     1941 | 2024-07-15 | Sangal          | L   | 0.835      | -            | -                | -                | -         |    -2.48 | executor, kinqie, Kiro, nota, tex1y       |
|           21 |     2351 | 2024-06-10 | PARIVISION      | L   | 0.600      | -            | -                | -                | -         |    -5.28 | executor, kinqie, Kiro, nota, tex1y       |
|           20 |     2359 | 2024-06-10 | SAW             | L   | 0.600      | -            | -                | -                | -         |    -0.98 | executor, kinqie, Kiro, nota, tex1y       |
|           19 |     2364 | 2024-06-10 | Monte           | W   | 0.599      | 0.143        | 0.076 (0.006)    | -                | 0 (0.000) |    11.76 | executor, kinqie, Kiro, nota, tex1y       |
|           18 |     2393 | 2024-06-09 | 9 Pandas        | W   | 0.594      | 0.143        | 0.059 (0.005)    | 0.732 (0.062)    | 0 (0.000) |    13.65 | executor, kinqie, Kiro, nota, tex1y       |
|           17 |     2402 | 2024-06-09 | Aurora          | W   | 0.593      | 0.143        | 0.290 (0.025)    | 0.603 (0.051)    | 0 (0.000) |    17.38 | executor, kinqie, Kiro, nota, tex1y       |
|           16 |     2409 | 2024-06-09 | SINNERS         | W   | 0.593      | 0.143        | 0.081 (0.007)    | 1.000 (0.085)    | 0 (0.000) |    14.01 | executor, kinqie, Kiro, nota, tex1y       |
|           15 |     2420 | 2024-06-09 | 3DMAX           | L   | 0.593      | -            | -                | -                | -         |    -0.30 | executor, kinqie, Kiro, nota, tex1y       |
|           14 |     2571 | 2024-06-06 | Aurora          | L   | 0.574      | -            | -                | -                | -         |    -0.97 | executor, kinqie, Kiro, nota, tex1y       |
|           13 |     2634 | 2024-06-05 | SINNERS         | L   | 0.568      | -            | -                | -                | -         |    -4.58 | executor, kinqie, Kiro, nota, tex1y       |
|           12 |     2682 | 2024-06-04 | SAW             | W   | 0.561      | 0.500        | 0.330 (0.093)    | 0.747 (0.210)    | 0 (0.000) |    17.17 | executor, kinqie, Kiro, nota, tex1y       |
|           11 |     3480 | 2024-05-07 | MOUZ NXT        | L   | 0.373      | -            | -                | -                | -         |    -3.76 | executor, kinqie, Kiro, nota, tex1y       |
|           10 |     3509 | 2024-05-05 | Sampi           | L   | 0.361      | -            | -                | -                | -         |    -4.72 | executor, kinqie, Kiro, nota, tex1y       |
|            9 |     3530 | 2024-05-04 | HAVU            | W   | 0.354      | -            | -                | -                | -         |     2.01 | executor, kinqie, Kiro, nota, tex1y       |
|            8 |     3575 | 2024-05-02 | EYEBALLERS      | L   | 0.340      | -            | -                | -                | -         |    -5.93 | executor, kinqie, Kiro, nota, tex1y       |
|            7 |     3632 | 2024-04-29 | ENCE Academy    | W   | 0.322      | -            | -                | -                | -         |     2.66 | executor, kinqie, Kiro, nota, tex1y       |
|            6 |     4135 | 2024-04-10 | KOI             | L   | 0.195      | -            | -                | -                | -         |    -2.22 | executor, kinqie, Kiro, nota, tex1y       |
|            5 |     4189 | 2024-04-09 | PARIVISION      | W   | 0.188      | 0.500        | -                | 0.730 (0.069)    | -         |     4.64 | executor, kinqie, Kiro, nota, tex1y       |
|            4 |     4424 | 2024-04-01 | Qiang           | L   | 0.134      | -            | -                | -                | -         |    -1.98 | executor, kinqie, Kiro, nota, tex1y       |
|            3 |     4433 | 2024-03-31 | Monte           | W   | 0.128      | 0.500        | 0.076 (0.005)    | -                | -         |     2.53 | executor, kinqie, Kiro, nota, tex1y       |
|            2 |     4445 | 2024-03-29 | System5         | W   | 0.115      | -            | -                | -                | -         |     0.87 | executor, kinqie, Kiro, nota, tex1y       |
|            1 |     4762 | 2024-03-13 | Betera          | W   | 0.008      | -            | -                | -                | -         |     0.07 | executor, kinqie, Kiro, nota, tex1y       |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($7,760.80)
- Divide that value by the 5th highest value among all rosters ($303,706.75)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-09-06 |      1.000 | $1,000.00      | $1,000.00       |
| 2024-08-04 |      0.966 | $3,000.00      | $2,899.17       |
| 2024-06-09 |      0.594 | $6,500.00      | $3,861.63       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
