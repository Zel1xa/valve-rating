### Roster Details<br />
Team Name: MOUZ<br />
Roster: Brollan, Jimpphat, siuhy, torzsi, xertioN<br />
Global Rank: [5](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [5]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1844.3<br />
<br />
Final Rank Value (1844.3) = Starting Rank Value (1854.7) + Head To Head Adjustments (-10.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 1.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.727[<sup>2</sup>](#table1)
- Opponent Network: 0.435[<sup>2</sup>](#table1)
- LAN Wins: 0.843[<sup>2</sup>](#table1)

The average of these factors is 0.751<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1854.7
- 400 + ( ( 0.751 - 0.000 ) / ( 0.826 - 0.000 ) ) * 1600 = 1854.7


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
|           34 |      214 | 2024-08-31 | Eternal Fire       | L   | 1.000      | -            | -                | -                | -         |   -20.43 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           33 |      225 | 2024-08-30 | Spirit             | L   | 1.000      | -            | -                | -                | -         |   -12.99 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           32 |      260 | 2024-08-29 | paiN               | W   | 1.000      | 0.769        | 0.420 (0.323)    | 0.935 (0.719)    | 1 (1.000) |     5.30 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           31 |      307 | 2024-08-28 | Eternal Fire       | W   | 1.000      | 0.769        | 0.972 (0.747)    | 0.700 (0.538)    | 1 (1.000) |     9.43 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           30 |      764 | 2024-08-17 | Natus Vincere      | L   | 1.000      | -            | -                | -                | -         |   -12.13 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           29 |      786 | 2024-08-16 | G2                 | W   | 1.000      | 1.000        | 1.000 (1.000)    | 0.481 (0.481)    | 1 (1.000) |    19.44 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           28 |      873 | 2024-08-13 | Vitality           | L   | 1.000      | -            | -                | -                | -         |   -13.81 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           27 |      928 | 2024-08-12 | Complexity         | W   | 1.000      | 1.000        | 0.337 (0.337)    | 0.367 (0.367)    | 1 (1.000) |     3.79 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           26 |      959 | 2024-08-11 | Falcons            | W   | 1.000      | 1.000        | 0.297 (0.297)    | 0.477 (0.477)    | 1 (1.000) |     3.20 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           25 |     1677 | 2024-07-20 | Natus Vincere      | L   | 0.868      | -            | -                | -                | -         |    -9.91 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           24 |     1720 | 2024-07-19 | FURIA              | W   | 0.861      | 1.000        | 0.319 (0.275)    | 0.513 (0.441)    | 1 (0.861) |     4.46 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           23 |     1857 | 2024-07-17 | Sashi              | W   | 0.846      | 1.000        | -                | 0.926 (0.783)    | 1 (0.846) |     0.37 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           22 |     2859 | 2024-05-28 | G2                 | L   | 0.516      | -            | -                | -                | -         |    -6.59 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           21 |     2880 | 2024-05-27 | Complexity         | W   | 0.510      | -            | -                | -                | 1 (0.510) |     2.02 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           20 |     2889 | 2024-05-27 | 9z                 | L   | 0.508      | -            | -                | -                | -         |   -14.98 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           19 |     3108 | 2024-05-19 | Spirit             | W   | 0.453      | 0.769        | 1.000 (0.348)    | 0.557 (0.194)    | 1 (0.453) |     8.58 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           18 |     3136 | 2024-05-18 | HEROIC             | W   | 0.447      | -            | -                | -                | 1 (0.447) |     0.93 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           17 |     3215 | 2024-05-16 | Virtus.pro         | W   | 0.433      | 0.769        | 0.520 (0.173)    | -                | -         |     1.70 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           16 |     3320 | 2024-05-14 | BetBoom            | W   | 0.420      | 0.769        | -                | 0.535 (0.173)    | -         |     0.33 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           15 |     3363 | 2024-05-12 | Vitality           | W   | 0.407      | 0.889        | 1.000 (0.362)    | -                | -         |     7.30 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           14 |     3385 | 2024-05-11 | Complexity         | W   | 0.401      | -            | -                | -                | -         |     1.71 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           13 |     3433 | 2024-05-09 | G2                 | W   | 0.388      | 0.889        | 1.000 (0.345)    | -                | -         |     7.66 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           12 |     3526 | 2024-05-04 | Liquid             | W   | 0.355      | -            | -                | -                | -         |     1.85 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           11 |     3594 | 2024-05-01 | GamerLegion        | W   | 0.334      | 0.889        | -                | 0.601 (0.178)    | -         |     0.12 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           10 |     3625 | 2024-04-30 | Bad News Kangaroos | W   | 0.326      | -            | -                | -                | -         |     0.01 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            9 |     4045 | 2024-04-14 | FaZe               | L   | 0.219      | -            | -                | -                | -         |    -4.49 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            8 |     4062 | 2024-04-13 | G2                 | W   | 0.212      | -            | -                | -                | -         |     4.35 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            7 |     4158 | 2024-04-10 | Liquid             | W   | 0.192      | -            | -                | -                | -         |     1.03 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            6 |     4232 | 2024-04-08 | FURIA              | W   | 0.180      | -            | -                | -                | -         |     1.27 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            5 |     4243 | 2024-04-07 | TYLOO              | W   | 0.178      | -            | -                | -                | -         |     0.01 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            4 |     4444 | 2024-03-29 | G2                 | L   | 0.115      | -            | -                | -                | -         |    -1.23 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            3 |     4567 | 2024-03-22 | Complexity         | W   | 0.067      | -            | -                | -                | -         |     0.28 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            2 |     4587 | 2024-03-21 | Eternal Fire       | W   | 0.061      | -            | -                | -                | -         |     1.01 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            1 |     4597 | 2024-03-21 | Gaimin Gladiators  | W   | 0.060      | -            | -                | -                | -         |     0.01 | Brollan, Jimpphat, siuhy, torzsi, xertioN |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($427,293.75)
- Divide that value by the 5th highest value among all rosters ($303,706.75)
- The final value (1.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-09-01 |      1.000 | $50,000.00     | $50,000.00      |
| 2024-08-18 |      1.000 | $80,000.00     | $80,000.00      |
| 2024-07-21 |      0.875 | $85,000.00     | $74,351.39      |
| 2024-06-02 |      0.548 | $5,000.00      | $2,740.28       |
| 2024-05-19 |      0.453 | $300,000.00    | $136,000.00     |
| 2024-05-12 |      0.407 | $170,000.00    | $69,227.78      |
| 2024-04-14 |      0.219 | $42,000.00     | $9,211.81       |
| 2024-03-31 |      0.128 | $45,000.00     | $5,762.50       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
