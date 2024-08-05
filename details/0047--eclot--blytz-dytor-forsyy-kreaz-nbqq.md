### Roster Details<br />
Team Name: ECLOT<br />
Roster: Blytz, Dytor, forsyy, kreaz, nbqq<br />
Global Rank: [47](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [34]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1087.8<br />
<br />
Final Rank Value (1087.8) = Starting Rank Value (1219.6) + Head To Head Adjustments (-131.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.453[<sup>1</sup>](#table2)
- Bounty Collected: 0.352[<sup>2</sup>](#table1)
- Opponent Network: 0.214[<sup>2</sup>](#table1)
- LAN Wins: 0.582[<sup>2</sup>](#table1)

The average of these factors is 0.400<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1219.6
- 400 + ( ( 0.400 - 0.000 ) / ( 0.781 - 0.000 ) ) * 1600 = 1219.6


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
|           57 |       53 | 2024-08-03 | AVEZ            | W   | 1.000      | -            | -                | -                | 1 (1.000) |     3.51 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           56 |       85 | 2024-08-02 | SINNERS         | W   | 1.000      | 0.345        | 0.037 (0.013)    | 0.794 (0.274)    | 1 (1.000) |    11.13 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           55 |      229 | 2024-07-30 | 1WIN            | W   | 1.000      | -            | -                | -                | 0 (0.000) |    12.36 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           54 |      271 | 2024-07-29 | DASH            | L   | 1.000      | -            | -                | -                | -         |   -29.73 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           53 |      386 | 2024-07-25 | HAVU            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.39 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           52 |      757 | 2024-07-16 | FAVBET          | L   | 1.000      | -            | -                | -                | -         |   -25.45 | Dytor, forsyy, kreaz, nbqq, olik  |
|           51 |      813 | 2024-07-14 | The Suspect     | L   | 1.000      | -            | -                | -                | -         |   -25.52 | Dytor, forsyy, nbqq, NEOFRAG, PR  |
|           50 |      824 | 2024-07-14 | The Suspect     | W   | 1.000      | -            | -                | -                | -         |     5.03 | Dytor, forsyy, nbqq, NEOFRAG, PR  |
|           49 |      830 | 2024-07-13 | ALTERNATE aTTaX | W   | 1.000      | -            | -                | -                | -         |     6.14 | Dytor, forsyy, K1-FiDa, nbqq, PR  |
|           48 |      925 | 2024-07-08 | Hungary         | W   | 1.000      | -            | -                | -                | -         |     4.27 | Dytor, forsyy, K1-FiDa, nbqq, PR  |
|           47 |     1098 | 2024-06-14 | 5W              | L   | 0.853      | -            | -                | -                | -         |   -19.15 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           46 |     1167 | 2024-06-11 | PERA            | L   | 0.835      | -            | -                | -                | -         |   -19.83 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           45 |     1249 | 2024-06-09 | Enterprise      | W   | 0.820      | 0.450        | 0.039 (0.014)    | 0.624 (0.230)    | -         |     4.99 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           44 |     1323 | 2024-06-08 | MOUZ NXT        | W   | 0.813      | 0.450        | 0.139 (0.051)    | 1.000 (0.366)    | -         |    11.08 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           43 |     1383 | 2024-06-07 | GhoulsW         | W   | 0.806      | -            | -                | -                | -         |     0.38 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           42 |     1414 | 2024-06-06 | GamerLegion     | L   | 0.802      | -            | -                | -                | -         |   -12.12 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           41 |     1580 | 2024-06-02 | UNiTY           | W   | 0.774      | 0.346        | 0.025 (0.007)    | -                | 1 (0.774) |     6.50 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           40 |     1612 | 2024-06-01 | UNiTY           | W   | 0.767      | 0.346        | 0.025 (0.007)    | -                | 1 (0.767) |     6.62 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           39 |     1644 | 2024-05-31 | Sampi           | W   | 0.761      | 0.346        | 0.027 (0.007)    | 1.000 (0.263)    | 1 (0.761) |     5.01 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           38 |     1769 | 2024-05-26 | Permitta        | L   | 0.725      | -            | -                | -                | -         |   -18.16 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           37 |     1857 | 2024-05-22 | Preasy          | L   | 0.699      | -            | -                | -                | -         |   -19.76 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           36 |     2197 | 2024-05-13 | Johnny Speeds   | L   | 0.639      | -            | -                | -                | -         |    -7.49 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           35 |     2267 | 2024-05-10 | Verdant         | W   | 0.619      | -            | -                | -                | -         |     3.94 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           34 |     2460 | 2024-04-30 | MOUZ NXT        | L   | 0.555      | -            | -                | -                | -         |   -12.15 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           33 |     2487 | 2024-04-29 | 1WIN            | W   | 0.547      | 0.500        | 0.033 (0.009)    | 0.705 (0.193)    | -         |     3.46 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           32 |     2524 | 2024-04-27 | MOUZ NXT        | L   | 0.535      | -            | -                | -                | -         |   -12.09 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           31 |     2595 | 2024-04-25 | Sampi           | W   | 0.519      | 0.371        | -                | 1.000 (0.192)    | -         |     2.90 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           30 |     2633 | 2024-04-23 | Sampi           | W   | 0.506      | 0.371        | -                | 1.000 (0.187)    | -         |     2.79 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           29 |     2665 | 2024-04-21 | MOUZ NXT        | W   | 0.493      | 0.371        | 0.139 (0.025)    | 1.000 (0.183)    | -         |     4.74 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           28 |     2749 | 2024-04-19 | SINNERS         | W   | 0.479      | 0.371        | 0.037 (0.007)    | 0.794 (0.141)    | -         |     6.81 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           27 |     2831 | 2024-04-17 | Alliance        | W   | 0.466      | -            | -                | -                | -         |     2.02 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           26 |     2883 | 2024-04-15 | Astralis Talent | W   | 0.452      | -            | -                | -                | -         |     1.31 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           25 |     3054 | 2024-04-09 | ALTERNATE aTTaX | L   | 0.413      | -            | -                | -                | -         |   -10.17 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           24 |     3142 | 2024-04-05 | UNiTY           | L   | 0.385      | -            | -                | -                | -         |    -9.61 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           23 |     3189 | 2024-04-04 | PGE Turow       | W   | 0.379      | -            | -                | -                | -         |     0.55 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           22 |     3229 | 2024-04-03 | Permitta        | W   | 0.373      | 0.333        | -                | 0.873 (0.108)    | -         |     2.41 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           21 |     3515 | 2024-03-17 | SINNERS         | W   | 0.261      | -            | -                | -                | 1 (0.261) |     3.40 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           20 |     3533 | 2024-03-16 | UNiTY           | W   | 0.254      | -            | -                | -                | 1 (0.254) |     1.74 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           19 |     3554 | 2024-03-15 | Sampi           | W   | 0.247      | -            | -                | -                | 1 (0.247) |     1.26 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           18 |     3558 | 2024-03-15 | Sashi           | L   | 0.246      | -            | -                | -                | -         |    -4.60 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           17 |     3625 | 2024-03-13 | Permitta        | L   | 0.233      | -            | -                | -                | -         |    -5.85 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           16 |     3640 | 2024-03-13 | Permitta        | L   | 0.232      | -            | -                | -                | -         |    -5.90 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           15 |     3683 | 2024-03-11 | Entropiq        | L   | 0.219      | -            | -                | -                | -         |    -6.72 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           14 |     3701 | 2024-03-10 | Zero Tenacity   | L   | 0.213      | -            | -                | -                | -         |    -4.42 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           13 |     3844 | 2024-03-05 | 9INE            | W   | 0.180      | -            | -                | -                | -         |     0.10 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           12 |     3888 | 2024-03-03 | Metizport       | W   | 0.167      | -            | -                | -                | -         |     0.55 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           11 |     3929 | 2024-03-01 | Viperio         | W   | 0.152      | -            | -                | -                | -         |     0.05 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           10 |     3957 | 2024-02-28 | Permitta        | W   | 0.139      | -            | -                | -                | -         |     0.80 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            9 |     3975 | 2024-02-27 | MOUZ NXT        | W   | 0.133      | 0.333        | 0.139 (0.006)    | -                | -         |     1.18 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            8 |     3977 | 2024-02-27 | ex-sYnck        | W   | 0.133      | -            | -                | -                | -         |     0.07 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            7 |     3994 | 2024-02-26 | PGE Turow       | W   | 0.126      | -            | -                | -                | -         |     0.16 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            6 |     4016 | 2024-02-25 | Sampi           | W   | 0.119      | -            | -                | -                | -         |     0.51 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            5 |     4049 | 2024-02-24 | Permitta        | L   | 0.113      | -            | -                | -                | -         |    -2.92 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            4 |     4078 | 2024-02-22 | BIG Academy     | W   | 0.100      | -            | -                | -                | -         |     0.03 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            3 |     4116 | 2024-02-21 | Permitta        | W   | 0.092      | -            | -                | -                | -         |     0.52 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            2 |     4133 | 2024-02-20 | NAVI Junior     | W   | 0.086      | -            | -                | -                | -         |     0.14 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            1 |     4161 | 2024-02-19 | Permitta        | L   | 0.080      | -            | -                | -                | -         |    -2.07 | Blytz, Dytor, forsyy, kreaz, nbqq |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($19,941.81)
- Divide that value by the 5th highest value among all rosters ($322,333.56)
- The final value (0.06) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-17 |      0.873 | $2,500.00      | $2,181.94       |
| 2024-06-13 |      0.848 | $545.00        | $462.29         |
| 2024-06-02 |      0.774 | $7,837.00      | $6,066.78       |
| 2024-05-13 |      0.639 | $3,000.00      | $1,915.83       |
| 2024-04-25 |      0.519 | $11,000.00     | $5,704.72       |
| 2024-04-06 |      0.392 | $1,500.00      | $587.92         |
| 2024-03-17 |      0.261 | $7,675.00      | $2,005.09       |
| 2024-02-28 |      0.139 | $5,000.00      | $694.44         |
| 2024-02-21 |      0.092 | $3,500.00      | $322.78         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
