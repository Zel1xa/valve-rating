### Roster Details<br />
Team Name: FlyQuest<br />
Roster: aliStair, dexter, INS, Liazz, Vexite<br />
Global Rank: [32](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [2]( ../standings_asia.md)<br />
<br />
Final Rank Value:  1176.7<br />
<br />
Final Rank Value (1176.7) = Starting Rank Value (1150.4) + Head To Head Adjustments (26.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.504[<sup>1</sup>](#table2)
- Bounty Collected: 0.416[<sup>2</sup>](#table1)
- Opponent Network: 0.139[<sup>2</sup>](#table1)
- LAN Wins: 0.403[<sup>2</sup>](#table1)

The average of these factors is 0.366<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1150.4
- 400 + ( ( 0.366 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 1150.4


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
|           48 |      656 | 2024-07-18 | FURIA              | L   | 1.000      | -            | -                | -                | -         |    -2.90 | aliStair, dexter, INS, Liazz, Vexite |
|           47 |      723 | 2024-07-17 | FaZe               | L   | 1.000      | -            | -                | -                | -         |    -1.51 | aliStair, dexter, INS, Liazz, Vexite |
|           46 |     1291 | 2024-06-08 | Rooster            | W   | 0.812      | 0.333        | 0.010 (0.003)    | 0.246 (0.067)    | 0 (0.000) |     3.65 | aliStair, dexter, INS, Liazz, Vexite |
|           45 |     1346 | 2024-06-08 | Mindfreak          | W   | 0.806      | 0.333        | 0.004 (0.001)    | 0.223 (0.060)    | -         |     2.08 | aliStair, dexter, INS, Liazz, Vexite |
|           44 |     1401 | 2024-06-07 | Rooster            | L   | 0.799      | -            | -                | -                | -         |   -21.95 | aliStair, dexter, INS, Liazz, Vexite |
|           43 |     1729 | 2024-05-28 | BIG                | L   | 0.736      | -            | -                | -                | -         |    -8.68 | aliStair, dexter, INS, Liazz, Vexite |
|           42 |     1750 | 2024-05-27 | Spirit             | L   | 0.730      | -            | -                | -                | -         |    -0.47 | aliStair, dexter, INS, Liazz, Vexite |
|           41 |     1877 | 2024-05-22 | Mindfreak          | W   | 0.693      | 0.333        | 0.004 (0.001)    | 0.223 (0.052)    | -         |     1.39 | aliStair, dexter, INS, Liazz, Vexite |
|           40 |     1882 | 2024-05-22 | Mindfreak          | W   | 0.693      | 0.333        | -                | 0.223 (0.052)    | -         |     1.41 | aliStair, dexter, INS, Liazz, Vexite |
|           39 |     1952 | 2024-05-20 | Canon Event        | W   | 0.680      | -            | -                | -                | -         |     0.37 | aliStair, dexter, INS, Liazz, Vexite |
|           38 |     1954 | 2024-05-20 | Canon Event        | W   | 0.680      | -            | -                | -                | -         |     0.37 | aliStair, dexter, INS, Liazz, Vexite |
|           37 |     2323 | 2024-05-08 | Liquid             | L   | 0.601      | -            | -                | -                | -         |    -1.96 | aliStair, dexter, INS, Liazz, Vexite |
|           36 |     2341 | 2024-05-07 | BetBoom            | W   | 0.595      | 0.889        | 0.248 (0.131)    | 0.526 (0.278)    | 1 (0.595) |    14.02 | aliStair, dexter, INS, Liazz, Vexite |
|           35 |     2385 | 2024-05-05 | Ninjas in Pyjamas  | W   | 0.580      | 0.889        | 0.254 (0.131)    | 0.543 (0.280)    | 1 (0.580) |    16.73 | aliStair, dexter, INS, Liazz, Vexite |
|           34 |     2401 | 2024-05-04 | PERA               | W   | 0.574      | 0.889        | 0.048 (0.024)    | 0.445 (0.227)    | 1 (0.574) |     3.57 | aliStair, dexter, INS, Liazz, Vexite |
|           33 |     2417 | 2024-05-03 | HEROIC             | L   | 0.567      | -            | -                | -                | -         |    -1.76 | aliStair, dexter, INS, Liazz, Vexite |
|           32 |     2444 | 2024-05-02 | BOSS               | W   | 0.560      | 0.889        | 0.014 (0.007)    | 0.326 (0.162)    | 1 (0.560) |     2.17 | aliStair, dexter, INS, Liazz, Vexite |
|           31 |     2466 | 2024-05-01 | Natus Vincere      | L   | 0.554      | -            | -                | -                | -         |    -0.19 | aliStair, dexter, INS, Liazz, Vexite |
|           30 |     2713 | 2024-04-20 | Bad News Kangaroos | W   | 0.480      | 0.143        | 0.016 (0.001)    | -                | -         |     1.68 | aliStair, dexter, INS, Liazz, Vexite |
|           29 |     2759 | 2024-04-19 | Rooster            | W   | 0.473      | -            | -                | -                | -         |     1.73 | aliStair, dexter, INS, Liazz, Vexite |
|           28 |     2766 | 2024-04-18 | Mindfreak          | W   | 0.472      | -            | -                | -                | -         |     1.04 | aliStair, dexter, INS, Liazz, Vexite |
|           27 |     3011 | 2024-04-10 | FaZe               | L   | 0.414      | -            | -                | -                | -         |    -0.67 | aliStair, dexter, INS, Liazz, Vexite |
|           26 |     3026 | 2024-04-09 | Nemiga             | W   | 0.412      | 0.624        | 0.315 (0.081)    | 0.720 (0.185)    | 1 (0.412) |     6.55 | aliStair, dexter, INS, Liazz, Vexite |
|           25 |     3076 | 2024-04-08 | Virtus.pro         | L   | 0.405      | -            | -                | -                | -         |    -0.61 | aliStair, dexter, INS, Liazz, Vexite |
|           24 |     3107 | 2024-04-08 | Cloud9             | W   | 0.399      | 0.624        | 0.061 (0.015)    | 0.105 (0.026)    | 1 (0.399) |     4.70 | aliStair, dexter, INS, Liazz, Vexite |
|           23 |     3248 | 2024-04-03 | Arcade             | W   | 0.367      | -            | -                | -                | -         |     0.72 | aliStair, dexter, INS, Liazz, Vexite |
|           22 |     3253 | 2024-04-03 | Arcade             | W   | 0.366      | -            | -                | -                | -         |     0.72 | aliStair, dexter, INS, Liazz, Vexite |
|           21 |     3376 | 2024-03-27 | KZG                | W   | 0.320      | -            | -                | -                | -         |     0.70 | aliStair, dexter, INS, Liazz, Vexite |
|           20 |     3381 | 2024-03-27 | KZG                | W   | 0.320      | -            | -                | -                | -         |     0.70 | aliStair, dexter, INS, Liazz, Vexite |
|           19 |     3646 | 2024-03-13 | Rooster            | W   | 0.227      | -            | -                | -                | -         |     0.81 | aliStair, dexter, INS, Liazz, Vexite |
|           18 |     3654 | 2024-03-13 | Rooster            | W   | 0.227      | -            | -                | -                | -         |     0.81 | aliStair, dexter, INS, Liazz, Vexite |
|           17 |     3823 | 2024-03-06 | DXA                | W   | 0.180      | -            | -                | -                | -         |     0.41 | aliStair, dexter, INS, Liazz, Vexite |
|           16 |     3825 | 2024-03-06 | DXA                | W   | 0.180      | -            | -                | -                | -         |     0.41 | aliStair, dexter, INS, Liazz, Vexite |
|           15 |     3973 | 2024-02-27 | Lynn Vision        | L   | 0.133      | -            | -                | -                | -         |    -2.69 | aliStair, dexter, INS, Liazz, Vexite |
|           14 |     3974 | 2024-02-27 | ATOX               | W   | 0.132      | -            | -                | -                | 1 (0.132) |     0.69 | aliStair, dexter, INS, Liazz, Vexite |
|           13 |     3995 | 2024-02-27 | JiJieHao           | W   | 0.126      | -            | -                | -                | 1 (0.126) |     0.06 | aliStair, dexter, INS, Liazz, Vexite |
|           12 |     4011 | 2024-02-25 | The MongolZ        | L   | 0.119      | -            | -                | -                | -         |    -0.04 | aliStair, dexter, INS, Liazz, Vexite |
|           11 |     4014 | 2024-02-25 | ATOX               | W   | 0.118      | -            | -                | -                | 1 (0.118) |     0.62 | aliStair, dexter, INS, Liazz, Vexite |
|           10 |     4076 | 2024-02-23 | Rooster            | W   | 0.100      | -            | -                | -                | -         |     0.35 | aliStair, dexter, INS, Liazz, Vexite |
|            9 |     4095 | 2024-02-22 | Rooster            | W   | 0.093      | -            | -                | -                | -         |     0.33 | aliStair, dexter, INS, Liazz, Vexite |
|            8 |     4099 | 2024-02-21 | Bad News Kangaroos | W   | 0.092      | -            | -                | -                | -         |     0.14 | aliStair, dexter, INS, Liazz, Vexite |
|            7 |     4122 | 2024-02-21 | Bad News Kangaroos | W   | 0.087      | -            | -                | -                | -         |     0.13 | aliStair, dexter, INS, Liazz, Vexite |
|            6 |     4126 | 2024-02-21 | Bad News Kangaroos | W   | 0.087      | -            | -                | -                | -         |     0.13 | aliStair, dexter, INS, Liazz, Vexite |
|            5 |     4181 | 2024-02-18 | Mindfreak          | W   | 0.072      | -            | -                | -                | -         |     0.16 | aliStair, dexter, INS, Liazz, Vexite |
|            4 |     4199 | 2024-02-18 | Arcade             | W   | 0.067      | -            | -                | -                | -         |     0.14 | aliStair, dexter, INS, Liazz, Vexite |
|            3 |     4203 | 2024-02-18 | MANTRA             | W   | 0.066      | -            | -                | -                | -         |     0.03 | aliStair, dexter, INS, Liazz, Vexite |
|            2 |     4204 | 2024-02-17 | Arcade             | W   | 0.064      | -            | -                | -                | -         |     0.13 | aliStair, dexter, INS, Liazz, Vexite |
|            1 |     4226 | 2024-02-16 | GR                 | W   | 0.059      | -            | -                | -                | -         |     0.12 | aliStair, dexter, INS, Liazz, Vexite |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($33,292.01)
- Divide that value by the 5th highest value among all rosters ($320,603.98)
- The final value (0.10) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-21 |      1.000 | $10,000.00     | $10,000.00      |
| 2024-06-08 |      0.812 | $3,250.00      | $2,639.72       |
| 2024-06-02 |      0.769 | $4,000.00      | $3,075.56       |
| 2024-05-12 |      0.628 | $23,500.00     | $14,759.31      |
| 2024-04-14 |      0.440 | $6,000.00      | $2,640.97       |
| 2024-02-17 |      0.064 | $2,750.00      | $176.46         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
