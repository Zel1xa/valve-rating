### Roster Details<br />
Team Name: RUSH B<br />
Roster: executor, kinqie, Kiro, nota, tex1y<br />
Global Rank: [80](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [58]( ../standings_europe.md)<br />
<br />
Final Rank Value:  934.7<br />
<br />
Final Rank Value (934.7) = Starting Rank Value (846.2) + Head To Head Adjustments (88.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.360[<sup>1</sup>](#table2)
- Bounty Collected: 0.363[<sup>2</sup>](#table1)
- Opponent Network: 0.144[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.217<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 846.2
- 400 + ( ( 0.217 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 846.2


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
|           28 |       86 | 2024-07-30 | Rebels          | W   | 1.000      | 0.500        | 0.040 (0.020)    | 0.635 (0.318)    | 0 (0.000) |    19.11 | executor, kinqie, Kiro, nota, tex1y |
|           27 |      317 | 2024-07-23 | SINNERS         | W   | 1.000      | 0.500        | 0.038 (0.019)    | 0.768 (0.384)    | 0 (0.000) |    18.42 | executor, kinqie, Kiro, nota, tex1y |
|           26 |      445 | 2024-07-19 | SAW             | L   | 1.000      | -            | -                | -                | -         |    -5.03 | executor, kinqie, Kiro, nota, tex1y |
|           25 |      568 | 2024-07-17 | brazylijski luz | L   | 1.000      | -            | -                | -                | -         |   -17.79 | executor, kinqie, Kiro, nota, tex1y |
|           24 |      675 | 2024-07-15 | Sangal          | L   | 1.000      | -            | -                | -                | -         |    -5.67 | executor, kinqie, Kiro, nota, tex1y |
|           23 |     1078 | 2024-06-10 | PARIVISION      | L   | 0.852      | -            | -                | -                | -         |    -8.01 | executor, kinqie, Kiro, nota, tex1y |
|           22 |     1086 | 2024-06-10 | SAW             | L   | 0.852      | -            | -                | -                | -         |    -5.61 | executor, kinqie, Kiro, nota, tex1y |
|           21 |     1091 | 2024-06-10 | Monte           | W   | 0.851      | 0.143        | 0.081 (0.010)    | 0.614 (0.075)    | 0 (0.000) |    16.79 | executor, kinqie, Kiro, nota, tex1y |
|           20 |     1120 | 2024-06-09 | 9 Pandas        | W   | 0.846      | 0.143        | 0.083 (0.010)    | 0.577 (0.070)    | 0 (0.000) |    18.86 | executor, kinqie, Kiro, nota, tex1y |
|           19 |     1129 | 2024-06-09 | Aurora          | W   | 0.845      | 0.143        | 0.431 (0.052)    | 0.798 (0.096)    | 0 (0.000) |    25.52 | executor, kinqie, Kiro, nota, tex1y |
|           18 |     1136 | 2024-06-09 | SINNERS         | W   | 0.845      | 0.143        | 0.038 (0.005)    | 0.768 (0.093)    | 0 (0.000) |    18.34 | executor, kinqie, Kiro, nota, tex1y |
|           17 |     1148 | 2024-06-09 | 3DMAX           | L   | 0.844      | -            | -                | -                | -         |    -0.89 | executor, kinqie, Kiro, nota, tex1y |
|           16 |     1309 | 2024-06-06 | Aurora          | L   | 0.826      | -            | -                | -                | -         |    -0.64 | executor, kinqie, Kiro, nota, tex1y |
|           15 |     1375 | 2024-06-05 | SINNERS         | L   | 0.820      | -            | -                | -                | -         |    -8.34 | executor, kinqie, Kiro, nota, tex1y |
|           14 |     1423 | 2024-06-04 | SAW             | W   | 0.813      | 0.500        | 0.108 (0.044)    | 0.544 (0.221)    | 0 (0.000) |    22.30 | executor, kinqie, Kiro, nota, tex1y |
|           13 |     2261 | 2024-05-07 | MOUZ NXT        | L   | 0.625      | -            | -                | -                | -         |    -5.78 | executor, kinqie, Kiro, nota, tex1y |
|           12 |     2290 | 2024-05-05 | Sampi           | L   | 0.613      | -            | -                | -                | -         |    -8.14 | executor, kinqie, Kiro, nota, tex1y |
|           11 |     2311 | 2024-05-04 | HAVU            | W   | 0.606      | 0.435        | -                | 0.168 (0.044)    | 0 (0.000) |     5.87 | executor, kinqie, Kiro, nota, tex1y |
|           10 |     2357 | 2024-05-02 | EYEBALLERS      | L   | 0.592      | -            | -                | -                | -         |    -8.33 | executor, kinqie, Kiro, nota, tex1y |
|            9 |     2416 | 2024-04-29 | ENCE Academy    | W   | 0.574      | 0.435        | 0.005 (0.001)    | 0.155 (0.039)    | 0 (0.000) |     6.00 | executor, kinqie, Kiro, nota, tex1y |
|            8 |     2930 | 2024-04-10 | KOI             | L   | 0.447      | -            | -                | -                | -         |    -5.34 | executor, kinqie, Kiro, nota, tex1y |
|            7 |     2984 | 2024-04-09 | PARIVISION      | W   | 0.440      | 0.500        | 0.018 (0.004)    | 0.457 (0.101)    | 0 (0.000) |    11.02 | executor, kinqie, Kiro, nota, tex1y |
|            6 |     3227 | 2024-04-01 | PERA            | L   | 0.386      | -            | -                | -                | -         |    -5.13 | executor, kinqie, Kiro, nota, tex1y |
|            5 |     3236 | 2024-03-31 | Monte           | W   | 0.379      | 0.500        | 0.062 (0.012)    | -                | -         |     8.40 | executor, kinqie, Kiro, nota, tex1y |
|            4 |     3248 | 2024-03-29 | System5         | W   | 0.367      | -            | -                | -                | -         |     3.26 | executor, kinqie, Kiro, nota, tex1y |
|            3 |     3575 | 2024-03-13 | Betera          | W   | 0.260      | -            | -                | -                | -         |     2.51 | executor, kinqie, Kiro, nota, tex1y |
|            2 |     3846 | 2024-03-03 | Metizport       | L   | 0.193      | -            | -                | -                | -         |    -2.56 | executor, kinqie, Kiro, nota, tex1y |
|            1 |     3959 | 2024-02-26 | SAW             | L   | 0.154      | -            | -                | -                | -         |    -0.65 | executor, kinqie, Kiro, nota, tex1y |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($5,499.27)
- Divide that value by the 5th highest value among all rosters ($326,952.13)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
