### Roster Details<br />
Team Name: ECLOT<br />
Roster: Blytz, Dytor, forsyy, kreaz, nbqq<br />
Global Rank: [48](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [35]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1091.0<br />
<br />
Final Rank Value (1091.0) = Starting Rank Value (1220.3) + Head To Head Adjustments (-129.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.452[<sup>1</sup>](#table2)
- Bounty Collected: 0.352[<sup>2</sup>](#table1)
- Opponent Network: 0.211[<sup>2</sup>](#table1)
- LAN Wins: 0.580[<sup>2</sup>](#table1)

The average of these factors is 0.399<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1220.3
- 400 + ( ( 0.399 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1220.3


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
|           57 |       81 | 2024-08-03 | AVEZ            | W   | 1.000      | -            | -                | -                | 1 (1.000) |     3.49 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           56 |      113 | 2024-08-02 | SINNERS         | W   | 1.000      | 0.345        | 0.037 (0.013)    | 0.800 (0.276)    | 1 (1.000) |    11.17 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           55 |      256 | 2024-07-30 | 1WIN            | W   | 1.000      | -            | -                | -                | 0 (0.000) |    12.37 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           54 |      300 | 2024-07-29 | DASH            | L   | 1.000      | -            | -                | -                | -         |   -29.76 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           53 |      414 | 2024-07-25 | HAVU            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.34 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           52 |      785 | 2024-07-16 | FAVBET          | L   | 1.000      | -            | -                | -                | -         |   -25.38 | Dytor, forsyy, kreaz, nbqq, olik  |
|           51 |      841 | 2024-07-14 | The Suspect     | L   | 1.000      | -            | -                | -                | -         |   -25.58 | Dytor, forsyy, nbqq, NEOFRAG, PR  |
|           50 |      852 | 2024-07-14 | The Suspect     | W   | 1.000      | -            | -                | -                | -         |     4.97 | Dytor, forsyy, nbqq, NEOFRAG, PR  |
|           49 |      858 | 2024-07-13 | ALTERNATE aTTaX | W   | 1.000      | -            | -                | -                | -         |     6.15 | Dytor, forsyy, K1-FiDa, nbqq, PR  |
|           48 |      953 | 2024-07-08 | Hungary         | W   | 1.000      | -            | -                | -                | -         |     4.22 | Dytor, forsyy, K1-FiDa, nbqq, PR  |
|           47 |     1126 | 2024-06-14 | 5W              | L   | 0.846      | -            | -                | -                | -         |   -19.06 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           46 |     1195 | 2024-06-11 | PERA            | L   | 0.828      | -            | -                | -                | -         |   -19.75 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           45 |     1277 | 2024-06-09 | Enterprise      | W   | 0.813      | 0.450        | 0.039 (0.014)    | 0.641 (0.234)    | -         |     5.01 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           44 |     1351 | 2024-06-08 | MOUZ NXT        | W   | 0.806      | 0.450        | 0.139 (0.050)    | 0.962 (0.349)    | -         |    11.02 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           43 |     1411 | 2024-06-07 | GhoulsW         | W   | 0.798      | -            | -                | -                | -         |     0.37 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           42 |     1442 | 2024-06-06 | GamerLegion     | L   | 0.794      | -            | -                | -                | -         |   -12.20 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           41 |     1608 | 2024-06-02 | UNiTY           | W   | 0.767      | 0.346        | 0.024 (0.006)    | -                | 1 (0.767) |     6.38 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           40 |     1640 | 2024-06-01 | UNiTY           | W   | 0.760      | 0.346        | 0.024 (0.006)    | -                | 1 (0.760) |     6.49 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           39 |     1672 | 2024-05-31 | Sampi           | W   | 0.754      | 0.346        | 0.027 (0.007)    | 1.000 (0.261)    | 1 (0.754) |     4.94 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           38 |     1797 | 2024-05-26 | Permitta        | L   | 0.718      | -            | -                | -                | -         |   -17.69 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           37 |     1885 | 2024-05-22 | Preasy          | L   | 0.692      | -            | -                | -                | -         |   -19.63 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           36 |     2225 | 2024-05-13 | Johnny Speeds   | L   | 0.631      | -            | -                | -                | -         |    -7.38 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           35 |     2295 | 2024-05-10 | Verdant         | W   | 0.612      | -            | -                | -                | -         |     3.87 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           34 |     2488 | 2024-04-30 | MOUZ NXT        | L   | 0.547      | -            | -                | -                | -         |   -12.03 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           33 |     2515 | 2024-04-29 | 1WIN            | W   | 0.540      | 0.500        | 0.033 (0.009)    | 0.718 (0.194)    | -         |     3.41 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           32 |     2552 | 2024-04-27 | MOUZ NXT        | L   | 0.527      | -            | -                | -                | -         |   -11.95 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           31 |     2623 | 2024-04-25 | Sampi           | W   | 0.511      | 0.371        | -                | 1.000 (0.189)    | -         |     2.84 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           30 |     2661 | 2024-04-23 | Sampi           | W   | 0.498      | 0.371        | -                | 1.000 (0.185)    | -         |     2.72 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           29 |     2693 | 2024-04-21 | MOUZ NXT        | W   | 0.485      | 0.371        | 0.139 (0.025)    | 0.962 (0.173)    | -         |     4.65 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           28 |     2777 | 2024-04-19 | SINNERS         | W   | 0.471      | 0.371        | 0.037 (0.006)    | 0.800 (0.140)    | -         |     6.77 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           27 |     2859 | 2024-04-17 | Alliance        | W   | 0.459      | -            | -                | -                | -         |     1.97 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           26 |     2911 | 2024-04-15 | Astralis Talent | W   | 0.445      | -            | -                | -                | -         |     1.26 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           25 |     3082 | 2024-04-09 | ALTERNATE aTTaX | L   | 0.406      | -            | -                | -                | -         |   -10.00 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           24 |     3170 | 2024-04-05 | UNiTY           | L   | 0.378      | -            | -                | -                | -         |    -9.46 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           23 |     3217 | 2024-04-04 | PGE Turow       | W   | 0.371      | -            | -                | -                | -         |     0.53 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           22 |     3257 | 2024-04-03 | Permitta        | W   | 0.365      | 0.333        | -                | 0.919 (0.112)    | -         |     2.67 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           21 |     3543 | 2024-03-17 | SINNERS         | W   | 0.254      | -            | -                | -                | 1 (0.254) |     3.36 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           20 |     3561 | 2024-03-16 | UNiTY           | W   | 0.247      | -            | -                | -                | 1 (0.247) |     1.68 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           19 |     3582 | 2024-03-15 | Sampi           | W   | 0.240      | -            | -                | -                | 1 (0.240) |     1.21 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           18 |     3586 | 2024-03-15 | Sashi           | L   | 0.239      | -            | -                | -                | -         |    -4.47 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           17 |     3653 | 2024-03-13 | Permitta        | L   | 0.226      | -            | -                | -                | -         |    -5.46 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           16 |     3668 | 2024-03-13 | Permitta        | L   | 0.225      | -            | -                | -                | -         |    -5.51 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           15 |     3711 | 2024-03-11 | Entropiq        | L   | 0.212      | -            | -                | -                | -         |    -6.50 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           14 |     3729 | 2024-03-10 | Zero Tenacity   | L   | 0.206      | -            | -                | -                | -         |    -4.27 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           13 |     3872 | 2024-03-05 | 9INE            | W   | 0.172      | -            | -                | -                | -         |     0.10 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           12 |     3916 | 2024-03-03 | Metizport       | W   | 0.159      | -            | -                | -                | -         |     0.74 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           11 |     3957 | 2024-03-01 | Viperio         | W   | 0.145      | -            | -                | -                | -         |     0.05 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           10 |     3985 | 2024-02-28 | Permitta        | W   | 0.132      | -            | -                | -                | -         |     0.88 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            9 |     4003 | 2024-02-27 | MOUZ NXT        | W   | 0.126      | 0.333        | 0.139 (0.006)    | -                | -         |     1.11 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            8 |     4005 | 2024-02-27 | ex-sYnck        | W   | 0.125      | -            | -                | -                | -         |     0.07 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            7 |     4022 | 2024-02-26 | PGE Turow       | W   | 0.118      | -            | -                | -                | -         |     0.15 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            6 |     4044 | 2024-02-25 | Sampi           | W   | 0.112      | -            | -                | -                | -         |     0.48 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            5 |     4077 | 2024-02-24 | Permitta        | L   | 0.106      | -            | -                | -                | -         |    -2.63 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            4 |     4106 | 2024-02-22 | BIG Academy     | W   | 0.092      | -            | -                | -                | -         |     0.03 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            3 |     4144 | 2024-02-21 | Permitta        | W   | 0.085      | -            | -                | -                | -         |     0.56 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            2 |     4161 | 2024-02-20 | NAVI Junior     | W   | 0.079      | -            | -                | -                | -         |     0.14 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            1 |     4189 | 2024-02-19 | Permitta        | L   | 0.072      | -            | -                | -                | -         |    -1.81 | Blytz, Dytor, forsyy, kreaz, nbqq |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($19,634.45)
- Divide that value by the 5th highest value among all rosters ($320,192.18)
- The final value (0.06) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-17 |      0.866 | $2,500.00      | $2,163.89       |
| 2024-06-13 |      0.841 | $545.00        | $458.36         |
| 2024-06-02 |      0.767 | $7,837.00      | $6,010.18       |
| 2024-05-13 |      0.631 | $3,000.00      | $1,894.17       |
| 2024-04-25 |      0.511 | $11,000.00     | $5,625.28       |
| 2024-04-06 |      0.385 | $1,500.00      | $577.08         |
| 2024-03-17 |      0.254 | $7,675.00      | $1,949.66       |
| 2024-02-28 |      0.132 | $5,000.00      | $658.33         |
| 2024-02-21 |      0.085 | $3,500.00      | $297.50         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
