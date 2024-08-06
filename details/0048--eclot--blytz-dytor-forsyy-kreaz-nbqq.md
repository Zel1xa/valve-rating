### Roster Details<br />
Team Name: ECLOT<br />
Roster: Blytz, Dytor, forsyy, kreaz, nbqq<br />
Global Rank: [48](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [35]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1090.0<br />
<br />
Final Rank Value (1090.0) = Starting Rank Value (1220.2) + Head To Head Adjustments (-130.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.452[<sup>1</sup>](#table2)
- Bounty Collected: 0.352[<sup>2</sup>](#table1)
- Opponent Network: 0.211[<sup>2</sup>](#table1)
- LAN Wins: 0.580[<sup>2</sup>](#table1)

The average of these factors is 0.399<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1220.2
- 400 + ( ( 0.399 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1220.2


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
|           57 |       72 | 2024-08-03 | AVEZ            | W   | 1.000      | -            | -                | -                | 1 (1.000) |     3.51 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           56 |      102 | 2024-08-02 | SINNERS         | W   | 1.000      | 0.345        | 0.037 (0.013)    | 0.790 (0.273)    | 1 (1.000) |    11.08 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           55 |      246 | 2024-07-30 | 1WIN            | W   | 1.000      | -            | -                | -                | 0 (0.000) |    12.36 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           54 |      289 | 2024-07-29 | DASH            | L   | 1.000      | -            | -                | -                | -         |   -29.75 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           53 |      403 | 2024-07-25 | HAVU            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.35 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           52 |      774 | 2024-07-16 | FAVBET          | L   | 1.000      | -            | -                | -                | -         |   -25.36 | Dytor, forsyy, kreaz, nbqq, olik  |
|           51 |      830 | 2024-07-14 | The Suspect     | L   | 1.000      | -            | -                | -                | -         |   -25.56 | Dytor, forsyy, nbqq, NEOFRAG, PR  |
|           50 |      841 | 2024-07-14 | The Suspect     | W   | 1.000      | -            | -                | -                | -         |     4.99 | Dytor, forsyy, nbqq, NEOFRAG, PR  |
|           49 |      847 | 2024-07-13 | ALTERNATE aTTaX | W   | 1.000      | -            | -                | -                | -         |     6.15 | Dytor, forsyy, K1-FiDa, nbqq, PR  |
|           48 |      942 | 2024-07-08 | Hungary         | W   | 1.000      | -            | -                | -                | -         |     4.25 | Dytor, forsyy, K1-FiDa, nbqq, PR  |
|           47 |     1115 | 2024-06-14 | 5W              | L   | 0.846      | -            | -                | -                | -         |   -19.07 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           46 |     1184 | 2024-06-11 | PERA            | L   | 0.828      | -            | -                | -                | -         |   -19.74 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           45 |     1266 | 2024-06-09 | Enterprise      | W   | 0.813      | 0.450        | 0.039 (0.014)    | 0.641 (0.234)    | -         |     5.01 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           44 |     1340 | 2024-06-08 | MOUZ NXT        | W   | 0.806      | 0.450        | 0.139 (0.050)    | 0.962 (0.349)    | -         |    10.94 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           43 |     1400 | 2024-06-07 | GhoulsW         | W   | 0.799      | -            | -                | -                | -         |     0.38 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           42 |     1431 | 2024-06-06 | GamerLegion     | L   | 0.795      | -            | -                | -                | -         |   -12.20 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           41 |     1597 | 2024-06-02 | UNiTY           | W   | 0.767      | 0.346        | 0.024 (0.006)    | -                | 1 (0.767) |     6.40 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           40 |     1629 | 2024-06-01 | UNiTY           | W   | 0.761      | 0.346        | 0.024 (0.006)    | -                | 1 (0.761) |     6.51 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           39 |     1661 | 2024-05-31 | Sampi           | W   | 0.754      | 0.346        | 0.027 (0.007)    | 1.000 (0.261)    | 1 (0.754) |     4.93 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           38 |     1786 | 2024-05-26 | Permitta        | L   | 0.719      | -            | -                | -                | -         |   -17.86 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           37 |     1874 | 2024-05-22 | Preasy          | L   | 0.693      | -            | -                | -                | -         |   -19.63 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           36 |     2214 | 2024-05-13 | Johnny Speeds   | L   | 0.632      | -            | -                | -                | -         |    -7.40 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           35 |     2284 | 2024-05-10 | Verdant         | W   | 0.613      | -            | -                | -                | -         |     3.89 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           34 |     2477 | 2024-04-30 | MOUZ NXT        | L   | 0.548      | -            | -                | -                | -         |   -12.03 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           33 |     2504 | 2024-04-29 | 1WIN            | W   | 0.540      | 0.500        | 0.033 (0.009)    | 0.718 (0.194)    | -         |     3.41 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           32 |     2541 | 2024-04-27 | MOUZ NXT        | L   | 0.528      | -            | -                | -                | -         |   -11.95 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           31 |     2612 | 2024-04-25 | Sampi           | W   | 0.512      | 0.371        | -                | 1.000 (0.190)    | -         |     2.84 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           30 |     2650 | 2024-04-23 | Sampi           | W   | 0.499      | 0.371        | -                | 1.000 (0.185)    | -         |     2.72 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           29 |     2682 | 2024-04-21 | MOUZ NXT        | W   | 0.486      | 0.371        | 0.139 (0.025)    | 0.962 (0.173)    | -         |     4.66 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           28 |     2766 | 2024-04-19 | SINNERS         | W   | 0.472      | 0.371        | 0.037 (0.006)    | 0.790 (0.138)    | -         |     6.78 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           27 |     2848 | 2024-04-17 | Alliance        | W   | 0.459      | -            | -                | -                | -         |     1.97 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           26 |     2900 | 2024-04-15 | Astralis Talent | W   | 0.445      | -            | -                | -                | -         |     1.27 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           25 |     3071 | 2024-04-09 | ALTERNATE aTTaX | L   | 0.406      | -            | -                | -                | -         |   -10.00 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           24 |     3159 | 2024-04-05 | UNiTY           | L   | 0.379      | -            | -                | -                | -         |    -9.47 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           23 |     3206 | 2024-04-04 | PGE Turow       | W   | 0.372      | -            | -                | -                | -         |     0.53 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           22 |     3246 | 2024-04-03 | Permitta        | W   | 0.366      | 0.333        | -                | 0.919 (0.112)    | -         |     2.50 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           21 |     3532 | 2024-03-17 | SINNERS         | W   | 0.254      | -            | -                | -                | 1 (0.254) |     3.36 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           20 |     3550 | 2024-03-16 | UNiTY           | W   | 0.248      | -            | -                | -                | 1 (0.248) |     1.68 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           19 |     3571 | 2024-03-15 | Sampi           | W   | 0.240      | -            | -                | -                | 1 (0.240) |     1.21 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           18 |     3575 | 2024-03-15 | Sashi           | L   | 0.239      | -            | -                | -                | -         |    -4.49 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           17 |     3642 | 2024-03-13 | Permitta        | L   | 0.227      | -            | -                | -                | -         |    -5.59 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           16 |     3657 | 2024-03-13 | Permitta        | L   | 0.225      | -            | -                | -                | -         |    -5.64 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           15 |     3700 | 2024-03-11 | Entropiq        | L   | 0.212      | -            | -                | -                | -         |    -6.52 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           14 |     3718 | 2024-03-10 | Zero Tenacity   | L   | 0.207      | -            | -                | -                | -         |    -4.28 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           13 |     3861 | 2024-03-05 | 9INE            | W   | 0.173      | -            | -                | -                | -         |     0.10 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           12 |     3905 | 2024-03-03 | Metizport       | W   | 0.160      | -            | -                | -                | -         |     0.73 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           11 |     3946 | 2024-03-01 | Viperio         | W   | 0.145      | -            | -                | -                | -         |     0.05 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           10 |     3974 | 2024-02-28 | Permitta        | W   | 0.132      | -            | -                | -                | -         |     0.82 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            9 |     3992 | 2024-02-27 | MOUZ NXT        | W   | 0.127      | 0.333        | 0.139 (0.006)    | -                | -         |     1.12 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            8 |     3994 | 2024-02-27 | ex-sYnck        | W   | 0.126      | -            | -                | -                | -         |     0.07 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            7 |     4011 | 2024-02-26 | PGE Turow       | W   | 0.119      | -            | -                | -                | -         |     0.15 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            6 |     4033 | 2024-02-25 | Sampi           | W   | 0.112      | -            | -                | -                | -         |     0.48 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            5 |     4066 | 2024-02-24 | Permitta        | L   | 0.106      | -            | -                | -                | -         |    -2.70 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            4 |     4095 | 2024-02-22 | BIG Academy     | W   | 0.093      | -            | -                | -                | -         |     0.03 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            3 |     4133 | 2024-02-21 | Permitta        | W   | 0.085      | -            | -                | -                | -         |     0.52 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            2 |     4150 | 2024-02-20 | NAVI Junior     | W   | 0.080      | -            | -                | -                | -         |     0.14 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            1 |     4178 | 2024-02-19 | Permitta        | L   | 0.073      | -            | -                | -                | -         |    -1.86 | Blytz, Dytor, forsyy, kreaz, nbqq |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($19,654.15)
- Divide that value by the 5th highest value among all rosters ($320,329.44)
- The final value (0.06) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-17 |      0.866 | $2,500.00      | $2,165.05       |
| 2024-06-13 |      0.841 | $545.00        | $458.61         |
| 2024-06-02 |      0.767 | $7,837.00      | $6,013.81       |
| 2024-05-13 |      0.632 | $3,000.00      | $1,895.56       |
| 2024-04-25 |      0.512 | $11,000.00     | $5,630.37       |
| 2024-04-06 |      0.385 | $1,500.00      | $577.78         |
| 2024-03-17 |      0.254 | $7,675.00      | $1,953.22       |
| 2024-02-28 |      0.132 | $5,000.00      | $660.65         |
| 2024-02-21 |      0.085 | $3,500.00      | $299.12         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
