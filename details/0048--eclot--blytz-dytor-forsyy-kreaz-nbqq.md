### Roster Details<br />
Team Name: ECLOT<br />
Roster: Blytz, Dytor, forsyy, kreaz, nbqq<br />
Global Rank: [48](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [35]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1089.1<br />
<br />
Final Rank Value (1089.1) = Starting Rank Value (1220.1) + Head To Head Adjustments (-131.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.453[<sup>1</sup>](#table2)
- Bounty Collected: 0.352[<sup>2</sup>](#table1)
- Opponent Network: 0.213[<sup>2</sup>](#table1)
- LAN Wins: 0.582[<sup>2</sup>](#table1)

The average of these factors is 0.400<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1220.1
- 400 + ( ( 0.400 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 1220.1


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
|           57 |       62 | 2024-08-03 | AVEZ            | W   | 1.000      | -            | -                | -                | 1 (1.000) |     3.50 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           56 |       94 | 2024-08-02 | SINNERS         | W   | 1.000      | 0.345        | 0.037 (0.013)    | 0.809 (0.279)    | 1 (1.000) |    11.16 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           55 |      238 | 2024-07-30 | 1WIN            | W   | 1.000      | -            | -                | -                | 0 (0.000) |    12.38 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           54 |      281 | 2024-07-29 | DASH            | L   | 1.000      | -            | -                | -                | -         |   -29.74 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           53 |      395 | 2024-07-25 | HAVU            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.37 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           52 |      766 | 2024-07-16 | FAVBET          | L   | 1.000      | -            | -                | -                | -         |   -25.40 | Dytor, forsyy, kreaz, nbqq, olik  |
|           51 |      822 | 2024-07-14 | The Suspect     | L   | 1.000      | -            | -                | -                | -         |   -25.55 | Dytor, forsyy, nbqq, NEOFRAG, PR  |
|           50 |      833 | 2024-07-14 | The Suspect     | W   | 1.000      | -            | -                | -                | -         |     5.00 | Dytor, forsyy, nbqq, NEOFRAG, PR  |
|           49 |      839 | 2024-07-13 | ALTERNATE aTTaX | W   | 1.000      | -            | -                | -                | -         |     6.13 | Dytor, forsyy, K1-FiDa, nbqq, PR  |
|           48 |      934 | 2024-07-08 | Hungary         | W   | 1.000      | -            | -                | -                | -         |     4.25 | Dytor, forsyy, K1-FiDa, nbqq, PR  |
|           47 |     1107 | 2024-06-14 | 5W              | L   | 0.852      | -            | -                | -                | -         |   -19.15 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           46 |     1176 | 2024-06-11 | PERA            | L   | 0.833      | -            | -                | -                | -         |   -19.84 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           45 |     1258 | 2024-06-09 | Enterprise      | W   | 0.818      | 0.450        | 0.039 (0.014)    | 0.616 (0.227)    | -         |     5.04 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           44 |     1332 | 2024-06-08 | MOUZ NXT        | W   | 0.812      | 0.450        | 0.139 (0.051)    | 0.987 (0.361)    | -         |    11.05 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           43 |     1392 | 2024-06-07 | GhoulsW         | W   | 0.804      | -            | -                | -                | -         |     0.38 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           42 |     1423 | 2024-06-06 | GamerLegion     | L   | 0.800      | -            | -                | -                | -         |   -12.16 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           41 |     1589 | 2024-06-02 | UNiTY           | W   | 0.773      | 0.346        | 0.025 (0.007)    | -                | 1 (0.773) |     6.49 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           40 |     1621 | 2024-06-01 | UNiTY           | W   | 0.766      | 0.346        | 0.025 (0.007)    | -                | 1 (0.766) |     6.61 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           39 |     1653 | 2024-05-31 | Sampi           | W   | 0.760      | 0.346        | 0.027 (0.007)    | 1.000 (0.263)    | 1 (0.760) |     5.00 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           38 |     1778 | 2024-05-26 | Permitta        | L   | 0.724      | -            | -                | -                | -         |   -17.99 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           37 |     1866 | 2024-05-22 | Preasy          | L   | 0.698      | -            | -                | -                | -         |   -19.77 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           36 |     2206 | 2024-05-13 | Johnny Speeds   | L   | 0.637      | -            | -                | -                | -         |    -7.49 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           35 |     2276 | 2024-05-10 | Verdant         | W   | 0.618      | -            | -                | -                | -         |     3.91 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           34 |     2469 | 2024-04-30 | MOUZ NXT        | L   | 0.553      | -            | -                | -                | -         |   -12.13 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           33 |     2496 | 2024-04-29 | 1WIN            | W   | 0.546      | 0.500        | 0.033 (0.009)    | 0.696 (0.190)    | -         |     3.46 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           32 |     2533 | 2024-04-27 | MOUZ NXT        | L   | 0.533      | -            | -                | -                | -         |   -12.06 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           31 |     2604 | 2024-04-25 | Sampi           | W   | 0.517      | 0.371        | -                | 1.000 (0.192)    | -         |     2.89 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           30 |     2642 | 2024-04-23 | Sampi           | W   | 0.504      | 0.371        | -                | 1.000 (0.187)    | -         |     2.77 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           29 |     2674 | 2024-04-21 | MOUZ NXT        | W   | 0.491      | 0.371        | 0.139 (0.025)    | 0.987 (0.180)    | -         |     4.72 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           28 |     2758 | 2024-04-19 | SINNERS         | W   | 0.477      | 0.371        | 0.037 (0.007)    | 0.809 (0.143)    | -         |     6.88 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           27 |     2840 | 2024-04-17 | Alliance        | W   | 0.464      | -            | -                | -                | -         |     2.01 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           26 |     2892 | 2024-04-15 | Astralis Talent | W   | 0.450      | -            | -                | -                | -         |     1.29 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           25 |     3063 | 2024-04-09 | ALTERNATE aTTaX | L   | 0.411      | -            | -                | -                | -         |   -10.14 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           24 |     3151 | 2024-04-05 | UNiTY           | L   | 0.384      | -            | -                | -                | -         |    -9.58 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           23 |     3198 | 2024-04-04 | PGE Turow       | W   | 0.377      | -            | -                | -                | -         |     0.54 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           22 |     3238 | 2024-04-03 | Permitta        | W   | 0.371      | 0.333        | -                | 0.902 (0.112)    | -         |     2.53 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           21 |     3524 | 2024-03-17 | SINNERS         | W   | 0.260      | -            | -                | -                | 1 (0.260) |     3.44 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           20 |     3542 | 2024-03-16 | UNiTY           | W   | 0.253      | -            | -                | -                | 1 (0.253) |     1.73 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           19 |     3563 | 2024-03-15 | Sampi           | W   | 0.245      | -            | -                | -                | 1 (0.245) |     1.25 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           18 |     3567 | 2024-03-15 | Sashi           | L   | 0.244      | -            | -                | -                | -         |    -4.58 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           17 |     3634 | 2024-03-13 | Permitta        | L   | 0.232      | -            | -                | -                | -         |    -5.72 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           16 |     3649 | 2024-03-13 | Permitta        | L   | 0.231      | -            | -                | -                | -         |    -5.77 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           15 |     3692 | 2024-03-11 | Entropiq        | L   | 0.217      | -            | -                | -                | -         |    -6.68 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           14 |     3710 | 2024-03-10 | Zero Tenacity   | L   | 0.212      | -            | -                | -                | -         |    -4.38 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           13 |     3853 | 2024-03-05 | 9INE            | W   | 0.178      | -            | -                | -                | -         |     0.10 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           12 |     3897 | 2024-03-03 | Metizport       | W   | 0.165      | -            | -                | -                | -         |     0.54 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           11 |     3938 | 2024-03-01 | Viperio         | W   | 0.151      | -            | -                | -                | -         |     0.05 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           10 |     3966 | 2024-02-28 | Permitta        | W   | 0.137      | -            | -                | -                | -         |     0.85 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            9 |     3984 | 2024-02-27 | MOUZ NXT        | W   | 0.132      | 0.333        | 0.139 (0.006)    | -                | -         |     1.17 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            8 |     3986 | 2024-02-27 | ex-sYnck        | W   | 0.131      | -            | -                | -                | -         |     0.07 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            7 |     4003 | 2024-02-26 | PGE Turow       | W   | 0.124      | -            | -                | -                | -         |     0.16 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            6 |     4025 | 2024-02-25 | Sampi           | W   | 0.117      | -            | -                | -                | -         |     0.50 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            5 |     4058 | 2024-02-24 | Permitta        | L   | 0.111      | -            | -                | -                | -         |    -2.83 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            4 |     4087 | 2024-02-22 | BIG Academy     | W   | 0.098      | -            | -                | -                | -         |     0.03 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            3 |     4125 | 2024-02-21 | Permitta        | W   | 0.091      | -            | -                | -                | -         |     0.55 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            2 |     4142 | 2024-02-20 | NAVI Junior     | W   | 0.085      | -            | -                | -                | -         |     0.13 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            1 |     4170 | 2024-02-19 | Permitta        | L   | 0.078      | -            | -                | -                | -         |    -2.00 | Blytz, Dytor, forsyy, kreaz, nbqq |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($19,876.79)
- Divide that value by the 5th highest value among all rosters ($321,880.58)
- The final value (0.06) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-17 |      0.871 | $2,500.00      | $2,178.13       |
| 2024-06-13 |      0.847 | $545.00        | $461.46         |
| 2024-06-02 |      0.773 | $7,837.00      | $6,054.81       |
| 2024-05-13 |      0.637 | $3,000.00      | $1,911.25       |
| 2024-04-25 |      0.517 | $11,000.00     | $5,687.92       |
| 2024-04-06 |      0.390 | $1,500.00      | $585.63         |
| 2024-03-17 |      0.260 | $7,675.00      | $1,993.37       |
| 2024-02-28 |      0.137 | $5,000.00      | $686.81         |
| 2024-02-21 |      0.091 | $3,500.00      | $317.43         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
