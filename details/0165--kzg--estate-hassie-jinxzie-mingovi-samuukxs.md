### Roster Details<br />
Team Name: KZG<br />
Roster: Estate, Hassie, JiNxZiE, Mingovi, Samuukxs<br />
Global Rank: [165](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [16]( ../standings_asia.md)<br />
<br />
Final Rank Value:  671.8<br />
<br />
Final Rank Value (671.8) = Starting Rank Value (705.8) + Head To Head Adjustments (-34.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.306[<sup>1</sup>](#table2)
- Bounty Collected: 0.226[<sup>2</sup>](#table1)
- Opponent Network: 0.031[<sup>2</sup>](#table1)
- LAN Wins: 0.034[<sup>2</sup>](#table1)

The average of these factors is 0.149<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 705.8
- 400 + ( ( 0.149 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 705.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent           | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                     |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           35 |      247 | 2024-07-30 | Above The Rest     | L   | 1.000      | -            | -                | -                | -         |   -22.78 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           34 |      468 | 2024-07-23 | DXA                | W   | 1.000      | 0.333        | 0.002 (0.001)    | 0.222 (0.074)    | 0 (0.000) |    14.49 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           33 |      472 | 2024-07-23 | DXA                | W   | 1.000      | 0.333        | 0.002 (0.001)    | 0.222 (0.074)    | 0 (0.000) |    15.83 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           32 |      495 | 2024-07-22 | Arcade             | W   | 1.000      | 0.333        | 0.002 (0.001)    | 0.134 (0.045)    | 0 (0.000) |    15.52 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           31 |      497 | 2024-07-22 | Arcade             | L   | 1.000      | -            | -                | -                | -         |   -16.01 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           30 |     1868 | 2024-05-22 | Bad News Kangaroos | L   | 0.698      | -            | -                | -                | -         |    -6.67 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           29 |     1873 | 2024-05-22 | Bad News Kangaroos | L   | 0.698      | -            | -                | -                | -         |    -7.03 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           28 |     2123 | 2024-05-15 | DXA                | W   | 0.651      | 0.333        | 0.002 (0.000)    | 0.222 (0.048)    | 0 (0.000) |     9.62 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           27 |     2130 | 2024-05-15 | DXA                | W   | 0.651      | 0.333        | 0.002 (0.000)    | 0.222 (0.048)    | 0 (0.000) |    10.19 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           26 |     2320 | 2024-05-08 | Rooster            | L   | 0.605      | -            | -                | -                | -         |    -5.92 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           25 |     2323 | 2024-05-08 | Rooster            | L   | 0.604      | -            | -                | -                | -         |    -6.20 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           24 |     2576 | 2024-04-26 | Rooster            | L   | 0.525      | -            | -                | -                | -         |    -5.62 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           23 |     2580 | 2024-04-25 | MIBR               | L   | 0.523      | -            | -                | -                | -         |    -0.21 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           22 |     2836 | 2024-04-17 | Mindfreak          | L   | 0.465      | -            | -                | -                | -         |    -7.11 | Hassie, Jynx, KRAXYT, Mingovi, Samuukxs    |
|           21 |     3010 | 2024-04-10 | Canon Event        | W   | 0.418      | 0.333        | 0.000 (0.000)    | -                | 0 (0.000) |     3.37 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           20 |     3015 | 2024-04-10 | Canon Event        | W   | 0.418      | 0.333        | 0.000 (0.000)    | -                | 0 (0.000) |     3.47 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           19 |     3236 | 2024-04-03 | Vantage            | L   | 0.372      | -            | -                | -                | -         |    -6.18 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           18 |     3243 | 2024-04-03 | Vantage            | L   | 0.371      | -            | -                | -                | -         |    -6.38 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           17 |     3369 | 2024-03-27 | FlyQuest           | L   | 0.325      | -            | -                | -                | -         |    -0.70 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           16 |     3374 | 2024-03-27 | FlyQuest           | L   | 0.325      | -            | -                | -                | -         |    -0.70 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           15 |     3417 | 2024-03-23 | Arcade             | W   | 0.298      | 0.315        | 0.002 (0.000)    | 0.134 (0.013)    | 1 (0.298) |     4.64 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           14 |     3418 | 2024-03-23 | DXA                | L   | 0.297      | -            | -                | -                | -         |    -4.65 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           13 |     3638 | 2024-03-13 | RKON               | L   | 0.232      | -            | -                | -                | -         |    -5.43 | bebest, Estate, Hassie, Mingovi, Samuukxs  |
|           12 |     3645 | 2024-03-13 | RKON               | W   | 0.231      | 0.333        | -                | 0.030 (0.002)    | 0 (0.000) |     1.88 | bebest, Estate, Hassie, Mingovi, Samuukxs  |
|           11 |     3813 | 2024-03-06 | Arcade             | L   | 0.185      | -            | -                | -                | -         |    -3.02 | Estate, Hassie, Mingovi, pain, Samuukxs    |
|           10 |     3819 | 2024-03-06 | Arcade             | L   | 0.185      | -            | -                | -                | -         |    -3.06 | Estate, Hassie, Mingovi, pain, Samuukxs    |
|            9 |     4116 | 2024-02-21 | Mindfreak          | L   | 0.092      | -            | -                | -                | -         |    -1.58 | Estate, Hassie, Mingovi, pain, Samuukxs    |
|            8 |     4121 | 2024-02-21 | Mindfreak          | L   | 0.091      | -            | -                | -                | -         |    -1.59 | Estate, Hassie, Mingovi, pain, Samuukxs    |
|            7 |     4149 | 2024-02-20 | Cringexe           | L   | 0.084      | -            | -                | -                | -         |    -2.07 | dpr, Estate, Hassie, Mingovi, Samuukxs     |
|            6 |     4194 | 2024-02-18 | Arcade             | L   | 0.071      | -            | -                | -                | -         |    -1.21 | dpr, Hassie, Lexon, Mingovi, Samuukxs      |
|            5 |     4248 | 2024-02-16 | sunday school      | L   | 0.058      | -            | -                | -                | -         |    -1.10 | Estate, Hassie, Mingovi, pain, Samuukxs    |
|            4 |     4276 | 2024-02-15 | sunday school      | W   | 0.051      | 0.143        | 0.003 (0.000)    | -                | 0 (0.000) |     0.64 | Estate, Hassie, Mingovi, pain, Samuukxs    |
|            3 |     4277 | 2024-02-14 | Vantage            | W   | 0.050      | 0.143        | -                | 0.067 (0.000)    | -         |     0.67 | Estate, Hassie, Mingovi, pain, Samuukxs    |
|            2 |     4318 | 2024-02-13 | Mindfreak          | W   | 0.044      | 0.143        | 0.004 (0.000)    | 0.049 (0.000)    | -         |     0.61 | Estate, Hassie, Mingovi, pain, Samuukxs    |
|            1 |     4343 | 2024-02-13 | RKON               | W   | 0.038      | 0.143        | -                | 0.030 (0.000)    | -         |     0.29 | Estate, Hassie, Mingovi, pain, Samuukxs    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,738.74)
- Divide that value by the 5th highest value among all rosters ($322,004.12)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-08 |      0.817 | $450.00        | $367.63         |
| 2024-04-28 |      0.538 | $2,000.00      | $1,075.65       |
| 2024-03-23 |      0.298 | $992.00        | $295.46         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
