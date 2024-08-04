### Roster Details<br />
Team Name: KZG<br />
Roster: Estate, Hassie, JiNxZiE, Mingovi, Samuukxs<br />
Global Rank: [173](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [17]( ../standings_asia.md)<br />
<br />
Final Rank Value:  662.2<br />
<br />
Final Rank Value (662.2) = Starting Rank Value (706.1) + Head To Head Adjustments (-43.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.306[<sup>1</sup>](#table2)
- Bounty Collected: 0.226[<sup>2</sup>](#table1)
- Opponent Network: 0.031[<sup>2</sup>](#table1)
- LAN Wins: 0.035[<sup>2</sup>](#table1)

The average of these factors is 0.150<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 706.1
- 400 + ( ( 0.150 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 706.1


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
|           35 |      190 | 2024-07-30 | Above The Rest     | L   | 1.000      | -            | -                | -                | -         |   -22.44 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           34 |      411 | 2024-07-23 | DXA                | W   | 1.000      | 0.333        | 0.002 (0.001)    | 0.227 (0.076)    | 0 (0.000) |    14.28 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           33 |      416 | 2024-07-23 | DXA                | W   | 1.000      | 0.333        | 0.002 (0.001)    | 0.227 (0.076)    | 0 (0.000) |    15.59 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           32 |      438 | 2024-07-22 | Arcade             | W   | 1.000      | 0.333        | 0.002 (0.001)    | 0.137 (0.046)    | 0 (0.000) |    15.01 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           31 |      441 | 2024-07-22 | Arcade             | L   | 1.000      | -            | -                | -                | -         |   -16.56 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           30 |     1811 | 2024-05-22 | Bad News Kangaroos | L   | 0.707      | -            | -                | -                | -         |    -9.79 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           29 |     1816 | 2024-05-22 | Bad News Kangaroos | L   | 0.706      | -            | -                | -                | -         |   -10.42 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           28 |     2066 | 2024-05-15 | DXA                | W   | 0.660      | 0.333        | 0.002 (0.001)    | 0.227 (0.050)    | 0 (0.000) |     9.53 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           27 |     2073 | 2024-05-15 | DXA                | W   | 0.660      | 0.333        | 0.002 (0.001)    | 0.227 (0.050)    | 0 (0.000) |    10.10 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           26 |     2263 | 2024-05-08 | Rooster            | L   | 0.613      | -            | -                | -                | -         |    -6.03 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           25 |     2266 | 2024-05-08 | Rooster            | L   | 0.613      | -            | -                | -                | -         |    -6.32 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           24 |     2519 | 2024-04-26 | Rooster            | L   | 0.533      | -            | -                | -                | -         |    -5.75 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           23 |     2523 | 2024-04-25 | MIBR               | L   | 0.531      | -            | -                | -                | -         |    -0.21 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           22 |     2779 | 2024-04-17 | Mindfreak          | L   | 0.473      | -            | -                | -                | -         |    -7.37 | Hassie, Jynx, KRAXYT, Mingovi, Samuukxs    |
|           21 |     2953 | 2024-04-10 | Canon Event        | W   | 0.427      | 0.333        | 0.000 (0.000)    | -                | 0 (0.000) |     3.43 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           20 |     2958 | 2024-04-10 | Canon Event        | W   | 0.426      | 0.333        | 0.000 (0.000)    | -                | 0 (0.000) |     3.53 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           19 |     3179 | 2024-04-03 | Vantage            | L   | 0.380      | -            | -                | -                | -         |    -6.31 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           18 |     3186 | 2024-04-03 | Vantage            | L   | 0.380      | -            | -                | -                | -         |    -6.51 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           17 |     3312 | 2024-03-27 | FlyQuest           | L   | 0.333      | -            | -                | -                | -         |    -0.70 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           16 |     3317 | 2024-03-27 | FlyQuest           | L   | 0.333      | -            | -                | -                | -         |    -0.71 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           15 |     3360 | 2024-03-23 | Arcade             | W   | 0.306      | 0.315        | 0.002 (0.000)    | 0.137 (0.013)    | 1 (0.306) |     4.65 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           14 |     3361 | 2024-03-23 | DXA                | L   | 0.306      | -            | -                | -                | -         |    -4.90 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           13 |     3581 | 2024-03-13 | RKON               | L   | 0.240      | -            | -                | -                | -         |    -5.63 | bebest, Estate, Hassie, Mingovi, Samuukxs  |
|           12 |     3588 | 2024-03-13 | RKON               | W   | 0.240      | 0.333        | -                | 0.032 (0.003)    | 0 (0.000) |     1.96 | bebest, Estate, Hassie, Mingovi, Samuukxs  |
|           11 |     3756 | 2024-03-06 | Arcade             | L   | 0.194      | -            | -                | -                | -         |    -3.24 | Estate, Hassie, Mingovi, pain, Samuukxs    |
|           10 |     3762 | 2024-03-06 | Arcade             | L   | 0.193      | -            | -                | -                | -         |    -3.29 | Estate, Hassie, Mingovi, pain, Samuukxs    |
|            9 |     4059 | 2024-02-21 | Mindfreak          | L   | 0.100      | -            | -                | -                | -         |    -1.73 | Estate, Hassie, Mingovi, pain, Samuukxs    |
|            8 |     4064 | 2024-02-21 | Mindfreak          | L   | 0.100      | -            | -                | -                | -         |    -1.75 | Estate, Hassie, Mingovi, pain, Samuukxs    |
|            7 |     4092 | 2024-02-20 | Cringexe           | L   | 0.093      | -            | -                | -                | -         |    -2.28 | dpr, Estate, Hassie, Mingovi, Samuukxs     |
|            6 |     4137 | 2024-02-18 | Arcade             | L   | 0.080      | -            | -                | -                | -         |    -1.40 | dpr, Hassie, Lexon, Mingovi, Samuukxs      |
|            5 |     4191 | 2024-02-16 | sunday school      | L   | 0.067      | -            | -                | -                | -         |    -1.27 | Estate, Hassie, Mingovi, pain, Samuukxs    |
|            4 |     4219 | 2024-02-15 | sunday school      | W   | 0.060      | 0.143        | 0.003 (0.000)    | -                | 0 (0.000) |     0.75 | Estate, Hassie, Mingovi, pain, Samuukxs    |
|            3 |     4220 | 2024-02-14 | Vantage            | W   | 0.059      | 0.143        | -                | 0.070 (0.001)    | -         |     0.79 | Estate, Hassie, Mingovi, pain, Samuukxs    |
|            2 |     4261 | 2024-02-13 | Mindfreak          | W   | 0.053      | 0.143        | 0.004 (0.000)    | 0.051 (0.000)    | -         |     0.73 | Estate, Hassie, Mingovi, pain, Samuukxs    |
|            1 |     4286 | 2024-02-13 | RKON               | W   | 0.046      | 0.143        | -                | 0.032 (0.000)    | -         |     0.35 | Estate, Hassie, Mingovi, pain, Samuukxs    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,768.38)
- Divide that value by the 5th highest value among all rosters ($324,557.31)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-08 |      0.826 | $450.00        | $371.50         |
| 2024-04-28 |      0.546 | $2,000.00      | $1,092.87       |
| 2024-03-23 |      0.306 | $992.00        | $304.01         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
