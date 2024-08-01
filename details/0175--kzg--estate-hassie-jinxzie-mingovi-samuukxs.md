### Roster Details<br />
Team Name: KZG<br />
Roster: Estate, Hassie, JiNxZiE, Mingovi, Samuukxs<br />
Global Rank: [175](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [16]( ../standings_asia.md)<br />
<br />
Final Rank Value:  664.7<br />
<br />
Final Rank Value (664.7) = Starting Rank Value (710.8) + Head To Head Adjustments (-46.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.308[<sup>1</sup>](#table2)
- Bounty Collected: 0.227[<sup>2</sup>](#table1)
- Opponent Network: 0.032[<sup>2</sup>](#table1)
- LAN Wins: 0.037[<sup>2</sup>](#table1)

The average of these factors is 0.151<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 710.8
- 400 + ( ( 0.151 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 710.8


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
|           35 |      106 | 2024-07-30 | Above The Rest     | L   | 1.000      | -            | -                | -                | -         |   -22.50 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           34 |      327 | 2024-07-23 | DXA                | W   | 1.000      | 0.333        | 0.002 (0.001)    | 0.228 (0.076)    | 0 (0.000) |    14.29 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           33 |      332 | 2024-07-23 | DXA                | W   | 1.000      | 0.333        | 0.002 (0.001)    | 0.228 (0.076)    | 0 (0.000) |    15.61 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           32 |      355 | 2024-07-22 | Arcade             | W   | 1.000      | 0.333        | 0.003 (0.001)    | 0.138 (0.046)    | 0 (0.000) |    15.03 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           31 |      358 | 2024-07-22 | Arcade             | L   | 1.000      | -            | -                | -                | -         |   -16.54 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           30 |     1762 | 2024-05-22 | Bad News Kangaroos | L   | 0.725      | -            | -                | -                | -         |    -9.96 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           29 |     1767 | 2024-05-22 | Bad News Kangaroos | L   | 0.724      | -            | -                | -                | -         |   -10.62 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           28 |     2037 | 2024-05-15 | DXA                | W   | 0.678      | 0.333        | 0.002 (0.001)    | 0.228 (0.051)    | 0 (0.000) |     9.77 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           27 |     2044 | 2024-05-15 | DXA                | W   | 0.678      | 0.333        | 0.002 (0.001)    | 0.228 (0.051)    | 0 (0.000) |    10.38 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           26 |     2241 | 2024-05-08 | Rooster            | L   | 0.631      | -            | -                | -                | -         |    -6.00 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           25 |     2244 | 2024-05-08 | Rooster            | L   | 0.631      | -            | -                | -                | -         |    -6.29 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           24 |     2500 | 2024-04-26 | Rooster            | L   | 0.551      | -            | -                | -                | -         |    -5.75 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           23 |     2504 | 2024-04-25 | MIBR               | L   | 0.549      | -            | -                | -                | -         |    -0.23 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           22 |     2769 | 2024-04-17 | Mindfreak          | L   | 0.491      | -            | -                | -                | -         |    -7.66 | Hassie, Jynx, KRAXYT, Mingovi, Samuukxs    |
|           21 |     2945 | 2024-04-10 | Canon Event        | W   | 0.445      | 0.333        | 0.000 (0.000)    | -                | 0 (0.000) |     3.53 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           20 |     2950 | 2024-04-10 | Canon Event        | W   | 0.444      | 0.333        | 0.000 (0.000)    | -                | 0 (0.000) |     3.64 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           19 |     3177 | 2024-04-03 | Vantage            | L   | 0.398      | -            | -                | -                | -         |    -6.57 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           18 |     3184 | 2024-04-03 | Vantage            | L   | 0.398      | -            | -                | -                | -         |    -6.80 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           17 |     3313 | 2024-03-27 | FlyQuest           | L   | 0.352      | -            | -                | -                | -         |    -0.69 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           16 |     3318 | 2024-03-27 | FlyQuest           | L   | 0.351      | -            | -                | -                | -         |    -0.69 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           15 |     3365 | 2024-03-23 | Arcade             | W   | 0.325      | 0.315        | 0.003 (0.000)    | 0.138 (0.014)    | 1 (0.325) |     4.95 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           14 |     3366 | 2024-03-23 | DXA                | L   | 0.324      | -            | -                | -                | -         |    -5.17 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           13 |     3590 | 2024-03-13 | RKON               | L   | 0.258      | -            | -                | -                | -         |    -6.06 | bebest, Estate, Hassie, Mingovi, Samuukxs  |
|           12 |     3597 | 2024-03-13 | RKON               | W   | 0.258      | 0.333        | -                | 0.034 (0.003)    | 0 (0.000) |     2.09 | bebest, Estate, Hassie, Mingovi, Samuukxs  |
|           11 |     3767 | 2024-03-06 | Arcade             | L   | 0.212      | -            | -                | -                | -         |    -3.53 | Estate, Hassie, Mingovi, pain, Samuukxs    |
|           10 |     3773 | 2024-03-06 | Arcade             | L   | 0.211      | -            | -                | -                | -         |    -3.59 | Estate, Hassie, Mingovi, pain, Samuukxs    |
|            9 |     4085 | 2024-02-21 | Mindfreak          | L   | 0.118      | -            | -                | -                | -         |    -2.05 | Estate, Hassie, Mingovi, pain, Samuukxs    |
|            8 |     4090 | 2024-02-21 | Mindfreak          | L   | 0.118      | -            | -                | -                | -         |    -2.07 | Estate, Hassie, Mingovi, pain, Samuukxs    |
|            7 |     4118 | 2024-02-20 | Cringexe           | L   | 0.111      | -            | -                | -                | -         |    -2.73 | dpr, Estate, Hassie, Mingovi, Samuukxs     |
|            6 |     4162 | 2024-02-18 | Arcade             | L   | 0.098      | -            | -                | -                | -         |    -1.72 | dpr, Hassie, Lexon, Mingovi, Samuukxs      |
|            5 |     4217 | 2024-02-16 | sunday school      | L   | 0.085      | -            | -                | -                | -         |    -1.62 | Estate, Hassie, Mingovi, pain, Samuukxs    |
|            4 |     4245 | 2024-02-15 | sunday school      | W   | 0.078      | 0.143        | 0.003 (0.000)    | -                | 0 (0.000) |     0.97 | Estate, Hassie, Mingovi, pain, Samuukxs    |
|            3 |     4246 | 2024-02-14 | Vantage            | W   | 0.077      | 0.143        | -                | 0.075 (0.001)    | -         |     1.02 | Estate, Hassie, Mingovi, pain, Samuukxs    |
|            2 |     4287 | 2024-02-13 | Mindfreak          | W   | 0.071      | 0.143        | 0.004 (0.000)    | 0.053 (0.001)    | -         |     0.98 | Estate, Hassie, Mingovi, pain, Samuukxs    |
|            1 |     4320 | 2024-02-13 | RKON               | W   | 0.064      | 0.143        | -                | 0.034 (0.000)    | -         |     0.48 | Estate, Hassie, Mingovi, pain, Samuukxs    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,830.52)
- Divide that value by the 5th highest value among all rosters ($327,030.46)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-08 |      0.844 | $450.00        | $379.63         |
| 2024-04-28 |      0.564 | $2,000.00      | $1,128.98       |
| 2024-03-23 |      0.325 | $992.00        | $321.92         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
