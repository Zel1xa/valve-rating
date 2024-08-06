### Roster Details<br />
Team Name: ECLOT<br />
Roster: Blytz, Dytor, forsyy, kreaz, nbqq<br />
Global Rank: [48](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [35]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1089.0<br />
<br />
Final Rank Value (1089.0) = Starting Rank Value (1219.6) + Head To Head Adjustments (-130.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.452[<sup>1</sup>](#table2)
- Bounty Collected: 0.352[<sup>2</sup>](#table1)
- Opponent Network: 0.213[<sup>2</sup>](#table1)
- LAN Wins: 0.581[<sup>2</sup>](#table1)

The average of these factors is 0.400<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1219.6
- 400 + ( ( 0.400 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 1219.6


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
|           57 |       64 | 2024-08-03 | AVEZ            | W   | 1.000      | -            | -                | -                | 1 (1.000) |     3.50 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           56 |       96 | 2024-08-02 | SINNERS         | W   | 1.000      | 0.345        | 0.037 (0.013)    | 0.808 (0.279)    | 1 (1.000) |    11.16 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           55 |      240 | 2024-07-30 | 1WIN            | W   | 1.000      | -            | -                | -                | 0 (0.000) |    12.38 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           54 |      283 | 2024-07-29 | DASH            | L   | 1.000      | -            | -                | -                | -         |   -29.74 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           53 |      397 | 2024-07-25 | HAVU            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.37 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           52 |      768 | 2024-07-16 | FAVBET          | L   | 1.000      | -            | -                | -                | -         |   -25.41 | Dytor, forsyy, kreaz, nbqq, olik  |
|           51 |      824 | 2024-07-14 | The Suspect     | L   | 1.000      | -            | -                | -                | -         |   -25.55 | Dytor, forsyy, nbqq, NEOFRAG, PR  |
|           50 |      835 | 2024-07-14 | The Suspect     | W   | 1.000      | -            | -                | -                | -         |     5.00 | Dytor, forsyy, nbqq, NEOFRAG, PR  |
|           49 |      841 | 2024-07-13 | ALTERNATE aTTaX | W   | 1.000      | -            | -                | -                | -         |     6.14 | Dytor, forsyy, K1-FiDa, nbqq, PR  |
|           48 |      936 | 2024-07-08 | Hungary         | W   | 1.000      | -            | -                | -                | -         |     4.25 | Dytor, forsyy, K1-FiDa, nbqq, PR  |
|           47 |     1109 | 2024-06-14 | 5W              | L   | 0.850      | -            | -                | -                | -         |   -19.11 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           46 |     1178 | 2024-06-11 | PERA            | L   | 0.831      | -            | -                | -                | -         |   -19.79 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           45 |     1260 | 2024-06-09 | Enterprise      | W   | 0.817      | 0.450        | 0.039 (0.014)    | 0.616 (0.226)    | -         |     5.03 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           44 |     1334 | 2024-06-08 | MOUZ NXT        | W   | 0.810      | 0.450        | 0.139 (0.051)    | 0.986 (0.359)    | -         |    11.02 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           43 |     1394 | 2024-06-07 | GhoulsW         | W   | 0.802      | -            | -                | -                | -         |     0.38 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           42 |     1425 | 2024-06-06 | GamerLegion     | L   | 0.798      | -            | -                | -                | -         |   -12.15 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           41 |     1591 | 2024-06-02 | UNiTY           | W   | 0.771      | 0.346        | 0.025 (0.007)    | -                | 1 (0.771) |     6.47 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           40 |     1623 | 2024-06-01 | UNiTY           | W   | 0.764      | 0.346        | 0.025 (0.006)    | -                | 1 (0.764) |     6.59 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           39 |     1655 | 2024-05-31 | Sampi           | W   | 0.758      | 0.346        | 0.027 (0.007)    | 1.000 (0.262)    | 1 (0.758) |     4.98 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           38 |     1780 | 2024-05-26 | Permitta        | L   | 0.722      | -            | -                | -                | -         |   -17.94 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           37 |     1868 | 2024-05-22 | Preasy          | L   | 0.696      | -            | -                | -                | -         |   -19.72 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           36 |     2208 | 2024-05-13 | Johnny Speeds   | L   | 0.635      | -            | -                | -                | -         |    -7.46 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           35 |     2278 | 2024-05-10 | Verdant         | W   | 0.616      | -            | -                | -                | -         |     3.90 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           34 |     2471 | 2024-04-30 | MOUZ NXT        | L   | 0.551      | -            | -                | -                | -         |   -12.09 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           33 |     2498 | 2024-04-29 | 1WIN            | W   | 0.544      | 0.500        | 0.033 (0.009)    | 0.696 (0.189)    | -         |     3.44 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           32 |     2535 | 2024-04-27 | MOUZ NXT        | L   | 0.531      | -            | -                | -                | -         |   -12.02 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           31 |     2606 | 2024-04-25 | Sampi           | W   | 0.515      | 0.371        | -                | 1.000 (0.191)    | -         |     2.88 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           30 |     2644 | 2024-04-23 | Sampi           | W   | 0.502      | 0.371        | -                | 1.000 (0.186)    | -         |     2.76 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           29 |     2676 | 2024-04-21 | MOUZ NXT        | W   | 0.489      | 0.371        | 0.139 (0.025)    | 0.986 (0.179)    | -         |     4.71 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           28 |     2760 | 2024-04-19 | SINNERS         | W   | 0.475      | 0.371        | 0.037 (0.007)    | 0.808 (0.142)    | -         |     6.85 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           27 |     2842 | 2024-04-17 | Alliance        | W   | 0.463      | -            | -                | -                | -         |     2.00 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           26 |     2894 | 2024-04-15 | Astralis Talent | W   | 0.449      | -            | -                | -                | -         |     1.28 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           25 |     3065 | 2024-04-09 | ALTERNATE aTTaX | L   | 0.410      | -            | -                | -                | -         |   -10.09 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           24 |     3153 | 2024-04-05 | UNiTY           | L   | 0.382      | -            | -                | -                | -         |    -9.53 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           23 |     3200 | 2024-04-04 | PGE Turow       | W   | 0.375      | -            | -                | -                | -         |     0.54 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           22 |     3240 | 2024-04-03 | Permitta        | W   | 0.369      | 0.333        | -                | 0.901 (0.111)    | -         |     2.52 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           21 |     3526 | 2024-03-17 | SINNERS         | W   | 0.258      | -            | -                | -                | 1 (0.258) |     3.42 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           20 |     3544 | 2024-03-16 | UNiTY           | W   | 0.251      | -            | -                | -                | 1 (0.251) |     1.72 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           19 |     3565 | 2024-03-15 | Sampi           | W   | 0.244      | -            | -                | -                | 1 (0.244) |     1.24 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           18 |     3569 | 2024-03-15 | Sashi           | L   | 0.242      | -            | -                | -                | -         |    -4.54 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           17 |     3636 | 2024-03-13 | Permitta        | L   | 0.230      | -            | -                | -                | -         |    -5.67 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           16 |     3651 | 2024-03-13 | Permitta        | L   | 0.229      | -            | -                | -                | -         |    -5.72 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           15 |     3694 | 2024-03-11 | Entropiq        | L   | 0.216      | -            | -                | -                | -         |    -6.62 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           14 |     3712 | 2024-03-10 | Zero Tenacity   | L   | 0.210      | -            | -                | -                | -         |    -4.34 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           13 |     3855 | 2024-03-05 | 9INE            | W   | 0.176      | -            | -                | -                | -         |     0.10 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           12 |     3899 | 2024-03-03 | Metizport       | W   | 0.163      | -            | -                | -                | -         |     0.54 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           11 |     3940 | 2024-03-01 | Viperio         | W   | 0.149      | -            | -                | -                | -         |     0.05 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           10 |     3968 | 2024-02-28 | Permitta        | W   | 0.136      | -            | -                | -                | -         |     0.84 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            9 |     3986 | 2024-02-27 | MOUZ NXT        | W   | 0.130      | 0.333        | 0.139 (0.006)    | -                | -         |     1.15 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            8 |     3988 | 2024-02-27 | ex-sYnck        | W   | 0.129      | -            | -                | -                | -         |     0.07 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            7 |     4005 | 2024-02-26 | PGE Turow       | W   | 0.122      | -            | -                | -                | -         |     0.16 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            6 |     4027 | 2024-02-25 | Sampi           | W   | 0.116      | -            | -                | -                | -         |     0.50 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            5 |     4060 | 2024-02-24 | Permitta        | L   | 0.110      | -            | -                | -                | -         |    -2.79 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            4 |     4089 | 2024-02-22 | BIG Academy     | W   | 0.096      | -            | -                | -                | -         |     0.03 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            3 |     4127 | 2024-02-21 | Permitta        | W   | 0.089      | -            | -                | -                | -         |     0.54 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            2 |     4144 | 2024-02-20 | NAVI Junior     | W   | 0.083      | -            | -                | -                | -         |     0.13 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            1 |     4172 | 2024-02-19 | Permitta        | L   | 0.076      | -            | -                | -                | -         |    -1.95 | Blytz, Dytor, forsyy, kreaz, nbqq |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($19,799.95)
- Divide that value by the 5th highest value among all rosters ($321,345.23)
- The final value (0.06) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-17 |      0.869 | $2,500.00      | $2,173.61       |
| 2024-06-13 |      0.845 | $545.00        | $460.47         |
| 2024-06-02 |      0.771 | $7,837.00      | $6,040.66       |
| 2024-05-13 |      0.635 | $3,000.00      | $1,905.83       |
| 2024-04-25 |      0.515 | $11,000.00     | $5,668.06       |
| 2024-04-06 |      0.389 | $1,500.00      | $582.92         |
| 2024-03-17 |      0.258 | $7,675.00      | $1,979.51       |
| 2024-02-28 |      0.136 | $5,000.00      | $677.78         |
| 2024-02-21 |      0.089 | $3,500.00      | $311.11         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
