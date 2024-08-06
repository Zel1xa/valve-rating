### Roster Details<br />
Team Name: KZG<br />
Roster: Estate, Hassie, JiNxZiE, Mingovi, Samuukxs<br />
Global Rank: [165](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [16]( ../standings_asia.md)<br />
<br />
Final Rank Value:  672.4<br />
<br />
Final Rank Value (672.4) = Starting Rank Value (705.6) + Head To Head Adjustments (-33.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.306[<sup>1</sup>](#table2)
- Bounty Collected: 0.225[<sup>2</sup>](#table1)
- Opponent Network: 0.030[<sup>2</sup>](#table1)
- LAN Wins: 0.034[<sup>2</sup>](#table1)

The average of these factors is 0.149<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 705.6
- 400 + ( ( 0.149 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 705.6


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
|           35 |      272 | 2024-07-30 | Above The Rest     | L   | 1.000      | -            | -                | -                | -         |   -22.79 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           34 |      493 | 2024-07-23 | DXA                | W   | 1.000      | 0.333        | 0.002 (0.001)    | 0.217 (0.072)    | 0 (0.000) |    14.49 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           33 |      497 | 2024-07-23 | DXA                | W   | 1.000      | 0.333        | 0.002 (0.001)    | 0.217 (0.072)    | 0 (0.000) |    15.83 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           32 |      520 | 2024-07-22 | Arcade             | W   | 1.000      | 0.333        | 0.002 (0.001)    | 0.130 (0.043)    | 0 (0.000) |    15.50 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           31 |      522 | 2024-07-22 | Arcade             | L   | 1.000      | -            | -                | -                | -         |   -16.02 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           30 |     1893 | 2024-05-22 | Bad News Kangaroos | L   | 0.692      | -            | -                | -                | -         |    -6.65 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           29 |     1898 | 2024-05-22 | Bad News Kangaroos | L   | 0.691      | -            | -                | -                | -         |    -7.01 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           28 |     2148 | 2024-05-15 | DXA                | W   | 0.645      | 0.333        | 0.002 (0.000)    | 0.217 (0.047)    | 0 (0.000) |     9.53 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           27 |     2155 | 2024-05-15 | DXA                | W   | 0.645      | 0.333        | 0.002 (0.000)    | 0.217 (0.047)    | 0 (0.000) |    10.09 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           26 |     2345 | 2024-05-08 | Rooster            | L   | 0.598      | -            | -                | -                | -         |    -5.89 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           25 |     2348 | 2024-05-08 | Rooster            | L   | 0.598      | -            | -                | -                | -         |    -6.16 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           24 |     2601 | 2024-04-26 | Rooster            | L   | 0.518      | -            | -                | -                | -         |    -5.57 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           23 |     2605 | 2024-04-25 | MIBR               | L   | 0.516      | -            | -                | -                | -         |    -0.22 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           22 |     2861 | 2024-04-17 | Mindfreak          | L   | 0.458      | -            | -                | -                | -         |    -7.02 | Hassie, Jynx, KRAXYT, Mingovi, Samuukxs    |
|           21 |     3035 | 2024-04-10 | Canon Event        | W   | 0.411      | 0.333        | 0.000 (0.000)    | -                | 0 (0.000) |     3.32 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           20 |     3040 | 2024-04-10 | Canon Event        | W   | 0.411      | 0.333        | 0.000 (0.000)    | -                | 0 (0.000) |     3.42 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           19 |     3261 | 2024-04-03 | Vantage            | L   | 0.365      | -            | -                | -                | -         |    -6.08 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           18 |     3268 | 2024-04-03 | Vantage            | L   | 0.365      | -            | -                | -                | -         |    -6.27 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           17 |     3394 | 2024-03-27 | FlyQuest           | L   | 0.318      | -            | -                | -                | -         |    -0.70 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           16 |     3399 | 2024-03-27 | FlyQuest           | L   | 0.318      | -            | -                | -                | -         |    -0.70 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           15 |     3442 | 2024-03-23 | Arcade             | W   | 0.291      | 0.315        | 0.002 (0.000)    | 0.130 (0.012)    | 1 (0.291) |     4.53 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           14 |     3443 | 2024-03-23 | DXA                | L   | 0.291      | -            | -                | -                | -         |    -4.55 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           13 |     3663 | 2024-03-13 | RKON               | L   | 0.225      | -            | -                | -                | -         |    -5.29 | bebest, Estate, Hassie, Mingovi, Samuukxs  |
|           12 |     3670 | 2024-03-13 | RKON               | W   | 0.225      | 0.333        | -                | 0.029 (0.002)    | 0 (0.000) |     1.82 | bebest, Estate, Hassie, Mingovi, Samuukxs  |
|           11 |     3838 | 2024-03-06 | Arcade             | L   | 0.178      | -            | -                | -                | -         |    -2.92 | Estate, Hassie, Mingovi, pain, Samuukxs    |
|           10 |     3844 | 2024-03-06 | Arcade             | L   | 0.178      | -            | -                | -                | -         |    -2.96 | Estate, Hassie, Mingovi, pain, Samuukxs    |
|            9 |     4141 | 2024-02-21 | Mindfreak          | L   | 0.085      | -            | -                | -                | -         |    -1.47 | Estate, Hassie, Mingovi, pain, Samuukxs    |
|            8 |     4146 | 2024-02-21 | Mindfreak          | L   | 0.085      | -            | -                | -                | -         |    -1.48 | Estate, Hassie, Mingovi, pain, Samuukxs    |
|            7 |     4174 | 2024-02-20 | Cringexe           | L   | 0.078      | -            | -                | -                | -         |    -1.91 | dpr, Estate, Hassie, Mingovi, Samuukxs     |
|            6 |     4219 | 2024-02-18 | Arcade             | L   | 0.065      | -            | -                | -                | -         |    -1.10 | dpr, Hassie, Lexon, Mingovi, Samuukxs      |
|            5 |     4273 | 2024-02-16 | sunday school      | L   | 0.052      | -            | -                | -                | -         |    -0.98 | Estate, Hassie, Mingovi, pain, Samuukxs    |
|            4 |     4301 | 2024-02-15 | sunday school      | W   | 0.045      | 0.143        | 0.003 (0.000)    | -                | 0 (0.000) |     0.56 | Estate, Hassie, Mingovi, pain, Samuukxs    |
|            3 |     4302 | 2024-02-14 | Vantage            | W   | 0.044      | 0.143        | -                | 0.064 (0.000)    | -         |     0.59 | Estate, Hassie, Mingovi, pain, Samuukxs    |
|            2 |     4343 | 2024-02-13 | Mindfreak          | W   | 0.037      | 0.143        | 0.004 (0.000)    | 0.047 (0.000)    | -         |     0.52 | Estate, Hassie, Mingovi, pain, Samuukxs    |
|            1 |     4368 | 2024-02-13 | RKON               | W   | 0.031      | 0.143        | -                | 0.029 (0.000)    | -         |     0.24 | Estate, Hassie, Mingovi, pain, Samuukxs    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,716.27)
- Divide that value by the 5th highest value among all rosters ($320,068.63)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-08 |      0.810 | $450.00        | $364.69         |
| 2024-04-28 |      0.531 | $2,000.00      | $1,062.59       |
| 2024-03-23 |      0.291 | $992.00        | $288.99         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
