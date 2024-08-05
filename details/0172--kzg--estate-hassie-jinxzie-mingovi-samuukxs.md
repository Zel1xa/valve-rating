### Roster Details<br />
Team Name: KZG<br />
Roster: Estate, Hassie, JiNxZiE, Mingovi, Samuukxs<br />
Global Rank: [172](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [15]( ../standings_asia.md)<br />
<br />
Final Rank Value:  664.8<br />
<br />
Final Rank Value (664.8) = Starting Rank Value (711.9) + Head To Head Adjustments (-47.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.307[<sup>1</sup>](#table2)
- Bounty Collected: 0.228[<sup>2</sup>](#table1)
- Opponent Network: 0.032[<sup>2</sup>](#table1)
- LAN Wins: 0.038[<sup>2</sup>](#table1)

The average of these factors is 0.151<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 711.9
- 400 + ( ( 0.151 - 0.000 ) / ( 0.776 - 0.000 ) ) * 1600 = 711.9


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
|           35 |       73 | 2024-07-30 | Above The Rest     | L   | 1.000      | -            | -                | -                | -         |   -22.50 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           34 |      294 | 2024-07-23 | DXA                | W   | 1.000      | 0.333        | 0.002 (0.001)    | 0.228 (0.076)    | 0 (0.000) |    14.29 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           33 |      298 | 2024-07-23 | DXA                | W   | 1.000      | 0.333        | 0.002 (0.001)    | 0.228 (0.076)    | 0 (0.000) |    15.61 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           32 |      321 | 2024-07-22 | Arcade             | W   | 1.000      | 0.333        | 0.003 (0.001)    | 0.139 (0.046)    | 0 (0.000) |    15.04 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           31 |      323 | 2024-07-22 | Arcade             | L   | 1.000      | -            | -                | -                | -         |   -16.52 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           30 |     1694 | 2024-05-22 | Bad News Kangaroos | L   | 0.730      | -            | -                | -                | -         |   -10.05 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           29 |     1699 | 2024-05-22 | Bad News Kangaroos | L   | 0.730      | -            | -                | -                | -         |   -10.71 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           28 |     1949 | 2024-05-15 | DXA                | W   | 0.684      | 0.333        | 0.002 (0.001)    | 0.228 (0.052)    | 0 (0.000) |     9.85 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           27 |     1956 | 2024-05-15 | DXA                | W   | 0.684      | 0.333        | 0.002 (0.001)    | 0.228 (0.052)    | 0 (0.000) |    10.46 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           26 |     2146 | 2024-05-08 | Rooster            | L   | 0.637      | -            | -                | -                | -         |    -6.11 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           25 |     2149 | 2024-05-08 | Rooster            | L   | 0.637      | -            | -                | -                | -         |    -6.41 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           24 |     2402 | 2024-04-26 | Rooster            | L   | 0.557      | -            | -                | -                | -         |    -5.87 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           23 |     2406 | 2024-04-25 | MIBR               | L   | 0.555      | -            | -                | -                | -         |    -0.21 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           22 |     2662 | 2024-04-17 | Mindfreak          | L   | 0.497      | -            | -                | -                | -         |    -7.71 | Hassie, Jynx, KRAXYT, Mingovi, Samuukxs    |
|           21 |     2836 | 2024-04-10 | Canon Event        | W   | 0.450      | 0.333        | 0.000 (0.000)    | -                | 0 (0.000) |     3.57 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           20 |     2841 | 2024-04-10 | Canon Event        | W   | 0.450      | 0.333        | 0.000 (0.000)    | -                | 0 (0.000) |     3.67 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           19 |     3062 | 2024-04-03 | Vantage            | L   | 0.404      | -            | -                | -                | -         |    -6.68 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           18 |     3069 | 2024-04-03 | Vantage            | L   | 0.404      | -            | -                | -                | -         |    -6.92 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           17 |     3195 | 2024-03-27 | FlyQuest           | L   | 0.357      | -            | -                | -                | -         |    -0.67 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           16 |     3200 | 2024-03-27 | FlyQuest           | L   | 0.357      | -            | -                | -                | -         |    -0.68 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           15 |     3243 | 2024-03-23 | Arcade             | W   | 0.330      | 0.315        | 0.003 (0.000)    | 0.139 (0.014)    | 1 (0.330) |     5.05 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           14 |     3244 | 2024-03-23 | DXA                | L   | 0.330      | -            | -                | -                | -         |    -5.27 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           13 |     3464 | 2024-03-13 | RKON               | L   | 0.264      | -            | -                | -                | -         |    -6.20 | bebest, Estate, Hassie, Mingovi, Samuukxs  |
|           12 |     3471 | 2024-03-13 | RKON               | W   | 0.264      | 0.333        | -                | 0.035 (0.003)    | 0 (0.000) |     2.14 | bebest, Estate, Hassie, Mingovi, Samuukxs  |
|           11 |     3639 | 2024-03-06 | Arcade             | L   | 0.217      | -            | -                | -                | -         |    -3.62 | Estate, Hassie, Mingovi, pain, Samuukxs    |
|           10 |     3645 | 2024-03-06 | Arcade             | L   | 0.217      | -            | -                | -                | -         |    -3.69 | Estate, Hassie, Mingovi, pain, Samuukxs    |
|            9 |     3942 | 2024-02-21 | Mindfreak          | L   | 0.124      | -            | -                | -                | -         |    -2.15 | Estate, Hassie, Mingovi, pain, Samuukxs    |
|            8 |     3947 | 2024-02-21 | Mindfreak          | L   | 0.124      | -            | -                | -                | -         |    -2.17 | Estate, Hassie, Mingovi, pain, Samuukxs    |
|            7 |     3975 | 2024-02-20 | Cringexe           | L   | 0.117      | -            | -                | -                | -         |    -2.87 | dpr, Estate, Hassie, Mingovi, Samuukxs     |
|            6 |     4020 | 2024-02-18 | Arcade             | L   | 0.103      | -            | -                | -                | -         |    -1.82 | dpr, Hassie, Lexon, Mingovi, Samuukxs      |
|            5 |     4074 | 2024-02-16 | sunday school      | L   | 0.090      | -            | -                | -                | -         |    -1.73 | Estate, Hassie, Mingovi, pain, Samuukxs    |
|            4 |     4102 | 2024-02-15 | sunday school      | W   | 0.084      | 0.143        | 0.003 (0.000)    | -                | 0 (0.000) |     1.04 | Estate, Hassie, Mingovi, pain, Samuukxs    |
|            3 |     4103 | 2024-02-14 | Vantage            | W   | 0.083      | 0.143        | -                | 0.076 (0.001)    | -         |     1.10 | Estate, Hassie, Mingovi, pain, Samuukxs    |
|            2 |     4144 | 2024-02-13 | Mindfreak          | W   | 0.076      | 0.143        | 0.004 (0.000)    | 0.054 (0.001)    | -         |     1.06 | Estate, Hassie, Mingovi, pain, Samuukxs    |
|            1 |     4169 | 2024-02-13 | RKON               | W   | 0.070      | 0.143        | -                | 0.035 (0.000)    | -         |     0.53 | Estate, Hassie, Mingovi, pain, Samuukxs    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,850.24)
- Divide that value by the 5th highest value among all rosters ($331,608.80)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-08 |      0.849 | $450.00        | $382.20         |
| 2024-04-28 |      0.570 | $2,000.00      | $1,140.44       |
| 2024-03-23 |      0.330 | $992.00        | $327.60         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
