### Roster Details<br />
Team Name: FlyQuest<br />
Roster: aliStair, dexter, INS, Liazz, Vexite<br />
Global Rank: [32](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [2]( ../standings_asia.md)<br />
<br />
Final Rank Value:  1201.1<br />
<br />
Final Rank Value (1201.1) = Starting Rank Value (1181.4) + Head To Head Adjustments (19.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.505[<sup>1</sup>](#table2)
- Bounty Collected: 0.423[<sup>2</sup>](#table1)
- Opponent Network: 0.147[<sup>2</sup>](#table1)
- LAN Wins: 0.440[<sup>2</sup>](#table1)

The average of these factors is 0.379<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1181.4
- 400 + ( ( 0.379 - 0.000 ) / ( 0.776 - 0.000 ) ) * 1600 = 1181.4


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
|           48 |      475 | 2024-07-18 | FURIA              | L   | 1.000      | -            | -                | -                | -         |    -3.13 | aliStair, dexter, INS, Liazz, Vexite |
|           47 |      542 | 2024-07-17 | FaZe               | L   | 1.000      | -            | -                | -                | -         |    -1.42 | aliStair, dexter, INS, Liazz, Vexite |
|           46 |     1110 | 2024-06-08 | Rooster            | W   | 0.849      | 0.333        | 0.010 (0.003)    | 0.266 (0.075)    | 0 (0.000) |     3.48 | aliStair, dexter, INS, Liazz, Vexite |
|           45 |     1165 | 2024-06-08 | Mindfreak          | W   | 0.843      | 0.333        | 0.004 (0.001)    | 0.227 (0.064)    | -         |     1.89 | aliStair, dexter, INS, Liazz, Vexite |
|           44 |     1220 | 2024-06-07 | Rooster            | L   | 0.837      | -            | -                | -                | -         |   -23.29 | aliStair, dexter, INS, Liazz, Vexite |
|           43 |     1548 | 2024-05-28 | BIG                | L   | 0.773      | -            | -                | -                | -         |   -11.58 | aliStair, dexter, INS, Liazz, Vexite |
|           42 |     1569 | 2024-05-27 | Spirit             | L   | 0.767      | -            | -                | -                | -         |    -0.53 | aliStair, dexter, INS, Liazz, Vexite |
|           41 |     1696 | 2024-05-22 | Mindfreak          | W   | 0.730      | 0.333        | -                | 0.227 (0.055)    | -         |     1.25 | aliStair, dexter, INS, Liazz, Vexite |
|           40 |     1701 | 2024-05-22 | Mindfreak          | W   | 0.730      | 0.333        | -                | 0.227 (0.055)    | -         |     1.27 | aliStair, dexter, INS, Liazz, Vexite |
|           39 |     1771 | 2024-05-20 | Canon Event        | W   | 0.717      | -            | -                | -                | -         |     0.32 | aliStair, dexter, INS, Liazz, Vexite |
|           38 |     1773 | 2024-05-20 | Canon Event        | W   | 0.717      | -            | -                | -                | -         |     0.32 | aliStair, dexter, INS, Liazz, Vexite |
|           37 |     2142 | 2024-05-08 | Liquid             | L   | 0.638      | -            | -                | -                | -         |    -3.91 | aliStair, dexter, INS, Liazz, Vexite |
|           36 |     2160 | 2024-05-07 | BetBoom            | W   | 0.632      | 0.889        | 0.256 (0.144)    | 0.554 (0.311)    | 1 (0.632) |    14.66 | aliStair, dexter, INS, Liazz, Vexite |
|           35 |     2204 | 2024-05-05 | Ninjas in Pyjamas  | W   | 0.618      | 0.889        | 0.256 (0.141)    | 0.477 (0.262)    | 1 (0.618) |    17.20 | aliStair, dexter, INS, Liazz, Vexite |
|           34 |     2220 | 2024-05-04 | PERA               | W   | 0.611      | 0.889        | 0.048 (0.026)    | 0.452 (0.245)    | 1 (0.611) |     3.35 | aliStair, dexter, INS, Liazz, Vexite |
|           33 |     2236 | 2024-05-03 | HEROIC             | L   | 0.604      | -            | -                | -                | -         |    -1.89 | aliStair, dexter, INS, Liazz, Vexite |
|           32 |     2263 | 2024-05-02 | BOSS               | W   | 0.598      | 0.889        | 0.014 (0.008)    | 0.334 (0.178)    | 1 (0.598) |     2.04 | aliStair, dexter, INS, Liazz, Vexite |
|           31 |     2285 | 2024-05-01 | Natus Vincere      | L   | 0.591      | -            | -                | -                | -         |    -0.22 | aliStair, dexter, INS, Liazz, Vexite |
|           30 |     2532 | 2024-04-20 | Bad News Kangaroos | W   | 0.517      | 0.143        | 0.017 (0.001)    | -                | -         |     1.53 | aliStair, dexter, INS, Liazz, Vexite |
|           29 |     2578 | 2024-04-19 | Rooster            | W   | 0.511      | -            | -                | -                | -         |     1.65 | aliStair, dexter, INS, Liazz, Vexite |
|           28 |     2585 | 2024-04-18 | Mindfreak          | W   | 0.509      | -            | -                | -                | -         |     0.94 | aliStair, dexter, INS, Liazz, Vexite |
|           27 |     2830 | 2024-04-10 | FaZe               | L   | 0.451      | -            | -                | -                | -         |    -0.68 | aliStair, dexter, INS, Liazz, Vexite |
|           26 |     2845 | 2024-04-09 | Nemiga             | W   | 0.449      | 0.624        | 0.322 (0.090)    | 0.698 (0.196)    | 1 (0.449) |     6.48 | aliStair, dexter, INS, Liazz, Vexite |
|           25 |     2895 | 2024-04-08 | Virtus.pro         | L   | 0.443      | -            | -                | -                | -         |    -0.67 | aliStair, dexter, INS, Liazz, Vexite |
|           24 |     2926 | 2024-04-08 | Cloud9             | W   | 0.436      | 0.624        | 0.067 (0.018)    | 0.118 (0.032)    | 1 (0.436) |     5.23 | aliStair, dexter, INS, Liazz, Vexite |
|           23 |     3067 | 2024-04-03 | Arcade             | W   | 0.404      | -            | -                | -                | -         |     0.66 | aliStair, dexter, INS, Liazz, Vexite |
|           22 |     3072 | 2024-04-03 | Arcade             | W   | 0.404      | -            | -                | -                | -         |     0.66 | aliStair, dexter, INS, Liazz, Vexite |
|           21 |     3195 | 2024-03-27 | KZG                | W   | 0.357      | -            | -                | -                | -         |     0.67 | aliStair, dexter, INS, Liazz, Vexite |
|           20 |     3200 | 2024-03-27 | KZG                | W   | 0.357      | -            | -                | -                | -         |     0.68 | aliStair, dexter, INS, Liazz, Vexite |
|           19 |     3465 | 2024-03-13 | Rooster            | W   | 0.264      | 0.333        | 0.010 (0.001)    | -                | -         |     0.83 | aliStair, dexter, INS, Liazz, Vexite |
|           18 |     3473 | 2024-03-13 | Rooster            | W   | 0.264      | -            | -                | -                | -         |     0.84 | aliStair, dexter, INS, Liazz, Vexite |
|           17 |     3642 | 2024-03-06 | DXA                | W   | 0.217      | -            | -                | -                | -         |     0.41 | aliStair, dexter, INS, Liazz, Vexite |
|           16 |     3644 | 2024-03-06 | DXA                | W   | 0.217      | -            | -                | -                | -         |     0.41 | aliStair, dexter, INS, Liazz, Vexite |
|           15 |     3792 | 2024-02-27 | Lynn Vision        | L   | 0.170      | -            | -                | -                | -         |    -3.98 | aliStair, dexter, INS, Liazz, Vexite |
|           14 |     3793 | 2024-02-27 | ATOX               | W   | 0.169      | -            | -                | -                | 1 (0.169) |     0.80 | aliStair, dexter, INS, Liazz, Vexite |
|           13 |     3814 | 2024-02-27 | JiJieHao           | W   | 0.164      | -            | -                | -                | 1 (0.164) |     0.07 | aliStair, dexter, INS, Liazz, Vexite |
|           12 |     3830 | 2024-02-25 | The MongolZ        | L   | 0.156      | -            | -                | -                | -         |    -0.06 | aliStair, dexter, INS, Liazz, Vexite |
|           11 |     3833 | 2024-02-25 | ATOX               | W   | 0.155      | -            | -                | -                | 1 (0.155) |     0.73 | aliStair, dexter, INS, Liazz, Vexite |
|           10 |     3895 | 2024-02-23 | Rooster            | W   | 0.137      | -            | -                | -                | -         |     0.42 | aliStair, dexter, INS, Liazz, Vexite |
|            9 |     3914 | 2024-02-22 | Rooster            | W   | 0.130      | -            | -                | -                | -         |     0.40 | aliStair, dexter, INS, Liazz, Vexite |
|            8 |     3918 | 2024-02-21 | Bad News Kangaroos | W   | 0.129      | -            | -                | -                | -         |     0.37 | aliStair, dexter, INS, Liazz, Vexite |
|            7 |     3941 | 2024-02-21 | Bad News Kangaroos | W   | 0.124      | -            | -                | -                | -         |     0.35 | aliStair, dexter, INS, Liazz, Vexite |
|            6 |     3945 | 2024-02-21 | Bad News Kangaroos | W   | 0.124      | -            | -                | -                | -         |     0.35 | aliStair, dexter, INS, Liazz, Vexite |
|            5 |     4000 | 2024-02-18 | Mindfreak          | W   | 0.110      | -            | -                | -                | -         |     0.20 | aliStair, dexter, INS, Liazz, Vexite |
|            4 |     4018 | 2024-02-18 | Arcade             | W   | 0.104      | -            | -                | -                | -         |     0.18 | aliStair, dexter, INS, Liazz, Vexite |
|            3 |     4022 | 2024-02-18 | MANTRA             | W   | 0.103      | -            | -                | -                | -         |     0.04 | aliStair, dexter, INS, Liazz, Vexite |
|            2 |     4023 | 2024-02-17 | Arcade             | W   | 0.101      | -            | -                | -                | -         |     0.17 | aliStair, dexter, INS, Liazz, Vexite |
|            1 |     4045 | 2024-02-16 | GR                 | W   | 0.096      | -            | -                | -                | -         |     0.17 | aliStair, dexter, INS, Liazz, Vexite |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($34,758.09)
- Divide that value by the 5th highest value among all rosters ($331,608.80)
- The final value (0.10) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-21 |      1.000 | $10,000.00     | $10,000.00      |
| 2024-06-08 |      0.849 | $3,250.00      | $2,760.35       |
| 2024-06-02 |      0.806 | $4,000.00      | $3,224.02       |
| 2024-05-12 |      0.665 | $23,500.00     | $15,631.53      |
| 2024-04-14 |      0.477 | $6,000.00      | $2,863.67       |
| 2024-02-17 |      0.101 | $2,750.00      | $278.53         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
