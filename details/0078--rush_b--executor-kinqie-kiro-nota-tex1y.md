### Roster Details<br />
Team Name: RUSH B<br />
Roster: executor, kinqie, Kiro, nota, tex1y<br />
Global Rank: [78](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [57]( ../standings_europe.md)<br />
<br />
Final Rank Value:  946.9<br />
<br />
Final Rank Value (946.9) = Starting Rank Value (860.9) + Head To Head Adjustments (86.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.387[<sup>1</sup>](#table2)
- Bounty Collected: 0.361[<sup>2</sup>](#table1)
- Opponent Network: 0.149[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.224<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 860.9
- 400 + ( ( 0.224 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 860.9


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
|           31 |       50 | 2024-08-04 | BC.Game         | L   | 1.000      | -            | -                | -                | -         |   -15.61 | executor, kinqie, Kiro, nota, tex1y |
|           30 |       86 | 2024-08-03 | Alliance        | W   | 1.000      | 0.342        | 0.017 (0.006)    | 0.283 (0.097)    | 0 (0.000) |    11.51 | executor, kinqie, Kiro, nota, tex1y |
|           29 |      123 | 2024-08-02 | Astralis Talent | W   | 1.000      | 0.342        | -                | 0.156 (0.054)    | 0 (0.000) |     6.66 | executor, kinqie, Kiro, nota, tex1y |
|           28 |      234 | 2024-07-30 | Rebels          | W   | 1.000      | 0.500        | 0.038 (0.019)    | 0.578 (0.289)    | 0 (0.000) |    19.62 | executor, kinqie, Kiro, nota, tex1y |
|           27 |      465 | 2024-07-23 | SINNERS         | W   | 1.000      | 0.500        | 0.037 (0.019)    | 0.790 (0.395)    | 0 (0.000) |    19.02 | executor, kinqie, Kiro, nota, tex1y |
|           26 |      589 | 2024-07-19 | SAW             | L   | 1.000      | -            | -                | -                | -         |    -5.32 | executor, kinqie, Kiro, nota, tex1y |
|           25 |      707 | 2024-07-17 | brazylijski luz | L   | 1.000      | -            | -                | -                | -         |   -19.03 | executor, kinqie, Kiro, nota, tex1y |
|           24 |      808 | 2024-07-15 | Sangal          | L   | 1.000      | -            | -                | -                | -         |    -5.33 | executor, kinqie, Kiro, nota, tex1y |
|           23 |     1218 | 2024-06-10 | PARIVISION      | L   | 0.820      | -            | -                | -                | -         |    -7.95 | executor, kinqie, Kiro, nota, tex1y |
|           22 |     1226 | 2024-06-10 | SAW             | L   | 0.819      | -            | -                | -                | -         |    -5.80 | executor, kinqie, Kiro, nota, tex1y |
|           21 |     1231 | 2024-06-10 | Monte           | W   | 0.819      | 0.143        | 0.080 (0.009)    | 0.598 (0.070)    | 0 (0.000) |    15.98 | executor, kinqie, Kiro, nota, tex1y |
|           20 |     1260 | 2024-06-09 | 9 Pandas        | W   | 0.814      | 0.143        | 0.081 (0.009)    | 0.700 (0.081)    | 0 (0.000) |    17.68 | executor, kinqie, Kiro, nota, tex1y |
|           19 |     1269 | 2024-06-09 | Aurora          | W   | 0.813      | 0.143        | 0.420 (0.049)    | 0.759 (0.088)    | 0 (0.000) |    24.54 | executor, kinqie, Kiro, nota, tex1y |
|           18 |     1276 | 2024-06-09 | SINNERS         | W   | 0.813      | 0.143        | 0.037 (0.004)    | 0.790 (0.092)    | 0 (0.000) |    18.11 | executor, kinqie, Kiro, nota, tex1y |
|           17 |     1287 | 2024-06-09 | 3DMAX           | L   | 0.812      | -            | -                | -                | -         |    -0.84 | executor, kinqie, Kiro, nota, tex1y |
|           16 |     1438 | 2024-06-06 | Aurora          | L   | 0.794      | -            | -                | -                | -         |    -0.64 | executor, kinqie, Kiro, nota, tex1y |
|           15 |     1501 | 2024-06-05 | SINNERS         | L   | 0.788      | -            | -                | -                | -         |    -7.57 | executor, kinqie, Kiro, nota, tex1y |
|           14 |     1549 | 2024-06-04 | SAW             | W   | 0.781      | 0.500        | 0.104 (0.041)    | 0.516 (0.202)    | 0 (0.000) |    21.03 | executor, kinqie, Kiro, nota, tex1y |
|           13 |     2347 | 2024-05-07 | MOUZ NXT        | L   | 0.593      | -            | -                | -                | -         |    -5.27 | executor, kinqie, Kiro, nota, tex1y |
|           12 |     2376 | 2024-05-05 | Sampi           | L   | 0.581      | -            | -                | -                | -         |    -7.90 | executor, kinqie, Kiro, nota, tex1y |
|           11 |     2397 | 2024-05-04 | HAVU            | W   | 0.574      | -            | -                | -                | 0 (0.000) |     5.14 | executor, kinqie, Kiro, nota, tex1y |
|           10 |     2442 | 2024-05-02 | EYEBALLERS      | L   | 0.560      | -            | -                | -                | -         |    -8.27 | executor, kinqie, Kiro, nota, tex1y |
|            9 |     2499 | 2024-04-29 | ENCE Academy    | W   | 0.542      | -            | -                | -                | -         |     5.04 | executor, kinqie, Kiro, nota, tex1y |
|            8 |     3002 | 2024-04-10 | KOI             | L   | 0.415      | -            | -                | -                | -         |    -3.21 | executor, kinqie, Kiro, nota, tex1y |
|            7 |     3056 | 2024-04-09 | PARIVISION      | W   | 0.408      | 0.500        | 0.017 (0.004)    | 0.590 (0.120)    | -         |    10.11 | executor, kinqie, Kiro, nota, tex1y |
|            6 |     3291 | 2024-04-01 | PERA            | L   | 0.354      | -            | -                | -                | -         |    -4.88 | executor, kinqie, Kiro, nota, tex1y |
|            5 |     3300 | 2024-03-31 | Monte           | W   | 0.347      | 0.500        | 0.057 (0.010)    | -                | -         |     7.22 | executor, kinqie, Kiro, nota, tex1y |
|            4 |     3312 | 2024-03-29 | System5         | W   | 0.335      | -            | -                | -                | -         |     2.76 | executor, kinqie, Kiro, nota, tex1y |
|            3 |     3629 | 2024-03-13 | Betera          | W   | 0.228      | -            | -                | -                | -         |     2.05 | executor, kinqie, Kiro, nota, tex1y |
|            2 |     3894 | 2024-03-03 | Metizport       | L   | 0.161      | -            | -                | -                | -         |    -2.24 | executor, kinqie, Kiro, nota, tex1y |
|            1 |     4005 | 2024-02-26 | SAW             | L   | 0.122      | -            | -                | -                | -         |    -0.60 | executor, kinqie, Kiro, nota, tex1y |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($8,291.03)
- Divide that value by the 5th highest value among all rosters ($320,329.44)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-04 |      1.000 | $3,000.00      | $3,000.00       |
| 2024-06-09 |      0.814 | $6,500.00      | $5,291.03       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
