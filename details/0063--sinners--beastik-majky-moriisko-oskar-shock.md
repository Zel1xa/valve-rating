### Roster Details<br />
Team Name: SINNERS<br />
Roster: beastik, majky, MoriiSko, oskar, SHOCK<br />
Global Rank: [63](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [47]( ../standings_europe.md)<br />
<br />
Final Rank Value:  991.5<br />
<br />
Final Rank Value (991.5) = Starting Rank Value (1151.0) + Head To Head Adjustments (-159.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.411[<sup>1</sup>](#table2)
- Bounty Collected: 0.434[<sup>2</sup>](#table1)
- Opponent Network: 0.239[<sup>2</sup>](#table1)
- LAN Wins: 0.376[<sup>2</sup>](#table1)

The average of these factors is 0.365<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1151.0
- 400 + ( ( 0.365 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1151.0


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
|           81 |       16 | 2024-08-05 | Rebels            | W   | 1.000      | 0.500        | 0.038 (0.019)    | 0.578 (0.289)    | 0 (0.000) |    16.74 | beastik, majky, MoriiSko, oskar, SHOCK |
|           80 |       48 | 2024-08-04 | AVEZ              | W   | 1.000      | -            | -                | -                | 1 (1.000) |     5.97 | beastik, majky, MoriiSko, oskar, SHOCK |
|           79 |       82 | 2024-08-03 | SINNERS Academy   | W   | 1.000      | -            | -                | -                | 1 (1.000) |     2.50 | beastik, majky, MoriiSko, oskar, SHOCK |
|           78 |      102 | 2024-08-02 | ECLOT             | L   | 1.000      | -            | -                | -                | -         |   -11.08 | beastik, majky, MoriiSko, oskar, SHOCK |
|           77 |      250 | 2024-07-30 | Sangal            | L   | 1.000      | -            | -                | -                | -         |    -5.29 | beastik, majky, MoriiSko, oskar, SHOCK |
|           76 |      286 | 2024-07-29 | Alliance          | W   | 1.000      | -            | -                | -                | 0 (0.000) |    10.46 | beastik, majky, MoriiSko, oskar, SHOCK |
|           75 |      390 | 2024-07-25 | B8                | L   | 1.000      | -            | -                | -                | -         |    -8.31 | beastik, majky, MoriiSko, oskar, SHOCK |
|           74 |      465 | 2024-07-23 | RUSH B            | L   | 1.000      | -            | -                | -                | -         |   -19.02 | beastik, majky, MoriiSko, oskar, SHOCK |
|           73 |      499 | 2024-07-22 | CPH Wolves        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.50 | beastik, majky, MoriiSko, oskar, SHOCK |
|           72 |      582 | 2024-07-19 | DMS               | W   | 1.000      | 0.435        | -                | 0.428 (0.186)    | 0 (0.000) |    12.43 | beastik, majky, MoriiSko, oskar, SHOCK |
|           71 |      712 | 2024-07-17 | Endpoint          | W   | 1.000      | 0.435        | -                | 0.502 (0.218)    | 0 (0.000) |    10.72 | beastik, majky, MoriiSko, oskar, SHOCK |
|           70 |      781 | 2024-07-16 | BC.Game           | L   | 1.000      | -            | -                | -                | -         |   -19.57 | beastik, majky, MoriiSko, oskar, SHOCK |
|           69 |      810 | 2024-07-15 | SAW               | L   | 1.000      | -            | -                | -                | -         |    -8.51 | beastik, majky, MoriiSko, oskar, SHOCK |
|           68 |      823 | 2024-07-15 | Nexus             | L   | 1.000      | -            | -                | -                | -         |   -25.51 | beastik, majky, MoriiSko, oskar, SHOCK |
|           67 |     1183 | 2024-06-11 | 3DMAX             | L   | 0.828      | -            | -                | -                | -         |    -2.38 | beastik, majky, MoriiSko, oskar, SHOCK |
|           66 |     1197 | 2024-06-11 | ex-Guild Eagles   | W   | 0.826      | -            | -                | -                | -         |     7.63 | beastik, majky, MoriiSko, oskar, SHOCK |
|           65 |     1211 | 2024-06-10 | Enterprise        | L   | 0.820      | -            | -                | -                | -         |   -16.38 | beastik, majky, MoriiSko, oskar, SHOCK |
|           64 |     1219 | 2024-06-10 | Monte             | L   | 0.820      | -            | -                | -                | -         |   -13.63 | beastik, majky, MoriiSko, oskar, SHOCK |
|           63 |     1223 | 2024-06-10 | 9 Pandas          | L   | 0.819      | -            | -                | -                | -         |   -12.76 | beastik, majky, MoriiSko, oskar, SHOCK |
|           62 |     1230 | 2024-06-10 | PARIVISION        | W   | 0.819      | -            | -                | -                | -         |    14.48 | beastik, majky, MoriiSko, oskar, SHOCK |
|           61 |     1232 | 2024-06-10 | Rare Atom         | L   | 0.819      | -            | -                | -                | -         |   -23.18 | beastik, majky, MoriiSko, oskar, SHOCK |
|           60 |     1262 | 2024-06-09 | SAW               | W   | 0.814      | -            | -                | -                | -         |    16.21 | beastik, majky, MoriiSko, oskar, SHOCK |
|           59 |     1270 | 2024-06-09 | 3DMAX             | W   | 0.813      | 0.143        | 0.510 (0.059)    | -                | -         |    23.66 | beastik, majky, MoriiSko, oskar, SHOCK |
|           58 |     1276 | 2024-06-09 | RUSH B            | L   | 0.813      | -            | -                | -                | -         |   -18.11 | beastik, majky, MoriiSko, oskar, SHOCK |
|           57 |     1285 | 2024-06-09 | Aurora            | W   | 0.812      | 0.143        | 0.420 (0.049)    | -                | -         |    23.83 | beastik, majky, MoriiSko, oskar, SHOCK |
|           56 |     1319 | 2024-06-08 | Sangal            | L   | 0.808      | -            | -                | -                | -         |    -7.13 | beastik, majky, MoriiSko, oskar, SHOCK |
|           55 |     1398 | 2024-06-07 | RUBY              | W   | 0.799      | 0.435        | 0.095 (0.033)    | -                | -         |     9.04 | beastik, majky, MoriiSko, oskar, SHOCK |
|           54 |     1441 | 2024-06-06 | KOI               | L   | 0.794      | -            | -                | -                | -         |   -11.08 | beastik, majky, MoriiSko, oskar, SHOCK |
|           53 |     1501 | 2024-06-05 | RUSH B            | W   | 0.788      | -            | -                | -                | -         |     7.57 | beastik, majky, MoriiSko, oskar, SHOCK |
|           52 |     1510 | 2024-06-05 | EYEBALLERS        | L   | 0.787      | -            | -                | -                | -         |   -17.30 | beastik, majky, MoriiSko, oskar, SHOCK |
|           51 |     1564 | 2024-06-04 | VP.Prodigy        | L   | 0.779      | -            | -                | -                | -         |   -16.22 | beastik, majky, MoriiSko, oskar, SHOCK |
|           50 |     1603 | 2024-06-02 | UNiTY             | L   | 0.767      | -            | -                | -                | -         |   -15.36 | AJTT, beastik, oskar, SHOCK, Tomkeejs  |
|           49 |     1620 | 2024-06-01 | GUN5              | L   | 0.762      | -            | -                | -                | -         |   -16.21 | AJTT, beastik, MoriiSko, oskar, SHOCK  |
|           48 |     1640 | 2024-06-01 | Sampi             | W   | 0.760      | 0.346        | -                | 1.000 (0.263)    | 1 (0.760) |     6.26 | AJTT, beastik, oskar, SHOCK, Tomkeejs  |
|           47 |     1672 | 2024-05-31 | UNiTY             | L   | 0.753      | -            | -                | -                | -         |   -15.88 | AJTT, beastik, oskar, SHOCK, Tomkeejs  |
|           46 |     1690 | 2024-05-30 | B8                | W   | 0.747      | 0.435        | 0.170 (0.055)    | 0.912 (0.296)    | -         |    14.08 | beastik, majky, MoriiSko, oskar, SHOCK |
|           45 |     1718 | 2024-05-29 | brazylijski luz   | W   | 0.741      | -            | -                | -                | -         |     4.75 | beastik, majky, MoriiSko, oskar, SHOCK |
|           44 |     1776 | 2024-05-26 | Sampi             | W   | 0.720      | 0.435        | -                | 1.000 (0.313)    | -         |     6.42 | beastik, majky, MoriiSko, oskar, SHOCK |
|           43 |     1810 | 2024-05-24 | GUN5              | W   | 0.708      | 0.435        | 0.072 (0.022)    | 0.550 (0.169)    | -         |     7.09 | AJTT, beastik, majky, MoriiSko, oskar  |
|           42 |     1818 | 2024-05-24 | 9 Pandas          | L   | 0.706      | -            | -                | -                | -         |   -12.44 | AJTT, beastik, majky, oskar, SHOCK     |
|           41 |     1829 | 2024-05-23 | UNiTY             | W   | 0.700      | -            | -                | -                | -         |     7.79 | AJTT, beastik, majky, MoriiSko, oskar  |
|           40 |     1835 | 2024-05-23 | Passion UA        | L   | 0.699      | -            | -                | -                | -         |   -12.18 | AJTT, beastik, majky, MoriiSko, oskar  |
|           39 |     1953 | 2024-05-20 | VP.Prodigy        | W   | 0.680      | -            | -                | -                | -         |     5.39 | AJTT, beastik, majky, MoriiSko, oskar  |
|           38 |     2001 | 2024-05-18 | 1WIN              | L   | 0.667      | -            | -                | -                | -         |   -12.91 | AJTT, beastik, oskar, SHOCK, Tomkeejs  |
|           37 |     2087 | 2024-05-16 | ALTERNATE aTTaX   | W   | 0.652      | -            | -                | -                | -         |     7.03 | AJTT, beastik, majky, oskar, SHOCK     |
|           36 |     2179 | 2024-05-14 | Passion UA        | W   | 0.641      | 0.435        | 0.173 (0.048)    | 1.000 (0.279)    | -         |     8.98 | AJTT, beastik, majky, oskar, SHOCK     |
|           35 |     2349 | 2024-05-07 | Nemiga            | L   | 0.593      | -            | -                | -                | -         |    -6.60 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           34 |     2384 | 2024-05-05 | Endpoint          | W   | 0.580      | -            | -                | -                | -         |     5.81 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           33 |     2447 | 2024-05-02 | Gaimin Gladiators | L   | 0.559      | -            | -                | -                | -         |   -11.17 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           32 |     2474 | 2024-05-01 | B8                | L   | 0.552      | -            | -                | -                | -         |   -10.06 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           31 |     2506 | 2024-04-29 | 1WIN              | W   | 0.540      | 0.435        | -                | 0.718 (0.169)    | -         |     5.30 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           30 |     2515 | 2024-04-29 | Sangal            | L   | 0.539      | -            | -                | -                | -         |    -7.66 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           29 |     2527 | 2024-04-28 | Zero Tenacity     | L   | 0.533      | -            | -                | -                | -         |    -9.35 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           28 |     2560 | 2024-04-27 | Zero Tenacity     | L   | 0.525      | -            | -                | -                | -         |    -9.70 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           27 |     2576 | 2024-04-26 | PARIVISION        | L   | 0.520      | -            | -                | -                | -         |    -9.32 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           26 |     2626 | 2024-04-24 | Endpoint          | L   | 0.507      | -            | -                | -                | -         |   -12.69 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           25 |     2662 | 2024-04-22 | HAVU              | W   | 0.493      | -            | -                | -                | -         |     1.23 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           24 |     2711 | 2024-04-20 | ENCE Academy      | L   | 0.480      | -            | -                | -                | -         |   -13.84 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           23 |     2766 | 2024-04-19 | ECLOT             | L   | 0.472      | -            | -                | -                | -         |    -6.78 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           22 |     2856 | 2024-04-17 | Gaimin Gladiators | L   | 0.459      | -            | -                | -                | -         |   -10.35 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           21 |     2881 | 2024-04-16 | BLEED             | L   | 0.452      | -            | -                | -                | -         |   -10.58 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           20 |     2911 | 2024-04-14 | Passion UA        | W   | 0.439      | 0.371        | 0.173 (0.028)    | -                | -         |     4.76 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           19 |     3000 | 2024-04-10 | 3DMAX             | W   | 0.415      | 0.500        | 0.510 (0.106)    | 1.000 (0.207)    | -         |    12.30 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           18 |     3027 | 2024-04-10 | UNiTY             | W   | 0.412      | -            | -                | -                | -         |     3.24 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           17 |     3053 | 2024-04-09 | 9 Pandas          | W   | 0.408      | -            | -                | -                | -         |     3.71 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           16 |     3104 | 2024-04-08 | ALTERNATE aTTaX   | W   | 0.399      | -            | -                | -                | -         |     3.24 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           15 |     3155 | 2024-04-05 | Nexus             | W   | 0.381      | -            | -                | -                | -         |     1.93 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           14 |     3247 | 2024-04-03 | Rebels            | W   | 0.366      | -            | -                | -                | -         |     3.41 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           13 |     3290 | 2024-04-01 | Aurora            | W   | 0.355      | 0.500        | 0.420 (0.075)    | -                | -         |    10.64 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           12 |     3313 | 2024-03-29 | ex-Sprout         | W   | 0.334      | -            | -                | -                | -         |     0.17 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           11 |     3532 | 2024-03-17 | ECLOT             | L   | 0.254      | -            | -                | -                | -         |    -3.36 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           10 |     3538 | 2024-03-17 | UNiTY             | W   | 0.254      | -            | -                | -                | 1 (0.254) |     2.18 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            9 |     3553 | 2024-03-16 | Sampi             | W   | 0.247      | -            | -                | -                | 1 (0.247) |     1.66 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            8 |     3565 | 2024-03-15 | UNiTY             | L   | 0.241      | -            | -                | -                | -         |    -5.58 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            7 |     3635 | 2024-03-13 | ALTERNATE aTTaX   | W   | 0.228      | -            | -                | -                | -         |     2.06 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            6 |     3688 | 2024-03-11 | brazylijski luz   | L   | 0.214      | -            | -                | -                | -         |    -5.93 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            5 |     3900 | 2024-03-03 | Gaimin Gladiators | L   | 0.161      | -            | -                | -                | -         |    -3.73 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            4 |     4193 | 2024-02-18 | Monte             | L   | 0.067      | -            | -                | -                | -         |    -1.51 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            3 |     4240 | 2024-02-16 | 500               | W   | 0.055      | -            | -                | -                | -         |     0.13 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            2 |     4243 | 2024-02-16 | PERA              | W   | 0.054      | -            | -                | -                | -         |     0.39 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            1 |     4248 | 2024-02-16 | 500               | L   | 0.054      | -            | -                | -                | -         |    -1.56 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($11,894.49)
- Divide that value by the 5th highest value among all rosters ($320,329.44)
- The final value (0.04) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-13 |      0.841 | $545.00        | $458.61         |
| 2024-06-09 |      0.814 | $10,000.00     | $8,140.05       |
| 2024-06-02 |      0.767 | $1,306.00      | $1,002.17       |
| 2024-06-02 |      0.767 | $2,000.00      | $1,534.26       |
| 2024-03-17 |      0.254 | $2,984.00      | $759.40         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
