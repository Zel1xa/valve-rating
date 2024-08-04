### Roster Details<br />
Team Name: ECLOT<br />
Roster: Blytz, Dytor, forsyy, kreaz, nbqq<br />
Global Rank: [47](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [34]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1087.2<br />
<br />
Final Rank Value (1087.2) = Starting Rank Value (1220.9) + Head To Head Adjustments (-133.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.453[<sup>1</sup>](#table2)
- Bounty Collected: 0.352[<sup>2</sup>](#table1)
- Opponent Network: 0.216[<sup>2</sup>](#table1)
- LAN Wins: 0.584[<sup>2</sup>](#table1)

The average of these factors is 0.401<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1220.9
- 400 + ( ( 0.401 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 1220.9


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent        | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                            |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           57 |       35 | 2024-08-03 | AVEZ            | W   | 1.000      | -            | -                | -                | 1 (1.000) |     3.51 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           56 |       67 | 2024-08-02 | SINNERS         | W   | 1.000      | 0.345        | 0.037 (0.013)    | 0.797 (0.275)    | 1 (1.000) |    11.06 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           55 |      211 | 2024-07-30 | 1WIN            | W   | 1.000      | -            | -                | -                | 0 (0.000) |    12.22 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           54 |      254 | 2024-07-29 | DASH            | L   | 1.000      | -            | -                | -                | -         |   -29.73 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           53 |      368 | 2024-07-25 | HAVU            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.40 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           52 |      739 | 2024-07-16 | FAVBET          | L   | 1.000      | -            | -                | -                | -         |   -25.44 | Dytor, forsyy, kreaz, nbqq, olik  |
|           51 |      795 | 2024-07-14 | The Suspect     | L   | 1.000      | -            | -                | -                | -         |   -25.51 | Dytor, forsyy, nbqq, NEOFRAG, PR  |
|           50 |      806 | 2024-07-14 | The Suspect     | W   | 1.000      | -            | -                | -                | -         |     5.04 | Dytor, forsyy, nbqq, NEOFRAG, PR  |
|           49 |      812 | 2024-07-13 | ALTERNATE aTTaX | W   | 1.000      | -            | -                | -                | -         |     6.13 | Dytor, forsyy, K1-FiDa, nbqq, PR  |
|           48 |      907 | 2024-07-08 | Hungary         | W   | 1.000      | -            | -                | -                | -         |     4.29 | Dytor, forsyy, K1-FiDa, nbqq, PR  |
|           47 |     1080 | 2024-06-14 | 5W              | L   | 0.859      | -            | -                | -                | -         |   -19.25 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           46 |     1149 | 2024-06-11 | PERA            | L   | 0.841      | -            | -                | -                | -         |   -19.96 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           45 |     1231 | 2024-06-09 | Enterprise      | W   | 0.826      | 0.450        | 0.039 (0.015)    | 0.625 (0.232)    | -         |     5.04 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           44 |     1305 | 2024-06-08 | MOUZ NXT        | W   | 0.819      | 0.450        | 0.139 (0.051)    | 1.000 (0.369)    | -         |    11.07 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           43 |     1365 | 2024-06-07 | GhoulsW         | W   | 0.812      | -            | -                | -                | -         |     0.39 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           42 |     1396 | 2024-06-06 | GamerLegion     | L   | 0.808      | -            | -                | -                | -         |   -12.20 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           41 |     1562 | 2024-06-02 | UNiTY           | W   | 0.780      | 0.346        | 0.025 (0.007)    | -                | 1 (0.780) |     6.56 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           40 |     1594 | 2024-06-01 | UNiTY           | W   | 0.774      | 0.346        | 0.025 (0.007)    | -                | 1 (0.774) |     6.69 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           39 |     1626 | 2024-05-31 | Sampi           | W   | 0.767      | 0.346        | 0.027 (0.007)    | 1.000 (0.265)    | 1 (0.767) |     5.07 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           38 |     1751 | 2024-05-26 | Permitta        | L   | 0.731      | -            | -                | -                | -         |   -18.31 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           37 |     1839 | 2024-05-22 | Preasy          | L   | 0.705      | -            | -                | -                | -         |   -19.93 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           36 |     2179 | 2024-05-13 | Johnny Speeds   | L   | 0.645      | -            | -                | -                | -         |    -7.59 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           35 |     2249 | 2024-05-10 | Verdant         | W   | 0.625      | -            | -                | -                | -         |     3.96 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           34 |     2442 | 2024-04-30 | MOUZ NXT        | L   | 0.561      | -            | -                | -                | -         |   -12.33 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           33 |     2469 | 2024-04-29 | 1WIN            | W   | 0.553      | 0.500        | 0.027 (0.007)    | 0.707 (0.196)    | -         |     3.40 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           32 |     2506 | 2024-04-27 | MOUZ NXT        | L   | 0.541      | -            | -                | -                | -         |   -12.28 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           31 |     2577 | 2024-04-25 | Sampi           | W   | 0.525      | 0.371        | -                | 1.000 (0.194)    | -         |     2.95 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           30 |     2615 | 2024-04-23 | Sampi           | W   | 0.512      | 0.371        | -                | 1.000 (0.190)    | -         |     2.83 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           29 |     2647 | 2024-04-21 | MOUZ NXT        | W   | 0.499      | 0.371        | 0.139 (0.026)    | 1.000 (0.185)    | -         |     4.75 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           28 |     2731 | 2024-04-19 | SINNERS         | W   | 0.485      | 0.371        | 0.037 (0.007)    | 0.797 (0.143)    | -         |     6.89 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           27 |     2813 | 2024-04-17 | Alliance        | W   | 0.472      | -            | -                | -                | -         |     2.05 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           26 |     2865 | 2024-04-15 | Astralis Talent | W   | 0.458      | -            | -                | -                | -         |     1.33 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           25 |     3036 | 2024-04-09 | ALTERNATE aTTaX | L   | 0.419      | -            | -                | -                | -         |   -10.32 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           24 |     3124 | 2024-04-05 | UNiTY           | L   | 0.391      | -            | -                | -                | -         |    -9.77 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           23 |     3171 | 2024-04-04 | PGE Turow       | W   | 0.385      | -            | -                | -                | -         |     0.56 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           22 |     3211 | 2024-04-03 | Permitta        | W   | 0.379      | 0.333        | -                | 0.876 (0.111)    | -         |     2.44 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           21 |     3497 | 2024-03-17 | SINNERS         | W   | 0.267      | -            | -                | -                | 1 (0.267) |     3.47 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           20 |     3515 | 2024-03-16 | UNiTY           | W   | 0.260      | -            | -                | -                | 1 (0.260) |     1.79 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           19 |     3536 | 2024-03-15 | Sampi           | W   | 0.253      | -            | -                | -                | 1 (0.253) |     1.30 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           18 |     3540 | 2024-03-15 | Sashi           | L   | 0.252      | -            | -                | -                | -         |    -4.73 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           17 |     3607 | 2024-03-13 | Permitta        | L   | 0.239      | -            | -                | -                | -         |    -6.00 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           16 |     3622 | 2024-03-13 | Permitta        | L   | 0.238      | -            | -                | -                | -         |    -6.05 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           15 |     3665 | 2024-03-11 | Entropiq        | L   | 0.225      | -            | -                | -                | -         |    -6.91 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           14 |     3683 | 2024-03-10 | Zero Tenacity   | L   | 0.219      | -            | -                | -                | -         |    -4.58 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           13 |     3826 | 2024-03-05 | 9INE            | W   | 0.186      | -            | -                | -                | -         |     0.10 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           12 |     3870 | 2024-03-03 | Metizport       | W   | 0.173      | -            | -                | -                | -         |     0.57 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           11 |     3911 | 2024-03-01 | Viperio         | W   | 0.158      | -            | -                | -                | -         |     0.05 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           10 |     3939 | 2024-02-28 | Permitta        | W   | 0.145      | -            | -                | -                | -         |     0.83 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            9 |     3957 | 2024-02-27 | MOUZ NXT        | W   | 0.139      | 0.333        | 0.139 (0.006)    | -                | -         |     1.22 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            8 |     3959 | 2024-02-27 | ex-sYnck        | W   | 0.139      | -            | -                | -                | -         |     0.07 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            7 |     3976 | 2024-02-26 | PGE Turow       | W   | 0.132      | -            | -                | -                | -         |     0.17 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            6 |     3998 | 2024-02-25 | Sampi           | W   | 0.125      | -            | -                | -                | -         |     0.54 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            5 |     4031 | 2024-02-24 | Permitta        | L   | 0.119      | -            | -                | -                | -         |    -3.08 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            4 |     4060 | 2024-02-22 | BIG Academy     | W   | 0.106      | -            | -                | -                | -         |     0.03 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            3 |     4098 | 2024-02-21 | Permitta        | W   | 0.098      | -            | -                | -                | -         |     0.55 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            2 |     4115 | 2024-02-20 | NAVI Junior     | W   | 0.092      | -            | -                | -                | -         |     0.14 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            1 |     4143 | 2024-02-19 | Permitta        | L   | 0.086      | -            | -                | -                | -         |    -2.23 | Blytz, Dytor, forsyy, kreaz, nbqq |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($20,197.94)
- Divide that value by the 5th highest value among all rosters ($324,118.06)
- The final value (0.06) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-17 |      0.879 | $2,500.00      | $2,196.99       |
| 2024-06-13 |      0.854 | $545.00        | $465.57         |
| 2024-06-02 |      0.780 | $7,837.00      | $6,113.95       |
| 2024-05-13 |      0.645 | $3,000.00      | $1,933.89       |
| 2024-04-25 |      0.525 | $11,000.00     | $5,770.93       |
| 2024-04-06 |      0.398 | $1,500.00      | $596.94         |
| 2024-03-17 |      0.267 | $7,675.00      | $2,051.29       |
| 2024-02-28 |      0.145 | $5,000.00      | $724.54         |
| 2024-02-21 |      0.098 | $3,500.00      | $343.84         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
