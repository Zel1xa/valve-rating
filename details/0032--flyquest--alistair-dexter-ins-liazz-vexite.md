### Roster Details<br />
Team Name: FlyQuest<br />
Roster: aliStair, dexter, INS, Liazz, Vexite<br />
Global Rank: [32](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [2]( ../standings_asia.md)<br />
<br />
Final Rank Value:  1179.6<br />
<br />
Final Rank Value (1179.6) = Starting Rank Value (1153.4) + Head To Head Adjustments (26.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.504[<sup>1</sup>](#table2)
- Bounty Collected: 0.417[<sup>2</sup>](#table1)
- Opponent Network: 0.143[<sup>2</sup>](#table1)
- LAN Wins: 0.408[<sup>2</sup>](#table1)

The average of these factors is 0.368<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1153.4
- 400 + ( ( 0.368 - 0.000 ) / ( 0.781 - 0.000 ) ) * 1600 = 1153.4


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
|           48 |      641 | 2024-07-18 | FURIA              | L   | 1.000      | -            | -                | -                | -         |    -2.95 | aliStair, dexter, INS, Liazz, Vexite |
|           47 |      708 | 2024-07-17 | FaZe               | L   | 1.000      | -            | -                | -                | -         |    -1.50 | aliStair, dexter, INS, Liazz, Vexite |
|           46 |     1276 | 2024-06-08 | Rooster            | W   | 0.818      | 0.333        | 0.010 (0.003)    | 0.250 (0.068)    | 0 (0.000) |     3.64 | aliStair, dexter, INS, Liazz, Vexite |
|           45 |     1331 | 2024-06-08 | Mindfreak          | W   | 0.812      | 0.333        | 0.004 (0.001)    | 0.226 (0.061)    | -         |     2.07 | aliStair, dexter, INS, Liazz, Vexite |
|           44 |     1386 | 2024-06-07 | Rooster            | L   | 0.805      | -            | -                | -                | -         |   -22.14 | aliStair, dexter, INS, Liazz, Vexite |
|           43 |     1714 | 2024-05-28 | BIG                | L   | 0.742      | -            | -                | -                | -         |    -8.82 | aliStair, dexter, INS, Liazz, Vexite |
|           42 |     1735 | 2024-05-27 | Spirit             | L   | 0.736      | -            | -                | -                | -         |    -0.48 | aliStair, dexter, INS, Liazz, Vexite |
|           41 |     1862 | 2024-05-22 | Mindfreak          | W   | 0.699      | 0.333        | 0.004 (0.001)    | 0.226 (0.053)    | -         |     1.38 | aliStair, dexter, INS, Liazz, Vexite |
|           40 |     1867 | 2024-05-22 | Mindfreak          | W   | 0.699      | 0.333        | -                | 0.226 (0.053)    | -         |     1.40 | aliStair, dexter, INS, Liazz, Vexite |
|           39 |     1937 | 2024-05-20 | Canon Event        | W   | 0.686      | -            | -                | -                | -         |     0.36 | aliStair, dexter, INS, Liazz, Vexite |
|           38 |     1939 | 2024-05-20 | Canon Event        | W   | 0.686      | -            | -                | -                | -         |     0.36 | aliStair, dexter, INS, Liazz, Vexite |
|           37 |     2308 | 2024-05-08 | Liquid             | L   | 0.607      | -            | -                | -                | -         |    -2.01 | aliStair, dexter, INS, Liazz, Vexite |
|           36 |     2326 | 2024-05-07 | BetBoom            | W   | 0.600      | 0.889        | 0.249 (0.133)    | 0.536 (0.286)    | 1 (0.600) |    14.13 | aliStair, dexter, INS, Liazz, Vexite |
|           35 |     2370 | 2024-05-05 | Ninjas in Pyjamas  | W   | 0.586      | 0.889        | 0.254 (0.132)    | 0.551 (0.287)    | 1 (0.586) |    16.88 | aliStair, dexter, INS, Liazz, Vexite |
|           34 |     2386 | 2024-05-04 | PERA               | W   | 0.580      | 0.889        | 0.048 (0.025)    | 0.451 (0.232)    | 1 (0.580) |     3.57 | aliStair, dexter, INS, Liazz, Vexite |
|           33 |     2402 | 2024-05-03 | HEROIC             | L   | 0.573      | -            | -                | -                | -         |    -1.78 | aliStair, dexter, INS, Liazz, Vexite |
|           32 |     2429 | 2024-05-02 | BOSS               | W   | 0.566      | 0.889        | 0.014 (0.007)    | 0.331 (0.167)    | 1 (0.566) |     2.15 | aliStair, dexter, INS, Liazz, Vexite |
|           31 |     2451 | 2024-05-01 | Natus Vincere      | L   | 0.560      | -            | -                | -                | -         |    -0.20 | aliStair, dexter, INS, Liazz, Vexite |
|           30 |     2698 | 2024-04-20 | Bad News Kangaroos | W   | 0.486      | 0.143        | 0.017 (0.001)    | -                | -         |     1.68 | aliStair, dexter, INS, Liazz, Vexite |
|           29 |     2744 | 2024-04-19 | Rooster            | W   | 0.479      | -            | -                | -                | -         |     1.73 | aliStair, dexter, INS, Liazz, Vexite |
|           28 |     2751 | 2024-04-18 | Mindfreak          | W   | 0.478      | -            | -                | -                | -         |     1.04 | aliStair, dexter, INS, Liazz, Vexite |
|           27 |     2996 | 2024-04-10 | FaZe               | L   | 0.420      | -            | -                | -                | -         |    -0.67 | aliStair, dexter, INS, Liazz, Vexite |
|           26 |     3011 | 2024-04-09 | Nemiga             | W   | 0.418      | 0.624        | 0.316 (0.082)    | 0.731 (0.191)    | 1 (0.418) |     6.61 | aliStair, dexter, INS, Liazz, Vexite |
|           25 |     3061 | 2024-04-08 | Virtus.pro         | L   | 0.411      | -            | -                | -                | -         |    -0.62 | aliStair, dexter, INS, Liazz, Vexite |
|           24 |     3092 | 2024-04-08 | Cloud9             | W   | 0.405      | 0.624        | 0.061 (0.016)    | 0.108 (0.027)    | 1 (0.405) |     4.79 | aliStair, dexter, INS, Liazz, Vexite |
|           23 |     3233 | 2024-04-03 | Arcade             | W   | 0.372      | -            | -                | -                | -         |     0.72 | aliStair, dexter, INS, Liazz, Vexite |
|           22 |     3238 | 2024-04-03 | Arcade             | W   | 0.372      | -            | -                | -                | -         |     0.72 | aliStair, dexter, INS, Liazz, Vexite |
|           21 |     3361 | 2024-03-27 | KZG                | W   | 0.326      | -            | -                | -                | -         |     0.70 | aliStair, dexter, INS, Liazz, Vexite |
|           20 |     3366 | 2024-03-27 | KZG                | W   | 0.326      | -            | -                | -                | -         |     0.70 | aliStair, dexter, INS, Liazz, Vexite |
|           19 |     3631 | 2024-03-13 | Rooster            | W   | 0.233      | -            | -                | -                | -         |     0.82 | aliStair, dexter, INS, Liazz, Vexite |
|           18 |     3639 | 2024-03-13 | Rooster            | W   | 0.233      | -            | -                | -                | -         |     0.82 | aliStair, dexter, INS, Liazz, Vexite |
|           17 |     3808 | 2024-03-06 | DXA                | W   | 0.186      | -            | -                | -                | -         |     0.41 | aliStair, dexter, INS, Liazz, Vexite |
|           16 |     3810 | 2024-03-06 | DXA                | W   | 0.186      | -            | -                | -                | -         |     0.41 | aliStair, dexter, INS, Liazz, Vexite |
|           15 |     3958 | 2024-02-27 | Lynn Vision        | L   | 0.139      | -            | -                | -                | -         |    -2.82 | aliStair, dexter, INS, Liazz, Vexite |
|           14 |     3959 | 2024-02-27 | ATOX               | W   | 0.138      | -            | -                | -                | 1 (0.138) |     0.71 | aliStair, dexter, INS, Liazz, Vexite |
|           13 |     3980 | 2024-02-27 | JiJieHao           | W   | 0.132      | -            | -                | -                | 1 (0.132) |     0.06 | aliStair, dexter, INS, Liazz, Vexite |
|           12 |     3996 | 2024-02-25 | The MongolZ        | L   | 0.125      | -            | -                | -                | -         |    -0.04 | aliStair, dexter, INS, Liazz, Vexite |
|           11 |     3999 | 2024-02-25 | ATOX               | W   | 0.124      | -            | -                | -                | 1 (0.124) |     0.64 | aliStair, dexter, INS, Liazz, Vexite |
|           10 |     4061 | 2024-02-23 | Rooster            | W   | 0.106      | -            | -                | -                | -         |     0.37 | aliStair, dexter, INS, Liazz, Vexite |
|            9 |     4080 | 2024-02-22 | Rooster            | W   | 0.099      | -            | -                | -                | -         |     0.34 | aliStair, dexter, INS, Liazz, Vexite |
|            8 |     4084 | 2024-02-21 | Bad News Kangaroos | W   | 0.098      | -            | -                | -                | -         |     0.15 | aliStair, dexter, INS, Liazz, Vexite |
|            7 |     4107 | 2024-02-21 | Bad News Kangaroos | W   | 0.093      | -            | -                | -                | -         |     0.14 | aliStair, dexter, INS, Liazz, Vexite |
|            6 |     4111 | 2024-02-21 | Bad News Kangaroos | W   | 0.092      | -            | -                | -                | -         |     0.14 | aliStair, dexter, INS, Liazz, Vexite |
|            5 |     4166 | 2024-02-18 | Mindfreak          | W   | 0.078      | -            | -                | -                | -         |     0.17 | aliStair, dexter, INS, Liazz, Vexite |
|            4 |     4184 | 2024-02-18 | Arcade             | W   | 0.072      | -            | -                | -                | -         |     0.15 | aliStair, dexter, INS, Liazz, Vexite |
|            3 |     4188 | 2024-02-18 | MANTRA             | W   | 0.072      | -            | -                | -                | -         |     0.03 | aliStair, dexter, INS, Liazz, Vexite |
|            2 |     4189 | 2024-02-17 | Arcade             | W   | 0.070      | -            | -                | -                | -         |     0.14 | aliStair, dexter, INS, Liazz, Vexite |
|            1 |     4211 | 2024-02-16 | GR                 | W   | 0.064      | -            | -                | -                | -         |     0.13 | aliStair, dexter, INS, Liazz, Vexite |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($33,522.43)
- Divide that value by the 5th highest value among all rosters ($322,333.56)
- The final value (0.10) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-21 |      1.000 | $10,000.00     | $10,000.00      |
| 2024-06-08 |      0.818 | $3,250.00      | $2,658.68       |
| 2024-06-02 |      0.775 | $4,000.00      | $3,098.89       |
| 2024-05-12 |      0.634 | $23,500.00     | $14,896.39      |
| 2024-04-14 |      0.446 | $6,000.00      | $2,675.97       |
| 2024-02-17 |      0.070 | $2,750.00      | $192.50         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
