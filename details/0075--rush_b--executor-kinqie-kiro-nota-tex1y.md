### Roster Details<br />
Team Name: RUSH B<br />
Roster: executor, kinqie, Kiro, nota, tex1y<br />
Global Rank: [75](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [54]( ../standings_europe.md)<br />
<br />
Final Rank Value:  946.5<br />
<br />
Final Rank Value (946.5) = Starting Rank Value (861.3) + Head To Head Adjustments (85.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.387[<sup>1</sup>](#table2)
- Bounty Collected: 0.361[<sup>2</sup>](#table1)
- Opponent Network: 0.152[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.225<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 861.3
- 400 + ( ( 0.225 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 861.3


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
|           31 |       41 | 2024-08-04 | BC.Game         | L   | 1.000      | -            | -                | -                | -         |   -16.03 | executor, kinqie, Kiro, nota, tex1y |
|           30 |       79 | 2024-08-03 | Alliance        | W   | 1.000      | 0.342        | 0.017 (0.006)    | 0.291 (0.100)    | 0 (0.000) |    11.47 | executor, kinqie, Kiro, nota, tex1y |
|           29 |      117 | 2024-08-02 | Astralis Talent | W   | 1.000      | 0.342        | -                | 0.160 (0.055)    | 0 (0.000) |     6.59 | executor, kinqie, Kiro, nota, tex1y |
|           28 |      228 | 2024-07-30 | Rebels          | W   | 1.000      | 0.500        | 0.038 (0.019)    | 0.591 (0.296)    | 0 (0.000) |    19.57 | executor, kinqie, Kiro, nota, tex1y |
|           27 |      459 | 2024-07-23 | SINNERS         | W   | 1.000      | 0.500        | 0.037 (0.019)    | 0.808 (0.404)    | 0 (0.000) |    19.05 | executor, kinqie, Kiro, nota, tex1y |
|           26 |      583 | 2024-07-19 | SAW             | L   | 1.000      | -            | -                | -                | -         |    -5.29 | executor, kinqie, Kiro, nota, tex1y |
|           25 |      701 | 2024-07-17 | brazylijski luz | L   | 1.000      | -            | -                | -                | -         |   -19.04 | executor, kinqie, Kiro, nota, tex1y |
|           24 |      802 | 2024-07-15 | Sangal          | L   | 1.000      | -            | -                | -                | -         |    -5.32 | executor, kinqie, Kiro, nota, tex1y |
|           23 |     1212 | 2024-06-10 | PARIVISION      | L   | 0.823      | -            | -                | -                | -         |    -8.05 | executor, kinqie, Kiro, nota, tex1y |
|           22 |     1220 | 2024-06-10 | SAW             | L   | 0.823      | -            | -                | -                | -         |    -5.79 | executor, kinqie, Kiro, nota, tex1y |
|           21 |     1225 | 2024-06-10 | Monte           | W   | 0.823      | 0.143        | 0.080 (0.009)    | 0.611 (0.072)    | 0 (0.000) |    16.03 | executor, kinqie, Kiro, nota, tex1y |
|           20 |     1254 | 2024-06-09 | 9 Pandas        | W   | 0.817      | 0.143        | 0.081 (0.009)    | 0.717 (0.084)    | 0 (0.000) |    17.75 | executor, kinqie, Kiro, nota, tex1y |
|           19 |     1263 | 2024-06-09 | Aurora          | W   | 0.817      | 0.143        | 0.421 (0.049)    | 0.777 (0.091)    | 0 (0.000) |    24.63 | executor, kinqie, Kiro, nota, tex1y |
|           18 |     1270 | 2024-06-09 | SINNERS         | W   | 0.816      | 0.143        | 0.037 (0.004)    | 0.808 (0.094)    | 0 (0.000) |    18.17 | executor, kinqie, Kiro, nota, tex1y |
|           17 |     1281 | 2024-06-09 | 3DMAX           | L   | 0.816      | -            | -                | -                | -         |    -0.85 | executor, kinqie, Kiro, nota, tex1y |
|           16 |     1432 | 2024-06-06 | Aurora          | L   | 0.798      | -            | -                | -                | -         |    -0.65 | executor, kinqie, Kiro, nota, tex1y |
|           15 |     1495 | 2024-06-05 | SINNERS         | L   | 0.791      | -            | -                | -                | -         |    -7.63 | executor, kinqie, Kiro, nota, tex1y |
|           14 |     1543 | 2024-06-04 | SAW             | W   | 0.784      | 0.500        | 0.104 (0.041)    | 0.529 (0.208)    | 0 (0.000) |    21.16 | executor, kinqie, Kiro, nota, tex1y |
|           13 |     2341 | 2024-05-07 | MOUZ NXT        | L   | 0.597      | -            | -                | -                | -         |    -5.30 | executor, kinqie, Kiro, nota, tex1y |
|           12 |     2370 | 2024-05-05 | Sampi           | L   | 0.584      | -            | -                | -                | -         |    -7.94 | executor, kinqie, Kiro, nota, tex1y |
|           11 |     2391 | 2024-05-04 | HAVU            | W   | 0.577      | -            | -                | -                | 0 (0.000) |     5.18 | executor, kinqie, Kiro, nota, tex1y |
|           10 |     2436 | 2024-05-02 | EYEBALLERS      | L   | 0.563      | -            | -                | -                | -         |    -8.36 | executor, kinqie, Kiro, nota, tex1y |
|            9 |     2493 | 2024-04-29 | ENCE Academy    | W   | 0.545      | -            | -                | -                | -         |     5.07 | executor, kinqie, Kiro, nota, tex1y |
|            8 |     2996 | 2024-04-10 | KOI             | L   | 0.418      | -            | -                | -                | -         |    -3.21 | executor, kinqie, Kiro, nota, tex1y |
|            7 |     3050 | 2024-04-09 | PARIVISION      | W   | 0.411      | 0.500        | 0.017 (0.004)    | 0.565 (0.116)    | -         |    10.16 | executor, kinqie, Kiro, nota, tex1y |
|            6 |     3285 | 2024-04-01 | PERA            | L   | 0.357      | -            | -                | -                | -         |    -4.92 | executor, kinqie, Kiro, nota, tex1y |
|            5 |     3294 | 2024-03-31 | Monte           | W   | 0.351      | 0.500        | 0.057 (0.010)    | -                | -         |     7.30 | executor, kinqie, Kiro, nota, tex1y |
|            4 |     3306 | 2024-03-29 | System5         | W   | 0.338      | -            | -                | -                | -         |     2.79 | executor, kinqie, Kiro, nota, tex1y |
|            3 |     3623 | 2024-03-13 | Betera          | W   | 0.232      | -            | -                | -                | -         |     2.08 | executor, kinqie, Kiro, nota, tex1y |
|            2 |     3888 | 2024-03-03 | Metizport       | L   | 0.164      | -            | -                | -                | -         |    -2.78 | executor, kinqie, Kiro, nota, tex1y |
|            1 |     3999 | 2024-02-26 | SAW             | L   | 0.125      | -            | -                | -                | -         |    -0.61 | executor, kinqie, Kiro, nota, tex1y |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($8,313.30)
- Divide that value by the 5th highest value among all rosters ($321,345.23)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-04 |      1.000 | $3,000.00      | $3,000.00       |
| 2024-06-09 |      0.817 | $6,500.00      | $5,313.30       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
