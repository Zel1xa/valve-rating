### Roster Details<br />
Team Name: KZG<br />
Roster: Estate, Hassie, JiNxZiE, Mingovi, Samuukxs<br />
Global Rank: [164](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [16]( ../standings_asia.md)<br />
<br />
Final Rank Value:  671.4<br />
<br />
Final Rank Value (671.4) = Starting Rank Value (705.8) + Head To Head Adjustments (-34.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.306[<sup>1</sup>](#table2)
- Bounty Collected: 0.226[<sup>2</sup>](#table1)
- Opponent Network: 0.031[<sup>2</sup>](#table1)
- LAN Wins: 0.035[<sup>2</sup>](#table1)

The average of these factors is 0.149<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 705.8
- 400 + ( ( 0.149 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 705.8


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
|           35 |      226 | 2024-07-30 | Above The Rest     | L   | 1.000      | -            | -                | -                | -         |   -22.77 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           34 |      447 | 2024-07-23 | DXA                | W   | 1.000      | 0.333        | 0.002 (0.001)    | 0.226 (0.075)    | 0 (0.000) |    14.49 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           33 |      451 | 2024-07-23 | DXA                | W   | 1.000      | 0.333        | 0.002 (0.001)    | 0.226 (0.075)    | 0 (0.000) |    15.83 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           32 |      474 | 2024-07-22 | Arcade             | W   | 1.000      | 0.333        | 0.002 (0.001)    | 0.136 (0.045)    | 0 (0.000) |    15.53 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           31 |      476 | 2024-07-22 | Arcade             | L   | 1.000      | -            | -                | -                | -         |   -16.00 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           30 |     1847 | 2024-05-22 | Bad News Kangaroos | L   | 0.702      | -            | -                | -                | -         |    -6.68 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           29 |     1852 | 2024-05-22 | Bad News Kangaroos | L   | 0.702      | -            | -                | -                | -         |    -7.04 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           28 |     2102 | 2024-05-15 | DXA                | W   | 0.656      | 0.333        | 0.002 (0.001)    | 0.226 (0.049)    | 0 (0.000) |     9.68 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           27 |     2109 | 2024-05-15 | DXA                | W   | 0.656      | 0.333        | 0.002 (0.001)    | 0.226 (0.049)    | 0 (0.000) |    10.25 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           26 |     2299 | 2024-05-08 | Rooster            | L   | 0.609      | -            | -                | -                | -         |    -5.94 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           25 |     2302 | 2024-05-08 | Rooster            | L   | 0.609      | -            | -                | -                | -         |    -6.22 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           24 |     2555 | 2024-04-26 | Rooster            | L   | 0.529      | -            | -                | -                | -         |    -5.64 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           23 |     2559 | 2024-04-25 | MIBR               | L   | 0.527      | -            | -                | -                | -         |    -0.21 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           22 |     2815 | 2024-04-17 | Mindfreak          | L   | 0.469      | -            | -                | -                | -         |    -7.16 | Hassie, Jynx, KRAXYT, Mingovi, Samuukxs    |
|           21 |     2989 | 2024-04-10 | Canon Event        | W   | 0.422      | 0.333        | 0.000 (0.000)    | -                | 0 (0.000) |     3.40 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           20 |     2994 | 2024-04-10 | Canon Event        | W   | 0.422      | 0.333        | 0.000 (0.000)    | -                | 0 (0.000) |     3.50 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           19 |     3215 | 2024-04-03 | Vantage            | L   | 0.376      | -            | -                | -                | -         |    -6.25 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           18 |     3222 | 2024-04-03 | Vantage            | L   | 0.376      | -            | -                | -                | -         |    -6.45 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           17 |     3348 | 2024-03-27 | FlyQuest           | L   | 0.329      | -            | -                | -                | -         |    -0.70 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           16 |     3353 | 2024-03-27 | FlyQuest           | L   | 0.329      | -            | -                | -                | -         |    -0.70 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           15 |     3396 | 2024-03-23 | Arcade             | W   | 0.302      | 0.315        | 0.002 (0.000)    | 0.136 (0.013)    | 1 (0.302) |     4.71 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           14 |     3397 | 2024-03-23 | DXA                | L   | 0.302      | -            | -                | -                | -         |    -4.72 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           13 |     3617 | 2024-03-13 | RKON               | L   | 0.236      | -            | -                | -                | -         |    -5.54 | bebest, Estate, Hassie, Mingovi, Samuukxs  |
|           12 |     3624 | 2024-03-13 | RKON               | W   | 0.236      | 0.333        | -                | 0.031 (0.002)    | 0 (0.000) |     1.92 | bebest, Estate, Hassie, Mingovi, Samuukxs  |
|           11 |     3792 | 2024-03-06 | Arcade             | L   | 0.189      | -            | -                | -                | -         |    -3.09 | Estate, Hassie, Mingovi, pain, Samuukxs    |
|           10 |     3798 | 2024-03-06 | Arcade             | L   | 0.189      | -            | -                | -                | -         |    -3.14 | Estate, Hassie, Mingovi, pain, Samuukxs    |
|            9 |     4095 | 2024-02-21 | Mindfreak          | L   | 0.096      | -            | -                | -                | -         |    -1.66 | Estate, Hassie, Mingovi, pain, Samuukxs    |
|            8 |     4100 | 2024-02-21 | Mindfreak          | L   | 0.096      | -            | -                | -                | -         |    -1.67 | Estate, Hassie, Mingovi, pain, Samuukxs    |
|            7 |     4128 | 2024-02-20 | Cringexe           | L   | 0.089      | -            | -                | -                | -         |    -2.17 | dpr, Estate, Hassie, Mingovi, Samuukxs     |
|            6 |     4173 | 2024-02-18 | Arcade             | L   | 0.075      | -            | -                | -                | -         |    -1.29 | dpr, Hassie, Lexon, Mingovi, Samuukxs      |
|            5 |     4227 | 2024-02-16 | sunday school      | L   | 0.063      | -            | -                | -                | -         |    -1.19 | Estate, Hassie, Mingovi, pain, Samuukxs    |
|            4 |     4255 | 2024-02-15 | sunday school      | W   | 0.056      | 0.143        | 0.003 (0.000)    | -                | 0 (0.000) |     0.70 | Estate, Hassie, Mingovi, pain, Samuukxs    |
|            3 |     4256 | 2024-02-14 | Vantage            | W   | 0.055      | 0.143        | -                | 0.069 (0.001)    | -         |     0.73 | Estate, Hassie, Mingovi, pain, Samuukxs    |
|            2 |     4297 | 2024-02-13 | Mindfreak          | W   | 0.048      | 0.143        | 0.004 (0.000)    | 0.050 (0.000)    | -         |     0.68 | Estate, Hassie, Mingovi, pain, Samuukxs    |
|            1 |     4322 | 2024-02-13 | RKON               | W   | 0.042      | 0.143        | -                | 0.031 (0.000)    | -         |     0.32 | Estate, Hassie, Mingovi, pain, Samuukxs    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,754.04)
- Divide that value by the 5th highest value among all rosters ($323,321.90)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-08 |      0.821 | $450.00        | $369.63         |
| 2024-04-28 |      0.542 | $2,000.00      | $1,084.54       |
| 2024-03-23 |      0.302 | $992.00        | $299.87         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
