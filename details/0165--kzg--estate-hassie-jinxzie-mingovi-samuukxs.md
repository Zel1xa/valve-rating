### Roster Details<br />
Team Name: KZG<br />
Roster: Estate, Hassie, JiNxZiE, Mingovi, Samuukxs<br />
Global Rank: [165](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [16]( ../standings_asia.md)<br />
<br />
Final Rank Value:  671.2<br />
<br />
Final Rank Value (671.2) = Starting Rank Value (706.1) + Head To Head Adjustments (-34.9)<br />

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
|           35 |      198 | 2024-07-30 | Above The Rest     | L   | 1.000      | -            | -                | -                | -         |   -22.76 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           34 |      419 | 2024-07-23 | DXA                | W   | 1.000      | 0.333        | 0.002 (0.001)    | 0.226 (0.075)    | 0 (0.000) |    14.49 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           33 |      424 | 2024-07-23 | DXA                | W   | 1.000      | 0.333        | 0.002 (0.001)    | 0.226 (0.075)    | 0 (0.000) |    15.83 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           32 |      446 | 2024-07-22 | Arcade             | W   | 1.000      | 0.333        | 0.002 (0.001)    | 0.137 (0.046)    | 0 (0.000) |    15.53 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           31 |      449 | 2024-07-22 | Arcade             | L   | 1.000      | -            | -                | -                | -         |   -15.99 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           30 |     1819 | 2024-05-22 | Bad News Kangaroos | L   | 0.706      | -            | -                | -                | -         |    -6.68 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           29 |     1824 | 2024-05-22 | Bad News Kangaroos | L   | 0.706      | -            | -                | -                | -         |    -7.05 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           28 |     2074 | 2024-05-15 | DXA                | W   | 0.659      | 0.333        | 0.002 (0.001)    | 0.226 (0.050)    | 0 (0.000) |     9.73 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           27 |     2081 | 2024-05-15 | DXA                | W   | 0.659      | 0.333        | 0.002 (0.001)    | 0.226 (0.050)    | 0 (0.000) |    10.31 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           26 |     2271 | 2024-05-08 | Rooster            | L   | 0.613      | -            | -                | -                | -         |    -5.95 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           25 |     2274 | 2024-05-08 | Rooster            | L   | 0.612      | -            | -                | -                | -         |    -6.24 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           24 |     2527 | 2024-04-26 | Rooster            | L   | 0.532      | -            | -                | -                | -         |    -5.67 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           23 |     2531 | 2024-04-25 | MIBR               | L   | 0.531      | -            | -                | -                | -         |    -0.21 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           22 |     2787 | 2024-04-17 | Mindfreak          | L   | 0.473      | -            | -                | -                | -         |    -7.21 | Hassie, Jynx, KRAXYT, Mingovi, Samuukxs    |
|           21 |     2961 | 2024-04-10 | Canon Event        | W   | 0.426      | 0.333        | 0.000 (0.000)    | -                | 0 (0.000) |     3.43 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           20 |     2966 | 2024-04-10 | Canon Event        | W   | 0.426      | 0.333        | 0.000 (0.000)    | -                | 0 (0.000) |     3.53 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           19 |     3187 | 2024-04-03 | Vantage            | L   | 0.380      | -            | -                | -                | -         |    -6.30 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           18 |     3194 | 2024-04-03 | Vantage            | L   | 0.379      | -            | -                | -                | -         |    -6.51 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           17 |     3320 | 2024-03-27 | FlyQuest           | L   | 0.333      | -            | -                | -                | -         |    -0.70 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           16 |     3325 | 2024-03-27 | FlyQuest           | L   | 0.333      | -            | -                | -                | -         |    -0.71 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           15 |     3368 | 2024-03-23 | Arcade             | W   | 0.306      | 0.315        | 0.002 (0.000)    | 0.137 (0.013)    | 1 (0.306) |     4.77 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           14 |     3369 | 2024-03-23 | DXA                | L   | 0.305      | -            | -                | -                | -         |    -4.77 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           13 |     3589 | 2024-03-13 | RKON               | L   | 0.240      | -            | -                | -                | -         |    -5.61 | bebest, Estate, Hassie, Mingovi, Samuukxs  |
|           12 |     3596 | 2024-03-13 | RKON               | W   | 0.239      | 0.333        | -                | 0.032 (0.003)    | 0 (0.000) |     1.95 | bebest, Estate, Hassie, Mingovi, Samuukxs  |
|           11 |     3764 | 2024-03-06 | Arcade             | L   | 0.193      | -            | -                | -                | -         |    -3.14 | Estate, Hassie, Mingovi, pain, Samuukxs    |
|           10 |     3770 | 2024-03-06 | Arcade             | L   | 0.193      | -            | -                | -                | -         |    -3.19 | Estate, Hassie, Mingovi, pain, Samuukxs    |
|            9 |     4067 | 2024-02-21 | Mindfreak          | L   | 0.100      | -            | -                | -                | -         |    -1.72 | Estate, Hassie, Mingovi, pain, Samuukxs    |
|            8 |     4072 | 2024-02-21 | Mindfreak          | L   | 0.099      | -            | -                | -                | -         |    -1.73 | Estate, Hassie, Mingovi, pain, Samuukxs    |
|            7 |     4100 | 2024-02-20 | Cringexe           | L   | 0.092      | -            | -                | -                | -         |    -2.26 | dpr, Estate, Hassie, Mingovi, Samuukxs     |
|            6 |     4145 | 2024-02-18 | Arcade             | L   | 0.079      | -            | -                | -                | -         |    -1.34 | dpr, Hassie, Lexon, Mingovi, Samuukxs      |
|            5 |     4199 | 2024-02-16 | sunday school      | L   | 0.066      | -            | -                | -                | -         |    -1.25 | Estate, Hassie, Mingovi, pain, Samuukxs    |
|            4 |     4227 | 2024-02-15 | sunday school      | W   | 0.059      | 0.143        | 0.003 (0.000)    | -                | 0 (0.000) |     0.74 | Estate, Hassie, Mingovi, pain, Samuukxs    |
|            3 |     4228 | 2024-02-14 | Vantage            | W   | 0.058      | 0.143        | -                | 0.070 (0.001)    | -         |     0.78 | Estate, Hassie, Mingovi, pain, Samuukxs    |
|            2 |     4269 | 2024-02-13 | Mindfreak          | W   | 0.052      | 0.143        | 0.004 (0.000)    | 0.051 (0.000)    | -         |     0.72 | Estate, Hassie, Mingovi, pain, Samuukxs    |
|            1 |     4294 | 2024-02-13 | RKON               | W   | 0.046      | 0.143        | -                | 0.032 (0.000)    | -         |     0.35 | Estate, Hassie, Mingovi, pain, Samuukxs    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,765.91)
- Divide that value by the 5th highest value among all rosters ($324,344.55)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-08 |      0.825 | $450.00        | $371.18         |
| 2024-04-28 |      0.546 | $2,000.00      | $1,091.44       |
| 2024-03-23 |      0.306 | $992.00        | $303.29         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
