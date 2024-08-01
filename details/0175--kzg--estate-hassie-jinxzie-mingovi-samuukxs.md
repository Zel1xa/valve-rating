### Roster Details<br />
Team Name: KZG<br />
Roster: Estate, Hassie, JiNxZiE, Mingovi, Samuukxs<br />
Global Rank: [175](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [16]( ../standings_asia.md)<br />
<br />
Final Rank Value:  665.0<br />
<br />
Final Rank Value (665.0) = Starting Rank Value (711.3) + Head To Head Adjustments (-46.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.308[<sup>1</sup>](#table2)
- Bounty Collected: 0.228[<sup>2</sup>](#table1)
- Opponent Network: 0.032[<sup>2</sup>](#table1)
- LAN Wins: 0.038[<sup>2</sup>](#table1)

The average of these factors is 0.151<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 711.3
- 400 + ( ( 0.151 - 0.000 ) / ( 0.777 - 0.000 ) ) * 1600 = 711.3


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
|           35 |      102 | 2024-07-30 | Above The Rest     | L   | 1.000      | -            | -                | -                | -         |   -22.51 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           34 |      323 | 2024-07-23 | DXA                | W   | 1.000      | 0.333        | 0.002 (0.001)    | 0.228 (0.076)    | 0 (0.000) |    14.29 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           33 |      328 | 2024-07-23 | DXA                | W   | 1.000      | 0.333        | 0.002 (0.001)    | 0.228 (0.076)    | 0 (0.000) |    15.61 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           32 |      351 | 2024-07-22 | Arcade             | W   | 1.000      | 0.333        | 0.003 (0.001)    | 0.138 (0.046)    | 0 (0.000) |    15.03 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           31 |      354 | 2024-07-22 | Arcade             | L   | 1.000      | -            | -                | -                | -         |   -16.54 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           30 |     1758 | 2024-05-22 | Bad News Kangaroos | L   | 0.726      | -            | -                | -                | -         |    -9.98 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           29 |     1763 | 2024-05-22 | Bad News Kangaroos | L   | 0.726      | -            | -                | -                | -         |   -10.63 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           28 |     2033 | 2024-05-15 | DXA                | W   | 0.679      | 0.333        | 0.002 (0.001)    | 0.228 (0.052)    | 0 (0.000) |     9.79 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           27 |     2040 | 2024-05-15 | DXA                | W   | 0.679      | 0.333        | 0.002 (0.001)    | 0.228 (0.052)    | 0 (0.000) |    10.40 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           26 |     2237 | 2024-05-08 | Rooster            | L   | 0.633      | -            | -                | -                | -         |    -6.01 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           25 |     2240 | 2024-05-08 | Rooster            | L   | 0.632      | -            | -                | -                | -         |    -6.30 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           24 |     2496 | 2024-04-26 | Rooster            | L   | 0.553      | -            | -                | -                | -         |    -5.75 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           23 |     2500 | 2024-04-25 | MIBR               | L   | 0.551      | -            | -                | -                | -         |    -0.23 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           22 |     2765 | 2024-04-17 | Mindfreak          | L   | 0.493      | -            | -                | -                | -         |    -7.68 | Hassie, Jynx, KRAXYT, Mingovi, Samuukxs    |
|           21 |     2941 | 2024-04-10 | Canon Event        | W   | 0.446      | 0.333        | 0.000 (0.000)    | -                | 0 (0.000) |     3.54 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           20 |     2946 | 2024-04-10 | Canon Event        | W   | 0.446      | 0.333        | 0.000 (0.000)    | -                | 0 (0.000) |     3.65 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           19 |     3173 | 2024-04-03 | Vantage            | L   | 0.400      | -            | -                | -                | -         |    -6.60 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           18 |     3180 | 2024-04-03 | Vantage            | L   | 0.399      | -            | -                | -                | -         |    -6.83 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           17 |     3309 | 2024-03-27 | FlyQuest           | L   | 0.353      | -            | -                | -                | -         |    -0.69 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           16 |     3314 | 2024-03-27 | FlyQuest           | L   | 0.353      | -            | -                | -                | -         |    -0.69 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           15 |     3361 | 2024-03-23 | Arcade             | W   | 0.326      | 0.315        | 0.003 (0.000)    | 0.138 (0.014)    | 1 (0.326) |     4.97 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           14 |     3362 | 2024-03-23 | DXA                | L   | 0.325      | -            | -                | -                | -         |    -5.20 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           13 |     3586 | 2024-03-13 | RKON               | L   | 0.260      | -            | -                | -                | -         |    -6.09 | bebest, Estate, Hassie, Mingovi, Samuukxs  |
|           12 |     3593 | 2024-03-13 | RKON               | W   | 0.259      | 0.333        | -                | 0.034 (0.003)    | 0 (0.000) |     2.10 | bebest, Estate, Hassie, Mingovi, Samuukxs  |
|           11 |     3763 | 2024-03-06 | Arcade             | L   | 0.213      | -            | -                | -                | -         |    -3.56 | Estate, Hassie, Mingovi, pain, Samuukxs    |
|           10 |     3769 | 2024-03-06 | Arcade             | L   | 0.213      | -            | -                | -                | -         |    -3.62 | Estate, Hassie, Mingovi, pain, Samuukxs    |
|            9 |     4081 | 2024-02-21 | Mindfreak          | L   | 0.120      | -            | -                | -                | -         |    -2.07 | Estate, Hassie, Mingovi, pain, Samuukxs    |
|            8 |     4086 | 2024-02-21 | Mindfreak          | L   | 0.119      | -            | -                | -                | -         |    -2.09 | Estate, Hassie, Mingovi, pain, Samuukxs    |
|            7 |     4114 | 2024-02-20 | Cringexe           | L   | 0.113      | -            | -                | -                | -         |    -2.76 | dpr, Estate, Hassie, Mingovi, Samuukxs     |
|            6 |     4158 | 2024-02-18 | Arcade             | L   | 0.099      | -            | -                | -                | -         |    -1.74 | dpr, Hassie, Lexon, Mingovi, Samuukxs      |
|            5 |     4213 | 2024-02-16 | sunday school      | L   | 0.086      | -            | -                | -                | -         |    -1.64 | Estate, Hassie, Mingovi, pain, Samuukxs    |
|            4 |     4241 | 2024-02-15 | sunday school      | W   | 0.079      | 0.143        | 0.003 (0.000)    | -                | 0 (0.000) |     0.99 | Estate, Hassie, Mingovi, pain, Samuukxs    |
|            3 |     4242 | 2024-02-14 | Vantage            | W   | 0.078      | 0.143        | -                | 0.075 (0.001)    | -         |     1.04 | Estate, Hassie, Mingovi, pain, Samuukxs    |
|            2 |     4283 | 2024-02-13 | Mindfreak          | W   | 0.072      | 0.143        | 0.004 (0.000)    | 0.053 (0.001)    | -         |     1.00 | Estate, Hassie, Mingovi, pain, Samuukxs    |
|            1 |     4316 | 2024-02-13 | RKON               | W   | 0.066      | 0.143        | -                | 0.034 (0.000)    | -         |     0.49 | Estate, Hassie, Mingovi, pain, Samuukxs    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,835.30)
- Divide that value by the 5th highest value among all rosters ($327,422.13)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-08 |      0.845 | $450.00        | $380.25         |
| 2024-04-28 |      0.566 | $2,000.00      | $1,131.76       |
| 2024-03-23 |      0.326 | $992.00        | $323.30         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
