### Roster Details<br />
Team Name: SINNERS<br />
Roster: beastik, majky, MoriiSko, oskar, SHOCK<br />
Global Rank: [70](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [50]( ../standings_europe.md)<br />
<br />
Final Rank Value:  956.3<br />
<br />
Final Rank Value (956.3) = Starting Rank Value (1056.0) + Head To Head Adjustments (-99.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.413[<sup>1</sup>](#table2)
- Bounty Collected: 0.450[<sup>2</sup>](#table1)
- Opponent Network: 0.254[<sup>2</sup>](#table1)
- LAN Wins: 0.157[<sup>2</sup>](#table1)

The average of these factors is 0.319<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1056.0
- 400 + ( ( 0.319 - 0.000 ) / ( 0.777 - 0.000 ) ) * 1600 = 1056.0


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
|           80 |       96 | 2024-07-30 | Sangal            | L   | 1.000      | -            | -                | -                | -         |    -5.40 | beastik, majky, MoriiSko, oskar, SHOCK |
|           79 |      130 | 2024-07-29 | Alliance          | W   | 1.000      | -            | -                | -                | 0 (0.000) |    11.44 | beastik, majky, MoriiSko, oskar, SHOCK |
|           78 |      236 | 2024-07-25 | B8                | L   | 1.000      | -            | -                | -                | -         |    -7.90 | beastik, majky, MoriiSko, oskar, SHOCK |
|           77 |      310 | 2024-07-23 | RUSH B            | L   | 1.000      | -            | -                | -                | -         |   -18.40 | beastik, majky, MoriiSko, oskar, SHOCK |
|           76 |      346 | 2024-07-22 | CPH Wolves        | W   | 1.000      | -            | -                | -                | 0 (0.000) |    10.51 | beastik, majky, MoriiSko, oskar, SHOCK |
|           75 |      432 | 2024-07-19 | DMS               | W   | 1.000      | 0.435        | -                | 0.447 (0.194)    | 0 (0.000) |    13.29 | beastik, majky, MoriiSko, oskar, SHOCK |
|           74 |      567 | 2024-07-17 | Endpoint          | W   | 1.000      | 0.435        | -                | 0.555 (0.241)    | 0 (0.000) |    12.63 | beastik, majky, MoriiSko, oskar, SHOCK |
|           73 |      638 | 2024-07-16 | BC.Game           | L   | 1.000      | -            | -                | -                | -         |   -26.71 | beastik, majky, MoriiSko, oskar, SHOCK |
|           72 |      671 | 2024-07-15 | SAW               | L   | 1.000      | -            | -                | -                | -         |    -7.63 | beastik, majky, MoriiSko, oskar, SHOCK |
|           71 |      685 | 2024-07-15 | Nexus             | L   | 1.000      | -            | -                | -                | -         |   -24.21 | beastik, majky, MoriiSko, oskar, SHOCK |
|           70 |     1036 | 2024-06-11 | 3DMAX             | L   | 0.862      | -            | -                | -                | -         |    -2.41 | beastik, majky, MoriiSko, oskar, SHOCK |
|           69 |     1050 | 2024-06-11 | ex-Guild Eagles   | W   | 0.860      | -            | -                | -                | 0 (0.000) |     8.90 | beastik, majky, MoriiSko, oskar, SHOCK |
|           68 |     1065 | 2024-06-10 | Enterprise        | L   | 0.854      | -            | -                | -                | -         |   -16.39 | beastik, majky, MoriiSko, oskar, SHOCK |
|           67 |     1073 | 2024-06-10 | Monte             | L   | 0.854      | -            | -                | -                | -         |   -13.48 | beastik, majky, MoriiSko, oskar, SHOCK |
|           66 |     1077 | 2024-06-10 | 9 Pandas          | L   | 0.853      | -            | -                | -                | -         |   -12.23 | beastik, majky, MoriiSko, oskar, SHOCK |
|           65 |     1084 | 2024-06-10 | PARIVISION        | W   | 0.853      | -            | -                | -                | 0 (0.000) |    15.79 | beastik, majky, MoriiSko, oskar, SHOCK |
|           64 |     1086 | 2024-06-10 | Rare Atom         | L   | 0.852      | -            | -                | -                | -         |   -23.74 | beastik, majky, MoriiSko, oskar, SHOCK |
|           63 |     1116 | 2024-06-09 | SAW               | W   | 0.847      | -            | -                | -                | 0 (0.000) |    18.01 | beastik, majky, MoriiSko, oskar, SHOCK |
|           62 |     1124 | 2024-06-09 | 3DMAX             | W   | 0.847      | 0.143        | 0.505 (0.061)    | -                | -         |    24.75 | beastik, majky, MoriiSko, oskar, SHOCK |
|           61 |     1130 | 2024-06-09 | RUSH B            | L   | 0.847      | -            | -                | -                | -         |   -18.38 | beastik, majky, MoriiSko, oskar, SHOCK |
|           60 |     1140 | 2024-06-09 | Aurora            | W   | 0.846      | 0.143        | 0.432 (0.052)    | -                | -         |    24.98 | beastik, majky, MoriiSko, oskar, SHOCK |
|           59 |     1175 | 2024-06-08 | Sangal            | L   | 0.841      | -            | -                | -                | -         |    -7.24 | beastik, majky, MoriiSko, oskar, SHOCK |
|           58 |     1261 | 2024-06-07 | RUBY              | W   | 0.833      | 0.435        | 0.097 (0.035)    | 0.544 (0.197)    | -         |    10.54 | beastik, majky, MoriiSko, oskar, SHOCK |
|           57 |     1306 | 2024-06-06 | KOI               | L   | 0.828      | -            | -                | -                | -         |   -14.41 | beastik, majky, MoriiSko, oskar, SHOCK |
|           56 |     1369 | 2024-06-05 | RUSH B            | W   | 0.821      | -            | -                | -                | -         |     8.35 | beastik, majky, MoriiSko, oskar, SHOCK |
|           55 |     1378 | 2024-06-05 | EYEBALLERS        | L   | 0.821      | -            | -                | -                | -         |   -17.13 | beastik, majky, MoriiSko, oskar, SHOCK |
|           54 |     1432 | 2024-06-04 | VP.Prodigy        | L   | 0.813      | -            | -                | -                | -         |   -15.82 | beastik, majky, MoriiSko, oskar, SHOCK |
|           53 |     1472 | 2024-06-02 | UNiTY             | L   | 0.800      | -            | -                | -                | -         |   -15.32 | AJTT, beastik, oskar, SHOCK, Tomkeejs  |
|           52 |     1489 | 2024-06-01 | GUN5              | L   | 0.795      | -            | -                | -                | -         |   -15.21 | AJTT, beastik, MoriiSko, oskar, SHOCK  |
|           51 |     1509 | 2024-06-01 | Sampi             | W   | 0.793      | 0.346        | -                | 1.000 (0.274)    | 1 (0.793) |     7.18 | AJTT, beastik, oskar, SHOCK, Tomkeejs  |
|           50 |     1541 | 2024-05-31 | UNiTY             | L   | 0.787      | -            | -                | -                | -         |   -15.76 | AJTT, beastik, oskar, SHOCK, Tomkeejs  |
|           49 |     1559 | 2024-05-30 | B8                | W   | 0.781      | 0.435        | 0.168 (0.057)    | 0.878 (0.298)    | -         |    15.32 | beastik, majky, MoriiSko, oskar, SHOCK |
|           48 |     1587 | 2024-05-29 | brazylijski luz   | W   | 0.774      | -            | -                | -                | -         |     6.38 | beastik, majky, MoriiSko, oskar, SHOCK |
|           47 |     1647 | 2024-05-26 | Sampi             | W   | 0.754      | 0.435        | -                | 1.000 (0.328)    | -         |     7.55 | beastik, majky, MoriiSko, oskar, SHOCK |
|           46 |     1681 | 2024-05-24 | GUN5              | W   | 0.742      | 0.435        | -                | 0.555 (0.179)    | -         |     9.31 | AJTT, beastik, majky, MoriiSko, oskar  |
|           45 |     1689 | 2024-05-24 | 9 Pandas          | L   | 0.740      | -            | -                | -                | -         |   -11.55 | AJTT, beastik, majky, oskar, SHOCK     |
|           44 |     1700 | 2024-05-23 | UNiTY             | W   | 0.734      | -            | -                | -                | -         |     9.18 | AJTT, beastik, majky, MoriiSko, oskar  |
|           43 |     1706 | 2024-05-23 | Passion UA        | L   | 0.733      | -            | -                | -                | -         |   -11.80 | AJTT, beastik, majky, MoriiSko, oskar  |
|           42 |     1844 | 2024-05-20 | VP.Prodigy        | W   | 0.713      | -            | -                | -                | -         |     6.78 | AJTT, beastik, majky, MoriiSko, oskar  |
|           41 |     1861 | 2024-05-19 | Zero Tenacity     | W   | 0.709      | 0.435        | 0.139 (0.043)    | 1.000 (0.308)    | -         |    12.51 | AJTT, beastik, oskar, SHOCK, Tomkeejs  |
|           40 |     1897 | 2024-05-18 | 1WIN              | L   | 0.701      | -            | -                | -                | -         |   -12.64 | AJTT, beastik, oskar, SHOCK, Tomkeejs  |
|           39 |     1984 | 2024-05-16 | ALTERNATE aTTaX   | W   | 0.686      | -            | -                | -                | -         |     8.55 | AJTT, beastik, majky, oskar, SHOCK     |
|           38 |     2082 | 2024-05-14 | Passion UA        | W   | 0.675      | 0.435        | 0.172 (0.051)    | 1.000 (0.293)    | -         |    10.78 | AJTT, beastik, majky, oskar, SHOCK     |
|           37 |     2257 | 2024-05-07 | Nemiga            | L   | 0.626      | -            | -                | -                | -         |    -5.89 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           36 |     2292 | 2024-05-05 | Endpoint          | W   | 0.614      | -            | -                | -                | -         |     8.10 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           35 |     2356 | 2024-05-02 | Gaimin Gladiators | L   | 0.593      | -            | -                | -                | -         |    -9.77 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           34 |     2384 | 2024-05-01 | B8                | L   | 0.586      | -            | -                | -                | -         |    -9.21 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           33 |     2417 | 2024-04-29 | 1WIN              | W   | 0.574      | -            | -                | -                | -         |     6.37 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           32 |     2426 | 2024-04-29 | Sangal            | L   | 0.573      | -            | -                | -                | -         |    -6.90 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           31 |     2438 | 2024-04-28 | Zero Tenacity     | L   | 0.567      | -            | -                | -                | -         |    -8.51 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           30 |     2472 | 2024-04-27 | Zero Tenacity     | L   | 0.559      | -            | -                | -                | -         |    -8.90 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           29 |     2487 | 2024-04-26 | PARIVISION        | L   | 0.554      | -            | -                | -                | -         |    -8.40 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           28 |     2537 | 2024-04-24 | Endpoint          | L   | 0.540      | -            | -                | -                | -         |   -11.97 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           27 |     2551 | 2024-04-23 | Nemiga            | W   | 0.535      | 0.435        | 0.324 (0.075)    | -                | -         |    10.78 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           26 |     2576 | 2024-04-22 | HAVU              | W   | 0.526      | -            | -                | -                | -         |     2.02 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           25 |     2628 | 2024-04-20 | ENCE Academy      | L   | 0.513      | -            | -                | -                | -         |   -13.96 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           24 |     2684 | 2024-04-19 | ECLOT             | L   | 0.506      | -            | -                | -                | -         |    -7.70 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           23 |     2776 | 2024-04-17 | Gaimin Gladiators | L   | 0.493      | -            | -                | -                | -         |    -9.03 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           22 |     2802 | 2024-04-16 | BLEED             | L   | 0.486      | -            | -                | -                | -         |    -9.69 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           21 |     2832 | 2024-04-14 | Passion UA        | W   | 0.473      | 0.371        | 0.172 (0.030)    | -                | -         |     6.69 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           20 |     2922 | 2024-04-10 | 3DMAX             | W   | 0.448      | 0.500        | 0.505 (0.113)    | 1.000 (0.224)    | -         |    13.57 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           19 |     2949 | 2024-04-10 | UNiTY             | W   | 0.446      | -            | -                | -                | -         |     4.82 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           18 |     2975 | 2024-04-09 | 9 Pandas          | W   | 0.442      | -            | -                | -                | -         |     5.64 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           17 |     3026 | 2024-04-08 | ALTERNATE aTTaX   | W   | 0.432      | -            | -                | -                | -         |     4.95 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           16 |     3077 | 2024-04-05 | Nexus             | W   | 0.414      | -            | -                | -                | -         |     3.18 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           15 |     3175 | 2024-04-03 | Rebels            | W   | 0.399      | -            | -                | -                | -         |     5.32 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           14 |     3220 | 2024-04-01 | Aurora            | W   | 0.388      | 0.500        | 0.432 (0.084)    | -                | -         |    11.89 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           13 |     3243 | 2024-03-29 | ex-Sprout         | W   | 0.368      | -            | -                | -                | -         |     0.31 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           12 |     3467 | 2024-03-17 | ECLOT             | L   | 0.288      | -            | -                | -                | -         |    -3.95 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           11 |     3473 | 2024-03-17 | UNiTY             | W   | 0.287      | -            | -                | -                | 1 (0.287) |     3.49 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           10 |     3488 | 2024-03-16 | Sampi             | W   | 0.281      | -            | -                | -                | 1 (0.281) |     2.87 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            9 |     3500 | 2024-03-15 | UNiTY             | L   | 0.275      | -            | -                | -                | -         |    -5.35 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            8 |     3574 | 2024-03-13 | ALTERNATE aTTaX   | W   | 0.262      | -            | -                | -                | -         |     3.39 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            7 |     3628 | 2024-03-11 | brazylijski luz   | L   | 0.248      | -            | -                | -                | -         |    -6.23 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            6 |     3846 | 2024-03-03 | Gaimin Gladiators | L   | 0.195      | -            | -                | -                | -         |    -3.59 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            5 |     4149 | 2024-02-18 | Monte             | L   | 0.101      | -            | -                | -                | -         |    -1.78 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            4 |     4196 | 2024-02-16 | 500               | W   | 0.088      | -            | -                | -                | -         |     0.39 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            3 |     4199 | 2024-02-16 | PERA              | W   | 0.088      | -            | -                | -                | -         |     0.93 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            2 |     4204 | 2024-02-16 | 500               | L   | 0.087      | -            | -                | -                | -         |    -2.37 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            1 |     4423 | 2024-02-04 | Into the Breach   | L   | 0.007      | -            | -                | -                | -         |    -0.19 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($12,461.89)
- Divide that value by the 5th highest value among all rosters ($327,422.13)
- The final value (0.04) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-13 |      0.875 | $545.00        | $476.98         |
| 2024-06-09 |      0.848 | $10,000.00     | $8,477.08       |
| 2024-06-02 |      0.801 | $1,306.00      | $1,046.19       |
| 2024-06-02 |      0.801 | $2,000.00      | $1,601.67       |
| 2024-03-17 |      0.288 | $2,984.00      | $859.97         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
