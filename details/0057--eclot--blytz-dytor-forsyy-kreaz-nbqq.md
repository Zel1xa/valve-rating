### Roster Details<br />
Team Name: ECLOT<br />
Roster: Blytz, Dytor, forsyy, kreaz, nbqq<br />
Global Rank: [57](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [42]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1023.5<br />
<br />
Final Rank Value (1023.5) = Starting Rank Value (1113.2) + Head To Head Adjustments (-89.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.456[<sup>1</sup>](#table2)
- Bounty Collected: 0.352[<sup>2</sup>](#table1)
- Opponent Network: 0.201[<sup>2</sup>](#table1)
- LAN Wins: 0.374[<sup>2</sup>](#table1)

The average of these factors is 0.346<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1113.2
- 400 + ( ( 0.346 - 0.000 ) / ( 0.776 - 0.000 ) ) * 1600 = 1113.2


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
|           55 |       63 | 2024-07-30 | 1WIN            | W   | 1.000      | -            | -                | -                | 0 (0.000) |    13.52 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           54 |      106 | 2024-07-29 | DASH            | L   | 1.000      | -            | -                | -                | -         |   -29.18 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           53 |      220 | 2024-07-25 | HAVU            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.49 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           52 |      591 | 2024-07-16 | FAVBET          | L   | 1.000      | -            | -                | -                | -         |   -23.70 | Dytor, forsyy, kreaz, nbqq, olik  |
|           51 |      647 | 2024-07-14 | Kosovo          | L   | 1.000      | -            | -                | -                | -         |   -23.81 | Dytor, forsyy, nbqq, NEOFRAG, PR  |
|           50 |      658 | 2024-07-14 | Kosovo          | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.63 | Dytor, forsyy, nbqq, NEOFRAG, PR  |
|           49 |      664 | 2024-07-13 | ALTERNATE aTTaX | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.74 | Dytor, forsyy, K1-FiDa, nbqq, PR  |
|           48 |      759 | 2024-07-08 | Hungary         | W   | 1.000      | -            | -                | -                | -         |     5.89 | Dytor, forsyy, K1-FiDa, nbqq, PR  |
|           47 |      932 | 2024-06-14 | 5W              | L   | 0.884      | -            | -                | -                | -         |   -17.42 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           46 |     1001 | 2024-06-11 | PERA            | L   | 0.866      | -            | -                | -                | -         |   -18.47 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           45 |     1083 | 2024-06-09 | Enterprise      | W   | 0.851      | 0.450        | 0.040 (0.015)    | 0.622 (0.238)    | -         |     6.93 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           44 |     1157 | 2024-06-08 | MOUZ NXT        | W   | 0.844      | 0.450        | 0.140 (0.053)    | 1.000 (0.380)    | -         |    14.01 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           43 |     1217 | 2024-06-07 | GhoulsW         | W   | 0.837      | -            | -                | -                | -         |     0.58 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           42 |     1248 | 2024-06-06 | GamerLegion     | L   | 0.833      | -            | -                | -                | -         |    -9.57 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           41 |     1414 | 2024-06-02 | UNiTY           | W   | 0.805      | 0.346        | 0.025 (0.007)    | -                | 1 (0.805) |     8.83 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           40 |     1446 | 2024-06-01 | UNiTY           | W   | 0.799      | 0.346        | 0.025 (0.007)    | -                | 1 (0.799) |     9.18 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           39 |     1478 | 2024-05-31 | Sampi           | W   | 0.793      | 0.346        | 0.028 (0.008)    | 1.000 (0.274)    | 1 (0.793) |     7.26 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           38 |     1603 | 2024-05-26 | Permitta        | L   | 0.757      | -            | -                | -                | -         |   -17.19 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           37 |     1691 | 2024-05-22 | Preasy          | L   | 0.731      | -            | -                | -                | -         |   -19.45 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           36 |     2031 | 2024-05-13 | Johnny Speeds   | L   | 0.670      | -            | -                | -                | -         |    -5.75 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           35 |     2101 | 2024-05-10 | Verdant         | W   | 0.651      | -            | -                | -                | -         |     6.04 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           34 |     2294 | 2024-04-30 | MOUZ NXT        | L   | 0.586      | -            | -                | -                | -         |   -10.85 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           33 |     2321 | 2024-04-29 | 1WIN            | W   | 0.579      | 0.500        | 0.027 (0.008)    | 0.630 (0.182)    | -         |     4.67 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           32 |     2358 | 2024-04-27 | MOUZ NXT        | L   | 0.566      | -            | -                | -                | -         |   -10.85 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           31 |     2429 | 2024-04-25 | Sampi           | W   | 0.550      | 0.371        | 0.028 (0.006)    | 1.000 (0.204)    | -         |     4.64 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           30 |     2467 | 2024-04-23 | Sampi           | W   | 0.537      | 0.371        | -                | 1.000 (0.199)    | -         |     4.53 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           29 |     2499 | 2024-04-21 | MOUZ NXT        | W   | 0.524      | 0.371        | 0.140 (0.027)    | 1.000 (0.194)    | -         |     7.10 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           28 |     2583 | 2024-04-19 | SINNERS         | W   | 0.510      | 0.371        | 0.038 (0.007)    | 0.721 (0.136)    | -         |     7.53 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           27 |     2665 | 2024-04-17 | Alliance        | W   | 0.497      | -            | -                | -                | -         |     3.37 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           26 |     2717 | 2024-04-15 | Astralis Talent | W   | 0.483      | -            | -                | -                | -         |     2.34 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           25 |     2888 | 2024-04-09 | ALTERNATE aTTaX | L   | 0.444      | -            | -                | -                | -         |    -9.34 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           24 |     2976 | 2024-04-05 | UNiTY           | L   | 0.417      | -            | -                | -                | -         |    -8.93 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           23 |     3023 | 2024-04-04 | PGE Turow       | W   | 0.410      | -            | -                | -                | -         |     1.03 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           22 |     3063 | 2024-04-03 | Permitta        | W   | 0.404      | 0.333        | -                | 0.799 (0.108)    | -         |     3.76 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           21 |     3349 | 2024-03-17 | SINNERS         | W   | 0.293      | -            | -                | -                | 1 (0.293) |     3.84 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           20 |     3367 | 2024-03-16 | UNiTY           | W   | 0.286      | -            | -                | -                | 1 (0.286) |     3.06 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           19 |     3388 | 2024-03-15 | Sampi           | W   | 0.278      | 0.345        | -                | 1.000 (0.096)    | 1 (0.278) |     2.32 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           18 |     3392 | 2024-03-15 | Sashi           | L   | 0.277      | -            | -                | -                | -         |    -3.88 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           17 |     3459 | 2024-03-13 | Permitta        | L   | 0.265      | -            | -                | -                | -         |    -5.84 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           16 |     3474 | 2024-03-13 | Permitta        | L   | 0.264      | -            | -                | -                | -         |    -5.93 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           15 |     3517 | 2024-03-11 | Entropiq        | L   | 0.250      | -            | -                | -                | -         |    -7.52 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           14 |     3535 | 2024-03-10 | Zero Tenacity   | L   | 0.245      | -            | -                | -                | -         |    -3.97 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           13 |     3678 | 2024-03-05 | 9INE            | W   | 0.211      | -            | -                | -                | -         |     0.21 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           12 |     3722 | 2024-03-03 | Metizport       | W   | 0.198      | -            | -                | -                | -         |     1.51 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           11 |     3763 | 2024-03-01 | Viperio         | W   | 0.184      | -            | -                | -                | -         |     0.10 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           10 |     3791 | 2024-02-28 | Permitta        | W   | 0.170      | -            | -                | -                | -         |     1.45 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            9 |     3809 | 2024-02-27 | MOUZ NXT        | W   | 0.165      | 0.333        | 0.140 (0.008)    | -                | -         |     2.19 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            8 |     3811 | 2024-02-27 | ex-sYnck        | W   | 0.164      | -            | -                | -                | -         |     0.16 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            7 |     3828 | 2024-02-26 | PGE Turow       | W   | 0.157      | -            | -                | -                | -         |     0.37 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            6 |     3850 | 2024-02-25 | Sampi           | W   | 0.150      | -            | -                | -                | -         |     1.09 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            5 |     3883 | 2024-02-24 | Permitta        | L   | 0.144      | -            | -                | -                | -         |    -3.32 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            4 |     3912 | 2024-02-22 | BIG Academy     | W   | 0.131      | -            | -                | -                | -         |     0.07 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            3 |     3950 | 2024-02-21 | Permitta        | W   | 0.124      | -            | -                | -                | -         |     1.05 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            2 |     3967 | 2024-02-20 | NAVI Junior     | W   | 0.118      | -            | -                | -                | -         |     0.33 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            1 |     3995 | 2024-02-19 | Permitta        | L   | 0.111      | -            | -                | -                | -         |    -2.57 | Blytz, Dytor, forsyy, kreaz, nbqq |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($21,273.09)
- Divide that value by the 5th highest value among all rosters ($331,608.80)
- The final value (0.06) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-17 |      0.904 | $2,500.00      | $2,260.15       |
| 2024-06-13 |      0.880 | $545.00        | $479.34         |
| 2024-06-02 |      0.805 | $7,837.00      | $6,311.94       |
| 2024-05-13 |      0.670 | $3,000.00      | $2,009.68       |
| 2024-04-25 |      0.550 | $11,000.00     | $6,048.83       |
| 2024-04-06 |      0.423 | $1,500.00      | $634.84         |
| 2024-03-17 |      0.293 | $7,675.00      | $2,245.19       |
| 2024-02-28 |      0.170 | $5,000.00      | $850.86         |
| 2024-02-21 |      0.124 | $3,500.00      | $432.27         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
