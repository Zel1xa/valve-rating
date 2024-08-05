### Roster Details<br />
Team Name: RUSH B<br />
Roster: executor, kinqie, Kiro, nota, tex1y<br />
Global Rank: [74](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [53]( ../standings_europe.md)<br />
<br />
Final Rank Value:  946.7<br />
<br />
Final Rank Value (946.7) = Starting Rank Value (861.4) + Head To Head Adjustments (85.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.386[<sup>1</sup>](#table2)
- Bounty Collected: 0.361[<sup>2</sup>](#table1)
- Opponent Network: 0.152[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.225<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 861.4
- 400 + ( ( 0.225 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 861.4


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
|           31 |       38 | 2024-08-04 | BC.Game         | L   | 1.000      | -            | -                | -                | -         |   -16.05 | executor, kinqie, Kiro, nota, tex1y |
|           30 |       76 | 2024-08-03 | Alliance        | W   | 1.000      | 0.342        | 0.017 (0.006)    | 0.292 (0.100)    | 0 (0.000) |    11.47 | executor, kinqie, Kiro, nota, tex1y |
|           29 |      114 | 2024-08-02 | Astralis Talent | W   | 1.000      | 0.342        | -                | 0.160 (0.055)    | 0 (0.000) |     6.59 | executor, kinqie, Kiro, nota, tex1y |
|           28 |      225 | 2024-07-30 | Rebels          | W   | 1.000      | 0.500        | 0.038 (0.019)    | 0.591 (0.296)    | 0 (0.000) |    19.55 | executor, kinqie, Kiro, nota, tex1y |
|           27 |      456 | 2024-07-23 | SINNERS         | W   | 1.000      | 0.500        | 0.037 (0.019)    | 0.809 (0.404)    | 0 (0.000) |    19.04 | executor, kinqie, Kiro, nota, tex1y |
|           26 |      580 | 2024-07-19 | SAW             | L   | 1.000      | -            | -                | -                | -         |    -5.28 | executor, kinqie, Kiro, nota, tex1y |
|           25 |      698 | 2024-07-17 | brazylijski luz | L   | 1.000      | -            | -                | -                | -         |   -19.04 | executor, kinqie, Kiro, nota, tex1y |
|           24 |      799 | 2024-07-15 | Sangal          | L   | 1.000      | -            | -                | -                | -         |    -5.33 | executor, kinqie, Kiro, nota, tex1y |
|           23 |     1209 | 2024-06-10 | PARIVISION      | L   | 0.826      | -            | -                | -                | -         |    -8.09 | executor, kinqie, Kiro, nota, tex1y |
|           22 |     1217 | 2024-06-10 | SAW             | L   | 0.825      | -            | -                | -                | -         |    -5.80 | executor, kinqie, Kiro, nota, tex1y |
|           21 |     1222 | 2024-06-10 | Monte           | W   | 0.825      | 0.143        | 0.080 (0.009)    | 0.611 (0.072)    | 0 (0.000) |    16.07 | executor, kinqie, Kiro, nota, tex1y |
|           20 |     1251 | 2024-06-09 | 9 Pandas        | W   | 0.819      | 0.143        | 0.081 (0.010)    | 0.718 (0.084)    | 0 (0.000) |    17.81 | executor, kinqie, Kiro, nota, tex1y |
|           19 |     1260 | 2024-06-09 | Aurora          | W   | 0.819      | 0.143        | 0.422 (0.049)    | 0.779 (0.091)    | 0 (0.000) |    24.69 | executor, kinqie, Kiro, nota, tex1y |
|           18 |     1267 | 2024-06-09 | SINNERS         | W   | 0.818      | 0.143        | 0.037 (0.004)    | 0.809 (0.095)    | 0 (0.000) |    18.21 | executor, kinqie, Kiro, nota, tex1y |
|           17 |     1278 | 2024-06-09 | 3DMAX           | L   | 0.818      | -            | -                | -                | -         |    -0.86 | executor, kinqie, Kiro, nota, tex1y |
|           16 |     1429 | 2024-06-06 | Aurora          | L   | 0.800      | -            | -                | -                | -         |    -0.66 | executor, kinqie, Kiro, nota, tex1y |
|           15 |     1492 | 2024-06-05 | SINNERS         | L   | 0.793      | -            | -                | -                | -         |    -7.66 | executor, kinqie, Kiro, nota, tex1y |
|           14 |     1540 | 2024-06-04 | SAW             | W   | 0.787      | 0.500        | 0.105 (0.041)    | 0.530 (0.208)    | 0 (0.000) |    21.23 | executor, kinqie, Kiro, nota, tex1y |
|           13 |     2338 | 2024-05-07 | MOUZ NXT        | L   | 0.599      | -            | -                | -                | -         |    -5.33 | executor, kinqie, Kiro, nota, tex1y |
|           12 |     2367 | 2024-05-05 | Sampi           | L   | 0.586      | -            | -                | -                | -         |    -7.99 | executor, kinqie, Kiro, nota, tex1y |
|           11 |     2388 | 2024-05-04 | HAVU            | W   | 0.579      | -            | -                | -                | 0 (0.000) |     5.20 | executor, kinqie, Kiro, nota, tex1y |
|           10 |     2433 | 2024-05-02 | EYEBALLERS      | L   | 0.565      | -            | -                | -                | -         |    -8.40 | executor, kinqie, Kiro, nota, tex1y |
|            9 |     2490 | 2024-04-29 | ENCE Academy    | W   | 0.547      | -            | -                | -                | -         |     5.10 | executor, kinqie, Kiro, nota, tex1y |
|            8 |     2993 | 2024-04-10 | KOI             | L   | 0.420      | -            | -                | -                | -         |    -3.22 | executor, kinqie, Kiro, nota, tex1y |
|            7 |     3047 | 2024-04-09 | PARIVISION      | W   | 0.414      | 0.500        | 0.017 (0.004)    | 0.565 (0.117)    | -         |    10.21 | executor, kinqie, Kiro, nota, tex1y |
|            6 |     3282 | 2024-04-01 | PERA            | L   | 0.360      | -            | -                | -                | -         |    -4.96 | executor, kinqie, Kiro, nota, tex1y |
|            5 |     3291 | 2024-03-31 | Monte           | W   | 0.353      | 0.500        | 0.057 (0.010)    | -                | -         |     7.36 | executor, kinqie, Kiro, nota, tex1y |
|            4 |     3303 | 2024-03-29 | System5         | W   | 0.341      | -            | -                | -                | -         |     2.81 | executor, kinqie, Kiro, nota, tex1y |
|            3 |     3620 | 2024-03-13 | Betera          | W   | 0.234      | -            | -                | -                | -         |     2.10 | executor, kinqie, Kiro, nota, tex1y |
|            2 |     3885 | 2024-03-03 | Metizport       | L   | 0.167      | -            | -                | -                | -         |    -2.81 | executor, kinqie, Kiro, nota, tex1y |
|            1 |     3996 | 2024-02-26 | SAW             | L   | 0.127      | -            | -                | -                | -         |    -0.62 | executor, kinqie, Kiro, nota, tex1y |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($8,327.74)
- Divide that value by the 5th highest value among all rosters ($322,004.12)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-04 |      1.000 | $3,000.00      | $3,000.00       |
| 2024-06-09 |      0.820 | $6,500.00      | $5,327.74       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
