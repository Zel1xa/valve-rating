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
Final Rank Value (1087.2) = Starting Rank Value (1220.8) + Head To Head Adjustments (-133.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.453[<sup>1</sup>](#table2)
- Bounty Collected: 0.352[<sup>2</sup>](#table1)
- Opponent Network: 0.216[<sup>2</sup>](#table1)
- LAN Wins: 0.584[<sup>2</sup>](#table1)

The average of these factors is 0.401<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1220.8
- 400 + ( ( 0.401 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 1220.8


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
|           57 |       36 | 2024-08-03 | AVEZ            | W   | 1.000      | -            | -                | -                | 1 (1.000) |     3.51 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           56 |       68 | 2024-08-02 | SINNERS         | W   | 1.000      | 0.345        | 0.037 (0.013)    | 0.797 (0.275)    | 1 (1.000) |    11.06 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           55 |      212 | 2024-07-30 | 1WIN            | W   | 1.000      | -            | -                | -                | 0 (0.000) |    12.22 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           54 |      255 | 2024-07-29 | DASH            | L   | 1.000      | -            | -                | -                | -         |   -29.73 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           53 |      369 | 2024-07-25 | HAVU            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.40 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           52 |      740 | 2024-07-16 | FAVBET          | L   | 1.000      | -            | -                | -                | -         |   -25.44 | Dytor, forsyy, kreaz, nbqq, olik  |
|           51 |      796 | 2024-07-14 | The Suspect     | L   | 1.000      | -            | -                | -                | -         |   -25.51 | Dytor, forsyy, nbqq, NEOFRAG, PR  |
|           50 |      807 | 2024-07-14 | The Suspect     | W   | 1.000      | -            | -                | -                | -         |     5.04 | Dytor, forsyy, nbqq, NEOFRAG, PR  |
|           49 |      813 | 2024-07-13 | ALTERNATE aTTaX | W   | 1.000      | -            | -                | -                | -         |     6.14 | Dytor, forsyy, K1-FiDa, nbqq, PR  |
|           48 |      908 | 2024-07-08 | Hungary         | W   | 1.000      | -            | -                | -                | -         |     4.29 | Dytor, forsyy, K1-FiDa, nbqq, PR  |
|           47 |     1081 | 2024-06-14 | 5W              | L   | 0.859      | -            | -                | -                | -         |   -19.24 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           46 |     1150 | 2024-06-11 | PERA            | L   | 0.840      | -            | -                | -                | -         |   -19.96 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           45 |     1232 | 2024-06-09 | Enterprise      | W   | 0.826      | 0.450        | 0.039 (0.015)    | 0.625 (0.232)    | -         |     5.03 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           44 |     1306 | 2024-06-08 | MOUZ NXT        | W   | 0.819      | 0.450        | 0.139 (0.051)    | 1.000 (0.369)    | -         |    11.08 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           43 |     1366 | 2024-06-07 | GhoulsW         | W   | 0.811      | -            | -                | -                | -         |     0.39 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           42 |     1397 | 2024-06-06 | GamerLegion     | L   | 0.807      | -            | -                | -                | -         |   -12.20 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           41 |     1563 | 2024-06-02 | UNiTY           | W   | 0.780      | 0.346        | 0.025 (0.007)    | -                | 1 (0.780) |     6.56 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           40 |     1595 | 2024-06-01 | UNiTY           | W   | 0.773      | 0.346        | 0.025 (0.007)    | -                | 1 (0.773) |     6.69 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           39 |     1627 | 2024-05-31 | Sampi           | W   | 0.767      | 0.346        | 0.027 (0.007)    | 1.000 (0.265)    | 1 (0.767) |     5.07 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           38 |     1752 | 2024-05-26 | Permitta        | L   | 0.731      | -            | -                | -                | -         |   -18.30 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           37 |     1840 | 2024-05-22 | Preasy          | L   | 0.705      | -            | -                | -                | -         |   -19.92 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           36 |     2180 | 2024-05-13 | Johnny Speeds   | L   | 0.644      | -            | -                | -                | -         |    -7.58 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           35 |     2250 | 2024-05-10 | Verdant         | W   | 0.625      | -            | -                | -                | -         |     3.96 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           34 |     2443 | 2024-04-30 | MOUZ NXT        | L   | 0.560      | -            | -                | -                | -         |   -12.32 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           33 |     2470 | 2024-04-29 | 1WIN            | W   | 0.553      | 0.500        | 0.027 (0.007)    | 0.707 (0.195)    | -         |     3.40 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           32 |     2507 | 2024-04-27 | MOUZ NXT        | L   | 0.540      | -            | -                | -                | -         |   -12.26 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           31 |     2578 | 2024-04-25 | Sampi           | W   | 0.524      | 0.371        | -                | 1.000 (0.194)    | -         |     2.95 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           30 |     2616 | 2024-04-23 | Sampi           | W   | 0.511      | 0.371        | -                | 1.000 (0.189)    | -         |     2.83 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           29 |     2648 | 2024-04-21 | MOUZ NXT        | W   | 0.498      | 0.371        | 0.139 (0.026)    | 1.000 (0.185)    | -         |     4.76 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           28 |     2732 | 2024-04-19 | SINNERS         | W   | 0.484      | 0.371        | 0.037 (0.007)    | 0.797 (0.143)    | -         |     6.90 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           27 |     2814 | 2024-04-17 | Alliance        | W   | 0.472      | -            | -                | -                | -         |     2.05 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           26 |     2866 | 2024-04-15 | Astralis Talent | W   | 0.458      | -            | -                | -                | -         |     1.33 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           25 |     3037 | 2024-04-09 | ALTERNATE aTTaX | L   | 0.419      | -            | -                | -                | -         |   -10.31 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           24 |     3125 | 2024-04-05 | UNiTY           | L   | 0.391      | -            | -                | -                | -         |    -9.76 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           23 |     3172 | 2024-04-04 | PGE Turow       | W   | 0.384      | -            | -                | -                | -         |     0.56 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           22 |     3212 | 2024-04-03 | Permitta        | W   | 0.378      | 0.333        | -                | 0.876 (0.110)    | -         |     2.44 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           21 |     3498 | 2024-03-17 | SINNERS         | W   | 0.267      | -            | -                | -                | 1 (0.267) |     3.48 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           20 |     3516 | 2024-03-16 | UNiTY           | W   | 0.260      | -            | -                | -                | 1 (0.260) |     1.78 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           19 |     3537 | 2024-03-15 | Sampi           | W   | 0.253      | -            | -                | -                | 1 (0.253) |     1.30 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           18 |     3541 | 2024-03-15 | Sashi           | L   | 0.252      | -            | -                | -                | -         |    -4.72 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           17 |     3608 | 2024-03-13 | Permitta        | L   | 0.239      | -            | -                | -                | -         |    -6.00 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           16 |     3623 | 2024-03-13 | Permitta        | L   | 0.238      | -            | -                | -                | -         |    -6.05 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           15 |     3666 | 2024-03-11 | Entropiq        | L   | 0.225      | -            | -                | -                | -         |    -6.90 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           14 |     3684 | 2024-03-10 | Zero Tenacity   | L   | 0.219      | -            | -                | -                | -         |    -4.55 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           13 |     3827 | 2024-03-05 | 9INE            | W   | 0.185      | -            | -                | -                | -         |     0.10 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           12 |     3871 | 2024-03-03 | Metizport       | W   | 0.172      | -            | -                | -                | -         |     0.57 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           11 |     3912 | 2024-03-01 | Viperio         | W   | 0.158      | -            | -                | -                | -         |     0.05 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           10 |     3940 | 2024-02-28 | Permitta        | W   | 0.145      | -            | -                | -                | -         |     0.83 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            9 |     3958 | 2024-02-27 | MOUZ NXT        | W   | 0.139      | 0.333        | 0.139 (0.006)    | -                | -         |     1.22 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            8 |     3960 | 2024-02-27 | ex-sYnck        | W   | 0.138      | -            | -                | -                | -         |     0.07 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            7 |     3977 | 2024-02-26 | PGE Turow       | W   | 0.131      | -            | -                | -                | -         |     0.17 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            6 |     3999 | 2024-02-25 | Sampi           | W   | 0.125      | -            | -                | -                | -         |     0.54 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            5 |     4032 | 2024-02-24 | Permitta        | L   | 0.119      | -            | -                | -                | -         |    -3.07 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            4 |     4061 | 2024-02-22 | BIG Academy     | W   | 0.105      | -            | -                | -                | -         |     0.03 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            3 |     4099 | 2024-02-21 | Permitta        | W   | 0.098      | -            | -                | -                | -         |     0.55 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            2 |     4116 | 2024-02-20 | NAVI Junior     | W   | 0.092      | -            | -                | -                | -         |     0.14 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            1 |     4144 | 2024-02-19 | Permitta        | L   | 0.085      | -            | -                | -                | -         |    -2.22 | Blytz, Dytor, forsyy, kreaz, nbqq |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($20,185.13)
- Divide that value by the 5th highest value among all rosters ($324,028.83)
- The final value (0.06) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-17 |      0.878 | $2,500.00      | $2,196.24       |
| 2024-06-13 |      0.854 | $545.00        | $465.41         |
| 2024-06-02 |      0.780 | $7,837.00      | $6,111.59       |
| 2024-05-13 |      0.644 | $3,000.00      | $1,932.99       |
| 2024-04-25 |      0.524 | $11,000.00     | $5,767.62       |
| 2024-04-06 |      0.398 | $1,500.00      | $596.49         |
| 2024-03-17 |      0.267 | $7,675.00      | $2,048.98       |
| 2024-02-28 |      0.145 | $5,000.00      | $723.03         |
| 2024-02-21 |      0.098 | $3,500.00      | $342.79         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
