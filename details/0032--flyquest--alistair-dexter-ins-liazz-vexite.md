### Roster Details<br />
Team Name: FlyQuest<br />
Roster: aliStair, dexter, INS, Liazz, Vexite<br />
Global Rank: [32](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [2]( ../standings_asia.md)<br />
<br />
Final Rank Value:  1178.9<br />
<br />
Final Rank Value (1178.9) = Starting Rank Value (1152.6) + Head To Head Adjustments (26.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.504[<sup>1</sup>](#table2)
- Bounty Collected: 0.417[<sup>2</sup>](#table1)
- Opponent Network: 0.140[<sup>2</sup>](#table1)
- LAN Wins: 0.407[<sup>2</sup>](#table1)

The average of these factors is 0.367<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1152.6
- 400 + ( ( 0.367 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 1152.6


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
|           48 |      650 | 2024-07-18 | FURIA              | L   | 1.000      | -            | -                | -                | -         |    -2.94 | aliStair, dexter, INS, Liazz, Vexite |
|           47 |      717 | 2024-07-17 | FaZe               | L   | 1.000      | -            | -                | -                | -         |    -1.50 | aliStair, dexter, INS, Liazz, Vexite |
|           46 |     1285 | 2024-06-08 | Rooster            | W   | 0.817      | 0.333        | 0.010 (0.003)    | 0.247 (0.067)    | 0 (0.000) |     3.65 | aliStair, dexter, INS, Liazz, Vexite |
|           45 |     1340 | 2024-06-08 | Mindfreak          | W   | 0.810      | 0.333        | 0.004 (0.001)    | 0.224 (0.060)    | -         |     2.07 | aliStair, dexter, INS, Liazz, Vexite |
|           44 |     1395 | 2024-06-07 | Rooster            | L   | 0.804      | -            | -                | -                | -         |   -22.09 | aliStair, dexter, INS, Liazz, Vexite |
|           43 |     1723 | 2024-05-28 | BIG                | L   | 0.740      | -            | -                | -                | -         |    -8.78 | aliStair, dexter, INS, Liazz, Vexite |
|           42 |     1744 | 2024-05-27 | Spirit             | L   | 0.734      | -            | -                | -                | -         |    -0.48 | aliStair, dexter, INS, Liazz, Vexite |
|           41 |     1871 | 2024-05-22 | Mindfreak          | W   | 0.698      | 0.333        | 0.004 (0.001)    | 0.224 (0.052)    | -         |     1.38 | aliStair, dexter, INS, Liazz, Vexite |
|           40 |     1876 | 2024-05-22 | Mindfreak          | W   | 0.697      | 0.333        | -                | 0.224 (0.052)    | -         |     1.40 | aliStair, dexter, INS, Liazz, Vexite |
|           39 |     1946 | 2024-05-20 | Canon Event        | W   | 0.685      | -            | -                | -                | -         |     0.36 | aliStair, dexter, INS, Liazz, Vexite |
|           38 |     1948 | 2024-05-20 | Canon Event        | W   | 0.684      | -            | -                | -                | -         |     0.36 | aliStair, dexter, INS, Liazz, Vexite |
|           37 |     2317 | 2024-05-08 | Liquid             | L   | 0.605      | -            | -                | -                | -         |    -2.00 | aliStair, dexter, INS, Liazz, Vexite |
|           36 |     2335 | 2024-05-07 | BetBoom            | W   | 0.599      | 0.889        | 0.249 (0.133)    | 0.529 (0.281)    | 1 (0.599) |    14.10 | aliStair, dexter, INS, Liazz, Vexite |
|           35 |     2379 | 2024-05-05 | Ninjas in Pyjamas  | W   | 0.585      | 0.889        | 0.254 (0.132)    | 0.544 (0.283)    | 1 (0.585) |    16.84 | aliStair, dexter, INS, Liazz, Vexite |
|           34 |     2395 | 2024-05-04 | PERA               | W   | 0.578      | 0.889        | 0.048 (0.024)    | 0.446 (0.229)    | 1 (0.578) |     3.56 | aliStair, dexter, INS, Liazz, Vexite |
|           33 |     2411 | 2024-05-03 | HEROIC             | L   | 0.571      | -            | -                | -                | -         |    -1.77 | aliStair, dexter, INS, Liazz, Vexite |
|           32 |     2438 | 2024-05-02 | BOSS               | W   | 0.565      | 0.889        | 0.014 (0.007)    | 0.327 (0.164)    | 1 (0.565) |     2.15 | aliStair, dexter, INS, Liazz, Vexite |
|           31 |     2460 | 2024-05-01 | Natus Vincere      | L   | 0.558      | -            | -                | -                | -         |    -0.19 | aliStair, dexter, INS, Liazz, Vexite |
|           30 |     2707 | 2024-04-20 | Bad News Kangaroos | W   | 0.484      | 0.143        | 0.017 (0.001)    | -                | -         |     1.68 | aliStair, dexter, INS, Liazz, Vexite |
|           29 |     2753 | 2024-04-19 | Rooster            | W   | 0.478      | -            | -                | -                | -         |     1.73 | aliStair, dexter, INS, Liazz, Vexite |
|           28 |     2760 | 2024-04-18 | Mindfreak          | W   | 0.477      | -            | -                | -                | -         |     1.04 | aliStair, dexter, INS, Liazz, Vexite |
|           27 |     3005 | 2024-04-10 | FaZe               | L   | 0.418      | -            | -                | -                | -         |    -0.67 | aliStair, dexter, INS, Liazz, Vexite |
|           26 |     3020 | 2024-04-09 | Nemiga             | W   | 0.416      | 0.624        | 0.316 (0.082)    | 0.722 (0.188)    | 1 (0.416) |     6.60 | aliStair, dexter, INS, Liazz, Vexite |
|           25 |     3070 | 2024-04-08 | Virtus.pro         | L   | 0.410      | -            | -                | -                | -         |    -0.62 | aliStair, dexter, INS, Liazz, Vexite |
|           24 |     3101 | 2024-04-08 | Cloud9             | W   | 0.403      | 0.624        | 0.061 (0.015)    | 0.107 (0.027)    | 1 (0.403) |     4.77 | aliStair, dexter, INS, Liazz, Vexite |
|           23 |     3242 | 2024-04-03 | Arcade             | W   | 0.371      | -            | -                | -                | -         |     0.72 | aliStair, dexter, INS, Liazz, Vexite |
|           22 |     3247 | 2024-04-03 | Arcade             | W   | 0.371      | -            | -                | -                | -         |     0.72 | aliStair, dexter, INS, Liazz, Vexite |
|           21 |     3370 | 2024-03-27 | KZG                | W   | 0.324      | -            | -                | -                | -         |     0.70 | aliStair, dexter, INS, Liazz, Vexite |
|           20 |     3375 | 2024-03-27 | KZG                | W   | 0.324      | -            | -                | -                | -         |     0.70 | aliStair, dexter, INS, Liazz, Vexite |
|           19 |     3640 | 2024-03-13 | Rooster            | W   | 0.231      | -            | -                | -                | -         |     0.82 | aliStair, dexter, INS, Liazz, Vexite |
|           18 |     3648 | 2024-03-13 | Rooster            | W   | 0.231      | -            | -                | -                | -         |     0.82 | aliStair, dexter, INS, Liazz, Vexite |
|           17 |     3817 | 2024-03-06 | DXA                | W   | 0.185      | -            | -                | -                | -         |     0.41 | aliStair, dexter, INS, Liazz, Vexite |
|           16 |     3819 | 2024-03-06 | DXA                | W   | 0.184      | -            | -                | -                | -         |     0.41 | aliStair, dexter, INS, Liazz, Vexite |
|           15 |     3967 | 2024-02-27 | Lynn Vision        | L   | 0.137      | -            | -                | -                | -         |    -2.79 | aliStair, dexter, INS, Liazz, Vexite |
|           14 |     3968 | 2024-02-27 | ATOX               | W   | 0.136      | -            | -                | -                | 1 (0.136) |     0.71 | aliStair, dexter, INS, Liazz, Vexite |
|           13 |     3989 | 2024-02-27 | JiJieHao           | W   | 0.131      | -            | -                | -                | 1 (0.131) |     0.06 | aliStair, dexter, INS, Liazz, Vexite |
|           12 |     4005 | 2024-02-25 | The MongolZ        | L   | 0.123      | -            | -                | -                | -         |    -0.04 | aliStair, dexter, INS, Liazz, Vexite |
|           11 |     4008 | 2024-02-25 | ATOX               | W   | 0.122      | -            | -                | -                | 1 (0.122) |     0.64 | aliStair, dexter, INS, Liazz, Vexite |
|           10 |     4070 | 2024-02-23 | Rooster            | W   | 0.104      | -            | -                | -                | -         |     0.36 | aliStair, dexter, INS, Liazz, Vexite |
|            9 |     4089 | 2024-02-22 | Rooster            | W   | 0.098      | -            | -                | -                | -         |     0.34 | aliStair, dexter, INS, Liazz, Vexite |
|            8 |     4093 | 2024-02-21 | Bad News Kangaroos | W   | 0.096      | -            | -                | -                | -         |     0.15 | aliStair, dexter, INS, Liazz, Vexite |
|            7 |     4116 | 2024-02-21 | Bad News Kangaroos | W   | 0.091      | -            | -                | -                | -         |     0.14 | aliStair, dexter, INS, Liazz, Vexite |
|            6 |     4120 | 2024-02-21 | Bad News Kangaroos | W   | 0.091      | -            | -                | -                | -         |     0.14 | aliStair, dexter, INS, Liazz, Vexite |
|            5 |     4175 | 2024-02-18 | Mindfreak          | W   | 0.077      | -            | -                | -                | -         |     0.17 | aliStair, dexter, INS, Liazz, Vexite |
|            4 |     4193 | 2024-02-18 | Arcade             | W   | 0.071      | -            | -                | -                | -         |     0.15 | aliStair, dexter, INS, Liazz, Vexite |
|            3 |     4197 | 2024-02-18 | MANTRA             | W   | 0.071      | -            | -                | -                | -         |     0.03 | aliStair, dexter, INS, Liazz, Vexite |
|            2 |     4198 | 2024-02-17 | Arcade             | W   | 0.068      | -            | -                | -                | -         |     0.14 | aliStair, dexter, INS, Liazz, Vexite |
|            1 |     4220 | 2024-02-16 | GR                 | W   | 0.063      | -            | -                | -                | -         |     0.13 | aliStair, dexter, INS, Liazz, Vexite |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($33,462.08)
- Divide that value by the 5th highest value among all rosters ($321,880.58)
- The final value (0.10) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-21 |      1.000 | $10,000.00     | $10,000.00      |
| 2024-06-08 |      0.817 | $3,250.00      | $2,653.72       |
| 2024-06-02 |      0.773 | $4,000.00      | $3,092.78       |
| 2024-05-12 |      0.632 | $23,500.00     | $14,860.49      |
| 2024-04-14 |      0.444 | $6,000.00      | $2,666.81       |
| 2024-02-17 |      0.068 | $2,750.00      | $188.30         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
