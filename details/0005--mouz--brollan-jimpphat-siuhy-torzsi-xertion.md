### Roster Details<br />
Team Name: MOUZ<br />
Roster: Brollan, Jimpphat, siuhy, torzsi, xertioN<br />
Global Rank: [5](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [5]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1827.8<br />
<br />
Final Rank Value (1827.8) = Starting Rank Value (1786.3) + Head To Head Adjustments (41.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 1.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.657[<sup>2</sup>](#table1)
- Opponent Network: 0.260[<sup>2</sup>](#table1)
- LAN Wins: 0.794[<sup>2</sup>](#table1)

The average of these factors is 0.678<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1786.3
- 400 + ( ( 0.678 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 1786.3


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
|           29 |      455 | 2024-07-20 | Natus Vincere      | L   | 1.000      | -            | -                | -                | -         |   -11.36 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           28 |      498 | 2024-07-19 | FURIA              | W   | 1.000      | 1.000        | 0.284 (0.284)    | 0.508 (0.508)    | 1 (1.000) |     6.54 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           27 |     1593 | 2024-05-28 | G2                 | L   | 0.755      | -            | -                | -                | -         |    -9.15 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           26 |     1614 | 2024-05-27 | Complexity         | W   | 0.749      | 0.624        | 0.313 (0.146)    | 0.394 (0.184)    | 1 (0.749) |     6.11 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           25 |     1623 | 2024-05-27 | 9z                 | L   | 0.747      | -            | -                | -                | -         |   -22.95 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           24 |     1840 | 2024-05-19 | Spirit             | W   | 0.692      | 0.769        | 1.000 (0.532)    | 0.477 (0.254)    | 1 (0.692) |    12.72 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           23 |     1868 | 2024-05-18 | HEROIC             | W   | 0.686      | 0.769        | -                | 0.388 (0.205)    | 1 (0.686) |     3.56 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           22 |     1947 | 2024-05-16 | Virtus.pro         | W   | 0.672      | 0.769        | 0.496 (0.256)    | 0.335 (0.173)    | 1 (0.672) |     6.19 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           21 |     2052 | 2024-05-14 | BetBoom            | W   | 0.659      | 0.769        | -                | 0.563 (0.285)    | 1 (0.659) |     1.43 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           20 |     2096 | 2024-05-12 | Vitality           | W   | 0.646      | 0.889        | 0.650 (0.373)    | 0.396 (0.228)    | 1 (0.646) |    11.40 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           19 |     2117 | 2024-05-11 | Complexity         | W   | 0.640      | 0.889        | 0.313 (0.178)    | 0.394 (0.224)    | 1 (0.640) |     6.16 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           18 |     2165 | 2024-05-09 | G2                 | W   | 0.627      | 0.889        | 1.000 (0.557)    | 0.516 (0.287)    | 1 (0.627) |    13.38 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           17 |     2257 | 2024-05-04 | Liquid             | W   | 0.594      | 0.889        | 0.316 (0.167)    | 0.478 (0.252)    | 1 (0.594) |     3.09 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           16 |     2325 | 2024-05-01 | GamerLegion        | W   | 0.573      | -            | -                | -                | -         |     0.41 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           15 |     2356 | 2024-04-30 | Bad News Kangaroos | W   | 0.565      | -            | -                | -                | -         |     0.06 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           14 |     2775 | 2024-04-14 | FaZe               | L   | 0.458      | -            | -                | -                | -         |    -9.03 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           13 |     2792 | 2024-04-13 | G2                 | W   | 0.451      | 0.624        | 1.000 (0.281)    | -                | -         |    10.30 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           12 |     2888 | 2024-04-10 | Liquid             | W   | 0.431      | -            | -                | -                | -         |     2.31 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           11 |     2962 | 2024-04-08 | FURIA              | W   | 0.419      | -            | -                | -                | -         |     4.77 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           10 |     2973 | 2024-04-07 | TYLOO              | W   | 0.417      | -            | -                | -                | -         |     0.04 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            9 |     3174 | 2024-03-29 | G2                 | L   | 0.354      | -            | -                | -                | -         |    -2.80 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            8 |     3292 | 2024-03-22 | Complexity         | W   | 0.306      | -            | -                | -                | -         |     2.99 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            7 |     3312 | 2024-03-21 | Eternal Fire       | W   | 0.300      | 1.000        | 0.746 (0.224)    | -                | -         |     3.67 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            6 |     3322 | 2024-03-21 | Gaimin Gladiators  | W   | 0.299      | -            | -                | -                | -         |     0.11 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            5 |     4000 | 2024-02-20 | Spirit             | W   | 0.100      | -            | -                | -                | -         |     2.10 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            4 |     4022 | 2024-02-19 | Gaimin Gladiators  | W   | 0.094      | -            | -                | -                | -         |     0.03 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            3 |     4035 | 2024-02-19 | ex-Guild Eagles    | W   | 0.092      | -            | -                | -                | -         |     0.01 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            2 |     4229 | 2024-02-10 | FaZe               | L   | 0.033      | -            | -                | -                | -         |    -0.65 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            1 |     4272 | 2024-02-06 | ENCE               | W   | 0.007      | -            | -                | -                | -         |     0.03 | Brollan, Jimpphat, siuhy, torzsi, xertioN |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($445,405.42)
- Divide that value by the 5th highest value among all rosters ($325,971.18)
- The final value (1.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-21 |      1.000 | $85,000.00     | $85,000.00      |
| 2024-06-02 |      0.787 | $5,000.00      | $3,934.95       |
| 2024-05-19 |      0.692 | $300,000.00    | $207,680.56     |
| 2024-05-12 |      0.646 | $170,000.00    | $109,846.76     |
| 2024-04-14 |      0.458 | $42,000.00     | $19,247.08      |
| 2024-03-31 |      0.367 | $45,000.00     | $16,514.58      |
| 2024-02-11 |      0.040 | $80,000.00     | $3,181.48       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
