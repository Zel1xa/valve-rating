### Roster Details<br />
Team Name: SINNERS<br />
Roster: beastik, majky, MoriiSko, oskar, SHOCK<br />
Global Rank: [64](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [47]( ../standings_europe.md)<br />
<br />
Final Rank Value:  993.5<br />
<br />
Final Rank Value (993.5) = Starting Rank Value (1151.1) + Head To Head Adjustments (-157.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.411[<sup>1</sup>](#table2)
- Bounty Collected: 0.434[<sup>2</sup>](#table1)
- Opponent Network: 0.239[<sup>2</sup>](#table1)
- LAN Wins: 0.376[<sup>2</sup>](#table1)

The average of these factors is 0.365<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1151.1
- 400 + ( ( 0.365 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1151.1


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
|           81 |       15 | 2024-08-05 | Rebels            | W   | 1.000      | 0.500        | 0.038 (0.019)    | 0.578 (0.289)    | 0 (0.000) |    16.67 | beastik, majky, MoriiSko, oskar, SHOCK |
|           80 |       49 | 2024-08-04 | AVEZ              | W   | 1.000      | -            | -                | -                | 1 (1.000) |     5.92 | beastik, majky, MoriiSko, oskar, SHOCK |
|           79 |       85 | 2024-08-03 | SINNERS Academy   | W   | 1.000      | -            | -                | -                | 1 (1.000) |     2.47 | beastik, majky, MoriiSko, oskar, SHOCK |
|           78 |      107 | 2024-08-02 | ECLOT             | L   | 1.000      | -            | -                | -                | -         |   -11.16 | beastik, majky, MoriiSko, oskar, SHOCK |
|           77 |      255 | 2024-07-30 | Sangal            | L   | 1.000      | -            | -                | -                | -         |    -5.31 | beastik, majky, MoriiSko, oskar, SHOCK |
|           76 |      291 | 2024-07-29 | Alliance          | W   | 1.000      | -            | -                | -                | 0 (0.000) |    10.37 | beastik, majky, MoriiSko, oskar, SHOCK |
|           75 |      395 | 2024-07-25 | B8                | L   | 1.000      | -            | -                | -                | -         |    -8.38 | beastik, majky, MoriiSko, oskar, SHOCK |
|           74 |      470 | 2024-07-23 | RUSH B            | L   | 1.000      | -            | -                | -                | -         |   -19.11 | beastik, majky, MoriiSko, oskar, SHOCK |
|           73 |      504 | 2024-07-22 | CPH Wolves        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.42 | beastik, majky, MoriiSko, oskar, SHOCK |
|           72 |      587 | 2024-07-19 | DMS               | W   | 1.000      | 0.435        | -                | 0.428 (0.186)    | 0 (0.000) |    12.43 | beastik, majky, MoriiSko, oskar, SHOCK |
|           71 |      717 | 2024-07-17 | Endpoint          | W   | 1.000      | 0.435        | -                | 0.502 (0.218)    | 0 (0.000) |    10.63 | beastik, majky, MoriiSko, oskar, SHOCK |
|           70 |      786 | 2024-07-16 | BC.Game           | L   | 1.000      | -            | -                | -                | -         |   -19.72 | beastik, majky, MoriiSko, oskar, SHOCK |
|           69 |      815 | 2024-07-15 | SAW               | L   | 1.000      | -            | -                | -                | -         |    -8.60 | beastik, majky, MoriiSko, oskar, SHOCK |
|           68 |      828 | 2024-07-15 | Nexus             | L   | 1.000      | -            | -                | -                | -         |   -25.59 | beastik, majky, MoriiSko, oskar, SHOCK |
|           67 |     1188 | 2024-06-11 | 3DMAX             | L   | 0.828      | -            | -                | -                | -         |    -2.42 | beastik, majky, MoriiSko, oskar, SHOCK |
|           66 |     1202 | 2024-06-11 | ex-Guild Eagles   | W   | 0.826      | -            | -                | -                | -         |     7.54 | beastik, majky, MoriiSko, oskar, SHOCK |
|           65 |     1216 | 2024-06-10 | Enterprise        | L   | 0.821      | -            | -                | -                | -         |   -16.49 | beastik, majky, MoriiSko, oskar, SHOCK |
|           64 |     1224 | 2024-06-10 | Monte             | L   | 0.820      | -            | -                | -                | -         |   -13.74 | beastik, majky, MoriiSko, oskar, SHOCK |
|           63 |     1228 | 2024-06-10 | 9 Pandas          | L   | 0.820      | -            | -                | -                | -         |   -12.88 | beastik, majky, MoriiSko, oskar, SHOCK |
|           62 |     1235 | 2024-06-10 | PARIVISION        | W   | 0.819      | -            | -                | -                | -         |    14.36 | beastik, majky, MoriiSko, oskar, SHOCK |
|           61 |     1237 | 2024-06-10 | Rare Atom         | L   | 0.819      | -            | -                | -                | -         |   -19.81 | beastik, majky, MoriiSko, oskar, SHOCK |
|           60 |     1267 | 2024-06-09 | SAW               | W   | 0.814      | -            | -                | -                | -         |    16.22 | beastik, majky, MoriiSko, oskar, SHOCK |
|           59 |     1275 | 2024-06-09 | 3DMAX             | W   | 0.814      | 0.143        | 0.510 (0.059)    | -                | -         |    23.67 | beastik, majky, MoriiSko, oskar, SHOCK |
|           58 |     1281 | 2024-06-09 | RUSH B            | L   | 0.813      | -            | -                | -                | -         |   -18.13 | beastik, majky, MoriiSko, oskar, SHOCK |
|           57 |     1290 | 2024-06-09 | Aurora            | W   | 0.813      | 0.143        | 0.420 (0.049)    | -                | -         |    23.84 | beastik, majky, MoriiSko, oskar, SHOCK |
|           56 |     1324 | 2024-06-08 | Sangal            | L   | 0.808      | -            | -                | -                | -         |    -7.08 | beastik, majky, MoriiSko, oskar, SHOCK |
|           55 |     1403 | 2024-06-07 | RUBY              | W   | 0.800      | 0.435        | 0.095 (0.033)    | -                | -         |     9.17 | beastik, majky, MoriiSko, oskar, SHOCK |
|           54 |     1446 | 2024-06-06 | KOI               | L   | 0.795      | -            | -                | -                | -         |   -11.08 | beastik, majky, MoriiSko, oskar, SHOCK |
|           53 |     1506 | 2024-06-05 | RUSH B            | W   | 0.788      | -            | -                | -                | -         |     7.58 | beastik, majky, MoriiSko, oskar, SHOCK |
|           52 |     1515 | 2024-06-05 | EYEBALLERS        | L   | 0.787      | -            | -                | -                | -         |   -17.30 | beastik, majky, MoriiSko, oskar, SHOCK |
|           51 |     1569 | 2024-06-04 | VP.Prodigy        | L   | 0.780      | -            | -                | -                | -         |   -16.22 | beastik, majky, MoriiSko, oskar, SHOCK |
|           50 |     1608 | 2024-06-02 | UNiTY             | L   | 0.767      | -            | -                | -                | -         |   -15.36 | AJTT, beastik, oskar, SHOCK, Tomkeejs  |
|           49 |     1625 | 2024-06-01 | GUN5              | L   | 0.762      | -            | -                | -                | -         |   -16.21 | AJTT, beastik, MoriiSko, oskar, SHOCK  |
|           48 |     1645 | 2024-06-01 | Sampi             | W   | 0.760      | 0.346        | -                | 1.000 (0.263)    | 1 (0.760) |     6.27 | AJTT, beastik, oskar, SHOCK, Tomkeejs  |
|           47 |     1677 | 2024-05-31 | UNiTY             | L   | 0.754      | -            | -                | -                | -         |   -15.89 | AJTT, beastik, oskar, SHOCK, Tomkeejs  |
|           46 |     1695 | 2024-05-30 | B8                | W   | 0.747      | 0.435        | 0.170 (0.055)    | 0.912 (0.296)    | -         |    14.09 | beastik, majky, MoriiSko, oskar, SHOCK |
|           45 |     1723 | 2024-05-29 | brazylijski luz   | W   | 0.741      | -            | -                | -                | -         |     4.76 | beastik, majky, MoriiSko, oskar, SHOCK |
|           44 |     1781 | 2024-05-26 | Sampi             | W   | 0.721      | 0.435        | -                | 1.000 (0.313)    | -         |     6.43 | beastik, majky, MoriiSko, oskar, SHOCK |
|           43 |     1815 | 2024-05-24 | GUN5              | W   | 0.708      | 0.435        | 0.072 (0.022)    | 0.550 (0.169)    | -         |     7.10 | AJTT, beastik, majky, MoriiSko, oskar  |
|           42 |     1823 | 2024-05-24 | 9 Pandas          | L   | 0.706      | -            | -                | -                | -         |   -12.44 | AJTT, beastik, majky, oskar, SHOCK     |
|           41 |     1834 | 2024-05-23 | UNiTY             | W   | 0.701      | -            | -                | -                | -         |     7.79 | AJTT, beastik, majky, MoriiSko, oskar  |
|           40 |     1840 | 2024-05-23 | Passion UA        | L   | 0.699      | -            | -                | -                | -         |   -12.19 | AJTT, beastik, majky, MoriiSko, oskar  |
|           39 |     1958 | 2024-05-20 | VP.Prodigy        | W   | 0.680      | -            | -                | -                | -         |     5.39 | AJTT, beastik, majky, MoriiSko, oskar  |
|           38 |     2006 | 2024-05-18 | 1WIN              | L   | 0.667      | -            | -                | -                | -         |   -12.92 | AJTT, beastik, oskar, SHOCK, Tomkeejs  |
|           37 |     2092 | 2024-05-16 | ALTERNATE aTTaX   | W   | 0.652      | -            | -                | -                | -         |     7.03 | AJTT, beastik, majky, oskar, SHOCK     |
|           36 |     2184 | 2024-05-14 | Passion UA        | W   | 0.641      | 0.435        | 0.173 (0.048)    | 1.000 (0.279)    | -         |     8.98 | AJTT, beastik, majky, oskar, SHOCK     |
|           35 |     2354 | 2024-05-07 | Nemiga            | L   | 0.593      | -            | -                | -                | -         |    -6.60 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           34 |     2389 | 2024-05-05 | Endpoint          | W   | 0.580      | -            | -                | -                | -         |     5.82 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           33 |     2452 | 2024-05-02 | Gaimin Gladiators | L   | 0.560      | -            | -                | -                | -         |   -11.16 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           32 |     2479 | 2024-05-01 | B8                | L   | 0.552      | -            | -                | -                | -         |   -10.06 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           31 |     2511 | 2024-04-29 | 1WIN              | W   | 0.540      | 0.435        | -                | 0.718 (0.169)    | -         |     5.30 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           30 |     2520 | 2024-04-29 | Sangal            | L   | 0.539      | -            | -                | -                | -         |    -7.66 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           29 |     2532 | 2024-04-28 | Zero Tenacity     | L   | 0.534      | -            | -                | -                | -         |    -9.35 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           28 |     2565 | 2024-04-27 | Zero Tenacity     | L   | 0.526      | -            | -                | -                | -         |    -9.70 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           27 |     2581 | 2024-04-26 | PARIVISION        | L   | 0.521      | -            | -                | -                | -         |    -9.33 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           26 |     2631 | 2024-04-24 | Endpoint          | L   | 0.507      | -            | -                | -                | -         |   -12.69 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           25 |     2667 | 2024-04-22 | HAVU              | W   | 0.493      | -            | -                | -                | -         |     1.23 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           24 |     2716 | 2024-04-20 | ENCE Academy      | L   | 0.480      | -            | -                | -                | -         |   -13.84 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           23 |     2771 | 2024-04-19 | ECLOT             | L   | 0.472      | -            | -                | -                | -         |    -6.79 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           22 |     2861 | 2024-04-17 | Gaimin Gladiators | L   | 0.459      | -            | -                | -                | -         |   -10.34 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           21 |     2886 | 2024-04-16 | BLEED             | L   | 0.452      | -            | -                | -                | -         |   -10.59 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           20 |     2916 | 2024-04-14 | Passion UA        | W   | 0.440      | 0.371        | 0.173 (0.028)    | -                | -         |     4.76 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           19 |     3005 | 2024-04-10 | 3DMAX             | W   | 0.415      | 0.500        | 0.510 (0.106)    | 1.000 (0.207)    | -         |    12.30 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           18 |     3032 | 2024-04-10 | UNiTY             | W   | 0.412      | -            | -                | -                | -         |     3.25 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           17 |     3058 | 2024-04-09 | 9 Pandas          | W   | 0.408      | -            | -                | -                | -         |     3.72 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           16 |     3109 | 2024-04-08 | ALTERNATE aTTaX   | W   | 0.399      | -            | -                | -                | -         |     3.24 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           15 |     3160 | 2024-04-05 | Nexus             | W   | 0.381      | -            | -                | -                | -         |     1.92 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           14 |     3252 | 2024-04-03 | Rebels            | W   | 0.366      | -            | -                | -                | -         |     3.41 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           13 |     3295 | 2024-04-01 | Aurora            | W   | 0.355      | 0.500        | 0.420 (0.075)    | -                | -         |    10.64 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           12 |     3318 | 2024-03-29 | ex-Sprout         | W   | 0.335      | -            | -                | -                | -         |     0.17 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           11 |     3537 | 2024-03-17 | ECLOT             | L   | 0.255      | -            | -                | -                | -         |    -3.37 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           10 |     3543 | 2024-03-17 | UNiTY             | W   | 0.254      | -            | -                | -                | 1 (0.254) |     2.18 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            9 |     3558 | 2024-03-16 | Sampi             | W   | 0.247      | -            | -                | -                | 1 (0.247) |     1.66 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            8 |     3570 | 2024-03-15 | UNiTY             | L   | 0.242      | -            | -                | -                | -         |    -5.58 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            7 |     3640 | 2024-03-13 | ALTERNATE aTTaX   | W   | 0.228      | -            | -                | -                | -         |     2.06 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            6 |     3693 | 2024-03-11 | brazylijski luz   | L   | 0.215      | -            | -                | -                | -         |    -5.94 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            5 |     3905 | 2024-03-03 | Gaimin Gladiators | L   | 0.161      | -            | -                | -                | -         |    -3.74 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            4 |     4198 | 2024-02-18 | Monte             | L   | 0.068      | -            | -                | -                | -         |    -1.52 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            3 |     4245 | 2024-02-16 | 500               | W   | 0.055      | -            | -                | -                | -         |     0.13 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            2 |     4248 | 2024-02-16 | PERA              | W   | 0.055      | -            | -                | -                | -         |     0.39 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            1 |     4253 | 2024-02-16 | 500               | L   | 0.054      | -            | -                | -                | -         |    -1.57 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($11,899.16)
- Divide that value by the 5th highest value among all rosters ($320,411.81)
- The final value (0.04) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-13 |      0.842 | $545.00        | $458.76         |
| 2024-06-09 |      0.814 | $10,000.00     | $8,142.82       |
| 2024-06-02 |      0.768 | $1,306.00      | $1,002.54       |
| 2024-06-02 |      0.767 | $2,000.00      | $1,534.81       |
| 2024-03-17 |      0.255 | $2,984.00      | $760.23         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
