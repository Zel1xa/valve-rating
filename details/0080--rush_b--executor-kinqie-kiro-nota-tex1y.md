### Roster Details<br />
Team Name: RUSH B<br />
Roster: executor, kinqie, Kiro, nota, tex1y<br />
Global Rank: [80](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [59]( ../standings_europe.md)<br />
<br />
Final Rank Value:  936.9<br />
<br />
Final Rank Value (936.9) = Starting Rank Value (844.8) + Head To Head Adjustments (92.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.360[<sup>1</sup>](#table2)
- Bounty Collected: 0.363[<sup>2</sup>](#table1)
- Opponent Network: 0.140[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.216<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 844.8
- 400 + ( ( 0.216 - 0.000 ) / ( 0.776 - 0.000 ) ) * 1600 = 844.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent        | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                              |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           28 |       51 | 2024-07-30 | Rebels          | W   | 1.000      | 0.500        | 0.040 (0.020)    | 0.596 (0.298)    | 0 (0.000) |    20.11 | executor, kinqie, Kiro, nota, tex1y |
|           27 |      282 | 2024-07-23 | SINNERS         | W   | 1.000      | 0.500        | 0.038 (0.019)    | 0.721 (0.360)    | 0 (0.000) |    18.04 | executor, kinqie, Kiro, nota, tex1y |
|           26 |      406 | 2024-07-19 | SAW             | L   | 1.000      | -            | -                | -                | -         |    -4.87 | executor, kinqie, Kiro, nota, tex1y |
|           25 |      524 | 2024-07-17 | brazylijski luz | L   | 1.000      | -            | -                | -                | -         |   -18.54 | executor, kinqie, Kiro, nota, tex1y |
|           24 |      625 | 2024-07-15 | Sangal          | L   | 1.000      | -            | -                | -                | -         |    -5.22 | executor, kinqie, Kiro, nota, tex1y |
|           23 |     1035 | 2024-06-10 | PARIVISION      | L   | 0.858      | -            | -                | -                | -         |    -8.40 | executor, kinqie, Kiro, nota, tex1y |
|           22 |     1043 | 2024-06-10 | SAW             | L   | 0.858      | -            | -                | -                | -         |    -5.48 | executor, kinqie, Kiro, nota, tex1y |
|           21 |     1048 | 2024-06-10 | Monte           | W   | 0.857      | 0.143        | 0.080 (0.010)    | 0.613 (0.075)    | 0 (0.000) |    17.21 | executor, kinqie, Kiro, nota, tex1y |
|           20 |     1077 | 2024-06-09 | 9 Pandas        | W   | 0.852      | 0.143        | 0.082 (0.010)    | 0.579 (0.070)    | 0 (0.000) |    18.99 | executor, kinqie, Kiro, nota, tex1y |
|           19 |     1086 | 2024-06-09 | Aurora          | W   | 0.851      | 0.143        | 0.429 (0.052)    | 0.800 (0.097)    | 0 (0.000) |    25.72 | executor, kinqie, Kiro, nota, tex1y |
|           18 |     1093 | 2024-06-09 | SINNERS         | W   | 0.851      | 0.143        | 0.038 (0.005)    | 0.721 (0.088)    | 0 (0.000) |    18.07 | executor, kinqie, Kiro, nota, tex1y |
|           17 |     1104 | 2024-06-09 | 3DMAX           | L   | 0.850      | -            | -                | -                | -         |    -0.86 | executor, kinqie, Kiro, nota, tex1y |
|           16 |     1255 | 2024-06-06 | Aurora          | L   | 0.832      | -            | -                | -                | -         |    -0.63 | executor, kinqie, Kiro, nota, tex1y |
|           15 |     1318 | 2024-06-05 | SINNERS         | L   | 0.826      | -            | -                | -                | -         |    -9.03 | executor, kinqie, Kiro, nota, tex1y |
|           14 |     1366 | 2024-06-04 | SAW             | W   | 0.819      | 0.500        | 0.107 (0.044)    | 0.545 (0.223)    | 0 (0.000) |    22.59 | executor, kinqie, Kiro, nota, tex1y |
|           13 |     2164 | 2024-05-07 | MOUZ NXT        | L   | 0.631      | -            | -                | -                | -         |    -5.40 | executor, kinqie, Kiro, nota, tex1y |
|           12 |     2193 | 2024-05-05 | Sampi           | L   | 0.619      | -            | -                | -                | -         |    -8.01 | executor, kinqie, Kiro, nota, tex1y |
|           11 |     2214 | 2024-05-04 | HAVU            | W   | 0.612      | 0.435        | -                | 0.162 (0.043)    | 0 (0.000) |     5.89 | executor, kinqie, Kiro, nota, tex1y |
|           10 |     2259 | 2024-05-02 | EYEBALLERS      | L   | 0.598      | -            | -                | -                | -         |    -8.39 | executor, kinqie, Kiro, nota, tex1y |
|            9 |     2316 | 2024-04-29 | ENCE Academy    | W   | 0.580      | 0.435        | 0.005 (0.001)    | 0.156 (0.039)    | 0 (0.000) |     6.05 | executor, kinqie, Kiro, nota, tex1y |
|            8 |     2819 | 2024-04-10 | KOI             | L   | 0.453      | -            | -                | -                | -         |    -3.03 | executor, kinqie, Kiro, nota, tex1y |
|            7 |     2873 | 2024-04-09 | PARIVISION      | W   | 0.446      | 0.500        | 0.018 (0.004)    | 0.452 (0.101)    | 0 (0.000) |    11.04 | executor, kinqie, Kiro, nota, tex1y |
|            6 |     3108 | 2024-04-01 | PERA            | L   | 0.392      | -            | -                | -                | -         |    -5.11 | executor, kinqie, Kiro, nota, tex1y |
|            5 |     3117 | 2024-03-31 | Monte           | W   | 0.385      | 0.500        | 0.062 (0.012)    | -                | -         |     8.60 | executor, kinqie, Kiro, nota, tex1y |
|            4 |     3129 | 2024-03-29 | System5         | W   | 0.373      | -            | -                | -                | -         |     3.34 | executor, kinqie, Kiro, nota, tex1y |
|            3 |     3446 | 2024-03-13 | Betera          | W   | 0.266      | -            | -                | -                | -         |     2.59 | executor, kinqie, Kiro, nota, tex1y |
|            2 |     3711 | 2024-03-03 | Metizport       | L   | 0.199      | -            | -                | -                | -         |    -2.57 | executor, kinqie, Kiro, nota, tex1y |
|            1 |     3822 | 2024-02-26 | SAW             | L   | 0.160      | -            | -                | -                | -         |    -0.66 | executor, kinqie, Kiro, nota, tex1y |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($5,538.30)
- Divide that value by the 5th highest value among all rosters ($331,608.80)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
