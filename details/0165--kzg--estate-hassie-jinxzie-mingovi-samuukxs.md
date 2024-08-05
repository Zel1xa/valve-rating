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
Final Rank Value (671.8) = Starting Rank Value (705.7) + Head To Head Adjustments (-34.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.306[<sup>1</sup>](#table2)
- Bounty Collected: 0.226[<sup>2</sup>](#table1)
- Opponent Network: 0.031[<sup>2</sup>](#table1)
- LAN Wins: 0.034[<sup>2</sup>](#table1)

The average of these factors is 0.149<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 705.7
- 400 + ( ( 0.149 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 705.7


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
|           35 |      248 | 2024-07-30 | Above The Rest     | L   | 1.000      | -            | -                | -                | -         |   -22.78 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           34 |      469 | 2024-07-23 | DXA                | W   | 1.000      | 0.333        | 0.002 (0.001)    | 0.222 (0.074)    | 0 (0.000) |    14.49 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           33 |      473 | 2024-07-23 | DXA                | W   | 1.000      | 0.333        | 0.002 (0.001)    | 0.222 (0.074)    | 0 (0.000) |    15.83 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           32 |      496 | 2024-07-22 | Arcade             | W   | 1.000      | 0.333        | 0.002 (0.001)    | 0.134 (0.045)    | 0 (0.000) |    15.52 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           31 |      498 | 2024-07-22 | Arcade             | L   | 1.000      | -            | -                | -                | -         |   -16.01 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           30 |     1869 | 2024-05-22 | Bad News Kangaroos | L   | 0.698      | -            | -                | -                | -         |    -6.67 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           29 |     1874 | 2024-05-22 | Bad News Kangaroos | L   | 0.697      | -            | -                | -                | -         |    -7.03 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           28 |     2124 | 2024-05-15 | DXA                | W   | 0.651      | 0.333        | 0.002 (0.000)    | 0.222 (0.048)    | 0 (0.000) |     9.61 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           27 |     2131 | 2024-05-15 | DXA                | W   | 0.651      | 0.333        | 0.002 (0.000)    | 0.222 (0.048)    | 0 (0.000) |    10.18 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           26 |     2321 | 2024-05-08 | Rooster            | L   | 0.604      | -            | -                | -                | -         |    -5.92 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           25 |     2324 | 2024-05-08 | Rooster            | L   | 0.604      | -            | -                | -                | -         |    -6.20 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           24 |     2577 | 2024-04-26 | Rooster            | L   | 0.524      | -            | -                | -                | -         |    -5.61 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           23 |     2581 | 2024-04-25 | MIBR               | L   | 0.522      | -            | -                | -                | -         |    -0.21 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           22 |     2837 | 2024-04-17 | Mindfreak          | L   | 0.464      | -            | -                | -                | -         |    -7.10 | Hassie, Jynx, KRAXYT, Mingovi, Samuukxs    |
|           21 |     3011 | 2024-04-10 | Canon Event        | W   | 0.418      | 0.333        | 0.000 (0.000)    | -                | 0 (0.000) |     3.37 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           20 |     3016 | 2024-04-10 | Canon Event        | W   | 0.417      | 0.333        | 0.000 (0.000)    | -                | 0 (0.000) |     3.46 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           19 |     3237 | 2024-04-03 | Vantage            | L   | 0.371      | -            | -                | -                | -         |    -6.17 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           18 |     3244 | 2024-04-03 | Vantage            | L   | 0.371      | -            | -                | -                | -         |    -6.37 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           17 |     3370 | 2024-03-27 | FlyQuest           | L   | 0.324      | -            | -                | -                | -         |    -0.70 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           16 |     3375 | 2024-03-27 | FlyQuest           | L   | 0.324      | -            | -                | -                | -         |    -0.70 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           15 |     3418 | 2024-03-23 | Arcade             | W   | 0.297      | 0.315        | 0.002 (0.000)    | 0.134 (0.013)    | 1 (0.297) |     4.63 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           14 |     3419 | 2024-03-23 | DXA                | L   | 0.297      | -            | -                | -                | -         |    -4.64 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           13 |     3639 | 2024-03-13 | RKON               | L   | 0.231      | -            | -                | -                | -         |    -5.42 | bebest, Estate, Hassie, Mingovi, Samuukxs  |
|           12 |     3646 | 2024-03-13 | RKON               | W   | 0.231      | 0.333        | -                | 0.030 (0.002)    | 0 (0.000) |     1.87 | bebest, Estate, Hassie, Mingovi, Samuukxs  |
|           11 |     3814 | 2024-03-06 | Arcade             | L   | 0.185      | -            | -                | -                | -         |    -3.01 | Estate, Hassie, Mingovi, pain, Samuukxs    |
|           10 |     3820 | 2024-03-06 | Arcade             | L   | 0.184      | -            | -                | -                | -         |    -3.06 | Estate, Hassie, Mingovi, pain, Samuukxs    |
|            9 |     4117 | 2024-02-21 | Mindfreak          | L   | 0.091      | -            | -                | -                | -         |    -1.57 | Estate, Hassie, Mingovi, pain, Samuukxs    |
|            8 |     4122 | 2024-02-21 | Mindfreak          | L   | 0.091      | -            | -                | -                | -         |    -1.58 | Estate, Hassie, Mingovi, pain, Samuukxs    |
|            7 |     4150 | 2024-02-20 | Cringexe           | L   | 0.084      | -            | -                | -                | -         |    -2.06 | dpr, Estate, Hassie, Mingovi, Samuukxs     |
|            6 |     4195 | 2024-02-18 | Arcade             | L   | 0.071      | -            | -                | -                | -         |    -1.20 | dpr, Hassie, Lexon, Mingovi, Samuukxs      |
|            5 |     4249 | 2024-02-16 | sunday school      | L   | 0.058      | -            | -                | -                | -         |    -1.10 | Estate, Hassie, Mingovi, pain, Samuukxs    |
|            4 |     4277 | 2024-02-15 | sunday school      | W   | 0.051      | 0.143        | 0.003 (0.000)    | -                | 0 (0.000) |     0.64 | Estate, Hassie, Mingovi, pain, Samuukxs    |
|            3 |     4278 | 2024-02-14 | Vantage            | W   | 0.050      | 0.143        | -                | 0.067 (0.000)    | -         |     0.67 | Estate, Hassie, Mingovi, pain, Samuukxs    |
|            2 |     4319 | 2024-02-13 | Mindfreak          | W   | 0.043      | 0.143        | 0.004 (0.000)    | 0.049 (0.000)    | -         |     0.61 | Estate, Hassie, Mingovi, pain, Samuukxs    |
|            1 |     4344 | 2024-02-13 | RKON               | W   | 0.037      | 0.143        | -                | 0.030 (0.000)    | -         |     0.28 | Estate, Hassie, Mingovi, pain, Samuukxs    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,737.30)
- Divide that value by the 5th highest value among all rosters ($321,880.58)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-08 |      0.817 | $450.00        | $367.44         |
| 2024-04-28 |      0.537 | $2,000.00      | $1,074.81       |
| 2024-03-23 |      0.297 | $992.00        | $295.05         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
