### Roster Details<br />
Team Name: ECLOT<br />
Roster: Blytz, Dytor, forsyy, kreaz, nbqq<br />
Global Rank: [48](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [35]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1090.1<br />
<br />
Final Rank Value (1090.1) = Starting Rank Value (1220.3) + Head To Head Adjustments (-130.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.452[<sup>1</sup>](#table2)
- Bounty Collected: 0.352[<sup>2</sup>](#table1)
- Opponent Network: 0.211[<sup>2</sup>](#table1)
- LAN Wins: 0.580[<sup>2</sup>](#table1)

The average of these factors is 0.399<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1220.3
- 400 + ( ( 0.399 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1220.3


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
|           57 |       74 | 2024-08-03 | AVEZ            | W   | 1.000      | -            | -                | -                | 1 (1.000) |     3.50 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           56 |      106 | 2024-08-02 | SINNERS         | W   | 1.000      | 0.345        | 0.037 (0.013)    | 0.790 (0.273)    | 1 (1.000) |    11.16 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           55 |      250 | 2024-07-30 | 1WIN            | W   | 1.000      | -            | -                | -                | 0 (0.000) |    12.37 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           54 |      293 | 2024-07-29 | DASH            | L   | 1.000      | -            | -                | -                | -         |   -29.75 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           53 |      407 | 2024-07-25 | HAVU            | W   | 1.000      | -            | -                | -                | 0 (0.000) |     3.35 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           52 |      778 | 2024-07-16 | FAVBET          | L   | 1.000      | -            | -                | -                | -         |   -25.36 | Dytor, forsyy, kreaz, nbqq, olik  |
|           51 |      834 | 2024-07-14 | The Suspect     | L   | 1.000      | -            | -                | -                | -         |   -25.56 | Dytor, forsyy, nbqq, NEOFRAG, PR  |
|           50 |      845 | 2024-07-14 | The Suspect     | W   | 1.000      | -            | -                | -                | -         |     4.99 | Dytor, forsyy, nbqq, NEOFRAG, PR  |
|           49 |      851 | 2024-07-13 | ALTERNATE aTTaX | W   | 1.000      | -            | -                | -                | -         |     6.15 | Dytor, forsyy, K1-FiDa, nbqq, PR  |
|           48 |      946 | 2024-07-08 | Hungary         | W   | 1.000      | -            | -                | -                | -         |     4.25 | Dytor, forsyy, K1-FiDa, nbqq, PR  |
|           47 |     1119 | 2024-06-14 | 5W              | L   | 0.847      | -            | -                | -                | -         |   -19.07 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           46 |     1188 | 2024-06-11 | PERA            | L   | 0.828      | -            | -                | -                | -         |   -19.75 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           45 |     1270 | 2024-06-09 | Enterprise      | W   | 0.814      | 0.450        | 0.039 (0.014)    | 0.641 (0.235)    | -         |     5.00 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           44 |     1344 | 2024-06-08 | MOUZ NXT        | W   | 0.807      | 0.450        | 0.139 (0.050)    | 0.962 (0.349)    | -         |    10.98 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           43 |     1404 | 2024-06-07 | GhoulsW         | W   | 0.799      | -            | -                | -                | -         |     0.38 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           42 |     1435 | 2024-06-06 | GamerLegion     | L   | 0.795      | -            | -                | -                | -         |   -12.20 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           41 |     1601 | 2024-06-02 | UNiTY           | W   | 0.768      | 0.346        | 0.024 (0.006)    | -                | 1 (0.768) |     6.40 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           40 |     1633 | 2024-06-01 | UNiTY           | W   | 0.761      | 0.346        | 0.024 (0.006)    | -                | 1 (0.761) |     6.51 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           39 |     1665 | 2024-05-31 | Sampi           | W   | 0.755      | 0.346        | 0.027 (0.007)    | 1.000 (0.261)    | 1 (0.755) |     4.93 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           38 |     1790 | 2024-05-26 | Permitta        | L   | 0.719      | -            | -                | -                | -         |   -17.87 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           37 |     1878 | 2024-05-22 | Preasy          | L   | 0.693      | -            | -                | -                | -         |   -19.64 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           36 |     2218 | 2024-05-13 | Johnny Speeds   | L   | 0.632      | -            | -                | -                | -         |    -7.40 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           35 |     2288 | 2024-05-10 | Verdant         | W   | 0.613      | -            | -                | -                | -         |     3.89 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           34 |     2481 | 2024-04-30 | MOUZ NXT        | L   | 0.548      | -            | -                | -                | -         |   -12.03 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           33 |     2508 | 2024-04-29 | 1WIN            | W   | 0.541      | 0.500        | 0.033 (0.009)    | 0.718 (0.194)    | -         |     3.42 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           32 |     2545 | 2024-04-27 | MOUZ NXT        | L   | 0.528      | -            | -                | -                | -         |   -11.96 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           31 |     2616 | 2024-04-25 | Sampi           | W   | 0.512      | 0.371        | -                | 1.000 (0.190)    | -         |     2.84 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           30 |     2654 | 2024-04-23 | Sampi           | W   | 0.499      | 0.371        | -                | 1.000 (0.185)    | -         |     2.72 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           29 |     2686 | 2024-04-21 | MOUZ NXT        | W   | 0.486      | 0.371        | 0.139 (0.025)    | 0.962 (0.173)    | -         |     4.66 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           28 |     2770 | 2024-04-19 | SINNERS         | W   | 0.472      | 0.371        | 0.037 (0.006)    | 0.790 (0.138)    | -         |     6.79 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           27 |     2852 | 2024-04-17 | Alliance        | W   | 0.459      | -            | -                | -                | -         |     1.97 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           26 |     2904 | 2024-04-15 | Astralis Talent | W   | 0.445      | -            | -                | -                | -         |     1.27 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           25 |     3075 | 2024-04-09 | ALTERNATE aTTaX | L   | 0.406      | -            | -                | -                | -         |   -10.01 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           24 |     3163 | 2024-04-05 | UNiTY           | L   | 0.379      | -            | -                | -                | -         |    -9.47 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           23 |     3210 | 2024-04-04 | PGE Turow       | W   | 0.372      | -            | -                | -                | -         |     0.53 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           22 |     3250 | 2024-04-03 | Permitta        | W   | 0.366      | 0.333        | -                | 0.919 (0.112)    | -         |     2.49 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           21 |     3536 | 2024-03-17 | SINNERS         | W   | 0.255      | -            | -                | -                | 1 (0.255) |     3.37 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           20 |     3554 | 2024-03-16 | UNiTY           | W   | 0.248      | -            | -                | -                | 1 (0.248) |     1.68 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           19 |     3575 | 2024-03-15 | Sampi           | W   | 0.240      | -            | -                | -                | 1 (0.240) |     1.22 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           18 |     3579 | 2024-03-15 | Sashi           | L   | 0.239      | -            | -                | -                | -         |    -4.49 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           17 |     3646 | 2024-03-13 | Permitta        | L   | 0.227      | -            | -                | -                | -         |    -5.61 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           16 |     3661 | 2024-03-13 | Permitta        | L   | 0.226      | -            | -                | -                | -         |    -5.65 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           15 |     3704 | 2024-03-11 | Entropiq        | L   | 0.212      | -            | -                | -                | -         |    -6.53 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           14 |     3722 | 2024-03-10 | Zero Tenacity   | L   | 0.207      | -            | -                | -                | -         |    -4.29 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           13 |     3865 | 2024-03-05 | 9INE            | W   | 0.173      | -            | -                | -                | -         |     0.10 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           12 |     3909 | 2024-03-03 | Metizport       | W   | 0.160      | -            | -                | -                | -         |     0.73 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           11 |     3950 | 2024-03-01 | Viperio         | W   | 0.146      | -            | -                | -                | -         |     0.05 | Blytz, Dytor, forsyy, kreaz, nbqq |
|           10 |     3978 | 2024-02-28 | Permitta        | W   | 0.132      | -            | -                | -                | -         |     0.81 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            9 |     3996 | 2024-02-27 | MOUZ NXT        | W   | 0.127      | 0.333        | 0.139 (0.006)    | -                | -         |     1.12 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            8 |     3998 | 2024-02-27 | ex-sYnck        | W   | 0.126      | -            | -                | -                | -         |     0.07 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            7 |     4015 | 2024-02-26 | PGE Turow       | W   | 0.119      | -            | -                | -                | -         |     0.15 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            6 |     4037 | 2024-02-25 | Sampi           | W   | 0.112      | -            | -                | -                | -         |     0.48 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            5 |     4070 | 2024-02-24 | Permitta        | L   | 0.106      | -            | -                | -                | -         |    -2.71 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            4 |     4099 | 2024-02-22 | BIG Academy     | W   | 0.093      | -            | -                | -                | -         |     0.03 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            3 |     4137 | 2024-02-21 | Permitta        | W   | 0.086      | -            | -                | -                | -         |     0.52 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            2 |     4154 | 2024-02-20 | NAVI Junior     | W   | 0.080      | -            | -                | -                | -         |     0.13 | Blytz, Dytor, forsyy, kreaz, nbqq |
|            1 |     4182 | 2024-02-19 | Permitta        | L   | 0.073      | -            | -                | -                | -         |    -1.87 | Blytz, Dytor, forsyy, kreaz, nbqq |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($19,665.97)
- Divide that value by the 5th highest value among all rosters ($320,411.81)
- The final value (0.06) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-17 |      0.866 | $2,500.00      | $2,165.74       |
| 2024-06-13 |      0.842 | $545.00        | $458.76         |
| 2024-06-02 |      0.768 | $7,837.00      | $6,015.99       |
| 2024-05-13 |      0.632 | $3,000.00      | $1,896.39       |
| 2024-04-25 |      0.512 | $11,000.00     | $5,633.43       |
| 2024-04-06 |      0.385 | $1,500.00      | $578.19         |
| 2024-03-17 |      0.255 | $7,675.00      | $1,955.35       |
| 2024-02-28 |      0.132 | $5,000.00      | $662.04         |
| 2024-02-21 |      0.086 | $3,500.00      | $300.09         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
