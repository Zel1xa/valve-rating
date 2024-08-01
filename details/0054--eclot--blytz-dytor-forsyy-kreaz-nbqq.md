### Roster Details<br />
Team Name: ECLOT<br />
Roster: Blytz, Dytor, forsyy, kreaz, nbqq<br />
Global Rank: [54](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [40]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1021.8<br />
<br />
Final Rank Value (1021.8) = Starting Rank Value (1109.7) + Head To Head Adjustments (-87.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.456[<sup>1</sup>](#table2)
- Bounty Collected: 0.352[<sup>2</sup>](#table1)
- Opponent Network: 0.200[<sup>2</sup>](#table1)
- LAN Wins: 0.371[<sup>2</sup>](#table1)

The average of these factors is 0.345<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1109.7
- 400 + ( ( 0.345 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1109.7


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
|           55 |       95 | 2024-07-30 | 1WIN            | W   | 1.000      | -            | -                | -                | 0 (0.000) |    13.65 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           54 |      138 | 2024-07-29 | DASH            | L   | 1.000      | -            | -                | -                | -         |   -29.16 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           53 |      252 | 2024-07-25 | HAVU            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     4.51 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           52 |      634 | 2024-07-16 | FAVBET          | L   | 1.000      | -            | -                | -                | -         |   -23.70 | Dytor, forsyy, kreaz, nbqq, olik  |
|           51 |      695 | 2024-07-14 | The Suspect     | L   | 1.000      | -            | -                | -                | -         |   -23.86 | Dytor, forsyy, nbqq, NEOFRAG, PR  |
|           50 |      707 | 2024-07-14 | The Suspect     | W   | 1.000      | -            | -                | -                | 0 (0.000) |     6.61 | Dytor, forsyy, nbqq, NEOFRAG, PR  |
|           49 |      714 | 2024-07-13 | ALTERNATE aTTaX | W   | 1.000      | -            | -                | -                | 0 (0.000) |     7.02 | Dytor, forsyy, K1-FiDa, nbqq, PR  |
|           48 |      809 | 2024-07-08 | Hungary         | W   | 1.000      | -            | -                | -                | -         |     5.89 | Dytor, forsyy, K1-FiDa, nbqq, PR  |
|           47 |      971 | 2024-06-14 | 5W              | L   | 0.879      | -            | -                | -                | -         |   -17.32 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           46 |     1041 | 2024-06-11 | PERA            | L   | 0.860      | -            | -                | -                | -         |   -18.49 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           45 |     1124 | 2024-06-09 | Enterprise      | W   | 0.846      | 0.450        | 0.040 (0.015)    | 0.622 (0.237)    | -         |     6.81 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           44 |     1201 | 2024-06-08 | MOUZ NXT        | W   | 0.839      | 0.450        | 0.141 (0.053)    | 1.000 (0.377)    | -         |    14.17 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           43 |     1267 | 2024-06-07 | GhoulsW         | W   | 0.831      | -            | -                | -                | -         |     1.11 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           42 |     1300 | 2024-06-06 | GamerLegion     | L   | 0.827      | -            | -                | -                | -         |    -9.81 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           41 |     1470 | 2024-06-02 | UNiTY           | W   | 0.800      | 0.346        | 0.025 (0.007)    | -                | 1 (0.800) |     8.68 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           40 |     1501 | 2024-06-01 | UNiTY           | W   | 0.793      | 0.346        | 0.025 (0.007)    | -                | 1 (0.793) |     8.98 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           39 |     1534 | 2024-05-31 | Sampi           | W   | 0.787      | 0.346        | 0.028 (0.008)    | 1.000 (0.272)    | 1 (0.787) |     7.09 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           38 |     1661 | 2024-05-26 | Permitta        | L   | 0.751      | -            | -                | -                | -         |   -16.95 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           37 |     1759 | 2024-05-22 | Preasy          | L   | 0.725      | -            | -                | -                | -         |   -19.28 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           36 |     2124 | 2024-05-13 | Johnny Speeds   | L   | 0.664      | -            | -                | -                | -         |    -5.69 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           35 |     2194 | 2024-05-10 | Verdant         | W   | 0.645      | -            | -                | -                | -         |     6.13 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           34 |     2392 | 2024-04-30 | MOUZ NXT        | L   | 0.580      | -            | -                | -                | -         |   -10.41 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           33 |     2419 | 2024-04-29 | 1WIN            | W   | 0.573      | 0.500        | 0.027 (0.008)    | 0.629 (0.180)    | -         |     4.69 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           32 |     2456 | 2024-04-27 | MOUZ NXT        | L   | 0.560      | -            | -                | -                | -         |   -10.38 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           31 |     2527 | 2024-04-25 | Sampi           | W   | 0.544      | 0.371        | 0.028 (0.006)    | 1.000 (0.202)    | -         |     4.43 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           30 |     2567 | 2024-04-23 | Sampi           | W   | 0.531      | 0.371        | -                | 1.000 (0.197)    | -         |     4.31 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           29 |     2601 | 2024-04-21 | MOUZ NXT        | W   | 0.518      | 0.371        | 0.141 (0.027)    | 1.000 (0.192)    | -         |     7.25 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           28 |     2688 | 2024-04-19 | SINNERS         | W   | 0.504      | 0.371        | 0.038 (0.007)    | 0.768 (0.144)    | -         |     7.68 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           27 |     2772 | 2024-04-17 | Alliance        | W   | 0.491      | -            | -                | -                | -         |     3.40 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           26 |     2825 | 2024-04-15 | Astralis Talent | W   | 0.477      | -            | -                | -                | -         |     2.37 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           25 |     2996 | 2024-04-09 | ALTERNATE aTTaX | L   | 0.438      | -            | -                | -                | -         |    -9.26 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           24 |     3085 | 2024-04-05 | UNiTY           | L   | 0.411      | -            | -                | -                | -         |    -8.91 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           23 |     3133 | 2024-04-04 | PGE Turow       | W   | 0.404      | -            | -                | -                | -         |     1.03 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           22 |     3178 | 2024-04-03 | Permitta        | W   | 0.398      | 0.333        | -                | 0.801 (0.106)    | -         |     3.84 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           21 |     3471 | 2024-03-17 | SINNERS         | W   | 0.287      | -            | -                | -                | 1 (0.287) |     3.94 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           20 |     3489 | 2024-03-16 | UNiTY           | W   | 0.280      | -            | -                | -                | 1 (0.280) |     2.92 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           19 |     3510 | 2024-03-15 | Sampi           | W   | 0.273      | 0.345        | -                | 1.000 (0.094)    | 1 (0.273) |     2.29 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           18 |     3514 | 2024-03-15 | Sashi           | L   | 0.271      | -            | -                | -                | -         |    -3.79 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           17 |     3585 | 2024-03-13 | Permitta        | L   | 0.259      | -            | -                | -                | -         |    -5.63 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           16 |     3600 | 2024-03-13 | Permitta        | L   | 0.258      | -            | -                | -                | -         |    -5.71 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           15 |     3644 | 2024-03-11 | Entropiq        | L   | 0.244      | -            | -                | -                | -         |    -7.35 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           14 |     3662 | 2024-03-10 | Zero Tenacity   | L   | 0.239      | -            | -                | -                | -         |    -3.91 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           13 |     3811 | 2024-03-05 | 9INE            | W   | 0.205      | -            | -                | -                | -         |     0.20 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           12 |     3855 | 2024-03-03 | Metizport       | W   | 0.192      | -            | -                | -                | -         |     1.44 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           11 |     3897 | 2024-03-01 | Viperio         | W   | 0.178      | -            | -                | -                | -         |     0.10 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           10 |     3926 | 2024-02-28 | Permitta        | W   | 0.164      | -            | -                | -                | -         |     1.47 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            9 |     3944 | 2024-02-27 | MOUZ NXT        | W   | 0.159      | 0.333        | 0.141 (0.007)    | -                | -         |     2.21 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            8 |     3946 | 2024-02-27 | ex-sYnck        | W   | 0.158      | -            | -                | -                | -         |     0.16 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            7 |     3964 | 2024-02-26 | PGE Turow       | W   | 0.151      | -            | -                | -                | -         |     0.36 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            6 |     3987 | 2024-02-25 | Sampi           | W   | 0.144      | -            | -                | -                | -         |     1.06 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            5 |     4022 | 2024-02-24 | Permitta        | L   | 0.138      | -            | -                | -                | -         |    -3.15 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            4 |     4054 | 2024-02-22 | BIG Academy     | W   | 0.125      | -            | -                | -                | -         |     0.07 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            3 |     4093 | 2024-02-21 | Permitta        | W   | 0.118      | -            | -                | -                | -         |     1.03 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            2 |     4110 | 2024-02-20 | NAVI Junior     | W   | 0.112      | -            | -                | -                | -         |     0.32 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            1 |     4138 | 2024-02-19 | Permitta        | L   | 0.105      | -            | -                | -                | -         |    -2.41 | Blytz, Dytor, forsyy, kreaz, nbqq |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($21,029.37)
- Divide that value by the 5th highest value among all rosters ($327,030.46)
- The final value (0.06) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-17 |      0.898 | $2,500.00      | $2,245.83       |
| 2024-06-13 |      0.874 | $545.00        | $476.22         |
| 2024-06-02 |      0.800 | $7,837.00      | $6,267.06       |
| 2024-05-13 |      0.664 | $3,000.00      | $1,992.50       |
| 2024-04-25 |      0.544 | $11,000.00     | $5,985.83       |
| 2024-04-06 |      0.417 | $1,500.00      | $626.25         |
| 2024-03-17 |      0.287 | $7,675.00      | $2,201.23       |
| 2024-02-28 |      0.164 | $5,000.00      | $822.22         |
| 2024-02-21 |      0.118 | $3,500.00      | $412.22         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
