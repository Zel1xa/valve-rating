### Roster Details<br />
Team Name: KZG<br />
Roster: Estate, Hassie, JiNxZiE, Mingovi, Samuukxs<br />
Global Rank: [165](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [16]( ../standings_asia.md)<br />
<br />
Final Rank Value:  671.8<br />
<br />
Final Rank Value (671.8) = Starting Rank Value (705.6) + Head To Head Adjustments (-33.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.306[<sup>1</sup>](#table2)
- Bounty Collected: 0.226[<sup>2</sup>](#table1)
- Opponent Network: 0.030[<sup>2</sup>](#table1)
- LAN Wins: 0.034[<sup>2</sup>](#table1)

The average of these factors is 0.149<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 705.6
- 400 + ( ( 0.149 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 705.6


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
|           35 |      250 | 2024-07-30 | Above The Rest     | L   | 1.000      | -            | -                | -                | -         |   -22.78 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           34 |      471 | 2024-07-23 | DXA                | W   | 1.000      | 0.333        | 0.002 (0.001)    | 0.222 (0.074)    | 0 (0.000) |    14.49 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           33 |      475 | 2024-07-23 | DXA                | W   | 1.000      | 0.333        | 0.002 (0.001)    | 0.222 (0.074)    | 0 (0.000) |    15.83 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           32 |      498 | 2024-07-22 | Arcade             | W   | 1.000      | 0.333        | 0.002 (0.001)    | 0.134 (0.045)    | 0 (0.000) |    15.51 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           31 |      500 | 2024-07-22 | Arcade             | L   | 1.000      | -            | -                | -                | -         |   -16.01 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           30 |     1871 | 2024-05-22 | Bad News Kangaroos | L   | 0.696      | -            | -                | -                | -         |    -6.66 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           29 |     1876 | 2024-05-22 | Bad News Kangaroos | L   | 0.696      | -            | -                | -                | -         |    -7.02 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           28 |     2126 | 2024-05-15 | DXA                | W   | 0.649      | 0.333        | 0.002 (0.000)    | 0.222 (0.048)    | 0 (0.000) |     9.59 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           27 |     2133 | 2024-05-15 | DXA                | W   | 0.649      | 0.333        | 0.002 (0.000)    | 0.222 (0.048)    | 0 (0.000) |    10.15 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           26 |     2323 | 2024-05-08 | Rooster            | L   | 0.603      | -            | -                | -                | -         |    -5.91 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           25 |     2326 | 2024-05-08 | Rooster            | L   | 0.602      | -            | -                | -                | -         |    -6.19 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           24 |     2579 | 2024-04-26 | Rooster            | L   | 0.522      | -            | -                | -                | -         |    -5.60 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           23 |     2583 | 2024-04-25 | MIBR               | L   | 0.521      | -            | -                | -                | -         |    -0.21 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           22 |     2839 | 2024-04-17 | Mindfreak          | L   | 0.463      | -            | -                | -                | -         |    -7.08 | Hassie, Jynx, KRAXYT, Mingovi, Samuukxs    |
|           21 |     3013 | 2024-04-10 | Canon Event        | W   | 0.416      | 0.333        | 0.000 (0.000)    | -                | 0 (0.000) |     3.36 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           20 |     3018 | 2024-04-10 | Canon Event        | W   | 0.416      | 0.333        | 0.000 (0.000)    | -                | 0 (0.000) |     3.45 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           19 |     3239 | 2024-04-03 | Vantage            | L   | 0.369      | -            | -                | -                | -         |    -6.14 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           18 |     3246 | 2024-04-03 | Vantage            | L   | 0.369      | -            | -                | -                | -         |    -6.34 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           17 |     3372 | 2024-03-27 | FlyQuest           | L   | 0.323      | -            | -                | -                | -         |    -0.70 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           16 |     3377 | 2024-03-27 | FlyQuest           | L   | 0.323      | -            | -                | -                | -         |    -0.70 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           15 |     3420 | 2024-03-23 | Arcade             | W   | 0.296      | 0.315        | 0.002 (0.000)    | 0.134 (0.012)    | 1 (0.296) |     4.60 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           14 |     3421 | 2024-03-23 | DXA                | L   | 0.295      | -            | -                | -                | -         |    -4.62 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           13 |     3641 | 2024-03-13 | RKON               | L   | 0.229      | -            | -                | -                | -         |    -5.38 | bebest, Estate, Hassie, Mingovi, Samuukxs  |
|           12 |     3648 | 2024-03-13 | RKON               | W   | 0.229      | 0.333        | -                | 0.030 (0.002)    | 0 (0.000) |     1.86 | bebest, Estate, Hassie, Mingovi, Samuukxs  |
|           11 |     3816 | 2024-03-06 | Arcade             | L   | 0.183      | -            | -                | -                | -         |    -2.98 | Estate, Hassie, Mingovi, pain, Samuukxs    |
|           10 |     3822 | 2024-03-06 | Arcade             | L   | 0.182      | -            | -                | -                | -         |    -3.03 | Estate, Hassie, Mingovi, pain, Samuukxs    |
|            9 |     4119 | 2024-02-21 | Mindfreak          | L   | 0.089      | -            | -                | -                | -         |    -1.54 | Estate, Hassie, Mingovi, pain, Samuukxs    |
|            8 |     4124 | 2024-02-21 | Mindfreak          | L   | 0.089      | -            | -                | -                | -         |    -1.55 | Estate, Hassie, Mingovi, pain, Samuukxs    |
|            7 |     4152 | 2024-02-20 | Cringexe           | L   | 0.082      | -            | -                | -                | -         |    -2.01 | dpr, Estate, Hassie, Mingovi, Samuukxs     |
|            6 |     4197 | 2024-02-18 | Arcade             | L   | 0.069      | -            | -                | -                | -         |    -1.17 | dpr, Hassie, Lexon, Mingovi, Samuukxs      |
|            5 |     4251 | 2024-02-16 | sunday school      | L   | 0.056      | -            | -                | -                | -         |    -1.06 | Estate, Hassie, Mingovi, pain, Samuukxs    |
|            4 |     4279 | 2024-02-15 | sunday school      | W   | 0.049      | 0.143        | 0.003 (0.000)    | -                | 0 (0.000) |     0.61 | Estate, Hassie, Mingovi, pain, Samuukxs    |
|            3 |     4280 | 2024-02-14 | Vantage            | W   | 0.048      | 0.143        | -                | 0.067 (0.000)    | -         |     0.65 | Estate, Hassie, Mingovi, pain, Samuukxs    |
|            2 |     4321 | 2024-02-13 | Mindfreak          | W   | 0.042      | 0.143        | 0.004 (0.000)    | 0.048 (0.000)    | -         |     0.58 | Estate, Hassie, Mingovi, pain, Samuukxs    |
|            1 |     4346 | 2024-02-13 | RKON               | W   | 0.036      | 0.143        | -                | 0.030 (0.000)    | -         |     0.27 | Estate, Hassie, Mingovi, pain, Samuukxs    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,731.09)
- Divide that value by the 5th highest value among all rosters ($321,345.23)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-08 |      0.815 | $450.00        | $366.63         |
| 2024-04-28 |      0.536 | $2,000.00      | $1,071.20       |
| 2024-03-23 |      0.296 | $992.00        | $293.26         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
