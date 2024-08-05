### Roster Details<br />
Team Name: ECLOT<br />
Roster: Blytz, Dytor, forsyy, kreaz, nbqq<br />
Global Rank: [48](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [35]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1088.6<br />
<br />
Final Rank Value (1088.6) = Starting Rank Value (1220.0) + Head To Head Adjustments (-131.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.453[<sup>1</sup>](#table2)
- Bounty Collected: 0.352[<sup>2</sup>](#table1)
- Opponent Network: 0.213[<sup>2</sup>](#table1)
- LAN Wins: 0.582[<sup>2</sup>](#table1)

The average of these factors is 0.400<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1220.0
- 400 + ( ( 0.400 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 1220.0


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
|           57 |       61 | 2024-08-03 | AVEZ            | W   | 1.000      | -            | -                | -                | 1 (1.000) |     3.51 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           56 |       93 | 2024-08-02 | SINNERS         | W   | 1.000      | 0.345        | 0.037 (0.013)    | 0.809 (0.279)    | 1 (1.000) |    11.17 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           55 |      237 | 2024-07-30 | 1WIN            | W   | 1.000      | -            | -                | -                | 0 (0.000) |    12.37 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           54 |      280 | 2024-07-29 | DASH            | L   | 1.000      | -            | -                | -                | -         |   -29.74 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           53 |      394 | 2024-07-25 | HAVU            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.38 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           52 |      765 | 2024-07-16 | FAVBET          | L   | 1.000      | -            | -                | -                | -         |   -25.39 | Dytor, forsyy, kreaz, nbqq, olik  |
|           51 |      821 | 2024-07-14 | The Suspect     | L   | 1.000      | -            | -                | -                | -         |   -25.54 | Dytor, forsyy, nbqq, NEOFRAG, PR  |
|           50 |      832 | 2024-07-14 | The Suspect     | W   | 1.000      | -            | -                | -                | -         |     5.02 | Dytor, forsyy, nbqq, NEOFRAG, PR  |
|           49 |      838 | 2024-07-13 | ALTERNATE aTTaX | W   | 1.000      | -            | -                | -                | -         |     6.14 | Dytor, forsyy, K1-FiDa, nbqq, PR  |
|           48 |      933 | 2024-07-08 | Hungary         | W   | 1.000      | -            | -                | -                | -         |     4.27 | Dytor, forsyy, K1-FiDa, nbqq, PR  |
|           47 |     1106 | 2024-06-14 | 5W              | L   | 0.852      | -            | -                | -                | -         |   -19.14 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           46 |     1175 | 2024-06-11 | PERA            | L   | 0.834      | -            | -                | -                | -         |   -19.83 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           45 |     1257 | 2024-06-09 | Enterprise      | W   | 0.819      | 0.450        | 0.039 (0.014)    | 0.616 (0.227)    | -         |     5.03 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           44 |     1331 | 2024-06-08 | MOUZ NXT        | W   | 0.812      | 0.450        | 0.139 (0.051)    | 0.987 (0.361)    | -         |    11.07 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           43 |     1391 | 2024-06-07 | GhoulsW         | W   | 0.804      | -            | -                | -                | -         |     0.38 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           42 |     1422 | 2024-06-06 | GamerLegion     | L   | 0.800      | -            | -                | -                | -         |   -12.14 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           41 |     1588 | 2024-06-02 | UNiTY           | W   | 0.773      | 0.346        | 0.025 (0.007)    | -                | 1 (0.773) |     6.51 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           40 |     1620 | 2024-06-01 | UNiTY           | W   | 0.766      | 0.346        | 0.025 (0.007)    | -                | 1 (0.766) |     6.63 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           39 |     1652 | 2024-05-31 | Sampi           | W   | 0.760      | 0.346        | 0.027 (0.007)    | 1.000 (0.263)    | 1 (0.760) |     5.00 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           38 |     1777 | 2024-05-26 | Permitta        | L   | 0.724      | -            | -                | -                | -         |   -18.12 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           37 |     1865 | 2024-05-22 | Preasy          | L   | 0.698      | -            | -                | -                | -         |   -19.78 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           36 |     2205 | 2024-05-13 | Johnny Speeds   | L   | 0.637      | -            | -                | -                | -         |    -7.49 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           35 |     2275 | 2024-05-10 | Verdant         | W   | 0.618      | -            | -                | -                | -         |     3.92 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           34 |     2468 | 2024-04-30 | MOUZ NXT        | L   | 0.554      | -            | -                | -                | -         |   -12.13 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           33 |     2495 | 2024-04-29 | 1WIN            | W   | 0.546      | 0.500        | 0.033 (0.009)    | 0.696 (0.190)    | -         |     3.45 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           32 |     2532 | 2024-04-27 | MOUZ NXT        | L   | 0.534      | -            | -                | -                | -         |   -12.07 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           31 |     2603 | 2024-04-25 | Sampi           | W   | 0.517      | 0.371        | -                | 1.000 (0.192)    | -         |     2.88 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           30 |     2641 | 2024-04-23 | Sampi           | W   | 0.505      | 0.371        | -                | 1.000 (0.187)    | -         |     2.77 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           29 |     2673 | 2024-04-21 | MOUZ NXT        | W   | 0.492      | 0.371        | 0.139 (0.025)    | 0.987 (0.180)    | -         |     4.73 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           28 |     2757 | 2024-04-19 | SINNERS         | W   | 0.477      | 0.371        | 0.037 (0.007)    | 0.809 (0.143)    | -         |     6.90 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           27 |     2839 | 2024-04-17 | Alliance        | W   | 0.465      | -            | -                | -                | -         |     2.02 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           26 |     2891 | 2024-04-15 | Astralis Talent | W   | 0.451      | -            | -                | -                | -         |     1.29 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           25 |     3062 | 2024-04-09 | ALTERNATE aTTaX | L   | 0.412      | -            | -                | -                | -         |   -10.14 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           24 |     3150 | 2024-04-05 | UNiTY           | L   | 0.384      | -            | -                | -                | -         |    -9.58 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           23 |     3197 | 2024-04-04 | PGE Turow       | W   | 0.378      | -            | -                | -                | -         |     0.55 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           22 |     3237 | 2024-04-03 | Permitta        | W   | 0.372      | 0.333        | -                | 0.863 (0.107)    | -         |     2.40 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           21 |     3523 | 2024-03-17 | SINNERS         | W   | 0.260      | -            | -                | -                | 1 (0.260) |     3.45 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           20 |     3541 | 2024-03-16 | UNiTY           | W   | 0.253      | -            | -                | -                | 1 (0.253) |     1.74 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           19 |     3562 | 2024-03-15 | Sampi           | W   | 0.246      | -            | -                | -                | 1 (0.246) |     1.25 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           18 |     3566 | 2024-03-15 | Sashi           | L   | 0.245      | -            | -                | -                | -         |    -4.58 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           17 |     3633 | 2024-03-13 | Permitta        | L   | 0.232      | -            | -                | -                | -         |    -5.82 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           16 |     3648 | 2024-03-13 | Permitta        | L   | 0.231      | -            | -                | -                | -         |    -5.87 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           15 |     3691 | 2024-03-11 | Entropiq        | L   | 0.218      | -            | -                | -                | -         |    -6.69 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           14 |     3709 | 2024-03-10 | Zero Tenacity   | L   | 0.212      | -            | -                | -                | -         |    -4.38 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           13 |     3852 | 2024-03-05 | 9INE            | W   | 0.178      | -            | -                | -                | -         |     0.10 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           12 |     3896 | 2024-03-03 | Metizport       | W   | 0.166      | -            | -                | -                | -         |     0.55 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           11 |     3937 | 2024-03-01 | Viperio         | W   | 0.151      | -            | -                | -                | -         |     0.05 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           10 |     3965 | 2024-02-28 | Permitta        | W   | 0.138      | -            | -                | -                | -         |     0.79 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            9 |     3983 | 2024-02-27 | MOUZ NXT        | W   | 0.132      | 0.333        | 0.139 (0.006)    | -                | -         |     1.17 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            8 |     3985 | 2024-02-27 | ex-sYnck        | W   | 0.131      | -            | -                | -                | -         |     0.07 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            7 |     4002 | 2024-02-26 | PGE Turow       | W   | 0.124      | -            | -                | -                | -         |     0.16 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            6 |     4024 | 2024-02-25 | Sampi           | W   | 0.118      | -            | -                | -                | -         |     0.50 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            5 |     4057 | 2024-02-24 | Permitta        | L   | 0.112      | -            | -                | -                | -         |    -2.89 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            4 |     4086 | 2024-02-22 | BIG Academy     | W   | 0.099      | -            | -                | -                | -         |     0.03 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            3 |     4124 | 2024-02-21 | Permitta        | W   | 0.091      | -            | -                | -                | -         |     0.52 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            2 |     4141 | 2024-02-20 | NAVI Junior     | W   | 0.085      | -            | -                | -                | -         |     0.13 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            1 |     4169 | 2024-02-19 | Permitta        | L   | 0.079      | -            | -                | -                | -         |    -2.04 | Blytz, Dytor, forsyy, kreaz, nbqq |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($19,894.52)
- Divide that value by the 5th highest value among all rosters ($322,004.12)
- The final value (0.06) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-17 |      0.872 | $2,500.00      | $2,179.17       |
| 2024-06-13 |      0.847 | $545.00        | $461.69         |
| 2024-06-02 |      0.773 | $7,837.00      | $6,058.07       |
| 2024-05-13 |      0.637 | $3,000.00      | $1,912.50       |
| 2024-04-25 |      0.517 | $11,000.00     | $5,692.50       |
| 2024-04-06 |      0.391 | $1,500.00      | $586.25         |
| 2024-03-17 |      0.260 | $7,675.00      | $1,996.57       |
| 2024-02-28 |      0.138 | $5,000.00      | $688.89         |
| 2024-02-21 |      0.091 | $3,500.00      | $318.89         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
