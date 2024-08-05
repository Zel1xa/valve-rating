### Roster Details<br />
Team Name: MOUZ<br />
Roster: Brollan, Jimpphat, siuhy, torzsi, xertioN<br />
Global Rank: [4](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [4]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1870.3<br />
<br />
Final Rank Value (1870.3) = Starting Rank Value (1845.0) + Head To Head Adjustments (25.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 1.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.659[<sup>2</sup>](#table1)
- Opponent Network: 0.329[<sup>2</sup>](#table1)
- LAN Wins: 0.836[<sup>2</sup>](#table1)

The average of these factors is 0.706<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1845.0
- 400 + ( ( 0.706 - 0.000 ) / ( 0.781 - 0.000 ) ) * 1600 = 1845.0


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
|           29 |      530 | 2024-07-20 | Natus Vincere      | L   | 1.000      | -            | -                | -                | -         |   -13.18 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           28 |      573 | 2024-07-19 | FURIA              | W   | 1.000      | 1.000        | 0.284 (0.284)    | 0.487 (0.487)    | 1 (1.000) |     5.69 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           27 |      710 | 2024-07-17 | Sashi              | W   | 1.000      | 1.000        | 0.184 (0.184)    | 0.996 (0.996)    | 1 (1.000) |     0.61 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           26 |     1709 | 2024-05-28 | G2                 | L   | 0.743      | -            | -                | -                | -         |   -10.24 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           25 |     1730 | 2024-05-27 | Complexity         | W   | 0.737      | 0.624        | -                | 0.378 (0.174)    | 1 (0.737) |     5.06 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           24 |     1739 | 2024-05-27 | 9z                 | L   | 0.735      | -            | -                | -                | -         |   -21.58 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           23 |     1958 | 2024-05-19 | Spirit             | W   | 0.680      | 0.769        | 1.000 (0.523)    | 0.458 (0.239)    | 1 (0.680) |    10.96 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           22 |     1986 | 2024-05-18 | HEROIC             | W   | 0.674      | 0.769        | -                | 0.370 (0.192)    | 1 (0.674) |     2.87 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           21 |     2065 | 2024-05-16 | Virtus.pro         | W   | 0.659      | 0.769        | 0.498 (0.252)    | -                | 1 (0.659) |     5.06 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           20 |     2170 | 2024-05-14 | BetBoom            | W   | 0.647      | 0.769        | -                | 0.536 (0.266)    | 1 (0.647) |     1.08 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           19 |     2213 | 2024-05-12 | Vitality           | W   | 0.634      | 0.889        | 0.648 (0.365)    | 0.381 (0.215)    | 1 (0.634) |     9.69 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           18 |     2235 | 2024-05-11 | Complexity         | W   | 0.628      | 0.889        | 0.342 (0.191)    | 0.378 (0.211)    | 1 (0.628) |     4.95 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           17 |     2283 | 2024-05-09 | G2                 | W   | 0.615      | 0.889        | 1.000 (0.546)    | 0.496 (0.271)    | 1 (0.615) |    11.92 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           16 |     2376 | 2024-05-04 | Liquid             | W   | 0.581      | 0.889        | 0.384 (0.198)    | 0.456 (0.236)    | -         |     3.41 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           15 |     2444 | 2024-05-01 | GamerLegion        | W   | 0.560      | -            | -                | -                | -         |     0.30 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           14 |     2475 | 2024-04-30 | Bad News Kangaroos | W   | 0.553      | -            | -                | -                | -         |     0.05 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           13 |     2895 | 2024-04-14 | FaZe               | L   | 0.446      | -            | -                | -                | -         |    -9.88 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           12 |     2912 | 2024-04-13 | G2                 | W   | 0.438      | 0.624        | 1.000 (0.274)    | -                | -         |     9.16 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           11 |     3008 | 2024-04-10 | Liquid             | W   | 0.419      | -            | -                | -                | -         |     2.58 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           10 |     3082 | 2024-04-08 | FURIA              | W   | 0.407      | -            | -                | -                | -         |     3.80 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            9 |     3093 | 2024-04-07 | TYLOO              | W   | 0.405      | -            | -                | -                | -         |     0.03 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            8 |     3294 | 2024-03-29 | G2                 | L   | 0.342      | -            | -                | -                | -         |    -3.39 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            7 |     3417 | 2024-03-22 | Complexity         | W   | 0.294      | -            | -                | -                | -         |     2.30 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            6 |     3437 | 2024-03-21 | Eternal Fire       | W   | 0.288      | 1.000        | 0.740 (0.213)    | -                | -         |     2.80 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            5 |     3447 | 2024-03-21 | Gaimin Gladiators  | W   | 0.286      | -            | -                | -                | -         |     0.07 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            4 |     4128 | 2024-02-20 | Spirit             | W   | 0.088      | -            | -                | -                | -         |     1.61 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            3 |     4150 | 2024-02-19 | Gaimin Gladiators  | W   | 0.082      | -            | -                | -                | -         |     0.02 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            2 |     4163 | 2024-02-19 | ex-Guild Eagles    | W   | 0.079      | -            | -                | -                | -         |     0.01 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            1 |     4358 | 2024-02-10 | FaZe               | L   | 0.021      | -            | -                | -                | -         |    -0.46 | Brollan, Jimpphat, siuhy, torzsi, xertioN |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($437,529.03)
- Divide that value by the 5th highest value among all rosters ($322,333.56)
- The final value (1.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-21 |      1.000 | $85,000.00     | $85,000.00      |
| 2024-06-02 |      0.775 | $5,000.00      | $3,873.61       |
| 2024-05-19 |      0.680 | $300,000.00    | $204,000.00     |
| 2024-05-12 |      0.634 | $170,000.00    | $107,761.11     |
| 2024-04-14 |      0.446 | $42,000.00     | $18,731.81      |
| 2024-03-31 |      0.355 | $45,000.00     | $15,962.50      |
| 2024-02-11 |      0.028 | $80,000.00     | $2,200.00       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
