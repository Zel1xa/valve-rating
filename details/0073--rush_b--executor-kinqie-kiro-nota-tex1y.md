### Roster Details<br />
Team Name: RUSH B<br />
Roster: executor, kinqie, Kiro, nota, tex1y<br />
Global Rank: [73](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [51]( ../standings_europe.md)<br />
<br />
Final Rank Value:  946.2<br />
<br />
Final Rank Value (946.2) = Starting Rank Value (860.6) + Head To Head Adjustments (85.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.386[<sup>1</sup>](#table2)
- Bounty Collected: 0.362[<sup>2</sup>](#table1)
- Opponent Network: 0.153[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.225<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 860.6
- 400 + ( ( 0.225 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 860.6


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
|           31 |       14 | 2024-08-04 | BC.Game         | L   | 1.000      | -            | -                | -                | -         |   -16.18 | executor, kinqie, Kiro, nota, tex1y |
|           30 |       51 | 2024-08-03 | Alliance        | W   | 1.000      | 0.342        | 0.017 (0.006)    | 0.299 (0.103)    | 0 (0.000) |    11.48 | executor, kinqie, Kiro, nota, tex1y |
|           29 |       89 | 2024-08-02 | Astralis Talent | W   | 1.000      | 0.342        | -                | 0.162 (0.056)    | 0 (0.000) |     6.59 | executor, kinqie, Kiro, nota, tex1y |
|           28 |      200 | 2024-07-30 | Rebels          | W   | 1.000      | 0.500        | 0.038 (0.019)    | 0.600 (0.300)    | 0 (0.000) |    19.58 | executor, kinqie, Kiro, nota, tex1y |
|           27 |      431 | 2024-07-23 | SINNERS         | W   | 1.000      | 0.500        | 0.037 (0.019)    | 0.797 (0.398)    | 0 (0.000) |    18.86 | executor, kinqie, Kiro, nota, tex1y |
|           26 |      555 | 2024-07-19 | SAW             | L   | 1.000      | -            | -                | -                | -         |    -5.25 | executor, kinqie, Kiro, nota, tex1y |
|           25 |      673 | 2024-07-17 | brazylijski luz | L   | 1.000      | -            | -                | -                | -         |   -19.00 | executor, kinqie, Kiro, nota, tex1y |
|           24 |      774 | 2024-07-15 | Sangal          | L   | 1.000      | -            | -                | -                | -         |    -5.37 | executor, kinqie, Kiro, nota, tex1y |
|           23 |     1184 | 2024-06-10 | PARIVISION      | L   | 0.832      | -            | -                | -                | -         |    -8.26 | executor, kinqie, Kiro, nota, tex1y |
|           22 |     1192 | 2024-06-10 | SAW             | L   | 0.832      | -            | -                | -                | -         |    -5.81 | executor, kinqie, Kiro, nota, tex1y |
|           21 |     1197 | 2024-06-10 | Monte           | W   | 0.832      | 0.143        | 0.080 (0.010)    | 0.619 (0.074)    | 0 (0.000) |    16.18 | executor, kinqie, Kiro, nota, tex1y |
|           20 |     1226 | 2024-06-09 | 9 Pandas        | W   | 0.826      | 0.143        | 0.081 (0.010)    | 0.690 (0.081)    | 0 (0.000) |    17.96 | executor, kinqie, Kiro, nota, tex1y |
|           19 |     1235 | 2024-06-09 | Aurora          | W   | 0.826      | 0.143        | 0.423 (0.050)    | 0.793 (0.093)    | 0 (0.000) |    24.86 | executor, kinqie, Kiro, nota, tex1y |
|           18 |     1242 | 2024-06-09 | SINNERS         | W   | 0.825      | 0.143        | 0.037 (0.004)    | 0.797 (0.094)    | 0 (0.000) |    18.27 | executor, kinqie, Kiro, nota, tex1y |
|           17 |     1253 | 2024-06-09 | 3DMAX           | L   | 0.825      | -            | -                | -                | -         |    -0.89 | executor, kinqie, Kiro, nota, tex1y |
|           16 |     1404 | 2024-06-06 | Aurora          | L   | 0.807      | -            | -                | -                | -         |    -0.68 | executor, kinqie, Kiro, nota, tex1y |
|           15 |     1467 | 2024-06-05 | SINNERS         | L   | 0.800      | -            | -                | -                | -         |    -7.82 | executor, kinqie, Kiro, nota, tex1y |
|           14 |     1515 | 2024-06-04 | SAW             | W   | 0.793      | 0.500        | 0.105 (0.042)    | 0.540 (0.214)    | 0 (0.000) |    21.47 | executor, kinqie, Kiro, nota, tex1y |
|           13 |     2313 | 2024-05-07 | MOUZ NXT        | L   | 0.606      | -            | -                | -                | -         |    -5.42 | executor, kinqie, Kiro, nota, tex1y |
|           12 |     2342 | 2024-05-05 | Sampi           | L   | 0.593      | -            | -                | -                | -         |    -8.04 | executor, kinqie, Kiro, nota, tex1y |
|           11 |     2363 | 2024-05-04 | HAVU            | W   | 0.586      | -            | -                | -                | 0 (0.000) |     5.28 | executor, kinqie, Kiro, nota, tex1y |
|           10 |     2408 | 2024-05-02 | EYEBALLERS      | L   | 0.572      | -            | -                | -                | -         |    -8.49 | executor, kinqie, Kiro, nota, tex1y |
|            9 |     2465 | 2024-04-29 | ENCE Academy    | W   | 0.554      | -            | -                | -                | -         |     5.19 | executor, kinqie, Kiro, nota, tex1y |
|            8 |     2968 | 2024-04-10 | KOI             | L   | 0.427      | -            | -                | -                | -         |    -3.24 | executor, kinqie, Kiro, nota, tex1y |
|            7 |     3022 | 2024-04-09 | PARIVISION      | W   | 0.420      | 0.500        | 0.017 (0.004)    | 0.534 (0.112)    | -         |    10.32 | executor, kinqie, Kiro, nota, tex1y |
|            6 |     3257 | 2024-04-01 | PERA            | L   | 0.367      | -            | -                | -                | -         |    -5.05 | executor, kinqie, Kiro, nota, tex1y |
|            5 |     3266 | 2024-03-31 | Monte           | W   | 0.360      | 0.500        | 0.057 (0.010)    | -                | -         |     7.54 | executor, kinqie, Kiro, nota, tex1y |
|            4 |     3278 | 2024-03-29 | System5         | W   | 0.347      | -            | -                | -                | -         |     2.87 | executor, kinqie, Kiro, nota, tex1y |
|            3 |     3595 | 2024-03-13 | Betera          | W   | 0.241      | -            | -                | -                | -         |     2.16 | executor, kinqie, Kiro, nota, tex1y |
|            2 |     3860 | 2024-03-03 | Metizport       | L   | 0.173      | -            | -                | -                | -         |    -2.92 | executor, kinqie, Kiro, nota, tex1y |
|            1 |     3971 | 2024-02-26 | SAW             | L   | 0.134      | -            | -                | -                | -         |    -0.65 | executor, kinqie, Kiro, nota, tex1y |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($8,372.13)
- Divide that value by the 5th highest value among all rosters ($324,028.83)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-04 |      1.000 | $3,000.00      | $3,000.00       |
| 2024-06-09 |      0.826 | $6,500.00      | $5,372.13       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
