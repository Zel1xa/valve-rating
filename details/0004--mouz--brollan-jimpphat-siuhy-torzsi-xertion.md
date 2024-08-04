### Roster Details<br />
Team Name: MOUZ<br />
Roster: Brollan, Jimpphat, siuhy, torzsi, xertioN<br />
Global Rank: [4](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [4]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1870.6<br />
<br />
Final Rank Value (1870.6) = Starting Rank Value (1844.9) + Head To Head Adjustments (25.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 1.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.660[<sup>2</sup>](#table1)
- Opponent Network: 0.328[<sup>2</sup>](#table1)
- LAN Wins: 0.838[<sup>2</sup>](#table1)

The average of these factors is 0.707<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1844.9
- 400 + ( ( 0.707 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 1844.9


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
|           30 |      513 | 2024-07-20 | Natus Vincere      | L   | 1.000      | -            | -                | -                | -         |   -13.18 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           29 |      556 | 2024-07-19 | FURIA              | W   | 1.000      | 1.000        | 0.284 (0.284)    | 0.490 (0.490)    | 1 (1.000) |     5.63 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           28 |      693 | 2024-07-17 | Sashi              | W   | 1.000      | 1.000        | 0.184 (0.184)    | 0.962 (0.962)    | 1 (1.000) |     0.61 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           27 |     1692 | 2024-05-28 | G2                 | L   | 0.749      | -            | -                | -                | -         |   -10.36 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           26 |     1713 | 2024-05-27 | Complexity         | W   | 0.742      | 0.624        | -                | 0.380 (0.176)    | 1 (0.742) |     5.13 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           25 |     1722 | 2024-05-27 | 9z                 | L   | 0.741      | -            | -                | -                | -         |   -21.75 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           24 |     1941 | 2024-05-19 | Spirit             | W   | 0.686      | 0.769        | 1.000 (0.527)    | 0.460 (0.243)    | 1 (0.686) |    11.06 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           23 |     1969 | 2024-05-18 | HEROIC             | W   | 0.680      | 0.769        | -                | 0.373 (0.195)    | 1 (0.680) |     2.91 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           22 |     2048 | 2024-05-16 | Virtus.pro         | W   | 0.665      | 0.769        | 0.497 (0.254)    | -                | 1 (0.665) |     5.13 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           21 |     2153 | 2024-05-14 | BetBoom            | W   | 0.652      | 0.769        | -                | 0.541 (0.271)    | 1 (0.652) |     1.09 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           20 |     2196 | 2024-05-12 | Vitality           | W   | 0.640      | 0.889        | 0.649 (0.369)    | 0.383 (0.218)    | 1 (0.640) |     9.80 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           19 |     2218 | 2024-05-11 | Complexity         | W   | 0.634      | 0.889        | 0.342 (0.193)    | 0.380 (0.214)    | 1 (0.634) |     5.03 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           18 |     2266 | 2024-05-09 | G2                 | W   | 0.620      | 0.889        | 1.000 (0.551)    | 0.498 (0.275)    | 1 (0.620) |    12.01 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           17 |     2359 | 2024-05-04 | Liquid             | W   | 0.587      | 0.889        | 0.384 (0.201)    | 0.460 (0.240)    | -         |     3.44 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           16 |     2427 | 2024-05-01 | GamerLegion        | W   | 0.566      | -            | -                | -                | -         |     0.30 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           15 |     2458 | 2024-04-30 | Bad News Kangaroos | W   | 0.559      | -            | -                | -                | -         |     0.05 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           14 |     2878 | 2024-04-14 | FaZe               | L   | 0.452      | -            | -                | -                | -         |    -9.95 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           13 |     2895 | 2024-04-13 | G2                 | W   | 0.444      | 0.624        | 1.000 (0.277)    | -                | -         |     9.28 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           12 |     2991 | 2024-04-10 | Liquid             | W   | 0.424      | -            | -                | -                | -         |     2.61 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           11 |     3065 | 2024-04-08 | FURIA              | W   | 0.412      | -            | -                | -                | -         |     3.82 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           10 |     3076 | 2024-04-07 | TYLOO              | W   | 0.410      | -            | -                | -                | -         |     0.03 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            9 |     3277 | 2024-03-29 | G2                 | L   | 0.347      | -            | -                | -                | -         |    -3.45 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            8 |     3400 | 2024-03-22 | Complexity         | W   | 0.299      | -            | -                | -                | -         |     2.36 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            7 |     3420 | 2024-03-21 | Eternal Fire       | W   | 0.294      | 1.000        | 0.742 (0.218)    | -                | -         |     2.88 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            6 |     3430 | 2024-03-21 | Gaimin Gladiators  | W   | 0.292      | -            | -                | -                | -         |     0.08 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            5 |     4111 | 2024-02-20 | Spirit             | W   | 0.093      | -            | -                | -                | -         |     1.72 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            4 |     4133 | 2024-02-19 | Gaimin Gladiators  | W   | 0.087      | -            | -                | -                | -         |     0.02 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            3 |     4146 | 2024-02-19 | ex-Guild Eagles    | W   | 0.085      | -            | -                | -                | -         |     0.01 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            2 |     4341 | 2024-02-10 | FaZe               | L   | 0.026      | -            | -                | -                | -         |    -0.59 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            1 |     4384 | 2024-02-06 | ENCE               | W   | 0.001      | -            | -                | -                | -         |     0.00 | Brollan, Jimpphat, siuhy, torzsi, xertioN |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($441,199.72)
- Divide that value by the 5th highest value among all rosters ($324,028.83)
- The final value (1.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-21 |      1.000 | $85,000.00     | $85,000.00      |
| 2024-06-02 |      0.780 | $5,000.00      | $3,902.20       |
| 2024-05-19 |      0.686 | $300,000.00    | $205,715.28     |
| 2024-05-12 |      0.640 | $170,000.00    | $108,733.10     |
| 2024-04-14 |      0.452 | $42,000.00     | $18,971.94      |
| 2024-03-31 |      0.360 | $45,000.00     | $16,219.79      |
| 2024-02-11 |      0.033 | $80,000.00     | $2,657.41       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
