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
Final Rank Value (1869.8) = Starting Rank Value (1844.7) + Head To Head Adjustments (25.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 1.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.659[<sup>2</sup>](#table1)
- Opponent Network: 0.329[<sup>2</sup>](#table1)
- LAN Wins: 0.838[<sup>2</sup>](#table1)

The average of these factors is 0.707<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1844.7
- 400 + ( ( 0.707 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 1844.7


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
|           30 |      489 | 2024-07-20 | Natus Vincere      | L   | 1.000      | -            | -                | -                | -         |   -13.23 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           29 |      532 | 2024-07-19 | FURIA              | W   | 1.000      | 1.000        | 0.284 (0.284)    | 0.490 (0.490)    | 1 (1.000) |     5.62 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           28 |      669 | 2024-07-17 | Sashi              | W   | 1.000      | 1.000        | 0.184 (0.184)    | 0.962 (0.962)    | 1 (1.000) |     0.61 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           27 |     1668 | 2024-05-28 | G2                 | L   | 0.750      | -            | -                | -                | -         |   -10.36 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           26 |     1689 | 2024-05-27 | Complexity         | W   | 0.743      | 0.624        | -                | 0.380 (0.176)    | 1 (0.743) |     4.95 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           25 |     1698 | 2024-05-27 | 9z                 | L   | 0.742      | -            | -                | -                | -         |   -21.78 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           24 |     1917 | 2024-05-19 | Spirit             | W   | 0.687      | 0.769        | 1.000 (0.528)    | 0.460 (0.243)    | 1 (0.687) |    11.04 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           23 |     1945 | 2024-05-18 | HEROIC             | W   | 0.681      | 0.769        | -                | 0.373 (0.195)    | 1 (0.681) |     2.90 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           22 |     2024 | 2024-05-16 | Virtus.pro         | W   | 0.666      | 0.769        | 0.497 (0.254)    | -                | 1 (0.666) |     5.12 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           21 |     2129 | 2024-05-14 | BetBoom            | W   | 0.653      | 0.769        | -                | 0.541 (0.272)    | 1 (0.653) |     1.10 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           20 |     2172 | 2024-05-12 | Vitality           | W   | 0.641      | 0.889        | 0.649 (0.370)    | 0.383 (0.218)    | 1 (0.641) |     9.83 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           19 |     2194 | 2024-05-11 | Complexity         | W   | 0.635      | 0.889        | 0.310 (0.175)    | 0.380 (0.214)    | 1 (0.635) |     4.86 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           18 |     2242 | 2024-05-09 | G2                 | W   | 0.621      | 0.889        | 1.000 (0.552)    | 0.498 (0.275)    | 1 (0.621) |    12.03 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           17 |     2335 | 2024-05-04 | Liquid             | W   | 0.588      | 0.889        | 0.384 (0.201)    | 0.460 (0.240)    | -         |     3.41 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           16 |     2403 | 2024-05-01 | GamerLegion        | W   | 0.567      | -            | -                | -                | -         |     0.30 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           15 |     2434 | 2024-04-30 | Bad News Kangaroos | W   | 0.560      | -            | -                | -                | -         |     0.05 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           14 |     2854 | 2024-04-14 | FaZe               | L   | 0.453      | -            | -                | -                | -         |    -9.98 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           13 |     2871 | 2024-04-13 | G2                 | W   | 0.445      | 0.624        | 1.000 (0.278)    | -                | -         |     9.30 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           12 |     2967 | 2024-04-10 | Liquid             | W   | 0.426      | -            | -                | -                | -         |     2.59 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           11 |     3041 | 2024-04-08 | FURIA              | W   | 0.413      | -            | -                | -                | -         |     3.82 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           10 |     3052 | 2024-04-07 | TYLOO              | W   | 0.412      | -            | -                | -                | -         |     0.03 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            9 |     3253 | 2024-03-29 | G2                 | L   | 0.349      | -            | -                | -                | -         |    -3.46 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            8 |     3376 | 2024-03-22 | Complexity         | W   | 0.300      | -            | -                | -                | -         |     2.27 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            7 |     3396 | 2024-03-21 | Eternal Fire       | W   | 0.295      | 1.000        | 0.742 (0.219)    | -                | -         |     2.90 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            6 |     3406 | 2024-03-21 | Gaimin Gladiators  | W   | 0.293      | -            | -                | -                | -         |     0.08 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            5 |     4087 | 2024-02-20 | Spirit             | W   | 0.094      | -            | -                | -                | -         |     1.73 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            4 |     4109 | 2024-02-19 | Gaimin Gladiators  | W   | 0.088      | -            | -                | -                | -         |     0.02 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            3 |     4122 | 2024-02-19 | ex-Guild Eagles    | W   | 0.086      | -            | -                | -                | -         |     0.01 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            2 |     4317 | 2024-02-10 | FaZe               | L   | 0.027      | -            | -                | -                | -         |    -0.61 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            1 |     4360 | 2024-02-06 | ENCE               | W   | 0.002      | -            | -                | -                | -         |     0.01 | Brollan, Jimpphat, siuhy, torzsi, xertioN |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($441,883.33)
- Divide that value by the 5th highest value among all rosters ($324,344.55)
- The final value (1.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-21 |      1.000 | $85,000.00     | $85,000.00      |
| 2024-06-02 |      0.782 | $5,000.00      | $3,907.52       |
| 2024-05-19 |      0.687 | $300,000.00    | $206,034.72     |
| 2024-05-12 |      0.641 | $170,000.00    | $108,914.12     |
| 2024-04-14 |      0.453 | $42,000.00     | $19,016.67      |
| 2024-03-31 |      0.362 | $45,000.00     | $16,267.71      |
| 2024-02-11 |      0.034 | $80,000.00     | $2,742.59       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
