### Roster Details<br />
Team Name: FlyQuest<br />
Roster: aliStair, dexter, INS, Liazz, Vexite<br />
Global Rank: [32](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [2]( ../standings_asia.md)<br />
<br />
Final Rank Value:  1193.7<br />
<br />
Final Rank Value (1193.7) = Starting Rank Value (1174.2) + Head To Head Adjustments (19.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.506[<sup>1</sup>](#table2)
- Bounty Collected: 0.418[<sup>2</sup>](#table1)
- Opponent Network: 0.143[<sup>2</sup>](#table1)
- LAN Wins: 0.437[<sup>2</sup>](#table1)

The average of these factors is 0.376<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1174.2
- 400 + ( ( 0.376 - 0.000 ) / ( 0.777 - 0.000 ) ) * 1600 = 1174.2


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
|           50 |      513 | 2024-07-18 | FURIA              | L   | 1.000      | -            | -                | -                | -         |    -3.32 | aliStair, dexter, INS, Liazz, Vexite |
|           49 |      580 | 2024-07-17 | FaZe               | L   | 1.000      | -            | -                | -                | -         |    -1.44 | aliStair, dexter, INS, Liazz, Vexite |
|           48 |     1148 | 2024-06-08 | Rooster            | W   | 0.845      | 0.333        | 0.010 (0.003)    | 0.281 (0.079)    | 0 (0.000) |     3.62 | aliStair, dexter, INS, Liazz, Vexite |
|           47 |     1206 | 2024-06-08 | Mindfreak          | W   | 0.839      | 0.333        | 0.004 (0.001)    | 0.227 (0.063)    | -         |     1.93 | aliStair, dexter, INS, Liazz, Vexite |
|           46 |     1266 | 2024-06-07 | Rooster            | L   | 0.832      | -            | -                | -                | -         |   -23.02 | aliStair, dexter, INS, Liazz, Vexite |
|           45 |     1600 | 2024-05-28 | BIG                | L   | 0.769      | -            | -                | -                | -         |   -11.72 | aliStair, dexter, INS, Liazz, Vexite |
|           44 |     1621 | 2024-05-27 | Spirit             | L   | 0.762      | -            | -                | -                | -         |    -0.53 | aliStair, dexter, INS, Liazz, Vexite |
|           43 |     1760 | 2024-05-22 | Mindfreak          | W   | 0.726      | 0.333        | -                | 0.227 (0.055)    | -         |     1.28 | aliStair, dexter, INS, Liazz, Vexite |
|           42 |     1765 | 2024-05-22 | Mindfreak          | W   | 0.726      | 0.333        | -                | 0.227 (0.055)    | -         |     1.30 | aliStair, dexter, INS, Liazz, Vexite |
|           41 |     1845 | 2024-05-20 | Canon Event        | W   | 0.713      | -            | -                | -                | -         |     0.34 | aliStair, dexter, INS, Liazz, Vexite |
|           40 |     1847 | 2024-05-20 | Canon Event        | W   | 0.713      | -            | -                | -                | -         |     0.34 | aliStair, dexter, INS, Liazz, Vexite |
|           39 |     2043 | 2024-05-15 | Vantage            | W   | 0.679      | -            | -                | -                | -         |     0.87 | aliStair, dexter, INS, Liazz, Vexite |
|           38 |     2044 | 2024-05-15 | Vantage            | W   | 0.679      | -            | -                | -                | -         |     0.88 | aliStair, dexter, INS, Liazz, Vexite |
|           37 |     2233 | 2024-05-08 | Liquid             | L   | 0.634      | -            | -                | -                | -         |    -4.12 | aliStair, dexter, INS, Liazz, Vexite |
|           36 |     2251 | 2024-05-07 | BetBoom            | W   | 0.627      | 0.889        | 0.257 (0.144)    | 0.551 (0.308)    | 1 (0.627) |    14.55 | aliStair, dexter, INS, Liazz, Vexite |
|           35 |     2295 | 2024-05-05 | Ninjas in Pyjamas  | W   | 0.613      | 0.889        | 0.207 (0.113)    | 0.409 (0.223)    | 1 (0.613) |    15.12 | aliStair, dexter, INS, Liazz, Vexite |
|           34 |     2311 | 2024-05-04 | PERA               | W   | 0.607      | 0.889        | 0.048 (0.026)    | 0.452 (0.244)    | 1 (0.607) |     3.35 | aliStair, dexter, INS, Liazz, Vexite |
|           33 |     2327 | 2024-05-03 | HEROIC             | L   | 0.600      | -            | -                | -                | -         |    -2.05 | aliStair, dexter, INS, Liazz, Vexite |
|           32 |     2355 | 2024-05-02 | BOSS               | W   | 0.593      | 0.889        | 0.014 (0.008)    | 0.334 (0.176)    | 1 (0.593) |     2.15 | aliStair, dexter, INS, Liazz, Vexite |
|           31 |     2378 | 2024-05-01 | Natus Vincere      | L   | 0.587      | -            | -                | -                | -         |    -0.21 | aliStair, dexter, INS, Liazz, Vexite |
|           30 |     2632 | 2024-04-20 | Bad News Kangaroos | W   | 0.513      | 0.143        | 0.017 (0.001)    | -                | -         |     1.57 | aliStair, dexter, INS, Liazz, Vexite |
|           29 |     2679 | 2024-04-19 | Rooster            | W   | 0.506      | -            | -                | -                | -         |     1.72 | aliStair, dexter, INS, Liazz, Vexite |
|           28 |     2686 | 2024-04-18 | Mindfreak          | W   | 0.505      | -            | -                | -                | -         |     0.96 | aliStair, dexter, INS, Liazz, Vexite |
|           27 |     2935 | 2024-04-10 | FaZe               | L   | 0.447      | -            | -                | -                | -         |    -0.67 | aliStair, dexter, INS, Liazz, Vexite |
|           26 |     2950 | 2024-04-09 | Nemiga             | W   | 0.445      | 0.624        | 0.324 (0.090)    | 0.697 (0.194)    | 1 (0.445) |     6.51 | aliStair, dexter, INS, Liazz, Vexite |
|           25 |     3000 | 2024-04-08 | Virtus.pro         | L   | 0.438      | -            | -                | -                | -         |    -0.70 | aliStair, dexter, INS, Liazz, Vexite |
|           24 |     3031 | 2024-04-08 | Cloud9             | W   | 0.432      | 0.624        | 0.067 (0.018)    | 0.117 (0.032)    | 1 (0.432) |     5.23 | aliStair, dexter, INS, Liazz, Vexite |
|           23 |     3178 | 2024-04-03 | Arcade             | W   | 0.399      | -            | -                | -                | -         |     0.67 | aliStair, dexter, INS, Liazz, Vexite |
|           22 |     3183 | 2024-04-03 | Arcade             | W   | 0.399      | -            | -                | -                | -         |     0.68 | aliStair, dexter, INS, Liazz, Vexite |
|           21 |     3309 | 2024-03-27 | KZG                | W   | 0.353      | -            | -                | -                | -         |     0.69 | aliStair, dexter, INS, Liazz, Vexite |
|           20 |     3314 | 2024-03-27 | KZG                | W   | 0.353      | -            | -                | -                | -         |     0.69 | aliStair, dexter, INS, Liazz, Vexite |
|           19 |     3587 | 2024-03-13 | Rooster            | W   | 0.260      | 0.333        | 0.010 (0.001)    | -                | -         |     0.84 | aliStair, dexter, INS, Liazz, Vexite |
|           18 |     3595 | 2024-03-13 | Rooster            | W   | 0.259      | -            | -                | -                | -         |     0.85 | aliStair, dexter, INS, Liazz, Vexite |
|           17 |     3766 | 2024-03-06 | DXA                | W   | 0.213      | -            | -                | -                | -         |     0.41 | aliStair, dexter, INS, Liazz, Vexite |
|           16 |     3768 | 2024-03-06 | DXA                | W   | 0.213      | -            | -                | -                | -         |     0.41 | aliStair, dexter, INS, Liazz, Vexite |
|           15 |     3923 | 2024-02-27 | Lynn Vision        | L   | 0.166      | -            | -                | -                | -         |    -3.85 | aliStair, dexter, INS, Liazz, Vexite |
|           14 |     3924 | 2024-02-27 | ATOX               | W   | 0.164      | -            | -                | -                | 1 (0.164) |     0.80 | aliStair, dexter, INS, Liazz, Vexite |
|           13 |     3947 | 2024-02-27 | JiJieHao           | W   | 0.159      | -            | -                | -                | 1 (0.159) |     0.07 | aliStair, dexter, INS, Liazz, Vexite |
|           12 |     3962 | 2024-02-25 | The MongolZ        | L   | 0.152      | -            | -                | -                | -         |    -0.06 | aliStair, dexter, INS, Liazz, Vexite |
|           11 |     3965 | 2024-02-25 | ATOX               | W   | 0.151      | -            | -                | -                | 1 (0.151) |     0.73 | aliStair, dexter, INS, Liazz, Vexite |
|           10 |     4032 | 2024-02-23 | Rooster            | W   | 0.133      | -            | -                | -                | -         |     0.42 | aliStair, dexter, INS, Liazz, Vexite |
|            9 |     4052 | 2024-02-22 | Rooster            | W   | 0.126      | -            | -                | -                | -         |     0.40 | aliStair, dexter, INS, Liazz, Vexite |
|            8 |     4056 | 2024-02-21 | Bad News Kangaroos | W   | 0.125      | -            | -                | -                | -         |     0.37 | aliStair, dexter, INS, Liazz, Vexite |
|            7 |     4078 | 2024-02-21 | Bad News Kangaroos | W   | 0.120      | -            | -                | -                | -         |     0.35 | aliStair, dexter, INS, Liazz, Vexite |
|            6 |     4084 | 2024-02-21 | Bad News Kangaroos | W   | 0.119      | -            | -                | -                | -         |     0.35 | aliStair, dexter, INS, Liazz, Vexite |
|            5 |     4139 | 2024-02-18 | Mindfreak          | W   | 0.105      | -            | -                | -                | -         |     0.20 | aliStair, dexter, INS, Liazz, Vexite |
|            4 |     4156 | 2024-02-18 | Arcade             | W   | 0.099      | -            | -                | -                | -         |     0.18 | aliStair, dexter, INS, Liazz, Vexite |
|            3 |     4160 | 2024-02-18 | MANTRA             | W   | 0.099      | -            | -                | -                | -         |     0.07 | aliStair, dexter, INS, Liazz, Vexite |
|            2 |     4161 | 2024-02-17 | Arcade             | W   | 0.097      | -            | -                | -                | -         |     0.17 | aliStair, dexter, INS, Liazz, Vexite |
|            1 |     4183 | 2024-02-16 | GR                 | W   | 0.091      | -            | -                | -                | -         |     0.16 | aliStair, dexter, INS, Liazz, Vexite |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($34,586.74)
- Divide that value by the 5th highest value among all rosters ($327,422.13)
- The final value (0.11) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-21 |      1.000 | $10,000.00     | $10,000.00      |
| 2024-06-08 |      0.845 | $3,250.00      | $2,746.25       |
| 2024-06-02 |      0.802 | $4,000.00      | $3,206.67       |
| 2024-05-12 |      0.661 | $23,500.00     | $15,529.58      |
| 2024-04-14 |      0.473 | $6,000.00      | $2,837.64       |
| 2024-02-17 |      0.097 | $2,750.00      | $266.60         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
