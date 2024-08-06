### Roster Details<br />
Team Name: KZG<br />
Roster: Estate, Hassie, JiNxZiE, Mingovi, Samuukxs<br />
Global Rank: [165](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [16]( ../standings_asia.md)<br />
<br />
Final Rank Value:  672.0<br />
<br />
Final Rank Value (672.0) = Starting Rank Value (705.4) + Head To Head Adjustments (-33.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.306[<sup>1</sup>](#table2)
- Bounty Collected: 0.225[<sup>2</sup>](#table1)
- Opponent Network: 0.030[<sup>2</sup>](#table1)
- LAN Wins: 0.034[<sup>2</sup>](#table1)

The average of these factors is 0.149<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 705.4
- 400 + ( ( 0.149 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 705.4


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
|           35 |      254 | 2024-07-30 | Above The Rest     | L   | 1.000      | -            | -                | -                | -         |   -22.78 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           34 |      475 | 2024-07-23 | DXA                | W   | 1.000      | 0.333        | 0.002 (0.001)    | 0.222 (0.074)    | 0 (0.000) |    14.49 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           33 |      479 | 2024-07-23 | DXA                | W   | 1.000      | 0.333        | 0.002 (0.001)    | 0.222 (0.074)    | 0 (0.000) |    15.82 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           32 |      502 | 2024-07-22 | Arcade             | W   | 1.000      | 0.333        | 0.002 (0.001)    | 0.133 (0.044)    | 0 (0.000) |    15.51 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           31 |      504 | 2024-07-22 | Arcade             | L   | 1.000      | -            | -                | -                | -         |   -16.02 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           30 |     1875 | 2024-05-22 | Bad News Kangaroos | L   | 0.693      | -            | -                | -                | -         |    -6.66 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           29 |     1880 | 2024-05-22 | Bad News Kangaroos | L   | 0.693      | -            | -                | -                | -         |    -7.02 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           28 |     2130 | 2024-05-15 | DXA                | W   | 0.647      | 0.333        | 0.002 (0.000)    | 0.222 (0.048)    | 0 (0.000) |     9.55 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           27 |     2137 | 2024-05-15 | DXA                | W   | 0.646      | 0.333        | 0.002 (0.000)    | 0.222 (0.048)    | 0 (0.000) |    10.11 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           26 |     2327 | 2024-05-08 | Rooster            | L   | 0.600      | -            | -                | -                | -         |    -5.90 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           25 |     2330 | 2024-05-08 | Rooster            | L   | 0.600      | -            | -                | -                | -         |    -6.17 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           24 |     2583 | 2024-04-26 | Rooster            | L   | 0.520      | -            | -                | -                | -         |    -5.58 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           23 |     2587 | 2024-04-25 | MIBR               | L   | 0.518      | -            | -                | -                | -         |    -0.21 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           22 |     2843 | 2024-04-17 | Mindfreak          | L   | 0.460      | -            | -                | -                | -         |    -7.04 | Hassie, Jynx, KRAXYT, Mingovi, Samuukxs    |
|           21 |     3017 | 2024-04-10 | Canon Event        | W   | 0.413      | 0.333        | 0.000 (0.000)    | -                | 0 (0.000) |     3.34 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           20 |     3022 | 2024-04-10 | Canon Event        | W   | 0.413      | 0.333        | 0.000 (0.000)    | -                | 0 (0.000) |     3.43 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           19 |     3243 | 2024-04-03 | Vantage            | L   | 0.367      | -            | -                | -                | -         |    -6.11 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           18 |     3250 | 2024-04-03 | Vantage            | L   | 0.366      | -            | -                | -                | -         |    -6.30 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           17 |     3376 | 2024-03-27 | FlyQuest           | L   | 0.320      | -            | -                | -                | -         |    -0.70 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           16 |     3381 | 2024-03-27 | FlyQuest           | L   | 0.320      | -            | -                | -                | -         |    -0.70 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           15 |     3424 | 2024-03-23 | Arcade             | W   | 0.293      | 0.315        | 0.002 (0.000)    | 0.133 (0.012)    | 1 (0.293) |     4.55 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           14 |     3425 | 2024-03-23 | DXA                | L   | 0.293      | -            | -                | -                | -         |    -4.58 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           13 |     3645 | 2024-03-13 | RKON               | L   | 0.227      | -            | -                | -                | -         |    -5.33 | bebest, Estate, Hassie, Mingovi, Samuukxs  |
|           12 |     3652 | 2024-03-13 | RKON               | W   | 0.227      | 0.333        | -                | 0.030 (0.002)    | 0 (0.000) |     1.84 | bebest, Estate, Hassie, Mingovi, Samuukxs  |
|           11 |     3820 | 2024-03-06 | Arcade             | L   | 0.180      | -            | -                | -                | -         |    -2.95 | Estate, Hassie, Mingovi, pain, Samuukxs    |
|           10 |     3826 | 2024-03-06 | Arcade             | L   | 0.180      | -            | -                | -                | -         |    -2.99 | Estate, Hassie, Mingovi, pain, Samuukxs    |
|            9 |     4123 | 2024-02-21 | Mindfreak          | L   | 0.087      | -            | -                | -                | -         |    -1.50 | Estate, Hassie, Mingovi, pain, Samuukxs    |
|            8 |     4128 | 2024-02-21 | Mindfreak          | L   | 0.087      | -            | -                | -                | -         |    -1.51 | Estate, Hassie, Mingovi, pain, Samuukxs    |
|            7 |     4156 | 2024-02-20 | Cringexe           | L   | 0.080      | -            | -                | -                | -         |    -1.95 | dpr, Estate, Hassie, Mingovi, Samuukxs     |
|            6 |     4201 | 2024-02-18 | Arcade             | L   | 0.066      | -            | -                | -                | -         |    -1.13 | dpr, Hassie, Lexon, Mingovi, Samuukxs      |
|            5 |     4255 | 2024-02-16 | sunday school      | L   | 0.053      | -            | -                | -                | -         |    -1.01 | Estate, Hassie, Mingovi, pain, Samuukxs    |
|            4 |     4283 | 2024-02-15 | sunday school      | W   | 0.047      | 0.143        | 0.003 (0.000)    | -                | 0 (0.000) |     0.58 | Estate, Hassie, Mingovi, pain, Samuukxs    |
|            3 |     4284 | 2024-02-14 | Vantage            | W   | 0.045      | 0.143        | -                | 0.066 (0.000)    | -         |     0.61 | Estate, Hassie, Mingovi, pain, Samuukxs    |
|            2 |     4325 | 2024-02-13 | Mindfreak          | W   | 0.039      | 0.143        | 0.004 (0.000)    | 0.048 (0.000)    | -         |     0.55 | Estate, Hassie, Mingovi, pain, Samuukxs    |
|            1 |     4350 | 2024-02-13 | RKON               | W   | 0.033      | 0.143        | -                | 0.030 (0.000)    | -         |     0.25 | Estate, Hassie, Mingovi, pain, Samuukxs    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,722.48)
- Divide that value by the 5th highest value among all rosters ($320,603.98)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-08 |      0.812 | $450.00        | $365.50         |
| 2024-04-28 |      0.533 | $2,000.00      | $1,066.20       |
| 2024-03-23 |      0.293 | $992.00        | $290.78         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
