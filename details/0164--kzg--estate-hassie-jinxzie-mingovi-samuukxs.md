### Roster Details<br />
Team Name: KZG<br />
Roster: Estate, Hassie, JiNxZiE, Mingovi, Samuukxs<br />
Global Rank: [164](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [16]( ../standings_asia.md)<br />
<br />
Final Rank Value:  671.5<br />
<br />
Final Rank Value (671.5) = Starting Rank Value (705.6) + Head To Head Adjustments (-34.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.306[<sup>1</sup>](#table2)
- Bounty Collected: 0.226[<sup>2</sup>](#table1)
- Opponent Network: 0.031[<sup>2</sup>](#table1)
- LAN Wins: 0.034[<sup>2</sup>](#table1)

The average of these factors is 0.149<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 705.6
- 400 + ( ( 0.149 - 0.000 ) / ( 0.781 - 0.000 ) ) * 1600 = 705.6


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
|           35 |      239 | 2024-07-30 | Above The Rest     | L   | 1.000      | -            | -                | -                | -         |   -22.77 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           34 |      460 | 2024-07-23 | DXA                | W   | 1.000      | 0.333        | 0.002 (0.001)    | 0.225 (0.075)    | 0 (0.000) |    14.49 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           33 |      464 | 2024-07-23 | DXA                | W   | 1.000      | 0.333        | 0.002 (0.001)    | 0.225 (0.075)    | 0 (0.000) |    15.83 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           32 |      487 | 2024-07-22 | Arcade             | W   | 1.000      | 0.333        | 0.002 (0.001)    | 0.136 (0.045)    | 0 (0.000) |    15.52 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           31 |      489 | 2024-07-22 | Arcade             | L   | 1.000      | -            | -                | -                | -         |   -16.00 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           30 |     1860 | 2024-05-22 | Bad News Kangaroos | L   | 0.699      | -            | -                | -                | -         |    -6.67 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           29 |     1865 | 2024-05-22 | Bad News Kangaroos | L   | 0.699      | -            | -                | -                | -         |    -7.03 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           28 |     2115 | 2024-05-15 | DXA                | W   | 0.653      | 0.333        | 0.002 (0.000)    | 0.225 (0.049)    | 0 (0.000) |     9.63 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           27 |     2122 | 2024-05-15 | DXA                | W   | 0.652      | 0.333        | 0.002 (0.000)    | 0.225 (0.049)    | 0 (0.000) |    10.20 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           26 |     2312 | 2024-05-08 | Rooster            | L   | 0.606      | -            | -                | -                | -         |    -5.92 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           25 |     2315 | 2024-05-08 | Rooster            | L   | 0.606      | -            | -                | -                | -         |    -6.20 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           24 |     2568 | 2024-04-26 | Rooster            | L   | 0.526      | -            | -                | -                | -         |    -5.62 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           23 |     2572 | 2024-04-25 | MIBR               | L   | 0.524      | -            | -                | -                | -         |    -0.21 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           22 |     2828 | 2024-04-17 | Mindfreak          | L   | 0.466      | -            | -                | -                | -         |    -7.12 | Hassie, Jynx, KRAXYT, Mingovi, Samuukxs    |
|           21 |     3002 | 2024-04-10 | Canon Event        | W   | 0.419      | 0.333        | 0.000 (0.000)    | -                | 0 (0.000) |     3.38 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           20 |     3007 | 2024-04-10 | Canon Event        | W   | 0.419      | 0.333        | 0.000 (0.000)    | -                | 0 (0.000) |     3.48 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           19 |     3228 | 2024-04-03 | Vantage            | L   | 0.373      | -            | -                | -                | -         |    -6.20 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           18 |     3235 | 2024-04-03 | Vantage            | L   | 0.372      | -            | -                | -                | -         |    -6.40 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           17 |     3361 | 2024-03-27 | FlyQuest           | L   | 0.326      | -            | -                | -                | -         |    -0.70 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           16 |     3366 | 2024-03-27 | FlyQuest           | L   | 0.326      | -            | -                | -                | -         |    -0.70 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           15 |     3409 | 2024-03-23 | Arcade             | W   | 0.299      | 0.315        | 0.002 (0.000)    | 0.136 (0.013)    | 1 (0.299) |     4.66 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           14 |     3410 | 2024-03-23 | DXA                | L   | 0.298      | -            | -                | -                | -         |    -4.67 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           13 |     3630 | 2024-03-13 | RKON               | L   | 0.233      | -            | -                | -                | -         |    -5.46 | bebest, Estate, Hassie, Mingovi, Samuukxs  |
|           12 |     3637 | 2024-03-13 | RKON               | W   | 0.233      | 0.333        | -                | 0.031 (0.002)    | 0 (0.000) |     1.89 | bebest, Estate, Hassie, Mingovi, Samuukxs  |
|           11 |     3805 | 2024-03-06 | Arcade             | L   | 0.186      | -            | -                | -                | -         |    -3.04 | Estate, Hassie, Mingovi, pain, Samuukxs    |
|           10 |     3811 | 2024-03-06 | Arcade             | L   | 0.186      | -            | -                | -                | -         |    -3.08 | Estate, Hassie, Mingovi, pain, Samuukxs    |
|            9 |     4108 | 2024-02-21 | Mindfreak          | L   | 0.093      | -            | -                | -                | -         |    -1.60 | Estate, Hassie, Mingovi, pain, Samuukxs    |
|            8 |     4113 | 2024-02-21 | Mindfreak          | L   | 0.092      | -            | -                | -                | -         |    -1.61 | Estate, Hassie, Mingovi, pain, Samuukxs    |
|            7 |     4141 | 2024-02-20 | Cringexe           | L   | 0.086      | -            | -                | -                | -         |    -2.09 | dpr, Estate, Hassie, Mingovi, Samuukxs     |
|            6 |     4186 | 2024-02-18 | Arcade             | L   | 0.072      | -            | -                | -                | -         |    -1.23 | dpr, Hassie, Lexon, Mingovi, Samuukxs      |
|            5 |     4240 | 2024-02-16 | sunday school      | L   | 0.059      | -            | -                | -                | -         |    -1.13 | Estate, Hassie, Mingovi, pain, Samuukxs    |
|            4 |     4268 | 2024-02-15 | sunday school      | W   | 0.052      | 0.143        | 0.003 (0.000)    | -                | 0 (0.000) |     0.65 | Estate, Hassie, Mingovi, pain, Samuukxs    |
|            3 |     4269 | 2024-02-14 | Vantage            | W   | 0.051      | 0.143        | -                | 0.068 (0.000)    | -         |     0.69 | Estate, Hassie, Mingovi, pain, Samuukxs    |
|            2 |     4310 | 2024-02-13 | Mindfreak          | W   | 0.045      | 0.143        | 0.004 (0.000)    | 0.049 (0.000)    | -         |     0.63 | Estate, Hassie, Mingovi, pain, Samuukxs    |
|            1 |     4335 | 2024-02-13 | RKON               | W   | 0.039      | 0.143        | -                | 0.031 (0.000)    | -         |     0.30 | Estate, Hassie, Mingovi, pain, Samuukxs    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,742.56)
- Divide that value by the 5th highest value among all rosters ($322,333.56)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-08 |      0.818 | $450.00        | $368.13         |
| 2024-04-28 |      0.539 | $2,000.00      | $1,077.87       |
| 2024-03-23 |      0.299 | $992.00        | $296.57         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
