### Roster Details<br />
Team Name: KZG<br />
Roster: Estate, Hassie, JiNxZiE, Mingovi, Samuukxs<br />
Global Rank: [173](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [17]( ../standings_asia.md)<br />
<br />
Final Rank Value:  662.1<br />
<br />
Final Rank Value (662.1) = Starting Rank Value (706.3) + Head To Head Adjustments (-44.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.307[<sup>1</sup>](#table2)
- Bounty Collected: 0.226[<sup>2</sup>](#table1)
- Opponent Network: 0.031[<sup>2</sup>](#table1)
- LAN Wins: 0.035[<sup>2</sup>](#table1)

The average of these factors is 0.150<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 706.3
- 400 + ( ( 0.150 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 706.3


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
|           35 |      187 | 2024-07-30 | Above The Rest     | L   | 1.000      | -            | -                | -                | -         |   -22.44 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           34 |      408 | 2024-07-23 | DXA                | W   | 1.000      | 0.333        | 0.002 (0.001)    | 0.227 (0.076)    | 0 (0.000) |    14.28 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           33 |      413 | 2024-07-23 | DXA                | W   | 1.000      | 0.333        | 0.002 (0.001)    | 0.227 (0.076)    | 0 (0.000) |    15.60 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           32 |      435 | 2024-07-22 | Arcade             | W   | 1.000      | 0.333        | 0.002 (0.001)    | 0.137 (0.046)    | 0 (0.000) |    15.02 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           31 |      438 | 2024-07-22 | Arcade             | L   | 1.000      | -            | -                | -                | -         |   -16.55 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           30 |     1807 | 2024-05-22 | Bad News Kangaroos | L   | 0.710      | -            | -                | -                | -         |    -9.82 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           29 |     1812 | 2024-05-22 | Bad News Kangaroos | L   | 0.709      | -            | -                | -                | -         |   -10.45 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           28 |     2062 | 2024-05-15 | DXA                | W   | 0.663      | 0.333        | 0.002 (0.001)    | 0.227 (0.050)    | 0 (0.000) |     9.57 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           27 |     2069 | 2024-05-15 | DXA                | W   | 0.663      | 0.333        | 0.002 (0.001)    | 0.227 (0.050)    | 0 (0.000) |    10.15 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           26 |     2259 | 2024-05-08 | Rooster            | L   | 0.616      | -            | -                | -                | -         |    -6.05 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           25 |     2262 | 2024-05-08 | Rooster            | L   | 0.616      | -            | -                | -                | -         |    -6.34 | Estate, Hassie, JiNxZiE, Mingovi, Samuukxs |
|           24 |     2514 | 2024-04-26 | Rooster            | L   | 0.536      | -            | -                | -                | -         |    -5.77 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           23 |     2518 | 2024-04-25 | MIBR               | L   | 0.534      | -            | -                | -                | -         |    -0.21 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           22 |     2774 | 2024-04-17 | Mindfreak          | L   | 0.476      | -            | -                | -                | -         |    -7.44 | Hassie, Jynx, KRAXYT, Mingovi, Samuukxs    |
|           21 |     2948 | 2024-04-10 | Canon Event        | W   | 0.430      | 0.333        | 0.000 (0.000)    | -                | 0 (0.000) |     3.46 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           20 |     2953 | 2024-04-10 | Canon Event        | W   | 0.429      | 0.333        | 0.000 (0.000)    | -                | 0 (0.000) |     3.56 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           19 |     3174 | 2024-04-03 | Vantage            | L   | 0.383      | -            | -                | -                | -         |    -6.33 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           18 |     3181 | 2024-04-03 | Vantage            | L   | 0.383      | -            | -                | -                | -         |    -6.55 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           17 |     3307 | 2024-03-27 | FlyQuest           | L   | 0.337      | -            | -                | -                | -         |    -0.70 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           16 |     3312 | 2024-03-27 | FlyQuest           | L   | 0.336      | -            | -                | -                | -         |    -0.71 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           15 |     3355 | 2024-03-23 | Arcade             | W   | 0.310      | 0.315        | 0.002 (0.000)    | 0.137 (0.013)    | 1 (0.310) |     4.70 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           14 |     3356 | 2024-03-23 | DXA                | L   | 0.309      | -            | -                | -                | -         |    -4.94 | Estate, Hassie, KRAXYT, Mingovi, Samuukxs  |
|           13 |     3575 | 2024-03-13 | RKON               | L   | 0.243      | -            | -                | -                | -         |    -5.70 | bebest, Estate, Hassie, Mingovi, Samuukxs  |
|           12 |     3582 | 2024-03-13 | RKON               | W   | 0.243      | 0.333        | -                | 0.032 (0.003)    | 0 (0.000) |     1.98 | bebest, Estate, Hassie, Mingovi, Samuukxs  |
|           11 |     3750 | 2024-03-06 | Arcade             | L   | 0.197      | -            | -                | -                | -         |    -3.29 | Estate, Hassie, Mingovi, pain, Samuukxs    |
|           10 |     3756 | 2024-03-06 | Arcade             | L   | 0.196      | -            | -                | -                | -         |    -3.34 | Estate, Hassie, Mingovi, pain, Samuukxs    |
|            9 |     4053 | 2024-02-21 | Mindfreak          | L   | 0.103      | -            | -                | -                | -         |    -1.79 | Estate, Hassie, Mingovi, pain, Samuukxs    |
|            8 |     4058 | 2024-02-21 | Mindfreak          | L   | 0.103      | -            | -                | -                | -         |    -1.80 | Estate, Hassie, Mingovi, pain, Samuukxs    |
|            7 |     4086 | 2024-02-20 | Cringexe           | L   | 0.096      | -            | -                | -                | -         |    -2.35 | dpr, Estate, Hassie, Mingovi, Samuukxs     |
|            6 |     4130 | 2024-02-18 | Arcade             | L   | 0.083      | -            | -                | -                | -         |    -1.45 | dpr, Hassie, Lexon, Mingovi, Samuukxs      |
|            5 |     4184 | 2024-02-16 | sunday school      | L   | 0.070      | -            | -                | -                | -         |    -1.33 | Estate, Hassie, Mingovi, pain, Samuukxs    |
|            4 |     4212 | 2024-02-15 | sunday school      | W   | 0.063      | 0.143        | 0.003 (0.000)    | -                | 0 (0.000) |     0.79 | Estate, Hassie, Mingovi, pain, Samuukxs    |
|            3 |     4213 | 2024-02-14 | Vantage            | W   | 0.062      | 0.143        | -                | 0.071 (0.001)    | -         |     0.83 | Estate, Hassie, Mingovi, pain, Samuukxs    |
|            2 |     4254 | 2024-02-13 | Mindfreak          | W   | 0.056      | 0.143        | 0.004 (0.000)    | 0.051 (0.000)    | -         |     0.78 | Estate, Hassie, Mingovi, pain, Samuukxs    |
|            1 |     4279 | 2024-02-13 | RKON               | W   | 0.049      | 0.143        | -                | 0.032 (0.000)    | -         |     0.38 | Estate, Hassie, Mingovi, pain, Samuukxs    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,778.89)
- Divide that value by the 5th highest value among all rosters ($325,463.29)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-08 |      0.829 | $450.00        | $372.88         |
| 2024-04-28 |      0.549 | $2,000.00      | $1,098.98       |
| 2024-03-23 |      0.310 | $992.00        | $307.04         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
