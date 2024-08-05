### Roster Details<br />
Team Name: SINNERS<br />
Roster: beastik, majky, MoriiSko, oskar, SHOCK<br />
Global Rank: [64](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [47]( ../standings_europe.md)<br />
<br />
Final Rank Value:  992.1<br />
<br />
Final Rank Value (992.1) = Starting Rank Value (1151.5) + Head To Head Adjustments (-159.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.412[<sup>1</sup>](#table2)
- Bounty Collected: 0.434[<sup>2</sup>](#table1)
- Opponent Network: 0.243[<sup>2</sup>](#table1)
- LAN Wins: 0.377[<sup>2</sup>](#table1)

The average of these factors is 0.367<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1151.5
- 400 + ( ( 0.367 - 0.000 ) / ( 0.780 - 0.000 ) ) * 1600 = 1151.5


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
|           81 |        1 | 2024-08-05 | Rebels            | W   | 1.000      | 0.500        | 0.038 (0.019)    | 0.591 (0.296)    | 0 (0.000) |    16.67 | beastik, majky, MoriiSko, oskar, SHOCK |
|           80 |       35 | 2024-08-04 | AVEZ              | W   | 1.000      | -            | -                | -                | 1 (1.000) |     5.92 | beastik, majky, MoriiSko, oskar, SHOCK |
|           79 |       71 | 2024-08-03 | SINNERS Academy   | W   | 1.000      | -            | -                | -                | 1 (1.000) |     2.48 | beastik, majky, MoriiSko, oskar, SHOCK |
|           78 |       93 | 2024-08-02 | ECLOT             | L   | 1.000      | -            | -                | -                | -         |   -11.17 | beastik, majky, MoriiSko, oskar, SHOCK |
|           77 |      241 | 2024-07-30 | Sangal            | L   | 1.000      | -            | -                | -                | -         |    -5.31 | beastik, majky, MoriiSko, oskar, SHOCK |
|           76 |      277 | 2024-07-29 | Alliance          | W   | 1.000      | -            | -                | -                | 0 (0.000) |    10.39 | beastik, majky, MoriiSko, oskar, SHOCK |
|           75 |      381 | 2024-07-25 | B8                | L   | 1.000      | -            | -                | -                | -         |    -8.37 | beastik, majky, MoriiSko, oskar, SHOCK |
|           74 |      456 | 2024-07-23 | RUSH B            | L   | 1.000      | -            | -                | -                | -         |   -19.04 | beastik, majky, MoriiSko, oskar, SHOCK |
|           73 |      490 | 2024-07-22 | CPH Wolves        | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.45 | beastik, majky, MoriiSko, oskar, SHOCK |
|           72 |      573 | 2024-07-19 | DMS               | W   | 1.000      | 0.435        | -                | 0.438 (0.191)    | 0 (0.000) |    12.47 | beastik, majky, MoriiSko, oskar, SHOCK |
|           71 |      703 | 2024-07-17 | Endpoint          | W   | 1.000      | 0.435        | -                | 0.514 (0.223)    | 0 (0.000) |    10.31 | beastik, majky, MoriiSko, oskar, SHOCK |
|           70 |      772 | 2024-07-16 | BC.Game           | L   | 1.000      | -            | -                | -                | -         |   -19.96 | beastik, majky, MoriiSko, oskar, SHOCK |
|           69 |      801 | 2024-07-15 | SAW               | L   | 1.000      | -            | -                | -                | -         |    -8.49 | beastik, majky, MoriiSko, oskar, SHOCK |
|           68 |      814 | 2024-07-15 | Nexus             | L   | 1.000      | -            | -                | -                | -         |   -25.65 | beastik, majky, MoriiSko, oskar, SHOCK |
|           67 |     1174 | 2024-06-11 | 3DMAX             | L   | 0.834      | -            | -                | -                | -         |    -2.47 | beastik, majky, MoriiSko, oskar, SHOCK |
|           66 |     1188 | 2024-06-11 | ex-Guild Eagles   | W   | 0.832      | -            | -                | -                | -         |     7.58 | beastik, majky, MoriiSko, oskar, SHOCK |
|           65 |     1202 | 2024-06-10 | Enterprise        | L   | 0.826      | -            | -                | -                | -         |   -16.62 | beastik, majky, MoriiSko, oskar, SHOCK |
|           64 |     1210 | 2024-06-10 | Monte             | L   | 0.826      | -            | -                | -                | -         |   -13.81 | beastik, majky, MoriiSko, oskar, SHOCK |
|           63 |     1214 | 2024-06-10 | 9 Pandas          | L   | 0.825      | -            | -                | -                | -         |   -12.92 | beastik, majky, MoriiSko, oskar, SHOCK |
|           62 |     1221 | 2024-06-10 | PARIVISION        | W   | 0.825      | -            | -                | -                | -         |    14.40 | beastik, majky, MoriiSko, oskar, SHOCK |
|           61 |     1223 | 2024-06-10 | Rare Atom         | L   | 0.824      | -            | -                | -                | -         |   -20.04 | beastik, majky, MoriiSko, oskar, SHOCK |
|           60 |     1253 | 2024-06-09 | SAW               | W   | 0.819      | -            | -                | -                | -         |    16.43 | beastik, majky, MoriiSko, oskar, SHOCK |
|           59 |     1261 | 2024-06-09 | 3DMAX             | W   | 0.819      | 0.143        | 0.508 (0.059)    | -                | -         |    23.79 | beastik, majky, MoriiSko, oskar, SHOCK |
|           58 |     1267 | 2024-06-09 | RUSH B            | L   | 0.818      | -            | -                | -                | -         |   -18.21 | beastik, majky, MoriiSko, oskar, SHOCK |
|           57 |     1276 | 2024-06-09 | Aurora            | W   | 0.818      | 0.143        | 0.422 (0.049)    | -                | -         |    23.97 | beastik, majky, MoriiSko, oskar, SHOCK |
|           56 |     1310 | 2024-06-08 | Sangal            | L   | 0.813      | -            | -                | -                | -         |    -7.15 | beastik, majky, MoriiSko, oskar, SHOCK |
|           55 |     1389 | 2024-06-07 | RUBY              | W   | 0.805      | 0.435        | 0.095 (0.033)    | 0.492 (0.172)    | -         |     9.13 | beastik, majky, MoriiSko, oskar, SHOCK |
|           54 |     1432 | 2024-06-06 | KOI               | L   | 0.800      | -            | -                | -                | -         |   -11.06 | beastik, majky, MoriiSko, oskar, SHOCK |
|           53 |     1492 | 2024-06-05 | RUSH B            | W   | 0.793      | -            | -                | -                | -         |     7.66 | beastik, majky, MoriiSko, oskar, SHOCK |
|           52 |     1501 | 2024-06-05 | EYEBALLERS        | L   | 0.792      | -            | -                | -                | -         |   -17.53 | beastik, majky, MoriiSko, oskar, SHOCK |
|           51 |     1555 | 2024-06-04 | VP.Prodigy        | L   | 0.785      | -            | -                | -                | -         |   -16.32 | beastik, majky, MoriiSko, oskar, SHOCK |
|           50 |     1594 | 2024-06-02 | UNiTY             | L   | 0.772      | -            | -                | -                | -         |   -15.43 | AJTT, beastik, oskar, SHOCK, Tomkeejs  |
|           49 |     1611 | 2024-06-01 | GUN5              | L   | 0.767      | -            | -                | -                | -         |   -16.30 | AJTT, beastik, MoriiSko, oskar, SHOCK  |
|           48 |     1631 | 2024-06-01 | Sampi             | W   | 0.765      | 0.346        | -                | 1.000 (0.265)    | 1 (0.765) |     6.31 | AJTT, beastik, oskar, SHOCK, Tomkeejs  |
|           47 |     1663 | 2024-05-31 | UNiTY             | L   | 0.759      | -            | -                | -                | -         |   -15.96 | AJTT, beastik, oskar, SHOCK, Tomkeejs  |
|           46 |     1681 | 2024-05-30 | B8                | W   | 0.753      | 0.435        | 0.165 (0.054)    | 0.935 (0.306)    | -         |    14.18 | beastik, majky, MoriiSko, oskar, SHOCK |
|           45 |     1709 | 2024-05-29 | brazylijski luz   | W   | 0.746      | -            | -                | -                | -         |     4.82 | beastik, majky, MoriiSko, oskar, SHOCK |
|           44 |     1767 | 2024-05-26 | Sampi             | W   | 0.726      | 0.435        | -                | 1.000 (0.316)    | -         |     6.47 | beastik, majky, MoriiSko, oskar, SHOCK |
|           43 |     1801 | 2024-05-24 | GUN5              | W   | 0.714      | 0.435        | 0.073 (0.022)    | 0.562 (0.174)    | -         |     7.18 | AJTT, beastik, majky, MoriiSko, oskar  |
|           42 |     1809 | 2024-05-24 | 9 Pandas          | L   | 0.712      | -            | -                | -                | -         |   -12.48 | AJTT, beastik, majky, oskar, SHOCK     |
|           41 |     1820 | 2024-05-23 | UNiTY             | W   | 0.706      | -            | -                | -                | -         |     7.90 | AJTT, beastik, majky, MoriiSko, oskar  |
|           40 |     1826 | 2024-05-23 | Passion UA        | L   | 0.704      | -            | -                | -                | -         |   -12.34 | AJTT, beastik, majky, MoriiSko, oskar  |
|           39 |     1944 | 2024-05-20 | VP.Prodigy        | W   | 0.685      | -            | -                | -                | -         |     5.44 | AJTT, beastik, majky, MoriiSko, oskar  |
|           38 |     1992 | 2024-05-18 | 1WIN              | L   | 0.673      | -            | -                | -                | -         |   -13.02 | AJTT, beastik, oskar, SHOCK, Tomkeejs  |
|           37 |     2078 | 2024-05-16 | ALTERNATE aTTaX   | W   | 0.657      | -            | -                | -                | -         |     7.06 | AJTT, beastik, majky, oskar, SHOCK     |
|           36 |     2170 | 2024-05-14 | Passion UA        | W   | 0.647      | 0.435        | 0.173 (0.049)    | 1.000 (0.281)    | -         |     8.99 | AJTT, beastik, majky, oskar, SHOCK     |
|           35 |     2340 | 2024-05-07 | Nemiga            | L   | 0.598      | -            | -                | -                | -         |    -6.61 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           34 |     2375 | 2024-05-05 | Endpoint          | W   | 0.586      | -            | -                | -                | -         |     5.88 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           33 |     2438 | 2024-05-02 | Gaimin Gladiators | L   | 0.565      | -            | -                | -                | -         |   -11.20 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           32 |     2465 | 2024-05-01 | B8                | L   | 0.558      | -            | -                | -                | -         |   -10.20 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           31 |     2497 | 2024-04-29 | 1WIN              | W   | 0.546      | -            | -                | -                | -         |     5.35 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           30 |     2506 | 2024-04-29 | Sangal            | L   | 0.544      | -            | -                | -                | -         |    -7.77 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           29 |     2518 | 2024-04-28 | Zero Tenacity     | L   | 0.539      | -            | -                | -                | -         |    -9.44 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           28 |     2551 | 2024-04-27 | Zero Tenacity     | L   | 0.531      | -            | -                | -                | -         |    -9.80 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           27 |     2567 | 2024-04-26 | PARIVISION        | L   | 0.526      | -            | -                | -                | -         |    -9.49 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           26 |     2617 | 2024-04-24 | Endpoint          | L   | 0.512      | -            | -                | -                | -         |   -12.83 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           25 |     2653 | 2024-04-22 | HAVU              | W   | 0.498      | -            | -                | -                | -         |     1.24 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           24 |     2702 | 2024-04-20 | ENCE Academy      | L   | 0.485      | -            | -                | -                | -         |   -13.99 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           23 |     2757 | 2024-04-19 | ECLOT             | L   | 0.477      | -            | -                | -                | -         |    -6.90 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           22 |     2847 | 2024-04-17 | Gaimin Gladiators | L   | 0.465      | -            | -                | -                | -         |   -10.41 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           21 |     2872 | 2024-04-16 | BLEED             | L   | 0.458      | -            | -                | -                | -         |   -10.71 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           20 |     2902 | 2024-04-14 | Passion UA        | W   | 0.445      | 0.371        | 0.173 (0.028)    | -                | -         |     4.76 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           19 |     2991 | 2024-04-10 | 3DMAX             | W   | 0.420      | 0.500        | 0.508 (0.107)    | 1.000 (0.210)    | -         |    12.45 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           18 |     3018 | 2024-04-10 | UNiTY             | W   | 0.417      | -            | -                | -                | -         |     3.30 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           17 |     3044 | 2024-04-09 | 9 Pandas          | W   | 0.414      | -            | -                | -                | -         |     3.78 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           16 |     3095 | 2024-04-08 | ALTERNATE aTTaX   | W   | 0.404      | -            | -                | -                | -         |     3.26 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           15 |     3146 | 2024-04-05 | Nexus             | W   | 0.386      | -            | -                | -                | -         |     1.93 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           14 |     3238 | 2024-04-03 | Rebels            | W   | 0.371      | -            | -                | -                | -         |     3.44 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           13 |     3281 | 2024-04-01 | Aurora            | W   | 0.360      | 0.500        | 0.422 (0.076)    | -                | -         |    10.79 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           12 |     3304 | 2024-03-29 | ex-Sprout         | W   | 0.340      | -            | -                | -                | -         |     0.17 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           11 |     3523 | 2024-03-17 | ECLOT             | L   | 0.260      | -            | -                | -                | -         |    -3.45 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           10 |     3529 | 2024-03-17 | UNiTY             | W   | 0.259      | -            | -                | -                | 1 (0.259) |     2.24 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            9 |     3544 | 2024-03-16 | Sampi             | W   | 0.253      | -            | -                | -                | 1 (0.253) |     1.70 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            8 |     3556 | 2024-03-15 | UNiTY             | L   | 0.247      | -            | -                | -                | -         |    -5.70 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            7 |     3626 | 2024-03-13 | ALTERNATE aTTaX   | W   | 0.234      | -            | -                | -                | -         |     2.10 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            6 |     3679 | 2024-03-11 | brazylijski luz   | L   | 0.220      | -            | -                | -                | -         |    -6.08 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            5 |     3891 | 2024-03-03 | Gaimin Gladiators | L   | 0.167      | -            | -                | -                | -         |    -3.85 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            4 |     4184 | 2024-02-18 | Monte             | L   | 0.073      | -            | -                | -                | -         |    -1.64 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            3 |     4231 | 2024-02-16 | 500               | W   | 0.060      | -            | -                | -                | -         |     0.14 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            2 |     4234 | 2024-02-16 | PERA              | W   | 0.060      | -            | -                | -                | -         |     0.43 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            1 |     4239 | 2024-02-16 | 500               | L   | 0.059      | -            | -                | -                | -         |    -1.73 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($11,989.57)
- Divide that value by the 5th highest value among all rosters ($322,004.12)
- The final value (0.04) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-13 |      0.847 | $545.00        | $461.69         |
| 2024-06-09 |      0.820 | $10,000.00     | $8,196.53       |
| 2024-06-02 |      0.773 | $1,306.00      | $1,009.55       |
| 2024-06-02 |      0.773 | $2,000.00      | $1,545.56       |
| 2024-03-17 |      0.260 | $2,984.00      | $776.25         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
