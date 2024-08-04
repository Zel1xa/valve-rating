### Roster Details<br />
Team Name: ECLOT<br />
Roster: Blytz, Dytor, forsyy, kreaz, nbqq<br />
Global Rank: [47](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [35]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1081.3<br />
<br />
Final Rank Value (1081.3) = Starting Rank Value (1220.0) + Head To Head Adjustments (-138.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.454[<sup>1</sup>](#table2)
- Bounty Collected: 0.353[<sup>2</sup>](#table1)
- Opponent Network: 0.213[<sup>2</sup>](#table1)
- LAN Wins: 0.585[<sup>2</sup>](#table1)

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
|           57 |        3 | 2024-08-03 | AVEZ            | W   | 1.000      | -            | -                | -                | 1 (1.000) |     1.71 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           56 |       35 | 2024-08-02 | SINNERS         | W   | 1.000      | 0.345        | 0.037 (0.013)    | 0.758 (0.262)    | 1 (1.000) |    10.54 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           55 |      176 | 2024-07-30 | 1WIN            | W   | 1.000      | -            | -                | -                | 0 (0.000) |    11.51 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           54 |      219 | 2024-07-29 | DASH            | L   | 1.000      | -            | -                | -                | -         |   -29.70 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           53 |      333 | 2024-07-25 | HAVU            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.45 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           52 |      703 | 2024-07-16 | FAVBET          | L   | 1.000      | -            | -                | -                | -         |   -25.40 | Dytor, forsyy, kreaz, nbqq, olik  |
|           51 |      761 | 2024-07-14 | The Suspect     | L   | 1.000      | -            | -                | -                | -         |   -25.50 | Dytor, forsyy, nbqq, NEOFRAG, PR  |
|           50 |      772 | 2024-07-14 | The Suspect     | W   | 1.000      | -            | -                | -                | -         |     5.05 | Dytor, forsyy, nbqq, NEOFRAG, PR  |
|           49 |      778 | 2024-07-13 | ALTERNATE aTTaX | W   | 1.000      | -            | -                | -                | -         |     6.05 | Dytor, forsyy, K1-FiDa, nbqq, PR  |
|           48 |      872 | 2024-07-08 | Hungary         | W   | 1.000      | -            | -                | -                | -         |     4.36 | Dytor, forsyy, K1-FiDa, nbqq, PR  |
|           47 |     1045 | 2024-06-14 | 5W              | L   | 0.864      | -            | -                | -                | -         |   -19.24 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           46 |     1114 | 2024-06-11 | PERA            | L   | 0.845      | -            | -                | -                | -         |   -20.04 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           45 |     1196 | 2024-06-09 | Enterprise      | W   | 0.831      | 0.450        | 0.039 (0.015)    | 0.624 (0.233)    | -         |     5.11 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           44 |     1270 | 2024-06-08 | MOUZ NXT        | W   | 0.824      | 0.450        | 0.139 (0.052)    | 1.000 (0.371)    | -         |    11.21 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           43 |     1330 | 2024-06-07 | GhoulsW         | W   | 0.816      | -            | -                | -                | -         |     0.40 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           42 |     1361 | 2024-06-06 | GamerLegion     | L   | 0.812      | -            | -                | -                | -         |   -12.11 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           41 |     1527 | 2024-06-02 | UNiTY           | W   | 0.785      | 0.346        | 0.025 (0.007)    | -                | 1 (0.785) |     6.55 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           40 |     1559 | 2024-06-01 | UNiTY           | W   | 0.778      | 0.346        | 0.025 (0.007)    | -                | 1 (0.778) |     6.70 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           39 |     1591 | 2024-05-31 | Sampi           | W   | 0.772      | 0.346        | 0.027 (0.007)    | 1.000 (0.267)    | 1 (0.772) |     5.14 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           38 |     1716 | 2024-05-26 | Permitta        | L   | 0.736      | -            | -                | -                | -         |   -18.39 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           37 |     1804 | 2024-05-22 | Preasy          | L   | 0.710      | -            | -                | -                | -         |   -20.03 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           36 |     2144 | 2024-05-13 | Johnny Speeds   | L   | 0.649      | -            | -                | -                | -         |    -7.77 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           35 |     2214 | 2024-05-10 | Verdant         | W   | 0.630      | -            | -                | -                | -         |     4.04 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           34 |     2407 | 2024-04-30 | MOUZ NXT        | L   | 0.565      | -            | -                | -                | -         |   -12.39 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           33 |     2434 | 2024-04-29 | 1WIN            | W   | 0.558      | 0.500        | 0.027 (0.007)    | 0.629 (0.175)    | -         |     3.09 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           32 |     2471 | 2024-04-27 | MOUZ NXT        | L   | 0.545      | -            | -                | -                | -         |   -12.35 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           31 |     2541 | 2024-04-25 | Sampi           | W   | 0.529      | 0.371        | -                | 1.000 (0.196)    | -         |     3.01 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           30 |     2579 | 2024-04-23 | Sampi           | W   | 0.516      | 0.371        | -                | 1.000 (0.191)    | -         |     2.89 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           29 |     2611 | 2024-04-21 | MOUZ NXT        | W   | 0.503      | 0.371        | 0.139 (0.026)    | 1.000 (0.186)    | -         |     4.84 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           28 |     2695 | 2024-04-19 | SINNERS         | W   | 0.489      | 0.371        | 0.037 (0.007)    | 0.758 (0.137)    | -         |     6.01 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           27 |     2777 | 2024-04-17 | Alliance        | W   | 0.476      | -            | -                | -                | -         |     2.09 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           26 |     2829 | 2024-04-15 | Astralis Talent | W   | 0.463      | -            | -                | -                | -         |     1.35 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           25 |     3000 | 2024-04-09 | ALTERNATE aTTaX | L   | 0.423      | -            | -                | -                | -         |   -10.41 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           24 |     3088 | 2024-04-05 | UNiTY           | L   | 0.396      | -            | -                | -                | -         |    -9.88 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           23 |     3135 | 2024-04-04 | PGE Turow       | W   | 0.389      | -            | -                | -                | -         |     0.57 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           22 |     3175 | 2024-04-03 | Permitta        | W   | 0.383      | 0.333        | -                | 0.876 (0.112)    | -         |     2.49 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           21 |     3461 | 2024-03-17 | SINNERS         | W   | 0.272      | -            | -                | -                | 1 (0.272) |     2.93 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           20 |     3479 | 2024-03-16 | UNiTY           | W   | 0.265      | -            | -                | -                | 1 (0.265) |     1.81 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           19 |     3500 | 2024-03-15 | Sampi           | W   | 0.258      | -            | -                | -                | 1 (0.258) |     1.33 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           18 |     3504 | 2024-03-15 | Sashi           | L   | 0.256      | -            | -                | -                | -         |    -4.83 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           17 |     3570 | 2024-03-13 | Permitta        | L   | 0.244      | -            | -                | -                | -         |    -6.11 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           16 |     3585 | 2024-03-13 | Permitta        | L   | 0.243      | -            | -                | -                | -         |    -6.17 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           15 |     3628 | 2024-03-11 | Entropiq        | L   | 0.229      | -            | -                | -                | -         |    -7.04 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           14 |     3646 | 2024-03-10 | Zero Tenacity   | L   | 0.224      | -            | -                | -                | -         |    -4.66 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           13 |     3789 | 2024-03-05 | 9INE            | W   | 0.190      | -            | -                | -                | -         |     0.11 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           12 |     3833 | 2024-03-03 | Metizport       | W   | 0.177      | -            | -                | -                | -         |     0.82 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           11 |     3874 | 2024-03-01 | Viperio         | W   | 0.163      | -            | -                | -                | -         |     0.05 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           10 |     3902 | 2024-02-28 | Permitta        | W   | 0.149      | -            | -                | -                | -         |     0.86 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            9 |     3920 | 2024-02-27 | MOUZ NXT        | W   | 0.144      | 0.333        | 0.139 (0.007)    | -                | -         |     1.26 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            8 |     3922 | 2024-02-27 | ex-sYnck        | W   | 0.143      | -            | -                | -                | -         |     0.08 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            7 |     3939 | 2024-02-26 | PGE Turow       | W   | 0.136      | -            | -                | -                | -         |     0.18 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            6 |     3961 | 2024-02-25 | Sampi           | W   | 0.129      | -            | -                | -                | -         |     0.56 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            5 |     3994 | 2024-02-24 | Permitta        | L   | 0.123      | -            | -                | -                | -         |    -3.19 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            4 |     4023 | 2024-02-22 | BIG Academy     | W   | 0.110      | -            | -                | -                | -         |     0.04 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            3 |     4061 | 2024-02-21 | Permitta        | W   | 0.103      | -            | -                | -                | -         |     0.58 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            2 |     4078 | 2024-02-20 | NAVI Junior     | W   | 0.097      | -            | -                | -                | -         |     0.15 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            1 |     4106 | 2024-02-19 | Permitta        | L   | 0.090      | -            | -                | -                | -         |    -2.34 | Blytz, Dytor, forsyy, kreaz, nbqq |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($20,391.02)
- Divide that value by the 5th highest value among all rosters ($325,463.29)
- The final value (0.06) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-17 |      0.883 | $2,500.00      | $2,208.33       |
| 2024-06-13 |      0.859 | $545.00        | $468.04         |
| 2024-06-02 |      0.785 | $7,837.00      | $6,149.51       |
| 2024-05-13 |      0.649 | $3,000.00      | $1,947.50       |
| 2024-04-25 |      0.529 | $11,000.00     | $5,820.83       |
| 2024-04-06 |      0.403 | $1,500.00      | $603.75         |
| 2024-03-17 |      0.272 | $7,675.00      | $2,086.11       |
| 2024-02-28 |      0.149 | $5,000.00      | $747.22         |
| 2024-02-21 |      0.103 | $3,500.00      | $359.72         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
