### Roster Details<br />
Team Name: FlyQuest<br />
Roster: aliStair, dexter, INS, Liazz, Vexite<br />
Global Rank: [32](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [2]( ../standings_asia.md)<br />
<br />
Final Rank Value:  1176.0<br />
<br />
Final Rank Value (1176.0) = Starting Rank Value (1149.5) + Head To Head Adjustments (26.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.504[<sup>1</sup>](#table2)
- Bounty Collected: 0.416[<sup>2</sup>](#table1)
- Opponent Network: 0.135[<sup>2</sup>](#table1)
- LAN Wins: 0.402[<sup>2</sup>](#table1)

The average of these factors is 0.364<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1149.5
- 400 + ( ( 0.364 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1149.5


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
|           48 |      673 | 2024-07-18 | FURIA              | L   | 1.000      | -            | -                | -                | -         |    -2.90 | aliStair, dexter, INS, Liazz, Vexite |
|           47 |      740 | 2024-07-17 | FaZe               | L   | 1.000      | -            | -                | -                | -         |    -1.51 | aliStair, dexter, INS, Liazz, Vexite |
|           46 |     1308 | 2024-06-08 | Rooster            | W   | 0.811      | 0.333        | 0.010 (0.003)    | 0.241 (0.065)    | 0 (0.000) |     3.66 | aliStair, dexter, INS, Liazz, Vexite |
|           45 |     1363 | 2024-06-08 | Mindfreak          | W   | 0.804      | 0.333        | 0.004 (0.001)    | 0.218 (0.059)    | -         |     2.09 | aliStair, dexter, INS, Liazz, Vexite |
|           44 |     1418 | 2024-06-07 | Rooster            | L   | 0.798      | -            | -                | -                | -         |   -21.89 | aliStair, dexter, INS, Liazz, Vexite |
|           43 |     1746 | 2024-05-28 | BIG                | L   | 0.734      | -            | -                | -                | -         |    -8.64 | aliStair, dexter, INS, Liazz, Vexite |
|           42 |     1767 | 2024-05-27 | Spirit             | L   | 0.728      | -            | -                | -                | -         |    -0.47 | aliStair, dexter, INS, Liazz, Vexite |
|           41 |     1894 | 2024-05-22 | Mindfreak          | W   | 0.692      | 0.333        | 0.004 (0.001)    | 0.218 (0.050)    | -         |     1.39 | aliStair, dexter, INS, Liazz, Vexite |
|           40 |     1899 | 2024-05-22 | Mindfreak          | W   | 0.691      | 0.333        | -                | 0.218 (0.050)    | -         |     1.41 | aliStair, dexter, INS, Liazz, Vexite |
|           39 |     1969 | 2024-05-20 | Canon Event        | W   | 0.679      | -            | -                | -                | -         |     0.37 | aliStair, dexter, INS, Liazz, Vexite |
|           38 |     1971 | 2024-05-20 | Canon Event        | W   | 0.678      | -            | -                | -                | -         |     0.37 | aliStair, dexter, INS, Liazz, Vexite |
|           37 |     2340 | 2024-05-08 | Liquid             | L   | 0.600      | -            | -                | -                | -         |    -1.95 | aliStair, dexter, INS, Liazz, Vexite |
|           36 |     2358 | 2024-05-07 | BetBoom            | W   | 0.593      | 0.889        | 0.248 (0.130)    | 0.513 (0.270)    | 1 (0.593) |    13.99 | aliStair, dexter, INS, Liazz, Vexite |
|           35 |     2402 | 2024-05-05 | Ninjas in Pyjamas  | W   | 0.579      | 0.889        | 0.253 (0.130)    | 0.531 (0.273)    | 1 (0.579) |    16.68 | aliStair, dexter, INS, Liazz, Vexite |
|           34 |     2418 | 2024-05-04 | PERA               | W   | 0.572      | 0.889        | 0.047 (0.024)    | 0.435 (0.221)    | 1 (0.572) |     3.57 | aliStair, dexter, INS, Liazz, Vexite |
|           33 |     2434 | 2024-05-03 | HEROIC             | L   | 0.565      | -            | -                | -                | -         |    -1.75 | aliStair, dexter, INS, Liazz, Vexite |
|           32 |     2461 | 2024-05-02 | BOSS               | W   | 0.559      | 0.889        | 0.014 (0.007)    | 0.319 (0.158)    | 1 (0.559) |     2.17 | aliStair, dexter, INS, Liazz, Vexite |
|           31 |     2483 | 2024-05-01 | Natus Vincere      | L   | 0.552      | -            | -                | -                | -         |    -0.19 | aliStair, dexter, INS, Liazz, Vexite |
|           30 |     2730 | 2024-04-20 | Bad News Kangaroos | W   | 0.478      | 0.143        | 0.016 (0.001)    | -                | -         |     1.68 | aliStair, dexter, INS, Liazz, Vexite |
|           29 |     2776 | 2024-04-19 | Rooster            | W   | 0.472      | -            | -                | -                | -         |     1.73 | aliStair, dexter, INS, Liazz, Vexite |
|           28 |     2783 | 2024-04-18 | Mindfreak          | W   | 0.471      | -            | -                | -                | -         |     1.04 | aliStair, dexter, INS, Liazz, Vexite |
|           27 |     3028 | 2024-04-10 | FaZe               | L   | 0.412      | -            | -                | -                | -         |    -0.67 | aliStair, dexter, INS, Liazz, Vexite |
|           26 |     3043 | 2024-04-09 | Nemiga             | W   | 0.410      | 0.624        | 0.314 (0.080)    | 0.704 (0.180)    | 1 (0.410) |     6.54 | aliStair, dexter, INS, Liazz, Vexite |
|           25 |     3093 | 2024-04-08 | Virtus.pro         | L   | 0.404      | -            | -                | -                | -         |    -0.61 | aliStair, dexter, INS, Liazz, Vexite |
|           24 |     3124 | 2024-04-08 | Cloud9             | W   | 0.398      | 0.624        | 0.061 (0.015)    | 0.102 (0.025)    | 1 (0.398) |     4.68 | aliStair, dexter, INS, Liazz, Vexite |
|           23 |     3265 | 2024-04-03 | Arcade             | W   | 0.365      | -            | -                | -                | -         |     0.72 | aliStair, dexter, INS, Liazz, Vexite |
|           22 |     3270 | 2024-04-03 | Arcade             | W   | 0.365      | -            | -                | -                | -         |     0.72 | aliStair, dexter, INS, Liazz, Vexite |
|           21 |     3393 | 2024-03-27 | KZG                | W   | 0.318      | -            | -                | -                | -         |     0.70 | aliStair, dexter, INS, Liazz, Vexite |
|           20 |     3398 | 2024-03-27 | KZG                | W   | 0.318      | -            | -                | -                | -         |     0.70 | aliStair, dexter, INS, Liazz, Vexite |
|           19 |     3663 | 2024-03-13 | Rooster            | W   | 0.225      | -            | -                | -                | -         |     0.81 | aliStair, dexter, INS, Liazz, Vexite |
|           18 |     3671 | 2024-03-13 | Rooster            | W   | 0.225      | -            | -                | -                | -         |     0.81 | aliStair, dexter, INS, Liazz, Vexite |
|           17 |     3840 | 2024-03-06 | DXA                | W   | 0.179      | -            | -                | -                | -         |     0.40 | aliStair, dexter, INS, Liazz, Vexite |
|           16 |     3842 | 2024-03-06 | DXA                | W   | 0.178      | -            | -                | -                | -         |     0.41 | aliStair, dexter, INS, Liazz, Vexite |
|           15 |     3990 | 2024-02-27 | Lynn Vision        | L   | 0.131      | -            | -                | -                | -         |    -2.60 | aliStair, dexter, INS, Liazz, Vexite |
|           14 |     3991 | 2024-02-27 | ATOX               | W   | 0.130      | -            | -                | -                | 1 (0.130) |     0.69 | aliStair, dexter, INS, Liazz, Vexite |
|           13 |     4012 | 2024-02-27 | JiJieHao           | W   | 0.125      | -            | -                | -                | 1 (0.125) |     0.06 | aliStair, dexter, INS, Liazz, Vexite |
|           12 |     4028 | 2024-02-25 | The MongolZ        | L   | 0.117      | -            | -                | -                | -         |    -0.04 | aliStair, dexter, INS, Liazz, Vexite |
|           11 |     4031 | 2024-02-25 | ATOX               | W   | 0.116      | -            | -                | -                | 1 (0.116) |     0.61 | aliStair, dexter, INS, Liazz, Vexite |
|           10 |     4093 | 2024-02-23 | Rooster            | W   | 0.098      | -            | -                | -                | -         |     0.35 | aliStair, dexter, INS, Liazz, Vexite |
|            9 |     4112 | 2024-02-22 | Rooster            | W   | 0.092      | -            | -                | -                | -         |     0.32 | aliStair, dexter, INS, Liazz, Vexite |
|            8 |     4116 | 2024-02-21 | Bad News Kangaroos | W   | 0.090      | -            | -                | -                | -         |     0.14 | aliStair, dexter, INS, Liazz, Vexite |
|            7 |     4139 | 2024-02-21 | Bad News Kangaroos | W   | 0.085      | -            | -                | -                | -         |     0.13 | aliStair, dexter, INS, Liazz, Vexite |
|            6 |     4143 | 2024-02-21 | Bad News Kangaroos | W   | 0.085      | -            | -                | -                | -         |     0.13 | aliStair, dexter, INS, Liazz, Vexite |
|            5 |     4198 | 2024-02-18 | Mindfreak          | W   | 0.071      | -            | -                | -                | -         |     0.16 | aliStair, dexter, INS, Liazz, Vexite |
|            4 |     4216 | 2024-02-18 | Arcade             | W   | 0.065      | -            | -                | -                | -         |     0.14 | aliStair, dexter, INS, Liazz, Vexite |
|            3 |     4220 | 2024-02-18 | MANTRA             | W   | 0.065      | -            | -                | -                | -         |     0.03 | aliStair, dexter, INS, Liazz, Vexite |
|            2 |     4221 | 2024-02-17 | Arcade             | W   | 0.063      | -            | -                | -                | -         |     0.13 | aliStair, dexter, INS, Liazz, Vexite |
|            1 |     4243 | 2024-02-16 | GR                 | W   | 0.057      | -            | -                | -                | -         |     0.12 | aliStair, dexter, INS, Liazz, Vexite |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($33,226.18)
- Divide that value by the 5th highest value among all rosters ($320,109.81)
- The final value (0.10) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-21 |      1.000 | $10,000.00     | $10,000.00      |
| 2024-06-08 |      0.811 | $3,250.00      | $2,634.31       |
| 2024-06-02 |      0.767 | $4,000.00      | $3,068.89       |
| 2024-05-12 |      0.626 | $23,500.00     | $14,720.14      |
| 2024-04-14 |      0.438 | $6,000.00      | $2,630.97       |
| 2024-02-17 |      0.063 | $2,750.00      | $171.88         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
