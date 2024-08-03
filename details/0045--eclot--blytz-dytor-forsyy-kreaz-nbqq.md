### Roster Details<br />
Team Name: ECLOT<br />
Roster: Blytz, Dytor, forsyy, kreaz, nbqq<br />
Global Rank: [45](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [33]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1082.7<br />
<br />
Final Rank Value (1082.7) = Starting Rank Value (1223.2) + Head To Head Adjustments (-140.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.454[<sup>1</sup>](#table2)
- Bounty Collected: 0.353[<sup>2</sup>](#table1)
- Opponent Network: 0.217[<sup>2</sup>](#table1)
- LAN Wins: 0.586[<sup>2</sup>](#table1)

The average of these factors is 0.402<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1223.2
- 400 + ( ( 0.402 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 1223.2


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
|           57 |        1 | 2024-08-03 | AVEZ            | W   | 1.000      | -            | -                | -                | 1 (1.000) |     1.70 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           56 |       29 | 2024-08-02 | SINNERS         | W   | 1.000      | 0.345        | 0.037 (0.013)    | 0.784 (0.271)    | 1 (1.000) |    10.38 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           55 |      153 | 2024-07-30 | 1WIN            | W   | 1.000      | -            | -                | -                | 0 (0.000) |    11.52 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           54 |      196 | 2024-07-29 | DASH            | L   | 1.000      | -            | -                | -                | -         |   -29.71 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           53 |      310 | 2024-07-25 | HAVU            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.44 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           52 |      678 | 2024-07-16 | FAVBET          | L   | 1.000      | -            | -                | -                | -         |   -25.43 | Dytor, forsyy, kreaz, nbqq, olik  |
|           51 |      734 | 2024-07-14 | The Suspect     | L   | 1.000      | -            | -                | -                | -         |   -25.52 | Dytor, forsyy, nbqq, NEOFRAG, PR  |
|           50 |      744 | 2024-07-14 | The Suspect     | W   | 1.000      | -            | -                | -                | -         |     5.04 | Dytor, forsyy, nbqq, NEOFRAG, PR  |
|           49 |      750 | 2024-07-13 | ALTERNATE aTTaX | W   | 1.000      | -            | -                | -                | -         |     6.03 | Dytor, forsyy, K1-FiDa, nbqq, PR  |
|           48 |      842 | 2024-07-08 | Hungary         | W   | 1.000      | -            | -                | -                | -         |     4.34 | Dytor, forsyy, K1-FiDa, nbqq, PR  |
|           47 |      995 | 2024-06-14 | 5W              | L   | 0.865      | -            | -                | -                | -         |   -19.28 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           46 |     1062 | 2024-06-11 | PERA            | L   | 0.847      | -            | -                | -                | -         |   -20.13 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           45 |     1141 | 2024-06-09 | Enterprise      | W   | 0.832      | 0.450        | 0.039 (0.015)    | 0.646 (0.242)    | -         |     5.12 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           44 |     1210 | 2024-06-08 | MOUZ NXT        | W   | 0.825      | 0.450        | 0.139 (0.052)    | 1.000 (0.371)    | -         |    11.10 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           43 |     1270 | 2024-06-07 | GhoulsW         | W   | 0.818      | -            | -                | -                | -         |     0.39 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           42 |     1301 | 2024-06-06 | GamerLegion     | L   | 0.814      | -            | -                | -                | -         |   -12.34 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           41 |     1465 | 2024-06-02 | UNiTY           | W   | 0.786      | 0.346        | 0.025 (0.007)    | -                | 1 (0.786) |     6.54 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           40 |     1494 | 2024-06-01 | UNiTY           | W   | 0.780      | 0.346        | 0.025 (0.007)    | -                | 1 (0.780) |     6.69 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           39 |     1528 | 2024-05-31 | Sampi           | W   | 0.774      | 0.346        | 0.028 (0.007)    | 1.000 (0.268)    | 1 (0.774) |     5.15 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           38 |     1652 | 2024-05-26 | Permitta        | L   | 0.738      | -            | -                | -                | -         |   -18.46 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           37 |     1740 | 2024-05-22 | Preasy          | L   | 0.712      | -            | -                | -                | -         |   -20.09 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           36 |     2079 | 2024-05-13 | Johnny Speeds   | L   | 0.651      | -            | -                | -                | -         |    -7.80 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           35 |     2149 | 2024-05-10 | Verdant         | W   | 0.632      | -            | -                | -                | -         |     4.03 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           34 |     2341 | 2024-04-30 | MOUZ NXT        | L   | 0.567      | -            | -                | -                | -         |   -12.56 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           33 |     2368 | 2024-04-29 | 1WIN            | W   | 0.559      | 0.500        | 0.027 (0.007)    | 0.650 (0.182)    | -         |     3.10 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           32 |     2405 | 2024-04-27 | MOUZ NXT        | L   | 0.547      | -            | -                | -                | -         |   -12.52 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           31 |     2475 | 2024-04-25 | Sampi           | W   | 0.531      | 0.371        | -                | 1.000 (0.197)    | -         |     3.02 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           30 |     2513 | 2024-04-23 | Sampi           | W   | 0.518      | 0.371        | -                | 1.000 (0.192)    | -         |     2.90 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           29 |     2545 | 2024-04-21 | MOUZ NXT        | W   | 0.505      | 0.371        | 0.139 (0.026)    | 1.000 (0.187)    | -         |     4.71 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           28 |     2629 | 2024-04-19 | SINNERS         | W   | 0.491      | 0.371        | 0.037 (0.007)    | 0.784 (0.143)    | -         |     6.04 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           27 |     2711 | 2024-04-17 | Alliance        | W   | 0.478      | -            | -                | -                | -         |     2.08 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           26 |     2763 | 2024-04-15 | Astralis Talent | W   | 0.464      | -            | -                | -                | -         |     1.32 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           25 |     2933 | 2024-04-09 | ALTERNATE aTTaX | L   | 0.425      | -            | -                | -                | -         |   -10.47 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           24 |     3022 | 2024-04-05 | UNiTY           | L   | 0.398      | -            | -                | -                | -         |    -9.95 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           23 |     3069 | 2024-04-04 | PGE Turow       | W   | 0.391      | -            | -                | -                | -         |     0.57 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           22 |     3109 | 2024-04-03 | Permitta        | W   | 0.385      | 0.333        | -                | 0.887 (0.114)    | -         |     2.48 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           21 |     3390 | 2024-03-17 | SINNERS         | W   | 0.274      | -            | -                | -                | 1 (0.274) |     2.95 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           20 |     3408 | 2024-03-16 | UNiTY           | W   | 0.267      | -            | -                | -                | 1 (0.267) |     1.81 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           19 |     3428 | 2024-03-15 | Sampi           | W   | 0.259      | -            | -                | -                | 1 (0.259) |     1.34 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           18 |     3432 | 2024-03-15 | Sashi           | L   | 0.258      | -            | -                | -                | -         |    -4.87 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           17 |     3498 | 2024-03-13 | Permitta        | L   | 0.246      | -            | -                | -                | -         |    -6.17 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           16 |     3513 | 2024-03-13 | Permitta        | L   | 0.244      | -            | -                | -                | -         |    -6.23 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           15 |     3555 | 2024-03-11 | Entropiq        | L   | 0.231      | -            | -                | -                | -         |    -7.10 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           14 |     3573 | 2024-03-10 | Zero Tenacity   | L   | 0.226      | -            | -                | -                | -         |    -4.73 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           13 |     3716 | 2024-03-05 | 9INE            | W   | 0.192      | -            | -                | -                | -         |     0.11 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           12 |     3760 | 2024-03-03 | Metizport       | W   | 0.179      | -            | -                | -                | -         |     0.81 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           11 |     3801 | 2024-03-01 | Viperio         | W   | 0.164      | -            | -                | -                | -         |     0.05 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           10 |     3829 | 2024-02-28 | Permitta        | W   | 0.151      | -            | -                | -                | -         |     0.86 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            9 |     3847 | 2024-02-27 | MOUZ NXT        | W   | 0.146      | 0.333        | 0.139 (0.007)    | -                | -         |     1.22 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            8 |     3849 | 2024-02-27 | ex-sYnck        | W   | 0.145      | -            | -                | -                | -         |     0.08 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            7 |     3866 | 2024-02-26 | PGE Turow       | W   | 0.138      | -            | -                | -                | -         |     0.18 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            6 |     3888 | 2024-02-25 | Sampi           | W   | 0.131      | -            | -                | -                | -         |     0.57 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            5 |     3921 | 2024-02-24 | Permitta        | L   | 0.125      | -            | -                | -                | -         |    -3.25 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            4 |     3950 | 2024-02-22 | BIG Academy     | W   | 0.112      | -            | -                | -                | -         |     0.04 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            3 |     3988 | 2024-02-21 | Permitta        | W   | 0.104      | -            | -                | -                | -         |     0.58 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            2 |     4005 | 2024-02-20 | NAVI Junior     | W   | 0.099      | -            | -                | -                | -         |     0.15 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            1 |     4033 | 2024-02-19 | Permitta        | L   | 0.092      | -            | -                | -                | -         |    -2.39 | Blytz, Dytor, forsyy, kreaz, nbqq |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($20,463.92)
- Divide that value by the 5th highest value among all rosters ($325,971.18)
- The final value (0.06) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-17 |      0.885 | $2,500.00      | $2,212.62       |
| 2024-06-13 |      0.861 | $545.00        | $468.98         |
| 2024-06-02 |      0.786 | $7,837.00      | $6,162.93       |
| 2024-05-13 |      0.651 | $3,000.00      | $1,952.64       |
| 2024-04-25 |      0.531 | $11,000.00     | $5,839.68       |
| 2024-04-06 |      0.404 | $1,500.00      | $606.32         |
| 2024-03-17 |      0.274 | $7,675.00      | $2,099.25       |
| 2024-02-28 |      0.151 | $5,000.00      | $755.79         |
| 2024-02-21 |      0.104 | $3,500.00      | $365.72         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
