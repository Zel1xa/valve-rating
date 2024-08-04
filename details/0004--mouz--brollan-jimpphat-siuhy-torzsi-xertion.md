### Roster Details<br />
Team Name: MOUZ<br />
Roster: Brollan, Jimpphat, siuhy, torzsi, xertioN<br />
Global Rank: [4](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [4]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1870.7<br />
<br />
Final Rank Value (1870.7) = Starting Rank Value (1845.0) + Head To Head Adjustments (25.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 1.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.660[<sup>2</sup>](#table1)
- Opponent Network: 0.328[<sup>2</sup>](#table1)
- LAN Wins: 0.838[<sup>2</sup>](#table1)

The average of these factors is 0.707<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1845.0
- 400 + ( ( 0.707 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 1845.0


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
|           30 |      512 | 2024-07-20 | Natus Vincere      | L   | 1.000      | -            | -                | -                | -         |   -13.18 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           29 |      555 | 2024-07-19 | FURIA              | W   | 1.000      | 1.000        | 0.284 (0.284)    | 0.490 (0.490)    | 1 (1.000) |     5.62 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           28 |      692 | 2024-07-17 | Sashi              | W   | 1.000      | 1.000        | 0.184 (0.184)    | 0.962 (0.962)    | 1 (1.000) |     0.61 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           27 |     1691 | 2024-05-28 | G2                 | L   | 0.749      | -            | -                | -                | -         |   -10.37 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           26 |     1712 | 2024-05-27 | Complexity         | W   | 0.743      | 0.624        | -                | 0.380 (0.176)    | 1 (0.743) |     5.13 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           25 |     1721 | 2024-05-27 | 9z                 | L   | 0.741      | -            | -                | -                | -         |   -21.76 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           24 |     1940 | 2024-05-19 | Spirit             | W   | 0.686      | 0.769        | 1.000 (0.527)    | 0.460 (0.243)    | 1 (0.686) |    11.06 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           23 |     1968 | 2024-05-18 | HEROIC             | W   | 0.680      | 0.769        | -                | 0.373 (0.195)    | 1 (0.680) |     2.91 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           22 |     2047 | 2024-05-16 | Virtus.pro         | W   | 0.665      | 0.769        | 0.497 (0.254)    | -                | 1 (0.665) |     5.13 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           21 |     2152 | 2024-05-14 | BetBoom            | W   | 0.653      | 0.769        | -                | 0.541 (0.271)    | 1 (0.653) |     1.09 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           20 |     2195 | 2024-05-12 | Vitality           | W   | 0.640      | 0.889        | 0.649 (0.369)    | 0.383 (0.218)    | 1 (0.640) |     9.80 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           19 |     2217 | 2024-05-11 | Complexity         | W   | 0.634      | 0.889        | 0.342 (0.193)    | 0.380 (0.214)    | 1 (0.634) |     5.04 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           18 |     2265 | 2024-05-09 | G2                 | W   | 0.621      | 0.889        | 1.000 (0.552)    | 0.498 (0.275)    | 1 (0.621) |    12.01 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           17 |     2358 | 2024-05-04 | Liquid             | W   | 0.587      | 0.889        | 0.384 (0.201)    | 0.460 (0.240)    | -         |     3.44 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           16 |     2426 | 2024-05-01 | GamerLegion        | W   | 0.566      | -            | -                | -                | -         |     0.30 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           15 |     2457 | 2024-04-30 | Bad News Kangaroos | W   | 0.559      | -            | -                | -                | -         |     0.05 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           14 |     2877 | 2024-04-14 | FaZe               | L   | 0.452      | -            | -                | -                | -         |    -9.95 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           13 |     2894 | 2024-04-13 | G2                 | W   | 0.444      | 0.624        | 1.000 (0.277)    | -                | -         |     9.28 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           12 |     2990 | 2024-04-10 | Liquid             | W   | 0.425      | -            | -                | -                | -         |     2.61 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           11 |     3064 | 2024-04-08 | FURIA              | W   | 0.413      | -            | -                | -                | -         |     3.82 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           10 |     3075 | 2024-04-07 | TYLOO              | W   | 0.411      | -            | -                | -                | -         |     0.03 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            9 |     3276 | 2024-03-29 | G2                 | L   | 0.348      | -            | -                | -                | -         |    -3.45 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            8 |     3399 | 2024-03-22 | Complexity         | W   | 0.300      | -            | -                | -                | -         |     2.36 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            7 |     3419 | 2024-03-21 | Eternal Fire       | W   | 0.294      | 1.000        | 0.742 (0.218)    | -                | -         |     2.88 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            6 |     3429 | 2024-03-21 | Gaimin Gladiators  | W   | 0.292      | -            | -                | -                | -         |     0.08 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            5 |     4110 | 2024-02-20 | Spirit             | W   | 0.094      | -            | -                | -                | -         |     1.73 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            4 |     4132 | 2024-02-19 | Gaimin Gladiators  | W   | 0.088      | -            | -                | -                | -         |     0.02 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            3 |     4145 | 2024-02-19 | ex-Guild Eagles    | W   | 0.085      | -            | -                | -                | -         |     0.01 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            2 |     4340 | 2024-02-10 | FaZe               | L   | 0.027      | -            | -                | -                | -         |    -0.60 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            1 |     4383 | 2024-02-06 | ENCE               | W   | 0.001      | -            | -                | -                | -         |     0.00 | Brollan, Jimpphat, siuhy, torzsi, xertioN |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($441,392.92)
- Divide that value by the 5th highest value among all rosters ($324,118.06)
- The final value (1.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-21 |      1.000 | $85,000.00     | $85,000.00      |
| 2024-06-02 |      0.781 | $5,000.00      | $3,903.70       |
| 2024-05-19 |      0.686 | $300,000.00    | $205,805.56     |
| 2024-05-12 |      0.640 | $170,000.00    | $108,784.26     |
| 2024-04-14 |      0.452 | $42,000.00     | $18,984.58      |
| 2024-03-31 |      0.361 | $45,000.00     | $16,233.33      |
| 2024-02-11 |      0.034 | $80,000.00     | $2,681.48       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
