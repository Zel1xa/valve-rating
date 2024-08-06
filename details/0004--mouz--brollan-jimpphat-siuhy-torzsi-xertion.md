### Roster Details<br />
Team Name: MOUZ<br />
Roster: Brollan, Jimpphat, siuhy, torzsi, xertioN<br />
Global Rank: [4](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [4]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1867.8<br />
<br />
Final Rank Value (1867.8) = Starting Rank Value (1842.1) + Head To Head Adjustments (25.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 1.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.656[<sup>2</sup>](#table1)
- Opponent Network: 0.314[<sup>2</sup>](#table1)
- LAN Wins: 0.834[<sup>2</sup>](#table1)

The average of these factors is 0.701<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1842.1
- 400 + ( ( 0.701 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1842.1


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
|           29 |      547 | 2024-07-20 | Natus Vincere      | L   | 1.000      | -            | -                | -                | -         |   -13.09 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           28 |      590 | 2024-07-19 | FURIA              | W   | 1.000      | 1.000        | 0.284 (0.284)    | 0.469 (0.469)    | 1 (1.000) |     5.75 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           27 |      727 | 2024-07-17 | Sashi              | W   | 1.000      | 1.000        | 0.184 (0.184)    | 0.958 (0.958)    | 1 (1.000) |     0.62 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           26 |     1726 | 2024-05-28 | G2                 | L   | 0.736      | -            | -                | -                | -         |   -10.04 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           25 |     1747 | 2024-05-27 | Complexity         | W   | 0.730      | 0.624        | -                | 0.364 (0.166)    | 1 (0.730) |     5.04 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           24 |     1756 | 2024-05-27 | 9z                 | L   | 0.728      | -            | -                | -                | -         |   -21.37 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           23 |     1975 | 2024-05-19 | Spirit             | W   | 0.673      | 0.769        | 1.000 (0.517)    | 0.441 (0.228)    | 1 (0.673) |    10.94 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           22 |     2003 | 2024-05-18 | HEROIC             | W   | 0.667      | 0.769        | -                | 0.354 (0.182)    | 1 (0.667) |     2.84 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           21 |     2082 | 2024-05-16 | Virtus.pro         | W   | 0.652      | 0.769        | 0.498 (0.250)    | -                | 1 (0.652) |     5.02 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           20 |     2187 | 2024-05-14 | BetBoom            | W   | 0.640      | 0.769        | -                | 0.514 (0.253)    | 1 (0.640) |     1.08 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           19 |     2230 | 2024-05-12 | Vitality           | W   | 0.627      | 0.889        | 0.647 (0.361)    | 0.367 (0.204)    | 1 (0.627) |     9.63 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           18 |     2252 | 2024-05-11 | Complexity         | W   | 0.621      | 0.889        | 0.341 (0.188)    | 0.364 (0.201)    | 1 (0.621) |     4.92 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           17 |     2300 | 2024-05-09 | G2                 | W   | 0.608      | 0.889        | 1.000 (0.540)    | 0.478 (0.258)    | 1 (0.608) |    11.88 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           16 |     2393 | 2024-05-04 | Liquid             | W   | 0.574      | 0.889        | 0.383 (0.195)    | 0.437 (0.223)    | -         |     3.41 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           15 |     2461 | 2024-05-01 | GamerLegion        | W   | 0.554      | -            | -                | -                | -         |     0.29 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           14 |     2492 | 2024-04-30 | Bad News Kangaroos | W   | 0.546      | -            | -                | -                | -         |     0.04 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           13 |     2912 | 2024-04-14 | FaZe               | L   | 0.439      | -            | -                | -                | -         |    -9.76 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           12 |     2929 | 2024-04-13 | G2                 | W   | 0.432      | 0.624        | 1.000 (0.269)    | -                | -         |     9.08 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           11 |     3025 | 2024-04-10 | Liquid             | W   | 0.412      | -            | -                | -                | -         |     2.57 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           10 |     3099 | 2024-04-08 | FURIA              | W   | 0.400      | -            | -                | -                | -         |     3.75 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            9 |     3110 | 2024-04-07 | TYLOO              | W   | 0.398      | -            | -                | -                | -         |     0.03 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            8 |     3311 | 2024-03-29 | G2                 | L   | 0.335      | -            | -                | -                | -         |    -3.28 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            7 |     3434 | 2024-03-22 | Complexity         | W   | 0.287      | -            | -                | -                | -         |     2.26 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            6 |     3454 | 2024-03-21 | Eternal Fire       | W   | 0.281      | 1.000        | 0.739 (0.208)    | -                | -         |     2.77 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            5 |     3464 | 2024-03-21 | Gaimin Gladiators  | W   | 0.280      | -            | -                | -                | -         |     0.07 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            4 |     4145 | 2024-02-20 | Spirit             | W   | 0.081      | -            | -                | -                | -         |     1.50 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            3 |     4167 | 2024-02-19 | Gaimin Gladiators  | W   | 0.075      | -            | -                | -                | -         |     0.02 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            2 |     4180 | 2024-02-19 | ex-Guild Eagles    | W   | 0.073      | -            | -                | -                | -         |     0.01 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            1 |     4375 | 2024-02-10 | FaZe               | L   | 0.014      | -            | -                | -                | -         |    -0.31 | Brollan, Jimpphat, siuhy, torzsi, xertioN |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($433,189.58)
- Divide that value by the 5th highest value among all rosters ($320,329.44)
- The final value (1.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-21 |      1.000 | $85,000.00     | $85,000.00      |
| 2024-06-02 |      0.768 | $5,000.00      | $3,839.81       |
| 2024-05-19 |      0.673 | $300,000.00    | $201,972.22     |
| 2024-05-12 |      0.627 | $170,000.00    | $106,612.04     |
| 2024-04-14 |      0.439 | $42,000.00     | $18,447.92      |
| 2024-03-31 |      0.348 | $45,000.00     | $15,658.33      |
| 2024-02-11 |      0.021 | $80,000.00     | $1,659.26       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
