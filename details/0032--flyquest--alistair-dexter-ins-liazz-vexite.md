### Roster Details<br />
Team Name: FlyQuest<br />
Roster: aliStair, dexter, INS, Liazz, Vexite<br />
Global Rank: [32](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [2]( ../standings_asia.md)<br />
<br />
Final Rank Value:  1182.6<br />
<br />
Final Rank Value (1182.6) = Starting Rank Value (1156.6) + Head To Head Adjustments (26.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.504[<sup>1</sup>](#table2)
- Bounty Collected: 0.418[<sup>2</sup>](#table1)
- Opponent Network: 0.145[<sup>2</sup>](#table1)
- LAN Wins: 0.412[<sup>2</sup>](#table1)

The average of these factors is 0.370<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1156.6
- 400 + ( ( 0.370 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 1156.6


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
|           48 |      623 | 2024-07-18 | FURIA              | L   | 1.000      | -            | -                | -                | -         |    -3.03 | aliStair, dexter, INS, Liazz, Vexite |
|           47 |      690 | 2024-07-17 | FaZe               | L   | 1.000      | -            | -                | -                | -         |    -1.50 | aliStair, dexter, INS, Liazz, Vexite |
|           46 |     1258 | 2024-06-08 | Rooster            | W   | 0.824      | 0.333        | 0.010 (0.003)    | 0.251 (0.069)    | 0 (0.000) |     3.64 | aliStair, dexter, INS, Liazz, Vexite |
|           45 |     1313 | 2024-06-08 | Mindfreak          | W   | 0.818      | 0.333        | 0.004 (0.001)    | 0.227 (0.062)    | -         |     2.06 | aliStair, dexter, INS, Liazz, Vexite |
|           44 |     1368 | 2024-06-07 | Rooster            | L   | 0.811      | -            | -                | -                | -         |   -22.34 | aliStair, dexter, INS, Liazz, Vexite |
|           43 |     1696 | 2024-05-28 | BIG                | L   | 0.748      | -            | -                | -                | -         |    -8.97 | aliStair, dexter, INS, Liazz, Vexite |
|           42 |     1717 | 2024-05-27 | Spirit             | L   | 0.742      | -            | -                | -                | -         |    -0.49 | aliStair, dexter, INS, Liazz, Vexite |
|           41 |     1844 | 2024-05-22 | Mindfreak          | W   | 0.705      | 0.333        | 0.004 (0.001)    | 0.227 (0.053)    | -         |     1.37 | aliStair, dexter, INS, Liazz, Vexite |
|           40 |     1849 | 2024-05-22 | Mindfreak          | W   | 0.705      | 0.333        | -                | 0.227 (0.053)    | -         |     1.39 | aliStair, dexter, INS, Liazz, Vexite |
|           39 |     1919 | 2024-05-20 | Canon Event        | W   | 0.692      | -            | -                | -                | -         |     0.36 | aliStair, dexter, INS, Liazz, Vexite |
|           38 |     1921 | 2024-05-20 | Canon Event        | W   | 0.692      | -            | -                | -                | -         |     0.36 | aliStair, dexter, INS, Liazz, Vexite |
|           37 |     2290 | 2024-05-08 | Liquid             | L   | 0.613      | -            | -                | -                | -         |    -2.07 | aliStair, dexter, INS, Liazz, Vexite |
|           36 |     2308 | 2024-05-07 | BetBoom            | W   | 0.606      | 0.889        | 0.251 (0.135)    | 0.541 (0.292)    | 1 (0.606) |    14.23 | aliStair, dexter, INS, Liazz, Vexite |
|           35 |     2352 | 2024-05-05 | Ninjas in Pyjamas  | W   | 0.592      | 0.889        | 0.255 (0.134)    | 0.553 (0.291)    | 1 (0.592) |    17.02 | aliStair, dexter, INS, Liazz, Vexite |
|           34 |     2368 | 2024-05-04 | PERA               | W   | 0.586      | 0.889        | 0.048 (0.025)    | 0.453 (0.236)    | 1 (0.586) |     3.54 | aliStair, dexter, INS, Liazz, Vexite |
|           33 |     2384 | 2024-05-03 | HEROIC             | L   | 0.579      | -            | -                | -                | -         |    -1.82 | aliStair, dexter, INS, Liazz, Vexite |
|           32 |     2411 | 2024-05-02 | BOSS               | W   | 0.572      | 0.889        | 0.014 (0.007)    | 0.332 (0.169)    | 1 (0.572) |     2.15 | aliStair, dexter, INS, Liazz, Vexite |
|           31 |     2433 | 2024-05-01 | Natus Vincere      | L   | 0.566      | -            | -                | -                | -         |    -0.20 | aliStair, dexter, INS, Liazz, Vexite |
|           30 |     2680 | 2024-04-20 | Bad News Kangaroos | W   | 0.492      | 0.143        | 0.017 (0.001)    | -                | -         |     1.69 | aliStair, dexter, INS, Liazz, Vexite |
|           29 |     2726 | 2024-04-19 | Rooster            | W   | 0.485      | -            | -                | -                | -         |     1.73 | aliStair, dexter, INS, Liazz, Vexite |
|           28 |     2733 | 2024-04-18 | Mindfreak          | W   | 0.484      | -            | -                | -                | -         |     1.03 | aliStair, dexter, INS, Liazz, Vexite |
|           27 |     2978 | 2024-04-10 | FaZe               | L   | 0.426      | -            | -                | -                | -         |    -0.68 | aliStair, dexter, INS, Liazz, Vexite |
|           26 |     2993 | 2024-04-09 | Nemiga             | W   | 0.424      | 0.624        | 0.317 (0.084)    | 0.734 (0.194)    | 1 (0.424) |     6.66 | aliStair, dexter, INS, Liazz, Vexite |
|           25 |     3043 | 2024-04-08 | Virtus.pro         | L   | 0.417      | -            | -                | -                | -         |    -0.64 | aliStair, dexter, INS, Liazz, Vexite |
|           24 |     3074 | 2024-04-08 | Cloud9             | W   | 0.411      | 0.624        | 0.062 (0.016)    | 0.111 (0.028)    | 1 (0.411) |     4.90 | aliStair, dexter, INS, Liazz, Vexite |
|           23 |     3215 | 2024-04-03 | Arcade             | W   | 0.378      | -            | -                | -                | -         |     0.72 | aliStair, dexter, INS, Liazz, Vexite |
|           22 |     3220 | 2024-04-03 | Arcade             | W   | 0.378      | -            | -                | -                | -         |     0.72 | aliStair, dexter, INS, Liazz, Vexite |
|           21 |     3343 | 2024-03-27 | KZG                | W   | 0.332      | -            | -                | -                | -         |     0.70 | aliStair, dexter, INS, Liazz, Vexite |
|           20 |     3348 | 2024-03-27 | KZG                | W   | 0.332      | -            | -                | -                | -         |     0.70 | aliStair, dexter, INS, Liazz, Vexite |
|           19 |     3613 | 2024-03-13 | Rooster            | W   | 0.239      | -            | -                | -                | -         |     0.83 | aliStair, dexter, INS, Liazz, Vexite |
|           18 |     3621 | 2024-03-13 | Rooster            | W   | 0.239      | -            | -                | -                | -         |     0.83 | aliStair, dexter, INS, Liazz, Vexite |
|           17 |     3790 | 2024-03-06 | DXA                | W   | 0.192      | -            | -                | -                | -         |     0.42 | aliStair, dexter, INS, Liazz, Vexite |
|           16 |     3792 | 2024-03-06 | DXA                | W   | 0.192      | -            | -                | -                | -         |     0.42 | aliStair, dexter, INS, Liazz, Vexite |
|           15 |     3940 | 2024-02-27 | Lynn Vision        | L   | 0.145      | -            | -                | -                | -         |    -2.98 | aliStair, dexter, INS, Liazz, Vexite |
|           14 |     3941 | 2024-02-27 | ATOX               | W   | 0.144      | -            | -                | -                | 1 (0.144) |     0.73 | aliStair, dexter, INS, Liazz, Vexite |
|           13 |     3962 | 2024-02-27 | JiJieHao           | W   | 0.138      | -            | -                | -                | 1 (0.138) |     0.07 | aliStair, dexter, INS, Liazz, Vexite |
|           12 |     3978 | 2024-02-25 | The MongolZ        | L   | 0.131      | -            | -                | -                | -         |    -0.05 | aliStair, dexter, INS, Liazz, Vexite |
|           11 |     3981 | 2024-02-25 | ATOX               | W   | 0.130      | -            | -                | -                | 1 (0.130) |     0.66 | aliStair, dexter, INS, Liazz, Vexite |
|           10 |     4043 | 2024-02-23 | Rooster            | W   | 0.112      | -            | -                | -                | -         |     0.38 | aliStair, dexter, INS, Liazz, Vexite |
|            9 |     4062 | 2024-02-22 | Rooster            | W   | 0.105      | -            | -                | -                | -         |     0.36 | aliStair, dexter, INS, Liazz, Vexite |
|            8 |     4066 | 2024-02-21 | Bad News Kangaroos | W   | 0.104      | -            | -                | -                | -         |     0.15 | aliStair, dexter, INS, Liazz, Vexite |
|            7 |     4089 | 2024-02-21 | Bad News Kangaroos | W   | 0.099      | -            | -                | -                | -         |     0.15 | aliStair, dexter, INS, Liazz, Vexite |
|            6 |     4093 | 2024-02-21 | Bad News Kangaroos | W   | 0.099      | -            | -                | -                | -         |     0.15 | aliStair, dexter, INS, Liazz, Vexite |
|            5 |     4148 | 2024-02-18 | Mindfreak          | W   | 0.084      | -            | -                | -                | -         |     0.18 | aliStair, dexter, INS, Liazz, Vexite |
|            4 |     4166 | 2024-02-18 | Arcade             | W   | 0.078      | -            | -                | -                | -         |     0.16 | aliStair, dexter, INS, Liazz, Vexite |
|            3 |     4170 | 2024-02-18 | MANTRA             | W   | 0.078      | -            | -                | -                | -         |     0.04 | aliStair, dexter, INS, Liazz, Vexite |
|            2 |     4171 | 2024-02-17 | Arcade             | W   | 0.076      | -            | -                | -                | -         |     0.15 | aliStair, dexter, INS, Liazz, Vexite |
|            1 |     4193 | 2024-02-16 | GR                 | W   | 0.071      | -            | -                | -                | -         |     0.14 | aliStair, dexter, INS, Liazz, Vexite |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($33,760.16)
- Divide that value by the 5th highest value among all rosters ($324,118.06)
- The final value (0.10) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-21 |      1.000 | $10,000.00     | $10,000.00      |
| 2024-06-08 |      0.824 | $3,250.00      | $2,678.24       |
| 2024-06-02 |      0.781 | $4,000.00      | $3,122.96       |
| 2024-05-12 |      0.640 | $23,500.00     | $15,037.82      |
| 2024-04-14 |      0.452 | $6,000.00      | $2,712.08       |
| 2024-02-17 |      0.076 | $2,750.00      | $209.05         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
