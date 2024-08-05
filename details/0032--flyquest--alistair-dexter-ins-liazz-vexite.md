### Roster Details<br />
Team Name: FlyQuest<br />
Roster: aliStair, dexter, INS, Liazz, Vexite<br />
Global Rank: [32](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [2]( ../standings_asia.md)<br />
<br />
Final Rank Value:  1179.1<br />
<br />
Final Rank Value (1179.1) = Starting Rank Value (1152.9) + Head To Head Adjustments (26.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.504[<sup>1</sup>](#table2)
- Bounty Collected: 0.417[<sup>2</sup>](#table1)
- Opponent Network: 0.140[<sup>2</sup>](#table1)
- LAN Wins: 0.407[<sup>2</sup>](#table1)

The average of these factors is 0.367<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1152.9
- 400 + ( ( 0.367 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 1152.9


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
|           48 |      649 | 2024-07-18 | FURIA              | L   | 1.000      | -            | -                | -                | -         |    -2.94 | aliStair, dexter, INS, Liazz, Vexite |
|           47 |      716 | 2024-07-17 | FaZe               | L   | 1.000      | -            | -                | -                | -         |    -1.50 | aliStair, dexter, INS, Liazz, Vexite |
|           46 |     1284 | 2024-06-08 | Rooster            | W   | 0.817      | 0.333        | 0.010 (0.003)    | 0.247 (0.067)    | 0 (0.000) |     3.65 | aliStair, dexter, INS, Liazz, Vexite |
|           45 |     1339 | 2024-06-08 | Mindfreak          | W   | 0.811      | 0.333        | 0.004 (0.001)    | 0.224 (0.060)    | -         |     2.07 | aliStair, dexter, INS, Liazz, Vexite |
|           44 |     1394 | 2024-06-07 | Rooster            | L   | 0.804      | -            | -                | -                | -         |   -22.11 | aliStair, dexter, INS, Liazz, Vexite |
|           43 |     1722 | 2024-05-28 | BIG                | L   | 0.741      | -            | -                | -                | -         |    -8.79 | aliStair, dexter, INS, Liazz, Vexite |
|           42 |     1743 | 2024-05-27 | Spirit             | L   | 0.734      | -            | -                | -                | -         |    -0.48 | aliStair, dexter, INS, Liazz, Vexite |
|           41 |     1870 | 2024-05-22 | Mindfreak          | W   | 0.698      | 0.333        | 0.004 (0.001)    | 0.224 (0.052)    | -         |     1.38 | aliStair, dexter, INS, Liazz, Vexite |
|           40 |     1875 | 2024-05-22 | Mindfreak          | W   | 0.698      | 0.333        | -                | 0.224 (0.052)    | -         |     1.40 | aliStair, dexter, INS, Liazz, Vexite |
|           39 |     1945 | 2024-05-20 | Canon Event        | W   | 0.685      | -            | -                | -                | -         |     0.36 | aliStair, dexter, INS, Liazz, Vexite |
|           38 |     1947 | 2024-05-20 | Canon Event        | W   | 0.685      | -            | -                | -                | -         |     0.36 | aliStair, dexter, INS, Liazz, Vexite |
|           37 |     2316 | 2024-05-08 | Liquid             | L   | 0.606      | -            | -                | -                | -         |    -2.00 | aliStair, dexter, INS, Liazz, Vexite |
|           36 |     2334 | 2024-05-07 | BetBoom            | W   | 0.599      | 0.889        | 0.249 (0.133)    | 0.529 (0.282)    | 1 (0.599) |    14.11 | aliStair, dexter, INS, Liazz, Vexite |
|           35 |     2378 | 2024-05-05 | Ninjas in Pyjamas  | W   | 0.585      | 0.889        | 0.254 (0.132)    | 0.544 (0.283)    | 1 (0.585) |    16.85 | aliStair, dexter, INS, Liazz, Vexite |
|           34 |     2394 | 2024-05-04 | PERA               | W   | 0.578      | 0.889        | 0.048 (0.024)    | 0.446 (0.229)    | 1 (0.578) |     3.56 | aliStair, dexter, INS, Liazz, Vexite |
|           33 |     2410 | 2024-05-03 | HEROIC             | L   | 0.572      | -            | -                | -                | -         |    -1.78 | aliStair, dexter, INS, Liazz, Vexite |
|           32 |     2437 | 2024-05-02 | BOSS               | W   | 0.565      | 0.889        | 0.014 (0.007)    | 0.327 (0.164)    | 1 (0.565) |     2.15 | aliStair, dexter, INS, Liazz, Vexite |
|           31 |     2459 | 2024-05-01 | Natus Vincere      | L   | 0.558      | -            | -                | -                | -         |    -0.19 | aliStair, dexter, INS, Liazz, Vexite |
|           30 |     2706 | 2024-04-20 | Bad News Kangaroos | W   | 0.485      | 0.143        | 0.017 (0.001)    | -                | -         |     1.68 | aliStair, dexter, INS, Liazz, Vexite |
|           29 |     2752 | 2024-04-19 | Rooster            | W   | 0.478      | -            | -                | -                | -         |     1.73 | aliStair, dexter, INS, Liazz, Vexite |
|           28 |     2759 | 2024-04-18 | Mindfreak          | W   | 0.477      | -            | -                | -                | -         |     1.04 | aliStair, dexter, INS, Liazz, Vexite |
|           27 |     3004 | 2024-04-10 | FaZe               | L   | 0.418      | -            | -                | -                | -         |    -0.67 | aliStair, dexter, INS, Liazz, Vexite |
|           26 |     3019 | 2024-04-09 | Nemiga             | W   | 0.417      | 0.624        | 0.316 (0.082)    | 0.722 (0.188)    | 1 (0.417) |     6.61 | aliStair, dexter, INS, Liazz, Vexite |
|           25 |     3069 | 2024-04-08 | Virtus.pro         | L   | 0.410      | -            | -                | -                | -         |    -0.62 | aliStair, dexter, INS, Liazz, Vexite |
|           24 |     3100 | 2024-04-08 | Cloud9             | W   | 0.404      | 0.624        | 0.061 (0.015)    | 0.107 (0.027)    | 1 (0.404) |     4.78 | aliStair, dexter, INS, Liazz, Vexite |
|           23 |     3241 | 2024-04-03 | Arcade             | W   | 0.371      | -            | -                | -                | -         |     0.72 | aliStair, dexter, INS, Liazz, Vexite |
|           22 |     3246 | 2024-04-03 | Arcade             | W   | 0.371      | -            | -                | -                | -         |     0.72 | aliStair, dexter, INS, Liazz, Vexite |
|           21 |     3369 | 2024-03-27 | KZG                | W   | 0.325      | -            | -                | -                | -         |     0.70 | aliStair, dexter, INS, Liazz, Vexite |
|           20 |     3374 | 2024-03-27 | KZG                | W   | 0.325      | -            | -                | -                | -         |     0.70 | aliStair, dexter, INS, Liazz, Vexite |
|           19 |     3639 | 2024-03-13 | Rooster            | W   | 0.232      | -            | -                | -                | -         |     0.82 | aliStair, dexter, INS, Liazz, Vexite |
|           18 |     3647 | 2024-03-13 | Rooster            | W   | 0.231      | -            | -                | -                | -         |     0.82 | aliStair, dexter, INS, Liazz, Vexite |
|           17 |     3816 | 2024-03-06 | DXA                | W   | 0.185      | -            | -                | -                | -         |     0.41 | aliStair, dexter, INS, Liazz, Vexite |
|           16 |     3818 | 2024-03-06 | DXA                | W   | 0.185      | -            | -                | -                | -         |     0.41 | aliStair, dexter, INS, Liazz, Vexite |
|           15 |     3966 | 2024-02-27 | Lynn Vision        | L   | 0.137      | -            | -                | -                | -         |    -2.79 | aliStair, dexter, INS, Liazz, Vexite |
|           14 |     3967 | 2024-02-27 | ATOX               | W   | 0.136      | -            | -                | -                | 1 (0.136) |     0.71 | aliStair, dexter, INS, Liazz, Vexite |
|           13 |     3988 | 2024-02-27 | JiJieHao           | W   | 0.131      | -            | -                | -                | 1 (0.131) |     0.06 | aliStair, dexter, INS, Liazz, Vexite |
|           12 |     4004 | 2024-02-25 | The MongolZ        | L   | 0.124      | -            | -                | -                | -         |    -0.04 | aliStair, dexter, INS, Liazz, Vexite |
|           11 |     4007 | 2024-02-25 | ATOX               | W   | 0.123      | -            | -                | -                | 1 (0.123) |     0.64 | aliStair, dexter, INS, Liazz, Vexite |
|           10 |     4069 | 2024-02-23 | Rooster            | W   | 0.105      | -            | -                | -                | -         |     0.36 | aliStair, dexter, INS, Liazz, Vexite |
|            9 |     4088 | 2024-02-22 | Rooster            | W   | 0.098      | -            | -                | -                | -         |     0.34 | aliStair, dexter, INS, Liazz, Vexite |
|            8 |     4092 | 2024-02-21 | Bad News Kangaroos | W   | 0.097      | -            | -                | -                | -         |     0.15 | aliStair, dexter, INS, Liazz, Vexite |
|            7 |     4115 | 2024-02-21 | Bad News Kangaroos | W   | 0.092      | -            | -                | -                | -         |     0.14 | aliStair, dexter, INS, Liazz, Vexite |
|            6 |     4119 | 2024-02-21 | Bad News Kangaroos | W   | 0.091      | -            | -                | -                | -         |     0.14 | aliStair, dexter, INS, Liazz, Vexite |
|            5 |     4174 | 2024-02-18 | Mindfreak          | W   | 0.077      | -            | -                | -                | -         |     0.17 | aliStair, dexter, INS, Liazz, Vexite |
|            4 |     4192 | 2024-02-18 | Arcade             | W   | 0.071      | -            | -                | -                | -         |     0.15 | aliStair, dexter, INS, Liazz, Vexite |
|            3 |     4196 | 2024-02-18 | MANTRA             | W   | 0.071      | -            | -                | -                | -         |     0.03 | aliStair, dexter, INS, Liazz, Vexite |
|            2 |     4197 | 2024-02-17 | Arcade             | W   | 0.069      | -            | -                | -                | -         |     0.14 | aliStair, dexter, INS, Liazz, Vexite |
|            1 |     4219 | 2024-02-16 | GR                 | W   | 0.063      | -            | -                | -                | -         |     0.13 | aliStair, dexter, INS, Liazz, Vexite |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($33,478.54)
- Divide that value by the 5th highest value among all rosters ($322,004.12)
- The final value (0.10) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-21 |      1.000 | $10,000.00     | $10,000.00      |
| 2024-06-08 |      0.817 | $3,250.00      | $2,655.07       |
| 2024-06-02 |      0.774 | $4,000.00      | $3,094.44       |
| 2024-05-12 |      0.633 | $23,500.00     | $14,870.28      |
| 2024-04-14 |      0.445 | $6,000.00      | $2,669.31       |
| 2024-02-17 |      0.069 | $2,750.00      | $189.44         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
