### Roster Details<br />
Team Name: ECLOT<br />
Roster: Blytz, Dytor, forsyy, kreaz, nbqq<br />
Global Rank: [54](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [40]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1022.7<br />
<br />
Final Rank Value (1022.7) = Starting Rank Value (1111.2) + Head To Head Adjustments (-88.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.456[<sup>1</sup>](#table2)
- Bounty Collected: 0.352[<sup>2</sup>](#table1)
- Opponent Network: 0.201[<sup>2</sup>](#table1)
- LAN Wins: 0.372[<sup>2</sup>](#table1)

The average of these factors is 0.345<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1111.2
- 400 + ( ( 0.345 - 0.000 ) / ( 0.777 - 0.000 ) ) * 1600 = 1111.2


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
|           55 |       91 | 2024-07-30 | 1WIN            | W   | 1.000      | -            | -                | -                | 0 (0.000) |    13.59 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           54 |      134 | 2024-07-29 | DASH            | L   | 1.000      | -            | -                | -                | -         |   -29.16 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           53 |      248 | 2024-07-25 | HAVU            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.51 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           52 |      630 | 2024-07-16 | FAVBET          | L   | 1.000      | -            | -                | -                | -         |   -23.71 | Dytor, forsyy, kreaz, nbqq, olik  |
|           51 |      691 | 2024-07-14 | The Suspect     | L   | 1.000      | -            | -                | -                | -         |   -23.87 | Dytor, forsyy, nbqq, NEOFRAG, PR  |
|           50 |      703 | 2024-07-14 | The Suspect     | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.60 | Dytor, forsyy, nbqq, NEOFRAG, PR  |
|           49 |      710 | 2024-07-13 | ALTERNATE aTTaX | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.00 | Dytor, forsyy, K1-FiDa, nbqq, PR  |
|           48 |      805 | 2024-07-08 | Hungary         | W   | 1.000      | -            | -                | -                | -         |     5.88 | Dytor, forsyy, K1-FiDa, nbqq, PR  |
|           47 |      967 | 2024-06-14 | 5W              | L   | 0.880      | -            | -                | -                | -         |   -17.36 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           46 |     1037 | 2024-06-11 | PERA            | L   | 0.862      | -            | -                | -                | -         |   -18.56 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           45 |     1120 | 2024-06-09 | Enterprise      | W   | 0.847      | 0.450        | 0.040 (0.015)    | 0.622 (0.237)    | -         |     6.81 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           44 |     1197 | 2024-06-08 | MOUZ NXT        | W   | 0.840      | 0.450        | 0.141 (0.053)    | 1.000 (0.378)    | -         |    14.19 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           43 |     1263 | 2024-06-07 | GhoulsW         | W   | 0.833      | -            | -                | -                | -         |     1.10 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           42 |     1296 | 2024-06-06 | GamerLegion     | L   | 0.828      | -            | -                | -                | -         |    -9.82 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           41 |     1466 | 2024-06-02 | UNiTY           | W   | 0.801      | 0.346        | 0.025 (0.007)    | -                | 1 (0.801) |     8.69 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           40 |     1497 | 2024-06-01 | UNiTY           | W   | 0.794      | 0.346        | 0.025 (0.007)    | -                | 1 (0.794) |     8.99 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           39 |     1530 | 2024-05-31 | Sampi           | W   | 0.788      | 0.346        | 0.028 (0.008)    | 1.000 (0.273)    | 1 (0.788) |     7.09 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           38 |     1657 | 2024-05-26 | Permitta        | L   | 0.752      | -            | -                | -                | -         |   -16.99 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           37 |     1755 | 2024-05-22 | Preasy          | L   | 0.726      | -            | -                | -                | -         |   -19.33 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           36 |     2120 | 2024-05-13 | Johnny Speeds   | L   | 0.666      | -            | -                | -                | -         |    -5.70 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           35 |     2190 | 2024-05-10 | Verdant         | W   | 0.646      | -            | -                | -                | -         |     6.12 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           34 |     2388 | 2024-04-30 | MOUZ NXT        | L   | 0.582      | -            | -                | -                | -         |   -10.44 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           33 |     2415 | 2024-04-29 | 1WIN            | W   | 0.574      | 0.500        | 0.027 (0.008)    | 0.630 (0.181)    | -         |     4.67 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           32 |     2452 | 2024-04-27 | MOUZ NXT        | L   | 0.562      | -            | -                | -                | -         |   -10.42 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           31 |     2523 | 2024-04-25 | Sampi           | W   | 0.546      | 0.371        | 0.028 (0.006)    | 1.000 (0.202)    | -         |     4.44 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           30 |     2563 | 2024-04-23 | Sampi           | W   | 0.533      | 0.371        | -                | 1.000 (0.197)    | -         |     4.31 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           29 |     2597 | 2024-04-21 | MOUZ NXT        | W   | 0.520      | 0.371        | 0.141 (0.027)    | 1.000 (0.193)    | -         |     7.26 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           28 |     2684 | 2024-04-19 | SINNERS         | W   | 0.506      | 0.371        | 0.038 (0.007)    | 0.768 (0.144)    | -         |     7.70 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           27 |     2768 | 2024-04-17 | Alliance        | W   | 0.493      | -            | -                | -                | -         |     3.40 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           26 |     2821 | 2024-04-15 | Astralis Talent | W   | 0.479      | -            | -                | -                | -         |     2.37 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           25 |     2992 | 2024-04-09 | ALTERNATE aTTaX | L   | 0.440      | -            | -                | -                | -         |    -9.30 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           24 |     3081 | 2024-04-05 | UNiTY           | L   | 0.412      | -            | -                | -                | -         |    -8.94 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           23 |     3129 | 2024-04-04 | PGE Turow       | W   | 0.406      | -            | -                | -                | -         |     1.03 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           22 |     3174 | 2024-04-03 | Permitta        | W   | 0.400      | 0.333        | -                | 0.801 (0.107)    | -         |     3.84 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           21 |     3467 | 2024-03-17 | SINNERS         | W   | 0.288      | -            | -                | -                | 1 (0.288) |     3.95 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           20 |     3485 | 2024-03-16 | UNiTY           | W   | 0.281      | -            | -                | -                | 1 (0.281) |     2.93 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           19 |     3506 | 2024-03-15 | Sampi           | W   | 0.274      | 0.345        | -                | 1.000 (0.094)    | 1 (0.274) |     2.30 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           18 |     3510 | 2024-03-15 | Sashi           | L   | 0.273      | -            | -                | -                | -         |    -3.82 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           17 |     3581 | 2024-03-13 | Permitta        | L   | 0.260      | -            | -                | -                | -         |    -5.66 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           16 |     3596 | 2024-03-13 | Permitta        | L   | 0.259      | -            | -                | -                | -         |    -5.75 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           15 |     3640 | 2024-03-11 | Entropiq        | L   | 0.246      | -            | -                | -                | -         |    -7.39 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           14 |     3658 | 2024-03-10 | Zero Tenacity   | L   | 0.240      | -            | -                | -                | -         |    -3.94 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           13 |     3807 | 2024-03-05 | 9INE            | W   | 0.207      | -            | -                | -                | -         |     0.20 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           12 |     3851 | 2024-03-03 | Metizport       | W   | 0.194      | -            | -                | -                | -         |     1.45 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           11 |     3893 | 2024-03-01 | Viperio         | W   | 0.179      | -            | -                | -                | -         |     0.10 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           10 |     3922 | 2024-02-28 | Permitta        | W   | 0.166      | -            | -                | -                | -         |     1.48 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            9 |     3940 | 2024-02-27 | MOUZ NXT        | W   | 0.160      | 0.333        | 0.141 (0.008)    | -                | -         |     2.23 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            8 |     3942 | 2024-02-27 | ex-sYnck        | W   | 0.159      | -            | -                | -                | -         |     0.16 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            7 |     3960 | 2024-02-26 | PGE Turow       | W   | 0.152      | -            | -                | -                | -         |     0.36 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            6 |     3983 | 2024-02-25 | Sampi           | W   | 0.146      | -            | -                | -                | -         |     1.07 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            5 |     4018 | 2024-02-24 | Permitta        | L   | 0.140      | -            | -                | -                | -         |    -3.19 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            4 |     4050 | 2024-02-22 | BIG Academy     | W   | 0.127      | -            | -                | -                | -         |     0.07 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            3 |     4089 | 2024-02-21 | Permitta        | W   | 0.119      | -            | -                | -                | -         |     1.04 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            2 |     4106 | 2024-02-20 | NAVI Junior     | W   | 0.113      | -            | -                | -                | -         |     0.32 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            1 |     4134 | 2024-02-19 | Permitta        | L   | 0.107      | -            | -                | -                | -         |    -2.44 | Blytz, Dytor, forsyy, kreaz, nbqq |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($21,088.48)
- Divide that value by the 5th highest value among all rosters ($327,422.13)
- The final value (0.06) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-17 |      0.900 | $2,500.00      | $2,249.31       |
| 2024-06-13 |      0.875 | $545.00        | $476.98         |
| 2024-06-02 |      0.801 | $7,837.00      | $6,277.94       |
| 2024-05-13 |      0.666 | $3,000.00      | $1,996.67       |
| 2024-04-25 |      0.546 | $11,000.00     | $6,001.11       |
| 2024-04-06 |      0.419 | $1,500.00      | $628.33         |
| 2024-03-17 |      0.288 | $7,675.00      | $2,211.89       |
| 2024-02-28 |      0.166 | $5,000.00      | $829.17         |
| 2024-02-21 |      0.119 | $3,500.00      | $417.08         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
