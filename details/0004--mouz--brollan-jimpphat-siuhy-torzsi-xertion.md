### Roster Details<br />
Team Name: MOUZ<br />
Roster: Brollan, Jimpphat, siuhy, torzsi, xertioN<br />
Global Rank: [4](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [4]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1869.2<br />
<br />
Final Rank Value (1869.2) = Starting Rank Value (1843.7) + Head To Head Adjustments (25.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 1.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.658[<sup>2</sup>](#table1)
- Opponent Network: 0.323[<sup>2</sup>](#table1)
- LAN Wins: 0.835[<sup>2</sup>](#table1)

The average of these factors is 0.704<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1843.7
- 400 + ( ( 0.704 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 1843.7


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
|           29 |      541 | 2024-07-20 | Natus Vincere      | L   | 1.000      | -            | -                | -                | -         |   -13.14 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           28 |      584 | 2024-07-19 | FURIA              | W   | 1.000      | 1.000        | 0.284 (0.284)    | 0.480 (0.480)    | 1 (1.000) |     5.72 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           27 |      721 | 2024-07-17 | Sashi              | W   | 1.000      | 1.000        | 0.184 (0.184)    | 0.982 (0.982)    | 1 (1.000) |     0.62 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           26 |     1720 | 2024-05-28 | G2                 | L   | 0.740      | -            | -                | -                | -         |   -10.15 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           25 |     1741 | 2024-05-27 | Complexity         | W   | 0.733      | 0.624        | -                | 0.373 (0.171)    | 1 (0.733) |     5.05 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           24 |     1750 | 2024-05-27 | 9z                 | L   | 0.732      | -            | -                | -                | -         |   -21.48 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           23 |     1969 | 2024-05-19 | Spirit             | W   | 0.677      | 0.769        | 1.000 (0.520)    | 0.452 (0.235)    | 1 (0.677) |    10.95 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           22 |     1997 | 2024-05-18 | HEROIC             | W   | 0.671      | 0.769        | -                | 0.364 (0.188)    | 1 (0.671) |     2.86 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           21 |     2076 | 2024-05-16 | Virtus.pro         | W   | 0.656      | 0.769        | 0.498 (0.251)    | -                | 1 (0.656) |     5.04 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           20 |     2181 | 2024-05-14 | BetBoom            | W   | 0.643      | 0.769        | -                | 0.527 (0.261)    | 1 (0.643) |     1.07 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           19 |     2224 | 2024-05-12 | Vitality           | W   | 0.631      | 0.889        | 0.647 (0.363)    | 0.376 (0.211)    | 1 (0.631) |     9.66 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           18 |     2246 | 2024-05-11 | Complexity         | W   | 0.625      | 0.889        | 0.342 (0.190)    | 0.373 (0.207)    | 1 (0.625) |     4.93 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           17 |     2294 | 2024-05-09 | G2                 | W   | 0.611      | 0.889        | 1.000 (0.543)    | 0.489 (0.266)    | 1 (0.611) |    11.90 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           16 |     2387 | 2024-05-04 | Liquid             | W   | 0.578      | 0.889        | 0.383 (0.197)    | 0.449 (0.231)    | -         |     3.41 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           15 |     2455 | 2024-05-01 | GamerLegion        | W   | 0.557      | -            | -                | -                | -         |     0.30 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           14 |     2486 | 2024-04-30 | Bad News Kangaroos | W   | 0.550      | -            | -                | -                | -         |     0.05 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           13 |     2906 | 2024-04-14 | FaZe               | L   | 0.443      | -            | -                | -                | -         |    -9.82 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           12 |     2923 | 2024-04-13 | G2                 | W   | 0.435      | 0.624        | 1.000 (0.272)    | -                | -         |     9.12 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           11 |     3019 | 2024-04-10 | Liquid             | W   | 0.415      | -            | -                | -                | -         |     2.57 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           10 |     3093 | 2024-04-08 | FURIA              | W   | 0.403      | -            | -                | -                | -         |     3.78 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            9 |     3104 | 2024-04-07 | TYLOO              | W   | 0.401      | -            | -                | -                | -         |     0.03 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            8 |     3305 | 2024-03-29 | G2                 | L   | 0.338      | -            | -                | -                | -         |    -3.34 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            7 |     3428 | 2024-03-22 | Complexity         | W   | 0.290      | -            | -                | -                | -         |     2.28 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            6 |     3448 | 2024-03-21 | Eternal Fire       | W   | 0.285      | 1.000        | 0.739 (0.210)    | -                | -         |     2.79 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            5 |     3458 | 2024-03-21 | Gaimin Gladiators  | W   | 0.283      | -            | -                | -                | -         |     0.07 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            4 |     4139 | 2024-02-20 | Spirit             | W   | 0.084      | -            | -                | -                | -         |     1.55 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            3 |     4161 | 2024-02-19 | Gaimin Gladiators  | W   | 0.078      | -            | -                | -                | -         |     0.02 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            2 |     4174 | 2024-02-19 | ex-Guild Eagles    | W   | 0.076      | -            | -                | -                | -         |     0.01 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            1 |     4369 | 2024-02-10 | FaZe               | L   | 0.017      | -            | -                | -                | -         |    -0.39 | Brollan, Jimpphat, siuhy, torzsi, xertioN |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($435,389.03)
- Divide that value by the 5th highest value among all rosters ($321,345.23)
- The final value (1.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-21 |      1.000 | $85,000.00     | $85,000.00      |
| 2024-06-02 |      0.771 | $5,000.00      | $3,856.94       |
| 2024-05-19 |      0.677 | $300,000.00    | $203,000.00     |
| 2024-05-12 |      0.631 | $170,000.00    | $107,194.44     |
| 2024-04-14 |      0.443 | $42,000.00     | $18,591.81      |
| 2024-03-31 |      0.351 | $45,000.00     | $15,812.50      |
| 2024-02-11 |      0.024 | $80,000.00     | $1,933.33       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
