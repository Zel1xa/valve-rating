### Roster Details<br />
Team Name: ECLOT<br />
Roster: Blytz, Dytor, forsyy, kreaz, nbqq<br />
Global Rank: [47](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [35]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1081.1<br />
<br />
Final Rank Value (1081.1) = Starting Rank Value (1219.1) + Head To Head Adjustments (-138.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.454[<sup>1</sup>](#table2)
- Bounty Collected: 0.353[<sup>2</sup>](#table1)
- Opponent Network: 0.212[<sup>2</sup>](#table1)
- LAN Wins: 0.584[<sup>2</sup>](#table1)

The average of these factors is 0.401<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1219.1
- 400 + ( ( 0.401 - 0.000 ) / ( 0.783 - 0.000 ) ) * 1600 = 1219.1


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
|           57 |        6 | 2024-08-03 | AVEZ            | W   | 1.000      | -            | -                | -                | 1 (1.000) |     1.72 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           56 |       38 | 2024-08-02 | SINNERS         | W   | 1.000      | 0.345        | 0.037 (0.013)    | 0.758 (0.262)    | 1 (1.000) |    10.53 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           55 |      179 | 2024-07-30 | 1WIN            | W   | 1.000      | -            | -                | -                | 0 (0.000) |    11.49 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           54 |      222 | 2024-07-29 | DASH            | L   | 1.000      | -            | -                | -                | -         |   -29.70 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           53 |      336 | 2024-07-25 | HAVU            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.44 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           52 |      706 | 2024-07-16 | FAVBET          | L   | 1.000      | -            | -                | -                | -         |   -25.41 | Dytor, forsyy, kreaz, nbqq, olik  |
|           51 |      764 | 2024-07-14 | The Suspect     | L   | 1.000      | -            | -                | -                | -         |   -25.50 | Dytor, forsyy, nbqq, NEOFRAG, PR  |
|           50 |      775 | 2024-07-14 | The Suspect     | W   | 1.000      | -            | -                | -                | -         |     5.05 | Dytor, forsyy, nbqq, NEOFRAG, PR  |
|           49 |      781 | 2024-07-13 | ALTERNATE aTTaX | W   | 1.000      | -            | -                | -                | -         |     6.06 | Dytor, forsyy, K1-FiDa, nbqq, PR  |
|           48 |      876 | 2024-07-08 | Hungary         | W   | 1.000      | -            | -                | -                | -         |     4.36 | Dytor, forsyy, K1-FiDa, nbqq, PR  |
|           47 |     1049 | 2024-06-14 | 5W              | L   | 0.861      | -            | -                | -                | -         |   -19.18 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           46 |     1118 | 2024-06-11 | PERA            | L   | 0.842      | -            | -                | -                | -         |   -19.97 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           45 |     1200 | 2024-06-09 | Enterprise      | W   | 0.828      | 0.450        | 0.039 (0.015)    | 0.625 (0.233)    | -         |     5.09 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           44 |     1274 | 2024-06-08 | MOUZ NXT        | W   | 0.821      | 0.450        | 0.139 (0.051)    | 1.000 (0.369)    | -         |    11.15 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           43 |     1334 | 2024-06-07 | GhoulsW         | W   | 0.813      | -            | -                | -                | -         |     0.40 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           42 |     1365 | 2024-06-06 | GamerLegion     | L   | 0.809      | -            | -                | -                | -         |   -12.09 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           41 |     1531 | 2024-06-02 | UNiTY           | W   | 0.782      | 0.346        | 0.025 (0.007)    | -                | 1 (0.782) |     6.52 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           40 |     1563 | 2024-06-01 | UNiTY           | W   | 0.775      | 0.346        | 0.025 (0.007)    | -                | 1 (0.775) |     6.67 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           39 |     1595 | 2024-05-31 | Sampi           | W   | 0.769      | 0.346        | 0.027 (0.007)    | 1.000 (0.266)    | 1 (0.769) |     5.12 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           38 |     1720 | 2024-05-26 | Permitta        | L   | 0.733      | -            | -                | -                | -         |   -18.32 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           37 |     1808 | 2024-05-22 | Preasy          | L   | 0.707      | -            | -                | -                | -         |   -19.94 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           36 |     2148 | 2024-05-13 | Johnny Speeds   | L   | 0.646      | -            | -                | -                | -         |    -7.72 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           35 |     2218 | 2024-05-10 | Verdant         | W   | 0.627      | -            | -                | -                | -         |     4.03 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           34 |     2411 | 2024-04-30 | MOUZ NXT        | L   | 0.562      | -            | -                | -                | -         |   -12.32 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           33 |     2438 | 2024-04-29 | 1WIN            | W   | 0.555      | 0.500        | 0.027 (0.007)    | 0.628 (0.174)    | -         |     3.07 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           32 |     2475 | 2024-04-27 | MOUZ NXT        | L   | 0.542      | -            | -                | -                | -         |   -12.28 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           31 |     2546 | 2024-04-25 | Sampi           | W   | 0.526      | 0.371        | -                | 1.000 (0.195)    | -         |     2.99 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           30 |     2584 | 2024-04-23 | Sampi           | W   | 0.513      | 0.371        | -                | 1.000 (0.190)    | -         |     2.87 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           29 |     2616 | 2024-04-21 | MOUZ NXT        | W   | 0.500      | 0.371        | 0.139 (0.026)    | 1.000 (0.185)    | -         |     4.81 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           28 |     2700 | 2024-04-19 | SINNERS         | W   | 0.486      | 0.371        | 0.037 (0.007)    | 0.758 (0.136)    | -         |     5.97 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           27 |     2782 | 2024-04-17 | Alliance        | W   | 0.473      | -            | -                | -                | -         |     2.07 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           26 |     2834 | 2024-04-15 | Astralis Talent | W   | 0.459      | -            | -                | -                | -         |     1.35 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           25 |     3005 | 2024-04-09 | ALTERNATE aTTaX | L   | 0.420      | -            | -                | -                | -         |   -10.33 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           24 |     3093 | 2024-04-05 | UNiTY           | L   | 0.393      | -            | -                | -                | -         |    -9.81 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           23 |     3140 | 2024-04-04 | PGE Turow       | W   | 0.386      | -            | -                | -                | -         |     0.57 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           22 |     3180 | 2024-04-03 | Permitta        | W   | 0.380      | 0.333        | -                | 0.876 (0.111)    | -         |     2.47 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           21 |     3466 | 2024-03-17 | SINNERS         | W   | 0.269      | -            | -                | -                | 1 (0.269) |     2.90 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           20 |     3484 | 2024-03-16 | UNiTY           | W   | 0.262      | -            | -                | -                | 1 (0.262) |     1.79 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           19 |     3505 | 2024-03-15 | Sampi           | W   | 0.254      | -            | -                | -                | 1 (0.254) |     1.31 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           18 |     3509 | 2024-03-15 | Sashi           | L   | 0.253      | -            | -                | -                | -         |    -4.77 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           17 |     3576 | 2024-03-13 | Permitta        | L   | 0.241      | -            | -                | -                | -         |    -6.03 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           16 |     3591 | 2024-03-13 | Permitta        | L   | 0.240      | -            | -                | -                | -         |    -6.09 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           15 |     3634 | 2024-03-11 | Entropiq        | L   | 0.226      | -            | -                | -                | -         |    -6.95 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           14 |     3652 | 2024-03-10 | Zero Tenacity   | L   | 0.221      | -            | -                | -                | -         |    -4.59 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           13 |     3795 | 2024-03-05 | 9INE            | W   | 0.187      | -            | -                | -                | -         |     0.10 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           12 |     3839 | 2024-03-03 | Metizport       | W   | 0.174      | -            | -                | -                | -         |     0.80 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           11 |     3880 | 2024-03-01 | Viperio         | W   | 0.160      | -            | -                | -                | -         |     0.05 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           10 |     3908 | 2024-02-28 | Permitta        | W   | 0.146      | -            | -                | -                | -         |     0.84 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            9 |     3926 | 2024-02-27 | MOUZ NXT        | W   | 0.141      | 0.333        | 0.139 (0.007)    | -                | -         |     1.23 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            8 |     3928 | 2024-02-27 | ex-sYnck        | W   | 0.140      | -            | -                | -                | -         |     0.08 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            7 |     3945 | 2024-02-26 | PGE Turow       | W   | 0.133      | -            | -                | -                | -         |     0.17 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            6 |     3967 | 2024-02-25 | Sampi           | W   | 0.126      | -            | -                | -                | -         |     0.55 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            5 |     4000 | 2024-02-24 | Permitta        | L   | 0.120      | -            | -                | -                | -         |    -3.11 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            4 |     4029 | 2024-02-22 | BIG Academy     | W   | 0.107      | -            | -                | -                | -         |     0.03 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            3 |     4067 | 2024-02-21 | Permitta        | W   | 0.100      | -            | -                | -                | -         |     0.56 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            2 |     4084 | 2024-02-20 | NAVI Junior     | W   | 0.094      | -            | -                | -                | -         |     0.15 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            1 |     4112 | 2024-02-19 | Permitta        | L   | 0.087      | -            | -                | -                | -         |    -2.26 | Blytz, Dytor, forsyy, kreaz, nbqq |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($20,260.98)
- Divide that value by the 5th highest value among all rosters ($324,557.31)
- The final value (0.06) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-17 |      0.880 | $2,500.00      | $2,200.69       |
| 2024-06-13 |      0.856 | $545.00        | $466.38         |
| 2024-06-02 |      0.782 | $7,837.00      | $6,125.56       |
| 2024-05-13 |      0.646 | $3,000.00      | $1,938.33       |
| 2024-04-25 |      0.526 | $11,000.00     | $5,787.22       |
| 2024-04-06 |      0.399 | $1,500.00      | $599.17         |
| 2024-03-17 |      0.269 | $7,675.00      | $2,062.66       |
| 2024-02-28 |      0.146 | $5,000.00      | $731.94         |
| 2024-02-21 |      0.100 | $3,500.00      | $349.03         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
