### Roster Details<br />
Team Name: ECLOT<br />
Roster: Blytz, Dytor, forsyy, kreaz, nbqq<br />
Global Rank: [48](../../standings_global_2024_08_06.md)<br />
<br />
Region: [Europe]( ../../standings_europe_2024_08_06.md)<br />
Regional Rank: [35]( ../../standings_europe_2024_08_06.md)<br />
<br />
Final Rank Value:  1091.4<br />
<br />
Final Rank Value (1091.4) = Starting Rank Value (1220.2) + Head To Head Adjustments (-128.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.452[<sup>1</sup>](#table2)
- Bounty Collected: 0.352[<sup>2</sup>](#table1)
- Opponent Network: 0.211[<sup>2</sup>](#table1)
- LAN Wins: 0.580[<sup>2</sup>](#table1)

The average of these factors is 0.399<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1220.2
- 400 + ( ( 0.399 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1220.2


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
|           57 |       87 | 2024-08-03 | AVEZ            | W   | 1.000      | -            | -                | -                | 1 (1.000) |     3.48 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           56 |      119 | 2024-08-02 | SINNERS         | W   | 1.000      | 0.345        | 0.037 (0.013)    | 0.800 (0.276)    | 1 (1.000) |    11.24 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           55 |      262 | 2024-07-30 | 1WIN            | W   | 1.000      | -            | -                | -                | 0 (0.000) |    12.40 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           54 |      306 | 2024-07-29 | DASH            | L   | 1.000      | -            | -                | -                | -         |   -29.76 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           53 |      420 | 2024-07-25 | HAVU            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.34 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           52 |      791 | 2024-07-16 | FAVBET          | L   | 1.000      | -            | -                | -                | -         |   -25.37 | Dytor, forsyy, kreaz, nbqq, olik  |
|           51 |      847 | 2024-07-14 | The Suspect     | L   | 1.000      | -            | -                | -                | -         |   -25.59 | Dytor, forsyy, nbqq, NEOFRAG, PR  |
|           50 |      858 | 2024-07-14 | The Suspect     | W   | 1.000      | -            | -                | -                | -         |     4.96 | Dytor, forsyy, nbqq, NEOFRAG, PR  |
|           49 |      864 | 2024-07-13 | ALTERNATE aTTaX | W   | 1.000      | -            | -                | -                | -         |     6.19 | Dytor, forsyy, K1-FiDa, nbqq, PR  |
|           48 |      959 | 2024-07-08 | Hungary         | W   | 1.000      | -            | -                | -                | -         |     4.22 | Dytor, forsyy, K1-FiDa, nbqq, PR  |
|           47 |     1132 | 2024-06-14 | 5W              | L   | 0.845      | -            | -                | -                | -         |   -19.06 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           46 |     1201 | 2024-06-11 | PERA            | L   | 0.827      | -            | -                | -                | -         |   -19.75 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           45 |     1283 | 2024-06-09 | Enterprise      | W   | 0.812      | 0.450        | 0.039 (0.014)    | 0.641 (0.234)    | -         |     5.01 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           44 |     1357 | 2024-06-08 | MOUZ NXT        | W   | 0.805      | 0.450        | 0.139 (0.050)    | 0.961 (0.348)    | -         |    11.08 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           43 |     1417 | 2024-06-07 | GhoulsW         | W   | 0.798      | -            | -                | -                | -         |     0.37 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           42 |     1448 | 2024-06-06 | GamerLegion     | L   | 0.794      | -            | -                | -                | -         |   -12.20 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           41 |     1614 | 2024-06-02 | UNiTY           | W   | 0.766      | 0.346        | 0.024 (0.006)    | -                | 1 (0.766) |     6.38 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           40 |     1646 | 2024-06-01 | UNiTY           | W   | 0.760      | 0.346        | 0.024 (0.006)    | -                | 1 (0.760) |     6.48 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           39 |     1678 | 2024-05-31 | Sampi           | W   | 0.754      | 0.346        | 0.027 (0.007)    | 1.000 (0.261)    | 1 (0.754) |     4.95 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           38 |     1803 | 2024-05-26 | Permitta        | L   | 0.718      | -            | -                | -                | -         |   -17.67 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           37 |     1891 | 2024-05-22 | Preasy          | L   | 0.692      | -            | -                | -                | -         |   -19.62 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           36 |     2231 | 2024-05-13 | Johnny Speeds   | L   | 0.631      | -            | -                | -                | -         |    -7.38 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           35 |     2301 | 2024-05-10 | Verdant         | W   | 0.612      | -            | -                | -                | -         |     3.94 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           34 |     2494 | 2024-04-30 | MOUZ NXT        | L   | 0.547      | -            | -                | -                | -         |   -11.97 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           33 |     2521 | 2024-04-29 | 1WIN            | W   | 0.540      | 0.500        | 0.033 (0.009)    | 0.718 (0.194)    | -         |     3.42 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           32 |     2558 | 2024-04-27 | MOUZ NXT        | L   | 0.527      | -            | -                | -                | -         |   -11.89 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           31 |     2629 | 2024-04-25 | Sampi           | W   | 0.511      | 0.371        | -                | 1.000 (0.189)    | -         |     2.84 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           30 |     2667 | 2024-04-23 | Sampi           | W   | 0.498      | 0.371        | -                | 1.000 (0.185)    | -         |     2.72 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           29 |     2699 | 2024-04-21 | MOUZ NXT        | W   | 0.485      | 0.371        | 0.139 (0.025)    | 0.961 (0.173)    | -         |     4.68 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           28 |     2783 | 2024-04-19 | SINNERS         | W   | 0.471      | 0.371        | 0.037 (0.006)    | 0.800 (0.140)    | -         |     6.77 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           27 |     2865 | 2024-04-17 | Alliance        | W   | 0.458      | -            | -                | -                | -         |     1.97 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           26 |     2917 | 2024-04-15 | Astralis Talent | W   | 0.444      | -            | -                | -                | -         |     1.26 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           25 |     3088 | 2024-04-09 | ALTERNATE aTTaX | L   | 0.405      | -            | -                | -                | -         |    -9.95 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           24 |     3176 | 2024-04-05 | UNiTY           | L   | 0.378      | -            | -                | -                | -         |    -9.45 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           23 |     3223 | 2024-04-04 | PGE Turow       | W   | 0.371      | -            | -                | -                | -         |     0.53 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           22 |     3263 | 2024-04-03 | Permitta        | W   | 0.365      | 0.333        | -                | 0.919 (0.112)    | -         |     2.67 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           21 |     3549 | 2024-03-17 | SINNERS         | W   | 0.254      | -            | -                | -                | 1 (0.254) |     3.35 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           20 |     3567 | 2024-03-16 | UNiTY           | W   | 0.247      | -            | -                | -                | 1 (0.247) |     1.67 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           19 |     3588 | 2024-03-15 | Sampi           | W   | 0.239      | -            | -                | -                | 1 (0.239) |     1.22 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           18 |     3592 | 2024-03-15 | Sashi           | L   | 0.238      | -            | -                | -                | -         |    -4.46 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           17 |     3659 | 2024-03-13 | Permitta        | L   | 0.226      | -            | -                | -                | -         |    -5.45 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           16 |     3674 | 2024-03-13 | Permitta        | L   | 0.225      | -            | -                | -                | -         |    -5.50 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           15 |     3717 | 2024-03-11 | Entropiq        | L   | 0.211      | -            | -                | -                | -         |    -6.49 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           14 |     3735 | 2024-03-10 | Zero Tenacity   | L   | 0.206      | -            | -                | -                | -         |    -4.26 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           13 |     3878 | 2024-03-05 | 9INE            | W   | 0.172      | -            | -                | -                | -         |     0.10 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           12 |     3922 | 2024-03-03 | Metizport       | W   | 0.159      | -            | -                | -                | -         |     0.75 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           11 |     3963 | 2024-03-01 | Viperio         | W   | 0.145      | -            | -                | -                | -         |     0.05 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           10 |     3991 | 2024-02-28 | Permitta        | W   | 0.131      | -            | -                | -                | -         |     0.88 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            9 |     4009 | 2024-02-27 | MOUZ NXT        | W   | 0.126      | 0.333        | 0.139 (0.006)    | -                | -         |     1.12 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            8 |     4011 | 2024-02-27 | ex-sYnck        | W   | 0.125      | -            | -                | -                | -         |     0.07 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            7 |     4028 | 2024-02-26 | PGE Turow       | W   | 0.118      | -            | -                | -                | -         |     0.15 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            6 |     4050 | 2024-02-25 | Sampi           | W   | 0.111      | -            | -                | -                | -         |     0.48 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            5 |     4083 | 2024-02-24 | Permitta        | L   | 0.105      | -            | -                | -                | -         |    -2.62 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            4 |     4112 | 2024-02-22 | BIG Academy     | W   | 0.092      | -            | -                | -                | -         |     0.03 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            3 |     4150 | 2024-02-21 | Permitta        | W   | 0.085      | -            | -                | -                | -         |     0.56 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            2 |     4167 | 2024-02-20 | NAVI Junior     | W   | 0.079      | -            | -                | -                | -         |     0.14 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            1 |     4195 | 2024-02-19 | Permitta        | L   | 0.072      | -            | -                | -                | -         |    -1.80 | Blytz, Dytor, forsyy, kreaz, nbqq |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($19,616.72)
- Divide that value by the 5th highest value among all rosters ($320,068.63)
- The final value (0.06) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-17 |      0.865 | $2,500.00      | $2,162.85       |
| 2024-06-13 |      0.841 | $545.00        | $458.13         |
| 2024-06-02 |      0.766 | $7,837.00      | $6,006.92       |
| 2024-05-13 |      0.631 | $3,000.00      | $1,892.92       |
| 2024-04-25 |      0.511 | $11,000.00     | $5,620.69       |
| 2024-04-06 |      0.384 | $1,500.00      | $576.46         |
| 2024-03-17 |      0.254 | $7,675.00      | $1,946.47       |
| 2024-02-28 |      0.131 | $5,000.00      | $656.25         |
| 2024-02-21 |      0.085 | $3,500.00      | $296.04         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
