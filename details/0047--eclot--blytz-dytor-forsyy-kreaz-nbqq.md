### Roster Details<br />
Team Name: ECLOT<br />
Roster: Blytz, Dytor, forsyy, kreaz, nbqq<br />
Global Rank: [47](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [35]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1082.9<br />
<br />
Final Rank Value (1082.9) = Starting Rank Value (1220.0) + Head To Head Adjustments (-137.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.454[<sup>1</sup>](#table2)
- Bounty Collected: 0.353[<sup>2</sup>](#table1)
- Opponent Network: 0.214[<sup>2</sup>](#table1)
- LAN Wins: 0.584[<sup>2</sup>](#table1)

The average of these factors is 0.401<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1220.0
- 400 + ( ( 0.401 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 1220.0


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
|           57 |       14 | 2024-08-03 | AVEZ            | W   | 1.000      | -            | -                | -                | 1 (1.000) |     1.70 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           56 |       46 | 2024-08-02 | SINNERS         | W   | 1.000      | 0.345        | 0.037 (0.013)    | 0.757 (0.262)    | 1 (1.000) |    10.72 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           55 |      187 | 2024-07-30 | 1WIN            | W   | 1.000      | -            | -                | -                | 0 (0.000) |    12.14 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           54 |      230 | 2024-07-29 | DASH            | L   | 1.000      | -            | -                | -                | -         |   -29.71 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           53 |      344 | 2024-07-25 | HAVU            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.44 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           52 |      714 | 2024-07-16 | FAVBET          | L   | 1.000      | -            | -                | -                | -         |   -25.38 | Dytor, forsyy, kreaz, nbqq, olik  |
|           51 |      772 | 2024-07-14 | The Suspect     | L   | 1.000      | -            | -                | -                | -         |   -25.53 | Dytor, forsyy, nbqq, NEOFRAG, PR  |
|           50 |      783 | 2024-07-14 | The Suspect     | W   | 1.000      | -            | -                | -                | -         |     5.03 | Dytor, forsyy, nbqq, NEOFRAG, PR  |
|           49 |      789 | 2024-07-13 | ALTERNATE aTTaX | W   | 1.000      | -            | -                | -                | -         |     6.05 | Dytor, forsyy, K1-FiDa, nbqq, PR  |
|           48 |      884 | 2024-07-08 | Hungary         | W   | 1.000      | -            | -                | -                | -         |     4.33 | Dytor, forsyy, K1-FiDa, nbqq, PR  |
|           47 |     1057 | 2024-06-14 | 5W              | L   | 0.860      | -            | -                | -                | -         |   -19.20 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           46 |     1126 | 2024-06-11 | PERA            | L   | 0.842      | -            | -                | -                | -         |   -19.92 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           45 |     1208 | 2024-06-09 | Enterprise      | W   | 0.827      | 0.450        | 0.039 (0.015)    | 0.625 (0.232)    | -         |     5.07 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           44 |     1282 | 2024-06-08 | MOUZ NXT        | W   | 0.820      | 0.450        | 0.139 (0.051)    | 1.000 (0.369)    | -         |    11.14 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           43 |     1342 | 2024-06-07 | GhoulsW         | W   | 0.812      | -            | -                | -                | -         |     0.39 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           42 |     1373 | 2024-06-06 | GamerLegion     | L   | 0.808      | -            | -                | -                | -         |   -12.12 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           41 |     1539 | 2024-06-02 | UNiTY           | W   | 0.781      | 0.346        | 0.025 (0.007)    | -                | 1 (0.781) |     6.49 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           40 |     1571 | 2024-06-01 | UNiTY           | W   | 0.774      | 0.346        | 0.025 (0.007)    | -                | 1 (0.774) |     6.63 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           39 |     1603 | 2024-05-31 | Sampi           | W   | 0.768      | 0.346        | 0.027 (0.007)    | 1.000 (0.266)    | 1 (0.768) |     5.10 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           38 |     1728 | 2024-05-26 | Permitta        | L   | 0.732      | -            | -                | -                | -         |   -18.30 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           37 |     1816 | 2024-05-22 | Preasy          | L   | 0.706      | -            | -                | -                | -         |   -19.93 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           36 |     2156 | 2024-05-13 | Johnny Speeds   | L   | 0.645      | -            | -                | -                | -         |    -7.75 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           35 |     2226 | 2024-05-10 | Verdant         | W   | 0.626      | -            | -                | -                | -         |     4.00 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           34 |     2419 | 2024-04-30 | MOUZ NXT        | L   | 0.562      | -            | -                | -                | -         |   -12.32 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           33 |     2446 | 2024-04-29 | 1WIN            | W   | 0.554      | 0.500        | 0.027 (0.007)    | 0.707 (0.196)    | -         |     3.35 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           32 |     2483 | 2024-04-27 | MOUZ NXT        | L   | 0.542      | -            | -                | -                | -         |   -12.27 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           31 |     2554 | 2024-04-25 | Sampi           | W   | 0.525      | 0.371        | -                | 1.000 (0.195)    | -         |     2.98 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           30 |     2592 | 2024-04-23 | Sampi           | W   | 0.512      | 0.371        | -                | 1.000 (0.190)    | -         |     2.86 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           29 |     2624 | 2024-04-21 | MOUZ NXT        | W   | 0.499      | 0.371        | 0.139 (0.026)    | 1.000 (0.185)    | -         |     4.80 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           28 |     2708 | 2024-04-19 | SINNERS         | W   | 0.485      | 0.371        | 0.037 (0.007)    | 0.757 (0.136)    | -         |     5.94 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           27 |     2790 | 2024-04-17 | Alliance        | W   | 0.473      | -            | -                | -                | -         |     2.06 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           26 |     2842 | 2024-04-15 | Astralis Talent | W   | 0.459      | -            | -                | -                | -         |     1.34 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           25 |     3013 | 2024-04-09 | ALTERNATE aTTaX | L   | 0.420      | -            | -                | -                | -         |   -10.33 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           24 |     3101 | 2024-04-05 | UNiTY           | L   | 0.392      | -            | -                | -                | -         |    -9.80 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           23 |     3148 | 2024-04-04 | PGE Turow       | W   | 0.385      | -            | -                | -                | -         |     0.56 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           22 |     3188 | 2024-04-03 | Permitta        | W   | 0.379      | 0.333        | -                | 0.876 (0.111)    | -         |     2.45 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           21 |     3474 | 2024-03-17 | SINNERS         | W   | 0.268      | -            | -                | -                | 1 (0.268) |     2.88 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           20 |     3492 | 2024-03-16 | UNiTY           | W   | 0.261      | -            | -                | -                | 1 (0.261) |     1.78 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           19 |     3513 | 2024-03-15 | Sampi           | W   | 0.254      | -            | -                | -                | 1 (0.254) |     1.31 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           18 |     3517 | 2024-03-15 | Sashi           | L   | 0.253      | -            | -                | -                | -         |    -4.74 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           17 |     3584 | 2024-03-13 | Permitta        | L   | 0.240      | -            | -                | -                | -         |    -6.02 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           16 |     3599 | 2024-03-13 | Permitta        | L   | 0.239      | -            | -                | -                | -         |    -6.08 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           15 |     3642 | 2024-03-11 | Entropiq        | L   | 0.226      | -            | -                | -                | -         |    -6.93 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           14 |     3660 | 2024-03-10 | Zero Tenacity   | L   | 0.220      | -            | -                | -                | -         |    -4.59 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           13 |     3803 | 2024-03-05 | 9INE            | W   | 0.186      | -            | -                | -                | -         |     0.10 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           12 |     3847 | 2024-03-03 | Metizport       | W   | 0.173      | -            | -                | -                | -         |     0.80 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           11 |     3888 | 2024-03-01 | Viperio         | W   | 0.159      | -            | -                | -                | -         |     0.05 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           10 |     3916 | 2024-02-28 | Permitta        | W   | 0.146      | -            | -                | -                | -         |     0.84 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            9 |     3934 | 2024-02-27 | MOUZ NXT        | W   | 0.140      | 0.333        | 0.139 (0.006)    | -                | -         |     1.23 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            8 |     3936 | 2024-02-27 | ex-sYnck        | W   | 0.139      | -            | -                | -                | -         |     0.07 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            7 |     3953 | 2024-02-26 | PGE Turow       | W   | 0.132      | -            | -                | -                | -         |     0.17 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            6 |     3975 | 2024-02-25 | Sampi           | W   | 0.126      | -            | -                | -                | -         |     0.54 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            5 |     4008 | 2024-02-24 | Permitta        | L   | 0.120      | -            | -                | -                | -         |    -3.10 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            4 |     4037 | 2024-02-22 | BIG Academy     | W   | 0.106      | -            | -                | -                | -         |     0.03 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            3 |     4075 | 2024-02-21 | Permitta        | W   | 0.099      | -            | -                | -                | -         |     0.56 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            2 |     4092 | 2024-02-20 | NAVI Junior     | W   | 0.093      | -            | -                | -                | -         |     0.15 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            1 |     4120 | 2024-02-19 | Permitta        | L   | 0.087      | -            | -                | -                | -         |    -2.25 | Blytz, Dytor, forsyy, kreaz, nbqq |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($20,230.44)
- Divide that value by the 5th highest value among all rosters ($324,344.55)
- The final value (0.06) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-17 |      0.880 | $2,500.00      | $2,198.90       |
| 2024-06-13 |      0.855 | $545.00        | $465.99         |
| 2024-06-02 |      0.781 | $7,837.00      | $6,119.94       |
| 2024-05-13 |      0.645 | $3,000.00      | $1,936.18       |
| 2024-04-25 |      0.525 | $11,000.00     | $5,779.33       |
| 2024-04-06 |      0.399 | $1,500.00      | $598.09         |
| 2024-03-17 |      0.268 | $7,675.00      | $2,057.15       |
| 2024-02-28 |      0.146 | $5,000.00      | $728.36         |
| 2024-02-21 |      0.099 | $3,500.00      | $346.52         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
