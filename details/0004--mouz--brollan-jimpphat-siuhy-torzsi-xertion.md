### Roster Details<br />
Team Name: MOUZ<br />
Roster: Brollan, Jimpphat, siuhy, torzsi, xertioN<br />
Global Rank: [4](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [4]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1868.1<br />
<br />
Final Rank Value (1868.1) = Starting Rank Value (1844.7) + Head To Head Adjustments (23.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 1.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.658[<sup>2</sup>](#table1)
- Opponent Network: 0.330[<sup>2</sup>](#table1)
- LAN Wins: 0.839[<sup>2</sup>](#table1)

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
|           30 |      478 | 2024-07-20 | Natus Vincere      | L   | 1.000      | -            | -                | -                | -         |   -13.24 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           29 |      521 | 2024-07-19 | FURIA              | W   | 1.000      | 1.000        | 0.284 (0.284)    | 0.491 (0.491)    | 1 (1.000) |     5.58 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           28 |      658 | 2024-07-17 | Sashi              | W   | 1.000      | 1.000        | 0.184 (0.184)    | 0.964 (0.964)    | 1 (1.000) |     0.61 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           27 |     1656 | 2024-05-28 | G2                 | L   | 0.754      | -            | -                | -                | -         |   -10.40 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           26 |     1677 | 2024-05-27 | Complexity         | W   | 0.747      | 0.624        | -                | 0.380 (0.177)    | 1 (0.747) |     4.97 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           25 |     1686 | 2024-05-27 | 9z                 | L   | 0.746      | -            | -                | -                | -         |   -21.88 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           24 |     1905 | 2024-05-19 | Spirit             | W   | 0.691      | 0.769        | 1.000 (0.531)    | 0.461 (0.244)    | 1 (0.691) |    11.15 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           23 |     1933 | 2024-05-18 | HEROIC             | W   | 0.684      | 0.769        | -                | 0.375 (0.197)    | 1 (0.684) |     2.92 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           22 |     2012 | 2024-05-16 | Virtus.pro         | W   | 0.670      | 0.769        | 0.496 (0.255)    | -                | 1 (0.670) |     5.15 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           21 |     2117 | 2024-05-14 | BetBoom            | W   | 0.657      | 0.769        | -                | 0.543 (0.274)    | 1 (0.657) |     1.12 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           20 |     2160 | 2024-05-12 | Vitality           | W   | 0.644      | 0.889        | 0.649 (0.372)    | 0.383 (0.219)    | 1 (0.644) |     9.80 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           19 |     2182 | 2024-05-11 | Complexity         | W   | 0.639      | 0.889        | 0.311 (0.176)    | 0.380 (0.216)    | 1 (0.639) |     4.93 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           18 |     2230 | 2024-05-09 | G2                 | W   | 0.625      | 0.889        | 1.000 (0.556)    | 0.498 (0.277)    | 1 (0.625) |    12.12 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           17 |     2323 | 2024-05-04 | Liquid             | W   | 0.592      | 0.889        | 0.316 (0.166)    | 0.461 (0.243)    | -         |     2.35 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           16 |     2391 | 2024-05-01 | GamerLegion        | W   | 0.571      | -            | -                | -                | -         |     0.31 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           15 |     2422 | 2024-04-30 | Bad News Kangaroos | W   | 0.563      | -            | -                | -                | -         |     0.04 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           14 |     2841 | 2024-04-14 | FaZe               | L   | 0.457      | -            | -                | -                | -         |   -10.07 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           13 |     2858 | 2024-04-13 | G2                 | W   | 0.449      | 0.624        | 1.000 (0.280)    | -                | -         |     9.38 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           12 |     2954 | 2024-04-10 | Liquid             | W   | 0.429      | -            | -                | -                | -         |     1.73 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           11 |     3028 | 2024-04-08 | FURIA              | W   | 0.417      | -            | -                | -                | -         |     3.84 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|           10 |     3039 | 2024-04-07 | TYLOO              | W   | 0.415      | -            | -                | -                | -         |     0.03 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            9 |     3240 | 2024-03-29 | G2                 | L   | 0.352      | -            | -                | -                | -         |    -3.50 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            8 |     3363 | 2024-03-22 | Complexity         | W   | 0.304      | -            | -                | -                | -         |     2.30 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            7 |     3383 | 2024-03-21 | Eternal Fire       | W   | 0.298      | 1.000        | 0.743 (0.222)    | -                | -         |     2.93 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            6 |     3393 | 2024-03-21 | Gaimin Gladiators  | W   | 0.297      | -            | -                | -                | -         |     0.08 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            5 |     4073 | 2024-02-20 | Spirit             | W   | 0.098      | -            | -                | -                | -         |     1.80 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            4 |     4095 | 2024-02-19 | Gaimin Gladiators  | W   | 0.092      | -            | -                | -                | -         |     0.02 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            3 |     4108 | 2024-02-19 | ex-Guild Eagles    | W   | 0.090      | -            | -                | -                | -         |     0.01 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            2 |     4302 | 2024-02-10 | FaZe               | L   | 0.031      | -            | -                | -                | -         |    -0.70 | Brollan, Jimpphat, siuhy, torzsi, xertioN |
|            1 |     4345 | 2024-02-06 | ENCE               | W   | 0.005      | -            | -                | -                | -         |     0.02 | Brollan, Jimpphat, siuhy, torzsi, xertioN |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($444,305.69)
- Divide that value by the 5th highest value among all rosters ($325,463.29)
- The final value (1.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-21 |      1.000 | $85,000.00     | $85,000.00      |
| 2024-06-02 |      0.785 | $5,000.00      | $3,926.39       |
| 2024-05-19 |      0.691 | $300,000.00    | $207,166.67     |
| 2024-05-12 |      0.644 | $170,000.00    | $109,555.56     |
| 2024-04-14 |      0.457 | $42,000.00     | $19,175.14      |
| 2024-03-31 |      0.365 | $45,000.00     | $16,437.50      |
| 2024-02-11 |      0.038 | $80,000.00     | $3,044.44       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
