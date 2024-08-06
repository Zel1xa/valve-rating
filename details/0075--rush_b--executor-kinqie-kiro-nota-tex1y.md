### Roster Details<br />
Team Name: RUSH B<br />
Roster: executor, kinqie, Kiro, nota, tex1y<br />
Global Rank: [75](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [54]( ../standings_europe.md)<br />
<br />
Final Rank Value:  946.3<br />
<br />
Final Rank Value (946.3) = Starting Rank Value (861.2) + Head To Head Adjustments (85.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.387[<sup>1</sup>](#table2)
- Bounty Collected: 0.361[<sup>2</sup>](#table1)
- Opponent Network: 0.151[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.225<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 861.2
- 400 + ( ( 0.225 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 861.2


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
|           31 |       45 | 2024-08-04 | BC.Game         | L   | 1.000      | -            | -                | -                | -         |   -16.01 | executor, kinqie, Kiro, nota, tex1y |
|           30 |       83 | 2024-08-03 | Alliance        | W   | 1.000      | 0.342        | 0.017 (0.006)    | 0.289 (0.099)    | 0 (0.000) |    11.47 | executor, kinqie, Kiro, nota, tex1y |
|           29 |      121 | 2024-08-02 | Astralis Talent | W   | 1.000      | 0.342        | -                | 0.160 (0.055)    | 0 (0.000) |     6.60 | executor, kinqie, Kiro, nota, tex1y |
|           28 |      232 | 2024-07-30 | Rebels          | W   | 1.000      | 0.500        | 0.038 (0.019)    | 0.591 (0.295)    | 0 (0.000) |    19.60 | executor, kinqie, Kiro, nota, tex1y |
|           27 |      463 | 2024-07-23 | SINNERS         | W   | 1.000      | 0.500        | 0.037 (0.019)    | 0.808 (0.404)    | 0 (0.000) |    19.07 | executor, kinqie, Kiro, nota, tex1y |
|           26 |      587 | 2024-07-19 | SAW             | L   | 1.000      | -            | -                | -                | -         |    -5.30 | executor, kinqie, Kiro, nota, tex1y |
|           25 |      705 | 2024-07-17 | brazylijski luz | L   | 1.000      | -            | -                | -                | -         |   -19.04 | executor, kinqie, Kiro, nota, tex1y |
|           24 |      806 | 2024-07-15 | Sangal          | L   | 1.000      | -            | -                | -                | -         |    -5.30 | executor, kinqie, Kiro, nota, tex1y |
|           23 |     1216 | 2024-06-10 | PARIVISION      | L   | 0.821      | -            | -                | -                | -         |    -7.99 | executor, kinqie, Kiro, nota, tex1y |
|           22 |     1224 | 2024-06-10 | SAW             | L   | 0.820      | -            | -                | -                | -         |    -5.79 | executor, kinqie, Kiro, nota, tex1y |
|           21 |     1229 | 2024-06-10 | Monte           | W   | 0.820      | 0.143        | 0.080 (0.009)    | 0.611 (0.072)    | 0 (0.000) |    16.02 | executor, kinqie, Kiro, nota, tex1y |
|           20 |     1258 | 2024-06-09 | 9 Pandas        | W   | 0.815      | 0.143        | 0.081 (0.009)    | 0.716 (0.083)    | 0 (0.000) |    17.69 | executor, kinqie, Kiro, nota, tex1y |
|           19 |     1267 | 2024-06-09 | Aurora          | W   | 0.814      | 0.143        | 0.421 (0.049)    | 0.776 (0.090)    | 0 (0.000) |    24.56 | executor, kinqie, Kiro, nota, tex1y |
|           18 |     1274 | 2024-06-09 | SINNERS         | W   | 0.814      | 0.143        | 0.037 (0.004)    | 0.808 (0.094)    | 0 (0.000) |    18.13 | executor, kinqie, Kiro, nota, tex1y |
|           17 |     1285 | 2024-06-09 | 3DMAX           | L   | 0.813      | -            | -                | -                | -         |    -0.84 | executor, kinqie, Kiro, nota, tex1y |
|           16 |     1436 | 2024-06-06 | Aurora          | L   | 0.795      | -            | -                | -                | -         |    -0.64 | executor, kinqie, Kiro, nota, tex1y |
|           15 |     1499 | 2024-06-05 | SINNERS         | L   | 0.789      | -            | -                | -                | -         |    -7.59 | executor, kinqie, Kiro, nota, tex1y |
|           14 |     1547 | 2024-06-04 | SAW             | W   | 0.782      | 0.500        | 0.104 (0.041)    | 0.528 (0.206)    | 0 (0.000) |    21.07 | executor, kinqie, Kiro, nota, tex1y |
|           13 |     2345 | 2024-05-07 | MOUZ NXT        | L   | 0.594      | -            | -                | -                | -         |    -5.27 | executor, kinqie, Kiro, nota, tex1y |
|           12 |     2374 | 2024-05-05 | Sampi           | L   | 0.582      | -            | -                | -                | -         |    -7.89 | executor, kinqie, Kiro, nota, tex1y |
|           11 |     2395 | 2024-05-04 | HAVU            | W   | 0.575      | -            | -                | -                | 0 (0.000) |     5.15 | executor, kinqie, Kiro, nota, tex1y |
|           10 |     2440 | 2024-05-02 | EYEBALLERS      | L   | 0.561      | -            | -                | -                | -         |    -8.31 | executor, kinqie, Kiro, nota, tex1y |
|            9 |     2497 | 2024-04-29 | ENCE Academy    | W   | 0.542      | -            | -                | -                | -         |     5.04 | executor, kinqie, Kiro, nota, tex1y |
|            8 |     3000 | 2024-04-10 | KOI             | L   | 0.416      | -            | -                | -                | -         |    -3.21 | executor, kinqie, Kiro, nota, tex1y |
|            7 |     3054 | 2024-04-09 | PARIVISION      | W   | 0.409      | 0.500        | 0.017 (0.004)    | 0.564 (0.115)    | -         |    10.11 | executor, kinqie, Kiro, nota, tex1y |
|            6 |     3289 | 2024-04-01 | PERA            | L   | 0.355      | -            | -                | -                | -         |    -4.89 | executor, kinqie, Kiro, nota, tex1y |
|            5 |     3298 | 2024-03-31 | Monte           | W   | 0.348      | 0.500        | 0.057 (0.010)    | -                | -         |     7.24 | executor, kinqie, Kiro, nota, tex1y |
|            4 |     3310 | 2024-03-29 | System5         | W   | 0.336      | -            | -                | -                | -         |     2.77 | executor, kinqie, Kiro, nota, tex1y |
|            3 |     3627 | 2024-03-13 | Betera          | W   | 0.229      | -            | -                | -                | -         |     2.06 | executor, kinqie, Kiro, nota, tex1y |
|            2 |     3892 | 2024-03-03 | Metizport       | L   | 0.162      | -            | -                | -                | -         |    -2.74 | executor, kinqie, Kiro, nota, tex1y |
|            1 |     4003 | 2024-02-26 | SAW             | L   | 0.122      | -            | -                | -                | -         |    -0.60 | executor, kinqie, Kiro, nota, tex1y |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($8,297.05)
- Divide that value by the 5th highest value among all rosters ($320,603.98)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-04 |      1.000 | $3,000.00      | $3,000.00       |
| 2024-06-09 |      0.815 | $6,500.00      | $5,297.05       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
