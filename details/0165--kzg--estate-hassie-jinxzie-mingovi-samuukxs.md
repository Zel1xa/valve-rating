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
Final Rank Value (671.2) = Starting Rank Value (706.0) + Head To Head Adjustments (-34.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.306[<sup>1</sup>](#table2)
- Bounty Collected: 0.226[<sup>2</sup>](#table1)
- Opponent Network: 0.031[<sup>2</sup>](#table1)
- LAN Wins: 0.035[<sup>2</sup>](#table1)

The average of these factors is 0.150<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 706.0
- 400 + ( ( 0.150 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 706.0


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
|           35 |      221 | 2024-07-30 | Above The Rest     | L   | 1.000      | -            | -                | -                | -         |   -22.77 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           34 |      442 | 2024-07-23 | DXA                | W   | 1.000      | 0.333        | 0.002 (0.001)    | 0.226 (0.075)    | 0 (0.000) |    14.49 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           33 |      446 | 2024-07-23 | DXA                | W   | 1.000      | 0.333        | 0.002 (0.001)    | 0.226 (0.075)    | 0 (0.000) |    15.83 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           32 |      469 | 2024-07-22 | Arcade             | W   | 1.000      | 0.333        | 0.002 (0.001)    | 0.137 (0.046)    | 0 (0.000) |    15.53 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           31 |      471 | 2024-07-22 | Arcade             | L   | 1.000      | -            | -                | -                | -         |   -15.99 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           30 |     1842 | 2024-05-22 | Bad News Kangaroos | L   | 0.705      | -            | -                | -                | -         |    -6.68 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           29 |     1847 | 2024-05-22 | Bad News Kangaroos | L   | 0.705      | -            | -                | -                | -         |    -7.05 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           28 |     2097 | 2024-05-15 | DXA                | W   | 0.659      | 0.333        | 0.002 (0.001)    | 0.226 (0.050)    | 0 (0.000) |     9.71 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           27 |     2104 | 2024-05-15 | DXA                | W   | 0.658      | 0.333        | 0.002 (0.001)    | 0.226 (0.050)    | 0 (0.000) |    10.30 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           26 |     2294 | 2024-05-08 | Rooster            | L   | 0.612      | -            | -                | -                | -         |    -5.95 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           25 |     2297 | 2024-05-08 | Rooster            | L   | 0.612      | -            | -                | -                | -         |    -6.23 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           24 |     2550 | 2024-04-26 | Rooster            | L   | 0.532      | -            | -                | -                | -         |    -5.66 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           23 |     2554 | 2024-04-25 | MIBR               | L   | 0.530      | -            | -                | -                | -         |    -0.21 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           22 |     2810 | 2024-04-17 | Mindfreak          | L   | 0.472      | -            | -                | -                | -         |    -7.20 | Hassie, Jynx, KRAXYT, Mingovi, Samuukxs    |
|           21 |     2984 | 2024-04-10 | Canon Event        | W   | 0.425      | 0.333        | 0.000 (0.000)    | -                | 0 (0.000) |     3.42 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           20 |     2989 | 2024-04-10 | Canon Event        | W   | 0.425      | 0.333        | 0.000 (0.000)    | -                | 0 (0.000) |     3.52 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           19 |     3210 | 2024-04-03 | Vantage            | L   | 0.379      | -            | -                | -                | -         |    -6.29 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           18 |     3217 | 2024-04-03 | Vantage            | L   | 0.378      | -            | -                | -                | -         |    -6.50 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           17 |     3343 | 2024-03-27 | FlyQuest           | L   | 0.332      | -            | -                | -                | -         |    -0.70 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           16 |     3348 | 2024-03-27 | FlyQuest           | L   | 0.332      | -            | -                | -                | -         |    -0.70 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           15 |     3391 | 2024-03-23 | Arcade             | W   | 0.305      | 0.315        | 0.002 (0.000)    | 0.137 (0.013)    | 1 (0.305) |     4.76 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           14 |     3392 | 2024-03-23 | DXA                | L   | 0.304      | -            | -                | -                | -         |    -4.76 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           13 |     3612 | 2024-03-13 | RKON               | L   | 0.239      | -            | -                | -                | -         |    -5.60 | bebest, Estate, Hassie, Mingovi, Samuukxs  |
|           12 |     3619 | 2024-03-13 | RKON               | W   | 0.239      | 0.333        | -                | 0.032 (0.003)    | 0 (0.000) |     1.94 | bebest, Estate, Hassie, Mingovi, Samuukxs  |
|           11 |     3787 | 2024-03-06 | Arcade             | L   | 0.192      | -            | -                | -                | -         |    -3.13 | Estate, Hassie, Mingovi, pain, Samuukxs    |
|           10 |     3793 | 2024-03-06 | Arcade             | L   | 0.192      | -            | -                | -                | -         |    -3.18 | Estate, Hassie, Mingovi, pain, Samuukxs    |
|            9 |     4090 | 2024-02-21 | Mindfreak          | L   | 0.099      | -            | -                | -                | -         |    -1.71 | Estate, Hassie, Mingovi, pain, Samuukxs    |
|            8 |     4095 | 2024-02-21 | Mindfreak          | L   | 0.099      | -            | -                | -                | -         |    -1.72 | Estate, Hassie, Mingovi, pain, Samuukxs    |
|            7 |     4123 | 2024-02-20 | Cringexe           | L   | 0.092      | -            | -                | -                | -         |    -2.24 | dpr, Estate, Hassie, Mingovi, Samuukxs     |
|            6 |     4168 | 2024-02-18 | Arcade             | L   | 0.078      | -            | -                | -                | -         |    -1.33 | dpr, Hassie, Lexon, Mingovi, Samuukxs      |
|            5 |     4222 | 2024-02-16 | sunday school      | L   | 0.065      | -            | -                | -                | -         |    -1.24 | Estate, Hassie, Mingovi, pain, Samuukxs    |
|            4 |     4250 | 2024-02-15 | sunday school      | W   | 0.058      | 0.143        | 0.003 (0.000)    | -                | 0 (0.000) |     0.73 | Estate, Hassie, Mingovi, pain, Samuukxs    |
|            3 |     4251 | 2024-02-14 | Vantage            | W   | 0.057      | 0.143        | -                | 0.070 (0.001)    | -         |     0.77 | Estate, Hassie, Mingovi, pain, Samuukxs    |
|            2 |     4292 | 2024-02-13 | Mindfreak          | W   | 0.051      | 0.143        | 0.004 (0.000)    | 0.050 (0.000)    | -         |     0.71 | Estate, Hassie, Mingovi, pain, Samuukxs    |
|            1 |     4317 | 2024-02-13 | RKON               | W   | 0.045      | 0.143        | -                | 0.032 (0.000)    | -         |     0.34 | Estate, Hassie, Mingovi, pain, Samuukxs    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,763.28)
- Divide that value by the 5th highest value among all rosters ($324,118.06)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-08 |      0.824 | $450.00        | $370.83         |
| 2024-04-28 |      0.545 | $2,000.00      | $1,089.91       |
| 2024-03-23 |      0.305 | $992.00        | $302.54         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
