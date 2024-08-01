### Roster Details<br />
Team Name: Zero Tenacity<br />
Roster: aVN, brutmonster, Cjoffo, nEMANHA, simke<br />
Global Rank: [40](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [29]( ../standings_europe.md)<br />
<br />
Final Rank Value:  1122.8<br />
<br />
Final Rank Value (1122.8) = Starting Rank Value (1099.8) + Head To Head Adjustments (22.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.538[<sup>1</sup>](#table2)
- Bounty Collected: 0.479[<sup>2</sup>](#table1)
- Opponent Network: 0.344[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.340<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 1099.8
- 400 + ( ( 0.340 - 0.000 ) / ( 0.778 - 0.000 ) ) * 1600 = 1099.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                   |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|          111 |       44 | 2024-07-31 | KOI               | W   | 1.000      | -            | -                | -                | 0 (0.000) |     9.54 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|          110 |       96 | 2024-07-30 | Sashi             | W   | 1.000      | 0.500        | 0.187 (0.093)    | 0.970 (0.485)    | 0 (0.000) |    18.89 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|          109 |      283 | 2024-07-24 | Insilio           | W   | 1.000      | 0.500        | -                | 0.554 (0.277)    | 0 (0.000) |     9.84 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|          108 |      374 | 2024-07-21 | Passion UA        | L   | 1.000      | -            | -                | -                | -         |   -15.00 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|          107 |      402 | 2024-07-20 | B8                | W   | 1.000      | 0.500        | 0.168 (0.084)    | 0.878 (0.439)    | 0 (0.000) |    18.54 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|          106 |      504 | 2024-07-18 | fnatic            | W   | 1.000      | 0.500        | 0.292 (0.146)    | 0.529 (0.265)    | 0 (0.000) |    25.52 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|          105 |      620 | 2024-07-16 | Monte             | W   | 1.000      | 0.500        | -                | 0.614 (0.307)    | 0 (0.000) |    15.37 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|          104 |      644 | 2024-07-16 | EYEBALLERS        | W   | 1.000      | 0.500        | -                | 0.512 (0.256)    | 0 (0.000) |     8.48 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|          103 |      895 | 2024-06-16 | FAVBET            | W   | 0.893      | -            | -                | -                | 0 (0.000) |     7.26 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|          102 |      925 | 2024-06-15 | Nemiga            | L   | 0.887      | -            | -                | -                | -         |    -9.38 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|          101 |      959 | 2024-06-14 | RUBY              | W   | 0.880      | -            | -                | -                | 0 (0.000) |     9.33 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|          100 |      998 | 2024-06-13 | Monte             | L   | 0.873      | -            | -                | -                | -         |   -13.82 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           99 |     1023 | 2024-06-12 | 9INE              | W   | 0.867      | -            | -                | -                | 0 (0.000) |     1.62 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           98 |     1044 | 2024-06-11 | DMS               | W   | 0.860      | -            | -                | -                | -         |     9.93 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           97 |     1053 | 2024-06-11 | EYEBALLERS        | W   | 0.858      | -            | -                | -                | -         |     8.91 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           96 |     1131 | 2024-06-09 | HAVU              | W   | 0.845      | -            | -                | -                | -         |     4.40 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           95 |     1138 | 2024-06-09 | Endpoint          | L   | 0.845      | -            | -                | -                | -         |   -18.62 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           94 |     1147 | 2024-06-09 | Nemiga            | L   | 0.844      | -            | -                | -                | -         |   -10.25 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           93 |     1167 | 2024-06-08 | Insilio           | L   | 0.840      | -            | -                | -                | -         |   -16.60 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           92 |     1186 | 2024-06-08 | Passion UA        | W   | 0.839      | 0.500        | 0.173 (0.072)    | 1.000 (0.420)    | -         |    13.30 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           91 |     1199 | 2024-06-08 | 9INE              | L   | 0.839      | -            | -                | -                | -         |   -17.38 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           90 |     1224 | 2024-06-07 | Aurora Young Blud | L   | 0.835      | -            | -                | -                | -         |   -20.27 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           89 |     1232 | 2024-06-07 | DMS               | W   | 0.834      | -            | -                | -                | -         |     8.36 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           88 |     1249 | 2024-06-07 | EYEBALLERS        | L   | 0.833      | -            | -                | -                | -         |   -19.35 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           87 |     1269 | 2024-06-07 | 5W                | L   | 0.831      | -            | -                | -                | -         |   -18.40 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           86 |     1295 | 2024-06-06 | FAVBET            | W   | 0.827      | -            | -                | -                | -         |     4.22 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           85 |     1321 | 2024-06-06 | Permitta          | L   | 0.826      | -            | -                | -                | -         |   -19.62 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           84 |     1341 | 2024-06-06 | GhoulsW           | W   | 0.824      | -            | -                | -                | -         |     0.83 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           83 |     1379 | 2024-06-05 | Aurora Young Blud | W   | 0.819      | -            | -                | -                | -         |     4.66 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           82 |     1418 | 2024-06-04 | CYBERSHOKE        | W   | 0.813      | -            | -                | -                | -         |     5.02 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           81 |     1428 | 2024-06-04 | Grannys Knockers  | W   | 0.812      | -            | -                | -                | -         |     3.91 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           80 |     1458 | 2024-06-03 | Johnny Speeds     | L   | 0.805      | -            | -                | -                | -         |    -8.24 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           79 |     1465 | 2024-06-02 | DMS               | W   | 0.800      | -            | -                | -                | -         |     8.58 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           78 |     1471 | 2024-06-02 | SAW               | W   | 0.799      | -            | -                | -                | -         |    16.42 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           77 |     1492 | 2024-06-01 | RUBY              | L   | 0.794      | -            | -                | -                | -         |   -17.42 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           76 |     1508 | 2024-06-01 | DMS               | W   | 0.793      | -            | -                | -                | -         |     7.60 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           75 |     1510 | 2024-06-01 | KOI               | W   | 0.792      | -            | -                | -                | -         |     7.02 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           74 |     1517 | 2024-06-01 | FURIA             | L   | 0.791      | -            | -                | -                | -         |    -1.43 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           73 |     1546 | 2024-05-31 | Passion UA        | W   | 0.785      | 0.435        | 0.173 (0.059)    | 1.000 (0.341)    | -         |    11.22 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           72 |     1554 | 2024-05-30 | ThunderFlash      | W   | 0.780      | -            | -                | -                | -         |     0.51 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           71 |     1567 | 2024-05-30 | Passion UA        | L   | 0.779      | -            | -                | -                | -         |   -13.66 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           70 |     1583 | 2024-05-29 | JANO              | W   | 0.774      | -            | -                | -                | -         |     2.33 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           69 |     1641 | 2024-05-27 | ALTERNATE aTTaX   | W   | 0.758      | -            | -                | -                | -         |     5.42 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           68 |     1655 | 2024-05-26 | RUBY              | W   | 0.752      | -            | -                | -                | -         |     7.74 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           67 |     1668 | 2024-05-25 | ex-Guild Eagles   | W   | 0.747      | -            | -                | -                | -         |     5.57 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           66 |     1671 | 2024-05-25 | Serbia            | W   | 0.746      | -            | -                | -                | -         |     3.79 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           65 |     1681 | 2024-05-25 | Rhyno             | W   | 0.744      | -            | -                | -                | -         |     9.37 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           64 |     1686 | 2024-05-24 | ex-Guild Eagles   | L   | 0.740      | -            | -                | -                | -         |   -18.16 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           63 |     1689 | 2024-05-24 | The Suspect       | W   | 0.739      | -            | -                | -                | -         |     4.42 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           62 |     1705 | 2024-05-23 | 3DMAX             | L   | 0.733      | -            | -                | -                | -         |    -1.47 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           61 |     1712 | 2024-05-23 | brazylijski luz   | W   | 0.731      | -            | -                | -                | -         |     4.86 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           60 |     1745 | 2024-05-22 | Sangal            | L   | 0.726      | -            | -                | -                | -         |   -10.55 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           59 |     1765 | 2024-05-22 | Illuminar         | W   | 0.724      | -            | -                | -                | -         |     5.91 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           58 |     1804 | 2024-05-21 | BLEED             | W   | 0.719      | 0.500        | 0.128 (0.046)    | -                | -         |    19.31 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           57 |     1809 | 2024-05-21 | Verdant           | W   | 0.718      | -            | -                | -                | -         |     7.24 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           56 |     1812 | 2024-05-21 | GUN5              | L   | 0.718      | -            | -                | -                | -         |   -14.40 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           55 |     1834 | 2024-05-20 | Metizport         | W   | 0.714      | -            | -                | -                | -         |     8.74 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           54 |     1865 | 2024-05-19 | SINNERS           | L   | 0.707      | -            | -                | -                | -         |   -12.49 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           53 |     1877 | 2024-05-19 | B8                | W   | 0.705      | 0.500        | 0.168 (0.059)    | 0.878 (0.309)    | -         |    13.06 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           52 |     1932 | 2024-05-17 | PARIVISION        | L   | 0.694      | -            | -                | -                | -         |   -10.62 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           51 |     1940 | 2024-05-17 | Endpoint          | W   | 0.693      | -            | -                | -                | -         |     7.53 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           50 |     1982 | 2024-05-16 | 1WIN              | L   | 0.685      | -            | -                | -                | -         |   -13.96 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           49 |     1989 | 2024-05-16 | kONO              | W   | 0.684      | -            | -                | -                | -         |     5.60 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           48 |     2035 | 2024-05-15 | 3DMAX             | W   | 0.679      | 0.500        | 0.505 (0.171)    | 1.000 (0.339)    | -         |    20.37 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           47 |     2098 | 2024-05-14 | Preasy            | W   | 0.672      | -            | -                | -                | -         |     4.00 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           46 |     2118 | 2024-05-13 | EYEBALLERS        | W   | 0.666      | -            | -                | -                | -         |     6.63 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           45 |     2146 | 2024-05-12 | Verdant           | W   | 0.658      | -            | -                | -                | -         |     7.67 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           44 |     2216 | 2024-05-09 | 9 Pandas          | L   | 0.639      | -            | -                | -                | -         |   -11.17 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           43 |     2273 | 2024-05-06 | Insilio           | W   | 0.620      | -            | -                | -                | -         |     7.14 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           42 |     2319 | 2024-05-03 | EYEBALLERS        | L   | 0.600      | -            | -                | -                | -         |   -12.96 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           41 |     2332 | 2024-05-03 | Metizport         | L   | 0.598      | -            | -                | -                | -         |   -12.18 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           40 |     2361 | 2024-05-02 | HAVU              | W   | 0.591      | -            | -                | -                | -         |     2.37 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           39 |     2384 | 2024-05-01 | KOI               | W   | 0.585      | -            | -                | -                | -         |     6.51 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           38 |     2398 | 2024-04-30 | Sangal            | L   | 0.579      | -            | -                | -                | -         |    -7.52 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           37 |     2410 | 2024-04-30 | B8                | W   | 0.578      | 0.435        | 0.168 (0.042)    | -                | -         |     8.39 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           36 |     2425 | 2024-04-29 | PARIVISION        | L   | 0.572      | -            | -                | -                | -         |    -8.30 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           35 |     2442 | 2024-04-28 | SINNERS           | W   | 0.566      | -            | -                | -                | -         |     8.48 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           34 |     2455 | 2024-04-27 | 500               | W   | 0.560      | -            | -                | -                | -         |     2.82 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           33 |     2476 | 2024-04-27 | SINNERS           | W   | 0.558      | -            | -                | -                | -         |     8.87 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           32 |     2499 | 2024-04-26 | Illuminar         | W   | 0.551      | -            | -                | -                | -         |     1.10 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           31 |     2521 | 2024-04-25 | EYEBALLERS        | L   | 0.545      | -            | -                | -                | -         |   -12.42 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           30 |     2544 | 2024-04-24 | ex-Guild Eagles   | L   | 0.538      | -            | -                | -                | -         |   -12.78 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           29 |     2562 | 2024-04-23 | Nemiga            | L   | 0.532      | -            | -                | -                | -         |    -6.24 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           28 |     2573 | 2024-04-22 | Grannys Knockers  | W   | 0.527      | -            | -                | -                | -         |     2.50 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           27 |     2579 | 2024-04-22 | Nexus             | W   | 0.525      | -            | -                | -                | -         |     3.98 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           26 |     2626 | 2024-04-20 | RUBY              | W   | 0.512      | -            | -                | -                | -         |     5.75 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           25 |     2657 | 2024-04-19 | PARIVISION        | W   | 0.507      | -            | -                | -                | -         |     8.04 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           24 |     2681 | 2024-04-19 | ALTERNATE aTTaX   | W   | 0.505      | -            | -                | -                | -         |     5.87 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           23 |     2741 | 2024-04-18 | B8                | L   | 0.498      | -            | -                | -                | -         |    -8.15 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           22 |     2764 | 2024-04-17 | B8                | W   | 0.492      | 0.500        | 0.168 (0.041)    | -                | -         |     7.60 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           21 |     2793 | 2024-04-16 | Sangal            | L   | 0.487      | -            | -                | -                | -         |    -6.20 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           20 |     2816 | 2024-04-15 | ALTERNATE aTTaX   | W   | 0.480      | -            | -                | -                | -         |     5.98 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           19 |     2867 | 2024-04-12 | JANO              | L   | 0.458      | -            | -                | -                | -         |   -12.85 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           18 |     2894 | 2024-04-11 | Alliance          | L   | 0.452      | -            | -                | -                | -         |   -10.93 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           17 |     2992 | 2024-04-09 | MOUZ NXT          | L   | 0.439      | -            | -                | -                | -         |    -7.13 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           16 |     3055 | 2024-04-07 | ex-Preasy         | L   | 0.425      | -            | -                | -                | -         |   -10.89 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           15 |     3232 | 2024-04-01 | Nemiga            | L   | 0.385      | -            | -                | -                | -         |    -5.00 | aVN, brutmonster, Cjoffo, kdaN, simke    |
|           14 |     3650 | 2024-03-10 | CYBERSHOKE        | L   | 0.240      | -            | -                | -                | -         |    -6.96 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           13 |     3662 | 2024-03-10 | ECLOT             | W   | 0.239      | -            | -                | -                | -         |     3.91 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           12 |     3682 | 2024-03-09 | Sangal            | W   | 0.233      | -            | -                | -                | -         |     4.08 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           11 |     3728 | 2024-03-07 | Nemiga            | L   | 0.220      | -            | -                | -                | -         |    -2.85 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|           10 |     3762 | 2024-03-06 | AURA              | W   | 0.212      | -            | -                | -                | -         |     0.23 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            9 |     3799 | 2024-03-05 | AMKAL             | L   | 0.207      | -            | -                | -                | -         |    -2.82 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            8 |     3858 | 2024-03-03 | Secret            | W   | 0.191      | -            | -                | -                | -         |     0.26 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            7 |     3878 | 2024-03-02 | Secret            | W   | 0.185      | -            | -                | -                | -         |     0.25 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            6 |     3905 | 2024-02-29 | Young Ninjas      | W   | 0.172      | -            | -                | -                | -         |     0.72 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            5 |     4031 | 2024-02-23 | ex-Anonymo        | W   | 0.133      | -            | -                | -                | -         |     0.15 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            4 |     4178 | 2024-02-17 | Sashi             | L   | 0.093      | -            | -                | -                | -         |    -1.18 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            3 |     4341 | 2024-02-10 | Sampi             | L   | 0.047      | -            | -                | -                | -         |    -1.12 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            2 |     4423 | 2024-02-04 | 500               | L   | 0.006      | -            | -                | -                | -         |    -0.16 | aVN, brutmonster, Cjoffo, nEMANHA, simke |
|            1 |     4436 | 2024-02-03 | The Chosen Few    | W   | 0.001      | -            | -                | -                | -         |     0.00 | aVN, brutmonster, Cjoffo, nEMANHA, simke |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($45,335.83)
- Divide that value by the 5th highest value among all rosters ($327,030.46)
- The final value (0.14) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-07-22 |      1.000 | $12,500.00     | $12,500.00      |
| 2024-06-10 |      0.854 | $2,000.00      | $1,707.50       |
| 2024-06-02 |      0.799 | $2,000.00      | $1,598.89       |
| 2024-05-22 |      0.726 | $25,000.00     | $18,152.78      |
| 2024-05-16 |      0.684 | $5,000.00      | $3,420.83       |
| 2024-05-04 |      0.606 | $2,000.00      | $1,212.78       |
| 2024-04-24 |      0.539 | $12,500.00     | $6,743.06       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
