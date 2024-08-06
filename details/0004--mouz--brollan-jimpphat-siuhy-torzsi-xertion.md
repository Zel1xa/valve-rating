### Roster Details<br />
Team Name: MOUZ<br />
Roster: Brollan, Jimpphat, siuhy, torzsi, xertioN<br />
Global Rank: [4](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [4]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1868.4<br />
<br />
Final Rank Value (1868.4) = Starting Rank Value (1842.9) + Head To Head Adjustments (25.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 1.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.657[<sup>2</sup>](#table1)
- Opponent Network: 0.322[<sup>2</sup>](#table1)
- LAN Wins: 0.834[<sup>2</sup>](#table1)

The average of these factors is 0.703<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1842.9
- 400 + ( ( 0.703 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 1842.9


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
|           29 |      545 | 2024-07-20 | Natus Vincere      | L   | 1.000      | -            | -                | -                | -         |   -13.11 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           28 |      588 | 2024-07-19 | FURIA              | W   | 1.000      | 1.000        | 0.284 (0.284)    | 0.479 (0.479)    | 1 (1.000) |     5.75 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           27 |      725 | 2024-07-17 | Sashi              | W   | 1.000      | 1.000        | 0.184 (0.184)    | 0.980 (0.980)    | 1 (1.000) |     0.62 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           26 |     1724 | 2024-05-28 | G2                 | L   | 0.737      | -            | -                | -                | -         |   -10.08 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           25 |     1745 | 2024-05-27 | Complexity         | W   | 0.731      | 0.624        | -                | 0.372 (0.170)    | 1 (0.731) |     5.03 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           24 |     1754 | 2024-05-27 | 9z                 | L   | 0.729      | -            | -                | -                | -         |   -21.40 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           23 |     1973 | 2024-05-19 | Spirit             | W   | 0.674      | 0.769        | 1.000 (0.518)    | 0.451 (0.234)    | 1 (0.674) |    10.93 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           22 |     2001 | 2024-05-18 | HEROIC             | W   | 0.668      | 0.769        | -                | 0.363 (0.186)    | 1 (0.668) |     2.85 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           21 |     2080 | 2024-05-16 | Virtus.pro         | W   | 0.653      | 0.769        | 0.498 (0.250)    | -                | 1 (0.653) |     5.03 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           20 |     2185 | 2024-05-14 | BetBoom            | W   | 0.641      | 0.769        | -                | 0.526 (0.259)    | 1 (0.641) |     1.07 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           19 |     2228 | 2024-05-12 | Vitality           | W   | 0.628      | 0.889        | 0.647 (0.361)    | 0.375 (0.209)    | 1 (0.628) |     9.63 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           18 |     2250 | 2024-05-11 | Complexity         | W   | 0.622      | 0.889        | 0.341 (0.189)    | 0.372 (0.206)    | 1 (0.622) |     4.92 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           17 |     2298 | 2024-05-09 | G2                 | W   | 0.609      | 0.889        | 1.000 (0.541)    | 0.489 (0.265)    | 1 (0.609) |    11.88 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           16 |     2391 | 2024-05-04 | Liquid             | W   | 0.575      | 0.889        | 0.383 (0.196)    | 0.448 (0.229)    | -         |     3.40 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           15 |     2459 | 2024-05-01 | GamerLegion        | W   | 0.555      | -            | -                | -                | -         |     0.29 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           14 |     2490 | 2024-04-30 | Bad News Kangaroos | W   | 0.547      | -            | -                | -                | -         |     0.05 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           13 |     2910 | 2024-04-14 | FaZe               | L   | 0.440      | -            | -                | -                | -         |    -9.78 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           12 |     2927 | 2024-04-13 | G2                 | W   | 0.432      | 0.624        | 1.000 (0.270)    | -                | -         |     9.09 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           11 |     3023 | 2024-04-10 | Liquid             | W   | 0.413      | -            | -                | -                | -         |     2.56 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           10 |     3097 | 2024-04-08 | FURIA              | W   | 0.401      | -            | -                | -                | -         |     3.77 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            9 |     3108 | 2024-04-07 | TYLOO              | W   | 0.399      | -            | -                | -                | -         |     0.03 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            8 |     3309 | 2024-03-29 | G2                 | L   | 0.336      | -            | -                | -                | -         |    -3.30 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            7 |     3432 | 2024-03-22 | Complexity         | W   | 0.288      | -            | -                | -                | -         |     2.26 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            6 |     3452 | 2024-03-21 | Eternal Fire       | W   | 0.282      | 1.000        | 0.739 (0.208)    | -                | -         |     2.76 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            5 |     3462 | 2024-03-21 | Gaimin Gladiators  | W   | 0.281      | -            | -                | -                | -         |     0.07 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            4 |     4143 | 2024-02-20 | Spirit             | W   | 0.082      | -            | -                | -                | -         |     1.51 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            3 |     4165 | 2024-02-19 | Gaimin Gladiators  | W   | 0.076      | -            | -                | -                | -         |     0.02 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            2 |     4178 | 2024-02-19 | ex-Guild Eagles    | W   | 0.074      | -            | -                | -                | -         |     0.01 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            1 |     4373 | 2024-02-10 | FaZe               | L   | 0.015      | -            | -                | -                | -         |    -0.33 | Brollan, Jimpphat, siuhy, torzsi, xertioN |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($433,784.03)
- Divide that value by the 5th highest value among all rosters ($320,603.98)
- The final value (1.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-21 |      1.000 | $85,000.00     | $85,000.00      |
| 2024-06-02 |      0.769 | $5,000.00      | $3,844.44       |
| 2024-05-19 |      0.674 | $300,000.00    | $202,250.00     |
| 2024-05-12 |      0.628 | $170,000.00    | $106,769.44     |
| 2024-04-14 |      0.440 | $42,000.00     | $18,486.81      |
| 2024-03-31 |      0.349 | $45,000.00     | $15,700.00      |
| 2024-02-11 |      0.022 | $80,000.00     | $1,733.33       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
