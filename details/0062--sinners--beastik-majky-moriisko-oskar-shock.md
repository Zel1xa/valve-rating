### Roster Details<br />
Team Name: SINNERS<br />
Roster: beastik, majky, MoriiSko, oskar, SHOCK<br />
Global Rank: [62](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [45]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1005.7<br />
<br />
Final Rank Value (1005.7) = Starting Rank Value (1151.8) + Head To Head Adjustments (-146.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.411[<sup>1</sup>](#table2)
- Bounty Collected: 0.434[<sup>2</sup>](#table1)
- Opponent Network: 0.240[<sup>2</sup>](#table1)
- LAN Wins: 0.376[<sup>2</sup>](#table1)

The average of these factors is 0.365<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1151.8
- 400 + ( ( 0.365 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1151.8


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
|           82 |        5 | 2024-08-06 | brazylijski luz   | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.21 | beastik, majky, MoriiSko, oskar, SHOCK |
|           81 |       27 | 2024-08-05 | Rebels            | W   | 1.000      | 0.500        | 0.038 (0.019)    | 0.578 (0.289)    | 0 (0.000) |    16.62 | beastik, majky, MoriiSko, oskar, SHOCK |
|           80 |       61 | 2024-08-04 | AVEZ              | W   | 1.000      | -            | -                | -                | 1 (1.000) |     5.84 | beastik, majky, MoriiSko, oskar, SHOCK |
|           79 |       97 | 2024-08-03 | SINNERS Academy   | W   | 1.000      | -            | -                | -                | 1 (1.000) |     2.43 | beastik, majky, MoriiSko, oskar, SHOCK |
|           78 |      119 | 2024-08-02 | ECLOT             | L   | 1.000      | -            | -                | -                | -         |   -11.24 | beastik, majky, MoriiSko, oskar, SHOCK |
|           77 |      268 | 2024-07-30 | Sangal            | L   | 1.000      | -            | -                | -                | -         |    -5.11 | beastik, majky, MoriiSko, oskar, SHOCK |
|           76 |      303 | 2024-07-29 | Alliance          | W   | 1.000      | -            | -                | -                | 0 (0.000) |    10.30 | beastik, majky, MoriiSko, oskar, SHOCK |
|           75 |      407 | 2024-07-25 | B8                | L   | 1.000      | -            | -                | -                | -         |    -8.39 | beastik, majky, MoriiSko, oskar, SHOCK |
|           74 |      482 | 2024-07-23 | RUSH B            | L   | 1.000      | -            | -                | -                | -         |   -19.13 | beastik, majky, MoriiSko, oskar, SHOCK |
|           73 |      516 | 2024-07-22 | CPH Wolves        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.33 | beastik, majky, MoriiSko, oskar, SHOCK |
|           72 |      599 | 2024-07-19 | DMS               | W   | 1.000      | 0.435        | -                | 0.428 (0.186)    | 0 (0.000) |    12.40 | beastik, majky, MoriiSko, oskar, SHOCK |
|           71 |      729 | 2024-07-17 | Endpoint          | W   | 1.000      | 0.435        | -                | 0.540 (0.235)    | -         |    10.63 | beastik, majky, MoriiSko, oskar, SHOCK |
|           70 |      798 | 2024-07-16 | BC.Game           | L   | 1.000      | -            | -                | -                | -         |   -19.77 | beastik, majky, MoriiSko, oskar, SHOCK |
|           69 |      827 | 2024-07-15 | SAW               | L   | 1.000      | -            | -                | -                | -         |    -8.59 | beastik, majky, MoriiSko, oskar, SHOCK |
|           68 |      840 | 2024-07-15 | Nexus             | L   | 1.000      | -            | -                | -                | -         |   -25.62 | beastik, majky, MoriiSko, oskar, SHOCK |
|           67 |     1200 | 2024-06-11 | 3DMAX             | L   | 0.827      | -            | -                | -                | -         |    -2.43 | beastik, majky, MoriiSko, oskar, SHOCK |
|           66 |     1214 | 2024-06-11 | ex-Guild Eagles   | W   | 0.825      | -            | -                | -                | -         |     7.52 | beastik, majky, MoriiSko, oskar, SHOCK |
|           65 |     1228 | 2024-06-10 | Enterprise        | L   | 0.820      | -            | -                | -                | -         |   -16.52 | beastik, majky, MoriiSko, oskar, SHOCK |
|           64 |     1236 | 2024-06-10 | Monte             | L   | 0.819      | -            | -                | -                | -         |   -13.74 | beastik, majky, MoriiSko, oskar, SHOCK |
|           63 |     1240 | 2024-06-10 | 9 Pandas          | L   | 0.819      | -            | -                | -                | -         |   -12.73 | beastik, majky, MoriiSko, oskar, SHOCK |
|           62 |     1247 | 2024-06-10 | PARIVISION        | W   | 0.818      | -            | -                | -                | -         |    15.02 | beastik, majky, MoriiSko, oskar, SHOCK |
|           61 |     1249 | 2024-06-10 | Rare Atom         | L   | 0.818      | -            | -                | -                | -         |   -19.79 | beastik, majky, MoriiSko, oskar, SHOCK |
|           60 |     1279 | 2024-06-09 | SAW               | W   | 0.813      | -            | -                | -                | -         |    16.24 | beastik, majky, MoriiSko, oskar, SHOCK |
|           59 |     1287 | 2024-06-09 | 3DMAX             | W   | 0.812      | 0.143        | 0.510 (0.059)    | -                | -         |    23.62 | beastik, majky, MoriiSko, oskar, SHOCK |
|           58 |     1293 | 2024-06-09 | RUSH B            | L   | 0.812      | -            | -                | -                | -         |   -18.13 | beastik, majky, MoriiSko, oskar, SHOCK |
|           57 |     1302 | 2024-06-09 | Aurora            | W   | 0.812      | 0.143        | 0.420 (0.049)    | -                | -         |    23.80 | beastik, majky, MoriiSko, oskar, SHOCK |
|           56 |     1336 | 2024-06-08 | Sangal            | L   | 0.807      | -            | -                | -                | -         |    -6.71 | beastik, majky, MoriiSko, oskar, SHOCK |
|           55 |     1415 | 2024-06-07 | RUBY              | W   | 0.798      | 0.435        | 0.095 (0.033)    | -                | -         |     9.17 | beastik, majky, MoriiSko, oskar, SHOCK |
|           54 |     1458 | 2024-06-06 | KOI               | L   | 0.793      | -            | -                | -                | -         |   -11.11 | beastik, majky, MoriiSko, oskar, SHOCK |
|           53 |     1518 | 2024-06-05 | RUSH B            | W   | 0.787      | -            | -                | -                | -         |     7.55 | beastik, majky, MoriiSko, oskar, SHOCK |
|           52 |     1527 | 2024-06-05 | EYEBALLERS        | L   | 0.786      | -            | -                | -                | -         |   -17.29 | beastik, majky, MoriiSko, oskar, SHOCK |
|           51 |     1581 | 2024-06-04 | VP.Prodigy        | L   | 0.778      | -            | -                | -                | -         |   -16.22 | beastik, majky, MoriiSko, oskar, SHOCK |
|           50 |     1620 | 2024-06-02 | UNiTY             | L   | 0.766      | -            | -                | -                | -         |   -15.39 | AJTT, beastik, oskar, SHOCK, Tomkeejs  |
|           49 |     1637 | 2024-06-01 | GUN5              | L   | 0.761      | -            | -                | -                | -         |   -16.13 | AJTT, beastik, MoriiSko, oskar, SHOCK  |
|           48 |     1657 | 2024-06-01 | Sampi             | W   | 0.759      | 0.346        | -                | 1.000 (0.262)    | 1 (0.759) |     6.26 | AJTT, beastik, oskar, SHOCK, Tomkeejs  |
|           47 |     1689 | 2024-05-31 | UNiTY             | L   | 0.752      | -            | -                | -                | -         |   -15.92 | AJTT, beastik, oskar, SHOCK, Tomkeejs  |
|           46 |     1707 | 2024-05-30 | B8                | W   | 0.746      | 0.435        | 0.170 (0.055)    | 0.912 (0.296)    | -         |    14.07 | beastik, majky, MoriiSko, oskar, SHOCK |
|           45 |     1735 | 2024-05-29 | brazylijski luz   | W   | 0.740      | -            | -                | -                | -         |     4.71 | beastik, majky, MoriiSko, oskar, SHOCK |
|           44 |     1793 | 2024-05-26 | Sampi             | W   | 0.720      | 0.435        | -                | 1.000 (0.313)    | -         |     6.41 | beastik, majky, MoriiSko, oskar, SHOCK |
|           43 |     1827 | 2024-05-24 | GUN5              | W   | 0.707      | 0.435        | 0.072 (0.022)    | 0.550 (0.169)    | -         |     7.14 | AJTT, beastik, majky, MoriiSko, oskar  |
|           42 |     1835 | 2024-05-24 | 9 Pandas          | L   | 0.705      | -            | -                | -                | -         |   -12.27 | AJTT, beastik, majky, oskar, SHOCK     |
|           41 |     1846 | 2024-05-23 | UNiTY             | W   | 0.700      | -            | -                | -                | -         |     7.72 | AJTT, beastik, majky, MoriiSko, oskar  |
|           40 |     1852 | 2024-05-23 | Passion UA        | L   | 0.698      | -            | -                | -                | -         |   -12.15 | AJTT, beastik, majky, MoriiSko, oskar  |
|           39 |     1970 | 2024-05-20 | VP.Prodigy        | W   | 0.679      | -            | -                | -                | -         |     5.37 | AJTT, beastik, majky, MoriiSko, oskar  |
|           38 |     2018 | 2024-05-18 | 1WIN              | L   | 0.666      | -            | -                | -                | -         |   -12.89 | AJTT, beastik, oskar, SHOCK, Tomkeejs  |
|           37 |     2104 | 2024-05-16 | ALTERNATE aTTaX   | W   | 0.651      | -            | -                | -                | -         |     7.04 | AJTT, beastik, majky, oskar, SHOCK     |
|           36 |     2196 | 2024-05-14 | Passion UA        | W   | 0.640      | 0.435        | 0.173 (0.048)    | 1.000 (0.278)    | -         |     8.97 | AJTT, beastik, majky, oskar, SHOCK     |
|           35 |     2366 | 2024-05-07 | Nemiga            | L   | 0.592      | -            | -                | -                | -         |    -6.59 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           34 |     2401 | 2024-05-05 | Endpoint          | W   | 0.579      | -            | -                | -                | -         |     5.82 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           33 |     2464 | 2024-05-02 | Gaimin Gladiators | L   | 0.558      | -            | -                | -                | -         |   -11.18 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           32 |     2491 | 2024-05-01 | B8                | L   | 0.551      | -            | -                | -                | -         |   -10.05 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           31 |     2523 | 2024-04-29 | 1WIN              | W   | 0.539      | 0.435        | -                | 0.718 (0.168)    | -         |     5.29 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           30 |     2532 | 2024-04-29 | Sangal            | L   | 0.538      | -            | -                | -                | -         |    -7.16 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           29 |     2544 | 2024-04-28 | Zero Tenacity     | L   | 0.532      | -            | -                | -                | -         |    -9.33 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           28 |     2577 | 2024-04-27 | Zero Tenacity     | L   | 0.525      | -            | -                | -                | -         |    -9.68 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           27 |     2593 | 2024-04-26 | PARIVISION        | L   | 0.519      | -            | -                | -                | -         |    -8.64 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           26 |     2643 | 2024-04-24 | Endpoint          | L   | 0.506      | -            | -                | -                | -         |   -12.63 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           25 |     2679 | 2024-04-22 | HAVU              | W   | 0.492      | -            | -                | -                | -         |     1.22 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           24 |     2728 | 2024-04-20 | ENCE Academy      | L   | 0.479      | -            | -                | -                | -         |   -13.82 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           23 |     2783 | 2024-04-19 | ECLOT             | L   | 0.471      | -            | -                | -                | -         |    -6.77 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           22 |     2873 | 2024-04-17 | Gaimin Gladiators | L   | 0.458      | -            | -                | -                | -         |   -10.33 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           21 |     2898 | 2024-04-16 | BLEED             | L   | 0.451      | -            | -                | -                | -         |   -10.55 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           20 |     2928 | 2024-04-14 | Passion UA        | W   | 0.439      | 0.371        | 0.173 (0.028)    | -                | -         |     4.74 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           19 |     3017 | 2024-04-10 | 3DMAX             | W   | 0.414      | 0.500        | 0.510 (0.106)    | 1.000 (0.207)    | -         |    12.27 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           18 |     3044 | 2024-04-10 | UNiTY             | W   | 0.411      | -            | -                | -                | -         |     3.23 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           17 |     3070 | 2024-04-09 | 9 Pandas          | W   | 0.407      | -            | -                | -                | -         |     3.83 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           16 |     3121 | 2024-04-08 | ALTERNATE aTTaX   | W   | 0.398      | -            | -                | -                | -         |     3.26 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           15 |     3172 | 2024-04-05 | Nexus             | W   | 0.380      | -            | -                | -                | -         |     1.93 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           14 |     3264 | 2024-04-03 | Rebels            | W   | 0.365      | -            | -                | -                | -         |     3.41 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           13 |     3307 | 2024-04-01 | Aurora            | W   | 0.354      | 0.500        | 0.420 (0.074)    | -                | -         |    10.61 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           12 |     3330 | 2024-03-29 | ex-Sprout         | W   | 0.333      | -            | -                | -                | -         |     0.17 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           11 |     3549 | 2024-03-17 | ECLOT             | L   | 0.254      | -            | -                | -                | -         |    -3.35 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           10 |     3555 | 2024-03-17 | UNiTY             | W   | 0.253      | -            | -                | -                | 1 (0.253) |     2.17 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            9 |     3570 | 2024-03-16 | Sampi             | W   | 0.246      | -            | -                | -                | 1 (0.246) |     1.66 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            8 |     3582 | 2024-03-15 | UNiTY             | L   | 0.241      | -            | -                | -                | -         |    -5.56 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            7 |     3652 | 2024-03-13 | ALTERNATE aTTaX   | W   | 0.227      | -            | -                | -                | -         |     2.07 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            6 |     3705 | 2024-03-11 | brazylijski luz   | L   | 0.213      | -            | -                | -                | -         |    -5.91 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            5 |     3917 | 2024-03-03 | Gaimin Gladiators | L   | 0.160      | -            | -                | -                | -         |    -3.72 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            4 |     4210 | 2024-02-18 | Monte             | L   | 0.067      | -            | -                | -                | -         |    -1.49 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            3 |     4257 | 2024-02-16 | 500               | W   | 0.054      | -            | -                | -                | -         |     0.13 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            2 |     4260 | 2024-02-16 | PERA              | W   | 0.053      | -            | -                | -                | -         |     0.38 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            1 |     4265 | 2024-02-16 | 500               | L   | 0.053      | -            | -                | -                | -         |    -1.53 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($11,879.68)
- Divide that value by the 5th highest value among all rosters ($320,068.63)
- The final value (0.04) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-13 |      0.841 | $545.00        | $458.13         |
| 2024-06-09 |      0.813 | $10,000.00     | $8,131.25       |
| 2024-06-02 |      0.766 | $1,306.00      | $1,001.02       |
| 2024-06-02 |      0.766 | $2,000.00      | $1,532.50       |
| 2024-03-17 |      0.254 | $2,984.00      | $756.78         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
