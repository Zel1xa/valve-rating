### Roster Details<br />
Team Name: SINNERS<br />
Roster: beastik, majky, MoriiSko, oskar, SHOCK<br />
Global Rank: [63](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [45]( ../standings_europe.md)<br />
<br />
Final Rank Value:  971.6<br />
<br />
Final Rank Value (971.6) = Starting Rank Value (1145.2) + Head To Head Adjustments (-173.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.412[<sup>1</sup>](#table2)
- Bounty Collected: 0.434[<sup>2</sup>](#table1)
- Opponent Network: 0.234[<sup>2</sup>](#table1)
- LAN Wins: 0.377[<sup>2</sup>](#table1)

The average of these factors is 0.364<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1145.2
- 400 + ( ( 0.364 - 0.000 ) / ( 0.782 - 0.000 ) ) * 1600 = 1145.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                 |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           80 |       14 | 2024-08-04 | AVEZ              | W   | 1.000      | -            | -                | -                | 1 (1.000) |     6.00 | beastik, majky, MoriiSko, oskar, SHOCK |
|           79 |       50 | 2024-08-03 | SINNERS Academy   | W   | 1.000      | -            | -                | -                | 1 (1.000) |     2.52 | beastik, majky, MoriiSko, oskar, SHOCK |
|           78 |       72 | 2024-08-02 | ECLOT             | L   | 1.000      | -            | -                | -                | -         |   -11.06 | beastik, majky, MoriiSko, oskar, SHOCK |
|           77 |      221 | 2024-07-30 | Sangal            | L   | 1.000      | -            | -                | -                | -         |    -5.25 | beastik, majky, MoriiSko, oskar, SHOCK |
|           76 |      256 | 2024-07-29 | Alliance          | W   | 1.000      | -            | -                | -                | 0 (0.000) |    10.55 | beastik, majky, MoriiSko, oskar, SHOCK |
|           75 |      360 | 2024-07-25 | B8                | L   | 1.000      | -            | -                | -                | -         |    -8.25 | beastik, majky, MoriiSko, oskar, SHOCK |
|           74 |      435 | 2024-07-23 | RUSH B            | L   | 1.000      | -            | -                | -                | -         |   -18.88 | beastik, majky, MoriiSko, oskar, SHOCK |
|           73 |      469 | 2024-07-22 | CPH Wolves        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.57 | beastik, majky, MoriiSko, oskar, SHOCK |
|           72 |      552 | 2024-07-19 | DMS               | W   | 1.000      | 0.435        | -                | 0.446 (0.194)    | 0 (0.000) |    12.52 | beastik, majky, MoriiSko, oskar, SHOCK |
|           71 |      682 | 2024-07-17 | Endpoint          | W   | 1.000      | 0.435        | -                | 0.522 (0.227)    | 0 (0.000) |    10.46 | beastik, majky, MoriiSko, oskar, SHOCK |
|           70 |      751 | 2024-07-16 | BC.Game           | L   | 1.000      | -            | -                | -                | -         |   -19.84 | beastik, majky, MoriiSko, oskar, SHOCK |
|           69 |      780 | 2024-07-15 | SAW               | L   | 1.000      | -            | -                | -                | -         |    -8.31 | beastik, majky, MoriiSko, oskar, SHOCK |
|           68 |      793 | 2024-07-15 | Nexus             | L   | 1.000      | -            | -                | -                | -         |   -25.54 | beastik, majky, MoriiSko, oskar, SHOCK |
|           67 |     1153 | 2024-06-11 | 3DMAX             | L   | 0.838      | -            | -                | -                | -         |    -2.46 | beastik, majky, MoriiSko, oskar, SHOCK |
|           66 |     1167 | 2024-06-11 | ex-Guild Eagles   | W   | 0.836      | -            | -                | -                | 0 (0.000) |     7.78 | beastik, majky, MoriiSko, oskar, SHOCK |
|           65 |     1181 | 2024-06-10 | Enterprise        | L   | 0.831      | -            | -                | -                | -         |   -16.61 | beastik, majky, MoriiSko, oskar, SHOCK |
|           64 |     1189 | 2024-06-10 | Monte             | L   | 0.830      | -            | -                | -                | -         |   -13.72 | beastik, majky, MoriiSko, oskar, SHOCK |
|           63 |     1193 | 2024-06-10 | 9 Pandas          | L   | 0.830      | -            | -                | -                | -         |   -12.82 | beastik, majky, MoriiSko, oskar, SHOCK |
|           62 |     1200 | 2024-06-10 | PARIVISION        | W   | 0.829      | -            | -                | -                | -         |    14.56 | beastik, majky, MoriiSko, oskar, SHOCK |
|           61 |     1202 | 2024-06-10 | Rare Atom         | L   | 0.829      | -            | -                | -                | -         |   -22.75 | beastik, majky, MoriiSko, oskar, SHOCK |
|           60 |     1232 | 2024-06-09 | SAW               | W   | 0.824      | -            | -                | -                | -         |    16.64 | beastik, majky, MoriiSko, oskar, SHOCK |
|           59 |     1240 | 2024-06-09 | 3DMAX             | W   | 0.823      | 0.143        | 0.507 (0.060)    | -                | -         |    23.92 | beastik, majky, MoriiSko, oskar, SHOCK |
|           58 |     1246 | 2024-06-09 | RUSH B            | L   | 0.823      | -            | -                | -                | -         |   -18.23 | beastik, majky, MoriiSko, oskar, SHOCK |
|           57 |     1255 | 2024-06-09 | Aurora            | W   | 0.823      | 0.143        | 0.423 (0.050)    | -                | -         |    24.09 | beastik, majky, MoriiSko, oskar, SHOCK |
|           56 |     1289 | 2024-06-08 | Sangal            | L   | 0.818      | -            | -                | -                | -         |    -7.15 | beastik, majky, MoriiSko, oskar, SHOCK |
|           55 |     1368 | 2024-06-07 | RUBY              | W   | 0.809      | 0.435        | 0.095 (0.033)    | 0.501 (0.176)    | -         |     9.11 | beastik, majky, MoriiSko, oskar, SHOCK |
|           54 |     1411 | 2024-06-06 | KOI               | L   | 0.804      | -            | -                | -                | -         |   -10.96 | beastik, majky, MoriiSko, oskar, SHOCK |
|           53 |     1471 | 2024-06-05 | RUSH B            | W   | 0.798      | -            | -                | -                | -         |     7.79 | beastik, majky, MoriiSko, oskar, SHOCK |
|           52 |     1480 | 2024-06-05 | EYEBALLERS        | L   | 0.797      | -            | -                | -                | -         |   -17.54 | beastik, majky, MoriiSko, oskar, SHOCK |
|           51 |     1534 | 2024-06-04 | VP.Prodigy        | L   | 0.789      | -            | -                | -                | -         |   -16.29 | beastik, majky, MoriiSko, oskar, SHOCK |
|           50 |     1573 | 2024-06-02 | UNiTY             | L   | 0.777      | -            | -                | -                | -         |   -15.44 | AJTT, beastik, oskar, SHOCK, Tomkeejs  |
|           49 |     1590 | 2024-06-01 | GUN5              | L   | 0.772      | -            | -                | -                | -         |   -16.30 | AJTT, beastik, MoriiSko, oskar, SHOCK  |
|           48 |     1610 | 2024-06-01 | Sampi             | W   | 0.770      | 0.346        | -                | 1.000 (0.266)    | 1 (0.770) |     6.45 | AJTT, beastik, oskar, SHOCK, Tomkeejs  |
|           47 |     1642 | 2024-05-31 | UNiTY             | L   | 0.763      | -            | -                | -                | -         |   -15.97 | AJTT, beastik, oskar, SHOCK, Tomkeejs  |
|           46 |     1660 | 2024-05-30 | B8                | W   | 0.757      | 0.435        | 0.165 (0.054)    | 0.951 (0.313)    | -         |    14.38 | beastik, majky, MoriiSko, oskar, SHOCK |
|           45 |     1688 | 2024-05-29 | brazylijski luz   | W   | 0.751      | -            | -                | -                | -         |     4.95 | beastik, majky, MoriiSko, oskar, SHOCK |
|           44 |     1746 | 2024-05-26 | Sampi             | W   | 0.731      | 0.435        | -                | 1.000 (0.317)    | -         |     6.64 | beastik, majky, MoriiSko, oskar, SHOCK |
|           43 |     1780 | 2024-05-24 | GUN5              | W   | 0.718      | 0.435        | 0.073 (0.023)    | 0.570 (0.178)    | -         |     7.34 | AJTT, beastik, majky, MoriiSko, oskar  |
|           42 |     1788 | 2024-05-24 | 9 Pandas          | L   | 0.716      | -            | -                | -                | -         |   -12.44 | AJTT, beastik, majky, oskar, SHOCK     |
|           41 |     1799 | 2024-05-23 | UNiTY             | W   | 0.711      | -            | -                | -                | -         |     8.05 | AJTT, beastik, majky, MoriiSko, oskar  |
|           40 |     1805 | 2024-05-23 | Passion UA        | L   | 0.709      | -            | -                | -                | -         |   -12.34 | AJTT, beastik, majky, MoriiSko, oskar  |
|           39 |     1923 | 2024-05-20 | VP.Prodigy        | W   | 0.690      | -            | -                | -                | -         |     5.59 | AJTT, beastik, majky, MoriiSko, oskar  |
|           38 |     1971 | 2024-05-18 | 1WIN              | L   | 0.677      | -            | -                | -                | -         |   -13.12 | AJTT, beastik, oskar, SHOCK, Tomkeejs  |
|           37 |     2057 | 2024-05-16 | ALTERNATE aTTaX   | W   | 0.662      | -            | -                | -                | -         |     7.21 | AJTT, beastik, majky, oskar, SHOCK     |
|           36 |     2149 | 2024-05-14 | Passion UA        | W   | 0.651      | 0.435        | 0.172 (0.049)    | 1.000 (0.283)    | -         |     9.12 | AJTT, beastik, majky, oskar, SHOCK     |
|           35 |     2319 | 2024-05-07 | Nemiga            | L   | 0.603      | -            | -                | -                | -         |    -6.53 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           34 |     2354 | 2024-05-05 | Endpoint          | W   | 0.590      | -            | -                | -                | -         |     6.05 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           33 |     2417 | 2024-05-02 | Gaimin Gladiators | L   | 0.569      | -            | -                | -                | -         |   -11.11 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           32 |     2444 | 2024-05-01 | B8                | L   | 0.562      | -            | -                | -                | -         |   -10.16 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           31 |     2476 | 2024-04-29 | 1WIN              | W   | 0.550      | 0.435        | -                | 0.707 (0.169)    | -         |     5.36 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           30 |     2485 | 2024-04-29 | Sangal            | L   | 0.549      | -            | -                | -                | -         |    -7.73 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           29 |     2497 | 2024-04-28 | Zero Tenacity     | L   | 0.543      | -            | -                | -                | -         |    -9.45 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           28 |     2530 | 2024-04-27 | Zero Tenacity     | L   | 0.536      | -            | -                | -                | -         |    -9.82 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           27 |     2546 | 2024-04-26 | PARIVISION        | L   | 0.530      | -            | -                | -                | -         |    -9.55 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           26 |     2596 | 2024-04-24 | Endpoint          | L   | 0.517      | -            | -                | -                | -         |   -12.87 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           25 |     2632 | 2024-04-22 | HAVU              | W   | 0.503      | -            | -                | -                | -         |     1.29 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           24 |     2681 | 2024-04-20 | ENCE Academy      | L   | 0.490      | -            | -                | -                | -         |   -14.08 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           23 |     2736 | 2024-04-19 | ECLOT             | L   | 0.482      | -            | -                | -                | -         |    -6.86 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           22 |     2826 | 2024-04-17 | Gaimin Gladiators | L   | 0.469      | -            | -                | -                | -         |   -10.38 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           21 |     2851 | 2024-04-16 | BLEED             | L   | 0.462      | -            | -                | -                | -         |   -10.70 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           20 |     2881 | 2024-04-14 | Passion UA        | W   | 0.450      | 0.371        | 0.172 (0.029)    | -                | -         |     4.84 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           19 |     2970 | 2024-04-10 | 3DMAX             | W   | 0.425      | 0.500        | 0.507 (0.108)    | 1.000 (0.212)    | -         |    12.59 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           18 |     2997 | 2024-04-10 | UNiTY             | W   | 0.422      | -            | -                | -                | -         |     3.40 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           17 |     3023 | 2024-04-09 | 9 Pandas          | W   | 0.418      | 0.500        | 0.081 (0.017)    | -                | -         |     3.92 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           16 |     3074 | 2024-04-08 | ALTERNATE aTTaX   | W   | 0.409      | -            | -                | -                | -         |     3.37 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           15 |     3125 | 2024-04-05 | Nexus             | W   | 0.391      | -            | -                | -                | -         |     2.01 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           14 |     3217 | 2024-04-03 | Rebels            | W   | 0.376      | -            | -                | -                | -         |     3.59 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           13 |     3260 | 2024-04-01 | Aurora            | W   | 0.365      | 0.500        | 0.423 (0.077)    | -                | -         |    10.94 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           12 |     3283 | 2024-03-29 | ex-Sprout         | W   | 0.344      | -            | -                | -                | -         |     0.18 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           11 |     3502 | 2024-03-17 | ECLOT             | L   | 0.265      | -            | -                | -                | -         |    -3.45 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           10 |     3508 | 2024-03-17 | UNiTY             | W   | 0.264      | -            | -                | -                | 1 (0.264) |     2.33 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            9 |     3523 | 2024-03-16 | Sampi             | W   | 0.257      | -            | -                | -                | 1 (0.257) |     1.79 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            8 |     3535 | 2024-03-15 | UNiTY             | L   | 0.251      | -            | -                | -                | -         |    -5.75 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            7 |     3605 | 2024-03-13 | ALTERNATE aTTaX   | W   | 0.238      | -            | -                | -                | -         |     2.20 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            6 |     3658 | 2024-03-11 | brazylijski luz   | L   | 0.224      | -            | -                | -                | -         |    -6.18 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            5 |     3870 | 2024-03-03 | Gaimin Gladiators | L   | 0.171      | -            | -                | -                | -         |    -3.90 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            4 |     4163 | 2024-02-18 | Monte             | L   | 0.077      | -            | -                | -                | -         |    -1.72 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            3 |     4210 | 2024-02-16 | 500               | W   | 0.065      | -            | -                | -                | -         |     0.16 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            2 |     4213 | 2024-02-16 | PERA              | W   | 0.064      | -            | -                | -                | -         |     0.47 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            1 |     4218 | 2024-02-16 | 500               | L   | 0.064      | -            | -                | -                | -         |    -1.85 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($12,064.40)
- Divide that value by the 5th highest value among all rosters ($323,321.90)
- The final value (0.04) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-13 |      0.852 | $545.00        | $464.11         |
| 2024-06-09 |      0.824 | $10,000.00     | $8,240.97       |
| 2024-06-02 |      0.777 | $1,306.00      | $1,015.35       |
| 2024-06-02 |      0.777 | $2,000.00      | $1,554.44       |
| 2024-03-17 |      0.265 | $2,984.00      | $789.52         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
