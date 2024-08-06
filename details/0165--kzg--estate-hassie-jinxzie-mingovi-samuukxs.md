### Roster Details<br />
Team Name: KZG<br />
Roster: Estate, Hassie, JiNxZiE, Mingovi, Samuukxs<br />
Global Rank: [165](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [16]( ../standings_asia.md)<br />
<br />
Final Rank Value:  672.3<br />
<br />
Final Rank Value (672.3) = Starting Rank Value (705.7) + Head To Head Adjustments (-33.3)<br />

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
|           35 |      268 | 2024-07-30 | Above The Rest     | L   | 1.000      | -            | -                | -                | -         |   -22.79 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           34 |      489 | 2024-07-23 | DXA                | W   | 1.000      | 0.333        | 0.002 (0.001)    | 0.217 (0.072)    | 0 (0.000) |    14.49 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           33 |      493 | 2024-07-23 | DXA                | W   | 1.000      | 0.333        | 0.002 (0.001)    | 0.217 (0.072)    | 0 (0.000) |    15.83 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           32 |      516 | 2024-07-22 | Arcade             | W   | 1.000      | 0.333        | 0.002 (0.001)    | 0.130 (0.043)    | 0 (0.000) |    15.51 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           31 |      518 | 2024-07-22 | Arcade             | L   | 1.000      | -            | -                | -                | -         |   -16.02 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           30 |     1889 | 2024-05-22 | Bad News Kangaroos | L   | 0.692      | -            | -                | -                | -         |    -6.65 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           29 |     1894 | 2024-05-22 | Bad News Kangaroos | L   | 0.692      | -            | -                | -                | -         |    -7.01 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           28 |     2144 | 2024-05-15 | DXA                | W   | 0.645      | 0.333        | 0.002 (0.000)    | 0.217 (0.047)    | 0 (0.000) |     9.53 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           27 |     2151 | 2024-05-15 | DXA                | W   | 0.645      | 0.333        | 0.002 (0.000)    | 0.217 (0.047)    | 0 (0.000) |    10.09 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           26 |     2341 | 2024-05-08 | Rooster            | L   | 0.599      | -            | -                | -                | -         |    -5.89 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           25 |     2344 | 2024-05-08 | Rooster            | L   | 0.598      | -            | -                | -                | -         |    -6.17 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           24 |     2597 | 2024-04-26 | Rooster            | L   | 0.518      | -            | -                | -                | -         |    -5.58 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           23 |     2601 | 2024-04-25 | MIBR               | L   | 0.517      | -            | -                | -                | -         |    -0.22 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           22 |     2857 | 2024-04-17 | Mindfreak          | L   | 0.459      | -            | -                | -                | -         |    -7.02 | Hassie, Jynx, KRAXYT, Mingovi, Samuukxs    |
|           21 |     3031 | 2024-04-10 | Canon Event        | W   | 0.412      | 0.333        | 0.000 (0.000)    | -                | 0 (0.000) |     3.33 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           20 |     3036 | 2024-04-10 | Canon Event        | W   | 0.412      | 0.333        | 0.000 (0.000)    | -                | 0 (0.000) |     3.42 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           19 |     3257 | 2024-04-03 | Vantage            | L   | 0.366      | -            | -                | -                | -         |    -6.08 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           18 |     3264 | 2024-04-03 | Vantage            | L   | 0.365      | -            | -                | -                | -         |    -6.27 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           17 |     3390 | 2024-03-27 | FlyQuest           | L   | 0.319      | -            | -                | -                | -         |    -0.70 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           16 |     3395 | 2024-03-27 | FlyQuest           | L   | 0.319      | -            | -                | -                | -         |    -0.70 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           15 |     3438 | 2024-03-23 | Arcade             | W   | 0.292      | 0.315        | 0.002 (0.000)    | 0.130 (0.012)    | 1 (0.292) |     4.53 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           14 |     3439 | 2024-03-23 | DXA                | L   | 0.291      | -            | -                | -                | -         |    -4.56 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           13 |     3659 | 2024-03-13 | RKON               | L   | 0.226      | -            | -                | -                | -         |    -5.29 | bebest, Estate, Hassie, Mingovi, Samuukxs  |
|           12 |     3666 | 2024-03-13 | RKON               | W   | 0.225      | 0.333        | -                | 0.029 (0.002)    | 0 (0.000) |     1.82 | bebest, Estate, Hassie, Mingovi, Samuukxs  |
|           11 |     3834 | 2024-03-06 | Arcade             | L   | 0.179      | -            | -                | -                | -         |    -2.92 | Estate, Hassie, Mingovi, pain, Samuukxs    |
|           10 |     3840 | 2024-03-06 | Arcade             | L   | 0.179      | -            | -                | -                | -         |    -2.97 | Estate, Hassie, Mingovi, pain, Samuukxs    |
|            9 |     4137 | 2024-02-21 | Mindfreak          | L   | 0.086      | -            | -                | -                | -         |    -1.48 | Estate, Hassie, Mingovi, pain, Samuukxs    |
|            8 |     4142 | 2024-02-21 | Mindfreak          | L   | 0.085      | -            | -                | -                | -         |    -1.48 | Estate, Hassie, Mingovi, pain, Samuukxs    |
|            7 |     4170 | 2024-02-20 | Cringexe           | L   | 0.078      | -            | -                | -                | -         |    -1.92 | dpr, Estate, Hassie, Mingovi, Samuukxs     |
|            6 |     4215 | 2024-02-18 | Arcade             | L   | 0.065      | -            | -                | -                | -         |    -1.10 | dpr, Hassie, Lexon, Mingovi, Samuukxs      |
|            5 |     4269 | 2024-02-16 | sunday school      | L   | 0.052      | -            | -                | -                | -         |    -0.99 | Estate, Hassie, Mingovi, pain, Samuukxs    |
|            4 |     4297 | 2024-02-15 | sunday school      | W   | 0.045      | 0.143        | 0.003 (0.000)    | -                | 0 (0.000) |     0.56 | Estate, Hassie, Mingovi, pain, Samuukxs    |
|            3 |     4298 | 2024-02-14 | Vantage            | W   | 0.044      | 0.143        | -                | 0.064 (0.000)    | -         |     0.59 | Estate, Hassie, Mingovi, pain, Samuukxs    |
|            2 |     4339 | 2024-02-13 | Mindfreak          | W   | 0.038      | 0.143        | 0.004 (0.000)    | 0.047 (0.000)    | -         |     0.53 | Estate, Hassie, Mingovi, pain, Samuukxs    |
|            1 |     4364 | 2024-02-13 | RKON               | W   | 0.032      | 0.143        | -                | 0.029 (0.000)    | -         |     0.24 | Estate, Hassie, Mingovi, pain, Samuukxs    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,717.70)
- Divide that value by the 5th highest value among all rosters ($320,192.18)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-08 |      0.811 | $450.00        | $364.88         |
| 2024-04-28 |      0.532 | $2,000.00      | $1,063.43       |
| 2024-03-23 |      0.292 | $992.00        | $289.40         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
