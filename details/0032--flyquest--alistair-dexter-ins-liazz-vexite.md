### Roster Details<br />
Team Name: FlyQuest<br />
Roster: aliStair, dexter, INS, Liazz, Vexite<br />
Global Rank: [32](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [2]( ../standings_asia.md)<br />
<br />
Final Rank Value:  1178.0<br />
<br />
Final Rank Value (1178.0) = Starting Rank Value (1151.7) + Head To Head Adjustments (26.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.504[<sup>1</sup>](#table2)
- Bounty Collected: 0.417[<sup>2</sup>](#table1)
- Opponent Network: 0.140[<sup>2</sup>](#table1)
- LAN Wins: 0.405[<sup>2</sup>](#table1)

The average of these factors is 0.366<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1151.7
- 400 + ( ( 0.366 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 1151.7


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
|           48 |      652 | 2024-07-18 | FURIA              | L   | 1.000      | -            | -                | -                | -         |    -2.92 | aliStair, dexter, INS, Liazz, Vexite |
|           47 |      719 | 2024-07-17 | FaZe               | L   | 1.000      | -            | -                | -                | -         |    -1.51 | aliStair, dexter, INS, Liazz, Vexite |
|           46 |     1287 | 2024-06-08 | Rooster            | W   | 0.815      | 0.333        | 0.010 (0.003)    | 0.246 (0.067)    | 0 (0.000) |     3.65 | aliStair, dexter, INS, Liazz, Vexite |
|           45 |     1342 | 2024-06-08 | Mindfreak          | W   | 0.809      | 0.333        | 0.004 (0.001)    | 0.223 (0.060)    | -         |     2.08 | aliStair, dexter, INS, Liazz, Vexite |
|           44 |     1397 | 2024-06-07 | Rooster            | L   | 0.802      | -            | -                | -                | -         |   -22.03 | aliStair, dexter, INS, Liazz, Vexite |
|           43 |     1725 | 2024-05-28 | BIG                | L   | 0.739      | -            | -                | -                | -         |    -8.74 | aliStair, dexter, INS, Liazz, Vexite |
|           42 |     1746 | 2024-05-27 | Spirit             | L   | 0.732      | -            | -                | -                | -         |    -0.47 | aliStair, dexter, INS, Liazz, Vexite |
|           41 |     1873 | 2024-05-22 | Mindfreak          | W   | 0.696      | 0.333        | 0.004 (0.001)    | 0.223 (0.052)    | -         |     1.39 | aliStair, dexter, INS, Liazz, Vexite |
|           40 |     1878 | 2024-05-22 | Mindfreak          | W   | 0.696      | 0.333        | -                | 0.223 (0.052)    | -         |     1.41 | aliStair, dexter, INS, Liazz, Vexite |
|           39 |     1948 | 2024-05-20 | Canon Event        | W   | 0.683      | -            | -                | -                | -         |     0.36 | aliStair, dexter, INS, Liazz, Vexite |
|           38 |     1950 | 2024-05-20 | Canon Event        | W   | 0.683      | -            | -                | -                | -         |     0.37 | aliStair, dexter, INS, Liazz, Vexite |
|           37 |     2319 | 2024-05-08 | Liquid             | L   | 0.604      | -            | -                | -                | -         |    -1.98 | aliStair, dexter, INS, Liazz, Vexite |
|           36 |     2337 | 2024-05-07 | BetBoom            | W   | 0.597      | 0.889        | 0.249 (0.132)    | 0.527 (0.280)    | 1 (0.597) |    14.07 | aliStair, dexter, INS, Liazz, Vexite |
|           35 |     2381 | 2024-05-05 | Ninjas in Pyjamas  | W   | 0.583      | 0.889        | 0.254 (0.131)    | 0.544 (0.282)    | 1 (0.583) |    16.80 | aliStair, dexter, INS, Liazz, Vexite |
|           34 |     2397 | 2024-05-04 | PERA               | W   | 0.576      | 0.889        | 0.048 (0.024)    | 0.445 (0.228)    | 1 (0.576) |     3.57 | aliStair, dexter, INS, Liazz, Vexite |
|           33 |     2413 | 2024-05-03 | HEROIC             | L   | 0.570      | -            | -                | -                | -         |    -1.77 | aliStair, dexter, INS, Liazz, Vexite |
|           32 |     2440 | 2024-05-02 | BOSS               | W   | 0.563      | 0.889        | 0.014 (0.007)    | 0.326 (0.163)    | 1 (0.563) |     2.17 | aliStair, dexter, INS, Liazz, Vexite |
|           31 |     2462 | 2024-05-01 | Natus Vincere      | L   | 0.556      | -            | -                | -                | -         |    -0.19 | aliStair, dexter, INS, Liazz, Vexite |
|           30 |     2709 | 2024-04-20 | Bad News Kangaroos | W   | 0.483      | 0.143        | 0.016 (0.001)    | -                | -         |     1.68 | aliStair, dexter, INS, Liazz, Vexite |
|           29 |     2755 | 2024-04-19 | Rooster            | W   | 0.476      | -            | -                | -                | -         |     1.73 | aliStair, dexter, INS, Liazz, Vexite |
|           28 |     2762 | 2024-04-18 | Mindfreak          | W   | 0.475      | -            | -                | -                | -         |     1.04 | aliStair, dexter, INS, Liazz, Vexite |
|           27 |     3007 | 2024-04-10 | FaZe               | L   | 0.416      | -            | -                | -                | -         |    -0.67 | aliStair, dexter, INS, Liazz, Vexite |
|           26 |     3022 | 2024-04-09 | Nemiga             | W   | 0.415      | 0.624        | 0.315 (0.082)    | 0.721 (0.187)    | 1 (0.415) |     6.58 | aliStair, dexter, INS, Liazz, Vexite |
|           25 |     3072 | 2024-04-08 | Virtus.pro         | L   | 0.408      | -            | -                | -                | -         |    -0.62 | aliStair, dexter, INS, Liazz, Vexite |
|           24 |     3103 | 2024-04-08 | Cloud9             | W   | 0.402      | 0.624        | 0.061 (0.015)    | 0.106 (0.027)    | 1 (0.402) |     4.74 | aliStair, dexter, INS, Liazz, Vexite |
|           23 |     3244 | 2024-04-03 | Arcade             | W   | 0.369      | -            | -                | -                | -         |     0.72 | aliStair, dexter, INS, Liazz, Vexite |
|           22 |     3249 | 2024-04-03 | Arcade             | W   | 0.369      | -            | -                | -                | -         |     0.72 | aliStair, dexter, INS, Liazz, Vexite |
|           21 |     3372 | 2024-03-27 | KZG                | W   | 0.323      | -            | -                | -                | -         |     0.70 | aliStair, dexter, INS, Liazz, Vexite |
|           20 |     3377 | 2024-03-27 | KZG                | W   | 0.323      | -            | -                | -                | -         |     0.70 | aliStair, dexter, INS, Liazz, Vexite |
|           19 |     3642 | 2024-03-13 | Rooster            | W   | 0.229      | -            | -                | -                | -         |     0.81 | aliStair, dexter, INS, Liazz, Vexite |
|           18 |     3650 | 2024-03-13 | Rooster            | W   | 0.229      | -            | -                | -                | -         |     0.82 | aliStair, dexter, INS, Liazz, Vexite |
|           17 |     3819 | 2024-03-06 | DXA                | W   | 0.183      | -            | -                | -                | -         |     0.41 | aliStair, dexter, INS, Liazz, Vexite |
|           16 |     3821 | 2024-03-06 | DXA                | W   | 0.182      | -            | -                | -                | -         |     0.41 | aliStair, dexter, INS, Liazz, Vexite |
|           15 |     3969 | 2024-02-27 | Lynn Vision        | L   | 0.135      | -            | -                | -                | -         |    -2.75 | aliStair, dexter, INS, Liazz, Vexite |
|           14 |     3970 | 2024-02-27 | ATOX               | W   | 0.134      | -            | -                | -                | 1 (0.134) |     0.70 | aliStair, dexter, INS, Liazz, Vexite |
|           13 |     3991 | 2024-02-27 | JiJieHao           | W   | 0.129      | -            | -                | -                | 1 (0.129) |     0.06 | aliStair, dexter, INS, Liazz, Vexite |
|           12 |     4007 | 2024-02-25 | The MongolZ        | L   | 0.121      | -            | -                | -                | -         |    -0.04 | aliStair, dexter, INS, Liazz, Vexite |
|           11 |     4010 | 2024-02-25 | ATOX               | W   | 0.121      | -            | -                | -                | 1 (0.121) |     0.63 | aliStair, dexter, INS, Liazz, Vexite |
|           10 |     4072 | 2024-02-23 | Rooster            | W   | 0.102      | -            | -                | -                | -         |     0.36 | aliStair, dexter, INS, Liazz, Vexite |
|            9 |     4091 | 2024-02-22 | Rooster            | W   | 0.096      | -            | -                | -                | -         |     0.34 | aliStair, dexter, INS, Liazz, Vexite |
|            8 |     4095 | 2024-02-21 | Bad News Kangaroos | W   | 0.095      | -            | -                | -                | -         |     0.14 | aliStair, dexter, INS, Liazz, Vexite |
|            7 |     4118 | 2024-02-21 | Bad News Kangaroos | W   | 0.089      | -            | -                | -                | -         |     0.14 | aliStair, dexter, INS, Liazz, Vexite |
|            6 |     4122 | 2024-02-21 | Bad News Kangaroos | W   | 0.089      | -            | -                | -                | -         |     0.14 | aliStair, dexter, INS, Liazz, Vexite |
|            5 |     4177 | 2024-02-18 | Mindfreak          | W   | 0.075      | -            | -                | -                | -         |     0.17 | aliStair, dexter, INS, Liazz, Vexite |
|            4 |     4195 | 2024-02-18 | Arcade             | W   | 0.069      | -            | -                | -                | -         |     0.14 | aliStair, dexter, INS, Liazz, Vexite |
|            3 |     4199 | 2024-02-18 | MANTRA             | W   | 0.069      | -            | -                | -                | -         |     0.03 | aliStair, dexter, INS, Liazz, Vexite |
|            2 |     4200 | 2024-02-17 | Arcade             | W   | 0.067      | -            | -                | -                | -         |     0.14 | aliStair, dexter, INS, Liazz, Vexite |
|            1 |     4222 | 2024-02-16 | GR                 | W   | 0.061      | -            | -                | -                | -         |     0.12 | aliStair, dexter, INS, Liazz, Vexite |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($33,390.76)
- Divide that value by the 5th highest value among all rosters ($321,345.23)
- The final value (0.10) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-21 |      1.000 | $10,000.00     | $10,000.00      |
| 2024-06-08 |      0.815 | $3,250.00      | $2,647.85       |
| 2024-06-02 |      0.771 | $4,000.00      | $3,085.56       |
| 2024-05-12 |      0.631 | $23,500.00     | $14,818.06      |
| 2024-04-14 |      0.443 | $6,000.00      | $2,655.97       |
| 2024-02-17 |      0.067 | $2,750.00      | $183.33         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
