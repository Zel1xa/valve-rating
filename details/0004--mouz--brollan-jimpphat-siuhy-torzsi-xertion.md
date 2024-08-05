### Roster Details<br />
Team Name: MOUZ<br />
Roster: Brollan, Jimpphat, siuhy, torzsi, xertioN<br />
Global Rank: [4](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [4]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1869.7<br />
<br />
Final Rank Value (1869.7) = Starting Rank Value (1844.3) + Head To Head Adjustments (25.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 1.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.658[<sup>2</sup>](#table1)
- Opponent Network: 0.324[<sup>2</sup>](#table1)
- LAN Wins: 0.835[<sup>2</sup>](#table1)

The average of these factors is 0.704<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1844.3
- 400 + ( ( 0.704 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 1844.3


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent           | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                    |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           29 |      539 | 2024-07-20 | Natus Vincere      | L   | 1.000      | -            | -                | -                | -         |   -13.15 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           28 |      582 | 2024-07-19 | FURIA              | W   | 1.000      | 1.000        | 0.284 (0.284)    | 0.481 (0.481)    | 1 (1.000) |     5.71 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           27 |      719 | 2024-07-17 | Sashi              | W   | 1.000      | 1.000        | 0.184 (0.184)    | 0.983 (0.983)    | 1 (1.000) |     0.62 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           26 |     1718 | 2024-05-28 | G2                 | L   | 0.742      | -            | -                | -                | -         |   -10.20 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           25 |     1739 | 2024-05-27 | Complexity         | W   | 0.735      | 0.624        | -                | 0.373 (0.171)    | 1 (0.735) |     5.06 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           24 |     1748 | 2024-05-27 | 9z                 | L   | 0.733      | -            | -                | -                | -         |   -21.54 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           23 |     1967 | 2024-05-19 | Spirit             | W   | 0.678      | 0.769        | 1.000 (0.521)    | 0.452 (0.236)    | 1 (0.678) |    10.96 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           22 |     1995 | 2024-05-18 | HEROIC             | W   | 0.672      | 0.769        | -                | 0.365 (0.189)    | 1 (0.672) |     2.87 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           21 |     2074 | 2024-05-16 | Virtus.pro         | W   | 0.658      | 0.769        | 0.498 (0.252)    | -                | 1 (0.658) |     5.05 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           20 |     2179 | 2024-05-14 | BetBoom            | W   | 0.645      | 0.769        | -                | 0.529 (0.262)    | 1 (0.645) |     1.08 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           19 |     2222 | 2024-05-12 | Vitality           | W   | 0.632      | 0.889        | 0.648 (0.364)    | 0.376 (0.211)    | 1 (0.632) |     9.68 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           18 |     2244 | 2024-05-11 | Complexity         | W   | 0.627      | 0.889        | 0.342 (0.190)    | 0.373 (0.208)    | 1 (0.627) |     4.95 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           17 |     2292 | 2024-05-09 | G2                 | W   | 0.613      | 0.889        | 1.000 (0.545)    | 0.490 (0.267)    | 1 (0.613) |    11.92 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           16 |     2385 | 2024-05-04 | Liquid             | W   | 0.580      | 0.889        | 0.383 (0.198)    | 0.450 (0.232)    | -         |     3.42 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           15 |     2453 | 2024-05-01 | GamerLegion        | W   | 0.559      | -            | -                | -                | -         |     0.30 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           14 |     2484 | 2024-04-30 | Bad News Kangaroos | W   | 0.551      | -            | -                | -                | -         |     0.05 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           13 |     2904 | 2024-04-14 | FaZe               | L   | 0.444      | -            | -                | -                | -         |    -9.85 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           12 |     2921 | 2024-04-13 | G2                 | W   | 0.437      | 0.624        | 1.000 (0.273)    | -                | -         |     9.15 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           11 |     3017 | 2024-04-10 | Liquid             | W   | 0.417      | -            | -                | -                | -         |     2.58 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           10 |     3091 | 2024-04-08 | FURIA              | W   | 0.405      | -            | -                | -                | -         |     3.79 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            9 |     3102 | 2024-04-07 | TYLOO              | W   | 0.403      | -            | -                | -                | -         |     0.03 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            8 |     3303 | 2024-03-29 | G2                 | L   | 0.340      | -            | -                | -                | -         |    -3.36 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            7 |     3426 | 2024-03-22 | Complexity         | W   | 0.292      | -            | -                | -                | -         |     2.29 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            6 |     3446 | 2024-03-21 | Eternal Fire       | W   | 0.286      | 1.000        | 0.740 (0.212)    | -                | -         |     2.80 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            5 |     3456 | 2024-03-21 | Gaimin Gladiators  | W   | 0.285      | -            | -                | -                | -         |     0.07 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            4 |     4137 | 2024-02-20 | Spirit             | W   | 0.086      | -            | -                | -                | -         |     1.59 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            3 |     4159 | 2024-02-19 | Gaimin Gladiators  | W   | 0.080      | -            | -                | -                | -         |     0.02 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            2 |     4172 | 2024-02-19 | ex-Guild Eagles    | W   | 0.078      | -            | -                | -                | -         |     0.01 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            1 |     4367 | 2024-02-10 | FaZe               | L   | 0.019      | -            | -                | -                | -         |    -0.43 | Brollan, Jimpphat, siuhy, torzsi, xertioN |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($436,548.19)
- Divide that value by the 5th highest value among all rosters ($321,880.58)
- The final value (1.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-21 |      1.000 | $85,000.00     | $85,000.00      |
| 2024-06-02 |      0.773 | $5,000.00      | $3,865.97       |
| 2024-05-19 |      0.678 | $300,000.00    | $203,541.67     |
| 2024-05-12 |      0.632 | $170,000.00    | $107,501.39     |
| 2024-04-14 |      0.444 | $42,000.00     | $18,667.64      |
| 2024-03-31 |      0.353 | $45,000.00     | $15,893.75      |
| 2024-02-11 |      0.026 | $80,000.00     | $2,077.78       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
