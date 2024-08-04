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
Final Rank Value (1179.6) = Starting Rank Value (1155.4) + Head To Head Adjustments (24.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.505[<sup>1</sup>](#table2)
- Bounty Collected: 0.415[<sup>2</sup>](#table1)
- Opponent Network: 0.145[<sup>2</sup>](#table1)
- LAN Wins: 0.413[<sup>2</sup>](#table1)

The average of these factors is 0.369<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1155.4
- 400 + ( ( 0.369 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 1155.4


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
|           48 |      592 | 2024-07-18 | FURIA              | L   | 1.000      | -            | -                | -                | -         |    -3.04 | aliStair, dexter, INS, Liazz, Vexite |
|           47 |      659 | 2024-07-17 | FaZe               | L   | 1.000      | -            | -                | -                | -         |    -1.52 | aliStair, dexter, INS, Liazz, Vexite |
|           46 |     1227 | 2024-06-08 | Rooster            | W   | 0.826      | 0.333        | 0.010 (0.003)    | 0.266 (0.073)    | 0 (0.000) |     3.58 | aliStair, dexter, INS, Liazz, Vexite |
|           45 |     1282 | 2024-06-08 | Mindfreak          | W   | 0.819      | 0.333        | 0.004 (0.001)    | 0.227 (0.062)    | -         |     1.98 | aliStair, dexter, INS, Liazz, Vexite |
|           44 |     1337 | 2024-06-07 | Rooster            | L   | 0.813      | -            | -                | -                | -         |   -22.44 | aliStair, dexter, INS, Liazz, Vexite |
|           43 |     1665 | 2024-05-28 | BIG                | L   | 0.749      | -            | -                | -                | -         |    -8.92 | aliStair, dexter, INS, Liazz, Vexite |
|           42 |     1686 | 2024-05-27 | Spirit             | L   | 0.743      | -            | -                | -                | -         |    -0.49 | aliStair, dexter, INS, Liazz, Vexite |
|           41 |     1813 | 2024-05-22 | Mindfreak          | W   | 0.707      | 0.333        | 0.004 (0.001)    | 0.227 (0.053)    | -         |     1.34 | aliStair, dexter, INS, Liazz, Vexite |
|           40 |     1818 | 2024-05-22 | Mindfreak          | W   | 0.706      | 0.333        | -                | 0.227 (0.053)    | -         |     1.36 | aliStair, dexter, INS, Liazz, Vexite |
|           39 |     1888 | 2024-05-20 | Canon Event        | W   | 0.694      | -            | -                | -                | -         |     0.36 | aliStair, dexter, INS, Liazz, Vexite |
|           38 |     1890 | 2024-05-20 | Canon Event        | W   | 0.693      | -            | -                | -                | -         |     0.36 | aliStair, dexter, INS, Liazz, Vexite |
|           37 |     2259 | 2024-05-08 | Liquid             | L   | 0.615      | -            | -                | -                | -         |    -3.08 | aliStair, dexter, INS, Liazz, Vexite |
|           36 |     2277 | 2024-05-07 | BetBoom            | W   | 0.608      | 0.889        | 0.251 (0.136)    | 0.542 (0.293)    | 1 (0.608) |    14.29 | aliStair, dexter, INS, Liazz, Vexite |
|           35 |     2321 | 2024-05-05 | Ninjas in Pyjamas  | W   | 0.594      | 0.889        | 0.222 (0.117)    | 0.553 (0.292)    | 1 (0.594) |    16.97 | aliStair, dexter, INS, Liazz, Vexite |
|           34 |     2337 | 2024-05-04 | PERA               | W   | 0.587      | 0.889        | 0.048 (0.025)    | 0.453 (0.236)    | 1 (0.587) |     3.53 | aliStair, dexter, INS, Liazz, Vexite |
|           33 |     2353 | 2024-05-03 | HEROIC             | L   | 0.580      | -            | -                | -                | -         |    -1.84 | aliStair, dexter, INS, Liazz, Vexite |
|           32 |     2380 | 2024-05-02 | BOSS               | W   | 0.574      | 0.889        | 0.014 (0.007)    | 0.333 (0.170)    | 1 (0.574) |     2.16 | aliStair, dexter, INS, Liazz, Vexite |
|           31 |     2402 | 2024-05-01 | Natus Vincere      | L   | 0.567      | -            | -                | -                | -         |    -0.20 | aliStair, dexter, INS, Liazz, Vexite |
|           30 |     2649 | 2024-04-20 | Bad News Kangaroos | W   | 0.493      | 0.143        | 0.017 (0.001)    | -                | -         |     1.58 | aliStair, dexter, INS, Liazz, Vexite |
|           29 |     2695 | 2024-04-19 | Rooster            | W   | 0.487      | -            | -                | -                | -         |     1.72 | aliStair, dexter, INS, Liazz, Vexite |
|           28 |     2702 | 2024-04-18 | Mindfreak          | W   | 0.486      | -            | -                | -                | -         |     1.00 | aliStair, dexter, INS, Liazz, Vexite |
|           27 |     2947 | 2024-04-10 | FaZe               | L   | 0.427      | -            | -                | -                | -         |    -0.69 | aliStair, dexter, INS, Liazz, Vexite |
|           26 |     2962 | 2024-04-09 | Nemiga             | W   | 0.425      | 0.624        | 0.317 (0.084)    | 0.695 (0.184)    | 1 (0.425) |     6.33 | aliStair, dexter, INS, Liazz, Vexite |
|           25 |     3012 | 2024-04-08 | Virtus.pro         | L   | 0.419      | -            | -                | -                | -         |    -0.65 | aliStair, dexter, INS, Liazz, Vexite |
|           24 |     3043 | 2024-04-08 | Cloud9             | W   | 0.412      | 0.624        | 0.062 (0.016)    | 0.111 (0.029)    | 1 (0.412) |     4.84 | aliStair, dexter, INS, Liazz, Vexite |
|           23 |     3184 | 2024-04-03 | Arcade             | W   | 0.380      | -            | -                | -                | -         |     0.69 | aliStair, dexter, INS, Liazz, Vexite |
|           22 |     3189 | 2024-04-03 | Arcade             | W   | 0.380      | -            | -                | -                | -         |     0.69 | aliStair, dexter, INS, Liazz, Vexite |
|           21 |     3312 | 2024-03-27 | KZG                | W   | 0.333      | -            | -                | -                | -         |     0.70 | aliStair, dexter, INS, Liazz, Vexite |
|           20 |     3317 | 2024-03-27 | KZG                | W   | 0.333      | -            | -                | -                | -         |     0.71 | aliStair, dexter, INS, Liazz, Vexite |
|           19 |     3582 | 2024-03-13 | Rooster            | W   | 0.240      | -            | -                | -                | -         |     0.83 | aliStair, dexter, INS, Liazz, Vexite |
|           18 |     3590 | 2024-03-13 | Rooster            | W   | 0.240      | -            | -                | -                | -         |     0.83 | aliStair, dexter, INS, Liazz, Vexite |
|           17 |     3759 | 2024-03-06 | DXA                | W   | 0.194      | -            | -                | -                | -         |     0.40 | aliStair, dexter, INS, Liazz, Vexite |
|           16 |     3761 | 2024-03-06 | DXA                | W   | 0.193      | -            | -                | -                | -         |     0.41 | aliStair, dexter, INS, Liazz, Vexite |
|           15 |     3909 | 2024-02-27 | Lynn Vision        | L   | 0.146      | -            | -                | -                | -         |    -3.37 | aliStair, dexter, INS, Liazz, Vexite |
|           14 |     3910 | 2024-02-27 | ATOX               | W   | 0.145      | -            | -                | -                | 1 (0.145) |     0.74 | aliStair, dexter, INS, Liazz, Vexite |
|           13 |     3931 | 2024-02-27 | JiJieHao           | W   | 0.140      | -            | -                | -                | 1 (0.140) |     0.07 | aliStair, dexter, INS, Liazz, Vexite |
|           12 |     3947 | 2024-02-25 | The MongolZ        | L   | 0.132      | -            | -                | -                | -         |    -0.05 | aliStair, dexter, INS, Liazz, Vexite |
|           11 |     3950 | 2024-02-25 | ATOX               | W   | 0.131      | -            | -                | -                | 1 (0.131) |     0.67 | aliStair, dexter, INS, Liazz, Vexite |
|           10 |     4012 | 2024-02-23 | Rooster            | W   | 0.113      | -            | -                | -                | -         |     0.38 | aliStair, dexter, INS, Liazz, Vexite |
|            9 |     4031 | 2024-02-22 | Rooster            | W   | 0.107      | -            | -                | -                | -         |     0.36 | aliStair, dexter, INS, Liazz, Vexite |
|            8 |     4035 | 2024-02-21 | Bad News Kangaroos | W   | 0.105      | -            | -                | -                | -         |     0.33 | aliStair, dexter, INS, Liazz, Vexite |
|            7 |     4058 | 2024-02-21 | Bad News Kangaroos | W   | 0.100      | -            | -                | -                | -         |     0.31 | aliStair, dexter, INS, Liazz, Vexite |
|            6 |     4062 | 2024-02-21 | Bad News Kangaroos | W   | 0.100      | -            | -                | -                | -         |     0.31 | aliStair, dexter, INS, Liazz, Vexite |
|            5 |     4117 | 2024-02-18 | Mindfreak          | W   | 0.086      | -            | -                | -                | -         |     0.18 | aliStair, dexter, INS, Liazz, Vexite |
|            4 |     4135 | 2024-02-18 | Arcade             | W   | 0.080      | -            | -                | -                | -         |     0.15 | aliStair, dexter, INS, Liazz, Vexite |
|            3 |     4139 | 2024-02-18 | MANTRA             | W   | 0.080      | -            | -                | -                | -         |     0.04 | aliStair, dexter, INS, Liazz, Vexite |
|            2 |     4140 | 2024-02-17 | Arcade             | W   | 0.077      | -            | -                | -                | -         |     0.15 | aliStair, dexter, INS, Liazz, Vexite |
|            1 |     4162 | 2024-02-16 | GR                 | W   | 0.072      | -            | -                | -                | -         |     0.14 | aliStair, dexter, INS, Liazz, Vexite |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($33,818.68)
- Divide that value by the 5th highest value among all rosters ($324,557.31)
- The final value (0.10) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-21 |      1.000 | $10,000.00     | $10,000.00      |
| 2024-06-08 |      0.826 | $3,250.00      | $2,683.06       |
| 2024-06-02 |      0.782 | $4,000.00      | $3,128.89       |
| 2024-05-12 |      0.641 | $23,500.00     | $15,072.64      |
| 2024-04-14 |      0.453 | $6,000.00      | $2,720.97       |
| 2024-02-17 |      0.077 | $2,750.00      | $213.13         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
