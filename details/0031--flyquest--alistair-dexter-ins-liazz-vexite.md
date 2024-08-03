### Roster Details<br />
Team Name: FlyQuest<br />
Roster: aliStair, dexter, INS, Liazz, Vexite<br />
Global Rank: [31](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [2]( ../standings_asia.md)<br />
<br />
Final Rank Value:  1181.4<br />
<br />
Final Rank Value (1181.4) = Starting Rank Value (1157.9) + Head To Head Adjustments (23.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.505[<sup>1</sup>](#table2)
- Bounty Collected: 0.414[<sup>2</sup>](#table1)
- Opponent Network: 0.146[<sup>2</sup>](#table1)
- LAN Wins: 0.417[<sup>2</sup>](#table1)

The average of these factors is 0.370<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1157.9
- 400 + ( ( 0.370 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 1157.9


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent           | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                               |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           48 |      566 | 2024-07-18 | FURIA              | L   | 1.000      | -            | -                | -                | -         |    -3.20 | aliStair, dexter, INS, Liazz, Vexite |
|           47 |      631 | 2024-07-17 | FaZe               | L   | 1.000      | -            | -                | -                | -         |    -1.48 | aliStair, dexter, INS, Liazz, Vexite |
|           46 |     1168 | 2024-06-08 | Rooster            | W   | 0.830      | 0.333        | 0.010 (0.003)    | 0.275 (0.076)    | 0 (0.000) |     3.57 | aliStair, dexter, INS, Liazz, Vexite |
|           45 |     1218 | 2024-06-08 | Mindfreak          | W   | 0.824      | 0.333        | 0.004 (0.001)    | 0.214 (0.059)    | -         |     1.96 | aliStair, dexter, INS, Liazz, Vexite |
|           44 |     1273 | 2024-06-07 | Rooster            | L   | 0.818      | -            | -                | -                | -         |   -22.60 | aliStair, dexter, INS, Liazz, Vexite |
|           43 |     1598 | 2024-05-28 | BIG                | L   | 0.754      | -            | -                | -                | -         |    -8.90 | aliStair, dexter, INS, Liazz, Vexite |
|           42 |     1619 | 2024-05-27 | Spirit             | L   | 0.748      | -            | -                | -                | -         |    -0.48 | aliStair, dexter, INS, Liazz, Vexite |
|           41 |     1745 | 2024-05-22 | Mindfreak          | W   | 0.711      | 0.333        | 0.004 (0.001)    | 0.214 (0.051)    | -         |     1.32 | aliStair, dexter, INS, Liazz, Vexite |
|           40 |     1750 | 2024-05-22 | Mindfreak          | W   | 0.711      | 0.333        | -                | 0.214 (0.051)    | -         |     1.34 | aliStair, dexter, INS, Liazz, Vexite |
|           39 |     1820 | 2024-05-20 | Canon Event        | W   | 0.698      | -            | -                | -                | -         |     0.36 | aliStair, dexter, INS, Liazz, Vexite |
|           38 |     1822 | 2024-05-20 | Canon Event        | W   | 0.698      | -            | -                | -                | -         |     0.36 | aliStair, dexter, INS, Liazz, Vexite |
|           37 |     2189 | 2024-05-08 | Liquid             | L   | 0.619      | -            | -                | -                | -         |    -3.07 | aliStair, dexter, INS, Liazz, Vexite |
|           36 |     2207 | 2024-05-07 | BetBoom            | W   | 0.613      | 0.889        | 0.252 (0.137)    | 0.563 (0.307)    | 1 (0.613) |    14.35 | aliStair, dexter, INS, Liazz, Vexite |
|           35 |     2251 | 2024-05-05 | Ninjas in Pyjamas  | W   | 0.599      | 0.889        | 0.204 (0.108)    | 0.502 (0.267)    | 1 (0.599) |    16.52 | aliStair, dexter, INS, Liazz, Vexite |
|           34 |     2267 | 2024-05-04 | PERA               | W   | 0.592      | 0.889        | 0.048 (0.025)    | 0.468 (0.246)    | 1 (0.592) |     3.52 | aliStair, dexter, INS, Liazz, Vexite |
|           33 |     2283 | 2024-05-03 | HEROIC             | L   | 0.585      | -            | -                | -                | -         |    -1.90 | aliStair, dexter, INS, Liazz, Vexite |
|           32 |     2310 | 2024-05-02 | BOSS               | W   | 0.579      | 0.889        | 0.014 (0.007)    | 0.344 (0.177)    | 1 (0.579) |     2.16 | aliStair, dexter, INS, Liazz, Vexite |
|           31 |     2332 | 2024-05-01 | Natus Vincere      | L   | 0.572      | -            | -                | -                | -         |    -0.20 | aliStair, dexter, INS, Liazz, Vexite |
|           30 |     2578 | 2024-04-20 | Bad News Kangaroos | W   | 0.498      | 0.143        | 0.017 (0.001)    | -                | -         |     1.59 | aliStair, dexter, INS, Liazz, Vexite |
|           29 |     2624 | 2024-04-19 | Rooster            | W   | 0.492      | -            | -                | -                | -         |     1.72 | aliStair, dexter, INS, Liazz, Vexite |
|           28 |     2631 | 2024-04-18 | Mindfreak          | W   | 0.490      | -            | -                | -                | -         |     0.99 | aliStair, dexter, INS, Liazz, Vexite |
|           27 |     2876 | 2024-04-10 | FaZe               | L   | 0.432      | -            | -                | -                | -         |    -0.67 | aliStair, dexter, INS, Liazz, Vexite |
|           26 |     2891 | 2024-04-09 | Nemiga             | W   | 0.430      | 0.624        | 0.318 (0.086)    | 0.719 (0.193)    | 1 (0.430) |     6.40 | aliStair, dexter, INS, Liazz, Vexite |
|           25 |     2941 | 2024-04-08 | Virtus.pro         | L   | 0.424      | -            | -                | -                | -         |    -0.65 | aliStair, dexter, INS, Liazz, Vexite |
|           24 |     2972 | 2024-04-08 | Cloud9             | W   | 0.417      | 0.624        | 0.063 (0.016)    | 0.116 (0.030)    | 1 (0.417) |     4.96 | aliStair, dexter, INS, Liazz, Vexite |
|           23 |     3113 | 2024-04-03 | Arcade             | W   | 0.385      | -            | -                | -                | -         |     0.71 | aliStair, dexter, INS, Liazz, Vexite |
|           22 |     3118 | 2024-04-03 | Arcade             | W   | 0.384      | -            | -                | -                | -         |     0.71 | aliStair, dexter, INS, Liazz, Vexite |
|           21 |     3239 | 2024-03-27 | KZG                | W   | 0.338      | -            | -                | -                | -         |     0.63 | aliStair, dexter, INS, Liazz, Vexite |
|           20 |     3244 | 2024-03-27 | KZG                | W   | 0.338      | -            | -                | -                | -         |     0.63 | aliStair, dexter, INS, Liazz, Vexite |
|           19 |     3504 | 2024-03-13 | Rooster            | W   | 0.245      | -            | -                | -                | -         |     0.84 | aliStair, dexter, INS, Liazz, Vexite |
|           18 |     3512 | 2024-03-13 | Rooster            | W   | 0.245      | -            | -                | -                | -         |     0.84 | aliStair, dexter, INS, Liazz, Vexite |
|           17 |     3680 | 2024-03-06 | DXA                | W   | 0.198      | -            | -                | -                | -         |     0.41 | aliStair, dexter, INS, Liazz, Vexite |
|           16 |     3682 | 2024-03-06 | DXA                | W   | 0.198      | -            | -                | -                | -         |     0.41 | aliStair, dexter, INS, Liazz, Vexite |
|           15 |     3830 | 2024-02-27 | Lynn Vision        | L   | 0.151      | -            | -                | -                | -         |    -3.49 | aliStair, dexter, INS, Liazz, Vexite |
|           14 |     3831 | 2024-02-27 | ATOX               | W   | 0.150      | -            | -                | -                | 1 (0.150) |     0.76 | aliStair, dexter, INS, Liazz, Vexite |
|           13 |     3854 | 2024-02-27 | JiJieHao           | W   | 0.144      | -            | -                | -                | 1 (0.144) |     0.07 | aliStair, dexter, INS, Liazz, Vexite |
|           12 |     3868 | 2024-02-25 | The MongolZ        | L   | 0.137      | -            | -                | -                | -         |    -0.05 | aliStair, dexter, INS, Liazz, Vexite |
|           11 |     3871 | 2024-02-25 | ATOX               | W   | 0.136      | -            | -                | -                | 1 (0.136) |     0.69 | aliStair, dexter, INS, Liazz, Vexite |
|           10 |     3933 | 2024-02-23 | Rooster            | W   | 0.118      | -            | -                | -                | -         |     0.40 | aliStair, dexter, INS, Liazz, Vexite |
|            9 |     3952 | 2024-02-22 | Rooster            | W   | 0.111      | -            | -                | -                | -         |     0.37 | aliStair, dexter, INS, Liazz, Vexite |
|            8 |     3956 | 2024-02-21 | Bad News Kangaroos | W   | 0.110      | -            | -                | -                | -         |     0.34 | aliStair, dexter, INS, Liazz, Vexite |
|            7 |     3977 | 2024-02-21 | Bad News Kangaroos | W   | 0.105      | -            | -                | -                | -         |     0.32 | aliStair, dexter, INS, Liazz, Vexite |
|            6 |     3983 | 2024-02-21 | Bad News Kangaroos | W   | 0.105      | -            | -                | -                | -         |     0.32 | aliStair, dexter, INS, Liazz, Vexite |
|            5 |     4038 | 2024-02-18 | Mindfreak          | W   | 0.091      | -            | -                | -                | -         |     0.18 | aliStair, dexter, INS, Liazz, Vexite |
|            4 |     4055 | 2024-02-18 | Arcade             | W   | 0.085      | -            | -                | -                | -         |     0.16 | aliStair, dexter, INS, Liazz, Vexite |
|            3 |     4059 | 2024-02-18 | MANTRA             | W   | 0.084      | -            | -                | -                | -         |     0.04 | aliStair, dexter, INS, Liazz, Vexite |
|            2 |     4060 | 2024-02-17 | Arcade             | W   | 0.082      | -            | -                | -                | -         |     0.16 | aliStair, dexter, INS, Liazz, Vexite |
|            1 |     4082 | 2024-02-16 | GR                 | W   | 0.077      | -            | -                | -                | -         |     0.15 | aliStair, dexter, INS, Liazz, Vexite |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($34,007.04)
- Divide that value by the 5th highest value among all rosters ($325,971.18)
- The final value (0.10) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-21 |      1.000 | $10,000.00     | $10,000.00      |
| 2024-06-08 |      0.830 | $3,250.00      | $2,698.55       |
| 2024-06-02 |      0.787 | $4,000.00      | $3,147.96       |
| 2024-05-12 |      0.646 | $23,500.00     | $15,184.70      |
| 2024-04-14 |      0.458 | $6,000.00      | $2,749.58       |
| 2024-02-17 |      0.082 | $2,750.00      | $226.24         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
