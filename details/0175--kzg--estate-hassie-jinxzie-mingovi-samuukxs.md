### Roster Details<br />
Team Name: KZG<br />
Roster: Estate, Hassie, JiNxZiE, Mingovi, Samuukxs<br />
Global Rank: [175](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [17]( ../standings_asia.md)<br />
<br />
Final Rank Value:  648.8<br />
<br />
Final Rank Value (648.8) = Starting Rank Value (687.9) + Head To Head Adjustments (-39.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.307[<sup>1</sup>](#table2)
- Bounty Collected: 0.225[<sup>2</sup>](#table1)
- Opponent Network: 0.031[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.141<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 687.9
- 400 + ( ( 0.141 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 687.9


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
|           34 |      164 | 2024-07-30 | Above The Rest     | L   | 1.000      | -            | -                | -                | -         |   -21.94 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           33 |      385 | 2024-07-23 | DXA                | W   | 1.000      | 0.333        | 0.002 (0.001)    | 0.235 (0.078)    | 0 (0.000) |    14.84 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           32 |      390 | 2024-07-23 | DXA                | W   | 1.000      | 0.333        | 0.002 (0.001)    | 0.235 (0.078)    | 0 (0.000) |    16.21 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           31 |      412 | 2024-07-22 | Arcade             | W   | 1.000      | 0.333        | 0.002 (0.001)    | 0.142 (0.047)    | 0 (0.000) |    15.79 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           30 |      415 | 2024-07-22 | Arcade             | L   | 1.000      | -            | -                | -                | -         |   -15.70 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           29 |     1743 | 2024-05-22 | Bad News Kangaroos | L   | 0.711      | -            | -                | -                | -         |    -9.31 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           28 |     1748 | 2024-05-22 | Bad News Kangaroos | L   | 0.711      | -            | -                | -                | -         |    -9.91 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           27 |     1997 | 2024-05-15 | DXA                | W   | 0.665      | 0.333        | 0.002 (0.001)    | 0.235 (0.052)    | 0 (0.000) |    10.12 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           26 |     2004 | 2024-05-15 | DXA                | W   | 0.664      | 0.333        | 0.002 (0.001)    | 0.235 (0.052)    | 0 (0.000) |    10.73 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           25 |     2193 | 2024-05-08 | Rooster            | L   | 0.618      | -            | -                | -                | -         |    -5.63 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           24 |     2196 | 2024-05-08 | Rooster            | L   | 0.618      | -            | -                | -                | -         |    -5.89 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           23 |     2448 | 2024-04-26 | Rooster            | L   | 0.538      | -            | -                | -                | -         |    -5.35 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           22 |     2452 | 2024-04-25 | MIBR               | L   | 0.536      | -            | -                | -                | -         |    -0.19 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           21 |     2708 | 2024-04-17 | Mindfreak          | L   | 0.478      | -            | -                | -                | -         |    -7.07 | Hassie, Jynx, KRAXYT, Mingovi, Samuukxs    |
|           20 |     2882 | 2024-04-10 | Canon Event        | W   | 0.431      | 0.333        | 0.000 (0.000)    | -                | 0 (0.000) |     3.77 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           19 |     2887 | 2024-04-10 | Canon Event        | W   | 0.431      | 0.333        | 0.000 (0.000)    | -                | 0 (0.000) |     3.89 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           18 |     3108 | 2024-04-03 | Vantage            | L   | 0.385      | -            | -                | -                | -         |    -6.00 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           17 |     3115 | 2024-04-03 | Vantage            | L   | 0.384      | -            | -                | -                | -         |    -6.20 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           16 |     3239 | 2024-03-27 | FlyQuest           | L   | 0.338      | -            | -                | -                | -         |    -0.63 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           15 |     3244 | 2024-03-27 | FlyQuest           | L   | 0.338      | -            | -                | -                | -         |    -0.63 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           14 |     3285 | 2024-03-23 | DXA                | L   | 0.311      | -            | -                | -                | -         |    -4.72 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           13 |     3503 | 2024-03-13 | RKON               | L   | 0.245      | -            | -                | -                | -         |    -5.59 | bebest, Estate, Hassie, Mingovi, Samuukxs  |
|           12 |     3510 | 2024-03-13 | RKON               | W   | 0.245      | 0.333        | -                | 0.034 (0.003)    | 0 (0.000) |     2.15 | bebest, Estate, Hassie, Mingovi, Samuukxs  |
|           11 |     3677 | 2024-03-06 | Arcade             | L   | 0.198      | -            | -                | -                | -         |    -3.16 | Estate, Hassie, Mingovi, pain, Samuukxs    |
|           10 |     3683 | 2024-03-06 | Arcade             | L   | 0.198      | -            | -                | -                | -         |    -3.21 | Estate, Hassie, Mingovi, pain, Samuukxs    |
|            9 |     3980 | 2024-02-21 | Mindfreak          | L   | 0.105      | -            | -                | -                | -         |    -1.73 | Estate, Hassie, Mingovi, pain, Samuukxs    |
|            8 |     3985 | 2024-02-21 | Mindfreak          | L   | 0.105      | -            | -                | -                | -         |    -1.74 | Estate, Hassie, Mingovi, pain, Samuukxs    |
|            7 |     4013 | 2024-02-20 | Cringexe           | L   | 0.098      | -            | -                | -                | -         |    -2.34 | dpr, Estate, Hassie, Mingovi, Samuukxs     |
|            6 |     4057 | 2024-02-18 | Arcade             | L   | 0.084      | -            | -                | -                | -         |    -1.41 | dpr, Hassie, Lexon, Mingovi, Samuukxs      |
|            5 |     4111 | 2024-02-16 | sunday school      | L   | 0.071      | -            | -                | -                | -         |    -1.30 | Estate, Hassie, Mingovi, pain, Samuukxs    |
|            4 |     4139 | 2024-02-15 | sunday school      | W   | 0.065      | 0.143        | 0.003 (0.000)    | 0.008 (0.000)    | 0 (0.000) |     0.86 | Estate, Hassie, Mingovi, pain, Samuukxs    |
|            3 |     4140 | 2024-02-14 | Vantage            | W   | 0.064      | 0.143        | 0.002 (0.000)    | 0.074 (0.001)    | 0 (0.000) |     0.90 | Estate, Hassie, Mingovi, pain, Samuukxs    |
|            2 |     4181 | 2024-02-13 | Mindfreak          | W   | 0.057      | 0.143        | 0.004 (0.000)    | 0.053 (0.000)    | -         |     0.85 | Estate, Hassie, Mingovi, pain, Samuukxs    |
|            1 |     4206 | 2024-02-13 | RKON               | W   | 0.051      | 0.143        | -                | 0.034 (0.000)    | -         |     0.42 | Estate, Hassie, Mingovi, pain, Samuukxs    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,784.79)
- Divide that value by the 5th highest value among all rosters ($325,971.18)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-08 |      0.830 | $450.00        | $373.65         |
| 2024-04-28 |      0.551 | $2,000.00      | $1,102.41       |
| 2024-03-23 |      0.311 | $992.00        | $308.74         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
