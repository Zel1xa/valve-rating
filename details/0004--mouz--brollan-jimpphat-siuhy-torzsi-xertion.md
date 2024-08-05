### Roster Details<br />
Team Name: MOUZ<br />
Roster: Brollan, Jimpphat, siuhy, torzsi, xertioN<br />
Global Rank: [4](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [4]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1895.0<br />
<br />
Final Rank Value (1895.0) = Starting Rank Value (1877.4) + Head To Head Adjustments (17.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 1.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.668[<sup>2</sup>](#table1)
- Opponent Network: 0.333[<sup>2</sup>](#table1)
- LAN Wins: 0.865[<sup>2</sup>](#table1)

The average of these factors is 0.716<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1877.4
- 400 + ( ( 0.716 - 0.000 ) / ( 0.776 - 0.000 ) ) * 1600 = 1877.4


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
|           32 |      364 | 2024-07-20 | Natus Vincere      | L   | 1.000      | -            | -                | -                | -         |   -13.62 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           31 |      407 | 2024-07-19 | FURIA              | W   | 1.000      | 1.000        | 0.284 (0.284)    | 0.495 (0.495)    | 1 (1.000) |     5.29 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           30 |      544 | 2024-07-17 | Sashi              | W   | 1.000      | 1.000        | 0.185 (0.185)    | 0.973 (0.973)    | 1 (1.000) |     0.55 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           29 |     1543 | 2024-05-28 | G2                 | L   | 0.774      | -            | -                | -                | -         |   -11.61 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           28 |     1564 | 2024-05-27 | Complexity         | W   | 0.768      | 0.624        | -                | 0.367 (0.176)    | 1 (0.768) |     4.72 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           27 |     1573 | 2024-05-27 | 9z                 | L   | 0.766      | -            | -                | -                | -         |   -22.61 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           26 |     1792 | 2024-05-19 | Spirit             | W   | 0.711      | 0.769        | 1.000 (0.547)    | 0.424 (0.232)    | 1 (0.711) |    11.03 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           25 |     1820 | 2024-05-18 | HEROIC             | W   | 0.705      | 0.769        | -                | 0.382 (0.207)    | 1 (0.705) |     2.92 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           24 |     1899 | 2024-05-16 | Virtus.pro         | W   | 0.691      | 0.769        | 0.494 (0.262)    | -                | 1 (0.691) |     5.25 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           23 |     2004 | 2024-05-14 | BetBoom            | W   | 0.678      | 0.769        | -                | 0.554 (0.288)    | 1 (0.678) |     1.07 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           22 |     2047 | 2024-05-12 | Vitality           | W   | 0.665      | 0.889        | 0.654 (0.387)    | 0.385 (0.228)    | 1 (0.665) |     9.61 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           21 |     2069 | 2024-05-11 | Complexity         | W   | 0.659      | 0.889        | 0.348 (0.204)    | 0.367 (0.215)    | 1 (0.659) |     4.71 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           20 |     2117 | 2024-05-09 | G2                 | W   | 0.646      | 0.889        | 1.000 (0.574)    | 0.492 (0.283)    | 1 (0.646) |    11.68 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           19 |     2210 | 2024-05-04 | Liquid             | W   | 0.613      | 0.889        | 0.387 (0.211)    | 0.430 (0.234)    | -         |     1.90 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           18 |     2278 | 2024-05-01 | GamerLegion        | W   | 0.592      | -            | -                | -                | -         |     0.29 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           17 |     2309 | 2024-04-30 | Bad News Kangaroos | W   | 0.584      | -            | -                | -                | -         |     0.04 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           16 |     2729 | 2024-04-14 | FaZe               | L   | 0.477      | -            | -                | -                | -         |   -10.44 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           15 |     2746 | 2024-04-13 | G2                 | W   | 0.470      | 0.624        | 1.000 (0.293)    | -                | -         |     9.21 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           14 |     2842 | 2024-04-10 | Liquid             | W   | 0.450      | -            | -                | -                | -         |     1.38 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           13 |     2916 | 2024-04-08 | FURIA              | W   | 0.438      | -            | -                | -                | -         |     3.90 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           12 |     2927 | 2024-04-07 | TYLOO              | W   | 0.436      | -            | -                | -                | -         |     0.03 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           11 |     3128 | 2024-03-29 | G2                 | L   | 0.373      | -            | -                | -                | -         |    -4.19 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           10 |     3251 | 2024-03-22 | Complexity         | W   | 0.325      | -            | -                | -                | -         |     2.23 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            9 |     3271 | 2024-03-21 | Eternal Fire       | W   | 0.319      | 1.000        | 0.752 (0.240)    | -                | -         |     3.07 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            8 |     3281 | 2024-03-21 | Gaimin Gladiators  | W   | 0.318      | -            | -                | -                | -         |     0.08 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            7 |     3962 | 2024-02-20 | Spirit             | W   | 0.119      | -            | -                | -                | -         |     2.10 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            6 |     3984 | 2024-02-19 | Gaimin Gladiators  | W   | 0.113      | -            | -                | -                | -         |     0.02 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            5 |     3997 | 2024-02-19 | ex-Guild Eagles    | W   | 0.111      | -            | -                | -                | -         |     0.01 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            4 |     4192 | 2024-02-10 | FaZe               | L   | 0.052      | -            | -                | -                | -         |    -1.15 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            3 |     4235 | 2024-02-06 | ENCE               | W   | 0.026      | -            | -                | -                | -         |     0.09 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            2 |     4247 | 2024-02-05 | GamerLegion        | W   | 0.019      | -            | -                | -                | -         |     0.00 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            1 |     4271 | 2024-02-04 | Cloud9             | W   | 0.011      | -            | -                | -                | -         |     0.00 | Brollan, Jimpphat, siuhy, torzsi, xertioN |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($457,612.33)
- Divide that value by the 5th highest value among all rosters ($331,608.80)
- The final value (1.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-21 |      1.000 | $85,000.00     | $85,000.00      |
| 2024-06-02 |      0.806 | $5,000.00      | $4,030.02       |
| 2024-05-19 |      0.711 | $300,000.00    | $213,384.72     |
| 2024-05-12 |      0.665 | $170,000.00    | $113,079.12     |
| 2024-04-14 |      0.477 | $42,000.00     | $20,045.67      |
| 2024-03-31 |      0.386 | $45,000.00     | $17,370.21      |
| 2024-02-11 |      0.059 | $80,000.00     | $4,702.59       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
