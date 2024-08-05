### Roster Details<br />
Team Name: MOUZ<br />
Roster: Brollan, Jimpphat, siuhy, torzsi, xertioN<br />
Global Rank: [4](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [4]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1869.9<br />
<br />
Final Rank Value (1869.9) = Starting Rank Value (1844.2) + Head To Head Adjustments (25.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 1.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.660[<sup>2</sup>](#table1)
- Opponent Network: 0.327[<sup>2</sup>](#table1)
- LAN Wins: 0.837[<sup>2</sup>](#table1)

The average of these factors is 0.706<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1844.2
- 400 + ( ( 0.706 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 1844.2


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
|           29 |      517 | 2024-07-20 | Natus Vincere      | L   | 1.000      | -            | -                | -                | -         |   -13.15 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           28 |      560 | 2024-07-19 | FURIA              | W   | 1.000      | 1.000        | 0.284 (0.284)    | 0.490 (0.490)    | 1 (1.000) |     5.66 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           27 |      697 | 2024-07-17 | Sashi              | W   | 1.000      | 1.000        | 0.184 (0.184)    | 0.961 (0.961)    | 1 (1.000) |     0.61 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           26 |     1696 | 2024-05-28 | G2                 | L   | 0.746      | -            | -                | -                | -         |   -10.30 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           25 |     1717 | 2024-05-27 | Complexity         | W   | 0.740      | 0.624        | -                | 0.380 (0.175)    | 1 (0.740) |     5.11 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           24 |     1726 | 2024-05-27 | 9z                 | L   | 0.738      | -            | -                | -                | -         |   -21.68 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           23 |     1945 | 2024-05-19 | Spirit             | W   | 0.683      | 0.769        | 1.000 (0.525)    | 0.460 (0.242)    | 1 (0.683) |    11.04 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           22 |     1973 | 2024-05-18 | HEROIC             | W   | 0.677      | 0.769        | -                | 0.372 (0.194)    | 1 (0.677) |     2.90 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           21 |     2052 | 2024-05-16 | Virtus.pro         | W   | 0.663      | 0.769        | 0.497 (0.253)    | -                | 1 (0.663) |     5.11 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           20 |     2157 | 2024-05-14 | BetBoom            | W   | 0.650      | 0.769        | -                | 0.540 (0.270)    | 1 (0.650) |     1.09 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           19 |     2200 | 2024-05-12 | Vitality           | W   | 0.637      | 0.889        | 0.648 (0.367)    | 0.382 (0.217)    | 1 (0.637) |     9.77 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           18 |     2222 | 2024-05-11 | Complexity         | W   | 0.631      | 0.889        | 0.342 (0.192)    | 0.380 (0.213)    | 1 (0.631) |     5.01 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           17 |     2270 | 2024-05-09 | G2                 | W   | 0.618      | 0.889        | 1.000 (0.549)    | 0.498 (0.273)    | 1 (0.618) |    11.99 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           16 |     2363 | 2024-05-04 | Liquid             | W   | 0.585      | 0.889        | 0.384 (0.200)    | 0.459 (0.238)    | -         |     3.45 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           15 |     2431 | 2024-05-01 | GamerLegion        | W   | 0.564      | -            | -                | -                | -         |     0.30 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           14 |     2462 | 2024-04-30 | Bad News Kangaroos | W   | 0.556      | -            | -                | -                | -         |     0.05 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           13 |     2882 | 2024-04-14 | FaZe               | L   | 0.449      | -            | -                | -                | -         |    -9.91 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           12 |     2899 | 2024-04-13 | G2                 | W   | 0.442      | 0.624        | 1.000 (0.276)    | -                | -         |     9.24 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           11 |     2995 | 2024-04-10 | Liquid             | W   | 0.422      | -            | -                | -                | -         |     2.62 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           10 |     3069 | 2024-04-08 | FURIA              | W   | 0.410      | -            | -                | -                | -         |     3.81 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            9 |     3080 | 2024-04-07 | TYLOO              | W   | 0.408      | -            | -                | -                | -         |     0.03 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            8 |     3281 | 2024-03-29 | G2                 | L   | 0.345      | -            | -                | -                | -         |    -3.41 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            7 |     3404 | 2024-03-22 | Complexity         | W   | 0.297      | -            | -                | -                | -         |     2.34 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            6 |     3424 | 2024-03-21 | Eternal Fire       | W   | 0.291      | 1.000        | 0.741 (0.216)    | -                | -         |     2.86 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            5 |     3434 | 2024-03-21 | Gaimin Gladiators  | W   | 0.290      | -            | -                | -                | -         |     0.08 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            4 |     4115 | 2024-02-20 | Spirit             | W   | 0.091      | -            | -                | -                | -         |     1.68 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            3 |     4137 | 2024-02-19 | Gaimin Gladiators  | W   | 0.085      | -            | -                | -                | -         |     0.02 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            2 |     4150 | 2024-02-19 | ex-Guild Eagles    | W   | 0.083      | -            | -                | -                | -         |     0.01 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            1 |     4345 | 2024-02-10 | FaZe               | L   | 0.024      | -            | -                | -                | -         |    -0.54 | Brollan, Jimpphat, siuhy, torzsi, xertioN |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($439,669.03)
- Divide that value by the 5th highest value among all rosters ($323,321.90)
- The final value (1.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-21 |      1.000 | $85,000.00     | $85,000.00      |
| 2024-06-02 |      0.778 | $5,000.00      | $3,890.28       |
| 2024-05-19 |      0.683 | $300,000.00    | $205,000.00     |
| 2024-05-12 |      0.637 | $170,000.00    | $108,327.78     |
| 2024-04-14 |      0.449 | $42,000.00     | $18,871.81      |
| 2024-03-31 |      0.358 | $45,000.00     | $16,112.50      |
| 2024-02-11 |      0.031 | $80,000.00     | $2,466.67       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
