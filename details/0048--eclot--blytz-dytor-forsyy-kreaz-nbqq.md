### Roster Details<br />
Team Name: ECLOT<br />
Roster: Blytz, Dytor, forsyy, kreaz, nbqq<br />
Global Rank: [48](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [35]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1089.4<br />
<br />
Final Rank Value (1089.4) = Starting Rank Value (1219.1) + Head To Head Adjustments (-129.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.452[<sup>1</sup>](#table2)
- Bounty Collected: 0.352[<sup>2</sup>](#table1)
- Opponent Network: 0.212[<sup>2</sup>](#table1)
- LAN Wins: 0.580[<sup>2</sup>](#table1)

The average of these factors is 0.399<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1219.1
- 400 + ( ( 0.399 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 1219.1


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
|           57 |       68 | 2024-08-03 | AVEZ            | W   | 1.000      | -            | -                | -                | 1 (1.000) |     3.50 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           56 |      100 | 2024-08-02 | SINNERS         | W   | 1.000      | 0.345        | 0.037 (0.013)    | 0.808 (0.279)    | 1 (1.000) |    11.19 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           55 |      244 | 2024-07-30 | 1WIN            | W   | 1.000      | -            | -                | -                | 0 (0.000) |    12.42 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           54 |      287 | 2024-07-29 | DASH            | L   | 1.000      | -            | -                | -                | -         |   -29.74 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           53 |      401 | 2024-07-25 | HAVU            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.36 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           52 |      772 | 2024-07-16 | FAVBET          | L   | 1.000      | -            | -                | -                | -         |   -25.40 | Dytor, forsyy, kreaz, nbqq, olik  |
|           51 |      828 | 2024-07-14 | The Suspect     | L   | 1.000      | -            | -                | -                | -         |   -25.55 | Dytor, forsyy, nbqq, NEOFRAG, PR  |
|           50 |      839 | 2024-07-14 | The Suspect     | W   | 1.000      | -            | -                | -                | -         |     5.00 | Dytor, forsyy, nbqq, NEOFRAG, PR  |
|           49 |      845 | 2024-07-13 | ALTERNATE aTTaX | W   | 1.000      | -            | -                | -                | -         |     6.15 | Dytor, forsyy, K1-FiDa, nbqq, PR  |
|           48 |      940 | 2024-07-08 | Hungary         | W   | 1.000      | -            | -                | -                | -         |     4.25 | Dytor, forsyy, K1-FiDa, nbqq, PR  |
|           47 |     1113 | 2024-06-14 | 5W              | L   | 0.847      | -            | -                | -                | -         |   -19.07 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           46 |     1182 | 2024-06-11 | PERA            | L   | 0.829      | -            | -                | -                | -         |   -19.74 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           45 |     1264 | 2024-06-09 | Enterprise      | W   | 0.814      | 0.450        | 0.039 (0.014)    | 0.616 (0.226)    | -         |     5.03 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           44 |     1338 | 2024-06-08 | MOUZ NXT        | W   | 0.807      | 0.450        | 0.139 (0.050)    | 0.984 (0.357)    | -         |    11.00 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           43 |     1398 | 2024-06-07 | GhoulsW         | W   | 0.800      | -            | -                | -                | -         |     0.38 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           42 |     1429 | 2024-06-06 | GamerLegion     | L   | 0.796      | -            | -                | -                | -         |   -12.15 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           41 |     1595 | 2024-06-02 | UNiTY           | W   | 0.768      | 0.346        | 0.024 (0.007)    | -                | 1 (0.768) |     6.43 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           40 |     1627 | 2024-06-01 | UNiTY           | W   | 0.762      | 0.346        | 0.024 (0.006)    | -                | 1 (0.762) |     6.55 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           39 |     1659 | 2024-05-31 | Sampi           | W   | 0.755      | 0.346        | 0.027 (0.007)    | 1.000 (0.261)    | 1 (0.755) |     4.97 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           38 |     1784 | 2024-05-26 | Permitta        | L   | 0.719      | -            | -                | -                | -         |   -17.87 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           37 |     1872 | 2024-05-22 | Preasy          | L   | 0.694      | -            | -                | -                | -         |   -19.65 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           36 |     2212 | 2024-05-13 | Johnny Speeds   | L   | 0.633      | -            | -                | -                | -         |    -7.41 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           35 |     2282 | 2024-05-10 | Verdant         | W   | 0.614      | -            | -                | -                | -         |     3.89 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           34 |     2475 | 2024-04-30 | MOUZ NXT        | L   | 0.549      | -            | -                | -                | -         |   -12.02 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           33 |     2502 | 2024-04-29 | 1WIN            | W   | 0.541      | 0.500        | 0.033 (0.009)    | 0.695 (0.188)    | -         |     3.45 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           32 |     2539 | 2024-04-27 | MOUZ NXT        | L   | 0.529      | -            | -                | -                | -         |   -11.95 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           31 |     2610 | 2024-04-25 | Sampi           | W   | 0.513      | 0.371        | -                | 1.000 (0.190)    | -         |     2.87 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           30 |     2648 | 2024-04-23 | Sampi           | W   | 0.500      | 0.371        | -                | 1.000 (0.185)    | -         |     2.75 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           29 |     2680 | 2024-04-21 | MOUZ NXT        | W   | 0.487      | 0.371        | 0.139 (0.025)    | 0.984 (0.177)    | -         |     4.69 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           28 |     2764 | 2024-04-19 | SINNERS         | W   | 0.473      | 0.371        | 0.037 (0.007)    | 0.808 (0.141)    | -         |     6.81 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           27 |     2846 | 2024-04-17 | Alliance        | W   | 0.460      | -            | -                | -                | -         |     1.98 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           26 |     2898 | 2024-04-15 | Astralis Talent | W   | 0.446      | -            | -                | -                | -         |     1.27 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           25 |     3069 | 2024-04-09 | ALTERNATE aTTaX | L   | 0.407      | -            | -                | -                | -         |   -10.03 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           24 |     3157 | 2024-04-05 | UNiTY           | L   | 0.379      | -            | -                | -                | -         |    -9.47 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           23 |     3204 | 2024-04-04 | PGE Turow       | W   | 0.373      | -            | -                | -                | -         |     0.54 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           22 |     3244 | 2024-04-03 | Permitta        | W   | 0.367      | 0.333        | -                | 0.940 (0.115)    | -         |     2.50 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           21 |     3530 | 2024-03-17 | SINNERS         | W   | 0.255      | -            | -                | -                | 1 (0.255) |     3.38 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           20 |     3548 | 2024-03-16 | UNiTY           | W   | 0.249      | -            | -                | -                | 1 (0.249) |     1.70 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           19 |     3569 | 2024-03-15 | Sampi           | W   | 0.241      | -            | -                | -                | 1 (0.241) |     1.23 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           18 |     3573 | 2024-03-15 | Sashi           | L   | 0.240      | -            | -                | -                | -         |    -4.49 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           17 |     3640 | 2024-03-13 | Permitta        | L   | 0.228      | -            | -                | -                | -         |    -5.61 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           16 |     3655 | 2024-03-13 | Permitta        | L   | 0.226      | -            | -                | -                | -         |    -5.66 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           15 |     3698 | 2024-03-11 | Entropiq        | L   | 0.213      | -            | -                | -                | -         |    -6.54 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           14 |     3716 | 2024-03-10 | Zero Tenacity   | L   | 0.207      | -            | -                | -                | -         |    -4.28 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           13 |     3859 | 2024-03-05 | 9INE            | W   | 0.174      | -            | -                | -                | -         |     0.10 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           12 |     3903 | 2024-03-03 | Metizport       | W   | 0.161      | -            | -                | -                | -         |     0.74 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           11 |     3944 | 2024-03-01 | Viperio         | W   | 0.146      | -            | -                | -                | -         |     0.05 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           10 |     3972 | 2024-02-28 | Permitta        | W   | 0.133      | -            | -                | -                | -         |     0.82 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            9 |     3990 | 2024-02-27 | MOUZ NXT        | W   | 0.128      | 0.333        | 0.139 (0.006)    | -                | -         |     1.14 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            8 |     3992 | 2024-02-27 | ex-sYnck        | W   | 0.127      | -            | -                | -                | -         |     0.07 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            7 |     4009 | 2024-02-26 | PGE Turow       | W   | 0.120      | -            | -                | -                | -         |     0.16 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            6 |     4031 | 2024-02-25 | Sampi           | W   | 0.113      | -            | -                | -                | -         |     0.49 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            5 |     4064 | 2024-02-24 | Permitta        | L   | 0.107      | -            | -                | -                | -         |    -2.72 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            4 |     4093 | 2024-02-22 | BIG Academy     | W   | 0.094      | -            | -                | -                | -         |     0.03 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            3 |     4131 | 2024-02-21 | Permitta        | W   | 0.086      | -            | -                | -                | -         |     0.53 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            2 |     4148 | 2024-02-20 | NAVI Junior     | W   | 0.081      | -            | -                | -                | -         |     0.13 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            1 |     4176 | 2024-02-19 | Permitta        | L   | 0.074      | -            | -                | -                | -         |    -1.88 | Blytz, Dytor, forsyy, kreaz, nbqq |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($19,693.56)
- Divide that value by the 5th highest value among all rosters ($320,603.98)
- The final value (0.06) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-17 |      0.867 | $2,500.00      | $2,167.36       |
| 2024-06-13 |      0.842 | $545.00        | $459.11         |
| 2024-06-02 |      0.768 | $7,837.00      | $6,021.07       |
| 2024-05-13 |      0.633 | $3,000.00      | $1,898.33       |
| 2024-04-25 |      0.513 | $11,000.00     | $5,640.56       |
| 2024-04-06 |      0.386 | $1,500.00      | $579.17         |
| 2024-03-17 |      0.255 | $7,675.00      | $1,960.32       |
| 2024-02-28 |      0.133 | $5,000.00      | $665.28         |
| 2024-02-21 |      0.086 | $3,500.00      | $302.36         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
