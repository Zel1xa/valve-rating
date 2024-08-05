### Roster Details<br />
Team Name: MOUZ<br />
Roster: Brollan, Jimpphat, siuhy, torzsi, xertioN<br />
Global Rank: [4](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [4]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1869.8<br />
<br />
Final Rank Value (1869.8) = Starting Rank Value (1844.4) + Head To Head Adjustments (25.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 1.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.658[<sup>2</sup>](#table1)
- Opponent Network: 0.324[<sup>2</sup>](#table1)
- LAN Wins: 0.835[<sup>2</sup>](#table1)

The average of these factors is 0.704<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1844.4
- 400 + ( ( 0.704 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 1844.4


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
|           29 |      538 | 2024-07-20 | Natus Vincere      | L   | 1.000      | -            | -                | -                | -         |   -13.16 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           28 |      581 | 2024-07-19 | FURIA              | W   | 1.000      | 1.000        | 0.284 (0.284)    | 0.481 (0.481)    | 1 (1.000) |     5.70 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           27 |      718 | 2024-07-17 | Sashi              | W   | 1.000      | 1.000        | 0.184 (0.184)    | 0.983 (0.983)    | 1 (1.000) |     0.61 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           26 |     1717 | 2024-05-28 | G2                 | L   | 0.742      | -            | -                | -                | -         |   -10.21 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           25 |     1738 | 2024-05-27 | Complexity         | W   | 0.735      | 0.624        | -                | 0.373 (0.171)    | 1 (0.735) |     5.06 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           24 |     1747 | 2024-05-27 | 9z                 | L   | 0.734      | -            | -                | -                | -         |   -21.55 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           23 |     1966 | 2024-05-19 | Spirit             | W   | 0.679      | 0.769        | 1.000 (0.522)    | 0.452 (0.236)    | 1 (0.679) |    10.97 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           22 |     1994 | 2024-05-18 | HEROIC             | W   | 0.673      | 0.769        | -                | 0.365 (0.189)    | 1 (0.673) |     2.87 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           21 |     2073 | 2024-05-16 | Virtus.pro         | W   | 0.658      | 0.769        | 0.498 (0.252)    | -                | 1 (0.658) |     5.05 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           20 |     2178 | 2024-05-14 | BetBoom            | W   | 0.645      | 0.769        | -                | 0.529 (0.262)    | 1 (0.645) |     1.08 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           19 |     2221 | 2024-05-12 | Vitality           | W   | 0.633      | 0.889        | 0.648 (0.364)    | 0.376 (0.212)    | 1 (0.633) |     9.68 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           18 |     2243 | 2024-05-11 | Complexity         | W   | 0.627      | 0.889        | 0.342 (0.191)    | 0.373 (0.208)    | 1 (0.627) |     4.95 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           17 |     2291 | 2024-05-09 | G2                 | W   | 0.613      | 0.889        | 1.000 (0.545)    | 0.490 (0.267)    | 1 (0.613) |    11.92 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           16 |     2384 | 2024-05-04 | Liquid             | W   | 0.580      | 0.889        | 0.383 (0.198)    | 0.450 (0.232)    | -         |     3.42 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           15 |     2452 | 2024-05-01 | GamerLegion        | W   | 0.559      | -            | -                | -                | -         |     0.30 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           14 |     2483 | 2024-04-30 | Bad News Kangaroos | W   | 0.552      | -            | -                | -                | -         |     0.05 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           13 |     2903 | 2024-04-14 | FaZe               | L   | 0.445      | -            | -                | -                | -         |    -9.86 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           12 |     2920 | 2024-04-13 | G2                 | W   | 0.437      | 0.624        | 1.000 (0.273)    | -                | -         |     9.15 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           11 |     3016 | 2024-04-10 | Liquid             | W   | 0.418      | -            | -                | -                | -         |     2.58 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           10 |     3090 | 2024-04-08 | FURIA              | W   | 0.405      | -            | -                | -                | -         |     3.79 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            9 |     3101 | 2024-04-07 | TYLOO              | W   | 0.404      | -            | -                | -                | -         |     0.03 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            8 |     3302 | 2024-03-29 | G2                 | L   | 0.341      | -            | -                | -                | -         |    -3.37 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            7 |     3425 | 2024-03-22 | Complexity         | W   | 0.293      | -            | -                | -                | -         |     2.29 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            6 |     3445 | 2024-03-21 | Eternal Fire       | W   | 0.287      | 1.000        | 0.740 (0.212)    | -                | -         |     2.81 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            5 |     3455 | 2024-03-21 | Gaimin Gladiators  | W   | 0.285      | -            | -                | -                | -         |     0.07 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            4 |     4136 | 2024-02-20 | Spirit             | W   | 0.087      | -            | -                | -                | -         |     1.59 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            3 |     4158 | 2024-02-19 | Gaimin Gladiators  | W   | 0.080      | -            | -                | -                | -         |     0.02 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            2 |     4171 | 2024-02-19 | ex-Guild Eagles    | W   | 0.078      | -            | -                | -                | -         |     0.01 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            1 |     4366 | 2024-02-10 | FaZe               | L   | 0.020      | -            | -                | -                | -         |    -0.44 | Brollan, Jimpphat, siuhy, torzsi, xertioN |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($436,815.69)
- Divide that value by the 5th highest value among all rosters ($322,004.12)
- The final value (1.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-21 |      1.000 | $85,000.00     | $85,000.00      |
| 2024-06-02 |      0.774 | $5,000.00      | $3,868.06       |
| 2024-05-19 |      0.679 | $300,000.00    | $203,666.67     |
| 2024-05-12 |      0.633 | $170,000.00    | $107,572.22     |
| 2024-04-14 |      0.445 | $42,000.00     | $18,685.14      |
| 2024-03-31 |      0.354 | $45,000.00     | $15,912.50      |
| 2024-02-11 |      0.026 | $80,000.00     | $2,111.11       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
