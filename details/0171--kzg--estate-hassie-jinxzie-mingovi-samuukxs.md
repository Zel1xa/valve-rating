### Roster Details<br />
Team Name: KZG<br />
Roster: Estate, Hassie, JiNxZiE, Mingovi, Samuukxs<br />
Global Rank: [171](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [16]( ../standings_asia.md)<br />
<br />
Final Rank Value:  663.7<br />
<br />
Final Rank Value (663.7) = Starting Rank Value (705.7) + Head To Head Adjustments (-42.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.306[<sup>1</sup>](#table2)
- Bounty Collected: 0.225[<sup>2</sup>](#table1)
- Opponent Network: 0.030[<sup>2</sup>](#table1)
- LAN Wins: 0.034[<sup>2</sup>](#table1)

The average of these factors is 0.149<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 705.7
- 400 + ( ( 0.149 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 705.7


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
|           35 |      256 | 2024-07-30 | Above The Rest     | L   | 1.000      | -            | -                | -                | -         |   -22.48 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           34 |      477 | 2024-07-23 | DXA                | W   | 1.000      | 0.333        | 0.002 (0.001)    | 0.217 (0.072)    | 0 (0.000) |    14.27 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           33 |      481 | 2024-07-23 | DXA                | W   | 1.000      | 0.333        | 0.002 (0.001)    | 0.217 (0.072)    | 0 (0.000) |    15.59 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           32 |      504 | 2024-07-22 | Arcade             | W   | 1.000      | 0.333        | 0.002 (0.001)    | 0.130 (0.043)    | 0 (0.000) |    14.98 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           31 |      506 | 2024-07-22 | Arcade             | L   | 1.000      | -            | -                | -                | -         |   -16.59 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           30 |     1877 | 2024-05-22 | Bad News Kangaroos | L   | 0.692      | -            | -                | -                | -         |    -9.64 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           29 |     1882 | 2024-05-22 | Bad News Kangaroos | L   | 0.692      | -            | -                | -                | -         |   -10.25 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           28 |     2132 | 2024-05-15 | DXA                | W   | 0.646      | 0.333        | 0.002 (0.000)    | 0.217 (0.047)    | 0 (0.000) |     9.34 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           27 |     2139 | 2024-05-15 | DXA                | W   | 0.645      | 0.333        | 0.002 (0.000)    | 0.217 (0.047)    | 0 (0.000) |     9.89 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           26 |     2329 | 2024-05-08 | Rooster            | L   | 0.599      | -            | -                | -                | -         |    -5.96 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           25 |     2332 | 2024-05-08 | Rooster            | L   | 0.599      | -            | -                | -                | -         |    -6.25 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           24 |     2585 | 2024-04-26 | Rooster            | L   | 0.519      | -            | -                | -                | -         |    -5.65 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           23 |     2589 | 2024-04-25 | MIBR               | L   | 0.517      | -            | -                | -                | -         |    -0.21 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           22 |     2845 | 2024-04-17 | Mindfreak          | L   | 0.459      | -            | -                | -                | -         |    -7.18 | Hassie, Jynx, KRAXYT, Mingovi, Samuukxs    |
|           21 |     3019 | 2024-04-10 | Canon Event        | W   | 0.412      | 0.333        | 0.000 (0.000)    | -                | 0 (0.000) |     3.33 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           20 |     3024 | 2024-04-10 | Canon Event        | W   | 0.412      | 0.333        | 0.000 (0.000)    | -                | 0 (0.000) |     3.42 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           19 |     3245 | 2024-04-03 | Vantage            | L   | 0.366      | -            | -                | -                | -         |    -6.08 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           18 |     3252 | 2024-04-03 | Vantage            | L   | 0.365      | -            | -                | -                | -         |    -6.28 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           17 |     3378 | 2024-03-27 | FlyQuest           | L   | 0.319      | -            | -                | -                | -         |    -0.70 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           16 |     3383 | 2024-03-27 | FlyQuest           | L   | 0.319      | -            | -                | -                | -         |    -0.70 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           15 |     3426 | 2024-03-23 | Arcade             | W   | 0.292      | 0.315        | 0.002 (0.000)    | 0.130 (0.012)    | 1 (0.292) |     4.41 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           14 |     3427 | 2024-03-23 | DXA                | L   | 0.292      | -            | -                | -                | -         |    -4.67 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           13 |     3647 | 2024-03-13 | RKON               | L   | 0.226      | -            | -                | -                | -         |    -5.30 | bebest, Estate, Hassie, Mingovi, Samuukxs  |
|           12 |     3654 | 2024-03-13 | RKON               | W   | 0.226      | 0.333        | -                | 0.029 (0.002)    | 0 (0.000) |     1.83 | bebest, Estate, Hassie, Mingovi, Samuukxs  |
|           11 |     3822 | 2024-03-06 | Arcade             | L   | 0.179      | -            | -                | -                | -         |    -3.01 | Estate, Hassie, Mingovi, pain, Samuukxs    |
|           10 |     3828 | 2024-03-06 | Arcade             | L   | 0.179      | -            | -                | -                | -         |    -3.06 | Estate, Hassie, Mingovi, pain, Samuukxs    |
|            9 |     4125 | 2024-02-21 | Mindfreak          | L   | 0.086      | -            | -                | -                | -         |    -1.49 | Estate, Hassie, Mingovi, pain, Samuukxs    |
|            8 |     4130 | 2024-02-21 | Mindfreak          | L   | 0.086      | -            | -                | -                | -         |    -1.49 | Estate, Hassie, Mingovi, pain, Samuukxs    |
|            7 |     4158 | 2024-02-20 | Cringexe           | L   | 0.079      | -            | -                | -                | -         |    -1.93 | dpr, Estate, Hassie, Mingovi, Samuukxs     |
|            6 |     4203 | 2024-02-18 | Arcade             | L   | 0.065      | -            | -                | -                | -         |    -1.14 | dpr, Hassie, Lexon, Mingovi, Samuukxs      |
|            5 |     4257 | 2024-02-16 | sunday school      | L   | 0.052      | -            | -                | -                | -         |    -1.00 | Estate, Hassie, Mingovi, pain, Samuukxs    |
|            4 |     4285 | 2024-02-15 | sunday school      | W   | 0.046      | 0.143        | 0.003 (0.000)    | -                | 0 (0.000) |     0.57 | Estate, Hassie, Mingovi, pain, Samuukxs    |
|            3 |     4286 | 2024-02-14 | Vantage            | W   | 0.044      | 0.143        | -                | 0.064 (0.000)    | -         |     0.60 | Estate, Hassie, Mingovi, pain, Samuukxs    |
|            2 |     4327 | 2024-02-13 | Mindfreak          | W   | 0.038      | 0.143        | 0.004 (0.000)    | 0.047 (0.000)    | -         |     0.54 | Estate, Hassie, Mingovi, pain, Samuukxs    |
|            1 |     4352 | 2024-02-13 | RKON               | W   | 0.032      | 0.143        | -                | 0.029 (0.000)    | -         |     0.24 | Estate, Hassie, Mingovi, pain, Samuukxs    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,719.30)
- Divide that value by the 5th highest value among all rosters ($320,329.44)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-08 |      0.811 | $450.00        | $365.08         |
| 2024-04-28 |      0.532 | $2,000.00      | $1,064.35       |
| 2024-03-23 |      0.292 | $992.00        | $289.86         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
