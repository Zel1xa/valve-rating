### Roster Details<br />
Team Name: ECLOT<br />
Roster: Blytz, Dytor, forsyy, kreaz, nbqq<br />
Global Rank: [46](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [33]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1087.1<br />
<br />
Final Rank Value (1087.1) = Starting Rank Value (1220.1) + Head To Head Adjustments (-133.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.453[<sup>1</sup>](#table2)
- Bounty Collected: 0.352[<sup>2</sup>](#table1)
- Opponent Network: 0.215[<sup>2</sup>](#table1)
- LAN Wins: 0.583[<sup>2</sup>](#table1)

The average of these factors is 0.401<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1220.1
- 400 + ( ( 0.401 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 1220.1


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
|           57 |       40 | 2024-08-03 | AVEZ            | W   | 1.000      | -            | -                | -                | 1 (1.000) |     3.52 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           56 |       72 | 2024-08-02 | SINNERS         | W   | 1.000      | 0.345        | 0.037 (0.013)    | 0.797 (0.275)    | 1 (1.000) |    11.06 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           55 |      216 | 2024-07-30 | 1WIN            | W   | 1.000      | -            | -                | -                | 0 (0.000) |    12.21 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           54 |      259 | 2024-07-29 | DASH            | L   | 1.000      | -            | -                | -                | -         |   -29.73 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           53 |      373 | 2024-07-25 | HAVU            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.40 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           52 |      744 | 2024-07-16 | FAVBET          | L   | 1.000      | -            | -                | -                | -         |   -25.45 | Dytor, forsyy, kreaz, nbqq, olik  |
|           51 |      800 | 2024-07-14 | The Suspect     | L   | 1.000      | -            | -                | -                | -         |   -25.51 | Dytor, forsyy, nbqq, NEOFRAG, PR  |
|           50 |      811 | 2024-07-14 | The Suspect     | W   | 1.000      | -            | -                | -                | -         |     5.04 | Dytor, forsyy, nbqq, NEOFRAG, PR  |
|           49 |      817 | 2024-07-13 | ALTERNATE aTTaX | W   | 1.000      | -            | -                | -                | -         |     6.14 | Dytor, forsyy, K1-FiDa, nbqq, PR  |
|           48 |      912 | 2024-07-08 | Hungary         | W   | 1.000      | -            | -                | -                | -         |     4.29 | Dytor, forsyy, K1-FiDa, nbqq, PR  |
|           47 |     1085 | 2024-06-14 | 5W              | L   | 0.856      | -            | -                | -                | -         |   -19.20 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           46 |     1154 | 2024-06-11 | PERA            | L   | 0.838      | -            | -                | -                | -         |   -19.91 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           45 |     1236 | 2024-06-09 | Enterprise      | W   | 0.823      | 0.450        | 0.039 (0.015)    | 0.625 (0.232)    | -         |     5.02 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           44 |     1310 | 2024-06-08 | MOUZ NXT        | W   | 0.816      | 0.450        | 0.139 (0.051)    | 1.000 (0.367)    | -         |    11.04 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           43 |     1370 | 2024-06-07 | GhoulsW         | W   | 0.809      | -            | -                | -                | -         |     0.39 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           42 |     1401 | 2024-06-06 | GamerLegion     | L   | 0.805      | -            | -                | -                | -         |   -12.12 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           41 |     1567 | 2024-06-02 | UNiTY           | W   | 0.777      | 0.346        | 0.025 (0.007)    | -                | 1 (0.777) |     6.53 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           40 |     1599 | 2024-06-01 | UNiTY           | W   | 0.771      | 0.346        | 0.025 (0.007)    | -                | 1 (0.771) |     6.66 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           39 |     1631 | 2024-05-31 | Sampi           | W   | 0.765      | 0.346        | 0.027 (0.007)    | 1.000 (0.264)    | 1 (0.765) |     5.05 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           38 |     1756 | 2024-05-26 | Permitta        | L   | 0.729      | -            | -                | -                | -         |   -18.24 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           37 |     1844 | 2024-05-22 | Preasy          | L   | 0.703      | -            | -                | -                | -         |   -19.86 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           36 |     2184 | 2024-05-13 | Johnny Speeds   | L   | 0.642      | -            | -                | -                | -         |    -7.55 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           35 |     2254 | 2024-05-10 | Verdant         | W   | 0.623      | -            | -                | -                | -         |     3.96 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           34 |     2447 | 2024-04-30 | MOUZ NXT        | L   | 0.558      | -            | -                | -                | -         |   -12.26 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           33 |     2474 | 2024-04-29 | 1WIN            | W   | 0.551      | 0.500        | 0.027 (0.007)    | 0.707 (0.195)    | -         |     3.39 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           32 |     2511 | 2024-04-27 | MOUZ NXT        | L   | 0.538      | -            | -                | -                | -         |   -12.21 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           31 |     2582 | 2024-04-25 | Sampi           | W   | 0.522      | 0.371        | -                | 1.000 (0.193)    | -         |     2.93 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           30 |     2620 | 2024-04-23 | Sampi           | W   | 0.509      | 0.371        | -                | 1.000 (0.189)    | -         |     2.81 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           29 |     2652 | 2024-04-21 | MOUZ NXT        | W   | 0.496      | 0.371        | 0.139 (0.026)    | 1.000 (0.184)    | -         |     4.74 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           28 |     2736 | 2024-04-19 | SINNERS         | W   | 0.482      | 0.371        | 0.037 (0.007)    | 0.797 (0.142)    | -         |     6.86 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           27 |     2818 | 2024-04-17 | Alliance        | W   | 0.469      | -            | -                | -                | -         |     2.04 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           26 |     2870 | 2024-04-15 | Astralis Talent | W   | 0.455      | -            | -                | -                | -         |     1.32 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           25 |     3041 | 2024-04-09 | ALTERNATE aTTaX | L   | 0.416      | -            | -                | -                | -         |   -10.25 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           24 |     3129 | 2024-04-05 | UNiTY           | L   | 0.389      | -            | -                | -                | -         |    -9.70 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           23 |     3176 | 2024-04-04 | PGE Turow       | W   | 0.382      | -            | -                | -                | -         |     0.55 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           22 |     3216 | 2024-04-03 | Permitta        | W   | 0.376      | 0.333        | -                | 0.876 (0.110)    | -         |     2.43 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           21 |     3502 | 2024-03-17 | SINNERS         | W   | 0.265      | -            | -                | -                | 1 (0.265) |     3.45 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           20 |     3520 | 2024-03-16 | UNiTY           | W   | 0.258      | -            | -                | -                | 1 (0.258) |     1.77 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           19 |     3541 | 2024-03-15 | Sampi           | W   | 0.250      | -            | -                | -                | 1 (0.250) |     1.29 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           18 |     3545 | 2024-03-15 | Sashi           | L   | 0.249      | -            | -                | -                | -         |    -4.67 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           17 |     3612 | 2024-03-13 | Permitta        | L   | 0.237      | -            | -                | -                | -         |    -5.93 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           16 |     3627 | 2024-03-13 | Permitta        | L   | 0.236      | -            | -                | -                | -         |    -5.99 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           15 |     3670 | 2024-03-11 | Entropiq        | L   | 0.222      | -            | -                | -                | -         |    -6.83 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           14 |     3688 | 2024-03-10 | Zero Tenacity   | L   | 0.217      | -            | -                | -                | -         |    -4.50 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           13 |     3831 | 2024-03-05 | 9INE            | W   | 0.183      | -            | -                | -                | -         |     0.10 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           12 |     3875 | 2024-03-03 | Metizport       | W   | 0.170      | -            | -                | -                | -         |     0.56 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           11 |     3916 | 2024-03-01 | Viperio         | W   | 0.156      | -            | -                | -                | -         |     0.05 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           10 |     3944 | 2024-02-28 | Permitta        | W   | 0.142      | -            | -                | -                | -         |     0.82 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            9 |     3962 | 2024-02-27 | MOUZ NXT        | W   | 0.137      | 0.333        | 0.139 (0.006)    | -                | -         |     1.20 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            8 |     3964 | 2024-02-27 | ex-sYnck        | W   | 0.136      | -            | -                | -                | -         |     0.07 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            7 |     3981 | 2024-02-26 | PGE Turow       | W   | 0.129      | -            | -                | -                | -         |     0.17 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            6 |     4003 | 2024-02-25 | Sampi           | W   | 0.122      | -            | -                | -                | -         |     0.53 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            5 |     4036 | 2024-02-24 | Permitta        | L   | 0.116      | -            | -                | -                | -         |    -3.00 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            4 |     4065 | 2024-02-22 | BIG Academy     | W   | 0.103      | -            | -                | -                | -         |     0.03 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            3 |     4103 | 2024-02-21 | Permitta        | W   | 0.096      | -            | -                | -                | -         |     0.54 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            2 |     4120 | 2024-02-20 | NAVI Junior     | W   | 0.090      | -            | -                | -                | -         |     0.14 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            1 |     4148 | 2024-02-19 | Permitta        | L   | 0.083      | -            | -                | -                | -         |    -2.15 | Blytz, Dytor, forsyy, kreaz, nbqq |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($20,083.66)
- Divide that value by the 5th highest value among all rosters ($323,321.90)
- The final value (0.06) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-17 |      0.876 | $2,500.00      | $2,190.28       |
| 2024-06-13 |      0.852 | $545.00        | $464.11         |
| 2024-06-02 |      0.777 | $7,837.00      | $6,092.90       |
| 2024-05-13 |      0.642 | $3,000.00      | $1,925.83       |
| 2024-04-25 |      0.522 | $11,000.00     | $5,741.39       |
| 2024-04-06 |      0.395 | $1,500.00      | $592.92         |
| 2024-03-17 |      0.265 | $7,675.00      | $2,030.68       |
| 2024-02-28 |      0.142 | $5,000.00      | $711.11         |
| 2024-02-21 |      0.096 | $3,500.00      | $334.44         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
