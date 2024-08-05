### Roster Details<br />
Team Name: RUSH B<br />
Roster: executor, kinqie, Kiro, nota, tex1y<br />
Global Rank: [73](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [51]( ../standings_europe.md)<br />
<br />
Final Rank Value:  945.9<br />
<br />
Final Rank Value (945.9) = Starting Rank Value (860.5) + Head To Head Adjustments (85.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.386[<sup>1</sup>](#table2)
- Bounty Collected: 0.362[<sup>2</sup>](#table1)
- Opponent Network: 0.152[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.225<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 860.5
- 400 + ( ( 0.225 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 860.5


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
|           31 |       18 | 2024-08-04 | BC.Game         | L   | 1.000      | -            | -                | -                | -         |   -16.17 | executor, kinqie, Kiro, nota, tex1y |
|           30 |       55 | 2024-08-03 | Alliance        | W   | 1.000      | 0.342        | 0.017 (0.006)    | 0.298 (0.102)    | 0 (0.000) |    11.48 | executor, kinqie, Kiro, nota, tex1y |
|           29 |       93 | 2024-08-02 | Astralis Talent | W   | 1.000      | 0.342        | -                | 0.163 (0.056)    | 0 (0.000) |     6.60 | executor, kinqie, Kiro, nota, tex1y |
|           28 |      204 | 2024-07-30 | Rebels          | W   | 1.000      | 0.500        | 0.038 (0.019)    | 0.600 (0.300)    | 0 (0.000) |    19.58 | executor, kinqie, Kiro, nota, tex1y |
|           27 |      435 | 2024-07-23 | SINNERS         | W   | 1.000      | 0.500        | 0.037 (0.019)    | 0.797 (0.398)    | 0 (0.000) |    18.88 | executor, kinqie, Kiro, nota, tex1y |
|           26 |      559 | 2024-07-19 | SAW             | L   | 1.000      | -            | -                | -                | -         |    -5.26 | executor, kinqie, Kiro, nota, tex1y |
|           25 |      677 | 2024-07-17 | brazylijski luz | L   | 1.000      | -            | -                | -                | -         |   -19.00 | executor, kinqie, Kiro, nota, tex1y |
|           24 |      778 | 2024-07-15 | Sangal          | L   | 1.000      | -            | -                | -                | -         |    -5.37 | executor, kinqie, Kiro, nota, tex1y |
|           23 |     1188 | 2024-06-10 | PARIVISION      | L   | 0.830      | -            | -                | -                | -         |    -8.22 | executor, kinqie, Kiro, nota, tex1y |
|           22 |     1196 | 2024-06-10 | SAW             | L   | 0.830      | -            | -                | -                | -         |    -5.80 | executor, kinqie, Kiro, nota, tex1y |
|           21 |     1201 | 2024-06-10 | Monte           | W   | 0.829      | 0.143        | 0.080 (0.009)    | 0.619 (0.073)    | 0 (0.000) |    16.14 | executor, kinqie, Kiro, nota, tex1y |
|           20 |     1230 | 2024-06-09 | 9 Pandas        | W   | 0.824      | 0.143        | 0.081 (0.010)    | 0.690 (0.081)    | 0 (0.000) |    17.89 | executor, kinqie, Kiro, nota, tex1y |
|           19 |     1239 | 2024-06-09 | Aurora          | W   | 0.823      | 0.143        | 0.423 (0.050)    | 0.792 (0.093)    | 0 (0.000) |    24.80 | executor, kinqie, Kiro, nota, tex1y |
|           18 |     1246 | 2024-06-09 | SINNERS         | W   | 0.823      | 0.143        | 0.037 (0.004)    | 0.797 (0.094)    | 0 (0.000) |    18.23 | executor, kinqie, Kiro, nota, tex1y |
|           17 |     1257 | 2024-06-09 | 3DMAX           | L   | 0.823      | -            | -                | -                | -         |    -0.88 | executor, kinqie, Kiro, nota, tex1y |
|           16 |     1408 | 2024-06-06 | Aurora          | L   | 0.804      | -            | -                | -                | -         |    -0.67 | executor, kinqie, Kiro, nota, tex1y |
|           15 |     1471 | 2024-06-05 | SINNERS         | L   | 0.798      | -            | -                | -                | -         |    -7.79 | executor, kinqie, Kiro, nota, tex1y |
|           14 |     1519 | 2024-06-04 | SAW             | W   | 0.791      | 0.500        | 0.105 (0.041)    | 0.539 (0.213)    | 0 (0.000) |    21.39 | executor, kinqie, Kiro, nota, tex1y |
|           13 |     2317 | 2024-05-07 | MOUZ NXT        | L   | 0.603      | -            | -                | -                | -         |    -5.40 | executor, kinqie, Kiro, nota, tex1y |
|           12 |     2346 | 2024-05-05 | Sampi           | L   | 0.591      | -            | -                | -                | -         |    -8.01 | executor, kinqie, Kiro, nota, tex1y |
|           11 |     2367 | 2024-05-04 | HAVU            | W   | 0.584      | -            | -                | -                | 0 (0.000) |     5.26 | executor, kinqie, Kiro, nota, tex1y |
|           10 |     2412 | 2024-05-02 | EYEBALLERS      | L   | 0.570      | -            | -                | -                | -         |    -8.46 | executor, kinqie, Kiro, nota, tex1y |
|            9 |     2469 | 2024-04-29 | ENCE Academy    | W   | 0.552      | -            | -                | -                | -         |     5.16 | executor, kinqie, Kiro, nota, tex1y |
|            8 |     2972 | 2024-04-10 | KOI             | L   | 0.425      | -            | -                | -                | -         |    -3.23 | executor, kinqie, Kiro, nota, tex1y |
|            7 |     3026 | 2024-04-09 | PARIVISION      | W   | 0.418      | 0.500        | 0.017 (0.004)    | 0.534 (0.112)    | -         |    10.27 | executor, kinqie, Kiro, nota, tex1y |
|            6 |     3261 | 2024-04-01 | PERA            | L   | 0.364      | -            | -                | -                | -         |    -5.01 | executor, kinqie, Kiro, nota, tex1y |
|            5 |     3270 | 2024-03-31 | Monte           | W   | 0.357      | 0.500        | 0.057 (0.010)    | -                | -         |     7.48 | executor, kinqie, Kiro, nota, tex1y |
|            4 |     3282 | 2024-03-29 | System5         | W   | 0.345      | -            | -                | -                | -         |     2.85 | executor, kinqie, Kiro, nota, tex1y |
|            3 |     3599 | 2024-03-13 | Betera          | W   | 0.238      | -            | -                | -                | -         |     2.14 | executor, kinqie, Kiro, nota, tex1y |
|            2 |     3864 | 2024-03-03 | Metizport       | L   | 0.171      | -            | -                | -                | -         |    -2.88 | executor, kinqie, Kiro, nota, tex1y |
|            1 |     3975 | 2024-02-26 | SAW             | L   | 0.132      | -            | -                | -                | -         |    -0.64 | executor, kinqie, Kiro, nota, tex1y |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($8,356.63)
- Divide that value by the 5th highest value among all rosters ($323,321.90)
- The final value (0.03) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-04 |      1.000 | $3,000.00      | $3,000.00       |
| 2024-06-09 |      0.824 | $6,500.00      | $5,356.63       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
