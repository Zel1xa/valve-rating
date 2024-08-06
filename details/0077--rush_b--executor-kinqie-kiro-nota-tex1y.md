### Roster Details<br />
Team Name: RUSH B<br />
Roster: executor, kinqie, Kiro, nota, tex1y<br />
Global Rank: [77](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [56]( ../standings_europe.md)<br />
<br />
Final Rank Value:  947.0<br />
<br />
Final Rank Value (947.0) = Starting Rank Value (860.9) + Head To Head Adjustments (86.1)<br />

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
|           31 |       49 | 2024-08-04 | BC.Game         | L   | 1.000      | -            | -                | -                | -         |   -15.66 | executor, kinqie, Kiro, nota, tex1y |
|           30 |       87 | 2024-08-03 | Alliance        | W   | 1.000      | 0.342        | 0.017 (0.006)    | 0.283 (0.097)    | 0 (0.000) |    11.51 | executor, kinqie, Kiro, nota, tex1y |
|           29 |      125 | 2024-08-02 | Astralis Talent | W   | 1.000      | 0.342        | -                | 0.156 (0.054)    | 0 (0.000) |     6.62 | executor, kinqie, Kiro, nota, tex1y |
|           28 |      236 | 2024-07-30 | Rebels          | W   | 1.000      | 0.500        | 0.038 (0.019)    | 0.578 (0.289)    | 0 (0.000) |    19.60 | executor, kinqie, Kiro, nota, tex1y |
|           27 |      467 | 2024-07-23 | SINNERS         | W   | 1.000      | 0.500        | 0.037 (0.019)    | 0.790 (0.395)    | 0 (0.000) |    19.10 | executor, kinqie, Kiro, nota, tex1y |
|           26 |      591 | 2024-07-19 | SAW             | L   | 1.000      | -            | -                | -                | -         |    -5.31 | executor, kinqie, Kiro, nota, tex1y |
|           25 |      709 | 2024-07-17 | brazylijski luz | L   | 1.000      | -            | -                | -                | -         |   -19.04 | executor, kinqie, Kiro, nota, tex1y |
|           24 |      810 | 2024-07-15 | Sangal          | L   | 1.000      | -            | -                | -                | -         |    -5.30 | executor, kinqie, Kiro, nota, tex1y |
|           23 |     1220 | 2024-06-10 | PARIVISION      | L   | 0.821      | -            | -                | -                | -         |    -7.96 | executor, kinqie, Kiro, nota, tex1y |
|           22 |     1228 | 2024-06-10 | SAW             | L   | 0.820      | -            | -                | -                | -         |    -5.80 | executor, kinqie, Kiro, nota, tex1y |
|           21 |     1233 | 2024-06-10 | Monte           | W   | 0.820      | 0.143        | 0.080 (0.009)    | 0.598 (0.070)    | 0 (0.000) |    15.99 | executor, kinqie, Kiro, nota, tex1y |
|           20 |     1262 | 2024-06-09 | 9 Pandas        | W   | 0.814      | 0.143        | 0.081 (0.009)    | 0.700 (0.081)    | 0 (0.000) |    17.69 | executor, kinqie, Kiro, nota, tex1y |
|           19 |     1271 | 2024-06-09 | Aurora          | W   | 0.814      | 0.143        | 0.421 (0.049)    | 0.759 (0.088)    | 0 (0.000) |    24.56 | executor, kinqie, Kiro, nota, tex1y |
|           18 |     1278 | 2024-06-09 | SINNERS         | W   | 0.813      | 0.143        | 0.037 (0.004)    | 0.790 (0.092)    | 0 (0.000) |    18.13 | executor, kinqie, Kiro, nota, tex1y |
|           17 |     1289 | 2024-06-09 | 3DMAX           | L   | 0.813      | -            | -                | -                | -         |    -0.84 | executor, kinqie, Kiro, nota, tex1y |
|           16 |     1440 | 2024-06-06 | Aurora          | L   | 0.795      | -            | -                | -                | -         |    -0.64 | executor, kinqie, Kiro, nota, tex1y |
|           15 |     1503 | 2024-06-05 | SINNERS         | L   | 0.788      | -            | -                | -                | -         |    -7.58 | executor, kinqie, Kiro, nota, tex1y |
|           14 |     1551 | 2024-06-04 | SAW             | W   | 0.782      | 0.500        | 0.104 (0.041)    | 0.516 (0.202)    | 0 (0.000) |    21.05 | executor, kinqie, Kiro, nota, tex1y |
|           13 |     2349 | 2024-05-07 | MOUZ NXT        | L   | 0.594      | -            | -                | -                | -         |    -5.27 | executor, kinqie, Kiro, nota, tex1y |
|           12 |     2378 | 2024-05-05 | Sampi           | L   | 0.581      | -            | -                | -                | -         |    -7.91 | executor, kinqie, Kiro, nota, tex1y |
|           11 |     2399 | 2024-05-04 | HAVU            | W   | 0.574      | -            | -                | -                | 0 (0.000) |     5.15 | executor, kinqie, Kiro, nota, tex1y |
|           10 |     2444 | 2024-05-02 | EYEBALLERS      | L   | 0.560      | -            | -                | -                | -         |    -8.28 | executor, kinqie, Kiro, nota, tex1y |
|            9 |     2501 | 2024-04-29 | ENCE Academy    | W   | 0.542      | -            | -                | -                | -         |     5.05 | executor, kinqie, Kiro, nota, tex1y |
|            8 |     3004 | 2024-04-10 | KOI             | L   | 0.415      | -            | -                | -                | -         |    -3.22 | executor, kinqie, Kiro, nota, tex1y |
|            7 |     3058 | 2024-04-09 | PARIVISION      | W   | 0.409      | 0.500        | 0.017 (0.004)    | 0.590 (0.121)    | -         |    10.13 | executor, kinqie, Kiro, nota, tex1y |
|            6 |     3293 | 2024-04-01 | PERA            | L   | 0.355      | -            | -                | -                | -         |    -4.89 | executor, kinqie, Kiro, nota, tex1y |
|            5 |     3302 | 2024-03-31 | Monte           | W   | 0.348      | 0.500        | 0.057 (0.010)    | -                | -         |     7.24 | executor, kinqie, Kiro, nota, tex1y |
|            4 |     3314 | 2024-03-29 | System5         | W   | 0.336      | -            | -                | -                | -         |     2.77 | executor, kinqie, Kiro, nota, tex1y |
|            3 |     3631 | 2024-03-13 | Betera          | W   | 0.229      | -            | -                | -                | -         |     2.06 | executor, kinqie, Kiro, nota, tex1y |
|            2 |     3896 | 2024-03-03 | Metizport       | L   | 0.162      | -            | -                | -                | -         |    -2.25 | executor, kinqie, Kiro, nota, tex1y |
|            1 |     4007 | 2024-02-26 | SAW             | L   | 0.122      | -            | -                | -                | -         |    -0.61 | executor, kinqie, Kiro, nota, tex1y |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($8,295.24)
- Divide that value by the 5th highest value among all rosters ($320,521.62)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-04 |      1.000 | $3,000.00      | $3,000.00       |
| 2024-06-09 |      0.815 | $6,500.00      | $5,295.24       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
