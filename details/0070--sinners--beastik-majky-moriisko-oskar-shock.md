### Roster Details<br />
Team Name: SINNERS<br />
Roster: beastik, majky, MoriiSko, oskar, SHOCK<br />
Global Rank: [70](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [50]( ../standings_europe.md)<br />
<br />
Final Rank Value:  950.6<br />
<br />
Final Rank Value (950.6) = Starting Rank Value (1043.0) + Head To Head Adjustments (-92.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.413[<sup>1</sup>](#table2)
- Bounty Collected: 0.439[<sup>2</sup>](#table1)
- Opponent Network: 0.238[<sup>2</sup>](#table1)
- LAN Wins: 0.158[<sup>2</sup>](#table1)

The average of these factors is 0.312<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1043.0
- 400 + ( ( 0.312 - 0.000 ) / ( 0.776 - 0.000 ) ) * 1600 = 1043.0


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
|           78 |       67 | 2024-07-30 | Sangal            | L   | 1.000      | -            | -                | -                | -         |    -4.69 | beastik, majky, MoriiSko, oskar, SHOCK |
|           77 |      102 | 2024-07-29 | Alliance          | W   | 1.000      | -            | -                | -                | 0 (0.000) |    11.64 | beastik, majky, MoriiSko, oskar, SHOCK |
|           76 |      207 | 2024-07-25 | B8                | L   | 1.000      | -            | -                | -                | -         |    -7.21 | beastik, majky, MoriiSko, oskar, SHOCK |
|           75 |      282 | 2024-07-23 | RUSH B            | L   | 1.000      | -            | -                | -                | -         |   -18.04 | beastik, majky, MoriiSko, oskar, SHOCK |
|           74 |      316 | 2024-07-22 | CPH Wolves        | W   | 1.000      | -            | -                | -                | 0 (0.000) |    10.74 | beastik, majky, MoriiSko, oskar, SHOCK |
|           73 |      399 | 2024-07-19 | DMS               | W   | 1.000      | 0.435        | -                | 0.447 (0.194)    | 0 (0.000) |    13.93 | beastik, majky, MoriiSko, oskar, SHOCK |
|           72 |      529 | 2024-07-17 | Endpoint          | W   | 1.000      | 0.435        | -                | 0.523 (0.227)    | 0 (0.000) |    12.00 | beastik, majky, MoriiSko, oskar, SHOCK |
|           71 |      598 | 2024-07-16 | BC.Game           | L   | 1.000      | -            | -                | -                | -         |   -26.59 | beastik, majky, MoriiSko, oskar, SHOCK |
|           70 |      627 | 2024-07-15 | SAW               | L   | 1.000      | -            | -                | -                | -         |    -7.14 | beastik, majky, MoriiSko, oskar, SHOCK |
|           69 |      640 | 2024-07-15 | Nexus             | L   | 1.000      | -            | -                | -                | -         |   -24.75 | beastik, majky, MoriiSko, oskar, SHOCK |
|           68 |     1000 | 2024-06-11 | 3DMAX             | L   | 0.866      | -            | -                | -                | -         |    -2.24 | beastik, majky, MoriiSko, oskar, SHOCK |
|           67 |     1014 | 2024-06-11 | ex-Guild Eagles   | W   | 0.864      | -            | -                | -                | 0 (0.000) |     9.37 | beastik, majky, MoriiSko, oskar, SHOCK |
|           66 |     1028 | 2024-06-10 | Enterprise        | L   | 0.859      | -            | -                | -                | -         |   -16.06 | beastik, majky, MoriiSko, oskar, SHOCK |
|           65 |     1036 | 2024-06-10 | Monte             | L   | 0.858      | -            | -                | -                | -         |   -12.84 | beastik, majky, MoriiSko, oskar, SHOCK |
|           64 |     1040 | 2024-06-10 | 9 Pandas          | L   | 0.858      | -            | -                | -                | -         |   -11.90 | beastik, majky, MoriiSko, oskar, SHOCK |
|           63 |     1047 | 2024-06-10 | PARIVISION        | W   | 0.857      | -            | -                | -                | 0 (0.000) |    16.05 | beastik, majky, MoriiSko, oskar, SHOCK |
|           62 |     1049 | 2024-06-10 | Rare Atom         | L   | 0.857      | -            | -                | -                | -         |   -23.72 | beastik, majky, MoriiSko, oskar, SHOCK |
|           61 |     1079 | 2024-06-09 | SAW               | W   | 0.852      | -            | -                | -                | 0 (0.000) |    18.70 | beastik, majky, MoriiSko, oskar, SHOCK |
|           60 |     1087 | 2024-06-09 | 3DMAX             | W   | 0.851      | 0.143        | 0.499 (0.061)    | -                | -         |    25.06 | beastik, majky, MoriiSko, oskar, SHOCK |
|           59 |     1093 | 2024-06-09 | RUSH B            | L   | 0.851      | -            | -                | -                | -         |   -18.07 | beastik, majky, MoriiSko, oskar, SHOCK |
|           58 |     1102 | 2024-06-09 | Aurora            | W   | 0.850      | 0.143        | 0.429 (0.052)    | -                | -         |    25.26 | beastik, majky, MoriiSko, oskar, SHOCK |
|           57 |     1136 | 2024-06-08 | Sangal            | L   | 0.846      | -            | -                | -                | -         |    -6.43 | beastik, majky, MoriiSko, oskar, SHOCK |
|           56 |     1215 | 2024-06-07 | RUBY              | W   | 0.837      | 0.435        | 0.096 (0.035)    | 0.506 (0.184)    | -         |    10.97 | beastik, majky, MoriiSko, oskar, SHOCK |
|           55 |     1258 | 2024-06-06 | KOI               | L   | 0.832      | -            | -                | -                | -         |    -9.48 | beastik, majky, MoriiSko, oskar, SHOCK |
|           54 |     1318 | 2024-06-05 | RUSH B            | W   | 0.826      | -            | -                | -                | -         |     9.03 | beastik, majky, MoriiSko, oskar, SHOCK |
|           53 |     1327 | 2024-06-05 | EYEBALLERS        | L   | 0.825      | -            | -                | -                | -         |   -16.54 | beastik, majky, MoriiSko, oskar, SHOCK |
|           52 |     1381 | 2024-06-04 | VP.Prodigy        | L   | 0.817      | -            | -                | -                | -         |   -15.30 | beastik, majky, MoriiSko, oskar, SHOCK |
|           51 |     1420 | 2024-06-02 | UNiTY             | L   | 0.805      | -            | -                | -                | -         |   -14.58 | AJTT, beastik, oskar, SHOCK, Tomkeejs  |
|           50 |     1437 | 2024-06-01 | GUN5              | L   | 0.800      | -            | -                | -                | -         |   -15.52 | AJTT, beastik, MoriiSko, oskar, SHOCK  |
|           49 |     1457 | 2024-06-01 | Sampi             | W   | 0.798      | 0.346        | -                | 1.000 (0.276)    | 1 (0.798) |     7.95 | AJTT, beastik, oskar, SHOCK, Tomkeejs  |
|           48 |     1489 | 2024-05-31 | UNiTY             | L   | 0.791      | -            | -                | -                | -         |   -14.98 | AJTT, beastik, oskar, SHOCK, Tomkeejs  |
|           47 |     1507 | 2024-05-30 | B8                | W   | 0.785      | 0.435        | 0.167 (0.057)    | 0.879 (0.300)    | -         |    16.71 | beastik, majky, MoriiSko, oskar, SHOCK |
|           46 |     1535 | 2024-05-29 | brazylijski luz   | W   | 0.779      | -            | -                | -                | -         |     6.51 | beastik, majky, MoriiSko, oskar, SHOCK |
|           45 |     1593 | 2024-05-26 | Sampi             | W   | 0.759      | 0.435        | -                | 1.000 (0.330)    | -         |     8.46 | beastik, majky, MoriiSko, oskar, SHOCK |
|           44 |     1627 | 2024-05-24 | GUN5              | W   | 0.746      | 0.435        | 0.073 (0.024)    | -                | -         |     9.18 | AJTT, beastik, majky, MoriiSko, oskar  |
|           43 |     1635 | 2024-05-24 | 9 Pandas          | L   | 0.744      | -            | -                | -                | -         |   -10.82 | AJTT, beastik, majky, oskar, SHOCK     |
|           42 |     1646 | 2024-05-23 | UNiTY             | W   | 0.739      | -            | -                | -                | -         |    10.24 | AJTT, beastik, majky, MoriiSko, oskar  |
|           41 |     1652 | 2024-05-23 | Passion UA        | L   | 0.737      | -            | -                | -                | -         |   -11.05 | AJTT, beastik, majky, MoriiSko, oskar  |
|           40 |     1770 | 2024-05-20 | VP.Prodigy        | W   | 0.718      | -            | -                | -                | -         |     7.51 | AJTT, beastik, majky, MoriiSko, oskar  |
|           39 |     1818 | 2024-05-18 | 1WIN              | L   | 0.705      | -            | -                | -                | -         |   -12.30 | AJTT, beastik, oskar, SHOCK, Tomkeejs  |
|           38 |     1904 | 2024-05-16 | ALTERNATE aTTaX   | W   | 0.690      | 0.435        | -                | 0.564 (0.169)    | -         |     9.46 | AJTT, beastik, majky, oskar, SHOCK     |
|           37 |     1996 | 2024-05-14 | Passion UA        | W   | 0.679      | 0.435        | 0.171 (0.050)    | 1.000 (0.295)    | -         |    11.33 | AJTT, beastik, majky, oskar, SHOCK     |
|           36 |     2166 | 2024-05-07 | Nemiga            | L   | 0.631      | -            | -                | -                | -         |    -5.29 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           35 |     2201 | 2024-05-05 | Endpoint          | W   | 0.618      | -            | -                | -                | -         |     8.26 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           34 |     2264 | 2024-05-02 | Gaimin Gladiators | L   | 0.597      | -            | -                | -                | -         |    -9.34 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           33 |     2291 | 2024-05-01 | B8                | L   | 0.590      | -            | -                | -                | -         |    -8.61 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           32 |     2323 | 2024-04-29 | 1WIN              | W   | 0.578      | -            | -                | -                | -         |     6.85 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           31 |     2332 | 2024-04-29 | Sangal            | L   | 0.577      | -            | -                | -                | -         |    -6.49 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           30 |     2344 | 2024-04-28 | Zero Tenacity     | L   | 0.571      | -            | -                | -                | -         |    -8.03 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           29 |     2377 | 2024-04-27 | Zero Tenacity     | L   | 0.564      | -            | -                | -                | -         |    -8.39 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           28 |     2393 | 2024-04-26 | PARIVISION        | L   | 0.558      | -            | -                | -                | -         |    -8.26 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           27 |     2443 | 2024-04-24 | Endpoint          | L   | 0.545      | -            | -                | -                | -         |   -11.99 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           26 |     2479 | 2024-04-22 | HAVU              | W   | 0.531      | -            | -                | -                | -         |     2.13 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           25 |     2528 | 2024-04-20 | ENCE Academy      | L   | 0.518      | -            | -                | -                | -         |   -13.96 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           24 |     2583 | 2024-04-19 | ECLOT             | L   | 0.510      | -            | -                | -                | -         |    -7.53 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           23 |     2673 | 2024-04-17 | Gaimin Gladiators | L   | 0.497      | -            | -                | -                | -         |    -8.85 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           22 |     2698 | 2024-04-16 | BLEED             | L   | 0.490      | -            | -                | -                | -         |    -9.51 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           21 |     2728 | 2024-04-14 | Passion UA        | W   | 0.477      | 0.371        | 0.171 (0.030)    | 1.000 (0.177)    | -         |     6.78 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           20 |     2817 | 2024-04-10 | 3DMAX             | W   | 0.453      | 0.500        | 0.499 (0.113)    | 1.000 (0.226)    | -         |    13.75 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           19 |     2844 | 2024-04-10 | UNiTY             | W   | 0.450      | -            | -                | -                | -         |     5.20 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           18 |     2870 | 2024-04-09 | 9 Pandas          | W   | 0.446      | 0.500        | 0.082 (0.018)    | -                | -         |     6.03 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           17 |     2921 | 2024-04-08 | ALTERNATE aTTaX   | W   | 0.437      | -            | -                | -                | -         |     5.28 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           16 |     2972 | 2024-04-05 | Nexus             | W   | 0.419      | -            | -                | -                | -         |     3.36 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           15 |     3064 | 2024-04-03 | Rebels            | W   | 0.404      | -            | -                | -                | -         |     5.58 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           14 |     3107 | 2024-04-01 | Aurora            | W   | 0.393      | 0.500        | 0.429 (0.084)    | -                | -         |    12.04 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           13 |     3130 | 2024-03-29 | ex-Sprout         | W   | 0.372      | -            | -                | -                | -         |     0.33 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           12 |     3349 | 2024-03-17 | ECLOT             | L   | 0.293      | -            | -                | -                | -         |    -3.84 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           11 |     3355 | 2024-03-17 | UNiTY             | W   | 0.292      | -            | -                | -                | 1 (0.292) |     3.80 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|           10 |     3370 | 2024-03-16 | Sampi             | W   | 0.285      | -            | -                | -                | 1 (0.285) |     3.05 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            9 |     3382 | 2024-03-15 | UNiTY             | L   | 0.279      | -            | -                | -                | -         |    -5.18 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            8 |     3452 | 2024-03-13 | ALTERNATE aTTaX   | W   | 0.266      | -            | -                | -                | -         |     3.66 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            7 |     3505 | 2024-03-11 | brazylijski luz   | L   | 0.252      | -            | -                | -                | -         |    -6.31 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            6 |     3717 | 2024-03-03 | Gaimin Gladiators | L   | 0.199      | -            | -                | -                | -         |    -3.54 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            5 |     4010 | 2024-02-18 | Monte             | L   | 0.105      | -            | -                | -                | -         |    -1.79 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            4 |     4057 | 2024-02-16 | 500               | W   | 0.093      | -            | -                | -                | -         |     0.39 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            3 |     4060 | 2024-02-16 | PERA              | W   | 0.092      | -            | -                | -                | -         |     1.05 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            2 |     4065 | 2024-02-16 | 500               | L   | 0.092      | -            | -                | -                | -         |    -2.51 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |
|            1 |     4274 | 2024-02-04 | Into the Breach   | L   | 0.011      | -            | -                | -                | -         |    -0.32 | AJTT, beastik, NEOFRAG, oskar, SHOCK   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($12,534.92)
- Divide that value by the 5th highest value among all rosters ($331,608.80)
- The final value (0.04) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-06-13 |      0.880 | $545.00        | $479.34         |
| 2024-06-09 |      0.852 | $10,000.00     | $8,520.46       |
| 2024-06-02 |      0.805 | $1,306.00      | $1,051.86       |
| 2024-06-02 |      0.805 | $2,000.00      | $1,610.34       |
| 2024-03-17 |      0.293 | $2,984.00      | $872.92         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
